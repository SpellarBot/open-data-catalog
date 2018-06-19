# Category Information

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/category-information-61e7d) |
| Metadata | [Link](https://data.hawaii.gov/api/views/yv27-ghxi) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/yv27-ghxi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/yv27-ghxi/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | yv27-ghxi |
| Name | Category Information |
| Created | 2012-07-06T17:10:34Z |
| Publication Date | 2013-11-20T06:54:08Z |

## Description

Dataset to configure categories on the Home page

## Columns

```ls
| Included | Schema Type | Field Name      | Name            | Data Type | Render Type |
| ======== | =========== | =============== | =============== | ========= | =========== |
| No       | time        | :updated_at     | updated_at      | meta_data | meta_data   |
| Yes      | series tag  | category        | category        | text      | text        |
| Yes      | series tag  | link            | link            | text      | text        |
| Yes      | series tag  | home_page_title | home page title | text      | text        |
| Yes      | series tag  | home_page_text  | home page text  | text      | text        |
| Yes      | series tag  | featured        | featured        | text      | text        |
| Yes      | series tag  | photo           | Photo           | photo     | photo       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:yv27-ghxi d:2013-01-08T17:58:44.000Z t:category="Culture and Recreation" t:home_page_text="To enrich the lives of people of all ages by providing and preserving opportunities and facilities for cultural and recreational activities." t:link=culture_and_recreation t:featured=yes t:photo=ggBb5EmJEEQSqHZrK8dXA_ryUAOH7Urr3jjP0mfhYpo t:home_page_title="Culture and Recreation" m:row_number.yv27-ghxi=1

series e:yv27-ghxi d:2013-01-08T17:58:53.000Z t:category="Economic Development" t:home_page_text="To assist in maintaining the States economy in a strong and competitive condition by providing policies, operations, facilities, services, advice and information so as to achieve appropriate rates of growth, high levels of employment, reasonable returns on investments, and steady gain in personal incomes in a balanced fashion in all sectors of the economy and areas of the State." t:link=economic_development t:photo=925nl_sPBR0JNO7mkuPeiFJNRu8TPNIFCOiVkYA78xw t:home_page_title="Economic Development" m:row_number.yv27-ghxi=2

series e:yv27-ghxi d:2013-01-08T17:59:08.000Z t:category=Employment t:home_page_text="To assure all workers full and equal opportunity to work, decent working conditions, fair treatment on the job, equitable compensation, and assistance in work-related difficulties." t:link=employment t:featured=yes t:photo=EUNpYVf005Ha8pSGW73ctXQbbHW-8BKcNr6U72J66PY t:home_page_title=Employment m:row_number.yv27-ghxi=3
```

## Meta Commands

```ls
metric m:row_number.yv27-ghxi p:long l:"Row Number"

entity e:yv27-ghxi l:"Category Information" t:url=https://data.hawaii.gov/api/views/yv27-ghxi

property e:yv27-ghxi t:meta.view v:id=yv27-ghxi v:averageRating=0 v:name="Category Information"

property e:yv27-ghxi t:meta.view.owner v:id=zs8p-j3v5 v:profileImageUrlMedium=/api/users/zs8p-j3v5/profile_images/THUMB v:profileImageUrlLarge=/api/users/zs8p-j3v5/profile_images/LARGE v:screenName="Darrell Cabales" v:profileImageUrlSmall=/api/users/zs8p-j3v5/profile_images/TINY v:displayName="Darrell Cabales"

property e:yv27-ghxi t:meta.view.tableauthor v:id=zs8p-j3v5 v:profileImageUrlMedium=/api/users/zs8p-j3v5/profile_images/THUMB v:profileImageUrlLarge=/api/users/zs8p-j3v5/profile_images/LARGE v:screenName="Darrell Cabales" v:profileImageUrlSmall=/api/users/zs8p-j3v5/profile_images/TINY v:displayName="Darrell Cabales"
```

## Top Records

```ls
| :updated_at | category                 | link                     | home_page_title          | home_page_text                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | featured | photo                                       | 
| =========== | ======================== | ======================== | ======================== | ===================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================== | ======== | =========================================== | 
| 1357667924  | Culture and Recreation   | culture_and_recreation   | Culture and Recreation   | To enrich the lives of people of all ages by providing and preserving opportunities and facilities for cultural and recreational activities.                                                                                                                                                                                                                                                                                                                                                          | yes      | ggBb5EmJEEQSqHZrK8dXA_ryUAOH7Urr3jjP0mfhYpo | 
| 1357667933  | Economic Development     | economic_development     | Economic Development     | To assist in maintaining the States economy in a strong and competitive condition by providing policies, operations, facilities, services, advice and information so as to achieve appropriate rates of growth, high levels of employment, reasonable returns on investments, and steady gain in personal incomes in a balanced fashion in all sectors of the economy and areas of the State.                                                                                                         |          | 925nl_sPBR0JNO7mkuPeiFJNRu8TPNIFCOiVkYA78xw | 
| 1357667948  | Employment               | employment               | Employment               | To assure all workers full and equal opportunity to work, decent working conditions, fair treatment on the job, equitable compensation, and assistance in work-related difficulties.                                                                                                                                                                                                                                                                                                                  | yes      | EUNpYVf005Ha8pSGW73ctXQbbHW-8BKcNr6U72J66PY | 
| 1357667955  | Formal Education         | formal_education         | Formal Education         | To maximize the realization of each individual's intellectual potential, to contribute to personal development, enhance social effectiveness, and provide the basis for satisfying vocations by making available a graduated and integrated series of high quality formal education programs; to add to the sum of human knowledge by conducting basic and applied research; and to enhance the welfare of the community by offering instruction and other services of benefit to the general public. | yes      | uMApJ9EJTNsFWoAGXKpwTxoMp-DIHrHYe0naHrJFJMY | 
| 1357667962  | Environmental Protection | environmental_protection | Environmental Protection | To restore, protect, and enhance, where appropriate, the natural and person-made physical environment.                                                                                                                                                                                                                                                                                                                                                                                                |          | j3_WYM2K-V4AxYSJETlWIIrw48XKPZ8hvwy_-YMS5PY | 
| 1357667965  | Government-Wide Support  | government-wide_support  | Government-wide Support  | To enhance the effectiveness and efficiency of State programs by providing executive direction, program coordination, and policy development as well as a wide variety of services supporting the work of State government as a whole or common to all or most programs.                                                                                                                                                                                                                              |          | icqjGTYQWsbr6wY3h2qM5HX3fJxCIo7AYsteWMwdysQ | 
| 1357667973  | Health                   | health                   | Health                   | To monitor, protect, and enhance the health of all people in Hawai'i by providing leadership in assesssment, policy development, and assurance to promote health and well-being, to preserve a clean, healthy and natural environment, and to assure basic health care for all.                                                                                                                                                                                                                       | yes      | sWn8-xWnjOUvOYhZ9qYZRaFJQJDMcWO6dCrhP4L0C_Q | 
| 1357667975  | Individual Rights        | individual_rights        | Individual Rights        | To ensure that the individual is provided with services and products meeting acceptable standards of quality, dependability and safety; given equitable and responsive treatment by public agencies; and afforded equal protection of legal and civil rights and interests.                                                                                                                                                                                                                           |          | DtQ6qko3tas4KvK08vN04vTA6Hd6jvkeKUTLexdsI9o | 
| 1357667981  | Public Safety            | public_safety            | Public Safety            | To protect the individual and property from injury and loss caused by criminal actions, accidents, physical hazards, and natural and man-made disasters.                                                                                                                                                                                                                                                                                                                                              | yes      | zATLn4gkDM1dYv0LDPgBXc7I7Kb5QuOhiMq_J8sDjIQ | 
| 1357668031  | Social Services          | social_services          | Social Services          | To enable individuals and families in need to attain a minimally adequate standard of living and to achieve the social and psychological adjustments necessary to successfully live in modern society.                                                                                                                                                                                                                                                                                                |          | bRcwT5opELbuBCaY3-ZoUO9L2EOIxXaGWSBeRK7lvvc | 
```