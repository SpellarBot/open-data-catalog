# DOE Building Space Usage

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/doe-building-space-usage) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/wavz-fkw8) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/wavz-fkw8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/wavz-fkw8/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | wavz-fkw8 |
| Name | DOE Building Space Usage |
| Attribution | School Construction Authority (SCA) |
| Category | Education |
| Tags | doe, schools, buildings, usage, education, classroom |
| Created | 2015-06-10T20:15:58Z |
| Publication Date | 2015-06-10T20:19:24Z |

## Description

List of DOE buildings schools housed within the building and with listing of rooms by size, usage.

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| No       | time           | :updated_at   | updated_at    | meta_data | meta_data   |
| Yes      | series tag     | bldg_id       | Bldg ID       | text      | text        |
| Yes      | series tag     | org_code      | Org Code      | text      | text        |
| Yes      | series tag     | room_number   | Room Number   | text      | text        |
| Yes      | numeric metric | length        | Length        | number    | number      |
| Yes      | numeric metric | width         | Width         | number    | number      |
| Yes      | numeric metric | area          | Area          | number    | number      |
| Yes      | series tag     | room_function | Room Function | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:wavz-fkw8 d:2015-06-10T13:16:02.000Z t:room_number=101 t:bldg_id=K001 t:org_code=K001 t:room_function=KINDERGARTEN m:area=702 m:width=26 m:length=27

series e:wavz-fkw8 d:2015-06-10T13:16:02.000Z t:room_number=102 t:bldg_id=K001 t:org_code=K001 t:room_function="SECOND GRADE" m:area=957 m:width=33 m:length=29

series e:wavz-fkw8 d:2015-06-10T13:16:02.000Z t:room_number=103 t:bldg_id=K001 t:org_code=K001 t:room_function=KINDERGARTEN m:area=729 m:width=27 m:length=27
```

## Meta Commands

```ls
metric m:length p:integer l:Length t:dataTypeName=number

metric m:width p:integer l:Width t:dataTypeName=number

metric m:area p:integer l:Area t:dataTypeName=number

entity e:wavz-fkw8 l:"DOE Building Space Usage" t:attribution="School Construction Authority (SCA)" t:url=https://data.cityofnewyork.us/api/views/wavz-fkw8

property e:wavz-fkw8 t:meta.view v:id=wavz-fkw8 v:category=Education v:averageRating=0 v:name="DOE Building Space Usage" v:attribution="School Construction Authority (SCA)"

property e:wavz-fkw8 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:wavz-fkw8 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | bldg_id | org_code | room_number | length | width | area | room_function            | 
| =========== | ======= | ======== | =========== | ====== | ===== | ==== | ======================== | 
| 1433942162  | K001    | K001     | 101         | 27     | 26    | 702  | KINDERGARTEN             | 
| 1433942162  | K001    | K001     | 102         | 29     | 33    | 957  | SECOND GRADE             | 
| 1433942162  | K001    | K001     | 103         | 27     | 27    | 729  | KINDERGARTEN             | 
| 1433942162  | K001    | K001     | 105         | 26     | 27    | 702  | KINDERGARTEN             | 
| 1433942162  | K001    | K001     | 106         | 29     | 32    | 928  | FIRST GRADE              | 
| 1433942162  | K001    | K001     | 107         | 27     | 26    | 702  | KINDERGARTEN             | 
| 1433942162  | K001    | K001     | 110         | 9      | 7     | 63   | GENERAL BUILDING SUPPORT | 
| 1433942162  | K001    | K001     | 111         | 8      | 8     | 64   | GENERAL BUILDING SUPPORT | 
| 1433942162  | K001    | K001     | 121         | 27     | 27    | 729  | KINDERGARTEN             | 
| 1433942162  | K001    | K001     | 123         | 27     | 27    | 729  | KINDERGARTEN             | 
```