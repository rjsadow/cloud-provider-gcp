load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "common",
    srcs = [
        "common.go",
        "doc.go",
        "interfaces.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/kube-openapi/pkg/common",
    importpath = "k8s.io/kube-openapi/pkg/common",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/github.com/emicklei/go-restful/v3:go-restful",
        "//vendor/k8s.io/kube-openapi/pkg/openapiconv",
        "//vendor/k8s.io/kube-openapi/pkg/spec3",
        "//vendor/k8s.io/kube-openapi/pkg/validation/spec",
    ],
)
