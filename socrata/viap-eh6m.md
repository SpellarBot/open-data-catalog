# Minority Business Enterprise: Statewide Directory - MBE, DBE (Disadvantaged Business Enterprise), SBE (Small Business Enterprise), and ACDBE (Airport Concession Disadvantaged Enterprise) Certified ...

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/minority-business-enterprise-b32e3) |
| Metadata | [Link](https://data.maryland.gov/api/views/viap-eh6m) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/viap-eh6m/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/viap-eh6m/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | viap-eh6m |
| Name | Minority Business Enterprise: Statewide Directory - MBE, DBE (Disadvantaged Business Enterprise), SBE (Small Business Enterprise), and ACDBE (Airport Concession Disadvantaged Enterprise) Certified ... |
| Attribution | Maryland Department of Transportation (MDOT) |
| Category | Business and Economy |
| Tags | mbe, minority business enterprise, mdot, maryland department of transportation |
| Created | 2014-06-19T19:26:27Z |
| Publication Date | 2017-03-01T17:04:41Z |

## Description

MBE, DBE (Disadvantaged Business Enterprise), SBE (Small Business Enterprise) and ACDBE (Airport Concession Disadvantaged Enterprise) certified businesses are all shown. This dataset contains a list of businesses certified by Minority Business Enterprise (MBE) within the state of Maryland. This program is affiliated with the Maryland Department of Transportation (MDOT)

Data are continually updated at MDOT's website for MBE: https://mbe.mdot.maryland.gov/directory/search_select.asp. This dataset was created on Jan. 14 2016 and therefore shows all businesses certified as of that date. The Department of Information Technology (DoIT) will update this dataset using MDOT's source data, at least once per month moving forward. If you have questions about the dataset or data please contact service.desk@maryland.gov.

## Columns

```ls
| Included | Schema Type | Field Name            | Name                  | Data Type     | Render Type   |
| ======== | =========== | ===================== | ===================== | ============= | ============= |
| Yes      | series tag  | name                  | Name                  | text          | text          |
| No       |             | address               | Address               | text          | text          |
| Yes      | series tag  | city                  | City                  | text          | text          |
| Yes      | series tag  | state                 | State                 | text          | text          |
| Yes      | series tag  | zip                   | Zip Code              | text          | text          |
| Yes      | series tag  | county                | County                | text          | text          |
| Yes      | series tag  | minority_group        | Minority Group(s)     | text          | text          |
| Yes      | series tag  | contact               | Contact Name          | text          | text          |
| Yes      | series tag  | phone                 | Contact Phone Number  | phone         | phone         |
| Yes      | series tag  | fax                   | Contact Fax           | phone         | phone         |
| Yes      | series tag  | certification_number  | Certification Number  | text          | text          |
| Yes      | time        | certification_date    | Certification Date    | calendar_date | calendar_date |
| Yes      | series tag  | contact_email_address | Contact Email Address | email         | email         |
| Yes      | series tag  | website               | Website               | url           | url           |
| Yes      | series tag  | naics_code            | NAICS Codes(s)        | text          | text          |
| Yes      | series tag  | products_services     | Products / Services   | text          | text          |
```

## Time Field

```ls
Value = certification_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:viap-eh6m d:2007-10-10T00:00:00.000Z t:certification_number=07-362 t:zip=20910 t:phone_number=8668050793 t:website=http://WWW.1STCHOICEGOV.COM t:state=MD t:contact="MICHELLE A. BELL" t:products_services="EMPLOYMENT PLACEMENT AGENCIES EXECUTIVE PLACEMENT SERVICES HUMAN RESOURCES CONSULTING SERVICES MANAGEMENT SERVICES ORGANIZATIONAL DEVELOPMENT AND TRAINING TEMPORARY HELP SERVICES OFFICE ADMINISTRATIVE SERVICES DOCUMENT DATA RECORD RETRIEVAL ADMINISTRATIVE MANAGEMENT AND GENERAL MANAGEMENT CONSULTING SERVICES" t:minority_group="AFRICAN AMERICAN / FEMALE" t:city="SILVER SPRING" t:contact_email_address=RWILSON@1STCHOICEGOV.COM t:county="BALTIMORE CITY" t:name="1ST CHOICE, LLC" t:naics_code="541611-MBE/DBE/SBE, 541612-MBE/DBE/SBE, 561110-MBE/DBE/SBE, 561311-MBE/DBE/SBE, 561320-MBE/DBE/SBE" m:row_number.viap-eh6m=1

series e:viap-eh6m d:2014-07-10T00:00:00.000Z t:certification_number=14-369 t:zip=21203 t:phone_number=4109615542 t:website=http://WWW.1STCLASSSECURITYSERVICES.COM t:state=MD t:contact="LATANYA BROWN" t:products_services="SECURITY GUARDS AND PATROL SERVICES" t:minority_group="AFRICAN AMERICAN / FEMALE" t:city=BALTIMORE t:contact_email_address=LBROWN@1STCLASSSECURITYSERVICES.COM t:county=BALTIMORE t:name="1ST CLASS SECURITY SERVICES, LLC" t:naics_code=561612-MBE/DBE/SBE m:row_number.viap-eh6m=2

series e:viap-eh6m d:2014-06-11T00:00:00.000Z t:certification_number=14-327 t:contact_email_address=AWATSON@ASREFUSE.COM t:zip=21224 t:phone_number=4102823868 t:county="ANNE ARUNDEL" t:name="A & S REFUSE, LLC" t:state=MD t:products_services="SOLID WASTE COLLECTION" t:contact="ANGELA WATSON" t:minority_group=FEMALE t:naics_code=562111-MBE/DBE/SBE t:city=BALTIMORE m:row_number.viap-eh6m=3
```

## Meta Commands

```ls
metric m:row_number.viap-eh6m p:long l:"Row Number"

entity e:viap-eh6m l:"Minority Business Enterprise: Statewide Directory - MBE, DBE (Disadvantaged Business Enterprise), SBE (Small Business Enterprise), and ACDBE (Airport Concession Disadvantaged Enterprise) Certified Businesses" t:attribution="Maryland Department of Transportation (MDOT)" t:url=https://data.maryland.gov/api/views/viap-eh6m

property e:viap-eh6m t:meta.view v:id=viap-eh6m v:category="Business and Economy" v:attributionLink=https://mbe.mdot.maryland.gov/directory/search_select.asp v:averageRating=0 v:name="Minority Business Enterprise: Statewide Directory - MBE, DBE (Disadvantaged Business Enterprise), SBE (Small Business Enterprise), and ACDBE (Airport Concession Disadvantaged Enterprise) Certified Businesses" v:attribution="Maryland Department of Transportation (MDOT)"

property e:viap-eh6m t:meta.view.license v:name="Public Domain"

property e:viap-eh6m t:meta.view.owner v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"

property e:viap-eh6m t:meta.view.tableauthor v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"
```

## Top Records

```ls
| name                                | address             | city          | state | zip        | county          | minority_group            | contact                    | phone              | fax                | certification_number | certification_date  | contact_email_address               | website                                         | naics_code                                                                                                             | products_services                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | 
| =================================== | =================== | ============= | ===== | ========== | =============== | ========================= | ========================== | ================== | ================== | ==================== | =================== | =================================== | =============================================== | ====================================================================================================================== | ================================================================================================================================================================================================================================================================================================================================================================================================================================================================================== | 
| 1ST CHOICE, LLC                     | 8121 GEROGIA AVENUE | SILVER SPRING | MD    | 20910      | BALTIMORE CITY  | AFRICAN AMERICAN / FEMALE | MICHELLE A. BELL           | [3015636404, null] | [8668050793, null] | 07-362               | 2007-10-10T00:00:00 | RWILSON@1STCHOICEGOV.COM            | [http://WWW.1STCHOICEGOV.COM, null]             | 541611-MBE/DBE/SBE, 541612-MBE/DBE/SBE, 561110-MBE/DBE/SBE, 561311-MBE/DBE/SBE, 561320-MBE/DBE/SBE                     | EMPLOYMENT PLACEMENT AGENCIES EXECUTIVE PLACEMENT SERVICES HUMAN RESOURCES CONSULTING SERVICES MANAGEMENT SERVICES ORGANIZATIONAL DEVELOPMENT AND TRAINING TEMPORARY HELP SERVICES OFFICE ADMINISTRATIVE SERVICES DOCUMENT DATA RECORD RETRIEVAL ADMINISTRATIVE MANAGEMENT AND GENERAL MANAGEMENT CONSULTING SERVICES                                                                                                                                                              | 
| 1ST CLASS SECURITY SERVICES, LLC    | PO BOX 41662        | BALTIMORE     | MD    | 21203      | BALTIMORE       | AFRICAN AMERICAN / FEMALE | LATANYA BROWN              | [4109615542, null] | [null, null]       | 14-369               | 2014-07-10T00:00:00 | LBROWN@1STCLASSSECURITYSERVICES.COM | [http://WWW.1STCLASSSECURITYSERVICES.COM, null] | 561612-MBE/DBE/SBE                                                                                                     | SECURITY GUARDS AND PATROL SERVICES                                                                                                                                                                                                                                                                                                                                                                                                                                                | 
| A & S REFUSE, LLC                   | P. O. BOX 25882     | BALTIMORE     | MD    | 21224      | ANNE ARUNDEL    | FEMALE                    | ANGELA WATSON              | [4102823867, null] | [4102823868, null] | 14-327               | 2014-06-11T00:00:00 | AWATSON@ASREFUSE.COM                | [null, null]                                    | 562111-MBE/DBE/SBE                                                                                                     | SOLID WASTE COLLECTION                                                                                                                                                                                                                                                                                                                                                                                                                                                             | 
| A DOSE OF BLOOM                     | P.O. BOX 1325       | RANDALLSTOWN  | MD    | 21133      | BALTIMORE       | AFRICAN AMERICAN          | DONALD CHEEK               | [4109634457, null] | [4105213290, null] | 09-009               | 2009-01-21T00:00:00 | ADOSEOFBLOOM@HOTMAIL.COM            | [http://WWW.ADOSEOFBLOOM.COM, null]             | 453110-MBE/DBE/SBE                                                                                                     | FLORISTS SPECIFICALLY INTERIOR AND EXTERIOR PLANTSCAPES                                                                                                                                                                                                                                                                                                                                                                                                                            | 
| A FRIEND OF THE FAMILY, INC.        | P. O. BOX 5051      | WILMINGTON    | DE    | 19808-0051 | OTHER STATE     | FEMALE                    | KIM L. ALLEN               | [3024634603, null] | [null, null]       | 13-384               | 2013-08-19T00:00:00 |                                     | [http://WWW.AFRIENDOFTHEFAMILY.COM, null]       | 611710-MBE-ONLY                                                                                                        | EDUCATIONAL SUPPORT SERVICES SPECIFICALLY EDUCATIONAL CONSULTANTS GUIDANCE COUNSELING EDUCATIONAL SUPPORT                                                                                                                                                                                                                                                                                                                                                                          | 
| A. BROWN & ASSOCIATES, LLC          | PO BOX 10           | COCKEYSVILLE  | MD    | 21030      | BALTIMORE       | FEMALE                    | ANGELA J. BROWN            | [4107857410, null] | [4107857411, null] | 05-553               | 2005-12-10T00:00:00 | ABROWN@ABROWNCPAS.COM               | [http://WWW.ABROWNCPAS.COM, null]               | 541211-MBE/DBE/SBE, 541213-MBE/DBE/SBE                                                                                 | TAX PREPARATION SERVICES SPECIFICALLY TAX PREPARATION PERSONAL BUSINESS OFFICES OF CERTIFIED PUBLIC ACCOUNTANTS SPECIFICALLY ACCOUNTING AUDITING AND BOOKKEEPING SERVICES OFFICES OF CERTIFIED PUBLIC ACCOUNTANTS                                                                                                                                                                                                                                                                  | 
| A. THOMPSON & ASSOCIATES, INC.      | P. O. BOX 176       | DEALE         | MD    | 20751      | ANNE ARUNDEL    | AFRICAN AMERICAN          | ALEXANDER M. THOMPSON, JR. | [4108679121, null] | [4108679123, null] | 08-674               | 2008-12-08T00:00:00 | ALEX@ATHOMPSONASSOCIATES.COM        | [null, null]                                    | 541613-MBE/DBE/SBE, 541618-MBE/DBE/SBE, 541820-MBE/DBE/SBE                                                             | MARKETING CONSULTING SERVICES SPECIFICALLY ASSISTING CLIENTS ON MARKETING STRATEGIES RELATING TO HEALTH CARE BENEFITS OTHER MANAGEMENT CONSULTING SERVICES SPECIFICALLY BENEFITS ADMINISTRATOR OF HEALTH CARE BENEFITS INCLUDING PREPARATION OF RFPS CONTRACT NEGOTIATION LIAISON WITH PROVIDERS PROCEDURE REVIEWS AND REPORT WRITING PUBLIC RELATIONS AGENCIES SPECIFICALLY DESIGNING AND IMPLEMENTING PUBLIC RELATIONS CAMPAIGNS RELATING TO HEALTH CARE BENEFITS                | 
| A.S. TOURS INC.                     | P. O. BOX 26463     | BALTIMORE     | MD    | 21207      | BALTIMORE       | AFRICAN AMERICAN          | ALBERT SPENCE              | [4103676900, null] | [4103677888, null] | 00-336               | 2000-12-21T00:00:00 | ALSASTOURS@YAHOO.COM                | [http://WWW.MIDWAYLIMO.COM, null]               | 485320-MBE/DBE/SBE, 485510-MBE/DBE/SBE, 561510-MBE/DBE/SBE                                                             | TRAVEL AGENCIES LIMOUSINE SERVICE CHARTER BUS INDUSTRY SPECIFICALLY MOTOR COACH SERVICES                                                                                                                                                                                                                                                                                                                                                                                           | 
| A+ QUALITY EDUCATION, LLC           | P. O. BOX 1312      | LANHAM        | MD    | 20703      | PRINCE GEORGE'S | AFRICAN AMERICAN / FEMALE | HEATHER R. HARDING, ED.D.  | [2408381971, null] | [null, null]       | 12-509               | 2012-08-22T00:00:00 | INFO@AESINOW.COM                    | [http://WWW.AESINOW.COM, null]                  | 541611-MBE/DBE/SBE, 541612-MBE/DBE/SBE, 541720-MBE/DBE/SBE, 611430-MBE/DBE/SBE, 611691-MBE/DBE/SBE, 611710-MBE/DBE/SBE | ADMINISTRATIVE MANAGEMENT AND GENERAL MANAGEMENT CONSULTING SERVICES SPECIFICALLY CONTRACT MANAGEMENT HUMAN RESOURCES CONSULTING SERVICES SPECIFICALLY WORKFORCE DEVELOPMENT AND TRAINING RESEARCH AND DEVELOPMENT IN THE SOCIAL SCIENCES AND HUMANITIES PROFESSIONAL AND MANAGEMENT DEVELOPMENT TRAINING EXAM PREPARATION AND TUTORING EDUCATIONAL SUPPORT SERVICES SPECIFICALLY EDUCATIONAL CONSULTANTS EDUCATIONAL TESTING SERVICES AND EDUCATIONAL TESTING EVALUATION SERVICES | 
| ABOVE & BEYOND TRAFFIC COMPANY, LLC | P.O. BOX 620        | RIDERWOOD     | MD    | 21139      | BALTIMORE       | AFRICAN AMERICAN          | DARIUS THOMPSON            | [4433060900, null] | [null, null]       | 14-503               | 2014-09-17T00:00:00 | ABOVEANDBEYONDTRAFFIC@GMAIL.COM     | [null, null]                                    | 561990-MBE/DBE/SBE                                                                                                     | ALL OTHER SUPPORT SERVICES SPECIFICALLY FLAGGING SERVICES                                                                                                                                                                                                                                                                                                                                                                                                                          | 
```