# Visual Studio Project Template for ASP.NET Core 2.X Razor Pages
ASP.NET Core 2.x Razor Pages Project Templates

This solution includes everything we need to create custom ASP.NET Core Razor Pages web application Template. 

## How to use the template 

Build the "RazorTemplate" project in the solution. It will gerate a RazorTemplate.vsix file in the folder \bin\Release. Close Visual Studio and run this RazorTemplate.vsix file. It will add 2 project templates to the IDE.

## Modify the Razor Projects

Modify the RazorPages21 or RazorPages22 projects to customise the template.

Then goto RazorTemplate folder from command line.
Now execute following command to regenerate the .nuget package:

neget pack RzrTemplate.nuspec 

Next rebuild the RzrTemplate project from the Visual Studio 2017 community.

Use RzrTemplate.vsix file to distribute the tempate.
