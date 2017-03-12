# Super Neighborhood Tracker

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/super-neighborhood-tracker) |
| Metadata | [Link](https://data.jacksonms.gov/api/views/jcxs-qmaz) |
| Data: JSON | [100 Rows](https://data.jacksonms.gov/api/views/jcxs-qmaz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.jacksonms.gov/api/views/jcxs-qmaz/rows.csv?max_rows=100) |
| Host | data.jacksonms.gov |
| Id | jcxs-qmaz |
| Name | Super Neighborhood Tracker |
| Attribution | City of Jackson |
| Category | Community Development |
| Tags | community, neighborhood associations, connected, city of jackson, super neighborhood, citizen engagment |
| Created | 2016-03-07T21:41:17Z |
| Publication Date | 2016-03-07T21:42:53Z |
| Rows Updated | 2016-03-07T21:41:25Z |

## Description

This dataset tracks the number of Neighborhood Associations engaged in the Super Neighborhood program and their participation start date.  This data is updated quarterly after Super Neighborhood training occurs.

## Columns

```ls
| Included | Schema Type    | Field Name                          | Name                                | Data Type     | Render Type   |
| ======== | ============== | =================================== | =================================== | ============= | ============= |
| Yes      | series tag     | cotacts_registered_1st_quarter_2016 | Cotacts Registered 1st Quarter 2016 | text          | text          |
| Yes      | numeric metric | projected_total_by_end_of_quarter   | Projected total by end of quarter   | number        | number        |
| Yes      | time           | date_received                       | Date Received:                      | calendar_date | calendar_date |
```

## Time Field

```ls
Value = date_received
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:jcxs-qmaz d:2016-03-07T00:00:00.000Z t:cotacts_registered_1st_quarter_2016="Westside Civic Club" m:projected_total_by_end_of_quarter=10

series e:jcxs-qmaz d:2017-03-12T10:49:33.739Z t:cotacts_registered_1st_quarter_2016="Contact projection for 2nd quarter 2016" m:projected_total_by_end_of_quarter=7

series e:jcxs-qmaz d:2017-03-12T10:49:33.739Z t:cotacts_registered_1st_quarter_2016="Contacts for 3rd and 4th Quarters" m:projected_total_by_end_of_quarter=13
```

## Meta Commands

```ls
metric m:projected_total_by_end_of_quarter p:integer l:"Projected total by end of quarter" t:dataTypeName=number

entity e:jcxs-qmaz l:"Super Neighborhood Tracker" t:attribution="City of Jackson" t:url=https://data.jacksonms.gov/api/views/jcxs-qmaz

property e:jcxs-qmaz t:meta.view v:id=jcxs-qmaz v:category="Community Development" v:attributionLink=http://www.jacksonms.gov v:averageRating=0 v:name="Super Neighborhood Tracker" v:attribution="City of Jackson"

property e:jcxs-qmaz t:meta.view.owner v:id=6ngd-c2u2 v:profileImageUrlMedium=/api/users/6ngd-c2u2/profile_images/THUMB v:profileImageUrlLarge=/api/users/6ngd-c2u2/profile_images/LARGE v:screenName="Justin Bruce" v:profileImageUrlSmall=/api/users/6ngd-c2u2/profile_images/TINY v:roleName=administrator v:displayName="Justin Bruce"

property e:jcxs-qmaz t:meta.view.tableauthor v:id=6ngd-c2u2 v:profileImageUrlMedium=/api/users/6ngd-c2u2/profile_images/THUMB v:profileImageUrlLarge=/api/users/6ngd-c2u2/profile_images/LARGE v:screenName="Justin Bruce" v:profileImageUrlSmall=/api/users/6ngd-c2u2/profile_images/TINY v:roleName=administrator v:displayName="Justin Bruce"
```