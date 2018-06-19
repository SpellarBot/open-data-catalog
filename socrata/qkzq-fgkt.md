# Environmental Control - Asbestos Demolition Permits - 2012 Q3

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/environmental-control-asbestos-demolition-permits-2012-q3-fd338) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/qkzq-fgkt) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/qkzq-fgkt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/qkzq-fgkt/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | qkzq-fgkt |
| Name | Environmental Control - Asbestos Demolition Permits - 2012 Q3 |
| Attribution | Cook County Bureau of Environmental Control |
| Category | Finance & Administration |
| Created | 2012-12-19T03:51:55Z |
| Publication Date | 2014-10-09T21:58:22Z |

## Description

From the Department of Environmental Control, a dataset of asbestos demolition permits for 3Q 2012.

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type     | Render Type   |
| ======== | ============== | ======================== | ======================== | ============= | ============= |
| Yes      | series tag     | demolition_permit_number | Demolition Permit Number | text          | text          |
| No       |                | permit_issue_date        | Permit Issue Date        | text          | text          |
| Yes      | numeric metric | permit_fees              | Permit Fees              | number        | number        |
| Yes      | time           | abatement_start_date     | Abatement Start Date     | calendar_date | calendar_date |
| No       |                | abatement_end_date       | Abatement End Date       | calendar_date | calendar_date |
| Yes      | series tag     | type_of_building         | Type of Building         | text          | text          |
| Yes      | series tag     | demolition_contractor    | Demolition Contractor    | text          | text          |
```

## Time Field

```ls
Value = abatement_start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = permit_issue_date,abatement_end_date
```

## Data Commands

```ls
series e:qkzq-fgkt d:2012-10-17T00:00:00.000Z t:demolition_permit_number=D1201352 t:demolition_contractor="McDonagh Demolition, Inc" t:type_of_building=Resturant m:permit_fees=0

series e:qkzq-fgkt d:2012-10-01T00:00:00.000Z t:demolition_permit_number=D1201190 t:demolition_contractor="J.M. Williams" t:type_of_building=Garage m:permit_fees=300

series e:qkzq-fgkt d:2012-09-24T00:00:00.000Z t:demolition_permit_number=D1201112 t:demolition_contractor="Better Built Lumber & Supply, Inc." t:type_of_building=Garage m:permit_fees=300
```

## Meta Commands

```ls
metric m:permit_fees p:float l:"Permit Fees" t:dataTypeName=number

entity e:qkzq-fgkt l:"Environmental Control - Asbestos Demolition Permits - 2012 Q3" t:attribution="Cook County Bureau of Environmental Control" t:url=https://datacatalog.cookcountyil.gov/api/views/qkzq-fgkt

property e:qkzq-fgkt t:meta.view v:id=qkzq-fgkt v:category="Finance & Administration" v:attributionLink=http://www.cookcountygov.com/portal/server.pt/community/environmental_control/291 v:averageRating=0 v:name="Environmental Control - Asbestos Demolition Permits - 2012 Q3" v:attribution="Cook County Bureau of Environmental Control"

property e:qkzq-fgkt t:meta.view.license v:name="Public Domain"

property e:qkzq-fgkt t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:qkzq-fgkt t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| demolition_permit_number | permit_issue_date | permit_fees | abatement_start_date | abatement_end_date  | type_of_building | demolition_contractor              | 
| ======================== | ================= | =========== | ==================== | =================== | ================ | ================================== | 
| D1201352                 | 16-Oct-12         | 0.00        | 2012-10-17T00:00:00  | 2012-11-09T00:00:00 | Resturant        | McDonagh Demolition, Inc           | 
| D1201190                 | 24-Sep-12         | 300.00      | 2012-10-01T00:00:00  | 2012-11-01T00:00:00 | Garage           | J.M. Williams                      | 
| D1201112                 | 11-Sep-12         | 300.00      | 2012-09-24T00:00:00  | 2012-10-24T00:00:00 | Garage           | Better Built Lumber & Supply, Inc. | 
| D1201316                 | 10-Oct-12         | 300.00      | 2012-11-01T00:00:00  | 2012-11-30T00:00:00 | Garage           | Tri- State Disposal                | 
| D1201397                 | 29-Oct-12         | 300.00      | 2012-11-07T00:00:00  | 2012-12-07T00:00:00 | House            | Bartholet Concrete                 | 
| D1201179                 | 20-Sep-12         | 300.00      | 2012-11-27T00:00:00  | 2012-12-27T00:00:00 | Garage           | Cummings & Sons                    | 
| D1201306                 | 10-Oct-12         | 300.00      | 2012-10-18T00:00:00  | 2012-11-18T00:00:00 | Garage           | Donco Hauling                      | 
| D1201482                 | 13-Nov-12         | 300.00      | 2012-11-21T00:00:00  | 2012-12-21T00:00:00 | Garage           | Tri- State Disposal                | 
| D1201117                 | 12-Sep-12         | 300.00      | 2012-09-17T00:00:00  | 2012-10-17T00:00:00 | Garage           | LandView Excavating Co             | 
| D1201099                 | 04-Sep-12         | 300.00      | 2012-09-17T00:00:00  | 2012-10-17T00:00:00 | Garage           | Archway Custom Homes, Inc.         | 
```