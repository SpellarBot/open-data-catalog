# MMP Loans Purchased By County FY 13

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/mmp-loans-purchased-by-county-fy-13-285ae) |
| Metadata | [Link](https://data.maryland.gov/api/views/rvup-j2d5) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/rvup-j2d5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/rvup-j2d5/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | rvup-j2d5 |
| Name | MMP Loans Purchased By County FY 13 |
| Created | 2014-05-07T22:44:59Z |
| Publication Date | 2014-05-07T22:49:47Z |

## Description

Maryland Mortgage Program (MMP), a program offered by the Community Development Administration (CDA), a part of the Maryland Department of Housing and Community Development (DHCD) provides home loans and down payment assistance to Maryland families, encouraging homeownership and community growth. In partnership with commercial lenders, MMP offers competitive loans with the added benefit of down payment and closing cost assistance in the form of zero percent deferred loans that can be used in conjunction with funding from other sources (e. g. partnership program organizations). For more information on how to apply, please visit mmp.maryland.gov.

## Columns

```ls
| Included | Schema Type    | Field Name   | Name           | Data Type | Render Type |
| ======== | ============== | ============ | ============== | ========= | =========== |
| No       | time           | :updated_at  | updated_at     | meta_data | meta_data   |
| Yes      | series tag     | county       | County         | text      | text        |
| Yes      | numeric metric | of_purchases | # of Purchases | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:rvup-j2d5 d:2014-05-07T15:45:02.000Z t:county=Allegheny m:of_purchases=9

series e:rvup-j2d5 d:2014-05-07T15:45:02.000Z t:county="Anne Arundel" m:of_purchases=145

series e:rvup-j2d5 d:2014-05-07T15:45:02.000Z t:county="Baltimore City" m:of_purchases=302
```

## Meta Commands

```ls
metric m:of_purchases p:integer l:"# of Purchases" t:dataTypeName=number

entity e:rvup-j2d5 l:"MMP Loans Purchased By County FY 13" t:url=https://data.maryland.gov/api/views/rvup-j2d5

property e:rvup-j2d5 t:meta.view v:id=rvup-j2d5 v:averageRating=0 v:name="MMP Loans Purchased By County FY 13"

property e:rvup-j2d5 t:meta.view.owner v:id=ixd6-5kyc v:screenName="Locke, Patrice" v:displayName="Locke, Patrice"

property e:rvup-j2d5 t:meta.view.tableauthor v:id=ixd6-5kyc v:screenName="Locke, Patrice" v:roleName=editor v:displayName="Locke, Patrice"
```

## Top Records

```ls
| :updated_at | county         | of_purchases | 
| =========== | ============== | ============ | 
| 1399477502  | County         |              | 
| 1399477502  | Allegheny      | 9            | 
| 1399477502  | Anne Arundel   | 145          | 
| 1399477502  | Baltimore City | 302          | 
| 1399477502  | Baltimore      | 241          | 
| 1399477502  | Calvert        | 7            | 
| 1399477502  | Caroline       | 4            | 
| 1399477502  | Carroll        | 21           | 
| 1399477502  | Cecil          | 14           | 
| 1399477502  | Charles        | 105          | 
```