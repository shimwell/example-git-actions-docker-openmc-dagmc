# example-git-actions-docker-openmc-dagmc

This is a minimal example showing use of github actions to build a docker image containing OpenMC with DAGMC and perform simulation tests when there are changes to the repository source code.

The Action is currently triggered on pull requests or pushes to the main branch but can be rolled out to include other branches as well.

The automated continuous integration (CI) testing process takes about 30 minutes to report if the simulation values are as expected.

The status of the git action can be reported via a badge [![ActionsCI](https://github.com/shimwell/example-git-actions-docker-openmc-dagmc/workflows/CI/badge.svg)](https://github.com/Shimwell/example-git-actions-docker-openmc-dagmc/actions?query=workflow%3ACI)
