# ee-rs-tools
[![DOI](https://zenodo.org/badge/393079988.svg)](https://zenodo.org/badge/latestdoi/393079988)

This repository hosts UI tools for exploring remote sensing datasets in [Google Earth Engine](https://earthengine.google.com/).

Earth Engine users can add this repository to the Code Editor using the following link: [https://code.earthengine.google.com/?accept_repo=users/valeriepasquarella/ee-rs-tools](
https://code.earthengine.google.com/?accept_repo=users/valeriepasquarella/ee-rs-tools
).

## Spectral Encounter
The **Spectral Encounter** apps are designed to facilitate visualization of spectral properties of optical remote sensing imagery. The app script `scripts/spectral_encounter_app` can be used to generate both [Sentinel-2](https://developers.google.com/earth-engine/datasets/catalog/COPERNICUS_S2) and [Landsat 8](https://developers.google.com/earth-engine/datasets/catalog/LANDSAT_LC08_C01_T1_RT_TOA) versions of the tool.

* [Sentinel-2 Spectral Encounter app](https://valeriepasquarella.users.earthengine.app/view/spectral-encounter-s2)
* [Landsat 8 Spectral Encounter app](https://valeriepasquarella.users.earthengine.app/view/spectral-encounter-l8)

For more information on spectral signatures and the Spectral Encounter tools see the Medium article [Exploring optical imagery: a spectral encounter](https://medium.com/geospatial-processing-at-scale/exploring-optical-imagery-a-spectral-encounter-996cd3f0b591?source=friends_link&sk=eecbc350bd9aec44534cc13952f3240f).

## EO Time Machine
The **Earth Observation (EO) Time Machine** app was designed for exploring the spatial, spectral, and temporal dimensions of image collections. The app script `scripts/eo_time_machine_app` displays collections of optical and SAR image products, including [Landsats 1-5 MSS (Tiers 1 and 2)](https://developers.google.com/earth-engine/datasets/catalog/landsat-mss), [Landsat 4](https://developers.google.com/earth-engine/datasets/catalog/LANDSAT_LT04_C02_T1_L2), [Landsat 5](https://developers.google.com/earth-engine/datasets/catalog/LANDSAT_LT05_C02_T1_L2), [Landsat 7](https://developers.google.com/earth-engine/datasets/catalog/LANDSAT_LE07_C02_T1_L2), [Landsat 8](https://developers.google.com/earth-engine/datasets/catalog/LANDSAT_LC08_C02_T1_L2), [Landsat 9](https://developers.google.com/earth-engine/datasets/catalog/LANDSAT_LC09_C02_T1_L2), Landsat Legacy (full time series of legacy bands for Landsat 5, 7, 8, and 9), [Sentinel-2 SR](https://developers.google.com/earth-engine/datasets/catalog/COPERNICUS_S2_SR_HARMONIZED), [Sentinel-2 TOA](https://developers.google.com/earth-engine/datasets/catalog/COPERNICUS_S2_HARMONIZED), and [MODIS Terra 16-day vegetation indices](https://developers.google.com/earth-engine/datasets/catalog/MODIS_061_MOD13A1), [MODIS Terra SR 8-day composites](https://developers.google.com/earth-engine/datasets/catalog/MODIS_061_MOD09A1), [MODIS Terra Daily SR](https://developers.google.com/earth-engine/datasets/catalog/MODIS_061_MOD09GA), and Sentinel-1 GRD (raw power values for IW mode, VV and VH polarizations).

* Link to [EO Time Machine app](https://valeriepasquarella.users.earthengine.app/view/eo-time-machine)

**General useage notes**: Click a point on the map to view of time series of spectral magnitude (with chart visualization inspired by Justin Braaten's [RGB time series tools](https://github.com/jdbcode/ee-rgb-timeseries)). Shows a composite image by default, click points on the time series chart to display individual images then click again to return to composite. Adjust composite dates using the text boxes below the time series chart. Change RGB band combinations to update image visualization parameters, which will also update chart visualization. Change to a different sensor to compare different EO records. Pop out the chart using the arrow to the top-right of the chart area and save chart image and/or time series for the clicked point as a CSV (including all spectral band values). Current version of the app also saves state as part of the URL, including clicked point location and RGB settings, for reproducibility and easy sharing.


## This repo
As more and more scientists begin to incorporate Earth observation imagery into analyses and workflows, tools that help build basic intuition about the properties of openly available images and image collections is more critical than ever. The hope is that this repository will grow to house more tools that enable students and experts alike to dig deeper into fundamental remote sensing concepts like spectral, spatial, temporal, and radiometric resolution. 

**Ideas for future tools:**
* *Spectral Encounter: S1 Edition* -- adaptation of Spectral Encounter script to view RGB of S1 polarizations and/or different dates of imagery (may require additional processing such as temporal compositing and/or spatial filtering options).
* *Resolution Review* -- a tool to compare spatial resolutions of different images and/or map products
* *Pick your Processing* -- a tool to compare different levels of pre-processing, e.g. Landsat Raw, TOA, and SR or S2 L1C and L2A



### Want to contribute?
Feedback, feature requests, extensions, modifications, and new tools welcome! 
Open issues [here](https://github.com/valpasq/ee-rs-tools/issues), submit pull requests [here](https://github.com/valpasq/ee-rs-tools/pulls), or just add to the [discussion](https://github.com/valpasq/ee-rs-tools/discussions).

