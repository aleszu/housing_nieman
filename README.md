# Covering Housing [Workshop](http://nieman.harvard.edu/sites/covering-housing/) at the Nieman Foundation for Journalism at Harvard 
March 18, 2017

## Presentation [here](https://docs.google.com/presentation/d/1HPN60v0WZVv483drKZ41_dEfrXMxj3bSi-hnYMiAARE/edit?usp=sharing)

## Before and after images

1. Open up [JuxtaposeJS](https://juxtapose.knightlab.com), an easy-to-use tool built by Northwestern's Knight Lab. We'll be using two screenshots of maps created for the Urban Institute's [Our Changing City: Housing](http://apps.urban.org/features/OurChangingCity/housing/index.html) project about Washington, D.C. 

2. Click "Make a slider now."

3. In left image, paste in this url: http://www.storybench.org/nieman/ui2003.png

4. In right image, paste in this url: http://www.storybench.org/nieman/ui2013.png

5. Delete Apr. 2005 and Nov. 2013 labels.

6. Click "Update preview."

![Alt text](http://www.storybench.org/nieman/ui2013web.jpg)

## Introduction to mapping

Using [Google My Maps](https://www.google.com/mymaps), we’ll quickly map some addresses and then plot "shapefiles" of public housing in New York City.

### Mapping points

7. Download point data of lead kit requests [here](https://drive.google.com/file/d/0B56vzj8m6JInVUVYSnpmelpQUU0/view?usp=sharing). 

8. Import this [CSV](https://drive.google.com/file/d/0B56vzj8m6JInVUVYSnpmelpQUU0/view?usp=sharing) into [Google My Maps](https://www.google.com/mymaps). 

9. Style the lead kit request points by selecting "uniform" and then customize their icon and color.

#### *What is this data?*

(This is pulled from **NYC 311 data** found at [opendata.cityofnewyork.us/](http://opendata.cityofnewyork.us/). 

311 service complaints data, by the way, is a huge list, with everything from rodent complaints to noise complaints to illegally parked cars. 

So, we will filter it down [here](https://nycopendata.socrata.com/Social-Services/311-Service-Requests-from-2010-to-Present/erm2-nwe9/data) in the Filter tab by **complaint type: lead, status: open, created date: after 2.1.2017.** Then we'll download a CSV in the Export tab.)

### Mapping buildings/shapes

10. Download **shapefiles of NYC public housing** [here](https://data.cityofnewyork.us/api/geospatial/i9rv-hdr5?method=export&format=KML).

11. Import the [KML file](https://data.cityofnewyork.us/api/geospatial/i9rv-hdr5?method=export&format=KML) into [Google My Maps](https://www.google.com/mymaps). 

12. Style the public housing buildings by "borough."

13. Set labels as “development.”

#### *What is this data?*

(This is pulled from [Data.gov](https://catalog.data.gov/dataset?q=%22nycha%22+%22new+york%22&sort=views_recent+desc&as_sfid=AAAAAAU1g8W83MzHP5UveS-1h5BDNFZFvTZMJKi1B7tXi1JDtoKB7zh-Twe4loPvwDf9Ihel2O_RGSktN_jf8681CrEnLnAFvpsp7Ns0EIfjfwKj_7QICDqd4x9vQzTmImdGkEQ%3D&as_fid=9ce1c7f7e75a6fb29a87a0fb90cc71380565ba01&ext_location=&ext_bbox=&ext_prev_extent=-142.03125%2C8.754794702435618%2C-59.0625%2C61.77312286453146) where we did a search for "nycha" "new york."

Click on KML below Map of NYCHA Developments. It will bring you to [this page](https://catalog.data.gov/dataset/map-of-nycha-developments/resource/bc435fbe-04a4-43d8-9be5-130f9acf2757). Click Download in top right.

KML is essentially a list of shapefiles. Shapefiles are polygons – or, more specifically, a list of coordinates outlining a polygon. A triangle has three coordinates. A square has four. A state like Colorado will have fewer than Rhode Island.) 

![Alt text](http://www.storybench.org/nieman/mymaps.png)

### Mapping boroughs or neighborhoods

14. Download **shapefile of NYC boroughs** [here](https://drive.google.com/file/d/0B56vzj8m6JInZVRkU1dLRWZ6LTQ/view?usp=sharing).

15. Upload the KML of NYC boroughs to Google My Maps.

16. Style by "BoroName."

17. Download **shapefile of NY neighborhoods** [here](https://drive.google.com/file/d/0B56vzj8m6JInRFd5N0p6Qmd1RUk/view?usp=sharing). Upload to Google My Maps.

#### *What is this data?*

The NYC boroughs KML file was converted from a shapefile zip I downloaded from NYC.gov [here](https://www1.nyc.gov/site/planning/data-maps/open-data/districts-download-metadata.page). I converted it using [My Geodata Converter](https://mygeodata.cloud/converter/). 

The NY neighborhoods shapefile was found on [Zillow](https://www.zillow.com/howto/api/neighborhood-boundaries.htm) and converted using [My Geodata Converter](https://mygeodata.cloud/converter/) into KML.

![Alt text](http://www.storybench.org/nieman/mygeodata.png)


