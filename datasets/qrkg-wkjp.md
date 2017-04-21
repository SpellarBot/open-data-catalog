# Holacracy - Roles

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/holacracy-roles) |
| Metadata | [Link](https://data.wa.gov/api/views/qrkg-wkjp) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/qrkg-wkjp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/qrkg-wkjp/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | qrkg-wkjp |
| Name | Holacracy - Roles |
| Category | Demographics |
| Tags | roles, circles, holacracy |
| Created | 2016-08-08T21:30:31Z |
| Publication Date | 2016-08-08T22:12:57Z |

## Description

Roles created in the Holacracy Groups

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| No       |             | id          | id         | text      | number      |
| Yes      | series tag  | name        | name       | text      | text        |
| Yes      | series tag  | purpose     | purpose    | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = id
```

## Data Commands

```ls
series e:qrkg-wkjp d:2016-08-08T14:30:35.000Z t:name="Lead Link" t:purpose="State employees get paid reliably" m:row_number.qrkg-wkjp=1

series e:qrkg-wkjp d:2016-08-08T14:30:35.000Z t:name="Rep Link" t:purpose="Within the Super-Circle, the Rep Link holds the Purpose of the SubCircle; within the Sub-Circle, the Rep Link?s Purpose is: Tensions relevant to process in the Super-Circle channeled out and resolved." m:row_number.qrkg-wkjp=2

series e:qrkg-wkjp d:2016-08-08T14:30:35.000Z t:name="Data Modeling" t:purpose="Define and analyze data requirements needed to support the business processes within the scope of corresponding information systems in organizations." m:row_number.qrkg-wkjp=3
```

## Meta Commands

```ls
metric m:row_number.qrkg-wkjp p:long l:"Row Number"

entity e:qrkg-wkjp l:"Holacracy - Roles" t:url=https://data.wa.gov/api/views/qrkg-wkjp

property e:qrkg-wkjp t:meta.view v:id=qrkg-wkjp v:category=Demographics v:averageRating=0 v:name="Holacracy - Roles"

property e:qrkg-wkjp t:meta.view.license v:name="Public Domain"

property e:qrkg-wkjp t:meta.view.owner v:id=nahs-vrbk v:profileImageUrlMedium=/api/users/nahs-vrbk/profile_images/THUMB v:profileImageUrlLarge=/api/users/nahs-vrbk/profile_images/LARGE v:screenName=max.pham v:profileImageUrlSmall=/api/users/nahs-vrbk/profile_images/TINY v:displayName=max.pham

property e:qrkg-wkjp t:meta.view.tableauthor v:id=nahs-vrbk v:profileImageUrlMedium=/api/users/nahs-vrbk/profile_images/THUMB v:profileImageUrlLarge=/api/users/nahs-vrbk/profile_images/LARGE v:screenName=max.pham v:profileImageUrlSmall=/api/users/nahs-vrbk/profile_images/TINY v:roleName=editor v:displayName=max.pham
```

## Top Records

```ls
| :updated_at | id      | name                             | purpose                                                                                                                                                                                                  | 
| =========== | ======= | ================================ | ======================================================================================================================================================================================================== | 
| 1470666635  | 8024770 | Lead Link                        | State employees get paid reliably                                                                                                                                                                        | 
| 1470666635  | 75125   | Rep Link                         | Within the Super-Circle, the Rep Link holds the Purpose of the SubCircle; within the Sub-Circle, the Rep Link?s Purpose is: Tensions relevant to process in the Super-Circle channeled out and resolved. | 
| 1470666635  | 8021741 | Data Modeling                    | Define and analyze data requirements needed to support the business processes within the scope of corresponding information systems in organizations.                                                    | 
| 1470666635  | 7793906 | Social Events Guru               | Wield fun as a force multiplier                                                                                                                                                                          | 
| 1470666635  | 8025689 | Internal Services Philanthropist | WaTech staff have secure, policy-compliant IT tools and services they need to execute with excellence                                                                                                    | 
| 1470666635  | 8350703 | Circle Champion                  | Circle impediments are escalated and resolved in the hierarchy                                                                                                                                           | 
| 1470666635  | 1329925 | Pilot Program Point of Contact   | Speed up adoption of new technologies.                                                                                                                                                                   | 
| 1470666635  | 8021759 | Rep Link                         | Within the Super-Circle, the Rep Link holds the Purpose of the SubCircle; within the Sub-Circle, the Rep Link?s Purpose is: Tensions relevant to process in the Super-Circle channeled out and resolved. | 
| 1470666635  | 8021755 | Lead Link                        | Capable and productive users                                                                                                                                                                             | 
| 1470666635  | 8170255 | Networking Ninja                 | Keep gateway components talking                                                                                                                                                                          | 
```