# Honolulu 311 Reports

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/honolulu-311-reports-c9ddd) |
| Metadata | [Link](https://data.honolulu.gov/api/views/6hui-dvrh) |
| Data: JSON | [100 Rows](https://data.honolulu.gov/api/views/6hui-dvrh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.honolulu.gov/api/views/6hui-dvrh/rows.csv?max_rows=100) |
| Host | data.honolulu.gov |
| Id | 6hui-dvrh |
| Name | Honolulu 311 Reports |
| Created | 2015-02-27T00:55:31Z |
| Publication Date | 2017-02-21T19:32:30Z |

## Description

Updated daily with reports from the past month.

## Columns

```ls
| Included | Schema Type | Field Name  | Name        | Data Type     | Render Type   |
| ======== | =========== | =========== | =========== | ============= | ============= |
| No       |             | id          | Id          | text          | number        |
| Yes      | time        | datecreated | DateCreated | calendar_date | calendar_date |
| No       |             | dateupdated | DateUpdated | calendar_date | calendar_date |
| Yes      | series tag  | requesttype | RequestType | text          | text          |
| Yes      | series tag  | city        | City        | text          | text          |
| Yes      | series tag  | zipcode     | ZipCode     | text          | number        |
| Yes      | series tag  | statustype  | StatusType  | text          | text          |
| Yes      | series tag  | description | Description | text          | text          |
```

## Time Field

```ls
Value = datecreated
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = id,dateupdated
```

## Data Commands

```ls
series e:6hui-dvrh d:2017-04-19T23:25:49.000Z t:description="4 door Toyota Camry purplish/maroon color" t:statustype=Closed t:requesttype="Abandoned Vehicle" m:row_number.6hui-dvrh=1

series e:6hui-dvrh d:2017-04-19T23:23:31.000Z t:description="Silver toyota forerunner.  Abandon for months." t:statustype=Closed t:requesttype="Abandoned Vehicle" m:row_number.6hui-dvrh=2

series e:6hui-dvrh d:2017-04-19T20:56:51.000Z t:description="Parked for months" t:statustype=Closed t:requesttype="Abandoned Vehicle" m:row_number.6hui-dvrh=3
```

## Meta Commands

```ls
metric m:row_number.6hui-dvrh p:long l:"Row Number"

entity e:6hui-dvrh l:"Honolulu 311 Reports" t:url=https://data.honolulu.gov/api/views/6hui-dvrh

property e:6hui-dvrh t:meta.view v:id=6hui-dvrh v:averageRating=0 v:name="Honolulu 311 Reports"

property e:6hui-dvrh t:meta.view.owner v:id=sr3i-nqxd v:screenName="Open Data" v:displayName="Open Data"

property e:6hui-dvrh t:meta.view.tableauthor v:id=sr3i-nqxd v:screenName="Open Data" v:roleName=administrator v:displayName="Open Data"
```

## Top Records

```ls
| id     | datecreated         | dateupdated         | requesttype               | city | zipcode | statustype     | description                                                                                                                                                                                            | 
| ====== | =================== | =================== | ========================= | ==== | ======= | ============== | ====================================================================================================================================================================================================== | 
| 342722 | 2017-04-19T23:25:49 | 2017-04-19T23:46:07 | Abandoned Vehicle         |      |         | Closed         | 4 door Toyota Camry purplish/maroon color                                                                                                                                                              | 
| 342719 | 2017-04-19T23:23:31 | 2017-04-20T00:39:59 | Abandoned Vehicle         |      |         | Closed         | Silver toyota forerunner. Abandon for months.                                                                                                                                                          | 
| 342672 | 2017-04-19T20:56:51 | 2017-04-19T21:22:58 | Abandoned Vehicle         |      |         | Closed         | Parked for months                                                                                                                                                                                      | 
| 342617 | 2017-04-19T18:38:48 | 2017-04-19T19:41:32 | Broken Street Light       |      |         | ReferredToDept | This pole is located at the end of Aawa Dr. When you get to the end, it's the pole staight ahead. There was no pole number and the light goes on and off.                                              | 
| 342585 | 2017-04-19T17:27:41 | 2017-04-19T20:30:41 | Other                     |      |         | ReferredToDept | Graffiti on the side of the Burgers and Things and Pauoa Chop Sui bldg, which can be seen from Pali highway and cannot be painted over by citizens bc of the gap between Pali highway and the building | 
| 342546 | 2017-04-19T16:19:39 | 2017-04-19T19:39:16 | Broken / Vandalized signs |      |         | ReferredToDept | This sign has been on the ground for a couple of weeks now.                                                                                                                                            | 
| 342426 | 2017-04-19T07:29:10 | 2017-04-19T19:35:54 | Illegal dump site         |      |         | ReferredToDept | Mid month bulk dump again. Started this past Friday with mattress set, freezer on Sunday. Then couch set, tables, and elliptical between 5pm and 9 pm tonight. Yay!!!                                  | 
| 342407 | 2017-04-19T03:49:14 | 2017-04-19T18:37:23 | Other                     |      |         | ReferredToDept | Crosswalk faded and no posted sign. On Nuuanu and Robinson Ln.                                                                                                                                         | 
| 342405 | 2017-04-19T03:43:01 | 2017-04-19T21:41:33 | Other                     |      |         | ReferredToDept | Crosswalk is faded and no crosswalk sign                                                                                                                                                               | 
| 342384 | 2017-04-19T02:03:35 | 2017-04-20T07:04:05 | Clogged Catch Basin       |      |         | ReferredToDept | Thick trees growing in storm drain at entrance to MARINERS COVE in Hawaii Kai. I have pictures from few yrs ago when area was cut. I can show u where - Kamilo St & Hai Dr. My cell 425 890 6611       | 
```