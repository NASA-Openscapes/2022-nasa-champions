<a align="left" href="https://github.com/nasa-openscapes/2022-nasa/"><img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" width="35px"></a>

# 2022 NASA Openscapes Champions Cohort

Welcome to the 2022 NASA Openscapes Champions Cohort! This is a Cohort for research teams using NASA Earthdata and transitioning workflows to the Cloud. This is part of NASA Openscapes: <https://nasa-openscapes.github.io>. Learn more about Openscapes and the Champions Program: <https://openscapes.org>. 

<img align="right" src="horst-champions-trailhead.png" width="450">  

## Cohort Agendas

We will meet as a Cohort via Zoom on five Fridays over two months for 1.5 hours each:  

- **Dates:** March 4, 18, April 1, 15, 29
- **Times:** 10:00-11:30 am Pacific Time
- **Location:** remotely, via Zoom


Agendas are accessible to Cohort participants in our [Cohort Google Drive Folder](https://drive.google.com/drive/folders/1d9gSLy5c7KjbgdADI4vSY-yNQnXP07eU?usp=sharing); they are also an archive of our live google-docing. Please see <https://openscapes.org/series> to view blank versions of the agendas. 

Date | Cohort Call Topics          | Series Chapters |      Seaside Chat Topics
----| ------------------|----------------------|--------------------------------
03/04 | 1. Openscapes mindset | [mindset](https://openscapes.github.io/series/mindset) | Pathway trailhead; create GitHub accounts 
03/18 | 2. GitHub Clinic; Team culture <br> | [publishing](https://openscapes.github.io/series/github-pub), [project management](https://openscapes.github.io/series/github-issues); [team culture](https://openscapes.github.io/series/team-culture) | Exploring GitHub 
04/01 | 3. JupyterHub Clinic; Data strategies for future us |  | Exploring JupyterHub
04/15 | 4. Coding strategies for future us; Next steps with cloud |  | Pathways preparation
04/29 | 5. Pathways share; Open communities | [coding with communities](https://openscapes.github.io/series/communities) | 

## Co-working times (optional)

Co-working sessions are where we work at the same time together. Sometimes, this means quiet work with check-ins to break up focused work and get feedback, and sometimes this involves asking questions and screensharing to learn and problem solve.

**Dates:** March 10, 24, April 7, 21  
**Times:** 11:30-1:00 pm Pacific Time
- **Location:** remotely, via Zoom

## Participating teams
Some brief information about participating teams.Please add any edits directly (we'll learn how in our GitHub Clinic!)

**The Cryosphere Geophysics and Remote Sensing (CryoGARS) Glaciology Team** at Boise State University analyzes modern changes to the Earth’s cryosphere, with a focus on rapid changes in glacier flow, glacier-ocean interactions, iceberg melting, and seasonal snow accumulation and melt. Nearly all of our projects use Landsat imagery to map changes in glacier, iceberg, and/or snow extent. Several projects also use Landsat data to map glacier velocities or rely on NASA-produced glacier velocities computed from Landsat and Sentinel images. We also use ICESat-2 data to map glacier volume change and seasonal snow in mountain regions. We look forward to using more cloud resources so that we can expand our analyses in space and time in order to advance our understanding of Cryosphere change!


**The Mapes Team** at the University of Miami studies atmospheric dynamics through multi-source data synthesis, with global grids as the glue. The global grids are huge, so downloading is out of the question. Fetching from aggregations (THREDDS, GDS) works for case studies, but sometimes we need to process it all (simplest example: make a multi-year climatology, to give context to actual fields as "anomalies"). So the data lake in the cloud will be a nice resource, and open new vistas like machine learning which always benefits from more more more data. 

**The Cornillon Team** at the University of Rhode Island has several projects making use of MODIS and VIIRS sea surface temperature (SST). 1) Statistical description of the location, strength and temporal evolution of SST fronts. As part of this project, I have developed an algorithm to unmask pixels improperly flagged as cloud contaminated in the standard MODIS SST products. The improved masks will be made available to the community at large as will the fronts identified by our edge detection algorithm. 2) The use of ML algorithms to discover anomalous SST fields in the MODIS and VIIRS archives. This project has evolved to a more general characterization of ocean regimes based on a Self Supervised Learning algorithm. 3) My group is working on a machine learning algorithm to deconvolve AMSR-E SST data resulting in a substantial improvement in its spatial resolution. The algorithm is being trained with MODIS data and with the output of a numerical model. Once the algorithm has been completed for SST data we will investigate its application to SMAP soil moisture products.

**The Ladies of Landsat Team** has members from USGS, UCSB, and the University of Arizona. Kate uses dense time series of Landsat data to build harmonic models to predict land use cover and land use change and its links to climatological signals. Crista researches the human dimensions of earth observation data, such as Landsat. Nikki uses NASA drought models to map climate hazards in her Navajo Nation community. The research project "Power of the Pixel: Connecting Indigenous Communities through Remote Sensing in the United States" combines the power of all three foci to use NASA/USGS Landsat data to build earth observation capacity in Indigenous communities across the United States.

**The SASSIE Team** has members from the University of Washington, JPL, and APL. They are part of the NASA salinity and SWOT science teams, and regularly use satellite salinity, temperature, altimetry and sea ice data, as well as in situ holdings (SPURS-2, upcoming SASSIE expt).

**The Tandon Team** at the University of Massachusetts Dartmouth uses the remotely sensed data to setup the larger scale perspectives for our more in depth analysis and cruise based work for in-situ experimental data from experiements in Indian ocean such as ASIRI and MISOBOB.

**The Palter Team** at the University of Rhode Island uses NASA data to compare with in-situ observations taken from ships and Uncrewed Surface Vehicles. NASA data provides additional parameters (like ocean surface topography) that are useful in the understanding of in-situ data (for example identifying fronts in the ACC). We have also used ocean color data from MODIS-Aqua to map distributions of ocean surface properties, such as chlorophyll concentration & sea surface salinity (region-specific algorithm), to analyze seasonal, annual, and decadal trends of key biogeochemical processes in the ocean.

**The Just Team** at Mount Siani uses earth observations to reconstruct ground-level environmental exposures to fine particulate matter, air temperature, and humidity which we use in epidemiologic health studies with cohorts and large registries in the US and Mexico. In a project that started out by seeking to understand the pattern of error in Aerosol Optical Depth (AOD) retrievals, we have developed an R-based reproducible workflow using the targets package for collocating and correcting AOD from the MAIAC algorithm (product MCD19A2 for Aqua and Terra) versus ground stations using gradient-boosted machine learning. This workflow adds reproducibility and extensibility for further development and new applications and builds on results we have published for AOD (https://doi.org/10.3390/rs10050803) and for column water vapor (https://doi.org/10.5194/amt-13-4669-2020 ; data/code in Zenodo: 10.5281/zenodo.3568449).

**The Hain/SPoRT Team** is a directly funded NASA activity, and engages with operational stakeholders to transition unique NASA observations and capabilities to improve decision-making. 

**The Roberts Team** supports evaluation of global energy and water budgets, develops retrieval algorithms and climate data records (e.g. SeaFlux V1), evaluates air-sea interaction and ocean winds, and downscales and bias corrects models for use in hydrologic and agricultural modeling).

## NASA Openscapes team

[Planning Google Folder](https://drive.google.com/drive/folders/1MGA2R7qJOJD2l5kpzXJ5I29sHfMPL5Kx?usp=sharing)

Julie Lowndes, NASA-Openscapes Co-Lead, NCEAS, UCSB, is co-leading
Erin Robinson, NASA-Openscapes Co-Lead, Metadata Game Changers, is co-leading

NASA Openscapes Mentors assisting: 

- Andy Barrett, NSIDC
- Aaron Friesz, LP DAAC
- Alexis Hunzinger, GES DISC
- Luis Lopez, NSIDC
- Catalina Oaida, PO.DAAC
- Jack McNelis, PO.DAAC
- Christine Smit, GES DISC
- Amy Steiker, NSIDC
- Makhan Virdi, ASDC

## More about Openscapes and the Champions program:

* **[Our path to better science in less time using open data science tools](https://www.nature.com/articles/s41559-017-0160)** (Lowndes et al 2017, _Nature Ecology & Evolution_) - this paper greatly influences the whole Champions program and we’ll ask that everyone participating reads it before our first Cohort Call on September 9. 
* **[Openscapes: Better Science for Future Us](https://docs.google.com/presentation/d/1HGw4P095-lblHiGQHXYidHiVysjrPxuojxTxKtE13vk/edit#slide=id.ge2b7c2f974_0_2017)** - 2021 plenary talk at the Society for Open, Reliable, and Transparent Ecology and Evolutionary biology (SORTEE) inaugural conference 
* **[Openscapes embraces kindness and inclusion in open science](https://sparcopen.org/impact-story/openscapes-embraces-kindness-and-inclusion-of-open-science/)** - 2021 article about Openscapes
* **[openscapes.org](https://openscapes.org/)** – Openscapes is operated at the National Center for Ecological Analysis & Synthesis, UC Santa Barbara


