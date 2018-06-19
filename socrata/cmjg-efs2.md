# Fire Department Annual Inspections

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fire-department-annual-inspections) |
| Metadata | [Link](https://data.srcity.org/api/views/cmjg-efs2) |
| Data: JSON | [100 Rows](https://data.srcity.org/api/views/cmjg-efs2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.srcity.org/api/views/cmjg-efs2/rows.csv?max_rows=100) |
| Host | data.srcity.org |
| Id | cmjg-efs2 |
| Name | Fire Department Annual Inspections |
| Category | Fire |
| Tags | inspection |
| Created | 2016-03-02T14:06:10Z |
| Publication Date | 2016-03-02T15:29:43Z |

## Description

Each year, the Fire Department inspects businesses for Life and Safety violations. Included in this data is the annual inspection along with any reinspections due to violations.

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type     | Render Type   |
| ======== | =========== | ================ | ================ | ============= | ============= |
| Yes      | series tag  | occupancy_number | Occupancy Number | text          | number        |
| Yes      | series tag  | business_name    | Business Name    | text          | text          |
| Yes      | time        | inspection_date  | Inspection Date  | calendar_date | calendar_date |
| Yes      | series tag  | inspection_type  | Inspection Type  | text          | text          |
| Yes      | series tag  | station          | Station          | text          | text          |
```

## Time Field

```ls
Value = inspection_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:cmjg-efs2 d:2009-01-14T00:00:00.000Z t:business_name="Guerneville Shell" t:station="02 - Station 2" t:inspection_type="CUPA Annual Inspection" t:occupancy_number=1875 m:row_number.cmjg-efs2=1

series e:cmjg-efs2 d:2009-01-07T00:00:00.000Z t:business_name="Essential Dental Care" t:station="04 - Station 4" t:inspection_type="CUPA Annual Inspection" t:occupancy_number=3264 m:row_number.cmjg-efs2=2

series e:cmjg-efs2 d:2009-01-22T00:00:00.000Z t:business_name="St Joseph Heritage Healthcare" t:station="01 - Station 1" t:inspection_type="CUPA Annual Inspection" t:occupancy_number=4057 m:row_number.cmjg-efs2=3
```

## Meta Commands

```ls
metric m:row_number.cmjg-efs2 p:long l:"Row Number"

entity e:cmjg-efs2 l:"Fire Department Annual Inspections" t:url=https://data.srcity.org/api/views/cmjg-efs2

property e:cmjg-efs2 t:meta.view v:id=cmjg-efs2 v:category=Fire v:averageRating=0 v:name="Fire Department Annual Inspections"

property e:cmjg-efs2 t:meta.view.owner v:id=jizs-3xc2 v:screenName="Reese, Jackie" v:displayName="Reese, Jackie"

property e:cmjg-efs2 t:meta.view.tableauthor v:id=jizs-3xc2 v:screenName="Reese, Jackie" v:roleName=publisher v:displayName="Reese, Jackie"
```

## Top Records

```ls
| occupancy_number | business_name                        | inspection_date     | inspection_type        | station         | 
| ================ | ==================================== | =================== | ====================== | =============== | 
| 1875             | Guerneville Shell                    | 2009-01-14T00:00:00 | CUPA Annual Inspection | 02 - Station 2  | 
| 3264             | Essential Dental Care                | 2009-01-07T00:00:00 | CUPA Annual Inspection | 04 - Station 4  | 
| 4057             | St Joseph Heritage Healthcare        | 2009-01-22T00:00:00 | CUPA Annual Inspection | 01 - Station 1  | 
| 8434             | Fulton Arco Am/Pm                    | 2008-12-17T00:00:00 | CUPA Annual Inspection | 02 - Station 2  | 
| 9411             | Alec C Nelson, DMD                   | 2009-01-07T00:00:00 | CUPA Annual Inspection | 05 - Station 5  | 
| 3907             | Dental Implant Center & Periodontics | 2009-01-07T00:00:00 | CUPA Annual Inspection | 01 - Station 1  | 
| 7156             | Amy's Kitchen                        | 2009-01-21T00:00:00 | CUPA Annual Inspection | 10 - Station 10 | 
| 4746             | Safeway #1265                        | 2012-02-29T00:00:00 | CUPA Annual Inspection | 04 - Station 4  | 
| 2911             | Timothy Hayes DC                     | 2009-01-06T00:00:00 | CUPA Annual Inspection | 02 - Station 2  | 
| 8983             | Wheel Works                          | 2009-01-14T00:00:00 | CUPA Annual Inspection | 11 - Station 11 | 
```