# Marketplace-events

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/marketplace-events) |
| Metadata | [Link](https://data.oregon.gov/api/views/y9z5-dqiu) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/y9z5-dqiu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/y9z5-dqiu/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | y9z5-dqiu |
| Name | Marketplace-events |
| Attribution | Oregon Health Insurance Marketplace |
| Category | Health & Human Services |
| Tags | healthcare education, insurance information, enrollment events, health insurance, open enrollment |
| Created | 2016-11-14T16:48:25Z |
| Publication Date | 2016-11-14T16:54:45Z |

## Description

Events and meetings for Oregon Health Insurance Marketplace.

## Columns

```ls
| Included | Schema Type | Field Name  | Name        | Data Type     | Render Type   |
| ======== | =========== | =========== | =========== | ============= | ============= |
| Yes      | time        | date        | Date        | calendar_date | calendar_date |
| Yes      | series tag  | event       | Event       | text          | text          |
| Yes      | series tag  | time        | Time        | text          | text          |
| Yes      | series tag  | location    | Location    | text          | text          |
| Yes      | series tag  | description | Description | text          | text          |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:y9z5-dqiu d:2016-11-05T00:00:00.000Z t:time="10 a.m. ? 3 p.m." t:location="Chemeketa Community College, 120 E. Lincoln St., Woodburn, OR 97071" t:description="OHA enrollment event. Assistance will be available in English, Spanish, and Russian. For more information, contact Federico Corzo at 503-949-8684 or Federico_corzo@aol.com" t:event="Woodburn Enrollment Event" m:row_number.y9z5-dqiu=1

series e:y9z5-dqiu d:2016-11-12T00:00:00.000Z t:time="10 a.m. ? 3 p.m." t:location="Salem Hospital, Building D, 890 Oak St SE, Salem, OR 97301. First Floor- Main Lobby" t:description="OHA enrollment event. Assistance will be available in English, Spanish, and Russian. For more information, contact Federico Corzo at 503-949-8684 or Federico_corzo@aol.com" t:event="Salem Enrollment Event" m:row_number.y9z5-dqiu=2

series e:y9z5-dqiu d:2016-11-19T00:00:00.000Z t:time="9 a.m. ? 1 p.m." t:location="Silverton Hospital, 342 Fairview St, Silverton, OR. Conference rooms D & E" t:description="OHA enrollment event. Assistance will be available in English and Spanish. For more information, contact Emily Hanson at 503-873-1650 or ehanson@silvertonhealth.org" t:event="Silverton Enrollment Event" m:row_number.y9z5-dqiu=3
```

## Meta Commands

```ls
metric m:row_number.y9z5-dqiu p:long l:"Row Number"

entity e:y9z5-dqiu l:Marketplace-events t:attribution="Oregon Health Insurance Marketplace" t:url=https://data.oregon.gov/api/views/y9z5-dqiu

property e:y9z5-dqiu t:meta.view v:id=y9z5-dqiu v:category="Health & Human Services" v:attributionLink=http://oregonhealthcare.gov/ v:averageRating=0 v:name=Marketplace-events v:attribution="Oregon Health Insurance Marketplace"

property e:y9z5-dqiu t:meta.view.owner v:id=hs3b-mjjg v:screenName="Angela Van Grunsven" v:displayName="Angela Van Grunsven"

property e:y9z5-dqiu t:meta.view.tableauthor v:id=hs3b-mjjg v:screenName="Angela Van Grunsven" v:roleName=editor v:displayName="Angela Van Grunsven"
```

## Top Records

```ls
| date                | event                                   | time             | location                                                                             | description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | 
| =================== | ======================================= | ================ | ==================================================================================== | ================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================= | 
| 2016-11-05T00:00:00 | Woodburn Enrollment Event               | 10 a.m. ? 3 p.m. | Chemeketa Community College, 120 E. Lincoln St., Woodburn, OR 97071                  | OHA enrollment event. Assistance will be available in English, Spanish, and Russian. For more information, contact Federico Corzo at 503-949-8684 or Federico_corzo@aol.com                                                                                                                                                                                                                                                                                                                                       | 
| 2016-11-12T00:00:00 | Salem Enrollment Event                  | 10 a.m. ? 3 p.m. | Salem Hospital, Building D, 890 Oak St SE, Salem, OR 97301. First Floor- Main Lobby  | OHA enrollment event. Assistance will be available in English, Spanish, and Russian. For more information, contact Federico Corzo at 503-949-8684 or Federico_corzo@aol.com                                                                                                                                                                                                                                                                                                                                       | 
| 2016-11-19T00:00:00 | Silverton Enrollment Event              | 9 a.m. ? 1 p.m.  | Silverton Hospital, 342 Fairview St, Silverton, OR. Conference rooms D & E           | OHA enrollment event. Assistance will be available in English and Spanish. For more information, contact Emily Hanson at 503-873-1650 or ehanson@silvertonhealth.org                                                                                                                                                                                                                                                                                                                                              | 
| 2016-11-08T00:00:00 | Health Insurance 101 Town Hall          | 2 - 4 p.m.       | Blue Mountain Community College, 2411 NW Carden Ave, Pendleton, Morrow Hall Room 208 | We invite you to a state-sponsored, FREE and unbiased "Health Insurance 101" town hall meeting where we will ease the confusion about what health insurance really is and the options for Oregonians, discuss the myths of health insurance and the Affordable Care Act, go over the ?rules? of health insurance, and provide answers to questions about health insurance in Oregon. Space is limited, so please register by emailing info.marketplace@oregon.gov or calling 855-268-3767 to guarantee your spot! | 
| 2016-11-08T00:00:00 | Health & Resource Fair/Enrollment Event | 2 - 4 p.m.       | Blue Mountain Community College, 2411 NW Carden Ave, Pendleton, Morrow Hall Room 208 | Health & Resource Fair and Health Insurance Enrollment Event to learn about local resources and sign up for health coverage through the Marketplace or the Oregon Health Plan. Free in-person assistance will be available to assist in the application process.                                                                                                                                                                                                                                                  | 
| 2016-11-12T00:00:00 | Portland Open Enrollment Event          | 1:15 ? 4 p.m.    | Maranatha Church, Portland, OR 97211                                                 | Open enrollment event. Contact Dolly England 503-896-5684 DollyEngland@gmail.com for more information                                                                                                                                                                                                                                                                                                                                                                                                             | 
| 2016-11-19T00:00:00 | Portland Open Enrollment Event          | 10 a.m. ? 2 p.m. | East Portland Community Center, 740 SE 106th Ave.,Portland, OR 97216                 | Open enrollment event. Contact Tina Kennedy 503-686-8663 for more information                                                                                                                                                                                                                                                                                                                                                                                                                                     | 
| 2016-11-01T00:00:00 | COFA OHA Enrollment Event               | Noon ? 6 p.m.    | Labor & Industries Building, Conference room F, 350 Winter St. N.E., Salem, OR 97301 | COFA Premium Assistance Program enrollment event. Language assistance will be available. For more information, contact Jackie Leung, CANN 626-848-8616                                                                                                                                                                                                                                                                                                                                                            | 
| 2016-11-03T00:00:00 | COFA OHA Enrollment Event               | Noon ? 6 p.m.    | Northwest Family Services, 6200 SE Kind Rd.,Portland, OR 97222                       | COFA OHA enrollment event. Language assistance will be available. For more information, contact David Anitok, CANN 503-428-2611 or Zuri Lopez 503-546-6377                                                                                                                                                                                                                                                                                                                                                        | 
| 2016-11-12T00:00:00 | COFA OHA Enrollment Event               | Noon ? 5 p.m.    | Albany Public Library, 2450 14th Ave S.E., Albany OR 97322                           | COFA Premium Assistance Program enrollment event. Language assistance will be available. For more information, contact David Anitok, CANN 503-428-2611                                                                                                                                                                                                                                                                                                                                                            | 
```