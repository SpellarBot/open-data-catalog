# Building Permits

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/building-permits-058f4) |
| Metadata | [Link](https://data.sfgov.org/api/views/i98e-djp9) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/i98e-djp9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/i98e-djp9/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | i98e-djp9 |
| Name | Building Permits |
| Category | Housing and Buildings |
| Created | 2016-04-21T02:30:56Z |
| Publication Date | 2016-10-12T17:08:54Z |

## Description

This data set pertains to all types of structural permits. Data includes details on application/permit numbers, job addresses, supervisorial districts, and the current status of the applications. Data is uploaded weekly by DBI. Users can access permit information online through DBI’s Permit Tracking System which is 24/7 at www.sfdbi.org/dbipts.

## Columns

```ls
| Included | Schema Type    | Field Name                             | Name                                   | Data Type     | Render Type   |
| ======== | ============== | ====================================== | ====================================== | ============= | ============= |
| Yes      | series tag     | permit_number                          | Permit Number                          | text          | text          |
| Yes      | series tag     | permit_type                            | Permit Type                            | text          | number        |
| Yes      | series tag     | permit_type_definition                 | Permit Type Definition                 | text          | text          |
| Yes      | time           | permit_creation_date                   | Permit Creation Date                   | date          | date          |
| Yes      | series tag     | block                                  | Block                                  | text          | text          |
| Yes      | series tag     | lot                                    | Lot                                    | text          | text          |
| Yes      | series tag     | street_number                          | Street Number                          | text          | text          |
| Yes      | series tag     | street_number_suffix                   | Street Number Suffix                   | text          | text          |
| Yes      | series tag     | street_name                            | Street Name                            | text          | text          |
| Yes      | series tag     | street_suffix                          | Street Suffix                          | text          | text          |
| Yes      | numeric metric | unit                                   | Unit                                   | number        | text          |
| Yes      | series tag     | unit_suffix                            | Unit Suffix                            | text          | text          |
| Yes      | series tag     | description                            | Description                            | text          | text          |
| Yes      | series tag     | status                                 | Status                                 | text          | text          |
| No       |                | status_date                            | Status Date                            | calendar_date | calendar_date |
| Yes      | series tag     | structural_notification                | Structural Notification                | checkbox      | checkbox      |
| Yes      | numeric metric | number_of_existing_stories             | Number of Existing Stories             | number        | number        |
| Yes      | numeric metric | number_of_proposed_stories             | Number of Proposed Stories             | number        | number        |
| Yes      | series tag     | voluntary_soft_story_retrofit          | Voluntary Soft-Story Retrofit          | checkbox      | checkbox      |
| Yes      | series tag     | fire_only_permit                       | Fire Only Permit                       | checkbox      | checkbox      |
| No       |                | permit_expiration_date                 | Permit Expiration Date                 | date          | date          |
| Yes      | numeric metric | estimated_cost                         | Estimated Cost                         | number        | number        |
| Yes      | numeric metric | revised_cost                           | Revised Cost                           | number        | number        |
| Yes      | series tag     | existing_use                           | Existing Use                           | text          | text          |
| Yes      | numeric metric | existing_units                         | Existing Units                         | number        | number        |
| Yes      | series tag     | proposed_use                           | Proposed Use                           | text          | text          |
| Yes      | numeric metric | proposed_units                         | Proposed Units                         | number        | number        |
| Yes      | numeric metric | plansets                               | Plansets                               | number        | number        |
| Yes      | series tag     | tidf_compliance                        | TIDF Compliance                        | checkbox      | checkbox      |
| Yes      | series tag     | use_codes                              | Use Codes                              | text          | text          |
| Yes      | series tag     | use_code_description                   | Use Code Description                   | text          | text          |
| Yes      | series tag     | existing_construction_type             | Existing Construction Type             | text          | text          |
| Yes      | series tag     | existing_construction_type_description | Existing Construction Type Description | text          | text          |
| Yes      | series tag     | proposed_construction_type             | Proposed Construction Type             | text          | text          |
| Yes      | series tag     | proposed_construction_type_description | Proposed Construction Type Description | text          | text          |
| Yes      | series tag     | supervisor_district                    | Supervisor District                    | text          | text          |
| Yes      | series tag     | neighborhoods_analysis_boundaries      | Neighborhoods - Analysis Boundaries    | text          | text          |
| Yes      | series tag     | zipcode                                | Zipcode                                | text          | text          |
```

## Time Field

```ls
Value = permit_creation_date
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = status_date,permit_expiration_date
```

## Data Commands

```ls
series e:i98e-djp9 d:2009-10-19T00:00:00.000Z t:proposed_use="radio & tv stations" t:existing_construction_type=5 t:proposed_construction_type=5 t:permit_number=200910199309 t:tidf_compliance=false t:description="to obtain final inspection for work approved under pa#9822980. all work has been completed. sign has been in place since 1998." t:street_name="South Van Ness" t:supervisor_district=9 t:street_suffix=Ave t:lot=043 t:fire_only_permit=false t:structural_notification=false t:block=3549 t:use_codes=46 t:neighborhoods_analysis_boundaries=Mission t:permit_type_definition="otc alterations permit" t:permit_type=8 t:zipcode=94103 t:proposed_construction_type_description="wood frame (5)" t:voluntary_soft_story_retrofit=false t:street_number=307 t:existing_use="radio & tv stations" t:use_code_description="radio & tv stations" t:status=complete t:existing_construction_type_description="wood frame (5)" m:number_of_existing_stories=3 m:number_of_proposed_stories=3 m:proposed_units=14 m:plansets=0 m:estimated_cost=1 m:existing_units=14 m:revised_cost=1

series e:i98e-djp9 d:2009-01-27T00:00:00.000Z t:proposed_use=office t:existing_construction_type=1 t:proposed_construction_type=1 t:permit_number=200901270869 t:tidf_compliance=false t:description="#700- demolition of partitions  doors  power/tel. data receptacles  ceiling grid + finisheson existing multi tenant flr. constr. of (n) partitions  doors  ceiling  power + tel./data receptacles + fin. mech.  elec.  + sprinkler system mod. under separate pemit" t:street_name=Market t:supervisor_district=6 t:street_suffix=St t:lot=057 t:fire_only_permit=false t:structural_notification=false t:block=3708 t:use_codes=10 t:neighborhoods_analysis_boundaries="Financial District/South Beach" t:permit_type_definition="otc alterations permit" t:permit_type=8 t:zipcode=94105 t:proposed_construction_type_description="constr type 1" t:voluntary_soft_story_retrofit=false t:street_number=555 t:existing_use=office t:use_code_description=office t:status=complete t:existing_construction_type_description="constr type 1" m:number_of_existing_stories=23 m:number_of_proposed_stories=23 m:proposed_units=0 m:plansets=2 m:estimated_cost=50000 m:existing_units=0 m:revised_cost=100000

series e:i98e-djp9 d:1997-04-02T00:00:00.000Z t:proposed_use=apartments t:existing_construction_type=5 t:proposed_construction_type=5 t:permit_number=9705962 t:tidf_compliance=false t:description="remove non bearing walls rev to 9619960 & add scope of work" t:street_name=Lombard t:supervisor_district=3 t:street_suffix=St t:lot=026 t:fire_only_permit=false t:structural_notification=false t:block=0076 t:use_codes=24 t:neighborhoods_analysis_boundaries="North Beach" t:permit_type_definition="otc alterations permit" t:permit_type=8 t:zipcode=94133 t:proposed_construction_type_description="wood frame (5)" t:voluntary_soft_story_retrofit=false t:street_number=571 t:existing_use=apartments t:use_code_description=apartments t:status=expired t:existing_construction_type_description="wood frame (5)" m:number_of_existing_stories=4 m:number_of_proposed_stories=4 m:proposed_units=7 m:plansets=2 m:estimated_cost=2500 m:existing_units=7
```

## Meta Commands

```ls
metric m:unit p:integer l:Unit t:dataTypeName=number

metric m:number_of_existing_stories p:integer l:"Number of Existing Stories" t:dataTypeName=number

metric m:number_of_proposed_stories p:integer l:"Number of Proposed Stories" t:dataTypeName=number

metric m:estimated_cost p:integer l:"Estimated Cost" t:dataTypeName=number

metric m:revised_cost p:integer l:"Revised Cost" t:dataTypeName=number

metric m:existing_units p:integer l:"Existing Units" t:dataTypeName=number

metric m:proposed_units p:long l:"Proposed Units" t:dataTypeName=number

metric m:plansets p:integer l:Plansets t:dataTypeName=number

entity e:i98e-djp9 l:"Building Permits" t:url=https://data.sfgov.org/api/views/i98e-djp9

property e:i98e-djp9 t:meta.view d:2017-09-25T07:25:27.054Z v:averageRating=0 v:name="Building Permits" v:id=i98e-djp9 v:category="Housing and Buildings"

property e:i98e-djp9 t:meta.view.license d:2017-09-25T07:25:27.054Z v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:i98e-djp9 t:meta.view.owner d:2017-09-25T07:25:27.054Z v:displayName=OpenData v:id=dbag-6qd9 v:screenName=OpenData

property e:i98e-djp9 t:meta.view.tableauthor d:2017-09-25T07:25:27.054Z v:displayName=OpenData v:roleName=publisher v:id=dbag-6qd9 v:screenName=OpenData
```

## Top Records

```ls
| permit_number | permit_type | permit_type_definition           | permit_creation_date | block | lot  | street_number | street_number_suffix | street_name    | street_suffix | unit | unit_suffix | description                                                                                                                                                                                                                                                 | status    | status_date         | structural_notification | number_of_existing_stories | number_of_proposed_stories | voluntary_soft_story_retrofit | fire_only_permit | permit_expiration_date | estimated_cost | revised_cost | existing_use        | existing_units | proposed_use        | proposed_units | plansets | tidf_compliance | use_codes | use_code_description | existing_construction_type | existing_construction_type_description | proposed_construction_type | proposed_construction_type_description | supervisor_district | neighborhoods_analysis_boundaries | zipcode | 
| ============= | =========== | ================================ | ==================== | ===== | ==== | ============= | ==================== | ============== | ============= | ==== | =========== | =========================================================================================================================================================================================================================================================== | ========= | =================== | ======================= | ========================== | ========================== | ============================= | ================ | ====================== | ============== | ============ | =================== | ============== | =================== | ============== | ======== | =============== | ========= | ==================== | ========================== | ====================================== | ========================== | ====================================== | =================== | ================================= | ======= | 
| 200910199309  | 8           | otc alterations permit           | 1255910400           | 3549  | 043  | 307           |                      | South Van Ness | Ave           |      |             | to obtain final inspection for work approved under pa#9822980. all work has been completed. sign has been in place since 1998.                                                                                                                              | complete  | 2010-05-27T00:00:00 | false                   | 3                          | 3                          | false                         | false            | 1287014400             | 1              | 1            | radio & tv stations | 14             | radio & tv stations | 14             | 0        | false           | 46        | radio & tv stations  | 5                          | wood frame (5)                         | 5                          | wood frame (5)                         | 9                   | Mission                           | 94103   | 
| 200901270869  | 8           | otc alterations permit           | 1233014400           | 3708  | 057  | 555           |                      | Market         | St            |      |             | #700- demolition of partitions doors power/tel. data receptacles ceiling grid + finisheson existing multi tenant flr. constr. of (n) partitions doors ceiling power + tel./data receptacles + fin. mech. elec. + sprinkler system mod. under separate pemit | complete  | 2009-04-28T00:00:00 | false                   | 23                         | 23                         | false                         | false            | 1264377600             | 50000          | 100000       | office              | 0              | office              | 0              | 2        | false           | 10        | office               | 1                          | constr type 1                          | 1                          | constr type 1                          | 6                   | Financial District/South Beach    | 94105   | 
| 9705962       | 8           | otc alterations permit           | 859939200            | 0076  | 026  | 571           |                      | Lombard        | St            |      |             | remove non bearing walls rev to 9619960 & add scope of work                                                                                                                                                                                                 | expired   | 1997-11-24T00:00:00 | false                   | 4                          | 4                          | false                         | false            | 870480000              | 2500           |              | apartments          | 7              | apartments          | 7              | 2        | false           | 24        | apartments           | 5                          | wood frame (5)                         | 5                          | wood frame (5)                         | 3                   | North Beach                       | 94133   | 
| 0429960       | 2           | new construction wood frame      | 122601600            | 1069  | 042  | 17            |                      | Dicha          | Al            |      |             | new nonbearing drywall partitions plumbing sprinklers elec                                                                                                                                                                                                  | expired   | 1984-03-01T00:00:00 | false                   |                            | 2                          | false                         | false            | 446947200              | 592800         |              |                     |                |                     | 1              | 0        | false           |           |                      |                            |                                        | 5                          | wood frame (5)                         | 2                   | Presidio Heights                  | 94118   | 
| 201510068960  | 8           | otc alterations permit           | 1444089600           | 6729  | 026  | 1             |                      | Sussex         | St            |      |             | reroofing                                                                                                                                                                                                                                                   | complete  | 2016-05-31T00:00:00 | false                   | 2                          | 2                          | false                         | false            | 1475193600             | 18985          | 18985        | 1 family dwelling   | 1              | 1 family dwelling   | 1              | 0        | false           | 27        | 1 family dwelling    | 5                          | wood frame (5)                         | 5                          | wood frame (5)                         | 8                   | Glen Park                         | 94131   | 
| 200307028633  | 3           | additions alterations or repairs | 1057104000           | 0811  | 020  | 250           |                      | Van Ness       | Ave           |      |             | demo of interior partition walls at 1st floor revision to appln #200111263778                                                                                                                                                                               | expired   | 2005-10-04T00:00:00 | false                   | 2                          | 2                          | false                         | false            | 1068854400             | 3000           | 3000         | office              | 0              | office              | 0              | 2        | false           | 10        | office               | 3                          | constr type 3                          | 3                          | constr type 3                          | 6                   | Tenderloin                        | 94102   | 
| 200507097247  | 8           | otc alterations permit           | 1120867200           | 2032  | 023A | 1726          |                      | 18th           | Ave           |      |             | replace 4 windows size for size wood to wood composite not visible from street.                                                                                                                                                                             | expired   | 2010-12-27T00:00:00 | false                   | 2                          | 2                          | false                         | false            | 1131494400             | 5000           | 5000         | 1 family dwelling   | 1              | 1 family dwelling   | 1              | 0        | false           | 27        | 1 family dwelling    | 5                          | wood frame (5)                         | 5                          | wood frame (5)                         | 7                   | Inner Sunset                      | 94122   | 
| 9404271       | 3           | additions alterations or repairs | 763776000            | 3749  | 062  | 303           |                      | 02nd           | St            |      |             | cti-1 grn flr el sp                                                                                                                                                                                                                                         | complete  | 1994-11-01T00:00:00 | false                   | 9                          | 9                          | false                         | false            | 799459200              | 20000          | 29300        | office              | 0              | office              | 0              | 2        | false           | 10        | office               | 1                          | constr type 1                          | 1                          | constr type 1                          | 6                   | Financial District/South Beach    | 94105   | 
| 9807610       | 1           | new construction                 | 893808000            | 4287  | 017  | 1229          |                      | Connecticut    | St            |      |             | erect new warehouse/storage                                                                                                                                                                                                                                 | cancelled | 0020-01-01T00:00:00 | false                   |                            | 1                          | false                         | false            |                        | 100000         |              |                     |                | warehouse           | 0              | 0        | false           | N         |                      | 31-JAN-00                  |                                        |                            |                                        | 10                  | Bayview Hunters Point             | 94107   | 
| 201509217520  | 8           | otc alterations permit           | 1442793600           | 0303  | 001  | 825           |                      | Post           | St            | 0    |             | units 209 &123                                                                                                                                                                                                                                              | complete  | 2015-12-17T00:00:00 | false                   | 3                          | 3                          | false                         | false            | 1473897600             | 18000          | 36000        | apartments          | 112            | apartments          | 112            | 0        | false           | 24        | apartments           | 5                          | wood frame (5)                         | 5                          | wood frame (5)                         | 6                   | Tenderloin                        | 94109   | 
```