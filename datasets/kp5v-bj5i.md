# Parkranger 2016 10

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/parkranger-2016-10) |
| Metadata | [Link](https://data.austintexas.gov/api/views/kp5v-bj5i) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/kp5v-bj5i/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/kp5v-bj5i/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | kp5v-bj5i |
| Name | Parkranger 2016 10 |
| Attribution | City of Austin |
| Created | 2016-10-13T16:40:29Z |
| Publication Date | 2017-02-24T16:53:50Z |

## Columns

```ls
| Included | Schema Type | Field Name             | Name                   | Data Type     | Render Type   |
| ======== | =========== | ====================== | ====================== | ============= | ============= |
| Yes      | time        | date                   | Date                   | calendar_date | calendar_date |
| Yes      | series tag  | event_or_activity      | Event or Activity      | text          | text          |
| Yes      | series tag  | location_name          | Location Name          | text          | text          |
| No       |             | time_of_event          | Time of Event          | text          | text          |
| Yes      | series tag  | details                | Details                | text          | text          |
| Yes      | series tag  | additional_information | Additional Information | text          | text          |
| Yes      | series tag  | drop_in_pop_up         | Drop-in/Pop-up         | text          | text          |
| Yes      | series tag  | staff                  | Staff                  | text          | text          |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = time_of_event
```

## Data Commands

```ls
series e:kp5v-bj5i d:2016-10-03T00:00:00.000Z t:staff="melissa, michelle" t:location_name="Vic Mathias" t:details="Rangers will be displaying a touch table of bones and pelts to showcase some interesting wildlife from our area. Come learn about wildlife!" t:event_or_activity="Touch Table" t:drop_in_pop_up=Pop-up t:additional_information="No registration necessary" m:row_number.kp5v-bj5i=1

series e:kp5v-bj5i d:2016-10-05T00:00:00.000Z t:staff=melissa t:location_name="Mayfield Park" t:details="Join a Ranger for a brief Introduction of the historic Mayfield Preserve before you enjoy the grounds at your own pace." t:event_or_activity="Walking History Tour: Mayfield" t:drop_in_pop_up=Pop-up t:additional_information="No registration necessary" m:row_number.kp5v-bj5i=2

series e:kp5v-bj5i d:2016-10-05T00:00:00.000Z t:staff=michelle t:location_name="Barton Springs Pool" t:details="Take only pictures and leave only footsteps! Join a Ranger and fellow photography enthusiasts for a brief introduction to the history of Nature Photography followed by some opportunities to snap some cool pictures of the historic Barton Springs Pool area." t:event_or_activity="Nature Photography walk" t:drop_in_pop_up=Pop-up t:additional_information="No registration necessary" m:row_number.kp5v-bj5i=3
```

## Meta Commands

```ls
metric m:row_number.kp5v-bj5i p:long l:"Row Number"

entity e:kp5v-bj5i l:"Parkranger 2016 10" t:attribution="City of Austin" t:url=https://data.austintexas.gov/api/views/kp5v-bj5i

property e:kp5v-bj5i t:meta.view v:id=kp5v-bj5i v:attributionLink=http://www.austintexas.gov/parkrangers v:averageRating=0 v:name="Parkranger 2016 10" v:attribution="City of Austin"

property e:kp5v-bj5i t:meta.view.license v:name="Public Domain"

property e:kp5v-bj5i t:meta.view.owner v:id=wpqw-45f6 v:screenName=Betty v:displayName=Betty

property e:kp5v-bj5i t:meta.view.tableauthor v:id=wpqw-45f6 v:screenName=Betty v:roleName=editor v:displayName=Betty
```

## Top Records

```ls
| date                | event_or_activity               | location_name                             | time_of_event           | details                                                                                                                                                                                                                                                         | additional_information         | drop_in_pop_up | staff             | 
| =================== | =============================== | ========================================= | ======================= | =============================================================================================================================================================================================================================================================== | ============================== | ============== | ================= | 
| 2016-10-03T00:00:00 | Touch Table                     | Vic Mathias                               | 1:00:00 PM - 2:00:00 PM | Rangers will be displaying a touch table of bones and pelts to showcase some interesting wildlife from our area. Come learn about wildlife!                                                                                                                     | No registration necessary      | Pop-up         | melissa, michelle | 
| 2016-10-05T00:00:00 | Walking History Tour: Mayfield  | Mayfield Park                             | 1:00:00 PM - 2:00:00 PM | Join a Ranger for a brief Introduction of the historic Mayfield Preserve before you enjoy the grounds at your own pace.                                                                                                                                         | No registration necessary      | Pop-up         | melissa           | 
| 2016-10-05T00:00:00 | Nature Photography walk         | Barton Springs Pool                       | 3:00:00 PM-4:00:00 PM   | Take only pictures and leave only footsteps! Join a Ranger and fellow photography enthusiasts for a brief introduction to the history of Nature Photography followed by some opportunities to snap some cool pictures of the historic Barton Springs Pool area. | No registration necessary      | Pop-up         | michelle          | 
| 2016-10-06T00:00:00 | Ranger Talk: Salamander Special | Barton Springs Pool                       | 1:00:00 PM - 2:00:00 PM | Learn some interesting facts from a Ranger about the special Salamanders of Barton Springs. You can learn about their ecology and the conservation project bieng conducted at Eliza Springs.                                                                    | No registration necessary      | Pop-up         | melissa           | 
| 2016-10-06T00:00:00 | L Library: Archery              | South Austin Rec Center                   | 3:30:00 PM-5:30:00 PM   |                                                                                                                                                                                                                                                                 | mary.beyer@austintexas.gov     | Drop-in        |                   | 
| 2016-10-12T00:00:00 | Walking History Tour: Mayfield  | Mayfield                                  | 1:00:00 PM - 2:00:00 PM | Join a Ranger for a brief Introduction of the historic Mayfield Preserve before you enjoy the grounds at your own pace.                                                                                                                                         | No registration necessary      | Pop-up         | melissa           | 
| 2016-10-13T00:00:00 | L Library: Backyard bass        | A.B. Cantu Pan American Recreation Center | 3:30:00 PM-5:30:00 PM   |                                                                                                                                                                                                                                                                 | johnny.saldana@austintexas.gov | Drop-in        |                   | 
| 2016-10-14T00:00:00 | Ranger Talk: Science Art        | Cottage Playground                        | 1:00:00 PM - 2:00:00 PM | Learn how to make your own biodigradable chalk and then use it to make fun Science Art! A ranger will be on site dicussing the value of an important ecological process called Biodegredation and how it works.                                                 | No registration necessary      | Pop-up         | Melissa           | 
| 2016-10-14T00:00:00 | Touch Table                     | Festival Beach                            | 3:00:00 PM-4:00:00 PM   | Rangers will be displaying a touch table of bones and pelts to showcase some interesting wildlife from our area. Come learn about wildlife!                                                                                                                     | No registration necessary      | Pop-up         | michelle          | 
| 2016-10-26T00:00:00 | Nature Photography walk         | Barton Springs Pool                       | 3:00:00 PM-4:00:00 PM   | Take only pictures and leave only footsteps! Join a Ranger and fellow photography enthusiasts for a brief introduction to the history of Nature Photography followed by some opportunities to snap some cool pictures of the historic Barton Springs Pool area. | No registration necessary      | Drop-in        | michelle          | 
```