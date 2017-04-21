# BPD Arrests

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/bpd-arrests-4f2eb) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/3i3v-ibrt) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/3i3v-ibrt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/3i3v-ibrt/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | 3i3v-ibrt |
| Name | BPD Arrests |
| Attribution | Baltimore Police Department |
| Category | Public Safety |
| Tags | arrests, crime, police |
| Created | 2011-10-18T14:10:55Z |
| Publication Date | 2017-04-07T16:52:01Z |

## Description

This data represents the top arrest charge of those processed at Baltimore's Central Booking & Intake Facility. This data does not contain those who have been processed through Juvenile Booking.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type     | Render Type   |
| ======== | ============== | ================= | ================= | ============= | ============= |
| Yes      | numeric metric | arrest            | Arrest            | number        | text          |
| Yes      | numeric metric | age               | Age               | number        | number        |
| Yes      | series tag     | sex               | Sex               | text          | text          |
| Yes      | series tag     | race              | Race              | text          | text          |
| Yes      | time           | arrestdate        | ArrestDate        | calendar_date | calendar_date |
| Yes      | series tag     | arresttime        | ArrestTime        | text          | text          |
| Yes      | series tag     | arrestlocation    | ArrestLocation    | text          | text          |
| Yes      | series tag     | incidento         | IncidentOffense   | text          | text          |
| Yes      | series tag     | incidentl         | IncidentLocation  | text          | text          |
| Yes      | series tag     | charge            | Charge            | text          | text          |
| Yes      | series tag     | chargedescription | ChargeDescription | text          | text          |
| Yes      | series tag     | district          | District          | text          | text          |
| Yes      | numeric metric | post              | Post              | number        | number        |
| Yes      | series tag     | name1             | Neighborhood      | text          | text          |
```

## Time Field

```ls
Value = arrestdate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:3i3v-ibrt d:2017-04-01T00:00:00.000Z t:sex=M t:charge="2 0480" t:arresttime=23:55 t:chargedescription="AUTO THEFT" t:incidentl="2600 HARFORD RD" t:arrestlocation="2600 HARFORD RD" t:name1="Coldstream Homestead Montebello" t:district=Northeastern t:race=B t:incidento="26RECOVERED VEHICLE" m:post=411 m:arrest=17049173 m:age=27

series e:3i3v-ibrt d:2017-04-01T00:00:00.000Z t:sex=M t:charge="1 1415" t:arresttime=23:49 t:chargedescription="2ND DEGREE ASSAULT" t:incidentl="3400 W BELVEDERE AVE" t:arrestlocation="3400 W BELVEDERE AVE" t:name1=Arlington t:district=Northwestern t:race=B t:incidento="4ECOMMON ASSAULT" m:post=633 m:arrest=17049144 m:age=32

series e:3i3v-ibrt d:2017-04-01T00:00:00.000Z t:sex=F t:charge="1 1415" t:arresttime=23:00 t:chargedescription="COMMON ASSAULT" t:incidentl="1600 N CALHOUN ST" t:arrestlocation="1600 N CALHOUN ST" t:name1=Sandtown-Winchester t:district=Western t:race=B t:incidento="4ECOMMON ASSAULT" m:post=742 m:arrest=17049162 m:age=52
```

## Meta Commands

```ls
metric m:arrest p:integer l:Arrest t:dataTypeName=number

metric m:age p:integer l:Age t:dataTypeName=number

metric m:post p:integer l:Post t:dataTypeName=number

entity e:3i3v-ibrt l:"BPD Arrests" t:attribution="Baltimore Police Department" t:url=https://data.baltimorecity.gov/api/views/3i3v-ibrt

property e:3i3v-ibrt t:meta.view v:id=3i3v-ibrt v:category="Public Safety" v:attributionLink=http://www.baltimorepolice.org/ v:averageRating=0 v:name="BPD Arrests" v:attribution="Baltimore Police Department"

property e:3i3v-ibrt t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:3i3v-ibrt t:meta.view.owner v:id=ye7n-cr57 v:screenName="Jeffrey Cooper" v:displayName="Jeffrey Cooper"

property e:3i3v-ibrt t:meta.view.tableauthor v:id=ye7n-cr57 v:screenName="Jeffrey Cooper" v:roleName=publisher v:displayName="Jeffrey Cooper"
```

## Top Records

```ls
| arrest   | age | sex | race | arrestdate          | arresttime | arrestlocation       | incidento                   | incidentl            | charge | chargedescription     | district     | post | name1                           | 
| ======== | === | === | ==== | =================== | ========== | ==================== | =========================== | ==================== | ====== | ===================== | ============ | ==== | =============================== | 
| 17049173 | 27  | M   | B    | 2017-04-01T00:00:00 | 23:55      | 2600 HARFORD RD      | 26RECOVERED VEHICLE         | 2600 HARFORD RD      | 2 0480 | AUTO THEFT            | Northeastern | 411  | Coldstream Homestead Montebello | 
| 17049144 | 32  | M   | B    | 2017-04-01T00:00:00 | 23:49      | 3400 W BELVEDERE AVE | 4ECOMMON ASSAULT            | 3400 W BELVEDERE AVE | 1 1415 | 2ND DEGREE ASSAULT    | Northwestern | 633  | Arlington                       | 
| 17049162 | 52  | F   | B    | 2017-04-01T00:00:00 | 23:00      | 1600 N CALHOUN ST    | 4ECOMMON ASSAULT            | 1600 N CALHOUN ST    | 1 1415 | COMMON ASSAULT        | Western      | 742  | Sandtown-Winchester             | 
| 17049132 | 28  | F   | B    | 2017-04-01T00:00:00 | 22:05      | 3700 BELAIR RD       | 118BURGLARY - FOURTH DEGREE | 3700 BELAIR RD       | 1 1130 | 4TH DEGREE BURGLARY   | Northeastern | 422  | Herring Run Park                | 
| 17049129 | 37  | M   | B    | 2017-04-01T00:00:00 | 22:05      | 3700 BELAIR RD       | 118BURGLARY - FOURTH DEGREE | 3700 BELAIR RD       | 1 1130 | FORTH DEGREE BURGLARY | Northeastern | 422  | Herring Run Park                | 
| 17049131 | 44  | F   | W    | 2017-04-01T00:00:00 | 21:50      | 400 NORTH AVE        | 4ECOMMON ASSAULT            | 400 E NORTH AVE      | 1 1415 | 2ND DEGREE ASSAULT    | Eastern      | 341  | Barclay                         | 
| 17049146 | 31  | M   | B    | 2017-04-01T00:00:00 | 21:39      | 400 E 25TH ST        | Unknown Offense             |                      |        | DRIVING W/O LIC.      | Northern     | 513  | Harwood                         | 
| 17049153 | 31  | M   | B    | 2017-04-01T00:00:00 | 21:25      |                      | Unknown Offense             |                      | 1 1415 | ASSAULT-SEC DEGREE    |              |      |                                 | 
| 17049123 | 27  | M   | B    | 2017-04-01T00:00:00 | 20:30      | 1900 GREENMOUNT AVE  | Unknown Offense             | 1900 GREENMOUNT AVE  | 1 0233 | CDS                   | Eastern      | 341  | Barclay                         | 
| 17049110 | 33  | M   | U    | 2017-04-01T00:00:00 | 20:30      | 1900 GREENMOUNT AVE  | Unknown Offense             | 1900 GREENMOUNT AVE  | 1 0233 | CDS                   | Eastern      | 341  | Barclay                         | 
```