# Contracts

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/contracts-029f9) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/rsxa-ify5) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/rsxa-ify5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/rsxa-ify5/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | rsxa-ify5 |
| Name | Contracts |
| Attribution | City of Chicago |
| Category | Administration & Finance |
| Tags | contracts, procurement |
| Created | 2011-09-30T08:02:22Z |
| Publication Date | 2015-09-14T20:32:56Z |

## Description

Contracts and modifications awarded by the City of Chicago since 1993. This data is currently maintained in the City?s Financial Management and Purchasing System (FMPS), which is used throughout the City for contract management and payment. 
Legacy System Records: Purchase Order/Contract Numbers that begin with alpha characters identify records imported from legacy systems. Records with a null value in the Contract Type field were imported from legacy systems. 
"Comptroller-Other" Contract Type: Some records where the Contract Type is "COMPTROLLER-OTHER" are ordinance-based agreements and may have start dates earlier than 1993. 
Depends Upon Requirements Contracts: If the contract Award Amount is $0, the contract is not cancelled, and the contract is a blanket contract, then the contract award total Depends Upon Requirements. A Depends Upon Requirements contract is an indefinite quantities contract in which the City places orders as needed and the vendor is not guaranteed any particular contract award amount. 

Blanket vs. Standard Contracts: Only blanket contracts (contracts for repeated purchases) have FMPS end dates. Standard contracts (for example, construction contracts) terminate upon completion and acceptance of all deliverables. These dates are tracked outside of FMPS. 

Negative Modifications: Some contracts are modified to delete scope and money from a contract. These reductions are indicated by negative numbers in the Award Amount field of this dataset. 

Data Owner: Procurement Services. 
Time Period: 1993 to present. 
Frequency: Data is updated daily.

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                             | Data Type     | Render Type   |
| ======== | ============== | ============================== | ================================ | ============= | ============= |
| Yes      | series tag     | purchase_order_description     | Purchase Order Description       | text          | text          |
| Yes      | series tag     | purchase_order_contract_number | Purchase Order (Contract) Number | text          | text          |
| Yes      | series tag     | revision_number                | Revision Number                  | text          | text          |
| Yes      | series tag     | specification_number           | Specification Number             | text          | text          |
| Yes      | series tag     | contract_type                  | Contract Type                    | text          | text          |
| No       |                | start_date                     | Start Date                       | calendar_date | calendar_date |
| No       |                | end_date                       | End Date                         | calendar_date | calendar_date |
| Yes      | time           | approval_date                  | Approval Date                    | calendar_date | calendar_date |
| Yes      | series tag     | department                     | Department                       | text          | text          |
| Yes      | series tag     | vendor_name                    | Vendor Name                      | text          | text          |
| Yes      | series tag     | vendor_id                      | Vendor ID                        | text          | text          |
| No       |                | address_1                      | Address 1                        | text          | text          |
| No       |                | address_2                      | Address 2                        | text          | text          |
| Yes      | series tag     | city                           | City                             | text          | text          |
| Yes      | series tag     | state                          | State                            | text          | text          |
| Yes      | series tag     | zip                            | Zip                              | text          | text          |
| Yes      | numeric metric | award_amount                   | Award Amount                     | money         | money         |
| Yes      | series tag     | procurement_type               | Procurement Type                 | text          | text          |
| Yes      | series tag     | contract_pdf                   | Contract PDF                     | url           | url           |
```

## Time Field

```ls
Value = approval_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = end_date,start_date,address_1,address_2
```

## Data Commands

```ls
series e:rsxa-ify5 d:2014-09-08T01:17:09.000Z t:zip=60632-3750 t:revision_number=0 t:purchase_order_description="JANITORIAL SUPPLIES" t:purchase_order_contract_number=T27497 t:state=IL t:specification_number=B74851001 t:vendor_id=15193295T t:vendor_name="IMM.M.M., INC" t:city=CHICAGO m:award_amount=0

series e:rsxa-ify5 d:2014-09-08T01:17:09.000Z t:zip=60622 t:revision_number=0 t:purchase_order_description=DEMOLITION t:purchase_order_contract_number=E011442 t:department="DEPARTMENT OF BUILDINGS" t:state=IL t:specification_number=E968020030 t:vendor_id=14878414T t:vendor_name="MIDWEST WRECKING COMPANY 01" t:city=CHICAGO m:award_amount=17500

series e:rsxa-ify5 d:2014-09-08T01:17:09.000Z t:zip=60604-3806 t:revision_number=0 t:purchase_order_description="JANITORIAL SUPPLIES" t:purchase_order_contract_number=T27500 t:state=IL t:specification_number=B74851001 t:vendor_id=22085024V t:vendor_name="CHICAGO UNITED INDUSTRIES, LIMITED" t:city=CHICAGO m:award_amount=0
```

## Meta Commands

```ls
metric m:award_amount p:double l:"Award Amount" t:dataTypeName=money

