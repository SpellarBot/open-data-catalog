# NYC Service: Volunteer Opportunities

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nyc-service-volunteer-opportunities-8434b) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/bquu-z2ht) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/bquu-z2ht/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/bquu-z2ht/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | bquu-z2ht |
| Name | NYC Service: Volunteer Opportunities |
| Attribution | NYC Service (NYCSERVICE) |
| Category | Social Services |
| Tags | jobs and economic mobility, volunteering, volunteers, volunteer opportunities, events, volunteer organizations, lifelong learning |
| Created | 2011-09-30T19:21:53Z |
| Publication Date | 2013-06-21T19:31:46Z |

## Description

A list of volunteer opportunities, organized by event, category of event type, organization and location. Update Frequency: As needed

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| No       | time           | :updated_at        | updated_at         | meta_data | meta_data   |
| Yes      | series tag     | opportunity_id     | opportunity_id     | text      | number      |
| Yes      | series tag     | content_id         | content_id         | text      | number      |
| Yes      | numeric metric | vol_requests       | vol_requests       | number    | number      |
| No       |                | event_time         | event_time         | number    | number      |
| Yes      | series tag     | title              | title              | text      | text        |
| Yes      | numeric metric | hits               | hits               | number    | number      |
| Yes      | series tag     | summary            | summary            | text      | text        |
| Yes      | series tag     | is_priority        | is_priority        | text      | text        |
| Yes      | series tag     | category_id        | category_id        | text      | number      |
| Yes      | series tag     | category_desc      | category_desc      | text      | text        |
| Yes      | series tag     | amsl               | amsl               | text      | text        |
| Yes      | series tag     | amsl_unit          | amsl_unit          | text      | text        |
| Yes      | series tag     | org_title          | org_title          | text      | text        |
| Yes      | series tag     | org_content_id     | org_content_id     | text      | number      |
| No       |                | addresses_count    | addresses_count    | number    | number      |
| Yes      | series tag     | region             | region             | text      | text        |
| Yes      | series tag     | postalcode         | postalcode         | text      | number      |
| Yes      | series tag     | primary_loc        | primary_loc        | text      | text        |
| Yes      | series tag     | display_url        | display_url        | text      | text        |
| Yes      | series tag     | recurrence_type    | recurrence_type    | text      | text        |
| Yes      | numeric metric | hours              | hours              | number    | number      |
| No       |                | created_date       | created_date       | text      | text        |
| No       |                | last_modified_date | last_modified_date | text      | text        |
| No       |                | start_date_date    | start_date_date    | text      | text        |
| No       |                | end_date_date      | end_date_date      | text      | text        |
| Yes      | series tag     | status             | status             | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = event_time,addresses_count,created_date,last_modified_date,start_date_date,end_date_date
```

## Data Commands

```ls
series e:bquu-z2ht d:2011-09-30T12:22:20.000Z t:summary="Building on successful events last summer and earlier this year in the Bronx and in Queens, the Center for NYC Neighborhoods (CNYCN) and its partners are now organizing the last 2011 Rise Up & Stay Put! Home Rescue Fair. It will be on Saturday, July 30 at Long Island University in Brooklyn." t:region=NY t:opportunity_id=4996 t:org_title="Center For NYC Neighborhoods" t:title="Volunteers Needed For Rise Up & Stay Put! Home Rescue Fair" t:content_id=37004 t:status=approved t:recurrence_type=onetime t:org_content_id=4426 t:display_url=/opportunities/4996 m:hits=737 m:hours=0 m:vol_requests=50

series e:bquu-z2ht d:2011-09-30T12:24:17.000Z t:summary="Build a website for an Afghan business" t:region=NY t:opportunity_id=5008 t:org_title=Bpeace t:postalcode=10010 t:title="Web designer" t:content_id=37036 t:status=approved t:recurrence_type=onetime t:org_content_id=37026 t:category_id=1 t:display_url=/opportunities/5008 t:category_desc="Strengthening Communities" m:hits=22 m:hours=0 m:vol_requests=2

