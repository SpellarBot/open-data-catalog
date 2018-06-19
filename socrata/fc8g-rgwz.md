# Local Government Efficiency Program Grants: Beginning 2005

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/local-government-efficiency-program-grants-beginning-2005) |
| Metadata | [Link](https://data.ny.gov/api/views/fc8g-rgwz) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/fc8g-rgwz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/fc8g-rgwz/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | fc8g-rgwz |
| Name | Local Government Efficiency Program Grants: Beginning 2005 |
| Attribution | New York State Department of State |
| Category | Government & Finance |
| Tags | local government, shared services |
| Created | 2014-05-30T17:15:33Z |
| Publication Date | 2016-07-12T22:01:26Z |

## Description

This dataset provides applicant and project information for grants given by the NYS Department of State's Division of Local Government Services.  The Division is responsible for assisting local officials in understanding and improving the local government financial health and promoting local government management based upon long-term planning and performance measurement.  The program provides incentive funding directly to local governments to help reduce the cost of local services and increase service efficiencies.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type     | Render Type   |
| ======== | ============== | =================== | =================== | ============= | ============= |
| Yes      | series tag     | lead_applicant      | Lead Applicant      | text          | text          |
| Yes      | series tag     | lead_applicant_type | Lead Applicant Type | text          | text          |
| Yes      | series tag     | project_title       | Project Title       | text          | text          |
| No       |                | fiscal_year         | Fiscal Year         | number        | number        |
| Yes      | numeric metric | final_award         | Final Award         | money         | money         |
| Yes      | series tag     | primary_county      | Primary County      | text          | text          |
| Yes      | series tag     | project_status      | Project Status      | text          | text          |
| Yes      | time           | completion_date     | Completion Date     | calendar_date | calendar_date |
```

## Time Field

```ls
Value = completion_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = fiscal_year
```

## Data Commands

```ls
series e:fc8g-rgwz d:2009-12-14T00:00:00.000Z t:lead_applicant=Southampton t:project_status=Closed t:project_title="Regional Five Eastern Town's Transportation System" t:primary_county=Suffolk t:lead_applicant_type=Town m:final_award=360000

series e:fc8g-rgwz d:2008-01-02T00:00:00.000Z t:lead_applicant=Troy t:project_status=Closed t:project_title="Albany Pool Combined Sewer Overflow Long Term Control Plan Intermunicipal Agreement Foundation" t:primary_county=Rensselaer t:lead_applicant_type=City m:final_award=200000

series e:fc8g-rgwz d:2010-04-07T00:00:00.000Z t:lead_applicant=Ticonderoga t:project_status=Closed t:project_title="Black Point Sewer Operation & Maintenance Program" t:primary_county=Essex t:lead_applicant_type=Town m:final_award=127800
```

## Meta Commands

```ls
metric m:final_award p:double l:"Final Award" d:"Amount awarded" t:dataTypeName=money

entity e:fc8g-rgwz l:"Local Government Efficiency Program Grants:  Beginning 2005" t:attribution="New York State Department of State" t:url=https://data.ny.gov/api/views/fc8g-rgwz

property e:fc8g-rgwz t:meta.view v:id=fc8g-rgwz v:category="Government & Finance" v:attributionLink=http://www.dos.ny.gov/lg/lge/index.html v:averageRating=0 v:name="Local Government Efficiency Program Grants:  Beginning 2005" v:attribution="New York State Department of State"

property e:fc8g-rgwz t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:fc8g-rgwz t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:fc8g-rgwz t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| lead_applicant          | lead_applicant_type | project_title                                                                                                     | fiscal_year | final_award | primary_county | project_status | completion_date     | 
| ======================= | =================== | ================================================================================================================= | =========== | =========== | ============== | ============== | =================== | 
| Southampton             | Town                | Regional Five Eastern Town's Transportation System                                                                | 2005        | 360000.00   | Suffolk        | Closed         | 2009-12-14T00:00:00 | 
| Troy                    | City                | Albany Pool Combined Sewer Overflow Long Term Control Plan Intermunicipal Agreement Foundation                    | 2005        | 200000.00   | Rensselaer     | Closed         | 2008-01-02T00:00:00 | 
| Ticonderoga             | Town                | Black Point Sewer Operation & Maintenance Program                                                                 | 2005        | 127800.00   | Essex          | Closed         | 2010-04-07T00:00:00 | 
| Adams                   | Village             | Town and Village of Adams Shared Municipal Building                                                               | 2005        | 200000.00   | Jefferson      | Closed         | 2007-06-25T00:00:00 | 
| Arkport School District | School District     | The Arkport Central School Joint Bus Garage, Maintenance and Fueling Facility                                     | 2005        | 100000.00   | Steuben        | Closed         | 2007-12-05T00:00:00 | 
| Fort Edward             | Village             | Shared Highways Services Project                                                                                  | 2005        | 23000.00    | Washington     | Closed         | 2009-06-22T00:00:00 | 
| Town of Chester         | Town                | Greater Chester Shared Services Feasibility Study and Implementation Plan                                         | 2005        | 39483.00    | Orange         | Closed         | 2009-06-09T00:00:00 | 
| Newstead                | Town                | Shared Town/Village Municipal Works Facility Feasibility Study                                                    | 2005        | 102510.00   | Erie           | Closed         | 2009-05-13T00:00:00 | 
| Cambridge               | Village             | Feasibility Study and Intermunicipal Agreement for Cambridge/Greenwich Administrator for Planning, Zoning and DPW | 2005        | 35145.00    | Washington     | Closed         | 2009-02-02T00:00:00 | 
| North Elba              | Town                | Lake Placid/North Elba Shared Services Study                                                                      | 2005        | 54724.00    | Essex          | Closed         | 2009-03-19T00:00:00 | 
```