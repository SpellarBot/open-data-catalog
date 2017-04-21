# Table 15: Oil and Chemical Releases

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/table-15-oil-and-chemical-releases-aa2e9) |
| Metadata | [Link](https://data.hawaii.gov/api/views/yqmp-94ap) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/yqmp-94ap/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/yqmp-94ap/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | yqmp-94ap |
| Name | Table 15: Oil and Chemical Releases |
| Attribution | DOH |
| Category | Health |
| Tags | oil, chemical, releases |
| Created | 2012-08-01T00:12:58Z |
| Publication Date | 2012-08-01T00:13:58Z |

## Description

DOH Environmental Indicators

## Columns

```ls
| Included | Schema Type    | Field Name                                         | Name                                                 | Data Type | Render Type |
| ======== | ============== | ================================================== | ==================================================== | ========= | =========== |
| No       |                | _                                                  | #                                                    | number    | number      |
| Yes      | time           | calendar_year                                      | Calendar Year                                        | number    | text        |
| Yes      | numeric metric | oil_releases_to_land                               | Oil Releases to Land                                 | number    | number      |
| Yes      | numeric metric | oil_releases_to_water                              | Oil Releases to Water                                | number    | number      |
| Yes      | numeric metric | total_oil_releases                                 | Total Oil Releases                                   | number    | number      |
| Yes      | numeric metric | chemical_releases_to_water                         | Chemical Releases to Water                           | number    | number      |
| Yes      | numeric metric | chemical_releases_to_land                          | Chemical Releases to Land                            | number    | number      |
| Yes      | numeric metric | total_chemical_releases                            | Total Chemical Releases                              | number    | number      |
| Yes      | numeric metric | total_chemical_releasestotal_oil_chemical_releases | Total Chemical ReleasesTotal Oil & Chemical Releases | number    | number      |
```

## Time Field

```ls
Value = calendar_year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = _
```

## Data Commands

```ls
series e:yqmp-94ap d:2006-01-01T00:00:00.000Z m:total_oil_releases=206 m:total_chemical_releases=178 m:total_chemical_releasestotal_oil_chemical_releases=384

series e:yqmp-94ap d:2007-01-01T00:00:00.000Z m:total_oil_releases=289 m:total_chemical_releases=200 m:total_chemical_releasestotal_oil_chemical_releases=489

series e:yqmp-94ap d:2008-01-01T00:00:00.000Z m:total_oil_releases=198 m:total_chemical_releases=107 m:total_chemical_releasestotal_oil_chemical_releases=305
```

## Meta Commands

```ls
metric m:oil_releases_to_land p:integer l:"Oil Releases to Land" t:dataTypeName=number

metric m:oil_releases_to_water p:integer l:"Oil Releases to Water" t:dataTypeName=number

metric m:total_oil_releases p:integer l:"Total Oil Releases" t:dataTypeName=number

metric m:chemical_releases_to_water p:integer l:"Chemical Releases to Water" t:dataTypeName=number

metric m:chemical_releases_to_land p:integer l:"Chemical Releases to Land" t:dataTypeName=number

metric m:total_chemical_releases p:integer l:"Total Chemical Releases" t:dataTypeName=number

metric m:total_chemical_releasestotal_oil_chemical_releases p:integer l:"Total Chemical ReleasesTotal Oil & Chemical Releases" t:dataTypeName=number

entity e:yqmp-94ap l:"Table 15: Oil and Chemical Releases" t:attribution=DOH t:url=https://data.hawaii.gov/api/views/yqmp-94ap

property e:yqmp-94ap t:meta.view v:id=yqmp-94ap v:category=Health v:attributionLink=http://hawaii.gov/doh v:averageRating=0 v:name="Table 15: Oil and Chemical Releases" v:attribution=DOH

property e:yqmp-94ap t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:yqmp-94ap t:meta.view.owner v:id=8c9u-vteh v:screenName=lorrink v:displayName=lorrink

property e:yqmp-94ap t:meta.view.tableauthor v:id=8c9u-vteh v:screenName=lorrink v:roleName=editor v:displayName=lorrink
```

## Top Records

```ls
| _ | calendar_year | oil_releases_to_land | oil_releases_to_water | total_oil_releases | chemical_releases_to_water | chemical_releases_to_land | total_chemical_releases | total_chemical_releasestotal_oil_chemical_releases | 
| = | ============= | ==================== | ===================== | ================== | ========================== | ========================= | ======================= | ================================================== | 
| 1 | 2006          |                      |                       | 206                |                            |                           | 178                     | 384                                                | 
| 2 | 2007          |                      |                       | 289                |                            |                           | 200                     | 489                                                | 
| 4 | 2008          |                      |                       | 198                |                            |                           | 107                     | 305                                                | 
| 5 | 2009          | 56                   | 87                    | 143                | 62                         | 63                        | 125                     | 268                                                | 
| 6 | 2010          | 126                  | 92                    | 218                | 65                         | 131                       | 196                     | 414                                                | 
```