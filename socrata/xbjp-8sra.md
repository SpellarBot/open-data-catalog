# Unemployment Insurance Beneficiaries and Benefit Amounts Paid: Beginning 2001

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/unemployment-insurance-beneficiaries-and-benefit-amounts-paid-beginning-2010) |
| Metadata | [Link](https://data.ny.gov/api/views/xbjp-8sra) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/xbjp-8sra/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/xbjp-8sra/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | xbjp-8sra |
| Name | Unemployment Insurance Beneficiaries and Benefit Amounts Paid: Beginning 2001 |
| Attribution | New York State Department of Labor |
| Category | Economic Development |
| Tags | unemployment, insurance, benefits, beneficiaries |
| Created | 2015-04-13T19:48:47Z |
| Publication Date | 2017-04-17T22:09:41Z |

## Description

Dataset contains monthly counts, from 2001 to present, of individuals receiving regular unemployment insurance benefits, as well as the total amount of benefits received from New York State. 

Data are provided for the state, 10 labor market regions, and counties.  State counts can include everyone who receives benefits through New York State (including out-of-state residents) or only state residents who do so (excluding out-of-state residents). 

Regular unemployment insurance includes: Unemployment Insurance (UI) Compensation, Compensation for Federal Employees (UCFE), Unemployment Compensation for Ex-Service Members (UCX), Shared Work (SW) and Self Employment Assistance Program (SEAP).  It excludes federal extensions and 599.2 training.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                      | Data Type | Render Type |
| ======== | ============== | ======================= | ========================= | ========= | =========== |
| No       |                | year                    | Year                      | number    | number      |
| No       |                | month                   | Month                     | number    | number      |
| Yes      | series tag     | region                  | Region                    | text      | text        |
| Yes      | series tag     | county                  | County                    | text      | text        |
| Yes      | numeric metric | beneficiaries           | Beneficiaries             | number    | number      |
| Yes      | numeric metric | benefit_amounts_dollars | Benefit Amounts (Dollars) | money     | money       |
```

## Time Field

```ls
Value = year-month
Format & Zone = yyyy-MM
```

## Series Fields

```ls
Excluded Fields = year,month
```

## Data Commands

```ls
series e:xbjp-8sra d:2001-01-01T00:00:00.000Z t:region=Capital t:county=Albany m:beneficiaries=2500 m:benefit_amounts_dollars=2390000

series e:xbjp-8sra d:2001-01-01T00:00:00.000Z t:region=Capital t:county=Columbia m:beneficiaries=600 m:benefit_amounts_dollars=580000

series e:xbjp-8sra d:2001-01-01T00:00:00.000Z t:region=Capital t:county=Greene m:beneficiaries=800 m:benefit_amounts_dollars=760000
```

## Meta Commands

```ls
metric m:beneficiaries p:integer l:Beneficiaries d:"Number of individuals who receive unemployment insurance benefits (in the described geography, during the demarcated time period). Counts of beneficiaries are rounded to the nearest 100." t:dataTypeName=number

metric m:benefit_amounts_dollars p:integer l:"Benefit Amounts (Dollars)" d:"Dollar amount of benefits disbursed to the unemployment insurance beneficiaries. Benefit Amounts are rounded to the nearest $10,000." t:dataTypeName=money

entity e:xbjp-8sra l:"Unemployment Insurance Beneficiaries and Benefit Amounts Paid: Beginning 2001" t:attribution="New York State Department of Labor" t:url=https://data.ny.gov/api/views/xbjp-8sra

property e:xbjp-8sra t:meta.view v:id=xbjp-8sra v:category="Economic Development" v:attributionLink=http://www.labor.ny.gov/stats/UI/Unemployment-Insurance-Data.shtm v:averageRating=0 v:name="Unemployment Insurance Beneficiaries and Benefit Amounts Paid: Beginning 2001" v:attribution="New York State Department of Labor"

property e:xbjp-8sra t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:xbjp-8sra t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:xbjp-8sra t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| year | month | region           | county      | beneficiaries | benefit_amounts_dollars | 
| ==== | ===== | ================ | =========== | ============= | ======================= | 
| 2001 | 1     | Capital          | Albany      | 2500          | 2390000                 | 
| 2001 | 1     | Capital          | Columbia    | 600           | 580000                  | 
| 2001 | 1     | Capital          | Greene      | 800           | 760000                  | 
| 2001 | 1     | Capital          | Rensselaer  | 1900          | 1830000                 | 
| 2001 | 1     | Capital          | Saratoga    | 2300          | 2340000                 | 
| 2001 | 1     | Capital          | Schenectady | 1500          | 1410000                 | 
| 2001 | 1     | Capital          | Warren      | 1400          | 1200000                 | 
| 2001 | 1     | Capital          | Washington  | 900           | 750000                  | 
| 2001 | 1     | Central New York | Cayuga      | 1500          | 1220000                 | 
| 2001 | 1     | Central New York | Cortland    | 900           | 980000                  | 
```