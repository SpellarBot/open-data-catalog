# Recurring Resident Economic Empowerment and Sustainability Programs

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/recurring-resident-economic-empowerment-and-sustainability-programs-a2e08) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/7su9-xgtn) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/7su9-xgtn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/7su9-xgtn/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 7su9-xgtn |
| Name | Recurring Resident Economic Empowerment and Sustainability Programs |
| Attribution | New York City Housing Authority (NYCHA) |
| Category | Social Services |
| Tags | rees, social services, job training, education, ged, financial counseling, entrepreneurship |
| Created | 2013-03-28T19:31:04Z |
| Publication Date | 2013-03-29T18:28:17Z |

## Description

Regulary occuring REES programs

## Columns

```ls
| Included | Schema Type | Field Name      | Name            | Data Type | Render Type |
| ======== | =========== | =============== | =============== | ========= | =========== |
| No       | time        | :updated_at     | updated_at      | meta_data | meta_data   |
| Yes      | series tag  | name_of_program | Name of Program | text      | text        |
| Yes      | series tag  | description     | Description     | text      | text        |
| Yes      | series tag  | days            | Days            | text      | text        |
| Yes      | series tag  | times           | Times           | text      | text        |
| Yes      | series tag  | location        | Location        | text      | text        |
| Yes      | series tag  | phone_number    | Phone Number    | text      | text        |
| Yes      | series tag  | email           | Email           | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:7su9-xgtn d:2013-03-28T13:00:38.000Z t:phone_number=212-487-6607 t:name_of_program="Financial Independence Today (FIT)" t:days="Mon, Tues, Fri" t:location="NYC Financial Empowerment Center at ERDA
38-81 13th Street Long Island City, NY 11101" t:times="9am - 5pm" t:description="FIT is an innovative public/private partnership between UWNYC and ERDA - run in collaboration with NYCHA - aimed at increasing the financial stability of public housing residents who find themselves in rental arrears. ERDA provides critical financial counseling services for public housing residents facing rental arrears and allows them to pay back their rent so they can achieve self-sufficiency and so the housing authority can collect needed revenue.

FIT Interventions Include:
- Rental arrears counseling for residents facing rental arrears
- Long-term financial counseling for all NYCHA residents
- Tenant advocacy services
- Comprehensive public benefits screening and enrollment
- Financial education workshops
- Savings, loans and NYCHA rent payment at the ERDA Federal Credit Union" m:row_number.7su9-xgtn=1

series e:7su9-xgtn d:2013-03-28T13:00:38.000Z t:phone_number=212-487-6607 t:name_of_program="Financial Independence Today (FIT)" t:days="Wed, Thurs" t:location="NYC Financial Empowerment Center at ERDA
38-81 13th Street Long Island City, NY 11101" t:times="9am - 7pm" t:description="FIT is an innovative public/private partnership between UWNYC and ERDA - run in collaboration with NYCHA - aimed at increasing the financial stability of public housing residents who find themselves in rental arrears. ERDA provides critical financial counseling services for public housing residents facing rental arrears and allows them to pay back their rent so they can achieve self-sufficiency and so the housing authority can collect needed revenue.

FIT Interventions Include:
- Rental arrears counseling for residents facing rental arrears
- Long-term financial counseling for all NYCHA residents
- Tenant advocacy services
- Comprehensive public benefits screening and enrollment
- Financial education workshops
- Savings, loans and NYCHA rent payment at the ERDA Federal Credit Union" m:row_number.7su9-xgtn=2

series e:7su9-xgtn d:2013-03-28T13:00:38.000Z t:phone_number=718-289-8100 t:name_of_program="NYCHA Resident Economic Empowerment & Sustainability" t:days="Tues, Thurs" t:location="787 Atlantic Avenue 2nd Floor Brooklyn, NY 11238" t:times=8:30am-10:30am t:description="REES staff provide an overview of: 
? Referrals for employment, training, adult education resources.
? Services available through zone partners, NRTA and financial counseling providers" m:row_number.7su9-xgtn=3
```

## Meta Commands

