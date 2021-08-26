# latest-release-test

On every commit to `main` (i.e. not PRs):

- `latest` tag is moved to this commit
- any existing `latest` Release is deleted

In parallel:

- usual CI build jobs run & upload artefacts

Finally after all the above finish:

- `latest` pre-release is created & artefacts are uploaded
