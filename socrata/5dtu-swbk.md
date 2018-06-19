# Active Committee Address Report

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/active-committee-address-report) |
| Metadata | [Link](https://data.iowa.gov/api/views/5dtu-swbk) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/5dtu-swbk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/5dtu-swbk/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | 5dtu-swbk |
| Name | Active Committee Address Report |
| Attribution | Iowa Ethics & Campaign Disclosure Board |
| Category | Government |
| Tags | political, candidates, campaigns, committees |
| Created | 2015-09-04T15:14:04Z |
| Publication Date | 2016-03-07T15:09:43Z |

## Description

The dataset contains address lists for registered candidates, committees, and other entities that file with the Iowa Ethics & Campaign Disclosure Board.

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type | Render Type |
| ======== | ============== | ======================== | ======================== | ========= | =========== |
| No       | time           | :updated_at              | updated_at               | meta_data | meta_data   |
| Yes      | series tag     | committee_name           | Committee Name           | text      | text        |
| Yes      | series tag     | committee_number         | Committee Number         | text      | number      |
| Yes      | series tag     | district                 | District                 | text      | number      |
| Yes      | series tag     | party                    | Party                    | text      | text        |
| Yes      | numeric metric | election_year            | Election Year            | number    | number      |
| Yes      | series tag     | office_sought            | Office Sought            | text      | text        |
| Yes      | series tag     | county                   | County                   | text      | text        |
| Yes      | series tag     | candidate_name           | Candidate Name           | text      | text        |
| No       |                | candidate_address        | Candidate Address        | text      | text        |
| Yes      | series tag     | candidate_city_state_zip | Candidate City State Zip | text      | text        |
| Yes      | series tag     | candidate_phone          | Candidate Phone          | text      | number      |
| Yes      | series tag     | candidate_email          | Candidate Email          | text      | text        |
| Yes      | series tag     | chair_name               | Chair Name               | text      | text        |
| No       |                | chair_address            | Chair Address            | text      | text        |
| Yes      | series tag     | chair_city_state_zip     | Chair City State Zip     | text      | text        |
| Yes      | series tag     | chair_phone              | Chair Phone              | text      | number      |
| Yes      | series tag     | chair_email              | Chair Email              | text      | text        |
| Yes      | series tag     | treasurer_name           | Treasurer Name           | text      | text        |
| No       |                | treasurer_address        | Treasurer Address        | text      | text        |
| Yes      | series tag     | treasurer_city_state_zip | Treasurer City State Zip | text      | text        |
| Yes      | series tag     | treasurer_phone          | Treasurer Phone          | text      | number      |
| Yes      | series tag     | treasurer_email          | Treasurer Email          | text      | text        |
| Yes      | series tag     | parent_entity            | Parent Entity            | text      | text        |
| No       |                | parent_address           | Parent Address           | text      | text        |
| Yes      | series tag     | parent_city_state_zip    | Parent City State Zip    | text      | text        |
| Yes      | series tag     | contact_name             | Contact Name             | text      | text        |
| No       |                | contact_address          | Contact Address          | text      | text        |
| Yes      | series tag     | contact_city_state_zip   | Contact City State Zip   | text      | text        |
| Yes      | series tag     | contact_phone            | Contact Phone            | text      | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = candidate_address,chair_address,treasurer_address,parent_address,contact_address
```

## Data Commands

```ls
series e:5dtu-swbk d:2017-02-16T23:00:56.000Z t:committee_number=1334 t:committee_name="Watts for House" t:treasurer_name="ReNae Arnold" t:office_sought=Representative t:candidate_name="Ralph Watts" t:contact_city_state_zip="Adel IA   50003" t:chair_name="Carter Nordman" t:treasurer_phone=5159932035 t:chair_phone=5159932035 t:party=Republican t:candidate_city_state_zip="Adel IA   50003" t:county=_NA t:treasurer_email=nae4isu@yahoo.com t:chair_city_state_zip="Adel IA   50003" t:contact_name="Caden Mager" t:candidate_phone=5159934850 t:treasurer_city_state_zip="Adel IA   50003" t:district=19 t:candidate_email=rnswatts@msn.com m:election_year=2016

series e:5dtu-swbk d:2016-10-25T01:00:07.000Z t:treasurer_name="james sporrer" t:committee_name="re-elect sheriff baloun" t:committee_number=17153 t:office_sought=sheriff t:candidate_name="Greg Baloun" t:contact_city_state_zip="lake park IA   51347" t:contact_phone=7123203001 t:treasurer_phone=7123304660 t:party=Republican t:candidate_city_state_zip="lake park IA   51347" t:county=Dickinson t:contact_name="Greg Baloun" t:candidate_phone=7123203001 t:treasurer_city_state_zip="milford IA   51351" t:district=0 t:candidate_email=deevellema@live.com m:election_year=2016

series e:5dtu-swbk d:2017-02-16T23:00:57.000Z t:treasurer_name="Allison Drahozal" t:committee_name="Isenhart Campaign for the Common Good" t:committee_number=1722 t:office_sought=Representative t:candidate_name="Charles Isenhart" t:contact_city_state_zip="Dubuque IA   52004" t:contact_phone=5635571261 t:treasurer_phone=0 t:party=Democratic t:candidate_city_state_zip="Dubuque IA   52001" t:county=_NA t:treasurer_email=iccgtreasurer@gmail.com t:contact_name="Charles Isenhart" t:candidate_phone=5635571261 t:treasurer_city_state_zip="Dubuque IA   52001" t:district=100 t:candidate_email=goodcampaign@aol.com m:election_year=2016
```

## Meta Commands

```ls
metric m:election_year p:integer l:"Election Year" t:dataTypeName=number

entity e:5dtu-swbk l:"Active Committee Address Report" t:attribution="Iowa Ethics & Campaign Disclosure Board" t:url=https://data.iowa.gov/api/views/5dtu-swbk

property e:5dtu-swbk t:meta.view v:id=5dtu-swbk v:category=Government v:averageRating=0 v:name="Active Committee Address Report" v:attribution="Iowa Ethics & Campaign Disclosure Board"

property e:5dtu-swbk t:meta.view.license v:name="Public Domain"

property e:5dtu-swbk t:meta.view.owner v:id=8x33-bu4e v:profileImageUrlMedium=/api/users/8x33-bu4e/profile_images/THUMB v:profileImageUrlLarge=/api/users/8x33-bu4e/profile_images/LARGE v:screenName="Ethics and Campaign Disclosure Board" v:profileImageUrlSmall=/api/users/8x33-bu4e/profile_images/TINY v:displayName="Ethics and Campaign Disclosure Board"

property e:5dtu-swbk t:meta.view.tableauthor v:id=8x33-bu4e v:profileImageUrlMedium=/api/users/8x33-bu4e/profile_images/THUMB v:profileImageUrlLarge=/api/users/8x33-bu4e/profile_images/LARGE v:screenName="Ethics and Campaign Disclosure Board" v:profileImageUrlSmall=/api/users/8x33-bu4e/profile_images/TINY v:roleName=editor v:displayName="Ethics and Campaign Disclosure Board"
```

## Top Records

```ls
| :updated_at | committee_name                                    | committee_number | district | party      | election_year | office_sought              | county     | candidate_name   | candidate_address       | candidate_city_state_zip | candidate_phone | candidate_email                        | chair_name     | chair_address        | chair_city_state_zip | chair_phone | chair_email               | treasurer_name      | treasurer_address  | treasurer_city_state_zip | treasurer_phone | treasurer_email          | parent_entity | parent_address | parent_city_state_zip | contact_name              | contact_address               | contact_city_state_zip | contact_phone | 
| =========== | ================================================= | ================ | ======== | ========== | ============= | ========================== | ========== | ================ | ======================= | ======================== | =============== | ====================================== | ============== | ==================== | ==================== | =========== | ========================= | =================== | ================== | ======================== | =============== | ======================== | ============= | ============== | ===================== | ========================= | ============================= | ====================== | ============= | 
| 1487286056  | Watts for House                                   | 1334             | 19       | Republican | 2016          | Representative             | _NA        | Ralph Watts      | 28232 Prospect Ave.     | Adel IA 50003            | 5159934850      | rnswatts@msn.com                       | Carter Nordman | 1404 Linden Cir      | Adel IA 50003        | 5159932035  |                           | ReNae Arnold        | 30236 K Ave        | Adel IA 50003            | 5159932035      | nae4isu@yahoo.com        |               |                |                       | Caden Mager               | 1712 S 14th St                | Adel IA 50003          |               | 
| 1477357207  | re-elect sheriff baloun                           | 17153            | 0        | Republican | 2016          | sheriff                    | Dickinson  | Greg Baloun      | 402 railroad st Box 263 | lake park IA 51347       | 7123203001      | deevellema@live.com                    |                |                      |                      |             |                           | james sporrer       | 1881 190th street  | milford IA 51351         | 7123304660      |                          |               |                |                       | Greg Baloun               | 402 railroad st Box 263       | lake park IA 51347     | 7123203001    | 
| 1487286057  | Isenhart Campaign for the Common Good             | 1722             | 100      | Democratic | 2016          | Representative             | _NA        | Charles Isenhart | 1665 Kaufmann Ave       | Dubuque IA 52001         | 5635571261      | goodcampaign@aol.com                   |                |                      |                      |             |                           | Allison Drahozal    | 683 W. 11th Street | Dubuque IA 52001         | 0               | iccgtreasurer@gmail.com  |               |                |                       | Charles Isenhart          | P.O. Box 3353                 | Dubuque IA 52004       | 5635571261    | 
| 1487286057  | Committee to Elect Angela Connolly for Supervisor | 17331            | 0        | Democratic | 2014          | County Supervisor          | Polk       | Angela Connolly  | 4707 NW Beaver          | Des Moines IA 50310-2147 | 5154913337      | Angela.connolly@polkcountyiowa.gov     |                |                      |                      |             |                           | Theodore Boesen Jr  | 3011 Don Lee Court | Des Moines IA 50317      | 5157787063      | tboesen@iowapca.org      |               |                |                       |                           | 1111 9th St #265              | Des Moines IA 50314    |               | 
| 1487286057  | Sarcone for County Attorney                       | 17343            | 0        | Democratic | 2014          | County Attorney            | Polk       | John Sarcone     | P.O. 21117              | Des Moines IA 50321      | 5152436999      | johnpsarcone@gmail.com                 | Nan Horvat     | 6239 N Winwood Drive | Johnston IA 50131    | 5152784517  |                           | Debra Leonard       | 2804 42nd Street   | Des Moines IA 50310      | 5152559525      | dleonard@mchsi.com       |               |                |                       |                           | 3900 Ingersoll Avenue #102    | Des Moines IA 50312    |               | 
| 1477357208  | Kris Rowley For Treasurer                         | 17920            | 3        | Republican | 2014          | Dickinson County Treasurer | Dickinson  | Kris Rowley      | 1311 Gary Ave.          | Spirit Lake IA 51360     | 7123304148      | rowleykd@gmail.com                     |                |                      |                      |             |                           | Emily Bossard       | 2188 213th Ave.    | Milford IA 51351         | 7123302624      | dbossard@milfordcomm.net |               |                |                       |                           | P.O. Box 192                  | Milford IA 51351       |               | 
| 1477357208  | Granzow for Supervisor                            | 18021            | 0        | Republican | 2018          | Supervisor                 | Hardin     | Lance Granzow    | 22496 250th St.         | Hubbard IA 50122         | 3194155910      |                                        | Polly Granzow  | 22978 Co. Hwy. S55   | Eldora IA 50627      | 6418582510  |                           | Katie Reifschneider | PO Box 43          | Alden IA 50006           | 6416402800      | kbracing36@hotmail.com   |               |                |                       | Inc. Damon Adams Services | 1834 Crescent Drive           | Iowa Falls IA 50126    |               | 
| 1477357208  | Thompson For Sheriff Committee                    | 18184            | 0        | Democratic | 2016          | Sheriff                    | Black Hawk | Tony Thompson    | 8847 Leversee Road      | Cedar Falls IA 50613     | 3192693092      | tony@thompsonforsheriff.net            | Don Page       | 3316 Parkridge Drive | Waterloo IA 50701    | 3192962587  | dfpage2@q.com             | Janel Thompson      | 8847 Leversee Road | Cedar Falls IA 50613     | 3192693092      | grandacres@yahoo.com     |               |                |                       |                           | 319 Main Street               | Janesville IA 50647    | 3199872058    | 
| 1487286057  | Sweeney for State House                           | 1776             | 44       | Republican | 2012          | Representative             | Hardin     | Annette Sweeney  | 21547 Hwy S27           | Alden IA 50006           | 5158554340      | sweeneyforhouse@yahoo.com              | David Sweeney  | 21547 Hwy S27        | Alden IA 50006       | 5158554340  | sweeneyforhouse@yahoo.com | Prentice Lofstedt   | 19799 Hwy D20      | Iowa Falls IA 50126      | 6413730950      |                          |               |                |                       |                           | 406 Stevens St                | Iowa Falls IA 50126    |               | 
| 1487286057  | Johnson for Sheriff Committee                     | 17996            | 0        | Republican | 2016          | Sheriff Butler County      | Butler     | Jason Johnson    | 1202 Sunset Drive       | Parkersburg IA 50665     | 3193469832      | lyojjo@aol.com lyoderforwork@gmail.com | Lisa Yoder     | 1202 Sunset Drive    | Parkersburg IA 50665 | 3193469832  | lyojjo@aol.com            | Lisa Yoder          | 1202 Sunset Drive  | Parkersburg IA 50665     | 3193469832      | lyojjo@aol.com           |               |                |                       |                           | P.O. Box 370 103 E. Traer St. | Greene IA 50636        |               | 
```