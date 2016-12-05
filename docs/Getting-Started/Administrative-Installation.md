[!WARNING]
Administrative installation is meant for IT Administrators and experienced power users only
[WARNING!]

GeoGlyph's MSI installer is designed to detect and install GeoGlyph dependencies into the appropriate World Machine installations. If the target computer has multiple versions of World Machine, a standard installation is recommended.

For a remote/command line installation, the following variables must be provided to the MSI package.

## Paths
- ```TARGETDIR``` The installation directory for GeoGlyph 2. Typically `~\Programs Files\QuadSpinner\GeoGlyph 2`.
- ```WM237``` The installation directory for World Machine version 2.3.7.
- ```WM303``` The installation directory for World Machine version 3.0.0.3.
- ```WM3011``` The installation directory for World Machine version 3.0.0.11.
- ```DOCS``` World Machine's Documents directory. Typically `%USERDOCS%\World Machine Documents`.
- ```MACROS``` World Machine's Macros repository. Typically the `Macros` folder inside World Machine Documents.

[!IMPORTANT]
The DOCS and MACROS folder must be unprotected paths that all users have read/write access to.
[IMPORTANT!]

## Conditions
Set these to 0 or 1 as required.
- ```IS237``` Install for World Machine version 2.3.7.
- ```IS303``` Install for World Machine version 3.0.0.3.
- ```IS3011``` Install for World Machine version 3.0.0.11.

## Prerequisites
1. World Machine 64-bit Standard or Professional (2.3.7, 3.0.0.3, 3.0.0.11)
2. Windows 7 or higher
3. Microsoft .NET Framework 4.5.1 or higher
4. Latest Drivers for CPU and GPU to utilize OpenCL

## Example Command Line
> `
> msiexec.exe -i "C:\Path\To\GeoGlyph.msi" 
> IS236=1 
> WM236="C:\Program Files (x86)\World Machine 2 Professional\" 
> DOCS="Path_to_WM_Docs" 
> MACROS="Path_to_Macros_Folder" 
> MACROPROTECTED=0
> `


## License Management

At the moment, licenses need to be [installed manually](6666). In a near future update, we will add license deployment to command line installations.