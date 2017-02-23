## General

### Sky Colors
This is the default Sky Color shown in the Editors.

### Default Sun
This is the default position of the sun in the Editors.

### WIP recorder screenshot interval
This option lets you set the interval (in seconds) at which the WIP recorder takes screenshot of the work area. The tooltip for the slider estimates how many files will be generated, how many seconds of video they are worth, and how much disk space it will consume.

### Icon Sets
Select between visual and typographic icons for GeoGlyph and World Machine elements.

### Interface Options
- *Show large icons in Toolbox* - Toolbox popup and sidebar show larger icons.
- *Hide less frequently used tabs* - The Macros, Parameters, Flow, and Curves tabs are hidden in the toolbar. They can still be accessed through Search or the Toolbox.
- *Use color accents for tabs* - Colored accents are added to tabs for easier recognition
- *Show Expanded buttons in Toolbar* - Commonly used buttons such as `Save`, `Device View`, and `Build to Current` are expanded for easier access.

## Renderer

### Parallel Processing
GeoGlyph can utilize OpenCL devices on your computer (both CPU and GPU) when available.

- **Disable OpenCL** - Without OpenCL, direct CPU processing will be performed. Use this if you are troubleshooting or have problems with OpenCL.
- **All Devices** - Use all OpenCL devices. This is useful ONLY if you have many, similarly powerful devices.
- **Best Device Only** - This is the recommended option. GeoGlyph will pick the device with the best score.

## Paths

### World Machine Paths
This option lets you set the path for World Machine installations for WM 2.3.7, WM 3.0.3, WM 3.0.11. It also lets you set the path for World Machine Documents and Macros. Changing any of the values in this section will require you to restart GeoGlyph.

If the Path for any World Machine installation is changed, you will need to manually move the GG###.dll and GGLib.dll files from the plugins folder. For more accurate results, we recommend reinstalling GeoGlyph if any World Machine path is changed.

## Notifications

When turned on, GeoGlyph will send a notification email to the specified email address. You can specify multiple addresses by separating them with a `,`.

Optionally, you can also choose to attach the 3D preview of the finished build.

Notifications are sent through a secure SSL encrypted connection. Contents of the emails are not stored except during transmission. We do not store or use the contents of the notifications except for transmission.

[!NOTE]
Only available in the Professional Edition.
[NOTE!]

## Privacy

### Collect anonymous usage data to help improve GeoGlyph
Usage data - such as statistics, hardware configuration and installation paths - helps us improve GeoGlyph. We encourage you to participate to help us create a better software for you.

We do not collect or use personal information in this process. Each week, GeoGlyph will send a few MB of usage data.