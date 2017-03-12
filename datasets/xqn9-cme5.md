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
| Rows Updated | 2012-01-26T16:41:43Z |

## Description

This coverage contains a highway Annual Average Daily Traffic (AADT) subset of the information included in the IDOT Illinois Highway Information System (IHIS) -- Illinois Roadway Information System (IRIS). Information is collected for all public highways as defined in Illinois Compiled Statutes (605 ILCS 5/2-202).

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | aadt        | AADT       | text      | text        |
| Yes      | numeric metric | aadt_yr     | AADT_YR    | number    | text        |
| Yes      | series tag     | marked_nam  | MARKED_NAM | text      | text        |
| Yes      | series tag     | road_name   | ROAD_NAME  | text      | text        |
| Yes      | series tag     | county_nam  | COUNTY_NAM | text      | text        |
| Yes      | series tag     | hcv         | HCV        | text      | text        |
| Yes      | numeric metric | hcv_mu_yr   | HCV_MU_YR  | number    | text        |
| Yes      | series tag     | mu_vol      | MU_VOL     | text      | text        |
| Yes      | series tag     | su_vol      | SU_VOL     | text      | text        |
| Yes      | numeric metric | mr_number   | MR_NUMBER  | number    | number      |
| Yes      | numeric metric | mr_type     | MR_TYPE    | number    | text        |
| Yes      | series tag     | inventory   | INVENTORY  | text      | text        |
| Yes      | numeric metric | key_rt_nbr  | KEY_RT_NBR | number    | number      |
| Yes      | numeric metric | point_x     | POINT_X    | number    | number      |
| Yes      | numeric metric | point_y     | POINT_Y    | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:xqn9-cme5 d:2011-06-16T13:19:52.000Z t:mu_vol="Not Counted" t:su_vol="Not Counted" t:inventory="016  93726 000000" t:road_name=SHERIDAN t:aadt=3650 t:marked_nam=0 t:hcv="Not Counted" t:county_nam=Cook m:point_x=-87.7652 m:point_y=42.15233 m:mr_number=0 m:mr_type=0 m:key_rt_nbr=3726 m:aadt_yr=2006

series e:xqn9-cme5 d:2011-06-16T13:19:52.000Z t:mu_vol="Not Counted" t:su_vol="Not Counted" t:inventory="016  93726 000000" t:road_name="LAKE COOK RD" t:aadt=3650 t:marked_nam=0 t:hcv="Not Counted" t:county_nam=Cook m:point_x=-87.7706 m:point_y=42.15238 m:mr_number=0 m:mr_type=0 m:key_rt_nbr=3726 m:aadt_yr=2006

series e:xqn9-cme5 d:2011-06-16T13:19:52.000Z t:mu_vol="Not Counted" t:su_vol="Not Counted" t:inventory="016  93726 000000" t:road_name="LAKE COOK RD" t:aadt=6600 t:marked_nam=0 t:hcv="Not Counted" t:county_nam=Cook m:point_x=-87.7756 m:point_y=42.15238 m:mr_number=0 m:mr_type=0 m:key_rt_nbr=3726 m:aadt_yr=2006
```

## Meta Commands

```ls
metric m:aadt_yr l:AADT_YR d:"AVERAGE DAILY TRAFFIC COUNT YEAR" t:dataTypeName=number

metric m:hcv_mu_yr l:HCV_MU_YR d:"HEAVY COMMERCIAL/MULTI-UNIT COUNT YEAR" t:dataTypeName=number

metric m:mr_number p:integer l:MR_NUMBER t:dataTypeName=number

metric m:key_rt_nbr p:integer l:KEY_RT_NBR t:dataTypeName=number

metric m:point_x l:POINT_X t:dataTypeName=number

metric m:point_y l:POINT_Y t:dataTypeName=number

entity e:xqn9-cme5 l:"IDOT Average Annual Daily Traffic 2006" t:attribution="Illinois Department of Transportation" t:url=https://data.illinois.gov/api/views/xqn9-cme5

property e:xqn9-cme5 t:meta.view v:id=xqn9-cme5 v:category=Transportation v:averageRating=0 v:name="IDOT Average Annual Daily Traffic 2006" v:attribution="Illinois Department of Transportation"

property e:xqn9-cme5 t:meta.view.owner v:id=ibpp-yb7w v:screenName="Jim Conlon" v:displayName="Jim Conlon"

property e:xqn9-cme5 t:meta.view.tableauthor v:id=ibpp-yb7w v:screenName="Jim Conlon" v:displayName="Jim Conlon"
```