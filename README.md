# GitHub-action-1
[![Context testing](https://github.com/iamdevops995/GitHub-action-1/actions/workflows/context-testing.yaml/badge.svg?branch=main)](https://github.com/iamdevops995/GitHub-action-1/actions/workflows/context-testing.yaml)


### workflow_dispatch event triggered  using GitHub's REST API .

curl -X POST \
  -H "Accept: application/vnd.github+json" \
  -H "Authorization: Bearer <PAT-token>" \
  -H "X-GitHub-Api-Version: 2022-11-28" \
  https://api.github.com/repos/iamdevops995/GitHub-action-1/actions/workflows/github-env.yaml/dispatches \
  -d '{"ref":"main"}}'
