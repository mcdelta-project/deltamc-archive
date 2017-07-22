# CMAN-Archive
If you want to add your mod, do it like this:

name of file = ModNameInCamelCase.json

```JSON
{
    "Name":"ModNameInCamelCase",
    "Version":"v0.42 alpha",
    "MCVersion":["1.8.8", "1.8.7"],
    "Link":"http://www.example.com/DirectLinkToTheMod.jar",
    "Author":"Developer(s) of mod",
    "Desc":"One or two line description of mod.",
    "License":"LicenseOfMod",
    "Requirements":["MinecaftForge", "MyModCore"],
    "Incompatibilities":["MCPatcher", "RedPower2"],
    "Recommended":["OtherModsWhichWorkWellWithThis."],
    "Type":"Forge, Liteloader, Basemod or Installer",
    "Unstable":"false/true",
    "InstallerName":"NameOfFile.jar(Only if installer)"
}
```
