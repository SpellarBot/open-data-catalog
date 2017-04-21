# Acceptable Reduced Pressure Zone Devices

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/acceptable-reduced-pressure-zone-devices-712c9) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/iftc-eqzb) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/iftc-eqzb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/iftc-eqzb/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | iftc-eqzb |
| Name | Acceptable Reduced Pressure Zone Devices |
| Attribution | Department of Environmental Protection (DEP) |
| Category | Environment |
| Tags | acceptable reduced pressure zone devices, dep, department of environmental protection |
| Created | 2014-03-06T03:11:10Z |
| Publication Date | 2014-03-06T03:12:38Z |

## Description

List of acceptable reduced pressure zone devices. Refer to the following report for more details http://www.nyc.gov/html/dep/pdf/water_sewer/42_doh_supplement.pdf

## Columns

```ls
| Included | Schema Type | Field Name   | Name         | Data Type | Render Type |
| ======== | =========== | ============ | ============ | ========= | =========== |
| No       | time        | :updated_at  | updated_at   | meta_data | meta_data   |
| Yes      | series tag  | company      | Company      | text      | text        |
| Yes      | series tag  | model_series | Model Series | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:iftc-eqzb d:2014-03-05T19:11:12.000Z t:company=AMES t:model_series=4000SS m:row_number.iftc-eqzb=1

series e:iftc-eqzb d:2014-03-05T19:11:12.000Z t:company=AMES t:model_series=4000B m:row_number.iftc-eqzb=2

series e:iftc-eqzb d:2014-03-05T19:11:12.000Z t:company=AMES t:model_series=4000BM2 m:row_number.iftc-eqzb=3
```

## Meta Commands

```ls
metric m:row_number.iftc-eqzb p:long l:"Row Number"

entity e:iftc-eqzb l:"Acceptable Reduced Pressure Zone Devices" t:attribution="Department of Environmental Protection (DEP)" t:url=https://data.cityofnewyork.us/api/views/iftc-eqzb

property e:iftc-eqzb t:meta.view v:id=iftc-eqzb v:category=Environment v:averageRating=0 v:name="Acceptable Reduced Pressure Zone Devices" v:attribution="Department of Environmental Protection (DEP)"

property e:iftc-eqzb t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:iftc-eqzb t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | company | model_series | 
| =========== | ======= | ============ | 
| 1394046672  | AMES    | 4000SS       | 
| 1394046672  | AMES    | 4000B        | 
| 1394046672  | AMES    | 4000BM2      | 
| 1394046672  | AMES    | COLT400      | 
| 1394046672  | AMES    | MAXIM400     | 
| 1394046672  | AMES    | COLT400N     | 
| 1394046672  | AMES    | COLT400Z     | 
| 1394046672  | AMES    | MAXIM400N    | 
| 1394046672  | AMES    | MAXIM400Z    | 
| 1394046672  | BUCKNER | 24000        | 
```