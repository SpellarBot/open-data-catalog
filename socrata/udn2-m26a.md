# Historical Auction Data, NYS Thruway Surplus Property

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/historical-auction-data-nys-thruway-surplus-property) |
| Metadata | [Link](https://data.ny.gov/api/views/udn2-m26a) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/udn2-m26a/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/udn2-m26a/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | udn2-m26a |
| Name | Historical Auction Data, NYS Thruway Surplus Property |
| Attribution | New York State Thruway Authority |
| Category | Transportation |
| Tags | thruway, auction, surplus property |
| Created | 2013-05-13T21:11:03Z |
| Publication Date | 2013-05-13T21:39:20Z |

## Description

This dataset contains a list of all surplus material sold at auction by the NYS Thruway Authority from the September 2010 through April 2013

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type     | Render Type   |
| ======== | ============== | ================== | ================== | ============= | ============= |
| Yes      | numeric metric | sale_yr            | SALE YR            | number        | number        |
| Yes      | series tag     | sale_no            | SALE NO            | text          | text          |
| Yes      | time           | sale_date          | SALE DATE          | calendar_date | calendar_date |
| Yes      | series tag     | sale_item_no       | SALE ITEM NO       | text          | text          |
| Yes      | series tag     | sale_type          | SALE TYPE          | text          | text          |
| Yes      | numeric metric | sale_price         | SALE PRICE         | money         | money         |
| Yes      | series tag     | description_line_1 | DESCRIPTION LINE 1 | text          | text          |
| Yes      | series tag     | description_line_2 | DESCRIPTION LINE 2 | text          | text          |
```

## Time Field

```ls
Value = sale_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:udn2-m26a d:2013-04-17T00:00:00.000Z t:sale_item_no=001 t:description_line_2="LOT OF 2  SONY DIGITAL CAMERA'S W/CHARGERS SONY MVC-FD97" t:sale_type=Auction t:description_line_1="LOT OF 2  SONY DIGITAL CAMERA'S W/CHARGERS" t:sale_no=001 m:sale_price=25 m:sale_yr=2013

series e:udn2-m26a d:2013-04-17T00:00:00.000Z t:sale_item_no=001 t:description_line_2="2001 SONY DIGITAL CAMERA SONY MVC-FD97" t:sale_type=Auction t:description_line_1="LOT OF 2  SONY DIGITAL CAMERA'S W/CHARGERS" t:sale_no=001 m:sale_price=25 m:sale_yr=2013

series e:udn2-m26a d:2013-04-17T00:00:00.000Z t:sale_item_no=001 t:description_line_2="2001 QUICK CHARGER SONY AC-VQ850" t:sale_type=Auction t:description_line_1="LOT OF 2  SONY DIGITAL CAMERA'S W/CHARGERS" t:sale_no=001 m:sale_price=25 m:sale_yr=2013
```

## Meta Commands

```ls
metric m:sale_yr p:integer l:"SALE YR" d:"Year that the sale took place" t:dataTypeName=number

metric m:sale_price p:double l:"SALE PRICE" d:"Price item or lot sold for" t:dataTypeName=money

entity e:udn2-m26a l:"Historical Auction Data, NYS Thruway Surplus Property" t:attribution="New York State Thruway Authority" t:url=https://data.ny.gov/api/views/udn2-m26a

property e:udn2-m26a t:meta.view v:id=udn2-m26a v:category=Transportation v:averageRating=0 v:name="Historical Auction Data, NYS Thruway Surplus Property" v:attribution="New York State Thruway Authority"

property e:udn2-m26a t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:udn2-m26a t:meta.view.tableauthor v:id=jtha-fqbi v:screenName="OPEN DATA NY Admin" v:roleName=publisher v:displayName="OPEN DATA NY Admin"

property e:udn2-m26a t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| sale_yr | sale_no | sale_date           | sale_item_no | sale_type | sale_price | description_line_1                        | description_line_2                                                       | 
| ======= | ======= | =================== | ============ | ========= | ========== | ========================================= | ======================================================================== | 
| 2013    | 001     | 2013-04-17T00:00:00 | 001          | Auction   | 25.00      | LOT OF 2 SONY DIGITAL CAMERA'S W/CHARGERS | LOT OF 2 SONY DIGITAL CAMERA'S W/CHARGERS SONY MVC-FD97                  | 
| 2013    | 001     | 2013-04-17T00:00:00 | 001          | Auction   | 25.00      | LOT OF 2 SONY DIGITAL CAMERA'S W/CHARGERS | 2001 SONY DIGITAL CAMERA SONY MVC-FD97                                   | 
| 2013    | 001     | 2013-04-17T00:00:00 | 001          | Auction   | 25.00      | LOT OF 2 SONY DIGITAL CAMERA'S W/CHARGERS | 2001 QUICK CHARGER SONY AC-VQ850                                         | 
| 2013    | 001     | 2013-04-17T00:00:00 | 001          | Auction   | 25.00      | LOT OF 2 SONY DIGITAL CAMERA'S W/CHARGERS | 2001 QUICK CHARGER NEWB SONY AC-VQ850                                    | 
| 2013    | 001     | 2013-04-17T00:00:00 | 002          | Auction   | 50.00      | LOT OF 6 ASSORTED CAMERA EQUIPMENT        | UNKNOWN TIME LAPSE VIDEO CASSETTE RECORDER UNKNOWN Qty: 1 good condition | 
| 2013    | 001     | 2013-04-17T00:00:00 | 002          | Auction   | 50.00      | LOT OF 6 ASSORTED CAMERA EQUIPMENT        | 2001 VCR RT TIME LAPSE                                                   | 
| 2013    | 001     | 2013-04-17T00:00:00 | 002          | Auction   | 50.00      | LOT OF 6 ASSORTED CAMERA EQUIPMENT        | 2001 SONY DIGITAL CAMERA                                                 | 
| 2013    | 001     | 2013-04-17T00:00:00 | 002          | Auction   | 50.00      | LOT OF 6 ASSORTED CAMERA EQUIPMENT        | 2001 SONY COLOR VIDEO CAMERA DC134                                       | 
| 2013    | 001     | 2013-04-17T00:00:00 | 002          | Auction   | 50.00      | LOT OF 6 ASSORTED CAMERA EQUIPMENT        | LOT OF 6 ASSORTED CAMERA EQUIPMENT 2001 SONY COLOR VIDEO CAMERA DC134    | 
| 2013    | 001     | 2013-04-17T00:00:00 | 002          | Auction   | 50.00      | LOT OF 6 ASSORTED CAMERA EQUIPMENT        | 1999 CAMERA MINOLTA W/2 LENSES worn                                      | 
```