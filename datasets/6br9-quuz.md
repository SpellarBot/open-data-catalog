# Ordinance Violations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ordinance-violations-buildings) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/6br9-quuz) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/6br9-quuz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/6br9-quuz/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | 6br9-quuz |
| Name | Ordinance Violations |
| Attribution | City of Chicago |
| Category | Administration & Finance |
| Tags | ordinance, ordinance violations, buildings, violations, administrative hearings |
| Created | 2015-01-16T17:42:15Z |
| Publication Date | 2015-02-10T19:14:59Z |

## Description

List of ordinance violations filed with the Department of Administrative Hearings. This data set reflects violations brought before the Chicago Department of Administrative Hearings.  It does not reflect violations brought before the Circuit Court of Cook County. Each row of data represents a unique violation. Multiple violations may be associated with a single case. The most recent status of the case is shown in the dataset and is updated daily. Hearing date corresponds to the date of the most recent hearing. Each case often consists of multiple hearings and may encounter continuances due to various circumstances before a final disposition is rendered. The case disposition, date of the disposition, and any applicable fines and administrative costs are listed when the case is fully completed. The latest hearing status or disposition reflects the condition of the property at that time and may not reflect the current condition of the property. When multiple respondents are cited, each respondent is separated by a pipe ("|") character. Respondents sometimes are added to cases for technical legal reasons so are not necessarily the parties believed to have committed the violations. This dataset currently lists violations issued by the Department of Buildings. Additional ordinance violations will be added over time.  Therefore, it is advisable to use the department-specific filtered view listed under the More Views button for purposes that require only one department's violations.

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type     | Render Type   |
| ======== | ============== | ===================== | ===================== | ============= | ============= |
| No       |                | id                    | ID                    | text          | text          |
| Yes      | series tag     | docket_number         | DOCKET NUMBER         | text          | text          |
| Yes      | series tag     | nov_number            | NOV NUMBER            | text          | text          |
| No       |                | address               | ADDRESS               | text          | text          |
| Yes      | series tag     | street_number         | STREET NUMBER         | text          | number        |
| Yes      | series tag     | street_direction      | STREET DIRECTION      | text          | text          |
| Yes      | series tag     | street_name           | STREET NAME           | text          | text          |
| Yes      | series tag     | street_type           | STREET TYPE           | text          | text          |
| Yes      | series tag     | ward                  | WARD                  | text          | number        |
| Yes      | series tag     | issuing_department    | ISSUING DEPARTMENT    | text          | text          |
| No       |                | hearing_date          | HEARING DATE          | calendar_date | calendar_date |
| Yes      | series tag     | case_disposition      | CASE DISPOSITION      | text          | text          |
| Yes      | numeric metric | imposed_fine          | IMPOSED FINE          | number        | number        |
| Yes      | numeric metric | admin_costs           | ADMIN COSTS           | number        | number        |
| No       |                | last_modified_date    | LAST MODIFIED DATE    | calendar_date | calendar_date |
| Yes      | time           | violation_date        | VIOLATION DATE        | calendar_date | calendar_date |
| Yes      | series tag     | violation_code        | VIOLATION CODE        | text          | text          |
| Yes      | series tag     | violation_description | VIOLATION DESCRIPTION | text          | text          |
| Yes      | series tag     | respondents           | RESPONDENTS           | text          | text          |
| No       |                | latitude              | LATITUDE              | number        | number        |
| No       |                | longitude             | LONGITUDE             | number        | number        |
```

## Time Field

```ls
Value = violation_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = id,address,last_modified_date,hearing_date,latitude,longitude
```

## Data Commands

```ls
series e:6br9-quuz d:2016-07-29T09:00:00.000Z t:respondents="BERNARD AVELLO | JOSEPH AVELLO" t:nov_number=16CO495175 t:docket_number=16BT05606A t:violation_code=138086 t:ward=26 t:street_name=OHIO t:issuing_department=Buildings t:street_direction=W t:case_disposition=Continuance t:street_number=2355 t:violation_description="Elevate wood, lumber or other material 18 inches above ground to eliminate rat harboring places or remove from premises. (7-28-720)" t:street_type=ST m:imposed_fine=0 m:admin_costs=0