series e:bquu-z2ht d:2011-09-30T12:22:20.000Z t:summary="Please join us and the students from Mott Hall on Saturday, January 29th, for an ice skating trip to Lasker Lanes!" t:region=NY t:opportunity_id=5016 t:org_title="Street Project" t:postalcode=10026 t:title="Urban Adventures - Ice Skating at Lasker Rink" t:content_id=37143 t:status=approved t:recurrence_type=onetime t:org_content_id=3001 t:category_id=1 t:display_url=/opportunities/5016 t:category_desc="Strengthening Communities" m:hits=62 m:hours=0 m:vol_requests=20
```

## Meta Commands

```ls
metric m:vol_requests p:integer l:vol_requests t:dataTypeName=number

metric m:hits p:integer l:hits t:dataTypeName=number

metric m:hours p:integer l:hours t:dataTypeName=number

entity e:bquu-z2ht l:"NYC Service: Volunteer Opportunities" t:attribution="NYC Service (NYCSERVICE)" t:url=https://data.cityofnewyork.us/api/views/bquu-z2ht

property e:bquu-z2ht t:meta.view v:id=bquu-z2ht v:category="Social Services" v:averageRating=0 v:name="NYC Service: Volunteer Opportunities" v:attribution="NYC Service (NYCSERVICE)"

