# DEQ Questions

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/deq-questions-4c022) |
| Metadata | [Link](https://data.oregon.gov/api/views/ukc9-nm8j) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/ukc9-nm8j/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/ukc9-nm8j/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | ukc9-nm8j |
| Name | DEQ Questions |
| Created | 2013-05-29T22:01:29Z |
| Publication Date | 2013-06-05T15:48:11Z |

## Columns

```ls
| Included | Schema Type | Field Name   | Name         | Data Type | Render Type |
| ======== | =========== | ============ | ============ | ========= | =========== |
| No       | time        | :updated_at  | updated_at   | meta_data | meta_data   |
| Yes      | series tag  | first_name   | First Name   | text      | text        |
| Yes      | series tag  | last_name    | Last Name    | text      | text        |
| Yes      | series tag  | email        | Email        | email     | email       |
| Yes      | series tag  | organization | Organization | text      | text        |
| Yes      | series tag  | state        | State        | text      | text        |
| Yes      | series tag  | question     | Question     | html      | html        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:ukc9-nm8j d:2013-05-31T14:34:45.000Z t:first_name=Howard t:organization="Sierra Club" t:email=howeird3@gmail.com t:state=Oregon t:last_name=Shapiro t:question="The information regarding diesel emissions deals with rail transport.  What can we expect from the 57 pages of tugboat transferring to the tow line in the river?  Has this been addressed in their application?

Since the port cannot supply adequate emergency fire service, the applicant should be responsible for having their own fire prevention or emergency service.  if a barge catches fire in the river and sinks this could be an enviornmental catastrophe for water sports and fishing.  Many tribal people and river communities depend on the health of the river.  We should not jeapordize Oregonians for the profit of an Australian company that has a non-existant bottom line financially. If there is a costly accident they will pull out and not be responsible." m:row_number.ukc9-nm8j=1

series e:ukc9-nm8j d:2013-05-31T16:53:22.000Z t:first_name=rene t:email=breierrene@yahoo.com t:state=oregon t:last_name=breier t:question="what arrangements will be made if permitting is approved and then Ambre (and they are known for this) does not comply. Once the process is in motion, what arrangements does DEQ propose to cleanup oil spills, air pollution not anticipated etc." m:row_number.ukc9-nm8j=2

series e:ukc9-nm8j d:2013-06-06T23:18:39.000Z t:first_name=Thomas t:email=hons@gorge.net t:state=Oregon t:last_name=Hons t:question="What would be the effect of coal spilling in rivers? How much oxygen demand would ensue and what would be the time frame?" m:row_number.ukc9-nm8j=3
```

## Meta Commands

```ls
metric m:row_number.ukc9-nm8j p:long l:"Row Number"

entity e:ukc9-nm8j l:"DEQ Questions" t:url=https://data.oregon.gov/api/views/ukc9-nm8j

property e:ukc9-nm8j t:meta.view v:id=ukc9-nm8j v:averageRating=0 v:name="DEQ Questions"

property e:ukc9-nm8j t:meta.view.owner v:id=7f2t-e4kt v:screenName="Mary-Frances Makichen" v:displayName="Mary-Frances Makichen"

property e:ukc9-nm8j t:meta.view.tableauthor v:id=7f2t-e4kt v:screenName="Mary-Frances Makichen" v:displayName="Mary-Frances Makichen"
```

## Top Records

```ls
| :updated_at | first_name | last_name     | email                    | organization             | state      | question                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | 
| =========== | ========== | ============= | ======================== | ======================== | ========== | ===================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================== | 
| 1370010885  | Howard     | Shapiro       | howeird3@gmail.com       | Sierra Club              | Oregon     | The information regarding diesel emissions deals with rail transport. What can we expect from the 57 pages of tugboat transferring to the tow line in the river? Has this been addressed in their application? Since the port cannot supply adequate emergency fire service, the applicant should be responsible for having their own fire prevention or emergency service. if a barge catches fire in the river and sinks this could be an enviornmental catastrophe for water sports and fishing. Many tribal people and river communities depend on the health of the river. We should not jeapordize Oregonians for the profit of an Australian company that has a non-existant bottom line financially. If there is a costly accident they will pull out and not be responsible. | 
| 1370019202  | rene       | breier        | breierrene@yahoo.com     |                          | oregon     | what arrangements will be made if permitting is approved and then Ambre (and they are known for this) does not comply. Once the process is in motion, what arrangements does DEQ propose to cleanup oil spills, air pollution not anticipated etc.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | 
| 1370560719  | Thomas     | Hons          | hons@gorge.net           |                          | Oregon     | What would be the effect of coal spilling in rivers? How much oxygen demand would ensue and what would be the time frame?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | 
| 1370863867  | Tom        | Barron        | tbarron@hevanet.com      | NONE                     | OR         | I read an article that said DEQ was ready to issue a permit for the Morrow Pacific project to start construction. It said the condition/quality of the Columbia River Gorge as a result of the coal trains was none of their concern. I'm confused....Isn't the condition of the Gorge part of the environment, and therefore of interest to DEQ?                                                                                                                                                                                                                                                                                                                                                                                                                                     | 
| 1372257051  | Tova       | Woyciechowicz | tova@oregonrural.org     | Oregon Rural Action      | OR         | Many of our members want to talk about the relationship between Coyote Island Terminal LLC Permits and Climate Change. Is that something that DEQ can/will consider in decision making? Thanks, Tova                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | 
| 1372275095  | Dave       | Shelman       | dave.w.shelman@gmail.com | citizen                  | OR         | How can I see the draft permits for the Coyote Island Terminal?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | 
| 1373112297  | Bart       | Preecs        | bpreecs@gmail.com        | Citizens Climate Lobby   | WA         | Did any federal official responded to the letters from Gov. Kitzhaber and Gov. Inslee? Are those responses, if any, available online? Thanks                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | 
| 1373143665  | Norman     | Osterman      | nosterman@hotmail.com    | Walla Wala Progressives  | Washington | Just to be clear, your air quality info says total HAP's/yr in tons are 6.7E06 1) What does E06 mean 2) If you alright with 6.7 tons of a mixture of arsenic, lead, chromium, mercury, etc escaping, then you are the DEW: Dept of Environmental Whatever--am I reading the 6.7 tons correctly?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | 
| 1373144075  | Norman     | Osterman      | nosterman@hotmail.com    | Walla Walla Progressives | WA         | Secondary emissions (tugs, trains, etc) "...should not be included in the emission inventory." " Should not" is the stuff of an opinion. Is there the slightest chance the DEQ could change their opinion to a common sense one that coyote Island is a linchpin in creating all the emissions, starting with mining the coal.                                                                                                                                                                                                                                                                                                                                                                                                                                                        | 
| 1373144254  | Norman     | Osterman      | nosterman@hotmail.com    | Walla Walla Progressives | Washington | The water table is 17-45 ft. down according to you. Is this a shallow gravel aquifer? Is is used as potable drinking water in the area? If so, how large an area does in cover?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | 
```