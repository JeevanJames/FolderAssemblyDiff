# Plugins Diff for .NET Core projects
Plugin Diff is a tool that is useful with .NET Core applications that use dynamically-loaded plugins (assemblies). Given the source code of your application and the details of the plugins, it will calculate all the assemblies or NuGet packages that are required to be dropped into the application for it to be able to load and run the plugins.

## What's included?
This is what is included (or planned) in the repo:
* A .NET Core class library that contains the core logic for calculating the plugin diffs.
* A CLI tool, available both as a .NET Core tool and a standalone cross-platform executable.
* A [Cake Build](https://cakebuild.net/) task

## Getting started
To run Plugins Diff, you will need the following installed:
* [.NET Core SDK](https://dotnet.microsoft.com/download): The tool uses the `dotnet` CLI tools to perform its core tasks.

### Class library
TBD

### CLI tool
TBD

### Cake Build task
TBD
