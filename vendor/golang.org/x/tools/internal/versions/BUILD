load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "versions",
    srcs = [
        "gover.go",
        "types.go",
        "types_go121.go",
        "types_go122.go",
        "versions.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/golang.org/x/tools/internal/versions",
    importpath = "golang.org/x/tools/internal/versions",
    visibility = ["//vendor/golang.org/x/tools:__subpackages__"],
)
