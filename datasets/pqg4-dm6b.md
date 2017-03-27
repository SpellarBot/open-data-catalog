# NYC Women's Resource Network Database

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nyc-womens-resource-network-database-b167e) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/pqg4-dm6b) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/pqg4-dm6b/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/pqg4-dm6b/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | pqg4-dm6b |
| Name | NYC Women's Resource Network Database |
| Attribution | Commission on Women's Issues (CWI) |
| Category | Social Services |
| Tags | jobs and economic mobility, women, woman, family, families, resource, network |
| Created | 2011-07-27T14:49:32Z |
| Publication Date | 2011-10-08T21:59:56Z |

## Description

The NYC Women's Resource Network is a free, user-friendly database of over 1,000 nonprofit organizations and governmental agencies that work to advance and benefit women and families in New York City.  A user can tailor their search by keyword, category, and/or borough to receive a customized listing of organizations that address their needs.

## Columns

```ls
| Included | Schema Type | Field Name                                       | Name                                             | Data Type | Render Type |
| ======== | =========== | ================================================ | ================================================ | ========= | =========== |
| No       | time        | :updated_at                                      | updated_at                                       | meta_data | meta_data   |
| Yes      | series tag  | organizationname                                 | OrganizationName                                 | text      | text        |
| Yes      | series tag  | brooklyn                                         | Brooklyn                                         | text      | text        |
| Yes      | series tag  | bronx                                            | Bronx                                            | text      | text        |
| Yes      | series tag  | manhattan                                        | Manhattan                                        | text      | text        |
| Yes      | series tag  | queens                                           | Queens                                           | text      | text        |
| Yes      | series tag  | staten_island                                    | Staten Island                                    | text      | text        |
| Yes      | series tag  | fax                                              | Fax                                              | text      | number      |
| Yes      | series tag  | phone                                            | Phone                                            | text      | number      |
| Yes      | series tag  | url                                              | URL                                              | text      | text        |
| Yes      | series tag  | nourl                                            | noURL                                            | text      | text        |
| Yes      | series tag  | description                                      | Description                                      | text      | text        |
| Yes      | series tag  | outsideloc                                       | outsideLoc                                       | text      | text        |
| Yes      | series tag  | outsidelocdesc                                   | outsideLocDesc                                   | text      | text        |
| Yes      | series tag  | aging                                            | Aging                                            | text      | text        |
| Yes      | series tag  | anti_discrimination_human_rights                 | Anti-Discrimination & Human Rights               | text      | text        |
| Yes      | series tag  | arts_culture                                     | Arts & Culture                                   | text      | text        |
| Yes      | series tag  | business                                         | Business                                         | text      | text        |
| Yes      | series tag  | child_care_parent_information                    | Child Care & Parent Information                  | text      | text        |
| Yes      | series tag  | community_service_volunteerism                   | Community Service & Volunteerism                 | text      | text        |
| Yes      | series tag  | counseling_support_groups                        | Counseling & Support Groups                      | text      | text        |
| Yes      | series tag  | disabilities                                     | Disabilities                                     | text      | text        |
| Yes      | series tag  | domestic_violence                                | Domestic Violence                                | text      | text        |
| Yes      | series tag  | education                                        | Education                                        | text      | text        |
| Yes      | series tag  | employment_job_training                          | Employment & Job Training                        | text      | text        |
| Yes      | series tag  | health                                           | Health                                           | text      | text        |
| Yes      | series tag  | homelessness                                     | Homelessness                                     | text      | text        |
| Yes      | series tag  | housing                                          | Housing                                          | text      | text        |
| Yes      | series tag  | immigration                                      | Immigration                                      | text      | text        |
| Yes      | series tag  | legal_services                                   | Legal Services                                   | text      | text        |
| Yes      | series tag  | lesbian_gay_bisexual_and_or_transgender          | Lesbian, Gay, Bisexual, and/or Transgender       | text      | text        |
| Yes      | series tag  | personal_finance_financial_education             | Personal Finance & Financial Education           | text      | text        |
| Yes      | series tag  | professional_association                         | Professional Association                         | text      | text        |
| Yes      | series tag  | veterans_military_families                       | Veterans & Military Families                     | text      | text        |
| Yes      | series tag  | victim_services                                  | Victim Services                                  | text      | text        |
| Yes      | series tag  | women_s_groups                                   | Women's Groups                                   | text      | text        |
| Yes      | series tag  | youth_services                                   | Youth Services                                   | text      | text        |
| Yes      | series tag  | faith_based_organization                         | Faith-based organization                         | text      | text        |
| Yes      | series tag  | foundation                                       | Foundation                                       | text      | text        |
| Yes      | series tag  | is_registered_with_the_attorney_general_s_office | Is registered with the Attorney General's office | text      | text        |
| Yes      | series tag  | new_york_city_agency                             | New York City Agency                             | text      | text        |
| Yes      | series tag  | none_of_the_above                                | None of the above                                | text      | text        |
| Yes      | series tag  | nonprofit                                        | Nonprofit                                        | text      | text        |
| Yes      | series tag  | comments                                         | Comments                                         | text      | text        |
| Yes      | series tag  | other_government_organization                    | Other government organization                    | text      | text        |
| Yes      | series tag  | published                                        | Published                                        | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:pqg4-dm6b d:2011-07-27T07:49:35.000Z t:community_service_volunteerism=N t:none_of_the_above=N t:victim_services=N t:phone=2127554500 t:disabilities=N t:child_care_parent_information=Y t:arts_culture=N t:education=N t:lesbian_gay_bisexual_and_or_transgender=N t:business=N t:veterans_military_families=N t:domestic_violence=N t:employment_job_training=Y t:description="Established in 1858, the YWCA of the City of New York is one of the nationï¿½s oldest non-profit organizations. Our mission is to address the critical needs of New York City women and to empower them for success and leadership in their lives, jobs and communities. We focus on underserved families through job training, educational child care and after school programs; partnerships with business, government and other not-for-profits; and advocacy on behalf of the clients we serve." t:immigration=N t:legal_services=N t:foundation=N t:nonprofit=Y t:published=Published t:aging=N t:organizationname="YWCA of the City of New York" t:staten_island=Y t:fax=2122236438 t:is_registered_with_the_attorney_general_s_office=N t:housing=N t:manhattan=Y t:nourl=N t:health=N t:youth_services=Y t:other_government_organization=N t:url=http://www.ywcanyc.org t:personal_finance_financial_education=N t:faith_based_organization=N t:outsideloc=N t:new_york_city_agency=N t:queens=N t:anti_discrimination_human_rights=N t:professional_association=N t:bronx=N t:homelessness=N t:counseling_support_groups=Y t:brooklyn=Y m:row_number.pqg4-dm6b=1

series e:pqg4-dm6b d:2011-07-27T07:49:35.000Z t:community_service_volunteerism=N t:none_of_the_above=N t:victim_services=N t:phone=2129660228 t:disabilities=N t:child_care_parent_information=N t:arts_culture=N t:education=N t:lesbian_gay_bisexual_and_or_transgender=N t:business=N t:veterans_military_families=N t:domestic_violence=N t:employment_job_training=N t:description="The Women's Health Department is a unique community based health care program serving uninsured women in New York City. The majority of our clients are low income women who are recent immigrants. The Health Center provides a wide array of primary and specialty services, including gynecological care, family planning, pregnancy testing, prenatal and postnatal care, genetic and nutritional counseling, breast-feeding education, screening and education for HIV and STD infections, and screening and education for breast, cervical, ovarian and prostate cancers. The Women's Health Department also sponsors many outreach and health education programs to promote and increase the community's awareness of women's health issues." t:immigration=N t:legal_services=N t:foundation=N t:nonprofit=Y t:published=Published t:aging=N t:organizationname="Charles B. Wang Community Health Center" t:staten_island=N t:housing=N t:is_registered_with_the_attorney_general_s_office=N t:manhattan=Y t:nourl=N t:health=Y t:youth_services=N t:other_government_organization=N t:url=http://www.cbwchc.org/hcs/wh/wh.html t:personal_finance_financial_education=N t:faith_based_organization=N t:outsideloc=N t:new_york_city_agency=N t:queens=N t:anti_discrimination_human_rights=N t:professional_association=N t:bronx=N t:homelessness=N t:counseling_support_groups=Y t:brooklyn=N m:row_number.pqg4-dm6b=2

series e:pqg4-dm6b d:2011-07-27T07:49:35.000Z t:community_service_volunteerism=N t:none_of_the_above=N t:victim_services=Y t:phone=7186461444 t:disabilities=Y t:child_care_parent_information=Y t:arts_culture=Y t:education=Y t:lesbian_gay_bisexual_and_or_transgender=N t:business=N t:veterans_military_families=N t:domestic_violence=N t:employment_job_training=Y t:description="Community center and settlement house serving south Brooklyn with programming and services for people of all ages.  Specialty is serving Russian speaking immigrants and their families." t:immigration=Y t:legal_services=N t:foundation=N t:nonprofit=Y t:published=Published t:aging=Y t:organizationname="Shorefront YM-YWHA" t:staten_island=N t:fax=7186460376 t:is_registered_with_the_attorney_general_s_office=N t:housing=N t:manhattan=N t:nourl=N t:health=Y t:youth_services=N t:other_government_organization=N t:url=http://shorefronty.org t:personal_finance_financial_education=N t:faith_based_organization=N t:outsideloc=N t:new_york_city_agency=N t:queens=N t:anti_discrimination_human_rights=N t:professional_association=N t:bronx=N t:homelessness=N t:counseling_support_groups=Y t:brooklyn=Y m:row_number.pqg4-dm6b=3
```

## Meta Commands

```ls
metric m:row_number.pqg4-dm6b p:long l:"Row Number"

entity e:pqg4-dm6b l:"NYC Women's Resource Network Database" t:attribution="Commission on Women's Issues (CWI)" t:url=https://data.cityofnewyork.us/api/views/pqg4-dm6b

property e:pqg4-dm6b t:meta.view v:id=pqg4-dm6b v:category="Social Services" v:averageRating=0 v:name="NYC Women's Resource Network Database" v:attribution="Commission on Women's Issues (CWI)"

property e:pqg4-dm6b t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:displayName="NYC OpenData"

property e:pqg4-dm6b t:meta.view.tableauthor v:id=txun-eb7e v:screenName="Albert Webber" v:roleName=administrator v:displayName="Albert Webber"
```