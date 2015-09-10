
# QTabFrameworkExample

This is an example application for the QTabFramework. The QTabFramework is a Qt powered framework for applications with various tabbed widgets. QTabFramework is an extension of the QMainWindow class, which allows tabs to be arbitrary placed within main window or within floating child windows.

![QTabFrameworkExample](/QTabFramework.png)

## Dependencies

* *mare* - A Visual Studio solution file generator.
* *qt* - The Qt sources.
* *libcppqt* - The header files for the Qt libraries, which are normally composed by one of Qt's build scripts.
* *QTabFramework* - The QTabFramework library.

## Usage

### Windows

* Create a working copy of the QTabFrameworkExample repository.
* Initialize submodules.
* Call `generate.bat`. This will compile *mare* and generate solutions files for Visual Studio 2013. You can use `generate.bat --vcxproj=20XX` to generate solution files for another version.
* Open the solution file and compile and work with QTabFrameworkExample within Visual Studio.

### Linux

* Create a working copy of the QTabFrameworkExample repository.
* Initialize submodules.
* Call `generate`.