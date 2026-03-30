# Greeter + GripMock Action

Example integration test.

This repository shows how to run GripMock in GitHub Actions via
`bavix/gripmock-action` for two descriptor formats:

- `api/greeter.proto`
- `api/greeter.pb`

The workflow is in `.github/workflows/integration.yml` and runs matrix tests
for both formats.

gRPC assertions are described in `tests/` and executed by
`grpctestify-rust` (`grpctestify tests/`).
