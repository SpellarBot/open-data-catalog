# Home Occupation Certificates

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/home-occupation-certificates) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/sryj-zivk) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/sryj-zivk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/sryj-zivk/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | sryj-zivk |
| Name | Home Occupation Certificates |
| Attribution | Montgomery County, MD |
| Category | Licenses/Permits |
| Tags | home, occupation, certificates |
| Created | 2016-04-12T22:30:49Z |
| Publication Date | 2016-06-20T15:27:09Z |

## Description

This dataset contains any homeowner in Montgomery County, who operates a home-based business which generates more than five visits to the site per week, or who provides a non-resident employee, must register his or her business with DPS.  In addition, all home-health practitioners and lawn maintenance services are required to register. Update Frequency - Daily

## Columns

```ls
| Included | Schema Type    | Field Name                          | Name                             | Data Type     | Render Type   |
| ======== | ============== | =================================== | ================================ | ============= | ============= |
| Yes      | series tag     | application_type                    | Application Type                 | text          | text          |
| Yes      | series tag     | application_number                  | Application Number               | text          | text          |
| Yes      | series tag     | city                                | City                             | text          | text          |
| No       |                | next_renewal_date                   | Comments                         | text          | text          |
| No       |                | license_expiration_date             | Expiration date                  | calendar_date | calendar_date |
| No       |                | final_date                          | Final date                       | calendar_date | calendar_date |
| Yes      | series tag     | home_occupation_category            | Home Occupation Category         | text          | text          |
| Yes      | time           | issued_date                         | Issue Date                       | calendar_date | calendar_date |
| Yes      | series tag     | work_location                       | Location                         | text          | text          |
| Yes      | numeric metric | number_of_client_visits_per_day     | Number of Client Visits Per Day  | number        | number        |
| Yes      | numeric metric | number_of_client_visits_per_week    | Number of Client visits Per Week | number        | number        |
| Yes      | numeric metric | number_of_commercial_vehicles       | Number of commercial vehicles    | number        | number        |
| Yes      | numeric metric | number_of_employees                 | Number of employees              | number        | number        |
| Yes      | numeric metric | number_of_non_residential_employees | Number of non-resident employees | number        | number        |
| Yes      | series tag     | parking                             | Parking                          | text          | text          |
| Yes      | series tag     | post_direction                      | Street Post direction            | text          | text          |
| Yes      | series tag     | pre_direction                       | Street Pre direction             | text          | text          |
| No       |                | processed_date                      | Date Processed                   | calendar_date | calendar_date |
| Yes      | series tag     | product_sold                        | Products sold                    | text          | text          |
| Yes      | series tag     | proposed_use                        | Proposed Use                     | text          | text          |
| Yes      | series tag     | registered_home                     | Registered Home                  | text          | text          |
| Yes      | numeric metric | square_foot_business                | Square FT Business               | number        | number        |
| Yes      | numeric metric | square_foot_dwelling                | Square FT Dwelling               | number        | number        |
| Yes      | series tag     | state                               | State                            | text          | text          |
| Yes      | series tag     | street_name_of_work_location        | Street Name                      | text          | text          |
| Yes      | series tag     | street_number                       | Street Number                    | text          | text          |
| Yes      | series tag     | street_suffix                       | Street Suffix                    | text          | text          |
| Yes      | series tag     | zip_code                            | Zip Code                         | text          | text          |
```

## Time Field

```ls
Value = issued_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = next_renewal_date,license_expiration_date,final_date,processed_date
```

## Data Commands

