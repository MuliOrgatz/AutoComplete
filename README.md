# AutoComplete
Responsive autocomplete component built from scratch

Angular 9.0.2 / ASP.NET Core 2.2

## Installation

1.  Clone the project into the folder of your choice - `git clone (your directory)`
2.  Remove the `.git` folder - `rm -rf .git`
3.  Initialize a new repository in the directory - `git init`
4.  Install NPM Packages - `(cd ClientApp && npm install)`
5.  Restore NuGet Packages - `dotnet restore`
6.  Launch Visual Studio 2017 or more 
7.  Debugging Server and Client code can be done by hitting `F5`

## Structure of the Project

### Back-End

The back-end is an ASP.NET Core 2.2 WebAPI application.

- `Controllers` - Add new endpoints by creating or updating Controllers in this directory
- `Models` - Add data models in this folder
- `Interfaces` - Add any interfaces that will be implemented in this directory
- `Services` - Add any services in this directory. Typically services will be making the direct HttpClient and Database interactions
- `Startup.cs` - Startup configuration exists here, as well as registration of any data services that will be injected into Controllers at runtime

### Front-End

You will find the front-end code in the `ClientApp` directory. 
This is a fully compatible Angular 9.0.2 CLI application. 
This means from within the `ClientApp` folder full `ng generate` capabilities are available and encouraged.

## Running the project

This is an ASP.NET Core 2.2 project with an Angular 9 front-end. 
The dotnet project is configured to automatically build the Angular project when `dotnet run` is executed. 
This means that you do not need to worry about running `ng serve -o` manually. 

## Debugging from Visual Studio Code

If you have issues when first running make sure that the `Full stack` debug target is chosen.

## Contributions Welcome

This is a very informal project and any and all pull requests with improvements will be accepted. 
I look forward to your feedback!
