package(default_visibility = ["//visibility:public"])

cc_library(
    name = "libhoth_device_mock",
    hdrs = ["libhoth_device_mock.h"],
    srcs = ["libhoth_device_mock.cc"],
    deps = [
        "@googletest//:gtest",
        "//transports:libhoth_device",
        "//protocol:host_cmd",
    ],
)

filegroup(
    name = "test_data",
    srcs = glob(["*.bin"]),
)
