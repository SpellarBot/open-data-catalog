# Pesticides news archives

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/pesticides-news-archives-c57b2) |
| Metadata | [Link](https://data.oregon.gov/api/views/m4ku-rg94) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/m4ku-rg94/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/m4ku-rg94/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | m4ku-rg94 |
| Name | Pesticides news archives |
| Category | Natural Resources |
| Tags | pesticides |
| Created | 2014-05-01T19:14:20Z |
| Publication Date | 2016-06-16T23:04:01Z |

## Columns

```ls
| Included | Schema Type | Field Name            | Name                  | Data Type     | Render Type   |
| ======== | =========== | ===================== | ===================== | ============= | ============= |
| Yes      | time        | date                  | Date                  | calendar_date | calendar_date |
| Yes      | series tag  | name                  | Name                  | text          | text          |
| Yes      | series tag  | document              | Document              | document      | document      |
| Yes      | series tag  | additional_document_1 | Additional Document 1 | document      | document      |
| Yes      | series tag  | additional_document_2 | Additional Document 2 | document      | document      |
| Yes      | series tag  | additional_document_3 | Additional Document 3 | document      | document      |
| Yes      | series tag  | additional_document_4 | Additional Document 4 | document      | document      |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:m4ku-rg94 d:2012-07-12T00:00:00.000Z t:document.filename=Thionex.pdf t:document.content_type="application/pdf; charset=binary" t:name="Thionex Advisory" t:document.size=53145 t:document.file_id=3i0aV2CUwN7SmbLsbXYKdvlnCCF7joJIjsBsoZwKWLA m:row_number.m4ku-rg94=1

series e:m4ku-rg94 d:2011-09-27T00:00:00.000Z t:document.filename="Metam Sodium.pdf" t:document.content_type="application/pdf; charset=binary" t:name="Pesticide Advisory ? Metam Sodium, Metam Potassium & Dazomet are now Restricted Use Pesticides (RUP)" t:document.size=39953 t:document.file_id=Qse0bnjNSd5w8UmhX22Lln0LDE2EEVWsEtIMwskiG-Q m:row_number.m4ku-rg94=2

series e:m4ku-rg94 d:2011-08-19T00:00:00.000Z t:document.filename="Imprelis Herbicide.pdf" t:document.content_type="application/pdf; charset=binary" t:name="Imprelis Herbicide Stop Sale Order and Composting Restriction" t:document.size=48884 t:document.file_id=bfhHuhfP8lRbeFry6Y6SV-lpOZCFUIjmIurrDZMQ3Dw m:row_number.m4ku-rg94=3
```

## Meta Commands

```ls
metric m:row_number.m4ku-rg94 p:long l:"Row Number"

entity e:m4ku-rg94 l:"Pesticides news archives" t:url=https://data.oregon.gov/api/views/m4ku-rg94

property e:m4ku-rg94 t:meta.view v:id=m4ku-rg94 v:category="Natural Resources" v:averageRating=0 v:name="Pesticides news archives"

property e:m4ku-rg94 t:meta.view.owner v:id=xzpq-yk3z v:screenName="Andy Zimmerman" v:displayName="Andy Zimmerman"

property e:m4ku-rg94 t:meta.view.tableauthor v:id=xzpq-yk3z v:screenName="Andy Zimmerman" v:roleName=editor v:displayName="Andy Zimmerman"
```

## Top Records

```ls
| date                | name                                                                                                 | document                                                                                                           | additional_document_1    | additional_document_2    | additional_document_3    | additional_document_4    | 
| =================== | ==================================================================================================== | ================================================================================================================== | ======================== | ======================== | ======================== | ======================== | 
| 2012-07-12T00:00:00 | Thionex Advisory                                                                                     | [application/pdf; charset=binary, 3i0aV2CUwN7SmbLsbXYKdvlnCCF7joJIjsBsoZwKWLA, Thionex.pdf, 53145]                 | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | 
| 2011-09-27T00:00:00 | Pesticide Advisory ? Metam Sodium, Metam Potassium & Dazomet are now Restricted Use Pesticides (RUP) | [application/pdf; charset=binary, Qse0bnjNSd5w8UmhX22Lln0LDE2EEVWsEtIMwskiG-Q, Metam Sodium.pdf, 39953]            | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | 
| 2011-08-19T00:00:00 | Imprelis Herbicide Stop Sale Order and Composting Restriction                                        | [application/pdf; charset=binary, bfhHuhfP8lRbeFry6Y6SV-lpOZCFUIjmIurrDZMQ3Dw, Imprelis Herbicide.pdf, 48884]      | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | 
| 2011-08-03T00:00:00 | Regulations Change for Mini-Bulks                                                                    | [application/pdf; charset=binary, 8wcihRMX6rd-0SxSEt9b8ih4nW0rz8TenpGpsaT63qo, Mini-Bulks.pdf, 34857]              | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | 
| 2011-07-15T00:00:00 | The Purchase of RUP is Category Specific                                                             | [application/pdf; charset=binary, YW6IRU24tz0Orer4USOTtnva4ApTN5XcR2IN6dBgTCI, RUP Purchase.pdf, 35686]            | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | 
| 2011-06-24T00:00:00 | Oregon Water Quality Pesticide Management Plan Approved                                              | [application/pdf; charset=binary, NkITfYbl-j1TVp3ck0cI4sTFICh1il3-YdJ7H6q3ahw, OWQ Pesticide Plan.pdf, 36360]      | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | 
| 2011-06-10T00:00:00 | What Category for Fruit Trees in Landscape Settings                                                  | [application/pdf; charset=binary, BQpk2Sho2qcdw2ao3oTYNejBf7y4T5h2j-KDPCqjDYo, Fruit Trees Category.pdf, 34924]    | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | 
| 2011-06-07T00:00:00 | Changes to Directly Supervised Trainee Testing                                                       | [application/pdf; charset=binary, 2MQoZOBTS_A_7DDDAwo_aTUJrSRqLlf25mDSY3jgmSQ, Trainee Testing Changes.pdf, 36522] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | 
| 2011-05-06T00:00:00 | New Computer-Based Testing Now Available                                                             | [application/pdf; charset=binary, bWpD5OctxJSaZ2GBHKsd6Knt7ZhW47yULTLgHMqC-mU, Computer-Based Testing.pdf, 52754]  | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | 
| 2011-04-26T00:00:00 | Compliance Tips When "Going Green"                                                                   | [application/pdf; charset=binary, 9JqP1xlWJnnazyqdUwajc1llCYUGnGul2ltt04-_uYY, Going Green.pdf, 40473]             | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | [null, null, null, null] | 
```