```ls
metric m:row_number.7su9-xgtn p:long l:"Row Number"

entity e:7su9-xgtn l:"Recurring Resident Economic Empowerment and Sustainability Programs" t:attribution="New York City Housing Authority (NYCHA)" t:url=https://data.cityofnewyork.us/api/views/7su9-xgtn

property e:7su9-xgtn t:meta.view v:id=7su9-xgtn v:category="Social Services" v:attributionLink=http://www.nyc.gov/html/nycha/html/community/rees.shtml v:averageRating=0 v:name="Recurring Resident Economic Empowerment and Sustainability Programs" v:attribution="New York City Housing Authority (NYCHA)"

property e:7su9-xgtn t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:7su9-xgtn t:meta.view.tableauthor v:id=8b43-zkvh v:screenName="Ram S." v:displayName="Ram S."
```

## Top Records

```ls
| :updated_at | name_of_program                                              | description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | days                 | times           | location                                                                              | phone_number  | email                        | 
| =========== | ============================================================ | ======================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================= | ==================== | =============== | ===================================================================================== | ============= | ============================ | 
| 1364475638  | Financial Independence Today (FIT)                           | FIT is an innovative public/private partnership between UWNYC and ERDA - run in collaboration with NYCHA - aimed at increasing the financial stability of public housing residents who find themselves in rental arrears. ERDA provides critical financial counseling services for public housing residents facing rental arrears and allows them to pay back their rent so they can achieve self-sufficiency and so the housing authority can collect needed revenue. FIT Interventions Include: - Rental arrears counseling for residents facing rental arrears - Long-term financial counseling for all NYCHA residents - Tenant advocacy services - Comprehensive public benefits screening and enrollment - Financial education workshops - Savings, loans and NYCHA rent payment at the ERDA Federal Credit Union | Mon, Tues, Fri       | 9am - 5pm       | NYC Financial Empowerment Center at ERDA 38-81 13th Street Long Island City, NY 11101 | 212-487-6607  |                              | 
| 1364475638  | Financial Independence Today (FIT)                           | FIT is an innovative public/private partnership between UWNYC and ERDA - run in collaboration with NYCHA - aimed at increasing the financial stability of public housing residents who find themselves in rental arrears. ERDA provides critical financial counseling services for public housing residents facing rental arrears and allows them to pay back their rent so they can achieve self-sufficiency and so the housing authority can collect needed revenue. FIT Interventions Include: - Rental arrears counseling for residents facing rental arrears - Long-term financial counseling for all NYCHA residents - Tenant advocacy services - Comprehensive public benefits screening and enrollment - Financial education workshops - Savings, loans and NYCHA rent payment at the ERDA Federal Credit Union | Wed, Thurs           | 9am - 7pm       | NYC Financial Empowerment Center at ERDA 38-81 13th Street Long Island City, NY 11101 | 212-487-6607  |                              | 
| 1364475638  | NYCHA Resident Economic Empowerment & Sustainability         | REES staff provide an overview of: ? Referrals for employment, training, adult education resources. ? Services available through zone partners, NRTA and financial counseling providers                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | Tues, Thurs          | 8:30am-10:30am  | 787 Atlantic Avenue 2nd Floor Brooklyn, NY 11238                                      | 718-289-8100  |                              | 
| 1364475638  | Year Up Information Sessions                                 | Year Up?s mission is to close the Opportunity Divide by providing urban young adults with the skills, experience, and support that will empower them to reach their potential through professional careers and higher education. ? Youth ages 18-24 ? ?Independent Living? NYCHA residents that have aged out of Foster Care System ? Hold a High School Diploma/ GED ? Legal United States residency ? Authorized to work in the US ? Highly motivated and eager to learn professional skills ? Interested in a business career including technology or finance Contact Dayanna Torres via email or phone: Dayanna.torres@nycha.nyc.gov                                                                                                                                                                                | Tuesday              | 3:30pm - 5:30pm | 55 Exchange Place Suite 403 New York, NY                                              | (718)218-1538 | Dayanna.torres@nycha.nyc.gov | 
| 1364475638  | REES Financial Counseling (NYC Financial Empowerment Center) | NYCHA worked with the NYC?s Office of Financial Empowerment (OFE) and Neighborhood Trust Financial Partners to bring a satellite Financial Empowerment Center to Manhattanville Houses? Community Center Residents who attend the REES Information Sessions are able to: 1. Download a FREE credit report 2. Receive referrals for individual appointments with financial counseling professionals.                                                                                                                                                                                                                                                                                                                                                                                                                     | Wednesday & Thursday | 9:30am - 1:30pm | Manhattanville Community Center, 530 W. 133rd Street                                  |               |                              | 
```