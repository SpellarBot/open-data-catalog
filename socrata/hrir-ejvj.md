# Toll Transactions

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/toll-transactions) |
| Metadata | [Link](https://data.maryland.gov/api/views/hrir-ejvj) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/hrir-ejvj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/hrir-ejvj/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | hrir-ejvj |
| Name | Toll Transactions |
| Attribution | Maryland Transportation Authority |
| Category | Transportation |
| Tags | tolls, toll transactions, mdta, toll facilities, e-zpass |
| Created | 2012-09-07T14:02:29Z |
| Publication Date | 2016-05-12T18:52:21Z |

## Description

Dataset contains counts of toll transactions collected by the MD Transportation Authority at its eight toll facilities.

## Columns

```ls
| Included | Schema Type    | Field Name                            | Name                                   | Data Type     | Render Type   |
| ======== | ============== | ===================================== | ====================================== | ============= | ============= |
| Yes      | time           | date                                  | Date                                   | calendar_date | calendar_date |
| Yes      | series tag     | facility                              | Facility                               | text          | text          |
| Yes      | numeric metric | total_transactions                    | Total Transactions                     | number        | number        |
| Yes      | numeric metric | electronic_transactions               | Transponder Transactions               | number        | number        |
| Yes      | numeric metric | percentage_of_electronic_transactions | Percentage of Transponder Transactions | percent       | percent       |
| Yes      | series tag     | comments                              | Comments                               | text          | text          |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:hrir-ejvj d:2012-10-30T00:00:00.000Z t:facility=BHT m:electronic_transactions=1453375 m:total_transactions=2058354 m:percentage_of_electronic_transactions=70.6

series e:hrir-ejvj d:2012-07-31T00:00:00.000Z t:facility=FMT m:electronic_transactions=2781129 m:total_transactions=4106681 m:percentage_of_electronic_transactions=69.41

series e:hrir-ejvj d:2012-07-31T00:00:00.000Z t:facility=FSK m:electronic_transactions=749688 m:total_transactions=1015814 m:percentage_of_electronic_transactions=73.8
```

## Meta Commands

```ls
metric m:total_transactions p:integer l:"Total Transactions" d:"Total number of all transactions collected at that facility for that indicated time period. Tranactions include electronic (E-ZPass, AVI, video, I-toll, etc), cash, tickets." t:dataTypeName=number

metric m:electronic_transactions p:integer l:"Transponder Transactions" d:"Total Count of all E-ZPass Transponder Transactions" t:dataTypeName=number

metric m:percentage_of_electronic_transactions p:integer l:"Percentage of Transponder Transactions" d:"Percentage of total transactions that were collected by a transponder." t:dataTypeName=percent

entity e:hrir-ejvj l:"Toll Transactions" t:attribution="Maryland Transportation Authority" t:url=https://data.maryland.gov/api/views/hrir-ejvj

property e:hrir-ejvj t:meta.view v:id=hrir-ejvj v:category=Transportation v:averageRating=0 v:name="Toll Transactions" v:attribution="Maryland Transportation Authority"

property e:hrir-ejvj t:meta.view.license v:name="Public Domain"

property e:hrir-ejvj t:meta.view.owner v:id=5x9h-2zmw v:screenName="Sarah Clifford" v:displayName="Sarah Clifford"

property e:hrir-ejvj t:meta.view.tableauthor v:id=5x9h-2zmw v:screenName="Sarah Clifford" v:roleName=publisher v:displayName="Sarah Clifford"
```

## Top Records

```ls
| date                | facility | total_transactions | electronic_transactions | percentage_of_electronic_transactions | comments                                                                                                                | 
| =================== | ======== | ================== | ======================= | ===================================== | ======================================================================================================================= | 
| 2012-10-30T00:00:00 | BHT      | 2058354            | 1453375                 | 70.6                                  |                                                                                                                         | 
| 2012-07-31T00:00:00 | FMT      | 4106681            | 2781129                 | 69.41                                 |                                                                                                                         | 
| 2012-07-31T00:00:00 | FSK      | 1015814            | 749688                  | 73.8                                  |                                                                                                                         | 
| 2012-08-31T00:00:00 | FSK      | 1104125            | 832071                  | 75.36                                 |                                                                                                                         | 
| 2012-08-31T00:00:00 | HMB      | 461001             | 275968                  | 59.86                                 |                                                                                                                         | 
| 2012-08-31T00:00:00 | ICC      | 1423802            |                         |                                       | Transponder Data not yet available. Previously reported transactions of 1,326,547 was updated in September to 1,423,802 | 
| 2012-08-31T00:00:00 | JFK      | 1446594            | 905288                  | 62.58                                 |                                                                                                                         | 
| 2012-08-31T00:00:00 | HWN      | 326955             | 155387                  | 47.53                                 |                                                                                                                         | 
| 2012-08-31T00:00:00 | BHT      | 1849657            | 1218709                 | 65.89                                 |                                                                                                                         | 
| 2012-09-30T00:00:00 | ICC      | 1267216            |                         |                                       | Transponder Data not yet available                                                                                      | 
```