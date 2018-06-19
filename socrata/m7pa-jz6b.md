# City of Seattle official Twitter accounts statistics

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cos-statistics-twitter) |
| Metadata | [Link](https://data.seattle.gov/api/views/m7pa-jz6b) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/m7pa-jz6b/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/m7pa-jz6b/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | m7pa-jz6b |
| Name | City of Seattle official Twitter accounts statistics |
| Attribution | ITD |
| Category | City Business |
| Tags | twitter, statistics, followers, nre |
| Created | 2017-01-05T23:57:05Z |
| Publication Date | 2017-02-22T23:37:53Z |

## Description

This dataset contains statistics on the usage patterns of the official City of Seattle Twitter accounts, as well their outreach impact. Jun 2016 - Jan 2017

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | account     | account    | text      | text        |
| Yes      | numeric metric | tweets      | tweets     | number    | number      |
| Yes      | numeric metric | following   | following  | number    | number      |
| Yes      | numeric metric | followers   | followers  | number    | number      |
| Yes      | series tag     | month       | month      | text      | text        |
| Yes      | numeric metric | likes       | likes      | number    | number      |
| Yes      | numeric metric | lists       | lists      | number    | number      |
| Yes      | numeric metric | moments     | moments    | number    | number      |
| Yes      | series tag     | dept        | dept       | text      | text        |
| Yes      | series tag     | department  | department | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:m7pa-jz6b d:2017-02-22T23:48:40.000Z t:department="Information Technology Department" t:month=16-Nov t:account=https://twitter.com/seattlecityjobs t:dept=ITD m:following=615 m:followers=1014 m:likes=373 m:tweets=961 m:moments=0 m:lists=0

series e:m7pa-jz6b d:2017-02-22T23:48:40.000Z t:department="Department of Construction and Inspections" t:month=16-Dec t:account=https://twitter.com/seattledci t:dept=DCI m:following=732 m:followers=4629 m:likes=535 m:tweets=3504 m:moments=0 m:lists=17

series e:m7pa-jz6b d:2017-02-22T23:48:40.000Z t:department="Information Technology Department" t:month=16-Dec t:account=https://twitter.com/seattlecityjobs t:dept=ITD m:following=613 m:followers=1025 m:likes=404 m:tweets=961 m:moments=0 m:lists=0
```

## Meta Commands

```ls
metric m:tweets p:integer l:tweets t:dataTypeName=number

metric m:following p:integer l:following t:dataTypeName=number

metric m:followers p:integer l:followers t:dataTypeName=number

metric m:likes p:integer l:likes t:dataTypeName=number

metric m:lists p:integer l:lists t:dataTypeName=number

metric m:moments p:integer l:moments t:dataTypeName=number

entity e:m7pa-jz6b l:"City of Seattle official Twitter accounts statistics" t:attribution=ITD t:url=https://data.seattle.gov/api/views/m7pa-jz6b

property e:m7pa-jz6b t:meta.view v:id=m7pa-jz6b v:category="City Business" v:attributionLink=http://www.seattle.gov/ v:averageRating=0 v:name="City of Seattle official Twitter accounts statistics" v:attribution=ITD

property e:m7pa-jz6b t:meta.view.license v:name="Public Domain"

property e:m7pa-jz6b t:meta.view.owner v:id=seg8-ihrf v:profileImageUrlMedium=/api/users/seg8-ihrf/profile_images/THUMB v:profileImageUrlLarge=/api/users/seg8-ihrf/profile_images/LARGE v:screenName="Eckstine, Nate" v:profileImageUrlSmall=/api/users/seg8-ihrf/profile_images/TINY v:displayName="Eckstine, Nate"

property e:m7pa-jz6b t:meta.view.tableauthor v:id=seg8-ihrf v:profileImageUrlMedium=/api/users/seg8-ihrf/profile_images/THUMB v:profileImageUrlLarge=/api/users/seg8-ihrf/profile_images/LARGE v:screenName="Eckstine, Nate" v:profileImageUrlSmall=/api/users/seg8-ihrf/profile_images/TINY v:roleName=administrator v:displayName="Eckstine, Nate"
```

## Top Records

```ls
| :updated_at | account                             | tweets | following | followers | month  | likes | lists | moments | dept | department                                   | 
| =========== | =================================== | ====== | ========= | ========= | ====== | ===== | ===== | ======= | ==== | ============================================ | 
| 1487807320  | https://twitter.com/seattlecityjobs | 961    | 615       | 1014      | 16-Nov | 373   | 0     | 0       | ITD  | Information Technology Department            | 
| 1487807320  | https://twitter.com/seattledci      | 3504   | 732       | 4629      | 16-Dec | 535   | 17    | 0       | DCI  | Department of Construction and Inspections   | 
| 1487807320  | https://twitter.com/seattlecityjobs | 961    | 613       | 1025      | 16-Dec | 404   | 0     | 0       | ITD  | Information Technology Department            | 
| 1487807320  | https://twitter.com/d5juarez        | 308    | 362       | 677       | 16-Jun | 166   | 0     | 0       | LEG  | Council                                      | 
| 1487807320  | https://twitter.com/seattleopcd     | 473    | 100       | 349       | 16-Aug | 70    | 0     | 0       | PCD  | Office of Planning and Community Development | 
| 1487807320  | https://twitter.com/seattlecouncil  | 8053   | 489       | 34379     | 17-Jan | 1212  | 1     | 0       | LEG  | Council                                      | 
| 1487807320  | https://twitter.com/seattlearts     | 6074   | 1347      | 82707     | 16-Nov | 3502  | 2     | 0       | ARTS | Office of Arts and Culture                   | 
| 1487807320  | https://twitter.com/seaeec          | 46     | 36        | 88        | 16-Nov | 0     | 0     | 0       | DOE  | Department of Education                      | 
| 1487807320  | https://twitter.com/cityofseattle/  | 3367   | 1522      | 119193    | 16-Nov | 145   | 27    | 0       | ITD  | Information Technology Department            | 
| 1487807320  | https://twitter.com/seattledot      | 59525  | 197       | 108773    | 16-Oct | 1116  | 0     | 0       | DOT  | Department of Transportation                 | 
```