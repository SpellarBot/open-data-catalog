# Constituent Services

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/constituent-services-39ee8) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/kpjg-ubxi) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/kpjg-ubxi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/kpjg-ubxi/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | kpjg-ubxi |
| Name | Constituent Services |
| Attribution | Manhattan Borough President (MBP) |
| Category | City Government |
| Tags | constituent, city government, mbp |
| Created | 2014-10-21T21:36:17Z |
| Publication Date | 2014-10-21T21:40:20Z |

## Description

This list contains information on the number and nature of constituent services handled by the Borough President's Office.

## Columns

```ls
| Included | Schema Type | Field Name                | Name                         | Data Type | Render Type |
| ======== | =========== | ========================= | ============================ | ========= | =========== |
| No       | time        | :updated_at               | updated_at                   | meta_data | meta_data   |
| Yes      | series tag  | initial_contact           | Initial Contact              | text      | text        |
| Yes      | series tag  | language_if_blank_english | Language (If blank, English) | text      | text        |
| Yes      | series tag  | issue                     | Issue                        | text      | text        |
| No       |             | date                      | Date                         | text      | text        |
| Yes      | series tag  | city_state                | City/State                   | text      | text        |
| Yes      | series tag  | zip                       | Zip                          | text      | text        |
| No       |             | cb                        | CB                           | number    | number      |
| Yes      | series tag  | council_member            | Council Member               | text      | text        |
| Yes      | series tag  | letter_drafted            | Letter Drafted               | text      | text        |
| Yes      | series tag  | status                    | Status                       | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = date,cb
```

## Data Commands

```ls
series e:kpjg-ubxi d:2014-10-21T14:36:20.000Z t:status=Closed t:issue=Foreclosure t:initial_contact=Call m:row_number.kpjg-ubxi=1

series e:kpjg-ubxi d:2014-10-21T14:36:20.000Z t:zip=10035 t:status=Closed t:issue="Start a business" t:initial_contact=Call t:city_state="NY, NY" t:council_member=Viverito m:row_number.kpjg-ubxi=2

series e:kpjg-ubxi d:2014-10-21T14:36:20.000Z t:zip=10013 t:status=Closed t:issue="DOH Permit" t:initial_contact=Call t:city_state="NY, NY" t:council_member=Chin m:row_number.kpjg-ubxi=3
```

## Meta Commands

```ls
metric m:row_number.kpjg-ubxi p:long l:"Row Number"

entity e:kpjg-ubxi l:"Constituent Services" t:attribution="Manhattan Borough President (MBP)" t:url=https://data.cityofnewyork.us/api/views/kpjg-ubxi

property e:kpjg-ubxi t:meta.view v:id=kpjg-ubxi v:category="City Government" v:averageRating=0 v:name="Constituent Services" v:attribution="Manhattan Borough President (MBP)"

property e:kpjg-ubxi t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:kpjg-ubxi t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | initial_contact | language_if_blank_english | issue                | date      | city_state | zip   | cb | council_member | letter_drafted | status    | 
| =========== | =============== | ========================= | ==================== | ========= | ========== | ===== | == | ============== | ============== | ========= | 
| 1413902180  | Call            |                           | Foreclosure          | 7-Jan-14  |            |       |    |                |                | Closed    | 
| 1413902180  | Call            |                           | Start a business     | 7-Jan-14  | NY, NY     | 10035 | 11 | Viverito       |                | Closed    | 
| 1413902180  | Call            |                           | DOH Permit           | 7-Jan-14  | NY, NY     | 10013 | 2  | Chin           |                | Closed    | 
| 1413902180  | Call            |                           | Health Care Exchange | 7-Jan-14  |            |       |    |                |                | Open      | 
| 1413902180  | Call            |                           | Health Care Exchange | 7-Jan-14  |            |       |    |                |                | Closed    | 
| 1413902180  | Call            |                           | Eviction Prevention  | 3-Jan-14  |            |       |    |                |                | Follow-up | 
| 1413902180  | Letter          |                           | DHCR                 | 3-Jan-14  | NY, NY     | 10024 | 7  | Rosenthal      |                | Follow-up | 
| 1413902180  | Call            |                           | Lease Renewal        | 8-Jan-14  | NY, NY     | 10023 | 9  | Levine         |                |           | 
| 1413902180  | Call            |                           | Eviction             | 15-Jan-14 | NY, NY     | 10027 | 9  | Levine         |                | Follow-up | 
| 1413902180  | Call            |                           | Unknown              | 8-Jan-14  |            |       |    |                |                | Closed    | 
```