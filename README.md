<h2>Cornell University Sustainable Design</h2>
<h3>2012 National Geothermal Student Competition, sponsored by the Department of Energy/Office of Energy Efficiency and Renewable Energy</h3>

This library contains GIS data and scripting for Cornell University Sustainable Design's entry for the 2012-13 National Geothermal Student Competition. This includes maps and datasets that are relevant to geothermal development of the Snake River Plain in southern Idaho.

<h4>Accessing the Library</h4>
To use this library, you can use Git (a type of version-control software) to both download and contribute to the library. You can also download a static, compressed version (under "Downloads").

To access this library using Git, use the following command in your operating system's terminal:

<pre>git clone https://github.com/cusd/cusd-ngsc.git</pre>

If you want to contribute to the project, please make a "pull request" by clicking the button above. There is extensive documentation available on Github to explain how Git, cloning, and pull requests work.

<h4>Contents</h4>
This library contains the following elements:
<ul>
<li><strong>Maps</strong> and GIS datasets, compatible with ArcGIS and in some cases Google Earth</li>
<li><strong>Data</strong>, typically in *.dbf format, which you can open in the newest version of Microsoft Excel or Access</li>
<li><strong>Utilities</strong>, such as DNR GPS and kml2shp, included for your convenience.</li>
</ul>

<h4>Opening the Map</h4>
In the <em>maps</em> folder, the *.mxd files are openable in ArcGIS, and include all relevant layers. The latest version is ngsc-improve.mxd -- we're ironing out some kinks and will consolidate to one mxd file shortly.

The individual layer files are stored, often in multiple formats, in the relevant folders, such as "faults" or "gravity". Anything containing an *.shp file (shapefile) can be opened in ArcGIS. Anything containing a *.kmz or *.kml file can be opened in Google Earth.

Either DNR GPS or kml2shp can convert to SHP. KMZ files can be opened in WinZip or similar extraction utilities, and contain a KML file inside.