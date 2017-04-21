# Haulers Licensed by City of Austin

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/haulers-licensed-by-city-of-austin) |
| Metadata | [Link](https://data.austintexas.gov/api/views/qe89-agqj) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/qe89-agqj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/qe89-agqj/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | qe89-agqj |
| Name | Haulers Licensed by City of Austin |
| Attribution | City of Austin, Code Department |
| Category | Public Safety |
| Tags | private, waste, recycling, hauler, garbage, trash, compost, organic, license, austin code |
| Created | 2014-11-06T19:42:33Z |
| Publication Date | 2017-04-13T19:55:04Z |

## Description

Licensed Waste, Recycling, and/or Compost/Organic Haulers. The City of Austin does not endorse any particular company, rather, we provide these lists as an informational resource.

## Columns

```ls
| Included | Schema Type | Field Name     | Name           | Data Type | Render Type |
| ======== | =========== | ============== | ============== | ========= | =========== |
| No       | time        | :updated_at    | updated_at     | meta_data | meta_data   |
| Yes      | series tag  | type_of_hauler | Type of Hauler | text      | text        |
| Yes      | series tag  | name_of_hauler | Name of Hauler | text      | text        |
| Yes      | series tag  | phone          | Phone          | text      | text        |
| Yes      | series tag  | website        | Website        | url       | url         |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:qe89-agqj d:2015-05-13T07:33:16.000Z t:phone=512-515-0705 t:website=http://www.absolutedemolition.com/ t:type_of_hauler="Landfill, Recycle" t:name_of_hauler="Absolute Demolition" m:row_number.qe89-agqj=1

series e:qe89-agqj d:2015-05-13T07:33:16.000Z t:phone="512-259-7430
FAX 512-259-6482" t:website=http://www.austinwoodrecycling.com/ t:type_of_hauler="Landfill, Recycle" t:name_of_hauler="Austin Wood Recycling / S&M Business / 
Austin Land Services" m:row_number.qe89-agqj=2

series e:qe89-agqj d:2015-05-13T07:33:16.000Z t:phone="512-442-2384
FAX 512-442-2384" t:website=https://www.cmc.com/ t:type_of_hauler=Recycle t:name_of_hauler="CMC Metal Recycling" m:row_number.qe89-agqj=3
```

## Meta Commands

```ls
metric m:row_number.qe89-agqj p:long l:"Row Number"

entity e:qe89-agqj l:"Haulers Licensed by City of Austin" t:attribution="City of Austin, Code Department" t:url=https://data.austintexas.gov/api/views/qe89-agqj

property e:qe89-agqj t:meta.view v:id=qe89-agqj v:category="Public Safety" v:attributionLink=http://austintexas.gov/code v:averageRating=0 v:name="Haulers Licensed by City of Austin" v:attribution="City of Austin, Code Department"

property e:qe89-agqj t:meta.view.license v:name="Public Domain"

property e:qe89-agqj t:meta.view.owner v:id=vesy-2din v:screenName="Mark Wensel" v:displayName="Mark Wensel"

property e:qe89-agqj t:meta.view.tableauthor v:id=vesy-2din v:screenName="Mark Wensel" v:roleName=editor v:displayName="Mark Wensel"
```

## Top Records

```ls
| :updated_at | type_of_hauler    | name_of_hauler                                              | phone                         | website                                                                        | 
| =========== | ================= | =========================================================== | ============================= | ============================================================================== | 
| 1431502396  | Landfill, Recycle | Absolute Demolition                                         | 512-515-0705                  | [http://www.absolutedemolition.com/, null]                                     | 
| 1431502396  | Landfill, Recycle | Austin Wood Recycling / S&M Business / Austin Land Services | 512-259-7430 FAX 512-259-6482 | [http://www.austinwoodrecycling.com/, null]                                    | 
| 1431502396  | Recycle           | CMC Metal Recycling                                         | 512-442-2384 FAX 512-442-2384 | [https://www.cmc.com/, null]                                                   | 
| 1431502396  | Recycle           | Gardner Iron & Metal / Gardner Metal Recycling              | 512-292-1022 FAX 512-291-1049 | [http://www.gardnermetals.com/, null]                                          | 
| 1431502396  | Recycle           | Hook'em Rolloff / Legacy Land Development                   | 512-751-8864 FAX 512-345-9588 | [null, null]                                                                   | 
| 1431502396  | Landfill          | Landmarc Contractors                                        | 512-844-1081                  | [null, null]                                                                   | 
| 1431502396  | Landfill          | Lossen Bros Co, Inc                                         | 512-845-3076                  | [null, null]                                                                   | 
| 1431502396  | Compost           | Organics by Gosh / Employee Owned Nursery Enterprises, Ltd  | 512-276-1211 FAX 512-276-9165 | [http://www.organicsbygosh.com/, null]                                         | 
| 1431502396  | Landfill, Recycle | Republic Services/Allied Waste                              | 512-247-5647                  | [http://site.republicservices.com/site/austin-tx/en/pages/location.aspx, null] | 
| 1431502396  | Landfill          | Rubbish, Inc                                                | 512-298-5445                  | [http://www.rubbish-inc.com/, null]                                            | 
```