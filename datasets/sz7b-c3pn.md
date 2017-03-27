# Lobbyists on Behalf of the City Disclosure Reports

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lobbyists-on-behalf-of-the-city-disclosure-reports) |
| Metadata | [Link](https://data.sfgov.org/api/views/sz7b-c3pn) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/sz7b-c3pn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/sz7b-c3pn/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | sz7b-c3pn |
| Name | Lobbyists on Behalf of the City Disclosure Reports |
| Attribution | San Francisco Ethics Commission |
| Category | City Management and Ethics |
| Created | 2015-07-28T22:43:31Z |
| Publication Date | 2016-05-23T22:16:50Z |

## Description

The San Francisco Sunshine Ordinance, S.F. Admin. Code Section 67.1 et seq., requires lobbyists who contract for economic consideration with the City to represent the City in matters before any local, regional, state or federal administrative or legislative body to file quarterly activity reports with the Ethics Commission. These persons and entities are referred to as “Lobbyists on Behalf of the City.”

Please note: Lobbyists on Behalf of the City should not be confused with lobbyists who attempt to influence City officers on local legislative or administrative action on behalf of private parties. The latter are regulated by the San Francisco Lobbyist Ordinance, S.F. Campaign and Governmental Conduct Code Section 2.100, et seq., not by the Sunshine Ordinance.

## Columns

```ls
| Included | Schema Type | Field Name                | Name                      | Data Type     | Render Type   |
| ======== | =========== | ========================= | ========================= | ============= | ============= |
| Yes      | series tag  | lobbyist_name             | Lobbyist Name             | text          | text          |
| Yes      | series tag  | report                    | Report                    | document      | document      |
| Yes      | time        | date_filed                | Date Filed                | calendar_date | calendar_date |
| No       |             | period_start_date         | Period Start Date         | calendar_date | calendar_date |
| No       |             | period_end_date           | Period End Date           | calendar_date | calendar_date |
| Yes      | series tag  | amendment_filing          | Amendment Filing          | checkbox      | checkbox      |
| No       |             | amendment_to_report_filed | Amendment to Report Filed | calendar_date | calendar_date |
```

## Time Field

```ls
Value = date_filed
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = period_start_date,period_end_date,amendment_to_report_filed
```

## Data Commands

```ls
series e:sz7b-c3pn d:2015-05-14T00:00:00.000Z t:report.content_type="application/pdf; charset=binary" t:report.filename="SHAW, YODER, ANTWIH, Inc - Quarter 1 - 2015 - Period February 1, 2015 to April 30, 2015.pdf" t:lobbyist_name="SHAW / YODER / ANTWIH / INC" t:report.size=1231828 t:report.file_id=9HIooxQA8K8VvZE-f8UVRn5VLcmzVZqDgQpIMqz2F34 m:row_number.sz7b-c3pn=1

series e:sz7b-c3pn d:2014-05-29T00:00:00.000Z t:report.content_type="application/pdf; charset=binary" t:report.filename=Holland.Knight.Quarter.1.2014.Period.February.1.2014.to.April.30.2014.pdf t:lobbyist_name="Holland & Knight" t:report.size=549723 t:report.file_id=YGRdp7o1zBDcuhlhdepRfhmg8Z9ccLbFdiS-4jDFX94 m:row_number.sz7b-c3pn=2

series e:sz7b-c3pn d:2014-08-18T00:00:00.000Z t:report.content_type="application/pdf; charset=binary" t:report.filename="Edelstein Gilbert Robson & Smith, LLC - Quarter 2 - 2014 - Period May 1, 2014 to July 31, 2014.pdf" t:lobbyist_name="Edelstein Gilbert Robson & Smith, LLC" t:report.size=636292 t:report.file_id=endLPCWvFKH5rdpFvN4aANjJsIiMAYyoIqvSyLhJUYw m:row_number.sz7b-c3pn=3
```

## Meta Commands

```ls
metric m:row_number.sz7b-c3pn p:long l:"Row Number"

entity e:sz7b-c3pn l:"Lobbyists on Behalf of the City Disclosure Reports" t:attribution="San Francisco Ethics Commission" t:url=https://data.sfgov.org/api/views/sz7b-c3pn

property e:sz7b-c3pn t:meta.view v:id=sz7b-c3pn v:category="City Management and Ethics" v:attributionLink=http://www.sfethics.org v:averageRating=0 v:name="Lobbyists on Behalf of the City Disclosure Reports" v:attribution="San Francisco Ethics Commission"

property e:sz7b-c3pn t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:sz7b-c3pn t:meta.view.owner v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:displayName="Steven Massey"

property e:sz7b-c3pn t:meta.view.tableauthor v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"
```