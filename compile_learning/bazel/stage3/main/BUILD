cc_binary(
    name = "hello-world",
    srcs = ["hello-world.cc"],
    deps = [
        "//lib:hello-time",
        "//external:stage2_",
        ]
)

cc_test(
    name = "mytest",
    srcs = ["test.cc"],
    #copts = ["-Iexternal/gtest/googletest-release-1.7.0/include"],
    deps = [
        "//external:stage2_",
        "@gtestt//:gtest11",
    ]
)

