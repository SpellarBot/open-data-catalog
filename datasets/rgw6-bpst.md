# Legislator Database

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/legislator-database) |
| Metadata | [Link](https://data.ct.gov/api/views/rgw6-bpst) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/rgw6-bpst/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/rgw6-bpst/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | rgw6-bpst |
| Name | Legislator Database |
| Attribution | Connecticut General Assembly |
| Category | Government |
| Tags | legislature, districts, senate, representatives |
| Created | 2015-01-16T20:38:07Z |
| Publication Date | 2017-01-10T20:19:40Z |

## Description

A listing of State Representatives and State Senators. For more information:http://www.cga.ct.gov/asp/menu/legdownload.asp

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| No       | time           | :updated_at             | updated_at              | meta_data | meta_data   |
| Yes      | series tag     | district                | district                | text      | number      |
| Yes      | series tag     | office_code             | office code             | text      | text        |
| Yes      | series tag     | district_number         | district number         | text      | text        |
| Yes      | series tag     | designator_code         | designator code         | text      | text        |
| Yes      | series tag     | first_name              | first name              | text      | text        |
| Yes      | series tag     | middle_initial          | middle initial          | text      | text        |
| Yes      | series tag     | last_name               | last name               | text      | text        |
| Yes      | series tag     | suffix                  | suffix                  | text      | text        |
| Yes      | series tag     | commonly_used_name      | commonly used name      | text      | text        |
| Yes      | series tag     | home_street_address     | home street address     | text      | text        |
| Yes      | series tag     | home_city               | home city               | text      | text        |
| Yes      | series tag     | home_state              | home state              | text      | text        |
| Yes      | series tag     | home_zip_code           | home zip code           | text      | number      |
| Yes      | series tag     | home_phone              | home phone              | text      | text        |
| Yes      | series tag     | capitol_street_address  | capitol street address  | text      | text        |
| Yes      | series tag     | capitol_city            | capitol city            | text      | text        |
| Yes      | series tag     | capitol_phone           | capitol phone           | text      | text        |
| Yes      | series tag     | room                    | room                    | text      | text        |
| Yes      | series tag     | room_number             | room number             | text      | number      |
| Yes      | series tag     | committees_chaired      | committees chaired      | text      | text        |
| Yes      | series tag     | committees_vice_chaired | committees vice chaired | text      | text        |
| Yes      | series tag     | ranking_member          | ranking member          | text      | text        |
| Yes      | series tag     | committee_member1       | committee member1       | text      | text        |
| Yes      | series tag     | senator_representative  | senator/representative  | text      | text        |
| Yes      | series tag     | party                   | party                   | text      | text        |
| Yes      | series tag     | title                   | title                   | text      | text        |
| Yes      | series tag     | gender                  | gender                  | text      | text        |
| Yes      | series tag     | business_phone          | business phone          | text      | text        |
| Yes      | series tag     | email                   | email                   | text      | text        |
| Yes      | series tag     | fax                     | fax                     | text      | number      |
| Yes      | numeric metric | prison                  | prison                  | number    | number      |
| Yes      | series tag     | url                     | URL                     | text      | text        |
| Yes      | series tag     | committee_codes         | committee codes         | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:rgw6-bpst d:2017-01-10T20:19:10.000Z t:home_state=CT t:committee_codes=;BA;PD;PH; t:party=Democrat t:district_number=1st t:home_zip_code=6105 t:first_name=Matthew t:title="House Majority Leader" t:senator_representative=Representative t:home_city=Hartford t:office_code=H t:gender=Male t:designator_code=R t:district=1 t:room_number=3004 t:capitol_street_address="Legislative Office Building" t:home_street_address="169 N. Beacon Street" t:capitol_city="Hartford, CT  06106-1591" t:url=http://www.housedems.ct.gov/Ritter t:capitol_phone=860-240-8585 t:business_phone=860-251-5000 t:commonly_used_name=Matthew t:email=Matthew.Ritter@cga.ct.gov t:last_name=Ritter t:home_phone=860-519-5685 t:committees_chaired="Public Health" t:committee_member1="Public Health (Chair); Banking; Planning and Development" t:room=Room m:prison=0

series e:rgw6-bpst d:2017-01-10T20:19:10.000Z t:home_state=CT t:home_street_address="33 Long Meadow Road" t:capitol_street_address="Legislative Office Building" t:committee_codes=; t:party=Republican t:capitol_city="Hartford, CT  06106-1591" t:url=http://repDuff.com t:home_zip_code=6105 t:district_number=2nd t:first_name=William t:office_code=H t:home_city=Bethel t:senator_representative=Representative t:email=William.Duff@housegop.ct.gov t:commonly_used_name=William t:last_name=Duff t:designator_code=N t:gender=Male t:district=2 t:room=Room m:prison=0

series e:rgw6-bpst d:2017-01-10T20:19:10.000Z t:room_number=4031 t:home_state=CT t:home_street_address="97 Amity Street" t:capitol_street_address="Legislative Office Building" t:committee_codes=;APP;JUD;PS; t:party=Democrat t:capitol_city="Hartford, CT  06106-1591" t:url=http://www.housedems.ct.gov/Gonzalez t:home_zip_code=6106 t:district_number=3rd t:capitol_phone=860-240-8585 t:first_name=Minnie t:title="Chief Majority Whip" t:office_code=H t:home_city=Hartford t:senator_representative=Representative t:email=Minnie.Gonzalez@cga.ct.gov t:commonly_used_name=Minnie t:last_name=Gonzalez t:home_phone=860-236-9654 t:designator_code=R t:gender=Female t:committee_member1="Appropriations; Judiciary; Public Safety and Security" t:district=3 t:room=Room m:prison=0
```

## Meta Commands

```ls
metric m:prison p:integer l:prison t:dataTypeName=number

entity e:rgw6-bpst l:"Legislator Database" t:attribution="Connecticut General Assembly" t:url=https://data.ct.gov/api/views/rgw6-bpst

property e:rgw6-bpst t:meta.view v:id=rgw6-bpst v:category=Government v:attributionLink=http://www.cga.ct.gov/asp/menu/legdownload.asp v:averageRating=0 v:name="Legislator Database" v:attribution="Connecticut General Assembly"

property e:rgw6-bpst t:meta.view.license v:name="Public Domain"

property e:rgw6-bpst t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:rgw6-bpst t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| :updated_at | district | office_code | district_number | designator_code | first_name | middle_initial | last_name | suffix | commonly_used_name | home_street_address     | home_city     | home_state | home_zip_code | home_phone   | capitol_street_address      | capitol_city            | capitol_phone | room | room_number | committees_chaired | committees_vice_chaired                         | ranking_member        | committee_member1                                                                                                                            | senator_representative | party      | title                     | gender | business_phone | email                        | fax | prison | url                                  | committee_codes      | 
| =========== | ======== | =========== | =============== | =============== | ========== | ============== | ========= | ====== | ================== | ======================= | ============= | ========== | ============= | ============ | =========================== | ======================= | ============= | ==== | =========== | ================== | =============================================== | ===================== | ============================================================================================================================================ | ====================== | ========== | ========================= | ====== | ============== | ============================ | === | ====== | ==================================== | ==================== | 
| 1484079550  | 1        | H           | 1st             | R               | Matthew    |                | Ritter    |        | Matthew            | 169 N. Beacon Street    | Hartford      | CT         | 6105          | 860-519-5685 | Legislative Office Building | Hartford, CT 06106-1591 | 860-240-8585  | Room | 3004        | Public Health      |                                                 |                       | Public Health (Chair); Banking; Planning and Development                                                                                     | Representative         | Democrat   | House Majority Leader     | Male   | 860-251-5000   | Matthew.Ritter@cga.ct.gov    |     | 0      | http://www.housedems.ct.gov/Ritter   | ;BA;PD;PH;           | 
| 1484079550  | 2        | H           | 2nd             | N               | William    |                | Duff      |        | William            | 33 Long Meadow Road     | Bethel        | CT         | 6105          |              | Legislative Office Building | Hartford, CT 06106-1591 |               | Room |             |                    |                                                 |                       |                                                                                                                                              | Representative         | Republican |                           | Male   |                | William.Duff@housegop.ct.gov |     | 0      | http://repDuff.com                   | ;                    | 
| 1484079550  | 3        | H           | 3rd             | R               | Minnie     |                | Gonzalez  |        | Minnie             | 97 Amity Street         | Hartford      | CT         | 6106          | 860-236-9654 | Legislative Office Building | Hartford, CT 06106-1591 | 860-240-8585  | Room | 4031        |                    |                                                 |                       | Appropriations; Judiciary; Public Safety and Security                                                                                        | Representative         | Democrat   | Chief Majority Whip       | Female |                | Minnie.Gonzalez@cga.ct.gov   |     | 0      | http://www.housedems.ct.gov/Gonzalez | ;APP;JUD;PS;         | 
| 1484079550  | 4        | H           | 4th             | R               | Angel      |                | Arce      |        | Angel              | 248 Franklin Ave, Apt B | Hartford      | CT         | 6106          |              | Legislative Office Building | Hartford, CT 06106-1591 | 860-240-8585  | Room | 2303        |                    | Transportation                                  |                       | Transportation (Vice Chair); Finance, Revenue and Bonding; Housing; Insurance and Real Estate                                                | Representative         | Democrat   | Assistant Majority Leader | Male   |                | Angel.Arce@cga.ct.gov        |     | 0      | http://www.housedems.ct.gov/Arce     | ;FIN;HSG;INS;TRA;    | 
| 1484079550  | 5        | H           | 5th             | R               | Brandon    | L.             | McGee     | Jr.    | Brandon            | 43 Warren Street        | Hartford      | CT         | 6120          | 860-578-2979 | Legislative Office Building | Hartford, CT 06106-1591 | 860-240-8585  | Room | 5009        |                    | Human Services                                  |                       | Human Services (Vice Chair); Appropriations; Education                                                                                       | Representative         | Democrat   | Assistant Majority Leader | Male   |                | Brandon.McGee@cga.ct.gov     |     | 0      | http://www.housedems.ct.gov/McGee    | ;APP;ED;HS;          | 
| 1484079550  | 6        | H           | 6th             | R               | Edwin      |                | Vargas    |        | Edwin              | 141 Douglas Street      | Hartford      | CT         | 6114          | 860-956-1503 | Legislative Office Building | Hartford, CT 06106-1591 | 860-240-8585  | Room | 4006        |                    | Commerce; Executive and Legislative Nominations |                       | Commerce (Vice Chair); Executive and Legislative Nominations (Vice Chair); Appropriations; Committee on Children; Labor and Public Employees | Representative         | Democrat   |                           | Male   | 860-930-6359   | Edwin.Vargas@cga.ct.gov      |     | 0      | http://www.housedems.ct.gov/Vargas   | ;APP;CE;EXN;KID;LAB; | 
| 1484079550  | 7        | H           | 7th             | R               | Douglas    |                | McCrory   |        | Douglas            | 235 Blue Hills Avenue   | Hartford      | CT         | 6112          |              | Legislative Office Building | Hartford, CT 06106-1591 | 860-240-8585  | Room | 4025        |                    |                                                 |                       | Appropriations; Education; Higher Education and Employment Advancement; Legislative Management                                               | Representative         | Democrat   | Deputy Majority Leader    | Male   |                | Douglas.McCrory@cga.ct.gov   |     | 0      | http://www.housedems.ct.gov/McCrory  | ;APP;ED;HED;LM;      | 
| 1484079550  | 8        | H           | 8th             | R               | Tim        |                | Ackert    |        | Tim                | 67 Deer Hill Lane       | Coventry      | CT         | 6238          | 860-742-5287 | Legislative Office Building | Hartford, CT 06106-1591 | 860-240-8700  | Room | 3904        |                    |                                                 | Energy and Technology | Energy and Technology (Ranking Member); Education; Higher Education and Employment Advancement                                               | Representative         | Republican |                           | Male   |                | tim.ackert@housegop.ct.gov   |     | 0      | http://repackert.com                 | ;ED;ET;HED;          | 
| 1484079550  | 9        | H           | 9th             | R               | Jason      |                | Rojas     |        | Jason              | 169 Langford Lane       | East Hartford | CT         | 6118          | 860-895-8374 | Legislative Office Building | Hartford, CT 06106-1591 | 860-240-0549  | Room | 4023        |                    |                                                 |                       | Education; Finance, Revenue and Bonding; Planning and Development                                                                            | Representative         | Democrat   | Deputy Majority Leader    | Male   |                | Jason.Rojas@cga.ct.gov       |     | 0      | http://www.housedems.ct.gov/Rojas    | ;ED;FIN;PD;          | 
| 1484079550  | 10       | H           | 10th            | R               | Henry      | J.             | Genga     |        | Henry              | 5 Elaine Drive          | East Hartford | CT         | 6118          | 860-569-8008 | Legislative Office Building | Hartford, CT 06106-1591 | 860-240-8534  | Room | 4030        |                    | Appropriations                                  |                       | Appropriations (Vice Chair); Education; Public Health                                                                                        | Representative         | Democrat   | Deputy Majority Whip      | Male   |                | henry.genga@cga.ct.gov       |     | 0      | http://www.housedems.ct.gov/Genga    | ;APP;ED;PH;          | 
```