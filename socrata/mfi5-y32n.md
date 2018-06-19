# Capital Improvement Projects ( CIP) Expenditures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/capital-improvement-projects-cip-expenditures) |
| Metadata | [Link](https://data.austintexas.gov/api/views/mfi5-y32n) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/mfi5-y32n/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/mfi5-y32n/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | mfi5-y32n |
| Name | Capital Improvement Projects ( CIP) Expenditures |
| Attribution | Austin Energy |
| Category | Utility |
| Tags | capital improvement, cip |
| Created | 2016-09-12T19:04:21Z |
| Publication Date | 2016-11-08T19:49:36Z |

## Description

Capital improvement expenditures include upgrades to the Distribution and Transmission system such as new substations and transformers. They also include expenditures to build or upgrade power plants, new or upgraded chillers, new or upgraded facilities, and information technology infrastructure.  All of these expenditures result in assets for the utility that become part of the rate base. Funding for CIP projects includes both current revenue and short-term debt or commercial paper which is eventually rolled into long-term bonds with a life of 30 years.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name                  | Data Type     | Render Type   |
| ======== | ============== | ================== | ===================== | ============= | ============= |
| Yes      | time           | fiscal_year_2      | Fiscal Year           | calendar_date | calendar_date |
| Yes      | numeric metric | non_electric_plant | Non-Electric Plant    | money         | money         |
| Yes      | numeric metric | stp                | South Texas Project   | money         | money         |
| Yes      | numeric metric | fpp                | Fayette Power Project | money         | money         |
| Yes      | numeric metric | power_production   | Power Production      | money         | money         |
| Yes      | numeric metric | transmission       | Transmission          | money         | money         |
| Yes      | numeric metric | distribution       | Distribution          | money         | money         |
| Yes      | numeric metric | metering           | Metering              | money         | money         |
| Yes      | numeric metric | support_services   | Support Services      | money         | money         |
| Yes      | numeric metric | equipment          | Equipment             | money         | money         |
| Yes      | numeric metric | other              | Other                 | money         | money         |
| Yes      | numeric metric | total              | Total                 | money         | money         |
```

## Time Field

```ls
Value = fiscal_year_2
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:mfi5-y32n d:2007-11-01T00:00:00.000Z m:total=189224097

series e:mfi5-y32n d:2008-11-01T00:00:00.000Z m:total=247874960

series e:mfi5-y32n d:2009-11-01T00:00:00.000Z m:total=254239693 m:other=508974 m:support_services=11494946 m:fpp=70938710 m:equipment=6101967 m:stp=9871794 m:power_production=33911069 m:transmission=17926229 m:distribution=66796229 m:non_electric_plant=14421627 m:metering=22267386
```

## Meta Commands

```ls
metric m:non_electric_plant p:integer l:"Non-Electric Plant" t:dataTypeName=money

metric m:stp p:integer l:"South Texas Project" t:dataTypeName=money

metric m:fpp p:integer l:"Fayette Power Project" t:dataTypeName=money

metric m:power_production p:integer l:"Power Production" t:dataTypeName=money

metric m:transmission p:integer l:Transmission t:dataTypeName=money

metric m:distribution p:integer l:Distribution t:dataTypeName=money

metric m:metering p:integer l:Metering t:dataTypeName=money

metric m:support_services p:integer l:"Support Services" t:dataTypeName=money

metric m:equipment p:integer l:Equipment t:dataTypeName=money

metric m:other p:integer l:Other t:dataTypeName=money

metric m:total p:integer l:Total t:dataTypeName=money

entity e:mfi5-y32n l:"Capital Improvement Projects ( CIP) Expenditures" t:attribution="Austin Energy" t:url=https://data.austintexas.gov/api/views/mfi5-y32n

property e:mfi5-y32n t:meta.view v:id=mfi5-y32n v:category=Utility v:averageRating=0 v:name="Capital Improvement Projects ( CIP) Expenditures" v:attribution="Austin Energy"

property e:mfi5-y32n t:meta.view.license v:name="Public Domain"

property e:mfi5-y32n t:meta.view.owner v:id=c433-zrb5 v:profileImageUrlMedium=/api/users/c433-zrb5/profile_images/THUMB v:profileImageUrlLarge=/api/users/c433-zrb5/profile_images/LARGE v:screenName="Sarah Lambert" v:profileImageUrlSmall=/api/users/c433-zrb5/profile_images/TINY v:displayName="Sarah Lambert"

property e:mfi5-y32n t:meta.view.tableauthor v:id=c433-zrb5 v:profileImageUrlMedium=/api/users/c433-zrb5/profile_images/THUMB v:profileImageUrlLarge=/api/users/c433-zrb5/profile_images/LARGE v:screenName="Sarah Lambert" v:profileImageUrlSmall=/api/users/c433-zrb5/profile_images/TINY v:roleName=publisher v:displayName="Sarah Lambert"
```

## Top Records

```ls
| fiscal_year_2       | non_electric_plant | stp      | fpp      | power_production | transmission | distribution | metering | support_services | equipment | other   | total     | 
| =================== | ================== | ======== | ======== | ================ | ============ | ============ | ======== | ================ | ========= | ======= | ========= | 
| 2007-11-01T00:00:00 |                    |          |          |                  |              |              |          |                  |           |         | 189224097 | 
| 2008-11-01T00:00:00 |                    |          |          |                  |              |              |          |                  |           |         | 247874960 | 
| 2009-11-01T00:00:00 | 14421627           | 9871794  | 70938710 | 33911069         | 17926229     | 66796229     | 22267386 | 11494946         | 6101967   | 508974  | 254239693 | 
| 2010-11-01T00:00:00 | 11299468           | 7214737  | 55125849 | 14807699         | 14551030     | 57901091     | 18282513 | 17341095         | 3788283   | 1300065 | 201611828 | 
| 2011-11-01T00:00:00 | 6470132            | 1577299  | 22545042 | 5850470          | 18170943     | 60766240     | 14035277 | 12730851         | 2045718   | 1868097 | 146060069 | 
| 2012-11-01T00:00:00 | 3588709            | 376461   | 9965063  | 2484229          | 15878301     | 62636482     | 5115572  | 59293811         | 1948422   | 4568905 | 165855955 | 
| 2013-11-01T00:00:00 | 11085602           | 11561993 | 3911416  | 2066102          | 32336167     | 73948429     | 2338111  | 14745222         | 985022    | 2444363 | 155422426 | 
| 2014-11-01T00:00:00 | 22909580           | 15329498 | 4234504  | 3227479          | 19229689     | 86420188     | 128870   | 13542254         | 1341925   | 418565  | 166782552 | 
| 2015-11-01T00:00:00 | 9442080            | 17608443 | 2914105  | 4467123          | 27002412     | 88642572     | 254465   | 19859880         | 1015457   | 65649   | 171272186 | 
```