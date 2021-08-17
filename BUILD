load("@build_bazel_rules_swift//swift:swift.bzl", "swift_proto_library")

proto_library(
    name = "my_proto",
    srcs = ["my.proto"],
)

swift_proto_library(
    name = "my_swift_library",
    deps = [":my_proto"],
)