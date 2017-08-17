# CMAN-Archive
If you want to add your mod, do it like this:

name of file = ModNameInCamelCase.json

```JSON
{
    "Name":"ModNameInCamelCase",
    "Author":"Developer(s) of mod",
    "Desc":"Description of mod.",
    "License":"LicenseOfMod",
    "Requirements":["Mods which this mod needs", "MyModLibrary"],
    "Incompatibilities":["Mods which break when used with this", "HerobrineMod"],
    "Recommended":["Mods which this mod works well with", "AmazingMod"],
    "Type":"Forge, Liteloader, Basemod or Installer",
    "Unstable":"true/false",
    "InstallerName":"NameOfFile.jar(Leave out if not installer mod)",
    "Versions":[
        {
            "Version":"v0.1",
            "MCVersion":["1.7.2, 1.7.10"],
            "Link":"http://www.example.com/DirectLinkToTheMod.jar"
        }
    ]
}
```
