# latest-release-test

On every commit to `main`:

- `latest` tag is moved to this commit
- any existing `latest` Release is deleted
- usual CI build jobs run & upload artefacts
- `latest` release is created & artefacts are uploaded
