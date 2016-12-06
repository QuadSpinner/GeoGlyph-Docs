## Prerequisites

- World Machine 64-bit Standard or Professional (2.3.7,3.0.0.3, 3.0.0.11)
- Windows 7 or higher
- Microsoft .NET Framework 4.6 or higher
- Latest Drivers for CPU and GPU to utilize OpenCL

## Download
1. Sign into your account on the [QuadSpinner Store](http://store.quadspinner.com).
1. Download the latest build. This is an MSI file *GeoGlyph_2.0.xxx.yyy.msi* (where xxx.yyy is a version number).
1. Download your license key if you have purchased GeoGlyph.

## Install
The new installer provides a fast, efficient, and automated method of installing GeoGlyph 2.0. 

1. Ensure World Machine is not running. If GeoGlyph 1.0 was installed, please uninstall it first (see below).
2. Download and run the MSI file.
3. Setup will attempt to automatically detect the locations of the World Machine installation(s), as well as the World Machine Documents and Macro paths. Check to see if the paths are accurate. If not, you may need to choose them manually. See below for help with the paths.
4. Choose the components you wish to install. In most cases, the default selection is recommended. You can also review the destination paths and modify them as needed.
5. Proceed with installation.
6. Once installation is complete, run GeoGlyph 2 from the Start Menu or Desktop.

## Troubleshoot path detection
The installer can have difficulty detecting the correct paths, especially with World Machine Standard Edition. If this happens, the installer will show you a warning dialog saying that paths were not detected properly. To install GeoGlyph successfully in this case, you will have to point GeoGlyph to the correct paths.

Use the **drop-down icon** next to each component, select "Install Locally". Then select the item in the list, and click the **Browse** to locate the correct path for that component.

[!TIP]

If you have trouble selecting the paths, use the Path Guide below, and [watch this video showing the correct process](https://vimeo.com/193373735).

[TIP!]

### Path guide
- World Machine 2.3.7 is typically installed in *C:\Program Files (x86)\World Machine 2 Professional*
- World Machine 3.0.x builds are typically installed in *C:\Program Files (x86)\World Machine Professional Edition Development Version*
- World Machine Documents are typically installed in *C:\Users\[YOU]\Documents\World Machine Documents*
- World Machine Macros are typically installed in *C:\Users\[YOU]\Documents\World Machine Documents\Macros*. 

[!IMPORTANT]

Sometimes Macros may be installed to *C:\Program Files (x86)\World Machine 2 Professional\Macros\*. If so, you will need to change it to the path above, or any other user-writable path that as no read/write restrictions. To change the path, go to ```World Commands menu > Preferences > Paths``` in World Machine.

[IMPORTANT!]

## Compatibility with GeoGlyph 1.0

Please see [this link](6666) for information on how to use GeoGlyph 1.0 macros in GeoGlyph 2.0. Ideally, you should [uninstall GeoGlyph 1.4 from the GeoGlyph Manager](6666) before installing GeoGlyph 2.0.
