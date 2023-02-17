"# AddingSimpleITKCSharp" 
Download the CSharp-win64-x64.zip file from github release
https://github.com/SimpleITK/SimpleITK/releases
(You might have to click show all assets)

Rename to be SimpleITK
Relocate to Modular_Projects\SimpleITK

In the project, top panel click 'Build' -> 'Configuration Manager'
Select active solution platform -> x64
Platform -> x64

Right click Rerefences -> Add Reference -> Browse -> SimpleITKCSharpmanged.dll

Right-click Project Name->Add Existing Item->Executable->Add Link->SimpleITKCSharpNative.dll

Click SimpleITKCSharpNative.dll -> Build Action -> Content. Copy to Outputdirectory -> Always

# Installing FellowOak?
NuGet -> fo-dicom
