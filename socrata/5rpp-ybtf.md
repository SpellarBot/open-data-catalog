# Procurement calendar

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/procurement-calendar) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/5rpp-ybtf) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/5rpp-ybtf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/5rpp-ybtf/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | 5rpp-ybtf |
| Name | Procurement calendar |
| Created | 2016-01-19T21:30:03Z |
| Publication Date | 2017-03-20T22:52:46Z |

## Columns

```ls
| Included | Schema Type | Field Name    | Name          | Data Type | Render Type |
| ======== | =========== | ============= | ============= | ========= | =========== |
| Yes      | time        | start_time    | Start time    | date      | date        |
| No       |             | end_time      | End time      | date      | date        |
| Yes      | series tag  | location_name | Location name | text      | text        |
| Yes      | series tag  | event_name    | Event name    | text      | text        |
| Yes      | series tag  | url           | URL           | url       | url         |
| Yes      | series tag  | business      | Business      | checkbox  | checkbox    |
| Yes      | series tag  | government    | Government    | checkbox  | checkbox    |
```

## Time Field

```ls
Value = start_time
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = end_time
```

## Data Commands

```ls
series e:5rpp-ybtf d:2016-01-21T09:00:00.000Z t:government=true t:event_name=TEST t:business=true m:row_number.5rpp-ybtf=1

series e:5rpp-ybtf d:2016-03-01T17:30:00.000Z t:location_name="Administration Building" t:government=true t:event_name="Oracle EBS iExpense Training" t:url=http://kcweb.metrokc.gov/des/brc/Oracle%20EBS/Training.aspx m:row_number.5rpp-ybtf=2

series e:5rpp-ybtf d:2016-03-01T21:30:00.000Z t:location_name="Dahlia Conference Room" t:government=true t:event_name="P-Card Training" t:url=https://www.eventbrite.com/e/p-card-training-king-county-employees-tickets-21230063692 m:row_number.5rpp-ybtf=3
```

## Meta Commands

```ls
metric m:row_number.5rpp-ybtf p:long l:"Row Number"

entity e:5rpp-ybtf l:"Procurement calendar" t:url=https://data.kingcounty.gov/api/views/5rpp-ybtf

property e:5rpp-ybtf t:meta.view v:id=5rpp-ybtf v:averageRating=0 v:name="Procurement calendar"

property e:5rpp-ybtf t:meta.view.owner v:id=vni2-xngb v:screenName=pryorli v:displayName=pryorli

property e:5rpp-ybtf t:meta.view.tableauthor v:id=vni2-xngb v:screenName=pryorli v:displayName=pryorli
```

## Top Records

```ls
| start_time | end_time   | location_name                      | event_name                                                  | url                                                                                                       | business | government | 
| ========== | ========== | ================================== | =========================================================== | ========================================================================================================= | ======== | ========== | 
| 1453366800 | 1453374000 |                                    | TEST                                                        | [null, null]                                                                                              | true     | true       | 
| 1456853400 | 1456862400 | Administration Building            | Oracle EBS iExpense Training                                | [http://kcweb.metrokc.gov/des/brc/Oracle%20EBS/Training.aspx, Oracle EBS Training]                        |          | true       | 
| 1456867800 | 1456875000 | Dahlia Conference Room             | P-Card Training                                             | [https://www.eventbrite.com/e/p-card-training-king-county-employees-tickets-21230063692, P-Card Training] |          | true       | 
| 1459357200 | 1459386000 | Washington State Convention Center | GoGreen Sustainability Conference for Business & Government | [http://seattle.gogreenconference.net/, GoGreen Conference]                                               | true     | true       | 
| 1462307400 | 1462316400 | Dahlia Conference Room             | P-Card Training                                             | [https://www.eventbrite.com/e/p-card-training-king-county-employees-tickets-21230063692, P-Card Training] |          | true       | 
| 1459888200 | 1457478000 | Dahlia Conference Room             | P-Card Training                                             | [https://www.eventbrite.com/e/p-card-training-king-county-employees-tickets-21230063692, P-Card Training] |          | true       | 
| 1465331400 | 1465336800 | Dahlia Conference Room             | P-Card Training                                             | [https://www.eventbrite.com/e/p-card-training-king-county-employees-tickets-21230063692, P-Card Training] |          | true       | 
| 1478032200 | 1478037600 | Dahlia Conference Room             | P-Card Training                                             | [https://www.eventbrite.com/e/p-card-training-king-county-employees-tickets-21230063692, P-Card Training] |          | true       | 
| 1467750600 | 1467756000 | Dahlia Conference Room             | P-Card Training                                             | [https://www.eventbrite.com/e/p-card-training-king-county-employees-tickets-21230063692, P-Card Training] |          | true       | 
| 1473193800 | 1473199200 | Dahlia Conference Room             | P-Card Training                                             | [https://www.eventbrite.com/e/p-card-training-king-county-employees-tickets-21230063692, P-Card Training] |          | true       | 
```