# Home Page Stories

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/home-page-stories-67dae) |
| Metadata | [Link](https://data.hawaii.gov/api/views/v2k9-msid) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/v2k9-msid/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/v2k9-msid/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | v2k9-msid |
| Name | Home Page Stories |
| Created | 2013-11-20T04:39:40Z |
| Publication Date | 2014-04-24T03:14:10Z |

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| No       | time           | :updated_at | updated_at  | meta_data | meta_data   |
| Yes      | series tag     | title       | Title       | text      | text        |
| Yes      | series tag     | description | Description | text      | text        |
| Yes      | series tag     | data_type   | Data-type   | text      | text        |
| Yes      | series tag     | link        | link        | text      | text        |
| Yes      | series tag     | image       | Image       | photo     | photo       |
| Yes      | series tag     | show        | Show        | checkbox  | checkbox    |
| Yes      | numeric metric | sort_order  | Sort Order  | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:v2k9-msid d:2013-11-21T09:35:05.000Z t:title="Video Tutorials" t:data_type=Link t:description="To help you get started with these tools, we've created a series of videos designed to teach you the basics about interacting with this data site." t:link=/videos t:show=true m:sort_order=2

series e:v2k9-msid d:2013-11-21T09:35:06.000Z t:title="Learn More" t:data_type=Link t:description="With the State of Hawaii's Open Data portal, the State of Hawaii provides residents, analysts, and civic developers with unparalleled access to State data for use in increasing transparency, driving civic innovation, and engaging participants in a more collaborative form of government. Click here to read more about the portal here." t:link=/about t:show=true m:sort_order=3

series e:v2k9-msid d:2013-11-21T09:49:00.000Z t:title="What's New?" t:description="The redesign and relaunch of Hawaii's Open Data Portal brings new features and new tools to open data. New charting libraries and new mapping tools allow the creation of dynamic visualizations, and datasets are larger and faster than ever.<br><br>The dataset catalog has expanded to more than twice the size it was this time last year, and more are added every day. Click here to explore the entire data catalog, or browse the categories on the right to see what's available." t:link=/browse t:image=Kkyrge-IAnciELG7pen3_bQFrJNGTD9RVV6HuWLK-i0 t:show=true m:sort_order=1
```

## Meta Commands

```ls
metric m:sort_order p:integer l:"Sort Order" t:dataTypeName=number

entity e:v2k9-msid l:"Home Page Stories" t:url=https://data.hawaii.gov/api/views/v2k9-msid

property e:v2k9-msid t:meta.view v:id=v2k9-msid v:averageRating=0 v:name="Home Page Stories"

property e:v2k9-msid t:meta.view.owner v:id=vcvp-yass v:profileImageUrlMedium=/api/users/vcvp-yass/profile_images/THUMB v:profileImageUrlLarge=/api/users/vcvp-yass/profile_images/LARGE v:screenName="Dylan Bussone" v:profileImageUrlSmall=/api/users/vcvp-yass/profile_images/TINY v:displayName="Dylan Bussone"

property e:v2k9-msid t:meta.view.tableauthor v:id=vcvp-yass v:profileImageUrlMedium=/api/users/vcvp-yass/profile_images/THUMB v:profileImageUrlLarge=/api/users/vcvp-yass/profile_images/LARGE v:screenName="Dylan Bussone" v:profileImageUrlSmall=/api/users/vcvp-yass/profile_images/TINY v:displayName="Dylan Bussone"
```

## Top Records

```ls
| :updated_at | title                          | description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | data_type | link                                                                                          | image                                       | show | sort_order | 
| =========== | ============================== | =========================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================== | ========= | ============================================================================================= | =========================================== | ==== | ========== | 
| 1385026505  | Video Tutorials                | To help you get started with these tools, we've created a series of videos designed to teach you the basics about interacting with this data site.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | Link      | /videos                                                                                       |                                             | true | 2          | 
| 1385026506  | Learn More                     | With the State of Hawaii's Open Data portal, the State of Hawaii provides residents, analysts, and civic developers with unparalleled access to State data for use in increasing transparency, driving civic innovation, and engaging participants in a more collaborative form of government. Click here to read more about the portal here.                                                                                                                                                                                                                                                                                                               | Link      | /about                                                                                        |                                             | true | 3          | 
| 1385027340  | What's New?                    | The redesign and relaunch of Hawaii's Open Data Portal brings new features and new tools to open data. New charting libraries and new mapping tools allow the creation of dynamic visualizations, and datasets are larger and faster than ever.

The dataset catalog has expanded to more than twice the size it was this time last year, and more are added every day. Click here to explore the entire data catalog, or browse the categories on the right to see what's available.                                                                                                                                                                       |           | /browse                                                                                       | Kkyrge-IAnciELG7pen3_bQFrJNGTD9RVV6HuWLK-i0 | true | 1          | 
| 1385028941  | Welcome to data.hawaii.gov!    | Leading public sector innovators are leveraging cloud, platform and social technologies to deliver better citizen access to information, modernize online service delivery and improve internal efficiencies. We call the transformation of your data assets into productive information resources that people can easily access, share and reuse, Open Data. By sharing our data via data.hawaii.gov in an open and transparent means we empower our citizens, ourselves and our customers to access information anywhere, anytime. Data.hawaii.gov provides a platform to promote our data to a common statewide location that is accessible to everyone. |           | /browse                                                                                       | CMwb1nskjrp5bUetHDc0hCUtlw2o9ULaAZmUltK3iLM |      | 2          | 
| 1385028952  | See Something Missing?         | Suggest a dataset to add!                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |           | /nominate                                                                                     |                                             | true | 9          | 
| 1385028987  | Average Gasoline Prices        | Explore the average monthly gas prices in different parts of Hawaii compared to the state as a whole and the US overall. Chart shows prices over time from 2006 on.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | Chart     | https://data.hawaii.gov/dataset/Average-Monthly-Regular-Gasoline-Prices-Hawaii-by-/hm2n-aire  |                                             | true | 7          | 
| 1385028997  | Farmer's Markets in Hawaii     | "Buy Local, It Matters" at one of many neighborhood farmer's market throughout Hawaii. Check out this map of local farmer's markets, and visit the underlying dataset for schedules and more information.                                                                                                                                                                                                                                                                                                                                                                                                                                                   | Map       | https://data.hawaii.gov/Economic-Development/Hawaii-s-Farmer-s-Market-Statewide-Map/kpdu-pehk | Pir2JnskMrweVTvalghcoz5GDfyyIiT5iE5JURlOPq4 | true | 6          | 
| 1398284047  | Hawaii Electricity Consumption | Data on Hawaii's electricity consumption (totals and per capita) from 1990 to today.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | Chart     | https://data.hawaii.gov/dataset/Hawaii-Electricity-Consumption/mx5j-fw5d                      |                                             | true | 8          | 
```