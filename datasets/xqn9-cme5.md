# IDOT Average Annual Daily Traffic 2006

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idot-average-annual-daily-traffic-2006-5756d) |
| Metadata | [Link](https://data.illinois.gov/api/views/xqn9-cme5) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/xqn9-cme5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/xqn9-cme5/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | xqn9-cme5 |
| Name | IDOT Average Annual Daily Traffic 2006 |
| Attribution | Illinois Department of Transportation |
| Category | Transportation |
| Created | 2011-06-16T20:19:50Z |
| Publication Date | 2012-01-26T16:55:17Z |

## Description

This coverage contains a highway Annual Average Daily Traffic (AADT) subset of the information included in the IDOT Illinois Highway Information System (IHIS) -- Illinois Roadway Information System (IRIS). Information is collected for all public highways as defined in Illinois Compiled Statutes (605 ILCS 5/2-202).

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type | Render Type |
| ======== | ============== | ========== | ========== | ========= | =========== |
| Yes      | series tag     | aadt       | AADT       | text      | text        |
| Yes      | numeric metric | aadt_yr    | AADT_YR    | number    | text        |
| Yes      | series tag     | marked_nam | MARKED_NAM | text      | text        |
| Yes      | series tag     | road_name  | ROAD_NAME  | text      | text        |
| Yes      | series tag     | county_nam | COUNTY_NAM | text      | text        |
| Yes      | series tag     | hcv        | HCV        | text      | text        |
| Yes      | numeric metric | hcv_mu_yr  | HCV_MU_YR  | number    | text        |
| Yes      | series tag     | mu_vol     | MU_VOL     | text      | text        |
| Yes      | series tag     | su_vol     | SU_VOL     | text      | text        |
| Yes      | series tag     | mr_number  | MR_NUMBER  | text      | number      |
| Yes      | series tag     | mr_type    | MR_TYPE    | text      | text        |
| Yes      | series tag     | inventory  | INVENTORY  | text      | text        |
| Yes      | numeric metric | key_rt_nbr | KEY_RT_NBR | number    | number      |
| No       |                | point_x    | POINT_X    | number    | number      |
| No       |                | point_y    | POINT_Y    | number    | number      |
```

## Time Field

```ls
Value = 2006
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = point_x,point_y
```

## Data Commands

```ls
series e:xqn9-cme5 d:2006-01-01T00:00:00.000Z t:mu_vol="Not Counted" t:su_vol="Not Counted" t:mr_type=0 t:inventory="016  93726 000000" t:mr_number=0 t:road_name=SHERIDAN t:aadt=3650 t:marked_nam=0 t:hcv="Not Counted" t:county_nam=Cook m:key_rt_nbr=3726 m:aadt_yr=2006

series e:xqn9-cme5 d:2006-01-01T00:00:00.000Z t:mu_vol="Not Counted" t:su_vol="Not Counted" t:mr_type=0 t:inventory="016  93726 000000" t:mr_number=0 t:road_name="LAKE COOK RD" t:aadt=3650 t:marked_nam=0 t:hcv="Not Counted" t:county_nam=Cook m:key_rt_nbr=3726 m:aadt_yr=2006

series e:xqn9-cme5 d:2006-01-01T00:00:00.000Z t:mu_vol="Not Counted" t:su_vol="Not Counted" t:mr_type=0 t:inventory="016  93726 000000" t:mr_number=0 t:road_name="LAKE COOK RD" t:aadt=6600 t:marked_nam=0 t:hcv="Not Counted" t:county_nam=Cook m:key_rt_nbr=3726 m:aadt_yr=2006
```

## Meta Commands

```ls
metric m:aadt_yr p:long l:AADT_YR d:"AVERAGE DAILY TRAFFIC COUNT YEAR" t:dataTypeName=number

metric m:hcv_mu_yr p:long l:HCV_MU_YR d:"HEAVY COMMERCIAL/MULTI-UNIT COUNT YEAR" t:dataTypeName=number

metric m:key_rt_nbr p:integer l:KEY_RT_NBR t:dataTypeName=number

entity e:xqn9-cme5 l:"IDOT Average Annual Daily Traffic 2006" t:attribution="Illinois Department of Transportation" t:url=https://data.illinois.gov/api/views/xqn9-cme5

property e:xqn9-cme5 t:meta.view v:id=xqn9-cme5 v:category=Transportation v:averageRating=0 v:name="IDOT Average Annual Daily Traffic 2006" v:attribution="Illinois Department of Transportation"

property e:xqn9-cme5 t:meta.view.owner v:id=ibpp-yb7w v:screenName="Jim Conlon" v:displayName="Jim Conlon"

property e:xqn9-cme5 t:meta.view.tableauthor v:id=ibpp-yb7w v:screenName="Jim Conlon" v:displayName="Jim Conlon"
```

## Top Records

```ls
| aadt  | aadt_yr | marked_nam | road_name    | county_nam | hcv         | hcv_mu_yr | mu_vol      | su_vol      | mr_number | mr_type | inventory        | key_rt_nbr | point_x  | point_y  | 
| ===== | ======= | ========== | ============ | ========== | =========== | ========= | =========== | =========== | ========= | ======= | ================ | ========== | ======== | ======== | 
| 3650  | 2006    | 0          | SHERIDAN     | Cook       | Not Counted |           | Not Counted | Not Counted | 0         | 0       | 016 93726 000000 | 3726       | -87.7652 | 42.15233 | 
| 3650  | 2006    | 0          | LAKE COOK RD | Cook       | Not Counted |           | Not Counted | Not Counted | 0         | 0       | 016 93726 000000 | 3726       | -87.7706 | 42.15238 | 
| 6600  | 2006    | 0          | LAKE COOK RD | Cook       | Not Counted |           | Not Counted | Not Counted | 0         | 0       | 016 93726 000000 | 3726       | -87.7756 | 42.15238 | 
| 12600 | 2006    | 0          | LAKE COOK RD | Cook       | Not Counted |           | Not Counted | Not Counted | 0         | 0       | 016 93726 000000 | 3726       | -87.7878 | 42.15246 | 
| 12600 | 2006    | 0          | LAKE COOK RD | Cook       | Not Counted |           | Not Counted | Not Counted | 0         | 0       | 016 93726 000000 | 3726       | -87.7984 | 42.15258 | 
| 31300 | 2006    | 0          | LAKE COOK RD | Cook       | Not Counted |           | Not Counted | Not Counted | 0         | 0       | 016 20379 000000 | 379        | -87.7993 | 42.15258 | 
| 31300 | 2006    | 0          | LAKE COOK RD | Cook       | Not Counted |           | Not Counted | Not Counted | 0         | 0       | 016 20379 000000 | 379        | -87.8008 | 42.15258 | 
| 31300 | 2006    | 0          | LAKE COOK RD | Cook       | Not Counted |           | Not Counted | Not Counted | 0         | 0       | 016 20379 000000 | 379        | -87.8055 | 42.15253 | 
| 37000 | 2006    | 0          | LAKE COOK RD | Cook       | Not Counted |           | Not Counted | Not Counted | 0         | 0       | 016 20379 000000 | 379        | -87.8254 | 42.15270 | 
| 31300 | 2006    | 0          | LAKE COOK RD | Cook       | Not Counted |           | Not Counted | Not Counted | 0         | 0       | 016 20379 000000 | 379        | -87.8131 | 42.15254 | 
```