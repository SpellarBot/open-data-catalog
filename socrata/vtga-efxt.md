# State of Iowa Out-of-State Travel Reimbursements

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-of-iowa-out-of-state-travel-reimbursements) |
| Metadata | [Link](https://data.iowa.gov/api/views/vtga-efxt) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/vtga-efxt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/vtga-efxt/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | vtga-efxt |
| Name | State of Iowa Out-of-State Travel Reimbursements |
| Attribution | Iowa Department of Administrative Services, State Accounting Enterprise, I3 Data Warehouse |
| Category | Government |
| Tags | out-of-state travel, travel reimbursements, state employees |
| Created | 2014-11-06T21:55:37Z |
| Publication Date | 2015-09-16T14:36:37Z |

## Description

Dataset provides information on out-of-state travel including amount reimbursed, source of funds, time frame for traveling, purpose for traveling, and destination starting July 1, 2011 through current fiscal year, year to date. The state fiscal year runs from July 1 to the following June 30 and is numbered for the calendar year in which it ends. The State of Iowa operates on a modified accrual basis which provides that encumbrances on June 30 must be paid within 60 days after year end.

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type     | Render Type   |
| ======== | ============== | ====================== | ====================== | ============= | ============= |
| No       |                | fiscal_year            | Fiscal Year            | number        | number        |
| Yes      | series tag     | tda                    | TDA#                   | text          | text          |
| Yes      | series tag     | function               | Function               | text          | text          |
| Yes      | series tag     | spec_dept              | Spec Dept              | text          | text          |
| Yes      | series tag     | dept_1                 | Dept #                 | text          | text          |
| Yes      | series tag     | dept_2                 | Dept                   | text          | text          |
| Yes      | series tag     | division               | Division               | text          | text          |
| Yes      | series tag     | legal_name             | Name                   | text          | text          |
| Yes      | series tag     | job_title              | Job Title              | text          | text          |
| Yes      | series tag     | event                  | Event                  | text          | text          |
| Yes      | series tag     | departure_city         | Departure City         | text          | text          |
| Yes      | series tag     | destination_city       | Destination City       | text          | text          |
| No       |                | event_start_date       | Event Start Date       | calendar_date | calendar_date |
| No       |                | event_end_date         | Event End Date         | calendar_date | calendar_date |
| Yes      | time           | travel_start_date      | Travel Start Date      | calendar_date | calendar_date |
| No       |                | travel_end_date        | Travel End Date        | calendar_date | calendar_date |
| Yes      | numeric metric | amount_reimbursed      | Amount Reimbursed      | money         | money         |
| Yes      | series tag     | funding                | Funding                | text          | text          |
| Yes      | series tag     | also_attending         | Also Attending         | text          | text          |
| Yes      | numeric metric | previous_of_trips      | Previous # of Trips    | number        | number        |
| Yes      | series tag     | purpose_of_trip        | Purpose of Trip        | text          | text          |
| Yes      | series tag     | reason_for_travel      | Reason for Travel      | text          | text          |
| Yes      | series tag     | mode_of_transportation | Mode of Transportation | text          | text          |
```

## Time Field

```ls
Value = travel_start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = event_end_date,event_start_date,travel_end_date,fiscal_year
```

## Data Commands

```ls
series e:vtga-efxt d:2011-07-01T00:00:00.000Z t:spec_dept="Economic Development Authority" t:funding="Fed-0% St-100% Oth-0%" t:departure_city="Des Moines, IA" t:purpose_of_trip="Normal Job Duties" t:reason_for_travel="Japan Office Expenses" t:dept_2="Economic Development Authority" t:dept_1=269 t:mode_of_transportation=Other t:tda=00000026900070111EO t:function="Economic Development" t:legal_name="State of Ia Japan Office" t:destination_city=Japan t:also_attending=none t:division=International t:event="Japan Office expenses" t:job_title="Japan Office" m:amount_reimbursed=0 m:previous_of_trips=0

series e:vtga-efxt d:2011-07-01T00:00:00.000Z t:spec_dept="Economic Development Authority" t:funding="Fed-0% St-100% Oth-0%" t:departure_city="Des Moines, IA" t:purpose_of_trip="Normal Job Duties" t:reason_for_travel="German office expenses" t:dept_2="Economic Development Authority" t:dept_1=269 t:mode_of_transportation=Other t:tda=00000026900070111EQ t:function="Economic Development" t:legal_name="State of IA European Off" t:destination_city=Germany t:also_attending=none t:division=International t:event="German office expenses" t:job_title="German office" m:amount_reimbursed=0 m:previous_of_trips=0

series e:vtga-efxt d:2012-05-30T00:00:00.000Z t:spec_dept="Human Services, Department of" t:funding="Fed-12.59% St-87.41% Oth-0%" t:departure_city="Omaha, NE" t:purpose_of_trip="Normal Job Duties" t:reason_for_travel="Foster parents transporting children to maternal Aunt in FL." t:dept_2="Human Services - Field Operations" t:dept_1=402 t:mode_of_transportation=Air t:tda=00002003615053012CV t:function="Human Services" t:legal_name="DANA RIEF" t:destination_city="Ft. Lauderdale, FL" t:also_attending="Kenneth Rief" t:division=DHS t:event=NA t:job_title=Volunteer m:amount_reimbursed=844.62 m:previous_of_trips=0
```

## Meta Commands

```ls
metric m:amount_reimbursed p:double l:"Amount Reimbursed" d:"Amount employee was reimbursed for this trip" t:dataTypeName=money

metric m:previous_of_trips p:integer l:"Previous # of Trips" d:"Number of previous trips in budget fiscal year" t:dataTypeName=number

entity e:vtga-efxt l:"State of Iowa Out-of-State Travel Reimbursements" t:attribution="Iowa Department of Administrative Services, State Accounting Enterprise, I3 Data Warehouse" t:url=https://data.iowa.gov/api/views/vtga-efxt

property e:vtga-efxt t:meta.view v:id=vtga-efxt v:category=Government v:averageRating=0 v:name="State of Iowa Out-of-State Travel Reimbursements" v:attribution="Iowa Department of Administrative Services, State Accounting Enterprise, I3 Data Warehouse"

property e:vtga-efxt t:meta.view.license v:name="Public Domain"

property e:vtga-efxt t:meta.view.owner v:id=vxmx-2ngw v:profileImageUrlMedium=/api/users/vxmx-2ngw/profile_images/THUMB v:profileImageUrlLarge=/api/users/vxmx-2ngw/profile_images/LARGE v:screenName="DAS, State Accounting Enterprise" v:profileImageUrlSmall=/api/users/vxmx-2ngw/profile_images/TINY v:displayName="DAS, State Accounting Enterprise"

property e:vtga-efxt t:meta.view.tableauthor v:id=vxmx-2ngw v:profileImageUrlMedium=/api/users/vxmx-2ngw/profile_images/THUMB v:profileImageUrlLarge=/api/users/vxmx-2ngw/profile_images/LARGE v:screenName="DAS, State Accounting Enterprise" v:profileImageUrlSmall=/api/users/vxmx-2ngw/profile_images/TINY v:roleName=editor v:displayName="DAS, State Accounting Enterprise"
```

## Top Records

```ls
| fiscal_year | tda                 | function                      | spec_dept                      | dept_1 | dept_2                                  | division                               | legal_name               | job_title                    | event                                             | departure_city  | destination_city   | event_start_date    | event_end_date      | travel_start_date   | travel_end_date     | amount_reimbursed | funding                             | also_attending                                                                 | previous_of_trips | purpose_of_trip     | reason_for_travel                                                                                                                                                                                                                                              | mode_of_transportation | 
| =========== | =================== | ============================= | ============================== | ====== | ======================================= | ====================================== | ======================== | ============================ | ================================================= | =============== | ================== | =================== | =================== | =================== | =================== | ================= | =================================== | ============================================================================== | ================= | =================== | ============================================================================================================================================================================================================================================================== | ====================== | 
| 2012        | 00000026900070111EO | Economic Development          | Economic Development Authority | 269    | Economic Development Authority          | International                          | State of Ia Japan Office | Japan Office                 | Japan Office expenses                             | Des Moines, IA  | Japan              | 2011-07-01T00:00:00 | 2012-06-30T00:00:00 | 2011-07-01T00:00:00 | 2012-06-30T00:00:00 | 0.00              | Fed-0% St-100% Oth-0%               | none                                                                           | 0                 | Normal Job Duties   | Japan Office Expenses                                                                                                                                                                                                                                          | Other                  | 
| 2012        | 00000026900070111EQ | Economic Development          | Economic Development Authority | 269    | Economic Development Authority          | International                          | State of IA European Off | German office                | German office expenses                            | Des Moines, IA  | Germany            | 2011-07-01T00:00:00 | 2012-06-30T00:00:00 | 2011-07-01T00:00:00 | 2012-06-30T00:00:00 | 0.00              | Fed-0% St-100% Oth-0%               | none                                                                           | 0                 | Normal Job Duties   | German office expenses                                                                                                                                                                                                                                         | Other                  | 
| 2012        | 00002003615053012CV | Human Services                | Human Services, Department of  | 402    | Human Services - Field Operations       | DHS                                    | DANA RIEF                | Volunteer                    | NA                                                | Omaha, NE       | Ft. Lauderdale, FL | 2012-05-30T00:00:00 | 2012-06-02T00:00:00 | 2012-05-30T00:00:00 | 2012-06-02T00:00:00 | 844.62            | Fed-12.59% St-87.41% Oth-0%         | Kenneth Rief                                                                   | 0                 | Normal Job Duties   | Foster parents transporting children to maternal Aunt in FL.                                                                                                                                                                                                   | Air                    | 
| 2012        | 000020052700611129O | Education                     | Education, Department of       | 282    | Education, Department of                | Community Colleges                     | Debora M Gosnell         | Contract Consultant          | CASAS Summer Institute                            | Clinton, IA     | San Diego, CA      | 2012-06-11T00:00:00 | 2012-06-14T00:00:00 | 2012-06-11T00:00:00 | 2012-06-14T00:00:00 | 1905.48           | Fed-100% St-0% Oth-0%               | Amy Vybiral, Alex Harris, Phyllis Hinton, Geoff Jones                          | 0                 | Conference/Seminar  | Debby Gosnell is attending the CASAS Summer Institute. Her expenses are covered via contract 011712.                                                                                                                                                           | Air                    | 
| 2012        | 00002005683042412EP | Human Services                | Public Health, Department of   | 588    | Public Health, Department of            | dir                                    | SIROOS S SHIRAZI         | Board member IBM             | AIM and FSMB annual meetings                      | Iowa City, IA   | Fort Worth, TX     | 2012-04-25T00:00:00 | 2012-04-28T00:00:00 | 2012-04-24T00:00:00 | 2012-04-29T00:00:00 | 1451.62           | Fed-0% St-0% Oth-100% RET FEES/FSMB | Russell Bardin, Mark Bowden, Diane Clark, Colleen Stockdale and Amy Van Maanen | 0                 | Meeting             | Siroos Shirazi, MD is chairman of the Board of Medicine and is the agencys voting delegate to the Federation of State Medical Boards annual meeting. He will participate in all plenary sessions for Administrators in Medicine AIM and the FSMB and will be i | Air                    | 
| 2017        | 000031045910114179O | Human Services                | Human Services, Department of  | 402    | Human Services - Field Operations       | DHS                                    | DEBORAH BARTHEL          | Volunteer                    | NA                                                | Elkton, SD      | Des Moines, IA     | 2017-01-14T00:00:00 | 2017-01-16T00:00:00 | 2017-01-14T00:00:00 | 2017-01-16T00:00:00 | 463.02            | Fed-12.2% St-87.8% Oth-0%           | Paul Barthel                                                                   | 0                 | Normal Job Duties   | Client visit.                                                                                                                                                                                                                                                  | Personal Car           | 
| 2012        | 00002011088061812B5 | Human Services                | Human Services, Department of  | 401    | Human Services - General Administration | DHS                                    | ANDREW KAISER            | DD Council Chair             | NACDD technical Assistance Institute              | LeClaire, IA    | Arlington, VA      | 2012-06-19T00:00:00 | 2012-06-20T00:00:00 | 2012-06-18T00:00:00 | 2012-06-21T00:00:00 | 1640.06           | Fed-100% St-0% Oth-0%               | Becky Harker                                                                   | 0                 | Conference/Seminar  | The Institute is an opportunity for the federal staff to update the State DD Council Chairs and staff on rules, regulations, best practices, and specific initiatives and compliance issues for the upcoming federal fiscal year.                              | Air                    | 
| 2012        | 00002011088072411BH | Human Services                | Human Services, Department of  | 401    | Human Services - General Administration | DHS                                    | ANDREW KAISER            | Iowa DD Council Chair        | NACDD Technical Assistance Institute              | LeClaire, IA    | Washington, DC     | 2011-07-25T00:00:00 | 2011-07-26T00:00:00 | 2011-07-24T00:00:00 | 2011-07-27T00:00:00 | 995.43            | Fed-100% St-0% Oth-0%               | Becky Harker                                                                   | 0                 | Conference/Seminar  | Federal staff will update state DD Council Chairs and staff on rules, regulations, best practices, and specific initiatives and compliance issues for the upcoming year.                                                                                       | Air                    | 
| 2012        | 000020121630416129C | Human Services                | Human Services, Department of  | 401    | Human Services - General Administration | DHS                                    | NOLA AALBERTS            | NW Decat Coordinator         | Natl Conf on Child Abuse and Neglect              | Des Moines, IA  | Washington, DC     | 2012-04-16T00:00:00 | 2012-04-20T00:00:00 | 2012-04-16T00:00:00 | 2012-04-20T00:00:00 | 1521.03           | Fed-100% St-0% Oth-0%               | Trisha Barto, Sandy Lint, Denise Moore                                         | 0                 | Conference/Seminar  | Receiving the National Child Abuse Prevention Commissioners Award at a banquet during the conference. Being honored for outstanding achievements and dedication to preventing child abuse.                                                                     | Air                    | 
| 2012        | 00002039842101111CS | Administration and Regulation | Human Rights, Department of    | 379    | Human Rights, Department of             | Criminal and Juvenile Justice Planning | Jim Morris               | State Advisory Council Chair | OJJDP Natl Conf. for Childrens Justice and Safety | Des Moines Iowa | Washington, DC     | 2011-10-12T00:00:00 | 2011-10-14T00:00:00 | 2011-10-11T00:00:00 | 2011-10-14T00:00:00 | 542.27            | Fed-100% St-0% Oth-0%               | Steve Michael, Dave Kuker, and Scott Musel                                     | 0                 | Required by Federal | Rev. James Morris, Chair of the Juvenile Justice Advisory Council will join DHR staff to represent the Designated State Agency DSA t the OJJDP conference. OJJDP expects each DSA to have representation from the Juvenile Justice Council and various OJJDP p | Air                    | 
```