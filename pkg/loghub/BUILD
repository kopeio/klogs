package(default_visibility = ["//visibility:public"])

licenses(["notice"])

load(
    "@io_bazel_rules_go//go:def.bzl",
    "go_library",
)

go_library(
    name = "go_default_library",
    srcs = [
        "logserver.go",
        "options.go",
    ],
    tags = ["automanaged"],
    deps = [
        "//pkg/grpc:go_default_library",
        "//pkg/mesh:go_default_library",
        "//pkg/proto:go_default_library",
        "@com_github_golang_glog//:go_default_library",
        "@org_golang_x_net//context:go_default_library",
    ],
)
