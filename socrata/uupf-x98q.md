# Business Licenses - Current Active

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://data.cityofchicago.org/Community-Economic-Development/Business-Licenses-Current-Active/uupf-x98q/about) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/uupf-x98q) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/uupf-x98q/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/uupf-x98q/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | uupf-x98q |
| Name | Business Licenses - Current Active |
| Attribution | City of Chicago |
| Category | Community & Economic Development |
| Tags | business, licenses, current |
| Created | 2011-12-15T20:50:49Z |
| Publication Date | 2016-08-30T22:01:35Z |

## Description

This dataset contains all current and active business licenses issued by the Department of Business Affairs and Consumer Protection.  This dataset contains a large number of records /rows of data and may not be viewed in full in Microsoft Excel.  Therefore, when downloading the file, select CSV from the Export menu.  Open the file in an ASCII text editor, such as Notepad or Wordpad, to view and search.  

 
Data fields requiring description are detailed below. 

APPLICATION TYPE:  'ISSUE' is the record associated with the initial license application.  'RENEW' is a subsequent renewal record.  All renewal records are created with a term start date and term expiration date.  'C_LOC' is a change of location record.  It means the business moved.   'C_CAPA' is a change of capacity record.  Only a few license types my file this type of application.  'C_EXPA' only applies to businesses that have liquor licenses.  It means the business location expanded.

LICENSE STATUS: 'AAI' means the license was issued. 

Business license owners may be accessed at:  http://data.cityofchicago.org/Community-Economic-Development/Business-Owners/ezma-pppn
To identify the owner of a business, you will need the account number or legal name.

 
Data Owner: Business Affairs and Consumer Protection 
 
Time Period: Current 
 
Frequency: Data is updated daily

## Columns

```ls
| Included | Schema Type | Field Name                        | Name                              | Data Type     | Render Type   |
| ======== | =========== | ================================= | ================================= | ============= | ============= |
| No       |             | id                                | ID                                | text          | text          |
| Yes      | series tag  | license_id                        | LICENSE ID                        | text          | number        |
| Yes      | series tag  | account_number                    | ACCOUNT NUMBER                    | text          | number        |
| Yes      | series tag  | site_number                       | SITE NUMBER                       | text          | number        |
| Yes      | series tag  | legal_name                        | LEGAL NAME                        | text          | text          |
| Yes      | series tag  | doing_business_as_name            | DOING BUSINESS AS NAME            | text          | text          |
| No       |             | address                           | ADDRESS                           | text          | text          |
| Yes      | series tag  | city                              | CITY                              | text          | text          |
| Yes      | series tag  | state                             | STATE                             | text          | text          |
| Yes      | series tag  | zip_code                          | ZIP CODE                          | text          | text          |
| Yes      | series tag  | ward                              | WARD                              | text          | number        |
| Yes      | series tag  | precinct                          | PRECINCT                          | text          | number        |
| Yes      | series tag  | ward_precinct                     | WARD PRECINCT                     | text          | text          |
| Yes      | series tag  | police_district                   | POLICE DISTRICT                   | text          | number        |
| Yes      | series tag  | license_code                      | LICENSE CODE                      | text          | number        |
| Yes      | series tag  | license_description               | LICENSE DESCRIPTION               | text          | text          |
| Yes      | series tag  | business_activity_id              | BUSINESS ACTIVITY ID              | text          | text          |
| Yes      | series tag  | business_activity                 | BUSINESS ACTIVITY                 | text          | text          |
| Yes      | series tag  | license_number                    | LICENSE NUMBER                    | text          | number        |
| Yes      | series tag  | application_type                  | APPLICATION TYPE                  | text          | text          |
| No       |             | application_created_date          | APPLICATION CREATED DATE          | calendar_date | calendar_date |
| No       |             | application_requirements_complete | APPLICATION REQUIREMENTS COMPLETE | calendar_date | calendar_date |
| No       |             | payment_date                      | PAYMENT DATE                      | calendar_date | calendar_date |
| Yes      | series tag  | conditional_approval              | CONDITIONAL APPROVAL              | text          | text          |
| No       |             | license_start_date                | LICENSE TERM START DATE           | calendar_date | calendar_date |
| Yes      | time        | expiration_date                   | LICENSE TERM EXPIRATION DATE      | calendar_date | calendar_date |
| No       |             | license_approved_for_issuance     | LICENSE APPROVED FOR ISSUANCE     | calendar_date | calendar_date |
| No       |             | date_issued                       | DATE ISSUED                       | calendar_date | calendar_date |
| Yes      | series tag  | license_status                    | LICENSE STATUS                    | text          | text          |
| No       |             | license_status_change_date        | LICENSE STATUS CHANGE DATE        | calendar_date | calendar_date |
| Yes      | series tag  | ssa                               | SSA                               | text          | text          |
| No       |             | latitude                          | LATITUDE                          | number        | number        |
| No       |             | longitude                         | LONGITUDE                         | number        | number        |
```

