# DFTA Contracts

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dfta-contracts-99367) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/6j6t-3ixh) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/6j6t-3ixh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/6j6t-3ixh/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 6j6t-3ixh |
| Name | DFTA Contracts |
| Attribution | Department for the Aging (DFTA) |
| Category | Social Services |
| Tags | dfta, congregate meals, abuse prevention, home care, legal services, norc, transportation, case management, home delivered meals, caregivers |
| Created | 2013-03-01T20:09:16Z |
| Publication Date | 2017-04-14T21:37:21Z |

## Description

Listing of all Senior Centers, Abuse Prevention Contracts, Home Care Contracts, Legal Services Contracts, NORC Contracts, Transportation Contracts, Case Mangement Contracts, Home Delivered Meal Contracts and  Caregiver Contracts in all five boroughs.

## Columns

```ls
| Included | Schema Type | Field Name      | Name            | Data Type | Render Type |
| ======== | =========== | =============== | =============== | ========= | =========== |
| No       | time        | :updated_at     | updated_at      | meta_data | meta_data   |
| Yes      | series tag  | contract_type   | Contract Type   | text      | text        |
| Yes      | series tag  | provider_id     | Provider ID     | text      | text        |
| Yes      | series tag  | program_name    | Program Name    | text      | text        |
| Yes      | series tag  | sponsor_name    | Sponsor Name    | text      | text        |
| No       |             | program_address | Program Address | text      | text        |
| Yes      | series tag  | program_borough | Program Borough | text      | text        |
| Yes      | series tag  | program_zipcode | Program Zipcode | text      | text        |
| Yes      | series tag  | program_phone   | Program Phone   | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = program_address
```

## Data Commands

```ls
series e:6j6t-3ixh d:2017-04-14T21:37:16.000Z t:program_borough="NEW YORK" t:program_phone=212-879-7400 t:contract_type="ABUSE PREVENTION" t:provider_id=3E201 t:sponsor_name="THE CARTER BURDEN CENTER FOR THE AGING INC" t:program_name="CARTER BURDEN ELDER ABUSE" t:program_zipcode=10021 m:row_number.6j6t-3ixh=1

series e:6j6t-3ixh d:2017-04-14T21:37:16.000Z t:program_borough="STATEN ISLAND" t:program_phone=718-981-6226 t:contract_type="ABUSE PREVENTION" t:provider_id=5E101 t:sponsor_name="COMMUNITY AGENCY FOR SENIOR CITIZENS INC" t:program_name="CASC ELDER ABUSE" t:program_zipcode=10301 m:row_number.6j6t-3ixh=2

series e:6j6t-3ixh d:2017-04-14T21:37:16.000Z t:program_borough=BROOKLYN t:program_phone=718-943-7752 t:contract_type="ABUSE PREVENTION" t:provider_id=2E101 t:sponsor_name="JEWISH ASSOCIATION FOR SERVICES FOR THE AGED" t:program_name="JASA ELDER ABUSE" t:program_zipcode=11201 m:row_number.6j6t-3ixh=3
```

## Meta Commands

```ls
metric m:row_number.6j6t-3ixh p:long l:"Row Number"

entity e:6j6t-3ixh l:"DFTA Contracts" t:attribution="Department for the Aging (DFTA)" t:url=https://data.cityofnewyork.us/api/views/6j6t-3ixh

property e:6j6t-3ixh t:meta.view v:id=6j6t-3ixh v:category="Social Services" v:attributionLink=http://www.nyc.gov/aging v:averageRating=0 v:name="DFTA Contracts" v:attribution="Department for the Aging (DFTA)"

property e:6j6t-3ixh t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:6j6t-3ixh t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | contract_type    | provider_id | program_name                            | sponsor_name                                       | program_address            | program_borough | program_zipcode | program_phone | 
| =========== | ================ | =========== | ======================================= | ================================================== | ========================== | =============== | =============== | ============= | 
| 1492205836  | ABUSE PREVENTION | 3E201       | CARTER BURDEN ELDER ABUSE               | THE CARTER BURDEN CENTER FOR THE AGING INC         | 1484 FIRST AVENUE          | NEW YORK        | 10021           | 212-879-7400  | 
| 1492205836  | ABUSE PREVENTION | 5E101       | CASC ELDER ABUSE                        | COMMUNITY AGENCY FOR SENIOR CITIZENS INC           | 56 BAY STREET              | STATEN ISLAND   | 10301           | 718-981-6226  | 
| 1492205836  | ABUSE PREVENTION | 2E101       | JASA ELDER ABUSE                        | JEWISH ASSOCIATION FOR SERVICES FOR THE AGED       | 44 COURT STREET            | BROOKLYN        | 11201           | 718-943-7752  | 
| 1492205836  | ABUSE PREVENTION | 4E101       | JASA ELDER ABUSE                        | JEWISH ASSOCIATION FOR SERVICES FOR THE AGED       | 97-77 QUEENS BOULEVARD     | REGO PARK       | 11374           | 718-286-1524  | 
| 1492205836  | ABUSE PREVENTION | 1E101       | SHOPP ELDER ABUSE BX 1-8                | THE NEIGHBORHOOD SELF-HELP BY OLDER PERSONS PROJEC | 953 SOUTHERN BOULEVARD     | BRONX           | 10459           | 718-542-0006  | 
| 1492205836  | CAREGIVER        | 4K301       | CAREGIVER PROGRAM OF SNAP               | SERVICES NOW FOR ADULT PERSONS INC                 | 80-45 WINCHESTER BOULEVARD | QUEENS VILLAGE  | 11427           | 718-527-5380  | 
| 1492205836  | CAREGIVER        | 2K401       | HEIGHTS AND HILL CAREGIVER PROGRAM      | HEIGHTS AND HILLS, INC.                            | 57 WILLOUGHBY STREET       | BROOKLYN        | 11201           | 718-596-8789  | 
| 1492205836  | CAREGIVER        | 6K101       | HMH CAREGIVER SERVICES MANHATTAN        | HAMILTON MADISON HOUSE INC                         | 100 GOLD STREET            | NEW YORK        | 10038           | 212-788-2318  | 
| 1492205836  | CAREGIVER        | 6K102       | HMH CAREGIVER SERVICES QUEENS           | HAMILTON MADISON HOUSE INC                         | 78-14 ROOSEVELT AVENUE     | FLUSHING        | 11372           | 718-672-4905  | 
| 1492205836  | CAREGIVER        | 2K201       | JASA BROOKLYN CAREGIVER RESPITE PROGRAM | JEWISH ASSOCIATION FOR SERVICES FOR THE AGED       | 161 CORBIN PLACE           | BROOKLYN        | 11235           | 718-934-4180  | 
```