# Jupiter Notebook set up with .NET Kernel

[↩️ Back to main page](../README.md)

1. **Install the .NET 9 SDK**  
   Get the latest .NET 9 SDK from the [.NET download page](https://dotnet.microsoft.com/download/dotnet/9.0).
1. **Install Jupyter**
   You can install Jupyter Notebook (or JupyterLab) using pip (if you have Python installed) or via Anaconda.
1. **Install .NET Interactive**
   Open Anaconda Prompt and run the command to install the .NET Interactive global tool. (Anaconda Prompt is the method Anaconda officially recommends to avoid potential conflicts with other Python installations or software on your system)

### Quick Setup on Windows

Open Windows Command Prompt and run the following commands:

```
winget install Microsoft.DotNet.SDK.9
winget install Anaconda.Anaconda3
dotnet tool install -g Microsoft.dotnet-interactive
```

Open Anaconda Prompt and run the following command:

```
dotnet interactive jupyter install
```

After completing these steps, you can start creating and running .NET notebooks in Jupyter Notebook.
