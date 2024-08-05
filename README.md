# PR (Pull Request) Validation

## Validate source branch

The idea is to prevent accidental merge from unauthorized branch. In my example, it prevents merge if the source branch name is not "qa" or starts with "hotfix".

**Pipeline**: [azure-pipelines-branches.yml](azure-pipelines-branches.yml)
