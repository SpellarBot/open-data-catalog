# Budget - FY2014 Appropriations And Expenditures with FY2015 Adopted Appropriation

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/budget-fy2014-appropriations-and-expenditures-with-fy2015-adopted-appropriation) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/rbkx-fj74) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/rbkx-fj74/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/rbkx-fj74/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | rbkx-fj74 |
| Name | Budget - FY2014 Appropriations And Expenditures with FY2015 Adopted Appropriation |
| Attribution | Cook County Department of Budget and Management Services |
| Category | Finance & Administration |
| Tags | budget, expenditures |
| Created | 2015-04-30T18:29:36Z |
| Publication Date | 2015-04-30T18:51:32Z |

## Description

Fiscal Year 2014 Adopted and Adjusted Appropriations with Final Fiscal Year 2014 Expenditures and Fiscal Year 2015 Adopted Appropriation

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| Yes      | series tag     | office                     | Office                     | text      | text        |
| Yes      | series tag     | control_officer            | Control Officer            | text      | text        |
| Yes      | series tag     | fund                       | Fund                       | text      | text        |
| Yes      | series tag     | fund_type                  | Fund Type                  | text      | text        |
| Yes      | series tag     | general_fund_type          | General Fund Type          | text      | text        |
| Yes      | series tag     | bureau                     | Bureau                     | text      | text        |
| Yes      | series tag     | tabcode                    | TabCode                    | text      | text        |
| Yes      | series tag     | tab                        | Tab                        | text      | text        |
| Yes      | series tag     | department_number          | Department Number          | text      | text        |
| Yes      | series tag     | department_name            | Department Name            | text      | text        |
| Yes      | numeric metric | object_class               | Object Class               | number    | number      |
| Yes      | series tag     | object_class_title         | Object Class Title         | text      | text        |
| Yes      | numeric metric | account                    | Account                    | number    | number      |
| Yes      | series tag     | object_account             | Object Account             | text      | number      |
| Yes      | series tag     | object_account_description | Object Account Description | text      | text        |
| Yes      | numeric metric | fy2014_adopted             | FY2014 Adopted             | money     | money       |
| Yes      | numeric metric | fy2014_adjusted            | FY2014 Adjusted            | money     | money       |
| Yes      | numeric metric | fy2014_expenditures        | FY2014 Expenditures        | money     | money       |
| Yes      | numeric metric | fy2015_adopted             | FY2015 Adopted             | money     | money       |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:rbkx-fj74 d:2014-01-01T00:00:00.000Z t:office="Cook County Health & Hospital Systems Board" t:fund_type=Enterprise t:general_fund_type="Health Fund" t:object_account=501010.0 t:department_number=240 t:control_officer="Cook County Health & Hospital System" t:tab="COOK COUNTY HEALTH AND HOSPITALS SYSTEM" t:object_class_title="Personal Services" t:fund="Health Fund" t:department_name="Cermak Health Services of Cook County" t:object_account_description="Salaries and Wages of Regular Employees" t:tabcode=O t:bureau="COOK COUNTY HEALTH AND HOSPITALS SYSTEM" m:fy2014_adjusted=32933493 m:fy2015_adopted=38599916 m:account=110 m:fy2014_expenditures=31588303.71 m:object_class=100 m:fy2014_adopted=37358390

series e:rbkx-fj74 d:2014-01-01T00:00:00.000Z t:office="Cook County Health & Hospital Systems Board" t:fund_type=Enterprise t:general_fund_type="Health Fund" t:object_account=501210.0 t:department_number=240 t:control_officer="Cook County Health & Hospital System" t:tab="COOK COUNTY HEALTH AND HOSPITALS SYSTEM" t:object_class_title="Personal Services" t:fund="Health Fund" t:department_name="Cermak Health Services of Cook County" t:object_account_description="Overtime Compensation" t:tabcode=O t:bureau="COOK COUNTY HEALTH AND HOSPITALS SYSTEM" m:fy2014_adjusted=4450018 m:fy2015_adopted=2096110 m:account=120 m:fy2014_expenditures=4450017.73 m:object_class=100 m:fy2014_adopted=2300000

