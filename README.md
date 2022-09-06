# Superdev.Editorconfig
[![Version](https://img.shields.io/nuget/v/Superdev.Editorconfig.svg)](https://www.nuget.org/packages/Superdev.Editorconfig)  [![Downloads](https://img.shields.io/nuget/dt/Superdev.Editorconfig.svg)](https://www.nuget.org/packages/Superdev.Editorconfig)

### Why _.editorconfig_?
EditorConfig helps maintain consistent coding styles for multiple developers working on the same project across various editors and IDEs. The EditorConfig project consists of a file format for defining coding styles and a collection of text editor plugins that enable editors to read the file format and adhere to defined styles. EditorConfig files are easily readable and they work nicely with version control systems.

### Download and Install Superdev.Editorconfig
This library is available on NuGet: https://www.nuget.org/packages/Superdev.Editorconfig
Use the following command to install Superdev.Editorconfig using NuGet package manager console:

    PM> Install-Package Superdev.Editorconfig

You can use this library in any .NET project which is compatible to .NET Standard 1.6 and higher.

### What rules are contained in _.editorconfig_?
The provided _**.editorconfig**_ file defines hand-picked, consistent rules covered by [.NET code-style analysis](https://docs.microsoft.com/en-us/dotnet/fundamentals/code-analysis/style-rules/).

### How to use _.editorconfig_?
If your project targets .NET 5 or later, code analysis is enabled by default.
If your project targets a different .NET implementation, for example, .NET Core, .NET Standard, or .NET Framework, you must manually enable code analysis by setting the EnableNETAnalyzers property to true.

### Contribution
Contributors welcome! If you have an addition or you find an inconsistency in the editorconfig file, feel free to create a new issue on github.com.

### Links
- [Code analysis in .NET](https://docs.microsoft.com/en-us/dotnet/fundamentals/code-analysis/overview)
- [EditorConfig](https://editorconfig.org/)
- [Configuration files for code analysis rules - .NET](https://docs.microsoft.com/en-us/dotnet/fundamentals/code-analysis/configuration-files)
- [Roslyn Analyzers](https://docs.microsoft.com/en-us/visualstudio/code-quality/roslyn-analyzers-overview?view=vs-2022), [StyleCop](https://www.nuget.org/packages/StyleCop.Analyzers/), [Roslynator](https://www.nuget.org/packages/Roslynator.Analyzers/), [XUnit Analyzers](https://www.nuget.org/packages/xunit.analyzers/), [Sonar Analyzer](https://www.nuget.org/packages/SonarAnalyzer.CSharp/).
