# Lobbyist Activity - Contacts of Public Officials

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lobbyist-activity-contacts-of-public-officials-922f0) |
| Metadata | [Link](https://data.sfgov.org/api/views/hr5m-xnxc) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/hr5m-xnxc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/hr5m-xnxc/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | hr5m-xnxc |
| Name | Lobbyist Activity - Contacts of Public Officials |
| Attribution | San Francisco Ethics Commission |
| Category | City Management and Ethics |
| Tags | ethics, lobbyist, contacts, public official |
| Created | 2012-04-26T23:58:29Z |
| Publication Date | 2014-08-22T16:45:55Z |

## Description

The name of each officer of the City and County of San Francisco with whom a lobbyist made a contact.  Contacts of public officials are disclosed by lobbyists registered with the Ethics Commission on a monthly basis.  This dataset updates automatically every night.

## Columns

```ls
| Included | Schema Type | Field Name          | Name                | Data Type     | Render Type   |
| ======== | =========== | =================== | =================== | ============= | ============= |
| Yes      | time        | date                | Date                | calendar_date | calendar_date |
| Yes      | series tag  | lobbyist            | Lobbyist            | text          | text          |
| Yes      | series tag  | lobbyist_firm       | Lobbyist_Firm       | text          | text          |
| Yes      | series tag  | official            | Official            | text          | text          |
| Yes      | series tag  | official_department | Official_Department | text          | text          |
| Yes      | series tag  | lobbyist_client     | Lobbyist_Client     | text          | text          |
| Yes      | series tag  | municipaldecision   | MunicipalDecision   | text          | text          |
| Yes      | series tag  | desiredoutcome      | DesiredOutcome      | text          | text          |
| Yes      | series tag  | filenumber          | FileNumber          | text          | text          |
| Yes      | series tag  | lobbyingsubjectarea | LobbyingSubjectArea | text          | text          |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:hr5m-xnxc d:2015-06-24T00:00:00.000Z t:filenumber=CPF-14-513661 t:lobbyist_firm="Reuben, Junius & Rose, Llp" t:municipaldecision="399 - Fee Litigation" t:lobbyingsubjectarea=Legal t:lobbyist="Junius, Andrew" t:official="Mendrin, Shaunn" t:desiredoutcome=Approval t:lobbyist_client=Udr t:official_department="Planning, Department Of" m:row_number.hr5m-xnxc=1

series e:hr5m-xnxc d:2016-05-31T00:00:00.000Z t:lobbyist_firm="Morgan Stanley Investment Management Inc." t:municipaldecision="Financial Services" t:lobbyingsubjectarea="Economic Development" t:lobbyist="Olson, Daniel" t:official="Wang, Art" t:desiredoutcome="Share class transfer of investments." t:lobbyist_client="Morgan Stanley Investment Management Inc." t:official_department="Retirement Board San Francisco Employees" m:row_number.hr5m-xnxc=2

series e:hr5m-xnxc d:2011-01-21T00:00:00.000Z t:lobbyist_firm=At&t t:municipaldecision="Fiber Network Upgrade" t:lobbyingsubjectarea=Technology t:lobbyist="Blakeman, Marc D." t:official="Chu, Carmen" t:desiredoutcome="Educate government officials and staff about company's proposed fiber network upgrade" t:lobbyist_client="At&t California" t:official_department="Board Of Supervisors" m:row_number.hr5m-xnxc=3
```

## Meta Commands

```ls
metric m:row_number.hr5m-xnxc p:long l:"Row Number"

entity e:hr5m-xnxc l:"Lobbyist Activity - Contacts of Public Officials" t:attribution="San Francisco Ethics Commission" t:url=https://data.sfgov.org/api/views/hr5m-xnxc

property e:hr5m-xnxc t:meta.view v:id=hr5m-xnxc v:category="City Management and Ethics" v:attributionLink=http://www.sfethics.org/ethics/2012/01/lobbyist-database-api.html v:averageRating=0 v:name="Lobbyist Activity - Contacts of Public Officials" v:attribution="San Francisco Ethics Commission"

property e:hr5m-xnxc t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:hr5m-xnxc t:meta.view.owner v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:displayName="Steven Massey"

property e:hr5m-xnxc t:meta.view.tableauthor v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"
```

## Top Records

```ls
| date                | lobbyist          | lobbyist_firm                             | official           | official_department                                | lobbyist_client                                                               | municipaldecision                                                                                             | desiredoutcome                                                                        | filenumber    | lobbyingsubjectarea           | 
| =================== | ================= | ========================================= | ================== | ================================================== | ============================================================================= | ============================================================================================================= | ===================================================================================== | ============= | ============================= | 
| 2015-06-24T00:00:00 | Junius, Andrew    | Reuben, Junius & Rose, Llp                | Mendrin, Shaunn    | Planning, Department Of                            | Udr                                                                           | 399 - Fee Litigation                                                                                          | Approval                                                                              | CPF-14-513661 | Legal                         | 
| 2016-05-31T00:00:00 | Olson, Daniel     | Morgan Stanley Investment Management Inc. | Wang, Art          | Retirement Board San Francisco Employees           | Morgan Stanley Investment Management Inc.                                     | Financial Services                                                                                            | Share class transfer of investments.                                                  |               | Economic Development          | 
| 2011-01-21T00:00:00 | Blakeman, Marc D. | At&t                                      | Chu, Carmen        | Board Of Supervisors                               | At&t California                                                               | Fiber Network Upgrade                                                                                         | Educate government officials and staff about company's proposed fiber network upgrade |               | Technology                    | 
| 2010-02-08T00:00:00 | Solem, Don        | Solem & Associates                        | Kawa, Steve        | Mayor Office Of The                                | Waste Management, Inc.                                                        | Dept. Of Environment Rfp For Waste Hauling                                                                    | Information only                                                                      | pending       | Environment                   | 
| 2016-04-28T00:00:00 | Peterson, Rich    | Goodyear Peterson Hayward & Associates    | Johnson, Christine | Planning Commission                                | Grocery Outlet                                                                | 1390 Silver Avenue                                                                                            | SUPPORT                                                                               |               | Planning and Building Permits | 
| 2015-12-10T00:00:00 | Rossi, Jaime      | Barbary Coast Consulting                  | Avalos, John       | Board Of Supervisors                               | Lick-Wilmerding High School                                                   | Lick-Wilmerding Informational                                                                                 | Lick-Wilmerding expansion                                                             |               | Economic Development          | 
| 2016-07-27T00:00:00 | Dane, Fiona       | Livingbridge Ep Llp                       | Schwartz, Glen     | Retirement Board San Francisco Employees           | San Francisco City And County Of San Francisco Employees??? Retirement System | Investment Decision                                                                                           | Investment                                                                            |               | City Employee Benefits        | 
| 2016-12-07T00:00:00 | Bozeman, John     | Boma San Francisco                        | Farrell, Mark      | Board Of Supervisors                               | Boma San Francisco                                                            | Urging The Department Of Homelessness And Supportive Housing To Adopt A Five Year Plan To Reduce Homelessness | Monitor                                                                               | 160674        | Government Administration     | 
| 2016-04-29T00:00:00 | Junius, Andrew    | Reuben, Junius & Rose, Llp                | Hart, Shane        | Community Investment And Infrastructure, Office Of | Tishman Speyer Properties, L.p.                                               | Block 1                                                                                                       | Approval                                                                              | 2014-000203   | Planning and Building Permits | 
| 2016-08-05T00:00:00 | Knight, Jody      | Reuben, Junius & Rose, Llp                | Antonini, Michael  | Board Of Supervisors                               | Sprincin, Phillip And Kristin                                                 | 60 Russell                                                                                                    | Approval                                                                              | 2014-001259   | Planning and Building Permits | 
```