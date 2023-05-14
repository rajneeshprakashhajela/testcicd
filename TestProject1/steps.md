
https://learn.microsoft.com/en-us/azure/devops/pipelines/tasks/reference/use-dotnet-v2?view=azure-pipelines

# Use .NET Core v2
# Acquires a specific version of the .NET Core SDK from the internet or the local cache and adds it to the PATH. Use this task to change the version of .NET Core used in subsequent tasks. Additionally provides proxy support.
- task: UseDotNet@2
  inputs:
    #packageType: 'sdk' # 'runtime' | 'sdk'. Package to install. Default: sdk.
    #useGlobalJson: false # boolean. Optional. Use when packageType = sdk. Use global json. Default: false.
    #workingDirectory: # string. Optional. Use when useGlobalJson = true. Working Directory. 
    #version: # string. Optional. Use when useGlobalJson = false || packageType = runtime. Version. 
    #includePreviewVersions: false # boolean. Optional. Use when useGlobalJson = false  || packageType = runtime. Include Preview Versions. Default: false.
  # Advanced
    #vsVersion: # string. Compatible Visual Studio version. 
    #installationPath: '$(Agent.ToolsDirectory)/dotnet' # string. Path To Install .Net Core. Default: $(Agent.ToolsDirectory)/dotnet.
    #performMultiLevelLookup: false # boolean. Perform Multi Level Lookup. Default: false.
    
