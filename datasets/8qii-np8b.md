# PED_NewHousingPermitsIssuedDetail

## Dataset

* [Dataset URL](https://data.srcity.org/api/views/8qii-np8b/rows.json?accessType=DOWNLOAD)
* [Catalog URL](https://catalog.data.gov/dataset/ped-newhousingpermitsissueddetail)
* Id = 8qii-np8b
* Name = PED_NewHousingPermitsIssuedDetail
* Created = 2017-01-20T00:18:03Z
* Publication Date = 2017-01-20T00:33:04Z
* Rows Updated = 2017-02-03T18:52:46Z

## Description



## Columns

```ls
| Name                | Field Name          | Data Type     | Render Type   | Schema Type    | Included | 
| =================== | =================== | ============= | ============= | ============== | ======== | 
| PermitType          | permittype          | text          | text          | series tag     | Yes      | 
| HousingUnits        | housingunits        | number        | number        | numeric metric | Yes      | 
| SqrFt               | sqrft               | number        | number        | numeric metric | Yes      | 
| HousingImpactType   | housingimpacttype   | text          | text          | series tag     | Yes      | 
| HousingImpactReason | housingimpactreason | text          | text          | series tag     | Yes      | 
| RECORD_ID           | record_id           | text          | text          | series tag     | Yes      | 
| RECORD_TYPE         | record_type         | text          | text          | series tag     | Yes      | 
| DATE_OPENED         | date_opened         | calendar_date | calendar_date | time           | Yes      | 
| RECORD_TYPE_4LEVEL# | record_type_4level  | text          | text          | series tag     | Yes      | 
| STATUS              | status              | text          | text          | series tag     | Yes      | 
| HistoryStatus       | historystatus       | text          | text          | series tag     | Yes      | 
| HistoryStatusDate   | historystatusdate   | calendar_date | calendar_date |                | No       | 
```

## Time Field

```ls
Value = date_opened
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = historystatusdate
Annotation Fields = 
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

property e:8qii-np8b t:meta.view d:2017-03-03T14:36:15.528Z v:id=8qii-np8b v:averageRating=0 v:name=PED_NewHousingPermitsIssuedDetail

property e:8qii-np8b t:meta.view.owner d:2017-03-03T14:36:15.528Z v:id=v4p4-re39 v:screenName="OpenData, RO" v:roleName=administrator v:displayName="OpenData, RO"

property e:8qii-np8b t:meta.view.tableauthor d:2017-03-03T14:36:15.528Z v:id=v4p4-re39 v:screenName="OpenData, RO" v:roleName=administrator v:displayName="OpenData, RO"
```