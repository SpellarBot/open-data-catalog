# Manhattan Community Grants

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/manhattan-community-grants-06904) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/rsnd-bbih) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/rsnd-bbih/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/rsnd-bbih/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | rsnd-bbih |
| Name | Manhattan Community Grants |
| Attribution | Manhattan Borough President (MBP) |
| Category | City Government |
| Tags | manhattan community grants, mbp, manhattan borough president (mbp) |
| Created | 2014-03-06T17:40:35Z |
| Publication Date | 2014-03-06T17:42:28Z |

## Description

This list contains information on Manhattan Community Grants

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                           | Data Type | Render Type |
| ======== | ============== | ============================ | ============================== | ========= | =========== |
| No       | time           | :updated_at                  | updated_at                     | meta_data | meta_data   |
| Yes      | series tag     | agency                       | Agency                         | text      | text        |
| Yes      | series tag     | mbpo_organization_dfta_fy_14 | MBPO ORGANIZATION DFTA - FY 14 | text      | text        |
| Yes      | series tag     | brief_program_description    | Brief Program Description      | text      | text        |
| Yes      | series tag     | new_applicant                | New Applicant?                 | text      | text        |
| Yes      | numeric metric | requested_funding            | REQUESTED FUNDING              | money     | money       |
| Yes      | numeric metric | recommended_funding          | RECOMMENDED FUNDING            | money     | money       |
| Yes      | series tag     | program_name                 | PROGRAM NAME                   | text      | text        |
| No       |                | address                      | Address                        | text      | text        |
| Yes      | series tag     | city                         | City                           | text      | text        |
| Yes      | series tag     | state                        | State                          | text      | text        |
| Yes      | series tag     | zip                          | ZIP                            | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:rsnd-bbih d:2014-03-06T09:40:40.000Z t:zip=10003 t:new_applicant=No t:program_name="Manhattan Tax Aide" t:state=NY t:agency=DFTA t:brief_program_description="Manhattan Tax Aide is a volunteer-run tax return preparation service absoultely free to low and middle income elderly residents of Manhattan. In 2013 we prepared and efiled over 5,500 federal/state returns and had over 160 volunteers." t:mbpo_organization_dfta_fy_14="AARP Foundation -Manhattan Tax Aide" t:city="New York" m:requested_funding=5000 m:recommended_funding=5000

series e:rsnd-bbih d:2014-03-06T09:40:40.000Z t:zip=10027 t:new_applicant=No t:program_name="Harlem NNORC" t:state=NY t:agency=DFTA t:brief_program_description="The Abyssinian Development Corporation Harlem NNORC is designed to provide services and support to Harlem seniors to enable them to maintain independence and successfully age in place. This is accomplished by bringing together a variety of local businesses, community organizations, and elected officials to ensure that services are available to seniors and highlight important issues to be addressed by the community to transform Harlem into an age friendly place." t:mbpo_organization_dfta_fy_14="Abyssinian Development Corporation" t:city="New York" m:requested_funding=20000 m:recommended_funding=8750

series e:rsnd-bbih d:2014-03-06T09:40:40.000Z t:zip=10033 t:new_applicant=No t:program_name="Wellness Project" t:state=NY t:agency=DFTA t:brief_program_description="The proposed project aims to expand and enhance our exisiting wellness activities to accommodate the growing interest and increasing demands of our senior clientele. Our current wellness program is attended by 25+ of our 95 daily congregants, all of whom are 60 years old and above and live in the Washington Heights/Inwood area." t:mbpo_organization_dfta_fy_14="Agudath Israel of America Community Services, Inc." t:city="New York" m:requested_funding=5760 m:recommended_funding=3000
```

## Meta Commands

```ls
metric m:requested_funding p:double l:"REQUESTED FUNDING" t:dataTypeName=money

metric m:recommended_funding p:integer l:"RECOMMENDED FUNDING" t:dataTypeName=money

entity e:rsnd-bbih l:"Manhattan Community Grants" t:attribution="Manhattan Borough President (MBP)" t:url=https://data.cityofnewyork.us/api/views/rsnd-bbih

property e:rsnd-bbih t:meta.view v:id=rsnd-bbih v:category="City Government" v:averageRating=0 v:name="Manhattan Community Grants" v:attribution="Manhattan Borough President (MBP)"

