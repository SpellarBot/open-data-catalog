# DCEO CPI Index

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dceo-cpi-index-fe29a) |
| Metadata | [Link](https://data.illinois.gov/api/views/6uaz-c8vs) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/6uaz-c8vs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/6uaz-c8vs/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 6uaz-c8vs |
| Name | DCEO CPI Index |
| Category | Economics |
| Tags | dceo, price index, consumer |
| Created | 2012-01-13T20:10:20Z |
| Publication Date | 2012-01-13T20:14:31Z |

## Description

Consumer Price Index - All Urban Consumers

## Columns

```ls
| Included | Schema Type    | Field Name | Name   | Data Type | Render Type |
| ======== | ============== | ========== | ====== | ========= | =========== |
| Yes      | time           | year       | Year   | number    | text        |
| Yes      | numeric metric | jan        | Jan    | number    | number      |
| Yes      | numeric metric | feb        | Feb    | number    | number      |
| Yes      | numeric metric | mar        | Mar    | number    | number      |
| Yes      | numeric metric | apr        | Apr    | number    | number      |
| Yes      | numeric metric | may        | May    | number    | number      |
| Yes      | numeric metric | jun        | Jun    | number    | number      |
| Yes      | numeric metric | jul        | Jul    | number    | number      |
| Yes      | numeric metric | aug        | Aug    | number    | number      |
| Yes      | numeric metric | sep        | Sep    | number    | number      |
| Yes      | numeric metric | oct        | Oct    | number    | number      |
| Yes      | numeric metric | nov        | Nov    | number    | number      |
| Yes      | numeric metric | dec        | Dec    | number    | number      |
| Yes      | numeric metric | annual     | Annual | number    | number      |
| Yes      | numeric metric | half1      | HALF1  | number    | number      |
| Yes      | numeric metric | half2      | HALF2  | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:6uaz-c8vs d:2001-01-01T00:00:00.000Z m:may=179.8 m:half2=178.2 m:apr=178.4 m:annual=178.3 m:half1=178.5 m:jul=177.7 m:jun=179.2 m:oct=178.1 m:dec=177.9 m:feb=178.5 m:nov=177.4 m:sep=179.7 m:mar=177.1 m:jan=178.1 m:aug=178.1

series e:6uaz-c8vs d:2002-01-01T00:00:00.000Z m:may=181.4 m:half2=182.2 m:apr=180.9 m:annual=181.2 m:half1=180.1 m:jul=181.2 m:jun=182.1 m:oct=182.8 m:dec=182.4 m:feb=178.7 m:nov=183.2 m:sep=182.1 m:mar=179.8 m:jan=177.9 m:aug=181.6

series e:6uaz-c8vs d:2003-01-01T00:00:00.000Z m:may=183.4 m:half2=185.3 m:apr=183.4 m:annual=184.5 m:half1=183.8 m:jul=184.1 m:jun=184.1 m:oct=185.8 m:dec=185.5 m:feb=184.1 m:nov=185.6 m:sep=186.1 m:mar=184.8 m:jan=182.7 m:aug=184.5
```

## Meta Commands

```ls
metric m:jan p:float l:Jan t:dataTypeName=number

metric m:feb p:float l:Feb t:dataTypeName=number

metric m:mar p:float l:Mar t:dataTypeName=number

metric m:apr p:float l:Apr t:dataTypeName=number

metric m:may p:float l:May t:dataTypeName=number

metric m:jun p:float l:Jun t:dataTypeName=number

metric m:jul p:float l:Jul t:dataTypeName=number

metric m:aug p:float l:Aug t:dataTypeName=number

metric m:sep p:float l:Sep t:dataTypeName=number

metric m:oct p:float l:Oct t:dataTypeName=number

metric m:nov p:float l:Nov t:dataTypeName=number

metric m:dec p:float l:Dec t:dataTypeName=number

metric m:annual p:float l:Annual t:dataTypeName=number

metric m:half1 p:float l:HALF1 t:dataTypeName=number

metric m:half2 p:float l:HALF2 t:dataTypeName=number

entity e:6uaz-c8vs l:"DCEO CPI Index" t:url=https://data.illinois.gov/api/views/6uaz-c8vs

property e:6uaz-c8vs t:meta.view v:id=6uaz-c8vs v:category=Economics v:averageRating=0 v:name="DCEO CPI Index"

property e:6uaz-c8vs t:meta.view.owner v:id=t6h9-hze3 v:screenName=Nicole v:displayName=Nicole

property e:6uaz-c8vs t:meta.view.tableauthor v:id=t6h9-hze3 v:screenName=Nicole v:roleName=publisher v:displayName=Nicole
```

## Top Records

```ls
| year | jan     | feb     | mar     | apr     | may     | jun     | jul     | aug     | sep     | oct     | nov     | dec     | annual  | half1   | half2   | 
| ==== | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | 
| 2001 | 178.1   | 178.5   | 177.1   | 178.4   | 179.8   | 179.2   | 177.7   | 178.1   | 179.7   | 178.1   | 177.4   | 177.9   | 178.3   | 178.5   | 178.2   | 
| 2002 | 177.9   | 178.7   | 179.8   | 180.9   | 181.4   | 182.1   | 181.2   | 181.6   | 182.1   | 182.8   | 183.2   | 182.4   | 181.2   | 180.1   | 182.2   | 
| 2003 | 182.7   | 184.1   | 184.8   | 183.4   | 183.4   | 184.1   | 184.1   | 184.5   | 186.1   | 185.8   | 185.6   | 185.5   | 184.5   | 183.8   | 185.3   | 
| 2004 | 185.4   | 186.4   | 186.3   | 187.2   | 188.7   | 189.1   | 189.2   | 190.2   | 190.0   | 190.8   | 190.7   | 189.6   | 188.6   | 187.2   | 190.1   | 
| 2005 | 189.9   | 190.5   | 191.3   | 193.2   | 193.3   | 194.0   | 194.2   | 195.8   | 198.3   | 197.9   | 197.3   | 196.4   | 194.3   | 192.0   | 196.7   | 
| 2006 | 197.5   | 197.2   | 197.6   | 197.7   | 198.4   | 199.0   | 199.3   | 200.4   | 199.6   | 197.5   | 197.9   | 197.8   | 198.3   | 197.9   | 198.8   | 
| 2007 | 199.401 | 200.630 | 202.483 | 204.019 | 205.686 | 206.092 | 205.561 | 205.813 | 206.454 | 206.696 | 207.821 | 207.155 | 204.818 | 203.052 | 206.583 | 
| 2008 | 208.757 | 209.526 | 211.542 | 212.662 | 214.932 | 215.738 | 217.459 | 215.971 | 215.465 | 213.363 | 209.053 | 205.959 | 212.536 | 212.193 | 212.878 | 
| 2009 | 207.616 | 207.367 | 207.462 | 207.886 | 209.809 | 211.010 | 210.906 | 211.441 | 211.345 | 211.708 | 212.206 | 211.185 | 209.995 | 208.525 | 211.465 | 
| 2010 | 212.104 | 212.456 | 212.952 | 212.929 | 212.984 | 212.186 | 212.535 | 212.784 | 213.339 | 213.332 | 213.066 | 213.778 | 212.870 | 212.602 | 213.139 | 
```