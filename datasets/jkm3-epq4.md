# Top 50 Employers - Honolulu County

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/top-50-employers-honolulu-county-fa193) |
| Metadata | [Link](https://data.hawaii.gov/api/views/jkm3-epq4) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/jkm3-epq4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/jkm3-epq4/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | jkm3-epq4 |
| Name | Top 50 Employers - Honolulu County |
| Attribution | Infogroup?, Omaha, NE, 800/555-5211. Copyright ? 2016 Edition 2. All Rights Reserved. |
| Category | Employment |
| Tags | employer, business, company |
| Created | 2012-12-10T20:58:12Z |
| Publication Date | 2016-07-29T21:18:11Z |

## Description

Largest employers in Honolulu County as provided by InfoGroup.

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type | Render Type |
| ======== | ============== | ======================== | ======================== | ========= | =========== |
| No       | time           | :updated_at              | updated_at               | meta_data | meta_data   |
| Yes      | numeric metric | rank                     | Rank                     | number    | number      |
| Yes      | series tag     | name                     | Name                     | text      | text        |
| Yes      | series tag     | telephone                | Telephone                | text      | number      |
| Yes      | series tag     | contact_first_name       | Contact First Name       | text      | text        |
| Yes      | series tag     | contact_last_name        | Contact Last Name        | text      | text        |
| Yes      | series tag     | contact_title            | Contact Title            | text      | text        |
| Yes      | series tag     | contact_gender           | Contact Gender           | text      | text        |
| Yes      | series tag     | contact_email            | Contact Email            | email     | email       |
| Yes      | series tag     | toll_free_phone          | Toll-Free Phone          | text      | number      |
| Yes      | series tag     | fax_number               | Fax Number               | text      | number      |
| Yes      | series tag     | web_url                  | Web Url                  | url       | url         |
| Yes      | series tag     | census_tract             | Census Tract             | text      | text        |
| Yes      | numeric metric | census_block_grp         | Census Block Grp         | number    | text        |
| Yes      | series tag     | business_description     | Business Description     | text      | text        |
| Yes      | numeric metric | naics_primary            | NAICS-Primary            | number    | text        |
| Yes      | series tag     | private_govt             | Private-Govt             | text      | text        |
| Yes      | series tag     | business_location_status | Business Location Status | text      | text        |
| Yes      | series tag     | emp_size                 | Emp Size                 | text      | text        |
| Yes      | numeric metric | annual_sales             | Annual Sales             | money     | money       |
| Yes      | numeric metric | yr_estab                 | Yr. Estab                | number    | text        |
| Yes      | numeric metric | last_update              | Last Update              | number    | text        |
| Yes      | numeric metric | release                  | Release                  | number    | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:jkm3-epq4 d:2016-07-29T14:16:55.000Z t:fax_number=8085918420 t:contact_email=KERRY.KOPP@ALTRES.COM t:business_description="Personnel Consultants" t:contact_first_name=Kerry t:web_url=http://HAWAIIANEMPLOYER.NET t:private_govt=Private t:toll_free_phone=8888681600 t:contact_gender=F t:contact_title=President t:emp_size=10,000+ t:business_location_status="Single location firm" t:name=Altres t:contact_last_name=Kopp t:census_tract=3700 t:telephone=8085914940 m:rank=1 m:last_update=201407 m:census_block_grp=2 m:yr_estab=1969 m:naics_primary=54161200 m:annual_sales=1936827000 m:release=162

series e:jkm3-epq4 d:2016-07-29T14:16:55.000Z t:fax_number=8089836086 t:business_description=Hospitals t:contact_first_name=Gail t:web_url=http://HAWAIIPACIFICHEALTH.ORG t:private_govt=Private t:toll_free_phone=8008508916 t:contact_gender=F t:contact_title="Hr Executive" t:emp_size=5,000-9,999 t:business_location_status="Single location firm" t:name="Kapiolani Medical Ctr" t:contact_last_name=Lerch t:census_tract=3502 t:telephone=8089838641 m:rank=2 m:last_update=201511 m:census_block_grp=1 m:yr_estab=1921 m:naics_primary=62211000 m:annual_sales=783951000 m:release=162

series e:jkm3-epq4 d:2016-07-29T14:16:55.000Z t:fax_number=8085855095 t:contact_email=CBLACK@QUEENS.ORG t:business_description=Hospitals t:contact_first_name=Richard t:web_url=http://QUEENSMEDICALCENTER.ORG t:private_govt=Private t:toll_free_phone=8003425901 t:contact_gender=M t:contact_title="Hr Executive" t:emp_size=1,000-4,999 t:business_location_status="Subsidiary headquarters" t:name="Queen's Medical Ctr" t:contact_last_name=Lau t:census_tract=4100 t:telephone=8086911000 m:rank=3 m:last_update=201509 m:census_block_grp=2 m:yr_estab=1984 m:naics_primary=62211000 m:release=162
```

## Meta Commands

```ls
metric m:rank p:integer l:Rank t:dataTypeName=number

metric m:census_block_grp p:integer l:"Census Block Grp" t:dataTypeName=number

metric m:naics_primary p:integer l:NAICS-Primary t:dataTypeName=number

metric m:annual_sales p:integer l:"Annual Sales" t:dataTypeName=money

metric m:yr_estab p:integer l:"Yr. Estab" t:dataTypeName=number

metric m:last_update p:integer l:"Last Update" t:dataTypeName=number

metric m:release p:integer l:Release t:dataTypeName=number

entity e:jkm3-epq4 l:"Top 50 Employers - Honolulu County" t:attribution="Infogroup?, Omaha, NE, 800/555-5211. Copyright ? 2016 Edition 2. All Rights Reserved." t:url=https://data.hawaii.gov/api/views/jkm3-epq4

property e:jkm3-epq4 t:meta.view v:id=jkm3-epq4 v:category=Employment v:averageRating=0 v:name="Top 50 Employers - Honolulu County" v:attribution="Infogroup?, Omaha, NE, 800/555-5211. Copyright ? 2016 Edition 2. All Rights Reserved."

property e:jkm3-epq4 t:meta.view.owner v:id=5ibs-8u6a v:profileImageUrlMedium=/api/users/5ibs-8u6a/profile_images/THUMB v:profileImageUrlLarge=/api/users/5ibs-8u6a/profile_images/LARGE v:screenName=Bill v:profileImageUrlSmall=/api/users/5ibs-8u6a/profile_images/TINY v:displayName=Bill

property e:jkm3-epq4 t:meta.view.tableauthor v:id=5ibs-8u6a v:profileImageUrlMedium=/api/users/5ibs-8u6a/profile_images/THUMB v:profileImageUrlLarge=/api/users/5ibs-8u6a/profile_images/LARGE v:screenName=Bill v:profileImageUrlSmall=/api/users/5ibs-8u6a/profile_images/TINY v:roleName=editor v:displayName=Bill
```

## Top Records

```ls
| :updated_at | rank | name                         | telephone  | contact_first_name | contact_last_name | contact_title | contact_gender | contact_email             | toll_free_phone | fax_number | web_url                                | census_tract | census_block_grp | business_description     | naics_primary | private_govt | business_location_status | emp_size    | annual_sales | yr_estab | last_update | release | 
| =========== | ==== | ============================ | ========== | ================== | ================= | ============= | ============== | ========================= | =============== | ========== | ====================================== | ============ | ================ | ======================== | ============= | ============ | ======================== | =========== | ============ | ======== | =========== | ======= | 
| 1469801815  | 1    | Altres                       | 8085914940 | Kerry              | Kopp              | President     | F              | KERRY.KOPP@ALTRES.COM     | 8888681600      | 8085918420 | [http://HAWAIIANEMPLOYER.NET, null]    | 3700         | 2                | Personnel Consultants    | 54161200      | Private      | Single location firm     | 10,000+     | 1936827000   | 1969     | 201407      | 162     | 
| 1469801815  | 2    | Kapiolani Medical Ctr        | 8089838641 | Gail               | Lerch             | Hr Executive  | F              |                           | 8008508916      | 8089836086 | [http://HAWAIIPACIFICHEALTH.ORG, null] | 3502         | 1                | Hospitals                | 62211000      | Private      | Single location firm     | 5,000-9,999 | 783951000    | 1921     | 201511      | 162     | 
| 1469801815  | 3    | Queen's Medical Ctr          | 8086911000 | Richard            | Lau               | Hr Executive  | M              | CBLACK@QUEENS.ORG         | 8003425901      | 8085855095 | [http://QUEENSMEDICALCENTER.ORG, null] | 4100         | 2                | Hospitals                | 62211000      | Private      | Subsidiary headquarters  | 1,000-4,999 |              | 1984     | 201509      | 162     | 
| 1469801815  | 4    | Hawaii Health Systems Corp   | 8087334020 | Janice             | Wakatsuki         | Hr Executive  | F              | VLEE@HHSC.ORG             |                 | 8087334028 | [http://KULAHOSPITAL.ORG, null]        | 800          | 4                | Government Offices-State | 92112000      | State        | Single location firm     | 1,000-4,999 |              | 1996     | 201504      | 162     | 
| 1469801815  | 5    | Hawaii State-Police Dept     | 8085293111 | Louis              | Kealoha           | Manager       | M              | LKEALOHA@HONOLULU.GOV     |                 |            | [http://HAWAII.GOV, null]              | 4100         | 2                | Government Offices-State | 92112000      | State        | Single location firm     | 1,000-4,999 |              | 2013     | 201512      | 162     | 
| 1469801815  | 6    | Tripler Army Medical Ctr     | 8084336661 | Paul               | Wingo             | Hr Executive  | M              |                           |                 | 8084331554 | [http://TAMC.AMEDD.ARMY.MIL, null]     | 6701         | 3                | Medical Centers          | 62211000      | Federal      | Branch office            | 1,000-4,999 |              | 1989     | 201506      | 162     | 
| 1469801815  | 7    | Bank of Hawaii               | 8085384171 | Mary E             | Sellers           | Hr            | F              | ROWELL.COMIA@BOH.COM      | 8004516022      | 8082332053 | [http://BOH.COM, null]                 | 4000         | 2                | Banks                    | 52211000      | Private      | Subsidiary headquarters  | 1,000-4,999 |              | 1897     | 201502      | 162     | 
| 1469801815  | 8    | Bank of Hawaii Corp          | 8086948000 | Therese M          | Dickerson         | Hr Executive  | F              | VWRIGHT@BOH.COM           |                 | 8085369433 | [http://BOH.COM, null]                 | 4000         | 2                | Holding Companies (bank) | 55111100      | Private      | Headquarters/home office | 1,000-4,999 |              | 1971     | 199209      | 162     | 
| 1469801815  | 9    | St Francis Healthcare System | 8085340777 | Sue                | Bias              | Hr Executive  | F              | JDICE@STFRANCISHAWAII.ORG |                 | 8086761300 | [http://STFRANCISHAWAII.ORG, null]     | 8614         | 9                | Home Health Service      | 62161000      | Private      | Single location firm     | 1,000-4,999 | 174442000    | 1927     | 201410      | 162     | 
| 1469801815  | 10   | Aloha Air Cargo              | 8088364191 | Jan                | Iga               | Hr Executive  | F              | JKILIN@ALOHAAIRCARGO.COM  |                 |            | [http://ALOHAAIRCARGO.COM, null]       | 980200       | 1                | Air Cargo Service        | 48111200      | Private      | Subsidiary headquarters  | 1,000-4,999 |              | 1946     | 201602      | 162     | 
```