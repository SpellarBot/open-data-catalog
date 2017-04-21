# Damage By Sandy By Age Of Building

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/damage-by-sandy-by-age-of-building-c2c67) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/mgjt-zuui) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/mgjt-zuui/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/mgjt-zuui/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | mgjt-zuui |
| Name | Damage By Sandy By Age Of Building |
| Attribution | Department of City Planning (DCP) |
| Category | Housing & Development |
| Tags | dcp, city, planning, hurricane, sandy, damage |
| Created | 2013-02-13T19:37:43Z |
| Publication Date | 2013-06-21T20:42:53Z |

## Description

Details about how the age and code of the building correlates to destruction due to Storm Sandy

## Columns

```ls
| Included | Schema Type | Field Name         | Name               | Data Type | Render Type |
| ======== | =========== | ================== | ================== | ========= | =========== |
| No       | time        | :updated_at        | updated_at         | meta_data | meta_data   |
| Yes      | series tag  | year_built         | Year Built         | text      | text        |
| Yes      | series tag  | inundation_area    | Inundation area    | text      | text        |
| Yes      | series tag  | destroyed_by_storm | Destroyed by Storm | text      | text        |
| Yes      | series tag  | red_tags           | Red tags           | text      | text        |
| Yes      | series tag  | yellow_tags        | Yellow Tags        | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:mgjt-zuui d:2013-02-13T11:38:19.000Z t:yellow_tags=67% t:inundation_area=84% t:year_built="Before 1983" t:red_tags=94% t:destroyed_by_storm=98% m:row_number.mgjt-zuui=1

series e:mgjt-zuui d:2013-02-13T11:38:19.000Z t:yellow_tags=23% t:inundation_area=9% t:year_built=1983-2001 t:red_tags=4% t:destroyed_by_storm="< 1%" m:row_number.mgjt-zuui=2

series e:mgjt-zuui d:2013-02-13T11:38:19.000Z t:yellow_tags=9% t:inundation_area=5% t:year_built="2002 or later" t:red_tags=1% t:destroyed_by_storm="< 1%" m:row_number.mgjt-zuui=3
```

## Meta Commands

```ls
metric m:row_number.mgjt-zuui p:long l:"Row Number"

entity e:mgjt-zuui l:"Damage By Sandy By Age Of Building" t:attribution="Department of City Planning (DCP)" t:url=https://data.cityofnewyork.us/api/views/mgjt-zuui

property e:mgjt-zuui t:meta.view v:id=mgjt-zuui v:category="Housing & Development" v:attributionLink=http://www.nyc.gov/html/dcp/pdf/climate_resilience/presentation_sandy.pdf v:averageRating=0 v:name="Damage By Sandy By Age Of Building" v:attribution="Department of City Planning (DCP)"

property e:mgjt-zuui t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:mgjt-zuui t:meta.view.tableauthor v:id=8b43-zkvh v:screenName="Ram S." v:displayName="Ram S."
```

## Top Records

```ls
| :updated_at | year_built    | inundation_area | destroyed_by_storm | red_tags | yellow_tags | 
| =========== | ============= | =============== | ================== | ======== | =========== | 
| 1360755499  | Before 1983   | 84%             | 98%                | 94%      | 67%         | 
| 1360755499  | 1983-2001     | 9%              | < 1%               | 4%       | 23%         | 
| 1360755499  | 2002 or later | 5%              | < 1%               | 1%       | 9%          | 
| 1360755499  | No Data       | 2%              | 2%                 | 1%       | 1%          | 
```