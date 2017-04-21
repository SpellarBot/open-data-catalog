# ACRIS - Document Control Codes

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/acris-document-control-codes-a990b) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/7isb-wh4c) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/7isb-wh4c/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/7isb-wh4c/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 7isb-wh4c |
| Name | ACRIS - Document Control Codes |
| Attribution | Department of Finance (DOF) |
| Category | City Government |
| Tags | dof, acris land records |
| Created | 2013-09-16T18:13:12Z |
| Publication Date | 2017-04-08T20:02:32Z |

## Description

ACRIS Document Type and Class Code mappings for Codes in the ACRIS Real and Personal Property Master Datasets

## Columns

```ls
| Included | Schema Type | Field Name             | Name                   | Data Type | Render Type |
| ======== | =========== | ====================== | ====================== | ========= | =========== |
| No       | time        | :updated_at            | updated_at             | meta_data | meta_data   |
| Yes      | series tag  | record_type            | RECORD TYPE            | text      | text        |
| Yes      | series tag  | doc__type              | DOC. TYPE              | text      | text        |
| Yes      | series tag  | doc__type_description  | DOC. TYPE DESCRIPTION  | text      | text        |
| Yes      | series tag  | class_code_description | CLASS CODE DESCRIPTION | text      | text        |
| Yes      | series tag  | party1_type            | PARTY1 TYPE            | text      | text        |
| Yes      | series tag  | party2_type            | PARTY2 TYPE            | text      | text        |
| Yes      | series tag  | party3_type            | PARTY3 TYPE            | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:7isb-wh4c d:2017-04-08T20:02:25.000Z t:party2_type="PARTY 2" t:record_type=D t:party1_type="PARTY 1" t:doc_type_description=AGREEMENT t:doc_type=AGMT t:class_code_description="MORTGAGES & INSTRUMENTS" m:row_number.7isb-wh4c=1

series e:7isb-wh4c d:2017-04-08T20:02:25.000Z t:party2_type="SECURED PARTY" t:record_type=D t:party1_type=DEBTOR t:doc_type_description="AMENDMENT OF FEDERAL LIEN" t:doc_type=AMFL t:class_code_description="UCC AND FEDERAL LIENS" m:row_number.7isb-wh4c=2

series e:7isb-wh4c d:2017-04-08T20:02:25.000Z t:party2_type=MORTGAGEE/LENDER t:record_type=D t:party1_type=MORTGAGER/BORROWER t:doc_type_description="ASSUMPTION OF MORTGAGE" t:doc_type=ASPM t:class_code_description="MORTGAGES & INSTRUMENTS" m:row_number.7isb-wh4c=3
```

## Meta Commands

```ls
metric m:row_number.7isb-wh4c p:long l:"Row Number"

entity e:7isb-wh4c l:"ACRIS - Document Control Codes" t:attribution="Department of Finance (DOF)" t:url=https://data.cityofnewyork.us/api/views/7isb-wh4c

property e:7isb-wh4c t:meta.view v:id=7isb-wh4c v:category="City Government" v:averageRating=0 v:name="ACRIS - Document Control Codes" v:attribution="Department of Finance (DOF)"

property e:7isb-wh4c t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:7isb-wh4c t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | record_type | doc__type | doc__type_description        | class_code_description      | party1_type         | party2_type         | party3_type | 
| =========== | =========== | ========= | ============================ | =========================== | =================== | =================== | =========== | 
| 1491681745  | D           | AGMT      | AGREEMENT                    | MORTGAGES & INSTRUMENTS     | PARTY 1             | PARTY 2             |             | 
| 1491681745  | D           | AMFL      | AMENDMENT OF FEDERAL LIEN    | UCC AND FEDERAL LIENS       | DEBTOR              | SECURED PARTY       |             | 
| 1491681745  | D           | ASPM      | ASSUMPTION OF MORTGAGE       | MORTGAGES & INSTRUMENTS     | MORTGAGER/BORROWER  | MORTGAGEE/LENDER    |             | 
| 1491681745  | D           | ASST      | ASSIGNMENT, MORTGAGE         | MORTGAGES & INSTRUMENTS     | ASSIGNOR/OLD LENDER | ASSIGNEE/NEW LENDER |             | 
| 1491681745  | D           | ASTU      | UNIT ASSIGNMENT              | DEEDS AND OTHER CONVEYANCES | GRANTOR/SELLER      | GRANTEE/BUYER       |             | 
| 1491681745  | D           | ASUM      | UCC3 ASSUMPTION              | UCC AND FEDERAL LIENS       | DEBTOR              | SECURED PARTY       |             | 
| 1491681745  | D           | BOND      | BOND                         | OTHER DOCUMENTS             | DEBTOR              | SECURED PARTY       |             | 
| 1491681745  | D           | BRUP      | UCC3 BANKRUPTCY              | UCC AND FEDERAL LIENS       | DEBTOR              | SECURED PARTY       |             | 
| 1491681745  | D           | CERR      | CERTIFICATE OF REDUCTION     | MORTGAGES & INSTRUMENTS     | MORTGAGER/BORROWER  | MORTGAGEE/LENDER    |             | 
| 1491681745  | D           | CNFL      | CONTINUATION OF FEDERAL LIEN | UCC AND FEDERAL LIENS       | DEBTOR              | SECURED PARTY       |             | 
```