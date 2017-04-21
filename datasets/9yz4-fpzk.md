# IEMA Facilities with Radiation Producing Equipment

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/iema-facilities-with-radiation-producing-equipment-35b6d) |
| Metadata | [Link](https://data.illinois.gov/api/views/9yz4-fpzk) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/9yz4-fpzk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/9yz4-fpzk/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 9yz4-fpzk |
| Name | IEMA Facilities with Radiation Producing Equipment |
| Category | Social/Healthcare |
| Tags | facilities, radiation, x-ray, laser, health care |
| Created | 2011-09-29T18:11:08Z |
| Publication Date | 2011-10-21T21:04:30Z |

## Description

A list of all facilities that possess radiation producing machines such as x-ray and laser equipment.

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | admin       | ADMIN      | text      | text        |
| Yes      | series tag  | facility    | FACILITY   | text      | text        |
| Yes      | series tag  | category    | CATEGORY   | text      | text        |
| Yes      | series tag  | county      | COUNTY     | text      | text        |
| Yes      | series tag  | email       | EMAIL      | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:9yz4-fpzk d:2011-09-29T11:11:24.000Z t:category="Laser Light Show" t:facility="Laser Design Productions" t:email=victor@pyrotekfx.com t:county="Out Of State" t:admin="Mr. Douglas Adams" m:row_number.9yz4-fpzk=1

series e:9yz4-fpzk d:2011-09-29T11:11:26.000Z t:category="Laser only-Industrial" t:facility=Lasertech t:county=Lake t:admin="Michael F. Werner, Chief LSO" m:row_number.9yz4-fpzk=2

series e:9yz4-fpzk d:2011-09-29T11:11:26.000Z t:category="Veterinary Clinic" t:facility="Skycrest Animal Clinic" t:email=skycrestanimal@comcast.net t:county=Lake t:admin="Kristin K. Wojcik, D.V.M." m:row_number.9yz4-fpzk=3
```

## Meta Commands

```ls
metric m:row_number.9yz4-fpzk p:long l:"Row Number"

entity e:9yz4-fpzk l:"IEMA Facilities with Radiation Producing Equipment" t:url=https://data.illinois.gov/api/views/9yz4-fpzk

property e:9yz4-fpzk t:meta.view v:id=9yz4-fpzk v:category=Social/Healthcare v:averageRating=0 v:name="IEMA Facilities with Radiation Producing Equipment"

property e:9yz4-fpzk t:meta.view.owner v:id=fx6u-bzri v:screenName=Paul v:displayName=Paul

property e:9yz4-fpzk t:meta.view.tableauthor v:id=fx6u-bzri v:screenName=Paul v:roleName=publisher v:displayName=Paul
```

## Top Records

```ls
| :updated_at | admin                                    | facility                                  | category              | county       | email                      | 
| =========== | ======================================== | ========================================= | ===================== | ============ | ========================== | 
| 1317294684  | Mr. Douglas Adams                        | Laser Design Productions                  | Laser Light Show      | Out Of State | victor@pyrotekfx.com       | 
| 1317294686  | Michael F. Werner, Chief LSO             | Lasertech                                 | Laser only-Industrial | Lake         |                            | 
| 1317294686  | Kristin K. Wojcik, D.V.M.                | Skycrest Animal Clinic                    | Veterinary Clinic     | Lake         | skycrestanimal@comcast.net | 
| 1317294788  | James P. Ryan, D.D.S.                    | Ryan, James P., D.D.S.                    | Dentist               | Cook         |                            | 
| 1317294689  | Michele M. Crase, Associate Director EHS | Northern Illinois University              | School                | De Kalb      | dscharenberg@niu.edu       | 
| 1317294689  | Wayne O. Larson, D.V.M.                  | Kaneville Veterinary Service              | Veterinary Clinic     | Kane         |                            | 
| 1317294689  | Mark A. Thompson, D.V.M.                 | Dundee Animal Hospital of Elgin           | Veterinary Clinic     | Kane         |                            | 
| 1317294689  | Cynthia Charlier, DVM                    | Fox Valley Veterinary Dentistry & Surgery | Veterinary Clinic     | Kane         | ccharlier@sbcglobal.net    | 
| 1317294832  | Brian A. King, D.P.M.                    | King, Brian A., D.P.M.                    | Podiatrist            | Kane         |                            | 
| 1317294709  | Timothy E. Skidmore, D.D.S.              | Mill Creek Dental Care                    | Dental Clinic         | Kane         | drskidmore@mchsi.com       | 
```