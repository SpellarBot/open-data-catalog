# eGov Platforms

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/egov-platforms) |
| Metadata | [Link](https://data.wa.gov/api/views/js5f-3yhb) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/js5f-3yhb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/js5f-3yhb/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | js5f-3yhb |
| Name | eGov Platforms |
| Created | 2016-05-03T20:58:23Z |
| Publication Date | 2016-05-03T23:02:01Z |

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| No       | time           | :updated_at     | updated_at      | meta_data | meta_data   |
| Yes      | series tag     | categories      | Categories      | text      | text        |
| Yes      | numeric metric | number_of_sites | Number of Sites | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:js5f-3yhb d:2016-05-03T15:31:01.000Z t:categories=Sharepoint m:number_of_sites=12

series e:js5f-3yhb d:2016-05-03T15:31:05.000Z t:categories=Drupal m:number_of_sites=10

series e:js5f-3yhb d:2016-05-03T15:31:09.000Z t:categories="Static HTML" m:number_of_sites=4
```

## Meta Commands

```ls
metric m:number_of_sites p:integer l:"Number of Sites" t:dataTypeName=number

entity e:js5f-3yhb l:"eGov Platforms" t:url=https://data.wa.gov/api/views/js5f-3yhb

property e:js5f-3yhb t:meta.view v:id=js5f-3yhb v:averageRating=0 v:name="eGov Platforms"

property e:js5f-3yhb t:meta.view.owner v:id=bjfs-pe5a v:screenName=justinb.ocio v:displayName=justinb.ocio

property e:js5f-3yhb t:meta.view.tableauthor v:id=bjfs-pe5a v:screenName=justinb.ocio v:roleName=publisher v:displayName=justinb.ocio
```

## Top Records

```ls
| :updated_at | categories  | number_of_sites | 
| =========== | =========== | =============== | 
| 1462289461  | Sharepoint  | 12              | 
| 1462289465  | Drupal      | 10              | 
| 1462289469  | Static HTML | 4               | 
| 1462289474  | Wordpress   | 3               | 
| 1462289480  | Other CMS   | 3               | 
```