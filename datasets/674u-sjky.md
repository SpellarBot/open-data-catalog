# New York State Budget Vetoes: 2013-14

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/new-york-state-budget-vetoes-2013-14) |
| Metadata | [Link](https://data.ny.gov/api/views/674u-sjky) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/674u-sjky/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/674u-sjky/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 674u-sjky |
| Name | New York State Budget Vetoes: 2013-14 |
| Attribution | Division of the Budget |
| Category | Government & Finance |
| Tags | enacted budget, budget, vetoes, veto, integrity |
| Created | 2013-04-16T20:58:24Z |
| Publication Date | 2016-05-12T20:49:08Z |

## Description

This data set includes vetoed reappropriation items from the 2013-14 enacted budget bills by veto number, agency, bill, fund type and justification.

## Columns

```ls
| Included | Schema Type    | Field Name                                             | Name                                                     | Data Type | Render Type |
| ======== | ============== | ====================================================== | ======================================================== | ========= | =========== |
| Yes      | series tag     | veto_number                                            | Veto Number                                              | text      | number      |
| Yes      | series tag     | agency                                                 | Agency                                                   | text      | text        |
| Yes      | series tag     | bill                                                   | Bill                                                     | text      | text        |
| Yes      | numeric metric | page_from                                              | Page From                                                | number    | number      |
| Yes      | numeric metric | page_to                                                | Page To                                                  | number    | number      |
| Yes      | numeric metric | line_from                                              | Line From                                                | number    | number      |
| Yes      | numeric metric | line_to                                                | Line To                                                  | number    | number      |
| Yes      | series tag     | fund_type                                              | Fund Type                                                | text      | text        |
| Yes      | series tag     | purpose                                                | Purpose                                                  | text      | text        |
| Yes      | numeric metric | reappropriation_amount_may_not_equal_available_funding | Reappropriation Amount (may not equal available funding) | money     | money       |
| Yes      | series tag     | justification                                          | Justification                                            | text      | text        |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:674u-sjky d:2013-01-01T00:00:00.000Z t:fund_type=SRF t:bill=ATL t:agency=DCJS t:veto_number=71 t:purpose="Town of Hamburg .................................. 19,900" t:justification="Reapprop-Expired Federal Grants  - This item passed by the Legislature, to which I object and do not approve, was funded by a Federal grant that has expired.  Accordingly, this item is disapproved." m:page_to=98 m:line_from=36 m:line_to=36 m:reappropriation_amount_may_not_equal_available_funding=19900 m:page_from=98

series e:674u-sjky d:2013-01-01T00:00:00.000Z t:fund_type=SRF t:bill=ATL t:agency=DCJS t:veto_number=72 t:purpose="Livingston County Youth Court ................... 65,000" t:justification="Reapprop-Expired Federal Grants  - This item passed by the Legislature, to which I object and do not approve, was funded by a Federal grant that has expired.  Accordingly, this item is disapproved." m:page_to=98 m:line_from=37 m:line_to=37 m:reappropriation_amount_may_not_equal_available_funding=65000 m:page_from=98

series e:674u-sjky d:2013-01-01T00:00:00.000Z t:fund_type=SRF t:bill=ATL t:agency=DCJS t:veto_number=73 t:purpose="Columbia County Sheriff's Department .......... 50,000" t:justification="Reapprop-Expired Federal Grants  - This item passed by the Legislature, to which I object and do not approve, was funded by a Federal grant that has expired.  Accordingly, this item is disapproved." m:page_to=98 m:line_from=38 m:line_to=38 m:reappropriation_amount_may_not_equal_available_funding=50000 m:page_from=98
```

## Meta Commands

```ls
metric m:page_from p:integer l:"Page From" d:"Starting page number on which the vetoed item is found in the bill." t:dataTypeName=number

metric m:page_to p:integer l:"Page To" d:"Ending page number on which the vetoed item is found in the bill." t:dataTypeName=number

metric m:line_from p:integer l:"Line From" d:"Ending line number on which the vetoed item is found in the bill." t:dataTypeName=number

metric m:line_to p:integer l:"Line To" d:"Ending line number of the vetoed item on the ending page (Page To)." t:dataTypeName=number

metric m:reappropriation_amount_may_not_equal_available_funding p:integer l:"Reappropriation Amount (may not equal available funding)" d:"Amount of the vetoed item." t:dataTypeName=money

entity e:674u-sjky l:"New York State Budget Vetoes: 2013-14" t:attribution="Division of the Budget" t:url=https://data.ny.gov/api/views/674u-sjky

property e:674u-sjky t:meta.view v:id=674u-sjky v:category="Government & Finance" v:averageRating=0 v:name="New York State Budget Vetoes: 2013-14" v:attribution="Division of the Budget"

property e:674u-sjky t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:674u-sjky t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:674u-sjky t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| veto_number | agency | bill | page_from | page_to | line_from | line_to | fund_type | purpose                                                                                                                                                                                                                                                                                                                                                  | reappropriation_amount_may_not_equal_available_funding | justification                                                                                                                                                                                                                                                                                                                                                           | 
| =========== | ====== | ==== | ========= | ======= | ========= | ======= | ========= | ======================================================================================================================================================================================================================================================================================================================================================== | ====================================================== | ======================================================================================================================================================================================================================================================================================================================================================================= | 
| 71          | DCJS   | ATL  | 98        | 98      | 36        | 36      | SRF       | Town of Hamburg .................................. 19,900                                                                                                                                                                                                                                                                                                | 19900                                                  | Reapprop-Expired Federal Grants - This item passed by the Legislature, to which I object and do not approve, was funded by a Federal grant that has expired. Accordingly, this item is disapproved.                                                                                                                                                                     | 
| 72          | DCJS   | ATL  | 98        | 98      | 37        | 37      | SRF       | Livingston County Youth Court ................... 65,000                                                                                                                                                                                                                                                                                                 | 65000                                                  | Reapprop-Expired Federal Grants - This item passed by the Legislature, to which I object and do not approve, was funded by a Federal grant that has expired. Accordingly, this item is disapproved.                                                                                                                                                                     | 
| 73          | DCJS   | ATL  | 98        | 98      | 38        | 38      | SRF       | Columbia County Sheriff's Department .......... 50,000                                                                                                                                                                                                                                                                                                   | 50000                                                  | Reapprop-Expired Federal Grants - This item passed by the Legislature, to which I object and do not approve, was funded by a Federal grant that has expired. Accordingly, this item is disapproved.                                                                                                                                                                     | 
| 74          | DCJS   | ATL  | 98        | 98      | 39        | 39      | SRF       | Rensselaer County Sheriff's Department .......... 50,000                                                                                                                                                                                                                                                                                                 | 50000                                                  | Reapprop-Expired Federal Grants - This item passed by the Legislature, to which I object and do not approve, was funded by a Federal grant that has expired. Accordingly, this item is disapproved.                                                                                                                                                                     | 
| 3           | DSP    | SO   | 640       | 640     | 16        | 18      | SRF       | For services and expenses related to community oriented policing activities. Nonpersonal service ... 135,000 ........................ (re. $73,000)                                                                                                                                                                                                      | 73000                                                  | Reapprop-Almost Fully Spent - This item passed by the Legislature, to which I object and do not approve, has been spent for its intended purpose and all contractual obligations have been satisfied. Accordingly, this item is disapproved.                                                                                                                            | 
| 4           | SUNY   | SO   | 657       | 657     | 5         | 6       | GEN       | For services and expenses related to the operation of the ATTAIN lab program ... 2,000,000 ............................. (re. $2,000,000)                                                                                                                                                                                                                | 2000000                                                | Reapprop-Fully Spent - This item passed by the Legislature, to which I object and do not approve, has already been fully expended. Accordingly, this item is disapproved.                                                                                                                                                                                               | 
| 75          | DCJS   | ATL  | 98        | 98      | 40        | 40      | SRF       | Saratoga County District Attorney's Office ....... 50,000                                                                                                                                                                                                                                                                                                | 50000                                                  | Reapprop-Expired Federal Grants - This item passed by the Legislature, to which I object and do not approve, was funded by a Federal grant that has expired. Accordingly, this item is disapproved.                                                                                                                                                                     | 
| 1           | DEC    | SO   | 207       | 208     | 43        | 2       | SRF       | For services and expenses of the Marine Science Research Center at the State University of New York at Stony Brook for research on marine disease and pathology, including suballocation to other state departments or agencies ... 500,000 .................. (re. $44,000)                                                                             | 44000                                                  | Reapprop-Older than 7 years - This item passed by the Legislature, to which I object and do not approve, is a reappropriation that is more than seven years old and no State funding has been disbursed over the most recent seven year period. In general, seven years is more than enough time to fund and implement services. Accordingly, this item is disapproved. | 
| 2           | DSP    | SO   | 638       | 638     | 21        | 25      | SRF       | For services and expenses of the federal internet crimes against chil- dren program as funded by the American Recovery and Reinvestment Act of 2009. Funds appropriated herein shall be subject to all applica- ble reporting and accountability requirements contained in such act ... 810,000 .......................................... (re. $44,000) | 44000                                                  | Reapprop-Fully Spent - This item passed by the Legislature, to which I object and do not approve, has already been fully expended. Accordingly, this item is disapproved.                                                                                                                                                                                               | 
| 5           | DOT    | SO   | 685       | 685     | 29        | 30      | SRF       | For the grant period October 1, 2004 to September 30, 2005: Maintenance undistributed ... 1,060,000 ............. (re. $1,060,000)                                                                                                                                                                                                                       | 1060000                                                | Reapprop-Older than 7 years - This item passed by the Legislature, to which I object and do not approve, is a reappropriation that is more than seven years old and no State funding has been disbursed over the most recent seven year period. In general, seven years is more than enough time to fund and implement services. Accordingly, this item is disapproved. | 
```