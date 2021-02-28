load("@bazel_tools//tools/build_defs/repo:git.bzl", "git_repository")

git_repository(
  name = "io_bazel_rules_dotnet",
  remote = "https://github.com/bazelbuild/rules_dotnet",
  branch = "master",
)

load("@io_bazel_rules_dotnet//dotnet:deps.bzl", "dotnet_repositories")

dotnet_repositories()

load("@io_bazel_rules_dotnet//dotnet:defs.bzl", "dotnet_register_toolchains", "dotnet_repositories_nugets", "nuget_package")

dotnet_register_toolchains()
dotnet_repositories_nugets()

### Generated by the tool
nuget_package(
    name = "fsharp.core",
    package = "fsharp.core",
    version = "4.7.2",
    core_lib = {
        "netcoreapp2.0": "lib/netstandard2.0/cs/FSharp.Core.resources.dll",
        "netcoreapp2.1": "lib/netstandard2.0/cs/FSharp.Core.resources.dll",
        "netcoreapp2.2": "lib/netstandard2.0/cs/FSharp.Core.resources.dll",
        "netcoreapp3.0": "lib/netstandard2.0/cs/FSharp.Core.resources.dll",
        "netcoreapp3.1": "lib/netstandard2.0/cs/FSharp.Core.resources.dll",
    },
    core_files = {
        "netcoreapp2.0": [
           "lib/netstandard2.0/cs/FSharp.Core.resources.dll",
           "lib/netstandard2.0/de/FSharp.Core.resources.dll",
           "lib/netstandard2.0/es/FSharp.Core.resources.dll",
           "lib/netstandard2.0/fr/FSharp.Core.resources.dll",
           "lib/netstandard2.0/FSharp.Core.dll",
           "lib/netstandard2.0/FSharp.Core.optdata",
           "lib/netstandard2.0/FSharp.Core.sigdata",
           "lib/netstandard2.0/FSharp.Core.xml",
           "lib/netstandard2.0/it/FSharp.Core.resources.dll",
           "lib/netstandard2.0/ja/FSharp.Core.resources.dll",
           "lib/netstandard2.0/ko/FSharp.Core.resources.dll",
           "lib/netstandard2.0/pl/FSharp.Core.resources.dll",
           "lib/netstandard2.0/pt-BR/FSharp.Core.resources.dll",
           "lib/netstandard2.0/ru/FSharp.Core.resources.dll",
           "lib/netstandard2.0/tr/FSharp.Core.resources.dll",
           "lib/netstandard2.0/zh-Hans/FSharp.Core.resources.dll",
           "lib/netstandard2.0/zh-Hant/FSharp.Core.resources.dll",
        ],
        "netcoreapp2.1": [
           "lib/netstandard2.0/cs/FSharp.Core.resources.dll",
           "lib/netstandard2.0/de/FSharp.Core.resources.dll",
           "lib/netstandard2.0/es/FSharp.Core.resources.dll",
           "lib/netstandard2.0/fr/FSharp.Core.resources.dll",
           "lib/netstandard2.0/FSharp.Core.dll",
           "lib/netstandard2.0/FSharp.Core.optdata",
           "lib/netstandard2.0/FSharp.Core.sigdata",
           "lib/netstandard2.0/FSharp.Core.xml",
           "lib/netstandard2.0/it/FSharp.Core.resources.dll",
           "lib/netstandard2.0/ja/FSharp.Core.resources.dll",
           "lib/netstandard2.0/ko/FSharp.Core.resources.dll",
           "lib/netstandard2.0/pl/FSharp.Core.resources.dll",
           "lib/netstandard2.0/pt-BR/FSharp.Core.resources.dll",
           "lib/netstandard2.0/ru/FSharp.Core.resources.dll",
           "lib/netstandard2.0/tr/FSharp.Core.resources.dll",
           "lib/netstandard2.0/zh-Hans/FSharp.Core.resources.dll",
           "lib/netstandard2.0/zh-Hant/FSharp.Core.resources.dll",
        ],
        "netcoreapp2.2": [
           "lib/netstandard2.0/cs/FSharp.Core.resources.dll",
           "lib/netstandard2.0/de/FSharp.Core.resources.dll",
           "lib/netstandard2.0/es/FSharp.Core.resources.dll",
           "lib/netstandard2.0/fr/FSharp.Core.resources.dll",
           "lib/netstandard2.0/FSharp.Core.dll",
           "lib/netstandard2.0/FSharp.Core.optdata",
           "lib/netstandard2.0/FSharp.Core.sigdata",
           "lib/netstandard2.0/FSharp.Core.xml",
           "lib/netstandard2.0/it/FSharp.Core.resources.dll",
           "lib/netstandard2.0/ja/FSharp.Core.resources.dll",
           "lib/netstandard2.0/ko/FSharp.Core.resources.dll",
           "lib/netstandard2.0/pl/FSharp.Core.resources.dll",
           "lib/netstandard2.0/pt-BR/FSharp.Core.resources.dll",
           "lib/netstandard2.0/ru/FSharp.Core.resources.dll",
           "lib/netstandard2.0/tr/FSharp.Core.resources.dll",
           "lib/netstandard2.0/zh-Hans/FSharp.Core.resources.dll",
           "lib/netstandard2.0/zh-Hant/FSharp.Core.resources.dll",
        ],
        "netcoreapp3.0": [
           "lib/netstandard2.0/cs/FSharp.Core.resources.dll",
           "lib/netstandard2.0/de/FSharp.Core.resources.dll",
           "lib/netstandard2.0/es/FSharp.Core.resources.dll",
           "lib/netstandard2.0/fr/FSharp.Core.resources.dll",
           "lib/netstandard2.0/FSharp.Core.dll",
           "lib/netstandard2.0/FSharp.Core.optdata",
           "lib/netstandard2.0/FSharp.Core.sigdata",
           "lib/netstandard2.0/FSharp.Core.xml",
           "lib/netstandard2.0/it/FSharp.Core.resources.dll",
           "lib/netstandard2.0/ja/FSharp.Core.resources.dll",
           "lib/netstandard2.0/ko/FSharp.Core.resources.dll",
           "lib/netstandard2.0/pl/FSharp.Core.resources.dll",
           "lib/netstandard2.0/pt-BR/FSharp.Core.resources.dll",
           "lib/netstandard2.0/ru/FSharp.Core.resources.dll",
           "lib/netstandard2.0/tr/FSharp.Core.resources.dll",
           "lib/netstandard2.0/zh-Hans/FSharp.Core.resources.dll",
           "lib/netstandard2.0/zh-Hant/FSharp.Core.resources.dll",
        ],
        "netcoreapp3.1": [
           "lib/netstandard2.0/cs/FSharp.Core.resources.dll",
           "lib/netstandard2.0/de/FSharp.Core.resources.dll",
           "lib/netstandard2.0/es/FSharp.Core.resources.dll",
           "lib/netstandard2.0/fr/FSharp.Core.resources.dll",
           "lib/netstandard2.0/FSharp.Core.dll",
           "lib/netstandard2.0/FSharp.Core.optdata",
           "lib/netstandard2.0/FSharp.Core.sigdata",
           "lib/netstandard2.0/FSharp.Core.xml",
           "lib/netstandard2.0/it/FSharp.Core.resources.dll",
           "lib/netstandard2.0/ja/FSharp.Core.resources.dll",
           "lib/netstandard2.0/ko/FSharp.Core.resources.dll",
           "lib/netstandard2.0/pl/FSharp.Core.resources.dll",
           "lib/netstandard2.0/pt-BR/FSharp.Core.resources.dll",
           "lib/netstandard2.0/ru/FSharp.Core.resources.dll",
           "lib/netstandard2.0/tr/FSharp.Core.resources.dll",
           "lib/netstandard2.0/zh-Hans/FSharp.Core.resources.dll",
           "lib/netstandard2.0/zh-Hant/FSharp.Core.resources.dll",
        ],
    },
)
nuget_package(
    name = "fable.core",
    package = "fable.core",
    version = "3.2.4",
    core_lib = {
        "netcoreapp2.0": "lib/netstandard2.0/Fable.Core.dll",
        "netcoreapp2.1": "lib/netstandard2.0/Fable.Core.dll",
        "netcoreapp2.2": "lib/netstandard2.0/Fable.Core.dll",
        "netcoreapp3.0": "lib/netstandard2.0/Fable.Core.dll",
        "netcoreapp3.1": "lib/netstandard2.0/Fable.Core.dll",
    },
    core_deps = {
        "netcoreapp2.0": [
           "@fsharp.core//:netcoreapp2.0_core",
        ],
        "netcoreapp2.1": [
           "@fsharp.core//:netcoreapp2.1_core",
        ],
        "netcoreapp2.2": [
           "@fsharp.core//:netcoreapp2.2_core",
        ],
        "netcoreapp3.0": [
           "@fsharp.core//:netcoreapp3.0_core",
        ],
        "netcoreapp3.1": [
           "@fsharp.core//:netcoreapp3.1_core",
        ],
    },
    core_files = {
        "netcoreapp2.0": [
           "lib/netstandard2.0/Fable.Core.dll",
           "lib/netstandard2.0/Fable.Core.xml",
        ],
        "netcoreapp2.1": [
           "lib/netstandard2.0/Fable.Core.dll",
           "lib/netstandard2.0/Fable.Core.xml",
        ],
        "netcoreapp2.2": [
           "lib/netstandard2.0/Fable.Core.dll",
           "lib/netstandard2.0/Fable.Core.xml",
        ],
        "netcoreapp3.0": [
           "lib/netstandard2.0/Fable.Core.dll",
           "lib/netstandard2.0/Fable.Core.xml",
        ],
        "netcoreapp3.1": [
           "lib/netstandard2.0/Fable.Core.dll",
           "lib/netstandard2.0/Fable.Core.xml",
        ],
    },
)
nuget_package(
    name = "fsharp.data",
    package = "fsharp.data",
    version = "3.3.3",
    core_lib = {
        "netcoreapp2.0": "lib/netstandard2.0/FSharp.Data.DesignTime.dll",
        "netcoreapp2.1": "lib/netstandard2.0/FSharp.Data.DesignTime.dll",
        "netcoreapp2.2": "lib/netstandard2.0/FSharp.Data.DesignTime.dll",
        "netcoreapp3.0": "lib/netstandard2.0/FSharp.Data.DesignTime.dll",
        "netcoreapp3.1": "lib/netstandard2.0/FSharp.Data.DesignTime.dll",
    },
    core_deps = {
        "netcoreapp2.0": [
           "@fsharp.core//:netcoreapp2.0_core",
        ],
        "netcoreapp2.1": [
           "@fsharp.core//:netcoreapp2.1_core",
        ],
        "netcoreapp2.2": [
           "@fsharp.core//:netcoreapp2.2_core",
        ],
        "netcoreapp3.0": [
           "@fsharp.core//:netcoreapp3.0_core",
        ],
        "netcoreapp3.1": [
           "@fsharp.core//:netcoreapp3.1_core",
        ],
    },
    core_files = {
        "netcoreapp2.0": [
           "lib/netstandard2.0/FSharp.Data.DesignTime.dll",
           "lib/netstandard2.0/FSharp.Data.DesignTime.pdb",
           "lib/netstandard2.0/FSharp.Data.dll",
           "lib/netstandard2.0/FSharp.Data.pdb",
           "lib/netstandard2.0/FSharp.Data.xml",
        ],
        "netcoreapp2.1": [
           "lib/netstandard2.0/FSharp.Data.DesignTime.dll",
           "lib/netstandard2.0/FSharp.Data.DesignTime.pdb",
           "lib/netstandard2.0/FSharp.Data.dll",
           "lib/netstandard2.0/FSharp.Data.pdb",
           "lib/netstandard2.0/FSharp.Data.xml",
        ],
        "netcoreapp2.2": [
           "lib/netstandard2.0/FSharp.Data.DesignTime.dll",
           "lib/netstandard2.0/FSharp.Data.DesignTime.pdb",
           "lib/netstandard2.0/FSharp.Data.dll",
           "lib/netstandard2.0/FSharp.Data.pdb",
           "lib/netstandard2.0/FSharp.Data.xml",
        ],
        "netcoreapp3.0": [
           "lib/netstandard2.0/FSharp.Data.DesignTime.dll",
           "lib/netstandard2.0/FSharp.Data.DesignTime.pdb",
           "lib/netstandard2.0/FSharp.Data.dll",
           "lib/netstandard2.0/FSharp.Data.pdb",
           "lib/netstandard2.0/FSharp.Data.xml",
        ],
        "netcoreapp3.1": [
           "lib/netstandard2.0/FSharp.Data.DesignTime.dll",
           "lib/netstandard2.0/FSharp.Data.DesignTime.pdb",
           "lib/netstandard2.0/FSharp.Data.dll",
           "lib/netstandard2.0/FSharp.Data.pdb",
           "lib/netstandard2.0/FSharp.Data.xml",
        ],
    },
)
### End of generated by the tool