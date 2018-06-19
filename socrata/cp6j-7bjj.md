# Fee Charges

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fee-charges-1c562) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/cp6j-7bjj) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/cp6j-7bjj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/cp6j-7bjj/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | cp6j-7bjj |
| Name | Fee Charges |
| Attribution | Department of Housing Preservation and Development (HPD) |
| Category | Housing & Development |
| Tags | fee charges, charges, department of housing preservation and development, hpd |
| Created | 2013-11-18T21:35:58Z |
| Publication Date | 2017-04-02T19:48:11Z |

## Description

Contains information about fees assessed against properties by HPD pursuant to the Housing Maintenance Code.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type     | Render Type   |
| ======== | ============== | =============== | =============== | ============= | ============= |
| Yes      | series tag     | feeid           | FeeID           | text          | number        |
| Yes      | series tag     | buildingid      | BuildingID      | text          | number        |
| Yes      | series tag     | boroid          | BoroID          | text          | number        |
| Yes      | series tag     | boro            | Boro            | text          | text          |
| Yes      | series tag     | housenumber     | HouseNumber     | text          | text          |
| Yes      | series tag     | streetname      | StreetName      | text          | text          |
| Yes      | series tag     | zip             | Zip             | text          | text          |
| Yes      | series tag     | block           | Block           | text          | number        |
| Yes      | series tag     | lot             | Lot             | text          | number        |
| Yes      | series tag     | lifecycle       | LifeCycle       | text          | text          |
| Yes      | series tag     | feetypeid       | FeeTypeID       | text          | number        |
| Yes      | series tag     | feetype         | FeeType         | text          | text          |
| Yes      | series tag     | feesourcetypeid | FeeSourceTypeID | text          | number        |
| Yes      | series tag     | feesourcetype   | FeeSourceType   | text          | text          |
| Yes      | series tag     | feesourceid     | FeeSourceID     | text          | number        |
| Yes      | time           | feeissueddate   | FeeIssuedDate   | calendar_date | calendar_date |
| Yes      | numeric metric | feeamount       | FeeAmount       | number        | number        |
| Yes      | series tag     | dofaccounttype  | DoFAccountType  | text          | text          |
| No       |                | doftransferdate | DoFTransferDate | calendar_date | calendar_date |
```

## Time Field

```ls
Value = feeissueddate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = doftransferdate
```

## Data Commands

```ls
series e:cp6j-7bjj d:2015-11-06T00:00:00.000Z t:dofaccounttype=240 t:zip=10019 t:boro=MANHATTAN t:buildingid=3844 t:feesourcetypeid=7 t:feetypeid=6 t:feesourcetype=VIOLATION t:block=1026 t:housenumber=854 t:feeid=444313 t:boroid=1 t:lifecycle=Building t:lot=35 t:feesourceid=10991189 t:feetype="Hot Water Inspection Fee" t:streetname="7 AVENUE" m:feeamount=200

series e:cp6j-7bjj d:2015-10-26T00:00:00.000Z t:dofaccounttype=240 t:zip=10019 t:boro=MANHATTAN t:buildingid=3844 t:feesourcetypeid=7 t:feetypeid=6 t:feesourcetype=VIOLATION t:block=1026 t:housenumber=854 t:feeid=444188 t:boroid=1 t:lifecycle=Building t:lot=35 t:feesourceid=10977982 t:feetype="Hot Water Inspection Fee" t:streetname="7 AVENUE" m:feeamount=200

series e:cp6j-7bjj d:2015-11-17T00:00:00.000Z t:dofaccounttype=240 t:zip=10019 t:boro=MANHATTAN t:buildingid=3844 t:feesourcetypeid=7 t:feetypeid=6 t:feesourcetype=VIOLATION t:block=1026 t:housenumber=854 t:feeid=444403 t:boroid=1 t:lifecycle=Building t:lot=35 t:feesourceid=11004251 t:feetype="Hot Water Inspection Fee" t:streetname="7 AVENUE" m:feeamount=200
```

## Meta Commands

```ls
metric m:feeamount p:float l:FeeAmount d:"Amount of Fee" t:dataTypeName=number

entity e:cp6j-7bjj l:"Fee Charges" t:attribution="Department of Housing Preservation and Development (HPD)" t:url=https://data.cityofnewyork.us/api/views/cp6j-7bjj

