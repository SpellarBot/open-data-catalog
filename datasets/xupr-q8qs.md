# IDOT Average Annual Daily Traffic 2008

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idot-average-annual-daily-traffic-2008-cd30a) |
| Metadata | [Link](https://data.illinois.gov/api/views/xupr-q8qs) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/xupr-q8qs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/xupr-q8qs/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | xupr-q8qs |
| Name | IDOT Average Annual Daily Traffic 2008 |
| Attribution | Illinois Department of Transportation |
| Category | Transportation |
| Tags | traffic, count |
| Created | 2011-06-17T13:16:56Z |
| Publication Date | 2012-01-26T16:24:32Z |

## Description

This coverage contains a highway Annual Average Daily Traffic (AADT) subset of the information included in the IDOT Illinois Highway Information System (IHIS) -- Illinois Roadway Information System (IRIS). Information is collected for all public highways as defined in Illinois Compiled Statutes (605 ILCS 5/2-202).

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| Yes      | series tag     | aadt        | AADT        | text      | text        |
| Yes      | numeric metric | aadt_yr     | AADT_YR     | number    | text        |
| Yes      | series tag     | marked_nam  | MARKED_NAM  | text      | text        |
| Yes      | numeric metric | aadt_yr_num | AADT_YR_NUM | number    | text        |
| Yes      | series tag     | road_name   | ROAD_NAME   | text      | text        |
| Yes      | series tag     | county_nam  | COUNTY_NAM  | text      | text        |
| Yes      | series tag     | hcv         | HCV         | text      | text        |
| Yes      | numeric metric | hcv_mu_yr   | HCV_MU_YR   | number    | text        |
| Yes      | series tag     | mu_vol      | MU_VOL      | text      | text        |
| Yes      | series tag     | su_vol      | SU_VOL      | text      | text        |
| Yes      | series tag     | mr_number   | MR_NUMBER   | text      | number      |
| Yes      | series tag     | mr_type     | MR_TYPE     | text      | number      |
| Yes      | series tag     | inventory   | INVENTORY   | text      | text        |
| Yes      | series tag     | key_rt_nbr  | KEY_RT_NBR  | text      | text        |
| No       |                | point_x     | POINT_X     | number    | number      |
| No       |                | point_y     | POINT_Y     | number    | number      |
```

## Time Field

```ls
Value = 2008
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = point_x,point_y
```

## Data Commands

```ls
series e:xupr-q8qs d:2008-01-01T00:00:00.000Z t:mu_vol="Not Counted" t:su_vol="Not Counted" t:key_rt_nbr=0003 t:inventory="002  70003 000000" t:mr_type=0 t:mr_number=0 t:road_name="S COUNTY LINE RD" t:aadt=375 t:marked_nam=0 t:hcv="Not Counted" t:county_nam=Alexander m:aadt_yr_num=2007 m:aadt_yr=2007

series e:xupr-q8qs d:2008-01-01T00:00:00.000Z t:mu_vol="Not Counted" t:su_vol="Not Counted" t:key_rt_nbr=0122 t:inventory="002  70122A000000" t:mr_type=0 t:mr_number=0 t:road_name="MOWERY VALLEY LN" t:aadt="Not Counted" t:marked_nam=0 t:hcv="Not Counted" t:county_nam=Alexander m:aadt_yr_num=0

series e:xupr-q8qs d:2008-01-01T00:00:00.000Z t:mu_vol="Not Counted" t:su_vol="Not Counted" t:key_rt_nbr=0003 t:inventory="002  70003 000000" t:mr_type=0 t:mr_number=0 t:road_name="COUNTY LINE RD" t:aadt=375 t:marked_nam=0 t:hcv="Not Counted" t:county_nam=Alexander m:aadt_yr_num=2007 m:aadt_yr=2007
```

## Meta Commands

```ls
metric m:aadt_yr p:long l:AADT_YR d:"AVERAGE DAILY TRAFFIC COUNT YEAR" t:dataTypeName=number

metric m:aadt_yr_num p:integer l:AADT_YR_NUM t:dataTypeName=number

metric m:hcv_mu_yr p:long l:HCV_MU_YR d:"HEAVY COMMERCIAL/MULTI-UNIT COUNT YEAR" t:dataTypeName=number

entity e:xupr-q8qs l:"IDOT Average Annual Daily Traffic 2008" t:attribution="Illinois Department of Transportation" t:url=https://data.illinois.gov/api/views/xupr-q8qs

property e:xupr-q8qs t:meta.view v:id=xupr-q8qs v:category=Transportation v:averageRating=0 v:name="IDOT Average Annual Daily Traffic 2008" v:attribution="Illinois Department of Transportation"

property e:xupr-q8qs t:meta.view.owner v:id=ibpp-yb7w v:screenName="Jim Conlon" v:displayName="Jim Conlon"

property e:xupr-q8qs t:meta.view.tableauthor v:id=ibpp-yb7w v:screenName="Jim Conlon" v:displayName="Jim Conlon"
```

## Top Records

```ls
| aadt        | aadt_yr | marked_nam | aadt_yr_num | road_name            | county_nam | hcv         | hcv_mu_yr | mu_vol      | su_vol      | mr_number | mr_type | inventory        | key_rt_nbr | point_x  | point_y  | 
| =========== | ======= | ========== | =========== | ==================== | ========== | =========== | ========= | =========== | =========== | ========= | ======= | ================ | ========== | ======== | ======== | 
| 375         | 2007    | 0          | 2007        | S COUNTY LINE RD     | Alexander  | Not Counted |           | Not Counted | Not Counted | 0         | 0       | 002 70003 000000 | 0003       | -89.2575 | 37.33541 | 
| Not Counted |         | 0          | 0           | MOWERY VALLEY LN     | Alexander  | Not Counted |           | Not Counted | Not Counted | 0         | 0       | 002 70122A000000 | 0122       | -89.2810 | 37.33426 | 
| 375         | 2007    | 0          | 2007        | COUNTY LINE RD       | Alexander  | Not Counted |           | Not Counted | Not Counted | 0         | 0       | 002 70003 000000 | 0003       | -89.2855 | 37.33360 | 
| 375         | 2007    | 0          | 2007        | COUNTY LINE RD       | Alexander  | Not Counted |           | Not Counted | Not Counted | 0         | 0       | 002 70003 000000 | 0003       | -89.2938 | 37.33355 | 
| Not Counted |         | 0          | 0           | WILDERNESS RETREAT   | Alexander  | Not Counted |           | Not Counted | Not Counted | 0         | 0       | 002 70122 000000 | 0122       | -89.2975 | 37.33419 | 
| 375         | 2007    | 0          | 2007        | COUNTY LINE RD       | Alexander  | Not Counted |           | Not Counted | Not Counted | 0         | 0       | 002 70003 000000 | 0003       | -89.2718 | 37.33383 | 
| 10          | 2007    | 0          | 2007        | CLEAR CREEK LEVEE RD | Alexander  | Not Counted |           | Not Counted | Not Counted | 0         | 0       | 002 70038 000000 | 0038       | -89.3835 | 37.33351 | 
| Not Counted |         | 0          | 0           | WEST CO LINE RD      | Alexander  | Not Counted |           | Not Counted | Not Counted | 0         | 0       | 002 70005 000000 | 0005       | -89.3948 | 37.33437 | 
| Not Counted |         | 0          | 0           | WALNUT RD            | Alexander  | Not Counted |           | Not Counted | Not Counted | 0         | 0       | 002 70019 000000 | 0019       | -89.2544 | 37.32876 | 
| 1300        | 2007    | IL 127     | 2007        |                      | Alexander  | 70          | 2007      | 30          | 40          | 127       |         | 002 31907 000000 | 1907       | -89.2526 | 37.33162 | 
```