# CI_Toolkit_Proxy

Proxy repository for CI enforcement in the BHoM org. It contains no CI logic: the tier bundle workflows (`ci-prototype.yml`, `ci-alpha.yml`, `ci-beta.yml`) and the standalone `ci-format.yml` and `ci-unit-tests.yml` all run CI defined in [BuroHappoldEngineeringAdmin/CI_Toolkit](https://github.com/BuroHappoldEngineeringAdmin/CI_Toolkit), the single source of truth. Org rulesets require workflows from this repo as merge gates on pull requests.