series e:6br9-quuz d:2012-09-26T09:00:00.000Z t:respondents="MARIA MATA | PEDRO MATA" t:nov_number=12TO347680 t:docket_number=12BT04450A t:violation_code=002011 t:ward=22 t:street_name="ST LOUIS" t:issuing_department=Buildings t:street_direction=S t:case_disposition=Liable t:street_number=3059 t:violation_description="Submit plans prepared, signed, and sealed by a licensed architect or registered structural engineer for approval and obtain permit. (13-32-010, 13-32-040, 13-40-010, 13-40-020)" t:street_type=AVE m:imposed_fine=1000 m:admin_costs=75

series e:6br9-quuz d:2010-09-17T14:56:00.000Z t:respondents="PRODIGY DEVELOPMENT, LLC C/O JOHN BOLAND" t:nov_number=10SO272670 t:docket_number=10BS07350A t:violation_code=070024 t:ward=17 t:street_name=78TH t:issuing_department=Buildings t:street_direction=W t:case_disposition=Continuance t:street_number=1647 t:violation_description="Repair or replace defective or missing members of porch system. (13-196-570)" t:street_type=ST m:imposed_fine=2500 m:admin_costs=0
```

## Meta Commands

```ls
metric m:imposed_fine p:integer l:"IMPOSED FINE" d:"Imposed fine based on the case disposition." t:dataTypeName=number

metric m:admin_costs p:integer l:"ADMIN COSTS" d:"Administrative costs associated with the case disposition." t:dataTypeName=number

entity e:6br9-quuz l:"Ordinance Violations" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/6br9-quuz

property e:6br9-quuz t:meta.view v:id=6br9-quuz v:category="Administration & Finance" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Ordinance Violations" v:attribution="City of Chicago"

property e:6br9-quuz t:meta.view.license v:name="Public Domain"

property e:6br9-quuz t:meta.view.owner v:id=vewm-vupz v:screenName="Jonathan Levy" v:displayName="Jonathan Levy"

