# Covering Housing Workshop at the Nieman Foundation 

## Before and after images

Open up [JuxtaposeJS](https://juxtapose.knightlab.com), an easy-to-use tool built by Northwestern's Knight Lab. We'll be using two screenshots of maps created for the Urban Institute's [Our Changing City: Housing](http://apps.urban.org/features/OurChangingCity/housing/index.html) project about Washington, D.C. 

Click "Make a slider now."

In left image, paste in this url: http://www.storybench.org/nieman/ui2003.png

In right image, paste in this url: http://www.storybench.org/nieman/ui2013.png

Delete Apr. 2005 and Nov. 2013 labels.

Click "Update preview."

![Urban](http://www.storybench.org/nieman/ui2013web.png)

## Introduction to mapping

Using [Google My Maps](https://www.google.com/mymaps), we’ll quickly map some addresses and then plot "shapefiles" of public housing in New York City.

### Mapping points

Download point data of lead kit requests [here](https://drive.google.com/file/d/0B56vzj8m6JInVUVYSnpmelpQUU0/view?usp=sharing). 

This is pulled from **NYC 311 data** found at [opendata.cityofnewyork.us/](http://opendata.cityofnewyork.us/). 

311 service complaints data, by the way, is a huge list, with everything from rodent complaints to noise complaints to illegally parked cars. 

So, we will filter it down [here](https://nycopendata.socrata.com/Social-Services/311-Service-Requests-from-2010-to-Present/erm2-nwe9/data) in the Filter tab by **complaint type: lead, status: open, created date: after 2.1.2017.** Then we'll download a CSV in the Export tab.

Import this [CSV](https://drive.google.com/file/d/0B56vzj8m6JInVUVYSnpmelpQUU0/view?usp=sharing) into [Google My Maps](https://www.google.com/mymaps). 
Style the lead kit request points by selecting "uniform" and then customize their icon and color.

### Mapping buildings/shapes

Download **shapefiles of NYC public housing** [here](https://data.cityofnewyork.us/api/geospatial/i9rv-hdr5?method=export&format=KML).

This is pulled from [Data.gov](https://catalog.data.gov/dataset?q=%22nycha%22+%22new+york%22&sort=views_recent+desc&as_sfid=AAAAAAU1g8W83MzHP5UveS-1h5BDNFZFvTZMJKi1B7tXi1JDtoKB7zh-Twe4loPvwDf9Ihel2O_RGSktN_jf8681CrEnLnAFvpsp7Ns0EIfjfwKj_7QICDqd4x9vQzTmImdGkEQ%3D&as_fid=9ce1c7f7e75a6fb29a87a0fb90cc71380565ba01&ext_location=&ext_bbox=&ext_prev_extent=-142.03125%2C8.754794702435618%2C-59.0625%2C61.77312286453146) where we did a search for "nycha" "new york."

Click on KML below Map of NYCHA Developments. It will bring you to [this page](https://catalog.data.gov/dataset/map-of-nycha-developments/resource/bc435fbe-04a4-43d8-9be5-130f9acf2757). Click Download in top right.

(KML is essentially a list of shapefiles. Shapefiles are polygons – or, more specifically, a list of coordinates outlining a polygon. A triangle has three coordinates. A square has four. A state like Colorado will have fewer than Rhode Island.) 

Import the [KML file](https://data.cityofnewyork.us/api/geospatial/i9rv-hdr5?method=export&format=KML) into [Google My Maps](https://www.google.com/mymaps). 

Style the public housing buildings by "borough."

Set labels as “development.”

![Alt text](http://www.storybench.org/nieman/mymaps.png)


