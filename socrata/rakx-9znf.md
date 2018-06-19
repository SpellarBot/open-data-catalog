# Weed Free Forage

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/weed-free-forage-313ee) |
| Metadata | [Link](https://data.oregon.gov/api/views/rakx-9znf) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/rakx-9znf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/rakx-9znf/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | rakx-9znf |
| Name | Weed Free Forage |
| Attribution | Oregon Department of Agriculture |
| Category | Natural Resources |
| Tags | agriculture, weed-free, forage, feed |
| Created | 2012-09-17T21:41:04Z |
| Publication Date | 2016-09-12T23:48:11Z |

## Description

List of Oregon weed free forage providers

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | county      | County     | text      | text        |
| Yes      | series tag  | provider    | Provider   | text      | text        |
| Yes      | series tag  | commodity   | Commodity  | text      | text        |
| Yes      | series tag  | phone       | Phone      | text      | text        |
| Yes      | series tag  | fax         | Fax        | text      | text        |
| Yes      | series tag  | state       | State      | text      | text        |
| Yes      | series tag  | web         | Web        | url       | url         |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:rakx-9znf d:2013-07-23T14:24:28.000Z t:phone="541-419-3637, C541-419-7682" t:commodity="orchardgrass hay" t:county=Crook t:state=OR t:provider="Iron Feather Ranch" m:row_number.rakx-9znf=1

series e:rakx-9znf d:2015-06-22T16:54:39.000Z t:phone=541-604-1350 t:commodity="orchardgrass hay" t:county=Deschutes t:state=OR t:provider="Kevin White - 2015" m:row_number.rakx-9znf=2

series e:rakx-9znf d:2015-07-10T15:23:31.000Z t:phone=541-519-3439 t:commodity="grass hay" t:county=Baker t:state=OR t:provider="Bailey Farms - 2015" m:row_number.rakx-9znf=3
```

## Meta Commands

```ls
metric m:row_number.rakx-9znf p:long l:"Row Number"

entity e:rakx-9znf l:"Weed Free Forage" t:attribution="Oregon Department of Agriculture" t:url=https://data.oregon.gov/api/views/rakx-9znf

property e:rakx-9znf t:meta.view v:id=rakx-9znf v:category="Natural Resources" v:attributionLink=http://oregon.gov/ODA v:averageRating=0 v:name="Weed Free Forage" v:attribution="Oregon Department of Agriculture"

property e:rakx-9znf t:meta.view.owner v:id=hfyt-zc65 v:screenName="Katherine Leamaster" v:displayName="Katherine Leamaster"

property e:rakx-9znf t:meta.view.tableauthor v:id=hfyt-zc65 v:screenName="Katherine Leamaster" v:displayName="Katherine Leamaster"
```

## Top Records

```ls
| :updated_at | county     | provider                          | commodity                     | phone                       | fax          | state | web          | 
| =========== | ========== | ================================= | ============================= | =========================== | ============ | ===== | ============ | 
| 1374589468  | Crook      | Iron Feather Ranch                | orchardgrass hay              | 541-419-3637, C541-419-7682 |              | OR    | [null, null] | 
| 1434992079  | Deschutes  | Kevin White - 2015                | orchardgrass hay              | 541-604-1350                |              | OR    | [null, null] | 
| 1436541811  | Baker      | Bailey Farms - 2015               | grass hay                     | 541-519-3439                |              | OR    | [null, null] | 
| 1438255204  | Polk       | Maxson Enterprises - 2015         | wheat straw                   | 503-437-1031                |              | OR    | [null, null] | 
| 1438255864  | Washington | Stadelman Farms - 2015            | wheat straw                   | 503-706-2669                |              | OR    | [null, null] | 
| 1439212000  | Klamath    | Quarter Circle N Ranch - 2015     | wheat straw                   | 541-882-3731, C541-891-1744 | 541-882-3731 | OR    | [null, null] | 
| 1439909124  | Marion     | Silver Mountain Farms LLC, - 2015 | wheat straw                   | Gary 503-932-7566           | 503-769-1738 | OR    | [null, null] | 
| 1463477991  | Umatilla   | Robert & Jerri Emert - 2016       | grass hay, alfalfa hay        | 541-376-8581, 541-571-0024  |              | OR    | [null, null] | 
| 1463584564  | Polk       | Orton Hay Farm - 2016             | grass hay                     | 503-580-4110                |              | OR    | [null, null] | 
| 1464963319  | Deschutes  | Sisters View Ranch - 2016         | alfalfa hay, orchardgrass hay | 541-521-1031                |              | OR    | [null, null] | 
```