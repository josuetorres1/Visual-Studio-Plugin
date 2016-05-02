# Visual-Studio-Plugin
Visual Studio Plugin to mix default and custom content

Issue:
Several resources files have to be built by mixing default content, stored in the .resx file, and custom content, stored in a SQL DB. 

Explanation:
One the properties of the resx file is the 'Custom Tool'. 
By default the field is empty and the .resx file uses the default tool provided by the Visual Studio SDK (ResXFileGenerator) to build the .resx files once the .sln compiles.

In order to achieve what is needed the default tool to generate the .resx files have to be replaced by a custom tool.
So, this repo is about what I did to create this tool using VS 2012 SDK.

Included a picture (VSPlugin.JPG) of the custom tool applied to the Confirmation.resx resource file.







