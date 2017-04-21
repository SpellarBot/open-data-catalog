# Intake within and outside CCRB Jurisdiction

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/intake-within-and-outside-ccrb-jurisdiction-2ecb8) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/m6nh-ye6v) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/m6nh-ye6v/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/m6nh-ye6v/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | m6nh-ye6v |
| Name | Intake within and outside CCRB Jurisdiction |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | City Government |
| Tags | ccrb, jurisdiction, complaints, referrals |
| Created | 2013-02-25T21:24:45Z |
| Publication Date | 2013-06-21T20:05:18Z |

## Description

This table represents the total intake of complaints within and outside CCRB Jurisdiction

## Columns

```ls
| Included | Schema Type    | Field Name                                     | Name                                           | Data Type | Render Type |
| ======== | ============== | ============================================== | ============================================== | ========= | =========== |
| Yes      | time           | year                                           | Year                                           | number    | text        |
| Yes      | numeric metric | complaints_within_ccrb_jurisdiction            | Complaints within CCRB Jurisdiction            | number    | text        |
| Yes      | series tag     | referrals_to_office_of_the_chief_of_department | Referrals to Office of the Chief Of Department | text      | text        |
| Yes      | numeric metric | referrals_to_internal_affairs_bureau           | Referrals to Internal Affairs Bureau           | number    | text        |
| Yes      | numeric metric | referrals_to_other_agencies                    | Referrals to Other Agencies                    | number    | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:m6nh-ye6v d:2009-01-01T00:00:00.000Z t:referrals_to_office_of_the_chief_of_department=9500 m:complaints_within_ccrb_jurisdiction=7660 m:referrals_to_internal_affairs_bureau=1626 m:referrals_to_other_agencies=305

series e:m6nh-ye6v d:2010-01-01T00:00:00.000Z t:referrals_to_office_of_the_chief_of_department=8634 m:complaints_within_ccrb_jurisdiction=6467 m:referrals_to_internal_affairs_bureau=1716 m:referrals_to_other_agencies=218

series e:m6nh-ye6v d:2011-01-01T00:00:00.000Z t:referrals_to_office_of_the_chief_of_department=8184 m:complaints_within_ccrb_jurisdiction=5966 m:referrals_to_internal_affairs_bureau=1734 m:referrals_to_other_agencies=182
```

## Meta Commands

```ls
metric m:complaints_within_ccrb_jurisdiction p:integer l:"Complaints within CCRB Jurisdiction" t:dataTypeName=number

metric m:referrals_to_internal_affairs_bureau p:integer l:"Referrals to Internal Affairs Bureau" t:dataTypeName=number

metric m:referrals_to_other_agencies p:integer l:"Referrals to Other Agencies" t:dataTypeName=number

entity e:m6nh-ye6v l:"Intake within and outside CCRB Jurisdiction" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/m6nh-ye6v

property e:m6nh-ye6v t:meta.view v:id=m6nh-ye6v v:category="City Government" v:attributionLink=http://www.nyc.gov/html/ccrb/pdf/ccrbappendices2011.pdf v:averageRating=0 v:name="Intake within and outside CCRB Jurisdiction" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:m6nh-ye6v t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:m6nh-ye6v t:meta.view.tableauthor v:id=iacr-duv5 v:screenName=Tejas.Patel v:displayName=Tejas.Patel
```

## Top Records

```ls
| year | complaints_within_ccrb_jurisdiction | referrals_to_office_of_the_chief_of_department | referrals_to_internal_affairs_bureau | referrals_to_other_agencies | 
| ==== | =================================== | ============================================== | ==================================== | =========================== | 
| 2009 | 7660                                | 9500                                           | 1626                                 | 305                         | 
| 2010 | 6467                                | 8634                                           | 1716                                 | 218                         | 
| 2011 | 5966                                | 8184                                           | 1734                                 | 182                         | 
```