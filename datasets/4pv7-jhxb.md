# Opioid Related Treatment Admissions by Town in Department of Mental Health and Addiction Services Programs

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/opioid-related-treatment-admsissions-by-town-in-department-of-mental-health-and-addiction-) |
| Metadata | [Link](https://data.ct.gov/api/views/4pv7-jhxb) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/4pv7-jhxb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/4pv7-jhxb/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | 4pv7-jhxb |
| Name | Opioid Related Treatment Admissions by Town in Department of Mental Health and Addiction Services Programs |
| Attribution | Department of Mental Health and Addiction Services |
| Category | Health and Human Services |
| Tags | opioid, dmhas, substance abuse |
| Created | 2016-09-20T19:29:09Z |
| Publication Date | 2016-09-26T16:10:20Z |

## Description

Town level data on depicting the number of admissions, and individuals served per year in treatment programs funded or operated by the Department of Mental Health and Addiction Services, where the primary drug at admission was an opioid. Clients entering these programs were treated for their opioid related disorder as a result of it being the primary drug at the time of admission. This dataset does not reflect ALL individuals in Connecticut who have participated in an opioid related treatment program, but only service provided by the Department of Mental Health and Addiction Services, nor are these programs specifically designated as "opioid treatment."

* Values less than or equal to 5 and greater than 0 have been suppressed to protect the identity of individuals.

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type | Render Type |
| ======== | ============== | ==================== | ==================== | ========= | =========== |
| Yes      | time           | fiscalyear           | FiscalYear           | number    | number      |
| Yes      | series tag     | town                 | Town                 | text      | text        |
| Yes      | numeric metric | admissions           | Admissions           | number    | number      |
| Yes      | numeric metric | unduplicated_clients | Unduplicated Clients | number    | number      |
```

## Time Field

```ls
Value = fiscalyear
Format & Zone = yyyy
```

## Data Commands

```ls
series e:4pv7-jhxb d:2014-01-01T00:00:00.000Z t:town=Woodbridge m:admissions=17 m:unduplicated_clients=16

series e:4pv7-jhxb d:2014-01-01T00:00:00.000Z t:town=Bozrah m:admissions=13 m:unduplicated_clients=11

series e:4pv7-jhxb d:2014-01-01T00:00:00.000Z t:town=Harwinton m:admissions=28 m:unduplicated_clients=13
```

## Meta Commands

```ls
metric m:admissions p:integer l:Admissions t:dataTypeName=number

metric m:unduplicated_clients p:integer l:"Unduplicated Clients" t:dataTypeName=number

entity e:4pv7-jhxb l:"Opioid Related Treatment Admissions by Town in Department of Mental Health and Addiction Services Programs" t:attribution="Department of Mental Health and Addiction Services" t:url=https://data.ct.gov/api/views/4pv7-jhxb

property e:4pv7-jhxb t:meta.view v:id=4pv7-jhxb v:category="Health and Human Services" v:attributionLink=http://www.ct.gov/dmhas v:averageRating=0 v:name="Opioid Related Treatment Admissions by Town in Department of Mental Health and Addiction Services Programs" v:attribution="Department of Mental Health and Addiction Services"

property e:4pv7-jhxb t:meta.view.license v:name="Public Domain"

property e:4pv7-jhxb t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:4pv7-jhxb t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| fiscalyear | town          | admissions | unduplicated_clients | 
| ========== | ============= | ========== | ==================== | 
| 2012       | Andover       |            |                      | 
| 2014       | Woodbridge    | 17         | 16                   | 
| 2014       | Bozrah        | 13         | 11                   | 
| 2014       | Harwinton     | 28         | 13                   | 
| 2015       | Oxford        | 62         | 36                   | 
| 2014       | Sharon        | 39         | 25                   | 
| 2012       | Coventry      | 43         | 21                   | 
| 2015       | New Fairfield | 58         | 37                   | 
| 2015       | Hartland      |            |                      | 
| 2014       | Hartford      | 2328       | 1286                 | 
```