# Controllable Agency Expenses Financial Plan

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/controllable-agency-expenses-financial-plan-5d031) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/t9tf-aegg) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/t9tf-aegg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/t9tf-aegg/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | t9tf-aegg |
| Name | Controllable Agency Expenses Financial Plan |
| Attribution | Office of the Mayor (OTM) |
| Category | City Government |
| Tags | controllable, expenses, uniformed forces, health and welfare, elected officals |
| Created | 2013-02-13T21:42:45Z |
| Publication Date | 2013-06-21T20:08:45Z |

## Description

Financial plan representing Controllable Agency Expenses

## Columns

```ls
| Included | Schema Type    | Field Name                       | Name                               | Data Type | Render Type |
| ======== | ============== | ================================ | ================================== | ========= | =========== |
| No       | time           | :updated_at                      | updated_at                         | meta_data | meta_data   |
| Yes      | series tag     | year                             | Year                               | text      | text        |
| Yes      | series tag     | police_department                | Police Department                  | text      | money       |
| Yes      | series tag     | fire_department                  | Fire Department                    | text      | money       |
| Yes      | series tag     | department_of_correction         | Department of Correction           | text      | money       |
| Yes      | series tag     | sanitation_department            | Sanitation Department              | text      | money       |
| Yes      | numeric metric | social_services                  | Social Services                    | money     | money       |
| Yes      | numeric metric | children_s_services              | Children?s Services                | money     | money       |
| Yes      | numeric metric | homeless_services                | Homeless Services                  | money     | money       |
| Yes      | numeric metric | health_and_mental_hygiene        | Health and Mental Hygiene          | money     | money       |
| Yes      | numeric metric | hhc_subsidy                      | HHC Subsidy                        | money     | money       |
| Yes      | numeric metric | housing_preservation_development | Housing Preservation & Development | money     | money       |
| Yes      | numeric metric | environmental_protection         | Environmental Protection           | money     | money       |
| Yes      | numeric metric | finance                          | Finance                            | money     | money       |
| Yes      | numeric metric | transportation                   | Transportation                     | money     | money       |
| Yes      | numeric metric | parks_and_recreation             | Parks and Recreation               | money     | money       |
| Yes      | series tag     | department_of_education          | Department of Education            | text      | money       |
| Yes      | numeric metric | cuny                             | CUNY                               | money     | money       |
| Yes      | numeric metric | mayoralty                        | Mayoralty                          | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:t9tf-aegg d:2013-02-13T13:42:47.000Z t:department_of_education=7143 t:department_of_correction=1059.00 t:police_department=4336.00 t:year="FY 2012" t:fire_department=1513.00 t:sanitation_department=1242.00 m:housing_preservation_development=36 m:health_and_mental_hygiene=612 m:mayoralty=61 m:parks_and_recreation=257 m:children_s_services=848 m:homeless_services=427 m:cuny=561 m:finance=217 m:transportation=416 m:hhc_subsidy=75 m:environmental_protection=943 m:social_services=466

series e:t9tf-aegg d:2013-02-13T13:42:47.000Z t:department_of_education=7083 t:department_of_correction=1043.00 t:police_department=4296.00 t:year="FY 2013" t:fire_department=1536.00 t:sanitation_department=1339.00 m:housing_preservation_development=61 m:health_and_mental_hygiene=614 m:mayoralty=64 m:parks_and_recreation=268 m:children_s_services=842 m:homeless_services=456 m:cuny=584 m:finance=227 m:transportation=424 m:hhc_subsidy=71 m:environmental_protection=1062 m:social_services=534

series e:t9tf-aegg d:2013-02-13T13:42:47.000Z t:department_of_education=7080 t:department_of_correction=1047.00 t:police_department=4311.00 t:year="FY 2014" t:fire_department=1453.00 t:sanitation_department=1400.00 m:housing_preservation_development=49 m:health_and_mental_hygiene=572 m:mayoralty=63 m:parks_and_recreation=283 m:children_s_services=810 m:homeless_services=437 m:cuny=553 m:finance=220 m:transportation=434 m:hhc_subsidy=65 m:environmental_protection=1040 m:social_services=488
```

## Meta Commands

