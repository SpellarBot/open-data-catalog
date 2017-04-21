# NON-DOMESTIC PROPERTY AND CASUALTY INSURERS

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/non-domestic-property-and-casualty-insurers) |
| Metadata | [Link](https://data.ct.gov/api/views/sygv-wsi2) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/sygv-wsi2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/sygv-wsi2/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | sygv-wsi2 |
| Name | NON-DOMESTIC PROPERTY AND CASUALTY INSURERS |
| Attribution | Department of Insurance |
| Category | Business |
| Tags | insurance, companies |
| Created | 2014-05-28T15:01:36Z |
| Publication Date | 2014-05-28T15:06:40Z |

## Description

LICENSED PROPERTY AND CASUALTY INSURANCE COMPANIES: ASSETS, LIABILITIES, CAPITAL AND SURPLUS, AND DIRECT WRITTEN PREMIUMS IN CONNECTICUT FOR 2012 - NON-DOMESTIC (OUT OF STATE) INSURERS

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| No       | time           | :updated_at             | updated_at              | meta_data | meta_data   |
| Yes      | series tag     | naic_group_code         | NAIC GROUP CODE         | text      | number      |
| Yes      | series tag     | naic_company_code       | NAIC COMPANY CODE       | text      | number      |
| Yes      | series tag     | company_name            | COMPANY NAME            | text      | text        |
| Yes      | series tag     | state_of_domicile       | STATE OF DOMICILE       | text      | text        |
| Yes      | numeric metric | admitted_assets         | ADMITTED ASSETS         | number    | number      |
| Yes      | numeric metric | capital_liabilities     | CAPITAL & LIABILITIES   | money     | money       |
| Yes      | numeric metric | capital_surplus         | CAPITAL & SURPLUS       | money     | money       |
| Yes      | numeric metric | direct_written_premiums | DIRECT WRITTEN PREMIUMS | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:sygv-wsi2 d:2014-05-28T08:01:39.000Z t:state_of_domicile=DE t:naic_group_code=212 t:company_name="21st Century Assur Co" t:naic_company_code=44245 m:direct_written_premiums=0 m:admitted_assets=68264478 m:capital_liabilities=3132170 m:capital_surplus=65132308

series e:sygv-wsi2 d:2014-05-28T08:01:39.000Z t:state_of_domicile=CA t:naic_group_code=212 t:company_name="21st Century Cas Co" t:naic_company_code=36404 m:direct_written_premiums=0 m:admitted_assets=12554978 m:capital_liabilities=687879 m:capital_surplus=11867099

series e:sygv-wsi2 d:2014-05-28T08:01:39.000Z t:state_of_domicile=PA t:naic_group_code=212 t:company_name="21st Century Centennial Ins Co" t:naic_company_code=34789 m:direct_written_premiums=930332 m:admitted_assets=540388682 m:capital_liabilities=31787880 m:capital_surplus=508600802
```

## Meta Commands

```ls
metric m:admitted_assets p:long l:"ADMITTED ASSETS" t:dataTypeName=number

metric m:capital_liabilities p:long l:"CAPITAL & LIABILITIES" t:dataTypeName=money

metric m:capital_surplus p:long l:"CAPITAL & SURPLUS" t:dataTypeName=money

metric m:direct_written_premiums p:integer l:"DIRECT WRITTEN PREMIUMS" t:dataTypeName=money

entity e:sygv-wsi2 l:"NON-DOMESTIC PROPERTY AND CASUALTY INSURERS" t:attribution="Department of Insurance" t:url=https://data.ct.gov/api/views/sygv-wsi2

property e:sygv-wsi2 t:meta.view v:id=sygv-wsi2 v:category=Business v:attributionLink="http://www.ct.gov/cid/cwp/view.asp?q=390172" v:averageRating=0 v:name="NON-DOMESTIC PROPERTY AND CASUALTY INSURERS" v:attribution="Department of Insurance"

property e:sygv-wsi2 t:meta.view.license v:name="Public Domain"

property e:sygv-wsi2 t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:sygv-wsi2 t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| :updated_at | naic_group_code | naic_company_code | company_name                   | state_of_domicile | admitted_assets | capital_liabilities | capital_surplus | direct_written_premiums | 
| =========== | =============== | ================= | ============================== | ================= | =============== | =================== | =============== | ======================= | 
| 1401264099  | 212             | 44245             | 21st Century Assur Co          | DE                | 68264478        | 3132170             | 65132308        | 0                       | 
| 1401264099  | 212             | 36404             | 21st Century Cas Co            | CA                | 12554978        | 687879              | 11867099        | 0                       | 
| 1401264099  | 212             | 34789             | 21st Century Centennial Ins Co | PA                | 540388682       | 31787880            | 508600802       | 930332                  | 
| 1401264099  | 212             | 12963             | 21st Century Ins Co            | CA                | 931855033       | 34451238            | 897403795       | 0                       | 
| 1401264099  | 212             | 10245             | 21st Century Ins Co Of the SW  | TX                | 5494074         | 0                   | 5494074         | 0                       | 
| 1401264099  | 212             | 32220             | 21st Century N Amer Ins Co     | NY                | 569023204       | 51680019            | 517343185       | 45474054                | 
| 1401264099  | 212             | 36587             | 21st Century Natl Ins Co       | NY                | 24775483        | 1589828             | 23185655        | 0                       | 
| 1401264099  | 212             | 23795             | 21st Century Pacific Ins Co    | CO                | 45047829        | 3132170             | 41915659        | 0                       | 
| 1401264099  | 212             | 22225             | 21st Century Preferred Ins Co  | PA                | 41937619        | 3132169             | 38805450        | 1265708                 | 
| 1401264099  | 212             | 20796             | 21st Century Premier Ins Co    | PA                | 256396258       | 15779049            | 240617209       | 1724805                 | 
```