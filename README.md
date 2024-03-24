# Github Actions examples

## General use cases:
- Reusable workflow
  - [calling workflow](.github/workflows/calling-workflow.yml)
  - [reusable workflow](.github/workflows/reusable-workflow.yml)
- [Create PR on push](.github/workflows/create-pr.yml)
- [Print environment variables](.github/workflows/print-env.yml)
- [Dynamic artifact name](.github/workflows/dynamic-artifact-name.yml)
- [Manual workflow with different input types](.github/workflows/manual-workflow.yml)
- [Multi-line environment variable](.github/workflows/multiline-variable.yml)
- [Run on keyword in commit message](.github/workflows/run-on-commit-message.yml)
- [Run on keyword in PR comment](.github/workflows/run-on-pr-comment.yml)
- [Run step after previous failed](.github/workflows/step-status-check.yml)

## Golang
- [Build and test](https://github.com/frennky/wol/blob/master/.github/workflows/build.yml)
- [Lint](https://github.com/frennky/wol/blob/master/.github/workflows/lint.yml)

## Helm
- [Release Charts](https://github.com/frennky/lab/blob/master/.github/workflows/release-charts.yml)
- [Lint and Test Charts](https://github.com/frennky/lab/blob/master/.github/workflows/test-charts.yml)

## Ansible
- [Ansible Lint](https://github.com/frennky/ansible-role-raspberry-pi/blob/master/.github/workflows/ansible-lint.yml)
