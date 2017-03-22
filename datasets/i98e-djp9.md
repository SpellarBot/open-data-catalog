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
| Rows Updated | 2017-03-20T12:47:26Z |

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
series e:i98e-djp9 d:1964-08-27T00:00:00.000Z t:permit_type=3 t:fire_only_permit=false t:neighborhoods_analysis_boundaries="Inner Richmond" t:use_code_description=office t:status=cancelled t:tidf_compliance=false t:zipcode=94118 t:street_suffix=Ave t:street_name=05th t:block=1548 t:voluntary_soft_story_retrofit=false t:proposed_use=office t:supervisor_district=1 t:structural_notification=false t:existing_use=office t:use_codes=10 t:permit_number=0304329 t:description=horizontal t:lot=014 t:street_number=553 t:permit_type_definition="additions alterations or repairs" m:plansets=2 m:revised_cost=15000 m:estimated_cost=100 m:number_of_existing_stories=999 m:proposed_units=9999 m:number_of_proposed_stories=999

series e:i98e-djp9 d:1966-07-08T00:00:00.000Z t:permit_type=4 t:fire_only_permit=false t:neighborhoods_analysis_boundaries="Pacific Heights" t:use_code_description="not applicable" t:status=cancelled t:tidf_compliance=false t:street_name="Van Ness" t:street_suffix=Ave t:zipcode=94109 t:block=0623 t:voluntary_soft_story_retrofit=false t:supervisor_district=2 t:structural_notification=false t:existing_use="not applicable" t:use_codes=00 t:permit_number=0332010 t:lot=002 t:street_number=1701 t:permit_type_definition=sign-errect m:unit=0 m:plansets=0 m:estimated_cost=1 m:number_of_existing_stories=6

series e:i98e-djp9 d:1966-12-02T00:00:00.000Z t:permit_type=4 t:fire_only_permit=false t:neighborhoods_analysis_boundaries="Pacific Heights" t:use_code_description="not applicable" t:status=cancelled t:tidf_compliance=false t:street_name="Van Ness" t:street_suffix=Ave t:zipcode=94109 t:block=0623 t:voluntary_soft_story_retrofit=false t:supervisor_district=2 t:structural_notification=false t:existing_use="not applicable" t:use_codes=00 t:permit_number=0337505 t:lot=002 t:street_number=1701 t:permit_type_definition=sign-errect m:plansets=0 m:estimated_cost=1 m:number_of_existing_stories=4
```

## Meta Commands

```ls
metric m:unit p:integer l:Unit t:dataTypeName=number

metric m:number_of_existing_stories p:integer l:"Number of Existing Stories" t:dataTypeName=number

metric m:number_of_proposed_stories p:integer l:"Number of Proposed Stories" t:dataTypeName=number

metric m:estimated_cost p:integer l:"Estimated Cost" t:dataTypeName=number

metric m:revised_cost p:double l:"Revised Cost" t:dataTypeName=number

metric m:existing_units p:integer l:"Existing Units" t:dataTypeName=number

metric m:proposed_units p:long l:"Proposed Units" t:dataTypeName=number

metric m:plansets p:integer l:Plansets t:dataTypeName=number

entity e:i98e-djp9 l:"Building Permits" t:url=https://data.sfgov.org/api/views/i98e-djp9

property e:i98e-djp9 t:meta.view v:id=i98e-djp9 v:category="Housing and Buildings" v:averageRating=0 v:name="Building Permits"

property e:i98e-djp9 t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:i98e-djp9 t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:i98e-djp9 t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```