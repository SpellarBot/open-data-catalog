# Recovery Plan Progress Indicator 12212012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/recovery-plan-progress-indicator-12212012-eb75f) |
| Metadata | [Link](https://data.wa.gov/api/views/k2zi-4hgf) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/k2zi-4hgf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/k2zi-4hgf/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | k2zi-4hgf |
| Name | Recovery Plan Progress Indicator 12212012 |
| Created | 2012-12-21T20:23:09Z |
| Publication Date | 2012-12-21T20:24:02Z |

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type | Render Type |
| ======== | ============== | ========== | ========== | ========= | =========== |
| Yes      | time           | year       | Year       | number    | number      |
| Yes      | series tag     | region     | Region     | text      | text        |
| Yes      | numeric metric | habitat    | Habitat    | number    | number      |
| Yes      | numeric metric | hatchery   | Hatchery   | number    | number      |
| Yes      | numeric metric | harvest    | Harvest    | number    | number      |
| Yes      | numeric metric | hydropower | Hydropower | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:k2zi-4hgf d:2008-01-01T00:00:00.000Z t:region="Hood Canal" m:habitat=21 m:hydropower=8 m:hatchery=60 m:harvest=100

series e:k2zi-4hgf d:2010-01-01T00:00:00.000Z t:region="Hood Canal" m:habitat=29 m:hydropower=17 m:hatchery=70 m:harvest=100

series e:k2zi-4hgf d:2012-01-01T00:00:00.000Z t:region="Hood Canal" m:habitat=34 m:hydropower=25 m:hatchery=80 m:harvest=100
```

## Meta Commands

```ls
metric m:habitat p:integer l:Habitat t:dataTypeName=number

metric m:hatchery p:integer l:Hatchery t:dataTypeName=number

metric m:harvest p:integer l:Harvest t:dataTypeName=number

metric m:hydropower p:integer l:Hydropower t:dataTypeName=number

entity e:k2zi-4hgf l:"Recovery Plan Progress Indicator 12212012" t:url=https://data.wa.gov/api/views/k2zi-4hgf

property e:k2zi-4hgf t:meta.view v:id=k2zi-4hgf v:averageRating=0 v:name="Recovery Plan Progress Indicator 12212012"

property e:k2zi-4hgf t:meta.view.owner v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:displayName="Jennifer Johnson"

property e:k2zi-4hgf t:meta.view.tableauthor v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"
```

## Top Records

```ls
| year | region         | habitat | hatchery | harvest | hydropower | 
| ==== | ============== | ======= | ======== | ======= | ========== | 
| 2008 | Hood Canal     | 21      | 60       | 100     | 8          | 
| 2010 | Hood Canal     | 29      | 70       | 100     | 17         | 
| 2012 | Hood Canal     | 34      | 80       | 100     | 25         | 
| 2008 | Lower Columbia |         |          | 50      |            | 
| 2010 | Lower Columbia | 30      | 35       | 60      | 30         | 
| 2012 | Lower Columbia | 40      | 60       | 70      | 50         | 
| 2008 | Mid-Columbia   | 10      | 80       | 80      | 60         | 
| 2010 | Mid-Columbia   | 25      | 80       | 85      | 70         | 
| 2012 | Mid-Columbia   | 35      | 85       | 90      | 75         | 
| 2008 | Puget Sound    | 2       |          | 88      |            | 
```