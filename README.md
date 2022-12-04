# base-generation-repository

## GitHub-GitLab sync

This repository is automatically synchronized with [a GitLab repository of the same name](https://clickndrest.gitlab.yandexcloud.net/user/base-generation-repository). <br />

How: via [a GitHub Action](.github/workflows/gitlab-sync.yml) <br />
How it works: every push action to this repository invokes the GitHub Action which pushes all the changes to the GitLab replica.