## Time Field

```ls
Value = expiration_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = id,address,application_created_date,payment_date,application_requirements_complete,license_start_date,license_approved_for_issuance,date_issued,license_status_change_date,latitude,longitude
```

## Data Commands

```ls
series e:uupf-x98q d:2018-05-15T00:00:00.000Z t:license_code=1010 t:application_type=RENEW t:business_activity_id=911 t:license_status=AAI t:account_number=295026 t:police_district=1 t:zip_code=60607 t:license_description="Limited Business License" t:license_number=1620668 t:state=IL t:site_number=1 t:business_activity="Retail Sales of Clothing / Accessories / Shoes" t:ward_precinct=25-28 t:city=CHICAGO t:precinct=28 t:legal_name="BUCCI BIG & TALL INC." t:ward=25 t:doing_business_as_name="BUCCI BIG & TALL INC." t:conditional_approval=N t:license_id=2455262 m:row_number.uupf-x98q=1

series e:uupf-x98q d:2018-09-15T00:00:00.000Z t:license_code=4404 t:application_type=ISSUE t:business_activity_id=674 t:license_status=AAI t:account_number=409564 t:police_district=7 t:zip_code=60636 t:license_description="Regulated Business License" t:license_number=2488345 t:state=IL t:site_number=1 t:business_activity="Home Repair Services (Home Occ)" t:ward_precinct=15-35 t:city=CHICAGO t:precinct=35 t:legal_name="BURKS HEATING AND COOLING SOLUTIONS, LLC" t:ward=15 t:doing_business_as_name="BURKS HEATING AND COOLING SOLUTIONS, LLC" t:conditional_approval=N t:license_id=2488345 m:row_number.uupf-x98q=2

series e:uupf-x98q d:2018-09-15T00:00:00.000Z t:license_code=4406 t:application_type=RENEW t:business_activity_id=915 t:license_status=AAI t:zip_code=60477 t:account_number=393149 t:license_description="Peddler License" t:license_number=2354707 t:state=IL t:site_number=1 t:business_activity="Street Performer, Moving Along the Public Way (Special)" t:city="TINLEY PARK" t:legal_name="ANGELINE R. MC CARTHY" t:doing_business_as_name="ANGELINE R. MC CARTHY" t:conditional_approval=N t:license_id=2482568 m:row_number.uupf-x98q=3
```

## Meta Commands

