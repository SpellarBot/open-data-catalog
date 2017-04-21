# Recovery Plan Progress Indicator 10-27-2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/recovery-plan-progress-indicator-1302015) |
| Metadata | [Link](https://data.wa.gov/api/views/y8vk-3hy9) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/y8vk-3hy9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/y8vk-3hy9/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | y8vk-3hy9 |
| Name | Recovery Plan Progress Indicator 10-27-2016 |
| Created | 2015-01-01T00:17:53Z |
| Publication Date | 2016-10-27T14:32:04Z |

## Columns

```ls
| Included | Schema Type    | Field Name | Name     | Data Type | Render Type |
| ======== | ============== | ========== | ======== | ========= | =========== |
| Yes      | series tag     | region     | Region   | text      | text        |
| Yes      | series tag     | which_h    | Which H? | text      | text        |
| Yes      | numeric metric | 2008       | 2008     | number    | number      |
| Yes      | numeric metric | 2010       | 2010     | number    | number      |
| Yes      | numeric metric | 2012       | 2012     | number    | number      |
| Yes      | numeric metric | 2014       | 2014     | number    | number      |
| Yes      | numeric metric | 2016       | 2016     | number    | number      |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:y8vk-3hy9 d:2016-01-01T00:00:00.000Z t:region="Hood Canal" t:which_h=Habitat m:2008=21 m:2014=36 m:2016=38 m:2012=34 m:2010=29

series e:y8vk-3hy9 d:2016-01-01T00:00:00.000Z t:region="Lower Columbia" t:which_h=Habitat m:2014=40 m:2016=41 m:2012=40 m:2010=30

series e:y8vk-3hy9 d:2016-01-01T00:00:00.000Z t:region=Mid-Columbia t:which_h=Habitat m:2008=15 m:2014=45 m:2016=50 m:2012=40 m:2010=30
```

## Meta Commands

```ls
metric m:2008 p:integer l:2008 t:dataTypeName=number

metric m:2010 p:integer l:2010 t:dataTypeName=number

metric m:2012 p:integer l:2012 t:dataTypeName=number

metric m:2014 p:integer l:2014 t:dataTypeName=number

metric m:2016 p:integer l:2016 t:dataTypeName=number

entity e:y8vk-3hy9 l:"Recovery Plan Progress Indicator 10-27-2016" t:url=https://data.wa.gov/api/views/y8vk-3hy9

property e:y8vk-3hy9 t:meta.view v:id=y8vk-3hy9 v:averageRating=0 v:name="Recovery Plan Progress Indicator 10-27-2016"

property e:y8vk-3hy9 t:meta.view.owner v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:displayName="Jennifer Johnson"

property e:y8vk-3hy9 t:meta.view.tableauthor v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"
```

## Top Records

```ls
| region         | which_h  | 2008 | 2010 | 2012 | 2014 | 2016 | 
| ============== | ======== | ==== | ==== | ==== | ==== | ==== | 
| Hood Canal     | Habitat  | 21   | 29   | 34   | 36   | 38   | 
| Lower Columbia | Habitat  |      | 30   | 40   | 40   | 41   | 
| Mid-Columbia   | Habitat  | 15   | 30   | 40   | 45   | 50   | 
| Puget Sound    | Habitat  | 3    | 5    | 8    | 12   | 17   | 
| Snake          | Habitat  | 25   | 28   | 32   | 35   | 37   | 
| Upper Columbia | Habitat  | 26   | 41   | 48   | 55   | 60   | 
| WA Coast       | Habitat  | 5    | 8    | 12   | 15   | 25   | 
| Statewide      | Habitat  | 16   | 24   | 31   | 34   | 38   | 
| Hood Canal     | Hatchery | 60   | 70   | 80   | 80   | 82   | 
| Lower Columbia | Hatchery |      | 35   | 60   | 70   | 72   | 
```