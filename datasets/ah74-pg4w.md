# 511 NY Events: Beginning 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/511-ny-events-beginning-2010) |
| Metadata | [Link](https://data.ny.gov/api/views/ah74-pg4w) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/ah74-pg4w/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/ah74-pg4w/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | ah74-pg4w |
| Name | 511 NY Events: Beginning 2010 |
| Attribution | New York State Department of Transportation |
| Category | Transportation |
| Tags | 511, incidents, traffic, transit, congestion, construction |
| Created | 2013-05-14T21:25:52Z |
| Publication Date | 2016-08-29T22:30:02Z |

## Description

The 511NY dataset contain historical traffic and transit event information provided by the New York State Department of Transportation (NYSDOT), the New York City Department of Transportation, the New York State Thruway Authority and the Niagara International Transportation Technology Coalition (Buffalo-Niagara Region). The file includes all incidents/accidents, construction projects and special events in New York State that were available on the 511NY traffic and transit map for the time period noted.

## Columns

```ls
| Included | Schema Type | Field Name                 | Name                       | Data Type     | Render Type   |
| ======== | =========== | ========================== | ========================== | ============= | ============= |
| Yes      | series tag  | event_type                 | Event Type                 | text          | text          |
| Yes      | series tag  | organization_name          | Organization Name          | text          | text          |
| Yes      | series tag  | facility_name              | Facility Name              | text          | text          |
| Yes      | series tag  | direction                  | Direction                  | text          | text          |
| Yes      | series tag  | city                       | City                       | text          | text          |
| Yes      | series tag  | county                     | County                     | text          | text          |
| Yes      | series tag  | state                      | State                      | text          | text          |
| Yes      | time        | create_time                | Create Time                | calendar_date | calendar_date |
| No       |             | close_time                 | Close Time                 | calendar_date | calendar_date |
| Yes      | series tag  | event_description          | Event Description          | text          | text          |
| Yes      | series tag  | responding_organization_id | Responding Organization Id | text          | text          |
| No       |             | latitude                   | Latitude                   | number        | number        |
| No       |             | longitude                  | Longitude                  | number        | number        |
```

## Time Field

```ls
Value = create_time
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = close_time,latitude,longitude
```

## Data Commands

```ls
series e:ah74-pg4w d:2012-11-06T08:06:35.000Z t:facility_name=I-290 t:county=Erie t:direction=east t:responding_organization_id=CARS t:event_type=accident t:state=NY t:event_description="NITTEC: accident on I-290 eastbound at I-90; End  Route I-290 until 8:06 AM, 11/07/12." t:organization_name=NITTEC m:row_number.ah74-pg4w=1

series e:ah74-pg4w d:2010-09-11T09:33:17.000Z t:facility_name="US 9" t:county=Saratoga t:responding_organization_id=CARS t:event_type=parade t:state=NY t:event_description="NYSDOT: parade on US 9 at NY 67 (Malta) closed to traffic from 9:45 A.M. until 11:15 A.M." t:organization_name=NYSDOT m:row_number.ah74-pg4w=2

series e:ah74-pg4w d:2010-12-14T10:42:52.000Z t:facility_name=I-290 t:county=Erie t:direction=east t:responding_organization_id=CARS t:event_type=incident t:state=NY t:event_description="NITTEC: incident on I-290 eastbound at NY 384 Delaware Avenue until 10:42 AM, 12/15/10." t:organization_name=NITTEC m:row_number.ah74-pg4w=3
```

## Meta Commands

```ls
metric m:row_number.ah74-pg4w p:long l:"Row Number"

entity e:ah74-pg4w l:"511 NY Events: Beginning 2010" t:attribution="New York State Department of Transportation" t:url=https://data.ny.gov/api/views/ah74-pg4w

property e:ah74-pg4w t:meta.view v:id=ah74-pg4w v:category=Transportation v:attributionLink=http://www.511ny.org/ v:averageRating=0 v:name="511 NY Events: Beginning 2010" v:attribution="New York State Department of Transportation"

property e:ah74-pg4w t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:ah74-pg4w t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:ah74-pg4w t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| event_type       | organization_name | facility_name | direction  | city | county   | state | create_time         | close_time          | event_description                                                                                     | responding_organization_id | latitude | longitude | 
| ================ | ================= | ============= | ========== | ==== | ======== | ===== | =================== | =================== | ===================================================================================================== | ========================== | ======== | ========= | 
| accident         | NITTEC            | I-290         | east       |      | Erie     | NY    | 2012-11-06T08:06:35 | 2012-11-06T08:33:00 | NITTEC: accident on I-290 eastbound at I-90; End Route I-290 until 8:06 AM, 11/07/12.                 | CARS                       | 42.95    | -78.76    | 
| parade           | NYSDOT            | US 9          |            |      | Saratoga | NY    | 2010-09-11T09:33:17 | 2010-09-11T11:16:12 | NYSDOT: parade on US 9 at NY 67 (Malta) closed to traffic from 9:45 A.M. until 11:15 A.M.             | CARS                       | 42.94    | -73.78    | 
| incident         | NITTEC            | I-290         | east       |      | Erie     | NY    | 2010-12-14T10:42:52 | 2010-12-14T10:46:02 | NITTEC: incident on I-290 eastbound at NY 384 Delaware Avenue until 10:42 AM, 12/15/10.               | CARS                       | 42.99    | -78.87    | 
| delays           | NJ DOT - STMC     | NJ 21         | southbound |      |          | NJ    | 2010-12-13T07:31:00 | 2010-12-13T09:42:37 | NJ DOT - STMC: Delays on NJ 21 southbound at Exit 11 - CR 624/River Dr (Passaic) delays due to volume | NJ SWIFT                   | 40.85    | -74.12    | 
| accident         | NYSDOT            | I-90          | west       |      | Albany   | NY    | 2010-12-12T11:55:09 | 2010-12-12T12:47:39 | NYSDOT: accident on I-90 westbound at Loudonville Road; Ramp until 12:45 PM, 12/12/10.                | CARS                       | 42.66    | -73.74    | 
| accident         | NJ DOT - STMC     | I-280         | eastbound  |      |          | NJ    | 2010-12-12T06:16:00 | 2010-12-12T06:38:53 | NJ DOT - STMC: Accident on I-280 eastbound East of Exit 15 - NJ 21 (Newark) left lane closed          | NJ SWIFT                   | 40.74    | -74.17    | 
| accident         | NYSDOT            | I-90          | west       |      | Albany   | NY    | 2010-12-07T08:49:13 | 2010-12-07T09:01:10 | NYSDOT: accident on I-90 westbound at Exit 6; US 9 until 9:45 AM, 12/07/10.                           | CARS                       | 42.67    | -73.75    | 
| accident cleared | NYSDOT            | I-690         | west       |      | Onondaga | NY    | 2010-11-10T10:07:11 | 2010-11-10T11:17:01 | NYSDOT: accident cleared on I-690 westbound at Exit 17 - Bridge Street until 11:15 AM, 11/10/10.      | CARS                       | 43.05    | -76.06    | 
| accident         | NYSDOT - Region 8 | NY 202        | east       |      |          | NY    | 2010-10-15T11:15:06 | 2010-10-15T11:29:23 | NYSDOT - Region 8: Accident on NY 202 Eastbound at Voris Ln. right shoulder blocked                   | NYSDOT - Region 8          | 0.00     | 0.00      | 
| weather related  | NJ Transit Rail   | All Trains    |            |      |          | NJ    | 2010-10-01T07:44:54 | 2010-10-01T09:43:00 | NJ TRANSIT Rail: Due to Weather related All Trains Systemwide 10-15 minute delays                     | TRANSCOM, Jersey City      | 0.00     | 0.00      | 
```