# LRAPAfed

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lrapafed-3aa80) |
| Metadata | [Link](https://data.oregon.gov/api/views/3sv8-uifh) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/3sv8-uifh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/3sv8-uifh/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 3sv8-uifh |
| Name | LRAPAfed |
| Created | 2013-12-16T21:17:31Z |
| Publication Date | 2014-03-11T23:52:33Z |

## Description

rulemaking for permitting requirements

## Columns

```ls
| Included | Schema Type | Field Name          | Name                | Data Type | Render Type |
| ======== | =========== | =================== | =================== | ========= | =========== |
| No       | time        | :updated_at         | updated_at          | meta_data | meta_data   |
| Yes      | series tag  | first_name          | First Name          | text      | text        |
| Yes      | series tag  | last_name           | Last Name           | text      | text        |
| Yes      | series tag  | email_address       | Email Address       | email     | email       |
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
series e:3sv8-uifh d:2014-10-07T01:31:10.000Z t:first_name=nmCOBHauqvFuidRCsasBFgmlhWkODHNnuCXPYfOoaQvCpN t:organization=wWRbA t:last_name=gkbynMQvPvCmqjBEoEukhxdBORCgQpovkNxVjxGChIgfqh t:comment="<a target=""_blank"" href=""http://www.lasvegaslegends.com/orig/buyambien/#t4mh"">Look At This</a> ambien side effects rare - ambien sleeping pill reviews" m:row_number.3sv8-uifh=1

series e:3sv8-uifh d:2014-10-27T02:29:07.000Z t:first_name=sTiBXW t:organization=hCFwm t:last_name=mwMJsR t:comment="<a target=""_blank"" href=""http://www.laluna.com/video/buyxanax/#5w9qa"">xanax generic</a> xanax the side effects - order xanax online no prescription canada" m:row_number.3sv8-uifh=2

series e:3sv8-uifh d:2017-03-12T02:59:40.000Z t:first_name="dep of educationCU" t:organization="online degrees" t:state="United States" t:last_name="education for allCU" t:comment="It's a pity you don't have a donate button! I'd most certainly donate to this superb blog! I guess for now i'll settle for bookmarking and adding your RSS feed to my Google account. I look forward to brand new updates and will share this blog with my Facebook group. Talk soon! 
http://learningtips.eu" t:email_address=klasoonmurphy@inbox.ru m:row_number.3sv8-uifh=3
```

## Meta Commands

```ls
metric m:row_number.3sv8-uifh p:long l:"Row Number"

entity e:3sv8-uifh l:LRAPAfed t:url=https://data.oregon.gov/api/views/3sv8-uifh

property e:3sv8-uifh t:meta.view v:id=3sv8-uifh v:averageRating=0 v:name=LRAPAfed

property e:3sv8-uifh t:meta.view.owner v:id=44u9-wper v:screenName="MT Oregon DEQ" v:displayName="MT Oregon DEQ"

property e:3sv8-uifh t:meta.view.tableauthor v:id=44u9-wper v:screenName="MT Oregon DEQ" v:roleName=editor v:displayName="MT Oregon DEQ"
```

## Top Records

```ls
| :updated_at | first_name                                     | last_name                                      | email_address           | organization           | state         | comment                                                                                                                                                                                                                                                                                                      | additional_document      | 
| =========== | ============================================== | ============================================== | ======================= | ====================== | ============= | ============================================================================================================================================================================================================================================================================================================ | ======================== | 
| 1412645470  | nmCOBHauqvFuidRCsasBFgmlhWkODHNnuCXPYfOoaQvCpN | gkbynMQvPvCmqjBEoEukhxdBORCgQpovkNxVjxGChIgfqh |                         | wWRbA                  |               | Look At This ambien side effects rare - ambien sleeping pill reviews                                                                                                                                                                                                                                         | [null, null, null, null] | 
| 1414376947  | sTiBXW                                         | mwMJsR                                         |                         | hCFwm                  |               | xanax generic xanax the side effects - order xanax online no prescription canada                                                                                                                                                                                                                             | [null, null, null, null] | 
| 1489287580  | dep of educationCU                             | education for allCU                            | klasoonmurphy@inbox.ru  | online degrees         | United States | It's a pity you don't have a donate button! I'd most certainly donate to this superb blog! I guess for now i'll settle for bookmarking and adding your RSS feed to my Google account. I look forward to brand new updates and will share this blog with my Facebook group. Talk soon! http://learningtips.eu | [null, null, null, null] | 
| 1489319793  | higher educationCU                             | educational websites for studentsCU            | klasoonmurphy@inbox.ru  | higher education       | United States | I am genuinely grateful to the holder of this site who has shared this enormous article at at this place. http://educationpoints.eu                                                                                                                                                                          | [null, null, null, null] | 
| 1489360586  | business finance websitesRX                    | financial advisorsRX                           | cliffordpratt69@mail.ru | financial advisor best | Ukraine       | I have learn some excellent stuff here. Definitely worth bookmarking for revisiting. I wonder how much attempt you place to create this sort of great informative site. http://financepoints.eu                                                                                                              | [null, null, null, null] | 
| 1489734283  | higher educationCU                             | online learningCU                              | klasoonmuhlhy@gmail.com | board of education     | United States | Right now it appears like Wordpress is the best blogging platform available right now. (from what I've read) Is that what you're using on your blog? http://educationguide.eu                                                                                                                                | [null, null, null, null] | 
```