## TerribleDev.RuntimeIdentifier.MSBuild

A simple package to build all of your runtime identifiers


# Installation

Visual Studio:

```
PM> Install-Package TerribleDev.RuntimeIdentifier.MSBuild
```

dotnet cli

```
$ dotnet add package TerribleDev.RuntimeIdentifier.MSBuild
```


# Usage


add some runtime identifiers to your property group

```xml
  <PropertyGroup>
    <RuntimeIdentifiers>win10-x64;osx.10.11-x64</RuntimeIdentifiers>
  </PropertyGroup>
```

run `dotnet publish` watch how you no longer have to specify the runtimes to compile for.