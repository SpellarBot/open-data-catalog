# Census Demographics at the Neighborhood Tabulation Area (NTA) level

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/census-demographics-at-the-neighborhood-tabulation-area-nta-level) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/rnsn-acs2) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/rnsn-acs2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/rnsn-acs2/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | rnsn-acs2 |
| Name | Census Demographics at the Neighborhood Tabulation Area (NTA) level |
| Attribution | Department of City Planning (DCP) |
| Category | City Government |
| Tags | census, demographics, neighborhood, pumas |
| Created | 2015-02-17T16:42:19Z |
| Publication Date | 2015-02-17T16:43:45Z |

## Description

Table of Census Demographics represented at the NTA level. NTAs are aggregations of census tracts that are subsets of New York City's 55 Public Use Micro data Areas (PUMAs)

## Columns

```ls
| Included | Schema Type    | Field Name                                            | Name                                                       | Data Type | Render Type |
| ======== | ============== | ===================================================== | ========================================================== | ========= | =========== |
| No       | time           | :updated_at                                           | updated_at                                                 | meta_data | meta_data   |
| Yes      | series tag     | geographic_area_borough                               | Geographic Area - Borough                                  | text      | text        |
| Yes      | series tag     | geographic_area_2010_census_fips_county_code          | Geographic Area - 2010 Census FIPS County Code             | text      | number      |
| Yes      | series tag     | geographic_area_neighborhood_tabulation_area_nta_code | Geographic Area - Neighborhood Tabulation Area (NTA)* Code | text      | text        |
| Yes      | series tag     | geographic_area_neighborhood_tabulation_area_nta_name | Geographic Area - Neighborhood Tabulation Area (NTA)* Name | text      | text        |
| Yes      | series tag     | total_population_2000_number                          | Total Population 2000 Number                               | text      | number      |
| Yes      | series tag     | total_population_2010_number                          | Total Population 2010 Number                               | text      | number      |
| Yes      | series tag     | total_population_change_2000_2010_number              | Total Population Change 2000-2010 Number                   | text      | number      |
| Yes      | numeric metric | total_population_change_2000_2010_percent             | Total Population Change 2000-2010 Percent                  | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:rnsn-acs2 d:2015-02-17T08:42:21.000Z t:total_population_2010_number=31078 t:geographic_area_2010_census_fips_county_code=5 t:geographic_area_borough=Bronx t:total_population_change_2000_2010_number=2929 t:geographic_area_neighborhood_tabulation_area_nta_name=Claremont-Bathgate t:total_population_2000_number=28149 t:geographic_area_neighborhood_tabulation_area_nta_code=BX01 m:total_population_change_2000_2010_percent=10.4

series e:rnsn-acs2 d:2015-02-17T08:42:21.000Z t:total_population_2010_number=34517 t:geographic_area_2010_census_fips_county_code=5 t:geographic_area_borough=Bronx t:total_population_change_2000_2010_number=-905 t:geographic_area_neighborhood_tabulation_area_nta_name=Eastchester-Edenwald-Baychester t:total_population_2000_number=35422 t:geographic_area_neighborhood_tabulation_area_nta_code=BX03 m:total_population_change_2000_2010_percent=-2.6

series e:rnsn-acs2 d:2015-02-17T08:42:21.000Z t:total_population_2010_number=54415 t:geographic_area_2010_census_fips_county_code=5 t:geographic_area_borough=Bronx t:total_population_change_2000_2010_number=-914 t:geographic_area_neighborhood_tabulation_area_nta_name="Bedford Park-Fordham North" t:total_population_2000_number=55329 t:geographic_area_neighborhood_tabulation_area_nta_code=BX05 m:total_population_change_2000_2010_percent=-1.7
```

## Meta Commands

```ls
metric m:total_population_change_2000_2010_percent p:float l:"Total Population Change 2000-2010 Percent" t:dataTypeName=number

entity e:rnsn-acs2 l:"Census Demographics at the Neighborhood Tabulation Area (NTA) level" t:attribution="Department of City Planning (DCP)" t:url=https://data.cityofnewyork.us/api/views/rnsn-acs2

property e:rnsn-acs2 t:meta.view v:id=rnsn-acs2 v:category="City Government" v:averageRating=0 v:name="Census Demographics at the Neighborhood Tabulation Area (NTA) level" v:attribution="Department of City Planning (DCP)"

property e:rnsn-acs2 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:rnsn-acs2 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | geographic_area_borough | geographic_area_2010_census_fips_county_code | geographic_area_neighborhood_tabulation_area_nta_code | geographic_area_neighborhood_tabulation_area_nta_name | total_population_2000_number | total_population_2010_number | total_population_change_2000_2010_number | total_population_change_2000_2010_percent | 
| =========== | ======================= | ============================================ | ===================================================== | ===================================================== | ============================ | ============================ | ======================================== | ========================================= | 
| 1424162541  | Bronx                   | 5                                            | BX01                                                  | Claremont-Bathgate                                    | 28149                        | 31078                        | 2929                                     | 10.4                                      | 
| 1424162541  | Bronx                   | 5                                            | BX03                                                  | Eastchester-Edenwald-Baychester                       | 35422                        | 34517                        | -905                                     | -2.6                                      | 
| 1424162541  | Bronx                   | 5                                            | BX05                                                  | Bedford Park-Fordham North                            | 55329                        | 54415                        | -914                                     | -1.7                                      | 
| 1424162541  | Bronx                   | 5                                            | BX06                                                  | Belmont                                               | 25967                        | 27378                        | 1411                                     | 5.4                                       | 
| 1424162541  | Bronx                   | 5                                            | BX07                                                  | Bronxdale                                             | 34309                        | 35538                        | 1229                                     | 3.6                                       | 
| 1424162541  | Bronx                   | 5                                            | BX08                                                  | West Farms-Bronx River                                | 34542                        | 35011                        | 469                                      | 1.4                                       | 
| 1424162541  | Bronx                   | 5                                            | BX09                                                  | Soundview-Castle Hill-Clason Point-Harding Park       | 50753                        | 53686                        | 2933                                     | 5.8                                       | 
| 1424162541  | Bronx                   | 5                                            | BX10                                                  | Pelham Bay-Country Club-City Island                   | 27140                        | 26583                        | -557                                     | -2.1                                      | 
| 1424162541  | Bronx                   | 5                                            | BX13                                                  | Co-Op City                                            | 40676                        | 43752                        | 3076                                     | 7.6                                       | 
| 1424162541  | Bronx                   | 5                                            | BX14                                                  | East Concourse-Concourse Village                      | 58961                        | 62284                        | 3323                                     | 5.6                                       | 
```