```ls
metric m:row_number.uupf-x98q p:long l:"Row Number"

entity e:uupf-x98q l:"Business Licenses - Current Active" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/uupf-x98q

property e:uupf-x98q t:meta.view v:id=uupf-x98q v:category="Community & Economic Development" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Business Licenses - Current Active" v:attribution="City of Chicago"

property e:uupf-x98q t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:uupf-x98q t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| id               | license_id | account_number | site_number | legal_name                               | doing_business_as_name                   | address                | city        | state | zip_code | ward | precinct | ward_precinct | police_district | license_code | license_description        | business_activity_id | business_activity                                                | license_number | application_type | application_created_date | application_requirements_complete | payment_date        | conditional_approval | license_start_date  | expiration_date     | license_approved_for_issuance | date_issued         | license_status | license_status_change_date | ssa | latitude     | longitude     | 
| ================ | ========== | ============== | =========== | ======================================== | ======================================== | ====================== | =========== | ===== | ======== | ==== | ======== | ============= | =============== | ============ | ========================== | ==================== | ================================================================ | ============== | ================ | ======================== | ================================= | =================== | ==================== | =================== | =================== | ============================= | =================== | ============== | ========================== | === | ============ | ============= | 
| 1620668-20160516 | 2455262    | 295026         | 1           | BUCCI BIG & TALL INC.                    | BUCCI BIG & TALL INC.                    | 558 W ROOSEVELT RD     | CHICAGO     | IL    | 60607    | 25   | 28       | 25-28         | 1               | 1010         | Limited Business License   | 911                  | Retail Sales of Clothing / Accessories / Shoes                   | 1620668        | RENEW            |                          | 2016-03-15T00:00:00               | 2016-05-18T00:00:00 | N                    | 2016-05-16T00:00:00 | 2018-05-15T00:00:00 | 2016-05-18T00:00:00           | 2016-08-30T00:00:00 | AAI            |                            |     | 41.867338566 | -87.641590057 | 
| 2488345-20160830 | 2488345    | 409564         | 1           | BURKS HEATING AND COOLING SOLUTIONS, LLC | BURKS HEATING AND COOLING SOLUTIONS, LLC | 5722 S WOOD ST 1ST     | CHICAGO     | IL    | 60636    | 15   | 35       | 15-35         | 7               | 4404         | Regulated Business License | 674                  | Home Repair Services (Home Occ)                                  | 2488345        | ISSUE            | 2016-08-30T00:00:00      | 2016-08-30T00:00:00               | 2016-08-30T00:00:00 | N                    | 2016-08-30T00:00:00 | 2018-09-15T00:00:00 | 2016-08-30T00:00:00           | 2016-08-30T00:00:00 | AAI            |                            |     | 41.78961679  | -87.669471996 | 
| 2354707-20160916 | 2482568    | 393149         | 1           | ANGELINE R. MC CARTHY                    | ANGELINE R. MC CARTHY                    | 17707 S HARLEM ST 1    | TINLEY PARK | IL    | 60477    |      |          |               |                 | 4406         | Peddler License            | 915                  | Street Performer, Moving Along the Public Way (Special)          | 2354707        | RENEW            |                          | 2016-07-15T00:00:00               | 2016-08-30T00:00:00 | N                    | 2016-09-16T00:00:00 | 2018-09-15T00:00:00 |                               | 2016-08-30T00:00:00 | AAI            |                            |     |              |               | 
| 2488245-20160830 | 2488245    | 336275         | 2           | MARIA G CAHUE                            | BEAUTY AND HEALTH                        | 2705 W 51ST ST 1ST     | CHICAGO     | IL    | 60632    | 14   | 19       | 14-19         | 9               | 1010         | Limited Business License   | 904                  | Retail Sales of General Merchandise                              | 2488245        | ISSUE            | 2016-08-29T00:00:00      | 2016-08-30T00:00:00               | 2016-08-30T00:00:00 | N                    | 2016-08-30T00:00:00 | 2017-06-15T00:00:00 | 2016-08-30T00:00:00           | 2016-08-30T00:00:00 | AAI            |                            |     | 41.80091646  | -87.691799519 | 
| 2483710-20160830 | 2483710    | 316966         | 3           | OLD TOWN OIL, LLC                        | OLD TOWN OIL, LLC                        | 1543 N WELLS ST 1ST    | CHICAGO     | IL    | 60610    | 27   | 54       | 27-54         | 18              | 1006         | Retail Food Establishment  | 782                  | Sale of Food Prepared Onsite Without Dining Area                 | 2483710        | C_LOC            | 2016-08-04T00:00:00      | 2016-08-04T00:00:00               | 2016-08-22T00:00:00 | N                    | 2016-08-30T00:00:00 | 2018-02-15T00:00:00 | 2016-08-30T00:00:00           | 2016-08-30T00:00:00 | AAI            |                            | 48  | 41.910408191 | -87.634540092 | 
| 2374115-20160916 | 2481313    | 352159         | 3           | Genesys Works Chicago                    | Genesys Works Chicago                    | 180 N WABASH AVE 6 600 | CHICAGO     | IL    | 60601    | 42   |          | 42-           |                 | 1010         | Limited Business License   | 708                  | Miscellaneous Commercial Services                                | 2374115        | RENEW            |                          | 2016-07-15T00:00:00               | 2016-08-30T00:00:00 | N                    | 2016-09-16T00:00:00 | 2018-09-15T00:00:00 | 2016-08-30T00:00:00           | 2016-08-30T00:00:00 | AAI            |                            | 1   | 41.885353704 | -87.626413285 | 
| 1169428-20160316 | 2444497    | 218178         | 1           | SHINE-AWN INC                            | SHINE-AWN INC                            | 6631 W 16TH ST         | BERWYN      | IL    | 60402    |      |          |               |                 | 1010         | Limited Business License   |                      |                                                                  | 1169428        | RENEW            |                          | 2016-01-15T00:00:00               | 2016-03-22T00:00:00 | N                    | 2016-03-16T00:00:00 | 2018-03-15T00:00:00 | 2016-03-22T00:00:00           | 2016-03-23T00:00:00 | AAI            |                            |     |              |               | 
| 2488347-20160830 | 2488347    | 409567         | 1           | ROSA I. MONTOYA                          | SOUL MIND BODYWORK                       | 3035 N MILWAUKEE AVE 1 | CHICAGO     | IL    | 60618    | 30   | 13       | 30-13         | 25              | 1010         | Limited Business License   | 956 | 896            | Provide Waxing Services | Skincare Services                      | 2488347        | ISSUE            | 2016-08-30T00:00:00      | 2016-08-30T00:00:00               | 2016-08-30T00:00:00 | N                    | 2016-08-30T00:00:00 | 2018-09-15T00:00:00 | 2016-08-30T00:00:00           | 2016-08-30T00:00:00 | AAI            |                            |     | 41.936432173 | -87.719244109 | 
| 70443-20151216   | 2429922    | 60446          | 1           | JUANA ZARATE                             | DISCOTECA ZARATE                         | 3115 W 26TH ST 1ST     | CHICAGO     | IL    | 60623    | 12   | 6        | 12-6          | 10              | 1010         | Limited Business License   |                      |                                                                  | 70443          | RENEW            |                          | 2015-10-15T00:00:00               | 2016-03-21T00:00:00 | N                    | 2015-12-16T00:00:00 | 2017-12-15T00:00:00 | 2016-03-21T00:00:00           | 2016-04-06T00:00:00 | AAI            |                            | 25  | 41.844428666 | -87.703236873 | 
| 2488343-20160830 | 2488343    | 409562         | 1           | TRANSITIONAL DEVELOPMENT REALTY INC.     | TRANSITIONAL DEVELOPMENT REALTY INC.     | 29 W 159TH ST          | HARVEY      | IL    | 60426    |      |          |               |                 | 4404         | Regulated Business License | 901                  | Heating, Ventilation and Air Conditioning Services - Residential | 2488343        | ISSUE            | 2016-08-30T00:00:00      | 2016-08-30T00:00:00               | 2016-08-30T00:00:00 | N                    | 2016-08-30T00:00:00 | 2018-09-15T00:00:00 | 2016-08-30T00:00:00           | 2016-08-30T00:00:00 | AAI            |                            |     |              |               | 
```