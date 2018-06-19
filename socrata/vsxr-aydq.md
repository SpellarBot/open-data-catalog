# Seattle Cultural Space Inventory

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/seattle-cultural-space-inventory-aab3c) |
| Metadata | [Link](https://data.seattle.gov/api/views/vsxr-aydq) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/vsxr-aydq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/vsxr-aydq/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | vsxr-aydq |
| Name | Seattle Cultural Space Inventory |
| Attribution | Office of Arts & Culture | Seattle |
| Category | Community |
| Tags | art, space, cultural, square, feet, theater, galley, museum, artist, organization, creative |
| Created | 2014-04-18T16:42:48Z |
| Publication Date | 2017-03-27T22:01:35Z |

## Description

These are the results of this ongoing inventory of cultural space in Seattle. From the largest to the smallest, The Office of Arts & Culture are counting every theater, gallery, arts office, rehearsal room, library, music club, museum, and cinema in town.

## Columns

```ls
| Included | Schema Type    | Field Name                                            | Name                                                       | Data Type | Render Type |
| ======== | ============== | ===================================================== | ========================================================== | ========= | =========== |
| Yes      | series tag     | name                                                  | Name                                                       | text      | text        |
| Yes      | series tag     | phone                                                 | Phone                                                      | text      | text        |
| Yes      | series tag     | url                                                   | URL                                                        | text      | text        |
| Yes      | numeric metric | square_feet_total                                     | Square Feet Total                                          | number    | number      |
| Yes      | series tag     | neighborhood                                          | Neighborhood                                               | text      | text        |
| Yes      | series tag     | nonprofit                                             | Organization Type                                          | text      | text        |
| Yes      | series tag     | dominant_discipline                                   | Dominant Discipline                                        | text      | text        |
| Yes      | numeric metric | year_of_occupation                                    | Year of Occupation                                         | number    | number      |
| Yes      | series tag     | own_or_rent                                           | Rent vs Own                                                | text      | text        |
| Yes      | numeric metric | year_bldg_built                                       | Age of Current Building                                    | number    | number      |
| No       |                | site_control_through_date                             | Length of Lease (Date)                                     | text      | text        |
| Yes      | time           | year_founded                                          | Year Organization Founded                                  | number    | number      |
| Yes      | numeric metric | previous_facilities                                   | Number of Past Facilities                                  | number    | number      |
| Yes      | numeric metric | how_many_theaters                                     | Stages and Theaters                                        | number    | number      |
| Yes      | numeric metric | seats_total                                           | Stage & Theater Seats                                      | number    | number      |
| Yes      | series tag     | visual_art_galleries                                  | Gallery Space                                              | text      | text        |
| Yes      | numeric metric | square_feet                                           | Gallery Square Feet                                        | number    | number      |
| Yes      | series tag     | ada_compliant                                         | ADA Compliant                                              | text      | text        |
| Yes      | numeric metric | parking_spaces                                        | Available Parking                                          | number    | number      |
| Yes      | series tag     | street_frontage                                       | Street Presence                                            | text      | text        |
| Yes      | series tag     | rental_space_avail                                    | Rental Space                                               | text      | text        |
| Yes      | series tag     | serve_alcohol                                         | Alcohol Sales                                              | text      | text        |
| Yes      | series tag     | mission_2                                             | Organization Mission                                       | text      | text        |
| Yes      | series tag     | funded_by_a_c                                         | Funded by A&C                                              | text      | text        |
| Yes      | numeric metric | stability_index_5_very_stable_1_very_uncertain        | Stability Index (5=very stable, 1=very uncertain)          | number    | number      |
| Yes      | numeric metric | control_index_5_very_in_control_1_very_out_of_control | Control Index (5=very in control, 1 = very out of control) | number    | number      |
| Yes      | series tag     | constituency_over_50_one_race                         | Constituency over 50% one race                             | text      | text        |
| Yes      | series tag     | specific_demographics_and_community                   | Specific Demographics and Community                        | text      | text        |
| Yes      | series tag     | organization_leadership                               | Organization Leadership                                    | text      | text        |
| Yes      | series tag     | organization_artists                                  | Organization Artists                                       | text      | text        |
| No       |                | closed_date                                           | Closed Date                                                | text      | text        |
| Yes      | numeric metric | closed                                                | Closed?                                                    | number    | number      |
| No       |                | address                                               | Address                                                    | text      | text        |
```

## Time Field

```ls
Value = year_founded
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = site_control_through_date,closed_date,address
```

## Data Commands

```ls
series e:vsxr-aydq d:1983-01-01T00:00:00.000Z t:phone="(206) 632-6397" t:organization_leadership=N/A t:specific_demographics_and_community=General t:ada_compliant=Y t:visual_art_galleries=Y t:neighborhood="University District" t:street_frontage=Y t:mission_2="By providing a comprehensive selection of periodicals and a gather place for coffee and conversation, Bulldog News encourages a convening of perspectives. We hope we act in support of the community as it creates for itself a unique identity based upon something more than individual or collective""interests""." t:dominant_discipline=Literary t:url=http://www.bulldognews.com/ t:funded_by_a_c=N t:organization_artists=N/A t:name="Bulldog News" t:rental_space_avail=No t:serve_alcohol=N t:nonprofit=N t:own_or_rent=R m:year_bldg_built=1930 m:how_many_theaters=0 m:control_index_5_very_in_control_1_very_out_of_control=2 m:stability_index_5_very_stable_1_very_uncertain=4 m:square_feet_total=500 m:seats_total=8 m:closed=0 m:previous_facilities=1 m:square_feet=0 m:year_of_occupation=1985

series e:vsxr-aydq d:2013-01-01T00:00:00.000Z t:phone="(206) 769-1151" t:organization_leadership=N/A t:specific_demographics_and_community=no t:ada_compliant=N t:visual_art_galleries=Y t:neighborhood="Pioneer Square" t:street_frontage=Y t:mission_2="The mission of METHOD Gallery is to foster and exhibit sculpture and installation that regards process, material, and concept, while engaging the METHOD space." t:dominant_discipline=Visual t:url=http://www.methodgallery.com/ t:funded_by_a_c=P t:organization_artists=N/A t:name="METHOD Gallery" t:serve_alcohol=N t:nonprofit=Y t:own_or_rent=R m:year_bldg_built=1907 m:control_index_5_very_in_control_1_very_out_of_control=4 m:stability_index_5_very_stable_1_very_uncertain=2 m:square_feet_total=800 m:previous_facilities=0 m:square_feet=800 m:year_of_occupation=2013

series e:vsxr-aydq d:2011-01-01T00:00:00.000Z t:phone="(206) 954-3497" t:organization_leadership=N/A t:specific_demographics_and_community=General t:ada_compliant=N t:visual_art_galleries=N t:neighborhood="Seward Park" t:street_frontage=N t:mission_2="To bring fun art experiences to people in South Seattle" t:dominant_discipline="Arts/Cultural Training or Education" t:url=https://themakeryseattleblog.wordpress.com t:funded_by_a_c=N t:organization_artists=N/A t:name="The Makery" t:rental_space_avail=No t:serve_alcohol=N t:nonprofit=N t:own_or_rent=R m:year_bldg_built=1940 m:control_index_5_very_in_control_1_very_out_of_control=3 m:stability_index_5_very_stable_1_very_uncertain=4 m:square_feet_total=500 m:closed=0 m:previous_facilities=0 m:year_of_occupation=2
```

## Meta Commands

```ls
metric m:square_feet_total p:double l:"Square Feet Total" t:dataTypeName=number

metric m:year_of_occupation p:float l:"Year of Occupation" t:dataTypeName=number

metric m:year_bldg_built p:float l:"Age of Current Building" t:dataTypeName=number

metric m:previous_facilities p:float l:"Number of Past Facilities" t:dataTypeName=number

metric m:how_many_theaters p:float l:"Stages and Theaters" t:dataTypeName=number

metric m:seats_total p:double l:"Stage & Theater Seats" t:dataTypeName=number

metric m:square_feet p:float l:"Gallery Square Feet" t:dataTypeName=number

metric m:parking_spaces p:float l:"Available Parking" t:dataTypeName=number

metric m:stability_index_5_very_stable_1_very_uncertain p:float l:"Stability Index (5=very stable, 1=very uncertain)" t:dataTypeName=number

metric m:control_index_5_very_in_control_1_very_out_of_control p:float l:"Control Index (5=very in control, 1 = very out of control)" t:dataTypeName=number

metric m:closed p:float l:Closed? d:"1=True 0=False" t:dataTypeName=number

entity e:vsxr-aydq l:"Seattle Cultural Space Inventory" t:attribution="Office of Arts & Culture | Seattle" t:url=https://data.seattle.gov/api/views/vsxr-aydq

property e:vsxr-aydq t:meta.view v:id=vsxr-aydq v:category=Community v:attributionLink=http://www.seattle.gov/arts/ v:averageRating=0 v:name="Seattle Cultural Space Inventory" v:attribution="Office of Arts & Culture | Seattle"

property e:vsxr-aydq t:meta.view.license v:name="Public Domain"

property e:vsxr-aydq t:meta.view.owner v:id=n96i-9u3b v:screenName="Pierce, Jeffrey" v:displayName="Pierce, Jeffrey"

property e:vsxr-aydq t:meta.view.tableauthor v:id=n96i-9u3b v:screenName="Pierce, Jeffrey" v:roleName=publisher v:displayName="Pierce, Jeffrey"
```

## Top Records

```ls
| name                         | phone          | url                                          | square_feet_total | neighborhood        | nonprofit | dominant_discipline                 | year_of_occupation | own_or_rent | year_bldg_built | site_control_through_date | year_founded | previous_facilities | how_many_theaters | seats_total | visual_art_galleries | square_feet | ada_compliant | parking_spaces | street_frontage | rental_space_avail | serve_alcohol | mission_2                                                                                                                                                                                                                                                                                                                                           | funded_by_a_c | stability_index_5_very_stable_1_very_uncertain | control_index_5_very_in_control_1_very_out_of_control | constituency_over_50_one_race | specific_demographics_and_community            | organization_leadership | organization_artists | closed_date | closed | address                                 | 
| ============================ | ============== | ============================================ | ================= | =================== | ========= | =================================== | ================== | =========== | =============== | ========================= | ============ | =================== | ================= | =========== | ==================== | =========== | ============= | ============== | =============== | ================== | ============= | =================================================================================================================================================================================================================================================================================================================================================== | ============= | ============================================== | ===================================================== | ============================= | ============================================== | ======================= | ==================== | =========== | ====== | ======================================= | 
| Bulldog News                 | (206) 632-6397 | http://www.bulldognews.com/                  | 500.0             | University District | N         | Literary                            | 1985.0             | R           | 1930.0          | 2020.0                    | 1983.0       | 1.0                 | 0.0               | 8.0         | Y                    | 0.0         | Y             |                | Y               | No                 | N             | By providing a comprehensive selection of periodicals and a gather place for coffee and conversation, Bulldog News encourages a convening of perspectives. We hope we act in support of the community as it creates for itself a unique identity based upon something more than individual or collective"interests".                                | N             | 4.0                                            | 2.0                                                   |                               | General                                        | N/A                     | N/A                  |             | 0.0    | 4208 University Way NE Seattle WA 98105 | 
| METHOD Gallery               | (206) 769-1151 | http://www.methodgallery.com/                | 800.0             | Pioneer Square      | Y         | Visual                              | 2013.0             | R           | 1907.0          | 0.0                       | 2013.0       | 0.0                 |                   |             | Y                    | 800.0       | N             |                | Y               |                    | N             | The mission of METHOD Gallery is to foster and exhibit sculpture and installation that regards process, material, and concept, while engaging the METHOD space.                                                                                                                                                                                     | P             | 2.0                                            | 4.0                                                   |                               | no                                             | N/A                     | N/A                  |             |        | 106 Third Ave S                         | 
| The Makery                   | (206) 954-3497 | https://themakeryseattleblog.wordpress.com   | 500.0             | Seward Park         | N         | Arts/Cultural Training or Education | 2.0                | R           | 1940.0          | 0.0                       | 2011.0       | 0.0                 |                   |             | N                    |             | N             |                | N               | No                 | N             | To bring fun art experiences to people in South Seattle                                                                                                                                                                                                                                                                                             | N             | 4.0                                            | 3.0                                                   |                               | General                                        | N/A                     | N/A                  |             | 0.0    | 5019 52nd St Seattle WA 98118           | 
| SEEDArts Studios             | (206) 760-4286 | http://www.seedseattle.org/seedarts-studios/ | 10200.0           | Hillman City        | Y         | Studios                             | 2014.0             | R           | 1920.0          | 2024.0                    | 1977.0       | 4.0                 |                   |             | N                    |             | N             |                | N               | Yes                | N             | The SEEDArts Studios in Hillman City are home to 22 artist studios and office spaces for creative enterprises.                                                                                                                                                                                                                                      | P             | 4.0                                            | 3.0                                                   |                               | We reflect the diversity of our community.     | Yes                     | N/A                  |             |        | 5617 Rainier Ave S                      | 
| The Royal Room               | (206) 906-9920 |                                              | 3000.0            | Columbia City       | N         | Music                               | 2011.0             | R           | 1917.0          | 2019.0                    | 2011.0       | 3.0                 | 1.0               | 150.0       | N                    |             | Y             |                | Y               | Yes                | Y             | Providing a venue for both musicians and the public to enjoy all types of music played by all types of people.                                                                                                                                                                                                                                      | N             | 4.0                                            | 3.0                                                   |                               | general                                        | N/A                     | N/A                  |             |        | 5000 Rainier Ave S                      | 
| Green Eileen                 | (206) 722-2551 | http://www.greeneileen.org/                  | 2500.0            | Columbia City       | N         | Arts/Cultural Training or Education | 2013.0             | R           | 1900.0          | 2021.0                    | 2013.0       |                     |                   |             | N                    |             | Y             |                | Y               | No                 | N             | GREEN EILEEN is a recycled clothing program committed to reducing environmental impact and generating income to support programs that improve the lives of women and girls. By selling gently worn EILEEN FISHER clothing, we extend the life of timeless garments and are able to support the non-profit programs in which we so strongly believe. | N             | 5.0                                            | 3.0                                                   |                               | Women, girls & their connected communities     |                         |                      |             | 0.0    | 4860 Rainier Ave S.                     | 
| Macabee Martial Arts Seattle | (206) 979-0459 | http://www.macabeeseattle.com                | 300.0             | Hillman City        | N         | Arts/Cultural Training or Education | 2012.0             | R           | 1960.0          | 0.0                       | 2016.0       | 0.0                 | 0.0               | 0.0         | N                    | 0.0         | N             |                | N               | No                 | N             | Train all ages in traditional Kung fu and self defense.                                                                                                                                                                                                                                                                                             | N             | 2.0                                            | 1.0                                                   |                               | Jewish and general                             | Yes                     | Yes                  |             | 0.0    | 5145 S Morgan St                        | 
| Jazz Night School            | (206) 722-6061 | http://www.jazznightschool.org               | 1500.0            | Hillman City        | Y         | Arts/Cultural Training or Education | 2016.0             | R           | 1950.0          | 2026.0                    | 2008.0       | 1.0                 | 1.0               | 35.0        | N                    | 0.0         | Y             |                | Y               | Yes                | N             | Jazz Night School uplifts lives by providing an exceptional and supportive environment where people of all ages and abilities come together to learn, perform, and enjoy jazz.                                                                                                                                                                      | P             | 4.0                                            | 4.0                                                   |                               | General                                        | N/A                     | N/A                  |             | 0.0    | 3916 S Morgan St                        | 
| SPLAB Seattle Poetics LAB    | (206) 422-5002 | http://www.splab.org                         | 150.0             | Columbia City       | Y         | Literary                            | 2015.0             | R           | 2015.0          | 2017.0                    | 1993.0       | 2.0                 | 0.0               | 0.0         | N                    | 0.0         | Y             |                | N               | No                 | N             | The SPLAB mission is to present poetry events, develop the audience and resources to support poetry, lead a bioregional cultural investigation using poetics and poetry festivals as main methodologies and build community through shared experience of the spoken and written word.                                                               | P             | 3.0                                            | 3.0                                                   |                               | Low Income                                     | Yes                     | Yes                  |             |        | 4801 Rainier Ave S                      | 
| Mead St.                     | (253) 683-0790 |                                              | 1000.0            | Hillman City        | Y         | Music                               | 2016.0             | R           | 1910.0          | 2019.0                    | 2016.0       | 0.0                 |                   |             | N                    |             | Y             |                | N               | No                 | N             | Provide access to creative tools and technology while promoting intersectionality and mindfulness                                                                                                                                                                                                                                                   | N             | 5.0                                            | 3.0                                                   |                               | We aim to empower women int he recording arts. | Yes                     | Yes                  |             |        | 5800 Rainier Ave S                      | 
```