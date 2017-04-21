# 2013 Apple Growers List

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2013-apple-growers-list) |
| Metadata | [Link](https://data.ct.gov/api/views/k7hr-c5u6) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/k7hr-c5u6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/k7hr-c5u6/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | k7hr-c5u6 |
| Name | 2013 Apple Growers List |
| Attribution | Department of Agriculture |
| Category | Environment and Natural Resources |
| Tags | apples, farm, doag |
| Created | 2014-05-09T19:06:47Z |
| Publication Date | 2014-05-09T19:09:07Z |

## Description

List of Apple growers in Connecticut

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| Yes      | series tag     | businessname1 | BusinessName1 | text      | text        |
| No       |                | address       | Address       | text      | text        |
| Yes      | series tag     | town          | Town          | text      | text        |
| Yes      | series tag     | state         | State         | text      | text        |
| Yes      | numeric metric | bushels       | Bushels       | number    | number      |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:k7hr-c5u6 d:2013-01-01T00:00:00.000Z t:businessname1="Colton's Corner Farm" t:state=CT t:town=Cheshire m:bushels=260

series e:k7hr-c5u6 d:2013-01-01T00:00:00.000Z t:businessname1="Woodstock Orchards LLC" t:state=ct t:town=woodstock m:bushels=17190

series e:k7hr-c5u6 d:2013-01-01T00:00:00.000Z t:businessname1="lapsley orchard" t:state=CT t:town="Pomfret Center" m:bushels=3900
```

## Meta Commands

```ls
metric m:bushels p:float l:Bushels t:dataTypeName=number

entity e:k7hr-c5u6 l:"2013 Apple Growers List" t:attribution="Department of Agriculture" t:url=https://data.ct.gov/api/views/k7hr-c5u6

property e:k7hr-c5u6 t:meta.view v:id=k7hr-c5u6 v:category="Environment and Natural Resources" v:attributionLink="http://www.ct.gov/doag/cwp/view.asp?a=3260&q=399560" v:averageRating=0 v:name="2013 Apple Growers List" v:attribution="Department of Agriculture"

property e:k7hr-c5u6 t:meta.view.license v:name="Public Domain"

property e:k7hr-c5u6 t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:k7hr-c5u6 t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| businessname1                   | address                          | town           | state | bushels  | 
| =============================== | ================================ | ============== | ===== | ======== | 
| LOST ACRES ORCHARD & FARM STORE | 130 Lost Acres Road              | North Granby   | CT    |          | 
| Colton's Corner Farm            | 636 Reservoir Road               | Cheshire       | CT    | 260.00   | 
| Horse Listeners Orchard         | 16 Brookfield Drive              | Ellington      | CT    |          | 
| Holiday Farm Orchard            | 265 South Road                   | New Hartford   | CT    |          | 
| Woodstock Orchards LLC          | po box 113                       | woodstock      | ct    | 17190.00 | 
| lapsley orchard                 | 403 Orchard Hill Road (Rte. 169) | Pomfret Center | CT    | 3900.00  | 
| Hidden Brook Gardens LLC        | 551 Colonel Ledyard Highway      | Ledyard        | CT    | 25.00    | 
| Deercrest Farm                  | 3499 HEBRON AVE                  | GLASTONBURY    | CT    | 2833.00  | 
| HAYWARD FARM                    | 238 Hayward Road                 | New Hartford   | CT    | 3000.00  | 
| Woodstock Orchards LLC          | P.O. Box 113                     | Woodstock      | CT    |          | 
```