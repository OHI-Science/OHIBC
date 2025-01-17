# Ocean Health Index British Columbia: /prep/hab_cs_cp/v2017

This folder describes the methods used to prepare data for Habitats, Carbon Storage, Coastal Protection for the OHIBC assessment.

More information about this goal is available [here](http://ohi-science.org/goals).

## Data management and citation info

Our [data managment SOP](https://rawgit.com/OHI-Science/ohiprep/master/src/dataOrganization_SOP.html) describes how we manage OHI global data, including a description of the file structure.

Please see our [citation policy](http://ohi-science.org/citation-policy/) if you use OHI data or methods.

Thank you!

## Directory information

This directory includes R/Rmd scripts and .html files, as well as subdirectories that include metadata, intermediate data, figures, and output layers for the indicated assessement year (i.e., the year the assessment was conducted).  The most current year represents the best available data and methods, and previous years are maintained for archival purposes.

## OHIBC: land use raster prep

* __Rmd file:__ https://github.com/OHI-Science/ohibc/blob/master/prep/hab_cs_cp/v2017/1_data_prep_landuse_rasters.Rmd 
* __HTML file:__ https://rawgit.com/OHI-Science/ohibc/master/prep/hab_cs_cp/v2017/1_data_prep_landuse_rasters.html

### Summary:

Merge landuse rasters, convert to BC Albers projection, and crop to BC extents

-----

## OHIBC: Habitat goals - saltmarsh and coastal forest layers prep

* __Rmd file:__ https://github.com/OHI-Science/ohibc/blob/master/prep/hab_cs_cp/v2017/2_data_prep_hab_sm_cf.Rmd 
* __HTML file:__ https://rawgit.com/OHI-Science/ohibc/master/prep/hab_cs_cp/v2017/2_data_prep_hab_sm_cf.html

### Summary:

Prepare existing habitat layers (salt marsh and forest raster land use raster) for HAB, CP, CS goals for OHIBC assessment.  For CP, calculate values based on exposure, elevation, and protective potential weighting as required for different protective habitats.  For CS, calculate values based on carbon storage potential.

Assessment areas for both habitats will be limited to the coastal watersheds, i.e. BC subwatersheds that intersect a 1 km buffer from the coastline.  For coastal protection, these will further be limited by an exposure band only 2 km wide.

-----

## OHIBC: Habitat goal - EBSA and soft bottom layer prep

* __Rmd file:__ https://github.com/OHI-Science/ohibc/blob/master/prep/hab_cs_cp/v2017/3_data_prep_hab_ebsa_sb.Rmd 
* __HTML file:__ https://rawgit.com/OHI-Science/ohibc/master/prep/hab_cs_cp/v2017/3_data_prep_hab_ebsa_sb.html

### Summary:

Create habitat info layer for EBSAs - ecologically and biologically significant areas - and soft bottom habitats.  The goal will be calculated based upon trawl pressure in each habitat type.

In addition, this will create a layer to represent the industry/ENGO trawl management agreement that was implemented in 2012 to reduce impacts of bottom trawling on deep water coral and sponge habitats.

-----

## OHIBC: Carbon Storage and Coastal Protection goals

* __Rmd file:__ https://github.com/OHI-Science/ohibc/blob/master/prep/hab_cs_cp/v2017/goal_model_cp_cs.Rmd 
* __HTML file:__ https://rawgit.com/OHI-Science/ohibc/master/prep/hab_cs_cp/v2017/goal_model_cp_cs.html

### Summary:

Pull data layers for Salt Marsh and Coastal Forests to calculate Howe Sound goals: Coastal Protection, Carbon Storage

-----

## OHIBC: Habitats goal prep

* __Rmd file:__ https://github.com/OHI-Science/ohibc/blob/master/prep/hab_cs_cp/v2017/goal_model_hab.Rmd 
* __HTML file:__ https://rawgit.com/OHI-Science/ohibc/master/prep/hab_cs_cp/v2017/goal_model_hab.html

### Summary:

Process individual habitat scores for each of the habitats in HAB subgoal.  Combine scores to determine overall status and trend for HAB subgoal.


