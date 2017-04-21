# Libraries Computers Available

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/libraries-computers-available-2ede4) |
| Metadata | [Link](https://data.hawaii.gov/api/views/tkwq-e4vi) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/tkwq-e4vi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/tkwq-e4vi/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | tkwq-e4vi |
| Name | Libraries Computers Available |
| Attribution | Hawaii State Public Library System |
| Category | Social Services |
| Tags | computers |
| Created | 2012-06-27T00:50:22Z |
| Publication Date | 2012-06-27T01:17:11Z |

## Description

Number of desktop coputers and laptops available in Hawaii Libraries

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type     | Render Type   |
| ======== | ============== | ========================= | ========================= | ============= | ============= |
| Yes      | series tag     | island                    | Island                    | text          | text          |
| Yes      | series tag     | library_location          | Library Location          | text          | text          |
| Yes      | numeric metric | library_staff_desktop_pcs | library staff desktop pcs | number        | number        |
| Yes      | numeric metric | public_desktop_pc         | public desktop pc         | number        | number        |
| Yes      | numeric metric | public_laptops            | public laptops            | number        | text          |
| Yes      | series tag     | line_type                 | Line Type                 | text          | text          |
| Yes      | series tag     | road_runner_line          | Road Runner Line          | text          | text          |
| Yes      | time           | installation_date_line    | Installation Date line    | calendar_date | calendar_date |
| No       |                | installation_date_active  | Installation Date active  | calendar_date | calendar_date |
```

## Time Field

```ls
Value = installation_date_line
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = installation_date_active
```

## Data Commands

```ls
series e:tkwq-e4vi d:2010-07-26T00:00:00.000Z t:library_location=Aiea t:line_type="DSL 11M" t:road_runner_line=25M t:island=Oahu m:public_desktop_pc=8 m:library_staff_desktop_pcs=8

series e:tkwq-e4vi d:2010-08-24T00:00:00.000Z t:library_location="Aina Haina" t:line_type="DSL 11M x 2" t:road_runner_line=n/a t:island=Oahu m:public_desktop_pc=10 m:library_staff_desktop_pcs=8

series e:tkwq-e4vi d:2010-07-19T00:00:00.000Z t:library_location="Ewa Beach" t:line_type="DSL 11M" t:road_runner_line=25M t:island=Oahu m:public_desktop_pc=6 m:library_staff_desktop_pcs=9
```

## Meta Commands

```ls
metric m:library_staff_desktop_pcs p:integer l:"library staff desktop pcs" t:dataTypeName=number

metric m:public_desktop_pc p:integer l:"public desktop pc" t:dataTypeName=number

metric m:public_laptops p:integer l:"public laptops" t:dataTypeName=number

entity e:tkwq-e4vi l:"Libraries Computers Available" t:attribution="Hawaii State Public Library System" t:url=https://data.hawaii.gov/api/views/tkwq-e4vi

property e:tkwq-e4vi t:meta.view v:id=tkwq-e4vi v:category="Social Services" v:attributionLink=http://hawaii.sdp.sirsi.net/custom/web/ v:averageRating=0 v:name="Libraries Computers Available" v:attribution="Hawaii State Public Library System"

property e:tkwq-e4vi t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:tkwq-e4vi t:meta.view.owner v:id=4hgi-fxu8 v:screenName="Paola Saibene" v:displayName="Paola Saibene"

property e:tkwq-e4vi t:meta.view.tableauthor v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:roleName=publisher v:displayName="OIMT Open Data Coordinator"
```

## Top Records

```ls
| island | library_location     | library_staff_desktop_pcs | public_desktop_pc | public_laptops | line_type   | road_runner_line | installation_date_line | installation_date_active | 
| ====== | ==================== | ========================= | ================= | ============== | =========== | ================ | ====================== | ======================== | 
| Oahu   | Aiea                 | 8                         | 8                 |                | DSL 11M     | 25M              | 2010-07-26T00:00:00    | 2010-07-26T00:00:00      | 
| Oahu   | Aina Haina           | 8                         | 10                |                | DSL 11M x 2 | n/a              | 2010-08-24T00:00:00    | 2010-08-24T00:00:00      | 
| Oahu   | Ewa Beach            | 9                         | 6                 |                | DSL 11M     | 25M              | 2010-07-19T00:00:00    | 2010-07-27T00:00:00      | 
| Oahu   | Hawaii Kai           | 7                         | 9                 |                | DSL 7M      | 25M              | 2010-08-09T00:00:00    | 2010-08-09T00:00:00      | 
| Oahu   | Hawaii State Library | 66                        | 55                |                | DSL 11M x 4 | 25M              | 2010-06-28T00:00:00    | 2010-06-28T00:00:00      | 
| Oahu   | Kahuku               | 7                         | 8                 |                | EoC 1.5M    | 25M              | 2010-08-10T00:00:00    | 2010-08-10T00:00:00      | 
| Oahu   | Kailua               | 12                        | 12                |                | DSL 11M     | 25M              | 2010-08-26T00:00:00    | 2010-08-26T00:00:00      | 
| Oahu   | Kaimuki              | 15                        | 13                |                | DSL 11M     | 25M              | 2010-08-13T00:00:00    | 2010-08-13T00:00:00      | 
| Oahu   | Kalihi-Palama        | 7                         | 13                |                | DSL 11M x 2 | n/a              | 2010-07-26T00:00:00    | 2010-07-26T00:00:00      | 
| Oahu   | Kaneohe              | 14                        | 18                |                | DSL 11M     | 25M              | 2010-08-18T00:00:00    | 2010-08-18T00:00:00      | 
```