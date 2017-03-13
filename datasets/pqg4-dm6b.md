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
| Rows Updated | 2011-10-08T21:59:32Z |

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
```

## Meta Commands

```ls
entity e:pqg4-dm6b l:"NYC Women's Resource Network Database" t:attribution="Commission on Women's Issues (CWI)" t:url=https://data.cityofnewyork.us/api/views/pqg4-dm6b

property e:pqg4-dm6b t:meta.view v:id=pqg4-dm6b v:category="Social Services" v:averageRating=0 v:name="NYC Women's Resource Network Database" v:attribution="Commission on Women's Issues (CWI)"

property e:pqg4-dm6b t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"

property e:pqg4-dm6b t:meta.view.tableauthor v:id=txun-eb7e v:screenName="Albert Webber" v:roleName=administrator v:displayName="Albert Webber"
```