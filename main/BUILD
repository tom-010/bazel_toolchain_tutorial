load("@rules_cc//cc:defs.bzl", "cc_binary")

#package(features = ["-warning_flags"]) # disable warnings as errors feature for the complete file

cc_binary(
    name = "hello-world",
    features = ["-warning_flags"], # disable warnings as errors feature
    srcs = ["hello-world.cc"],
)
