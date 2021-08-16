# Saxo Dataworkbench Helm: Fork of Acryl Datahub Helm
- [Introduction](#introduction)
- [Branches](#branches)
- [Workflows](#workflows)

## Introduction
This project repository hosts the fork of Acryl Datahub Helm(https://github.com/acryldata/datahub-helm) for Saxo's DataWorkbench Helm Implementation.

## Branches
- master: reflection of upstream branch, datahub-helm/master
- automation: host automation workflows to keep master branch, in sync with datahub-helm/master

## Workflows
- sync-repo 
  ### Parameters:
  - source_repo: "https://github.com/acryldata/datahub-helm"
  - source_branch: "master"
  - destination_branch: "master"
  - github_token: personal access token, stored in repository's secret as PAT
  - sync_tags: "true"
