# Families & Education Levy III Estimated Revenues

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/families-education-levy-iii-estimated-revenues-f500e) |
| Metadata | [Link](https://data.seattle.gov/api/views/vu6n-t5x5) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/vu6n-t5x5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/vu6n-t5x5/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | vu6n-t5x5 |
| Name | Families & Education Levy III Estimated Revenues |
| Attribution | City of Seattle Office of Education |
| Category | Education |
| Tags | families, education, family, early learning, revenues |
| Created | 2010-06-03T17:38:39Z |
| Publication Date | 2011-04-17T00:03:09Z |

## Description

Families & Education Levy III Estimated Revenues
7-year levy (2nd half of 2005 through 1st half of 2012)		
Levy programs increase 1 1/2%/year once program is fully ramped up		
Levy admin is capped at 5%/year		
Crossing Guard program expires mid-2008

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| No       | time           | :updated_at        | updated_at         | meta_data | meta_data   |
| Yes      | series tag     | estimated_revenues | Estimated Revenues | text      | text        |
| Yes      | numeric metric | 2005               | 2005               | number    | number      |
| Yes      | numeric metric | 2006               | 2006               | number    | number      |
| Yes      | numeric metric | 2007               | 2007               | number    | number      |
| Yes      | numeric metric | 2008               | 2008               | number    | number      |
| Yes      | numeric metric | 2009               | 2009               | number    | number      |
| Yes      | numeric metric | 2010               | 2010               | number    | number      |
| Yes      | numeric metric | 2011               | 2011               | number    | number      |
| Yes      | numeric metric | 2012               | 2012               | number    | number      |
| Yes      | numeric metric | total              | Total              | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:vu6n-t5x5 d:2010-06-03T10:38:41.000Z t:estimated_revenues="Levy Legal Allocation (per Ordinance)" m:2008=16677000 m:total=116739000 m:2009=16677000 m:2006=16677000 m:2007=16677000 m:2005=16677000 m:2012=0 m:2011=16677000 m:2010=16677000

series e:vu6n-t5x5 d:2010-06-03T10:38:41.000Z t:estimated_revenues="Estimated Property taxes to be collected" m:2008=16608000 m:total=116134000 m:2009=16612000 m:2006=16509000 m:2007=16567000 m:2005=16265000 m:2012=348000 m:2011=16613000 m:2010=16612000

series e:vu6n-t5x5 d:2010-06-03T10:38:41.000Z t:estimated_revenues="Investment Earnings" m:2008=344000 m:total=2348000 m:2009=427000 m:2006=173000 m:2007=282000 m:2005=77000 m:2012=65000 m:2011=389000 m:2010=591000
```

## Meta Commands

```ls
metric m:2005 p:integer l:2005 t:dataTypeName=number

metric m:2006 p:integer l:2006 t:dataTypeName=number

metric m:2007 p:integer l:2007 t:dataTypeName=number

metric m:2008 p:integer l:2008 t:dataTypeName=number

metric m:2009 p:integer l:2009 t:dataTypeName=number

metric m:2010 p:integer l:2010 t:dataTypeName=number

metric m:2011 p:integer l:2011 t:dataTypeName=number

metric m:2012 p:integer l:2012 t:dataTypeName=number

metric m:total p:integer l:Total t:dataTypeName=number

entity e:vu6n-t5x5 l:"Families & Education Levy III Estimated Revenues" t:attribution="City of Seattle Office of Education" t:url=https://data.seattle.gov/api/views/vu6n-t5x5

property e:vu6n-t5x5 t:meta.view v:id=vu6n-t5x5 v:category=Education v:averageRating=0 v:name="Families & Education Levy III Estimated Revenues" v:attribution="City of Seattle Office of Education"

property e:vu6n-t5x5 t:meta.view.license v:name="Public Domain"

property e:vu6n-t5x5 t:meta.view.owner v:id=2h5m-u3bx v:screenName="Office of the Mayor" v:displayName="Office of the Mayor"

property e:vu6n-t5x5 t:meta.view.tableauthor v:id=2h5m-u3bx v:screenName="Office of the Mayor" v:roleName=publisher v:displayName="Office of the Mayor"
```

## Top Records

```ls
| :updated_at | estimated_revenues                       | 2005     | 2006     | 2007     | 2008     | 2009     | 2010     | 2011     | 2012   | total     | 
| =========== | ======================================== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ====== | ========= | 
| 1275561521  | Levy Legal Allocation (per Ordinance)    | 16677000 | 16677000 | 16677000 | 16677000 | 16677000 | 16677000 | 16677000 | 0      | 116739000 | 
| 1275561521  | Estimated Property taxes to be collected | 16265000 | 16509000 | 16567000 | 16608000 | 16612000 | 16612000 | 16613000 | 348000 | 116134000 | 
| 1275561521  | Investment Earnings                      | 77000    | 173000   | 282000   | 344000   | 427000   | 591000   | 389000   | 65000  | 2348000   | 
| 1275561521  | Subtotal                                 | 16342000 | 16682000 | 16849000 | 16952000 | 17039000 | 17203000 | 17002000 | 413000 | 118482000 | 
```