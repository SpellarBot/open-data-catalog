# Justice Scholars Organization Information

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/justice-scholars-organization-information-9c840) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/69w5-fdhb) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/69w5-fdhb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/69w5-fdhb/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 69w5-fdhb |
| Name | Justice Scholars Organization Information |
| Attribution | Department of Probation (DOP) |
| Category | City Government |
| Tags | dop, probation, law, contact, justice, scholar |
| Created | 2013-02-12T18:02:31Z |
| Publication Date | 2013-06-21T20:08:07Z |

## Description

These are the address of Organizations providing Justice Scholars Programs

## Columns

```ls
| Included | Schema Type | Field Name                   | Name                         | Data Type | Render Type |
| ======== | =========== | ============================ | ============================ | ========= | =========== |
| No       | time        | :updated_at                  | updated_at                   | meta_data | meta_data   |
| Yes      | series tag  | justice_scholar_organization | Justice Scholar Organization | text      | text        |
| Yes      | series tag  | community_district_served    | Community District Served    | text      | text        |
| No       |             | address                      | Address                      | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:69w5-fdhb d:2013-02-12T10:02:32.000Z t:justice_scholar_organization="The Fortune Society" t:community_district_served="Bronx 1" m:row_number.69w5-fdhb=1

series e:69w5-fdhb d:2013-02-12T10:02:32.000Z t:justice_scholar_organization="The Fortune Society" t:community_district_served="Bronx 2" m:row_number.69w5-fdhb=2

series e:69w5-fdhb d:2013-02-12T10:02:32.000Z t:justice_scholar_organization="The Fortune Society" t:community_district_served="Bronx 3" m:row_number.69w5-fdhb=3
```

## Meta Commands

```ls
metric m:row_number.69w5-fdhb p:long l:"Row Number"

entity e:69w5-fdhb l:"Justice Scholars Organization  Information" t:attribution="Department of Probation (DOP)" t:url=https://data.cityofnewyork.us/api/views/69w5-fdhb

property e:69w5-fdhb t:meta.view v:id=69w5-fdhb v:category="City Government" v:attributionLink=http://www.nyc.gov/html/prob/html/young_men/yajc.shtml v:averageRating=0 v:name="Justice Scholars Organization  Information" v:attribution="Department of Probation (DOP)"

property e:69w5-fdhb t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:69w5-fdhb t:meta.view.tableauthor v:id=iacr-duv5 v:screenName=Tejas.Patel v:displayName=Tejas.Patel
```

## Top Records

```ls
| :updated_at | justice_scholar_organization | community_district_served | address                                          | 
| =========== | ============================ | ========================= | ================================================ | 
| 1360663352  | The Fortune Society          | Bronx 1                   | 29-76 Northern Blvd., Long Island City, NY 11101 | 
| 1360663352  | The Fortune Society          | Bronx 2                   | 29-76 Northern Blvd., Long Island City, NY 11101 | 
| 1360663352  | The Fortune Society          | Bronx 3                   | 29-76 Northern Blvd., Long Island City, NY 11101 | 
| 1360663352  | The Fortune Society          | Bronx 4                   | 29-76 Northern Blvd., Long Island City, NY 11101 | 
| 1360663352  | The Fortune Society          | Bronx 5                   | 29-76 Northern Blvd., Long Island City, NY 11101 | 
| 1360663352  | The Fortune Society          | Bronx 6                   | 29-76 Northern Blvd., Long Island City, NY 11101 | 
| 1360663352  | The Fortune Society          | Bronx 9                   | 29-76 Northern Blvd., Long Island City, NY 11101 | 
| 1360663352  | The Fortune Society          | Brooklyn 3                | 29-76 Northern Blvd., Long Island City, NY 11101 | 
| 1360663352  | The Fortune Society          | Brooklyn 5                | 29-76 Northern Blvd., Long Island City, NY 11101 | 
| 1360663352  | The Fortune Society          | Brooklyn 8                | 29-76 Northern Blvd., Long Island City, NY 11101 | 
```