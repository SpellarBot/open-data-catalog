# AISP 1 & 2-Year Tyvek Tag Dealers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/aisp-1-2-year-tyvek-tag-dealers-online-odfw-license-sales-017bf) |
| Metadata | [Link](https://data.oregon.gov/api/views/df3k-buyh) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/df3k-buyh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/df3k-buyh/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | df3k-buyh |
| Name | AISP 1 & 2-Year Tyvek Tag Dealers |
| Attribution | Oregon State Marine Board |
| Category | Recreation |
| Tags | aquatic, invasive, species, permit, program, paddle, craft, vessel, out-of-state, motor boats, boats, non-motorized |
| Created | 2011-09-26T14:13:35Z |
| Publication Date | 2015-07-21T20:16:55Z |

## Description

Where to get the Tyvek AISP Permit. Paddle craft, out-of-state Motor Boats, and other non-motorized vessels 10' and over.

## Columns

```ls
| Included | Schema Type | Field Name                 | Name                       | Data Type | Render Type |
| ======== | =========== | ========================== | ========================== | ========= | =========== |
| No       | time        | :updated_at                | updated_at                 | meta_data | meta_data   |
| Yes      | series tag  | county                     | County                     | text      | text        |
| Yes      | series tag  | name                       | Name                       | text      | text        |
| Yes      | series tag  | hours                      | Hours                      | text      | text        |
| Yes      | series tag  | website                    | Website                    | url       | url         |
| Yes      | series tag  | phone                      | Phone                      | phone     | phone       |
| Yes      | series tag  | icon                       | icon                       | photo     | photo       |
| Yes      | series tag  | type_of_tyvek_permits_sold | Type of Tyvek Permits Sold | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:df3k-buyh d:2012-09-10T08:17:52.000Z t:icon=TCl1Z7GtFuJ6OjPcbkJQbjHxZWxwD6LC4RryT9-j6gE t:phone_number=800-427-6442 t:website=http://www.peaksportscorvallis.com/ t:county="Benton County" t:hours="Mon, Sat 9am-6pm; Tue-Thu 9am-5pm; Fri 9am-8pm; Sun 12pm- 5pm" t:name="Peak Sports, Inc" t:type_of_tyvek_permits_sold="One & Two Year Tyvek Tag" m:row_number.df3k-buyh=1

series e:df3k-buyh d:2012-09-10T08:17:56.000Z t:icon=TCl1Z7GtFuJ6OjPcbkJQbjHxZWxwD6LC4RryT9-j6gE t:phone_number=503-622-3120 t:website=http://www.mtnsportsonhood.com/ t:county="Clackamas County" t:hours=N/A t:name="Mountain Sports" t:type_of_tyvek_permits_sold="One & Two Year Tyvek Tag" m:row_number.df3k-buyh=2

series e:df3k-buyh d:2012-09-10T08:18:03.000Z t:icon=TCl1Z7GtFuJ6OjPcbkJQbjHxZWxwD6LC4RryT9-j6gE t:phone_number=503-659-1156 t:website=http://www.rei.com/stores/102 t:county="Clackamas County" t:hours="Mon-Fri 10am-9pm; Sat 10am-9pm; Sun 11am-6pm" t:name="REI- Clackamas #102" t:type_of_tyvek_permits_sold="One & Two Year Tyvek Tag" m:row_number.df3k-buyh=3
```

## Meta Commands

```ls
metric m:row_number.df3k-buyh p:long l:"Row Number"

entity e:df3k-buyh l:"AISP 1 & 2-Year Tyvek Tag Dealers" t:attribution="Oregon State Marine Board" t:url=https://data.oregon.gov/api/views/df3k-buyh

property e:df3k-buyh t:meta.view v:id=df3k-buyh v:category=Recreation v:attributionLink=http://www.boatoregon.com v:averageRating=0 v:name="AISP 1 & 2-Year Tyvek Tag Dealers" v:attribution="Oregon State Marine Board"

property e:df3k-buyh t:meta.view.owner v:id=a2bu-8256 v:profileImageUrlMedium=/api/users/a2bu-8256/profile_images/THUMB v:profileImageUrlLarge=/api/users/a2bu-8256/profile_images/LARGE v:screenName="Ashley Massey" v:profileImageUrlSmall=/api/users/a2bu-8256/profile_images/TINY v:displayName="Ashley Massey"

property e:df3k-buyh t:meta.view.tableauthor v:id=a2bu-8256 v:profileImageUrlMedium=/api/users/a2bu-8256/profile_images/THUMB v:profileImageUrlLarge=/api/users/a2bu-8256/profile_images/LARGE v:screenName="Ashley Massey" v:profileImageUrlSmall=/api/users/a2bu-8256/profile_images/TINY v:roleName=editor v:displayName="Ashley Massey"
```

## Top Records

```ls
| :updated_at | county            | name                        | hours                                                         | website                                                                                       | phone                | icon                                        | type_of_tyvek_permits_sold | 
| =========== | ================= | =========================== | ============================================================= | ============================================================================================= | ==================== | =========================================== | ========================== | 
| 1347265072  | Benton County     | Peak Sports, Inc            | Mon, Sat 9am-6pm; Tue-Thu 9am-5pm; Fri 9am-8pm; Sun 12pm- 5pm | [http://www.peaksportscorvallis.com/, null]                                                   | [800-427-6442, null] | TCl1Z7GtFuJ6OjPcbkJQbjHxZWxwD6LC4RryT9-j6gE | One & Two Year Tyvek Tag   | 
| 1347265076  | Clackamas County  | Mountain Sports             | N/A                                                           | [http://www.mtnsportsonhood.com/, null]                                                       | [503-622-3120, null] | TCl1Z7GtFuJ6OjPcbkJQbjHxZWxwD6LC4RryT9-j6gE | One & Two Year Tyvek Tag   | 
| 1347265083  | Clackamas County  | REI- Clackamas #102         | Mon-Fri 10am-9pm; Sat 10am-9pm; Sun 11am-6pm                  | [http://www.rei.com/stores/102, null]                                                         | [503-659-1156, null] | TCl1Z7GtFuJ6OjPcbkJQbjHxZWxwD6LC4RryT9-j6gE | One & Two Year Tyvek Tag   | 
| 1347265085  | Clackamas County  | Sportcraft Marina Inc       | Tue-Fri 9am-5:30pm; Sat 9am-4:00pm; Sun-Mon Closed            | [http://www.sportcraftmarina.com/, null]                                                      | [877-662-9965, null] | TCl1Z7GtFuJ6OjPcbkJQbjHxZWxwD6LC4RryT9-j6gE | Two Year Tyvek Tag         | 
| 1347265087  | Clackamas County  | West Coast Adventures, Inc. | 10 a.m. to 6 p.m. summer. Winter -by appt.                    | [http://www.westcoastadventures.com, null]                                                    | [503-729-0818, null] | TCl1Z7GtFuJ6OjPcbkJQbjHxZWxwD6LC4RryT9-j6gE | Two Year Tyvek Tag         | 
| 1347265090  | Clatsop County    | Astoria Scuba & Kayak       | Daily 8am-6pm; excluding federal holidays                     | [http://www.astoriascuba.com/index.php?option=com_content&view=article&id=46&Itemid=75, null] | [503-325-2502, null] | TCl1Z7GtFuJ6OjPcbkJQbjHxZWxwD6LC4RryT9-j6gE | One & Two Year Tyvek Tag   | 
| 1347265095  | Deschutes County  | REI- Bend #96               | Mon-Fri 10am-8pm; Sat 10am-8pm; Sun 11am-6pm                  | [http://www.rei.com/stores/96, null]                                                          | [541-385-0594, null] | TCl1Z7GtFuJ6OjPcbkJQbjHxZWxwD6LC4RryT9-j6gE | One & Two Year Tyvek Tag   | 
| 1347265100  | Douglas County    | City Sporting Goods         | N/A                                                           | [null, null]                                                                                  | [541-459-9295, null] | TCl1Z7GtFuJ6OjPcbkJQbjHxZWxwD6LC4RryT9-j6gE | Two Year Tyvek Tag         | 
| 1347265103  | Hood River County | Big Winds                   | Daily 9am-5:30pm                                              | [http://www.bigwinds.com/, null]                                                              | [888-509-4210, null] | TCl1Z7GtFuJ6OjPcbkJQbjHxZWxwD6LC4RryT9-j6gE | Two Year Tyvek Tags        | 
| 1347265106  | Hood River County | Windance Boardshop          | Mon-Sat 9am-6pm; Sun 9am-5pm                                  | [http://www.windance.com/, null]                                                              | [541-386-2131, null] | TCl1Z7GtFuJ6OjPcbkJQbjHxZWxwD6LC4RryT9-j6gE | One year Tyvek Tag         | 
```