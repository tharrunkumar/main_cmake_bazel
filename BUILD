# Load the necessary Bazel rules
load("@rules_cc//cc:defs.bzl", "cc_library")

cc_library(
	name = "export",
	srcs = ["libdummy_cmake_project.a"],
    hdrs = ["sample.h"],
    visibility = ["//visibility:public"]
	)