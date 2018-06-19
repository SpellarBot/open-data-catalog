# Rockford Police Department 72 Hour Dispatch Call Log

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/rockford-police-department-72-hour-dispatch-call-log) |
| Metadata | [Link](https://data.illinois.gov/api/views/9zru-nvxs) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/9zru-nvxs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/9zru-nvxs/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 9zru-nvxs |
| Name | Rockford Police Department 72 Hour Dispatch Call Log |
| Category | Public Safety |
| Tags | city of rockford, rockford, calls for service, dispatch |
| Created | 2016-07-25T20:44:45Z |
| Publication Date | 2016-07-25T21:18:47Z |

## Description

City of Rockford Police Department Open Data Disclaimer:

The purpose of this dataset is to display a continuing dispatched Call for Service (CFS) log for the previous 72 hours. Only CFS that have been dispatched for at least one hour will display and the log will be refreshed once every hour. Some CFS have been suppressed from this log due to the sensitivity of the type of call. Primarily, any CFS involving sexual, domestic related or sensitive juvenile incidents have been suppressed.

All data contained on this site has been gathered through legitimate means and with the knowledge and approval of the Rockford Police Department. All data has been extracted, processed and presented through appropriate channels. 

Data and Information: 
All CFS data is obtained from the Police/911 Computer Aided Dispatch (CAD) system as reported. Information is preliminary and subject to change as police reports are submitted. Media outlets are advised to confirm any information not already verified through department issued press releases. Data is illustrative, not an official crime report, and should not be used for comparative reporting. The Rockford Police Department is not responsible for any error or omission, misuse, or results obtained from the use of this information. Although no personal information is disseminated through data.illinois.gov, remember that all subjects are presumed innocent until proven guilty in a court of law.

## Columns

```ls
| Included | Schema Type | Field Name         | Name               | Data Type | Render Type |
| ======== | =========== | ================== | ================== | ========= | =========== |
| Yes      | series tag  | event_number       | Event Number       | text      | text        |
| No       |             | full_address       | Full Address       | text      | text        |
| Yes      | series tag  | city               | City               | text      | text        |
| Yes      | series tag  | reporting_district | Reporting District | text      | text        |
| Yes      | series tag  | incident_type      | Incident Type      | text      | text        |
| No       |             | dispatch_date      | Dispatch Date      | text      | text        |
| No       |             | dispatch_time      | Dispatch Time      | text      | text        |
| Yes      | time        | dispatch_datetime  | Dispatch Datetime  | text      | text        |
```

## Time Field

```ls
Value = dispatch_datetime
Format & Zone = yyyy-MM-dd HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = full_address,dispatch_date,dispatch_time
```

## Data Commands

```ls
series e:9zru-nvxs d:2017-04-18T07:46:20.000Z t:incident_type="INVESTIGATION NON-SPECIFIC" t:event_number=17-044845 t:reporting_district=RP07 t:city=Rockford m:row_number.9zru-nvxs=1

series e:9zru-nvxs d:2017-04-18T07:34:00.000Z t:incident_type=DECEPTION:FRAUD t:event_number=17-044841 t:reporting_district=RP05 t:city=Rockford m:row_number.9zru-nvxs=2

series e:9zru-nvxs d:2017-04-18T07:00:36.000Z t:incident_type="TRAFFIC ACCIDENT W/INJURIES" t:event_number=17-044836 t:reporting_district=RP03 t:city=Rockford m:row_number.9zru-nvxs=3
```

## Meta Commands

```ls
metric m:row_number.9zru-nvxs p:long l:"Row Number"

entity e:9zru-nvxs l:"Rockford Police Department 72 Hour Dispatch Call Log" t:url=https://data.illinois.gov/api/views/9zru-nvxs

property e:9zru-nvxs t:meta.view v:id=9zru-nvxs v:category="Public Safety" v:averageRating=0 v:name="Rockford Police Department 72 Hour Dispatch Call Log"

property e:9zru-nvxs t:meta.view.owner v:id=xph9-z7ij v:profileImageUrlMedium=/api/users/xph9-z7ij/profile_images/THUMB v:profileImageUrlLarge=/api/users/xph9-z7ij/profile_images/LARGE v:screenName="Open Data Rockford" v:profileImageUrlSmall=/api/users/xph9-z7ij/profile_images/TINY v:displayName="Open Data Rockford"

property e:9zru-nvxs t:meta.view.tableauthor v:id=xph9-z7ij v:profileImageUrlMedium=/api/users/xph9-z7ij/profile_images/THUMB v:profileImageUrlLarge=/api/users/xph9-z7ij/profile_images/LARGE v:screenName="Open Data Rockford" v:profileImageUrlSmall=/api/users/xph9-z7ij/profile_images/TINY v:roleName=publisher v:displayName="Open Data Rockford"
```

## Top Records

```ls
| event_number | full_address                  | city     | reporting_district | incident_type                                     | dispatch_date | dispatch_time | dispatch_datetime   | 
| ============ | ============================= | ======== | ================== | ================================================= | ============= | ============= | =================== | 
| 17-044845    | 3134 11TH ST                  | Rockford | RP07               | INVESTIGATION NON-SPECIFIC                        | 2017-04-18    | 07:46:20      | 2017-04-18 07:46:20 | 
| 17-044841    | 200 PRAIRIE ST                | Rockford | RP05               | DECEPTION:FRAUD                                   | 2017-04-18    | 07:34:00      | 2017-04-18 07:34:00 | 
| 17-044836    | MONTAGUE RD&S SPRINGFIELD AVE | Rockford | RP03               | TRAFFIC ACCIDENT W/INJURIES                       | 2017-04-18    | 07:00:36      | 2017-04-18 07:00:36 | 
| 17-044844    | 501 W STATE ST                | Rockford | RP03               | DEPARTMENT SERVICE/ACTIVITY PRELIMINARY FOLLOW-UP | 2017-04-18    | 07:40:35      | 2017-04-18 07:40:35 | 
| 17-044848    | 3137 LIBERTY DR               | Rockford | RP04               | CRIMINAL DAMAGE TO PROPERTY                       | 2017-04-18    | 07:53:07      | 2017-04-18 07:53:07 | 
| 17-044838    | 10TH ST&BROADWAY              | Rockford | RP06               | Walk-in Report                                    | 2017-04-18    | 07:43:19      | 2017-04-18 07:43:19 | 
| 17-044840    | 1407 7TH AVE                  | Rockford | RP06               | RECOVER STOLEN VEHICLE                            | 2017-04-18    | 07:34:32      | 2017-04-18 07:34:32 | 
| 17-044834    | 1000 CHAMBERLAIN ST           | Rockford | RP05               | LOUD MUSIC                                        | 2017-04-18    | 07:13:35      | 2017-04-18 07:13:35 | 
| 17-044837    | 5205 EINOR AVE                | Rockford | RP09               | ALARM - BUSINESS                                  | 2017-04-18    | 07:26:32      | 2017-04-18 07:26:32 | 
| 17-044843    | 5666 E STATE ST               | Rockford | RP08               | 911 HANG UP                                       | 2017-04-18    | 07:39:15      | 2017-04-18 07:39:15 | 
```