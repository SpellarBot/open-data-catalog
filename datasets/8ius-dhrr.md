# 2010 Census Tract to Neighborhood Tabulation Area Equivalency table

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2010-census-tract-to-neighborhood-tabulation-area-equivalency-table) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/8ius-dhrr) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/8ius-dhrr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/8ius-dhrr/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 8ius-dhrr |
| Name | 2010 Census Tract to Neighborhood Tabulation Area Equivalency table |
| Attribution | Department of City Planning (DCP) |
| Category | City Government |
| Tags | census, planyc |
| Created | 2015-02-17T16:34:48Z |
| Publication Date | 2015-02-17T16:36:07Z |

## Description

Excel table of census data created to project populations at the Neighborhood Tabulation Area, a small area level, from 2000 to 2030 for PlaNYC, the long-term sustainability plan for New York City

## Columns

```ls
| Included | Schema Type    | Field Name                            | Name                                    | Data Type | Render Type |
| ======== | ============== | ===================================== | ======================================= | ========= | =========== |
| Yes      | series tag     | borough                               | Borough                                 | text      | text        |
| Yes      | series tag     | 2010_census_bureau_fips_county_code   | 2010 Census Bureau FIPS County Code     | text      | number      |
| Yes      | series tag     | 2010_nyc_borough_code                 | 2010 NYC Borough Code                   | text      | number      |
| Yes      | numeric metric | 2010_census_tract                     | 2010 Census Tract                       | number    | number      |
| Yes      | numeric metric | puma                                  | PUMA                                    | number    | number      |
| Yes      | series tag     | neighborhood_tabulation_area_nta_code | Neighborhood Tabulation Area (NTA)Code  | text      | text        |
| Yes      | series tag     | neighborhood_tabulation_area_nta_name | Neighborhood Tabulation Area (NTA) Name | text      | text        |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:8ius-dhrr d:2010-01-01T00:00:00.000Z t:2010_nyc_borough_code=2 t:neighborhood_tabulation_area_nta_name="Allerton-Pelham Gardens" t:neighborhood_tabulation_area_nta_code=BX31 t:borough=Bronx t:2010_census_bureau_fips_county_code=5 m:2010_census_tract=31000 m:puma=3704

series e:8ius-dhrr d:2010-01-01T00:00:00.000Z t:2010_nyc_borough_code=2 t:neighborhood_tabulation_area_nta_name="Allerton-Pelham Gardens" t:neighborhood_tabulation_area_nta_code=BX31 t:borough=Bronx t:2010_census_bureau_fips_county_code=5 m:2010_census_tract=31200 m:puma=3704

series e:8ius-dhrr d:2010-01-01T00:00:00.000Z t:2010_nyc_borough_code=2 t:neighborhood_tabulation_area_nta_name="Allerton-Pelham Gardens" t:neighborhood_tabulation_area_nta_code=BX31 t:borough=Bronx t:2010_census_bureau_fips_county_code=5 m:2010_census_tract=31400 m:puma=3704
```

## Meta Commands

```ls
metric m:2010_census_tract p:integer l:"2010 Census Tract" t:dataTypeName=number

metric m:puma p:integer l:PUMA t:dataTypeName=number

entity e:8ius-dhrr l:"2010 Census Tract to Neighborhood Tabulation Area Equivalency table" t:attribution="Department of City Planning (DCP)" t:url=https://data.cityofnewyork.us/api/views/8ius-dhrr

property e:8ius-dhrr t:meta.view v:id=8ius-dhrr v:category="City Government" v:averageRating=0 v:name="2010 Census Tract to Neighborhood Tabulation Area Equivalency table" v:attribution="Department of City Planning (DCP)"

property e:8ius-dhrr t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:8ius-dhrr t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| borough | 2010_census_bureau_fips_county_code | 2010_nyc_borough_code | 2010_census_tract | puma | neighborhood_tabulation_area_nta_code | neighborhood_tabulation_area_nta_name | 
| ======= | =================================== | ===================== | ================= | ==== | ===================================== | ===================================== | 
| Bronx   | 5                                   | 2                     | 31000             | 3704 | BX31                                  | Allerton-Pelham Gardens               | 
| Bronx   | 5                                   | 2                     | 31200             | 3704 | BX31                                  | Allerton-Pelham Gardens               | 
| Bronx   | 5                                   | 2                     | 31400             | 3704 | BX31                                  | Allerton-Pelham Gardens               | 
| Bronx   | 5                                   | 2                     | 31600             | 3704 | BX31                                  | Allerton-Pelham Gardens               | 
| Bronx   | 5                                   | 2                     | 31800             | 3704 | BX31                                  | Allerton-Pelham Gardens               | 
| Bronx   | 5                                   | 2                     | 32600             | 3704 | BX31                                  | Allerton-Pelham Gardens               | 
| Bronx   | 5                                   | 2                     | 34200             | 3704 | BX31                                  | Allerton-Pelham Gardens               | 
| Bronx   | 5                                   | 2                     | 34400             | 3704 | BX31                                  | Allerton-Pelham Gardens               | 
| Bronx   | 5                                   | 2                     | 34800             | 3704 | BX31                                  | Allerton-Pelham Gardens               | 
| Bronx   | 5                                   | 2                     | 35000             | 3704 | BX31                                  | Allerton-Pelham Gardens               | 
```