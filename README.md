# Welcome 

Welcome Exercices-csharp public repository. This repository contains a collection of c# exercices you can complete at your leisure!

It is heavily inspired by https://exercism.io/ and similar websites.

# How to use
- Clone this repository ```git clone https://github.com/richardlalancette/exercises-csharp```
- Install .net core 3.1 from CLI
    - Mac ```brew cask install dotnet-sdk```
    - Win10 ```choco install dotnetcore-sdk```
    - Linux ```sudo apt-get update; sudo apt-get install -y apt-transport-https && sudo apt-get update && sudo apt-get install -y dotnet-sdk-3.1```
- Install your favorite c# editor: `rider/vs/vscode/vsmac`
- Checkout a tag containing a question you want to do: ```git checkout tags/<questionxxx> -b <branch>```
- Fetch with tags: ```git fetch --all --tags```
- Complete the code and run it: ```dotnet run --project exercises\exercises.csproj```
- Run the tests until they pass! ```dotnet test```