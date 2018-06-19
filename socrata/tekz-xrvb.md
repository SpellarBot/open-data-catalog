# Political Consultant Filings: Beginning 2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/political-consultant-filings-beginning-2016) |
| Metadata | [Link](https://data.ny.gov/api/views/tekz-xrvb) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/tekz-xrvb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/tekz-xrvb/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | tekz-xrvb |
| Name | Political Consultant Filings: Beginning 2016 |
| Attribution | New York State Department of State (NYS DOS) |
| Category | Transparency |
| Tags | political consultant, political consulting, political consultant client, political consulting services, public official, candidate for public office |
| Created | 2016-12-08T20:44:22Z |
| Publication Date | 2017-04-20T10:08:26Z |

## Description

This dataset contains Political Consultant Disclosure Statements and Correction Filings, as well as an agency-generated final records for each political consultant.  Each line contains the Political Consultant?s name, business address and telephone as well as the public official/candidate and client names, business address, telephone number, the office held or sought by each public official/candidate where applicable and a brief description of the services provided to each.

## Columns

```ls
| Included | Schema Type | Field Name                                           | Name                                                 | Data Type     | Render Type   |
| ======== | =========== | ==================================================== | ==================================================== | ============= | ============= |
| No       |             | year                                                 | Year                                                 | number        | number        |
| Yes      | series tag  | reporting_period                                     | Reporting Period                                     | text          | text          |
| Yes      | time        | filing_date                                          | Filing Date                                          | calendar_date | calendar_date |
| Yes      | series tag  | filing_record_identifier                             | Filing Record Identifier                             | text          | text          |
| Yes      | series tag  | filing_type                                          | Filing Type                                          | text          | text          |
| Yes      | series tag  | correction_type                                      | Correction Type                                      | text          | text          |
| Yes      | series tag  | political_consultant_name                            | Political Consultant (PC) Name                       | text          | text          |
| Yes      | series tag  | pc_business_name                                     | PC Business Name                                     | text          | text          |
| No       |             | pc_business_address_1                                | PC Business Address 1                                | text          | text          |
| Yes      | series tag  | pc_business_city                                     | PC Business City                                     | text          | text          |
| Yes      | series tag  | pc_business_state                                    | PC Business State                                    | text          | text          |
| Yes      | series tag  | pc_business_zip_code                                 | PC Business Zip Code                                 | text          | text          |
| Yes      | series tag  | pc_business_county                                   | PC Business County                                   | text          | text          |
| Yes      | series tag  | pc_business_country                                  | PC Business Country                                  | text          | text          |
| Yes      | series tag  | pc_business_telephone_number                         | PC Business Telephone Number                         | text          | text          |
| Yes      | series tag  | client_type                                          | Client Type                                          | text          | text          |
| Yes      | series tag  | client_name                                          | Client Name                                          | text          | text          |
| Yes      | series tag  | office_held_sought                                   | Office Held/Sought                                   | text          | text          |
| No       |             | client_business_address_1                            | Client Business Address 1                            | text          | text          |
| Yes      | series tag  | client_business_city                                 | Client Business City                                 | text          | text          |
| Yes      | series tag  | client_business_state                                | Client Business State                                | text          | text          |
| Yes      | series tag  | client_business_zip_code                             | Client Business Zip Code                             | text          | text          |
| Yes      | series tag  | client_business_country                              | Client Business Country                              | text          | text          |
| Yes      | series tag  | client_business_telephone_number                     | Client Business Telephone Number                     | text          | text          |
| Yes      | series tag  | name_of_person_with_controlling_interest_in_business | Name of Person with Controlling Interest in Business | text          | text          |
| Yes      | series tag  | description_of_services_provided                     | Description of Services Provided                     | text          | text          |
| Yes      | series tag  | registration_id                                      | Registration ID                                      | text          | text          |
| Yes      | series tag  | application_or_file_id                               | Reporting Period ID                                  | text          | text          |
```

## Time Field

```ls
Value = filing_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = pc_business_address_1,client_business_address_1,year
```

## Data Commands

```ls
series e:tekz-xrvb d:2017-02-03T00:00:00.000Z t:pc_business_zip_code=10003 t:registration_id=PC-201701241000002 t:political_consultant_name="MIRANDA, LUIS A JR" t:pc_business_state="NEW YORK" t:pc_business_name="MIRRAM GROUP LLC" t:pc_business_county="NEW YORK" t:filing_record_identifier=PCF-201701241000002 t:pc_business_country="UNITED STATES" t:description_of_services_provided="DIRECT VOTER CONTACT - MAIL AND MEDIA" t:client_business_zip_code=10034 t:reporting_period="JULY 1 - DECEMBER 31" t:client_business_telephone_number=212-304-0200 t:filing_type="PUBLIC DISCLOSURE" t:pc_business_city="NEW YORK" t:pc_business_telephone_number=212-544-2200 t:client_business_country="UNITED STATES" t:office_held_sought="NYS SENATE 31ST DISTRICT" t:client_business_city="NEW YORK" t:client_type="PUBLIC OFFICIAL/CANDIDATE" t:client_business_state="NEW YORK" t:application_or_file_id=2 t:client_name="ALCANTARA, MARISOL" m:row_number.tekz-xrvb=1

series e:tekz-xrvb d:2017-02-03T00:00:00.000Z t:pc_business_zip_code=10003 t:registration_id=PC-201701241000002 t:political_consultant_name="MIRANDA, LUIS A JR" t:pc_business_state="NEW YORK" t:pc_business_name="MIRRAM GROUP LLC" t:pc_business_county="NEW YORK" t:filing_record_identifier=PCF-201701241000002 t:pc_business_country="UNITED STATES" t:description_of_services_provided="TV COMMERCIAL" t:client_business_zip_code=10954 t:reporting_period="JULY 1 - DECEMBER 31" t:client_business_telephone_number=845-708-5815 t:filing_type="PUBLIC DISCLOSURE" t:pc_business_city="NEW YORK" t:pc_business_telephone_number=212-544-2200 t:client_business_country="UNITED STATES" t:office_held_sought="NYS SENATE 38TH DISTRICT" t:client_business_city=NANUET t:client_type="PUBLIC OFFICIAL/CANDIDATE" t:client_business_state="NEW YORK" t:application_or_file_id=2 t:client_name="CARLUCCI, DAVID" m:row_number.tekz-xrvb=2

series e:tekz-xrvb d:2017-02-03T00:00:00.000Z t:pc_business_zip_code=10003 t:registration_id=PC-201701241000002 t:political_consultant_name="MIRANDA, LUIS A JR" t:pc_business_state="NEW YORK" t:pc_business_name="MIRRAM GROUP LLC" t:pc_business_county="NEW YORK" t:filing_record_identifier=PCF-201701241000002 t:pc_business_country="UNITED STATES" t:description_of_services_provided="DIRECT MAIL" t:client_business_zip_code=10465 t:reporting_period="JULY 1 - DECEMBER 31" t:client_business_telephone_number=347-281-9759 t:filing_type="PUBLIC DISCLOSURE" t:pc_business_city="NEW YORK" t:pc_business_telephone_number=212-544-2200 t:client_business_country="UNITED STATES" t:office_held_sought="NYS ASSEMBLY 85TH DISTRICT" t:client_business_city=BRONX t:client_type="PUBLIC OFFICIAL/CANDIDATE" t:client_business_state="NEW YORK" t:application_or_file_id=2 t:client_name="CRESPO, MARCOS A" m:row_number.tekz-xrvb=3
```

## Meta Commands

```ls
metric m:row_number.tekz-xrvb p:long l:"Row Number"

entity e:tekz-xrvb l:"Political Consultant Filings: Beginning 2016" t:attribution="New York State Department of State (NYS DOS)" t:url=https://data.ny.gov/api/views/tekz-xrvb

property e:tekz-xrvb t:meta.view v:id=tekz-xrvb v:category=Transparency v:attributionLink=http://www.dos.ny.gov/licensing/ v:averageRating=0 v:name="Political Consultant Filings: Beginning 2016" v:attribution="New York State Department of State (NYS DOS)"

property e:tekz-xrvb t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:tekz-xrvb t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| year | reporting_period     | filing_date         | filing_record_identifier | filing_type       | correction_type | political_consultant_name | pc_business_name | pc_business_address_1      | pc_business_city | pc_business_state | pc_business_zip_code | pc_business_county | pc_business_country | pc_business_telephone_number | client_type               | client_name                  | office_held_sought         | client_business_address_1       | client_business_city | client_business_state | client_business_zip_code | client_business_country | client_business_telephone_number | name_of_person_with_controlling_interest_in_business | description_of_services_provided                           | registration_id    | application_or_file_id | 
| ==== | ==================== | =================== | ======================== | ================= | =============== | ========================= | ================ | ========================== | ================ | ================= | ==================== | ================== | =================== | ============================ | ========================= | ============================ | ========================== | =============================== | ==================== | ===================== | ======================== | ======================= | ================================ | ==================================================== | ========================================================== | ================== | ====================== | 
| 2016 | JULY 1 - DECEMBER 31 | 2017-02-03T00:00:00 | PCF-201701241000002      | PUBLIC DISCLOSURE |                 | MIRANDA, LUIS A JR        | MIRRAM GROUP LLC | 215 PARK AVE SOUTH 15TH FL | NEW YORK         | NEW YORK          | 10003                | NEW YORK           | UNITED STATES       | 212-544-2200                 | PUBLIC OFFICIAL/CANDIDATE | ALCANTARA, MARISOL           | NYS SENATE 31ST DISTRICT   | 5030 BROADWAY                   | NEW YORK             | NEW YORK              | 10034                    | UNITED STATES           | 212-304-0200                     |                                                      | DIRECT VOTER CONTACT - MAIL AND MEDIA                      | PC-201701241000002 | 2                      | 
| 2016 | JULY 1 - DECEMBER 31 | 2017-02-03T00:00:00 | PCF-201701241000002      | PUBLIC DISCLOSURE |                 | MIRANDA, LUIS A JR        | MIRRAM GROUP LLC | 215 PARK AVE SOUTH 15TH FL | NEW YORK         | NEW YORK          | 10003                | NEW YORK           | UNITED STATES       | 212-544-2200                 | PUBLIC OFFICIAL/CANDIDATE | CARLUCCI, DAVID              | NYS SENATE 38TH DISTRICT   | PO BOX 833                      | NANUET               | NEW YORK              | 10954                    | UNITED STATES           | 845-708-5815                     |                                                      | TV COMMERCIAL                                              | PC-201701241000002 | 2                      | 
| 2016 | JULY 1 - DECEMBER 31 | 2017-02-03T00:00:00 | PCF-201701241000002      | PUBLIC DISCLOSURE |                 | MIRANDA, LUIS A JR        | MIRRAM GROUP LLC | 215 PARK AVE SOUTH 15TH FL | NEW YORK         | NEW YORK          | 10003                | NEW YORK           | UNITED STATES       | 212-544-2200                 | PUBLIC OFFICIAL/CANDIDATE | CRESPO, MARCOS A             | NYS ASSEMBLY 85TH DISTRICT | 721 VINCENT AVE                 | BRONX                | NEW YORK              | 10465                    | UNITED STATES           | 347-281-9759                     |                                                      | DIRECT MAIL                                                | PC-201701241000002 | 2                      | 
| 2016 | JULY 1 - DECEMBER 31 | 2017-02-03T00:00:00 | PCF-201701241000002      | PUBLIC DISCLOSURE |                 | MIRANDA, LUIS A JR        | MIRRAM GROUP LLC | 215 PARK AVE SOUTH 15TH FL | NEW YORK         | NEW YORK          | 10003                | NEW YORK           | UNITED STATES       | 212-544-2200                 | PUBLIC OFFICIAL/CANDIDATE | DE LA ROSA, CARMEN           | NYS ASSEMBLY 72ND DISTRICT | 452 FORTH WASHINGTON AVE APT 46 | NEW YORK             | NEW YORK              | 10033                    | UNITED STATES           | 646-200-2101                     |                                                      | DIRECT MAIL                                                | PC-201701241000002 | 2                      | 
| 2016 | JULY 1 - DECEMBER 31 | 2017-02-03T00:00:00 | PCF-201701241000002      | PUBLIC DISCLOSURE |                 | MIRANDA, LUIS A JR        | MIRRAM GROUP LLC | 215 PARK AVE SOUTH 15TH FL | NEW YORK         | NEW YORK          | 10003                | NEW YORK           | UNITED STATES       | 212-544-2200                 | PUBLIC OFFICIAL/CANDIDATE | FERRERAS-COPELAND, JULISSA   | NYC COUNCIL DISTRICT 21    | 2440 97TH ST                    | EAST ELMHURST        | NEW YORK              | 11369                    | UNITED STATES           | 917-251-7005                     |                                                      | COMPLIANCE                                                 | PC-201701241000002 | 2                      | 
| 2016 | JULY 1 - DECEMBER 31 | 2017-02-03T00:00:00 | PCF-201701241000002      | PUBLIC DISCLOSURE |                 | MIRANDA, LUIS A JR        | MIRRAM GROUP LLC | 215 PARK AVE SOUTH 15TH FL | NEW YORK         | NEW YORK          | 10003                | NEW YORK           | UNITED STATES       | 212-544-2200                 | PUBLIC OFFICIAL/CANDIDATE | JAMES, LETITIA               | NYC PUBLIC ADVOCATE        | 5030 BROADWAY SUITE 810         | NEW YORK             | NEW YORK              | 10034                    | UNITED STATES           | 212-740-6100                     |                                                      | COMPLIANCE                                                 | PC-201701241000002 | 2                      | 
| 2016 | JULY 1 - DECEMBER 31 | 2017-02-03T00:00:00 | PCF-201701241000002      | PUBLIC DISCLOSURE |                 | MIRANDA, LUIS A JR        | MIRRAM GROUP LLC | 215 PARK AVE SOUTH 15TH FL | NEW YORK         | NEW YORK          | 10003                | NEW YORK           | UNITED STATES       | 212-544-2200                 | PUBLIC OFFICIAL/CANDIDATE | KLEIN, JEFFREY D             | NYS SENATE 34TH DISTRICT   | 2018 WLLIAMSBRIDGE RD           | BRONX                | NEW YORK              | 10461                    | UNITED STATES           | 718-684-2074                     |                                                      | DIRECT MAIL                                                | PC-201701241000002 | 2                      | 
| 2016 | JULY 1 - DECEMBER 31 | 2017-02-03T00:00:00 | PCF-201701241000002      | PUBLIC DISCLOSURE |                 | MIRANDA, LUIS A JR        | MIRRAM GROUP LLC | 215 PARK AVE SOUTH 15TH FL | NEW YORK         | NEW YORK          | 10003                | NEW YORK           | UNITED STATES       | 212-544-2200                 | CLIENT BUSINESS NAME      | 1-10 BUSH TERMINAL OWNER LP  |                            | 220 36TH ST STE 2A              | BROOKLYN             | NEW YORK              | 11232                    | UNITED STATES           | 718-965-6450                     | KIMBALL, ANDREW                                      | STRATEGIC COUNSEL- NYC COUNCIL                             | PC-201701241000002 | 2                      | 
| 2016 | JULY 1 - DECEMBER 31 | 2017-02-03T00:00:00 | PCF-201701241000002      | PUBLIC DISCLOSURE |                 | MIRANDA, LUIS A JR        | MIRRAM GROUP LLC | 215 PARK AVE SOUTH 15TH FL | NEW YORK         | NEW YORK          | 10003                | NEW YORK           | UNITED STATES       | 212-544-2200                 | CLIENT BUSINESS NAME      | 19-20 BUSH TERMINAL OWNER LP |                            | 220 36TH ST STE 2A              | BROOKLYN             | NEW YORK              | 11232                    | UNITED STATES           | 718-965-6450                     | KIMBALL, ANDREW                                      | STRATEGIC COUNSEL- NYC COUNCIL                             | PC-201701241000002 | 2                      | 
| 2016 | JULY 1 - DECEMBER 31 | 2017-02-03T00:00:00 | PCF-201701241000002      | PUBLIC DISCLOSURE |                 | MIRANDA, LUIS A JR        | MIRRAM GROUP LLC | 215 PARK AVE SOUTH 15TH FL | NEW YORK         | NEW YORK          | 10003                | NEW YORK           | UNITED STATES       | 212-544-2200                 | CLIENT BUSINESS NAME      | 2520 JEROME LLC              |                            | 225 WILLOW AVE                  | BRONX                | NEW YORK              | 10454                    | UNITED STATES           | 718-292-6400                     | SEGAL, AARON                                         | STRATEGIC COUNSEL (BUDGET) - NYC COUNCIL AND CITY AGENCIES | PC-201701241000002 | 2                      | 
```