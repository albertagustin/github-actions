# Post Deploy

Action to run on pull request closed:

```yaml
on:
  pull_request:
    branches:
      - main
    types: [closed]
```

This action should handle the work needed after a deploy like:

- send notifications
- update change ticket
- update external tools
