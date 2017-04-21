# Austin Animal Center Intakes

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/austin-animal-center-intakes) |
| Metadata | [Link](https://data.austintexas.gov/api/views/wter-evkm) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/wter-evkm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/wter-evkm/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | wter-evkm |
| Name | Austin Animal Center Intakes |
| Attribution | Austin Animal Center |
| Category | Health |
| Tags | intakes, animal, cat, dog, pet, no kill, stray, surrendered, lost, found |
| Created | 2015-10-19T20:16:34Z |
| Publication Date | 2017-01-13T22:47:40Z |

## Description

Animal Center Intakes from Oct, 1st 2013 to present. Intakes represent  animals brought to the center by citizens or Animal Services staff.  Animals may be brought to the center as lost, injured or for the purpose of adoption. Animals may also be brought to the center as Public Assist.  The found location is often only an estimation of where the animal was found.  All animals receive a unique Animal ID during intake.

This data set replaces all previous Animal Center Intakes data sets.

THIS DATA SET IS STILL IN BETA.

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type     | Render Type   |
| ======== | =========== | ================ | ================ | ============= | ============= |
| Yes      | series tag  | animal_id        | Animal ID        | text          | text          |
| Yes      | series tag  | name             | Name             | text          | text          |
| Yes      | time        | datetime         | DateTime         | calendar_date | calendar_date |
| No       |             | datetime2        | MonthYear        | calendar_date | calendar_date |
| Yes      | series tag  | found_location   | Found Location   | text          | text          |
| Yes      | series tag  | intake_type      | Intake Type      | text          | text          |
| Yes      | series tag  | intake_condition | Intake Condition | text          | text          |
| Yes      | series tag  | animal_type      | Animal Type      | text          | text          |
| Yes      | series tag  | sex_upon_intake  | Sex upon Intake  | text          | text          |
| Yes      | series tag  | age_upon_intake  | Age upon Intake  | text          | text          |
| Yes      | series tag  | breed            | Breed            | text          | text          |
| Yes      | series tag  | color            | Color            | text          | text          |
```

## Time Field

```ls
Value = datetime
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = datetime2
```

## Data Commands

```ls
series e:wter-evkm d:2016-07-07T12:11:00.000Z t:sex_upon_intake="Intact Male" t:breed="Domestic Shorthair Mix" t:intake_condition=Normal t:color="Blue Tabby" t:age_upon_intake="7 months" t:found_location="1109 Shady Ln in Austin (TX)" t:animal_type=Cat t:intake_type=Stray t:animal_id=A730601 m:row_number.wter-evkm=1

series e:wter-evkm d:2014-07-13T11:02:00.000Z t:sex_upon_intake="Intact Female" t:breed="Border Collie Mix" t:intake_condition=Nursing t:color=Brown/White t:name=*Zoey t:age_upon_intake="4 weeks" t:found_location="Austin (TX)" t:animal_type=Dog t:intake_type="Owner Surrender" t:animal_id=A683644 m:row_number.wter-evkm=2

series e:wter-evkm d:2014-04-11T08:45:00.000Z t:sex_upon_intake="Intact Male" t:breed="Pit Bull Mix" t:intake_condition=Normal t:color=White/Brown t:name=Rico t:age_upon_intake="2 months" t:found_location="615 E. Wonsley in Austin (TX)" t:animal_type=Dog t:intake_type=Stray t:animal_id=A676515 m:row_number.wter-evkm=3
```

## Meta Commands

```ls
metric m:row_number.wter-evkm p:long l:"Row Number"

entity e:wter-evkm l:"Austin Animal Center Intakes" t:attribution="Austin Animal Center" t:url=https://data.austintexas.gov/api/views/wter-evkm

property e:wter-evkm t:meta.view v:id=wter-evkm v:category=Health v:attributionLink=http://www.austintexas.gov/department/animal-services v:averageRating=0 v:name="Austin Animal Center Intakes" v:attribution="Austin Animal Center"

property e:wter-evkm t:meta.view.license v:name="Public Domain"

property e:wter-evkm t:meta.view.owner v:id=nc6h-vjxb v:screenName=duron v:displayName=duron

property e:wter-evkm t:meta.view.tableauthor v:id=nc6h-vjxb v:screenName=duron v:roleName=editor v:displayName=duron
```

## Top Records

```ls
| animal_id | name       | datetime            | datetime2           | found_location                             | intake_type     | intake_condition | animal_type | sex_upon_intake | age_upon_intake | breed                    | color             | 
| ========= | ========== | =================== | =================== | ========================================== | =============== | ================ | =========== | =============== | =============== | ======================== | ================= | 
| A730601   |            | 2016-07-07T12:11:00 | 2016-07-07T12:11:00 | 1109 Shady Ln in Austin (TX)               | Stray           | Normal           | Cat         | Intact Male     | 7 months        | Domestic Shorthair Mix   | Blue Tabby        | 
| A683644   | *Zoey      | 2014-07-13T11:02:00 | 2014-07-13T11:02:00 | Austin (TX)                                | Owner Surrender | Nursing          | Dog         | Intact Female   | 4 weeks         | Border Collie Mix        | Brown/White       | 
| A676515   | Rico       | 2014-04-11T08:45:00 | 2014-04-11T08:45:00 | 615 E. Wonsley in Austin (TX)              | Stray           | Normal           | Dog         | Intact Male     | 2 months        | Pit Bull Mix             | White/Brown       | 
| A742953   |            | 2017-01-31T13:30:00 | 2017-01-31T13:30:00 | S Hwy 183 And Thompson Lane in Austin (TX) | Stray           | Normal           | Dog         | Intact Male     | 2 years         | Saluki                   | Sable/Cream       | 
| A679549   | *Gilbert   | 2014-05-22T15:43:00 | 2014-05-22T15:43:00 | 124 W Anderson in Austin (TX)              | Stray           | Normal           | Cat         | Intact Male     | 1 month         | Domestic Shorthair Mix   | Black/White       | 
| A683798   | Mustachala | 2016-07-21T12:16:00 | 2016-07-21T12:16:00 | 3118 Windsor Rd in Austin (TX)             | Stray           | Normal           | Cat         | Spayed Female   | 3 years         | Domestic Medium Hair Mix | White/Black       | 
| A683656   |            | 2014-07-13T13:20:00 | 2014-07-13T13:20:00 | 8238 Research Blvd in Austin (TX)          | Stray           | Normal           | Cat         | Intact Male     | 2 months        | Snowshoe Mix             | Lynx Point        | 
| A709749   | *Janeane   | 2015-08-12T18:29:00 | 2015-08-12T18:29:00 | 4800 Weletka Dr in Austin (TX)             | Stray           | Normal           | Cat         | Intact Female   | 1 year          | Domestic Shorthair Mix   | Calico            | 
| A692161   | George     | 2014-11-15T15:18:00 | 2014-11-15T15:18:00 | Avenue G/42Nd in Austin (TX)               | Owner Surrender | Normal           | Dog         | Intact Male     | 5 months        | Pit Bull Mix             | Brown/White       | 
| A733551   | *Phillip   | 2016-08-23T14:35:00 | 2016-08-23T14:35:00 | 183 And Cameron in Austin (TX)             | Stray           | Normal           | Cat         | Intact Male     | 1 month         | Domestic Shorthair Mix   | Brown Tabby/White | 
```