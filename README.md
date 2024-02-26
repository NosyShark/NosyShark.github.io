# Nosy Whale
<br>
This GIS shows the distribution of endemic shyshark species in southern African waters. <br>
The chosen sharks are the Puffadder shyshark and the dark shyshark. There are two other endemic species, but they are very cryptic and not enough observations have been made on iNaturalist to include them in these maps. <br>

Code dataframes
"puffyshark" <- Puffadder shysharks from iNat - includes positional accuracy < 100, research grade observations, and latitude < 0; excludes latitudes that are NA <br>
"darkshark" <- same same but for dark shyshark observations <br>
"world_land" <- dataframe (sf) for differentiating between ocean and land <br>
"landsharks_ps" <- puffadder shyshark observations of sharks on land (to be excluded) <br>
"oceanshark_ps" <- puffadder shyshark observations in the ocean <br>
"landshark_ds" <- dark shyshark observations on land <br>
"oceanshark_ds <- dark shyshark observations in the ocean <br>
"loceanshark_ps" <- puffadder shyshark observations with link to iNat <br>
"loceanshark_ds" <- dark shyshark observations with link to iNat <br>

