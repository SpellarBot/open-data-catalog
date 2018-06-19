# Report Card 3a Resident Sentiment Benefits

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/report-card-3a-resident-sentiment-benefits-28da4) |
| Metadata | [Link](https://data.hawaii.gov/api/views/i58n-7utq) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/i58n-7utq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/i58n-7utq/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | i58n-7utq |
| Name | Report Card 3a Resident Sentiment Benefits |
| Created | 2012-11-19T01:22:55Z |
| Publication Date | 2012-11-19T01:23:29Z |

## Columns

```ls
| Included | Schema Type    | Field Name         | Name                 | Data Type | Render Type |
| ======== | ============== | ================== | ==================== | ========= | =========== |
| Yes      | time           | year               | Year                 | number    | text        |
| Yes      | numeric metric | oahu               | Oahu                 | number    | number      |
| Yes      | numeric metric | maui               | Maui                 | number    | number      |
| Yes      | numeric metric | molokai            | Molokai              | number    | number      |
| Yes      | numeric metric | lanai              | Lanai                | number    | number      |
| Yes      | numeric metric | kauai              | Kauai                | number    | number      |
| Yes      | numeric metric | hawaii_island_kona | Hawaii Island (Kona) | number    | number      |
| Yes      | numeric metric | hawaii_island_hilo | Hawaii Island (Hilo) | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:i58n-7utq d:2005-01-01T00:00:00.000Z m:kauai=0.6969035836600667 m:maui=0.7408955066233577 m:hawaii_island_hilo=0.6523465983093297 m:hawaii_island_kona=0.5984670303324121 m:molokai=0.5722932380675924 m:oahu=0.7176930163241899 m:lanai=0.5737148093548071

series e:i58n-7utq d:2006-01-01T00:00:00.000Z m:kauai=0.6303019931510752 m:maui=0.675469194713893 m:hawaii_island_hilo=0.7019142107668879 m:hawaii_island_kona=0.7165069624329098 m:molokai=0.6207168370008496 m:oahu=0.736001020115832 m:lanai=0.7852388311321222

series e:i58n-7utq d:2007-01-01T00:00:00.000Z m:kauai=0.6954009934501498 m:maui=0.7070333431327421 m:hawaii_island_hilo=0.6759433595329923 m:hawaii_island_kona=0.7644019709706253 m:molokai=0.5199460554030798 m:oahu=0.7134469862940986 m:lanai=0.7173628214041644
```

## Meta Commands

```ls
metric m:oahu p:decimal l:Oahu t:dataTypeName=number

metric m:maui p:float l:Maui t:dataTypeName=number

metric m:molokai p:float l:Molokai t:dataTypeName=number

metric m:lanai p:float l:Lanai t:dataTypeName=number

metric m:kauai p:decimal l:Kauai t:dataTypeName=number

metric m:hawaii_island_kona p:float l:"Hawaii Island (Kona)" t:dataTypeName=number

metric m:hawaii_island_hilo p:decimal l:"Hawaii Island (Hilo)" t:dataTypeName=number

entity e:i58n-7utq l:"Report Card 3a Resident Sentiment Benefits" t:url=https://data.hawaii.gov/api/views/i58n-7utq

property e:i58n-7utq t:meta.view v:id=i58n-7utq v:averageRating=0 v:name="Report Card 3a Resident Sentiment Benefits"

property e:i58n-7utq t:meta.view.owner v:id=pvmv-89ja v:screenName="Daniel Nahoopii" v:displayName="Daniel Nahoopii"

property e:i58n-7utq t:meta.view.tableauthor v:id=pvmv-89ja v:screenName="Daniel Nahoopii" v:roleName=editor v:displayName="Daniel Nahoopii"
```

## Top Records

```ls
| year | oahu                | maui                | molokai             | lanai               | kauai               | hawaii_island_kona  | hawaii_island_hilo  | 
| ==== | =================== | =================== | =================== | =================== | =================== | =================== | =================== | 
| 2005 | 0.71769301632418991 | 0.74089550662335768 | 0.57229323806759236 | 0.57371480935480712 | 0.69690358366006666 | 0.59846703033241211 | 0.65234659830932973 | 
| 2006 | 0.73600102011583202 | 0.675469194713893   | 0.62071683700084956 | 0.78523883113212223 | 0.63030199315107516 | 0.71650696243290979 | 0.70191421076688787 | 
| 2007 | 0.71344698629409864 | 0.70703334313274213 | 0.51994605540307981 | 0.71736282140416441 | 0.69540099345014983 | 0.76440197097062534 | 0.67594335953299234 | 
| 2009 | 0.77975215034262202 | 0.8                 | 0.66                | 0.79                | 0.756719406711859   | 0.83                | 0.77                | 
| 2010 | 0.82191478245569005 | 0.7205248312901712  | 0.64709756673027297 | 0.69005014588839497 | 0.82523032929079398 | 0.772220521953498   | 0.77557783335040997 | 
| 2012 | 0.69020460360468894 | 0.66734772818638199 | 0.44056037388076624 | 0.76960825237473152 | 0.57665169078897904 | 0.60549856197296825 | 0.56907831826244226 | 
```