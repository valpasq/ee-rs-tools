# ee-rs-tools
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.5167544.svg)](https://doi.org/10.5281/zenodo.5167544)

This repository hosts UI tools for exploring remote sensing datasets in [Google Earth Engine](https://earthengine.google.com/).

Earth Engine users can add this repository to the Code Editor using the following link: [https://code.earthengine.google.com/?accept_repo=users/valeriepasquarella/ee-rs-tools](
https://code.earthengine.google.com/?accept_repo=users/valeriepasquarella/ee-rs-tools
).

## Spectral Encounter
The *Spectral Encounter* apps are designed to facilitate visualization of spectral properties of optical remote sensing imagery. The app script `scripts/spectral_encounter_app` can be used to generate both [Sentinel-2](https://developers.google.com/earth-engine/datasets/catalog/COPERNICUS_S2) and [Landsat 8](https://developers.google.com/earth-engine/datasets/catalog/LANDSAT_LC08_C01_T1_RT_TOA) versions of the tool.

* [Sentinel-2 Spectral Encounter app](https://valeriepasquarella.users.earthengine.app/view/spectral-encounter-s2)
* [Landsat 8 Spectral Encounter app](https://valeriepasquarella.users.earthengine.app/view/spectral-encounter-l8)

For more information on spectral signatures and the Spectral Encounter tools see the Medium article [Exploring optical imagery: a spectral encounter](https://medium.com/geospatial-processing-at-scale/exploring-optical-imagery-a-spectral-encounter-996cd3f0b591?source=friends_link&sk=eecbc350bd9aec44534cc13952f3240f).


## This repo
As more and more scientists begin to incorporate Earth observation imagery into analyses and workflows, tools that help build basic intuition about the properties of openly available images and image collections is more critical than ever. The hope is that this repository will grow to house more tools that enable students and experts alike to dig deeper into fundamental remote sensing concepts like spectral, spatial, temporal, and radiometric resolution. 

**Ideas for future tools:**
* *Spectral Encounter: S1 Edition* -- adaptation of Spectral Encounter script to view RGB of S1 polarizations and/or different dates of imagery (may require additional processing such as temporal compositing and/or spatial filtering options).
* *Resolution Review* -- a tool to compare spatial resolutions of different images and/or map products
* *Pick your Processing* -- a tool to compare different levels of pre-processing, e.g. Landsat Raw, TOA, and SR or S2 L1C and L2A



### Want to contribute?
Feedback, feature requests, extensions, modifications, and new tools welcome! 
Open issues [here](https://github.com/valpasq/ee-rs-tools/issues), submit pull requests [here](https://github.com/valpasq/ee-rs-tools/pulls), or just add to the [discussion](https://github.com/valpasq/ee-rs-tools/discussions).

