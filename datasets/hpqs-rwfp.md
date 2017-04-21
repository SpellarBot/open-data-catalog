# HPD Tax Incentive Element

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hpd-tax-incentive-element-d0ceb) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/hpqs-rwfp) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/hpqs-rwfp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/hpqs-rwfp/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | hpqs-rwfp |
| Name | HPD Tax Incentive Element |
| Attribution | Department of Housing Preservation and Development (HPD) |
| Category | Housing & Development |
| Tags | department of housing preservation and development, hpd, tax incentive |
| Created | 2014-02-26T21:30:07Z |
| Publication Date | 2014-02-27T19:51:53Z |

## Description

Information on tax incentive Year 1 amounts, name and type for those tax exemptions or abatements that meet the definition of City Financial Assistance for each project.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| No       | time           | :updated_at        | updated_at         | meta_data | meta_data   |
| Yes      | series tag     | taxincentive_dw_id | TaxIncentive DW ID | text      | number      |
| Yes      | series tag     | project_id         | Project ID         | text      | number      |
| Yes      | series tag     | tax_incentive_name | Tax Incentive Name | text      | text        |
| Yes      | numeric metric | year1_amount       | Year1 Amount       | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:hpqs-rwfp d:2014-02-26T13:30:13.000Z t:taxincentive_dw_id=1700 t:tax_incentive_name="Article XI Tax Exemption" t:project_id=39223 m:year1_amount=2443001

series e:hpqs-rwfp d:2014-02-26T13:30:13.000Z t:taxincentive_dw_id=1839 t:tax_incentive_name="Article XI Tax Exemption" t:project_id=39264 m:year1_amount=1266379

series e:hpqs-rwfp d:2014-02-26T13:30:13.000Z t:taxincentive_dw_id=1887 t:tax_incentive_name="Article XI Tax Exemption" t:project_id=39326 m:year1_amount=28658
```

## Meta Commands

```ls
metric m:year1_amount p:float l:"Year1 Amount" d:"Estimated dollar amount for Year 1 of associated tax exemption" t:dataTypeName=number

entity e:hpqs-rwfp l:"HPD Tax Incentive Element" t:attribution="Department of Housing Preservation and Development (HPD)" t:url=https://data.cityofnewyork.us/api/views/hpqs-rwfp

property e:hpqs-rwfp t:meta.view v:id=hpqs-rwfp v:category="Housing & Development" v:averageRating=0 v:name="HPD Tax Incentive Element" v:attribution="Department of Housing Preservation and Development (HPD)"

property e:hpqs-rwfp t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:hpqs-rwfp t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | taxincentive_dw_id | project_id | tax_incentive_name       | year1_amount | 
| =========== | ================== | ========== | ======================== | ============ | 
| 1393421413  | 1700               | 39223      | Article XI Tax Exemption | 2443001.00   | 
| 1393421413  | 1839               | 39264      | Article XI Tax Exemption | 1266379.00   | 
| 1393421413  | 1887               | 39326      | Article XI Tax Exemption | 28658.00     | 
| 1393421413  | 1082               | 39359      | Article XI Tax Exemption | 6882567.00   | 
| 1393421413  | 2189               | 39385      | Article XI Tax Exemption | 9863405.00   | 
| 1393421413  | 2079               | 39402      | Article XI Tax Exemption | 69684.00     | 
| 1393421413  | 1927               | 39408      | Article XI Tax Exemption | 63000.00     | 
| 1393421413  | 2121               | 39522      | UDAAP Tax Exemption      | 20.00        | 
| 1393421413  | 2358               | 40548      | 422 Tax Exemption        | 81054.00     | 
| 1393421413  | 842                | 41274      | Article XI Tax Exemption | 257868.00    | 
```