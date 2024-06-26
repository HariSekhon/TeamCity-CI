# TeamCity CI Config

[![GitHub stars](https://img.shields.io/github/stars/HariSekhon/TeamCity-CI?logo=github)](https://github.com/HariSekhon/TeamCity-CI/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/HariSekhon/TeamCity-CI?logo=github)](https://github.com/HariSekhon/TeamCity-CI/network)
[![License](https://img.shields.io/github/license/HariSekhon/TeamCity-CI)](https://github.com/HariSekhon/TeamCity-CI/blob/master/LICENSE)
[![GitHub Last Commit](https://img.shields.io/github/last-commit/HariSekhon/TeamCity-CI?logo=github)](https://github.com/HariSekhon/TeamCity-CI/commits/master)

[![TeamCity](https://img.shields.io/badge/TeamCity-Configs-blue?logo=teamcity)](https://github.com/HariSekhon/TeamCity-CI)
[![Linux](https://img.shields.io/badge/OS-Linux-blue?logo=linux)]()
[![Mac](https://img.shields.io/badge/OS-Mac-blue?logo=apple)]()

[![CI Builds Overview](https://img.shields.io/badge/CI%20Builds-Overview%20Page-blue?logo=circleci)](https://harisekhon.github.io/CI-CD/)
[![JSON](https://github.com/HariSekhon/TeamCity-CI/actions/workflows/json.yaml/badge.svg)](https://github.com/HariSekhon/TeamCity-CI/actions/workflows/json.yaml)
[![YAML](https://github.com/HariSekhon/TeamCity-CI/actions/workflows/yaml.yaml/badge.svg)](https://github.com/HariSekhon/TeamCity-CI/actions/workflows/yaml.yaml)
[![XML](https://github.com/HariSekhon/TeamCity-CI/actions/workflows/xml.yaml/badge.svg)](https://github.com/HariSekhon/TeamCity-CI/actions/workflows/xml.yaml)
[![Validation](https://github.com/HariSekhon/TeamCity-CI/actions/workflows/validate.yaml/badge.svg)](https://github.com/HariSekhon/TeamCity-CI/actions/workflows/validate.yaml)
[![Kics](https://github.com/HariSekhon/TeamCity-CI/actions/workflows/kics.yaml/badge.svg)](https://github.com/HariSekhon/TeamCity-CI/actions/workflows/kics.yaml)
[![Grype](https://github.com/HariSekhon/TeamCity-CI/actions/workflows/grype.yaml/badge.svg)](https://github.com/HariSekhon/TeamCity-CI/actions/workflows/grype.yaml)
[![Semgrep](https://github.com/HariSekhon/TeamCity-CI/actions/workflows/semgrep.yaml/badge.svg)](https://github.com/HariSekhon/TeamCity-CI/actions/workflows/semgrep.yaml)
[![Semgrep Cloud](https://github.com/HariSekhon/TeamCity-CI/actions/workflows/semgrep-cloud.yaml/badge.svg)](https://github.com/HariSekhon/TeamCity-CI/actions/workflows/semgrep-cloud.yaml)
[![Trivy](https://github.com/HariSekhon/TeamCity-CI/actions/workflows/trivy.yaml/badge.svg)](https://github.com/HariSekhon/TeamCity-CI/actions/workflows/trivy.yaml)

[![Repo on Azure DevOps](https://img.shields.io/badge/repo-Azure%20DevOps-0078D7?logo=azure%20devops)](https://dev.azure.com/harisekhon/GitHub/_git/TeamCity-CI)
[![Repo on GitHub](https://img.shields.io/badge/repo-GitHub-2088FF?logo=github)](https://github.com/HariSekhon/TeamCity-CI)
[![Repo on GitLab](https://img.shields.io/badge/repo-GitLab-FCA121?logo=gitlab)](https://gitlab.com/HariSekhon/TeamCity-CI)
[![Repo on BitBucket](https://img.shields.io/badge/repo-BitBucket-0052CC?logo=bitbucket)](https://bitbucket.org/HariSekhon/TeamCity-CI)

[TeamCity](https://www.jetbrains.com/teamcity/) CI configurations, synchronized from my automated TeamCity cluster.


### TeamCity configuration

- `.teamcity/` - XML format live sync'd
- `exports/` - JSON exports using API scripts in [DevOps Bash tools](https://github.com/HariSekhon/DevOps-Bash-tools) repo
- `kotlin/` - Kotlin exports from UI
- `.teamcity.vcs.oauth.json` - VCS connection to this repo via OAuth
- `.teamcity.vcs.ssh.json` - VCS connection to this repo via SSH key

[teamcity.sh](https://github.com/HariSekhon/DevOps-Bash-tools/blob/master/teamcity.sh) - one-shot TeamCity cluster on Docker with automated agent authorization and VCS integration via API calls.

TeamCity on Docker - [docker-compose.yml](https://github.com/HariSekhon/DevOps-Bash-tools/blob/master/setup/teamcity-docker-compose.yml)

TeamCity on Kubernetes configurations are [here](https://github.com/HariSekhon/Kubernetes-configs).

### Automation

- [Kubernetes configs](https://github.com/HariSekhon/Kubernetes-configs) - extensive Kubernetes configurations, including TeamCity-on-Kubernetes & Jenkins-on-Kubernetes, plus advanced templates for most major kubernetes objects

- [DevOps Bash tools](https://github.com/HariSekhon/DevOps-Bash-tools):
  - [teamcity.sh](https://github.com/HariSekhon/DevOps-Bash-tools/blob/master/teamcity.sh) - launches a [TeamCity](https://www.jetbrains.com/teamcity/) cluster in Docker
    - auto-loads VCS with all the builds
  - [teamcity_api.sh](https://github.com/HariSekhon/DevOps-Bash-tools/blob/master/teamcity/teamcity_api.sh) - query the [TeamCity API](https://www.jetbrains.com/help/teamcity/rest-api.html), handling authentication and other details
  - [jenkins.sh](https://github.com/HariSekhon/DevOps-Bash-tools/blob/master/jenkins.sh) - one-touch [Jenkins CI](https://jenkins.io/) instance in Docker
     - auto-loads and builds a pipeline from `Jenkinsfile`
  - [concourse.sh](https://github.com/HariSekhon/DevOps-Bash-tools/blob/master/cicd/concourse.sh) - one-touch [Concourse CI](https://concourse-ci.org/) instance in Docker
    - auto-loads and builds a pipeline from `.concourse.yml`
  - [gocd.sh](https://github.com/HariSekhon/DevOps-Bash-tools/blob/master/cicd/gocd.sh) - one-touch [GoCD CI](https://www.gocd.org/) cluster in Docker
    - auto-loads and builds a pipeline from a config repo


### See Also

- [Templates](https://github.com/HariSekhon/Templates) - templates for many CI systems, code and configs eg. advanced Jenkinsfile & Jenkins Shared Library (Groovy), GitHub Actions, Travis CI, CircleCI, AWS CodeBuild, GCP Cloud Build, Makefile, Vagrantfile, Dockerfile, docker-compose.yml etc.

- [Advanced Nagios Plugins](https://github.com/HariSekhon/Nagios-Plugins) - 450+ production monitoring checks including for the Jenkins API


### CI Systems

All my [major GitHub repos](https://github.com/HariSekhon) contain fully working live configs for most major CI system out there.

See [CI/CD](https://github.com/HariSekhon/Knowledge-Base/blob/main/ci-cd.md) notes in my public Knowledge Base for more details and comparisons between different CI/CD systems.

##### Local CI

You can boot any of these CI and run the repo's build with a single short one-word command using the scripts above.

- [Jenkins](https://www.jenkins.io/) - `Jenkinsfile` at the top of each repo
- [Concourse](https://concourse-ci.org/) - `.concourse.yml` at the top of each repo
- [GoCD](https://www.gocd.org/) - `setup/gocd_config_repo.json` in each repo
- [TeamCity](https://www.jetbrains.com/teamcity/) - `.teamcity.vcs.oauth.json` / `.teamcity.vcs.ssh.json` connection to this repo

##### Hosted CI

- [AppVeyor](https://www.appveyor.com/)
- [AWS CodeBuild](https://aws.amazon.com/codebuild/)
- [Azure DevOps Pipelines](https://dev.azure.com/)
- [BitBucket Pipelines](https://bitbucket.org/product/features/pipelines)
- [Buddy](https://buddy.works/)
- [BuildKite](https://buildkite.com/)
- [Circle CI](https://circleci.com/)
- [Cirrus CI](https://cirrus-ci.org/)
- [CodeShip](https://codeship.com/)
- [Codefresh](https://codefresh.io/)
- [Drone.io](https://drone.io/)
- [GCP Cloud Build](https://cloud.google.com/cloud-build)
- [GitHub Actions Workflows](https://github.com/features/actions)
- [GitLab CI](https://docs.gitlab.com/ee/ci/)
- [Semaphore CI](https://semaphoreci.com/)
- [Shippable](https://www.shippable.com/)
- [Travis CI](https://travis-ci.org/)

## Related Repositories

- [Jenkins](https://github.com/HariSekhon/Jenkins) - Advanced Jenkinsfile & Jenkins Shared Library

- [GitHub-Actions](https://github.com/HariSekhon/GitHub-Actions) - GitHub Actions master template & GitHub Actions Shared Workflows library

- [DevOps Bash Tools](https://github.com/HariSekhon/DevOps-Bash-tools) - 1000+ DevOps Bash Scripts, Advanced `.bashrc`, `.vimrc`, `.screenrc`, `.tmux.conf`, `.gitconfig`, CI configs & Utility Code Library - AWS, GCP, Kubernetes, Docker, Kafka, Hadoop, SQL, BigQuery, Hive, Impala, PostgreSQL, MySQL, LDAP, DockerHub, Jenkins, Spotify API & MP3 tools, Git tricks, GitHub API, GitLab API, BitBucket API, Code & build linting, package management for Linux / Mac / Python / Perl / Ruby / NodeJS / Golang, and lots more random goodies

- [SQL Scripts](https://github.com/HariSekhon/SQL-scripts) - 100+ SQL Scripts - PostgreSQL, MySQL, AWS Athena, Google BigQuery

- [Kubernetes configs](https://github.com/HariSekhon/Kubernetes-configs) - Kubernetes YAML configs - Best Practices, Tips & Tricks are baked right into the templates for future deployments

- [Terraform](https://github.com/HariSekhon/Terraform) - Terraform templates for AWS / GCP / Azure / GitHub management

- [DevOps Python Tools](https://github.com/HariSekhon/DevOps-Python-tools) - 80+ DevOps CLI tools for AWS, GCP, Hadoop, HBase, Spark, Log Anonymizer, Ambari Blueprints, AWS CloudFormation, Linux, Docker, Spark Data Converters & Validators (Avro / Parquet / JSON / CSV / INI / XML / YAML), Elasticsearch, Solr, Travis CI, Pig, IPython

- [DevOps Perl Tools](https://github.com/harisekhon/perl-tools) - 25+ DevOps CLI tools for Hadoop, HDFS, Hive, Solr/SolrCloud CLI, Log Anonymizer, Nginx stats & HTTP(S) URL watchers for load balanced web farms, Dockerfiles & SQL ReCaser (MySQL, PostgreSQL, AWS Redshift, Snowflake, Apache Drill, Hive, Impala, Cassandra CQL, Microsoft SQL Server, Oracle, Couchbase N1QL, Dockerfiles, Pig Latin, Neo4j, InfluxDB), Ambari FreeIPA Kerberos, Datameer, Linux...

- [The Advanced Nagios Plugins Collection](https://github.com/HariSekhon/Nagios-Plugins) - 450+ programs for Nagios monitoring your Hadoop & NoSQL clusters. Covers every Hadoop vendor's management API and every major NoSQL technology (HBase, Cassandra, MongoDB, Elasticsearch, Solr, Riak, Redis etc.) as well as message queues (Kafka, RabbitMQ), continuous integration (Jenkins, Travis CI) and traditional infrastructure (SSL, Whois, DNS, Linux)

- [Nagios Plugin Kafka](https://github.com/HariSekhon/Nagios-Plugin-Kafka) - Kafka API pub/sub Nagios Plugin written in Scala with Kerberos support

- [HAProxy Configs](https://github.com/HariSekhon/HAProxy-configs) - 80+ HAProxy Configs for Hadoop, Big Data, NoSQL, Docker, Elasticsearch, SolrCloud, HBase, Cloudera, Hortonworks, MapR, MySQL, PostgreSQL, Apache Drill, Hive, Presto, Impala, ZooKeeper, OpenTSDB, InfluxDB, Prometheus, Kibana, Graphite, SSH, RabbitMQ, Redis, Riak, Rancher etc.

- [Dockerfiles](https://github.com/HariSekhon/Dockerfiles) - 50+ DockerHub public images for Docker & Kubernetes - Hadoop, Kafka, ZooKeeper, HBase, Cassandra, Solr, SolrCloud, Presto, Apache Drill, Nifi, Spark, Mesos, Consul, Riak, OpenTSDB, Jython, Advanced Nagios Plugins & DevOps Tools repos on Alpine, CentOS, Debian, Fedora, Ubuntu, Superset, H2O, Serf, Alluxio / Tachyon, FakeS3

- [HashiCorp Packer templates](https://github.com/HariSekhon/Packer-templates) - Linux automated bare-metal installs and portable virtual machines OVA format appliances using HashiCorp Packer, Redhat Kickstart, Debian Preseed and Ubuntu AutoInstaller / Cloud-Init

- [Diagrams-as-Code](https://github.com/HariSekhon/Diagrams-as-Code) - Cloud & Open Source architecture diagrams with Python & D2 source code provided - automatically regenerated via GitHub Actions CI/CD - AWS, GCP, Kubernetes, Jenkins, ArgoCD, Traefik, Kong API Gateway, Nginx, Redis, PostgreSQL, Kafka, Spark, web farms, event processing...

- [Knowledge-Base](https://github.com/HariSekhon/Knowledge-Base) - IT Knowledge Base from 20 years in DevOps, Linux, Cloud, Big Data, AWS, GCP etc.
