# DevOps.Code.Entities.Metapackages.EntityFrameworkCore

[![AppVeyor build status](https://img.shields.io/appveyor/ci/cdorst/devops-code-entities-metapackages-entityframeworkc.svg?label=AppVeyor&style=for-the-badge)](https://ci.appveyor.com/project/cdorst/devops-code-entities-metapackages-entityframeworkc)
[![NuGet package status](https://img.shields.io/nuget/v/CDorst.DevOps.Code.Entities.Metapackages.EntityFrameworkCore.svg?label=NuGet&style=for-the-badge)](https://www.nuget.org/packages/CDorst.DevOps.Code.Entities.Metapackages.EntityFrameworkCore)

## Description

Metapackage for EntityFrameworkCore dependencies

## Environment Variables

This project depends on this environment variable:

Name | Description
---- | -----------
`LOCAL_NUGET_SOURCE_PATH` | *Required* to build the project, but not required during code execution. This is set to `c:\projects\nuget\cache` on the build server. On your development machine, set this to an empty, existing path. `dotnet restore` will inspect this folder prior to checking NuGet.

## Dependencies

Name | Status
---- | ------
Microsoft.EntityFrameworkCore | [![NuGet package status](https://img.shields.io/nuget/v/Microsoft.EntityFrameworkCore.svg?label=NuGet&style=flat-square)](https://www.nuget.org/packages/Microsoft.EntityFrameworkCore)

## NuGet

This project is published as a NuGet package at [https://www.nuget.org/packages/CDorst.DevOps.Code.Entities.Metapackages.EntityFrameworkCore](https://www.nuget.org/packages/CDorst.DevOps.Code.Entities.Metapackages.EntityFrameworkCore)

## Version

1.0.2

## Metaproject

DevOps.Code.Entities.Metapackages.EntityFrameworkCore is maintained by robots and exists because of a declarative template metaproject. View the metaproject's component directory at [https://github.com/CDorst/Project.Index](https://github.com/CDorst/Project.Index)

