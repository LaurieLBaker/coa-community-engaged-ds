---
date: "2022-04-25 T00:00:00Z"
external_link: ""
image:
  caption: Sign saying "Beware of ticks with hikers walking through woods in the background."
  focal_point: Smart
links:
slides: 
summary: 
tags:
- epidemiology
- reporting
- passive surveillance
- lyme disease
- ticks
title: Mapping Primary Care Providers for Lyme Disease Education Outreach
publishDate: "2022-04-25T00:00:00Z"
---

Maine has high rates of tickborne diseases including Lyme disease, anaplasmosis, and babesiosis. Tickborne disease are spread to humans through the bite of an infected deer tick (*Ixodes scapularis*) and can have serious health implications (see table below). 

Diagnosis of Lyme disease is typically through primary care providers. While 70-80% of people nationally infected with Lyme disease show a skin rash referred to as the "Bull's-eye" rash or erythema migrans (EM) [Maine Tracking Network](https://gateway.maine.gov/cognos/cgi-bin/cognosisapi.dll?b_action=cognosViewer&ui.action=run&ui.object=%2fcontent%2ffolder%5b%40name%3d%27CDC%20EOHP%20EPHT%20AVR%27%5d%2freportView%5b%40name%3d%27Maine%20Environmental%20Public%20Health%20Tracking%20%28EPHT%29%20Network%20-%20Public%20Data%20Portal%27%5d&cv.header=false&cv.toolbar=false). Further educational training on how to recognize Lyme disease in patients could help primary care provider's diagnose the 20-30% of Lyme disease cases where the patient does not present the Bull's eye rash.

Studying Lyme disease incidence is a challenging problem. High Lyme disease incidence may reflect areas with a higher risk of Lyme disease or where primary care providers are able to accurately diagnose Lyme disease in patients. Similarly, low Lyme disease incidence may reflect areas with a lower risk of Lyme disease or where people with Lyme may not be seeking treatment or where primary care providers are missing Lyme disease cases. Passive tick submission data (where ticks are mailed in or dropped off at testing facilities) can give some insight into the prevalence of Lyme disease in ticks across Maine, however, this data can be biased by who submits ticks for testing which might depend on the Lyme disease awareness and concern of individuals. 

Students will work in partnership with researchers from the [Maine Medical Center Research Institute's Lyme and Vector-Borne Disease Lab](https://mmcri.org/?page_id=1090) to explore, visualize, and analyze the data which could include interactive dashboard to map primary care providers and identify areas with a high-risk of Lyme disease where medical education training programs might be offered to improve Lyme disease diagnosis. Some questions students might consider in this work is whether to look both at areas with very low (possible undiagnosed cases) and areas with high incidence of Lyme disease, how to take into account the population and/or catchment area a provider serves, and how to consider and represent inequity in access to healthcare, including distance to a primary care provider or lack of insurance which act as barriers to treatment. 

 | <div style="width:140px;text-align:left">Disease</div> | <div style="width:100px;text-align:left">Cause</div> |  <div style="width:160px;text-align:left">Symptoms </div> | <div  style="width:160px;text-align:left">Health Implications </div> |
|:---|:--|:--|:--|
| **Anaplasmosis** | Caused by the *Anaplasma phagocytophila* bacteria | Symptoms include fever, headache, malaise, and body aches. | Anaplasmosis can be a serious illness and can be fatal if not treated correctly. |
| **Babesiosis** | Caused by the *Babesia microti* parasite | Symptoms include extreme fatigue, aches, fever, chills, sweating, dark urine, and possibly anemia. | Babesiosis can be life threatening. |
| **Lyme disease** | Caused by the *Borrelia burgdorferi* bacteria | The first clinical sign of the disease is a skin rash referred to as the "Bull’s-eye" rash or erythema migrans (EM). This occurs in 70-80% of people nationally, usually within 3-30 days after a tick bite. Other signs include arthritis, Bell’s Palsy, and heart problems. |  |

Source: [The Maine Tracking Network](https://gateway.maine.gov/cognos/cgi-bin/cognosisapi.dll?b_action=cognosViewer&ui.action=run&ui.object=%2fcontent%2ffolder%5b%40name%3d%27CDC%20EOHP%20EPHT%20AVR%27%5d%2freportView%5b%40name%3d%27Maine%20Environmental%20Public%20Health%20Tracking%20%28EPHT%29%20Network%20-%20Public%20Data%20Portal%27%5d&cv.header=false&cv.toolbar=false)

### What skills you can expect to learn:

- Importing, cleaning and working with multiple data sources including Lyme disease cases, locations of primary care providers, and Maine population census data. 
- Data visualization and communication of public health information.
- Report writing using Rmarkdown.
- Creation of interactive applications using RShiny.
- Geocomputational methods (e.g. determining if a point is inside a polygon).
- Geospatial statistical analysis techniques applied to health data.
- Knowledge exchange including documenting and sharing coding knowledge with community partners. 


### Data:

- This html document gives an [overview of the main datasets in the GitHub repository](https://mlclayton6.github.io/Maine-Ticks/pop_lyme_leaflet.html). These data include: tick submission and testing data, Lyme disease cases, and census data to get you started!

- Hospitalization data will be added to the Github Repo soon.

- Data in the repo comes from the [Maine Tracking Network](https://gateway.maine.gov/cognos/cgi-bin/cognosisapi.dll?b_action=cognosViewer&ui.action=run&ui.object=%2fcontent%2ffolder%5b%40name%3d%27CDC%20EOHP%20EPHT%20AVR%27%5d%2freportView%5b%40name%3d%27Maine%20Environmental%20Public%20Health%20Tracking%20%28EPHT%29%20Network%20-%20Public%20Data%20Portal%27%5d&cv.header=false&cv.toolbar=false) and the U.S. Census.  

### Resources:

These resources are a starting place which you can add to.

**Ticks and Lyme Disease**
- [Ticks and tick-borne diseases reference sheet](https://www.maine.gov/dhhs/mecdc/infectious-disease/epi/vector-borne/documents/tick-reference-guide.pdf)
- [Tick ecology and tick testing](https://www.maine.gov/dhhs/mecdc/infectious-disease/epi/vector-borne/lyme/tick-ecology-and-tick-testing.shtml)

- [Tick attachment and tickborne diseases](https://www.maine.gov/dhhs/mecdc/infectious-disease/epi/vector-borne/lyme/tick-attachment-and-tickborne-diseases.shtml)

- [Tick diseases and symptoms](https://www.cdc.gov/ticks/diseases/)

**Geocomputation and Geospatial Health Data**

- [Geocomputation with R by Robin Lovelace, Jakub Nowosad, and Jannes Muenchow](https://geocompr.robinlovelace.net/index.html)
- [Geospatial Health Data: Modeling and Visualization with R-INLA and Shiny by Paula Moraga](https://www.paulamoraga.com/book-geospatial/)

### Acknowledgments

Special thanks to [Matt Clayton '23](https://github.com/mlclayton6) for finding, preparing and creating initial visualizations and maps of the data. 