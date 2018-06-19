# Decision Package Prioritization 2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/decision-package-prioritization-2016) |
| Metadata | [Link](https://data.wa.gov/api/views/gdw2-uv4h) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/gdw2-uv4h/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/gdw2-uv4h/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | gdw2-uv4h |
| Name | Decision Package Prioritization 2016 |
| Created | 2016-12-29T21:51:53Z |
| Publication Date | 2016-12-29T21:55:58Z |

## Description

Formal IT expenditure prioritization occurs on an annual basis as part of the state?s budget building activities (link is external). The Governor and the Legislature look to the OCIO to provide guidance on whether an agency's proposed IT expenditure is sound and consistent with the state?s IT strategy to inform policy decisions on the allocation of limited state funds.

The OCIO establishes prioritization criteria in response to current state business needs and changing technologies. The OCIO evaluates agency funding requests (received in the form of decision packages) against those values and establishes a priority ranking of all funding requests. The resulting prioritized list of project funding requests is submitted to both the Governor?s office and the Legislature.

## Columns

```ls
| Included | Schema Type    | Field Name                                                | Name                                                      | Data Type | Render Type |
| ======== | ============== | ========================================================= | ========================================================= | ========= | =========== |
| Yes      | series tag     | agency                                                    | Agency                                                    | text      | text        |
| Yes      | series tag     | decision_package_title                                    | Decision Package Title                                    | text      | text        |
| Yes      | numeric metric | final_score                                               | Final Score                                               | number    | number      |
| Yes      | numeric metric | business_process_improvement                              | Business Process Improvement                              | number    | number      |
| Yes      | numeric metric | risk_mitigation_organizational_change_management          | Risk Mitigation / Organizational Change Management        | number    | number      |
| Yes      | numeric metric | measurable_business_outcomes_aligned_to_agency_strategy   | Measurable Business Outcomes Aligned to Agency Strategy   | number    | number      |
| Yes      | numeric metric | impact_of_not_doing                                       | Impact of Not Doing                                       | number    | number      |
| Yes      | numeric metric | interoperability                                          | Interoperability                                          | number    | number      |
| Yes      | numeric metric | leverages_existing_systems_or_creates_reusable_components | Leverages Existing Systems or Creates Reusable Components | number    | number      |
| Yes      | numeric metric | mobility                                                  | Mobility                                                  | number    | number      |
| Yes      | numeric metric | open_data                                                 | Open Data                                                 | number    | number      |
| Yes      | numeric metric | modernization                                             | Modernization                                             | number    | number      |
| Yes      | numeric metric | early_value_delivery                                      | Early Value Delivery                                      | number    | number      |
| Yes      | numeric metric | security                                                  | Security                                                  | number    | number      |
| Yes      | numeric metric | privacy_principles                                        | Privacy Principles                                        | number    | number      |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:gdw2-uv4h d:2016-01-01T00:00:00.000Z t:decision_package_title="Procure and Time and Attendance System" t:agency=DEL m:privacy_principles=0.07 m:early_value_delivery=0.04 m:modernization=0.05 m:impact_of_not_doing=0.14 m:business_process_improvement=0.05 m:interoperability=0.07 m:security=0.12 m:final_score=0.76 m:leverages_existing_systems_or_creates_reusable_components=0.04 m:risk_mitigation_organizational_change_management=0.06 m:open_data=0.01 m:measurable_business_outcomes_aligned_to_agency_strategy=0.08 m:mobility=0.03

series e:gdw2-uv4h d:2016-01-01T00:00:00.000Z t:decision_package_title="Pension and Relief Tracking System" t:agency=BVFFRO m:privacy_principles=0.07 m:early_value_delivery=0.04 m:modernization=0.05 m:impact_of_not_doing=0.13 m:business_process_improvement=0.05 m:interoperability=0.05 m:security=0.19 m:final_score=0.74 m:leverages_existing_systems_or_creates_reusable_components=0.03 m:risk_mitigation_organizational_change_management=0.05 m:open_data=0 m:measurable_business_outcomes_aligned_to_agency_strategy=0.05 m:mobility=0.03

series e:gdw2-uv4h d:2016-01-01T00:00:00.000Z t:decision_package_title="Continuation of Business and Technology Modernization DRIVES Rollout 2" t:agency=DOL m:privacy_principles=0.06 m:early_value_delivery=0.02 m:modernization=0.03 m:impact_of_not_doing=0.13 m:business_process_improvement=0.06 m:interoperability=0.08 m:security=0.11 m:final_score=0.72 m:leverages_existing_systems_or_creates_reusable_components=0.05 m:risk_mitigation_organizational_change_management=0.08 m:open_data=0.01 m:measurable_business_outcomes_aligned_to_agency_strategy=0.08 m:mobility=0.01
```

## Meta Commands

```ls
metric m:final_score p:float l:"Final Score" t:dataTypeName=number

metric m:business_process_improvement p:float l:"Business Process Improvement" t:dataTypeName=number

metric m:risk_mitigation_organizational_change_management p:float l:"Risk Mitigation / Organizational Change Management" t:dataTypeName=number

metric m:measurable_business_outcomes_aligned_to_agency_strategy p:float l:"Measurable Business Outcomes Aligned to Agency Strategy" t:dataTypeName=number

metric m:impact_of_not_doing p:float l:"Impact of Not Doing" t:dataTypeName=number

metric m:interoperability p:float l:Interoperability t:dataTypeName=number

metric m:leverages_existing_systems_or_creates_reusable_components p:float l:"Leverages Existing Systems or Creates Reusable Components" t:dataTypeName=number

metric m:mobility p:float l:Mobility t:dataTypeName=number

metric m:open_data p:float l:"Open Data" t:dataTypeName=number

metric m:modernization p:float l:Modernization t:dataTypeName=number

metric m:early_value_delivery p:float l:"Early Value Delivery" t:dataTypeName=number

metric m:security p:float l:Security t:dataTypeName=number

metric m:privacy_principles p:float l:"Privacy Principles" t:dataTypeName=number

entity e:gdw2-uv4h l:"Decision Package Prioritization 2016" t:url=https://data.wa.gov/api/views/gdw2-uv4h

property e:gdw2-uv4h t:meta.view v:id=gdw2-uv4h v:averageRating=0 v:name="Decision Package Prioritization 2016"

property e:gdw2-uv4h t:meta.view.owner v:id=2iur-ynm8 v:profileImageUrlMedium=/api/users/2iur-ynm8/profile_images/THUMB v:profileImageUrlLarge=/api/users/2iur-ynm8/profile_images/LARGE v:screenName=ryan.leisinger v:profileImageUrlSmall=/api/users/2iur-ynm8/profile_images/TINY v:displayName=ryan.leisinger

property e:gdw2-uv4h t:meta.view.tableauthor v:id=2iur-ynm8 v:profileImageUrlMedium=/api/users/2iur-ynm8/profile_images/THUMB v:profileImageUrlLarge=/api/users/2iur-ynm8/profile_images/LARGE v:screenName=ryan.leisinger v:profileImageUrlSmall=/api/users/2iur-ynm8/profile_images/TINY v:roleName=administrator v:displayName=ryan.leisinger
```

## Top Records

```ls
| agency     | decision_package_title                                                 | final_score | business_process_improvement | risk_mitigation_organizational_change_management | measurable_business_outcomes_aligned_to_agency_strategy | impact_of_not_doing | interoperability | leverages_existing_systems_or_creates_reusable_components | mobility | open_data | modernization | early_value_delivery | security | privacy_principles | 
| ========== | ====================================================================== | =========== | ============================ | ================================================ | ======================================================= | =================== | ================ | ========================================================= | ======== | ========= | ============= | ==================== | ======== | ================== | 
| DEL        | Procure and Time and Attendance System                                 | 0.76        | 0.05                         | 0.06                                             | 0.08                                                    | 0.14                | 0.07             | 0.04                                                      | 0.03     | 0.01      | 0.05          | 0.04                 | 0.12     | 0.07               | 
| BVFFRO     | Pension and Relief Tracking System                                     | 0.74        | 0.05                         | 0.05                                             | 0.05                                                    | 0.13                | 0.05             | 0.03                                                      | 0.03     | 0.00      | 0.05          | 0.04                 | 0.19     | 0.07               | 
| DOL        | Continuation of Business and Technology Modernization DRIVES Rollout 2 | 0.72        | 0.06                         | 0.08                                             | 0.08                                                    | 0.13                | 0.08             | 0.05                                                      | 0.01     | 0.01      | 0.03          | 0.02                 | 0.11     | 0.06               | 
| DFW        | Information Security Compliance                                        | 0.71        | 0.04                         | 0.02                                             | 0.04                                                    | 0.14                | 0.05             | 0.04                                                      | 0.01     | 0.00      | 0.03          | 0.04                 | 0.21     | 0.10               | 
| LCB        | Traceability System Replacement                                        | 0.69        | 0.03                         | 0.07                                             | 0.07                                                    | 0.12                | 0.08             | 0.01                                                      | 0.01     | 0.01      | 0.05          | 0.03                 | 0.14     | 0.07               | 
| LCB        | Tax and Fee System Replacement                                         | 0.68        | 0.05                         | 0.07                                             | 0.07                                                    | 0.12                | 0.08             | 0.02                                                      | 0.01     | 0.01      | 0.05          | 0.03                 | 0.10     | 0.06               | 
| CTS        | Infrastructure for Cloud Services                                      | 0.66        | 0.04                         | 0.03                                             | 0.03                                                    | 0.11                | 0.06             | 0.05                                                      | 0.02     | 0.00      | 0.05          | 0.04                 | 0.18     | 0.04               | 
| DSHS BHA   | Electronic Health Record                                               | 0.66        | 0.06                         | 0.08                                             | 0.06                                                    | 0.14                | 0.06             | 0.04                                                      | 0.02     | 0.00      | 0.05          | 0.02                 | 0.08     | 0.06               | 
| DOT        | Labor System Replacement                                               | 0.65        | 0.06                         | 0.08                                             | 0.07                                                    | 0.11                | 0.06             | 0.05                                                      | 0.01     | 0.00      | 0.05          | 0.02                 | 0.06     | 0.07               | 
| CTS WATECH | Increased Cyber Defense                                                | 0.62        | 0.03                         | 0.04                                             | 0.06                                                    | 0.09                | 0.05             | 0.04                                                      | 0.00     | 0.00      | 0.02          | 0.03                 | 0.21     | 0.05               | 
```