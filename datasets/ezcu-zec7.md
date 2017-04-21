# DOMESTIC HEALTH INSURERS

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/domestic-health-insurers) |
| Metadata | [Link](https://data.ct.gov/api/views/ezcu-zec7) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/ezcu-zec7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/ezcu-zec7/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | ezcu-zec7 |
| Name | DOMESTIC HEALTH INSURERS |
| Attribution | Department of Insurance |
| Category | Business |
| Tags | insurance, companies |
| Created | 2014-05-28T15:20:20Z |
| Publication Date | 2014-05-28T15:23:35Z |

## Description

LICENSED HEALTH INSURERS: ASSETS, LIABILITIES, CAPITAL AND SURPLUS, AND DIRECT WRITTEN PREMIUMS IN CONNECTICUT FOR 2012. DOMESTIC (IN-STATE) INSURERS

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
| Yes      | numeric metric | direct_written_premiums | DIRECT WRITTEN PREMIUMS | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:ezcu-zec7 d:2014-05-28T08:20:22.000Z t:naic_groupcode=1 t:company_name="Aetna Better Hlth Inc" t:naic_company_code=13174 m:liabilities=2223454 m:admitted_assets=19744351 m:capital_surplus=17520897

series e:ezcu-zec7 d:2014-05-28T08:20:22.000Z t:naic_groupcode=1 t:company_name="Aetna Hlth Inc CT Corp" t:naic_company_code=95935 m:liabilities=51912407 m:direct_written_premiums=320324033 m:admitted_assets=75410275 m:capital_surplus=23497868

series e:ezcu-zec7 d:2014-05-28T08:20:22.000Z t:naic_groupcode=707 t:company_name="Americhoice of CT Inc" t:naic_company_code=13178 m:liabilities=1710352 m:admitted_assets=5822525 m:capital_surplus=4112174
```

## Meta Commands

```ls
metric m:admitted_assets p:integer l:"ADMITTED ASSETS" t:dataTypeName=number

metric m:liabilities p:integer l:LIABILITIES t:dataTypeName=number

metric m:capital_surplus p:integer l:"CAPITAL & SURPLUS" t:dataTypeName=number

metric m:direct_written_premiums p:integer l:"DIRECT WRITTEN PREMIUMS" t:dataTypeName=number

entity e:ezcu-zec7 l:"DOMESTIC HEALTH INSURERS" t:attribution="Department of Insurance" t:url=https://data.ct.gov/api/views/ezcu-zec7

property e:ezcu-zec7 t:meta.view v:id=ezcu-zec7 v:category=Business v:attributionLink="http://www.ct.gov/cid/cwp/view.asp?q=390172" v:averageRating=0 v:name="DOMESTIC HEALTH INSURERS" v:attribution="Department of Insurance"

property e:ezcu-zec7 t:meta.view.license v:name="Public Domain"

property e:ezcu-zec7 t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:ezcu-zec7 t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| :updated_at | naic_groupcode | naic_company_code | company_name             | admitted_assets | liabilities | capital_surplus | direct_written_premiums | 
| =========== | ============== | ================= | ======================== | =============== | =========== | =============== | ======================= | 
| 1401265222  | 1              | 13174             | Aetna Better Hlth Inc    | 19744351        | 2223454     | 17520897        |                         | 
| 1401265222  | 1              | 95935             | Aetna Hlth Inc CT Corp   | 75410275        | 51912407    | 23497868        | 320324033               | 
| 1401265222  | 707            | 13178             | Americhoice of CT Inc    | 5822525         | 1710352     | 4112174         |                         | 
| 1401265222  | 671            | 60217             | Anthem Hlth Plans Inc    | 720740783       | 391830708   | 328910075       | 1897648644              | 
| 1401265222  | 901            | 95660             | Cigna Hlthcare of CT Inc | 31099952        | 2841636     | 28258316        | 11948581                | 
| 1401265222  | 1127           | 95675             | Connecticare Inc         | 278666263       | 125408107   | 153258155       | 974951803               | 
| 1401265222  | 1127           | 11209             | Connecticare Ins Co Inc  | 61659230        | 37919121    | 23740113        | 225056927               | 
| 1401265222  | 707            | 95968             | Health Net Of CT Inc     | 8517554         | 1729359     | 6788195         |                         | 
| 1401265222  | 707            | 96798             | Oxford Hlth Plans CT Inc | 223373645       | 125974846   | 97398800        | 656221253               | 
| 1401265222  | 1189           | 39616             | Vision Serv Plan Ins Co  | 228314494       | 94047281    | 134267213       | 15787619                | 
```