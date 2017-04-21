# Locations of HOC Offices

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/locations-of-hoc-offices-9ebc4) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/7nik-bq7n) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/7nik-bq7n/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/7nik-bq7n/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | 7nik-bq7n |
| Name | Locations of HOC Offices |
| Category | Consumer/Housing |
| Tags | housing, opportunities, commission, hoc, locations |
| Created | 2014-03-12T19:49:59Z |
| Publication Date | 2014-10-21T17:47:53Z |

## Description

Office Locations for the Housing Opportunities Commission (HOC) of Montgomery County. Source: HOC

## Columns

```ls
| Included | Schema Type | Field Name     | Name           | Data Type | Render Type |
| ======== | =========== | ============== | ============== | ========= | =========== |
| No       | time        | :updated_at    | updated_at     | meta_data | meta_data   |
| Yes      | series tag  | office_type    | Office Type    | text      | text        |
| Yes      | series tag  | property       | Property       | text      | text        |
| Yes      | series tag  | email          | Email          | text      | text        |
| Yes      | series tag  | phone          | Phone          | text      | text        |
| Yes      | series tag  | city           | City           | text      | text        |
| Yes      | series tag  | state          | State          | text      | text        |
| Yes      | series tag  | zip            | Zip            | text      | number      |
| Yes      | series tag  | street_address | Street Address | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:7nik-bq7n d:2014-10-21T10:47:24.000Z t:zip=20850 t:phone="(301) 424-5450" t:email=towncenter@hocmc.org t:office_type=HUB t:state=MD t:property="Town Center (Rockville)" t:street_address="90 Monroe Street" t:city=Rockville m:row_number.7nik-bq7n=1

series e:7nik-bq7n d:2014-10-21T10:47:24.000Z t:zip=20877 t:phone="(301) 948-1882" t:email=emorygrove@hocmc.org t:office_type=HUB t:state=MD t:property="Emory Grove" t:street_address="8107 Morning View Drive" t:city=Gaithersburg m:row_number.7nik-bq7n=2

series e:7nik-bq7n d:2014-10-21T10:47:24.000Z t:zip=20817 t:phone="(301) 365-7251" t:email=magruders@hocmc.org t:office_type=HUB t:state=MD t:property="Magruders Discovery" t:street_address="10508 Westlake Drive" t:city=Bethesda m:row_number.7nik-bq7n=3
```

## Meta Commands

```ls
metric m:row_number.7nik-bq7n p:long l:"Row Number"

entity e:7nik-bq7n l:"Locations of HOC Offices" t:url=https://data.montgomerycountymd.gov/api/views/7nik-bq7n

property e:7nik-bq7n t:meta.view v:id=7nik-bq7n v:category=Consumer/Housing v:averageRating=0 v:name="Locations of HOC Offices"

property e:7nik-bq7n t:meta.view.owner v:id=qzhb-tftn v:screenName="Kathy Luh" v:displayName="Kathy Luh"

property e:7nik-bq7n t:meta.view.tableauthor v:id=qzhb-tftn v:screenName="Kathy Luh" v:roleName=administrator v:displayName="Kathy Luh"
```

## Top Records

```ls
| :updated_at | office_type                    | property                             | email                 | phone          | city          | state | zip   | street_address                 | 
| =========== | ============================== | ==================================== | ===================== | ============== | ============= | ===== | ===== | ============================== | 
| 1413888444  | HUB                            | Town Center (Rockville)              | towncenter@hocmc.org  | (301) 424-5450 | Rockville     | MD    | 20850 | 90 Monroe Street               | 
| 1413888444  | HUB                            | Emory Grove                          | emorygrove@hocmc.org  | (301) 948-1882 | Gaithersburg  | MD    | 20877 | 8107 Morning View Drive        | 
| 1413888444  | HUB                            | Magruders Discovery                  | magruders@hocmc.org   | (301) 365-7251 | Bethesda      | MD    | 20817 | 10508 Westlake Drive           | 
| 1413888444  | HUB                            | Seneca Ridge                         | senecaridge@hocmc.org | (240) 627-9772 | Germantown    | MD    | 20876 | 19568 Scenery Drive            | 
| 1413888444  | HUB                            | Waverly House                        | waverly@hocmc.org     | (301) 986-0052 | Bethesda      | MD    | 20814 | 4521 East-West Highway         | 
| 1413888444  | Service Center                 | Gaithersburg Customer Service Center | hrs@hocmc.org         | (240) 627-9792 | Gaithersburg  | MD    | 20877 | 101 Lakeforest Blvd., #200     | 
| 1413888444  | Headquarters                   | Main Office                          | hrs@hocmc.org         | (240) 627-9400 | Kensington    | MD    | 20895 | 10400 Detrick Avenue           | 
| 1413888444  | HUB                            | Arcola Towers                        | arcola@hocmc.org      | (301) 649-3590 | Silver Spring | MD    | 20902 | 1135 University Boulevard West | 
| 1413888444  | HUB                            | Towne Centre Place (Olney)           | tcpolney@hocmc.org    | (301) 774-1574 | Olney         | MD    | 20832 | 3502 Morningwood Drive         | 
| 1413888444  | Upcounty Administrative Office | East Deer Park                       | hrs@hocmc.org         | (240) 627-9744 | Gaithersburg  | MD    | 20877 | 231 East Deer Park Drive       | 
```