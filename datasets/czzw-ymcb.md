# Veteran Owned Businesses

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/veteran-owned-businesses) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/czzw-ymcb) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/czzw-ymcb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/czzw-ymcb/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | czzw-ymcb |
| Name | Veteran Owned Businesses |
| Attribution | Cook County Certification |
| Category | Administration & Finance |
| Tags | business, vendors, procurement |
| Created | 2016-07-13T20:59:19Z |
| Publication Date | 2016-08-01T21:12:37Z |

## Description

Cook County Certified Veteran Owned Businesses

## Columns

```ls
| Included | Schema Type | Field Name               | Name                     | Data Type     | Render Type   |
| ======== | =========== | ======================== | ======================== | ============= | ============= |
| Yes      | series tag  | business_name            | Business Name            | text          | text          |
| Yes      | series tag  | dba_name                 | DBA Name                 | text          | text          |
| Yes      | series tag  | phone                    | Phone                    | text          | text          |
| Yes      | series tag  | fax                      | Fax                      | text          | text          |
| Yes      | series tag  | email                    | Email                    | text          | text          |
| No       |             | address_1                | Address 1                | text          | text          |
| No       |             | address_2                | Address 2                | text          | text          |
| No       |             | address_3                | Address 3                | text          | text          |
| Yes      | series tag  | city                     | City                     | text          | text          |
| Yes      | series tag  | state                    | State                    | text          | text          |
| Yes      | series tag  | zip                      | Zip                      | text          | text          |
| Yes      | series tag  | zip4                     | Zip4                     | text          | text          |
| Yes      | series tag  | business_description     | Business Description     | text          | text          |
| Yes      | series tag  | primary_owner_salutation | Primary Owner Salutation | text          | text          |
| Yes      | series tag  | primary_owner_first_name | Primary Owner First Name | text          | text          |
| Yes      | series tag  | primary_owner_last_name  | Primary Owner Last Name  | text          | text          |
| Yes      | series tag  | primary_owner_suffix     | Primary Owner Suffix     | text          | text          |
| Yes      | time        | certification_date       | Certification Date       | calendar_date | calendar_date |
| No       |             | renewal_date             | Renewal Date             | calendar_date | calendar_date |
| No       |             | expiration_date          | Expiration Date          | calendar_date | calendar_date |
| Yes      | series tag  | certified_description    | Certified Description    | text          | text          |
```

## Time Field

```ls
Value = certification_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address_1,address_2,address_3,renewal_date,expiration_date
```

## Data Commands

```ls
series e:czzw-ymcb d:2016-05-23T00:00:00.000Z t:business_name="Two Soldiers and A Marine, LLC" t:zip=60062 t:phone=847-239-7146 t:primary_owner_first_name=Daniel t:business_description="Food Service:  Food Truck Vendor" t:email=delsner@iraqvetfoods.com t:certified_description="Food Service:  Food Truck Vendor" t:state=IL t:primary_owner_last_name=Elsner t:city=Northbrook m:row_number.czzw-ymcb=1

series e:czzw-ymcb d:2016-12-22T00:00:00.000Z t:zip=60707 t:phone=773-837-4876 t:fax=708-452-0278 t:business_description="Snow and Ice Removal Services;Paint, Masonry;Masonry, Concrete, and Stucco Maintenance and Repair (Includes Inside Concrete Sawing Work);Masonry" t:primary_owner_first_name=William t:state=IL t:dba_name="The Newcastle Company" t:primary_owner_last_name=Marrero t:city="Elmwood park" t:business_name="Newcastle Tuckpointing, Inc." t:email=Newcastle129@yahoo.com t:zip4=3331 t:certified_description="Construction:  Painting Services; Masonry Services; Concrete and Stucco Maintenance and Repair; and Snow and Ice Removal Services" m:row_number.czzw-ymcb=2

series e:czzw-ymcb d:2016-05-10T00:00:00.000Z t:zip=60429 t:phone=708-335-4380 t:fax=708-335-4514 t:business_description="Guard and Security Services (Including Traffic Control)" t:primary_owner_first_name=Lawrence t:state=IL t:primary_owner_last_name=Moore t:city="Hazel Crest" t:business_name="Gideon's 300 Security Services, Inc." t:email=info@g300security.com t:zip4=1340 t:primary_owner_salutation=Mr. t:certified_description="Security:  Safety and Security Consultants; Guard and Security Services" m:row_number.czzw-ymcb=3
```

