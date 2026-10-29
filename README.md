# compai-mirror
this is a mirror of https://gitlab-ext.utu.fi/tt.utu.fi/compai for agents to use as context

## Mirroring

`.github/workflows/mirror.yml` runs daily and copies the latest
https://gitlab-ext.utu.fi/tt.utu.fi/compai into this repository. If the upstream
becomes internal or private, the workflow makes this repository private.
That requires a repository secret `REPO_ADMIN_TOKEN` (a token with permission to
administer this repository).
