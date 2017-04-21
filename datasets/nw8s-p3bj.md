# Digital Inclusion Organization Inventory

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/digital-inclusion-organization-inventory) |
| Metadata | [Link](https://data.austintexas.gov/api/views/nw8s-p3bj) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/nw8s-p3bj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/nw8s-p3bj/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | nw8s-p3bj |
| Name | Digital Inclusion Organization Inventory |
| Attribution | City of AUstin |
| Category | Neighborhood |
| Tags | computer lab, public access, digital inclusion |
| Created | 2015-08-21T17:03:18Z |
| Publication Date | 2015-08-21T18:34:08Z |

## Description

This is an inventory of public access computer labs in Austin.

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                           | Data Type     | Render Type   |
| ======== | ============== | ============================== | ============================== | ============= | ============= |
| Yes      | series tag     | program                        | Program                        | text          | text          |
| Yes      | series tag     | branch_lab                     | Branch/Lab                     | text          | text          |
| Yes      | series tag     | status                         | Status                         | text          | text          |
| Yes      | numeric metric | of_machines                    | # of Machines                  | number        | number        |
| Yes      | series tag     | on_site_trainer                | On-Site Trainer                | text          | text          |
| Yes      | series tag     | sub_training_programs_offered  | Sub Training Programs Offered  | text          | text          |
| Yes      | series tag     | public_access                  | Public Access?                 | text          | text          |
| Yes      | series tag     | street_address                 | Street Address                 | text          | text          |
| Yes      | series tag     | county                         | County                         | text          | text          |
| Yes      | series tag     | council_district               | Council District               | text          | text          |
| Yes      | series tag     | our_contact                    | Our Contact                    | text          | text          |
| Yes      | series tag     | our_contact_email              | Our Contact Email              | text          | text          |
| Yes      | series tag     | phone                          | Phone                          | text          | text          |
| Yes      | series tag     | hours                          | Hours                          | text          | text          |
| Yes      | series tag     | trainnig_hours                 | Trainnig Hours                 | text          | text          |
| Yes      | series tag     | paid_or_volunteer_trainer      | Paid or Volunteer Trainer      | text          | text          |
| Yes      | series tag     | special_training               | Special Training               | text          | text          |
| Yes      | series tag     | non_english_speaking_languages | Non-English Speaking Languages | text          | text          |
| Yes      | series tag     | disabled_accessibility         | Disabled Accessibility         | text          | text          |
| Yes      | time           | last_updated                   | Last Updated                   | calendar_date | calendar_date |
```

## Time Field

```ls
Value = last_updated
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:nw8s-p3bj d:2015-03-09T00:00:00.000Z t:branch_lab="M-Station - a Foundation Communities Facility" t:phone="(512) 474-6767" t:county=Travis t:status=Updated t:program="Austin Free-Net*" t:on_site_trainer=No t:public_access="Residents Only" t:our_contact="Michael Bass" t:council_district=1 t:our_contact_email=michael.bass@austinfree.net t:street_address="2906 E Martin Luther King Jr Boulevard" m:of_machines=6

series e:nw8s-p3bj d:2015-03-10T00:00:00.000Z t:branch_lab="Oak Springs Villas" t:phone="(512) 928-2015" t:county=Travis t:status=Updated t:program="Austin Free-Net*" t:on_site_trainer=No t:public_access="Residents Only" t:our_contact="Michael Bass" t:council_district=3 t:our_contact_email=michael.bass@austinfree.net t:street_address="3001 Oak Springs Drive" m:of_machines=3

series e:nw8s-p3bj d:2015-03-11T00:00:00.000Z t:branch_lab="Palm Square Community Center" t:phone="(512) 854-4120" t:county=Travis t:status=Updated t:program="Austin Free-Net*" t:on_site_trainer=No t:public_access="Program Members Only" t:hours="M-F: 7-5" t:our_contact="Michael Bass" t:our_contact_email=michael.bass@austinfree.net t:street_address="100 I H 35 Frontage Road" m:of_machines=4
```

## Meta Commands

```ls
metric m:of_machines p:integer l:"# of Machines" t:dataTypeName=number

entity e:nw8s-p3bj l:"Digital Inclusion Organization Inventory" t:attribution="City of AUstin" t:url=https://data.austintexas.gov/api/views/nw8s-p3bj

property e:nw8s-p3bj t:meta.view v:id=nw8s-p3bj v:category=Neighborhood v:averageRating=0 v:name="Digital Inclusion Organization Inventory" v:attribution="City of AUstin"

property e:nw8s-p3bj t:meta.view.license v:name="Public Domain"

property e:nw8s-p3bj t:meta.view.owner v:id=yczp-v4p4 v:screenName="Sharla Chamberlain" v:displayName="Sharla Chamberlain"

property e:nw8s-p3bj t:meta.view.tableauthor v:id=yczp-v4p4 v:screenName="Sharla Chamberlain" v:roleName=editor v:displayName="Sharla Chamberlain"
```

## Top Records

```ls
| program               | branch_lab                                      | status  | of_machines | on_site_trainer     | sub_training_programs_offered                                                                                       | public_access                      | street_address                         | county | council_district | our_contact    | our_contact_email                       | phone          | hours                              | trainnig_hours      | paid_or_volunteer_trainer | special_training                            | non_english_speaking_languages | disabled_accessibility                        | last_updated        | 
| ===================== | =============================================== | ======= | =========== | =================== | =================================================================================================================== | ================================== | ====================================== | ====== | ================ | ============== | ======================================= | ============== | ================================== | =================== | ========================= | =========================================== | ============================== | ============================================= | =================== | 
| Austin Free-Net/PARD  | South Austin Neighborhood Center                | Updated |             | Yes                 |                                                                                                                     | Yes                                | 2508 Durwood                           | Travis | 3                | Michael Bass   | michael.bass@austinfree.net             | (512) 972-6840 | M-Th: 9-5 F: 9-12:00               | M-Th: 9-5 F: 9-noon | Volunteer                 | Resume building, job hunting, social media. | No                             |                                               | 2015-03-01T00:00:00 | 
| Austin Free-Net*      | M-Station - a Foundation Communities Facility   | Updated | 6           | No                  |                                                                                                                     | Residents Only                     | 2906 E Martin Luther King Jr Boulevard | Travis | 1                | Michael Bass   | michael.bass@austinfree.net             | (512) 474-6767 |                                    |                     |                           |                                             |                                |                                               | 2015-03-09T00:00:00 | 
| Austin Free-Net*      | Oak Springs Villas                              | Updated | 3           | No                  |                                                                                                                     | Residents Only                     | 3001 Oak Springs Drive                 | Travis | 3                | Michael Bass   | michael.bass@austinfree.net             | (512) 928-2015 |                                    |                     |                           |                                             |                                |                                               | 2015-03-10T00:00:00 | 
| Austin Free-Net*      | Palm Square Community Center                    | Updated | 4           | No                  |                                                                                                                     | Program Members Only               | 100 I H 35 Frontage Road               | Travis |                  | Michael Bass   | michael.bass@austinfree.net             | (512) 854-4120 | M-F: 7-5                           |                     |                           |                                             |                                |                                               | 2015-03-11T00:00:00 | 
| Austin Free-Net*      | Project Recovery                                | Updated |             | No                  |                                                                                                                     | Residents Only                     | 8402 Cross Park Drirve                 | Travis | 1                | Michael Bass   | michael.bass@austinfree.net             | 521 804 3551   |                                    |                     |                           |                                             |                                |                                               | 2015-03-12T00:00:00 | 
| Skillpoint Alliance   | HACA-Georgian Manor                             | Updated |             |                     | 10 Week Empower Computer Proficiency Program: professional development skills (MS Office, Internet, Email, Outlook) |                                    | 110 Bolles Circle                      | Travis | 4                | Ben Nelson     | bnelson@skillpointalliance.org          | 512 814 3278   |                                    |                     |                           |                                             | No                             |                                               | 2014-12-09T00:00:00 | 
| Skillpoint Alliance   | Mendez Middle School                            | Updated |             |                     | 10 Week Empower Computer Proficiency Program: professional development skills (MS Office, Internet, Email, Outlook) |                                    | 5106 Village Square                    | Travis | 2                | Ben Nelson     | bnelson@skillpointalliance.org          | 514 814 3278   |                                    |                     |                           |                                             | Yes, Spanish                   |                                               | 2014-12-09T00:00:00 | 
| Skillpoint Alliance   | The Henry Flores Learning Center at Meadowbrook | Updated |             |                     | 10 Week Empower Computer Proficiency Program: professional development skills (MS Office, Internet, Email, Outlook) |                                    | 1200 E Rundberg Lane                   | Travis | 4                | Ben Nelson     | bnelson@skillpointalliance.org          | 515 814 3278   |                                    |                     |                           |                                             | No                             |                                               | 2014-12-09T00:00:00 | 
| Goodwill              | Goodwill Community Center                       | Updated | 14          | No                  | Learner Web: Job Readiness Trainer by Request                                                                       | Goodwill Program Participants Only | 1015 Norwood Park Boulevard            | Travis | 4                | Zachary Haines | Zachary.Haines@goodwillcentraltexas.org | 512-637-7502   |                                    |                     |                           | Job finding                                 |                                |                                               | 2014-12-11T00:00:00 | 
| Austin Public Library | Howson Branch                                   | Updated | 8           | no specific trainer |                                                                                                                     | Yes                                | 2500 Exposition Boulevard              | Travis |                  | Sue Soy        | Sue.Soy@austintexas.gov                 | 512 974 8800   | M-Th: 10a-9p; F: 1p-6p; Sa: 10a-5p |                     |                           |                                             |                                | MAGic Software, MAGic Largetype Keyboard JAWS |                     | 
```