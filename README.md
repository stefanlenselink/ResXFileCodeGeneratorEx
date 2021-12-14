ResXFileCodeGeneratorEx2022
===========================

A VS2022 port of the ResXFileCodeGeneratorEx extension.

Original extension developed by Dmytro Kryvko (DMK Software).  More information can be found [here](http://www.codeproject.com/Articles/13830/Extended-Strongly-Typed-Resource-Generator)

The original extension has been updated for multiple versions of Visual Studio over the years.  Currently this version for VS2022 is not published in the VS Gallery.  

Previous versions can be found at

* [VS2017](https://github.com/cpaton/ResXFileCodeGeneratorEx/tree/vs-2017)
* [VS2015](https://marketplace.visualstudio.com/items?itemName=Paruz.ExtendedStronglyTypedResourceGenerator)
* [VS2013](https://marketplace.visualstudio.com/vsgallery/16d24be3-6400-4a43-b946-766e41aca4bd)
* [VS2012](http://visualstudiogallery.msdn.microsoft.com/18e29594-3527-4bbb-986a-52b610b77e23) ([Source Code](https://github.com/EZSlaver/ResXFileCodeGeneratorEx2012/))


# Installing
The original project included an MSI, but installers are no longer supported in VisualStudio.

Open Visual Studio and open the ResXFileCodeGeneratorEx.sln. It is grouped into Deployment and Design folders. Note that VS-2022 is 64-bit, so all modules must be translated with "AnyCPU" or "x64". Build the solution. This will output the files to src\ResXFileCodeGeneratorExPackage\bin\Debug. Open the ResxCodeFileGeneratorEx2022.vsix file in that folder. This will register the generator with Visual Studio.
