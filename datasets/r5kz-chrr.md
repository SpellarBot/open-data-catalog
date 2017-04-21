# Business Licenses

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/business-licenses-71e6d) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/r5kz-chrr) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/r5kz-chrr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/r5kz-chrr/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | r5kz-chrr |
| Name | Business Licenses |
| Attribution | City of Chicago |
| Category | Community & Economic Development |
| Tags | business, licenses |
| Created | 2011-09-27T16:03:34Z |
| Publication Date | 2016-08-30T22:01:35Z |

## Description

Business licenses issued by the Department of Business Affairs and Consumer Protection in the City of Chicago from 2002 to the present. This dataset contains a large number of records/rows of data and may not be viewed in full in Microsoft Excel. Therefore, when downloading the file, select CSV from the Export menu. Open the file in an ASCII text editor, such as Notepad or Wordpad, to view and search. 
 
Data fields requiring description are detailed below. 

APPLICATION TYPE:  ?ISSUE? is the record associated with the initial license application.  ?RENEW? is a subsequent renewal record.  All renewal records are created with a term start date and term expiration date.  ?C_LOC? is a change of location record.  It means the business moved.   ?C_CAPA? is a change of capacity record.  Only a few license types may file this type of application.  ?C_EXPA? only applies to businesses that have liquor licenses.  It means the business location expanded.  'C_SBA' is a change of business activity record. It means that a new business activity was added or an existing business activity was marked as expired.

LICENSE STATUS: ?AAI? means the license was issued. ?AAC? means the license was cancelled during its term.  ?REV? means the license was revoked. 'REA' means the license revocation has been appealed.

LICENSE STATUS CHANGE DATE:  This date corresponds to the date a license was cancelled (AAC), revoked (REV) or appealed (REA).

Business License Owner information may be accessed at:  https://data.cityofchicago.org/dataset/Business-Owners/ezma-pppn. To identify the owner of a business, you will need the account number or legal name, which may be obtained from this Business Licenses dataset. 

Data Owner: Business Affairs and Consumer Protection. Time Period: January 1, 2002 to present. Frequency: Data is updated daily.

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
| No       |             | expiration_date                   | LICENSE TERM EXPIRATION DATE      | calendar_date | calendar_date |
| No       |             | license_approved_for_issuance     | LICENSE APPROVED FOR ISSUANCE     | calendar_date | calendar_date |
| Yes      | time        | date_issued                       | DATE ISSUED                       | calendar_date | calendar_date |
| Yes      | series tag  | license_status                    | LICENSE STATUS                    | text          | text          |
| No       |             | license_status_change_date        | LICENSE STATUS CHANGE DATE        | calendar_date | calendar_date |
| Yes      | series tag  | ssa                               | SSA                               | text          | text          |
| No       |             | latitude                          | LATITUDE                          | number        | number        |
| No       |             | longitude                         | LONGITUDE                         | number        | number        |
```

## Time Field

```ls
Value = date_issued
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = id,address,application_created_date,payment_date,application_requirements_complete,license_start_date,license_approved_for_issuance,expiration_date,license_status_change_date,latitude,longitude
```

## Data Commands

```ls
series e:r5kz-chrr d:2006-08-11T00:00:00.000Z t:license_code=1010 t:application_type=RENEW t:license_status=AAI t:account_number=29481 t:zip_code=60623 t:police_district=8 t:license_description="Limited Business License" t:license_number=22308 t:state=IL t:site_number=1 t:ward_precinct=14- t:city=CHICAGO t:legal_name="BELL OIL TERMINAL INC" t:ward=14 t:doing_business_as_name="Bell Oil Terminal LLC" t:conditional_approval=N t:license_id=1723393 m:row_number.r5kz-chrr=1

series e:r5kz-chrr d:2016-08-30T00:00:00.000Z t:license_code=1010 t:application_type=RENEW t:business_activity_id=911 t:license_status=AAI t:account_number=295026 t:police_district=1 t:zip_code=60607 t:license_description="Limited Business License" t:license_number=1620668 t:state=IL t:site_number=1 t:business_activity="Retail Sales of Clothing / Accessories / Shoes" t:ward_precinct=25-28 t:city=CHICAGO t:precinct=28 t:legal_name="BUCCI BIG & TALL INC." t:ward=25 t:doing_business_as_name="BUCCI BIG & TALL INC." t:conditional_approval=N t:license_id=2455262 m:row_number.r5kz-chrr=2

