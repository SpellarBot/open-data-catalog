# Transit Communities Funding Toolkit

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/transit-communities-funding-toolkit-a7336) |
| Metadata | [Link](https://data.seattle.gov/api/views/bnq7-2pc8) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/bnq7-2pc8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/bnq7-2pc8/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | bnq7-2pc8 |
| Name | Transit Communities Funding Toolkit |
| Attribution | City of Seattle, Seattle Planning Commission |
| Category | Community |
| Tags | funding, levies, community development, economic development |
| Created | 2011-02-14T19:47:12Z |
| Publication Date | 2011-04-17T00:03:09Z |

## Description

The funding toolkit identifies funding sources for three broad categories of livability elements: infrastructure investments, which may include right-of-way improvements, sidewalks, Green Streets, or bike lanes/facilities; community development, such as affordable housing, public services, schools, historic preservation; and parks and open space, which includes parks, playfields, plazas, and p-patches.

## Columns

```ls
| Included | Schema Type | Field Name            | Name                  | Data Type | Render Type |
| ======== | =========== | ===================== | ===================== | ========= | =========== |
| No       | time        | :updated_at           | updated_at            | meta_data | meta_data   |
| Yes      | series tag  | administrator         | administrator         | text      | text        |
| Yes      | series tag  | program               | program               | text      | text        |
| Yes      | series tag  | infrastructure        | infrastructure        | checkbox  | checkbox    |
| Yes      | series tag  | community_development | community development | checkbox  | checkbox    |
| Yes      | series tag  | open_space            | open space            | checkbox  | checkbox    |
| Yes      | series tag  | funding_amount        | funding amount        | text      | text        |
| Yes      | series tag  | funding_type          | funding type          | text      | text        |
| Yes      | series tag  | description           | description           | text      | text        |
| Yes      | series tag  | opportunities         | opportunities         | text      | text        |
| Yes      | series tag  | challenges            | challenges            | text      | text        |
| Yes      | series tag  | website               | website               | url       | url         |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:bnq7-2pc8 d:2011-02-14T11:47:16.000Z t:website=http://www.seattle.gov/arts/publicart/default.asp t:administrator="Arts & Cultural Affairs" t:open_space=false t:infrastructure=false t:funding_type="legislative encumbrance" t:community_development=true t:description="identifies and coordinates opportunities to include public art in capital projects funded at the local, state, and federal levels." t:program="1% for Art" t:funding_amount=$ m:row_number.bnq7-2pc8=1

series e:bnq7-2pc8 d:2011-02-14T11:47:16.000Z t:website=http://www.seattle.gov/parks/levy/opportunity.htm t:administrator=Parks t:open_space=true t:infrastructure=false t:funding_type="competitive grants" t:community_development=false t:description="funds community-initiated park development or acquisition projects." t:program="Opportunity Fund" t:funding_amount=$-$$ m:row_number.bnq7-2pc8=2

series e:bnq7-2pc8 d:2011-02-14T11:47:16.000Z t:website=http://www.seattle.gov/neighborhoods/nmf/ t:administrator=DON t:open_space=true t:infrastructure=true t:funding_type="matching grants" t:community_development=true t:description="include four funds (Small Sparks, Small and Simple Projects, Large Projects, and Tree) for community-initiated neighborhood projects." t:program="Neighborhood Matching Fund" t:funding_amount=$-$$ m:row_number.bnq7-2pc8=3
```

## Meta Commands

```ls
metric m:row_number.bnq7-2pc8 p:long l:"Row Number"

entity e:bnq7-2pc8 l:"Transit Communities Funding Toolkit" t:attribution="City of Seattle, Seattle Planning Commission" t:url=https://data.seattle.gov/api/views/bnq7-2pc8

property e:bnq7-2pc8 t:meta.view d:2017-09-25T07:28:20.104Z v:averageRating=0 v:name="Transit Communities Funding Toolkit" v:attribution="City of Seattle, Seattle Planning Commission" v:id=bnq7-2pc8 v:category=Community

property e:bnq7-2pc8 t:meta.view.license d:2017-09-25T07:28:20.104Z v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:bnq7-2pc8 t:meta.view.owner d:2017-09-25T07:28:20.104Z v:displayName="Sheehy, Katie" v:profileImageUrlLarge=/api/users/9vuc-jwdr/profile_images/LARGE v:profileImageUrlSmall=/api/users/9vuc-jwdr/profile_images/TINY v:id=9vuc-jwdr v:screenName="Sheehy, Katie" v:profileImageUrlMedium=/api/users/9vuc-jwdr/profile_images/THUMB

property e:bnq7-2pc8 t:meta.view.tableauthor d:2017-09-25T07:28:20.104Z v:displayName="Seattle IT" v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:roleName=administrator v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:id=pfbu-yuv5 v:screenName="Seattle IT" v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB
```

## Top Records

```ls
| :updated_at | administrator           | program                            | infrastructure | community_development | open_space | funding_amount | funding_type            | description                                                                                                                                                                                                                   | opportunities | challenges                                                                                                                                                                               | website                                                                     | 
| =========== | ======================= | ================================== | ============== | ===================== | ========== | ============== | ======================= | ============================================================================================================================================================================================================================= | ============= | ======================================================================================================================================================================================== | =========================================================================== | 
| 1297684036  | Arts & Cultural Affairs | 1% for Art                         | false          | true                  | false      | $              | legislative encumbrance | identifies and coordinates opportunities to include public art in capital projects funded at the local, state, and federal levels.                                                                                            |               |                                                                                                                                                                                          | [http://www.seattle.gov/arts/publicart/default.asp, null]                   | 
| 1297684036  | Parks                   | Opportunity Fund                   | false          | false                 | true       | $-$$           | competitive grants      | funds community-initiated park development or acquisition projects.                                                                                                                                                           |               |                                                                                                                                                                                          | [http://www.seattle.gov/parks/levy/opportunity.htm, null]                   | 
| 1297684036  | DON                     | Neighborhood Matching Fund         | true           | true                  | true       | $-$$           | matching grants         | include four funds (Small Sparks, Small and Simple Projects, Large Projects, and Tree) for community-initiated neighborhood projects.                                                                                         |               |                                                                                                                                                                                          | [http://www.seattle.gov/neighborhoods/nmf/, null]                           | 
| 1297684036  | OH                      | Multifamily Tax Exemption          | false          | true                  | false      | $$-$$$         | tax credits/exemptions  | contributes to the development of affordable housing (one piece of funding available to for- and non-profit developers and public development authorities to build affordable housing.                                        |               |                                                                                                                                                                                          | [http://www.seattle.gov/housing/incentives/mfte.htm, null]                  | 
| 1297684036  | SDOT                    | Local Improvement Districts        | true           | false                 | false      | $$-$$$         | special assessments     | provide funding for large projects that can create a demonstrable increase in property value [want to deemphasize this as a potential tool but I think it's hard to leave out]                                                |               | requires agreement from 60% of property owners                                                                                                                                           | [null, null]                                                                | 
| 1297684036  | OED                     | Business Improvement Area          | false          | true                  | false      | $-$$           | special assessments     | fund services and improvements in neighborhood business districts. While the business district is governed by a ratepayer's advisory board, the City provides support, collects the assessments, and reimburses BIA expenses. |               |                                                                                                                                                                                          | [http://www.seattle.gov/economicdevelopment/support_tools.htm, null]        | 
| 1297684036  | OED                     | Community Revitalization Financing | false          | false                 | false      |                |                         | funds infrastructure improvements through increased value of property taxes?!?!?                                                                                                                                              |               | no info found at OED's website.                                                                                                                                                          | [null, null]                                                                | 
| 1297684036  | SDOT                    | Impact Fees                        | true           | true                  | true       | $$$            | development fees        | help pay for the cost of new services and public facilities needed to support growth                                                                                                                                          |               |                                                                                                                                                                                          | [null, null]                                                                | 
| 1297684036  | OED                     | Real Estate Financing              | false          | true                  | false      |                | loans                   | , Section 108 and Float Loans, that help finance development of mixed-use and commercial buildings.                                                                                                                           |               |                                                                                                                                                                                          | [http://www.seattle.gov/EconomicDevelopment/financial_realestate.htm, null] | 
| 1297684036  | Arts & Cultural Affairs | Neighborhood & Community Arts      | false          | true                  | false      | $              | competitive grants      | provide funds for community activities such as street fairs and art walks                                                                                                                                                     |               | must be a Neighborhood Arts Council or Community Stewardship group that has been existing for at least one year with a track record of producing recurring festivals or community events | [http://www.seattle.gov/arts/funding/neighborhood_community.asp, null]      | 
```