```ls
metric m:social_services p:double l:"Social Services" t:dataTypeName=money

metric m:children_s_services p:double l:"Children?s Services" t:dataTypeName=money

metric m:homeless_services p:double l:"Homeless Services" t:dataTypeName=money

metric m:health_and_mental_hygiene p:double l:"Health and Mental Hygiene" t:dataTypeName=money

metric m:hhc_subsidy p:double l:"HHC Subsidy" t:dataTypeName=money

metric m:housing_preservation_development p:double l:"Housing Preservation & Development" t:dataTypeName=money

metric m:environmental_protection p:double l:"Environmental Protection" t:dataTypeName=money

metric m:finance p:double l:Finance t:dataTypeName=money

metric m:transportation p:double l:Transportation t:dataTypeName=money

metric m:parks_and_recreation p:double l:"Parks and Recreation" t:dataTypeName=money

metric m:cuny p:double l:CUNY t:dataTypeName=money

metric m:mayoralty p:double l:Mayoralty t:dataTypeName=money

entity e:t9tf-aegg l:"Controllable Agency Expenses Financial Plan" t:attribution="Office of the Mayor (OTM)" t:url=https://data.cityofnewyork.us/api/views/t9tf-aegg

property e:t9tf-aegg t:meta.view v:id=t9tf-aegg v:category="City Government" v:attributionLink="http://www.nyc.gov/portal/site/nycgov/menuitem.c0935b9a57bb4ef3daf2f1c701c789a0/index.jsp?pageID=mayor_press_release&catID=1194&doc_name=http%3A%2F%2Fwww.nyc.gov%2Fhtml%2Fom%2Fhtml%2F2010b%2Fpr389-10.html&cc=unused1978&rc=1194&ndi=1" v:averageRating=0 v:name="Controllable Agency Expenses Financial Plan" v:attribution="Office of the Mayor (OTM)"

property e:t9tf-aegg t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:t9tf-aegg t:meta.view.tableauthor v:id=iacr-duv5 v:screenName=Tejas.Patel v:displayName=Tejas.Patel
```

## Top Records

```ls
| :updated_at | year    | police_department | fire_department | department_of_correction | sanitation_department | social_services | children_s_services | homeless_services | health_and_mental_hygiene | hhc_subsidy | housing_preservation_development | environmental_protection | finance | transportation | parks_and_recreation | department_of_education | cuny   | mayoralty | 
| =========== | ======= | ================= | =============== | ======================== | ===================== | =============== | =================== | ================= | ========================= | =========== | ================================ | ======================== | ======= | ============== | ==================== | ======================= | ====== | ========= | 
| 1360762967  | FY 2012 | 4336.00           | 1513.00         | 1059.00                  | 1242.00               | 466.00          | 848.00              | 427.00            | 612.00                    | 75.00       | 36.00                            | 943.00                   | 217.00  | 416.00         | 257.00               | 7143                    | 561.00 | 61.00     | 
| 1360762967  | FY 2013 | 4296.00           | 1536.00         | 1043.00                  | 1339.00               | 534.00          | 842.00              | 456.00            | 614.00                    | 71.00       | 61.00                            | 1062.00                  | 227.00  | 424.00         | 268.00               | 7083                    | 584.00 | 64.00     | 
| 1360762967  | FY 2014 | 4311.00           | 1453.00         | 1047.00                  | 1400.00               | 488.00          | 810.00              | 437.00            | 572.00                    | 65.00       | 49.00                            | 1040.00                  | 220.00  | 434.00         | 283.00               | 7080                    | 553.00 | 63.00     | 
| 1360762967  | FY 2015 | 4327.00           | 1408.00         | 1044.00                  | 1447.00               | 501.00          | 810.00              | 433.00            | 569.00                    | 64.00       | 49.00                            | 1024.00                  | 219.00  | 449.00         | 283.00               | 7114                    | 547.00 | 63.00     | 
| 1360762967  | FY 2016 | 4329.00           | 1405.00         | 1044.00                  | 1445.00               | 490.00          | 810.00              | 433.00            | 569.00                    | 64.00       | 49.00                            | 1022.00                  | 219.00  | 451.00         | 283.00               | 7133                    | 546.00 | 63.00     | 
| 1360762967  | FY 2017 | 4329.00           | 1407.00         | 1044.00                  | 1445.00               | 487.00          | 810.00              | 433.00            | 569.00                    | 64.00       | 49.00                            | 1020.00                  | 220.00  | 451.00         | 283.00               | 7239                    | 546.00 | 63.00     | 
```