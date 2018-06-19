# Lobbyist Data - Contributions

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lobbyist-data-contributions) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/p9p7-vfqc) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/p9p7-vfqc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/p9p7-vfqc/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | p9p7-vfqc |
| Name | Lobbyist Data - Contributions |
| Attribution | City of Chicago |
| Category | Ethics |
| Tags | ethics, lobbyists |
| Created | 2015-06-09T19:22:20Z |
| Publication Date | 2015-10-20T21:51:32Z |

## Description

Political contributions by registered lobbyists, who must report every political contribution made to any candidate for City office, any elected official of the City, and any official or employee of the City seeking election to an office other that a City office during the reporting period.
See http://www.cityofchicago.org/city/en/depts/ethics/provdrs/lobby.html for more information on the Board of Ethics' role in regulating and reporting on lobbying in Chicago.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type     | Render Type   |
| ======== | ============== | =================== | =================== | ============= | ============= |
| Yes      | series tag     | contribution_id     | CONTRIBUTION_ID     | text          | number        |
| Yes      | time           | period_start        | PERIOD_START        | calendar_date | calendar_date |
| No       |                | period_end          | PERIOD_END          | calendar_date | calendar_date |
| No       |                | contribution_date   | CONTRIBUTION_DATE   | calendar_date | calendar_date |
| Yes      | series tag     | recipient           | RECIPIENT           | text          | text          |
| Yes      | numeric metric | amount              | AMOUNT              | money         | money         |
| Yes      | series tag     | lobbyist_id         | LOBBYIST_ID         | text          | number        |
| Yes      | series tag     | lobbyist_first_name | LOBBYIST_FIRST_NAME | text          | text          |
| Yes      | series tag     | lobbyist_last_name  | LOBBYIST_LAST_NAME  | text          | text          |
| No       |                | created_date        | CREATED_DATE        | calendar_date | calendar_date |
```

## Time Field

```ls
Value = period_start
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = period_end,contribution_date,created_date
```

## Data Commands

```ls
series e:p9p7-vfqc d:2012-01-01T00:00:00.000Z t:lobbyist_first_name=David t:lobbyist_id=8061 t:contribution_id=125 t:lobbyist_last_name=Dring t:recipient="Alderman Will Burns" m:amount=500

series e:p9p7-vfqc d:2012-01-01T00:00:00.000Z t:lobbyist_first_name=Robert t:lobbyist_id=6922 t:contribution_id=147 t:lobbyist_last_name=Gamrath t:recipient="40th Ward Organization" m:amount=100

series e:p9p7-vfqc d:2012-01-01T00:00:00.000Z t:lobbyist_first_name=Thomas t:lobbyist_id=5858 t:contribution_id=181 t:lobbyist_last_name=Livingston t:recipient="Alderman Toni Foulkes" m:amount=1000
```

## Meta Commands

```ls
metric m:amount p:double l:AMOUNT t:dataTypeName=money

entity e:p9p7-vfqc l:"Lobbyist Data - Contributions" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/p9p7-vfqc

property e:p9p7-vfqc t:meta.view v:id=p9p7-vfqc v:category=Ethics v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Lobbyist Data - Contributions" v:attribution="City of Chicago"

property e:p9p7-vfqc t:meta.view.owner v:id=vewm-vupz v:screenName="Jonathan Levy" v:displayName="Jonathan Levy"

property e:p9p7-vfqc t:meta.view.tableauthor v:id=vewm-vupz v:screenName="Jonathan Levy" v:roleName=administrator v:displayName="Jonathan Levy"
```

## Top Records

```ls
| contribution_id | period_start        | period_end          | contribution_date   | recipient                     | amount | lobbyist_id | lobbyist_first_name | lobbyist_last_name | created_date        | 
| =============== | =================== | =================== | =================== | ============================= | ====== | =========== | =================== | ================== | =================== | 
| 125             | 2012-01-01T00:00:00 | 2012-06-30T00:00:00 | 2012-06-05T00:00:00 | Alderman Will Burns           | 500    | 8061        | David               | Dring              | 2012-08-08T00:00:00 | 
| 147             | 2012-01-01T00:00:00 | 2012-06-30T00:00:00 | 2012-02-18T00:00:00 | 40th Ward Organization        | 100    | 6922        | Robert              | Gamrath            | 2012-08-10T00:00:00 | 
| 181             | 2012-01-01T00:00:00 | 2012-06-30T00:00:00 | 2012-04-26T00:00:00 | Alderman Toni Foulkes         | 1000   | 5858        | Thomas              | Livingston         | 2012-08-14T00:00:00 | 
| 187             | 2012-01-01T00:00:00 | 2012-06-30T00:00:00 | 2012-04-24T00:00:00 | Citizens for Tunney           | 500    | 6039        | Michael             | Lufrano            | 2012-08-14T00:00:00 | 
| 295             | 2012-01-01T00:00:00 | 2012-06-30T00:00:00 | 2012-06-29T00:00:00 | Citizens for Alderman Reilly  | 200    | 8482        | Daniel              | Shomon             | 2012-08-22T00:00:00 | 
| 294             | 2012-01-01T00:00:00 | 2012-06-30T00:00:00 | 2012-06-13T00:00:00 | Friends of Will Burns         | 300    | 8482        | Daniel              | Shomon             | 2012-08-22T00:00:00 | 
| 342             | 2012-01-01T00:00:00 | 2012-06-30T00:00:00 | 2012-03-01T00:00:00 | Alderman Patrick J. O'Connor  | 1500   | 7001        | Meredith            | O'Connor           | 2012-08-23T00:00:00 | 
| 422             | 2012-01-01T00:00:00 | 2012-06-30T00:00:00 | 2012-02-21T00:00:00 | Friends of Walter Burnett Jr. | 150    | 8621        | Joseph              | Pilewski           | 2012-08-28T00:00:00 | 
| 354             | 2012-01-01T00:00:00 | 2012-06-30T00:00:00 | 2012-06-26T00:00:00 | Citizens for Tim Cullerton    | 1000   | 6116        | Michael             | Paulos             | 2012-08-23T00:00:00 | 
| 353             | 2012-01-01T00:00:00 | 2012-06-30T00:00:00 | 2012-06-26T00:00:00 | Neighbors for Harry Osterman  | 1500   | 6116        | Michael             | Paulos             | 2012-08-23T00:00:00 | 
```