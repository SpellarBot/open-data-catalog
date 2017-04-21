# Current Fleet Surplus/Auction List

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/current-fleet-surplus-auction-list-564d2) |
| Metadata | [Link](https://data.seattle.gov/api/views/6gnm-7jex) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/6gnm-7jex/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/6gnm-7jex/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | 6gnm-7jex |
| Name | Current Fleet Surplus/Auction List |
| Attribution | Fleet Management Division |
| Category | Finance |
| Tags | fleet, equipment, surplus, auction |
| Created | 2014-03-25T17:01:36Z |
| Publication Date | 2017-03-31T18:39:32Z |

## Description

Most recent list of fleet equipment sent to auction

## Columns

```ls
| Included | Schema Type | Field Name    | Name          | Data Type | Render Type |
| ======== | =========== | ============= | ============= | ========= | =========== |
| Yes      | series tag  | equip_id      | EQUIP_ID      | text      | text        |
| Yes      | time        | year          | YEAR          | number    | text        |
| Yes      | series tag  | make          | MAKE          | text      | text        |
| Yes      | series tag  | model         | MODEL         | text      | text        |
| Yes      | series tag  | color         | COLOR         | text      | text        |
| Yes      | series tag  | description   | DESCRIPTION   | text      | text        |
| Yes      | series tag  | auction_house | AUCTION HOUSE | text      | text        |
| Yes      | series tag  | comments      | COMMENTS      | text      | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
```

## Meta Commands

```ls
entity e:6gnm-7jex l:"Current Fleet Surplus/Auction List" t:attribution="Fleet Management Division" t:url=https://data.seattle.gov/api/views/6gnm-7jex

property e:6gnm-7jex t:meta.view v:id=6gnm-7jex v:category=Finance v:averageRating=0 v:name="Current Fleet Surplus/Auction List" v:attribution="Fleet Management Division"

property e:6gnm-7jex t:meta.view.license v:name="Public Domain"

property e:6gnm-7jex t:meta.view.owner v:id=sb28-e8im v:screenName="FAS - Fleet Management" v:displayName="FAS - Fleet Management"

property e:6gnm-7jex t:meta.view.tableauthor v:id=sb28-e8im v:screenName="FAS - Fleet Management" v:roleName=publisher v:displayName="FAS - Fleet Management"
```

## Top Records

```ls
| equip_id | year | make      | model          | color  | description                     | auction_house          | comments                 | 
| ======== | ==== | ========= | ============== | ====== | =============================== | ====================== | ======================== | 
| 61725    | 2006 | CHEVROLET | IMPALA         | BLACK  | MIDSIZE SEDAN                   | BIDADOO ONLINE AUCTION | REPLACED                 | 
| 62905    | 2006 | TOYOTA    | PRIUS          | SILVER | COMPACT SEDAN - HYBRID          | MURPHYS AUCTION        | REPLACED                 | 
| 31533    | 2011 | NISSAN    | LEAF           | WHITE  | SEDAN SUBCOMPACT ELECTRIC       | MURPHYS AUCTION        | REPLACMENT TBD - TOTALED | 
| 64628    | 2006 | FORD      | ESCAPE         | WHITE  | SUV COMPACT 4X4                 | MURPHYS AUCTION        |                          | 
| 63450    | 2006 | FORD      | F150           | GREEN  | PICKUP                          | BIDADOO ONLINE AUCTION | REPLACED                 | 
| 59856    | 2005 | FORD      | CROWN VICTORIA | BLACK  | FULLSIZE SEDAN                  | BIDADOO ONLINE AUCTION | REPLACED                 | 
| 65323    | 2006 | FORD      | E450           | RED    | MEDIC AID VAN - NEW BODY        | MURPHYS AUCTION        | REPLACMENT TBD - TOTALED | 
| 63566    | 2006 | CHEVROLET | COLORADO 4X4   | WHITE  | COMPACT PICKUP - CREW CAB - 4X4 | MURPHYS AUCTION        | REPLACED                 | 
| 70466    | 2007 | CHEVROLET | IMPALA         | SILVER | PEO MIDSIZE SEDAN               | BIDADOO ONLINE AUCTION | REPLACED                 | 
| 74509    | 2007 | CHEVROLET | COLORADO 4X4   | WHITE  | COMPACT PICKUP - CREW CAB - 4X4 | MURPHYS AUCTION        | REPLACMENT TBD - TOTALED | 
```