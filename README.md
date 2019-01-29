# Travis CI template for NuGet packages built with .NET Core

A simple Travis CI configuration to build, test, and publish a NuGet package using .NET Core.

## Quickstart

[Install .NET Core](https://www.microsoft.com/net/core) then install this template:

```bash
dotnet new -i Syncromatics.Engineering.DX.TravisCI.NetCore
```

Use this template in your project's root directory:

```bash
dotnet new syncdx-travisci-netcore --projectName 'MyProject'
```

See what other parameters are supported in this template:

```bash
dotnet new syncdx-travisci-netcore -h
```

## Building

_Remove any shields below that do not apply_

[![Travis](https://img.shields.io/travis/syncromatics/Syncromatics.Engineering.DX.TravisCI.NetCore.svg)](https://travis-ci.org/syncromatics/Syncromatics.Engineering.DX.TravisCI.NetCore)
[![NuGet](https://img.shields.io/nuget/v/Syncromatics.Engineering.DX.TravisCI.NetCore.svg)](https://www.nuget.org/packages/Syncromatics.Engineering.DX.TravisCI.NetCore/)
[![NuGet Pre Release](https://img.shields.io/nuget/vpre/Syncromatics.Engineering.DX.TravisCI.NetCore.svg)](https://www.nuget.org/packages/Syncromatics.Engineering.DX.TravisCI.NetCore/)

1. Ensure you have [installed .NET Core](https://www.microsoft.com/net/core)
r. Run `dotnet pack Syncromatics.Engineering.DX.TravisCI.NetCore.csproj` in the root directory

This will build a `Syncromatics.Engineering.DX.TravisCI.NetCore.0.0.0.nupkg` file that you can test locally by installing with the `dotnet new` command:

```bash
dotnet new -i ./bin/Debug/Syncromatics.Engineering.DX.TravisCI.NetCore.0.0.0.nupkg
```

## Code of Conduct

We are committed to fostering an open and welcoming environment. Please read our [code of conduct](CODE_OF_CONDUCT.md) before participating in or contributing to this project.

## Contributing

We welcome contributions and collaboration on this project. Please read our [contributor's guide](CONTRIBUTING.md) to understand how best to work with us.

## License and Authors

[![GMV Syncromatics Engineering logo](https://secure.gravatar.com/avatar/645145afc5c0bc24ba24c3d86228ad39?size=16) GMV Syncromatics Engineering](https://github.com/syncromatics)

[![license](https://img.shields.io/github/license/syncromatics/Syncromatics.Engineering.DX.TravisCI.NetCore.svg)](https://github.com/syncromatics/Syncromatics.Engineering.DX.TravisCI.NetCore/blob/master/LICENSE)
[![GitHub contributors](https://img.shields.io/github/contributors/syncromatics/Syncromatics.Engineering.DX.TravisCI.NetCore.svg)](https://github.com/syncromatics/Syncromatics.Engineering.DX.TravisCI.NetCore/graphs/contributors)

This software is made available by GMV Syncromatics Engineering under the MIT license.