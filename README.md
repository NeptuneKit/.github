# .github
NeptuneKit organization reusable workflows

## Workflows

- `.github/workflows/ohpm-publish.yml`
  - Reusable OHPM publish pipeline (`workflow_call`)
- `.github/workflows/auto-tag-on-main.yml`
  - Reusable auto-tag pipeline for `main` pushes (`workflow_call`)
  - Requires secret: `RELEASE_BOT_TOKEN`
