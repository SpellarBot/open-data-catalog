# Directory Of Approved Tree Species List

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/directory-of-approved-tree-species-list-49696) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/99wq-x9cr) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/99wq-x9cr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/99wq-x9cr/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 99wq-x9cr |
| Name | Directory Of Approved Tree Species List |
| Attribution | Department of Parks and Recreation (DPR) |
| Category | Recreation |
| Tags | dpr, recreation, park, tree, species, healthy living |
| Created | 2013-01-24T23:14:31Z |
| Publication Date | 2013-06-21T20:28:12Z |

## Description

Tree species that are approved to be planted in NY City

## Columns

```ls
| Included | Schema Type | Field Name                | Name                      | Data Type | Render Type |
| ======== | =========== | ========================= | ========================= | ========= | =========== |
| No       | time        | :updated_at               | updated_at                | meta_data | meta_data   |
| Yes      | series tag  | species_scientific_name   | Species Scientific Name   | text      | text        |
| Yes      | series tag  | species_common_name       | Species Common Name       | text      | text        |
| Yes      | series tag  | form                      | Form                      | text      | text        |
| Yes      | series tag  | growth_rate               | Growth Rate               | text      | text        |
| Yes      | series tag  | fall_color                | Fall Color                | text      | text        |
| Yes      | series tag  | environmental_tolerances  | Environmental Tolerances  | text      | text        |
| Yes      | series tag  | location_tolerances       | Location Tolerances       | text      | text        |
| Yes      | series tag  | notes_suggested_cultivars | Notes/Suggested Cultivars | text      | text        |
| Yes      | series tag  | tree_size                 | Tree Size                 | text      | text        |
| Yes      | series tag  | comments                  | Comments                  | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:99wq-x9cr d:2013-01-24T15:14:32.000Z t:species_scientific_name="Ginkgo biloba" t:species_common_name=Ginkgo t:location_tolerances="Median Tree, Narrow Growing Space" t:growth_rate=Slow t:form=Upright t:environmental_tolerances="Salt, Drought, High Wind, Pollution and High pH Tolerant" t:notes_suggested_cultivars="'Autumn Gold' or 'Presedential Gold'" t:tree_size="Large (Mature Height > 50 ft)" t:fall_color=Yellow m:row_number.99wq-x9cr=1

series e:99wq-x9cr d:2013-01-24T15:14:32.000Z t:species_scientific_name="Quercus spp. 'Fastigiata'" t:species_common_name="Fastigiata Oak" t:location_tolerances="Median Tree, Narrow Growing Space" t:growth_rate=Slow t:form=Upright t:environmental_tolerances=none t:notes_suggested_cultivars="Similar tree is Quercus robur" t:tree_size="Large (Mature Height > 50 ft)" t:fall_color=Maroon m:row_number.99wq-x9cr=2

series e:99wq-x9cr d:2013-01-24T15:14:32.000Z t:species_scientific_name="Liquidambar styraciflua" t:species_common_name=Sweetgum t:location_tolerances=none t:growth_rate=Medium t:form=Pyramidal t:environmental_tolerances="Wet Site Tolerant" t:notes_suggested_cultivars="Plant Spring Only, lawn pits only, look for 'Rotundiloba'" t:tree_size="Large (Mature Height > 50 ft)" t:fall_color=Yellow m:row_number.99wq-x9cr=3
```

## Meta Commands

```ls
metric m:row_number.99wq-x9cr p:long l:"Row Number"

entity e:99wq-x9cr l:"Directory Of Approved Tree Species List" t:attribution="Department of Parks and Recreation (DPR)" t:url=https://data.cityofnewyork.us/api/views/99wq-x9cr

property e:99wq-x9cr t:meta.view v:id=99wq-x9cr v:category=Recreation v:attributionLink=https://www.nycgovparks.org/trees/street-tree-planting/species-list v:averageRating=0 v:name="Directory Of Approved Tree Species List" v:attribution="Department of Parks and Recreation (DPR)"

property e:99wq-x9cr t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:99wq-x9cr t:meta.view.tableauthor v:id=8b43-zkvh v:screenName="Ram S." v:displayName="Ram S."
```

## Top Records

```ls
| :updated_at | species_scientific_name            | species_common_name | form      | growth_rate | fall_color   | environmental_tolerances                                            | location_tolerances               | notes_suggested_cultivars                                 | tree_size                     | comments | 
| =========== | ================================== | =================== | ========= | =========== | ============ | =================================================================== | ================================= | ========================================================= | ============================= | ======== | 
| 1359040472  | Ginkgo biloba                      | Ginkgo              | Upright   | Slow        | Yellow       | Salt, Drought, High Wind, Pollution and High pH Tolerant            | Median Tree, Narrow Growing Space | 'Autumn Gold' or 'Presedential Gold'                      | Large (Mature Height > 50 ft) |          | 
| 1359040472  | Quercus spp. 'Fastigiata'          | Fastigiata Oak      | Upright   | Slow        | Maroon       | none                                                                | Median Tree, Narrow Growing Space | Similar tree is Quercus robur                             | Large (Mature Height > 50 ft) |          | 
| 1359040472  | Liquidambar styraciflua            | Sweetgum            | Pyramidal | Medium      | Yellow       | Wet Site Tolerant                                                   | none                              | Plant Spring Only, lawn pits only, look for 'Rotundiloba' | Large (Mature Height > 50 ft) |          | 
| 1359040472  | Metasequoia glyptostroboides       | Dawn Redwood        | Pyramidal | Medium      | Orange/Brown | Wet Site, Drought, High pH Tolerant                                 | Median Tree, Narrow Growing Space | Can Grow 2 to 3 Feet per Year                             | Large (Mature Height > 50 ft) |          | 
| 1359040472  | Taxodium distichum                 | Baldcypress         | Pyramidal | Medium      | Orange/Brown | Wet Site, Salt and High Wind Tolerant                               | Median Tree, Narrow Growing Space | Ideal For Wet Soils                                       | Large (Mature Height > 50 ft) |          | 
| 1359040472  | Tilia cordata                      | Littleleaf Linden   | Pyramidal | Medium      | Yellow       | Pollution Tolerant                                                  | Median Tree                       | 'Greenspire'                                              | Large (Mature Height > 50 ft) |          | 
| 1359040472  | Gymnocladus dioicus                | Coffeetree          | Rounded   | Medium      | Yellow       | Drought Tolerant                                                    | none                              | 'Espresso'                                                | Large (Mature Height > 50 ft) |          | 
| 1359040472  | Gleditsia triacanthos var. inermis | Honeylocust         | Rounded   | Medium      | Yellow       | Wet Site, Salt, Drought, High Wind, Pollution, and High pH Tolerant | Median Tree                       | 'Halka'                                                   | Large (Mature Height > 50 ft) |          | 
| 1359040472  | Liriodendron tulipifera            | Tulip Tree          | Pyramidal | Medium      | Yellow       | none                                                                | none                              | 'Rotundiloba'                                             | Large (Mature Height > 50 ft) |          | 
| 1359040472  | Quercus rubra                      | Northern Red Oak    | Rounded   | Medium      | Maroon       | Salt Tolerant                                                       | none                              | Plant Spring Only                                         | Large (Mature Height > 50 ft) |          | 
```