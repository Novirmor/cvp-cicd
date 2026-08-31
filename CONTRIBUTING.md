# Contributing

Thank you for contributing to cvp-cicd. This is a one-engineer practice, so
responses are slower than in a full-time open-source project — please be
patient.

## Ground rules

- Every change goes through a pull request, must pass the checks, and must
  be reviewed.
- Reusable workflows are pinned by commit SHA by every caller. A behavior
  change here is a coordinated change across the platform repositories.

## Getting started

1. Create a feature branch.
2. Install the toolchain from `mise.toml` (`mise install`).
3. Run the local gates before opening a pull request:

   ```sh
   task lint
   task test
   ```

4. Open a pull request against `main` and describe what changed and why.

## Security

Do not include security fixes in ordinary pull requests. Report them through
private vulnerability reporting as described in `SECURITY.md`.
