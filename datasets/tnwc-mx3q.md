# Parcel Counts By Type By Municipality: Beginning Roll Year 2000

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/parcel-counts-by-type-by-municipality-beginning-roll-year-2000) |
| Metadata | [Link](https://data.ny.gov/api/views/tnwc-mx3q) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/tnwc-mx3q/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/tnwc-mx3q/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | tnwc-mx3q |
| Name | Parcel Counts By Type By Municipality: Beginning Roll Year 2000 |
| Attribution | Office of Tax Policy Analysis |
| Category | Government & Finance |
| Tags | parcels, property class, distribution |
| Created | 2013-02-26T23:11:59Z |
| Publication Date | 2017-04-13T22:01:27Z |

## Description

The Department of Taxation and Finance annually produces a report pertaining to the distribution of parcels by property class.  The data analysis involves a breakdown of property classes to nine segments of broad use, namely Agricultural, Residential, Vacant Land/Farm, Commercial, Recreation, Community Service, Industrial, Public Service, and Forest/Conservation. For more information please go to:  http://www.tax.ny.gov/research/property/default.htm

## Columns

```ls
| Included | Schema Type    | Field Name                                           | Name                                                   | Data Type | Render Type |
| ======== | ============== | ==================================================== | ====================================================== | ========= | =========== |
| Yes      | time           | roll_year                                            | Roll Year                                              | number    | number      |
| Yes      | series tag     | swis_code                                            | Swis Code                                              | text      | text        |
| Yes      | series tag     | municipality_name                                    | Municipality Name                                      | text      | text        |
| Yes      | series tag     | county_name                                          | County Name                                            | text      | text        |
| Yes      | numeric metric | broad_use_100_agricultural_property_count            | Broad Use 100 - Agricultural Property Count            | number    | number      |
| Yes      | numeric metric | broad_use_200_residential_property_count             | Broad Use 200 - Residential Property Count             | number    | number      |
| Yes      | numeric metric | broad_use_300_vacant_land_property_count             | Broad Use 300 - Vacant Land Property Count             | number    | number      |
| Yes      | numeric metric | broad_use_400_commercial_property_count              | Broad Use 400 - Commercial Property Count              | number    | number      |
| Yes      | numeric metric | broad_use_500_recreation_property_count              | Broad Use 500 - Recreation Property Count              | number    | number      |
| Yes      | numeric metric | broad_use_600_community_service_property_count       | Broad Use 600 - Community Service Property Count       | number    | number      |
| Yes      | numeric metric | broad_use_700_industrial_property_count              | Broad Use 700 - Industrial Property Count              | number    | number      |
| Yes      | numeric metric | broad_use_800_public_service_property_count          | Broad Use 800 - Public Service Property Count          | number    | number      |
| Yes      | numeric metric | broad_use_900_forest_and_conservation_property_count | Broad Use 900 - Forest and Conservation Property Count | number    | number      |
| Yes      | numeric metric | total_parcel_count                                   | Total Parcel Count                                     | number    | number      |
```

## Time Field

```ls
Value = roll_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:tnwc-mx3q d:2011-01-01T00:00:00.000Z t:municipality_name=Albany t:swis_code=010100 t:county_name=Albany m:broad_use_700_industrial_property_count=28 m:broad_use_900_forest_and_conservation_property_count=102 m:broad_use_500_recreation_property_count=83 m:broad_use_400_commercial_property_count=3787 m:total_parcel_count=30076 m:broad_use_100_agricultural_property_count=0 m:broad_use_800_public_service_property_count=166 m:broad_use_200_residential_property_count=21324 m:broad_use_300_vacant_land_property_count=4009 m:broad_use_600_community_service_property_count=577

series e:tnwc-mx3q d:2011-01-01T00:00:00.000Z t:municipality_name=Cohoes t:swis_code=010300 t:county_name=Albany m:broad_use_700_industrial_property_count=10 m:broad_use_900_forest_and_conservation_property_count=38 m:broad_use_500_recreation_property_count=12 m:broad_use_400_commercial_property_count=569 m:total_parcel_count=5274 m:broad_use_100_agricultural_property_count=1 m:broad_use_800_public_service_property_count=43 m:broad_use_200_residential_property_count=3794 m:broad_use_300_vacant_land_property_count=738 m:broad_use_600_community_service_property_count=69

series e:tnwc-mx3q d:2011-01-01T00:00:00.000Z t:municipality_name=Watervliet t:swis_code=011800 t:county_name=Albany m:broad_use_700_industrial_property_count=13 m:broad_use_900_forest_and_conservation_property_count=0 m:broad_use_500_recreation_property_count=18 m:broad_use_400_commercial_property_count=290 m:total_parcel_count=2822 m:broad_use_100_agricultural_property_count=0 m:broad_use_800_public_service_property_count=25 m:broad_use_200_residential_property_count=2322 m:broad_use_300_vacant_land_property_count=108 m:broad_use_600_community_service_property_count=46
```

## Meta Commands

```ls
metric m:broad_use_100_agricultural_property_count p:integer l:"Broad Use 100 - Agricultural Property Count" d:"Count of agricultural parcels in municipality" t:dataTypeName=number

metric m:broad_use_200_residential_property_count p:integer l:"Broad Use 200 - Residential Property Count" d:"Count of residential parcels in municipality" t:dataTypeName=number

metric m:broad_use_300_vacant_land_property_count p:integer l:"Broad Use 300 - Vacant Land Property Count" d:"Count of vacant land parcels in municipality" t:dataTypeName=number

metric m:broad_use_400_commercial_property_count p:integer l:"Broad Use 400 - Commercial Property Count" d:"Count of commercial parcels in municipality" t:dataTypeName=number

metric m:broad_use_500_recreation_property_count p:integer l:"Broad Use 500 - Recreation Property Count" d:"Count of recreation parcels in municipality" t:dataTypeName=number

metric m:broad_use_600_community_service_property_count p:integer l:"Broad Use 600 - Community Service Property Count" d:"Count of community service parcels in municipality" t:dataTypeName=number

metric m:broad_use_700_industrial_property_count p:integer l:"Broad Use 700 - Industrial Property Count" d:"Count of industrial parcels in municipality" t:dataTypeName=number

metric m:broad_use_800_public_service_property_count p:integer l:"Broad Use 800 - Public Service Property Count" d:"Count of public service parcels in municipality" t:dataTypeName=number

metric m:broad_use_900_forest_and_conservation_property_count p:integer l:"Broad Use 900 - Forest and Conservation Property Count" d:"Count of forest and conservation parcels in municipality" t:dataTypeName=number

metric m:total_parcel_count p:integer l:"Total Parcel Count" d:"Total parcel count in municipality" t:dataTypeName=number

entity e:tnwc-mx3q l:"Parcel Counts By Type By Municipality: Beginning Roll Year 2000" t:attribution="Office of Tax Policy Analysis" t:url=https://data.ny.gov/api/views/tnwc-mx3q

property e:tnwc-mx3q t:meta.view v:id=tnwc-mx3q v:category="Government & Finance" v:attributionLink=http://www.tax.ny.gov/pubs_and_bulls/orpts/publications/reports_annual.htm v:averageRating=0 v:name="Parcel Counts By Type By Municipality: Beginning Roll Year 2000" v:attribution="Office of Tax Policy Analysis"

property e:tnwc-mx3q t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:tnwc-mx3q t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:tnwc-mx3q t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| roll_year | swis_code | municipality_name | county_name | broad_use_100_agricultural_property_count | broad_use_200_residential_property_count | broad_use_300_vacant_land_property_count | broad_use_400_commercial_property_count | broad_use_500_recreation_property_count | broad_use_600_community_service_property_count | broad_use_700_industrial_property_count | broad_use_800_public_service_property_count | broad_use_900_forest_and_conservation_property_count | total_parcel_count | 
| ========= | ========= | ================= | =========== | ========================================= | ======================================== | ======================================== | ======================================= | ======================================= | ============================================== | ======================================= | =========================================== | ==================================================== | ================== | 
| 2011      | 010100    | Albany            | Albany      | 0                                         | 21324                                    | 4009                                     | 3787                                    | 83                                      | 577                                            | 28                                      | 166                                         | 102                                                  | 30076              | 
| 2011      | 010300    | Cohoes            | Albany      | 1                                         | 3794                                     | 738                                      | 569                                     | 12                                      | 69                                             | 10                                      | 43                                          | 38                                                   | 5274               | 
| 2011      | 011800    | Watervliet        | Albany      | 0                                         | 2322                                     | 108                                      | 290                                     | 18                                      | 46                                             | 13                                      | 25                                          | 0                                                    | 2822               | 
| 2011      | 012000    | Berne             | Albany      | 51                                        | 1279                                     | 459                                      | 33                                      | 150                                     | 39                                             | 2                                       | 34                                          | 29                                                   | 2076               | 
| 2011      | 012200    | Bethlehem         | Albany      | 78                                        | 10848                                    | 1501                                     | 609                                     | 23                                      | 102                                            | 29                                      | 161                                         | 17                                                   | 13368              | 
| 2011      | 012400    | Coeymans          | Albany      | 21                                        | 2156                                     | 584                                      | 155                                     | 15                                      | 41                                             | 23                                      | 78                                          | 2                                                    | 3075               | 
| 2011      | 012600    | Colonie           | Albany      | 15                                        | 25717                                    | 3162                                     | 1920                                    | 77                                      | 189                                            | 38                                      | 238                                         | 0                                                    | 31356              | 
| 2011      | 012800    | Green Island      | Albany      | 0                                         | 579                                      | 99                                       | 123                                     | 10                                      | 11                                             | 13                                      | 26                                          | 7                                                    | 868                | 
| 2011      | 013000    | Guilderland       | Albany      | 109                                       | 10426                                    | 1088                                     | 413                                     | 38                                      | 130                                            | 4                                       | 144                                         | 194                                                  | 12546              | 
| 2011      | 013200    | Knox              | Albany      | 111                                       | 966                                      | 404                                      | 15                                      | 5                                       | 15                                             | 1                                       | 28                                          | 12                                                   | 1557               | 
```