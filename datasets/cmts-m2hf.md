# Operation Orange Street Resurfacing 2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/operation-orange-street-resurfacing-2016) |
| Metadata | [Link](https://data.jacksonms.gov/api/views/cmts-m2hf) |
| Data: JSON | [100 Rows](https://data.jacksonms.gov/api/views/cmts-m2hf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.jacksonms.gov/api/views/cmts-m2hf/rows.csv?max_rows=100) |
| Host | data.jacksonms.gov |
| Id | cmts-m2hf |
| Name | Operation Orange Street Resurfacing 2016 |
| Attribution | IMS Engineers/City of Jackson Public Works Department |
| Category | Public Works |
| Tags | street, paving, resurfacing, public works, infrastructure |
| Created | 2016-08-16T16:00:50Z |
| Publication Date | 2016-11-16T17:06:07Z |

## Description

Track Operation Orange Cone projects for 2016. ?Operation Orange Cone? is an initiative launched in 2015 as part of the Yarber Administration?s push to address the condition of the City?s streets and eliminate the presence of orange cones throughout the City where potholes exist.  While this initiative was first discussed in relation to the 1% Sales Tax program, it is an initiative which is part of the City?s Bold New Infrastructure Improvement Program.  Funding for Operation Orange Cone is not limited to Sales Tax funds and work will include in-house and contracted roadway maintenance projects, as well as roadway reconstruction and rehabilitation projects.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                      | Data Type     | Render Type   |
| ======== | ============== | ======================= | ========================= | ============= | ============= |
| Yes      | series tag     | ward                    | Ward                      | text          | number        |
| Yes      | series tag     | from                    | From                      | text          | text          |
| No       |                | to                      | To                        | text          | text          |
| Yes      | numeric metric | length_resurfaced_miles | Length Resurfaced (Miles) | number        | number        |
| Yes      | series tag     | fund_type               | Fund Type                 | text          | text          |
| Yes      | time           | year_completed          | Year Completed            | calendar_date | calendar_date |
```

## Time Field

```ls
Value = year_completed
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = to
```

## Data Commands

```ls
series e:cmts-m2hf d:2016-02-01T00:00:00.000Z t:fund_type="General Fund" t:ward=4 t:from="Hwy 18" m:length_resurfaced_miles=0.731

series e:cmts-m2hf d:2016-02-01T00:00:00.000Z t:fund_type="One Percent Funds" t:ward=6 t:from=Belvedere m:length_resurfaced_miles=0.292

series e:cmts-m2hf d:2016-03-01T00:00:00.000Z t:fund_type="General Fund" t:ward=4 t:from="West Capitol" m:length_resurfaced_miles=0.17
```

## Meta Commands

```ls
metric m:length_resurfaced_miles p:double l:"Length Resurfaced (Miles)" d:"Length of street resurfaced in miles" t:dataTypeName=number

entity e:cmts-m2hf l:"Operation Orange Street Resurfacing 2016" t:attribution="IMS Engineers/City of Jackson Public Works Department" t:url=https://data.jacksonms.gov/api/views/cmts-m2hf

property e:cmts-m2hf t:meta.view v:id=cmts-m2hf v:category="Public Works" v:attributionLink="http://www.jacksonms.gov/index.aspx?nid=670" v:averageRating=0 v:name="Operation Orange Street Resurfacing 2016" v:attribution="IMS Engineers/City of Jackson Public Works Department"

property e:cmts-m2hf t:meta.view.owner v:id=6ngd-c2u2 v:profileImageUrlMedium=/api/users/6ngd-c2u2/profile_images/THUMB v:profileImageUrlLarge=/api/users/6ngd-c2u2/profile_images/LARGE v:screenName="Justin Bruce" v:profileImageUrlSmall=/api/users/6ngd-c2u2/profile_images/TINY v:lastNotificationSeenAt=1492180672 v:displayName="Justin Bruce"

property e:cmts-m2hf t:meta.view.tableauthor v:id=6ngd-c2u2 v:profileImageUrlMedium=/api/users/6ngd-c2u2/profile_images/THUMB v:profileImageUrlLarge=/api/users/6ngd-c2u2/profile_images/LARGE v:screenName="Justin Bruce" v:profileImageUrlSmall=/api/users/6ngd-c2u2/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492180672 v:displayName="Justin Bruce"
```

## Top Records

```ls
| ward | from                | to              | length_resurfaced_miles | fund_type         | year_completed      | 
| ==== | =================== | =============== | ======================= | ================= | =================== | 
| 4    | Hwy 18              | Raymond Rd.     | 0.73099999999999998     | General Fund      | 2016-02-01T00:00:00 | 
| 6    | Belvedere           | Gunda St.       | 0.29199999999999998     | One Percent Funds | 2016-02-01T00:00:00 | 
| 4    | West Capitol        | Lindbergh       | 0.17                    | General Fund      | 2016-03-01T00:00:00 | 
| 4    | Byrd Street         | Veterans Blvd   | 0.432                   | General Fund      | 2016-03-01T00:00:00 | 
| 4    | Dead End            | Park Byrd Ave.  | 0.26                    | General Fund      | 2016-04-01T00:00:00 | 
| 4    | Norman St.          | Orrell St.      | 0.06                    | One Percent Funds | 2016-04-01T00:00:00 | 
| 4    | Gresham Cv.         | Dead End        | 0.03                    | One Percent Funds | 2016-05-01T00:00:00 | 
| 4    | Beach St.           | Capitol St.     | 0.32                    | One Percent Funds | 2016-05-01T00:00:00 | 
| 4    | Petunia St.         | Westhaven Blvd. | 0.19                    | One Percent Funds | 2016-05-01T00:00:00 | 
| 4    | Road of Remembrance | Rosslyn Ave.    | 0.08                    | One Percent Funds | 2016-05-01T00:00:00 | 
```