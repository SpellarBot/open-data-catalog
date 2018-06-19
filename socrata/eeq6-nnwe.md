# Solicitations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/solicitations) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/eeq6-nnwe) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/eeq6-nnwe/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/eeq6-nnwe/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | eeq6-nnwe |
| Name | Solicitations |
| Category | Government |
| Tags | business, contract, bid, solicitation |
| Created | 2015-12-08T23:15:05Z |
| Publication Date | 2016-01-07T14:08:34Z |

## Description

The dataset contains a listing of all active and closed Montgomery County solicitations issued in the past 7 years. Data Update Frequency : Daily.

## Columns

```ls
| Included | Schema Type | Field Name         | Name                      | Data Type     | Render Type   |
| ======== | =========== | ================== | ========================= | ============= | ============= |
| Yes      | series tag  | status             | Status                    | text          | text          |
| Yes      | series tag  | type               | Solicitation Type         | text          | text          |
| Yes      | series tag  | number             | Solicitation Number       | text          | text          |
| Yes      | series tag  | description        | Solicitation Title        | text          | text          |
| Yes      | time        | issuancedate       | Issuance Date             | calendar_date | calendar_date |
| No       |             | closingdate        | Closing Date              | calendar_date | calendar_date |
| Yes      | series tag  | cancelledpostponed | Cancelled or Postponed    | text          | text          |
| Yes      | series tag  | construction       | Construction Solicitation | text          | text          |
| Yes      | series tag  | lsbrpindicator     | LSBRP                     | text          | text          |
| Yes      | series tag  | buyer              | Buyer Name                | text          | text          |
| Yes      | series tag  | department         | Issuing Department        | text          | text          |
| Yes      | series tag  | deptcontact        | Department Contact        | text          | text          |
```

## Time Field

```ls
Value = issuancedate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = closingdate
```

## Data Commands

```ls
series e:eeq6-nnwe d:2010-07-27T00:00:00.000Z t:status=Closed t:description="Rehabilitation of Westbound Bridge No. M-0131-4 on East Gude Drive over the CSXT and WMATA" t:department="Department of Transportation" t:deptcontact="Aebig, Mark" t:buyer="Norris, Robert" t:number=0504530018 t:lsbrpindicator=N t:type=IFB t:construction=Y m:row_number.eeq6-nnwe=1

series e:eeq6-nnwe d:2011-08-16T00:00:00.000Z t:status=Closed t:description="Inmate Hanging Property Bag" t:department="Department of Correction & Rehabilitation" t:deptcontact="Bright-Davies, Jannie" t:buyer=-- t:number=1011556 t:lsbrpindicator=Y t:type=Informal t:construction=N m:row_number.eeq6-nnwe=2

series e:eeq6-nnwe d:2011-07-09T00:00:00.000Z t:status=Closed t:description="Physical Fitness Apparel" t:department="Fire & Rescue Services" t:deptcontact="Fornatora, Ron" t:buyer="Karakaya, Penny Perrus" t:number=1008089 t:lsbrpindicator=Y t:type=IFB t:construction=N m:row_number.eeq6-nnwe=3
```

## Meta Commands

```ls
metric m:row_number.eeq6-nnwe p:long l:"Row Number"

entity e:eeq6-nnwe l:Solicitations t:url=https://data.montgomerycountymd.gov/api/views/eeq6-nnwe

property e:eeq6-nnwe t:meta.view v:id=eeq6-nnwe v:category=Government v:averageRating=0 v:name=Solicitations

property e:eeq6-nnwe t:meta.view.owner v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"

property e:eeq6-nnwe t:meta.view.tableauthor v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:roleName=administrator v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"
```

## Top Records

```ls
| status | type     | number     | description                                                                                | issuancedate        | closingdate         | cancelledpostponed                  | construction | lsbrpindicator | buyer                         | department                                | deptcontact           | 
| ====== | ======== | ========== | ========================================================================================== | =================== | =================== | =================================== | ============ | ============== | ============================= | ========================================= | ===================== | 
| Closed | IFB      | 0504530018 | Rehabilitation of Westbound Bridge No. M-0131-4 on East Gude Drive over the CSXT and WMATA | 2010-07-27T00:00:00 | 2010-08-25T00:00:00 |                                     | Y            | N              | Norris, Robert                | Department of Transportation              | Aebig, Mark           | 
| Closed | Informal | 1011556    | Inmate Hanging Property Bag                                                                | 2011-08-16T00:00:00 | 2011-09-06T00:00:00 |                                     | N            | Y              | --                            | Department of Correction & Rehabilitation | Bright-Davies, Jannie | 
| Closed | IFB      | 1008089    | Physical Fitness Apparel                                                                   | 2011-07-09T00:00:00 | 2011-07-07T00:00:00 |                                     | N            | Y              | Karakaya, Penny Perrus        | Fire & Rescue Services                    | Fornatora, Ron        | 
| Closed | IFB      | 1029112    | Printing of Parking Ticket Books & Parking Garage Tickets                                  | 2013-10-30T00:00:00 | 2013-12-03T00:00:00 |                                     | N            | N              | Thomas, Michael               | Department of General Services            | Richard Taylor        | 
| Closed | RFP      | 1008446    | Time and Material HVAC Services                                                            | 2011-11-22T00:00:00 |                     | Cancelled or Indefinitely Postponed | N            | Y              | Harris, Eric                  | Department of General Services            | Herrmann, William     | 
| Closed | IFB      | 1018098    | Full Service and Pooled Preventive Maintenance of Mailroom Equipment                       | 2012-07-02T00:00:00 |                     | Cancelled or Indefinitely Postponed | N            | Y              | Stone, Noah (Inactive Buyer)  | Department of General Services            | Taylor, Richard       | 
| Closed | RFP      | 1000615    | Multilingual Health Navigation Line/Medical Interpretation                                 | 2010-10-15T00:00:00 |                     | Cancelled or Indefinitely Postponed | N            | N              | Gudeta, Mary (Inactive Buyer) | Department of Health & Human Svcs         | Martinez, Luis        | 
| Closed | Informal | 1042660    | Graphic Art and Design Services                                                            | 2014-07-11T00:00:00 | 2014-08-04T00:00:00 |                                     | N            | Y              | --                            | Department of Environmental Protection    | DEP Procurements      | 
| Closed | IFB      | 1035189    | Printing and Distribution of Recreation Guides                                             | 2013-12-12T00:00:00 | 2014-01-13T00:00:00 |                                     | N            | N              | Thomas, Michael               | Department of Recreation                  | Ginny Horvath         | 
| Closed | RFP      | 1038024    | Friendly Visitation                                                                        | 2014-04-08T00:00:00 | 2014-05-22T00:00:00 |                                     | N            | N              | Flood, Samuel                 | Department of Health & Human Svcs         | David Salem           | 
```