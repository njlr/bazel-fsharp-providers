# bazel-fsharp-providers

```bash
dotnet run
bazel run //:foo.exe
```

Expected output is:

```
[|1; 2; 3|]
```

You may need a `.bazelrc` like this:

```
build --host_platform @io_bazel_rules_dotnet//dotnet/toolchain:linux_amd64_3.1.100
build --platforms @io_bazel_rules_dotnet//dotnet/toolchain:linux_amd64_3.1.100
```
