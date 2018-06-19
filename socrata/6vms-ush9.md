# IDHR Eligible Public Contract Numbers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idhr-eligible-public-contract-numbers-d95c5) |
| Metadata | [Link](https://data.illinois.gov/api/views/6vms-ush9) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/6vms-ush9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/6vms-ush9/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 6vms-ush9 |
| Name | IDHR Eligible Public Contract Numbers |
| Created | 2012-03-13T21:09:59Z |
| Publication Date | 2017-03-28T16:03:27Z |

## Description

Eligible IDHR Public Contract Numbers as of March 27, 2017. For further information contact IDHR at IDHR.PublicContracts@illinois.gov or 312-814-2431.

## Columns

```ls
| Included | Schema Type | Field Name         | Name                | Data Type | Render Type |
| ======== | =========== | ================== | =================== | ========= | =========== |
| Yes      | series tag  | public_contract_no | Public Contract No. | text      | text        |
| Yes      | series tag  | name               | Name                | text      | text        |
| Yes      | series tag  | city               | City                | text      | text        |
| Yes      | series tag  | state              | State               | text      | text        |
| Yes      | series tag  | zip_code           | Zip Code            | text      | text        |
| Yes      | time        | expiration_date    | Expiration Date     | text      | text        |
```

## Time Field

```ls
Value = expiration_date
Format & Zone = MM/dd/yy
```

## Data Commands

```ls
series e:6vms-ush9 d:2020-11-16T00:00:00.000Z t:zip_code=62708 t:name="THEATRICAL SERVICES INC." t:state=IL t:public_contract_no=9000600 t:city=SPRINGFIELD m:row_number.6vms-ush9=1

series e:6vms-ush9 d:2021-10-31T00:00:00.000Z t:zip_code=53076 t:name="RITEWAY BUS SERVICE, INC." t:state=WI t:public_contract_no=9001000 t:city=RICHFIELD m:row_number.6vms-ush9=2

series e:6vms-ush9 d:2018-02-14T00:00:00.000Z t:zip_code=94558 t:name=WALKENHORST'S t:state=CA t:public_contract_no=9002800 t:city=NAPA m:row_number.6vms-ush9=3
```

## Meta Commands

```ls
metric m:row_number.6vms-ush9 p:long l:"Row Number"

entity e:6vms-ush9 l:"IDHR Eligible Public Contract Numbers" t:url=https://data.illinois.gov/api/views/6vms-ush9

property e:6vms-ush9 t:meta.view v:id=6vms-ush9 v:averageRating=0 v:name="IDHR Eligible Public Contract Numbers"

property e:6vms-ush9 t:meta.view.license v:name="Public Domain"

property e:6vms-ush9 t:meta.view.owner v:id=puxq-5aqd v:screenName="Burley Howard" v:displayName="Burley Howard"

property e:6vms-ush9 t:meta.view.tableauthor v:id=puxq-5aqd v:screenName="Burley Howard" v:roleName=publisher v:displayName="Burley Howard"
```

## Top Records

```ls
| public_contract_no | name                                  | city        | state | zip_code | expiration_date | 
| ================== | ===================================== | =========== | ===== | ======== | =============== | 
| 9000600            | THEATRICAL SERVICES INC.              | SPRINGFIELD | IL    | 62708    | 11/16/20        | 
| 9001000            | RITEWAY BUS SERVICE, INC.             | RICHFIELD   | WI    | 53076    | 10/31/21        | 
| 9002800            | WALKENHORST'S                         | NAPA        | CA    | 94558    | 2/14/18         | 
| 9002900            | PRESCRIPTION SUPPLY, INC.             | NORTHWOOD   | OH    | 43619    | 9/14/20         | 
| 9003901            | WACH SECURITIES                       | RICH        | VA    | 23219    | 4/17/19         | 
| 9005800            | JL WAGNER PLUMBING & PIPING, INC.     | ST. CHARLES | IL    | 60174    | 5/6/19          | 
| 9012000            | MANEVAL CONSTRUCTION                  | GRAYSLAKE   | IL    | 60030    | 1/8/18          | 
| 9013900            | APPLIED INDUSTRIAL TECHNOLOGIES, INC. | CLEVELAND   | OH    | 44115    | 5/8/18          | 
| 9016700            | EARTHWISE ENVIRONMENTAL, INC.         | WOOD DALE   | IL    | 60191    | 8/5/21          | 
| 9020300            | ERA VALDIVIA CONTRACTORS INC.         | CHICAGO     | IL    | 60617    | 4/23/18         | 
```