# Maryland Total Residential Sales - PFA - 2012 - Zipcode

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-total-residential-sales-pfa-2012-zipcode-00dc0) |
| Metadata | [Link](https://data.maryland.gov/api/views/ag7x-nwtv) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/ag7x-nwtv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/ag7x-nwtv/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | ag7x-nwtv |
| Name | Maryland Total Residential Sales - PFA - 2012 - Zipcode |
| Attribution | Maryland Department of Planning |
| Category | Demographic |
| Tags | residential, sales, median, mean, value, inside pfa, outside pfa, mdproperty view, planning, mdp |
| Created | 2012-11-09T19:01:24Z |
| Publication Date | 2014-10-21T14:16:58Z |

## Description

Residential home sales based on MdProperty View Sales Databases created for Maryland?s 23 counties and Baltimore City for all 2012 Zip Code areas; also provides median and mean sales values and sales inside and outside Priority Funding Areas (PFA).
Priority Funding Areas are existing communities and places where local governments want State investment to support future growth

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| Yes      | time           | year            | Year            | number    | text        |
| Yes      | series tag     | geo_code        | Geo Code        | text      | text        |
| Yes      | series tag     | jurisdictions   | Jurisdictions   | text      | text        |
| Yes      | series tag     | zipcode         | Zipcode         | text      | text        |
| Yes      | numeric metric | tot_sales       | Tot_Sales       | number    | number      |
| Yes      | numeric metric | medianvalue     | MedianValue     | money     | money       |
| Yes      | numeric metric | meanvalue       | MeanValue       | money     | money       |
| Yes      | numeric metric | sales_insidepfa | Sales_insidePFA | number    | number      |
| Yes      | numeric metric | medval_inpfa    | MedVal_inPFA    | money     | money       |
| Yes      | numeric metric | meanvalue_inpfa | MeanValue_inPFA | money     | money       |
| Yes      | numeric metric | sales_outpfa    | Sales_OutPFA    | number    | number      |
| Yes      | numeric metric | medval_outpfa   | MedVal_OutPFA   | money     | money       |
| Yes      | numeric metric | meanval_outpfa  | MeanVal_OutPFA  | money     | money       |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ag7x-nwtv d:2012-01-01T00:00:00.000Z t:jurisdictions="Anne Arundel" t:zipcode=20779 m:sales_outpfa=8 m:meanvalue=521119 m:medianvalue=409975 m:meanval_outpfa=521119 m:tot_sales=8 m:medval_outpfa=409975

series e:ag7x-nwtv d:2012-01-01T00:00:00.000Z t:jurisdictions=Baltimore t:zipcode=21111 m:sales_outpfa=34 m:meanvalue=481884 m:medianvalue=460000 m:meanval_outpfa=481884 m:tot_sales=34 m:medval_outpfa=460000

series e:ag7x-nwtv d:2012-01-01T00:00:00.000Z t:jurisdictions=Somerset t:zipcode=21817 m:medval_inpfa=98500 m:sales_insidepfa=14 m:sales_outpfa=1 m:meanvalue=125587 m:meanvalue_inpfa=113200 m:medianvalue=98500 m:meanval_outpfa=999 m:tot_sales=15 m:medval_outpfa=999
```

## Meta Commands

```ls
metric m:tot_sales p:integer l:Tot_Sales t:dataTypeName=number

metric m:medianvalue p:integer l:MedianValue t:dataTypeName=money

metric m:meanvalue p:integer l:MeanValue t:dataTypeName=money

metric m:sales_insidepfa p:integer l:Sales_insidePFA t:dataTypeName=number

metric m:medval_inpfa p:integer l:MedVal_inPFA t:dataTypeName=money

metric m:meanvalue_inpfa p:integer l:MeanValue_inPFA t:dataTypeName=money

metric m:sales_outpfa p:integer l:Sales_OutPFA t:dataTypeName=number

metric m:medval_outpfa p:integer l:MedVal_OutPFA t:dataTypeName=money

metric m:meanval_outpfa p:integer l:MeanVal_OutPFA t:dataTypeName=money

entity e:ag7x-nwtv l:"Maryland Total Residential Sales - PFA - 2012 - Zipcode" t:attribution="Maryland Department of Planning" t:url=https://data.maryland.gov/api/views/ag7x-nwtv

property e:ag7x-nwtv t:meta.view v:id=ag7x-nwtv v:category=Demographic v:attributionLink=http://planning.maryland.gov/msdc/sale_data/saledata.shtml v:averageRating=0 v:name="Maryland Total Residential Sales - PFA - 2012 - Zipcode" v:attribution="Maryland Department of Planning"

property e:ag7x-nwtv t:meta.view.license v:name="Public Domain"

property e:ag7x-nwtv t:meta.view.owner v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:displayName=MDP

property e:ag7x-nwtv t:meta.view.tableauthor v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:roleName=editor v:displayName=MDP
```

## Top Records

```ls
| year | geo_code | jurisdictions  | zipcode | tot_sales | medianvalue | meanvalue | sales_insidepfa | medval_inpfa | meanvalue_inpfa | sales_outpfa | medval_outpfa | meanval_outpfa | 
| ==== | ======== | ============== | ======= | ========= | =========== | ========= | =============== | ============ | =============== | ============ | ============= | ============== | 
| 2012 |          | Anne Arundel   | 20779   | 8         | 409975      | 521119    |                 |              |                 | 8            | 409975        | 521119         | 
| 2012 |          | Baltimore      | 21111   | 34        | 460000      | 481884    |                 |              |                 | 34           | 460000        | 481884         | 
| 2012 |          | Somerset       | 21817   | 15        | 98500       | 125587    | 14              | 98500        | 113200          | 1            | 999           | 999            | 
| 2012 |          | Montgomery     | 20904   | 325       | 335000      | 335585    | 319             | 335000       | 334333          | 6            | 400000        | 402167         | 
| 2012 |          | Dorchester     | 21669   | 1         | 999         | 999       |                 |              |                 | 1            | 999           | 999            | 
| 2012 |          | Talbot         | 21612   | 7         | 652750      | 613929    | 2               | 999          | 999             | 5            | 652750        | 636500         | 
| 2012 |          | Baltimore City | 21215   | 183       | 63950       | 99702     | 183             | 63950        | 99702           |              |               |                | 
| 2012 |          | Charles        | 20622   | 17        | 346000      | 323063    |                 |              |                 | 17           | 346000        | 323063         | 
| 2012 |          | Harford        | 21132   | 15        | 405000      | 401315    |                 |              |                 | 15           | 405000        | 401315         | 
| 2012 |          | Washington     | 21722   | 18        | 207500      | 190717    | 3               | 999          | 999             | 15           | 207500        | 199327         | 
```