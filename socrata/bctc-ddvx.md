# Maryland WIC Average State Fiscal Year Participation, 2007-2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-wic-average-state-fiscal-year-participation-2007-2012-09011) |
| Metadata | [Link](https://data.maryland.gov/api/views/bctc-ddvx) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/bctc-ddvx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/bctc-ddvx/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | bctc-ddvx |
| Name | Maryland WIC Average State Fiscal Year Participation, 2007-2012 |
| Attribution | Maryland WIC Program, Maternal and Child Health Bureau, Prevention and Health Promotion Administration. |
| Category | Health and Human Services |
| Tags | wic, women, infants, children, supplemental food |
| Created | 2013-01-04T18:22:07Z |
| Publication Date | 2013-01-04T18:34:33Z |

## Description

Data is by state fiscal year (SFY) which runs from July 1 - June 30.  Baltimore City includes Baltimore City Health Department, Johns Hopkins, and University WIC participation numbers for 2007-2009.  2009-2012 Includes BCHD and JH participation.  Montgomery is run by Community Clinic Inc, and includes participants from CCI's Greenbelt clinic.  Prince George's includes Prince George's Health Department and Greater Baden participation numbers.

## Columns

```ls
| Included | Schema Type    | Field Name | Name     | Data Type | Render Type |
| ======== | ============== | ========== | ======== | ========= | =========== |
| Yes      | series tag     | county     | COUNTY   | text      | text        |
| Yes      | numeric metric | sfy_2007   | SFY 2007 | number    | number      |
| Yes      | numeric metric | sfy_2008   | SFY 2008 | number    | number      |
| Yes      | numeric metric | sfy_2009   | SFY 2009 | number    | number      |
| Yes      | numeric metric | sfy_2010   | SFY 2010 | number    | number      |
| Yes      | numeric metric | sfy_2011   | SFY 2011 | number    | number      |
| Yes      | numeric metric | sfy_2012   | SFY 2012 | number    | number      |
```

## Time Field

```ls
Value = 2007
Format & Zone = yyyy
```

## Data Commands

```ls
series e:bctc-ddvx d:2007-01-01T00:00:00.000Z t:county=ALLEGANY m:sfy_2009=2217 m:sfy_2010=2171 m:sfy_2011=2076 m:sfy_2012=2024 m:sfy_2007=1946 m:sfy_2008=2032

series e:bctc-ddvx d:2007-01-01T00:00:00.000Z t:county="ANNE ARUNDEL" m:sfy_2009=7871 m:sfy_2010=8345 m:sfy_2011=9136 m:sfy_2012=8788 m:sfy_2007=6343 m:sfy_2008=6868

series e:bctc-ddvx d:2007-01-01T00:00:00.000Z t:county="BALTIMORE CITY" m:sfy_2009=29371 m:sfy_2010=28982 m:sfy_2011=28831 m:sfy_2012=28778 m:sfy_2007=26737 m:sfy_2008=29186
```

## Meta Commands

```ls
metric m:sfy_2007 p:integer l:"SFY 2007" t:dataTypeName=number

metric m:sfy_2008 p:integer l:"SFY 2008" t:dataTypeName=number

metric m:sfy_2009 p:integer l:"SFY 2009" t:dataTypeName=number

metric m:sfy_2010 p:integer l:"SFY 2010" t:dataTypeName=number

metric m:sfy_2011 p:integer l:"SFY 2011" t:dataTypeName=number

metric m:sfy_2012 p:integer l:"SFY 2012" t:dataTypeName=number

entity e:bctc-ddvx l:"Maryland WIC Average State Fiscal Year Participation, 2007-2012" t:attribution="Maryland WIC Program, Maternal and Child Health Bureau, Prevention and Health Promotion Administration." t:url=https://data.maryland.gov/api/views/bctc-ddvx

property e:bctc-ddvx t:meta.view v:id=bctc-ddvx v:category="Health and Human Services" v:attributionLink=http://www.mdwic.org v:averageRating=0 v:name="Maryland WIC Average State Fiscal Year Participation, 2007-2012" v:attribution="Maryland WIC Program, Maternal and Child Health Bureau, Prevention and Health Promotion Administration."

property e:bctc-ddvx t:meta.view.owner v:id=e5tx-wz6d v:screenName="Andrea Bankoski" v:displayName="Andrea Bankoski"

property e:bctc-ddvx t:meta.view.tableauthor v:id=e5tx-wz6d v:screenName="Andrea Bankoski" v:roleName=editor v:displayName="Andrea Bankoski"
```

## Top Records

```ls
| county           | sfy_2007 | sfy_2008 | sfy_2009 | sfy_2010 | sfy_2011 | sfy_2012 | 
| ================ | ======== | ======== | ======== | ======== | ======== | ======== | 
| ALLEGANY         | 1946     | 2032     | 2217     | 2171     | 2076     | 2024     | 
| ANNE ARUNDEL     | 6343     | 6868     | 7871     | 8345     | 9136     | 8788     | 
| BALTIMORE CITY   | 26737    | 29186    | 29371    | 28982    | 28831    | 28778    | 
| BALTIMORE COUNTY | 12964    | 13989    | 15648    | 16339    | 16212    | 16160    | 
| CALVERT          | 986      | 1068     | 1218     | 1268     | 1186     | 1204     | 
| CAROLINE         | 1221     | 1314     | 1386     | 1415     | 1351     | 1312     | 
| CARROLL          | 1481     | 1634     | 1796     | 1774     | 1823     | 1934     | 
| CECIL            | 2036     | 2218     | 2326     | 2281     | 2136     | 2169     | 
| CHARLES          | 2398     | 2624     | 2798     | 2771     | 2884     | 3063     | 
| DORCHESTER       | 949      | 1074     | 1188     | 1175     | 1097     | 1098     | 
```