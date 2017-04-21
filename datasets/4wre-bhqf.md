# TVCPI

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/tvcpi-1a6eb) |
| Metadata | [Link](https://data.oregon.gov/api/views/4wre-bhqf) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/4wre-bhqf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/4wre-bhqf/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 4wre-bhqf |
| Name | TVCPI |
| Created | 2014-05-14T20:34:18Z |
| Publication Date | 2014-05-14T21:12:40Z |

## Columns

```ls
| Included | Schema Type | Field Name          | Name                | Data Type | Render Type |
| ======== | =========== | =================== | =================== | ========= | =========== |
| No       | time        | :updated_at         | updated_at          | meta_data | meta_data   |
| Yes      | series tag  | first_name          | First Name          | text      | text        |
| Yes      | series tag  | last_name           | Last Name           | text      | text        |
| Yes      | series tag  | email               | Email               | email     | email       |
| Yes      | series tag  | organization        | Organization        | text      | text        |
| Yes      | series tag  | state               | State               | text      | text        |
| Yes      | series tag  | comment             | Comment             | html      | html        |
| Yes      | series tag  | additional_document | Additional Document | document  | document    |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:4wre-bhqf d:2014-05-20T09:09:02.000Z t:first_name=nick t:organization="north bend prospectors" t:email=nmaness8541@charter.net t:state=Oregon t:last_name=maness t:comment="no more fees!!!!!!" m:row_number.4wre-bhqf=1

series e:4wre-bhqf d:2014-06-11T18:31:02.000Z t:first_name=Laura t:organization="Oregon Refuse & Recycling Association" t:additional_document.filename="Title V permit rulemaking comments JUNE_2014.doc" t:email=laural@orra.net t:additional_document.size=118784 t:additional_document.content_type=application/msword t:state=Oregon t:last_name=Leebrick t:additional_document.file_id=u7Dqzpkv5hBOxM1_Eab60ACz64eYqHc36K8Aawh2GjM t:comment="Please see attached document for comments." m:row_number.4wre-bhqf=2
```

## Meta Commands

```ls
metric m:row_number.4wre-bhqf p:long l:"Row Number"

entity e:4wre-bhqf l:TVCPI t:url=https://data.oregon.gov/api/views/4wre-bhqf

property e:4wre-bhqf t:meta.view v:id=4wre-bhqf v:averageRating=0 v:name=TVCPI

property e:4wre-bhqf t:meta.view.owner v:id=44u9-wper v:screenName="MT Oregon DEQ" v:displayName="MT Oregon DEQ"

property e:4wre-bhqf t:meta.view.tableauthor v:id=44u9-wper v:screenName="MT Oregon DEQ" v:roleName=editor v:displayName="MT Oregon DEQ"
```

## Top Records

```ls
| :updated_at | first_name | last_name | email                   | organization                          | state  | comment                                    | additional_document                                                                                                         | 
| =========== | ========== | ========= | ======================= | ===================================== | ====== | ========================================== | =========================================================================================================================== | 
| 1400576942  | nick       | maness    | nmaness8541@charter.net | north bend prospectors                | Oregon | no more fees!!!!!!                         | [null, null, null, null]                                                                                                    | 
| 1402511462  | Laura      | Leebrick  | laural@orra.net         | Oregon Refuse & Recycling Association | Oregon | Please see attached document for comments. | [application/msword, u7Dqzpkv5hBOxM1_Eab60ACz64eYqHc36K8Aawh2GjM, Title V permit rulemaking comments JUNE_2014.doc, 118784] | 
```