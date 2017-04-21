# List Of Translation Services Provided At OATH

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/list-of-translation-services-provided-at-oath-68767) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/8n8g-m3vw) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/8n8g-m3vw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/8n8g-m3vw/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 8n8g-m3vw |
| Name | List Of Translation Services Provided At OATH |
| Attribution | Office of Administrative Trials and Hearings (OATH) |
| Category | City Government |
| Tags | oath, office of administrative trials and hearings, cases, translation, language |
| Created | 2013-03-06T15:42:29Z |
| Publication Date | 2013-06-21T20:09:00Z |

## Description

This is the list of Translation Services which are provided in different language at Office of Administrative Trials and Hearings

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | language    | Language   | text      | text        |
| Yes      | numeric metric | number      | Number     | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:8n8g-m3vw d:2013-03-06T07:42:30.000Z t:language=Spanish m:number=129

series e:8n8g-m3vw d:2013-03-06T07:42:30.000Z t:language=Urdu m:number=5

series e:8n8g-m3vw d:2013-03-06T07:42:30.000Z t:language=Arabic m:number=5
```

## Meta Commands

```ls
metric m:number p:integer l:Number t:dataTypeName=number

entity e:8n8g-m3vw l:"List Of Translation Services Provided At OATH" t:attribution="Office of Administrative Trials and Hearings (OATH)" t:url=https://data.cityofnewyork.us/api/views/8n8g-m3vw

property e:8n8g-m3vw t:meta.view v:id=8n8g-m3vw v:category="City Government" v:attributionLink=http://www.nyc.gov/html/oath/downloads/pdf/oath_stats/OATH.pdf v:averageRating=0 v:name="List Of Translation Services Provided At OATH" v:attribution="Office of Administrative Trials and Hearings (OATH)"

property e:8n8g-m3vw t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:8n8g-m3vw t:meta.view.tableauthor v:id=iacr-duv5 v:screenName=Tejas.Patel v:displayName=Tejas.Patel
```

## Top Records

```ls
| :updated_at | language  | number | 
| =========== | ========= | ====== | 
| 1362555750  | Spanish   | 129    | 
| 1362555750  | Urdu      | 5      | 
| 1362555750  | Arabic    | 5      | 
| 1362555750  | Mandarin  | 7      | 
| 1362555750  | Bengali   | 5      | 
| 1362555750  | Cantonese | 4      | 
```