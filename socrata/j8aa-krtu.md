# Customized Plates & Copy Records Monthly Activity

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/customized-plates-copy-records-monthly-activity) |
| Metadata | [Link](https://data.ct.gov/api/views/j8aa-krtu) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/j8aa-krtu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/j8aa-krtu/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | j8aa-krtu |
| Name | Customized Plates & Copy Records Monthly Activity |
| Attribution | Department of Motor Vehicles |
| Category | Transportation |
| Tags | dmv |
| Created | 2014-10-03T19:02:53Z |
| Publication Date | 2014-10-03T19:11:58Z |

## Description

Activity for Jun, July, August

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| No       | time           | :updated_at       | updated_at        | meta_data | meta_data   |
| Yes      | series tag     | month             | Month             | text      | text        |
| Yes      | numeric metric | driver_histories  | Driver Histories  | number    | number      |
| Yes      | numeric metric | handicap_placards | Handicap Placards | number    | number      |
| Yes      | numeric metric | special_plates    | Special Plates    | number    | number      |
| Yes      | numeric metric | ncic_histories    | NCIC Histories    | number    | number      |
| Yes      | numeric metric | phone_calls       | Phone Calls       | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:j8aa-krtu d:2014-10-03T12:02:56.000Z t:month=June m:handicap_placards=2509 m:ncic_histories=2217 m:phone_calls=2325 m:special_plates=857 m:driver_histories=1223

series e:j8aa-krtu d:2014-10-03T12:02:56.000Z t:month=July m:handicap_placards=2729 m:ncic_histories=2584 m:phone_calls=2205 m:special_plates=865 m:driver_histories=1116

series e:j8aa-krtu d:2014-10-03T12:02:56.000Z t:month=August m:handicap_placards=2392 m:ncic_histories=4453 m:phone_calls=2195 m:special_plates=710 m:driver_histories=1056
```

## Meta Commands

```ls
metric m:driver_histories p:integer l:"Driver Histories" t:dataTypeName=number

metric m:handicap_placards p:integer l:"Handicap Placards" t:dataTypeName=number

metric m:special_plates p:integer l:"Special Plates" t:dataTypeName=number

metric m:ncic_histories p:integer l:"NCIC Histories" t:dataTypeName=number

metric m:phone_calls p:integer l:"Phone Calls" t:dataTypeName=number

entity e:j8aa-krtu l:"Customized Plates & Copy Records Monthly Activity" t:attribution="Department of Motor Vehicles" t:url=https://data.ct.gov/api/views/j8aa-krtu

property e:j8aa-krtu t:meta.view v:id=j8aa-krtu v:category=Transportation v:attributionLink=http://www.ct.gov/dmv v:averageRating=0 v:name="Customized Plates & Copy Records Monthly Activity" v:attribution="Department of Motor Vehicles"

property e:j8aa-krtu t:meta.view.owner v:id=fd5k-6njr v:screenName=APatel v:displayName=APatel

property e:j8aa-krtu t:meta.view.tableauthor v:id=fd5k-6njr v:screenName=APatel v:roleName=editor v:displayName=APatel
```

## Top Records

```ls
| :updated_at | month  | driver_histories | handicap_placards | special_plates | ncic_histories | phone_calls | 
| =========== | ====== | ================ | ================= | ============== | ============== | =========== | 
| 1412337776  | June   | 1223             | 2509              | 857            | 2217           | 2325        | 
| 1412337776  | July   | 1116             | 2729              | 865            | 2584           | 2205        | 
| 1412337776  | August | 1056             | 2392              | 710            | 4453           | 2195        | 
```