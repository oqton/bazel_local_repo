workspace(name = "app")

local_repository(
  name = "lib",
  path = "lib",
)

load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_jar")

http_jar(
    name = "bazel_diff",
    urls = [
        "https://github.com/Tinder/bazel-diff/releases/download/4.0.5/bazel-diff_deploy.jar",
    ],
    sha256 = "59f2a614f90b4c2a6c83f1e6146d8722dfaac3a1d8f42734dcbb6ccf373a1cbd",
)
