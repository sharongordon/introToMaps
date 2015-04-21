# introToMaps
Exploring interactive web maps


//Issue: A user wants to be able to query some basic watershed information based on an area of interest (AOI).  Specifically, they are interested in 3 data-sets: watershed boundaries, county boundaries and stream length.  Currently, the user goes through a tedious process to find, query and save the data they are interested in.  They have to find each data source, zoom into the correct extent using varying user interfaces, and then manually query and aggregate the results through a manual process. This process limits the type of user who can fetch common data to a few people how have been trained in the process.  

//Product vision:  I would like to build a product that allows a user to select an area of interest (AOI) on a single map and have a simple summary table returned to them. This would be a simple one page design.  The landing page would have a map, a second tab would have an about, how to and contact.  This product is streamlining one common workflow where the user retrievers the following data within an AOI:  the number of basins and sub basins, the number of counties, and the length of streams.

//Data sources:  All the data is public.  Watershed boundaries and stream lines are provided in NHD plus (USGS) and the county boundaries are provided through the census data.  Stream length is a derived data set based on the length attribute of the stream lines.  All data is vector based (lines and polygons).  

//Risks:  It is not clear at this time whether or not the geospatial analyst tools required to be able to make something like this work exists in one of the various web map api’s.  If these tools do not exist, then I will look at alternative methods of prepping the data before the user does spatial queries on it.  In addition to this, there a risk of the data being to large or complicated to work with for this project.  In which case, I will change the scope so that the same type of functionality is completed with a smaller dataset. 

//Development plan:

Iteration 0 -create wireframes, explore map api that is able to meet all the basic requirements, setting up a basic bootstrap web page where the map will be embedded. (2 weeks)
Iteration 1 -embed a simple map with no customization or functionality.  This step includes setting up github, an api token, and map canvass (1 week)
Iteration 2 -add a simple layer to the map, set the extent of the map view, add minimal user interactivity by allowing the user to click on a feature to retrieve basic information (1 week)
Iteration 3 -user draws a polygon on layer (1 week)
Iteration 4 -overlay polygon and another feature to select for features within the area of interest (2 weeks)
Iteration 5 -add multiple layers that can be selected (1 week)
Iteration 6 -display the information that is returned some where on the page (2 weeks)
Iteration 7 -complete styling and finalize the page (2 weeks)


