# Finance Entities

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/finance-entities-9bcc6) |
| Metadata | [Link](https://data.mo.gov/api/views/vfrr-8z5c) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/vfrr-8z5c/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/vfrr-8z5c/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | vfrr-8z5c |
| Name | Finance Entities |
| Attribution | Missouri Department of Insurance, Financial Institutions & Professional (DIFP) |
| Category | Regulatory |
| Tags | finance entities, finance |
| Created | 2013-11-07T22:37:17Z |
| Publication Date | 2017-04-19T19:42:17Z |

## Description

List of Missouri Finance Entities

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| No       | time           | :updated_at   | updated_at    | meta_data | meta_data   |
| Yes      | series tag     | description   | Description   | text      | text        |
| Yes      | series tag     | name          | NAME          | text      | text        |
| No       |                | address       | Address       | text      | text        |
| No       |                | address2      | Address2      | text      | text        |
| Yes      | series tag     | city          | City          | text      | text        |
| Yes      | series tag     | state         | State         | text      | text        |
| Yes      | series tag     | zipcode       | ZIPCode       | text      | text        |
| Yes      | numeric metric | phone         | Phone         | number    | text        |
| Yes      | series tag     | license       | License       | text      | text        |
| Yes      | numeric metric | assets        | Assets        | number    | text        |
| Yes      | series tag     | ceo           | CEO           | text      | text        |
| Yes      | series tag     | dba           | DBA           | text      | text        |
| Yes      | series tag     | agent         | Agent         | text      | text        |
| Yes      | series tag     | contact       | Contact       | text      | text        |
| Yes      | series tag     | expiration    | Expiration    | text      | text        |
| Yes      | series tag     | letter_issued | Letter Issued | text      | text        |
| Yes      | series tag     | branch_number | Branch Number | text      | text        |
| Yes      | series tag     | approval      | Approval      | text      | text        |
| Yes      | series tag     | type          | Type          | text      | text        |
| Yes      | series tag     | county        | County        | text      | text        |
| Yes      | series tag     | contact_email | Contact Email | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address,address2
```

## Data Commands

```ls
series e:vfrr-8z5c d:2017-04-19T19:41:56.000Z t:ceo="Charles R. Adamson, Chm/CEO" t:expiration=0/0/0000 t:description="Chartered Banks" t:name="1st Cameron State Bank" t:zipcode=64429 t:state=MO t:license=9343 t:type=CB t:city=Cameron m:assets=60689

series e:vfrr-8z5c d:2017-04-19T19:41:56.000Z t:ceo="David Charles Chinnery, Pres/CEO" t:expiration=0/0/0000 t:description="Chartered Banks" t:name="Adams Dairy Bank" t:zipcode=64014 t:state=MO t:license=2899 t:type=CB t:city="Blue Springs" m:assets=107778

series e:vfrr-8z5c d:2017-04-19T19:41:56.000Z t:ceo="Jack Wagner, Co-Chm/CEO" t:expiration=0/0/0000 t:description="Chartered Banks" t:name="Adrian Bank" t:zipcode=64720 t:state=MO t:license=2485 t:type=CB t:city=Adrian m:assets=139527
```

## Meta Commands

```ls
metric m:phone p:long l:Phone t:dataTypeName=number

metric m:assets p:integer l:Assets t:dataTypeName=number

entity e:vfrr-8z5c l:"Finance Entities" t:attribution="Missouri Department of Insurance, Financial Institutions & Professional (DIFP)" t:url=https://data.mo.gov/api/views/vfrr-8z5c

property e:vfrr-8z5c t:meta.view v:id=vfrr-8z5c v:category=Regulatory v:averageRating=0 v:name="Finance Entities" v:attribution="Missouri Department of Insurance, Financial Institutions & Professional (DIFP)"

property e:vfrr-8z5c t:meta.view.owner v:id=byu7-dn9b v:screenName=DIFP v:displayName=DIFP

property e:vfrr-8z5c t:meta.view.tableauthor v:id=byu7-dn9b v:screenName=DIFP v:roleName=editor v:displayName=DIFP
```

## Top Records

```ls
| :updated_at | description     | name                          | address                    | address2 | city         | state | zipcode | phone | license | assets | ceo                              | dba | agent | contact | expiration | letter_issued | branch_number | approval | type | county | contact_email | 
| =========== | =============== | ============================= | ========================== | ======== | ============ | ===== | ======= | ===== | ======= | ====== | ================================ | === | ===== | ======= | ========== | ============= | ============= | ======== | ==== | ====== | ============= | 
| 1492630916  | Chartered Banks | 1st Cameron State Bank        |                            |          | Cameron      | MO    | 64429   |       | 9343    | 60689  | Charles R. Adamson, Chm/CEO      |     |       |         | 0/0/0000   |               |               |          | CB   |        |               | 
| 1492630916  | Chartered Banks | Adams Dairy Bank              |                            |          | Blue Springs | MO    | 64014   |       | 2899    | 107778 | David Charles Chinnery, Pres/CEO |     |       |         | 0/0/0000   |               |               |          | CB   |        |               | 
| 1492630916  | Chartered Banks | Adrian Bank                   |                            |          | Adrian       | MO    | 64720   |       | 2485    | 139527 | Jack Wagner, Co-Chm/CEO          |     |       |         | 0/0/0000   |               |               |          | CB   |        |               | 
| 1492630916  | Chartered Banks | America's Community Bank      | 1100 West Main Street      |          | Blue Springs | MO    | 64015   |       | 468     | 29765  | I. Wesley Condron, Chm/CEO       |     |       |         | 0/0/0000   |               |               |          | CB   |        |               | 
| 1492630916  | Chartered Banks | Bank 21                       | One West Washington Street |          | Carrollton   | MO    | 64633   |       | 9298    | 106641 | Tyler A. Knott, Chairman/CEO     |     |       |         | 0/0/0000   |               |               |          | CB   |        |               | 
| 1492630916  | Chartered Banks | Bank Northwest                | 201 South Davis Street     |          | Hamilton     | MO    | 64644   |       | 2576    | 126668 | James L. Anderson, Pres/CEO      |     |       |         | 0/0/0000   |               |               |          | CB   |        |               | 
| 1492630916  | Chartered Banks | Bank of Odessa                | 301 West Highway 40        |          | Odessa       | MO    | 64076   |       | 1004    | 229081 | Dan Cobb, Chm/Pres/CEO           |     |       |         | 0/0/0000   |               |               |          | CB   |        |               | 
| 1492630916  | Chartered Banks | Bank of Weston                | 18255 Highway 45 North     |          | Weston       | MO    | 64098   |       | 1010    | 130616 | Theodore S. Wilson, Chm/CEO      |     |       |         | 0/0/0000   |               |               |          | CB   |        |               | 
| 1492630916  | Chartered Banks | BankLiberty                   |                            |          | Liberty      | MO    | 64068   |       | 2908    | 439172 | Brent M. Giles, Pres/CEO         |     |       |         | 0/0/0000   |               |               |          | CB   |        |               | 
| 1492630916  | Chartered Banks | Blue Ridge Bank and Trust Co. | 4200 Little Blue Parkway   |          | Independence | MO    | 64057   |       | 9290    | 510549 | William C. Esry, Pres/CEO        |     |       |         | 0/0/0000   |               |               |          | CB   |        |               | 
```