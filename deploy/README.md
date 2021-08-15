# Deploy

Action to run on push to main branch:

```yaml
on:
  push:
    branches:
      - main
```

This action should handle the work needed when deploying like:

- open change ticket
- wait till change ticket valid
