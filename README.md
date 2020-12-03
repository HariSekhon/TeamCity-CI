TeamCity CI Config
==================

Synchronized config from my automated dockerized [TeamCity](https://www.jetbrains.com/teamcity/) cluster.

See Also:

- [DevOps Bash tools](https://github.com/HariSekhon/DevOps-Bash-tools):
  - `teamcity.sh` - create your own [TeamCity](https://www.jetbrains.com/teamcity/) cluster in 1 command
  - `teamcity_api.sh` - query the [TeamCity API](https://www.jetbrains.com/help/teamcity/rest-api.html), handling authentication and other details
  - `jenkins.sh` - one-touch [Jenkins CI](https://jenkins.io/)
     - auto-loads and builds a pipeline from `Jenkinsfile` if available (there is one in that repo and all my major GitHub repos)
  - `concourse.sh` - one-touch [Concourse CI](https://concourse-ci.org/)
    - auto-loads and builds a pipeline from `.concourse.yml` if available
  - `gocd.sh` - one-touch [GoCD CI](https://www.gocd.org/) cluster
    - auto-loads and builds a pipeline from a config repo if available
