# Report Card 1: Overall Hawaii Visitor Numbers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/report-card-1-overall-hawaii-visitor-numbers-4c631) |
| Metadata | [Link](https://data.hawaii.gov/api/views/puxz-9rab) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/puxz-9rab/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/puxz-9rab/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | puxz-9rab |
| Name | Report Card 1: Overall Hawaii Visitor Numbers |
| Created | 2012-11-18T22:39:28Z |
| Publication Date | 2012-11-18T22:41:31Z |

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| Yes      | time           | year                   | Year                   | number    | text        |
| Yes      | numeric metric | total_visitor_arrivals | Total Visitor Arrivals | number    | number      |
| Yes      | numeric metric | domestic_arrivals      | Domestic Arrivals      | number    | number      |
| Yes      | numeric metric | international_arrivals | International Arrivals | number    | number      |
| Yes      | numeric metric | total_visitor_days     | Total Visitor Days     | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:puxz-9rab d:2002-01-01T00:00:00.000Z m:domestic_arrivals=4358850 m:total_visitor_arrivals=6389058 m:international_arrivals=2030208 m:total_visitor_days=58471088

series e:puxz-9rab d:2003-01-01T00:00:00.000Z m:domestic_arrivals=4531289 m:total_visitor_arrivals=6380439 m:international_arrivals=1849150 m:total_visitor_days=58782699

series e:puxz-9rab d:2004-01-01T00:00:00.000Z m:domestic_arrivals=4892960 m:total_visitor_arrivals=6912094 m:international_arrivals=2019134 m:total_visitor_days=62761989
```

## Meta Commands

```ls
metric m:total_visitor_arrivals p:integer l:"Total Visitor Arrivals" t:dataTypeName=number

metric m:domestic_arrivals p:integer l:"Domestic Arrivals" t:dataTypeName=number

metric m:international_arrivals p:integer l:"International Arrivals" t:dataTypeName=number

metric m:total_visitor_days p:integer l:"Total Visitor Days" t:dataTypeName=number

entity e:puxz-9rab l:"Report Card 1:  Overall Hawaii Visitor Numbers" t:url=https://data.hawaii.gov/api/views/puxz-9rab

property e:puxz-9rab t:meta.view d:2017-06-09T14:01:01.775Z v:id=puxz-9rab v:averageRating=0 v:name="Report Card 1:  Overall Hawaii Visitor Numbers"

property e:puxz-9rab t:meta.view.owner d:2017-06-09T14:01:01.775Z v:id=pvmv-89ja v:screenName="Daniel Nahoopii" v:displayName="Daniel Nahoopii"

property e:puxz-9rab t:meta.view.tableauthor d:2017-06-09T14:01:01.775Z v:id=pvmv-89ja v:screenName="Daniel Nahoopii" v:roleName=editor v:displayName="Daniel Nahoopii"
```

## Top Records

```ls
| year | total_visitor_arrivals | domestic_arrivals | international_arrivals | total_visitor_days | 
| ==== | ====================== | ================= | ====================== | ================== | 
| 2002 | 6389058                | 4358850           | 2030208                | 58471088           | 
| 2003 | 6380439                | 4531289           | 1849150                | 58782699           | 
| 2004 | 6912094                | 4892960           | 2019134                | 62761989           | 
| 2005 | 7416574                | 5313281           | 2103293                | 67687479           | 
| 2006 | 7528106                | 5550125           | 1977981                | 69145854           | 
| 2007 | 7496820                | 5582530           | 1914290                | 69135310           | 
| 2008 | 6713436                | 4901893           | 1811543                | 63130133           | 
| 2009 | 6420448                | 4672001           | 1748447                | 60255061           | 
| 2010 | 6982425                | 5022883           | 1959542                | 65598078           | 
| 2011 | 7174397                | 5127291           | 2047106                | 67825871           | 
```