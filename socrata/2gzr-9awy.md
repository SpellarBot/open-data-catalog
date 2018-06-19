# IDPH ASBESTOS LICENSED PROFESSIONALS

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idph-asbestos-licensed-professionals-e4696) |
| Metadata | [Link](https://data.illinois.gov/api/views/2gzr-9awy) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/2gzr-9awy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/2gzr-9awy/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 2gzr-9awy |
| Name | IDPH ASBESTOS LICENSED PROFESSIONALS |
| Category | Public Health |
| Tags | asbestos, professionals |
| Created | 2013-09-10T20:42:11Z |
| Publication Date | 2017-03-02T15:28:12Z |

## Description

Last Update:  March 2017
Asbestos Licensed Professionals fall into six major categories. 
o	Supervisors are the Contractor's designees on asbestos abatement projects and are responsible for ensuring that work is conducted in accordance with state and federal regulations. 
o	Project Managers are the building owner's or school district's representative on school projects and are responsible for ensuring that the workers and supervisors are complying with the contract specification and state and federal regulations. Projects Managers are not required to oversee asbestos abatement projects in commercial and public buildings, but if a building owner chooses to have an individual oversee the project, then the Department requires that the person be licensed. 
o	Air Sampling Professionals are responsible for taking air samples to determine the airborne concentration of asbestos inside and outside the work area. The Air Sampling Professional conducts aggressive clearance air monitoring at the end of asbestos abatement projects to ensure that the concentration of asbestos in the air is acceptable for reoccupation of the area. 
o	Project Designers are required to develop project designs for school buildings. The project designers are required to draw up specifications and contracts that contractors must follow to complete an asbestos abatement project that meets state and federal regulations. If a project design is developed for asbestos abatement in commercial and public buildings, then it must be completed by a licensed Project Designer.
o	Inspectors are required to identify asbestos-containing materials by sampling suspected asbestos-containing materials discovered during an inspection. 
o	Management Planners are required to develop management plans based upon information from an Inspector. Each school in Illinois must develop and maintain an asbestos management plan describing the management of the school's asbestos-containing building materials. Commercial and public buildings in Illinois are not required to develop management plans.

## Columns

```ls
| Included | Schema Type | Field Name                              | Name                                    | Data Type | Render Type |
| ======== | =========== | ======================================= | ======================================= | ========= | =========== |
| No       | time        | :updated_at                             | updated_at                              | meta_data | meta_data   |
| Yes      | series tag  | last_name                               | LAST NAME                               | text      | text        |
| Yes      | series tag  | first_name                              | FIRST NAME                              | text      | text        |
| No       |             | address                                 | ADDRESS                                 | text      | text        |
| Yes      | series tag  | city                                    | CITY                                    | text      | text        |
| Yes      | series tag  | state                                   | STATE                                   | text      | text        |
| Yes      | series tag  | zip_code                                | ZIP CODE                                | text      | text        |
| Yes      | series tag  | phone                                   | PHONE                                   | text      | number      |
| Yes      | series tag  | company_name                            | COMPANY NAME                            | text      | text        |
| No       |             | company_address                         | COMPANY ADDRESS                         | text      | text        |
| Yes      | series tag  | company_city                            | COMPANY CITY                            | text      | text        |
| Yes      | series tag  | company_state                           | COMPANY STATE                           | text      | text        |
| Yes      | series tag  | company_zip_code                        | COMPANY ZIP CODE                        | text      | text        |
| Yes      | series tag  | company_phone                           | COMPANY PHONE                           | text      | number      |
| Yes      | series tag  | company_county                          | COMPANY COUNTY                          | text      | text        |
| Yes      | series tag  | supervisor_professional_license         | SUPERVISOR PROFESSIONAL LICENSE         | text      | text        |
| Yes      | series tag  | inspector_professional_license          | INSPECTOR PROFESSIONAL LICENSE          | text      | text        |
| Yes      | series tag  | management_planner_professional_license | MANAGEMENT PLANNER PROFESSIONAL LICENSE | text      | text        |
| Yes      | series tag  | project_designer_professional_license   | PROJECT DESIGNER PROFESSIONAL LICENSE   | text      | text        |
| Yes      | series tag  | project_manager_professional_license    | PROJECT MANAGER PROFESSIONAL LICENSE    | text      | text        |
| Yes      | series tag  | air_sampling_professional_license       | AIR SAMPLING PROFESSIONAL LICENSE       | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address,company_address
```

## Data Commands

```ls
series e:2gzr-9awy d:2017-03-02T15:27:12.000Z t:company_state=MO t:first_name=WADE t:company_zip_code=63103 t:zip_code=62930 t:company_name="ENVIROTECH, INC." t:supervisor_professional_license=SUPERVISOR t:last_name=ABELL t:state=IL t:company_county="OUT OF STATE" t:company_city="ST. LOUIS" t:city=ELDORADO m:row_number.2gzr-9awy=1

series e:2gzr-9awy d:2017-03-02T15:27:12.000Z t:company_state=MO t:first_name=TERESA t:company_zip_code=63103 t:zip_code=62930 t:company_name="ENVIROTECH, INC." t:supervisor_professional_license=SUPERVISOR t:last_name=ABELL t:state=IL t:company_city="ST. LOUIS" t:city=ELDORADO m:row_number.2gzr-9awy=2

series e:2gzr-9awy d:2017-03-02T15:27:12.000Z t:company_state=IL t:company_zip_code=60612 t:zip_code=60527 t:state=IL t:inspector_professional_license=INSPECTOR t:company_county=Cook t:company_city=CHICAGO t:city="BURR RIDGE" t:first_name=SARA t:air_sampling_professional_license="AIR SAMPLING PROFESSIONAL" t:company_name="ENVIRONMENTAL ANALYSIS INC." t:last_name=ABRAMOWICZ t:project_manager_professional_license="PROJECT MANAGER" m:row_number.2gzr-9awy=3
```

## Meta Commands

```ls
metric m:row_number.2gzr-9awy p:long l:"Row Number"

entity e:2gzr-9awy l:"IDPH ASBESTOS LICENSED PROFESSIONALS" t:url=https://data.illinois.gov/api/views/2gzr-9awy

property e:2gzr-9awy t:meta.view v:id=2gzr-9awy v:category="Public Health" v:attributionLink=http://www.dph.illinois.gov/topics-services/environmental-health-protection/abatement-structures-migrant-labor/asbestos v:averageRating=0 v:name="IDPH ASBESTOS LICENSED PROFESSIONALS"

property e:2gzr-9awy t:meta.view.owner v:id=e75b-y6hv v:screenName=Jenny v:displayName=Jenny

property e:2gzr-9awy t:meta.view.tableauthor v:id=e75b-y6hv v:screenName=Jenny v:roleName=publisher v:displayName=Jenny
```

## Top Records

```ls
| :updated_at | last_name  | first_name | address | city         | state | zip_code | phone | company_name                         | company_address | company_city | company_state | company_zip_code | company_phone | company_county | supervisor_professional_license | inspector_professional_license | management_planner_professional_license | project_designer_professional_license | project_manager_professional_license | air_sampling_professional_license | 
| =========== | ========== | ========== | ======= | ============ | ===== | ======== | ===== | ==================================== | =============== | ============ | ============= | ================ | ============= | ============== | =============================== | ============================== | ======================================= | ===================================== | ==================================== | ================================= | 
| 1488468432  | ABELL      | WADE       | NA      | ELDORADO     | IL    | 62930    |       | ENVIROTECH, INC.                     | NA              | ST. LOUIS    | MO            | 63103            |               | OUT OF STATE   | SUPERVISOR                      |                                |                                         |                                       |                                      |                                   | 
| 1488468432  | ABELL      | TERESA     | NA      | ELDORADO     | IL    | 62930    |       | ENVIROTECH, INC.                     | NA              | ST. LOUIS    | MO            | 63103            |               |                | SUPERVISOR                      |                                |                                         |                                       |                                      |                                   | 
| 1488468432  | ABRAMOWICZ | SARA       | NA      | BURR RIDGE   | IL    | 60527    |       | ENVIRONMENTAL ANALYSIS INC.          | NA              | CHICAGO      | IL            | 60612            |               | Cook           |                                 | INSPECTOR                      |                                         |                                       | PROJECT MANAGER                      | AIR SAMPLING PROFESSIONAL         | 
| 1488468432  | ABRAMOWICZ | STEVE      | NA      | BURR RIDGE   | IL    | 60527    |       | ENVIRONMENTAL ANALYSIS INC.          | NA              | CHICAGO      | IL            | 60612            |               | Cook           |                                 |                                |                                         |                                       | PROJECT MANAGER                      | AIR SAMPLING PROFESSIONAL         | 
| 1488468432  | ACKERS     | BRUCE      | NA      | MACOMB       | IL    | 61455    |       | WESTERN IL UNIVERSITY PHYSICAL PLANT | NA              | MACOMB       | IL            | 61455            |               |                | SUPERVISOR                      |                                |                                         |                                       |                                      |                                   | 
| 1488468432  | ACORD      | ROBERT     | NA      | BRIGHTON     | IL    | 62012    |       | Olin Brass                           | NA              | East Alton   | IL            | 62024            |               | Madison        | SUPERVISOR                      | INSPECTOR                      |                                         |                                       |                                      |                                   | 
| 1488468432  | ACOSTA     | EDWIN      | NA      | Indianapolis | IN    | 46214    |       | MIDWEST ASBESTOS ABATEMENT CORP.     | NA              | ST. PETERS   | MO            | 63376            |               | OUT OF STATE   | SUPERVISOR                      |                                |                                         |                                       |                                      |                                   | 
| 1488468432  | ADAMEK     | BROOKE     | NA      | CHICAGO      | IL    | 60641    |       | PIONEER ENVIRONMENTAL SERVICES, INC. | NA              | CHICAGO      | IL            | 60612            |               | Cook           |                                 | INSPECTOR                      |                                         |                                       |                                      |                                   | 
| 1488468432  | ADAMS      | RONDELL    | NA      | GARY         | IN    | 46406    |       | JHF CONSULTING INC                   | NA              | OAK PARK     | IL            | 60302            | 8474528659    |                |                                 | INSPECTOR                      |                                         |                                       | PROJECT MANAGER                      | AIR SAMPLING PROFESSIONAL         | 
| 1488468432  | ADAMS      | STEVE      | NA      | DEMOTTE      | IN    | 46310    |       | MIDWAY CONTRACTING GROUP, LLC        | NA              | TINLEY PARK  | IL            | 60477            |               | Cook           | SUPERVISOR                      |                                |                                         |                                       |                                      |                                   | 
```