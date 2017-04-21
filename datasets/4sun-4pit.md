# Columbia River Crossing Comments

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/columbia-river-crossing-comments-fd482) |
| Metadata | [Link](https://data.oregon.gov/api/views/4sun-4pit) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/4sun-4pit/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/4sun-4pit/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 4sun-4pit |
| Name | Columbia River Crossing Comments |
| Created | 2013-04-18T15:48:40Z |
| Publication Date | 2013-10-17T21:46:42Z |

## Description

Columbia River Crossing Comments

## Columns

```ls
| Included | Schema Type | Field Name          | Name                | Data Type      | Render Type    |
| ======== | =========== | =================== | =================== | ============== | ============== |
| Yes      | series tag  | first_name          | First Name          | text           | text           |
| Yes      | series tag  | last_name           | Last Name           | text           | text           |
| Yes      | series tag  | email               | Email               | email          | email          |
| Yes      | series tag  | organization        | Organization        | text           | text           |
| Yes      | series tag  | state               | State               | text           | text           |
| Yes      | series tag  | comment             | Comment             | html           | html           |
| Yes      | series tag  | additional_document | Additional Document | document       | document       |
| Yes      | series tag  | type_of_comment     | Type of Comment     | drop_down_list | drop_down_list |
| Yes      | series tag  | comment_types       | Comment Types       | drop_down_list | drop_down_list |
| Yes      | time        | time_stamp          | Time stamp          | date           | date           |
```

## Time Field

```ls
Value = time_stamp
Format & Zone = seconds
```

## Data Commands

```ls
series e:4sun-4pit d:2013-05-21T09:05:23.000Z t:first_name=Jane t:organization=test t:email=doe@gmail.com t:state=test t:last_name=Doe t:comment="<p>test</p>
<p>&nbsp;</p>" m:row_number.4sun-4pit=1

series e:4sun-4pit d:2013-05-21T09:21:46.000Z t:type_of_comment=2gdn-fvh7 t:first_name=john t:comment_types=pqua-uehj t:email=john.q.public@hotmail.com t:state=OR t:last_name=public t:comment=test2 m:row_number.4sun-4pit=2

series e:4sun-4pit d:2013-10-06T11:12:20.000Z t:type_of_comment=2gdn-fvh7 t:first_name=BguERxHnZAUT t:organization=SKeKolwPHX t:comment_types=pqua-uehj t:email=Timlin430@gmail.com t:last_name=rMCgqhxlrcUT t:comment="<a target=""_blank"" href=""http://groch.com/serv/#45172"">buy tramadol online</a> tramadol no prescription free shipping - order tramadol for pets" m:row_number.4sun-4pit=3
```

## Meta Commands

```ls
metric m:row_number.4sun-4pit p:long l:"Row Number"

entity e:4sun-4pit l:"Columbia River Crossing Comments" t:url=https://data.oregon.gov/api/views/4sun-4pit

property e:4sun-4pit t:meta.view v:id=4sun-4pit v:averageRating=0 v:name="Columbia River Crossing Comments"

property e:4sun-4pit t:meta.view.owner v:id=7f2t-e4kt v:screenName="Mary-Frances Makichen" v:displayName="Mary-Frances Makichen"

property e:4sun-4pit t:meta.view.tableauthor v:id=7f2t-e4kt v:screenName="Mary-Frances Makichen" v:displayName="Mary-Frances Makichen"
```

## Top Records

```ls
| first_name   | last_name        | email                                 | organization | state | comment                                                                              | additional_document      | type_of_comment | comment_types | time_stamp   | 
| ============ | ================ | ===================================== | ============ | ===== | ==================================================================================== | ======================== | =============== | ============= | ============ | 
| Jane         | Doe              | doe@gmail.com                         | test         | test  | test
                                                                                | [null, null, null, null] |                 |               |              | 
| john         | public           | john.q.public@hotmail.com             |              | OR    | test2                                                                                | [null, null, null, null] | 2gdn-fvh7       | pqua-uehj     |              | 
| BguERxHnZAUT | rMCgqhxlrcUT     | Timlin430@gmail.com                   | SKeKolwPHX   |       | buy tramadol online tramadol no prescription free shipping - order tramadol for pets | [null, null, null, null] | 2gdn-fvh7       | pqua-uehj     |              | 
| John         | Doe              | doe@gmail.com                         |              | OR    | test                                                                                 | [null, null, null, null] | veqh-ejbr       |               |              | 
| Jane         | doe              | doe@gmail.com                         | TEST         | TEST  | TEST                                                                                 | [null, null, null, null] |                 |               | 1382071036   | 
| John         | Doe              | doe@gmail.com                         | TEST         | test  | test                                                                                 | [null, null, null, null] |                 |               | 1382071194   | 
| Joan         | Doe              | doe@gmail.com                         | test         | test  | test                                                                                 | [null, null, null, null] |                 |               | 1382071319   | 
| Did          | you              | allreceiveanemailnotifcation@nope.com | Dis-org      | Or    | This is a important comment                                                          | [null, null, null, null] | veqh-ejbr       | pqua-uehj     | -61472713502 | 
| Utah         | Fun              | nogiven@lawless.org                   | Aunt Marie   | OR    | this is for real                                                                     | [null, null, null, null] | t867-n9xq       | icyy-zz3c     | -60775788182 | 
| Halloween    | Isthebestholiday | noneprovided@happy.org                | None         | or    | this is it                                                                           | [null, null, null, null] | 2gdn-fvh7       | pqua-uehj     | -61817316962 | 
```