property e:6br9-quuz t:meta.view.tableauthor v:id=vewm-vupz v:screenName="Jonathan Levy" v:roleName=administrator v:displayName="Jonathan Levy"
```

## Top Records

```ls
| id                                       | docket_number | nov_number | address             | street_number | street_direction | street_name | street_type | ward | issuing_department | hearing_date        | case_disposition | imposed_fine | admin_costs | last_modified_date  | violation_date      | violation_code | violation_description                                                                                                                                                                                                               | respondents                                                                                                                   | latitude     | longitude     | 
| ======================================== | ============= | ========== | =================== | ============= | ================ | =========== | =========== | ==== | ================== | =================== | ================ | ============ | =========== | =================== | =================== | ============== | =================================================================================================================================================================================================================================== | ============================================================================================================================= | ============ | ============= | 
| 6343fbcb328f9d8be791e67fbe2b9993c65883b0 | 16BT05606A    | 16CO495175 | 2355 W OHIO ST      | 2355          | W                | OHIO        | ST          | 26   | Buildings          | 2017-08-16T00:00:00 | Continuance      | 0            | 0           | 2017-03-15T11:23:39 | 2016-07-29T09:00:00 | 138086         | Elevate wood, lumber or other material 18 inches above ground to eliminate rat harboring places or remove from premises. (7-28-720)                                                                                                 | BERNARD AVELLO | JOSEPH AVELLO                                                                                                | 41.892002257 | -87.686506045 | 
| 965ad2fd6e8f961798c5bacefb2e209752bd25ad | 12BT04450A    | 12TO347680 | 3059 S ST LOUIS AVE | 3059          | S                | ST LOUIS    | AVE         | 22   | Buildings          | 2013-07-24T00:00:00 | Liable           | 1000         | 75          | 2013-09-12T10:15:31 | 2012-09-26T09:00:00 | 002011         | Submit plans prepared, signed, and sealed by a licensed architect or registered structural engineer for approval and obtain permit. (13-32-010, 13-32-040, 13-40-010, 13-40-020)                                                    | MARIA MATA | PEDRO MATA                                                                                                       | 41.837218587 | -87.712010032 | 
| aee0da696087cb466af545c91aed47b22ab06b60 | 10BS07350A    | 10SO272670 | 1647 W 78TH ST      | 1647          | W                | 78TH        | ST          | 17   | Buildings          | 2014-05-30T00:00:00 | Continuance      | 2500         | 0           | 2014-06-13T15:19:24 | 2010-09-17T14:56:00 | 070024         | Repair or replace defective or missing members of porch system. (13-196-570)                                                                                                                                                        | PRODIGY DEVELOPMENT, LLC C/O JOHN BOLAND                                                                                      | 41.752040532 | -87.665342972 | 
| 0080068c9a238801e1b3c261abee7080b61a39d7 | 09BS06589A    | 09SO212941 | 2649 W 72ND ST      | 2649          | W                | 72ND        | ST          | 18   | Buildings          | 2010-06-02T00:00:00 | Not Liable       | 0            | 0           | 2010-06-02T09:33:03 | 2009-04-29T09:00:00 | 220029         | Remove exposed wiring. (18-27-300.4)                                                                                                                                                                                                | LAVEDA POWELL AKA LAVEDA R. GEORGE                                                                                            | 41.762651532 | -87.690044968 | 
| ea5e070d934f04e4ae9c7c566210ad386a44a79c | 08BN00099A    | 08F0148696 | 911 N HAMLIN AVE    | 911           | N                | HAMLIN      | AVE         | 27   | Buildings          | 2008-03-10T00:00:00 | Liable           | 400          | 75          | 2008-04-22T08:44:35 | 2007-11-07T09:00:00 | 196029         | Post name, address, and telephone of owner, owner's agent for managing, controlling or collecting rents, and any other person managing or controlling building conspicuously where accessible or visible to public way. (13-12-030) | MARIA SZUPERNAK                                                                                                               | 41.897613961 | -87.721117568 | 
| 3c8f5e1079f972d97dde635417e9896c3d3dc2ef | 12BT03873A    | 12NO344833 | 3227 N KENMORE AVE  | 3227          | N                | KENMORE     | AVE         | 44   | Buildings          | 2013-06-24T00:00:00 | Liable           | 500          | 75          | 2013-06-24T09:25:42 | 2012-08-24T12:12:00 | 104035         | Repair or replace defective window frame. (13-196-550 B, F)                                                                                                                                                                         | DAVID ROBERTS                                                                                                                 | 41.940725558 | -87.655201182 | 
| 3140adcc43c278b0cabad9e71bbba676df81de16 | 14BT05050A    | 14CO416005 | 2022 W 51ST ST      | 2022          | W                | 51ST        | ST          | 15   | Buildings          | 2015-06-05T00:00:00 | Liable           | 200          | 75          | 2015-06-09T11:22:44 | 2014-08-11T14:02:00 | 131026         | Repair or replace defective screen. (13-196-560 B)                                                                                                                                                                                  | CELESTION SANCHEZ | MARIA SANCHEZ                                                                                             | 41.801329264 | -87.675572733 | 
| 81123659543f4d090b89b2532cf70778addac79a | 08BS01503A    | 08S0149806 | 448 W NORMAL PKWY   | 448           | W                | NORMAL      | PKWY        | 6    | Buildings          | 2008-05-30T00:00:00 | Non-Suit         | 0            | 0           | 2008-05-30T12:31:04 | 2007-10-17T09:00:00 | 192019         | Notify Building Dept of proposed use of vacant and unoccupied space.                                                                                                                                                                | JOSEPH D DRIVER                                                                                                               | 41.7715322   | -87.63680052  | 
| 736d641d51cb6f6f25e24dfede9022e68db02d28 | 09BS07643A    | 09SO217571 | 7802 S ESSEX AVE    | 7802          | S                | ESSEX       | AVE         | 7    | Buildings          | 2009-10-14T00:00:00 | Default          | 6000         | 75          | 2009-10-14T14:23:42 | 2008-11-04T09:00:00 | 105055         | Install in dwelling unit entrance door viewing device. (13-164-020 I, 13-164-030)                                                                                                                                                   | THE ESTATE OF STEPHAN R BANKS | THE ESTATE OF STEPHAN R BANKS C/O VERNA BANKS | THE ESTATE OF STEPHEN R BANKS C/O VERNA BANKS | 41.753429091 | -87.563984964 | 
| 146e58ac873626008984b72c9b56137581769996 | 11BS05000A    | 11NO299141 | 4705 W SCHUBERT AVE | 4705          | W                | SCHUBERT    | AVE         | 31   | Buildings          | 2011-12-14T00:00:00 | Liable           | 200          | 75          | 2011-12-14T09:46:31 | 2011-05-31T15:00:00 | 070014         | Repair or replace defective or missing members of exterior stair system. (13-196-570)                                                                                                                                               | JUAN DELGADO | MARGARITA DELGADO                                                                                              | 41.929431804 | -87.744339421 | 
```