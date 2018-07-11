# MsDeployReplaceRulesTest

Sample project demonstrating issue with dotnet publish and MsDeployReplaceRules

Issue logged here: [https://github.com/aspnet/websdk/issues/383](https://github.com/aspnet/websdk/issues/383)

open cmd / powershell prompt at solution or project root

```dotnet publish /p:PublishProfile=WebDeployPackage /v:diagnostic > build.log```

open the build.log file;  The replace rule match and replace parameters are listed with their values but the generated command line is missing the values
