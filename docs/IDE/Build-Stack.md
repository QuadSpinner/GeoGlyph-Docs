## Build Stack
> Build Stack helps you record the build information of the world you are working on. This information gets added to the build stack when you build using the **Build World** button or **Build to current device** on the top right GeoGlyph toolbar. Build stack records build time taken by each device. It also keeps the record of the build profile which includes information like World resolution, world height & width.

## Build Stack viewer 
> Build Stack viewer helps you view the build stack data, it can be accessed by **Build Stack** menu item under GeoGlyph Menu or **Build Stack** button on the top right GeoGlyph toolbar.

### Build Stack toolbar
> When you build a world in WM 3, the build stack also records the data of the world which includes details of each devices and its values. Using the Build stack toolbar, you can mark two builds and compare them to see the changes.

> **Mark A** and **Mark B** button marks the builds for comparison. When two builds are marked, comparison viewer becomes visible. In this viewer you can see the devices list with values for both the selected builds side-by-side. This viewer helps you compare value of each devices. The differences in the values are marked in color to make comparison easier. **Clear A/B Selection** button clears the files marked earlier. You can close the comparison viewer by unchecking the **Compare A/B** button.

> you mark two builds which are not built in WM3, you will get following error message "Devices.txt missing".

### Build Stack Tree view
> Left side of the Build stack viewer has tree view with projects in build stack. Each tree view item represents the project and each children of the project is the build record which is shown by build date and time. When you select a particular record, you can see the details of that build on the right pane of the dialog. Right clicking any build record gives you a option **Show in Explorer**, it opens the folder location where these build details are stored.

### Build Stack right pane
> Build stack right pane has three sections: 
- Build data shown in three tabs
- Output preview of the build
- Chart representation of the data

### Build Tab
> Shows the list of the devices in the build along with the time taken by each device to build.
### World Tab
> If the build is done in WM3, This tab shows the devices list in XML format along with the values of each property of the device.
### Build Profile
> Shows the details of the build profile such as World Resolution, World height and width, terrain maximum elevation and terrain base elevation

### Output preview
> It shows the 3D preview of the build output. In this section there is a button **Edit Build Comments** which opens a dialog and allows to edit the existing comments of that particular build. If a build record has comment, it will be visible with the build record in the tree view.

### Chart
> This section shows the pie and donut chart drawn based on the build record. The line chart shows the time taken by each device.



