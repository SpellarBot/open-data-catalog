# Debt Service Coverage Ratio

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/debt-service-coverage) |
| Metadata | [Link](https://data.austintexas.gov/api/views/isev-msr7) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/isev-msr7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/isev-msr7/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | isev-msr7 |
| Name | Debt Service Coverage Ratio |
| Attribution | Austin Energy |
| Category | Utility |
| Tags | debt service, finance, austin energy, utilities, bond ratings, equity, debt |
| Created | 2016-09-19T17:23:30Z |
| Publication Date | 2017-04-18T15:32:13Z |

## Description

Debt Service Coverage Ratio is a measure of the cash flow available to pay current debt payments. View our debt-to-equity ratio, debt service coverage ratio, and more starting from fiscal year 2005. Go to http://austinenergy.com/go/corporatereports to learn more.

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                        | Data Type | Render Type |
| ======== | ============== | ========================= | =========================== | ========= | =========== |
| Yes      | time           | fiscal_year               | Fiscal Year                 | number    | number      |
| Yes      | numeric metric | debt_to_equity            | Debt-to-Capital Ratio       | percent   | percent     |
| Yes      | numeric metric | debt_service_coverage     | Debt Service Coverage Ratio | number    | number      |
| Yes      | numeric metric | revenue_bonds_millions    | Revenue Bonds               | number    | number      |
| Yes      | numeric metric | commercial_paper_millions | Commercial Paper            | number    | number      |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:isev-msr7 d:2005-01-01T00:00:00.000Z m:revenue_bonds_millions=1176510000 m:commercial_paper_millions=157480000 m:debt_service_coverage=2.39 m:debt_to_equity=51.3

series e:isev-msr7 d:2006-01-01T00:00:00.000Z m:revenue_bonds_millions=1260170000 m:commercial_paper_millions=54330000 m:debt_service_coverage=2.96 m:debt_to_equity=49.1

series e:isev-msr7 d:2007-01-01T00:00:00.000Z m:revenue_bonds_millions=1167300000 m:commercial_paper_millions=149940000 m:debt_service_coverage=2.32 m:debt_to_equity=47.6
```

## Meta Commands

```ls
metric m:debt_to_equity p:float l:"Debt-to-Capital Ratio" t:dataTypeName=percent

metric m:debt_service_coverage p:float l:"Debt Service Coverage Ratio" t:dataTypeName=number

metric m:revenue_bonds_millions p:integer l:"Revenue Bonds" t:dataTypeName=number

metric m:commercial_paper_millions p:integer l:"Commercial Paper" t:dataTypeName=number

entity e:isev-msr7 l:"Debt Service Coverage Ratio" t:attribution="Austin Energy" t:url=https://data.austintexas.gov/api/views/isev-msr7

property e:isev-msr7 t:meta.view v:id=isev-msr7 v:category=Utility v:averageRating=0 v:name="Debt Service Coverage Ratio" v:attribution="Austin Energy"

property e:isev-msr7 t:meta.view.license v:name="Public Domain"

property e:isev-msr7 t:meta.view.owner v:id=c433-zrb5 v:profileImageUrlMedium=/api/users/c433-zrb5/profile_images/THUMB v:profileImageUrlLarge=/api/users/c433-zrb5/profile_images/LARGE v:screenName="Sarah Lambert" v:profileImageUrlSmall=/api/users/c433-zrb5/profile_images/TINY v:displayName="Sarah Lambert"

property e:isev-msr7 t:meta.view.tableauthor v:id=c433-zrb5 v:profileImageUrlMedium=/api/users/c433-zrb5/profile_images/THUMB v:profileImageUrlLarge=/api/users/c433-zrb5/profile_images/LARGE v:screenName="Sarah Lambert" v:profileImageUrlSmall=/api/users/c433-zrb5/profile_images/TINY v:roleName=publisher v:displayName="Sarah Lambert"
```

## Top Records

```ls
| fiscal_year | debt_to_equity | debt_service_coverage | revenue_bonds_millions | commercial_paper_millions | 
| =========== | ============== | ===================== | ====================== | ========================= | 
| 2005        | 51.30          | 2.39                  | 1176510000             | 157480000                 | 
| 2006        | 49.10          | 2.96                  | 1260170000             | 54330000                  | 
| 2007        | 47.60          | 2.32                  | 1167300000             | 149940000                 | 
| 2008        | 47.80          | 2.93                  | 1308140000             | 35150000                  | 
| 2009        | 48.10          | 1.91                  | 1236140000             | 140710000                 | 
| 2010        | 48.60          | 1.77                  | 1326280000             | 85150000                  | 
| 2011        | 47.60          | 2.04                  | 1256100000             | 152580000                 | 
| 2012        | 48.20          | 2.01                  | 1185690000             | 225260000                 | 
| 2013        | 47.00          | 2.09                  | 1309729000             | 88541000                  | 
| 2014        | 46.00          | 2.42                  | 1252386000             | 166456000                 | 
```