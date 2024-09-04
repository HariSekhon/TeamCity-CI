# TeamCity CI Config

[![GitHub stars](https://img.shields.io/github/stars/HariSekhon/TeamCity-CI?logo=github)](https://github.com/HariSekhon/TeamCity-CI/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/HariSekhon/TeamCity-CI?logo=github)](https://github.com/HariSekhon/TeamCity-CI/network)
[![License](https://img.shields.io/github/license/HariSekhon/TeamCity-CI)](https://github.com/HariSekhon/TeamCity-CI/blob/master/LICENSE)
[![My LinkedIn](https://img.shields.io/badge/LinkedIn%20Profile-HariSekhon-blue?logo=data:image/svg%2bxml;base64,PHN2ZyByb2xlPSJpbWciIGZpbGw9IiNmZmZmZmYiIHZpZXdCb3g9IjAgMCAyNCAyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj48dGl0bGU+TGlua2VkSW48L3RpdGxlPjxwYXRoIGQ9Ik0yMC40NDcgMjAuNDUyaC0zLjU1NHYtNS41NjljMC0xLjMyOC0uMDI3LTMuMDM3LTEuODUyLTMuMDM3LTEuODUzIDAtMi4xMzYgMS40NDUtMi4xMzYgMi45Mzl2NS42NjdIOS4zNTFWOWgzLjQxNHYxLjU2MWguMDQ2Yy40NzctLjkgMS42MzctMS44NSAzLjM3LTEuODUgMy42MDEgMCA0LjI2NyAyLjM3IDQuMjY3IDUuNDU1djYuMjg2ek01LjMzNyA3LjQzM2MtMS4xNDQgMC0yLjA2My0uOTI2LTIuMDYzLTIuMDY1IDAtMS4xMzguOTItMi4wNjMgMi4wNjMtMi4wNjMgMS4xNCAwIDIuMDY0LjkyNSAyLjA2NCAyLjA2MyAwIDEuMTM5LS45MjUgMi4wNjUtMi4wNjQgMi4wNjV6bTEuNzgyIDEzLjAxOUgzLjU1NVY5aDMuNTY0djExLjQ1MnpNMjIuMjI1IDBIMS43NzFDLjc5MiAwIDAgLjc3NCAwIDEuNzI5djIwLjU0MkMwIDIzLjIyNy43OTIgMjQgMS43NzEgMjRoMjAuNDUxQzIzLjIgMjQgMjQgMjMuMjI3IDI0IDIyLjI3MVYxLjcyOUMyNCAuNzc0IDIzLjIgMCAyMi4yMjIgMGguMDAzeiIvPjwvc3ZnPgo=)](https://www.linkedin.com/in/HariSekhon/)
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

[![Repo on GitHub](https://img.shields.io/badge/repo-GitHub-2088FF?logo=github)](https://github.com/HariSekhon/TeamCity-CI)
[![Repo on GitLab](https://img.shields.io/badge/repo-GitLab-FCA121?logo=gitlab)](https://gitlab.com/HariSekhon/TeamCity-CI)
[![Repo on Azure DevOps](https://img.shields.io/badge/repo-Azure%20DevOps-0078D7?logo=azure%20devops)](https://dev.azure.com/harisekhon/GitHub/_git/TeamCity-CI)
[![Repo on BitBucket](https://img.shields.io/badge/repo-BitBucket-0052CC?logo=bitbucket)](https://bitbucket.org/HariSekhon/TeamCity-CI)

[TeamCity](https://www.jetbrains.com/teamcity/) CI configurations, synchronized from my automated TeamCity cluster.

## TeamCity configuration

- `.teamcity/` - XML format live sync'd
- `exports/` - JSON exports using API scripts in [DevOps Bash tools](https://github.com/HariSekhon/DevOps-Bash-tools) repo
- `kotlin/` - Kotlin exports from UI
- `.teamcity.vcs.oauth.json` - VCS connection to this repo via OAuth
- `.teamcity.vcs.ssh.json` - VCS connection to this repo via SSH key

[teamcity.sh](https://github.com/HariSekhon/DevOps-Bash-tools/blob/master/teamcity.sh) - one-shot TeamCity cluster on Docker with automated agent authorization and VCS integration via API calls.

TeamCity on Docker - [docker-compose.yml](https://github.com/HariSekhon/DevOps-Bash-tools/blob/master/setup/teamcity-docker-compose.yml)

TeamCity on Kubernetes configurations are [here](https://github.com/HariSekhon/Kubernetes-configs).

## Automation

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

#### Local CI

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

### Stargazers over time

[![Stargazers over time](https://starchart.cc/HariSekhon/TeamCity-CI.svg)](https://starchart.cc/HariSekhon/TeamCity-CI)

## More Core Repos

<!-- OTHER_REPOS_START -->

### Knowledge

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=HariSekhon&repo=Knowledge-Base&theme=ambient_gradient&description_lines_count=3)](https://github.com/HariSekhon/Knowledge-Base)
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=HariSekhon&repo=Diagrams-as-Code&theme=ambient_gradient&description_lines_count=3)](https://github.com/HariSekhon/Diagrams-as-Code)

<!--

Not support on GitHub Markdown:

<iframe src="https://raw.githubusercontent.com/HariSekhon/HariSekhon/main/knowledge.md" width="100%" height="500px"></iframe>

Does nothing:

<embed src="https://raw.githubusercontent.com/HariSekhon/HariSekhon/main/knowledge.md" width="100%" height="500px" />

-->

### DevOps Code

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=HariSekhon&repo=DevOps-Bash-tools&theme=ambient_gradient&description_lines_count=3)](https://github.com/HariSekhon/DevOps-Bash-tools)
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=HariSekhon&repo=DevOps-Python-tools&theme=ambient_gradient&description_lines_count=3)](https://github.com/HariSekhon/DevOps-Python-tools)
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=HariSekhon&repo=DevOps-Perl-tools&theme=ambient_gradient&description_lines_count=3)](https://github.com/HariSekhon/DevOps-Perl-tools)
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=HariSekhon&repo=DevOps-Golang-tools&theme=ambient_gradient&description_lines_count=3)](https://github.com/HariSekhon/DevOps-Golang-tools)

<!--
[![Gist Card](https://github-readme-stats.vercel.app/api/gist?id=f8f551332440f1ca8897ff010e363e03)](https://gist.github.com/HariSekhon/f8f551332440f1ca8897ff010e363e03)
-->

### Containerization

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=HariSekhon&repo=Kubernetes-configs&theme=ambient_gradient&description_lines_count=3)](https://github.com/HariSekhon/Kubernetes-configs)
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=HariSekhon&repo=Dockerfiles&theme=ambient_gradient&description_lines_count=3)](https://github.com/HariSekhon/Dockerfiles)

### CI/CD

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=HariSekhon&repo=GitHub-Actions&theme=ambient_gradient&description_lines_count=3)](https://github.com/HariSekhon/GitHub-Actions)
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=HariSekhon&repo=Jenkins&theme=ambient_gradient&description_lines_count=3)](https://github.com/HariSekhon/Jenkins)

### DBA - SQL

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=HariSekhon&repo=SQL-scripts&theme=ambient_gradient&description_lines_count=3)](https://github.com/HariSekhon/SQL-scripts)

### DevOps Reloaded

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=HariSekhon&repo=Nagios-Plugins&theme=ambient_gradient&description_lines_count=3)](https://github.com/HariSekhon/Nagios-Plugins)
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=HariSekhon&repo=HAProxy-configs&theme=ambient_gradient&description_lines_count=3)](https://github.com/HariSekhon/HAProxy-configs)
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=HariSekhon&repo=Templates&theme=ambient_gradient&description_lines_count=3)](https://github.com/HariSekhon/Templates)
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=HariSekhon&repo=Terraform&theme=ambient_gradient&description_lines_count=3)](https://github.com/HariSekhon/Terraform)
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=HariSekhon&repo=Packer-templates&theme=ambient_gradient&description_lines_count=3)](https://github.com/HariSekhon/Packer-templates)
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=HariSekhon&repo=Nagios-Plugin-Kafka&theme=ambient_gradient&description_lines_count=3)](https://github.com/HariSekhon/Nagios-Plugin-Kafka)

### Misc

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=HariSekhon&repo=Template-repo&theme=ambient_gradient&description_lines_count=3)](https://github.com/HariSekhon/Template-repo)
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=HariSekhon&repo=Spotify-tools&theme=ambient_gradient&description_lines_count=3)](https://github.com/HariSekhon/Spotify-tools)
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=HariSekhon&repo=Spotify-playlists&theme=ambient_gradient&description_lines_count=3)](https://github.com/HariSekhon/Spotify-playlists)

The rest of my original source repos are
[here](https://github.com/HariSekhon?tab=repositories&q=&type=source&language=&sort=stargazers).

Pre-built Docker images are available on my [DockerHub](https://hub.docker.com/u/harisekhon/).

<!-- 1x1 pixel counter to record hits -->
![](https://hit.yhype.me/github/profile?user_id=2211051)

<!-- OTHER_REPOS_END -->
