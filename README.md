# Earth Observation Hub

This repository brings together my work applying Earth observation data and methods to public health research. It acts as a storytelling hub—showing the evolution of my research program from early spatial analyses to large-scale, multi-disease, and multi-country projects.

> **Definition:** *Earth Observation (EO)* refers to observational data about processes and conditions at or near Earth’s surface. EO spans (a) **environmental sensing** — in-situ gauges and stations (i.e. weather stations), plus **remote sensing** from satellites, aircraft, and drones — and (b) **human-systems sensing** — data on population location or movement such as GPS logger records, mobile-network CDR/handover data, and various forms of telemetry. I treat **Remote Sensing** as a **subset** of EO.

---

## Practical How-To Guides

If you are looking for **step-by-step methods** (e.g., downloading weather station data, pulling ERA5 climate series, or running zonal statistics in QGIS), these are maintained separately here:

👉 [parker-group/earth-observation-howto](https://github.com/parker-group/earth-observation-howto)


## Background

The Mahidol–Oxford Tropical Medicine Research Unit ([MORU](https://www.tropmedres.ac/)) network, and especially the Shoklo Malaria Research Unit (SMRU) and Lao–Oxford–Mahosot Hospital–Wellcome Trust Research Unit ([LOMWRU](https://www.tropicalmedicine.ox.ac.uk/research/lao-lomwru-moru-network)), provided me opportunities to integrate Earth observation data into public health.  

Initial work used SRTM elevation data to better understand distances, friction-of-distance, and travel times in malaria research (especially with regard to [METF](https://github.com/DMParker1/METF-mapping)). While at SMRU, I was invited by [Paul Newton](https://www.ndm.ox.ac.uk/team/paul-newton) to give a GIS workshop ([QGIS](https://qgis.org/)) at LOMWRU. This led to collaborations on the spatial epidemiology of infections of the central nervous system in Laos — work that inspired me to explore neglected tropical diseases and environmental predictors of a broad range of health outcomes.

---

## Selected Publications

- **Spatial epidemiology of Japanese encephalitis virus and other infections of the central nervous system in Lao PDR (2003–2011): A retrospective analysis.**  
  Rattanavong S, Dubot-Pérès A, Mayxay M, Vongsouvath M, Lee SJ, Cappelle J, et al. *PLOS Neglected Tropical Diseases*. 2020;14(5):e0008333.  
  https://doi.org/10.1371/journal.pntd.0008333

- **A spatio-temporal analysis of scrub typhus and murine typhus in Laos; implications from changing landscapes and climate.**  
  Roberts T, Parker DM, Bulterys PL, Rattanavong S, Elliott I, Phommasone K, et al. *PLOS Neglected Tropical Diseases*. 2021;15(8):e0009685.  
  https://doi.org/10.1371/journal.pntd.0009685

- **Discovering disease-causing pathogens in resource-scarce Southeast Asia using a global metagenomic pathogen monitoring system.**  
  Bohl JA, Lay S, Chea S, Ahyong V, Parker DM, Gallagher S, et al. *Proceedings of the National Academy of Sciences*. 2022;119(11):e2115285119.  
  https://doi.org/10.1073/pnas.2115285119

- **Geographical distribution of *Burkholderia pseudomallei* in soil in Myanmar.**  
  Swe MMM, Win MM, Cohen J, Phyo AP, Lin HN, Soe K, et al. *PLOS Neglected Tropical Diseases*. 2021;15(5):e0009372.  
  https://doi.org/10.1371/journal.pntd.0009372

- **Mobile phone handover data for measuring and analysing human population mobility in Western Ethiopia: implication for malaria disease epidemiology and elimination efforts.** 
  Haileselassie W, Getnet A, Solomon H, Deressa W, Yan G, Parker DM. *Malaria Journal*. 2022;21:323.  
  https://doi.org/10.1186/s12936-022-04337-w

- **Determinants of exposure to *Aedes* mosquitoes: A comprehensive geospatial analysis in peri-urban Cambodia.**  
  Parker DM, Medina C, Bohl JA, Lon C, Chea S, Lay S, et al. *Acta Tropica*. 2023;239:106829.  
  https://doi.org/10.1016/j.actatropica.2023.106829

- **Spatio-temporal trends of malaria incidence from 2011 to 2017 and environmental predictors of malaria transmission in Myanmar.**  
  Zhao Y, Aung PL, Ruan S, Win KM, Wu Z, Soe TN, et al. *Infectious Diseases of Poverty*. 2023;12:2.  
  https://doi.org/10.1186/s40249-023-01055-6

- **Association between air raids and reported incidence of cholera in Yemen, 2016–19: An ecological modelling study.**  
  Tarnas MC, Al-Dheeb N, Zaman MH, Parker DM. *The Lancet Global Health*. 2023;11(12):e1955–e1963.  
  https://doi.org/10.1016/S2214-109X(23)00272-3

- **Ecological study measuring the association between conflict, environmental factors, and annual global cutaneous and mucocutaneous leishmaniasis incidence (2005–2022).**  
  Tarnas MC, Abbara A, Desai AN, Parker DM. *PLOS Neglected Tropical Diseases*. 2024;18(9):e0012549.  
  https://doi.org/10.1371/journal.pntd.0012549

- **A conceptual framework for understanding extractive settlements and disease: Demography, environment, and epidemiology.**  
  Glendening N, Haileselassie W, Parker DM. In: *Planetary health approaches to understand and control vector-borne diseases*. 2024.  
  https://doi.org/10.3920/9789004688650_007


<hr />

<h2>Featured Case Studies</h2>

<details>
  <summary><strong>Kinshasa EO</strong> — Urban Earth Observation workflows (weather stations + satellite data)</summary>

  <p><strong>Overview:</strong> <a href="https://github.com/parker-group/Kinshasa_EO/blob/main/docs/OVERVIEW_KinshasaEO.md">Overview of EO data processing</a><br/>
  <strong>Repository:</strong> <a href="https://github.com/parker-group/Kinshasa_EO">parker-group/Kinshasa_EO</a></p>

  <p><em>What’s inside:</em> end-to-end pipeline for Kinshasa, including weather station extraction, ERA5 time series, MODIS/Landsat indices, QGIS zonal statistics, and R visualizations.</p>
</details>


---

## Data Sources Commonly Used

- [MODIS](https://modis.gsfc.nasa.gov/data/) (NDVI, EVI, surface water indices)  
- [SRTM](https://www2.jpl.nasa.gov/srtm/) elevation data  
- [ERA5](https://www.ecmwf.int/en/forecasts/datasets/reanalysis-datasets/era5) climate reanalysis  
- [Landsat](https://landsat.gsfc.nasa.gov/) and [Sentinel](https://sentinels.copernicus.eu/) satellite imagery  
- [GEE](https://earthengine.google.com/) for scalable environmental data extraction  

---


## Related Repositories

- [spatial-epidemiology-hub](https://github.com/DMParker1/spatial-epidemiology-hub) — Minimal umbrella repo showing how my projects connect through GIS and spatial epidemiology.  
- [METF-mapping](https://github.com/DMParker1/METF-mapping) — Mapping and community engagement groundwork for malaria post placement and METF operations.  
- [tMDA-program](https://github.com/DMParker1/tmda-program) — Targeted mass drug administration trials and modeling in Southeast Asia.  
- [early-dx-tx](https://github.com/DMParker1/early-dx-tx) — Early access to malaria diagnosis and treatment.  
- [tm-border-mch](https://github.com/DMParker1/tm-border-mch) — Maternal and child health research on the Thailand–Myanmar border.  
- [earth-observation-hub](https://github.com/DMParker1/earth-observation-hub) — Remote sensing and Earth observation methods applied to public health.  
- [SDEtool](https://github.com/parker-group/SDEtool) — In-house standard deviational ellipse generation tool for spatial epidemiology and movement analysis; available for related work but not used in these specific projects.
- [activity-spaces](https://github.com/DMParker1/activity-spaces) — Methods + narrative on multi-place exposure (farm huts, GPS, mobile phone data) for infectious disease transmission.


---


*Maintained by Daniel M. Parker*