series e:rbkx-fj74 d:2014-01-01T00:00:00.000Z t:office="Cook County Health & Hospital Systems Board" t:fund_type=Enterprise t:general_fund_type="Health Fund" t:object_account=501360.0 t:department_number=240 t:control_officer="Cook County Health & Hospital System" t:tab="COOK COUNTY HEALTH AND HOSPITALS SYSTEM" t:object_class_title="Personal Services" t:fund="Health Fund" t:department_name="Cermak Health Services of Cook County" t:object_account_description="Per Diem Personnel" t:tabcode=O t:bureau="COOK COUNTY HEALTH AND HOSPITALS SYSTEM" m:fy2014_adjusted=929048 m:fy2015_adopted=1375237 m:account=133 m:fy2014_expenditures=798346.71 m:object_class=100 m:fy2014_adopted=929048
```

## Meta Commands

```ls
metric m:object_class p:float l:"Object Class" t:dataTypeName=number

metric m:account p:integer l:Account t:dataTypeName=number

metric m:fy2014_adopted p:double l:"FY2014 Adopted" t:dataTypeName=money

metric m:fy2014_adjusted p:double l:"FY2014 Adjusted" t:dataTypeName=money

metric m:fy2014_expenditures p:double l:"FY2014 Expenditures" t:dataTypeName=money

metric m:fy2015_adopted p:double l:"FY2015 Adopted" t:dataTypeName=money

entity e:rbkx-fj74 l:"Budget - FY2014 Appropriations And Expenditures with FY2015 Adopted Appropriation" t:attribution="Cook County Department of Budget and Management Services" t:url=https://datacatalog.cookcountyil.gov/api/views/rbkx-fj74

property e:rbkx-fj74 t:meta.view v:id=rbkx-fj74 v:category="Finance & Administration" v:attributionLink=http://www.cookcountyil.gov/budget-and-management-services-department-of/ v:averageRating=0 v:name="Budget - FY2014 Appropriations And Expenditures with FY2015 Adopted Appropriation" v:attribution="Cook County Department of Budget and Management Services"

property e:rbkx-fj74 t:meta.view.license v:name="Public Domain"

property e:rbkx-fj74 t:meta.view.owner v:id=u38g-hbsa v:screenName="Cook County Open Data" v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"

