# NuGet.org V3 Service Index history

This repository uses [Simon Willison's clever Git scraping technique](https://simonwillison.net/2020/Oct/9/git-scraping/)
to keep a history of NuGet.org's V3 service index. This is done for the main (PROD) environment, but also their
pre-production/integration (INT) environment and testing (DEV) environment. It also tracks a service index on Azure DevOps
and MyGet.

## PROD

[History](api.nuget.org/v3/index.json) ([original endpoint](https://api.nuget.org/v3/index.json))

## INT 

[History](apiint.nugettest.org/v3/index.json) ([original endpoint](https://apiint.nugettest.org/v3/index.json))

## DEV 

[History](apidev.nugettest.org/v3/index.json) ([original endpoint](https://apidev.nugettest.org/v3/index.json))

## AzureDevOps nuget-build 

[History](pkgs.dev.azure.com/dnceng/public/_packaging/nuget-build/nuget/v3/index.json) ([original endpoint](https://pkgs.dev.azure.com/dnceng/public/_packaging/nuget-build/nuget/v3/index.json))

## MyGet nuget-build 

[History](dotnet.myget.org/F/nuget-build/api/v3/index.json) ([original endpoint](https://dotnet.myget.org/F/nuget-build/api/v3/index.json))
