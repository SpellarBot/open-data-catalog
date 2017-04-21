# IDOT Average Annual Daily Traffic 2007

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idot-average-annual-daily-traffic-2007-3fe0c) |
| Metadata | [Link](https://data.illinois.gov/api/views/86j7-vghm) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/86j7-vghm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/86j7-vghm/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 86j7-vghm |
| Name | IDOT Average Annual Daily Traffic 2007 |
| Attribution | Illinois Department of Transportation |
| Category | Transportation |
| Tags | traffic, count |
| Created | 2011-06-17T13:08:02Z |
| Publication Date | 2012-01-26T17:07:05Z |

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
| Yes      | series tag     | mr_type    | MR_TYPE    | text      | number      |
| Yes      | series tag     | inventory  | INVENTORY  | text      | text        |
| Yes      | series tag     | key_rt_nbr | KEY_RT_NBR | text      | text        |
| No       |                | point_x    | POINT_X    | number    | number      |
| No       |                | point_y    | POINT_Y    | number    | number      |
```

## Time Field

```ls
Value = 2007
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = point_x,point_y
```

## Data Commands

```ls
series e:86j7-vghm d:2007-01-01T00:00:00.000Z t:mu_vol="Not Counted" t:su_vol="Not Counted" t:key_rt_nbr=0003 t:mr_type=0 t:inventory="002  70003 000000" t:mr_number=0 t:road_name="S COUNTY LINE RD" t:aadt=375 t:marked_nam=0 t:hcv="Not Counted" t:county_nam=Alexander m:aadt_yr=2007

series e:86j7-vghm d:2007-01-01T00:00:00.000Z t:mu_vol="Not Counted" t:su_vol="Not Counted" t:key_rt_nbr=0003 t:mr_type=0 t:inventory="002  70003 000000" t:mr_number=0 t:road_name="COUNTY LINE RD" t:aadt=375 t:marked_nam=0 t:hcv="Not Counted" t:county_nam=Alexander m:aadt_yr=2007

series e:86j7-vghm d:2007-01-01T00:00:00.000Z t:mu_vol="Not Counted" t:su_vol="Not Counted" t:key_rt_nbr=0003 t:mr_type=0 t:inventory="002  70003 000000" t:mr_number=0 t:road_name="COUNTY LINE RD" t:aadt=375 t:marked_nam=0 t:hcv="Not Counted" t:county_nam=Alexander m:aadt_yr=2007
```

## Meta Commands

```ls
metric m:aadt_yr p:long l:AADT_YR d:"AVERAGE DAILY TRAFFIC COUNT YEAR" t:dataTypeName=number

metric m:hcv_mu_yr p:long l:HCV_MU_YR d:"HEAVY COMMERCIAL/MULTI-UNIT COUNT YEAR" t:dataTypeName=number

entity e:86j7-vghm l:"IDOT Average Annual Daily Traffic 2007" t:attribution="Illinois Department of Transportation" t:url=https://data.illinois.gov/api/views/86j7-vghm

property e:86j7-vghm t:meta.view v:id=86j7-vghm v:category=Transportation v:averageRating=0 v:name="IDOT Average Annual Daily Traffic 2007" v:attribution="Illinois Department of Transportation"

property e:86j7-vghm t:meta.view.owner v:id=ibpp-yb7w v:screenName="Jim Conlon" v:displayName="Jim Conlon"

property e:86j7-vghm t:meta.view.tableauthor v:id=ibpp-yb7w v:screenName="Jim Conlon" v:displayName="Jim Conlon"
```

## Top Records

```ls
| aadt        | aadt_yr | marked_nam | road_name            | county_nam | hcv         | hcv_mu_yr | mu_vol      | su_vol      | mr_number | mr_type | inventory        | key_rt_nbr | point_x  | point_y  | 
| =========== | ======= | ========== | ==================== | ========== | =========== | ========= | =========== | =========== | ========= | ======= | ================ | ========== | ======== | ======== | 
| 375         | 2007    | 0          | S COUNTY LINE RD     | Alexander  | Not Counted |           | Not Counted | Not Counted | 0         | 0       | 002 70003 000000 | 0003       | -89.2575 | 37.33541 | 
| Not Counted |         | 0          | MOWERY VALLEY LN     | Alexander  | Not Counted |           | Not Counted | Not Counted | 0         | 0       | 002 70122A000000 | 0122       | -89.2810 | 37.33426 | 
| 375         | 2007    | 0          | COUNTY LINE RD       | Alexander  | Not Counted |           | Not Counted | Not Counted | 0         | 0       | 002 70003 000000 | 0003       | -89.2855 | 37.33360 | 
| 375         | 2007    | 0          | COUNTY LINE RD       | Alexander  | Not Counted |           | Not Counted | Not Counted | 0         | 0       | 002 70003 000000 | 0003       | -89.2938 | 37.33355 | 
| Not Counted |         | 0          | WILDERNESS RETREAT   | Alexander  | Not Counted |           | Not Counted | Not Counted | 0         | 0       | 002 70122 000000 | 0122       | -89.2975 | 37.33419 | 
| 375         | 2007    | 0          | COUNTY LINE RD       | Alexander  | Not Counted |           | Not Counted | Not Counted | 0         | 0       | 002 70003 000000 | 0003       | -89.2718 | 37.33383 | 
| 10          | 2007    | 0          | CLEAR CREEK LEVEE RD | Alexander  | Not Counted |           | Not Counted | Not Counted | 0         | 0       | 002 70038 000000 | 0038       | -89.3835 | 37.33351 | 
| Not Counted |         | 0          | WEST CO LINE RD      | Alexander  | Not Counted |           | Not Counted | Not Counted | 0         | 0       | 002 70005 000000 | 0005       | -89.3948 | 37.33437 | 
| Not Counted |         | 0          | WALNUT RD            | Alexander  | Not Counted |           | Not Counted | Not Counted | 0         | 0       | 002 70019 000000 | 0019       | -89.2544 | 37.32876 | 
| 1300        | 2007    | IL 127     |                      | Alexander  | 70          | 2007      | 30          | 40          | 127       |         | 002 31907 000000 | 1907       | -89.2526 | 37.33162 | 
```