property e:bquu-z2ht t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:bquu-z2ht t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | opportunity_id | content_id | vol_requests | event_time | title                                                                               | hits | summary                                                                                                                                                                                                                                                                                             | is_priority | category_id | category_desc             | amsl | amsl_unit | org_title                                                | org_content_id | addresses_count | region | postalcode | primary_loc | display_url         | recurrence_type | hours | created_date     | last_modified_date | start_date_date  | end_date_date    | status   | 
| =========== | ============== | ========== | ============ | ========== | =================================================================================== | ==== | =================================================================================================================================================================================================================================================================================================== | =========== | =========== | ========================= | ==== | ========= | ======================================================== | ============== | =============== | ====== | ========== | =========== | =================== | =============== | ===== | ================ | ================== | ================ | ================ | ======== | 
| 1317385340  | 4996           | 37004      | 50           | 0          | Volunteers Needed For Rise Up & Stay Put! Home Rescue Fair                          | 737  | Building on successful events last summer and earlier this year in the Bronx and in Queens, the Center for NYC Neighborhoods (CNYCN) and its partners are now organizing the last 2011 Rise Up & Stay Put! Home Rescue Fair. It will be on Saturday, July 30 at Long Island University in Brooklyn. |             |             |                           |      |           | Center For NYC Neighborhoods                             | 4426           | 1               | NY     |            |             | /opportunities/4996 | onetime         | 0     | January 13 2011  | June 23 2011       | July 30 2011     | July 30 2011     | approved | 
| 1317385457  | 5008           | 37036      | 2            | 0          | Web designer                                                                        | 22   | Build a website for an Afghan business                                                                                                                                                                                                                                                              |             | 1           | Strengthening Communities |      |           | Bpeace                                                   | 37026          | 1               | NY     | 10010      |             | /opportunities/5008 | onetime         | 0     | January 14 2011  | January 25 2011    | February 01 2011 | February 01 2011 | approved | 
| 1317385340  | 5016           | 37143      | 20           | 0          | Urban Adventures - Ice Skating at Lasker Rink                                       | 62   | Please join us and the students from Mott Hall on Saturday, January 29th, for an ice skating trip to Lasker Lanes!                                                                                                                                                                                  |             | 1           | Strengthening Communities |      |           | Street Project                                           | 3001           | 1               | NY     | 10026      |             | /opportunities/5016 | onetime         | 0     | January 19 2011  | January 21 2011    | January 29 2011  | January 29 2011  | approved | 
| 1317385340  | 5022           | 37237      | 500          | 0          | Fight global hunger and support women farmers - Join the Oxfam Action Corps in NYC! | 14   | The Oxfam Action Corps is a group of dedicated volunteers that raise awareness by holding events and reaching out to people in our neighborhoods, town events, rock concerts ? and, most importantly, in the halls of Congress. Sign up by February 14: http://www.oxfamactioncorps.org             |             | 1           | Strengthening Communities |      |           | Oxfam America                                            | 2170           | 1               | NY     | 2114       |             | /opportunities/5022 | ongoing         | 0     | January 21 2011  | January 25 2011    | February 14 2011 | March 31 2012    | approved | 
| 1317385340  | 5055           | 37425      | 15           | 0          | Stop 'N' Swap                                                                       | 31   | Stop 'N' Swap reduces NYC's waste by finding new homes for unwanted, but usable items. Help sort, fold and display items to make this a fun free reuse experience for all.                                                                                                                          |             | 4           | Environment               |      |           | Office of Recycling Outreach and Education               | 36773          | 1               | NY     | 10455      |             | /opportunities/5055 | onetime         | 0     | January 28 2011  | February 01 2011   | February 05 2011 | February 05 2011 | approved | 
| 1317385340  | 5056           | 37426      | 15           | 0          | Queens Stop 'N' Swap                                                                | 135  | Stop 'N' Swap reduces NYC's waste by finding new homes for unwanted, but usable items. Help sort, fold and display items to make this a fun free reuse experience for all.                                                                                                                          |             | 4           | Environment               |      |           | Office of Recycling Outreach and Education               | 36773          | 1               | NY     | 11372      |             | /opportunities/5056 | onetime         | 0     | January 28 2011  | January 28 2011    | February 12 2011 | February 12 2011 | approved | 
| 1317385436  | 5053           | 37406      | 2            | 0          | Staff Development Trainer                                                           | 156  | The Jewish Museum seeks a volunteer staff development trainer.                                                                                                                                                                                                                                      |             | 1           | Strengthening Communities |      |           | The Jewish Museum                                        | 37348          | 1               | NY     | 10128      |             | /opportunities/5053 | ongoing         | 0     | January 27 2011  | January 28 2011    | January 27 2011  | January 27 2012  | approved | 
| 1317385340  | 5085           | 37652      | 20           | 0          | CLARO Brooklyn Volunteer Attorney                                                   | 4407 | Provide legal advice, information and resources to individuals facing consumer debt cases in Kings County Civil Court. Use your legal skills to give self-represented litigants the tools they need to effectively represent themselves in civil court.                                             | y           | 2           | Helping Neighbors in Need |      |           | Brooklyn Bar Association Volunteer Lawyers Project, Inc. | 3784           | 1               | NY     | 11201      |             | /opportunities/5085 | ongoing         | 0     | February 07 2011 | August 11 2011     | February 07 2011 | February 07 2012 | approved | 
| 1317385340  | 5091           | 37730      | 100          | 0          | Join Cents Ability!                                                                 | 325  | Join the Cents Ability volunteer corps to teach, mentor and coach young people to achieve their financial goals!                                                                                                                                                                                    |             |             |                           |      |           | Cents Ability, Inc.                                      | 37154          | 1               | NY     | 10020      |             | /opportunities/5091 | ongoing         | 0     | February 09 2011 | February 09 2011   | February 08 2011 | February 08 2012 | approved | 
| 1317385340  | 5093           | 37741      | 1            | 0          | Volunteer-Community Health Advocates                                                | 928  | Community Health Advocates (CHA);formerly NYC Managed Care Consumer Assistance Program or NYC MCCAP provides information, advice, and navigational assistance to New Yorkers.                                                                                                                       |             | 5           | Health                    |      |           | Community Service Society of New York                    | 37737          | 1               | NY     | 10010      |             | /opportunities/5093 | ongoing         | 0     | February 09 2011 | February 11 2011   | February 14 2011 | February 09 2012 | approved | 
```