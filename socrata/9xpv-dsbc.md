# Families & Education Levy III Expenditures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/families-education-levy-iii-expenditures-2e88a) |
| Metadata | [Link](https://data.seattle.gov/api/views/9xpv-dsbc) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/9xpv-dsbc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/9xpv-dsbc/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | 9xpv-dsbc |
| Name | Families & Education Levy III Expenditures |
| Category | Education |
| Tags | families, education, family, early learning, expenditures |
| Created | 2010-06-03T15:47:01Z |
| Publication Date | 2011-04-17T00:03:09Z |

## Description

Families & Education Levy III		
Projected Expenditures for seven-year levy (Original Plan)		

7-year levy (2nd half of 2005 through 1st half of 2012)		
Levy programs increase 1 1/2%/year once program is fully ramped up		
Levy admin is capped at 5%/year		
Crossing Guard program expires mid-2008

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                           | Data Type | Render Type |
| ======== | ============== | ============================ | ============================== | ========= | =========== |
| No       | time           | :updated_at                  | updated_at                     | meta_data | meta_data   |
| Yes      | series tag     | investment_area_expenditures | Investment Area - Expenditures | text      | text        |
| Yes      | numeric metric | 2005                         | 2005                           | number    | number      |
| Yes      | numeric metric | 2006                         | 2006                           | number    | number      |
| Yes      | numeric metric | 2007                         | 2007                           | number    | number      |
| Yes      | numeric metric | 2008                         | 2008                           | number    | number      |
| Yes      | numeric metric | 2009                         | 2009                           | number    | number      |
| Yes      | numeric metric | 2010                         | 2010                           | number    | number      |
| Yes      | numeric metric | 2011                         | 2011                           | number    | number      |
| Yes      | numeric metric | 2012                         | 2012                           | number    | number      |
| Yes      | numeric metric | total                        | Total                          | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:9xpv-dsbc d:2010-06-03T08:47:03.000Z t:investment_area_expenditures="Early Learning Networks" m:2008=4025554 m:total=26125197 m:2009=4085937 m:2006=2587603 m:2007=3310118 m:2005=1240983 m:2012=2518341 m:2011=4209435 m:2010=4147226

series e:9xpv-dsbc d:2010-06-03T08:47:03.000Z t:investment_area_expenditures="Middle School Support" m:2008=1045678 m:total=7395588 m:2009=1061364 m:2006=1014321 m:2007=1030225 m:2005=329677 m:2012=743596 m:2011=1093443 m:2010=1077284

series e:9xpv-dsbc d:2010-06-03T08:47:03.000Z t:investment_area_expenditures="Out of School Time" m:2008=3146500 m:total=20678312 m:2009=3193698 m:2006=2078489 m:2007=2743582 m:2005=746694 m:2012=2237519 m:2011=3290227 m:2010=3241603
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

entity e:9xpv-dsbc l:"Families & Education Levy III Expenditures" t:url=https://data.seattle.gov/api/views/9xpv-dsbc

property e:9xpv-dsbc t:meta.view v:id=9xpv-dsbc v:category=Education v:averageRating=0 v:name="Families & Education Levy III Expenditures"

property e:9xpv-dsbc t:meta.view.owner v:id=2h5m-u3bx v:screenName="Office of the Mayor" v:displayName="Office of the Mayor"

property e:9xpv-dsbc t:meta.view.tableauthor v:id=2h5m-u3bx v:screenName="Office of the Mayor" v:roleName=publisher v:displayName="Office of the Mayor"
```

## Top Records

```ls
| :updated_at | investment_area_expenditures | 2005    | 2006    | 2007    | 2008    | 2009    | 2010    | 2011    | 2012    | total    | 
| =========== | ============================ | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======== | 
| 1275554823  | Early Learning Networks      | 1240983 | 2587603 | 3310118 | 4025554 | 4085937 | 4147226 | 4209435 | 2518341 | 26125197 | 
| 1275554823  | Middle School Support        | 329677  | 1014321 | 1030225 | 1045678 | 1061364 | 1077284 | 1093443 | 743596  | 7395588  | 
| 1275554823  | Out of School Time           | 746694  | 2078489 | 2743582 | 3146500 | 3193698 | 3241603 | 3290227 | 2237519 | 20678312 | 
| 1275554823  | Middle & High School Youth   | 400108  | 1226297 | 1250318 | 1269073 | 1288109 | 1307430 | 1327042 | 902455  | 8970832  | 
| 1275554823  | Student Health Services      | 1230891 | 3779137 | 3846475 | 3904172 | 3962735 | 4022176 | 4082508 | 2776310 | 27604404 | 
| 1275554823  | Family Support               | 768071  | 2354559 | 2400680 | 2436690 | 2473241 | 2510339 | 2547994 | 1732763 | 17224337 | 
| 1275554823  | Family Involvement           | 161420  | 499206  | 503935  | 511494  | 519166  | 526954  | 534858  | 363730  | 3620763  | 
| 1275554823  | School Crossing Guards       | 513397  | 520165  | 529433  | 268687  |         |         |         |         | 1831682  | 
| 1275554823  | Levy Administration          | 165000  | 505541  | 515113  | 522839  | 530681  | 538641  | 546721  | 371798  | 3696334  | 
| 1275554823  | Evaluation                   | 65774   | 200000  | 200000  | 200000  | 200000  | 200000  | 200000  | 134000  | 1399774  | 
```