# Godot build fails with Central Pacakge Management enabled.

```
PS /path/cpm-test> dotnet restore
    /path/cpm-test/CPM Test.csproj : error NU1008: Projects that use central package version management should not define the version on the PackageReference items but on the PackageVersion items: Godot.SourceGenerators;GodotSharp;GodotSharpEditor.

Restore failed with 1 error(s) in 0,5s
```