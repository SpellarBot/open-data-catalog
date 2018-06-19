# Procurement - Bid Tabulations Archive

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/procurement-bid-tabulations) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/pn38-yupm) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/pn38-yupm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/pn38-yupm/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | pn38-yupm |
| Name | Procurement - Bid Tabulations Archive |
| Attribution | Office of the Chief Procurement Officer |
| Category | Finance & Administration |
| Tags | procurement, purchase, contract, bid, rfp, rfi, award, bid tab, bid tabs |
| Created | 2016-06-23T04:05:27Z |
| Publication Date | 2016-06-29T22:51:01Z |

## Description

This is an archive of bid tabulations before June 2016. For current bid tabulations see https://datacatalog.cookcountyil.gov/d/32au-zaqn. The bid tabulations provided herein are preliminary and are for informational purposes only. The purpose of providing this preliminary information is to improve process transparency.  The information contained in the preliminary bid tabulations is subject to change pending math review, analysis of all bids, and review of documentation provided.

Bids:  All bids estimated at $25,000 or more are publicly opened and read at the time, date, and place specified in the bid document.

RFP/RFQ/RFI:  Responses to RFP/RFQ/RFI are not publicly opened. Names of respondents will be made available based on the names identified on the sealed package and is, therefore, subject to change.

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type     | Render Type   |
| ======== | =========== | ================ | ================ | ============= | ============= |
| Yes      | time        | bid_opening_date | Bid Opening Date | calendar_date | calendar_date |
| Yes      | series tag  | contract_number  | Contract Number  | text          | text          |
| Yes      | series tag  | description      | Description      | text          | text          |
| Yes      | series tag  | link             | Link             | url           | url           |
```

## Time Field

```ls
Value = bid_opening_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:pn38-yupm d:2016-04-29T00:00:00.000Z t:description="VETERINARY SERVICES" t:link=http://opendocs.cookcountyil.gov/procurement/bid-tabulations/1626-15368R.pdf t:contract_number=1626-15368R m:row_number.pn38-yupm=1

series e:pn38-yupm d:2016-04-27T00:00:00.000Z t:description="DESIGN ENGINEERING SERVICES" t:link=http://opendocs.cookcountyil.gov/procurement/bid-tabulations/1628-15166.pdf t:contract_number=1628-15166 m:row_number.pn38-yupm=2

series e:pn38-yupm d:2016-04-22T00:00:00.000Z t:description="WILLOUGHBY TOILET FIXTURES" t:link=http://opendocs.cookcountyil.gov/procurement/bid-tabulations/1626-15412.pdf t:contract_number=1626-15412 m:row_number.pn38-yupm=3
```

## Meta Commands

```ls
metric m:row_number.pn38-yupm p:long l:"Row Number"

entity e:pn38-yupm l:"Procurement - Bid Tabulations Archive" t:attribution="Office of the Chief Procurement Officer" t:url=https://datacatalog.cookcountyil.gov/api/views/pn38-yupm

property e:pn38-yupm t:meta.view v:id=pn38-yupm v:category="Finance & Administration" v:averageRating=0 v:name="Procurement - Bid Tabulations Archive" v:attribution="Office of the Chief Procurement Officer"

property e:pn38-yupm t:meta.view.license v:name="Public Domain"

property e:pn38-yupm t:meta.view.owner v:id=u38g-hbsa v:screenName="Cook County Open Data" v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"

property e:pn38-yupm t:meta.view.tableauthor v:id=u38g-hbsa v:screenName="Cook County Open Data" v:roleName=administrator v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"
```

## Top Records

```ls
| bid_opening_date    | contract_number | description                                        | link                                                                                   | 
| =================== | =============== | ================================================== | ====================================================================================== | 
| 2016-04-29T00:00:00 | 1626-15368R     | VETERINARY SERVICES                                | [http://opendocs.cookcountyil.gov/procurement/bid-tabulations/1626-15368R.pdf, null]   | 
| 2016-04-27T00:00:00 | 1628-15166      | DESIGN ENGINEERING SERVICES                        | [http://opendocs.cookcountyil.gov/procurement/bid-tabulations/1628-15166.pdf, null]    | 
| 2016-04-22T00:00:00 | 1626-15412      | WILLOUGHBY TOILET FIXTURES                         | [http://opendocs.cookcountyil.gov/procurement/bid-tabulations/1626-15412.pdf, null]    | 
| 2016-04-22T00:00:00 | 1626-15411      | ACORN SHOWER UNITS                                 | [http://opendocs.cookcountyil.gov/procurement/bid-tabulations/1626-15411.pdf, null]    | 
| 2016-04-22T00:00:00 | 1626-15407      | QUINCY COMPRESSOR SUPPLIES                         | [http://opendocs.cookcountyil.gov/procurement/bid-tabulations/1626-15407.pdf, null]    | 
| 2016-04-22T00:00:00 | 1581-14932      | MICROFILM READERS AND PRINTERS                     | [http://opendocs.cookcountyil.gov/procurement/bid-tabulations/1581-14932.pdf, null]    | 
| 2016-04-22T00:00:00 | 1511-15075r     | MAINTENANCE AND DECONTAMINATION SERVICES           | [http://opendocs.cookcountyil.gov/procurement/bid-tabulations/1511-15075r.pdf, null]   | 
| 2016-04-22T00:00:00 | 1645-15224      | FUSE SUPPLIES                                      | [http://opendocs.cookcountyil.gov/procurement/bid-tabulations/1645-15224.pdf, null]    | 
| 2016-04-22T00:00:00 | 1625-15301      | JANITORIAL SERVICES                                | [http://opendocs.cookcountyil.gov/procurement/bid-tabulations/1625-15301.pdf, null]    | 
| 2016-04-20T00:00:00 | 1515-14988R     | CONTINUOUS AND MULTI-EVENT SEQUENTIAL AIR MONITORS | [http://opendocs.cookcountyil.gov/procurement/bid-tabulations/1515-14988R-1.pdf, null] | 
```