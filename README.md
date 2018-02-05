# Einfacher NuGet Packer
Modifizierter Packer basierend auf jchadwick/NuGet.Packer 

## NuGet Packer Optionen


| MSBuild Property   | Standard      | Bezeichnung                          |
|--------------------|:-------------:|--------------------------------------|
| BuildNuGetPackage  | true          | Build the .nupkg during compilation  |
| BuildSymbolsPackage| true          | Build the corresponding symbols package during compilation                                     |
| MajorVersion       | 1             | Package version (major)              |
| MinorVersion       | 0             | Package version (minor)              |
| PatchVersion       | 0             | Packetversion (patch)                |
| PackageVersion     | [MajorVersion].[MinorVersion].[PatchVersion] | The full version number.  Override this property if you are managing version numbers outside of this system. |
| PublishNuGetPackage| false         | Enables publishing a NuGet package   |

