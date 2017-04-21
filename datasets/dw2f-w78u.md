# Lobbyist Data - Compensation

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lobbyist-data-compensation) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/dw2f-w78u) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/dw2f-w78u/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/dw2f-w78u/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | dw2f-w78u |
| Name | Lobbyist Data - Compensation |
| Attribution | City of Chicago |
| Category | Ethics |
| Tags | ethics, lobbyists |
| Created | 2015-06-16T17:46:26Z |
| Publication Date | 2015-10-20T16:58:37Z |

## Description

Lobbying-related compensation received by registered lobbyists as reported in their quarterly reports.  
See http://www.cityofchicago.org/city/en/depts/ethics/provdrs/lobby.html for more information on the Board of Ethics' role in regulating and reporting on lobbying in Chicago.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type     | Render Type   |
| ======== | ============== | ======================= | ======================= | ============= | ============= |
| Yes      | series tag     | compensation_id         | COMPENSATION_ID         | text          | number        |
| Yes      | time           | period_start            | PERIOD_START            | calendar_date | calendar_date |
| No       |                | period_end              | PERIOD_END              | calendar_date | calendar_date |
| Yes      | series tag     | lobbyist_id             | LOBBYIST_ID             | text          | number        |
| Yes      | series tag     | lobbyist_first_name     | LOBBYIST_FIRST_NAME     | text          | text          |
| Yes      | series tag     | lobbyist_middle_initial | LOBBYIST_MIDDLE_INITIAL | text          | text          |
| Yes      | series tag     | lobbyist_last_name      | LOBBYIST_LAST_NAME      | text          | text          |
| Yes      | numeric metric | compensation_amount     | COMPENSATION_AMOUNT     | money         | money         |
| Yes      | series tag     | client_id               | CLIENT_ID               | text          | number        |
| Yes      | series tag     | client_name             | CLIENT_NAME             | text          | text          |
| No       |                | created_date            | CREATED_DATE            | calendar_date | calendar_date |
```

## Time Field

```ls
Value = period_start
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = period_end,created_date
```

## Data Commands

```ls
series e:dw2f-w78u d:2012-01-01T00:00:00.000Z t:lobbyist_first_name=John t:lobbyist_id=7106 t:client_id=12789 t:compensation_id=33 t:client_name="Spaan Tech" t:lobbyist_last_name=Dunn t:lobbyist_middle_initial=F m:compensation_amount=5000

series e:dw2f-w78u d:2012-01-01T00:00:00.000Z t:lobbyist_first_name=John t:lobbyist_id=8081 t:client_id=12784 t:compensation_id=299 t:client_name="Hudson Group" t:lobbyist_last_name=Dunn t:lobbyist_middle_initial=F m:compensation_amount=52500

series e:dw2f-w78u d:2012-01-01T00:00:00.000Z t:lobbyist_first_name=Mariah t:lobbyist_id=5947 t:client_id=12732 t:compensation_id=328 t:client_name="Great Lakes Prinicipals  c%2fo CD_EP Retail JV LLC" t:lobbyist_last_name=DiGrino m:compensation_amount=25000
```

## Meta Commands

```ls
metric m:compensation_amount p:integer l:COMPENSATION_AMOUNT t:dataTypeName=money

entity e:dw2f-w78u l:"Lobbyist Data - Compensation" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/dw2f-w78u

property e:dw2f-w78u t:meta.view v:id=dw2f-w78u v:category=Ethics v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Lobbyist Data - Compensation" v:attribution="City of Chicago"

property e:dw2f-w78u t:meta.view.owner v:id=vewm-vupz v:screenName="Jonathan Levy" v:displayName="Jonathan Levy"

property e:dw2f-w78u t:meta.view.tableauthor v:id=vewm-vupz v:screenName="Jonathan Levy" v:roleName=administrator v:displayName="Jonathan Levy"
```

## Top Records

```ls
| compensation_id | period_start        | period_end          | lobbyist_id | lobbyist_first_name | lobbyist_middle_initial | lobbyist_last_name | compensation_amount | client_id | client_name                                       | created_date        | 
| =============== | =================== | =================== | =========== | =================== | ======================= | ================== | =================== | ========= | ================================================= | =================== | 
| 33              | 2012-01-01T00:00:00 | 2012-06-30T00:00:00 | 7106        | John                | F                       | Dunn               | 5000                | 12789     | Spaan Tech                                        | 2012-08-02T00:00:00 | 
| 299             | 2012-01-01T00:00:00 | 2012-06-30T00:00:00 | 8081        | John                | F                       | Dunn               | 52500               | 12784     | Hudson Group                                      | 2012-08-08T00:00:00 | 
| 328             | 2012-01-01T00:00:00 | 2012-06-30T00:00:00 | 5947        | Mariah              |                         | DiGrino            | 25000               | 12732     | Great Lakes Prinicipals c%2fo CD_EP Retail JV LLC | 2012-08-09T00:00:00 | 
| 402             | 2012-01-01T00:00:00 | 2012-06-30T00:00:00 | 5710        | John                |                         | Gust               | 3365                | 12163     | Jefferies & Company Inc                           | 2012-08-10T00:00:00 | 
| 496             | 2012-01-01T00:00:00 | 2012-06-30T00:00:00 | 7005        | John                | F                       | Kattner            | 1500                | 11807     | Thermal Chicago Corp.                             | 2012-08-14T00:00:00 | 
| 506             | 2012-01-01T00:00:00 | 2012-06-30T00:00:00 | 6039        | Michael             | R                       | Lufrano            | 2000                | 12925     | Chicago Cubs Baseball Club LLC                    | 2012-08-14T00:00:00 | 
| 740             | 2012-01-01T00:00:00 | 2012-06-30T00:00:00 | 7744        | Langdon             | D                       | Neal               | 1800                | 11633     | Odessy Loft owners                                | 2012-08-23T00:00:00 | 
| 798             | 2012-01-01T00:00:00 | 2012-06-30T00:00:00 | 6980        | Bridget             | M                       | O'Keefe            | 1600                | 12678     | Remus Partners LLC                                | 2012-08-23T00:00:00 | 
| 806             | 2012-01-01T00:00:00 | 2012-06-30T00:00:00 | 5988        | Kevin               | P                       | O'Hara             | 4200                | 12822     | Chicago Parking Meters LLC                        | 2012-08-23T00:00:00 | 
| 815             | 2012-01-01T00:00:00 | 2012-06-30T00:00:00 | 7082        | Samuel              |                         | Panayotovich       | 14000               | 14302     | 7-Eleven, Inc                                     | 2012-08-23T00:00:00 | 
```