```ls
series e:sryj-zivk d:2002-07-25T00:00:00.000Z t:application_type="HOME OCCUPATION CERTIFICATE" t:registered_home=Y t:street_name_of_work_location=RANDOLPH t:zip_code=20906 t:street_suffix=RD t:state=MD t:street_number=4501 t:proposed_use="LAWN SERVICE" t:application_number=217932 t:city="SILVER SPRING" m:square_foot_business=50 m:number_of_employees=2 m:number_of_commercial_vehicles=1 m:number_of_non_residential_employees=1 m:number_of_client_visits_per_day=0 m:number_of_client_visits_per_week=0 m:square_foot_dwelling=648

series e:sryj-zivk d:2006-04-19T00:00:00.000Z t:application_type="HOME OCCUPATION CERTIFICATE" t:parking=4 t:registered_home=Y t:street_name_of_work_location="NEW HAMPSHIRE" t:zip_code=20904 t:home_occupation_category=LAWN t:street_suffix=AVE t:state=MD t:proposed_use="CUTTING LAWNS - LAWN SERVICE" t:city="SILVER SPRING" t:product_sold=NONE t:street_number=12900 t:application_number=244982 m:square_foot_business=300 m:number_of_employees=4 m:number_of_commercial_vehicles=0 m:number_of_non_residential_employees=1 m:number_of_client_visits_per_day=1 m:number_of_client_visits_per_week=1 m:square_foot_dwelling=2624

series e:sryj-zivk d:1995-09-12T00:00:00.000Z t:application_type="HOME OCCUPATION CERTIFICATE" t:registered_home=Y t:street_name_of_work_location=EPPING t:zip_code=20906 t:street_suffix=TER t:home_occupation_category=COSMT t:state=MD t:street_number=12718 t:proposed_use=HO-ACUPUNCTURE t:application_number=10350 t:city="SILVER SPRING" m:square_foot_business=63 m:number_of_employees=1 m:number_of_commercial_vehicles=0 m:number_of_non_residential_employees=0 m:number_of_client_visits_per_day=3 m:number_of_client_visits_per_week=18 m:square_foot_dwelling=300
```

## Meta Commands

```ls
metric m:number_of_client_visits_per_day p:integer l:"Number of Client Visits Per Day" d:"Number of client visits per day" t:dataTypeName=number

metric m:number_of_client_visits_per_week p:integer l:"Number of Client visits Per Week" d:"Number of client visits per week" t:dataTypeName=number

metric m:number_of_commercial_vehicles p:integer l:"Number of commercial vehicles" d:"Number of commercial vehicles" t:dataTypeName=number

metric m:number_of_employees p:integer l:"Number of employees" d:"Number of employees" t:dataTypeName=number

metric m:number_of_non_residential_employees p:integer l:"Number of non-resident employees" d:"Number of non-resident employees" t:dataTypeName=number

metric m:square_foot_business p:integer l:"Square FT Business" d:"Square feet for the business" t:dataTypeName=number

metric m:square_foot_dwelling p:integer l:"Square FT Dwelling" d:"Square feet for the dwelling" t:dataTypeName=number

entity e:sryj-zivk l:"Home Occupation Certificates" t:attribution="Montgomery County, MD" t:url=https://data.montgomerycountymd.gov/api/views/sryj-zivk

property e:sryj-zivk t:meta.view v:id=sryj-zivk v:category=Licenses/Permits v:averageRating=0 v:name="Home Occupation Certificates" v:attribution="Montgomery County, MD"

property e:sryj-zivk t:meta.view.license v:name="Public Domain"

property e:sryj-zivk t:meta.view.owner v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"

property e:sryj-zivk t:meta.view.tableauthor v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:roleName=administrator v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"
```

## Top Records

