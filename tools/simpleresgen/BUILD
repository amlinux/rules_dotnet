load("@io_bazel_rules_dotnet//dotnet:defs.bzl", "core_binary")

core_binary(
    name = "simpleresgen",
    srcs = glob(["**/*.cs"]),
    unsafe = True,
    visibility = ["//visibility:public"],
    deps = [
        "@io_bazel_rules_dotnet//dotnet/stdlib.core:system.dll",
        "@io_bazel_rules_dotnet//dotnet/stdlib.core:system.xml.dll",
    ],
)
