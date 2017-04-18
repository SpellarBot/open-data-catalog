# CGB - Consumer Complaints Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cgb-consumer-complaints-data) |
| Metadata | [Link](https://opendata.fcc.gov/api/views/3xyp-aqkj) |
| Data: JSON | [100 Rows](https://opendata.fcc.gov/api/views/3xyp-aqkj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://opendata.fcc.gov/api/views/3xyp-aqkj/rows.csv?max_rows=100) |
| Host | opendata.fcc.gov |
| Id | 3xyp-aqkj |
| Name | CGB - Consumer Complaints Data |
| Attribution | Federal Communications Commission: Consumer Inquiries and Complaints Division |
| Category | Consumer and Government Affairs |
| Tags | fcc consumer inquiry, fcc consumer complaints, fcc |
| Created | 2016-03-07T23:15:08Z |
| Publication Date | 2017-03-02T21:24:52Z |

## Description

Individual informal consumer complaint data detailing complaints filed with the Consumer Help Center beginning October 31, 2014. This data represents information selected by the consumer. The FCC does not verify the facts alleged in these complaints.

## Columns

```ls
| Included | Schema Type | Field Name                       | Name                       | Data Type     | Render Type   |
| ======== | =========== | ================================ | ========================== | ============= | ============= |
| No       |             | id                               | Ticket ID                  | text          | number        |
| Yes      | time        | ticket_created                   | Ticket Created             | date          | date          |
| No       |             | issue_date                       | Date of Issue              | calendar_date | calendar_date |
| No       |             | issue_time                       | Time of Issue              | text          | text          |
| Yes      | series tag  | issue_type                       | Form                       | text          | text          |
| Yes      | series tag  | method                           | Method                     | text          | text          |
| Yes      | series tag  | issue                            | Issue                      | text          | text          |
| Yes      | series tag  | caller_id_number                 | Caller ID Number           | text          | text          |
| Yes      | series tag  | type_of_call_or_messge           | Type of Call or Messge     | text          | text          |
| Yes      | series tag  | advertiser_business_phone_number | Advertiser Business Number | text          | text          |
| Yes      | series tag  | city                             | City                       | text          | text          |
| Yes      | series tag  | state                            | State                      | text          | text          |
| Yes      | series tag  | zip                              | Zip                        | text          | text          |
```

## Time Field

```ls
Value = ticket_created
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = id,issue_date,issue_time
```

## Data Commands

```ls
series e:3xyp-aqkj d:2016-05-25T11:15:29.000Z t:zip=33324 t:issue_type=Phone t:issue=Robocalls t:state=FL t:type_of_call_or_messge="Autodialed Live Voice Call" t:method="Internet (VOIP)" t:caller_id_number=866-410-0458 t:city=Plantation m:row_number.3xyp-aqkj=1

series e:3xyp-aqkj d:2016-05-25T12:51:35.000Z t:zip=92078 t:issue_type=Phone t:issue="Telemarketing (including do not call and spoofing)" t:state=CA t:advertiser_business_phone_number=619-840-7262 t:type_of_call_or_messge="Live Voice" t:method=Wired t:caller_id_number=619-840-7262 t:city="San Marcos" m:row_number.3xyp-aqkj=2

series e:3xyp-aqkj d:2016-05-25T12:56:54.000Z t:zip=07481 t:issue_type=Phone t:issue="Telemarketing (including do not call and spoofing)" t:state=NJ t:advertiser_business_phone_number=626-691-9090 t:type_of_call_or_messge="Live Voice" t:method="Wireless (cell phone/other mobile device)" t:caller_id_number=626-691-9090 t:city=Wyckoff m:row_number.3xyp-aqkj=3
```

## Meta Commands

```ls
metric m:row_number.3xyp-aqkj p:long l:"Row Number"

entity e:3xyp-aqkj l:"CGB - Consumer Complaints Data" t:attribution="Federal Communications Commission: Consumer Inquiries and Complaints Division" t:url=https://opendata.fcc.gov/api/views/3xyp-aqkj

property e:3xyp-aqkj t:meta.view v:id=3xyp-aqkj v:category="Consumer and Government Affairs" v:attributionLink=https://consumercomplaints.fcc.gov/hc/en-us v:averageRating=0 v:name="CGB - Consumer Complaints Data" v:attribution="Federal Communications Commission: Consumer Inquiries and Complaints Division"

property e:3xyp-aqkj t:meta.view.license v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:3xyp-aqkj t:meta.view.owner v:id=3p4u-pzii v:profileImageUrlMedium=/api/users/3p4u-pzii/profile_images/THUMB v:profileImageUrlLarge=/api/users/3p4u-pzii/profile_images/LARGE v:screenName=Andrew v:profileImageUrlSmall=/api/users/3p4u-pzii/profile_images/TINY v:lastNotificationSeenAt=1491330879 v:displayName=Andrew

property e:3xyp-aqkj t:meta.view.tableauthor v:id=3p4u-pzii v:profileImageUrlMedium=/api/users/3p4u-pzii/profile_images/THUMB v:profileImageUrlLarge=/api/users/3p4u-pzii/profile_images/LARGE v:screenName=Andrew v:profileImageUrlSmall=/api/users/3p4u-pzii/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1491330879 v:displayName=Andrew

property e:3xyp-aqkj t:meta.view.metadata.custom_fields.common_core v:Contact_Name="Andrew Nebus" v:Bureau_Code=356:00 v:Program_Code=000:000
```

## Top Records

```ls
| id      | ticket_created | issue_date          | issue_time | issue_type | method                                    | issue                                              | caller_id_number | type_of_call_or_messge     | advertiser_business_phone_number | city                | state | zip   | 
| ======= | ============== | =================== | ========== | ========== | ========================================= | ================================================== | ================ | ========================== | ================================ | =================== | ===== | ===== | 
| 1000296 | 1464174929     | 2016-05-01T00:00:00 | 1:00 pm    | Phone      | Internet (VOIP)                           | Robocalls                                          | 866-410-0458     | Autodialed Live Voice Call |                                  | Plantation          | FL    | 33324 | 
| 1000319 | 1464180695     | 2016-03-07T00:00:00 | 12:00 pm   | Phone      | Wired                                     | Telemarketing (including do not call and spoofing) | 619-840-7262     | Live Voice                 | 619-840-7262                     | San Marcos          | CA    | 92078 | 
| 1000322 | 1464181014     | 2016-05-24T00:00:00 | 8:08 PM    | Phone      | Wireless (cell phone/other mobile device) | Telemarketing (including do not call and spoofing) | 626-691-9090     | Live Voice                 | 626-691-9090                     | Wyckoff             | NJ    | 07481 | 
| 1000323 | 1464181222     | 2016-03-07T00:00:00 |            | Phone      | Wired                                     | Telemarketing (including do not call and spoofing) | 877-218-8361     | Abandoned Calls            |                                  | Hopkington          | MA    | 01748 | 
| 1000326 | 1464181351     | 2016-05-25T00:00:00 | 7:24 PM    | Phone      | Internet (VOIP)                           | Telemarketing (including do not call and spoofing) | 877-705-6767     | Abandoned Calls            |                                  | Aurora              | IL    | 60504 | 
| 1000328 | 1464181397     | 2016-05-25T00:00:00 | 7:00 am    | Phone      | Internet (VOIP)                           | Telemarketing (including do not call and spoofing) | 541-826-3147     | Live Voice                 |                                  | Watertown           | NY    | 13601 | 
| 1000330 | 1464181806     | 2016-03-14T00:00:00 | 11:00 am   | Phone      | Wired                                     | Telemarketing (including do not call and spoofing) | 484-938-8231     | Live Voice                 | 484-938-8231                     | Allentown           | PA    | 18104 | 
| 1000332 | 1464182174     | 2016-03-14T00:00:00 | 11:00 am   | Phone      | Wired                                     | Telemarketing (including do not call and spoofing) | 601-553-0515     |                            |                                  | Meridian            | MS    | 39301 | 
| 1000335 | 1464182705     | 2016-05-24T00:00:00 | 2:30 p.m.  | Phone      | Wired                                     | Robocalls                                          | 763-307-5755     | Abandoned Calls            |                                  | Hot Springs Village | AR    | 71909 | 
| 1000336 | 1464183002     | 2016-03-14T00:00:00 | 2:30 pm    | Phone      | Wired                                     | Telemarketing (including do not call and spoofing) | 818-666-4016     |                            |                                  | Irvine              | CA    | 92620 | 
```