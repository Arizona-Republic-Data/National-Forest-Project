# National Forest Project

The analysis and the data on this page were used to publish a USA Today Network project exploring special use permits for systems that divert or transport water on national forest land. 

# About the ipynb files

<b>Forest Check:</b> confirms that permits or easements exist in every continental National Forest admin area

<b>Final copy of analysis based on NF acreage:</b> Analysis on Forest to Faucet data to determine net change in runoff volume within the boundaries of national forests

<b>Permit_data_master_FS:</b> This code created from the original FOIA response the master permit file used in the searchable database, and for analysis of permits / easements within each forest

# About the data files
<b>original water use file.xslx:</b> Data in its original form sent to us from the National Forest Service, in response to our FOIA. 

<b>cb_2018_us_state_20m.zip:</b> Shapefile of state boundaries from the census

# Links to files not included 
<b>Forest to Faucet geodatabase:</b> https://usfs-public.app.box.com/v/Forests2Faucets

Forest Service researchers determined percentage change in average annual water yield using a climate model with a relatively ‘wet’ scenario. The researchers projected change based on a future with relatively low carbon emissions, and one with unlikely and extremely high emissions. 

Climate scientists typically use models to compare how the climate is likely to change under different amounts of environmental interventions. The Republic is showing the low-emissions model, which is considered to be fairly optimistic.

The Republic's watershed map reflects only one potential future and predicting precipitation comes with a lot of uncertainty.

Percentage change is based on average annual water yields from 1960 to 2015, compared to what is projected under this model from 2030 to 2049.   

<b>Forest Service Shapefiles:</b> https://data.fs.usda.gov/geodata/edw/datasets.php?xmlKeyword=boundaries

The Republic used the original, proclaimed boundaries of national forests shapefiles to identify watersheds that overlap or border land inside the boundaries of national forests. 

To estimate runoff changes within forests, the Republic calculated volumes within each selected watershed by multiplying the projected change in milimeters (provided by the Forest Service data) by the area of that watershed that existed within a forest. The Republic ran this by a couple watershed experts to ensure its accuracy. 

The calculation, for each watershed, looks like this: (this is all hypothetical)
 
<li>Watershed A has a mean annual water yield of 200 mm/yr

<li>It’s predicted to have a -5 percent change between 2010 and 2040 under the low emissions climate change scenario

<li>To get the millimeter change: 200*-5 = -10 mm

<li>Watershed A is 10,000 acres but 50 percent of it is in a national forest

<li>To get the volume change in acre feet between 2010 and 2040:

<li>-10/304.8 = -.033 feet

<li>.033 feet * 5,000 acres of NF land = -165 acre-feet change specifically in the national forest

The interactive watershed map found in the main story shows all watersheds that were in and around national forests. The volume change amounts in that map reflect the change for the whole watershed, regardless if only part of it overlapped with a forest. 
 
