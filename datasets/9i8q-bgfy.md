# Top 50 Employers - Maui County

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/top-50-employers-maui-county-0ff63) |
| Metadata | [Link](https://data.hawaii.gov/api/views/9i8q-bgfy) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/9i8q-bgfy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/9i8q-bgfy/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | 9i8q-bgfy |
| Name | Top 50 Employers - Maui County |
| Attribution | Infogroup?, Omaha, NE, 800/555-5211. Copyright ? 2016 Edition 2. All Rights Reserved. |
| Category | Employment |
| Tags | employer, business, company |
| Created | 2012-12-11T00:36:13Z |
| Publication Date | 2016-07-29T21:31:30Z |

## Description

Largest employers in Maui County as provided by InfoGroup.

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
| Yes      | numeric metric | release                  | Release                  | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:9i8q-bgfy d:2016-07-29T14:30:11.000Z t:fax_number=8082435354 t:business_description="Real Estate" t:contact_first_name=Marcus t:web_url=http://TOWNEHAWAII.COM t:private_govt=Private t:contact_gender=M t:contact_title="Vice President" t:emp_size=1,000-4,999 t:business_location_status="Branch office" t:name="Towne Realty of Hawaii" t:contact_last_name=Ohlheiser t:census_tract=30901 t:telephone=8082435354 m:rank=1 m:last_update=201410 m:census_block_grp=2 m:yr_estab=2004 m:naics_primary=53121000 m:annual_sales=348758000 m:release=162

series e:9i8q-bgfy d:2016-07-29T14:30:11.000Z t:fax_number=8088742411 t:contact_email=NANCIE.BROWN@GRANDWAILEA.COM t:business_description=Resorts t:contact_first_name=Suzy t:private_govt=Private t:toll_free_phone=8008886100 t:contact_gender=F t:contact_title="Hr Executive" t:emp_size=1,000-4,999 t:business_location_status="Branch office" t:name="Grand Wailea-Waldorf Astoria" t:contact_last_name=Desousa t:census_tract=30303 t:telephone=8088751234 m:rank=2 m:last_update=201402 m:census_block_grp=2 m:yr_estab=1991 m:naics_primary=72119900 m:annual_sales=216360000 m:release=162

series e:9i8q-bgfy d:2016-07-29T14:30:11.000Z t:fax_number=8086691566 t:contact_email=MICHAEL.MAASTERSON@RITZCARLTON.COM t:business_description="Hotels & Motels" t:contact_first_name=Chris t:web_url=http://RITZCARLTON.COM t:private_govt=Private t:toll_free_phone=8002413333 t:contact_gender=M t:contact_title="Hr Executive" t:emp_size=1,000-4,999 t:business_location_status="Single location firm" t:name=Ritz-Carlton-Kapalua t:contact_last_name=Ramos t:census_tract=31501 t:telephone=8086696200 m:rank=3 m:last_update=201507 m:census_block_grp=2 m:yr_estab=1992 m:naics_primary=72111000 m:annual_sales=154543000 m:release=162
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

entity e:9i8q-bgfy l:"Top 50 Employers - Maui County" t:attribution="Infogroup?, Omaha, NE, 800/555-5211. Copyright ? 2016 Edition 2. All Rights Reserved." t:url=https://data.hawaii.gov/api/views/9i8q-bgfy

property e:9i8q-bgfy t:meta.view v:id=9i8q-bgfy v:category=Employment v:averageRating=0 v:name="Top 50 Employers - Maui County" v:attribution="Infogroup?, Omaha, NE, 800/555-5211. Copyright ? 2016 Edition 2. All Rights Reserved."

property e:9i8q-bgfy t:meta.view.owner v:id=5ibs-8u6a v:profileImageUrlMedium=/api/users/5ibs-8u6a/profile_images/THUMB v:profileImageUrlLarge=/api/users/5ibs-8u6a/profile_images/LARGE v:screenName=Bill v:profileImageUrlSmall=/api/users/5ibs-8u6a/profile_images/TINY v:displayName=Bill

property e:9i8q-bgfy t:meta.view.tableauthor v:id=5ibs-8u6a v:profileImageUrlMedium=/api/users/5ibs-8u6a/profile_images/THUMB v:profileImageUrlLarge=/api/users/5ibs-8u6a/profile_images/LARGE v:screenName=Bill v:profileImageUrlSmall=/api/users/5ibs-8u6a/profile_images/TINY v:roleName=editor v:displayName=Bill
```

## Top Records

```ls
| :updated_at | rank | name                           | telephone  | contact_first_name | contact_last_name | contact_title  | contact_gender | contact_email                      | toll_free_phone | fax_number | web_url                                  | census_tract | census_block_grp | business_description        | naics_primary | private_govt | business_location_status | emp_size    | annual_sales | yr_estab | last_update | release | 
| =========== | ==== | ============================== | ========== | ================== | ================= | ============== | ============== | ================================== | =============== | ========== | ======================================== | ============ | ================ | =========================== | ============= | ============ | ======================== | =========== | ============ | ======== | =========== | ======= | 
| 1469802611  | 1    | Towne Realty of Hawaii         | 8082435354 | Marcus             | Ohlheiser         | Vice President | M              |                                    |                 | 8082435354 | [http://TOWNEHAWAII.COM, null]           | 30901        | 2                | Real Estate                 | 53121000      | Private      | Branch office            | 1,000-4,999 | 348758000    | 2004     | 201410      | 162     | 
| 1469802611  | 2    | Grand Wailea-Waldorf Astoria   | 8088751234 | Suzy               | Desousa           | Hr Executive   | F              | NANCIE.BROWN@GRANDWAILEA.COM       | 8008886100      | 8088742411 | [null, null]                             | 30303        | 2                | Resorts                     | 72119900      | Private      | Branch office            | 1,000-4,999 | 216360000    | 1991     | 201402      | 162     | 
| 1469802611  | 3    | Ritz-Carlton-Kapalua           | 8086696200 | Chris              | Ramos             | Hr Executive   | M              | MICHAEL.MAASTERSON@RITZCARLTON.COM | 8002413333      | 8086691566 | [http://RITZCARLTON.COM, null]           | 31501        | 2                | Hotels & Motels             | 72111000      | Private      | Single location firm     | 1,000-4,999 | 154543000    | 1992     | 201507      | 162     | 
| 1469802611  | 4    | Four Seasons-Maui              | 8088748000 | Thomas             | Steinhauer        | General Mgr    | M              | THOMAS.STEINHAUER@FOURSEASONS.COM  |                 | 8088746449 | [http://FOURSEASONS.COM, null]           | 30303        | 2                | Hotels & Motels             | 72111000      | Private      | Single location firm     | 500-999     | 123634000    | 1988     | 201506      | 162     | 
| 1469802611  | 5    | Maui Memorial Medical Ctr      | 8082449056 | Lisa               | Knutson           | Hr Executive   | F              | LKNUTSON@HHSC.ORG                  |                 | 8082422443 | [http://MAUIMEMORIALMEDICAL.ORG, null]   | 31000        | 4                | Hospitals                   | 62211000      | Private      | Single location firm     | 500-999     | 125432000    | 2000     | 201507      | 162     | 
| 1469802611  | 6    | Maui Brand Sugar               | 8088772969 | Rick               | Volner Jr         | Manager        | M              |                                    |                 |            | [null, null]                             | 31900        | 1                | Sugar-Brokers & Wholesalers | 42512000      | Private      | Branch office            | 500-999     | 1396943000   | 2008     | 201509      | 162     | 
| 1469802611  | 7    | Four Seasons                   | 8085652092 | Ce Ce              | Moore             | Hr             | M              | ADAM.PARKER@FOURSEASONS.COM        | 8003214666      | 8085652483 | [http://FOURSEASONS.COM, null]           | 31601        | 1                | Hotels & Motels             | 72111000      | Private      | Single location firm     | 500-999     | 108180000    | 1991     | 201508      | 162     | 
| 1469802611  | 8    | Westin Maui Resrt-Spa K'Npl    | 8086672525 | Carol              | Kawabata          | Hr Executive   | F              | CAROL.KAWABATA@WESTIN.COM          | 8009378461      | 8086615764 | [http://STARWOODHOTELS.COM/WESTIN, null] | 31503        | 1                | Hotels & Motels             | 72111000      | Private      | Branch office            | 500-999     | 108180000    | 1971     | 201502      | 162     | 
| 1469802611  | 9    | Fairmont-Kea Lani              | 8088754100 | Colleen            | Chong             | Hr Executive   | F              | JAMES.AVILA@FAIRMONT.COM           | 8006594100      | 8088751200 | [http://FAIRMONT.COM, null]              | 30303        | 2                | Hotels & Motels             | 72111000      | Private      | Single location firm     | 500-999     | 92725000     | 1991     | 201509      | 162     | 
| 1469802611  | 10   | Hyatt Regency-Maui Resrt & Spa | 8086611234 | Jean               | Ewing             | Hr Executive   | F              | KHORNBOSTEL@HYATT.COM              |                 | 8086674498 | [http://REGENCY.HYATT.COM, null]         | 31402        | 1                | Hotels & Motels             | 72111000      | Private      | Branch office            | 500-999     | 92725000     | 1980     | 201403      | 162     | 
```