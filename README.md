# ci-smoke-lab-18
Throwaway sandbox for release-readiness CI smoke test

## Build artifact

The CI pipeline (`.github/workflows/demo.yml`) is triggered on demand via `workflow_dispatch`.
It writes `build-output.txt` and uploads it as a build artifact named exactly `demo-build`,
which can be downloaded from the workflow run's **Artifacts** tab.
