# Real Estate Sales By Town for 2011, 2012, 2013, 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/real-estate-sales-by-town-for-2011-2012) |
| Metadata | [Link](https://data.ct.gov/api/views/8udc-aepg) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/8udc-aepg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/8udc-aepg/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | 8udc-aepg |
| Name | Real Estate Sales By Town for 2011, 2012, 2013, 2014 |
| Category | Housing and Development |
| Tags | igp, opm, sales ratio, real estate sales |
| Created | 2014-09-11T12:22:47Z |
| Publication Date | 2016-09-27T17:09:22Z |

## Description

The Office of Policy and Management maintains a listing of all real estate sales with a sales price of $2,000 or greater that occur between October 1 and September 30 of each year. For each sale record, the file includes: town, property address, date of sale, property type (residential, apartment, commercial, industrial or vacant land), sales price, and property assessment

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type     | Render Type   |
| ======== | ============== | ================= | ================= | ============= | ============= |
| Yes      | series tag     | name              | Name              | text          | text          |
| Yes      | numeric metric | serialnbr         | SerialNbr         | number        | number        |
| No       |                | listyear          | ListYear          | number        | text          |
| Yes      | time           | daterecorded      | DateRecorded      | calendar_date | calendar_date |
| Yes      | numeric metric | assessedvalue     | AssessedValue     | money         | money         |
| Yes      | numeric metric | saleprice         | SalePrice         | money         | money         |
| Yes      | numeric metric | additionalremarks | AdditionalRemarks | number        | number        |
| Yes      | numeric metric | salesratio        | SalesRatio        | number        | number        |
| Yes      | series tag     | nonusecode        | NonUseCode        | text          | number        |
| Yes      | series tag     | residentialtype   | ResidentialType   | text          | text          |
| Yes      | numeric metric | residentialunits  | ResidentialUnits  | number        | number        |
| No       |                | address           | Address           | text          | text          |
```

## Time Field

```ls
Value = daterecorded
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address,listyear
```

## Data Commands

```ls
series e:8udc-aepg d:2012-03-08T00:00:00.000Z t:name=Bridgeport t:residentialtype=1 m:saleprice=233500 m:assessedvalue=162040 m:salesratio=0.693961456102784 m:serialnbr=110682 m:residentialunits=1

series e:8udc-aepg d:2013-01-16T00:00:00.000Z t:name=Ledyard t:residentialtype=C m:saleprice=75000 m:assessedvalue=67830 m:salesratio=0.9044 m:serialnbr=120059 m:residentialunits=1 m:additionalremarks=0

series e:8udc-aepg d:2013-05-31T00:00:00.000Z t:name=Milford t:residentialtype=1 m:saleprice=255000 m:assessedvalue=201300 m:salesratio=0.789411764705882 m:serialnbr=12497 m:residentialunits=1 m:additionalremarks=0
```

## Meta Commands

```ls
metric m:serialnbr p:integer l:SerialNbr d:"Serial Number" t:dataTypeName=number

metric m:assessedvalue p:double l:AssessedValue t:dataTypeName=money

metric m:saleprice p:integer l:SalePrice t:dataTypeName=money

metric m:additionalremarks p:integer l:AdditionalRemarks t:dataTypeName=number

metric m:salesratio p:float l:SalesRatio t:dataTypeName=number

metric m:residentialunits p:integer l:ResidentialUnits t:dataTypeName=number

entity e:8udc-aepg l:"Real Estate Sales By Town for 2011, 2012, 2013, 2014" t:url=https://data.ct.gov/api/views/8udc-aepg

property e:8udc-aepg t:meta.view v:id=8udc-aepg v:category="Housing and Development" v:averageRating=0 v:name="Real Estate Sales By Town for 2011, 2012, 2013, 2014"

property e:8udc-aepg t:meta.view.owner v:id=6ypf-grnx v:screenName="Jamie Gamble" v:displayName="Jamie Gamble"

property e:8udc-aepg t:meta.view.tableauthor v:id=6ypf-grnx v:screenName="Jamie Gamble" v:roleName=editor v:displayName="Jamie Gamble"
```

## Top Records

```ls
| name          | serialnbr | listyear | daterecorded        | assessedvalue | saleprice  | additionalremarks | salesratio        | nonusecode | residentialtype | residentialunits | address                | 
| ============= | ========= | ======== | =================== | ============= | ========== | ================= | ================= | ========== | =============== | ================ | ====================== | 
| Bridgeport    | 110682    | 2011     | 2012-03-08T00:00:00 | 162040.00     | 233500.00  |                   | 0.693961456102784 |            | 1               | 1                | 144 HUGHES AVE         | 
| Ledyard       | 120059    | 2012     | 2013-01-16T00:00:00 | 67830.00      | 75000.00   | 0                 | 0.9044            |            | C               | 1                | 1742-3G ROUTE 12       | 
| Milford       | 12497     | 2012     | 2013-05-31T00:00:00 | 201300.00     | 255000.00  | 0                 | 0.789411764705882 |            | 1               | 1                | 51 SPARROWBUSH LANE    | 
| New Haven     | 110828    | 2011     | 2012-07-30T00:00:00 | 49630.00      | 39900.00   |                   | 1.24385964912281  | 14         | 1               | 1                | 337 GREENWICH AVENUE   | 
| Colebrook     | 11007     | 2011     | 2012-05-14T00:00:00 | 196100.00     | 235000.00  |                   | 0.834468085106383 |            | 1               | 1                | 15 WHEELER RD          | 
| Wethersfield  | 12206     | 2012     | 2013-06-14T00:00:00 | 128400.00     | 165000.00  | 0                 | 0.778181818181818 | 10         | 1               | 1                | 56 CEDAR ST            | 
| New Canaan    | 120430    | 2012     | 2013-09-12T00:00:00 | 857920.00     | 1176501.00 | 0                 | 0.729213149840077 |            | 1               | 1                | 219 BUTTERY ROAD       | 
| East Hartford | 12125     | 2012     | 2013-09-03T00:00:00 | 83800.00      | 120000.00  | 0                 | 0.698333333333333 |            | C               | 1                | 31 HIGH ST., UNIT 8206 | 
| Litchfield    | 120048    | 2012     | 2013-03-20T00:00:00 | 171320.00     | 238000.00  | 0                 | 0.719831932773109 |            | 1               | 1                | 17 TOLL GATE RD        | 
| Southbury     | 11187     | 2011     | 2012-05-30T00:00:00 | 125370.00     | 119000.00  |                   | 1.05352941176471  |            | C               | 1                | 485 B HERITAGE VLG     | 
```