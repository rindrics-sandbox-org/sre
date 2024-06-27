# GitHub Action `fetch-all-repos`

Fetches all repositories under given organization

## Input

```yaml
  inputs:
    organization:
      type: string
      description: Name of GitHub organization to fetch repositories
      required: true
    token:
      type: string
      description: GitHub Token with `read` permission of `repo:metadata`
      required: true
```

## Output

```yaml
  outputs:
    repositories:
      type: string
      description: List of repository names in format `["repoA", "repoB"]`
```
