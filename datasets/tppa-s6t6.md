# MTA Customer Feedback Data: Beginning 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/mta-customer-feedback-data-beginning-2014) |
| Metadata | [Link](https://data.ny.gov/api/views/tppa-s6t6) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/tppa-s6t6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/tppa-s6t6/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | tppa-s6t6 |
| Name | MTA Customer Feedback Data: Beginning 2014 |
| Attribution | Metropolitan Transportation Authority (MTA) |
| Category | Transportation |
| Tags | transit, customer service, commendation, complaint |
| Created | 2015-09-14T19:43:10Z |
| Publication Date | 2016-11-02T23:04:49Z |

## Description

This dataset is generated from the Customer Relationship Management System.  This system allows the public to correspond to the MTA about complaints or commendations in a variety of categories.  The dataset contains information about areas of customer service and how that service was rated.

## Columns

```ls
| Included | Schema Type | Field Name                | Name                      | Data Type | Render Type |
| ======== | =========== | ========================= | ========================= | ========= | =========== |
| Yes      | series tag  | agency                    | Agency                    | text      | text        |
| Yes      | series tag  | commendation_or_complaint | Commendation or Complaint | text      | text        |
| Yes      | series tag  | subject_matter            | Subject Matter            | text      | text        |
| Yes      | series tag  | subject_detail            | Subject Detail            | text      | text        |
| Yes      | series tag  | issue_detail              | Issue Detail              | text      | text        |
| No       |             | year                      | Year                      | number    | number      |
| No       |             | quarter                   | Quarter                   | number    | number      |
| Yes      | series tag  | branch_line_route         | Branch/Line/Route         | text      | text        |
```

## Time Field

```ls
Value = year-quarter
Format & Zone = yyyy-q
```

## Series Fields

```ls
Excluded Fields = year,quarter
```

## Data Commands

```ls
```

## Meta Commands

```ls
entity e:tppa-s6t6 l:"MTA Customer Feedback Data: Beginning 2014" t:attribution="Metropolitan Transportation Authority (MTA)" t:url=https://data.ny.gov/api/views/tppa-s6t6

property e:tppa-s6t6 t:meta.view v:id=tppa-s6t6 v:category=Transportation v:averageRating=0 v:name="MTA Customer Feedback Data: Beginning 2014" v:attribution="Metropolitan Transportation Authority (MTA)"

property e:tppa-s6t6 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:tppa-s6t6 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:tppa-s6t6 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```