# Technology Matching Funds

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/technology-matching-funds-86c56) |
| Metadata | [Link](https://data.seattle.gov/api/views/6d4q-w9dv) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/6d4q-w9dv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/6d4q-w9dv/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | 6d4q-w9dv |
| Name | Technology Matching Funds |
| Attribution | City of Seattle, CommunityTechnology |
| Category | Community |
| Tags | grants, funding, community, technology, digital, inclusion, matching funds |
| Created | 2016-09-15T21:37:51Z |
| Publication Date | 2016-09-15T22:01:57Z |

## Description

All awarded Technology Matching Fund projects from 1998-2016.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| Yes      | series tag     | organization_name   | Organization Name   | text      | text        |
| Yes      | series tag     | project_title       | Project Title       | text      | text        |
| Yes      | series tag     | project_description | Project Description | text      | text        |
| Yes      | series tag     | type                | Type                | text      | text        |
| Yes      | numeric metric | award_amount        | Award Amount        | money     | money       |
| Yes      | numeric metric | match_amount        | Match Amount        | money     | money       |
| Yes      | time           | award_year          | Award Year          | number    | text        |
| No       |                | address             | Address             | text      | text        |
| Yes      | series tag     | council_district    | Council District    | text      | text        |
| Yes      | series tag     | zip_code            | Zip Code            | text      | text        |
| No       |                | longitude           | Longitude           | number    | text        |
| No       |                | latitude            | Latitude            | number    | text        |
```

## Time Field

```ls
Value = award_year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = address,longitude,latitude
```

## Data Commands

```ls
series e:6d4q-w9dv d:2011-01-01T00:00:00.000Z t:zip_code=98144 t:project_title="Mobile Computer Lab" t:council_district=3 t:project_description="Build a mobile computer lab and train a team of worker-leaders and volunteers to provide basic computer and Internet training for Latino immigrants." t:organization_name="Casa Latina" m:award_amount=14837 m:match_amount=17860

series e:6d4q-w9dv d:2011-01-01T00:00:00.000Z t:zip_code=98144 t:project_title="Mobile computer lab expansion" t:council_district=3 t:project_description="Hire part-time staff to expand hours of mobile computer lab training and offer a summer computer literacy camp for newly arrived refugees from Burma." t:organization_name="Coalition for Refugees from Burma" m:award_amount=17750 m:match_amount=22560

series e:6d4q-w9dv d:2011-01-01T00:00:00.000Z t:zip_code=98104 t:project_title="Technology Access & Literacy Enhancement" t:council_district=7 t:project_description="Upgrade computers at the Drop-in Center and Computer Lab serving homeless clients, and provide portable USB drives to clients enrolled in technology and job skills classes. Upgrade software to Microsoft Professional Plus so that clients can learn to use" t:organization_name="Downtown Emergency Service Center" m:award_amount=15000 m:match_amount=21350
```

## Meta Commands

```ls
metric m:award_amount p:integer l:"Award Amount" t:dataTypeName=money

metric m:match_amount p:integer l:"Match Amount" t:dataTypeName=money

entity e:6d4q-w9dv l:"Technology Matching Funds" t:attribution="City of Seattle, CommunityTechnology" t:url=https://data.seattle.gov/api/views/6d4q-w9dv

property e:6d4q-w9dv t:meta.view v:id=6d4q-w9dv v:category=Community v:attributionLink=http://www.seattle.gov/tech v:averageRating=0 v:name="Technology Matching Funds" v:attribution="City of Seattle, CommunityTechnology"

property e:6d4q-w9dv t:meta.view.license v:name="Public Domain"

property e:6d4q-w9dv t:meta.view.owner v:id=fs78-6jsr v:screenName="Blood, Bruce" v:displayName="Blood, Bruce"

property e:6d4q-w9dv t:meta.view.tableauthor v:id=fs78-6jsr v:screenName="Blood, Bruce" v:displayName="Blood, Bruce"
```

## Top Records

```ls
| organization_name                      | project_title                                                           | project_description                                                                                                                                                                                                                                            | type | award_amount | match_amount | award_year | address               | council_district | zip_code | longitude | latitude | 
| ====================================== | ======================================================================= | ============================================================================================================================================================================================================================================================== | ==== | ============ | ============ | ========== | ===================== | ================ | ======== | ========= | ======== | 
| Casa Latina                            | Mobile Computer Lab                                                     | Build a mobile computer lab and train a team of worker-leaders and volunteers to provide basic computer and Internet training for Latino immigrants.                                                                                                           |      | 14837        | 17860        | 2011       | 317 17th AVE S        | 3                | 98144    | -122.3104 | 47.5999  | 
| Coalition for Refugees from Burma      | Mobile computer lab expansion                                           | Hire part-time staff to expand hours of mobile computer lab training and offer a summer computer literacy camp for newly arrived refugees from Burma.                                                                                                          |      | 17750        | 22560        | 2011       | 1265 S Main ST        | 3                | 98144    | -122.3155 | 47.6000  | 
| Downtown Emergency Service Center      | Technology Access & Literacy Enhancement                                | Upgrade computers at the Drop-in Center and Computer Lab serving homeless clients, and provide portable USB drives to clients enrolled in technology and job skills classes. Upgrade software to Microsoft Professional Plus so that clients can learn to use  |      | 15000        | 21350        | 2011       | 515 3rd AVE           | 7                | 98104    | -122.3309 | 47.6021  | 
| Ethiopian Community Mutual Association | Computer Resource Center Project                                        | Upgrade the existing resource center with state-of-the art desktop and laptop computers and software to provide Ethiopians and Ethiopian-Americans with English and Amharic learning resources, homework help, job and Internet skills.                        |      | 17296        | 22520        | 2011       | 8323 Rainier AVE S    | 2                | 98118    | -122.2701 | 47.5288  | 
| InterConnection                        | PC Hardware Repair Training and A+ Certification Program                | Develop a three month training program in partnership with the business community that offers low income individuals job skills and life skills training, real world job experience and industry level A+ certification.                                       |      | 15733        | 18620        | 2011       | 3415 Stone Way N      | 4                | 98013    | -122.3429 | 47.6487  | 
| Jack Straw Foundation                  | Language and Technology Literacy: English Language Learners             | English Language Learners attending the Seattle Public Schools' Secondary Bilingual Orientation Center will write, perform and record their own audio pieces around family and cultural traditions and community issues. Funds will also upgrade the technolog |      | 19924        | 35437        | 2011       | 4261 Roosevelt Way NE | 4                | 98105    | -122.3179 | 47.6586  | 
| NW Parkinson's Foundation              | Health Web Browsing Training for People Living with Parkinson's Disease | Develop and implement six training seminars for people with Parkinson's disease on how to use their website health resources and chat rooms, and introduce adaptive technology to aid web navigation for people with hand tremors and other motor difficulties |      | 5700         | 5700         | 2011       | 400 Mercer ST         | 7                | 98109    | -122.3489 | 47.6246  | 
| Plymouth Housing Group                 | Plymouth Place Computer Resource Center Upgrade                         | Replace eight computers in the Computer Resource Center and expand programming to involve low income tenants in greater community awareness, problem solving and civic engagement.                                                                             |      | 3600         | 4580         | 2011       | 2113 3rd AVE          | 7                | 98121    | -122.3424 | 47.6132  | 
| Reel Grrls                             | Project Access                                                          | Upgrade media lab with voice recognition software and other adaptive equipment to expand media production training to serve teenage girls with disabilities. The project will hAVE girls with and without disabilities work together to produce a documentary  |      | 16555        | 20250        | 2011       | 1409 21st AVE         | 3                | 98122    | -122.3050 | 47.6131  | 
| Salaam Urban Village Association       | Technology Education Center                                             | Provide technology training with translation support to 40 East African youth and adults. Create an ongoing digital storytelling program that records the life stories of elders in the community.                                                             |      | 16555        | 23650        | 2011       | 3642 33rd AVE S       | 2                | 98144    | -122.2909 | 47.5712  | 
```