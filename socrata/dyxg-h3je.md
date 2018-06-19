# Ecology Wastewater Operator Professional Growth

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ecology-wastewater-operator-professional-growth) |
| Metadata | [Link](https://data.wa.gov/api/views/dyxg-h3je) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/dyxg-h3je/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/dyxg-h3je/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | dyxg-h3je |
| Name | Ecology Wastewater Operator Professional Growth |
| Attribution | Washington Department of Ecology |
| Category | Natural Resources & Environment |
| Tags | ecology, opcert, operator certification, wastewater, ceu, ceus |
| Created | 2015-12-05T00:33:13Z |
| Publication Date | 2015-12-05T00:51:29Z |

## Description

This is a list of the courses approved by Ecology for use by Washington wastewater treatment plant operators to meet their professional growth obligations.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type     | Render Type   |
| ======== | ============== | =============== | =============== | ============= | ============= |
| Yes      | series tag     | title           | Title           | text          | text          |
| Yes      | series tag     | url             | URL             | url           | url           |
| Yes      | series tag     | course_id       | Course ID       | text          | text          |
| Yes      | numeric metric | ceu_minimum     | CEU Minimum     | number        | number        |
| Yes      | numeric metric | ceu_maximum     | CEU Maximum     | number        | number        |
| Yes      | series tag     | online          | Online          | checkbox      | checkbox      |
| Yes      | series tag     | correspondence  | Correspondence  | checkbox      | checkbox      |
| Yes      | series tag     | training_day    | Training Day    | text          | text          |
| Yes      | time           | review_day      | Review Day      | calendar_date | calendar_date |
| No       |                | expiration_day  | Expiration Day  | calendar_date | calendar_date |
| Yes      | series tag     | submitted_by    | Submitted By    | text          | text          |
| Yes      | series tag     | contact_phone   | Contact Phone   | text          | text          |
| Yes      | series tag     | contact_website | Contact Website | url           | url           |
| Yes      | series tag     | contact_email   | Contact Email   | email         | email         |
| Yes      | series tag     | notes           | Notes           | text          | text          |
```

## Time Field

```ls
Value = review_day
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = expiration_day
```

## Data Commands

```ls
series e:dyxg-h3je d:2014-06-02T00:00:00.000Z t:title="Process Safety Boot Camp" t:correspondence=false t:contact_phone=1-800-242-4363 t:submitted_by="American Institute of Chemical Eng." t:training_day=Various t:course_id=ECYS14-908 t:online=false m:ceu_maximum=3.2 m:ceu_minimum=3.2

series e:dyxg-h3je d:2010-03-01T00:00:00.000Z t:title="Confined Space Entry Essentials" t:correspondence=false t:contact_phone=1-800-765-9055 t:submitted_by=OXARC t:training_day=Various t:course_id=ECYS10-55 t:online=false m:ceu_maximum=0.3 m:ceu_minimum=0.3

series e:dyxg-h3je d:2010-03-01T00:00:00.000Z t:title="Chlorine Safety Awareness" t:correspondence=false t:contact_phone=1-800-765-9055 t:submitted_by=OXARC t:training_day=Various t:course_id=ECYS10-56 t:online=false m:ceu_maximum=0.2 m:ceu_minimum=0.2
```

## Meta Commands

```ls
metric m:ceu_minimum p:float l:"CEU Minimum" t:dataTypeName=number

metric m:ceu_maximum p:float l:"CEU Maximum" t:dataTypeName=number

entity e:dyxg-h3je l:"Ecology Wastewater Operator Professional Growth" t:attribution="Washington Department of Ecology" t:url=https://data.wa.gov/api/views/dyxg-h3je

property e:dyxg-h3je t:meta.view v:id=dyxg-h3je v:category="Natural Resources & Environment" v:attributionLink=http://www.ecy.wa.gov/programs/wq/wastewater/op_cert/index.html v:averageRating=0 v:name="Ecology Wastewater Operator Professional Growth" v:attribution="Washington Department of Ecology"

property e:dyxg-h3je t:meta.view.owner v:id=23xe-caxx v:profileImageUrlMedium=/api/users/23xe-caxx/profile_images/THUMB v:profileImageUrlLarge=/api/users/23xe-caxx/profile_images/LARGE v:screenName="Nat Kale" v:profileImageUrlSmall=/api/users/23xe-caxx/profile_images/TINY v:displayName="Nat Kale"

property e:dyxg-h3je t:meta.view.tableauthor v:id=23xe-caxx v:profileImageUrlMedium=/api/users/23xe-caxx/profile_images/THUMB v:profileImageUrlLarge=/api/users/23xe-caxx/profile_images/LARGE v:screenName="Nat Kale" v:profileImageUrlSmall=/api/users/23xe-caxx/profile_images/TINY v:roleName=viewer v:displayName="Nat Kale"
```

## Top Records

```ls
| title                                                                         | url          | course_id  | ceu_minimum | ceu_maximum | online | correspondence | training_day | review_day          | expiration_day      | submitted_by                        | contact_phone  | contact_website | contact_email | notes | 
| ============================================================================= | ============ | ========== | =========== | =========== | ====== | ============== | ============ | =================== | =================== | =================================== | ============== | =============== | ============= | ===== | 
| Process Safety Boot Camp                                                      | [null, null] | ECYS14-908 | 3.2         | 3.2         | false  | false          | Various      | 2014-06-02T00:00:00 | 2017-06-02T00:00:00 | American Institute of Chemical Eng. | 1-800-242-4363 | [null, null]    |               |       | 
| Confined Space Entry Essentials                                               | [null, null] | ECYS10-55  | 0.3         | 0.3         | false  | false          | Various      | 2010-03-01T00:00:00 | 2013-03-01T00:00:00 | OXARC                               | 1-800-765-9055 | [null, null]    |               |       | 
| Chlorine Safety Awareness                                                     | [null, null] | ECYS10-56  | 0.2         | 0.2         | false  | false          | Various      | 2010-03-01T00:00:00 | 2013-03-01T00:00:00 | OXARC                               | 1-800-765-9055 | [null, null]    |               |       | 
| Lockout/Tagout                                                                | [null, null] | ECYS10-54  | 0.1         | 0.1         | false  | false          | Various      | 2010-03-01T00:00:00 | 2013-03-01T00:00:00 | OXARC                               | 1-800-765-9055 | [null, null]    |               |       | 
| Excel - Beyond the Basics                                                     | [null, null] | ECYS11-224 | 0.6         | 0.6         | false  | false          | Various      | 2011-09-23T00:00:00 | 2014-09-23T00:00:00 | Fred Pryor Seminars                 | 1-800-780-8476 | [null, null]    |               |       | 
| Excel Basics                                                                  | [null, null] | ECYS11-223 | 0.6         | 0.6         | false  | false          | Various      | 2011-09-23T00:00:00 | 2014-09-23T00:00:00 | Fred Pryor Seminars                 | 1-800-780-8476 | [null, null]    |               |       | 
| Free Preparedness Tools & Resources for Drinking Water & Wastewater Utilities | [null, null] | ECYS14-888 | 0.1         | 0.1         | false  | false          | 5/6/2014     | 2014-05-06T00:00:00 | 2017-05-06T00:00:00 | US EPA                              | 202-564-3797   | [null, null]    |               |       | 
| WASWD 2014 Spring Conference & Trade Show                                     | [null, null] | ECYS14-970 | 0.1         | 0.6         | false  | false          | 4/9-11/2014  | 2014-10-10T00:00:00 | 2014-04-12T00:00:00 | WA Assoc. of Sewer & Water Dist.    | 206-246-1299   | [null, null]    |               |       | 
| WASWD 2015 Spring Conference & Trade Show                                     | [null, null] | ECY15-1018 | 0.1         | 0.6         | false  | false          | 4/15-17/2015 | 2015-03-27T00:00:00 | 2015-04-18T00:00:00 | WA Assoc. of Sewer & Water Dist.    | 206-246-1299   | [null, null]    |               |       | 
| WASWD 2014 Fall Conference & Trade Show                                       | [null, null] | ECYS14-969 | 0.1         | 0.6         | false  | false          | 9/17-19/2014 | 2014-10-09T00:00:00 | 2014-09-20T00:00:00 | WA Assoc. of Sewer & Water Dist.    | 206-246-1299   | [null, null]    |               |       | 
```