property e:cp6j-7bjj t:meta.view v:id=cp6j-7bjj v:category="Housing & Development" v:attributionLink=http://www.nyc.gov/html/hpd/html/pr/HPD-Open-Data.shtml v:averageRating=0 v:name="Fee Charges" v:attribution="Department of Housing Preservation and Development (HPD)"

property e:cp6j-7bjj t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:cp6j-7bjj t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| feeid  | buildingid | boroid | boro      | housenumber | streetname                   | zip   | block | lot | lifecycle | feetypeid | feetype                      | feesourcetypeid | feesourcetype        | feesourceid | feeissueddate       | feeamount | dofaccounttype | doftransferdate     | 
| ====== | ========== | ====== | ========= | =========== | ============================ | ===== | ===== | === | ========= | ========= | ============================ | =============== | ==================== | =========== | =================== | ========= | ============== | =================== | 
| 444313 | 3844       | 1      | MANHATTAN | 854         | 7 AVENUE                     | 10019 | 1026  | 35  | Building  | 6         | Hot Water Inspection Fee     | 7               | VIOLATION            | 10991189    | 2015-11-06T00:00:00 | 200.00    | 240            | 2015-11-20T00:00:00 | 
| 444188 | 3844       | 1      | MANHATTAN | 854         | 7 AVENUE                     | 10019 | 1026  | 35  | Building  | 6         | Hot Water Inspection Fee     | 7               | VIOLATION            | 10977982    | 2015-10-26T00:00:00 | 200.00    | 240            | 2015-11-20T00:00:00 | 
| 444403 | 3844       | 1      | MANHATTAN | 854         | 7 AVENUE                     | 10019 | 1026  | 35  | Building  | 6         | Hot Water Inspection Fee     | 7               | VIOLATION            | 11004251    | 2015-11-17T00:00:00 | 200.00    | 240            | 2015-11-20T00:00:00 | 
| 444254 | 3844       | 1      | MANHATTAN | 854         | 7 AVENUE                     | 10019 | 1026  | 35  | Building  | 6         | Hot Water Inspection Fee     | 7               | VIOLATION            | 10983004    | 2015-10-30T00:00:00 | 200.00    | 240            | 2015-11-20T00:00:00 | 
| 443768 | 3844       | 1      | MANHATTAN | 854         | 7 AVENUE                     | 10019 | 1026  | 35  | Building  | 6         | Hot Water Inspection Fee     | 7               | VIOLATION            | 10841105    | 2015-09-01T00:00:00 | 200.00    | 240            | 2015-09-18T00:00:00 | 
| 443828 | 3844       | 1      | MANHATTAN | 854         | 7 AVENUE                     | 10019 | 1026  | 35  | Building  | 6         | Hot Water Inspection Fee     | 7               | VIOLATION            | 10855808    | 2015-09-14T00:00:00 | 200.00    | 240            | 2015-09-18T00:00:00 | 
| 294161 | 3913       | 1      | MANHATTAN | 2076        | FREDERICK DOUGLASS BOULEVARD | 10026 | 1828  | 4   | Building  | 5         | Heat Inspection Fee          | 7               | VIOLATION            | 10521491    | 2015-01-30T00:00:00 | 200.00    | 240            | 2015-02-20T00:00:00 | 
| 606455 | 4037       | 1      | MANHATTAN | 2359        | FREDERICK DOUGLASS BOULEVARD | 10027 | 1953  | 33  | Building  | 3         | AEP Complaint Inspection Fee | 3               | Route for Inspection | 936429      | 2017-03-08T00:00:00 | 200.00    | 236            | 2017-03-20T00:00:00 | 
| 605448 | 4037       | 1      | MANHATTAN | 2359        | FREDERICK DOUGLASS BOULEVARD | 10027 | 1953  | 33  | Building  | 3         | AEP Complaint Inspection Fee | 3               | Route for Inspection | 927791      | 2017-01-19T00:00:00 | 200.00    | 236            | 2017-02-17T00:00:00 | 
| 604332 | 4037       | 1      | MANHATTAN | 2359        | FREDERICK DOUGLASS BOULEVARD | 10027 | 1953  | 33  | Building  | 3         | AEP Complaint Inspection Fee | 3               | Route for Inspection | 919456      | 2016-12-07T00:00:00 | 200.00    | 236            | 2016-12-20T00:00:00 | 
```