load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "internal",
    srcs = [
        "atmostevery.go",
        "buildmanagerinfo.go",
        "capmanagers.go",
        "conflict.go",
        "fieldmanager.go",
        "fields.go",
        "lastapplied.go",
        "lastappliedmanager.go",
        "lastappliedupdater.go",
        "managedfields.go",
        "managedfieldsupdater.go",
        "manager.go",
        "pathelement.go",
        "skipnonapplied.go",
        "stripmeta.go",
        "structuredmerge.go",
        "typeconverter.go",
        "versionconverter.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/apimachinery/pkg/util/managedfields/internal",
    importpath = "k8s.io/apimachinery/pkg/util/managedfields/internal",
    visibility = ["//vendor/k8s.io/apimachinery/pkg/util/managedfields:__subpackages__"],
    deps = [
        "//vendor/k8s.io/apimachinery/pkg/api/errors",
        "//vendor/k8s.io/apimachinery/pkg/api/meta",
        "//vendor/k8s.io/apimachinery/pkg/api/validation",
        "//vendor/k8s.io/apimachinery/pkg/apis/meta/v1:meta",
        "//vendor/k8s.io/apimachinery/pkg/apis/meta/v1/unstructured",
        "//vendor/k8s.io/apimachinery/pkg/runtime",
        "//vendor/k8s.io/apimachinery/pkg/runtime/schema",
        "//vendor/k8s.io/klog/v2:klog",
        "//vendor/k8s.io/kube-openapi/pkg/schemaconv",
        "//vendor/k8s.io/kube-openapi/pkg/validation/spec",
        "//vendor/sigs.k8s.io/structured-merge-diff/v4/fieldpath",
        "//vendor/sigs.k8s.io/structured-merge-diff/v4/merge",
        "//vendor/sigs.k8s.io/structured-merge-diff/v4/schema",
        "//vendor/sigs.k8s.io/structured-merge-diff/v4/typed",
        "//vendor/sigs.k8s.io/structured-merge-diff/v4/value",
    ],
)
