# MDOT Performance Dashboard - Monthly Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/mdot-performance-dashboard-monthly-data) |
| Metadata | [Link](https://data.maryland.gov/api/views/n8ay-8iqy) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/n8ay-8iqy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/n8ay-8iqy/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | n8ay-8iqy |
| Name | MDOT Performance Dashboard - Monthly Data |
| Attribution | Maryland Department of Transportation |
| Category | Transportation |
| Created | 2016-07-28T21:53:32Z |
| Publication Date | 2017-01-12T15:17:05Z |

## Description

Contains monthly commercial passenger data at BWI Thurgood Marshall Airport.

## Columns

```ls
| Included | Schema Type    | Field Name                                                                         | Name                                                                               | Data Type     | Render Type   |
| ======== | ============== | ================================================================================== | ================================================================================== | ============= | ============= |
| Yes      | time           | date                                                                               | Date                                                                               | calendar_date | calendar_date |
| No       |                | year                                                                               | Year                                                                               | number        | text          |
| No       |                | month                                                                              | Month                                                                              | text          | text          |
| No       |                | date_label                                                                         | Date Label                                                                         | text          | text          |
| Yes      | numeric metric | baltimore_washington_international_thurgood_marshall_airport_commercial_passengers | Baltimore/Washington International Thurgood Marshall Airport Commercial Passengers | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = date_label,year,month
```

## Data Commands

```ls
series e:n8ay-8iqy d:2011-05-31T00:00:00.000Z m:baltimore_washington_international_thurgood_marshall_airport_commercial_passengers=2078548

series e:n8ay-8iqy d:2011-06-30T00:00:00.000Z m:baltimore_washington_international_thurgood_marshall_airport_commercial_passengers=2126776

series e:n8ay-8iqy d:2011-07-31T00:00:00.000Z m:baltimore_washington_international_thurgood_marshall_airport_commercial_passengers=2205035
```

## Meta Commands

```ls
metric m:baltimore_washington_international_thurgood_marshall_airport_commercial_passengers p:integer l:"Baltimore/Washington International Thurgood Marshall Airport Commercial Passengers" t:dataTypeName=number

entity e:n8ay-8iqy l:"MDOT Performance Dashboard - Monthly Data" t:attribution="Maryland Department of Transportation" t:url=https://data.maryland.gov/api/views/n8ay-8iqy

property e:n8ay-8iqy t:meta.view v:id=n8ay-8iqy v:category=Transportation v:averageRating=0 v:name="MDOT Performance Dashboard - Monthly Data" v:attribution="Maryland Department of Transportation"

property e:n8ay-8iqy t:meta.view.license v:name="Public Domain"

property e:n8ay-8iqy t:meta.view.owner v:id=w3wv-wxfw v:screenName="Mike Haley" v:displayName="Mike Haley"

property e:n8ay-8iqy t:meta.view.tableauthor v:id=w3wv-wxfw v:screenName="Mike Haley" v:roleName=editor v:displayName="Mike Haley"
```

## Top Records

```ls
| date                | year | month     | date_label | baltimore_washington_international_thurgood_marshall_airport_commercial_passengers | 
| =================== | ==== | ========= | ========== | ================================================================================== | 
| 2011-05-31T00:00:00 | 2011 | May       | May 2011   | 2078548                                                                            | 
| 2011-06-30T00:00:00 | 2011 | June      | Jun 2011   | 2126776                                                                            | 
| 2011-07-31T00:00:00 | 2011 | July      | Jul 2011   | 2205035                                                                            | 
| 2011-08-31T00:00:00 | 2011 | August    | Aug 2011   | 2051191                                                                            | 
| 2011-09-30T00:00:00 | 2011 | September | Sep 2011   | 1767564                                                                            | 
| 2011-10-31T00:00:00 | 2011 | October   | Oct 2011   | 1940029                                                                            | 
| 2011-11-30T00:00:00 | 2011 | November  | Nov 2011   | 1789962                                                                            | 
| 2011-12-31T00:00:00 | 2011 | December  | Dec 2011   | 1724216                                                                            | 
| 2012-01-31T00:00:00 | 2012 | January   | Jan 2012   | 1522469                                                                            | 
| 2012-02-29T00:00:00 | 2012 | February  | Feb 2012   | 1507692                                                                            | 
```