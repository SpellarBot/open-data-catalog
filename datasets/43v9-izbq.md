# IDOT Average Annual Daily Traffic 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idot-average-annual-daily-traffic-2009-aea95) |
| Metadata | [Link](https://data.illinois.gov/api/views/43v9-izbq) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/43v9-izbq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/43v9-izbq/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 43v9-izbq |
| Name | IDOT Average Annual Daily Traffic 2009 |
| Attribution | Illinois Department of Transportation |
| Category | Transportation |
| Tags | traffic, count |
| Created | 2011-06-17T13:47:04Z |
| Publication Date | 2012-01-26T16:02:19Z |

## Description

This coverage contains a highway Annual Average Daily Traffic (AADT) subset of the information included in the IDOT Illinois Highway Information System (IHIS) -- Illinois Roadway Information System (IRIS). Information is collected for all public highways as defined in Illinois Compiled Statutes (605 ILCS 5/2-202).

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type | Render Type |
| ======== | ============== | ========== | ========== | ========= | =========== |
| Yes      | series tag     | aadt       | AADT       | text      | text        |
| Yes      | numeric metric | aadtyr_str | AADTYR_STR | number    | text        |
| Yes      | series tag     | marked_nam | MARKED_NAM | text      | text        |
| Yes      | series tag     | road_name  | ROAD_NAME  | text      | text        |
| Yes      | series tag     | county_nam | COUNTY_NAM | text      | text        |
| Yes      | series tag     | hcv_aadt_s | HCV_AADT_S | text      | text        |
| Yes      | numeric metric | hcv_mu_yr  | HCV_MU_YR  | number    | text        |
| Yes      | series tag     | mu_vol     | MU_VOL     | text      | text        |
| Yes      | series tag     | su_vol     | SU_VOL     | text      | text        |
| Yes      | series tag     | mr_number  | MR_NUMBER  | text      | number      |
| Yes      | series tag     | mr_type    | MR_TYPE    | text      | number      |
| Yes      | series tag     | inventory  | INVENTORY  | text      | text        |
| Yes      | series tag     | key_rt_nbr | KEY_RT_NBR | text      | text        |
| No       |                | point_x    | POINT_X    | number    | number      |
| No       |                | point_y    | POINT_Y    | number    | number      |
```

## Time Field

```ls
Value = 2009
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = point_x,point_y
```

## Data Commands

```ls
series e:43v9-izbq d:2009-01-01T00:00:00.000Z t:hcv_aadt_s="Not Counted" t:mu_vol="Not Counted" t:su_vol="Not Counted" t:key_rt_nbr=3726 t:mr_type=0 t:inventory="016  93726 000000" t:mr_number=0 t:road_name="LAKE COOK RD" t:aadt=3650 t:marked_nam=0 t:county_nam=Cook m:aadtyr_str=2006

series e:43v9-izbq d:2009-01-01T00:00:00.000Z t:hcv_aadt_s="Not Counted" t:mu_vol="Not Counted" t:su_vol="Not Counted" t:key_rt_nbr=3726 t:mr_type=0 t:inventory="016  93726 000000" t:mr_number=0 t:road_name="LAKE COOK RD" t:aadt=6600 t:marked_nam=0 t:county_nam=Cook m:aadtyr_str=2006

series e:43v9-izbq d:2009-01-01T00:00:00.000Z t:hcv_aadt_s="Not Counted" t:mu_vol="Not Counted" t:su_vol="Not Counted" t:key_rt_nbr=3726 t:mr_type=0 t:inventory="016  93726 000000" t:mr_number=0 t:road_name="LAKE COOK RD" t:aadt=12600 t:marked_nam=0 t:county_nam=Cook m:aadtyr_str=2006
```

## Meta Commands

```ls
metric m:aadtyr_str p:long l:AADTYR_STR t:dataTypeName=number

metric m:hcv_mu_yr p:long l:HCV_MU_YR d:"HEAVY COMMERCIAL/MULTI-UNIT COUNT YEAR" t:dataTypeName=number

entity e:43v9-izbq l:"IDOT Average Annual Daily Traffic 2009" t:attribution="Illinois Department of Transportation" t:url=https://data.illinois.gov/api/views/43v9-izbq

property e:43v9-izbq t:meta.view v:id=43v9-izbq v:category=Transportation v:averageRating=0 v:name="IDOT Average Annual Daily Traffic 2009" v:attribution="Illinois Department of Transportation"

property e:43v9-izbq t:meta.view.owner v:id=ibpp-yb7w v:screenName="Jim Conlon" v:displayName="Jim Conlon"

property e:43v9-izbq t:meta.view.tableauthor v:id=ibpp-yb7w v:screenName="Jim Conlon" v:displayName="Jim Conlon"
```

## Top Records

```ls
| aadt        | aadtyr_str | marked_nam | road_name      | county_nam | hcv_aadt_s  | hcv_mu_yr | mu_vol      | su_vol      | mr_number | mr_type | inventory        | key_rt_nbr | point_x  | point_y  | 
| =========== | ========== | ========== | ============== | ========== | =========== | ========= | =========== | =========== | ========= | ======= | ================ | ========== | ======== | ======== | 
| Not Counted |            | 0          | PROVIDENCE RD  | Cook       | Not Counted |           | Not Counted | Not Counted | 0         | 0       | 016 03145 000320 | 3145       | -88.1309 | 42.16856 | 
| Not Counted |            | 0          | MEADOW WAY     | Cook       | Not Counted |           | Not Counted | Not Counted | 0         | 0       | 016 03130 000320 | 3130       | -88.1121 | 42.16405 | 
| Not Counted |            | 0          | SUNNY LANE     | Cook       | Not Counted |           | Not Counted | Not Counted | 0         | 0       | 016 02005 000320 | 2005       | -88.1368 | 42.16415 | 
| Not Counted |            | 0          | SYCAMORE RD    | Cook       | Not Counted |           | Not Counted | Not Counted | 0         | 0       | 016 01005 000320 | 1005       | -88.1352 | 42.16312 | 
| Not Counted |            | 0          | FOX GLOVE LN N | Cook       | Not Counted |           | Not Counted | Not Counted | 0         | 0       | 016 01270 000320 | 1270       | -88.1029 | 42.16039 | 
| 3650        | 2006       | 0          | LAKE COOK RD   | Cook       | Not Counted |           | Not Counted | Not Counted | 0         | 0       | 016 93726 000000 | 3726       | -87.7675 | 42.15232 | 
| 6600        | 2006       | 0          | LAKE COOK RD   | Cook       | Not Counted |           | Not Counted | Not Counted | 0         | 0       | 016 93726 000000 | 3726       | -87.7751 | 42.15236 | 
| 12600       | 2006       | 0          | LAKE COOK RD   | Cook       | Not Counted |           | Not Counted | Not Counted | 0         | 0       | 016 93726 000000 | 3726       | -87.7877 | 42.15244 | 
| 12600       | 2006       | 0          | LAKE COOK RD   | Cook       | Not Counted |           | Not Counted | Not Counted | 0         | 0       | 016 93726 000000 | 3726       | -87.7982 | 42.15249 | 
| 31300       | 2006       | 0          | LAKE COOK RD   | Cook       | Not Counted |           | Not Counted | Not Counted | 0         | 0       | 016 20379 000000 | 0379       | -87.7990 | 42.15249 | 
```