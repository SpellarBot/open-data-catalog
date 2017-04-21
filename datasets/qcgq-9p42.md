# 2014 Nonprofit Grant Program

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2014-nonprofit-grant-program) |
| Metadata | [Link](https://data.ct.gov/api/views/qcgq-9p42) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/qcgq-9p42/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/qcgq-9p42/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | qcgq-9p42 |
| Name | 2014 Nonprofit Grant Program |
| Category | Government |
| Tags | nonprofit, grant, opm |
| Created | 2014-06-27T16:56:24Z |
| Publication Date | 2014-06-27T17:10:45Z |

## Description

A list of grants-in-aid to private, nonprofit health and human service organizations pursuant to Sec. 13(a)(1) of Public Act 13-239

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                         | Data Type | Render Type |
| ======== | ============== | ============================ | ============================ | ========= | =========== |
| Yes      | series tag     | contract                     | Contract #                   | text      | text        |
| Yes      | series tag     | name_of_organization         | Name of Organization         | text      | text        |
| No       |                | mailing_address              | Mailing Address              | text      | text        |
| No       |                | address_line_2               | Address Line 2               | text      | text        |
| Yes      | series tag     | zip_code                     | ZIP Code                     | text      | number      |
| Yes      | series tag     | name_of_project              | Name of Project              | text      | text        |
| Yes      | series tag     | project_type                 | Project Type                 | text      | text        |
| Yes      | numeric metric | committee_recommended_amount | Committee Recommended Amount | money     | money       |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = mailing_address,address_line_2
```

## Data Commands

```ls
series e:qcgq-9p42 d:2014-01-01T00:00:00.000Z m:committee_recommended_amount=20000000

series e:qcgq-9p42 d:2014-01-01T00:00:00.000Z t:zip_code=6320 t:contract=14OPM8000DH t:name_of_project="Roof Replacement" t:project_type=Improvement t:name_of_organization="Safe Futures, Inc" m:committee_recommended_amount=43975

series e:qcgq-9p42 d:2014-01-01T00:00:00.000Z t:zip_code=6019 t:contract=14OPM8000BZ t:name_of_project="Boiler/Generator System" t:project_type=Improvement t:name_of_organization="The Arc of the Farmington Valley, Inc" m:committee_recommended_amount=51513
```

## Meta Commands

```ls
metric m:committee_recommended_amount p:integer l:"Committee Recommended Amount" t:dataTypeName=money

entity e:qcgq-9p42 l:"2014 Nonprofit Grant Program" t:url=https://data.ct.gov/api/views/qcgq-9p42

property e:qcgq-9p42 t:meta.view v:id=qcgq-9p42 v:category=Government v:averageRating=0 v:name="2014 Nonprofit Grant Program"

property e:qcgq-9p42 t:meta.view.owner v:id=6ypf-grnx v:screenName="Jamie Gamble" v:displayName="Jamie Gamble"

property e:qcgq-9p42 t:meta.view.tableauthor v:id=6ypf-grnx v:screenName="Jamie Gamble" v:roleName=editor v:displayName="Jamie Gamble"
```

## Top Records

```ls
| contract    | name_of_organization                                                                          | mailing_address      | address_line_2 | zip_code | name_of_project                   | project_type       | committee_recommended_amount | 
| =========== | ============================================================================================= | ==================== | ============== | ======== | ================================= | ================== | ============================ | 
|             |                                                                                               |                      |                |          |                                   |                    | 20000000                     | 
| 14OPM8000DH | Safe Futures, Inc                                                                             | 16 JAY ST            |                | 6320     | Roof Replacement                  | Improvement        | 43975                        | 
| 14OPM8000BZ | The Arc of the Farmington Valley, Inc                                                         | 225 COMMERCE DR      | PO BOX 1099    | 6019     | Boiler/Generator System           | Improvement        | 51513                        | 
| 14OPM8000FL | Child Guidance Center of Southern Connecticut, Inc                                            | 196 GREYROCK PL      |                | 6901     | Security                          | Health & Safety    | 28000                        | 
| 14OPM8000DE | The Bridge Family Center, Inc                                                                 | 1022 FARMINGTON AVE  |                | 6107     | Renovation - counseling rooms     | Renovation         | 270760                       | 
| 14OPM8000FM | Mid-Fairfield Child Guidance Center, Inc. d/b/a Child Guidance Center of Mid-Fairfield County | 100 EAST AVE         |                | 6851     | Vehicle                           | Vehicles/Equipment | 142500                       | 
| 14OPM8000BC | Ability Beyond Disability, Inc                                                                | 4 BERKSHIRE BLVD     |                | 6801     | Safety - Saw Mill                 | Renovation         | 209000                       | 
| 14OPM8000DV | Foodshare, Inc                                                                                | 450 WOODLAND AVE     |                | 6002     | I/T                               | I/T                | 160027                       | 
| 14OPM8000FH | Bridges...A Community Support System, Inc.                                                    | 949 BRIDGEPORT AVE   |                | 6460     | Renovations/Open Door Social Club | Renovation         | 107000                       | 
| 14OPM8000DS | Shelter for the Homeless, Inc.                                                                | 137 HENRY ST STE 205 |                | 6902     | Shelter Improvement               | Improvement        | 153000                       | 
```