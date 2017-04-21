# WEBS Vendors by commodity code and MWBE/V/Small status

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/webs-vendors-by-commodity-code-and-mwbe-v-small-status) |
| Metadata | [Link](https://data.wa.gov/api/views/3kwi-7zsj) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/3kwi-7zsj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/3kwi-7zsj/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | 3kwi-7zsj |
| Name | WEBS Vendors by commodity code and MWBE/V/Small status |
| Category | Procurements and Contracts |
| Tags | webs, vendors, commodity, omwbe, small, vet status |
| Created | 2016-05-20T22:26:38Z |
| Publication Date | 2017-02-06T23:20:10Z |

## Description

Active WEBS vendors who have chosen to share their information for potential partnering opportunities. Includes contact information, city, state and MWBE, vet, small status

## Columns

```ls
| Included | Schema Type | Field Name          | Name                | Data Type | Render Type |
| ======== | =========== | =================== | =================== | ========= | =========== |
| No       | time        | :updated_at         | updated_at          | meta_data | meta_data   |
| Yes      | series tag  | company_name        | Company Name        | text      | text        |
| Yes      | series tag  | dba_name            | DBA Name            | text      | text        |
| Yes      | series tag  | phone_number        | Phone Number        | text      | text        |
| Yes      | series tag  | contact_email       | Contact Email       | text      | text        |
| Yes      | series tag  | city                | City                | text      | text        |
| Yes      | series tag  | state               | State               | text      | text        |
| Yes      | series tag  | web_address         | Web Address         | text      | text        |
| Yes      | series tag  | code                | Code                | text      | text        |
| Yes      | series tag  | description_of_work | Description Of Work | text      | text        |
| Yes      | series tag  | omwbe               | OMWBE               | text      | text        |
| Yes      | series tag  | small_business      | Small Business      | text      | text        |
| Yes      | series tag  | veteran_owned       | Veteran Owned       | text      | text        |
| Yes      | series tag  | other_cert          | Other Cert          | text      | text        |
| Yes      | series tag  | other_cert_2        | Other Cert 2        | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:3kwi-7zsj d:2017-02-06T23:18:40.000Z t:description_of_work="Programming Services, Computer" t:phone_number="(916) 932-2910" t:web_address=www.sunrisetechnologies.com t:veteran_owned=N t:contact_email=kdavis@sunrisetechnologies.com t:company_name="Sunrise Technologies, Inc." t:small_business=Y t:state=CA t:code=920-40 t:dba_name="Sunrise Integrated Solutions" t:other_cert_2=CALTRANS t:other_cert=DBE t:city=Folsom m:row_number.3kwi-7zsj=1

series e:3kwi-7zsj d:2017-02-06T23:18:40.000Z t:description_of_work="Geotechnical - Soils" t:phone_number="(253) 475-7711" t:web_address=www.robinson-noble.com t:veteran_owned=N t:contact_email=jbecker@robinson-noble.com t:company_name="Robinson Noble, Inc." t:small_business=Y t:state=WA t:code=907-42 t:dba_name="Robinson Noble,  Inc." t:other_cert_2="WA St Engineer Corp" t:other_cert="King County SCS" t:city=Tacoma m:row_number.3kwi-7zsj=2

series e:3kwi-7zsj d:2017-02-06T23:18:40.000Z t:description_of_work="Site Assessment and Site Field Observation" t:phone_number="(253) 475-7711" t:web_address=www.robinson-noble.com t:veteran_owned=N t:contact_email=jbecker@robinson-noble.com t:company_name="Robinson Noble, Inc." t:small_business=Y t:state=WA t:code=907-75 t:dba_name="Robinson Noble,  Inc." t:other_cert_2="WA St Engineer Corp" t:other_cert="King County SCS" t:city=Tacoma m:row_number.3kwi-7zsj=3
```

## Meta Commands

```ls
metric m:row_number.3kwi-7zsj p:long l:"Row Number"

entity e:3kwi-7zsj l:"WEBS Vendors by commodity code and MWBE/V/Small status" t:url=https://data.wa.gov/api/views/3kwi-7zsj

property e:3kwi-7zsj t:meta.view v:id=3kwi-7zsj v:category="Procurements and Contracts" v:averageRating=0 v:name="WEBS Vendors by commodity code and MWBE/V/Small status"

property e:3kwi-7zsj t:meta.view.owner v:id=vrr3-nct2 v:profileImageUrlMedium=/api/users/vrr3-nct2/profile_images/THUMB v:profileImageUrlLarge=/api/users/vrr3-nct2/profile_images/LARGE v:screenName="DES-Rebecca Linville" v:profileImageUrlSmall=/api/users/vrr3-nct2/profile_images/TINY v:displayName="DES-Rebecca Linville"

property e:3kwi-7zsj t:meta.view.tableauthor v:id=vrr3-nct2 v:profileImageUrlMedium=/api/users/vrr3-nct2/profile_images/THUMB v:profileImageUrlLarge=/api/users/vrr3-nct2/profile_images/LARGE v:screenName="DES-Rebecca Linville" v:profileImageUrlSmall=/api/users/vrr3-nct2/profile_images/TINY v:roleName=publisher v:displayName="DES-Rebecca Linville"
```

## Top Records

```ls
| :updated_at | company_name               | dba_name                     | phone_number   | contact_email                  | city   | state | web_address                 | code   | description_of_work                                                                     | omwbe | small_business | veteran_owned | other_cert      | other_cert_2        | 
| =========== | ========================== | ============================ | ============== | ============================== | ====== | ===== | =========================== | ====== | ======================================================================================= | ===== | ============== | ============= | =============== | =================== | 
| 1486423120  | Sunrise Technologies, Inc. | Sunrise Integrated Solutions | (916) 932-2910 | kdavis@sunrisetechnologies.com | Folsom | CA    | www.sunrisetechnologies.com | 920-40 | Programming Services, Computer                                                          |       | Y              | N             | DBE             | CALTRANS            | 
| 1486423120  | Robinson Noble, Inc.       | Robinson Noble, Inc.         | (253) 475-7711 | jbecker@robinson-noble.com     | Tacoma | WA    | www.robinson-noble.com      | 907-42 | Geotechnical - Soils                                                                    |       | Y              | N             | King County SCS | WA St Engineer Corp | 
| 1486423120  | Robinson Noble, Inc.       | Robinson Noble, Inc.         | (253) 475-7711 | jbecker@robinson-noble.com     | Tacoma | WA    | www.robinson-noble.com      | 907-75 | Site Assessment and Site Field Observation                                              |       | Y              | N             | King County SCS | WA St Engineer Corp | 
| 1486423120  | Robinson Noble, Inc.       | Robinson Noble, Inc.         | (253) 475-7711 | jbecker@robinson-noble.com     | Tacoma | WA    | www.robinson-noble.com      | 918-43 | Environmental Consulting                                                                |       | Y              | N             | King County SCS | WA St Engineer Corp | 
| 1486423120  | Robinson Noble, Inc.       | Robinson Noble, Inc.         | (253) 475-7711 | jbecker@robinson-noble.com     | Tacoma | WA    | www.robinson-noble.com      | 925-46 | Geotechnical Engineering                                                                |       | Y              | N             | King County SCS | WA St Engineer Corp | 
| 1486423120  | Robinson Noble, Inc.       | Robinson Noble, Inc.         | (253) 475-7711 | jbecker@robinson-noble.com     | Tacoma | WA    | www.robinson-noble.com      | 925-97 | Water Supply, Treatment, and Distribution/Engineering                                   |       | Y              | N             | King County SCS | WA St Engineer Corp | 
| 1486423120  | Robinson Noble, Inc.       | Robinson Noble, Inc.         | (253) 475-7711 | jbecker@robinson-noble.com     | Tacoma | WA    | www.robinson-noble.com      | 926-30 | Contaminated Soil Services                                                              |       | Y              | N             | King County SCS | WA St Engineer Corp | 
| 1486423120  | Robinson Noble, Inc.       | Robinson Noble, Inc.         | (253) 475-7711 | jbecker@robinson-noble.com     | Tacoma | WA    | www.robinson-noble.com      | 926-42 | Environmental Services (Not Otherwise Classified)                                       |       | Y              | N             | King County SCS | WA St Engineer Corp | 
| 1486423120  | Robinson Noble, Inc.       | Robinson Noble, Inc.         | (253) 475-7711 | jbecker@robinson-noble.com     | Tacoma | WA    | www.robinson-noble.com      | 926-45 | Hazardous Material and Waste Services (Including Emergency Response and Nuclear Wastes) |       | Y              | N             | King County SCS | WA St Engineer Corp | 
| 1486423120  | Robinson Noble, Inc.       | Robinson Noble, Inc.         | (253) 475-7711 | jbecker@robinson-noble.com     | Tacoma | WA    | www.robinson-noble.com      | 926-54 | Investigation Services, Pollution                                                       |       | Y              | N             | King County SCS | WA St Engineer Corp | 
```