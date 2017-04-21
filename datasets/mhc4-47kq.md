# ODA Pesticide Applicator Licenses

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/oda-pesticide-applicator-licenses-cca2d) |
| Metadata | [Link](https://data.oregon.gov/api/views/mhc4-47kq) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/mhc4-47kq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/mhc4-47kq/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | mhc4-47kq |
| Name | ODA Pesticide Applicator Licenses |
| Attribution | Oregon Department of Agriculture |
| Category | Natural Resources |
| Tags | license, pesticide |
| Created | 2014-03-26T22:39:43Z |
| Publication Date | 2014-03-26T22:41:12Z |

## Description

Status information for persons holding any type of pesticide applicator license from the Oregon Department of Agriculture.

## Columns

```ls
| Included | Schema Type | Field Name     | Name           | Data Type     | Render Type   |
| ======== | =========== | ============== | ============== | ============= | ============= |
| Yes      | series tag  | name           | Name           | text          | text          |
| Yes      | series tag  | city           | City           | text          | text          |
| Yes      | series tag  | state          | State          | text          | text          |
| Yes      | series tag  | zip            | Zip            | text          | text          |
| Yes      | series tag  | county_country | County-Country | text          | text          |
| Yes      | series tag  | licensenum     | LicenseNum     | text          | text          |
| Yes      | series tag  | licensetype    | LicenseType    | text          | text          |
| Yes      | series tag  | licensestatus  | LicenseStatus  | text          | text          |
| Yes      | time        | expirationdate | ExpirationDate | calendar_date | calendar_date |
| Yes      | series tag  | categories     | Categories     | text          | text          |
```

## Time Field

```ls
Value = expirationdate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:mhc4-47kq d:2017-12-31T00:00:00.000Z t:zip=97850 t:county_country=Union t:licensestatus=Active t:licensenum=AG-L0109374CPA t:name="RICHARD D GOODRICK" t:state=OR t:categories="Ornamental & Turf; Ornamental & Turf - Insecticide & Fungicide; Ornamental & Turf - Herbicide" t:licensetype="Commercial Pesticide Applicator" t:city="LA GRANDE" m:row_number.mhc4-47kq=1

series e:mhc4-47kq d:2007-12-31T00:00:00.000Z t:zip=97630 t:county_country=Lake t:licensestatus=Inactive t:licensenum=AG-L0109381CPA t:name="FREDRICK J BAGLEY" t:state=OR t:categories="Industrial, Institutional, Health & Struct. (IIHS); IIHS - Structural Pests" t:licensetype="Commercial Pesticide Applicator" t:city=LAKEVIEW m:row_number.mhc4-47kq=2

series e:mhc4-47kq d:2016-12-31T00:00:00.000Z t:zip=97701 t:county_country=Deschutes t:licensestatus=Inactive t:licensenum=AG-L0109393CPA t:name="DOUG W FEHER" t:state=OR t:categories="Ornamental & Turf; Ornamental & Turf - Herbicide; Agriculture; Agriculture - Insecticide & Fungicide" t:licensetype="Commercial Pesticide Applicator" t:city=BEND m:row_number.mhc4-47kq=3
```

## Meta Commands

```ls
metric m:row_number.mhc4-47kq p:long l:"Row Number"

entity e:mhc4-47kq l:"ODA Pesticide Applicator Licenses" t:attribution="Oregon Department of Agriculture" t:url=https://data.oregon.gov/api/views/mhc4-47kq

property e:mhc4-47kq t:meta.view v:id=mhc4-47kq v:category="Natural Resources" v:attributionLink=http://oda.state.or.us v:averageRating=0 v:name="ODA Pesticide Applicator Licenses" v:attribution="Oregon Department of Agriculture"

property e:mhc4-47kq t:meta.view.owner v:id=sugd-sgpc v:screenName="ODA Job Scheduler" v:displayName="ODA Job Scheduler"

property e:mhc4-47kq t:meta.view.tableauthor v:id=sugd-sgpc v:screenName="ODA Job Scheduler" v:roleName=editor v:displayName="ODA Job Scheduler"
```

## Top Records

```ls
| name                    | city        | state | zip   | county_country | licensenum     | licensetype                     | licensestatus | expirationdate      | categories                                                                                                   | 
| ======================= | =========== | ===== | ===== | ============== | ============== | =============================== | ============= | =================== | ============================================================================================================ | 
| RICHARD D GOODRICK      | LA GRANDE   | OR    | 97850 | Union          | AG-L0109374CPA | Commercial Pesticide Applicator | Active        | 2017-12-31T00:00:00 | Ornamental & Turf; Ornamental & Turf - Insecticide & Fungicide; Ornamental & Turf - Herbicide                | 
| FREDRICK J BAGLEY       | LAKEVIEW    | OR    | 97630 | Lake           | AG-L0109381CPA | Commercial Pesticide Applicator | Inactive      | 2007-12-31T00:00:00 | Industrial, Institutional, Health & Struct. (IIHS); IIHS - Structural Pests                                  | 
| DOUG W FEHER            | BEND        | OR    | 97701 | Deschutes      | AG-L0109393CPA | Commercial Pesticide Applicator | Inactive      | 2016-12-31T00:00:00 | Ornamental & Turf; Ornamental & Turf - Herbicide; Agriculture; Agriculture - Insecticide & Fungicide         | 
| PATRICE D ENGELKING     | IMNAHA      | OR    | 97842 | Wallowa        | AG-L0158849CPA | Commercial Pesticide Applicator | Inactive      | 2009-12-31T00:00:00 | Agriculture - Herbicide; Agriculture                                                                         | 
| LORI L MCMURPHY         | LAKE OSWEGO | OR    | 97035 | Clackamas      | AG-L0158850CPA | Commercial Pesticide Applicator | Inactive      | 2005-12-31T00:00:00 | Ornamental & Turf - Herbicide; Ornamental & Turf - Insecticide & Fungicide; Ornamental & Turf                | 
| MICHAEL A VANDERSCHUERE | PORTLAND    | OR    | 97206 | Multnomah      | AG-L0158851CPA | Commercial Pesticide Applicator | Inactive      | 2006-12-31T00:00:00 | Ornamental & Turf - Herbicide; Ornamental & Turf - Insecticide & Fungicide; Ornamental & Turf                | 
| JAMES E COGHILL JR      | MEDFORD     | OR    | 97501 | Jackson        | AG-L0158853CPA | Commercial Pesticide Applicator | Inactive      | 2006-12-31T00:00:00 | Right of Way; Ornamental & Turf - Herbicide; Ornamental & Turf - Insecticide & Fungicide; Ornamental & Turf  | 
| MICHAEL J BAYBADO I     | COVE        | OR    | 97824 | Union          | AG-L0174893CPA | Commercial Pesticide Applicator | Inactive      | 2015-12-31T00:00:00 | Forest; Agriculture; Agriculture - Herbicide; Right of Way; Ornamental & Turf; Ornamental & Turf - Herbicide | 
| BRIEN T DALLAS          | MEDFORD     | OR    | 97501 | Jackson        | AG-L0158855CPA | Commercial Pesticide Applicator | Inactive      | 2006-12-31T00:00:00 | Ornamental & Turf - Herbicide; Ornamental & Turf - Insecticide & Fungicide; Ornamental & Turf; Right of Way  | 
| GARY L FUHRER           | MEDFORD     | OR    | 97501 | Jackson        | AG-L0158856CPA | Commercial Pesticide Applicator | Inactive      | 2006-12-31T00:00:00 | Ornamental & Turf - Herbicide; Ornamental & Turf - Insecticide & Fungicide; Ornamental & Turf; Right of Way  | 
```