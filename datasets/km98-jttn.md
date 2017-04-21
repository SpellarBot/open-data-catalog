# IDPH Births to Teen Mothers, by County, 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idph-births-to-teen-mothers-by-county-2009-9f720) |
| Metadata | [Link](https://data.illinois.gov/api/views/km98-jttn) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/km98-jttn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/km98-jttn/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | km98-jttn |
| Name | IDPH Births to Teen Mothers, by County, 2009 |
| Attribution | Illinois Center for Health Statistics |
| Category | Public Health |
| Tags | teen, birth |
| Created | 2012-01-18T21:49:20Z |
| Publication Date | 2012-01-23T21:25:32Z |

## Description

* City of Chicago totals may include births occurring to residents of the city of Chicago in DuPage County and appear also in the DuPage County birth numbers.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name               | Data Type | Render Type |
| ======== | ============== | ================= | ================== | ========= | =========== |
| Yes      | series tag     | county            | County             | text      | text        |
| Yes      | numeric metric | births_2008       | Births, 2008       | number    | number      |
| Yes      | numeric metric | teens_2008        | Teens, 2008        | number    | number      |
| Yes      | numeric metric | under_15_2008_    | Under 15, 2008     | number    | number      |
| No       |                | _1                | 15-17, 2008        | number    | number      |
| No       |                | _2                | 18-19, 2008        | number    | number      |
| Yes      | numeric metric | teen_percent_2008 | Teen Percent, 2008 | number    | number      |
| Yes      | numeric metric | births_2009       | Births, 2009       | number    | number      |
| Yes      | numeric metric | teens_2009        | Teens, 2009        | number    | number      |
| Yes      | numeric metric | under_15_2009_    | Under 15, 2009     | number    | number      |
| No       |                | _3                | 15-17, 2009        | number    | number      |
| No       |                | _4                | 18-19, 2009        | number    | number      |
| Yes      | numeric metric | teen_percent_2009 | Teen Percent, 2009 | number    | number      |
```

## Time Field

```ls
Value = 2009
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = _1,_2,_3,_4
```

## Data Commands

```ls
series e:km98-jttn d:2009-01-01T00:00:00.000Z t:county=Adams m:teen_percent_2008=10.2 m:teen_percent_2009=11.1 m:under_15_2008_=0 m:births_2008=817 m:teens_2009=89 m:under_15_2009_=1 m:births_2009=804 m:teens_2008=83

series e:km98-jttn d:2009-01-01T00:00:00.000Z t:county=Alexander m:teen_percent_2008=26.7 m:teen_percent_2009=21.9 m:under_15_2008_=0 m:births_2008=120 m:teens_2009=25 m:under_15_2009_=0 m:births_2009=114 m:teens_2008=32

series e:km98-jttn d:2009-01-01T00:00:00.000Z t:county=Bond m:teen_percent_2008=11.6 m:teen_percent_2009=10.6 m:under_15_2008_=0 m:births_2008=173 m:teens_2009=21 m:under_15_2009_=2 m:births_2009=198 m:teens_2008=20
```

## Meta Commands

```ls
metric m:births_2008 p:integer l:"Births, 2008" t:dataTypeName=number

metric m:teens_2008 p:integer l:"Teens, 2008" t:dataTypeName=number

metric m:under_15_2008_ p:integer l:"Under 15, 2008" t:dataTypeName=number

metric m:teen_percent_2008 p:float l:"Teen Percent, 2008" t:dataTypeName=number

metric m:births_2009 p:integer l:"Births, 2009" t:dataTypeName=number

metric m:teens_2009 p:integer l:"Teens, 2009" t:dataTypeName=number

metric m:under_15_2009_ p:integer l:"Under 15, 2009" t:dataTypeName=number

metric m:teen_percent_2009 p:float l:"Teen Percent, 2009" t:dataTypeName=number

entity e:km98-jttn l:"IDPH Births to Teen Mothers, by County, 2009" t:attribution="Illinois Center for Health Statistics" t:url=https://data.illinois.gov/api/views/km98-jttn

property e:km98-jttn t:meta.view v:id=km98-jttn v:category="Public Health" v:attributionLink=http://www.idph.state.il.us/health/statshome.htm v:averageRating=0 v:name="IDPH Births to Teen Mothers, by County, 2009" v:attribution="Illinois Center for Health Statistics"

property e:km98-jttn t:meta.view.owner v:id=e75b-y6hv v:screenName=Jenny v:displayName=Jenny

property e:km98-jttn t:meta.view.tableauthor v:id=ws2v-m6rq v:screenName="jonathan nuttall" v:displayName="jonathan nuttall"
```

## Top Records

```ls
| county    | births_2008 | teens_2008 | under_15_2008_ | _1 | _2  | teen_percent_2008 | births_2009 | teens_2009 | under_15_2009_ | _3 | _4  | teen_percent_2009 | 
| ========= | =========== | ========== | ============== | == | === | ================= | =========== | ========== | ============== | == | === | ================= | 
| Adams     | 817         | 83         | 0              | 24 | 59  | 10.2              | 804         | 89         | 1              | 21 | 67  | 11.1              | 
| Alexander | 120         | 32         | 0              | 11 | 21  | 26.7              | 114         | 25         | 0              | 5  | 20  | 21.9              | 
| Bond      | 173         | 20         | 0              | 4  | 16  | 11.6              | 198         | 21         | 2              | 3  | 16  | 10.6              | 
| Boone     | 676         | 74         | 0              | 24 | 50  | 10.9              | 622         | 57         | 1              | 11 | 45  | 9.2               | 
| Brown     | 64          | 3          | 0              | 1  | 2   | 4.7               | 65          | 4          | 0              | 2  | 2   | 6.2               | 
| Bureau    | 409         | 30         | 0              | 9  | 21  | 7.3               | 381         | 40         | 0              | 11 | 29  | 10.5              | 
| Calhoun   | 59          | 2          | 0              | 0  | 2   | 3.4               | 53          | 6          | 0              | 3  | 3   | 11.3              | 
| Carroll   | 142         | 15         | 0              | 5  | 10  | 10.6              | 123         | 10         | 0              | 2  | 8   | 8.1               | 
| Cass      | 200         | 27         | 0              | 7  | 20  | 13.5              | 164         | 19         | 1              | 8  | 10  | 11.6              | 
| Champaign | 2482        | 244        | 4              | 74 | 166 | 9.8               | 2407        | 204        | 2              | 66 | 136 | 8.5               | 
```