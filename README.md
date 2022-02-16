# DXS | DOTNET first blazor application
 
 ## WHAT WE WILL DO HERE?  
    This application give you a basic knowledge about creating a new component, inserting them to a page, creating a new public parameter to modify one component behavior at page in importing time.
    
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

### Adding a component
Each of the .razor files defines a UI component that can be reused.
    Open the Index.razor file in a text editor of your choice. The Index.razor file already exists,  
    and it was created when you ran the dotnet new command.  
    It's located in the Pages folder inside the BlazorApp directory that was created earlier.  

### Modify a component
Component parameters are specified using attributes or child content, which allow you to set properties on the child component.  
Define a parameter on the Counter component for specifying how much it increments with every button click:
    Add a public property for IncrementAmount with a [Parameter] attribute.  
    Change the IncrementCount method to use the IncrementAmount when incrementing the value of currentCount.  

### Run command
    dotnet watch

Fiquem por dentro deste repositório com atualizações sempre que possível!  
[DOTNET] #notnet #blazor