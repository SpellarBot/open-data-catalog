# Cable Complaints

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cable-complaints-90266) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/v2ei-xfce) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/v2ei-xfce/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/v2ei-xfce/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | v2ei-xfce |
| Name | Cable Complaints |
| Attribution | Montgomery County, MD |
| Category | Government |
| Tags | cable, complaints |
| Created | 2012-03-09T20:47:20Z |
| Publication Date | 2015-10-26T14:52:31Z |

## Description

All cable complaints filed with the Montgomery County Cable Office since January 2010. This data will be updated on a quarterly basis.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type     | Render Type   |
| ======== | ============== | ========================== | ========================== | ============= | ============= |
| Yes      | time           | date_of_complaint          | Date of Complaint          | calendar_date | calendar_date |
| No       |                | date_of_closure            | Date of Closure            | calendar_date | calendar_date |
| Yes      | series tag     | street                     | Street                     | text          | text          |
| Yes      | series tag     | city                       | City                       | text          | text          |
| Yes      | series tag     | state                      | State                      | text          | text          |
| Yes      | series tag     | zip                        | ZIP                        | text          | number        |
| Yes      | series tag     | cable_provider             | Cable Provider             | text          | text          |
| Yes      | numeric metric | billing                    | Billing                    | number        | number        |
| Yes      | numeric metric | service                    | Service                    | number        | number        |
| Yes      | numeric metric | internet                   | Internet                   | number        | number        |
| No       |                | telephone_answering_time   | Telephone Answering Time   | number        | number        |
| Yes      | numeric metric | reception                  | Reception                  | number        | number        |
| Yes      | numeric metric | construction               | Construction               | number        | number        |
| Yes      | numeric metric | marketing                  | Marketing                  | number        | number        |
| Yes      | numeric metric | installation               | Installation               | number        | number        |
| Yes      | numeric metric | cable_service_availability | Cable Service Availability | number        | number        |
| Yes      | numeric metric | cable_line_related         | Cable Line Related         | number        | number        |
| Yes      | numeric metric | telephone_service          | Telephone Service          | number        | number        |
| Yes      | numeric metric | other                      | Other                      | number        | number        |
| Yes      | series tag     | type                       | Type                       | text          | text          |
```

## Time Field

```ls
Value = date_of_complaint
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = date_of_closure,telephone_answering_time
```

## Data Commands

```ls
series e:v2ei-xfce d:2013-05-14T00:00:00.000Z t:cable_provider=Inquiry t:state=MD t:type=Complaint m:billing=1

series e:v2ei-xfce d:2014-08-06T00:00:00.000Z t:cable_provider=Comcast t:state=MD t:type=Complaint m:reception=1

series e:v2ei-xfce d:2014-12-01T00:00:00.000Z t:cable_provider=Inquiry t:state=MD t:type=Complaint m:billing=1
```

## Meta Commands

```ls
metric m:billing p:integer l:Billing d:"""1"" if the complaint involved a billing issue" t:dataTypeName=number

metric m:service p:integer l:Service d:"""1"" if the complaint involved a service issue" t:dataTypeName=number

metric m:internet p:integer l:Internet d:"""1"" if the complaint was related to Internet service" t:dataTypeName=number

metric m:reception p:integer l:Reception d:"""1"" if the complaint involved the signal quality (reception)" t:dataTypeName=number

metric m:construction p:integer l:Construction d:"""1"" if the complaint was related to construction" t:dataTypeName=number

metric m:marketing p:integer l:Marketing d:"""1"" if the complaint was related to marketing" t:dataTypeName=number

metric m:installation p:integer l:Installation d:"""1"" if the complaint was related to an installation issue" t:dataTypeName=number

metric m:cable_service_availability p:integer l:"Cable Service Availability" d:"""1"" if the complaint was related to lack of cable services available in the person's area" t:dataTypeName=number

metric m:cable_line_related p:integer l:"Cable Line Related" d:"""1"" if the complaint was related to the physical cable line" t:dataTypeName=number

metric m:telephone_service p:integer l:"Telephone Service" d:"""1"" if the complaint was related to telephone services from the cable provider" t:dataTypeName=number

