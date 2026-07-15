# CI_Toolkit_Proxy

[![Release Readiness](https://github.com/BHoM/CI_Toolkit_Proxy/actions/workflows/release-readiness.yml/badge.svg)](https://github.com/BHoM/CI_Toolkit_Proxy/actions/workflows/release-readiness.yml)

Proxy repository for CI enforcement in the BHoM org. It contains no CI logic: the tier bundle workflows (`ci-prototype.yml`, `ci-alpha.yml`, `ci-beta.yml`) and the weekly `release-readiness.yml` caller all run CI defined in [BuroHappoldEngineeringAdmin/CI_Toolkit](https://github.com/BuroHappoldEngineeringAdmin/CI_Toolkit), the single source of truth. Org rulesets require workflows from this repo as merge gates on pull requests.
