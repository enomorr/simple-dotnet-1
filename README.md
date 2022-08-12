# to create new dotnet mvc project
dotnet new mvc -n projectName

# to build and package
dotnet restore projectName.csproj
dotnet build projectName.csproj --configuration Release
dotnet publish projectName.csproj --configuration Release --output "directory path"



# simple-dotnet-files
dotnet new console (to create a new console)
dotnet add package Colorful.Console
# edit Preogram.cs file to add 
// using Console = Colorful.Console
dotnet run
dotnet new sln
dotnet add sln xxx.csproj file