property e:rbkx-fj74 t:meta.view.tableauthor v:id=u38g-hbsa v:screenName="Cook County Open Data" v:roleName=administrator v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"
```

## Top Records

```ls
| office                                      | control_officer                      | fund        | fund_type  | general_fund_type | bureau                                  | tabcode | tab                                     | department_number | department_name                       | object_class | object_class_title   | account | object_account | object_account_description                             | fy2014_adopted | fy2014_adjusted | fy2014_expenditures | fy2015_adopted | 
| =========================================== | ==================================== | =========== | ========== | ================= | ======================================= | ======= | ======================================= | ================= | ===================================== | ============ | ==================== | ======= | ============== | ====================================================== | ============== | =============== | =================== | ============== | 
| Cook County Health & Hospital Systems Board | Cook County Health & Hospital System | Health Fund | Enterprise | Health Fund       | COOK COUNTY HEALTH AND HOSPITALS SYSTEM | O       | COOK COUNTY HEALTH AND HOSPITALS SYSTEM | 240               | Cermak Health Services of Cook County | 100.0        | Personal Services    | 110     | 501010.0       | Salaries and Wages of Regular Employees                | 37358390.0     | 32933493.0      | 31588303.71         | 38599916.0     | 
| Cook County Health & Hospital Systems Board | Cook County Health & Hospital System | Health Fund | Enterprise | Health Fund       | COOK COUNTY HEALTH AND HOSPITALS SYSTEM | O       | COOK COUNTY HEALTH AND HOSPITALS SYSTEM | 240               | Cermak Health Services of Cook County | 100.0        | Personal Services    | 120     | 501210.0       | Overtime Compensation                                  | 2300000.0      | 4450018.0       | 4450017.73          | 2096110.0      | 
| Cook County Health & Hospital Systems Board | Cook County Health & Hospital System | Health Fund | Enterprise | Health Fund       | COOK COUNTY HEALTH AND HOSPITALS SYSTEM | O       | COOK COUNTY HEALTH AND HOSPITALS SYSTEM | 240               | Cermak Health Services of Cook County | 100.0        | Personal Services    | 133     | 501360.0       | Per Diem Personnel                                     | 929048.0       | 929048.0        | 798346.71           | 1375237.0      | 
| Cook County Health & Hospital Systems Board | Cook County Health & Hospital System | Health Fund | Enterprise | Health Fund       | COOK COUNTY HEALTH AND HOSPITALS SYSTEM | O       | COOK COUNTY HEALTH AND HOSPITALS SYSTEM | 240               | Cermak Health Services of Cook County | 100.0        | Personal Services    | 136     | 501400.0       | Differential Pay                                       | 2000000.0      | 2000000.0       | 1886532.14          | 2466301.0      | 
| Cook County Health & Hospital Systems Board | Cook County Health & Hospital System | Health Fund | Enterprise | Health Fund       | COOK COUNTY HEALTH AND HOSPITALS SYSTEM | O       | COOK COUNTY HEALTH AND HOSPITALS SYSTEM | 240               | Cermak Health Services of Cook County | 100.0        | Personal Services    | 155     | 501420.0       | Medical Practitioners As Required                      | 45484.0        | 45484.0         | 37019.6             | 45484.0        | 
| Cook County Health & Hospital Systems Board | Cook County Health & Hospital System | Health Fund | Enterprise | Health Fund       | COOK COUNTY HEALTH AND HOSPITALS SYSTEM | O       | COOK COUNTY HEALTH AND HOSPITALS SYSTEM | 240               | Cermak Health Services of Cook County | 100.0        | Personal Services    | 170     | 501510.0       | Mandatory Medicare Costs                               | 0.0            | 373861.0        | 373860.05           | 644754.0       | 
| Cook County Health & Hospital Systems Board | Cook County Health & Hospital System | Health Fund | Enterprise | Health Fund       | COOK COUNTY HEALTH AND HOSPITALS SYSTEM | O       | COOK COUNTY HEALTH AND HOSPITALS SYSTEM | 240               | Cermak Health Services of Cook County | 100.0        | Personal Services    | 183     | 501770.0       | Seminars for Professional Employees                    | 19400.0        | 19400.0         | 0.0                 | 19400.0        | 
| Cook County Health & Hospital Systems Board | Cook County Health & Hospital System | Health Fund | Enterprise | Health Fund       | COOK COUNTY HEALTH AND HOSPITALS SYSTEM | O       | COOK COUNTY HEALTH AND HOSPITALS SYSTEM | 240               | Cermak Health Services of Cook County | 100.0        | Personal Services    | 186     | 501860.0       | Training Programs for Staff Personnel                  | 54320.0        | 54320.0         | 0.0                 | 30000.0        | 
| Cook County Health & Hospital Systems Board | Cook County Health & Hospital System | Health Fund | Enterprise | Health Fund       | COOK COUNTY HEALTH AND HOSPITALS SYSTEM | O       | COOK COUNTY HEALTH AND HOSPITALS SYSTEM | 240               | Cermak Health Services of Cook County | 100.0        | Personal Services    | 190     | 501970.0       | Transportation and Other Travel Expenses for Employees | 25000.0        | 25000.0         | 3198.16             | 25000.0        | 
| Cook County Health & Hospital Systems Board | Cook County Health & Hospital System | Health Fund | Enterprise | Health Fund       | COOK COUNTY HEALTH AND HOSPITALS SYSTEM | O       | COOK COUNTY HEALTH AND HOSPITALS SYSTEM | 240               | Cermak Health Services of Cook County | 200.0        | Contractual Services | 213     | 520010.0       | Ambulance and Patient Transportation Service           | 230000.0       | 259600.0        | 259600.0            | 258901.0       | 
```