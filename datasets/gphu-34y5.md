# Top 50 Employers - Hawaii County

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/top-50-employers-hawaii-county-ad09f) |
| Metadata | [Link](https://data.hawaii.gov/api/views/gphu-34y5) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/gphu-34y5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/gphu-34y5/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | gphu-34y5 |
| Name | Top 50 Employers - Hawaii County |
| Attribution | Infogroup?, Omaha, NE, 800/555-5211. Copyright ? 2016 Edition 2. All Rights Reserved. |
| Category | Employment |
| Tags | employer, business, company |
| Created | 2012-12-10T20:26:47Z |
| Publication Date | 2016-07-29T20:42:37Z |

## Description

Largest employers in Hawaii County as provided by InfoGroup.

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
| Yes      | series tag     | emp_size_range           | Emp Size Range           | text      | text        |
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
series e:gphu-34y5 d:2016-07-29T13:38:30.000Z t:fax_number=8089744746 t:contact_email=HKAAKIMAKA@HHSC.ORG t:business_description="Diagnostic Imaging Centers" t:contact_first_name=Holly t:private_govt=Private t:emp_size_range=1,000-4,999 t:contact_gender=F t:contact_title="Hr Executive" t:business_location_status="Single Location firm" t:name="Hilo Medical Ctr Radiology" t:contact_last_name=Kaakimaka t:census_tract=20300 t:telephone=8089233800 m:rank=1 m:last_update=201509 m:census_block_grp=1 m:yr_estab=1995 m:naics_primary=62151200 m:annual_sales=202477000 m:release=162

series e:gphu-34y5 d:2016-07-29T13:38:30.000Z t:fax_number=8088862906 t:contact_email=SALES@HILTONWAIKOLOAVILLAGE.COM t:business_description="Hotels & Motels" t:contact_first_name=Evangeline t:web_url=http://HILTON.COM t:private_govt=Private t:emp_size_range=500-999 t:toll_free_phone=8004458667 t:contact_gender=F t:contact_title="Hr Executive" t:business_location_status="Branch office" t:name="Hilton-Waikoloa Village" t:contact_last_name=Sobrepena t:census_tract=21704 t:telephone=8088861234 m:rank=2 m:last_update=201511 m:census_block_grp=1 m:yr_estab=1988 m:naics_primary=72111000 m:annual_sales=139088000 m:release=162

series e:gphu-34y5 d:2016-07-29T13:38:30.000Z t:business_description=Resorts t:business_location_status="Branch office" t:contact_first_name=Debi t:name=Hilton t:private_govt=Private t:web_url=http://MYOWNBS.COM t:emp_size_range=500-999 t:contact_gender=F t:contact_title="General Mgr" t:contact_last_name=Bishop t:census_tract=21704 t:telephone=8088861234 m:rank=3 m:last_update=201511 m:census_block_grp=3 m:yr_estab=2015 m:naics_primary=72119900 m:annual_sales=123634000 m:release=162
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

entity e:gphu-34y5 l:"Top 50 Employers - Hawaii County" t:attribution="Infogroup?, Omaha, NE, 800/555-5211. Copyright ? 2016 Edition 2. All Rights Reserved." t:url=https://data.hawaii.gov/api/views/gphu-34y5

property e:gphu-34y5 t:meta.view v:id=gphu-34y5 v:category=Employment v:averageRating=0 v:name="Top 50 Employers - Hawaii County" v:attribution="Infogroup?, Omaha, NE, 800/555-5211. Copyright ? 2016 Edition 2. All Rights Reserved."

property e:gphu-34y5 t:meta.view.owner v:id=5ibs-8u6a v:profileImageUrlMedium=/api/users/5ibs-8u6a/profile_images/THUMB v:profileImageUrlLarge=/api/users/5ibs-8u6a/profile_images/LARGE v:screenName=Bill v:profileImageUrlSmall=/api/users/5ibs-8u6a/profile_images/TINY v:displayName=Bill

property e:gphu-34y5 t:meta.view.tableauthor v:id=5ibs-8u6a v:profileImageUrlMedium=/api/users/5ibs-8u6a/profile_images/THUMB v:profileImageUrlLarge=/api/users/5ibs-8u6a/profile_images/LARGE v:screenName=Bill v:profileImageUrlSmall=/api/users/5ibs-8u6a/profile_images/TINY v:roleName=editor v:displayName=Bill
```

## Top Records

```ls
| :updated_at | rank | name                           | telephone  | contact_first_name | contact_last_name | contact_title | contact_gender | contact_email                         | toll_free_phone | fax_number | web_url                                | census_tract | census_block_grp | business_description       | naics_primary | private_govt | business_location_status | emp_size_range | annual_sales | yr_estab | last_update | release | 
| =========== | ==== | ============================== | ========== | ================== | ================= | ============= | ============== | ===================================== | =============== | ========== | ====================================== | ============ | ================ | ========================== | ============= | ============ | ======================== | ============== | ============ | ======== | =========== | ======= | 
| 1469799510  | 1    | Hilo Medical Ctr Radiology     | 8089233800 | Holly              | Kaakimaka         | Hr Executive  | F              | HKAAKIMAKA@HHSC.ORG                   |                 | 8089744746 | [null, null]                           | 20300        | 1                | Diagnostic Imaging Centers | 62151200      | Private      | Single Location firm     | 1,000-4,999    | 202477000    | 1995     | 201509      | 162     | 
| 1469799510  | 2    | Hilton-Waikoloa Village        | 8088861234 | Evangeline         | Sobrepena         | Hr Executive  | F              | SALES@HILTONWAIKOLOAVILLAGE.COM       | 8004458667      | 8088862906 | [http://HILTON.COM, null]              | 21704        | 1                | Hotels & Motels            | 72111000      | Private      | Branch office            | 500-999        | 139088000    | 1988     | 201511      | 162     | 
| 1469799510  | 3    | Hilton                         | 8088861234 | Debi               | Bishop            | General Mgr   | F              |                                       |                 |            | [http://MYOWNBS.COM, null]             | 21704        | 3                | Resorts                    | 72119900      | Private      | Branch office            | 500-999        | 123634000    | 2015     | 201511      | 162     | 
| 1469799510  | 4    | Hapuna Beach Prince Hotel      | 8088801111 | Gary               | Rockwood          | Hr Executive  | M              | SMARCELINO@HAPUNABEACHPRINCEHOTEL.COM |                 | 8088803200 | [http://PRINCERESORTSHAWAII.COM, null] | 21704        | 1                | Hotels & Motels            | 72111000      | Private      | Branch office            | 500-999        | 108180000    | 1929     | 201510      | 162     | 
| 1469799510  | 5    | Kona Community Hospital        | 8083229311 | Kathleen           | Soliman           | Hr Executive  | F              | KROKAVEC@HHSC.ORG                     |                 | 8083224488 | [http://KHFHAWAII.ORG, null]           | 21402        | 2                | Hospitals                  | 62211000      | Private      | Single Location firm     | 500-999        | 78395000     | 1984     | 201508      | 162     | 
| 1469799510  | 6    | Mauna Kea Spa By Mandara Mauna | 8088827222 | Jon                | Gersonde          | General Mgr   | M              | JGERSONDE@MAUNAKEARESORT.NET          | 8667746236      | 8088827552 | [http://PRINCERESORTSHAWAII.COM, null] | 21704        | 1                | Spas-Beauty & Day          | 81211200      | Private      | Branch office            | 500-999        | 20047000     | 1929     | 201508      | 162     | 
| 1469799510  | 7    | Hawaii County Police Dept      | 8089353311 | Harry              | Kubojiri          | Manager       | M              | HCPDONE@CO.HAWAII.HI.US               |                 | 8089618869 | [http://HAWAIIPOLICE.ORG, null]        | 20400        | 2                | Government Offices-County  | 92112000      | County       | Single Location firm     | 250-499        |              | 1996     | 201602      | 162     | 
| 1469799510  | 8    | Four Seasons-Hualalai          | 8083258000 | Robert             | Whitfield         | General Mgr   | M              | ROBERT.WHITFIELD@FOURSEASONS.COM      |                 | 8083258200 | [http://FOURSEASONS.COM, null]         | 21507        | 1                | Hotels & Motels            | 72111000      | Private      | Single Location firm     | 250-499        | 72944000     | 1988     | 201502      | 162     | 
| 1469799510  | 9    | North Hawaii Community Hosp    | 8088854444 | John               | White             | CEO           | M              | WHITEJ@NHCH.COM                       |                 | 8088814404 | [http://NHCH.COM, null]                | 21702        | 3                | Hospitals                  | 62211000      | Private      | Headquarters/home office | 250-499        |              | 1999     | 201406      | 162     | 
| 1469799510  | 10   | Walmart                        | 8089619115 | Crystal            | Fernandez         | Hr Executive  | F              |                                       |                 | 8089614436 | [http://WALMART.COM, null]             | 20600        | 4                | Department Stores          | 45211100      | Private      | Branch office            | 250-499        | 98167000     | 1997     | 201507      | 162     | 
```