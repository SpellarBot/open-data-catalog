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

## Description

This dataset tracks the number of Neighborhood Associations engaged in the Super Neighborhood program and their participation start date.  This data is updated quarterly after Super Neighborhood training occurs.

## Columns

```ls
| Included | Schema Type | Field Name                          | Name                                | Data Type     | Render Type   |
| ======== | =========== | =================================== | =================================== | ============= | ============= |
| Yes      | series tag  | cotacts_registered_1st_quarter_2016 | Cotacts Registered 1st Quarter 2016 | text          | text          |
| No       |             | projected_total_by_end_of_quarter   | Projected total by end of quarter   | number        | number        |
| Yes      | time        | date_received                       | Date Received:                      | calendar_date | calendar_date |
```

## Time Field

```ls
Value = date_received
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = projected_total_by_end_of_quarter
```

## Data Commands

```ls
series e:jcxs-qmaz d:2016-03-07T00:00:00.000Z t:cotacts_registered_1st_quarter_2016="Westside Civic Club" m:row_number.jcxs-qmaz=1

series e:jcxs-qmaz d:2016-03-07T13:41:20.000Z t:cotacts_registered_1st_quarter_2016=ASJN m:row_number.jcxs-qmaz=2

series e:jcxs-qmaz d:2016-03-07T13:41:20.000Z t:cotacts_registered_1st_quarter_2016="Swan Lake NA" m:row_number.jcxs-qmaz=3
```

## Meta Commands

```ls
metric m:row_number.jcxs-qmaz p:long l:"Row Number"

entity e:jcxs-qmaz l:"Super Neighborhood Tracker" t:attribution="City of Jackson" t:url=https://data.jacksonms.gov/api/views/jcxs-qmaz

property e:jcxs-qmaz t:meta.view d:2017-09-25T07:30:25.815Z v:averageRating=0 v:name="Super Neighborhood Tracker" v:attribution="City of Jackson" v:attributionLink=http://www.jacksonms.gov v:id=jcxs-qmaz v:category="Community Development"

property e:jcxs-qmaz t:meta.view.owner d:2017-09-25T07:30:25.815Z v:displayName="Justin Bruce" v:lastNotificationSeenAt=1492180672 v:profileImageUrlLarge=/api/users/6ngd-c2u2/profile_images/LARGE v:profileImageUrlSmall=/api/users/6ngd-c2u2/profile_images/TINY v:id=6ngd-c2u2 v:screenName="Justin Bruce" v:profileImageUrlMedium=/api/users/6ngd-c2u2/profile_images/THUMB

property e:jcxs-qmaz t:meta.view.tableauthor d:2017-09-25T07:30:25.815Z v:displayName="Justin Bruce" v:lastNotificationSeenAt=1492180672 v:profileImageUrlLarge=/api/users/6ngd-c2u2/profile_images/LARGE v:roleName=administrator v:profileImageUrlSmall=/api/users/6ngd-c2u2/profile_images/TINY v:id=6ngd-c2u2 v:screenName="Justin Bruce" v:profileImageUrlMedium=/api/users/6ngd-c2u2/profile_images/THUMB
```

## Top Records

```ls
| cotacts_registered_1st_quarter_2016     | projected_total_by_end_of_quarter | date_received       | 
| ======================================= | ================================= | =================== | 
| Westside Civic Club                     | 10                                | 2016-03-07T00:00:00 | 
| ASJN                                    |                                   |                     | 
| Swan Lake NA                            |                                   |                     | 
| Cedar Hills                             |                                   |                     | 
| Mid City NA                             |                                   |                     | 
| Raintree Place NA                       |                                   |                     | 
| Brookhollow NA                          |                                   |                     | 
| Willowood NA                            |                                   |                     | 
| Capital                                 |                                   |                     | 
| Contact projection for 2nd quarter 2016 | 7                                 |                     | 
```