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
| Rows Updated | 2017-03-20T07:00:56Z |

## Description

Individual informal consumer complaint data detailing complaints filed with the Consumer Help Center beginning October 31, 2014. This data represents information selected by the consumer. The FCC does not verify the facts alleged in these complaints.

## Columns

```ls
| Included | Schema Type | Field Name                       | Name                       | Data Type     | Render Type   |
| ======== | =========== | ================================ | ========================== | ============= | ============= |
| No       |             | id                               | Ticket ID                  | text          | number        |
| Yes      | time        | ticket_created                   | Ticket Created             | date          | date          |
| No       |             | issue_date                       | Date of Issue              | calendar_date | calendar_date |
| Yes      | series tag  | issue_time                       | Time of Issue              | text          | text          |
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
Excluded Fields = id,issue_date
```

## Data Commands

```ls
series e:3xyp-aqkj d:2016-05-25T11:15:29.000Z t:zip=33324 t:issue_type=Phone t:issue_time="1:00 pm" t:issue=Robocalls t:state=FL t:type_of_call_or_messge="Autodialed Live Voice Call" t:method="Internet (VOIP)" t:caller_id_number=866-410-0458 t:city=Plantation m:row_number.3xyp-aqkj=1

series e:3xyp-aqkj d:2016-05-25T12:51:35.000Z t:zip=92078 t:issue_type=Phone t:issue_time="12:00 pm" t:issue="Telemarketing (including do not call and spoofing)" t:state=CA t:advertiser_business_phone_number=619-840-7262 t:type_of_call_or_messge="Live Voice" t:method=Wired t:caller_id_number=619-840-7262 t:city="San Marcos" m:row_number.3xyp-aqkj=2

series e:3xyp-aqkj d:2016-05-25T12:56:54.000Z t:zip=07481 t:issue_type=Phone t:issue_time="8:08 PM" t:issue="Telemarketing (including do not call and spoofing)" t:state=NJ t:advertiser_business_phone_number=626-691-9090 t:type_of_call_or_messge="Live Voice" t:method="Wireless (cell phone/other mobile device)" t:caller_id_number=626-691-9090 t:city=Wyckoff m:row_number.3xyp-aqkj=3
```

## Meta Commands

```ls
metric m:row_number.3xyp-aqkj p:long l:"Row Number"

entity e:3xyp-aqkj l:"CGB - Consumer Complaints Data" t:attribution="Federal Communications Commission: Consumer Inquiries and Complaints Division" t:url=https://opendata.fcc.gov/api/views/3xyp-aqkj

property e:3xyp-aqkj t:meta.view v:id=3xyp-aqkj v:category="Consumer and Government Affairs" v:attributionLink=https://consumercomplaints.fcc.gov/hc/en-us v:averageRating=0 v:name="CGB - Consumer Complaints Data" v:attribution="Federal Communications Commission: Consumer Inquiries and Complaints Division"

property e:3xyp-aqkj t:meta.view.license v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:3xyp-aqkj t:meta.view.owner v:id=3p4u-pzii v:profileImageUrlMedium=/api/users/3p4u-pzii/profile_images/THUMB v:profileImageUrlLarge=/api/users/3p4u-pzii/profile_images/LARGE v:screenName=Andrew v:profileImageUrlSmall=/api/users/3p4u-pzii/profile_images/TINY v:roleName=administrator v:displayName=Andrew

property e:3xyp-aqkj t:meta.view.tableauthor v:id=3p4u-pzii v:profileImageUrlMedium=/api/users/3p4u-pzii/profile_images/THUMB v:profileImageUrlLarge=/api/users/3p4u-pzii/profile_images/LARGE v:screenName=Andrew v:profileImageUrlSmall=/api/users/3p4u-pzii/profile_images/TINY v:roleName=administrator v:displayName=Andrew

property e:3xyp-aqkj t:meta.view.metadata.custom_fields.common_core v:Contact_Name="Andrew Nebus" v:Bureau_Code=356:00 v:Program_Code=000:000
```