metric m:other p:integer l:Other d:"""1"" if the complaint was related to an issue not captured by the previous columns in this table" t:dataTypeName=number

entity e:v2ei-xfce l:"Cable Complaints" t:attribution="Montgomery County, MD" t:url=https://data.montgomerycountymd.gov/api/views/v2ei-xfce

property e:v2ei-xfce t:meta.view v:id=v2ei-xfce v:category=Government v:averageRating=0 v:name="Cable Complaints" v:attribution="Montgomery County, MD"

property e:v2ei-xfce t:meta.view.license v:name="Public Domain"

property e:v2ei-xfce t:meta.view.owner v:id=rykt-6e5x v:profileImageUrlMedium=/api/users/rykt-6e5x/profile_images/THUMB v:profileImageUrlLarge=/api/users/rykt-6e5x/profile_images/LARGE v:screenName=Brian v:profileImageUrlSmall=/api/users/rykt-6e5x/profile_images/TINY v:displayName=Brian

property e:v2ei-xfce t:meta.view.tableauthor v:id=rykt-6e5x v:profileImageUrlMedium=/api/users/rykt-6e5x/profile_images/THUMB v:profileImageUrlLarge=/api/users/rykt-6e5x/profile_images/LARGE v:screenName=Brian v:profileImageUrlSmall=/api/users/rykt-6e5x/profile_images/TINY v:roleName=editor v:displayName=Brian
```

## Top Records

```ls
| date_of_complaint   | date_of_closure     | street      | city      | state | zip   | cable_provider | billing | service | internet | telephone_answering_time | reception | construction | marketing | installation | cable_service_availability | cable_line_related | telephone_service | other | type      | 
| =================== | =================== | =========== | ========= | ===== | ===== | ============== | ======= | ======= | ======== | ======================== | ========= | ============ | ========= | ============ | ========================== | ================== | ================= | ===== | ========= | 
| 2013-05-14T00:00:00 | 2013-05-14T00:00:00 |             |           | MD    |       | Inquiry        | 1       |         |          |                          |           |              |           |              |                            |                    |                   |       | Complaint | 
| 2014-08-06T00:00:00 | 2014-08-06T00:00:00 |             |           | MD    |       | Comcast        |         |         |          |                          | 1         |              |           |              |                            |                    |                   |       | Complaint | 
| 2014-12-01T00:00:00 | 2014-12-03T00:00:00 |             |           | MD    |       | Inquiry        | 1       |         |          |                          |           |              |           |              |                            |                    |                   |       | Complaint | 
| 2014-07-29T00:00:00 | 2014-07-29T00:00:00 |             |           | MD    |       | Comcast        |         |         |          |                          | 1         |              |           |              |                            |                    |                   |       | Complaint | 
| 2012-04-23T00:00:00 | 2012-04-17T00:00:00 | Ohara Place | Olney     | MD    | 20832 | Comcast        |         |         |          |                          |           | 1            |           |              |                            |                    |                   |       | Complaint | 
| 2014-07-17T00:00:00 | 2014-07-17T00:00:00 |             |           | MD    |       | Comcast        | 1       |         |          |                          |           |              |           |              |                            |                    |                   |       | Complaint | 
| 2013-03-22T00:00:00 | 2013-03-22T00:00:00 | Duke Street | Rockville | MD    | 20850 | Comcast        | 1       |         |          |                          |           |              |           |              |                            |                    |                   |       | Complaint | 
| 2014-07-22T00:00:00 | 2014-07-22T00:00:00 |             | Bethesda  | MD    |       | Inquiry        |         |         |          |                          | 1         |              |           |              |                            |                    |                   |       | Complaint | 
| 2015-06-12T00:00:00 | 2015-06-12T00:00:00 |             |           | MD    |       | Inquiry        |         |         |          |                          |           |              |           |              |                            |                    |                   | 1     | Complaint | 
| 2014-07-17T00:00:00 | 2014-07-17T00:00:00 |             |           | MD    |       | Inquiry        |         |         |          |                          |           |              |           |              |                            |                    |                   | 1     | Complaint | 
```