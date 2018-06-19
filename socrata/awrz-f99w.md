# 2014 Grants Information Collection Act Report

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2014-grants-information-collection-act-report-563b5) |
| Metadata | [Link](https://data.illinois.gov/api/views/awrz-f99w) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/awrz-f99w/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/awrz-f99w/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | awrz-f99w |
| Name | 2014 Grants Information Collection Act Report |
| Category | Health-Medicaid |
| Tags | hfs, medicaid |
| Created | 2014-02-25T21:54:26Z |
| Publication Date | 2014-02-25T22:00:38Z |

## Description

Grants issued by Healthcare and Family Services for the support of various programs and initiatives.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| Yes      | series tag     | strdocid            | strDocID            | text      | text        |
| Yes      | series tag     | vendor_name         | VENDOR_NAME         | text      | text        |
| Yes      | series tag     | zip_code            | ZIP_CODE            | text      | text        |
| Yes      | series tag     | line_no             | LINE No.            | text      | number      |
| Yes      | series tag     | line_description_30 | LINE_DESCRIPTION_30 | text      | text        |
| Yes      | numeric metric | max_contract_amt    | MAX_CONTRACT_AMT    | money     | money       |
| No       |                | multi_yr_from_date  | MULTI_YR_FROM_DATE  | text      | text        |
| No       |                | multi_yr_to_date    | MULTI_YR_TO_DATE    | text      | text        |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = multi_yr_from_date,multi_yr_to_date
```

## Data Commands

```ls
series e:awrz-f99w d:2014-01-01T00:00:00.000Z t:strdocid=32M00000038 t:line_no=1 t:zip_code=60611 t:line_description_30=CHIPRA t:vendor_name="NORTHWESTERN UNIVERSITY" m:max_contract_amt=88069.71

series e:awrz-f99w d:2014-01-01T00:00:00.000Z t:strdocid=39947816759 t:line_no=1 t:zip_code=55170-9705 t:line_description_30="ALTGELD GARDEN HOUSING PROJ" t:vendor_name="TCA HEALTH INC NFP" m:max_contract_amt=400000

series e:awrz-f99w d:2014-01-01T00:00:00.000Z t:strdocid=32M00000054 t:line_no=1 t:zip_code=60901-0809 t:line_description_30="TRANSITION ENGAGEMENT SPLST" t:vendor_name="NORTHESTERN ILL AREA ON AGING" m:max_contract_amt=130666
```

## Meta Commands

```ls
metric m:max_contract_amt p:double l:MAX_CONTRACT_AMT t:dataTypeName=money

entity e:awrz-f99w l:"2014 Grants Information  Collection Act Report" t:url=https://data.illinois.gov/api/views/awrz-f99w

property e:awrz-f99w t:meta.view v:id=awrz-f99w v:category=Health-Medicaid v:averageRating=0 v:name="2014 Grants Information  Collection Act Report"

property e:awrz-f99w t:meta.view.owner v:id=xh33-g7e8 v:screenName="HFS - Administrator" v:displayName="HFS - Administrator"

property e:awrz-f99w t:meta.view.tableauthor v:id=xh33-g7e8 v:screenName="HFS - Administrator" v:roleName=publisher v:displayName="HFS - Administrator"
```

## Top Records

```ls
| strdocid    | vendor_name                    | zip_code   | line_no | line_description_30          | max_contract_amt | multi_yr_from_date | multi_yr_to_date | 
| =========== | ============================== | ========== | ======= | ============================ | ================ | ================== | ================ | 
| 32M00000038 | NORTHWESTERN UNIVERSITY        | 60611      | 1       | CHIPRA                       | 88069.71         | 17-Oct-11          | 16-Oct-13        | 
| 39947816759 | TCA HEALTH INC NFP             | 55170-9705 | 1       | ALTGELD GARDEN HOUSING PROJ  | 400000.00        | 01-Jul-96          | 30-Jun-09        | 
| 32M00000054 | NORTHESTERN ILL AREA ON AGING  | 60901-0809 | 1       | TRANSITION ENGAGEMENT SPLST  | 130666.00        | 14-May-12          | 13-May-14        | 
| 32M00000053 | AGEOPTIONS INC                 | 60301      | 1       | TRANSITION ENGAGEMENT SPCLST | 130666.00        | 10-May-12          | 09-May-14        | 
| 32M00000065 | CHICAGO FAMILY HEALTH CTR INC  | 60629      | 1       | DENTAL CLINIC                | 100000.00        | 29-Jun-12          | 31-May-14        | 
| 32M00000066 | HOWARD BROWN HEALTH CENTER     | 60613-2010 | 1       | DENTAL CLINIC                | 100000.00        | 29-Jun-12          | 31-May-14        | 
| 31M00000066 | ADVOCATE CHARITABLE FOUNDATION | 60515      | 1       | EDOPC PROJECT                | 640000.00        | 13-Jun-11          | 12-Jun-13        | 
| 32M00000037 | ILLINOIS MATERNAL CHILD HEALTH | 60642      | 1       | CHIPRA                       | 30000.00         | 29-Sep-11          | 28-Sep-13        | 
| 32M00000064 | FAMILY CHRISTIAN HEALTH CENTER | 60426-4171 | 1       | ACCESS TO DENTAL CARE        | 100000.00        | 29-Jun-12          | 31-May-14        | 
| 32M00000058 | MENTAL HLTH CTRS OF CNTRL IL   | 62702      | 2       | TRANSITION COORDINATOR       | 95385.00         | 21-Jun-12          | 20-Jun-13        | 
```