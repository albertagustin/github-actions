# Pre Deploy

Action to run on pull request open:

```yaml
on:
  pull_request:
    branches:
      - main
```

This action should do required pre-work when the PR is open like:

- linting
- validation
