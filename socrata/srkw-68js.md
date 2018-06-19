# BPD Arrests 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/bpd-arrests-2012-d0d9e) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/srkw-68js) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/srkw-68js/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/srkw-68js/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | srkw-68js |
| Name | BPD Arrests 2012 |
| Attribution | Baltimore Police Department |
| Category | Public Safety |
| Tags | arrests, crime, police |
| Created | 2014-01-13T16:23:20Z |
| Publication Date | 2014-01-13T20:19:46Z |

## Description

This data represents the top arrest charge of those processed at Baltimore's Central Booking & Intake Facility. This data does not contain those who have been processed through Juvenile Booking.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type     | Render Type   |
| ======== | ============== | ================= | ================= | ============= | ============= |
| Yes      | numeric metric | arrest            | arrest            | number        | number        |
| Yes      | numeric metric | age               | age               | number        | number        |
| Yes      | series tag     | sex               | sex               | text          | text          |
| Yes      | series tag     | race              | race              | text          | text          |
| Yes      | time           | arrestdate        | arrestDate        | calendar_date | calendar_date |
| Yes      | series tag     | arresttime        | arrestTime        | text          | text          |
| Yes      | series tag     | arrestlocation    | arrestLocation    | text          | text          |
| Yes      | series tag     | incidentoffense   | incidentOffense   | text          | text          |
| Yes      | series tag     | offenselocation   | offenseLocation   | text          | text          |
| Yes      | series tag     | charge            | charge            | text          | text          |
| Yes      | series tag     | chargedescription | chargeDescription | text          | text          |
| Yes      | series tag     | district          | district          | text          | text          |
| Yes      | numeric metric | post              | post              | number        | number        |
| Yes      | series tag     | neighborhood      | neighborhood      | text          | text          |
```

## Time Field

```ls
Value = arrestdate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:srkw-68js d:2012-01-01T00:00:00.000Z t:sex=M t:incidentoffense=87-Narcotics t:charge="1 0573" t:arresttime=01:25 t:offenselocation="0 N Calvert St" t:chargedescription="Cds: Possession-Marihuana || Poss. Marijuana" t:neighborhood="Charles Village" t:arrestlocation="0 N Calvert St" t:district=NORTHERN t:race=B m:post=515 m:arrest=12395857 m:age=23

series e:srkw-68js d:2012-01-01T00:00:00.000Z t:sex=M t:incidentoffense="4E-Common Assault" t:charge="1 1415" t:arresttime=14:20 t:offenselocation="0 N Gay St" t:chargedescription="Asslt-Sec Degree || Assault" t:neighborhood=Downtown t:arrestlocation="0 Gay St" t:district=CENTRAL t:race=W m:post=111 m:arrest=12396075 m:age=34

series e:srkw-68js d:2012-01-01T00:00:00.000Z t:sex=M t:incidentoffense="4B-Agg. Asslt.- Cut" t:charge="1 4200" t:arresttime=01:25 t:offenselocation="100 W Jeffrey St" t:chargedescription="Alc. Bev./Intox:Endanger || Aggravated Assault" t:neighborhood=Brooklyn t:arrestlocation="100 W Jeffrey St" t:district=SOUTHERN t:race=U m:post=912 m:arrest=12395968 m:age=22
```

## Meta Commands

```ls
metric m:arrest p:integer l:arrest t:dataTypeName=number

metric m:age p:integer l:age t:dataTypeName=number

metric m:post p:integer l:post t:dataTypeName=number

entity e:srkw-68js l:"BPD Arrests 2012" t:attribution="Baltimore Police Department" t:url=https://data.baltimorecity.gov/api/views/srkw-68js

property e:srkw-68js t:meta.view v:id=srkw-68js v:category="Public Safety" v:attributionLink=http://www.baltimorepolice.org/ v:averageRating=0 v:name="BPD Arrests 2012" v:attribution="Baltimore Police Department"

property e:srkw-68js t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:srkw-68js t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:srkw-68js t:meta.view.tableauthor v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```

## Top Records

```ls
| arrest   | age | sex | race | arrestdate          | arresttime | arrestlocation     | incidentoffense      | offenselocation    | charge | chargedescription                              | district     | post | neighborhood                    | 
| ======== | === | === | ==== | =================== | ========== | ================== | ==================== | ================== | ====== | ============================================== | ============ | ==== | =============================== | 
| 12395857 | 23  | M   | B    | 2012-01-01T00:00:00 | 01:25      | 0 N Calvert St     | 87-Narcotics         | 0 N Calvert St     | 1 0573 | Cds: Possession-Marihuana || Poss. Marijuana   | NORTHERN     | 515  | Charles Village                 | 
| 12396075 | 34  | M   | W    | 2012-01-01T00:00:00 | 14:20      | 0 Gay St           | 4E-Common Assault    | 0 N Gay St         | 1 1415 | Asslt-Sec Degree || Assault                    | CENTRAL      | 111  | Downtown                        | 
| 12395968 | 22  | M   | U    | 2012-01-01T00:00:00 | 01:25      | 100 W Jeffrey St   | 4B-Agg. Asslt.- Cut  | 100 W Jeffrey St   | 1 4200 | Alc. Bev./Intox:Endanger || Aggravated Assault | SOUTHERN     | 912  | Brooklyn                        | 
| 12396099 | 29  | F   | B    | 2012-01-01T00:00:00 | 18:30      | 1000 N Wolfe St    | 4E-Common Assault    | 1000 N Wolfe St    | 1 1415 | Asslt-Sec Degree || Common Assault             | EASTERN      | 323  | Middle East                     | 
| 12396094 | 32  | M   | B    | 2012-01-01T00:00:00 | 18:30      | 1000 N Wolfe St    | 4E-Common Assault    | 1000 N Wolfe St    | 1 1415 | Asslt-Sec Degree || Common Assault             | EASTERN      | 323  | Middle East                     | 
| 12395848 | 24  | M   | W    | 2012-01-01T00:00:00 | 00:19      | 1000 S Carey St    | 4A-Agg. Asslt.- Gun  | 1000 S Carey St    | 1 1415 | Asslt-Sec Degree || Cds Common Assault         | SOUTHERN     | 931  | Washington Village/Pigtown      | 
| 12396084 | 33  | M   | B    | 2012-01-01T00:00:00 | 19:00      | 1000 W Franklin St | 4C-Agg. Asslt.- Oth. | 1000 W Franklin St | 1 1415 | Asslt-Sec Degree || Child Abuse                | WESTERN      | 714  | Harlem Park                     | 
| 12395879 | 21  | M   | B    | 2012-01-01T00:00:00 | 00:30      | 0 W Cross St       | 4E-Common Assault    | 1100 S Charles St  | 2 0050 | Dis.Erly Conduct || Disorderly                 | SOUTHERN     | 942  | Federal Hill                    | 
| 12396126 | 29  | M   | B    | 2012-01-01T00:00:00 | 20:24      | 1200 E 25 Th St    | 24-Towed Vehicle     | 1200 E 25Th St     |        | Agg Assault                                    | NORTHEASTERN | 411  | Coldstream Homestead Montebello | 
| 12395891 | 60  | M   | B    | 2012-01-01T00:00:00 | 02:00      | 1200 Shellbanks Rd | 4B-Agg. Asslt.- Cut  | 1200 Shellbanks Rd | 1 1425 | Reckless Endangerment || 1St Degree Assault    | SOUTHERN     | 922  | Cherry Hill                     | 
```