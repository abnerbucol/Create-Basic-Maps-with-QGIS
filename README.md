# Create-Basic-Maps-with-QGIS
This document describes a stepwise process how to plot basic locator maps that can be used in papers and presentations using the free GIS software (QGIS). Steps will involve: 1) downloading and setting up the QGIS software; 2) downloading and uploading the basemap; 3) uploading waypoints; 4) editing; and exporting options.
## A. Setting up Software
Download the latest version of QGIS that is compatible with your computer. 
Link to QGIS [here](https://qgis.org/en/site/forusers/download.html)
**Note:** If you encounter compatibility issues in your computer with the latest version,
 you can use an earlier version (i.e. v3.16; Hannover).
## B. Getting your data ready

1. Get GPS coordinates for your site(s). You can obtain coordinates using GoogleEarth 
(to be exported as KMZ file) or directly from a GPS device (as GPX file). 

or 

2. If you have coordinates already in CSV file, you can also upload the file in GoogleEarth,
 save as “My Places” and export as KMZ file.  

There are a number of online file converter such as [gpsvisualizer](https://www.gpsvisualizer.com/convert_input).
 Just upload the KMZ file online and download the converted file (GPX).
 It would be easier if you rename the downloaded GPX file (eg species name).

## C. Generate the Map

1. Upload the Basemap shapefile. 

In this example, we will be using the Philippine basemap extracted from the GADM database [www.gadm.org](https://gadm.org/download_country.html) version 4.1 (© 2018-2022 GADM). 
The coordinate reference system is longitude/latitude and the WGS84 datum. 

***They can be used for non-commercial purposes only. It is not allowed to redistribute these data, or use them for commercial purposes, without prior consent***


Add the basemap as raster layer. Click Layer>Add Layer>Add Vector layer or **CTRL+SHIFT+V*** 

Choose File then click on the Source to Add the shapefile (eg. gadm41_PHL_0 for Philippines w/o subnational boundary) saved in your local computer. Then Click ADD. 

**Note:** Avoid uploading the entire zipfile (too bulky) but extract the files and save into a folder for easier uploading.
In the Layer section, Click the button showing the shapefile/Raster Layer to edit color and other properties (eg opacity).
 Example, choose fill color and then Click Apply. 
 In the right side of the window you will also see editing options under Layer Styling.
2. Add another layer, this time the GPX file saved in your local computer.

Click the button on the left side “waypoints” and adjust the color and size of the marker as shown.
Open the Layout Manager to finalize the Map and add legend, grids, and coordinates.
**Click Create**

In the Layout manager, you can adjust the image size and add text labels and decorations such as North Arrow, Scale, Gridlines, border, and coordinates. 
3. Export Image according to your preference (Image, PDF). I prefer tiff file so its easier to edit and enhance if necessary.
Then set the desired resolution by adjusting “dpi” (the higher the better) under Export Options. Make sure to click Crop to Content.  
