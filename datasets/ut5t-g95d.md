# Ethnic Media Program

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ethnic-media-program) |
| Metadata | [Link](https://data.seattle.gov/api/views/ut5t-g95d) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/ut5t-g95d/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/ut5t-g95d/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | ut5t-g95d |
| Name | Ethnic Media Program |
| Attribution | Seattle Office of Immigrant and Refugee Affairs |
| Category | Community |
| Created | 2015-11-10T17:35:36Z |
| Publication Date | 2015-11-17T17:07:05Z |

## Columns

```ls
| Included | Schema Type | Field Name     | Name           | Data Type | Render Type |
| ======== | =========== | ============== | ============== | ========= | =========== |
| No       | time        | :updated_at    | updated_at     | meta_data | meta_data   |
| Yes      | series tag  | community      | Community      | text      | text        |
| Yes      | series tag  | name           | Name           | text      | text        |
| Yes      | series tag  | type           | Type           | text      | text        |
| Yes      | series tag  | contact        | Contact        | text      | text        |
| Yes      | series tag  | street_address | Street Address | text      | text        |
| No       |             | address2       | Address2       | text      | text        |
| Yes      | series tag  | city           | City           | text      | text        |
| Yes      | series tag  | state          | State          | text      | text        |
| Yes      | series tag  | zip            | ZIP            | text      | number      |
| Yes      | series tag  | website        | Website        | url       | url         |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address2
```

## Data Commands

```ls
series e:ut5t-g95d d:2015-11-17T09:05:57.000Z t:zip=98122 t:website=http://nwfacts.com/about_us t:name="The Facts" t:state=WA t:community="African American" t:street_address="1112 34th Ave" t:type="Weekly Print Newspaper" t:contact="Elizabeth Beaver ""LaVonne"" (Editor)" t:city=Seattle m:row_number.ut5t-g95d=1

series e:ut5t-g95d d:2015-11-17T09:05:57.000Z t:zip=98144 t:website=http://www.seattlemedium.com t:name="The Seattle Medium Newspaper" t:state=WA t:community="African American" t:street_address="2600 S Jackson" t:type="Online Newspaper/Radio Station" t:contact="Chris B. Bennett" t:city=Seattle m:row_number.ut5t-g95d=2

series e:ut5t-g95d d:2015-11-17T09:05:57.000Z t:zip=98124 t:website=http://www.theskanner.com t:name="The Skanner" t:state=WA t:community="African American" t:street_address="PO Box 94473" t:type=Newspaper t:contact="Lisa Loving (News Editor)" t:city=Seattle m:row_number.ut5t-g95d=3
```

## Meta Commands

```ls
metric m:row_number.ut5t-g95d p:long l:"Row Number"

entity e:ut5t-g95d l:"Ethnic Media Program" t:attribution="Seattle Office of Immigrant and Refugee Affairs" t:url=https://data.seattle.gov/api/views/ut5t-g95d

property e:ut5t-g95d t:meta.view v:id=ut5t-g95d v:category=Community v:attributionLink=http://www.seattle.gov/office-of-immigrant-and-refugee-affairs v:averageRating=0 v:name="Ethnic Media Program" v:attribution="Seattle Office of Immigrant and Refugee Affairs"

property e:ut5t-g95d t:meta.view.license v:name="Public Domain"

property e:ut5t-g95d t:meta.view.owner v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:displayName="Seattle IT"

property e:ut5t-g95d t:meta.view.tableauthor v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:roleName=administrator v:displayName="Seattle IT"
```

## Top Records

```ls
| :updated_at | community                  | name                                                  | type                                              | contact                             | street_address       | address2  | city       | state | zip   | website                                      | 
| =========== | ========================== | ===================================================== | ================================================= | =================================== | ==================== | ========= | ========== | ===== | ===== | ============================================ | 
| 1447751157  | African American           | The Facts                                             | Weekly Print Newspaper                            | Elizabeth Beaver "LaVonne" (Editor) | 1112 34th Ave        |           | Seattle    | WA    | 98122 | [http://nwfacts.com/about_us, null]          | 
| 1447751157  | African American           | The Seattle Medium Newspaper                          | Online Newspaper/Radio Station                    | Chris B. Bennett                    | 2600 S Jackson       |           | Seattle    | WA    | 98144 | [http://www.seattlemedium.com, null]         | 
| 1447751157  | African American           | The Skanner                                           | Newspaper                                         | Lisa Loving (News Editor)           | PO Box 94473         |           | Seattle    | WA    | 98124 | [http://www.theskanner.com, null]            | 
| 1447751157  | Asian (Chinese/Vietnamese) | AAT TV (Asian American TV)                            | Television                                        | David Cho (President)               | 3429 4th Ave         |           | Seattle    | WA    | 98121 | [http://www.aattv.com/, null]                | 
| 1447751157  | Asian (ALL)                | Crossings TV                                          | Television                                        | Cecily Bailey                       | 2030 W El Camino Ave | Suite 263 | Sacramento | CA    | 95833 | [http://www.crossingstv.com, null]           | 
| 1447751157  | Asian (ALL)                | International Examiner                                | Twice monthly Newspaper & Online updated everyday | Travis Quezon                       | 622 S Washington     |           | Seattle    | WA    | 98104 | [http://www.iexaminer.org, null]             | 
| 1447751157  | Asian (ALL)                | International Networks                                | Television                                        | Shelly Kurtz                        | 18 W Mercer St       | #110      | Seattle    | WA    | 98119 | [null, null]                                 | 
| 1447751157  | Asian (ALL)                | Northwest Asian Weekly                                | Weekly Newspaper                                  | Asunta Ng (Publisher)               | 412 Maynard Ave S    |           | Seattle    | WA    | 98104 | [http://www.nwasianweekly.com/page/2/, null] | 
| 1447751157  | Chinese                    | Asia Today                                            | Online Weekly Newspaper                           | John Chou (Publisher)               | PO Box 75461         |           | Seattle    | WA    | 98175 | [http://www.asiatoday.us, null]              | 
| 1447751157  | Chinese                    | KKNW 1150 AM Alternative Talk - Chinese Radio Seattle | Radio                                             | Xiaoyuan Su (CEO)                   | 3650 131st Ave SE    | Suite 550 | Bellevue   | WA    | 98006 | [http://www.chineseradioseattle.com, null]   | 
```