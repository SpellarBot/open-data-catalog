# Approved registrants in the wholesale markets

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/approved-registrants-in-the-wholesale-markets-ce955) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/sapz-4gsi) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/sapz-4gsi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/sapz-4gsi/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | sapz-4gsi |
| Name | Approved registrants in the wholesale markets |
| Attribution | Business Integrity Commission (BIC) |
| Category | Business |
| Tags | wholesale, vendor, market, registration, approved |
| Created | 2011-10-08T21:28:53Z |
| Publication Date | 2013-06-21T19:28:33Z |

## Description

Approved registrants in the wholesale markets

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | mtype       | MTYPE      | text      | text        |
| Yes      | series tag  | compname    | CompName   | text      | text        |
| Yes      | series tag  | comptel     | CompTel    | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:sapz-4gsi d:2011-10-08T14:28:54.000Z t:compname="CAPTAIN BLUE, LLC." t:mtype=FFM t:comptel="(703) 868-4622" m:row_number.sapz-4gsi=1

series e:sapz-4gsi d:2011-10-08T14:28:54.000Z t:compname="FRANK W. WILKISSON INC." t:mtype=FFM t:comptel=7185895280 m:row_number.sapz-4gsi=2

series e:sapz-4gsi d:2011-10-08T14:28:54.000Z t:compname="NICHLOSI BROTHERS LLC" t:mtype=HPA t:comptel="(856) 467-3494" m:row_number.sapz-4gsi=3
```

## Meta Commands

```ls
metric m:row_number.sapz-4gsi p:long l:"Row Number"

entity e:sapz-4gsi l:"Approved registrants in the wholesale markets" t:attribution="Business Integrity Commission (BIC)" t:url=https://data.cityofnewyork.us/api/views/sapz-4gsi

property e:sapz-4gsi t:meta.view v:id=sapz-4gsi v:category=Business v:averageRating=0 v:name="Approved registrants in the wholesale markets" v:attribution="Business Integrity Commission (BIC)"

property e:sapz-4gsi t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:sapz-4gsi t:meta.view.tableauthor v:id=txun-eb7e v:screenName="Albert Webber" v:roleName=administrator v:displayName="Albert Webber"
```

## Top Records

```ls
| :updated_at | mtype | compname                                | comptel        | 
| =========== | ===== | ======================================= | ============== | 
| 1318084134  | FFM   | CAPTAIN BLUE, LLC.                      | (703) 868-4622 | 
| 1318084134  | FFM   | FRANK W. WILKISSON INC.                 | 7185895280     | 
| 1318084134  | HPA   | NICHLOSI BROTHERS LLC                   | (856) 467-3494 | 
| 1318084134  | HPM   | NATION'S BEST MEAT WHOLESALERS, INC.    | 2018427400     | 
| 1318084134  | HPM   | NEBRASKALAND, INC.                      | 7188420700     | 
| 1318084134  | HPM   | SUPREME KOSHER MEAT                     | 7188605300     | 
| 1318084134  | HPP   | NATHEL & NATHEL, INC.                   | 7189916050     | 
| 1318084136  | BMM   | CHOWS BROTHERS WHOLESALE MEAT CO., INC. | (718) 836-8159 | 
| 1318084136  | BMM   | CHOW TRADING CO., INC.                  | (718) 238-8766 | 
| 1318084136  | BMM   | E & G FOODS, INC.                       | (718) 680-1300 | 
```