package(default_visibility = ["//visibility:public"])

licenses(["notice"])

load(
    "@io_bazel_rules_go//go:def.bzl",
    "go_library",
)

go_library(
    name = "go_default_library",
    srcs = ["crd_finalizer.go"],
    tags = ["automanaged"],
    deps = [
        "//vendor/github.com/golang/glog:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/api/errors:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/api/meta:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/apis/meta/v1:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/apis/meta/v1/unstructured:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/conversion:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/runtime/schema:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/util/errors:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/util/runtime:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/util/sets:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/util/wait:go_default_library",
        "//vendor/k8s.io/client-go/dynamic:go_default_library",
        "//vendor/k8s.io/client-go/tools/cache:go_default_library",
        "//vendor/k8s.io/client-go/util/workqueue:go_default_library",
        "//vendor/k8s.io/kube-apiextensions-server/pkg/apis/apiextensions:go_default_library",
        "//vendor/k8s.io/kube-apiextensions-server/pkg/client/clientset/internalclientset/typed/apiextensions/internalversion:go_default_library",
        "//vendor/k8s.io/kube-apiextensions-server/pkg/client/informers/internalversion/apiextensions/internalversion:go_default_library",
        "//vendor/k8s.io/kube-apiextensions-server/pkg/client/listers/apiextensions/internalversion:go_default_library",
    ],
)
