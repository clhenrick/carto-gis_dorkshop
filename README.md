## Cartography Dorkshop
Parsons The New School for Design
9/29/2013
Chris Henrick

This Dorkshop is intended to introduce some general topics relating to Cartographic Design,
Geographic Information Systems (GIS), and open-source web-mapping. My intention is to cover
some basic areas within the disciplines and give you some hands on experience with tutorials.
Depending on what we are able to cover and how the audience feels about the material this
dorkshop may be the first in a series. My goal is to inform the audience how we as designers
can have greater control over map design using Adobe Illustrator and some open-source tools.

In this folder you will find some tutorial files for learning the pen tool in Adobe Illustrator.
Knowing the Pen tool is key for creating, editing, and styling vectors in Illustrator,
ie: for drawing maps the fast and dirty way and for creating SVG icons you may want to use in 
your online web maps. There is also a sample template you may use for creating a map in illustrator.
This template comes with some layers to help keep your map organized and some graphic and character styles to use.
Additionally there are files from the National Park Service containing public-domain symbols and patterns,
as well as a world locator map.

In the images folder you will find a screen shot of Google Maps I will be using for the first tutorial to
create a way finding map in Adobe Illustrator. Having basic knowledge of Adobe Illustrator is not a requirement
but strongly suggested if you would like to follow along with the first tutorial in the dorkshop.

If you'd like to participate in the GIS and web-mapping tutorials in the second half please install the following
software ***prior to*** the dorkshop:


### QGIS (open-source cross-platform Geographic Information Systems desktop app)
  -For mac OS X:
     http://www.kyngchaos.com/software/qgis
    *important! > Be sure to install the GDAL Complete 1.10 framework before running the QGIS dmg
   
  -For windows, linux, ubuntu, etc:
    http://www.qgis.org/en/site/forusers/download.html
   
### Tile Mill (open-source cross-platform Web Mapping Design Studio desktop app)
  -For Mac Os X, Ubuntu, Windows:
    http://www.mapbox.com/tilemill/
    
  -then go to help > installation
  
### MapBox (cloud-based web-map hosting, we will use this in conjunction with TileMill)
  -sign up for a free account online @
    http://mapbox.com
    
### Additionally, if you'd like to try running GDAL on the command-line (I recommend having
prior knowledge of working with the command line), it is available in the Terminal App (Mac OS X 
and on similar Shells for other linux based systems such as Ubuntu), 

Following the installation of QGIS copy and paste the following code into the Terminal App:

  echo 'export PATH=/Library/Frameworks/GDAL.framework/Programs:$PATH' >> ~/.bash_profile source ~/.bash_profile

Then double check that GDAL is in your environment PATH by running the command:
  
  gdalinfo --version

You should get back something like:

  GDAL 1.10.0, released 2013/04/24


### I plan on trying to not spend time helping people set up these tools during the dorkshop so 
please come prepared with them installed prior to attending. They should be fairly straightforward
to install and setup if you follow the directions on the mentioned webpages. Thanks!