## Meta Commands

```ls
metric m:row_number.czzw-ymcb p:long l:"Row Number"

entity e:czzw-ymcb l:"Veteran Owned Businesses" t:attribution="Cook County Certification" t:url=https://data.cityofchicago.org/api/views/czzw-ymcb

property e:czzw-ymcb t:meta.view v:id=czzw-ymcb v:category="Administration & Finance" v:attributionLink=https://www.cookcountyil.gov/service/mbewbevbe-certification v:averageRating=0 v:name="Veteran Owned Businesses" v:attribution="Cook County Certification"

property e:czzw-ymcb t:meta.view.owner v:id=vewm-vupz v:screenName="Jonathan Levy" v:displayName="Jonathan Levy"

property e:czzw-ymcb t:meta.view.tableauthor v:id=vewm-vupz v:screenName="Jonathan Levy" v:roleName=administrator v:displayName="Jonathan Levy"
```

## Top Records

```ls
| business_name                        | dba_name              | phone        | fax          | email                          | address_1                            | address_2 | address_3 | city         | state | zip   | zip4 | business_description                                                                                                                                                                      | primary_owner_salutation | primary_owner_first_name | primary_owner_last_name | primary_owner_suffix | certification_date  | renewal_date        | expiration_date     | certified_description                                                                                                                       | 
| ==================================== | ===================== | ============ | ============ | ============================== | ==================================== | ========= | ========= | ============ | ===== | ===== | ==== | ========================================================================================================================================================================================= | ======================== | ======================== | ======================= | ==================== | =================== | =================== | =================== | =========================================================================================================================================== | 
| Two Soldiers and A Marine, LLC       |                       | 847-239-7146 |              | delsner@iraqvetfoods.com       | 1363 Shermer Road                    |           |           | Northbrook   | IL    | 60062 |      | Food Service: Food Truck Vendor                                                                                                                                                           |                          | Daniel                   | Elsner                  |                      | 2016-05-23T00:00:00 | 2017-05-23T00:00:00 | 2020-05-23T00:00:00 | Food Service: Food Truck Vendor                                                                                                             | 
| Newcastle Tuckpointing, Inc.         | The Newcastle Company | 773-837-4876 | 708-452-0278 | Newcastle129@yahoo.com         | 1800 N 78th Ave                      |           |           | Elmwood park | IL    | 60707 | 3331 | Snow and Ice Removal Services;Paint, Masonry;Masonry, Concrete, and Stucco Maintenance and Repair (Includes Inside Concrete Sawing Work);Masonry                                          |                          | William                  | Marrero                 |                      | 2016-12-22T00:00:00 | 2017-12-22T00:00:00 | 2021-12-22T00:00:00 | Construction: Painting Services; Masonry Services; Concrete and Stucco Maintenance and Repair; and Snow and Ice Removal Services            | 
| Gideon's 300 Security Services, Inc. |                       | 708-335-4380 | 708-335-4514 | info@g300security.com          | 16901 Dixie Highway                  |           |           | Hazel Crest  | IL    | 60429 | 1340 | Guard and Security Services (Including Traffic Control)                                                                                                                                   | Mr.                      | Lawrence                 | Moore                   |                      | 2016-05-10T00:00:00 | 2017-05-10T00:00:00 | 2020-05-10T00:00:00 | Security: Safety and Security Consultants; Guard and Security Services                                                                      | 
| ONeill Contractors, Inc.             |                       | 773-774-2029 | 888-571-4822 | oneillcontractors@gmail.com    | 4307 Regency Drive                   |           |           | Glenview     | IL    | 60025 | 5209 | Construction                                                                                                                                                                              | Ms.                      | Kaney                    | ONeill                  |                      | 2016-07-12T00:00:00 | 2017-07-12T00:00:00 | 2019-07-12T00:00:00 | Construction: Roofing Contractor                                                                                                            | 
| Virtual Energy Solutions, Inc.       | VES                   | 312-583-7023 |              | svela@veschicago.com           | 6252 W 59th St                       |           |           | Chicago      | IL    | 60638 | 3439 | Professional Services: Engineering Services; Consulting: Architectural, Mechanical, Electrical, Plumbing and Fire Protection                                                              | Mr.                      | Samuel                   | Vela                    |                      | 2016-03-18T00:00:00 | 2017-05-17T00:00:00 | 2021-03-18T00:00:00 | Professional Services: Engineering Services; Consulting: Architectural, Mechanical, Electrical, Plumbing and Fire Protection                | 
| Frega Associates, Ltd.               |                       | 312-663-0640 | 312-663-0834 | jvfrega@fregaarchitects.com    | 411 S. Wells Street                  | 5th Floor |           | Chicago      | IL    | 60607 | 3924 | Professional Service: Architectural Services                                                                                                                                              | Mr.                      | Paul                     | Krutulis                |                      | 2016-08-25T00:00:00 | 2017-10-06T00:00:00 | 2020-10-06T00:00:00 | Professional Service: Architectural Services                                                                                                | 
| Strike First Security Labs, LLC      |                       | 312-546-1060 | 312-546-1060 | jones@strikefirstlabs.com      | 1463 E. Evergreen Drive              |           |           | Palatine     | IL    | 60074 |      | Technology                                                                                                                                                                                | Mr.                      | Joseph                   | Jones                   |                      | 2014-02-24T00:00:00 | 2015-02-24T00:00:00 | 2017-02-24T00:00:00 | Technology                                                                                                                                  | 
| Vernate Construction Inc.            |                       | 708-420-8396 | 708-420-8396 | nbrown@vernateconstruction.com | 1392 west 103rd st. Chicago IL 60643 |           |           | Chicago      | IL    | 60643 |      | Construction: Carpentry, Drywall, Taping and Painting                                                                                                                                     | Mr.                      | Nate                     | Brown                   |                      | 2016-04-04T00:00:00 | 2017-06-03T00:00:00 | 2020-04-04T00:00:00 |                                                                                                                                             | 
| CHESS TECHNOLOGY LLC.                |                       | 630-202-6617 | 000-000-0000 | rjones@chesstechs.com          | 9238 S. Bishop St. Apt. 3            |           |           | Chicago      | IL    | 60620 |      | NAICS 541512 Computer hardware consulting services or consultants; NAICS 541519 Software installation services, computer; NAICS 811212 Computer and Office Machine Repair and Maintenance |                          | Ramsey                   | Ponc De L Jones         |                      | 2016-10-19T00:00:00 | 2017-10-19T00:00:00 | 2020-10-19T00:00:00 | Technology: Network Infrastructure and CCTV ? Installation, Maintenance and Monitoring; Desktop Support; Data Center Service and Solutions; | 
| Arete Consulting Group LLC           |                       | 708-213-7995 | 708-575-9434 | psims@actscompany.com          | 1 So. Wacker Drive                   | Suite 200 |           | Chicago      | IL    | 60606 |      | Technology                                                                                                                                                                                | MR.                      | Paul C.                  | Sims                    |                      | 2016-09-14T00:00:00 | 2017-09-14T00:00:00 | 2020-09-14T00:00:00 | Technology: Cyber Security; Information Assurance and Managed IT Services                                                                   | 
```