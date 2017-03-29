# PED_NewHousingPermitsIssuedDetail

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ped-newhousingpermitsissueddetail) |
| Metadata | [Link](https://data.srcity.org/api/views/8qii-np8b) |
| Data: JSON | [100 Rows](https://data.srcity.org/api/views/8qii-np8b/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.srcity.org/api/views/8qii-np8b/rows.csv?max_rows=100) |
| Host | data.srcity.org |
| Id | 8qii-np8b |
| Name | PED_NewHousingPermitsIssuedDetail |
| Created | 2017-01-20T00:18:03Z |
| Publication Date | 2017-01-20T00:33:04Z |

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type     | Render Type   |
| ======== | ============== | =================== | =================== | ============= | ============= |
| Yes      | series tag     | permittype          | PermitType          | text          | text          |
| Yes      | numeric metric | housingunits        | HousingUnits        | number        | number        |
| Yes      | numeric metric | sqrft               | SqrFt               | number        | number        |
| Yes      | series tag     | housingimpacttype   | HousingImpactType   | text          | text          |
| Yes      | series tag     | housingimpactreason | HousingImpactReason | text          | text          |
| Yes      | series tag     | record_id           | RECORD_ID           | text          | text          |
| Yes      | series tag     | record_type         | RECORD_TYPE         | text          | text          |
| Yes      | time           | date_opened         | DATE_OPENED         | calendar_date | calendar_date |
| Yes      | series tag     | record_type_4level  | RECORD_TYPE_4LEVEL# | text          | text          |
| Yes      | series tag     | status              | STATUS              | text          | text          |
| Yes      | series tag     | historystatus       | HistoryStatus       | text          | text          |
| No       |                | historystatusdate   | HistoryStatusDate   | calendar_date | calendar_date |
```

## Time Field

```ls
Value = date_opened
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = historystatusdate
```

## Data Commands

```ls
series e:8qii-np8b d:2013-12-19T00:00:00.000Z t:status=Issued t:record_type="Residential New" t:permittype="Custom SFD" t:record_type_4level=Building/Residential/New/NA t:historystatus=Issued t:record_id=B13-5120 m:housingunits=1 m:sqrft=2309

series e:8qii-np8b d:2013-12-19T00:00:00.000Z t:status=Issued t:record_type="Residential New" t:permittype="Second Dwelling Unit" t:record_type_4level=Building/Residential/New/NA t:historystatus=Issued t:record_id=B13-5121 m:housingunits=1 m:sqrft=1463

series e:8qii-np8b d:2013-12-24T00:00:00.000Z t:housingimpactreason=SALE t:status=Finaled t:record_type="Residential New" t:permittype="Single Family Dwelling per MP" t:record_type_4level=Building/Residential/New/NA t:historystatus=Issued t:record_id=B13-5189 m:housingunits=1 m:sqrft=1708
```

## Meta Commands

```ls
metric m:housingunits p:integer l:HousingUnits t:dataTypeName=number

metric m:sqrft p:integer l:SqrFt t:dataTypeName=number

entity e:8qii-np8b l:PED_NewHousingPermitsIssuedDetail t:url=https://data.srcity.org/api/views/8qii-np8b

property e:8qii-np8b t:meta.view v:id=8qii-np8b v:averageRating=0 v:name=PED_NewHousingPermitsIssuedDetail

property e:8qii-np8b t:meta.view.owner v:id=v4p4-re39 v:screenName="OpenData, RO" v:displayName="OpenData, RO"

property e:8qii-np8b t:meta.view.tableauthor v:id=v4p4-re39 v:screenName="OpenData, RO" v:roleName=administrator v:displayName="OpenData, RO"
```

## Top Records

```ls
| permittype                                  | housingunits | sqrft | housingimpacttype | housingimpactreason | record_id | record_type     | date_opened         | record_type_4level          | status  | historystatus | historystatusdate   | 
| =========================================== | ============ | ===== | ================= | =================== | ========= | =============== | =================== | =========================== | ======= | ============= | =================== | 
| Custom SFD                                  | 1            | 2309  |                   |                     | B13-5120  | Residential New | 2013-12-19T00:00:00 | Building/Residential/New/NA | Issued  | Issued        | 2015-07-27T00:00:00 | 
| Second Dwelling Unit                        | 1            | 1463  |                   |                     | B13-5121  | Residential New | 2013-12-19T00:00:00 | Building/Residential/New/NA | Issued  | Issued        | 2015-07-27T00:00:00 | 
| Single Family Dwelling per MP               | 1            | 1708  |                   | SALE                | B13-5189  | Residential New | 2013-12-24T00:00:00 | Building/Residential/New/NA | Finaled | Issued        | 2015-08-12T00:00:00 | 
| Single Family Dwelling per MP               | 1            | 1936  |                   | SALE                | B13-5190  | Residential New | 2013-12-24T00:00:00 | Building/Residential/New/NA | Finaled | Issued        | 2015-08-12T00:00:00 | 
| Single Family Dwelling per MP               | 1            | 3052  |                   | SALE                | B13-5193  | Residential New | 2013-12-24T00:00:00 | Building/Residential/New/NA | Finaled | Issued        | 2015-08-12T00:00:00 | 
| Single Family Dwelling per MP               | 1            | 2896  |                   | SALE                | B13-5198  | Residential New | 2013-12-24T00:00:00 | Building/Residential/New/NA | Finaled | Issued        | 2015-07-28T00:00:00 | 
| Single Family Dwelling per MP               | 1            | 2572  |                   | SALE                | B13-5208  | Residential New | 2013-12-24T00:00:00 | Building/Residential/New/NA | Finaled | Issued        | 2015-07-28T00:00:00 | 
| Single Family Dwelling per MP               | 1            | 3052  |                   | SALE                | B13-5214  | Residential New | 2013-12-24T00:00:00 | Building/Residential/New/NA | Finaled | Issued        | 2015-07-28T00:00:00 | 
| Custom SFD                                  | 1            | 2922  |                   | RENT                | B14-2547  | Residential New | 2014-06-30T00:00:00 | Building/Residential/New/NA | Issued  | Issued        | 2015-12-08T00:00:00 | 
| Single Family Dwelling per MP with 2nd Unit | 2            | 2723  |                   | SALE                | B14-2792  | Residential New | 2014-07-17T00:00:00 | Building/Residential/New/NA | Finaled | Issued        | 2016-01-26T00:00:00 | 
```