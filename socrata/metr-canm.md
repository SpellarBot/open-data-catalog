# Top 50 Employers - Kauai County

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/top-50-employers-kauai-county-a9153) |
| Metadata | [Link](https://data.hawaii.gov/api/views/metr-canm) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/metr-canm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/metr-canm/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | metr-canm |
| Name | Top 50 Employers - Kauai County |
| Attribution | Infogroup?, Omaha, NE, 800/555-5211. Copyright ? 2016 Edition 2. All Rights Reserved. |
| Category | Employment |
| Tags | employer, business, company |
| Created | 2012-12-11T00:22:34Z |
| Publication Date | 2016-07-29T21:25:25Z |

## Description

Largest employers in Kauai County as provided by InfoGroup.

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
series e:metr-canm d:2016-07-29T14:24:16.000Z t:business_description="Construction Companies" t:contact_email=UNLIMITED@UNLIMITEDHAWAII.COM t:business_location_status="Single location firm" t:contact_first_name=Brett t:name="Unlimited Construction" t:private_govt=Private t:contact_gender=M t:contact_title="General Mgr" t:contact_last_name=Schmauch t:census_tract=40400 t:telephone=8082417368 t:emp_size=1,000-4,999 m:rank=1 m:last_update=201511 m:census_block_grp=1 m:yr_estab=1990 m:naics_primary=23611500 m:annual_sales=603467000 m:release=162

series e:metr-canm d:2016-07-29T14:24:16.000Z t:fax_number=8087428691 t:contact_email=DOUG.SEARS@HYATT.COM t:business_description="Signs (mfrs)" t:contact_first_name=Doug t:private_govt=Private t:contact_gender=M t:contact_title="General Mgr" t:emp_size=500-999 t:business_location_status="Single location firm" t:name="Business Center At Grand Hyatt" t:contact_last_name=Sears t:census_tract=40603 t:telephone=8082406328 m:rank=2 m:last_update=201503 m:census_block_grp=2 m:yr_estab=2008 m:naics_primary=33995000 m:annual_sales=247043000 m:release=162

series e:metr-canm d:2016-07-29T14:24:16.000Z t:fax_number=8087421557 t:business_description="Hotels & Motels" t:contact_first_name=Joseph t:web_url=http://HYATT.COM t:private_govt=Private t:toll_free_phone=8007422353 t:contact_gender=M t:contact_title="Hr Executive" t:emp_size=500-999 t:business_location_status="Branch office" t:name="Grand Hyatt-Kauai Resort & Spa" t:contact_last_name=Taitano t:census_tract=40603 t:telephone=8087421234 m:rank=3 m:last_update=201502 m:census_block_grp=2 m:yr_estab=1990 m:naics_primary=72111000 m:annual_sales=139088000 m:release=162
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

entity e:metr-canm l:"Top 50 Employers - Kauai County" t:attribution="Infogroup?, Omaha, NE, 800/555-5211. Copyright ? 2016 Edition 2. All Rights Reserved." t:url=https://data.hawaii.gov/api/views/metr-canm

property e:metr-canm t:meta.view v:id=metr-canm v:category=Employment v:averageRating=0 v:name="Top 50 Employers - Kauai County" v:attribution="Infogroup?, Omaha, NE, 800/555-5211. Copyright ? 2016 Edition 2. All Rights Reserved."

property e:metr-canm t:meta.view.owner v:id=5ibs-8u6a v:profileImageUrlMedium=/api/users/5ibs-8u6a/profile_images/THUMB v:profileImageUrlLarge=/api/users/5ibs-8u6a/profile_images/LARGE v:screenName=Bill v:profileImageUrlSmall=/api/users/5ibs-8u6a/profile_images/TINY v:displayName=Bill

property e:metr-canm t:meta.view.tableauthor v:id=5ibs-8u6a v:profileImageUrlMedium=/api/users/5ibs-8u6a/profile_images/THUMB v:profileImageUrlLarge=/api/users/5ibs-8u6a/profile_images/LARGE v:screenName=Bill v:profileImageUrlSmall=/api/users/5ibs-8u6a/profile_images/TINY v:roleName=editor v:displayName=Bill
```

## Top Records

```ls
| :updated_at | rank | name                           | telephone  | contact_first_name | contact_last_name | contact_title | contact_gender | contact_email                    | toll_free_phone | fax_number | web_url                             | census_tract | census_block_grp | business_description        | naics_primary | private_govt | business_location_status | emp_size    | annual_sales | yr_estab | last_update | release | 
| =========== | ==== | ============================== | ========== | ================== | ================= | ============= | ============== | ================================ | =============== | ========== | =================================== | ============ | ================ | =========================== | ============= | ============ | ======================== | =========== | ============ | ======== | =========== | ======= | 
| 1469802256  | 1    | Unlimited Construction         | 8082417368 | Brett              | Schmauch          | General Mgr   | M              | UNLIMITED@UNLIMITEDHAWAII.COM    |                 |            | [null, null]                        | 40400        | 1                | Construction Companies      | 23611500      | Private      | Single location firm     | 1,000-4,999 | 603467000    | 1990     | 201511      | 162     | 
| 1469802256  | 2    | Business Center At Grand Hyatt | 8082406328 | Doug               | Sears             | General Mgr   | M              | DOUG.SEARS@HYATT.COM             |                 | 8087428691 | [null, null]                        | 40603        | 2                | Signs (mfrs)                | 33995000      | Private      | Single location firm     | 500-999     | 247043000    | 2008     | 201503      | 162     | 
| 1469802256  | 3    | Grand Hyatt-Kauai Resort & Spa | 8087421234 | Joseph             | Taitano           | Hr Executive  | M              |                                  | 8007422353      | 8087421557 | [http://HYATT.COM, null]            | 40603        | 2                | Hotels & Motels             | 72111000      | Private      | Branch office            | 500-999     | 139088000    | 1990     | 201502      | 162     | 
| 1469802256  | 4    | Wilcox Memorial Hospital       | 8082451100 | Dee                | Knudsen           | Hr Executive  | F              | GINNY.PRESSLER@WILCOXHEALTH.ORG  |                 | 8082461625 | [null, null]                        | 40500        | 1                | Hospitals                   | 62211000      | Private      | Single location firm     | 500-999     | 133271000    | 1921     | 201507      | 162     | 
| 1469802256  | 5    | Marriott-Kaua'i Beach Club     | 8082455050 | Chuck              | Bradey            | Hr Executive  | M              | LYNNE.NAGAOKA@MARRIOTTHOTELS.COM | 8008455279      | 8082455049 | [http://MARRIOTT.COM, null]         | 40500        | 1                | Hotels & Motels             | 72111000      | Private      | Branch office            | 500-999     | 92725000     | 1960     | 201503      | 162     | 
| 1469802256  | 6    | Kauai Veterans Memorial Hosp   | 8083389431 | Scott              | Mcfarland         | CEO           | M              | MCFARLAND@HHSC.ORG               |                 |            | [http://KVMH.COM, null]             | 40900        | 2                | Hospitals                   | 62211000      | Private      | Single location firm     | 500-999     | 78395000     | 2012     | 201412      | 162     | 
| 1469802256  | 7    | St Regis-Princeville Resort    | 8088269644 | Deborah            | Baker             | Hr Executive  | F              | CHERYL.ALAPAI@STREGIS.COM        | 8777873447      | 8088261166 | [null, null]                        | 40103        | 4                | Resorts                     | 72119900      | Private      | Branch office            | 250-499     | 55635000     | 1985     | 201505      | 162     | 
| 1469802256  | 8    | Walmart                        | 8082461599 | Valerie            | Grammar           | Hr Executive  | F              |                                  | 8009256278      | 8082461856 | [http://WALMART.COM, null]          | 40500        | 1                | Department Stores           | 45211100      | Private      | Branch office            | 250-499     | 76352000     | 1995     | 201503      | 162     | 
| 1469802256  | 10   | Kauai Medical Clinic           | 8082451523 | Lynne              | Joseph            | CEO           | F              |                                  |                 | 8082461625 | [null, null]                        | 40500        | 1                | Physicians & Surgeons       | 62111100      | Private      | Single location firm     | 250-499     | 57939000     | 1921     | 201410      | 162     | 
| 1469802256  | 11   | Wyndham Vacation Rentals       | 8088227417 | Sandy              | Klute             | General Mgr   | F              |                                  |                 |            | [http://WYNDHAMWORLDWIDE.COM, null] | 40205        | 1                | Vacation Time Sharing Plans | 81299000      | Private      | Branch office            | 250-499     | 16938000     | 2011     | 201503      | 162     | 
```