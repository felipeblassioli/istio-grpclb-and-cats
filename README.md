# istio-grpclb-and-cats

This demo uses [bazel](https://bazel.build/) to build gRPC services using golang.

Observations:

### Requirements

1. Install [bazel](https://bazel.build/)

### WORKSPACE

1. [rules_go](https://github.com/bazelbuild/rules_go) for golang build logic (rule_go do not use `go.mod` but instead use its [go_repository rule](https://github.com/bazelbuild/bazel-gazelle/blob/master/repository.rst))
2. [Gazelle](https://github.com/bazelbuild/bazel-gazelle) for build file generation (pretty handy)
