# Community HealthCare Centers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/community-healthcare-centers) |
| Metadata | [Link](https://data.hartford.gov/api/views/n9tp-i3k3) |
| Data: JSON | [100 Rows](https://data.hartford.gov/api/views/n9tp-i3k3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hartford.gov/api/views/n9tp-i3k3/rows.csv?max_rows=100) |
| Host | data.hartford.gov |
| Id | n9tp-i3k3 |
| Name | Community HealthCare Centers |
| Attribution | City of Hartford |
| Category | Public Health |
| Tags | health, hartford, hospital |
| Created | 2014-07-01T20:21:10Z |
| Publication Date | 2015-06-13T20:14:23Z |
| Rows Updated | 2015-06-13T20:13:27Z |

## Description

The locations represent Community Health Care Centers in the City of Hartford. This data was uploaded July 1, 2014

## Columns

```ls
| Included | Schema Type | Field Name   | Name         | Data Type | Render Type |
| ======== | =========== | ============ | ============ | ========= | =========== |
| No       | time        | :updated_at  | updated_at   | meta_data | meta_data   |
| Yes      | series tag  | name         | Name         | text      | text        |
| Yes      | series tag  | description  | Description  | text      | text        |
| Yes      | series tag  | location     | Location     | text      | text        |
| Yes      | series tag  | phone_number | Phone_Number | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:n9tp-i3k3 d:2014-07-01T13:21:12.000Z t:phone_number="(860) 249-9625" t:location="500 ALBANY AV" t:description="Community Health Services, Inc." t:name="Community Health Services, Inc." m:row_number.n9tp-i3k3=1

series e:n9tp-i3k3 d:2014-07-01T13:21:12.000Z t:phone_number="(860) 808-8607" t:location="500 ALBANY AV" t:description="Clinical Services - Adult Medicine" t:name="Community Health Services, Inc." m:row_number.n9tp-i3k3=2

series e:n9tp-i3k3 d:2014-07-01T13:21:12.000Z t:phone_number="(860) 808-8720" t:location="500 ALBANY AV" t:description="Clinical Services - Adolescent Medicine" t:name="Community Health Services, Inc." m:row_number.n9tp-i3k3=3
```

## Meta Commands

```ls
metric m:row_number.n9tp-i3k3 p:long l:"Row Number"

entity e:n9tp-i3k3 l:"Community HealthCare Centers" t:attribution="City of Hartford" t:url=https://data.hartford.gov/api/views/n9tp-i3k3

property e:n9tp-i3k3 t:meta.view v:id=n9tp-i3k3 v:category="Public Health" v:attributionLink=http://www.hartford.gov v:averageRating=0 v:name="Community HealthCare Centers" v:attribution="City of Hartford"

property e:n9tp-i3k3 t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:n9tp-i3k3 t:meta.view.owner v:id=cdqe-xcn5 v:screenName=Brett v:displayName=Brett

property e:n9tp-i3k3 t:meta.view.tableauthor v:id=cdqe-xcn5 v:screenName=Brett v:roleName=administrator v:displayName=Brett
```