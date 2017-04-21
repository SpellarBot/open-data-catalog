# BMP Definitions

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/bmp-definitions) |
| Metadata | [Link](https://data.maryland.gov/api/views/rm5m-2b2j) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/rm5m-2b2j/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/rm5m-2b2j/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | rm5m-2b2j |
| Name | BMP Definitions |
| Attribution | MDA |
| Category | Agriculture |
| Tags | bmp, best management practices, maryland, agriculture, gis, dashboard, department of agriculture |
| Created | 2015-11-24T19:19:16Z |
| Publication Date | 2016-03-22T13:09:59Z |

## Description

To ensure that the Bay cleanup stays on track, a series of 2-year commitments called milestones have been established. The Maryland Department of Agriculture (MDA) has developed a list of BMPs (Best Management Practices) that would result in nutrient and sediment reductions to assist Maryland in meeting its milestone goals. This data set contains the descriptions of the BMPs.

## Columns

```ls
| Included | Schema Type | Field Name  | Name        | Data Type | Render Type |
| ======== | =========== | =========== | =========== | ========= | =========== |
| No       | time        | :updated_at | updated_at  | meta_data | meta_data   |
| Yes      | series tag  | bmp_type    | BMP_type    | text      | text        |
| Yes      | series tag  | description | Description | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:rm5m-2b2j d:2016-03-03T10:29:33.000Z t:bmp_type="Conservation Tillage" t:description="Conservation tillage involves planting and growing crops with minimal disturbance of the surface soil." m:row_number.rm5m-2b2j=1

series e:rm5m-2b2j d:2016-03-03T10:29:33.000Z t:bmp_type="Cover Crops" t:description="Cover crops are cold-hardy cereal grains such as wheat, rye and barley that are planted following fall harvest. Once established, cover crops recycle unused plant nutrients remaining in the soil from the previous summer crop and protect fields against wind and water erosion." m:row_number.rm5m-2b2j=2

series e:rm5m-2b2j d:2016-03-03T10:29:33.000Z t:bmp_type="Cropland Irrigation Management*" t:description="Cropland under irrigation management is used to decrease climatic variability and maximize crop yields." m:row_number.rm5m-2b2j=3
```

## Meta Commands

```ls
metric m:row_number.rm5m-2b2j p:long l:"Row Number"

entity e:rm5m-2b2j l:"BMP Definitions" t:attribution=MDA t:url=https://data.maryland.gov/api/views/rm5m-2b2j

property e:rm5m-2b2j t:meta.view v:id=rm5m-2b2j v:category=Agriculture v:averageRating=0 v:name="BMP Definitions" v:attribution=MDA

property e:rm5m-2b2j t:meta.view.owner v:id=hcsr-zg76 v:screenName="Alisha Mulkey" v:displayName="Alisha Mulkey"

property e:rm5m-2b2j t:meta.view.tableauthor v:id=hcsr-zg76 v:screenName="Alisha Mulkey" v:roleName=editor v:displayName="Alisha Mulkey"
```

## Top Records

```ls
| :updated_at | bmp_type                        | description                                                                                                                                                                                                                                                                                                   | 
| =========== | =============================== | ============================================================================================================================================================================================================================================================================================================= | 
| 1457000973  | Conservation Tillage            | Conservation tillage involves planting and growing crops with minimal disturbance of the surface soil.                                                                                                                                                                                                        | 
| 1457000973  | Cover Crops                     | Cover crops are cold-hardy cereal grains such as wheat, rye and barley that are planted following fall harvest. Once established, cover crops recycle unused plant nutrients remaining in the soil from the previous summer crop and protect fields against wind and water erosion.                           | 
| 1457000973  | Cropland Irrigation Management* | Cropland under irrigation management is used to decrease climatic variability and maximize crop yields.                                                                                                                                                                                                       | 
| 1457000973  | Dairy Manure Incorporation      | Manure is incorporated into the soil at the time of application using low disturbance technology. This practice can reduce ammonia loss to the atmosphere by up to 95% compared to traditional surface application                                                                                            | 
| 1457000973  | Decision Agriculture            | Decision Agriculture is used to improve the agronomic, environmental and economical management of crop production in accordance with in-field variability.                                                                                                                                                    | 
| 1457000973  | Manure Transport Program        | Animal producers with high soil phosphorus levels or inadequate land to utilize their manure in accordance with a nutrient management plan receive cost-share assistance to transport excess manure to other farms or alternative use facilities that can use the product in an environmentally sound manner. | 
| 1457000973  | Nutrient Management             | Farmers grossing $2,500 a year or more annually or livestock producers with 8,000 pounds or more of live animal weight are required to follow a state approved nutrient management plans when fertilizing crops and managing animal manure.                                                                   | 
| 1457000973  | Nutrient Management Pasture     | Plans detail the optimum use of nutrients to minimize nutrient loss while maintaining pasture productivity.                                                                                                                                                                                                   | 
| 1457000973  | Poultry Litter Incorporation*   | Poultry litter is incorporated into the soil when applied as a fertilizer to reduce both volatilization of N and sediment/P losses from rain events.                                                                                                                                                          | 
| 1457000973  | Poultry Litter Treatment        | The use of amendments to reduce ammonia and other emissions from manure in confined spaces.                                                                                                                                                                                                                   | 
```