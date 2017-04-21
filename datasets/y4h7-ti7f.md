# Battery Drop Off Locations: 2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/battery-drop-off-locations-2016) |
| Metadata | [Link](https://data.austintexas.gov/api/views/y4h7-ti7f) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/y4h7-ti7f/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/y4h7-ti7f/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | y4h7-ti7f |
| Name | Battery Drop Off Locations: 2016 |
| Category | Environmental |
| Tags | battery, drop off, location |
| Created | 2016-02-19T15:15:06Z |
| Publication Date | 2016-02-19T19:40:35Z |

## Description

This is a list of battery drop off locations. Only batteries will be accepted at these locations. DO NOT put any other items in bags with batteries. These locations are not equipped to handle other types of waste. *Please call first to make sure the location is actively participating in the program. Locations change often

## Columns

```ls
| Included | Schema Type | Field Name   | Name         | Data Type | Render Type |
| ======== | =========== | ============ | ============ | ========= | =========== |
| Yes      | series tag  | location     | Location     | text      | text        |
| Yes      | series tag  | zip_code     | Zip Code     | text      | text        |
| Yes      | series tag  | phone_number | Phone Number | text      | number      |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:y4h7-ti7f d:2016-01-01T00:00:00.000Z t:zip_code=78723 t:location="Radio Shack" m:row_number.y4h7-ti7f=1

series e:y4h7-ti7f d:2016-01-01T00:00:00.000Z t:zip_code=78723 t:location="Radio Shack" m:row_number.y4h7-ti7f=2

series e:y4h7-ti7f d:2016-01-01T00:00:00.000Z t:zip_code=78738 t:location="Radio Shack" m:row_number.y4h7-ti7f=3
```

## Meta Commands

```ls
metric m:row_number.y4h7-ti7f p:long l:"Row Number"

entity e:y4h7-ti7f l:"Battery Drop Off Locations: 2016" t:url=https://data.austintexas.gov/api/views/y4h7-ti7f

property e:y4h7-ti7f t:meta.view v:id=y4h7-ti7f v:category=Environmental v:averageRating=0 v:name="Battery Drop Off Locations: 2016"

property e:y4h7-ti7f t:meta.view.owner v:id=nnyu-u79i v:screenName=erin.benoit@austintexas.gov v:displayName=erin.benoit@austintexas.gov

property e:y4h7-ti7f t:meta.view.tableauthor v:id=nnyu-u79i v:screenName=erin.benoit@austintexas.gov v:roleName=editor v:displayName=erin.benoit@austintexas.gov
```

## Top Records

```ls
| location                    | zip_code | phone_number | 
| =========================== | ======== | ============ | 
| Radio Shack                 | 78723    |              | 
| Radio Shack                 | 78723    |              | 
| Radio Shack                 | 78738    |              | 
| Library: Pleasant Hill      | 78745    |              | 
| Radio Shack                 | 78746    |              | 
| Library: Hampton @ Oak Hill | 78749    |              | 
| Radio Shack                 | 78751    |              | 
| Radio Shack                 | 78753    |              | 
| Radio Shack                 | 78758    |              | 
| Fresh Plus                  | 78757    |              | 
```