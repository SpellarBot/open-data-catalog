# Table 3.14 HAWAII STATE HIGH SCHOOL GRADUATES BY PUBLIC AND PRIVATE HIGH SCHOOL 1982 TO 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/table-3-14-hawaii-state-high-school-graduates-by-public-and-private-high-school-1982-to-20-5289b) |
| Metadata | [Link](https://data.hawaii.gov/api/views/bvnw-4za7) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/bvnw-4za7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/bvnw-4za7/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | bvnw-4za7 |
| Name | Table 3.14 HAWAII STATE HIGH SCHOOL GRADUATES BY PUBLIC AND PRIVATE HIGH SCHOOL 1982 TO 2014 |
| Attribution | Department of Economic Development and Tourism |
| Category | Economic Development |
| Tags | high school, graduates, public, private |
| Created | 2012-08-27T20:06:23Z |
| Publication Date | 2015-10-27T00:18:29Z |

## Description

Source: University of Hawai'i, Institutional Research and Analysis Office, records.

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type | Render Type |
| ======== | ============== | ======================== | ======================== | ========= | =========== |
| Yes      | time           | year                     | Year                     | number    | number      |
| Yes      | numeric metric | total_graduates          | Total graduates          | number    | number      |
| Yes      | numeric metric | public_school_graduates  | Public school graduates  | number    | number      |
| Yes      | numeric metric | private_school_graduates | Private school graduates | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:bvnw-4za7 d:1982-01-01T00:00:00.000Z m:total_graduates=13999 m:public_school_graduates=11563 m:private_school_graduates=2436

series e:bvnw-4za7 d:1983-01-01T00:00:00.000Z m:total_graduates=13301 m:public_school_graduates=10757 m:private_school_graduates=2544

series e:bvnw-4za7 d:1984-01-01T00:00:00.000Z m:total_graduates=13041 m:public_school_graduates=10454 m:private_school_graduates=2587
```

## Meta Commands

```ls
metric m:total_graduates p:integer l:"Total graduates" t:dataTypeName=number

metric m:public_school_graduates p:integer l:"Public school graduates" t:dataTypeName=number

metric m:private_school_graduates p:integer l:"Private school graduates" t:dataTypeName=number

entity e:bvnw-4za7 l:"Table 3.14 HAWAII STATE HIGH SCHOOL GRADUATES BY PUBLIC AND PRIVATE HIGH SCHOOL 1982 TO 2014" t:attribution="Department of Economic Development and Tourism" t:url=https://data.hawaii.gov/api/views/bvnw-4za7

property e:bvnw-4za7 t:meta.view v:id=bvnw-4za7 v:category="Economic Development" v:attributionLink=http://hawaii.gov/dbedt/databook v:averageRating=0 v:name="Table 3.14 HAWAII STATE HIGH SCHOOL GRADUATES BY PUBLIC AND PRIVATE HIGH SCHOOL 1982 TO 2014" v:attribution="Department of Economic Development and Tourism"

property e:bvnw-4za7 t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:bvnw-4za7 t:meta.view.owner v:id=6k8y-ahyw v:screenName="Yang-Seon Kim" v:displayName="Yang-Seon Kim"

property e:bvnw-4za7 t:meta.view.tableauthor v:id=6k8y-ahyw v:screenName="Yang-Seon Kim" v:roleName=editor v:displayName="Yang-Seon Kim"
```

## Top Records

```ls
| year | total_graduates | public_school_graduates | private_school_graduates | 
| ==== | =============== | ======================= | ======================== | 
| 1982 | 13999           | 11563                   | 2436                     | 
| 1983 | 13301           | 10757                   | 2544                     | 
| 1984 | 13041           | 10454                   | 2587                     | 
| 1985 | 12575           | 10092                   | 2483                     | 
| 1986 | 12511           | 9958                    | 2553                     | 
| 1987 | 13146           | 10491                   | 2655                     | 
| 1988 | 13449           | 10751                   | 2698                     | 
| 1989 | 13094           | 10551                   | 2543                     | 
| 1990 | 12278           | 9848                    | 2430                     | 
| 1991 | 11877           | 9482                    | 2395                     | 
```