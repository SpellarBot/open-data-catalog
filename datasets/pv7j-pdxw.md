# Noise Complaints

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/noise-complaints) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/pv7j-pdxw) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/pv7j-pdxw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/pv7j-pdxw/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | pv7j-pdxw |
| Name | Noise Complaints |
| Attribution | Montgomery County, MD |
| Category | Environment |
| Tags | noise, complaints |
| Created | 2016-11-08T19:38:32Z |
| Publication Date | 2016-11-10T16:30:32Z |

## Description

This dataset contains information on the Noise complaints initiated by citizens through 311 or web form. Update Frequency - Daily, Monday-Friday

## Columns

```ls
| Included | Schema Type | Field Name | Name             | Data Type     | Render Type   |
| ======== | =========== | ========== | ================ | ============= | ============= |
| Yes      | series tag  | case_no    | Case Number      | text          | number        |
| Yes      | time        | open_date  | Case Open Date   | calendar_date | calendar_date |
| No       |             | close_date | Case Close Date  | calendar_date | calendar_date |
| No       |             | case_year  | Case Year        | number        | text          |
| Yes      | series tag  | sub_type   | Case Sub-Type    | text          | text          |
| No       |             | address    | Address Zip Code | text          | text          |
```

## Time Field

```ls
Value = open_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = close_date,address,case_year
```

## Data Commands

```ls
series e:pv7j-pdxw d:2007-05-10T10:05:52.000Z t:sub_type="Industrial/commercial  construction/repair/demolit" t:case_no=19002 m:row_number.pv7j-pdxw=1

series e:pv7j-pdxw d:2016-02-05T13:04:59.000Z t:sub_type="Industrial/commercial  construction/repair/demolit" t:case_no=20161106 m:row_number.pv7j-pdxw=2

series e:pv7j-pdxw d:2007-12-28T10:58:39.000Z t:sub_type="Waiver Request" t:case_no=19847 m:row_number.pv7j-pdxw=3
```

## Meta Commands

```ls
metric m:row_number.pv7j-pdxw p:long l:"Row Number"

entity e:pv7j-pdxw l:"Noise Complaints" t:attribution="Montgomery County, MD" t:url=https://data.montgomerycountymd.gov/api/views/pv7j-pdxw

property e:pv7j-pdxw t:meta.view v:id=pv7j-pdxw v:category=Environment v:averageRating=0 v:name="Noise Complaints" v:attribution="Montgomery County, MD"

property e:pv7j-pdxw t:meta.view.license v:name="Public Domain"

property e:pv7j-pdxw t:meta.view.owner v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"

property e:pv7j-pdxw t:meta.view.tableauthor v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:roleName=administrator v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"
```

## Top Records

```ls
| case_no  | open_date           | close_date          | case_year | sub_type                                          | address | 
| ======== | =================== | =================== | ========= | ================================================= | ======= | 
| 19002    | 2007-05-10T10:05:52 | 2013-01-08T13:35:40 | 2007      | Industrial/commercial construction/repair/demolit | 20871   | 
| 20161106 | 2016-02-05T13:04:59 | 2016-04-07T09:37:35 | 2016      | Industrial/commercial construction/repair/demolit | 20906   | 
| 19847    | 2007-12-28T10:58:39 | 2008-04-25T15:14:24 | 2007      | Waiver Request                                    | 20895   | 
| 15816    | 2005-01-18T15:12:09 | 2005-01-27T09:58:44 | 2005      | Industrial/commercial Equipment Noise             | 20814   | 
| 20161573 | 2016-06-03T08:12:52 | 2016-06-20T15:26:36 | 2016      | Industrial/commercial Equipment Noise             |         | 
| 8280     | 1999-04-09T00:00:00 | 1999-05-06T00:00:00 | 1999      | Industrial/commercial Equipment Noise             | 20876   | 
| 19944    | 2008-01-31T10:20:51 | 2008-04-01T09:21:40 | 2008      | Residential El Amplification Equip                | 20879   | 
| 4883     | 1995-09-11T00:00:00 | 1995-11-30T00:00:00 | 1995      | Residential El Amplification Equip                | 20877   | 
| 19392    | 2007-08-13T07:25:28 | 2007-08-30T12:04:42 | 2007      | Industrial/commercial construction/repair/demolit |         | 
| 27313    | 2012-11-23T09:17:25 | 2013-01-14T11:45:22 | 2012      | Industrial/commercial Equipment Noise             | 20852   | 
```