# Agency Admin Rules URLs

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/agency-admin-rules-urls-f036c) |
| Metadata | [Link](https://data.oregon.gov/api/views/qisn-cfm3) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/qisn-cfm3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/qisn-cfm3/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | qisn-cfm3 |
| Name | Agency Admin Rules URLs |
| Category | Administrative |
| Tags | administrative rules, admin rules, agency admin rules, agency administrative rules |
| Created | 2013-12-17T15:14:11Z |
| Publication Date | 2017-01-13T18:58:17Z |

## Description

As a result of HB 2370 that was passed in 2013 agencies began providing links to Agency website/webpage that has Agency Administrative Rules or information about rules. Sorted by Agency name. This data is updated periodically as new links are reported..

## Columns

```ls
| Included | Schema Type | Field Name       | Name              | Data Type | Render Type |
| ======== | =========== | ================ | ================= | ========= | =========== |
| No       | time        | :updated_at      | updated_at        | meta_data | meta_data   |
| Yes      | series tag  | name_of_agency   | Name of Agency    | text      | text        |
| Yes      | series tag  | division_section | Division/ Section | text      | text        |
| Yes      | series tag  | url_links_to     | URL Links to?     | text      | text        |
| Yes      | series tag  | link             | Link              | url       | url         |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:qisn-cfm3 d:2014-05-22T09:17:46.000Z t:name_of_agency="Administrative Services, Department of" t:link=http://www.oregon.gov/DAS/Pages/index.aspx t:url_links_to="URL links to agency Administrative Rules" m:row_number.qisn-cfm3=1

series e:qisn-cfm3 d:2014-05-22T09:17:46.000Z t:name_of_agency="Administrative Services, Department of" t:link=http://www.oregon.gov/DAS/IA/Pages/CAE_resources.aspx t:division_section="Internal Auditing" t:url_links_to="URL links to agency Administrative Rules" m:row_number.qisn-cfm3=2

series e:qisn-cfm3 d:2014-05-22T09:17:46.000Z t:name_of_agency="Administrative Services, Department of" t:link=http://www.oregon.gov/DAS/CHRO/pages/rules.aspx t:division_section="Chief Human Resources Office" t:url_links_to="URL links to agency Administrative Rules" m:row_number.qisn-cfm3=3
```

## Meta Commands

```ls
metric m:row_number.qisn-cfm3 p:long l:"Row Number"

entity e:qisn-cfm3 l:"Agency Admin Rules URLs" t:url=https://data.oregon.gov/api/views/qisn-cfm3

property e:qisn-cfm3 t:meta.view v:id=qisn-cfm3 v:category=Administrative v:averageRating=0 v:name="Agency Admin Rules URLs"

property e:qisn-cfm3 t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:qisn-cfm3 t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| :updated_at | name_of_agency                         | division_section                                     | url_links_to                                        | link                                                                            | 
| =========== | ====================================== | ==================================================== | =================================================== | =============================================================================== | 
| 1400750266  | Administrative Services, Department of |                                                      | URL links to agency Administrative Rules            | [http://www.oregon.gov/DAS/Pages/index.aspx, null]                              | 
| 1400750266  | Administrative Services, Department of | Internal Auditing                                    | URL links to agency Administrative Rules            | [http://www.oregon.gov/DAS/IA/Pages/CAE_resources.aspx, null]                   | 
| 1400750266  | Administrative Services, Department of | Chief Human Resources Office                         | URL links to agency Administrative Rules            | [http://www.oregon.gov/DAS/CHRO/pages/rules.aspx, null]                         | 
| 1400750266  | Administrative Services, Department of | EAM State and Federal Surplus Property Program       | URL links to agency Administrative Rules            | [http://www.oregon.gov/DAS/EAM/SURPLS/Pages/adminrules.aspx, null]              | 
| 1400750266  | Administrative Services, Department of | Department of Business Services                      | URL links to both Rules and Information about Rules | [http://www.oregon.gov/DAS/OP/Pages/policies.aspx, null]                        | 
| 1400750266  | Administrative Services, Department of | Chief Information Office                             | URL links to agency Administrative Rules            | [http://www.oregon.gov/DAS/CIO/pages/adminrules.aspx, null]                     | 
| 1400750266  | Administrative Services, Department of | Chief Financial Office                               | URL links to agency Administrative Rules            | [http://arcweb.sos.state.or.us/pages/rules/oars_100/oar_122/122_070.html, null] | 
| 1400750266  | Administrative Services, Department of | Enterprise Goods and Services / Procurement Services | URL links to both Rules and Information about Rules | [http://authoring-cms.oregon.egov.com/DAS/EGS/ps/Pages/ors279-menu.aspx, null]  | 
| 1400750266  | Administrative Services, Department of | Enterprise Asset Management                          | URL links to both Rules and Information about Rules | [http://www.oregon.gov/DAS/EAM/pages/adminrules.aspx, null]                     | 
| 1400750266  | Administrative Services, Department of | Chief Financial Office/Procurement Policy            | URL links to both Rules and Information about Rules | [http://www.oregon.gov/DAS/EGS/ps/Pages/ors279-menu.aspx, null]                 | 
```