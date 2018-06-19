# Alternate Transportation Miles Traveled

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/alternate-transportation-miles-traveled) |
| Metadata | [Link](https://data.oregon.gov/api/views/mmpn-adtj) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/mmpn-adtj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/mmpn-adtj/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | mmpn-adtj |
| Name | Alternate Transportation Miles Traveled |
| Category | Administrative |
| Created | 2015-05-27T16:27:18Z |
| Publication Date | 2015-05-27T16:49:29Z |

## Columns

```ls
| Included | Schema Type    | Field Name                              | Name                                | Data Type      | Render Type    |
| ======== | ============== | ======================================= | =================================== | ============== | ============== |
| No       | time           | :updated_at                             | updated_at                          | meta_data      | meta_data      |
| Yes      | series tag     | month                                   | Month                               | drop_down_list | drop_down_list |
| Yes      | series tag     | name                                    | Name                                | text           | text           |
| Yes      | numeric metric | how_many_miles_traveled                 | Miles Traveled                      | number         | number         |
| Yes      | numeric metric | how_days_using_alternate_transportation | Days Using Alternate Transportation | number         | number         |
| Yes      | series tag     | transport_type                          | Transport Type                      | drop_down_list | drop_down_list |
| Yes      | series tag     | division                                | Division                            | drop_down_list | drop_down_list |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:mmpn-adtj d:2015-05-27T09:53:54.000Z t:division=zyw7-dipb t:transport_type=bnvt-ddvm t:name=Emme t:month=79na-4r9q m:how_many_miles_traveled=100 m:how_days_using_alternate_transportation=4

series e:mmpn-adtj d:2015-06-09T13:57:00.000Z t:division=c832-bhkn t:transport_type=bnvt-ddvm t:name="Emma snodgrass" t:month=79na-4r9q m:how_many_miles_traveled=55 m:how_days_using_alternate_transportation=1
```

## Meta Commands

```ls
metric m:how_many_miles_traveled p:integer l:"Miles Traveled" t:dataTypeName=number

metric m:how_days_using_alternate_transportation p:integer l:"Days Using Alternate Transportation" t:dataTypeName=number

entity e:mmpn-adtj l:"Alternate Transportation Miles Traveled" t:url=https://data.oregon.gov/api/views/mmpn-adtj

property e:mmpn-adtj t:meta.view v:id=mmpn-adtj v:category=Administrative v:averageRating=0 v:name="Alternate Transportation Miles Traveled"

property e:mmpn-adtj t:meta.view.owner v:id=mxyf-wbw4 v:profileImageUrlMedium=/api/users/mxyf-wbw4/profile_images/THUMB v:profileImageUrlLarge=/api/users/mxyf-wbw4/profile_images/LARGE v:screenName="Emma Snodgrass" v:profileImageUrlSmall=/api/users/mxyf-wbw4/profile_images/TINY v:displayName="Emma Snodgrass"

property e:mmpn-adtj t:meta.view.tableauthor v:id=mxyf-wbw4 v:profileImageUrlMedium=/api/users/mxyf-wbw4/profile_images/THUMB v:profileImageUrlLarge=/api/users/mxyf-wbw4/profile_images/LARGE v:screenName="Emma Snodgrass" v:profileImageUrlSmall=/api/users/mxyf-wbw4/profile_images/TINY v:roleName=editor v:displayName="Emma Snodgrass"
```

## Top Records

```ls
| :updated_at | month     | name           | how_many_miles_traveled | how_days_using_alternate_transportation | transport_type | division  | 
| =========== | ========= | ============== | ======================= | ======================================= | ============== | ========= | 
| 1432720434  | 79na-4r9q | Emme           | 100                     | 4                                       | bnvt-ddvm      | zyw7-dipb | 
| 1433858220  | 79na-4r9q | Emma snodgrass | 55                      | 1                                       | bnvt-ddvm      | c832-bhkn | 
```