entity e:rsxa-ify5 l:Contracts t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/rsxa-ify5

property e:rsxa-ify5 t:meta.view v:id=rsxa-ify5 v:category="Administration & Finance" v:attributionLink=http://www.cityofchicago.org/city/en/depts/dps/provdrs/contract.html v:averageRating=0 v:name=Contracts v:attribution="City of Chicago"

property e:rsxa-ify5 t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:rsxa-ify5 t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| purchase_order_description                     | purchase_order_contract_number | revision_number | specification_number | contract_type | start_date          | end_date            | approval_date | department              | vendor_name                        | vendor_id | address_1                | address_2      | city       | state | zip        | award_amount | procurement_type | contract_pdf | 
| ============================================== | ============================== | =============== | ==================== | ============= | =================== | =================== | ============= | ======================= | ================================== | ========= | ======================== | ============== | ========== | ===== | ========== | ============ | ================ | ============ | 
| JANITORIAL SUPPLIES                            | T27497                         | 0               | B74851001            |               | 1997-12-01T00:00:00 | 1999-11-30T00:00:00 |               |                         | IMM.M.M., INC                      | 15193295T | 5262 S KOLMAR AVE        |                | CHICAGO    | IL    | 60632-3750 | 0            |                  | [null, null] | 
| DEMOLITION                                     | E011442                        | 0               | E968020030           |               |                     |                     |               | DEPARTMENT OF BUILDINGS | MIDWEST WRECKING COMPANY 01        | 14878414T | 1950 W HUBBARD ST        |                | CHICAGO    | IL    | 60622      | 17500        |                  | [null, null] | 
| JANITORIAL SUPPLIES                            | T27500                         | 0               | B74851001            |               | 1997-12-01T00:00:00 | 1999-11-30T00:00:00 |               |                         | CHICAGO UNITED INDUSTRIES, LIMITED | 22085024V | 53 W JACKSON BLVD # 1450 |                | CHICAGO    | IL    | 60604-3806 | 0            |                  | [null, null] | 
| MASTER AGREEMENT FOR DEMOLITION SERVICES       | C02163                         | 0               | B89683203            |               |                     |                     |               | DEPARTMENT OF BUILDINGS | DEMOLITION & DEVELOPMENT, LIMITED. | 22414299V | P.0. BOX 10263           |                | CHICAGO    | IL    | 60610      | 7000         |                  | [null, null] | 
| MASTER AGREEMENT FOR DEMOLITION SERVICES       | C02106                         | 0               | B89683203            |               |                     |                     |               | DEPARTMENT OF BUILDINGS | DEMOLITION & DEVELOPMENT, LIMITED. | 22414299V | P.0. BOX 10263           |                | CHICAGO    | IL    | 60610      | 8200         |                  | [null, null] | 
| MIDWAY AIRPORT PARKING STRUCTURE               | P011339                        | 0               | PM50169701           |               |                     |                     |               | DEPT OF AVIATION        | MCHUGH/RITEWAY (JV)                | 25956572X | 1737 S MICHIGAN AVE      |                | CHICAGO    | IL    | 60616      | 42840000     |                  | [null, null] | 
| PARTS & SERVICE FOR TARGET CONCRETE SAWS       | T25387                         | 0               | B74455802            |               |                     |                     |               |                         | JULIE & STEVE'S ACQUISITION        | 23105142M | PORTABLE TOOL SALES&SRVS | 3228 S WOOD ST | CHICAGO    | IL    | 60608      | 22220        |                  | [null, null] | 
| PARTS, & SERVICE, HOMELITE EQUIPMENT           | T25483                         | 0               | B79364802            |               |                     |                     |               |                         | JULIE & STEVE'S ACQUISITION        | 23105142M | PORTABLE TOOL SALES&SRVS | 3228 S WOOD ST | CHICAGO    | IL    | 60608      | 68100        |                  | [null, null] | 
| RENTAL, MACHINERY & HEAVY EQUIPMENT - CITYWIDE | T25327                         | 0               | B69756601            |               |                     |                     |               |                         | JULIE & STEVE'S ACQUISITION        | 23105142M | PORTABLE TOOL SALES&SRVS | 3228 S WOOD ST | CHICAGO    | IL    | 60608      | 100000       |                  | [null, null] | 
| EMS INCIDENT REPORT DATA SYSTEM                | T27465                         | 0               | B72051107            |               |                     |                     |               |                         | ZOLL MEDICAL CORP                  | 31286790H | 32 SECOND AVE            |                | BURLINGTON | MA    |            | 1258514      |                  | [null, null] | 
```