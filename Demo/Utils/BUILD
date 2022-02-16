load("@rules_cc//cc:defs.bzl", "objc_library")

objc_library(
    name = "Utils",
    srcs = glob([
        "*.m",
    ]),
    hdrs = glob([
        "*.h",
    ]),
    includes = [
    ],
    module_name = "Utils",
    visibility = ["//visibility:public"],
    deps = [
        "//Demo/AttributeGenerator",
    ],
)
