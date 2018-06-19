# Populated Places in Connecticut

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/populated-places-in-connecticut) |
| Metadata | [Link](https://data.ct.gov/api/views/t8jt-ytwj) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/t8jt-ytwj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/t8jt-ytwj/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | t8jt-ytwj |
| Name | Populated Places in Connecticut |
| Attribution | United State Geological Service |
| Category | Government |
| Tags | places, names, ct |
| Created | 2015-04-06T13:41:25Z |
| Publication Date | 2015-04-06T14:07:46Z |

## Description

A listing of named populated places within Connecticut. This listing represents a subset of place names in Connecticut from the U.S. Board on Geographic Names, and is limited to populated places.

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | town_no     | TOWN_NO    | text      | number      |
| Yes      | series tag  | geoname_no  | GEONAME_NO | text      | number      |
| Yes      | series tag  | name        | NAME       | text      | text        |
| Yes      | series tag  | short_name  | SHORT_NAME | text      | text        |
| Yes      | series tag  | category    | CATEGORY   | text      | text        |
| Yes      | series tag  | town        | TOWN       | text      | text        |
| No       |             | latitude    | Latitude   | number    | number      |
| No       |             | longitude   | Longitude  | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = latitude,longitude
```

## Data Commands

```ls
series e:t8jt-ytwj d:2015-04-06T06:41:37.000Z t:category="Populated Place" t:name=Hammertown t:town_no=122 t:geoname_no=1532 t:town=Salisbury t:short_name=Hammertown m:row_number.t8jt-ytwj=1

series e:t8jt-ytwj d:2015-04-06T06:41:37.000Z t:category="Populated Place" t:name=Weatogue t:town_no=122 t:geoname_no=1533 t:town=Salisbury t:short_name=Weatogue m:row_number.t8jt-ytwj=2

series e:t8jt-ytwj d:2015-04-06T06:41:37.000Z t:category="Populated Place" t:name="Canaan Valley" t:town_no=100 t:geoname_no=1534 t:town="North Canaan" t:short_name="Canaan Valley" m:row_number.t8jt-ytwj=3
```

## Meta Commands

```ls
metric m:row_number.t8jt-ytwj p:long l:"Row Number"

entity e:t8jt-ytwj l:"Populated Places in Connecticut" t:attribution="United State Geological Service" t:url=https://data.ct.gov/api/views/t8jt-ytwj

property e:t8jt-ytwj t:meta.view v:id=t8jt-ytwj v:category=Government v:attributionLink=http://geonames.usgs.gov/ v:averageRating=0 v:name="Populated Places in Connecticut" v:attribution="United State Geological Service"

property e:t8jt-ytwj t:meta.view.license v:name="Public Domain"

property e:t8jt-ytwj t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:t8jt-ytwj t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| :updated_at | town_no | geoname_no | name          | short_name    | category        | town         | latitude      | longitude      | 
| =========== | ======= | ========== | ============= | ============= | =============== | ============ | ============= | ============== | 
| 1428302497  | 122     | 1532       | Hammertown    | Hammertown    | Populated Place | Salisbury    | 42.0433809348 | -73.4125734091 | 
| 1428302497  | 122     | 1533       | Weatogue      | Weatogue      | Populated Place | Salisbury    | 42.0439238112 | -73.3448585621 | 
| 1428302497  | 100     | 1534       | Canaan Valley | Canaan Valley | Populated Place | North Canaan | 42.041049488  | -73.2567575885 | 
| 1428302498  | 29      | 1535       | McClaveville  | McClaveville  | Populated Place | Colebrook    | 42.0396180848 | -73.0961041679 | 
| 1428302498  | 122     | 1536       | Taconic       | Taconic       | Populated Place | Salisbury    | 42.0358065674 | -73.407850073  | 
| 1428302498  | 100     | 1537       | Sodom         | Sodom         | Populated Place | North Canaan | 42.0346933736 | -73.2979373745 | 
| 1428302498  | 139     | 1538       | Rising Corner | Rising Corner | Populated Place | Suffield     | 42.0355737365 | -72.7130155998 | 
| 1428302498  | 100     | 1539       | Canaan        | Canaan        | Populated Place | North Canaan | 42.0261728793 | -73.3278787746 | 
| 1428302498  | 141     | 1540       | Quinebaug     | Quinebaug     | Populated Place | Thompson     | 42.0237176955 | -71.9497950008 | 
| 1428302498  | 122     | 1541       | Twin Lakes    | Twin Lakes    | Populated Place | Salisbury    | 42.0185552922 | -73.3865065001 | 
```