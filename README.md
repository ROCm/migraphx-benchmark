# migraphx-benchmark

This directory contains reusable workflows in subdirectory that can be used in different workflows. The reusable workflows are designed to automate repetitive tasks in a software development workflow, such as deploying the application to different environments, checking the code for errors, and generating reports.

## List of reusable workflows
- [benchmarks.yml](https://github.com/ROCmSoftwarePlatform/migraphx-benchmark/blob/main/.github/workflows/benchmarks.yml) caller of this workflow is [here](https://github.com/ROCmSoftwarePlatform/AMDMIGraphX/blob/develop/.github/workflows/benchmark.yaml)
- [history.yml](https://github.com/ROCmSoftwarePlatform/migraphx-benchmark/blob/main/.github/workflows/history.yml) caller of this workflow is [here](https://github.com/ROCmSoftwarePlatform/AMDMIGraphX/blob/develop/.github/workflows/history.yaml)
- [perf-test.yml](https://github.com/ROCmSoftwarePlatform/migraphx-benchmark/blob/main/.github/workflows/perf-test.yml) caller of this workflow is [here](https://github.com/ROCmSoftwarePlatform/AMDMIGraphX/blob/develop/.github/workflows/performance.yaml)
- [rocm-release.yml](https://github.com/ROCmSoftwarePlatform/migraphx-benchmark/blob/main/.github/workflows/rocm-release.yml) caller of this workflow is [here](https://github.com/ROCmSoftwarePlatform/AMDMIGraphX/blob/develop/.github/workflows/rocm-image-release.yaml)

Each reusable workflow is described in more details [here](https://github.com/ROCmSoftwarePlatform/migraphx-benchmark/tree/main/.github/workflows)

---
