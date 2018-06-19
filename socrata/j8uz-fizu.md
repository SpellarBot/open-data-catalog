# List Of Total Cases Filed At OATH

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/list-of-total-cases-filed-at-oath-13d59) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/j8uz-fizu) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/j8uz-fizu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/j8uz-fizu/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | j8uz-fizu |
| Name | List Of Total Cases Filed At OATH |
| Attribution | Office of Administrative Trials and Hearings (OATH) |
| Category | City Government |
| Tags | oath, office of administrative trials and hearings, cases |
| Created | 2013-03-06T15:37:54Z |
| Publication Date | 2013-06-21T20:08:23Z |

## Description

This is the list of total case count maintained annually which are filed at Office of Administrative Trials and Hearings

## Columns

```ls
| Included | Schema Type    | Field Name | Name      | Data Type | Render Type |
| ======== | ============== | ========== | ========= | ========= | =========== |
| Yes      | time           | year       | Year      | number    | text        |
| Yes      | numeric metric | july       | July      | number    | text        |
| Yes      | numeric metric | august     | August    | number    | text        |
| Yes      | numeric metric | september  | September | number    | text        |
| Yes      | numeric metric | october    | October   | number    | text        |
| Yes      | numeric metric | november   | November  | number    | text        |
| Yes      | numeric metric | december   | December  | number    | text        |
| Yes      | numeric metric | january    | January   | number    | text        |
| Yes      | numeric metric | february   | February  | number    | text        |
| Yes      | numeric metric | march      | March     | number    | text        |
| Yes      | numeric metric | april      | April     | number    | text        |
| Yes      | numeric metric | may        | May       | number    | text        |
| Yes      | numeric metric | june       | June      | number    | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:j8uz-fizu d:2011-01-01T00:00:00.000Z m:december=175 m:november=209 m:may=193 m:march=245 m:april=189 m:february=205 m:june=225 m:january=209 m:august=317 m:july=225 m:october=202 m:september=217

series e:j8uz-fizu d:2012-01-01T00:00:00.000Z m:december=157 m:november=137 m:may=201 m:march=203 m:april=201 m:february=138 m:june=165 m:january=167 m:august=159 m:july=159 m:october=175 m:september=168

series e:j8uz-fizu d:2013-01-01T00:00:00.000Z m:december=185 m:november=147 m:january=231 m:august=183 m:july=170 m:october=255 m:september=140
```

## Meta Commands

```ls
metric m:july p:integer l:July t:dataTypeName=number

metric m:august p:integer l:August t:dataTypeName=number

metric m:september p:integer l:September t:dataTypeName=number

metric m:october p:integer l:October t:dataTypeName=number

metric m:november p:integer l:November t:dataTypeName=number

metric m:december p:integer l:December t:dataTypeName=number

metric m:january p:integer l:January t:dataTypeName=number

metric m:february p:integer l:February t:dataTypeName=number

metric m:march p:integer l:March t:dataTypeName=number

metric m:april p:integer l:April t:dataTypeName=number

metric m:may p:integer l:May t:dataTypeName=number

metric m:june p:integer l:June t:dataTypeName=number

entity e:j8uz-fizu l:"List Of Total Cases Filed At OATH" t:attribution="Office of Administrative Trials and Hearings (OATH)" t:url=https://data.cityofnewyork.us/api/views/j8uz-fizu

property e:j8uz-fizu t:meta.view v:id=j8uz-fizu v:category="City Government" v:attributionLink=http://www.nyc.gov/html/oath/downloads/pdf/oath_stats/OATH.pdf v:averageRating=0 v:name="List Of Total Cases Filed At OATH" v:attribution="Office of Administrative Trials and Hearings (OATH)"

property e:j8uz-fizu t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:j8uz-fizu t:meta.view.tableauthor v:id=iacr-duv5 v:screenName=Tejas.Patel v:displayName=Tejas.Patel
```

## Top Records

```ls
| year | july | august | september | october | november | december | january | february | march | april | may | june | 
| ==== | ==== | ====== | ========= | ======= | ======== | ======== | ======= | ======== | ===== | ===== | === | ==== | 
| 2011 | 225  | 317    | 217       | 202     | 209      | 175      | 209     | 205      | 245   | 189   | 193 | 225  | 
| 2012 | 159  | 159    | 168       | 175     | 137      | 157      | 167     | 138      | 203   | 201   | 201 | 165  | 
| 2013 | 170  | 183    | 140       | 255     | 147      | 185      | 231     |          |       |       |     |      | 
```