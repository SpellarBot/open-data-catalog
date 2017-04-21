# State Agency Status Implementing Open Data- (Includes Agency Data Officers)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/agency-status) |
| Metadata | [Link](https://data.ct.gov/api/views/pb5x-kf8z) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/pb5x-kf8z/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/pb5x-kf8z/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | pb5x-kf8z |
| Name | State Agency Status Implementing Open Data- (Includes Agency Data Officers) |
| Tags | od, policy, datastatus, agency data officers |
| Created | 2015-09-15T18:09:06Z |
| Publication Date | 2017-02-24T16:43:37Z |

## Description

A dataset used to track State Agency implementation of the Open Data Policy. This also includes a list of Agency Data Officers

## Columns

```ls
| Included | Schema Type | Field Name                      | Name                            | Data Type | Render Type |
| ======== | =========== | =============================== | =============================== | ========= | =========== |
| No       | time        | :updated_at                     | updated_at                      | meta_data | meta_data   |
| Yes      | series tag  | agency                          | Agency                          | text      | text        |
| Yes      | series tag  | acronym                         | ACRONYM                         | text      | text        |
| Yes      | series tag  | first_name                      | First Name                      | text      | text        |
| Yes      | series tag  | last_name                       | Last Name                       | text      | text        |
| Yes      | series tag  | email                           | Email                           | text      | text        |
| Yes      | series tag  | ado                             | ADO                             | text      | text        |
| Yes      | series tag  | submitted_initial_datasets      | SUBMITTED INITIAL DATASETS      | text      | text        |
| Yes      | series tag  | published_initial_datasets      | PUBLISHED INITIAL DATASETS      | text      | text        |
| Yes      | series tag  | enterpise_data_inventory_status | ENTERPISE DATA INVENTORY STATUS | text      | text        |
| Yes      | series tag  | public_data_listing_status      | PUBLIC DATA LISTING STATUS      | text      | text        |
| Yes      | series tag  | number_of_public_datasets       | NUMBER OF PUBLIC DATASETS       | text      | text        |
| Yes      | series tag  | total_datasets_published        | TOTAL DATASETS PUBLISHED        | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:pb5x-kf8z d:2016-01-08T12:07:24.000Z t:first_name=Julie t:ado=YES t:submitted_initial_datasets=YES t:acronym=OEC t:email=julie.bisi@ct.gov t:public_data_listing_status=NA t:last_name=Bisi t:agency="Early Childhood" t:published_initial_datasets=YES t:enterpise_data_inventory_status=NO m:row_number.pb5x-kf8z=1

series e:pb5x-kf8z d:2016-01-08T12:07:27.000Z t:first_name=Susan t:ado=YES t:submitted_initial_datasets=YES t:acronym=DCF t:email=susan.smith@ct.gov t:public_data_listing_status=NA t:last_name=Smith t:agency="Children and Families" t:published_initial_datasets=YES t:enterpise_data_inventory_status=NO m:row_number.pb5x-kf8z=2

series e:pb5x-kf8z d:2016-01-08T12:07:31.000Z t:first_name=Michael t:ado=YES t:submitted_initial_datasets=YES t:acronym=DSS t:email=mike.gilbert@ct.gov t:public_data_listing_status=NA t:last_name=Gilbert t:agency="Social Services" t:published_initial_datasets=YES t:enterpise_data_inventory_status=NO m:row_number.pb5x-kf8z=3
```

## Meta Commands

```ls
metric m:row_number.pb5x-kf8z p:long l:"Row Number"

entity e:pb5x-kf8z l:"State Agency Status Implementing Open Data- (Includes Agency Data Officers)" t:url=https://data.ct.gov/api/views/pb5x-kf8z

property e:pb5x-kf8z t:meta.view v:id=pb5x-kf8z v:averageRating=0 v:name="State Agency Status Implementing Open Data- (Includes Agency Data Officers)"

property e:pb5x-kf8z t:meta.view.license v:name="Public Domain"

property e:pb5x-kf8z t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:pb5x-kf8z t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| :updated_at | agency                            | acronym  | first_name | last_name   | email                        | ado | submitted_initial_datasets | published_initial_datasets | enterpise_data_inventory_status | public_data_listing_status | number_of_public_datasets | total_datasets_published | 
| =========== | ================================= | ======== | ========== | =========== | ============================ | === | ========================== | ========================== | =============================== | ========================== | ========================= | ======================== | 
| 1452254844  | Early Childhood                   | OEC      | Julie      | Bisi        | julie.bisi@ct.gov            | YES | YES                        | YES                        | NO                              | NA                         |                           |                          | 
| 1452254847  | Children and Families             | DCF      | Susan      | Smith       | susan.smith@ct.gov           | YES | YES                        | YES                        | NO                              | NA                         |                           |                          | 
| 1452254851  | Social Services                   | DSS      | Michael    | Gilbert     | mike.gilbert@ct.gov          | YES | YES                        | YES                        | NO                              | NA                         |                           |                          | 
| 1452254854  | Energy & Environmental Protection | DEEP     | Bob        | Kaliszewski | Robert.Kaliszewski@ct.gov    | YES | YES                        | NO                         | YES                             | NA                         |                           |                          | 
| 1452254866  | Consumer Protection               | DCP      | Farnk      | Virnelli    | Frank.Virnelli@ct.gov        | YES | YES                        | YES                        | YES                             | NA                         |                           |                          | 
| 1452254869  | Aging                             | Aging    | Stephanie  | Marino      | stephanie.marino@ct.gov      | YES | YES                        | YES                        | NO                              | NA                         |                           |                          | 
| 1452254873  | Military Dept.                    | Military | Russell    | Bonaccorso  | Russell.Bonaccorso@ct.gov    | YES | NO                         | NO                         | NO                              | NA                         |                           |                          | 
| 1452254876  | Revenue Services                  | DRS      | Susan      | Sherman     | Susan.Sherman@po.state.ct.us | YES | YES                        | YES                        | NO                              | NA                         |                           |                          | 
| 1452254881  | Agricultural Experiment Stat      | Ag Exp   | Micahel    | Last        | Michael.Last@ct.gov          | YES | NO                         | NO                         | NO                              | NA                         |                           |                          | 
| 1452254885  | Housing                           | DOH      | Dimple     | Desai       | dimple.desai@ct.gov          | YES | YES                        | YES                        | NO                              | NA                         |                           |                          | 
```