# DXS | DOTNET first blazor application
 
 ### Information
Program.cs is the entry point for the app that starts the server and where you configure the app services and middleware.  
    App.razor is the root component for the app.  
    The Pages directory contains some example web pages for the app.  
    BlazorApp.csproj defines the app project and its dependencies.  
    The launchSettings.json file inside the Properties directory defines different profile settings for the local development     environment. A port number ranging between 5000-5300 is automatically assigned at project creation and saved on this file.    

### Homepage basics
The displayed page is defined by the Index.razor file located inside the Pages directory. This is what its contents look like:
![homepage](https://dotnet.microsoft.com/static/images/screenshot-blazor-tutorial-run.png?v=ML-XF4Mca53pi6FrhnsZvQeYyL-C6Yc-3BDlKLPvGDY)

### Counter click function
Each time the Click me button is selected:  
    The onclick event is fired.  
    The IncrementCount method is called.  
    The currentCount is incremented.  
    The component is rendered to show the updated count.  
