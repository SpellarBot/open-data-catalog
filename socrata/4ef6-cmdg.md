# NON-DOMESTIC HEALTH INSURERS

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/non-domestic-health-insurers) |
| Metadata | [Link](https://data.ct.gov/api/views/4ef6-cmdg) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/4ef6-cmdg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/4ef6-cmdg/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | 4ef6-cmdg |
| Name | NON-DOMESTIC HEALTH INSURERS |
| Attribution | Department of Insurance |
| Category | Business |
| Tags | insurance, companies |
| Created | 2014-05-28T15:15:37Z |
| Publication Date | 2014-05-28T15:19:37Z |

## Description

LICENSED HEALTH INSURERS. ASSETS, LIABILITIES, CAPITAL AND SURPLUS, AND DIRECT WRITTEN PREMIUMS IN CONNECTICUT FOR 2012. NON-DOMESTIC (OUT-OF-STATE) HEALTH INSURERS

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| No       | time           | :updated_at             | updated_at              | meta_data | meta_data   |
| Yes      | series tag     | naic_group_code         | NAIC GROUP CODE         | text      | number      |
| Yes      | series tag     | naic_company_code       | NAIC COMPANY CODE       | text      | number      |
| Yes      | series tag     | state_of_domicile       | STATE OF DOMICILE       | text      | text        |
| Yes      | series tag     | company_name            | COMPANY NAME            | text      | text        |
| Yes      | numeric metric | admitted_assets         | ADMITTED ASSETS         | number    | number      |
| Yes      | numeric metric | capital_liabilities     | CAPITAL & LIABILITIES   | number    | number      |
| Yes      | numeric metric | capital_surplus         | CAPITAL & SURPLUS       | number    | number      |
| Yes      | numeric metric | direct_written_premiums | DIRECT WRITTEN PREMIUMS | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:4ef6-cmdg d:2014-05-28T08:15:39.000Z t:state_of_domicile=UT t:naic_group_code=4667 t:company_name="Accendo Ins Co" t:naic_company_code=63444 m:admitted_assets=117574301 m:capital_liabilities=35026565 m:capital_surplus=82547736

series e:4ef6-cmdg d:2014-05-28T08:15:39.000Z t:state_of_domicile=IN t:naic_group_code=671 t:company_name="Anthem Ins Co Inc" t:naic_company_code=28207 m:direct_written_premiums=24024659 m:admitted_assets=2638304103 m:capital_liabilities=1740210835 m:capital_surplus=898093268

series e:4ef6-cmdg d:2014-05-28T08:15:39.000Z t:state_of_domicile=DE t:naic_group_code=2479 t:company_name="Delta Dental Ins Co" t:naic_company_code=81396 m:direct_written_premiums=17940999 m:admitted_assets=141550451 m:capital_liabilities=75988312 m:capital_surplus=65562139
```

## Meta Commands

```ls
metric m:admitted_assets p:long l:"ADMITTED ASSETS" t:dataTypeName=number

metric m:capital_liabilities p:long l:"CAPITAL & LIABILITIES" t:dataTypeName=number

metric m:capital_surplus p:long l:"CAPITAL & SURPLUS" t:dataTypeName=number

metric m:direct_written_premiums p:integer l:"DIRECT WRITTEN PREMIUMS" t:dataTypeName=number

entity e:4ef6-cmdg l:"NON-DOMESTIC HEALTH INSURERS" t:attribution="Department of Insurance" t:url=https://data.ct.gov/api/views/4ef6-cmdg

property e:4ef6-cmdg t:meta.view v:id=4ef6-cmdg v:category=Business v:attributionLink="http://www.ct.gov/cid/cwp/view.asp?q=390172" v:averageRating=0 v:name="NON-DOMESTIC HEALTH INSURERS" v:attribution="Department of Insurance"

property e:4ef6-cmdg t:meta.view.license v:name="Public Domain"

property e:4ef6-cmdg t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:4ef6-cmdg t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| :updated_at | naic_group_code | naic_company_code | state_of_domicile | company_name                         | admitted_assets | capital_liabilities | capital_surplus | direct_written_premiums | 
| =========== | =============== | ================= | ================= | ==================================== | =============== | =================== | =============== | ======================= | 
| 1401264939  | 4667            | 63444             | UT                | Accendo Ins Co                       | 117574301       | 35026565            | 82547736        |                         | 
| 1401264939  | 671             | 28207             | IN                | Anthem Ins Co Inc                    | 2638304103      | 1740210835          | 898093268       | 24024659                | 
| 1401264939  | 2479            | 81396             | DE                | Delta Dental Ins Co                  | 141550451       | 75988312            | 65562139        | 17940999                | 
| 1401264939  | 2479            | 73474             | DE                | Dentegra Ins Co                      | 33302434        | 10260934            | 23041500        | 3944250                 | 
| 1401264939  |                 | 12747             | OH                | Envision Ins Co                      | 237780833       | 215751332           | 22029501        | 296756                  | 
| 1401264939  |                 | 60025             | AZ                | Express Scripts Ins Co               | 80589512        | 62607359            | 17982153        | 2749152                 | 
| 1401264939  | 812             | 71768             | PA                | HM Hlth Ins Co                       | 1335779318      | 694527090           | 641252228       | 0                       | 
| 1401264939  | 917             | 70670             | IL                | Health Care Serv Corp A Mut Legal Re | 15517613693     | 5963865276          | 9553748416      | 288096                  | 
| 1401264939  | 901             | 12902             | TX                | Healthspring Life & Hlth Ins Co Inc  | 796241036       | 356922081           | 439318956       | 8490006                 | 
| 1401264939  | 433             | 63762             | PA                | Medco Containment Life Ins Co        | 397247977       | 170554922           | 226693055       | 2644199                 | 
```