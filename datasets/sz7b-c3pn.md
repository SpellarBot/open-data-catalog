# Lobbyists on Behalf of the City Disclosure Reports

## Dataset

* [Dataset URL](https://data.sfgov.org/api/views/sz7b-c3pn/rows.json?accessType=DOWNLOAD)
* [Catalog URL](https://catalog.data.gov/dataset/lobbyists-on-behalf-of-the-city-disclosure-reports)
* Id = sz7b-c3pn
* Name = Lobbyists on Behalf of the City Disclosure Reports
* Attribution = San Francisco Ethics Commission
* Attribution Link = http://www.sfethics.org
* Category = City Management and Ethics
* Created = 2015-07-28T22:43:31Z
* Publication Date = 2016-05-23T22:16:50Z
* Rows Updated = 2016-11-16T22:30:40Z

## Description

The San Francisco Sunshine Ordinance, S.F. Admin. Code Section 67.1 et seq., requires lobbyists who contract for economic consideration with the City to represent the City in matters before any local, regional, state or federal administrative or legislative body to file quarterly activity reports with the Ethics Commission. These persons and entities are referred to as ?Lobbyists on Behalf of the City.?

Please note: Lobbyists on Behalf of the City should not be confused with lobbyists who attempt to influence City officers on local legislative or administrative action on behalf of private parties. The latter are regulated by the San Francisco Lobbyist Ordinance, S.F. Campaign and Governmental Conduct Code Section 2.100, et seq., not by the Sunshine Ordinance.

## Columns

```ls
| Name                      | Field Name                | Data Type     | Render Type   | Schema Type | Included | 
| ========================= | ========================= | ============= | ============= | =========== | ======== | 
| Lobbyist Name             | lobbyist_name             | text          | text          | series tag  | Yes      | 
| Report                    | report                    | document      | document      | series tag  | Yes      | 
| Date Filed                | date_filed                | calendar_date | calendar_date | time        | Yes      | 
| Period Start Date         | period_start_date         | calendar_date | calendar_date |             | No       | 
| Period End Date           | period_end_date           | calendar_date | calendar_date |             | No       | 
| Amendment Filing          | amendment_filing          | checkbox      | checkbox      | series tag  | Yes      | 
| Amendment to Report Filed | amendment_to_report_filed | calendar_date | calendar_date |             | No       | 
```

## Time Field

```ls
Value = date_filed
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = period_end_date,amendment_to_report_filed,period_start_date
Annotation Fields = 
```

## Data Commands

```ls





```

## Meta Commands

```ls
entity e:sz7b-c3pn l:"Lobbyists on Behalf of the City Disclosure Reports" t:attribution="San Francisco Ethics Commission" t:url=https://data.sfgov.org/api/views/sz7b-c3pn

property e:sz7b-c3pn t:meta.view d:2017-03-03T14:12:24.792Z v:id=sz7b-c3pn v:category="City Management and Ethics" v:attributionLink=http://www.sfethics.org v:averageRating=0 v:name="Lobbyists on Behalf of the City Disclosure Reports" v:attribution="San Francisco Ethics Commission"

property e:sz7b-c3pn t:meta.view.license d:2017-03-03T14:12:24.792Z v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:sz7b-c3pn t:meta.view.owner d:2017-03-03T14:12:24.792Z v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"

property e:sz7b-c3pn t:meta.view.tableauthor d:2017-03-03T14:12:24.792Z v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"
```