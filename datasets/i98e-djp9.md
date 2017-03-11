# Building Permits

## Dataset

* [Dataset URL](https://data.sfgov.org/api/views/i98e-djp9/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/building-permits-058f4)
* [Metadata URL](https://data.sfgov.org/api/views/i98e-djp9)
* Id = i98e-djp9
* Name = Building Permits
* Category = Housing and Buildings
* Created = 2016-04-21T02:30:56Z
* Publication Date = 2016-10-12T17:08:54Z
* Rows Updated = 2017-03-06T11:57:22Z

## Description

This data set pertains to all types of structural permits. Data includes details on application/permit numbers, job addresses, supervisorial districts, and the current status of the applications. Data is uploaded weekly by DBI. Users can access permit information online through DBI?s Permit Tracking System which is 24/7 at www.sfdbi.org/dbipts.

## Columns

```ls
| Name                                   | Field Name                             | Data Type     | Render Type   | Schema Type    | Included | 
| ====================================== | ====================================== | ============= | ============= | ============== | ======== | 
| Permit Number                          | permit_number                          | text          | text          | series tag     | Yes      | 
| Permit Type                            | permit_type                            | number        | number        | numeric metric | Yes      | 
| Permit Type Definition                 | permit_type_definition                 | text          | text          | series tag     | Yes      | 
| Permit Creation Date                   | permit_creation_date                   | date          | date          | time           | Yes      | 
| Block                                  | block                                  | text          | text          | series tag     | Yes      | 
| Lot                                    | lot                                    | text          | text          | series tag     | Yes      | 
| Street Number                          | street_number                          | text          | text          | series tag     | Yes      | 
| Street Number Suffix                   | street_number_suffix                   | text          | text          | series tag     | Yes      | 
| Street Name                            | street_name                            | text          | text          | series tag     | Yes      | 
| Street Suffix                          | street_suffix                          | text          | text          | series tag     | Yes      | 
| Unit                                   | unit                                   | number        | text          | numeric metric | Yes      | 
| Unit Suffix                            | unit_suffix                            | text          | text          | series tag     | Yes      | 
| Description                            | description                            | text          | text          | series tag     | Yes      | 
| Status                                 | status                                 | text          | text          | series tag     | Yes      | 
| Status Date                            | status_date                            | calendar_date | calendar_date |                | No       | 
| Structural Notification                | structural_notification                | checkbox      | checkbox      | series tag     | Yes      | 
| Number of Existing Stories             | number_of_existing_stories             | number        | number        | numeric metric | Yes      | 
| Number of Proposed Stories             | number_of_proposed_stories             | number        | number        | numeric metric | Yes      | 
| Voluntary Soft-Story Retrofit          | voluntary_soft_story_retrofit          | checkbox      | checkbox      | series tag     | Yes      | 
| Fire Only Permit                       | fire_only_permit                       | checkbox      | checkbox      | series tag     | Yes      | 
| Permit Expiration Date                 | permit_expiration_date                 | date          | date          |                | No       | 
| Estimated Cost                         | estimated_cost                         | number        | number        | numeric metric | Yes      | 
| Revised Cost                           | revised_cost                           | number        | number        | numeric metric | Yes      | 
| Existing Use                           | existing_use                           | text          | text          | series tag     | Yes      | 
| Existing Units                         | existing_units                         | number        | number        | numeric metric | Yes      | 
| Proposed Use                           | proposed_use                           | text          | text          | series tag     | Yes      | 
| Proposed Units                         | proposed_units                         | number        | number        | numeric metric | Yes      | 
| Plansets                               | plansets                               | number        | number        | numeric metric | Yes      | 
| TIDF Compliance                        | tidf_compliance                        | checkbox      | checkbox      | series tag     | Yes      | 
| Use Codes                              | use_codes                              | number        | text          | numeric metric | Yes      | 
| Use Code Description                   | use_code_description                   | text          | text          | series tag     | Yes      | 
| Existing Construction Type             | existing_construction_type             | text          | text          | series tag     | Yes      | 
| Existing Construction Type Description | existing_construction_type_description | text          | text          | series tag     | Yes      | 
| Proposed Construction Type             | proposed_construction_type             | text          | text          | series tag     | Yes      | 
| Proposed Construction Type Description | proposed_construction_type_description | text          | text          | series tag     | Yes      | 
| Supervisor District                    | supervisor_district                    | text          | text          | series tag     | Yes      | 
| Neighborhoods - Analysis Boundaries    | neighborhoods_analysis_boundaries      | text          | text          | series tag     | Yes      | 
| Zipcode                                | zipcode                                | text          | text          | series tag     | Yes      | 
```

## Time Field

```ls
Value = permit_creation_date
Format & Zone = seconds
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = permit_expiration_date,status_date
Annotation Fields = 
```

## Data Commands

```ls
series e:i98e-djp9 d:1964-08-27T00:00:00.000Z t:fire_only_permit=false t:neighborhoods_analysis_boundaries="Inner Richmond" t:use_code_description=office t:status=cancelled t:tidf_compliance=false t:zipcode=94118 t:street_name=05th t:street_suffix=Ave t:block=1548 t:voluntary_soft_story_retrofit=false t:proposed_use=office t:supervisor_district=1 t:structural_notification=false t:existing_use=office t:permit_number=0304329 t:description=horizontal t:lot=014 t:street_number=553 t:permit_type_definition="additions alterations or repairs" m:permit_type=3 m:use_codes=10 m:plansets=2 m:revised_cost=15000 m:estimated_cost=100 m:number_of_existing_stories=999 m:proposed_units=9999 m:number_of_proposed_stories=999

series e:i98e-djp9 d:1966-07-08T00:00:00.000Z t:fire_only_permit=false t:neighborhoods_analysis_boundaries="Pacific Heights" t:use_code_description="not applicable" t:status=cancelled t:tidf_compliance=false t:street_name="Van Ness" t:street_suffix=Ave t:zipcode=94109 t:block=0623 t:voluntary_soft_story_retrofit=false t:supervisor_district=2 t:structural_notification=false t:existing_use="not applicable" t:permit_number=0332010 t:lot=002 t:street_number=1701 t:permit_type_definition=sign-errect m:permit_type=4 m:unit=0 m:use_codes=0 m:plansets=0 m:estimated_cost=1 m:number_of_existing_stories=6

series e:i98e-djp9 d:1966-12-02T00:00:00.000Z t:fire_only_permit=false t:neighborhoods_analysis_boundaries="Pacific Heights" t:use_code_description="not applicable" t:status=cancelled t:tidf_compliance=false t:street_name="Van Ness" t:street_suffix=Ave t:zipcode=94109 t:block=0623 t:voluntary_soft_story_retrofit=false t:supervisor_district=2 t:structural_notification=false t:existing_use="not applicable" t:permit_number=0337505 t:lot=002 t:street_number=1701 t:permit_type_definition=sign-errect m:permit_type=4 m:use_codes=0 m:plansets=0 m:estimated_cost=1 m:number_of_existing_stories=4
```

## Meta Commands

```ls
metric m:permit_type p:integer l:"Permit Type" t:dataTypeName=number

metric m:unit p:integer l:Unit t:dataTypeName=number

metric m:number_of_existing_stories p:integer l:"Number of Existing Stories" t:dataTypeName=number

metric m:number_of_proposed_stories p:integer l:"Number of Proposed Stories" t:dataTypeName=number

metric m:estimated_cost p:integer l:"Estimated Cost" t:dataTypeName=number

metric m:revised_cost p:integer l:"Revised Cost" t:dataTypeName=number

metric m:existing_units p:integer l:"Existing Units" t:dataTypeName=number

metric m:proposed_units p:long l:"Proposed Units" t:dataTypeName=number

metric m:plansets p:integer l:Plansets t:dataTypeName=number

metric m:use_codes l:"Use Codes" t:dataTypeName=number

entity e:i98e-djp9 l:"Building Permits" t:url=https://data.sfgov.org/api/views/i98e-djp9

property e:i98e-djp9 t:meta.view d:2017-03-07T18:44:37.880Z v:id=i98e-djp9 v:category="Housing and Buildings" v:averageRating=0 v:name="Building Permits"

property e:i98e-djp9 t:meta.view.license d:2017-03-07T18:44:37.880Z v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:i98e-djp9 t:meta.view.owner d:2017-03-07T18:44:37.880Z v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData

property e:i98e-djp9 t:meta.view.tableauthor d:2017-03-07T18:44:37.880Z v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```