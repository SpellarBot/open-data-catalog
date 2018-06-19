# Connecticut List of Scenic Roads as of Dec 31 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/connecticut-list-of-scenic-roads-as-of-dec-31-2010) |
| Metadata | [Link](https://data.ct.gov/api/views/b9zb-xkhg) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/b9zb-xkhg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/b9zb-xkhg/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | b9zb-xkhg |
| Name | Connecticut List of Scenic Roads as of Dec 31 2010 |
| Attribution | Colleen Kissane |
| Category | Transportation |
| Created | 2015-10-22T12:57:51Z |
| Publication Date | 2015-10-22T12:59:58Z |

## Description

Connecticut List of Scenic Roads as of Dec 31 2010

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type     | Render Type   |
| ======== | ============== | =============== | =============== | ============= | ============= |
| Yes      | series tag     | route           | ROUTE           | text          | number        |
| Yes      | series tag     | town            | TOWN            | text          | text          |
| Yes      | time           | date_designated | DATE DESIGNATED | calendar_date | calendar_date |
| Yes      | numeric metric | miles           | MILES           | number        | number        |
| Yes      | series tag     | location        | LOCATION        | text          | text          |
```

## Time Field

```ls
Value = date_designated
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:b9zb-xkhg d:2008-10-14T00:00:00.000Z t:location="From Neck Road #2 north to Lovers Lane" t:route=1 t:town=Madison m:miles=2.3

series e:b9zb-xkhg d:1990-07-26T00:00:00.000Z t:location="From Route 7 west to Dunbar Road." t:route=4 t:town=Sharon m:miles=3.1

series e:b9zb-xkhg d:1992-10-22T00:00:00.000Z t:location="From Dunbar Road west to Old Sharon Road." t:route=4 t:town=Sharon m:miles=0.8
```

## Meta Commands

```ls
metric m:miles p:float l:MILES t:dataTypeName=number

entity e:b9zb-xkhg l:"Connecticut List of Scenic Roads as of Dec 31 2010" t:attribution="Colleen Kissane" t:url=https://data.ct.gov/api/views/b9zb-xkhg

property e:b9zb-xkhg t:meta.view v:id=b9zb-xkhg v:category=Transportation v:averageRating=0 v:name="Connecticut List of Scenic Roads as of Dec 31 2010" v:attribution="Colleen Kissane"

property e:b9zb-xkhg t:meta.view.owner v:id=krit-g9ue v:screenName="James Spencer" v:displayName="James Spencer"

property e:b9zb-xkhg t:meta.view.tableauthor v:id=krit-g9ue v:screenName="James Spencer" v:roleName=editor v:displayName="James Spencer"
```

## Top Records

```ls
| route | town                      | date_designated     | miles | location                                                                                            | 
| ===== | ========================= | =================== | ===== | =================================================================================================== | 
| 1     | Madison                   | 2008-10-14T00:00:00 | 2.3   | From Neck Road #2 north to Lovers Lane                                                              | 
| 4     | Sharon                    | 1990-07-26T00:00:00 | 3.10  | From Route 7 west to Dunbar Road.                                                                   | 
| 4     | Sharon                    | 1992-10-22T00:00:00 | 0.80  | From Dunbar Road west to Old Sharon Road.                                                           | 
| 4     | Harwinton                 | 1996-07-29T00:00:00 | 1.60  | From Cooks Dam west to Route 118                                                                    | 
| 118   |                           |                     | 0.10  | From Route 4 west to Cemetery Road                                                                  | 
| 7     | Sharon                    | 1990-07-26T00:00:00 | 4.29  | From the Cornwall Bridge crossing of the Housatonic River north to Route 128 at the covered bridge. | 
| 7     | Kent                      | 1991-10-17T00:00:00 | 10.50 | From the New Milford town line north to the Cornwall town line.                                     | 
| 7     | Cornwall                  | 2002-01-03T00:00:00 | 3.56  | From the Kent town line north to Route 4.                                                           | 
| 7     | Sharon, Salisbury, Canaan | 2002-01-03T00:00:00 | 10.26 | From Route 128 north to the North Canaan town line.                                                 | 
| 10    | Farmington                | 1999-04-13T00:00:00 | 1.0   | From Route 4 south to Tunxis Street.                                                                | 
```