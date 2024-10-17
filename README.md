# labtools
Simple space to share

AppEEARS: This code can download images from AppEEARS. Image products are not limited to Landsat, but the range of products given in [product list](https://appeears.earthdatacloud.nasa.gov/products)  
The user should adjust location coordinates, date range, products, and bands should be adjusted accordingly. 
Author- Y A Marambe

M2M API: USGS EROS image downloading  
This program will download images from M2M API from USGS. The code is setup to download images on ARD grid, for given corner coordintes from a csv file. However, user can change these parameters as suitable
Adopted and Modified - Y A Marambe

Quality control GUI: DYCE Lab tool
This program contains two sections to give the flexibility to modify this program for other projects' QC workflows.  

Section 1: Create image views to display within the QC GUI widget. This specific example can take tree-labels included in point-shape files as time series information and join that information to the tree canopy shape layer. The code will drop additional images and adjust the view window based on the number of available images. Then, it will draw the canopy layers on NAIP high-resolution images as a time series in a single view.

Section 2: This code generates a GUI widget with different functionalities for QC implementation. 
Available functions: Next, back, QCflags(Approve, Drop, Redo), confidence level (High, low), Comment box
