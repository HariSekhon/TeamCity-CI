TeamCity CI Config
==================

Synchronized config from my automated dockerized [TeamCity](https://www.jetbrains.com/teamcity/) cluster.

TeamCity configuration is under `.teamcity/` directory.

#### See Also:

- [DevOps Bash tools](https://github.com/HariSekhon/DevOps-Bash-tools):
  - `teamcity.sh` - create your own [TeamCity](https://www.jetbrains.com/teamcity/) cluster in 1 command
  - `teamcity_api.sh` - query the [TeamCity API](https://www.jetbrains.com/help/teamcity/rest-api.html), handling authentication and other details
  - `jenkins.sh` - one-touch [Jenkins CI](https://jenkins.io/)
     - auto-loads and builds a pipeline from `Jenkinsfile` if available
  - `concourse.sh` - one-touch [Concourse CI](https://concourse-ci.org/)
    - auto-loads and builds a pipeline from `.concourse.yml` if available
  - `gocd.sh` - one-touch [GoCD CI](https://www.gocd.org/) cluster
    - auto-loads and builds a pipeline from a config repo if available

- [Templates](https://github.com/HariSekhon/Templates) - templates for many CI systems, code and configs eg. GitHub Actions, CircleCI, Jenkinsfile, GCP Cloud Build, Makefile, Vagrantfile, Dockerfile, docker-compose.yml etc.

- [Advanced Nagios Plugins](https://github.com/HariSekhon/Nagios-Plugins) - 450+ production monitoring checks including for the Jenkins API

All my [major GitHub repos](https://github.com/HariSekhon) also contain fully working configs for just about every major CI system out there:

Eg. [DevOps Bash tools](https://github.com/HariSekhon/DevOps-Bash-tools) repo contains CI configs for:

Local CI:

You can boot any of these CI and run the repo's build in just a short 1 word command using the scripts.

- [Jenkins](https://www.jenkins.io/) - `Jenkinsfile` at the top of each repo
- [Concourse](https://concourse-ci.org/) - `.concourse.yml` at the top of each repo
- [GoCD](https://www.gocd.org/) - `gocd_config_repo.json` in `setup/` in each repo
- [TeamCity](https://www.jetbrains.com/teamcity/) - this repo

Hosted CI:

- [AppVeyor](https://www.appveyor.com/)
- [Azure DevOps Pipelines](https://dev.azure.com/)
- [BitBucket Pipelines](https://bitbucket.org/product/features/pipelines)
- [Buddy](https://buddy.works/)
- [BuildKite](https://buildkite.com/)
- [Circle CI](https://circleci.com/)
- [Cirrus CI](https://cirrus-ci.org/)
- [CodeShip](https://codeship.com/)
- [Codefresh](https://codefresh.io/)
- [Drone.io](https://drone.io/)
- [GitHub Actions](https://github.com/features/actions)
- [GitLab CI](https://docs.gitlab.com/ee/ci/)
- [Semaphore CI](https://semaphoreci.com/)
- [Shippable](https://www.shippable.com/)
- [Travis CI](https://travis-ci.org/)
- [Wercker](https://app.wercker.com/)