series e:r5kz-chrr d:2016-06-22T00:00:00.000Z t:license_code=1625 t:application_type=RENEW t:business_activity_id=720 t:license_status=AAC t:account_number=291461 t:police_district=9 t:zip_code=60616 t:license_description=Raffles t:license_number=2368602 t:state=IL t:site_number=3 t:business_activity="Not-For-Profit Selling Raffles for Prizes of $50 or More" t:ward_precinct=25-18 t:city=CHICAGO t:precinct=18 t:legal_name="PROJECT: VISION , INC." t:ward=25 t:doing_business_as_name="PROJECT : VISION , INC" t:conditional_approval=N t:license_id=2460909 m:row_number.r5kz-chrr=3
```

## Meta Commands

```ls
metric m:row_number.r5kz-chrr p:long l:"Row Number"

entity e:r5kz-chrr l:"Business Licenses" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/r5kz-chrr

property e:r5kz-chrr t:meta.view v:id=r5kz-chrr v:category="Community & Economic Development" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Business Licenses" v:attribution="City of Chicago"

property e:r5kz-chrr t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:r5kz-chrr t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| id               | license_id | account_number | site_number | legal_name                               | doing_business_as_name                   | address                   | city        | state | zip_code | ward | precinct | ward_precinct | police_district | license_code | license_description         | business_activity_id | business_activity                                                                   | license_number | application_type | application_created_date | application_requirements_complete | payment_date        | conditional_approval | license_start_date  | expiration_date     | license_approved_for_issuance | date_issued         | license_status | license_status_change_date | ssa | latitude     | longitude     | 
| ================ | ========== | ============== | =========== | ======================================== | ======================================== | ========================= | =========== | ===== | ======== | ==== | ======== | ============= | =============== | ============ | =========================== | ==================== | =================================================================================== | ============== | ================ | ======================== | ================================= | =================== | ==================== | =================== | =================== | ============================= | =================== | ============== | ========================== | === | ============ | ============= | 
| 22308-20060816   | 1723393    | 29481          | 1           | BELL OIL TERMINAL INC                    | Bell Oil Terminal LLC                    | 3741 S PULASKI RD 1       | CHICAGO     | IL    | 60623    | 14   |          | 14-           | 8               | 1010         | Limited Business License    |                      |                                                                                     | 22308          | RENEW            |                          | 2006-06-21T00:00:00               | 2006-08-10T00:00:00 | N                    | 2006-08-16T00:00:00 | 2007-08-15T00:00:00 | 2006-08-10T00:00:00           | 2006-08-11T00:00:00 | AAI            |                            |     | 41.82531993  | -87.723959997 | 
| 1620668-20160516 | 2455262    | 295026         | 1           | BUCCI BIG & TALL INC.                    | BUCCI BIG & TALL INC.                    | 558 W ROOSEVELT RD        | CHICAGO     | IL    | 60607    | 25   | 28       | 25-28         | 1               | 1010         | Limited Business License    | 911                  | Retail Sales of Clothing / Accessories / Shoes                                      | 1620668        | RENEW            |                          | 2016-03-15T00:00:00               | 2016-05-18T00:00:00 | N                    | 2016-05-16T00:00:00 | 2018-05-15T00:00:00 | 2016-05-18T00:00:00           | 2016-08-30T00:00:00 | AAI            |                            |     | 41.867338566 | -87.641590057 | 
| 2368602-20160616 | 2460909    | 291461         | 3           | PROJECT: VISION , INC.                   | PROJECT : VISION , INC                   | 2301 S ARCHER AVE 1 1     | CHICAGO     | IL    | 60616    | 25   | 18       | 25-18         | 9               | 1625         | Raffles                     | 720                  | Not-For-Profit Selling Raffles for Prizes of $50 or More                            | 2368602        | RENEW            |                          | 2016-04-15T00:00:00               | 2016-06-21T00:00:00 | N                    | 2016-06-16T00:00:00 | 2017-06-15T00:00:00 | 2016-06-21T00:00:00           | 2016-06-22T00:00:00 | AAC            | 2016-08-30T00:00:00        |     | 41.850842944 | -87.638734244 | 
| 2060891-20141016 | 2353257    | 357247         | 1           | FOLASHADE'S CLEANING SERVICE INC.        | FOLASHADE'S CLEANING SERVICE INC.        | 1965 BERNICE RD 1 1SW     | LANSING     | IL    | 60438    |      |          |               |                 | 1010         | Limited Business License    |                      |                                                                                     | 2060891        | RENEW            |                          | 2014-08-15T00:00:00               | 2016-04-01T00:00:00 | N                    | 2014-10-16T00:00:00 | 2016-10-15T00:00:00 | 2016-04-01T00:00:00           | 2016-04-01T00:00:00 | AAI            |                            | 38  | 41.951315556 | -87.67858578  | 
| 1144216-20070516 | 1804790    | 147            | 63          | WALGREEN CO.                             | Walgreens # 05192                        | 9148 S COMMERCIAL AVE 1ST | CHICAGO     | IL    | 60617    | 10   | 25       | 10-25         | 4               | 1010         | Limited Business License    |                      |                                                                                     | 1144216        | RENEW            |                          | 2007-03-23T00:00:00               | 2007-05-10T00:00:00 | N                    | 2007-05-16T00:00:00 | 2008-05-15T00:00:00 | 2007-05-10T00:00:00           | 2007-05-11T00:00:00 | AAI            |                            | 5   | 41.728621736 | -87.551366466 | 
| 2488345-20160830 | 2488345    | 409564         | 1           | BURKS HEATING AND COOLING SOLUTIONS, LLC | BURKS HEATING AND COOLING SOLUTIONS, LLC | 5722 S WOOD ST 1ST        | CHICAGO     | IL    | 60636    | 15   | 35       | 15-35         | 7               | 4404         | Regulated Business License  | 674                  | Home Repair Services (Home Occ)                                                     | 2488345        | ISSUE            | 2016-08-30T00:00:00      | 2016-08-30T00:00:00               | 2016-08-30T00:00:00 | N                    | 2016-08-30T00:00:00 | 2018-09-15T00:00:00 | 2016-08-30T00:00:00           | 2016-08-30T00:00:00 | AAI            |                            |     | 41.78961679  | -87.669471996 | 
| 22308-20030816   | 1479006    | 29481          | 1           | BELL OIL TERMINAL INC                    | Bell Oil Terminal LLC                    | 3741 S PULASKI RD 1       | CHICAGO     | IL    | 60623    | 14   |          | 14-           | 8               | 1010         | Limited Business License    |                      |                                                                                     | 22308          | RENEW            |                          | 2004-03-05T00:00:00               | 2004-03-22T00:00:00 | N                    | 2003-08-16T00:00:00 | 2004-08-15T00:00:00 | 2004-03-25T00:00:00           | 2004-04-16T00:00:00 | AAI            |                            |     | 41.82531993  | -87.723959997 | 
| 2488318-20160830 | 2488318    | 85538          | 20          | JAM PRODUCTIONS, LTD.                    | 9/7/16 Concert with Andrew Bird          | 201 E RANDOLPH ST         | CHICAGO     | IL    | 60601    | 42   | 44       | 42-44         | 1               | 4409         | Itinerant Merchant          | 723                  | Organizer of Vendors That Sell for Retail at a Trade Show, Exhibition or Convention | 2488318        | ISSUE            | 2016-08-30T00:00:00      | 2016-08-30T00:00:00               | 2016-08-30T00:00:00 | N                    | 2016-08-30T00:00:00 | 2016-09-07T00:00:00 | 2016-08-30T00:00:00           | 2016-08-30T00:00:00 | AAI            |                            |     | 41.884167384 | -87.622250042 | 
| 2354707-20160916 | 2482568    | 393149         | 1           | ANGELINE R. MC CARTHY                    | ANGELINE R. MC CARTHY                    | 17707 S HARLEM ST 1       | TINLEY PARK | IL    | 60477    |      |          |               |                 | 4406         | Peddler License             | 915                  | Street Performer, Moving Along the Public Way (Special)                             | 2354707        | RENEW            |                          | 2016-07-15T00:00:00               | 2016-08-30T00:00:00 | N                    | 2016-09-16T00:00:00 | 2018-09-15T00:00:00 |                               | 2016-08-30T00:00:00 | AAI            |                            |     |              |               | 
| 2488279-20160830 | 2488279    | 334474         | 4           | REVOLUTION BREWING, LLC                  | Revolution Brewing                       | 3340 N KEDZIE AVE         | CHICAGO     | IL    | 60618    | 35   | 24       | 35-24         | 17              | 1476         | Special Event Beer and Wine | 717                  | Special Event Beer & Wine                                                           | 2488279        | ISSUE            | 2016-08-30T00:00:00      | 2016-08-30T00:00:00               | 2016-08-30T00:00:00 | N                    | 2016-08-30T00:00:00 | 2016-09-24T00:00:00 | 2016-08-30T00:00:00           | 2016-08-30T00:00:00 | AAI            |                            |     | 41.94217262  | -87.70784755  | 
```