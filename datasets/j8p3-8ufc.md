# DCLA: Programs Funding for FY2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dcla-programs-funding-for-fy2010-e93d0) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/j8p3-8ufc) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/j8p3-8ufc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/j8p3-8ufc/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | j8p3-8ufc |
| Name | DCLA: Programs Funding for FY2010 |
| Attribution | Department of Cultural Affairs (DCLA) |
| Category | Recreation |
| Tags | cultural, culture, program, fund, funding |
| Created | 2011-07-27T14:23:34Z |
| Publication Date | 2013-06-21T19:41:05Z |

## Description

Department of Cultural Affairs (DCLA) This data set is the Programs funding award amount for FY10.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| Yes      | series tag     | application_number | Application Number | text      | text        |
| Yes      | series tag     | orgname            | Orgname            | text      | text        |
| Yes      | numeric metric | fy10_programs_     | FY10 Programs $    | money     | money       |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:j8p3-8ufc d:2010-01-01T00:00:00.000Z t:orgname="13 Playwrights" t:application_number=FY10-AN-001701 m:fy10_programs_=4850

series e:j8p3-8ufc d:2010-01-01T00:00:00.000Z t:orgname="3 Graces Theater Company" t:application_number=FY10-AN-002645 m:fy10_programs_=4850

series e:j8p3-8ufc d:2010-01-01T00:00:00.000Z t:orgname="3 Legged Dog" t:application_number=FY10-MY-002902 m:fy10_programs_=24255
```

## Meta Commands

```ls
metric m:fy10_programs_ p:integer l:"FY10 Programs $" t:dataTypeName=money

entity e:j8p3-8ufc l:"DCLA: Programs Funding for FY2010" t:attribution="Department of Cultural Affairs (DCLA)" t:url=https://data.cityofnewyork.us/api/views/j8p3-8ufc

property e:j8p3-8ufc t:meta.view v:id=j8p3-8ufc v:category=Recreation v:averageRating=0 v:name="DCLA: Programs Funding for FY2010" v:attribution="Department of Cultural Affairs (DCLA)"

property e:j8p3-8ufc t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:j8p3-8ufc t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| application_number | orgname                               | fy10_programs_ | 
| ================== | ===================================== | ============== | 
| FY10-AN-001701     | 13 Playwrights                        | 4850           | 
| FY10-AN-002645     | 3 Graces Theater Company              | 4850           | 
| FY10-MY-002902     | 3 Legged Dog                          | 24255          | 
| FY10-AN-002501     | 42nd Street Workshop                  | 4850           | 
| FY10-MY-002163     | 52nd Street Project, Inc.             | 56005          | 
| FY10-RN-003901     | 7 Loaves, Inc.                        | 14280          | 
| FY10-MY-001062     | 826NYC, Inc.                          | 14550          | 
| FY10-AN-001991     | A Better Jamaica, Inc.                | 9700           | 
| FY10-AN-000343     | A Gathering of the Tribes             | 3000           | 
| FY10-AN-001995     | A Public Space Literary Projects Inc. | 4850           | 
```