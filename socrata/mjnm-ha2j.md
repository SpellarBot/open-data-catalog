# DOMESTIC PROPERTY AND CASUALTY INSURERS

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/domestic-property-and-casualty-insurers) |
| Metadata | [Link](https://data.ct.gov/api/views/mjnm-ha2j) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/mjnm-ha2j/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/mjnm-ha2j/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | mjnm-ha2j |
| Name | DOMESTIC PROPERTY AND CASUALTY INSURERS |
| Attribution | Department of Insurance |
| Category | Business |
| Tags | insurance, companies |
| Created | 2014-05-28T15:07:17Z |
| Publication Date | 2014-05-28T15:10:31Z |

## Description

LICENSED PROPERTY AND CASUALTY INSURANCE COMPANIES. ASSETS, LIABILITIES, CAPITAL AND SURPLUS, AND DIRECT WRITTEN PREMIUMS IN CONNECTICUT FOR 2012. DOMESTIC (IN-STATE) PROPERTY AND CASUALTY INSURERS

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| No       | time           | :updated_at             | updated_at              | meta_data | meta_data   |
| Yes      | series tag     | naic_groupcode          | NAIC GROUPCODE          | text      | number      |
| Yes      | series tag     | naic_company_code       | NAIC COMPANY CODE       | text      | number      |
| Yes      | series tag     | company_name            | COMPANY NAME            | text      | text        |
| Yes      | numeric metric | admitted_assets         | ADMITTED ASSETS         | number    | number      |
| Yes      | numeric metric | liabilities             | LIABILITIES             | number    | number      |
| Yes      | numeric metric | capital_surplus         | CAPITAL & SURPLUS       | number    | number      |
| Yes      | numeric metric | direct_written_premiums | DIRECT WRITTEN PREMIUMS | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:mjnm-ha2j d:2014-05-28T08:07:20.000Z t:naic_groupcode=3416 t:company_name="AXIS Specialty Ins Co" t:naic_company_code=15610 m:liabilities=28641254 m:direct_written_premiums=0 m:admitted_assets=93558717 m:capital_surplus=64917463

series e:mjnm-ha2j d:2014-05-28T08:07:20.000Z t:naic_groupcode=1 t:company_name="Aetna Ins Co of CT" t:naic_company_code=36153 m:liabilities=7335774 m:direct_written_premiums=1189660 m:admitted_assets=22370829 m:capital_surplus=15035055

series e:mjnm-ha2j d:2014-05-28T08:07:20.000Z t:naic_groupcode=4636 t:company_name="Alterra Reins USA Inc" t:naic_company_code=10829 m:liabilities=627581314 m:direct_written_premiums=0 m:admitted_assets=1299208139 m:capital_surplus=671626825
```

## Meta Commands

```ls
metric m:admitted_assets p:long l:"ADMITTED ASSETS" t:dataTypeName=number

metric m:liabilities p:long l:LIABILITIES t:dataTypeName=number

metric m:capital_surplus p:long l:"CAPITAL & SURPLUS" t:dataTypeName=number

metric m:direct_written_premiums p:integer l:"DIRECT WRITTEN PREMIUMS" t:dataTypeName=money

entity e:mjnm-ha2j l:"DOMESTIC PROPERTY AND CASUALTY INSURERS" t:attribution="Department of Insurance" t:url=https://data.ct.gov/api/views/mjnm-ha2j

property e:mjnm-ha2j t:meta.view v:id=mjnm-ha2j v:category=Business v:attributionLink="http://www.ct.gov/cid/cwp/view.asp?q=390172" v:averageRating=0 v:name="DOMESTIC PROPERTY AND CASUALTY INSURERS" v:attribution="Department of Insurance"

property e:mjnm-ha2j t:meta.view.license v:name="Open Database License" v:termsLink=http://opendatacommons.org/licenses/odbl/1.0/

property e:mjnm-ha2j t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:mjnm-ha2j t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| :updated_at | naic_groupcode | naic_company_code | company_name                     | admitted_assets | liabilities | capital_surplus | direct_written_premiums | 
| =========== | ============== | ================= | ================================ | =============== | =========== | =============== | ======================= | 
| 1401264440  | 3416           | 15610             | AXIS Specialty Ins Co            | 93558717        | 28641254    | 64917463        | 0                       | 
| 1401264440  | 1              | 36153             | Aetna Ins Co of CT               | 22370829        | 7335774     | 15035055        | 1189660                 | 
| 1401264440  | 4636           | 10829             | Alterra Reins USA Inc            | 1299208139      | 627581314   | 671626825       | 0                       | 
| 1401264440  | 3548           | 10819             | American Equity Specialty Ins Co | 76280480        | 48352435    | 27928045        | 0                       | 
| 1401264440  | 3548           | 19062             | Automobile Ins Co Of Hartford CT | 983096013       | 687983164   | 295112849       | 12172530                | 
| 1401264440  |                | 37540             | Beazley Ins Co Inc               | 237009995       | 117628525   | 119381470       | 3406856                 | 
| 1401264440  |                | 11171             | CBIA Comp Serv Inc               | 20677206        | 16206691    | 4470515         | 5171682                 | 
| 1401264440  | 3548           | 25615             | Charter Oak Fire Ins Co          | 918495654       | 686324572   | 232171082       | 33937625                | 
| 1401264440  | 158            | 10019             | Clearwater Select Ins Co         | 118599401       | 7325571     | 111273830       | 0                       | 
| 1401264440  | 4770           | 15890             | Connecticut Medical Ins Co       | 440773044       | 197024702   | 243748342       | 28142266                | 
```