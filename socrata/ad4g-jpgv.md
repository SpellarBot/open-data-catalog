# TPW_AssetAvailability

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/tpw-assetavailability) |
| Metadata | [Link](https://data.srcity.org/api/views/ad4g-jpgv) |
| Data: JSON | [100 Rows](https://data.srcity.org/api/views/ad4g-jpgv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.srcity.org/api/views/ad4g-jpgv/rows.csv?max_rows=100) |
| Host | data.srcity.org |
| Id | ad4g-jpgv |
| Name | TPW_AssetAvailability |
| Created | 2017-02-02T01:28:29Z |
| Publication Date | 2017-02-04T01:42:12Z |
| Rows Updated | 2017-02-04T01:42:10Z |

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type     | Render Type   |
| ======== | ============== | ====================== | ====================== | ============= | ============= |
| Yes      | time           | year                   | Year                   | calendar_date | calendar_date |
| Yes      | series tag     | groupbycomponent       | GroupByComponent       | text          | text          |
| Yes      | series tag     | groupbycomponentdesc   | GroupByComponentDesc   | text          | text          |
| Yes      | numeric metric | availabilitypercentage | AvailabilityPercentage | number        | number        |
| Yes      | numeric metric | downtimepercentage     | DownTimePercentage     | number        | number        |
| Yes      | numeric metric | totalpercentage        | TotalPercentage        | number        | number        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:ad4g-jpgv d:2016-12-31T00:00:00.000Z t:groupbycomponent=070302 t:groupbycomponentdesc=Patrol m:availabilitypercentage=100 m:downtimepercentage=0 m:totalpercentage=98.537265

series e:ad4g-jpgv d:2016-12-31T00:00:00.000Z t:groupbycomponent=080202 t:groupbycomponentdesc="Community Development Department" m:availabilitypercentage=100 m:downtimepercentage=0 m:totalpercentage=98.537265

series e:ad4g-jpgv d:2016-12-31T00:00:00.000Z t:groupbycomponent=080204 t:groupbycomponentdesc="Community Development" m:availabilitypercentage=99.51 m:downtimepercentage=0.49 m:totalpercentage=98.537265
```

## Meta Commands

```ls
metric m:availabilitypercentage p:double l:AvailabilityPercentage t:dataTypeName=number

metric m:downtimepercentage p:float l:DownTimePercentage t:dataTypeName=number

metric m:totalpercentage p:double l:TotalPercentage t:dataTypeName=number

entity e:ad4g-jpgv l:TPW_AssetAvailability t:url=https://data.srcity.org/api/views/ad4g-jpgv

property e:ad4g-jpgv t:meta.view v:id=ad4g-jpgv v:averageRating=0 v:name=TPW_AssetAvailability

property e:ad4g-jpgv t:meta.view.owner v:id=v4p4-re39 v:screenName="OpenData, RO" v:roleName=administrator v:displayName="OpenData, RO"

property e:ad4g-jpgv t:meta.view.tableauthor v:id=v4p4-re39 v:screenName="OpenData, RO" v:roleName=administrator v:displayName="OpenData, RO"
```