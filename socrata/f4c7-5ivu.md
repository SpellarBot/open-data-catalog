# Kirwan Institute Opportunity Map Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/kirwan-institute-opportunity-map-data) |
| Metadata | [Link](https://data.austintexas.gov/api/views/f4c7-5ivu) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/f4c7-5ivu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/f4c7-5ivu/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | f4c7-5ivu |
| Name | Kirwan Institute Opportunity Map Data |
| Attribution | NHCD |
| Category | Neighborhood |
| Tags | opportunity map, kirwan, housing, economic, education |
| Created | 2015-08-07T19:21:01Z |
| Publication Date | 2015-08-07T20:33:44Z |

## Description

This 2013 dataset includes information at the block group-level for the 5-county Austin metro area. Economic, educational, housing, mobility, and environmental indicators are calculated for each block group to provide a comprehensive opportunity index score. This score reflects "opportunity" in the area, defined as a situation or condition that places individuals in a position to be more likely to succeed or excel. This data was collected and calculated by the Kirwan Institute, with collaboration from Green Doors and various community partners, and is compiled in  "Geography of Opportunity in Austin" (http://www.greendoors.org/programs/docs/Geography-of-Opportunity-Austin-2013.pdf#page=43). The data can be viewed in an interactive map form here: http://www.arcgis.com/home/webmap/viewer.html?webmap=5db08646b03547abab85aec0a3592fb7. The data is also available in shapefile format for use in ESRI GIS mapping applications here: https://data.austintexas.gov/Neighborhood/Kirwin-Opportunity-Map/3ns6-m3cy.

## Columns

```ls
| Included | Schema Type    | Field Name                      | Name                            | Data Type | Render Type |
| ======== | ============== | =============================== | =============================== | ========= | =========== |
| No       | time           | :updated_at                     | updated_at                      | meta_data | meta_data   |
| Yes      | series tag     | geoid                           | GeoID                           | text      | number      |
| Yes      | series tag     | census_geography                | Census Geography                | text      | text        |
| Yes      | series tag     | housing_environment_index       | Housing & Environment Index     | text      | text        |
| Yes      | series tag     | education_index                 | Education Index                 | text      | text        |
| Yes      | series tag     | economic_mobility_index         | Economic & Mobility Index       | text      | text        |
| Yes      | series tag     | comprehensive_opportunity_index | Comprehensive Opportunity Index | text      | text        |
| Yes      | numeric metric | housing_environment_score       | Housing & Environment Score     | number    | number      |
| Yes      | numeric metric | education_score                 | Education Score                 | number    | number      |
| Yes      | numeric metric | economic_mobility_score         | Economic & Mobility Score       | number    | number      |
| Yes      | numeric metric | comprehensive_opportunity_score | Comprehensive Opportunity Score | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:f4c7-5ivu d:2015-08-07T12:21:06.000Z t:economic_mobility_index="Very Low" t:census_geography="Block Group 1, Census Tract 9501, Bastrop County, Texas" t:education_index=Low t:comprehensive_opportunity_index=Low t:housing_environment_index=High t:geoid=480219501001 m:economic_mobility_score=1 m:housing_environment_score=4 m:comprehensive_opportunity_score=2 m:education_score=2

series e:f4c7-5ivu d:2015-08-07T12:21:06.000Z t:economic_mobility_index="Very Low" t:census_geography="Block Group 2, Census Tract 9501, Bastrop County, Texas" t:education_index=Moderate t:comprehensive_opportunity_index=Low t:housing_environment_index=High t:geoid=480219501002 m:economic_mobility_score=1 m:housing_environment_score=4 m:comprehensive_opportunity_score=2 m:education_score=3

series e:f4c7-5ivu d:2015-08-07T12:21:06.000Z t:economic_mobility_index="Very Low" t:census_geography="Block Group 3, Census Tract 9501, Bastrop County, Texas" t:education_index=Low t:comprehensive_opportunity_index=Low t:housing_environment_index=Moderate t:geoid=480219501003 m:economic_mobility_score=1 m:housing_environment_score=3 m:comprehensive_opportunity_score=2 m:education_score=2
```

## Meta Commands

```ls
metric m:housing_environment_score p:integer l:"Housing & Environment Score" t:dataTypeName=number

metric m:education_score p:integer l:"Education Score" t:dataTypeName=number

metric m:economic_mobility_score p:integer l:"Economic & Mobility Score" t:dataTypeName=number

metric m:comprehensive_opportunity_score p:integer l:"Comprehensive Opportunity Score" t:dataTypeName=number

entity e:f4c7-5ivu l:"Kirwan Institute Opportunity Map Data" t:attribution=NHCD t:url=https://data.austintexas.gov/api/views/f4c7-5ivu

property e:f4c7-5ivu t:meta.view v:id=f4c7-5ivu v:category=Neighborhood v:averageRating=0 v:name="Kirwan Institute Opportunity Map Data" v:attribution=NHCD

property e:f4c7-5ivu t:meta.view.license v:name="Public Domain"

property e:f4c7-5ivu t:meta.view.owner v:id=8uru-zr6m v:screenName=Lauren v:displayName=Lauren

property e:f4c7-5ivu t:meta.view.tableauthor v:id=8uru-zr6m v:screenName=Lauren v:roleName=editor v:displayName=Lauren
```

## Top Records

```ls
| :updated_at | geoid        | census_geography                                        | housing_environment_index | education_index | economic_mobility_index | comprehensive_opportunity_index | housing_environment_score | education_score | economic_mobility_score | comprehensive_opportunity_score | 
| =========== | ============ | ======================================================= | ========================= | =============== | ======================= | =============================== | ========================= | =============== | ======================= | =============================== | 
| 1438950066  | 480219501001 | Block Group 1, Census Tract 9501, Bastrop County, Texas | High                      | Low             | Very Low                | Low                             | 4                         | 2               | 1                       | 2                               | 
| 1438950066  | 480219501002 | Block Group 2, Census Tract 9501, Bastrop County, Texas | High                      | Moderate        | Very Low                | Low                             | 4                         | 3               | 1                       | 2                               | 
| 1438950066  | 480219501003 | Block Group 3, Census Tract 9501, Bastrop County, Texas | Moderate                  | Low             | Very Low                | Low                             | 3                         | 2               | 1                       | 2                               | 
| 1438950066  | 480219501004 | Block Group 4, Census Tract 9501, Bastrop County, Texas | Moderate                  | Low             | Very Low                | Low                             | 3                         | 2               | 1                       | 2                               | 
| 1438950066  | 480219501005 | Block Group 5, Census Tract 9501, Bastrop County, Texas | Moderate                  | Low             | Very Low                | Low                             | 3                         | 2               | 1                       | 2                               | 
| 1438950066  | 480219502001 | Block Group 1, Census Tract 9502, Bastrop County, Texas | Moderate                  | Low             | Very Low                | Very Low                        | 3                         | 2               | 1                       | 1                               | 
| 1438950066  | 480219502002 | Block Group 2, Census Tract 9502, Bastrop County, Texas | Moderate                  | Moderate        | Very Low                | Low                             | 3                         | 3               | 1                       | 2                               | 
| 1438950066  | 480219502003 | Block Group 3, Census Tract 9502, Bastrop County, Texas | Moderate                  | Low             | Very Low                | Very Low                        | 3                         | 2               | 1                       | 1                               | 
| 1438950066  | 480219502004 | Block Group 4, Census Tract 9502, Bastrop County, Texas | Moderate                  | Low             | Very Low                | Low                             | 3                         | 2               | 1                       | 2                               | 
| 1438950066  | 480219502005 | Block Group 5, Census Tract 9502, Bastrop County, Texas | Low                       | Low             | Very Low                | Very Low                        | 2                         | 2               | 1                       | 1                               | 
```