# Education Programs Offered in Hudson River Park: Beginning 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/education-programs-offered-in-hudson-river-park-beginning-2013) |
| Metadata | [Link](https://data.ny.gov/api/views/by6w-btmk) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/by6w-btmk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/by6w-btmk/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | by6w-btmk |
| Name | Education Programs Offered in Hudson River Park: Beginning 2013 |
| Attribution | Hudson River Park Trust (HRPT) |
| Category | Education |
| Tags | education, learning, hrpt |
| Created | 2014-11-04T18:19:00Z |
| Publication Date | 2015-12-23T18:40:56Z |

## Description

This dataset is a list of educational programs offered by Hudson River Park Trust (HRPT) and includes the type of program, the date of the first and last offerings, and participation numbers.

## Columns

```ls
| Included | Schema Type    | Field Name                                 | Name                                       | Data Type     | Render Type   |
| ======== | ============== | ========================================== | ========================================== | ============= | ============= |
| Yes      | series tag     | program_name                               | Program Name                               | text          | text          |
| Yes      | series tag     | program_type                               | Program Type                               | text          | text          |
| Yes      | time           | start_date                                 | Start Date                                 | calendar_date | calendar_date |
| No       |                | end_date                                   | End Date                                   | calendar_date | calendar_date |
| Yes      | numeric metric | number_of_programs                         | Number of Programs                         | number        | number        |
| Yes      | numeric metric | total_number_of_participants               | Total Number of Participants               | number        | number        |
| Yes      | numeric metric | average_number_of_participants_per_program | Average Number of Participants Per Program | number        | number        |
```

## Time Field

```ls
Value = start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = end_date
```

## Data Commands

```ls
series e:by6w-btmk d:2013-05-26T00:00:00.000Z t:program_type="Public Programs" t:program_name="Big City Fishing @ Pier 84" m:average_number_of_participants_per_program=54 m:number_of_programs=16 m:total_number_of_participants=869

series e:by6w-btmk d:2013-06-27T00:00:00.000Z t:program_type="Public Programs" t:program_name="Big City Fishing @ Pier 25" m:average_number_of_participants_per_program=75 m:number_of_programs=11 m:total_number_of_participants=821

series e:by6w-btmk d:2013-06-25T00:00:00.000Z t:program_type="Public Programs" t:program_name="Big City Fishing @ Pier 46" m:average_number_of_participants_per_program=57 m:number_of_programs=11 m:total_number_of_participants=628
```

## Meta Commands

```ls
metric m:number_of_programs p:integer l:"Number of Programs" d:"The total number of times the program was offered throughout the season." t:dataTypeName=number

metric m:total_number_of_participants p:integer l:"Total Number of Participants" d:"The total number of people who participated in the program throughout the season" t:dataTypeName=number

metric m:average_number_of_participants_per_program p:integer l:"Average Number of Participants Per Program" d:"The average number of people who participated per program (the total number of participants divided by the number of programs)" t:dataTypeName=number

entity e:by6w-btmk l:"Education Programs Offered in Hudson River Park:  Beginning 2013" t:attribution="Hudson River Park Trust (HRPT)" t:url=https://data.ny.gov/api/views/by6w-btmk

property e:by6w-btmk t:meta.view v:id=by6w-btmk v:category=Education v:attributionLink=http://www.hudsonriverpark.org/education-and-environment v:averageRating=0 v:name="Education Programs Offered in Hudson River Park:  Beginning 2013" v:attribution="Hudson River Park Trust (HRPT)"

property e:by6w-btmk t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:by6w-btmk t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:by6w-btmk t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| program_name                  | program_type         | start_date          | end_date            | number_of_programs | total_number_of_participants | average_number_of_participants_per_program | 
| ============================= | ==================== | =================== | =================== | ================== | ============================ | ========================================== | 
| Big City Fishing @ Pier 84    | Public Programs      | 2013-05-26T00:00:00 | 2013-09-29T00:00:00 | 16                 | 869                          | 54                                         | 
| Big City Fishing @ Pier 25    | Public Programs      | 2013-06-27T00:00:00 | 2013-08-29T00:00:00 | 11                 | 821                          | 75                                         | 
| Big City Fishing @ Pier 46    | Public Programs      | 2013-06-25T00:00:00 | 2013-08-27T00:00:00 | 11                 | 628                          | 57                                         | 
| Big City Fishing @ Pier 63    | Public Programs      | 2013-07-07T00:00:00 | 2013-09-01T00:00:00 | 10                 | 621                          | 62                                         | 
| River Tots @ Pier 25          | Public Programs      | 2013-06-02T00:00:00 | 2013-09-26T00:00:00 | 13                 | 390                          | 30                                         | 
| River Tots @ Pier46           | Public Programs      | 2013-05-30T00:00:00 | 2013-09-24T00:00:00 | 13                 | 350                          | 27                                         | 
| Hudson River Park WILD!       | Public Programs      | 2013-04-07T00:00:00 | 2013-09-29T00:00:00 | 22                 | 105                          | 5                                          | 
| Estuary Adventures - Fish     | Summer Camp Programs | 2013-06-25T00:00:00 | 2013-08-30T00:00:00 | 102                | 3256                         | 32                                         | 
| Estuary Adventures - Plankton | Summer Camp Programs | 2013-06-25T00:00:00 | 2013-08-30T00:00:00 | 15                 | 386                          | 26                                         | 
| Urban Naturalist              | Summer Camp Programs | 2013-06-25T00:00:00 | 2013-08-30T00:00:00 | 25                 | 770                          | 31                                         | 
```