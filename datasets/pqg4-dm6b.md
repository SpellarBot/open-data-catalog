# NYC Women's Resource Network Database

## Dataset

* [Dataset URL](https://data.cityofnewyork.us/api/views/pqg4-dm6b/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/nyc-womens-resource-network-database-b167e)
* [Metadata URL](https://data.cityofnewyork.us/api/views/pqg4-dm6b)
* Id = pqg4-dm6b
* Name = NYC Women's Resource Network Database
* Attribution = Commission on Women's Issues (CWI)
* Category = Social Services
* Tags = [jobs and economic mobility, women, woman, family, families, resource, network]
* Created = 2011-07-27T14:49:32Z
* Publication Date = 2011-10-08T21:59:56Z
* Rows Updated = 2011-10-08T21:59:32Z

## Description

The NYC Women's Resource Network is a free, user-friendly database of over 1,000 nonprofit organizations and governmental agencies that work to advance and benefit women and families in New York City.  A user can tailor their search by keyword, category, and/or borough to receive a customized listing of organizations that address their needs.

## Columns

```ls
| Name                                             | Field Name                                       | Data Type | Render Type | Schema Type    | Included | 
| ================================================ | ================================================ | ========= | =========== | ============== | ======== | 
| updated_at                                       | :updated_at                                      | meta_data | meta_data   | time           | No       | 
| OrganizationName                                 | organizationname                                 | text      | text        | series tag     | Yes      | 
| Brooklyn                                         | brooklyn                                         | number    | text        | numeric metric | Yes      | 
| Bronx                                            | bronx                                            | number    | text        | numeric metric | Yes      | 
| Manhattan                                        | manhattan                                        | number    | text        | numeric metric | Yes      | 
| Queens                                           | queens                                           | number    | text        | numeric metric | Yes      | 
| Staten Island                                    | staten_island                                    | number    | text        | numeric metric | Yes      | 
| Fax                                              | fax                                              | number    | number      | numeric metric | Yes      | 
| Phone                                            | phone                                            | number    | number      | numeric metric | Yes      | 
| URL                                              | url                                              | text      | text        | series tag     | Yes      | 
| noURL                                            | nourl                                            | number    | text        | numeric metric | Yes      | 
| Description                                      | description                                      | text      | text        | series tag     | Yes      | 
| outsideLoc                                       | outsideloc                                       | text      | text        | series tag     | Yes      | 
| outsideLocDesc                                   | outsidelocdesc                                   | text      | text        | series tag     | Yes      | 
| Aging                                            | aging                                            | number    | text        | numeric metric | Yes      | 
| Anti-Discrimination & Human Rights               | anti_discrimination_human_rights                 | number    | text        | numeric metric | Yes      | 
| Arts & Culture                                   | arts_culture                                     | number    | text        | numeric metric | Yes      | 
| Business                                         | business                                         | number    | text        | numeric metric | Yes      | 
| Child Care & Parent Information                  | child_care_parent_information                    | number    | text        | numeric metric | Yes      | 
| Community Service & Volunteerism                 | community_service_volunteerism                   | number    | text        | numeric metric | Yes      | 
| Counseling & Support Groups                      | counseling_support_groups                        | number    | text        | numeric metric | Yes      | 
| Disabilities                                     | disabilities                                     | number    | text        | numeric metric | Yes      | 
| Domestic Violence                                | domestic_violence                                | number    | text        | numeric metric | Yes      | 
| Education                                        | education                                        | number    | text        | numeric metric | Yes      | 
| Employment & Job Training                        | employment_job_training                          | number    | text        | numeric metric | Yes      | 
| Health                                           | health                                           | number    | text        | numeric metric | Yes      | 
| Homelessness                                     | homelessness                                     | number    | text        | numeric metric | Yes      | 
| Housing                                          | housing                                          | number    | text        | numeric metric | Yes      | 
| Immigration                                      | immigration                                      | number    | text        | numeric metric | Yes      | 
| Legal Services                                   | legal_services                                   | number    | text        | numeric metric | Yes      | 
| Lesbian, Gay, Bisexual, and/or Transgender       | lesbian_gay_bisexual_and_or_transgender          | number    | text        | numeric metric | Yes      | 
| Personal Finance & Financial Education           | personal_finance_financial_education             | number    | text        | numeric metric | Yes      | 
| Professional Association                         | professional_association                         | number    | text        | numeric metric | Yes      | 
| Veterans & Military Families                     | veterans_military_families                       | number    | text        | numeric metric | Yes      | 
| Victim Services                                  | victim_services                                  | number    | text        | numeric metric | Yes      | 
| Women's Groups                                   | women_s_groups                                   | text      | text        | series tag     | Yes      | 
| Youth Services                                   | youth_services                                   | number    | text        | numeric metric | Yes      | 
| Faith-based organization                         | faith_based_organization                         | number    | text        | numeric metric | Yes      | 
| Foundation                                       | foundation                                       | number    | text        | numeric metric | Yes      | 
| Is registered with the Attorney General's office | is_registered_with_the_attorney_general_s_office | number    | text        | numeric metric | Yes      | 
| New York City Agency                             | new_york_city_agency                             | number    | text        | numeric metric | Yes      | 
| None of the above                                | none_of_the_above                                | number    | text        | numeric metric | Yes      | 
| Nonprofit                                        | nonprofit                                        | number    | text        | numeric metric | Yes      | 
| Comments                                         | comments                                         | text      | text        | series tag     | Yes      | 
| Other government organization                    | other_government_organization                    | number    | text        | numeric metric | Yes      | 
| Published                                        | published                                        | text      | text        | series tag     | Yes      | 
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
```

## Data Commands

```ls
series e:pqg4-dm6b d:2011-07-27T07:49:35.000Z t:community_service_volunteerism=N t:none_of_the_above=N t:victim_services=N t:disabilities=N t:child_care_parent_information=Y t:arts_culture=N t:education=N t:lesbian_gay_bisexual_and_or_transgender=N t:business=N t:veterans_military_families=N t:domestic_violence=N t:employment_job_training=Y t:description="Established in 1858, the YWCA of the City of New York is one of the nation???s oldest non-profit organizations. Our mission is to address the critical needs of New York City women and to empower them for success and leadership in their lives, jobs and communities. We focus on underserved families through job training, educational child care and after school programs; partnerships with business, government and other not-for-profits; and advocacy on behalf of the clients we serve." t:immigration=N t:legal_services=N t:foundation=N t:nonprofit=Y t:published=Published t:aging=N t:organizationname="YWCA of the City of New York" t:staten_island=Y t:housing=N t:is_registered_with_the_attorney_general_s_office=N t:manhattan=Y t:nourl=N t:health=N t:youth_services=Y t:other_government_organization=N t:url=http://www.ywcanyc.org t:personal_finance_financial_education=N t:faith_based_organization=N t:outsideloc=N t:new_york_city_agency=N t:queens=N t:anti_discrimination_human_rights=N t:professional_association=N t:bronx=N t:homelessness=N t:counseling_support_groups=Y t:brooklyn=Y m:phone=2127554500 m:fax=2122236438

series e:pqg4-dm6b d:2011-07-27T07:49:35.000Z t:community_service_volunteerism=N t:none_of_the_above=N t:victim_services=N t:disabilities=N t:child_care_parent_information=N t:arts_culture=N t:education=N t:lesbian_gay_bisexual_and_or_transgender=N t:business=N t:veterans_military_families=N t:domestic_violence=N t:employment_job_training=N t:description="The Women's Health Department is a unique community based health care program serving uninsured women in New York City. The majority of our clients are low income women who are recent immigrants. The Health Center provides a wide array of primary and specialty services, including gynecological care, family planning, pregnancy testing, prenatal and postnatal care, genetic and nutritional counseling, breast-feeding education, screening and education for HIV and STD infections, and screening and education for breast, cervical, ovarian and prostate cancers. The Women's Health Department also sponsors many outreach and health education programs to promote and increase the community's awareness of women's health issues." t:immigration=N t:legal_services=N t:foundation=N t:nonprofit=Y t:published=Published t:aging=N t:organizationname="Charles B. Wang Community Health Center" t:staten_island=N t:housing=N t:is_registered_with_the_attorney_general_s_office=N t:manhattan=Y t:nourl=N t:health=Y t:youth_services=N t:other_government_organization=N t:url=http://www.cbwchc.org/hcs/wh/wh.html t:personal_finance_financial_education=N t:faith_based_organization=N t:outsideloc=N t:new_york_city_agency=N t:queens=N t:anti_discrimination_human_rights=N t:professional_association=N t:bronx=N t:homelessness=N t:counseling_support_groups=Y t:brooklyn=N m:phone=2129660228

series e:pqg4-dm6b d:2011-07-27T07:49:35.000Z t:community_service_volunteerism=N t:none_of_the_above=N t:victim_services=Y t:disabilities=Y t:child_care_parent_information=Y t:arts_culture=Y t:education=Y t:lesbian_gay_bisexual_and_or_transgender=N t:business=N t:veterans_military_families=N t:domestic_violence=N t:employment_job_training=Y t:description="Community center and settlement house serving south Brooklyn with programming and services for people of all ages.  Specialty is serving Russian speaking immigrants and their families." t:immigration=Y t:legal_services=N t:foundation=N t:nonprofit=Y t:published=Published t:aging=Y t:organizationname="Shorefront YM-YWHA" t:staten_island=N t:housing=N t:is_registered_with_the_attorney_general_s_office=N t:manhattan=N t:nourl=N t:health=Y t:youth_services=N t:other_government_organization=N t:url=http://shorefronty.org t:personal_finance_financial_education=N t:faith_based_organization=N t:outsideloc=N t:new_york_city_agency=N t:queens=N t:anti_discrimination_human_rights=N t:professional_association=N t:bronx=N t:homelessness=N t:counseling_support_groups=Y t:brooklyn=Y m:phone=7186461444 m:fax=7186460376
```

## Meta Commands

```ls
metric m:fax p:long l:Fax t:dataTypeName=number

metric m:phone p:long l:Phone t:dataTypeName=number

entity e:pqg4-dm6b l:"NYC Women's Resource Network Database" t:attribution="Commission on Women's Issues (CWI)" t:url=https://data.cityofnewyork.us/api/views/pqg4-dm6b

property e:pqg4-dm6b t:meta.view d:2017-03-07T23:50:11.975Z v:id=pqg4-dm6b v:category="Social Services" v:averageRating=0 v:name="NYC Women's Resource Network Database" v:attribution="Commission on Women's Issues (CWI)"

property e:pqg4-dm6b t:meta.view.owner d:2017-03-07T23:50:11.975Z v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"

property e:pqg4-dm6b t:meta.view.tableauthor d:2017-03-07T23:50:11.975Z v:id=txun-eb7e v:screenName="Albert Webber" v:roleName=administrator v:displayName="Albert Webber"
```