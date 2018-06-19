# Type & Number Of Allegation Complaints Received

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/type-number-of-allegation-complaints-received-6e3fb) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/ngf9-zejg) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/ngf9-zejg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/ngf9-zejg/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | ngf9-zejg |
| Name | Type & Number Of Allegation Complaints Received |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | City Government |
| Tags | ccrb, allegations, complaints, abuse, force, offensive language |
| Created | 2013-02-25T21:24:34Z |
| Publication Date | 2013-06-21T20:06:35Z |

## Description

This table represents the type of allegation and total number of allegations received for a particular type of complaint. Types of allegations and complaints are Force, Abuse of Authority, Discourtsey, Offensive Language.

## Columns

```ls
| Included | Schema Type | Field Name                | Name                        | Data Type | Render Type |
| ======== | =========== | ========================= | =========================== | ========= | =========== |
| Yes      | time        | year                      | Year                        | number    | text        |
| Yes      | series tag  | force_number              | Force (Number)              | text      | text        |
| Yes      | series tag  | force_type                | Force (Type)                | text      | text        |
| Yes      | series tag  | abuse_of_authority_number | Abuse of Authority (Number) | text      | text        |
| Yes      | series tag  | abuse_of_authority_type   | Abuse of Authority (Type)   | text      | text        |
| Yes      | series tag  | discourtsey_number        | Discourtsey (Number)        | text      | text        |
| Yes      | series tag  | discourtsey_type          | Discourtsey (Type)          | text      | text        |
| Yes      | series tag  | offensive_language_number | Offensive Language (Number) | text      | text        |
| Yes      | series tag  | offensive_language_type   | Offensive Language (Type)   | text      | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
```

## Meta Commands

```ls
entity e:ngf9-zejg l:"Type & Number Of Allegation Complaints Received" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/ngf9-zejg

property e:ngf9-zejg t:meta.view v:id=ngf9-zejg v:category="City Government" v:attributionLink=http://www.nyc.gov/html/ccrb/pdf/ccrbappendices2011.pdf v:averageRating=0 v:name="Type & Number Of Allegation Complaints Received" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:ngf9-zejg t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:ngf9-zejg t:meta.view.tableauthor v:id=iacr-duv5 v:screenName=Tejas.Patel v:displayName=Tejas.Patel
```

## Top Records

```ls
| year | force_number | force_type | abuse_of_authority_number | abuse_of_authority_type | discourtsey_number | discourtsey_type | offensive_language_number | offensive_language_type | 
| ==== | ============ | ========== | ========================= | ======================= | ================== | ================ | ========================= | ======================= | 
| 2009 | 6404         | 3984       | 10549                     | 4858                    | 3828               | 3172             | 589                       | 554                     | 
| 2010 | 5298         | 3225       | 8677                      | 3998                    | 3308               | 2698             | 514                       | 467                     | 
| 2011 | 5283         | 2903       | 8743                      | 3631                    | 3307               | 2561             | 534                       | 451                     | 
```