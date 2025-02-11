---
Title: .NET Core
Contributor: Microsoft
Logo: microsoft.jpg
Web: https://www.microsoft.com
---
# .NET Core

.NET Core has a high-performance and modular design, and supports full side by side to make it easy to adopt new .NET Core versions without affecting other apps. It currently runs on Linux, Mac, and Windows. [ASP.NET Core](/projects/aspnet-core) is built on top of .NET Core. ASP.NET Core is a high-performance and modular design, and supports full side by side to make it easy to adopt new versions without affecting other apps. These products are actively developed by the .NET team and in collaboration with a community of open source developers. Together we are dedicated to improving and extending the .NET platform with new features and for new scenarios.

.NET Core has two major components. It includes a small runtime that is built from the same codebase as the .NET Framework CLR. The .NET Core runtime includes the same GC and JIT (RyuJIT), but doesn't include features like Application Domains or Code Access Security. The runtime is delivered on NuGet,via the Microsoft.CoreCLR package.

.NET Core also includes the base class libraries. These libraries are largely the same code as the .NET Framework class libraries, but have been factored (removal of dependencies) to enable us to ship a smaller set of libraries. These libraries are shipped as System.* NuGet packages on NuGet.org. This enables both smaller footprint applications, and allows different applications on the same machine to use different versions of .NET Core.

## Project Details

* [Project Info Site](https://github.com/dotnet/core)
* Project Code Repos: [.NET Runtime](https://github.com/dotnet/runtime), [.NET Core Framework](https://github.com/dotnet/corefx), [.NET Core Tools](https://github.com/dotnet/cli)
* Project Docs Repos: [Concepts](https://github.com/dotnet/docs), [APIs](https://github.com/dotnet/dotnet-api-docs), [Samples](https://github.com/dotnet/samples)
* Project License Type: [MIT](https://github.com/dotnet/runtime/blob/master/LICENSE.TXT)
* Project Main Contact: [Immo Landwerth](https://github.com/terrajobst)

## Quicklinks

* [Contribute](https://github.com/dotnet/corefx/blob/master/CONTRIBUTING.md)
* [Discussions](https://forums.dotnetfoundation.org/)
* [Samples](https://github.com/Microsoft/dotnetsamples)
* [Blog](https://blogs.msdn.microsoft.com/dotnet/)
* Twitter: [@DotNet](https://twitter.com/dotnet)
* [Documentation](https://docs.microsoft.com/dotnet)
