F:\WF\vsix\demo\src\Content>dotnet new --install F:\WF\vsix\demo\src\Content\MyConsole01
dotnet new prasadContool -o ConsoleDemo
dotnet new --uninstall "F:\WF\vsix\demo\src\Content\MyConsole01

F:\WF\vsix\demo\src\Content>Reset-Templates  ????


F:\WF\vsix\demo\src>nuget.exe pack .\Prasad.Template.NetCoreTool.nuspec
Attempting to build package from 'Prasad.Template.NetCoreTool.nuspec'.
Successfully created package 'F:\WF\vsix\demo\src\Prasad.Template.NetCoreTool.nuspec.1.0.0.nupkg'."

F:\WF\vsix\demo\src>nuget.exe pack .\Prasad.Template.NetCoreTool.nuspec -OutputDirectory .\nupkg
Attempting to build package from 'Prasad.Template.NetCoreTool.nuspec'.
Successfully created package 'F:\WF\vsix\demo\src\nupkg\Prasad.Template.NetCoreTool.nuspec.1.0.0.nupkg'.

F:\WF\vsix\demo\src>dotnet new --install F:\WF\vsix\demo\src\nupkg\Prasad.Template.NetCoreTool.nuspec.1.0.0.nupkg
