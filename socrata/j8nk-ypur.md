# IDES - UI Claims & Payments 2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ides-ui-claims-payments-2011-3a62b) |
| Metadata | [Link](https://data.illinois.gov/api/views/j8nk-ypur) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/j8nk-ypur/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/j8nk-ypur/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | j8nk-ypur |
| Name | IDES - UI Claims & Payments 2011 |
| Attribution | IDES - Economic Information and Analysis Division |
| Category | Economics |
| Tags | ui, claims, payments |
| Created | 2012-04-12T15:42:54Z |
| Publication Date | 2012-04-12T15:49:07Z |

## Description

Unemployment Insurance Regular Program Claims and Payments for 2011.

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| Yes      | series tag     | activity      | Activity      | text      | text        |
| Yes      | numeric metric | total_cy2011  | Total_CY2011  | money     | money       |
| Yes      | numeric metric | total_cy2010  | Total_CY2010  | money     | money       |
| Yes      | numeric metric | netchange     | NetChange     | money     | money       |
| Yes      | numeric metric | percentchange | PercentChange | percent   | percent     |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Data Commands

```ls
series e:j8nk-ypur d:2011-01-01T00:00:00.000Z t:activity="Insured Unemployment Weekly Average" m:total_cy2011=182445 m:total_cy2010=220556 m:netchange=-38111 m:percentchange=-17

series e:j8nk-ypur d:2011-01-01T00:00:00.000Z t:activity="First Payments to New Beneficiaries" m:total_cy2011=418422 m:total_cy2010=475822 m:netchange=-57400 m:percentchange=-12

series e:j8nk-ypur d:2011-01-01T00:00:00.000Z t:activity="Final Payments to Exhaustees" m:total_cy2011=205376 m:total_cy2010=286400 m:netchange=-81024 m:percentchange=-28
```

## Meta Commands

```ls
metric m:total_cy2011 p:double l:Total_CY2011 t:dataTypeName=money

metric m:total_cy2010 p:double l:Total_CY2010 t:dataTypeName=money

metric m:netchange p:double l:NetChange t:dataTypeName=money

metric m:percentchange p:integer l:PercentChange t:dataTypeName=percent

entity e:j8nk-ypur l:"IDES - UI Claims & Payments 2011" t:attribution="IDES - Economic Information and Analysis Division" t:url=https://data.illinois.gov/api/views/j8nk-ypur

property e:j8nk-ypur t:meta.view v:id=j8nk-ypur v:category=Economics v:attributionLink="http://www.ides.illinois.gov/page.aspx?item=917" v:averageRating=0 v:name="IDES - UI Claims & Payments 2011" v:attribution="IDES - Economic Information and Analysis Division"

property e:j8nk-ypur t:meta.view.owner v:id=6i42-mskp v:screenName="David Egan" v:displayName="David Egan"

property e:j8nk-ypur t:meta.view.tableauthor v:id=6i42-mskp v:screenName="David Egan" v:displayName="David Egan"
```

## Top Records

```ls
| activity                             | total_cy2011 | total_cy2010 | netchange  | percentchange | 
| ==================================== | ============ | ============ | ========== | ============= | 
| Insured Unemployment Weekly Average  | 182445       | 220556       | -38111     | -17           | 
| First Payments to New Beneficiaries  | 418422       | 475822       | -57400     | -12           | 
| Final Payments to Exhaustees         | 205376       | 286400       | -81024     | -28           | 
| Total Claims                         | 763319       | 863328       | -100009    | -12           | 
| New Claims                           | 445462       | 476941       | -31479     | -7            | 
| Additional Claims                    | 301636       | 369701       | -68065     | -18           | 
| Interstate Agent Claims              | 16221        | 16686        | -465       | -3            | 
| Weeks Claimed (including interstate) | 9487153      | 11468944     | -1981791   | -17           | 
| Weeks Compensated                    | 7953402      | 10156789     | -2203387   | -22           | 
| Gross Benefits Paid                  | 2442919397   | 3193064887   | -750145490 | -23           | 
```