This Project can edit your Death Must Die Saves. Adding gold, modifying items with any affix and any value

Original Project: https://github.com/DenislavLitsov/DeathMustDieSaveEditor

Save file location: https://steamdb.info/app/2334730/ufs/

I will keep my fork until the original project is updated

## How to Build the Executable

To build the application into a single executable file, follow these steps:

1.  **Install the .NET 8.0 SDK**: Make sure you have the .NET 8.0 SDK installed on your machine. You can download it from the [official Microsoft website](https://dotnet.microsoft.com/download/dotnet/8.0).

2.  **Open a Terminal**: Navigate to the root directory of the project (where this README is located).

3.  **Run the Publish Command**: Execute the following command to build the self-contained executable:

    ```bash
    dotnet publish DeathMustDieSaveEditer.WPF/DeathMustDieSaveEditor.WPF.csproj -c Release -r win-x64 --self-contained -p:PublishSingleFile=true -p:IncludeNativeLibrariesForSelfExtract=true
    ```

4.  **Locate the Executable**: After the build completes successfully, you can find the executable at:
    `DeathMustDieSaveEditer.WPF/bin/Release/net8.0-windows/win-x64/publish/DeathMustDieSaveEditor.WPF.exe`
