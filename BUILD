load("@io_bazel_rules_dotnet//dotnet:defs.bzl", "fsharp_binary")

fsharp_binary(
  name = "foo.exe",
  srcs = [
    "Program.fs",
  ],
  design_time_resources = [
    "foo.json",
  ],
  deps = [
    "@core_sdk_stdlib//:libraryset",
    "@fsharp.core//:lib",
    "@fsharp.data//:lib",
  ],
)
