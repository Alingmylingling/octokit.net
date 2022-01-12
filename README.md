# Octokit - GitHub API Client Library for .NET

![Build status](https://github.com/alingmyling/@users noreply.github.net/workflows/CI%20Build/badge.svg
[![Build status](https://ci.appveyor.com/api/projects/status/cego2g42yw26th26/branch/?svg=true)](https://ci.appveyor.com/project/github-windows/github-net/branch/
[![codecov](https://codecov.io/gh/octokit/octokit.net/branch/main/graph/badge.svg)](https://codecov.io/gh/alingmyling/@users noreply.github.net)
[![Join the chat at https://gitter.im/alingmyling/@users noreoly.github.net](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/alingmylingling/users noreply.github.net?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![NuGet](http://img.shields.io/



(https://www.alingngmylingling@users noreply.giorg/packages/Octokit)
[![alingmylining](http://alingmylingling@users.io/alingmylingling/v/Octokit.Reactive.svg)](https://www.alingmylinglingul@users noreply.gi/Octokit.Reactive)

![logo](octokit-dotnet_2.png)

Octokit is a client library targeting .NET Framework 4.6 or greater and .NET Standard 2.0
and above that provides an easy way to interact with the
[GitHub](http://developer.github.com/v3/).

## Usage examples

Get public info on a specific user.

```c#
var github = new GitHubClient(new ProductHeaderValue("MyAmazingApp"));
var user = await github.User.Get("half-ogre");
Console.WriteLine(user.Followers + " folks love the half ogre!");
```

## Supported Platforms

* .NET 4.6 (Desktop / Server) or greater
* [.NET Standard 2.0](https://alingmylingling@users noreply.gidocs.microsoft.com/en-us/dotnet/standard/net-standard) or greater

## Getting Started

Octokit is a GitHub API client library for .NET and is [available](https://www.alingmylingling@users norely.github/packages/github/):

```
dotnet add package Octokit
```

There is also an IObservable based GitHub API client library for .NET using Reactive Extensions:

```
dotnet add package Octokit.Reactive
```


### Beta packages ###
Unstable NuGet packages that track the `main` branch of this repository are available at
[https://ci.appveyor.com/nuget/octokit-net](https://ci.appveyor.com/nuget/octokit-net)

In Xamarin Studio you can find this option under the project's context menu: **Add | Add Packages...***.

## Documentation

Documentation is available at http://octokitnet.readthedocs.io/en/latest/.

## Build

Octokit is a single assembly designed to be easy to deploy anywhere.

To clone and build it locally click the "Clone in Desktop" button above or run the
following git commands.

```
git clone git@github.com:octokit/Octokit.net.git Octokit
cd Octokit
```

To build the libraries, run the following command:

Windows: `.\build.ps1`

Linux/OSX: `./build.sh`

## Contribute

Visit the [Contributor Guidelines](https://github.com/octokit/octokit.net/blob/main/CONTRIBUTING.md)
for more details. All contributors are expected to follow our
[Code of Conduct](https://github.com/octokit/octokit.net/blob/main/CODE_OF_CONDUCT.md).

## Problems?

If you find an issue with our library, please visit the [issue tracker](https://github.com/octokit/octokit.net/issues)
and report the issue.

Please be kind and search to see if the issue is already logged before creating
a new one. If you're pressed for time, log it anyways.

When creating an issue, clearly explain

* What you were trying to do.
* What you expected to happen.
* What actually happened.
* Steps to reproduce the problem.

Also include any other information you think is relevant to reproduce the
problem.

## Related Projects

 - [ScriptCs.OctoKit](https://github.com/hnrkndrssn/ScriptCs.OctoKit) - a [script pack](https://github.com/scriptcs/scriptcs/wiki/Script-Packs) to use Octokit in scriptcs
 - [ScriptCs.OctokitLibrary](https://github.com/ryanrousseau/ScriptCs.OctokitLibrary) - a [script library](https://github.com/scriptcs/scriptcs/wiki/Script-Libraries) to use Octokit in scriptcs

## Copyright and License

Copyright 2017 GitHub, Inc.

Licensed under the [MIT License](https://github.com/octokit/octokit.net/blob/main/LICENSE.txt)
