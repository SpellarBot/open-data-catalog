# License Event Notification Service (LENS) Customers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/license-event-notification-service-lens-customers) |
| Metadata | [Link](https://data.ny.gov/api/views/tt84-bydt) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/tt84-bydt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/tt84-bydt/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | tt84-bydt |
| Name | License Event Notification Service (LENS) Customers |
| Attribution | New York State Department of Motor Vehicles |
| Category | Transportation |
| Tags | driver, qualification, license, employer |
| Created | 2013-02-28T20:00:03Z |
| Publication Date | 2017-04-07T22:18:28Z |

## Description

The License Event Notification Service (LENS) is a tool that enables LENS customers to monitor a set of drivers? qualifications, and to receive notifications of changes to drivers? qualifications. The source for LENS drivers? information is the New York State Department of Motor Vehicles Driving Record. LENS customers include employers of drivers, insurers of drivers and entities that regulate drivers or their employers.

## Columns

```ls
| Included | Schema Type    | Field Name                                            | Name                                                   | Data Type     | Render Type   |
| ======== | ============== | ===================================================== | ====================================================== | ============= | ============= |
| Yes      | series tag     | customer                                              | Customer                                               | text          | text          |
| Yes      | series tag     | street_address                                        | Street Address                                         | text          | text          |
| No       |                | address_line_2                                        | Address Line 2                                         | text          | text          |
| Yes      | series tag     | city                                                  | City                                                   | text          | text          |
| Yes      | series tag     | state                                                 | State                                                  | text          | text          |
| Yes      | series tag     | zip_code                                              | Zip Code                                               | text          | text          |
| Yes      | series tag     | contact_person                                        | Contact Person                                         | text          | text          |
| Yes      | series tag     | phone                                                 | Phone                                                  | text          | text          |
| Yes      | series tag     | e_mail                                                | E-mail                                                 | email         | email         |
| Yes      | time           | date_enrolled                                         | Date Enrolled                                          | calendar_date | calendar_date |
| Yes      | series tag     | vat202_category                                       | VAT202 Category                                        | text          | text          |
| Yes      | series tag     | status                                                | Status                                                 | text          | text          |
| No       |                | observation_date                                      | Observation Date                                       | calendar_date | calendar_date |
| Yes      | series tag     | crash_notification                                    | Crash Notification                                     | text          | text          |
| Yes      | series tag     | conviction_notification                               | Conviction Notification                                | text          | text          |
| Yes      | series tag     | suspension_notification                               | Suspension Notification                                | text          | text          |
| Yes      | series tag     | insurance_pt_reduction_course_completion_notification | Insurance Pt. Reduction Course Completion Notification | text          | text          |
| Yes      | series tag     | driver_status_change_notification                     | Driver Status Change Notification                      | text          | text          |
| Yes      | series tag     | license_expiration_notification                       | License Expiration Notification                        | text          | text          |
| Yes      | series tag     | hazardous_material_endorsement_notification           | Hazardous Material Endorsement Notification            | text          | text          |
| Yes      | series tag     | cdl_medical_certification_status_change               | CDL Medical Certification Status Change                | text          | text          |
| Yes      | series tag     | ticket_notification                                   | Ticket Notification                                    | text          | text          |
| Yes      | numeric metric | number_of_drivers_monitored                           | Number of Drivers Monitored                            | number        | number        |
| No       |                | date_of_most_recent_driver_addition                   | Date of Most Recent Driver Addition                    | calendar_date | calendar_date |
| No       |                | date_of_most_recent_driver_deletion                   | Date of Most Recent Driver Deletion                    | calendar_date | calendar_date |
| Yes      | numeric metric | number_of_lens_interface_users                        | Number of LENS Interface Users                         | number        | number        |
```

## Time Field

```ls
Value = date_enrolled
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address_line_2,observation_date,date_of_most_recent_driver_addition,date_of_most_recent_driver_deletion
```

## Data Commands

```ls
series e:tt84-bydt d:2010-01-07T00:00:00.000Z t:conviction_notification=Y t:cdl_medical_certification_status_change=N t:phone=3155982900 t:zip_code=13069 t:status=ACTIVE t:state=NY t:contact_person="JAMES BOWERS" t:customer="1 ST FIRE DISTRICT TOWN OF GRANBY" t:license_expiration_notification=Y t:city=FULTON t:insurance_pt_reduction_course_completion_notification=Y t:suspension_notification=Y t:ticket_notification=N t:crash_notification=Y t:e_mail=bigguy-41@hotmail.com t:hazardous_material_endorsement_notification=N t:street_address="PO BOX 351" t:vat202_category=EXEMPT t:driver_status_change_notification=Y m:number_of_lens_interface_users=1 m:number_of_drivers_monitored=37

series e:tt84-bydt d:2013-02-11T00:00:00.000Z t:conviction_notification=Y t:cdl_medical_certification_status_change=N t:phone=7182491207 t:zip_code=11230 t:status=ACTIVE t:state=NY t:contact_person="ALBERT FOUERTI" t:customer="1 STOP ELECTRONIC CENTER INC" t:license_expiration_notification=Y t:city=BROOKLYN t:insurance_pt_reduction_course_completion_notification=Y t:suspension_notification=Y t:ticket_notification=N t:crash_notification=Y t:e_mail=ALBERT.F@1STOPCAMERA.COM t:hazardous_material_endorsement_notification=Y t:street_address="1100 CONEY ISLAND AVE" t:vat202_category=PAYING t:driver_status_change_notification=N m:number_of_lens_interface_users=0 m:number_of_drivers_monitored=22

series e:tt84-bydt d:2006-09-15T00:00:00.000Z t:conviction_notification=Y t:cdl_medical_certification_status_change=N t:phone=6317237298 t:zip_code=11978 t:status=ACTIVE t:state=NY t:contact_person="THOMAS CONNELL" t:customer="106TH LOGISTICS READINESS SQUADRON" t:license_expiration_notification=Y t:city="WESTHAMPTON BCH" t:insurance_pt_reduction_course_completion_notification=Y t:suspension_notification=Y t:ticket_notification=N t:crash_notification=Y t:e_mail=THOMAS.G.CONNELL.MIL@MAIL.MIL t:hazardous_material_endorsement_notification=N t:street_address="150 RIVERHEAD RD" t:vat202_category=EXEMPT t:driver_status_change_notification=Y m:number_of_lens_interface_users=4 m:number_of_drivers_monitored=635
```

## Meta Commands

```ls
metric m:number_of_drivers_monitored p:integer l:"Number of Drivers Monitored" t:dataTypeName=number

metric m:number_of_lens_interface_users p:integer l:"Number of LENS Interface Users" t:dataTypeName=number

entity e:tt84-bydt l:"License Event Notification Service (LENS) Customers" t:attribution="New York State Department of Motor Vehicles" t:url=https://data.ny.gov/api/views/tt84-bydt

property e:tt84-bydt t:meta.view v:id=tt84-bydt v:category=Transportation v:attributionLink=http://www.dmv.ny.gov/lens.htm v:averageRating=0 v:name="License Event Notification Service (LENS) Customers" v:attribution="New York State Department of Motor Vehicles"

property e:tt84-bydt t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:tt84-bydt t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:tt84-bydt t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| customer                             | street_address           | address_line_2 | city            | state | zip_code | contact_person    | phone      | e_mail                          | date_enrolled       | vat202_category | status | observation_date    | crash_notification | conviction_notification | suspension_notification | insurance_pt_reduction_course_completion_notification | driver_status_change_notification | license_expiration_notification | hazardous_material_endorsement_notification | cdl_medical_certification_status_change | ticket_notification | number_of_drivers_monitored | date_of_most_recent_driver_addition | date_of_most_recent_driver_deletion | number_of_lens_interface_users | 
| ==================================== | ======================== | ============== | =============== | ===== | ======== | ================= | ========== | =============================== | =================== | =============== | ====== | =================== | ================== | ======================= | ======================= | ===================================================== | ================================= | =============================== | =========================================== | ======================================= | =================== | =========================== | =================================== | =================================== | ============================== | 
| 1 ST FIRE DISTRICT TOWN OF GRANBY    | PO BOX 351               |                | FULTON          | NY    | 13069    | JAMES BOWERS      | 3155982900 | bigguy-41@hotmail.com           | 2010-01-07T00:00:00 | EXEMPT          | ACTIVE | 2017-04-07T00:00:00 | Y                  | Y                       | Y                       | Y                                                     | Y                                 | Y                               | N                                           | N                                       | N                   | 37                          | 2016-12-17T00:00:00                 | 2016-12-17T00:00:00                 | 1                              | 
| 1 STOP ELECTRONIC CENTER INC         | 1100 CONEY ISLAND AVE    |                | BROOKLYN        | NY    | 11230    | ALBERT FOUERTI    | 7182491207 | ALBERT.F@1STOPCAMERA.COM        | 2013-02-11T00:00:00 | PAYING          | ACTIVE | 2017-04-07T00:00:00 | Y                  | Y                       | Y                       | Y                                                     | N                                 | Y                               | Y                                           | N                                       | N                   | 22                          | 2015-01-19T00:00:00                 | 2015-01-05T00:00:00                 | 0                              | 
| 106TH LOGISTICS READINESS SQUADRON   | 150 RIVERHEAD RD         | BUILDING 250   | WESTHAMPTON BCH | NY    | 11978    | THOMAS CONNELL    | 6317237298 | THOMAS.G.CONNELL.MIL@MAIL.MIL   | 2006-09-15T00:00:00 | EXEMPT          | ACTIVE | 2017-04-07T00:00:00 | Y                  | Y                       | Y                       | Y                                                     | Y                                 | Y                               | N                                           | N                                       | N                   | 635                         | 2017-03-31T00:00:00                 | 2017-04-01T00:00:00                 | 4                              | 
| 109TH SECURITY FORCES SQUADRON       | 1 AIR NATIONAL GUARD RD. | BLDG #26       | SCOTIA          | NY    | 12302    | JOSHUA WALTERS    | 5183442605 | JOSHUA.J.WALTERS3.MIL@MAIL.MIL  | 2009-08-06T00:00:00 | EXEMPT          | ACTIVE | 2017-04-07T00:00:00 | Y                  | Y                       | Y                       | N                                                     | Y                                 | Y                               | N                                           | Y                                       | N                   | 252                         | 2015-06-12T00:00:00                 | 2015-03-05T00:00:00                 | 4                              | 
| 1553 HARLEM RD INC                   | P.O.B 1651               |                | BUFFALO         | NY    | 14240    | JEFF SCHMITT      | 7168937060 | DSCHMITT@NATIONALCOURIERINC.COM | 2005-06-27T00:00:00 | PAYING          | ACTIVE | 2017-04-07T00:00:00 | Y                  | Y                       | Y                       | N                                                     | N                                 | Y                               | Y                                           | N                                       | N                   | 3                           | 2013-08-01T00:00:00                 | 2013-12-04T00:00:00                 | 1                              | 
| 1-800-GOT-JUNK                       | 828 HOOSICK ROAD         |                | TROY            | NY    | 12180    | CARL SCHILLING    | 5182791634 | carl.schilling@1800gotjunk.com  | 2011-10-20T00:00:00 | PAYING          | ACTIVE | 2017-04-07T00:00:00 | Y                  | Y                       | Y                       | Y                                                     | Y                                 | Y                               | Y                                           | N                                       | N                   | 0                           |                                     |                                     | 1                              | 
| 1936 TRUCKING, INC.                  | 630 E. 133RD STREET      |                | BRONX           | NY    | 10454    | JEFFREY GAMSS     | 7185852882 | 1936trucking@gmail.com          | 2008-03-06T00:00:00 | PAYING          | ACTIVE | 2017-04-07T00:00:00 | Y                  | Y                       | Y                       | Y                                                     | Y                                 | Y                               | Y                                           | N                                       | N                   | 2                           | 2014-02-19T00:00:00                 | 2016-03-07T00:00:00                 | 1                              | 
| 21ST CENTURY POOL AND PATIO WEST INC | 3736 VESTAL PARKWAY E    |                | VESTAL          | NY    | 13850    | ANGELA B SULLIVAN | 6077296000 | ANGELA@21STPOOL.COM             | 2015-12-09T00:00:00 | PAYING          | ACTIVE | 2017-04-07T00:00:00 | Y                  | Y                       | Y                       | Y                                                     | Y                                 | Y                               | N                                           | N                                       | N                   | 12                          | 2017-03-28T00:00:00                 |                                     | 1                              | 
| 2740 TRUCKING LLC                    | 2740 NOSTRAND AVE        |                | BROOKLYN        | NY    | 11210    | FRANK S MESSINA   | 6464991452 | FRANK@PLAZACARS.COM             | 2016-12-23T00:00:00 | PAYING          | ACTIVE | 2017-04-07T00:00:00 | Y                  | Y                       | Y                       | Y                                                     | Y                                 | Y                               | Y                                           | Y                                       | N                   | 0                           |                                     |                                     | 1                              | 
| 275 TECHNOLOGY SOLUTIONS             | 35 N. TYSON AVENUE       | SUITE 202      | FLORAL PARK     | NY    | 11001    | MARTIN J BROPHY   | 5168331333 | SALES@SAFEWAYFIRE.COM           | 2015-10-21T00:00:00 | PAYING          | ACTIVE | 2017-04-07T00:00:00 | Y                  | Y                       | Y                       | Y                                                     | Y                                 | Y                               | Y                                           | N                                       | N                   | 30                          | 2017-01-03T00:00:00                 | 2016-01-22T00:00:00                 | 1                              | 
```