property e:rsnd-bbih t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:rsnd-bbih t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | agency | mbpo_organization_dfta_fy_14                       | brief_program_description                                                                                                                                                                                                                                                                                                                                                                                                                                                         | new_applicant | requested_funding | recommended_funding | program_name                                  | address                                      | city     | state | zip   | 
| =========== | ====== | ================================================== | ================================================================================================================================================================================================================================================================================================================================================================================================================================================================================= | ============= | ================= | =================== | ============================================= | ============================================ | ======== | ===== | ===== | 
| 1394098840  | DFTA   | AARP Foundation -Manhattan Tax Aide                | Manhattan Tax Aide is a volunteer-run tax return preparation service absoultely free to low and middle income elderly residents of Manhattan. In 2013 we prepared and efiled over 5,500 federal/state returns and had over 160 volunteers.                                                                                                                                                                                                                                        | No            | 5000.00           | 5000                | Manhattan Tax Aide                            | c/o Elizabeth Mindlin - 130 East 18th Street | New York | NY    | 10003 | 
| 1394098840  | DFTA   | Abyssinian Development Corporation                 | The Abyssinian Development Corporation Harlem NNORC is designed to provide services and support to Harlem seniors to enable them to maintain independence and successfully age in place. This is accomplished by bringing together a variety of local businesses, community organizations, and elected officials to ensure that services are available to seniors and highlight important issues to be addressed by the community to transform Harlem into an age friendly place. | No            | 20000.00          | 8750                | Harlem NNORC                                  | 4 West 125th Street                          | New York | NY    | 10027 | 
| 1394098840  | DFTA   | Agudath Israel of America Community Services, Inc. | The proposed project aims to expand and enhance our exisiting wellness activities to accommodate the growing interest and increasing demands of our senior clientele. Our current wellness program is attended by 25+ of our 95 daily congregants, all of whom are 60 years old and above and live in the Washington Heights/Inwood area.                                                                                                                                         | No            | 5760.00           | 3000                | Wellness Project                              | 90 Bennett Avenue                            | New York | NY    | 10033 | 
| 1394098840  | DFTA   | Alpha Omega 1-7 Theatrical Dance Company, Inc.     | A choreography lab is being developed for the seniors of the East Harlem community at the Leonard Covello Senior Center. Utilizing a blend of contemporary modern dance and Latin influenced movement, choreography will be created and taught to approximately 20 senior participants.                                                                                                                                                                                           | Yes           | 7200.00           | 3000                | Wellness program - Choreography Lab           | 711 Amsterdam Avenue, Ste. 4E                | New York | NY    | 10025 | 
| 1394098840  | DFTA   | Ansonia Music Outreach Organization, Inc.          | Our Access to Music program continues to bring free classical music performances to the elderly at senior centers, nursing homes, and senior care facilities in New York City, through our Music for the Elderly Series. We provide enriching arts experiences where previously none were offered, and in many cases our musicians help seniors maintain the quality of life.                                                                                                     | No            | 6000.00           | 3000                | Access to Music: Music for the Elderly Series | 330 Wadsworth Avenue, 2G                     | New York | NY    | 10040 | 
| 1394098840  | DFTA   | Bloomingdale Aging in Place, Inc.                  | The Neighborhood Senior Wellness program of BAiP is aimed at reducing falls, frailty, stress and isolation in this vulnerable senior population. During the current (fiscal) year, thanks to the generosity of the MBPO Community Grant program, BAiP has offered free tai chi and yoga classes that have been attended, to date, by 52 BAiP members for an average of 11 sessions each.                                                                                          | No            | 6000.00           | 4000                | Neighborhood Senior Wellness                  | P.O. Box 497                                 | New York | NY    | 10025 | 
| 1394098840  | DFTA   | Canaan Baptist Church of Christ                    | Canaan serve the elderly population in Central Harlem, which consist of east and West from 110th Street to 155th Street North. Through the nutrition programs breakfast and lunch Canaan Serves an average of 20 to 40 breakfast and 55 to 60 lunches daily.                                                                                                                                                                                                                      | No            | 15000.00          | 5000                | Canaan Baptist Church of Christ               | 132 West 116th Street                        | New York | NY    | 10026 | 
| 1394098840  | DFTA   | Carnegie East House                                | The support services at Carnegie East House are important to the health and longevity of our nearly 100 older adult residents. We provide three meals a daily as well as nursing care, managing their appoinrments with doctors, monitoring their taking of medications and other programs designed to assure their continued health, mental acuity and quality of life.                                                                                                          | No            | 20000.00          | 0                   | Social Work Services                          | 1844 Second Avenue                           | New York | NY    | 10128 | 
| 1394098840  | DFTA   | Central Harlem Senior Citizen's Centers            | CHSCC seeks to collaborate with Harlem Seeds whose mission is to empower the Central Harlem community to live long and healthy lives by making appropriate food and lifestyle choices and instilling in them the principles that healthy living is a right and an obligation;not a privilege.                                                                                                                                                                                     | Yes           | 10000.00          | 3000                | Healthy In My Neighborhood                    | 34 West 134th Street                         | New York | NY    | 10037 | 
| 1394098840  | DFTA   | Church Street School for Music and Art, Inc.       | Church Street School for Music and Art's Seniors Chorus Program plays a key role in the artistic and cultural lives of Lower Manhattan's residents of advanced age. The seniors Chorus Program provides the opportunity for senior citizens to socialize with one another through a collaborative artistic process that expands their cultural horizons and helps support their physical and mental health.                                                                       | No            | 7500.00           | 4000                | Seniors Chorus Program                        | 74 Warren Street                             | New York | NY    | 10007 | 
```