# Environmental Control - Asbestos Abatement Permits - 2012 Q3

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/environmental-control-asbestos-abatement-permits-2012-q3-127c2) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/erxw-ipht) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/erxw-ipht/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/erxw-ipht/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | erxw-ipht |
| Name | Environmental Control - Asbestos Abatement Permits - 2012 Q3 |
| Attribution | Cook County Bureau of Environmental Control |
| Category | Finance & Administration |
| Created | 2012-12-19T03:58:38Z |
| Publication Date | 2014-10-09T21:19:16Z |

## Description

From the Department of Environmental Control, a list of Asbestos Abatement Permits for 3Q 2012.

## Columns

```ls
| Included | Schema Type    | Field Name                       | Name                             | Data Type     | Render Type   |
| ======== | ============== | ================================ | ================================ | ============= | ============= |
| Yes      | series tag     | asbestos_abatement_permit_number | Asbestos Abatement Permit Number | text          | text          |
| No       |                | permit_issue_date                | Permit Issue Date                | text          | text          |
| Yes      | numeric metric | inspection_fees                  | Inspection Fees                  | number        | number        |
| Yes      | numeric metric | filing_fees                      | Filing Fees                      | number        | number        |
| Yes      | time           | abatement_start_date             | Abatement Start Date             | calendar_date | calendar_date |
| No       |                | abatement_end_date               | Abatement End Date               | calendar_date | calendar_date |
| Yes      | series tag     | abatement_contractor             | Abatement Contractor             | text          | text          |
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
series e:erxw-ipht d:2012-11-05T00:00:00.000Z t:asbestos_abatement_permit_number=A1201465 t:abatement_contractor="Peak Services LLC" m:filing_fees=200 m:inspection_fees=2000

series e:erxw-ipht d:2012-11-14T00:00:00.000Z t:asbestos_abatement_permit_number=A1201501 t:abatement_contractor="Safe Environmental Corporation" m:filing_fees=200 m:inspection_fees=2000

series e:erxw-ipht d:2012-10-03T00:00:00.000Z t:asbestos_abatement_permit_number=A1201317 t:abatement_contractor="J. P.  General Construction, Inc." m:filing_fees=200 m:inspection_fees=0
```

## Meta Commands

```ls
metric m:inspection_fees p:float l:"Inspection Fees" t:dataTypeName=number

metric m:filing_fees p:float l:"Filing Fees" t:dataTypeName=number

entity e:erxw-ipht l:"Environmental Control - Asbestos Abatement Permits - 2012 Q3" t:attribution="Cook County Bureau of Environmental Control" t:url=https://datacatalog.cookcountyil.gov/api/views/erxw-ipht

property e:erxw-ipht t:meta.view v:id=erxw-ipht v:category="Finance & Administration" v:attributionLink=http://www.cookcountygov.com/portal/server.pt/community/environmental_control/291 v:averageRating=0 v:name="Environmental Control - Asbestos Abatement Permits - 2012 Q3" v:attribution="Cook County Bureau of Environmental Control"

property e:erxw-ipht t:meta.view.license v:name="Public Domain"

property e:erxw-ipht t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:erxw-ipht t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| asbestos_abatement_permit_number | permit_issue_date | inspection_fees | filing_fees | abatement_start_date | abatement_end_date  | abatement_contractor                   | 
| ================================ | ================= | =============== | =========== | ==================== | =================== | ====================================== | 
| A1201465                         | 29-Oct-12         | 2000.00         | 200.00      | 2012-11-05T00:00:00  | 2012-11-09T00:00:00 | Peak Services LLC                      | 
| A1201501                         | 05-Nov-12         | 2000.00         | 200.00      | 2012-11-14T00:00:00  | 2012-11-23T00:00:00 | Safe Environmental Corporation         | 
| A1201317                         | 24-Sep-12         | 0.00            | 200.00      | 2012-10-03T00:00:00  | 2012-10-04T00:00:00 | J. P. General Construction, Inc.       | 
| A1201461                         | 24-Oct-12         | 0.00            | 200.00      | 2012-10-29T00:00:00  | 2012-10-29T00:00:00 | Bain Environmental                     | 
| A1201457                         | 24-Oct-12         | 1248.00         | 200.00      | 2012-11-06T00:00:00  | 2012-11-06T00:00:00 | Celtic Environmental Company           | 
| A1201364                         | 09-Oct-12         | 1390.00         | 200.00      | 2012-10-15T00:00:00  | 2012-10-17T00:00:00 | EHC Industries, Inc.                   | 
| A1201398                         | 15-Oct-12         | 0.00            | 200.00      | 2012-10-23T00:00:00  | 2012-10-23T00:00:00 | American Environmental Solutions, Inc. | 
| A1201507                         | 05-Nov-12         | 140.00          | 200.00      | 2012-11-14T00:00:00  | 2012-11-16T00:00:00 | Tecnica Environmental Services Inc     | 
| A1201267                         | 12-Sep-12         | 50.00           | 200.00      | 2012-09-20T00:00:00  | 2012-09-21T00:00:00 | Superb Environmental Control, Inc.     | 
| A1201384                         | 12-Oct-12         | 40.00           | 200.00      | 2012-10-16T00:00:00  | 2012-10-16T00:00:00 | NES, INC.                              | 
```