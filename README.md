
# QTabFrameworkExample

This is an example of the QTabFramework.

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
* Open the solution file and compile and work with HelloQt within Visual Studio.

### Linux

* Create a working copy of the QTabFrameworkExample repository.
* Initialize submodules.
* Call `generate.bat`.