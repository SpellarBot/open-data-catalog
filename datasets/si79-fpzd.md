# What's Happening LA Calender - Type of Event Categories - Reference

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/whats-happening-la-calender-type-of-event-categories-reference) |
| Metadata | [Link](https://data.lacity.org/api/views/si79-fpzd) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/si79-fpzd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/si79-fpzd/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | si79-fpzd |
| Name | What's Happening LA Calender - Type of Event Categories - Reference |
| Attribution | individual |
| Category | A Livable and Sustainable City |
| Tags | citywide calendar, what's happening, type of event, event |
| Created | 2014-05-02T16:25:30Z |
| Publication Date | 2015-12-07T19:44:16Z |

## Description

Reference data set for type of event

## Columns

```ls
| Included | Schema Type | Field Name    | Name          | Data Type | Render Type |
| ======== | =========== | ============= | ============= | ========= | =========== |
| No       | time        | :updated_at   | updated_at    | meta_data | meta_data   |
| Yes      | series tag  | type_of_event | Type of Event | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:si79-fpzd d:2014-05-02T09:25:32.000Z t:type_of_event=Business m:row_number.si79-fpzd=1

series e:si79-fpzd d:2014-05-02T09:25:32.000Z t:type_of_event=Conference m:row_number.si79-fpzd=2

series e:si79-fpzd d:2014-05-02T09:25:32.000Z t:type_of_event="Consumer Show" m:row_number.si79-fpzd=3
```

## Meta Commands

```ls
metric m:row_number.si79-fpzd p:long l:"Row Number"

entity e:si79-fpzd l:"What's Happening LA Calender - Type of Event Categories - Reference" t:attribution=individual t:url=https://data.lacity.org/api/views/si79-fpzd

property e:si79-fpzd t:meta.view v:id=si79-fpzd v:category="A Livable and Sustainable City" v:averageRating=0 v:name="What's Happening LA Calender - Type of Event Categories - Reference" v:attribution=individual

property e:si79-fpzd t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:si79-fpzd t:meta.view.owner v:id=yb4r-dcys v:profileImageUrlMedium=/api/users/yb4r-dcys/profile_images/THUMB v:profileImageUrlLarge=/api/users/yb4r-dcys/profile_images/LARGE v:screenName="ITA OpenData" v:profileImageUrlSmall=/api/users/yb4r-dcys/profile_images/TINY v:displayName="ITA OpenData"

property e:si79-fpzd t:meta.view.tableauthor v:id=yb4r-dcys v:profileImageUrlMedium=/api/users/yb4r-dcys/profile_images/THUMB v:profileImageUrlLarge=/api/users/yb4r-dcys/profile_images/LARGE v:screenName="ITA OpenData" v:profileImageUrlSmall=/api/users/yb4r-dcys/profile_images/TINY v:roleName=publisher v:displayName="ITA OpenData"
```

## Top Records

```ls
| :updated_at | type_of_event     | 
| =========== | ================= | 
| 1399022732  | Business          | 
| 1399022732  | Conference        | 
| 1399022732  | Consumer Show     | 
| 1399022732  | Convention / Expo | 
| 1399022732  | Dinner / Banquet  | 
| 1399022732  | Education         | 
| 1399022732  | Fair              | 
| 1399022732  | Filming           | 
| 1399022732  | Hackathon         | 
| 1399022732  | Health            | 
```