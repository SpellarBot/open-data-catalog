# Lower Manhattan Retailers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lower-manhattan-retailers-53d81) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/cw88-qpsr) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/cw88-qpsr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/cw88-qpsr/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | cw88-qpsr |
| Name | Lower Manhattan Retailers |
| Attribution | Downtown Alliance |
| Category | Business |
| Tags | manhattan, downtown, retail, block, lot, vendor, sale, sell, community |
| Created | 2011-08-30T22:12:29Z |
| Publication Date | 2013-06-21T19:27:31Z |

## Description

Listing of lower Manhattan retailers

## Columns

```ls
| Included | Schema Type | Field Name         | Name               | Data Type | Render Type |
| ======== | =========== | ================== | ================== | ========= | =========== |
| No       | time        | :updated_at        | updated_at         | meta_data | meta_data   |
| Yes      | series tag  | cnbio_org_name     | CnBio_Org_Name     | text      | text        |
| Yes      | series tag  | cnadrprf_addrline1 | CnAdrPrf_Addrline1 | text      | text        |
| Yes      | series tag  | cnadrprf_addrline2 | CnAdrPrf_Addrline2 | text      | text        |
| Yes      | series tag  | cnadrprf_city      | CnAdrPrf_City      | text      | text        |
| Yes      | series tag  | cnadrprf_state     | CnAdrPrf_State     | text      | text        |
| Yes      | series tag  | cnadrprf_zip       | CnAdrPrf_ZIP       | text      | number      |
| Yes      | series tag  | block_lot          | Block-Lot          | text      | text        |
| Yes      | series tag  | primary            | Primary            | text      | text        |
| Yes      | series tag  | secondary          | Secondary          | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:cw88-qpsr d:2011-08-30T15:12:30.000Z t:primary=Primary t:secondary=Secondary t:block_lot=Block-Lot t:cnadrprf_state=CnAdrPrf_State t:cnadrprf_city=CnAdrPrf_City t:cnadrprf_addrline1=CnAdrPrf_Addrline1 t:cnbio_org_name=CnBio_Org_Name t:cnadrprf_addrline2=CnAdrPrf_Addrline2 m:row_number.cw88-qpsr=1

series e:cw88-qpsr d:2011-08-30T15:12:30.000Z t:cnadrprf_zip=10004 t:primary="Casual Eating & Takeout" t:secondary=F-Coffeehouse t:block_lot=8-32 t:cnadrprf_state=NY t:cnadrprf_city="New York" t:cnadrprf_addrline1="3 New York Plaza" t:cnbio_org_name="Starbucks Coffee" m:row_number.cw88-qpsr=2

series e:cw88-qpsr d:2011-08-30T15:12:30.000Z t:cnadrprf_zip=10004 t:primary="Personal and Professional Services" t:secondary="P-Athletic Clubs/Fitness" t:block_lot=8-32 t:cnadrprf_state=NY t:cnadrprf_city="New York" t:cnadrprf_addrline1="39 Whitehall Street" t:cnbio_org_name="New York Health & Racquet Club" m:row_number.cw88-qpsr=3
```

## Meta Commands

```ls
metric m:row_number.cw88-qpsr p:long l:"Row Number"

entity e:cw88-qpsr l:"Lower Manhattan Retailers" t:attribution="Downtown Alliance" t:url=https://data.cityofnewyork.us/api/views/cw88-qpsr

property e:cw88-qpsr t:meta.view v:id=cw88-qpsr v:category=Business v:averageRating=0 v:name="Lower Manhattan Retailers" v:attribution="Downtown Alliance"

property e:cw88-qpsr t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:cw88-qpsr t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | cnbio_org_name                    | cnadrprf_addrline1  | cnadrprf_addrline2 | cnadrprf_city | cnadrprf_state | cnadrprf_zip | block_lot | primary                            | secondary                | 
| =========== | ================================= | =================== | ================== | ============= | ============== | ============ | ========= | ================================== | ======================== | 
| 1314717150  | CnBio_Org_Name                    | CnAdrPrf_Addrline1  | CnAdrPrf_Addrline2 | CnAdrPrf_City | CnAdrPrf_State |              | Block-Lot | Primary                            | Secondary                | 
| 1314717150  | Starbucks Coffee                  | 3 New York Plaza    |                    | New York      | NY             | 10004        | 8-32      | Casual Eating & Takeout            | F-Coffeehouse            | 
| 1314717150  | New York Health & Racquet Club    | 39 Whitehall Street |                    | New York      | NY             | 10004        | 8-32      | Personal and Professional Services | P-Athletic Clubs/Fitness | 
| 1314717150  | A.J. Kelly's                      | 6 Stone Street      |                    | New York      | NY             | 10004        | 10-32     | Full Service Dining                | F-Irish Pub              | 
| 1314717150  | Fraunces Tavern? Restaurant       | 54 Pearl Street     |                    | New York      | NY             | 10004        | 7-35      | Full Service Dining                | F-American               | 
| 1314717150  | Bombay's                          | 60 Pearl Street     |                    | New York      | NY             | 10004        | 7-37      | Casual Eating & Takeout            | F-Indian                 | 
| 1314717150  | Pearl Bodywork                    | 60 Pearl Street     | Floor 2            | New York      | NY             | 10004        | 7-38      | Personal and Professional Services | P-Spa                    | 
| 1314717150  | McDonald's                        | 6 Water Street      |                    | New York      | NY             | 10004        | 8-51      | Casual Eating & Takeout            | F-Fast Food              | 
| 1314717150  | Water Street Gourmet Deli & Pizza | 12 Water Street     |                    | New York      | NY             | 10004        | 8-51      | Casual Eating & Takeout            | F-Deli                   | 
| 1314717150  | Alice's Fashion                   | 1 New York Plaza    |                    | New York      | NY             | 10004        | 4-1       | Shopping                           | S-Apparel: Women's       | 
```