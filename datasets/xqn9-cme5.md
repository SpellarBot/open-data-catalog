# IDOT Average Annual Daily Traffic 2006

## Dataset

* [Dataset URL](https://data.illinois.gov/api/views/xqn9-cme5/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/idot-average-annual-daily-traffic-2006-5756d)
* [Metadata URL](https://data.illinois.gov/api/views/xqn9-cme5)
* Id = xqn9-cme5
* Name = IDOT Average Annual Daily Traffic 2006
* Attribution = Illinois Department of Transportation
* Category = Transportation
* Created = 2011-06-16T20:19:50Z
* Publication Date = 2012-01-26T16:55:17Z
* Rows Updated = 2012-01-26T16:41:43Z

## Description

This coverage contains a highway Annual Average Daily Traffic (AADT) subset of the information included in the IDOT Illinois Highway Information System (IHIS) -- Illinois Roadway Information System (IRIS). Information is collected for all public highways as defined in Illinois Compiled Statutes (605 ILCS 5/2-202).

## Columns

```ls
| Name       | Field Name  | Data Type | Render Type | Schema Type    | Included | 
| ========== | =========== | ========= | =========== | ============== | ======== | 
| updated_at | :updated_at | meta_data | meta_data   | time           | No       | 
| AADT       | aadt        | text      | text        | series tag     | Yes      | 
| AADT_YR    | aadt_yr     | number    | text        | numeric metric | Yes      | 
| MARKED_NAM | marked_nam  | text      | text        | series tag     | Yes      | 
| ROAD_NAME  | road_name   | text      | text        | series tag     | Yes      | 
| COUNTY_NAM | county_nam  | text      | text        | series tag     | Yes      | 
| HCV        | hcv         | text      | text        | series tag     | Yes      | 
| HCV_MU_YR  | hcv_mu_yr   | number    | text        | numeric metric | Yes      | 
| MU_VOL     | mu_vol      | text      | text        | series tag     | Yes      | 
| SU_VOL     | su_vol      | text      | text        | series tag     | Yes      | 
| MR_NUMBER  | mr_number   | number    | number      | numeric metric | Yes      | 
| MR_TYPE    | mr_type     | number    | text        | numeric metric | Yes      | 
| INVENTORY  | inventory   | text      | text        | series tag     | Yes      | 
| KEY_RT_NBR | key_rt_nbr  | number    | number      | numeric metric | Yes      | 
| POINT_X    | point_x     | number    | number      | numeric metric | Yes      | 
| POINT_Y    | point_y     | number    | number      | numeric metric | Yes      | 
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
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

property e:xqn9-cme5 t:meta.view d:2017-03-07T18:05:39.812Z v:id=xqn9-cme5 v:category=Transportation v:averageRating=0 v:name="IDOT Average Annual Daily Traffic 2006" v:attribution="Illinois Department of Transportation"

property e:xqn9-cme5 t:meta.view.owner d:2017-03-07T18:05:39.812Z v:id=ibpp-yb7w v:screenName="Jim Conlon" v:displayName="Jim Conlon"

property e:xqn9-cme5 t:meta.view.tableauthor d:2017-03-07T18:05:39.812Z v:id=ibpp-yb7w v:screenName="Jim Conlon" v:displayName="Jim Conlon"
```