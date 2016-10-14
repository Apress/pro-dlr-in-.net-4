-------------------------
Setting Up Code Examples
-------------------------

If you download and unzip the file that contains the code examples of this book, you will see the following file structure:

ProDLR
lib
       Antlr
       DLR
       …
src
       Examples
Chapter 1
Chapter 2
…

The Examples folder contains a subfolder for each chapter. You can find all of a chapter’s code examples in that chapter’s 
folder under the Examples folder. Most of the code examples depend on one or more software components. The lib folder has 
a subfolder for each of the software components used in this book. You will need to download those components and put the 
needed assembly files into the subfolders under the lib folder. Chapter 1 of the book will describe what you need to do to 
download the DLR assemblies and put them into the lib\DLR folder. For the other software components, I will describe how to 
set them up when we encounter them in the book. Throughout the book, I’ll assume that the ProDLR folder is placed under C:\. 
If you choose to place it in a different folder, then you need to substitute the path with your own whenever I refer to it 
in the book.

----------------------
Software Requirements
----------------------

For most of the examples in this book, you will need the following software to follow along:
• .NET 4.0 SDK: You can download this from Microsoft’s website and follow the instructions there to install it.
• Visual Studio 2010 Express: Although you don’t need to install this per se, it is highly recommended as it will 
make it a lot easier to follow along the code examples. The installation of Visual Studio 2010 Express also installs 
.NET 4.0 SDK. If you choose to install this component, then you don’t need to install .NET 4.0 SDK separately.
• DLR, IronPython and IronRuby: You can go to the DLR project website at CodePlex to download all of the three 
components in one bundle. At the time of this writing, the download page of the DLR CodePlex website provides only source 
code but no binaries. Chapter 1 will describe where to get the binaries and how to install them. 
 
DLR, IronPython and IronRuby can run on .NET 2.0. To do so, you will need to download different binaries from the 
IronPython and IronRuby websites. As we go through the installation of DLR, IronPython and IronRuby in Chapter 1, 
I will point out the binaries you need download if you want to use .NET 2.0 as the target platform. The code examples in 
this book are developed to run on .NET 4.0. Chapter 3 will show you how to develop DLR based applications that run on both 
.NET 2.0 and .NET 4.0.       