```ls
| application_type            | application_number | city          | next_renewal_date                                                                                                                                                    | license_expiration_date | final_date          | home_occupation_category | issued_date         | work_location | number_of_client_visits_per_day | number_of_client_visits_per_week | number_of_commercial_vehicles | number_of_employees | number_of_non_residential_employees | parking | post_direction | pre_direction | processed_date      | product_sold       | proposed_use                                       | registered_home | square_foot_business | square_foot_dwelling | state | street_name_of_work_location | street_number | street_suffix | zip_code | 
| =========================== | ================== | ============= | ==================================================================================================================================================================== | ======================= | =================== | ======================== | =================== | ============= | =============================== | ================================ | ============================= | =================== | =================================== | ======= | ============== | ============= | =================== | ================== | ================================================== | =============== | ==================== | ==================== | ===== | ============================ | ============= | ============= | ======== | 
| HOME OCCUPATION CERTIFICATE | 217932             | SILVER SPRING | lawn maintenance                                                                                                                                                     |                         | 2002-07-25T00:00:00 |                          | 2002-07-25T00:00:00 |               | 0                               | 0                                | 1                             | 2                   | 1                                   |         |                |               | 2002-07-11T00:00:00 |                    | LAWN SERVICE                                       | Y               | 50                   | 648                  | MD    | RANDOLPH                     | 4501          | RD            | 20906    | 
| HOME OCCUPATION CERTIFICATE | 244982             | SILVER SPRING |                                                                                                                                                                      |                         | 2006-04-19T00:00:00 | LAWN                     | 2006-04-19T00:00:00 |               | 1                               | 1                                | 0                             | 4                   | 1                                   | 4       |                |               | 2006-04-10T00:00:00 | NONE               | CUTTING LAWNS - LAWN SERVICE                       | Y               | 300                  | 2624                 | MD    | NEW HAMPSHIRE                | 12900         | AVE           | 20904    | 
| HOME OCCUPATION CERTIFICATE | 10350              | SILVER SPRING |                                                                                                                                                                      |                         |                     | COSMT                    | 1995-09-12T00:00:00 |               | 3                               | 18                               | 0                             | 1                   | 0                                   |         |                |               |                     |                    | HO-ACUPUNCTURE                                     | Y               | 63                   | 300                  | MD    | EPPING                       | 12718         | TER           | 20906    | 
| HOME OCCUPATION CERTIFICATE | 10118              | SILVER SPRING |                                                                                                                                                                      |                         |                     | ARTIN                    | 1992-03-13T00:00:00 |               | 5                               | 19                               | 0                             | 1                   | 0                                   |         |                |               |                     |                    | HO-VIOLIN INSTRUCTION                              | Y               | 216                  | 1850                 | MD    | MINDEN                       | 3903          | RD            | 20906    | 
| HOME OCCUPATION CERTIFICATE | 254535             | SILVER SPRING |                                                                                                                                                                      |                         | 2007-09-14T00:00:00 | COSMT                    | 2007-09-14T00:00:00 |               | 5                               | 20                               | 0                             | 0                   | 0                                   | 4       |                |               | 2007-09-10T00:00:00 | NO SALES PERMITTED | BEAUTY CARE, HAIR CARE SERVICES                    | Y               | 650                  | 8800                 | MD    | BRIGGS CHANEY                | 2509          | RD            | 20905    | 
| HOME OCCUPATION CERTIFICATE | 210903             | SILVER SPRING | health practice                                                                                                                                                      |                         |                     | CSW                      | 2001-05-09T00:00:00 |               | 4                               | 16                               | 0                             | 2                   | 1                                   | 4       |                |               | 2001-05-09T00:00:00 | N/A                | LICENSED CLINICAL SOCIAL WORKER OFFICE             | Y               | 447                  | 4875                 | MD    | COLESVILLE                   | 8931          | RD            | 20910    | 
| HOME OCCUPATION CERTIFICATE | 10303              | SILVER SPRING |                                                                                                                                                                      |                         |                     |                          | 1994-08-05T00:00:00 |               | 0                               | 0                                | 0                             | 0                   | 0                                   |         |                |               |                     |                    | HHP-PODIATRIST                                     | N               | 0                    | 0                    | MD    | COLESVILLE                   | 9211          | RD            | 20910    | 
| HOME OCCUPATION CERTIFICATE | 236487             | SPENCERVILLE  | Home Tailering Business-(Clothing alterations)                                                                                                                       |                         | 2005-05-26T00:00:00 |                          | 2005-05-26T00:00:00 |               | 2                               | 10                               | 0                             | 0                   | 0                                   |         |                |               | 2005-05-09T00:00:00 |                    | HOME TAILORING BUISNESS                            | Y               | 500                  | 4000                 | MD    | SPENCERVILLE                 | 2300          | RD            | 20868    | 
| HOME OCCUPATION CERTIFICATE | 256976             | ROCKVILLE     | Suite 808                                                                                                                                                            |                         | 2008-03-11T00:00:00 |                          | 2008-03-11T00:00:00 |               | 0                               | 0                                | 0                             | 1                   | 0                                   | 2       |                |               | 2008-03-11T00:00:00 |                    | CENTRALIZED MAIL, EMAIL, & PHONE CALLS FOR INVESTM | Y               | 250                  | 1044                 | MD    | OLD GEORGETOWN               | 11710         | RD            | 20852    | 
| HOME OCCUPATION CERTIFICATE | 257437             | SILVER SPRING | PRIMARY USE: Laser (permanent facial & rechair reduction & wrinkles reduction rejuvenator) # of Employees 2 (including applicant) # of Client Visits: 4; 20 per Week |                         |                     |                          |                     |               | 4                               | 20                               | 0                             | 1                   | 1                                   |         |                |               | 2008-04-17T00:00:00 |                    |                                                    | N               | 660                  | 2440                 | MD    | GEORGIA                      | 10705         | AVE           | 20902    | 
```