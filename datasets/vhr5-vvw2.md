# OIS Dataset 2006-15 - Officers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ois-dataset-2006-15-officers-76edc) |
| Metadata | [Link](https://data.austintexas.gov/api/views/vhr5-vvw2) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/vhr5-vvw2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/vhr5-vvw2/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | vhr5-vvw2 |
| Name | OIS Dataset 2006-15 - Officers |
| Category | Public Safety |
| Tags | police, ois, safety, shooting |
| Created | 2016-06-16T18:02:14Z |
| Publication Date | 2016-06-16T18:04:28Z |

## Description

This Officer-Involved Shooting dataset provides the raw data needed to better understand the characteristics of these incidents in APD's jurisdiction and by APD officers. It is used to assist in identifying training and procedure improvements to improve outcomes.

This report reflects all officer-involved shootings that occurred from 2006 through 2015 in Austin. It includes incidents in which APD or non-APD officers fired their weapons within the city of Austin as well as incidents in which APD officers fired their weapons outside the city of Austin.
Officer-involved shootings are defined as:
-an incident in which an officer fired his/her firearm intentionally at a subject;
-an incident in which an officer fired his/her firearm unintentionally and struck a subject; or
-an incident in which an officer used a less-lethal firearm, struck the subject, and contributed to the subject?s death.


AUSTIN POLICE DEPARTMENT DATA DISCLAIMER
1. The data provided is for informational use only and is not considered official APD crime data as in official Texas DPS or FBI crime reports.
2. APD?s crime database is continuously updated, so reports run at different times may produce different results.  Care should be taken when comparing against other reports as different data collection methods and different data sources may have been used.
3. The Austin Police Department does not assume any liability for any decision made or action taken or not taken by the recipient in reliance upon any information or data provided.

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                     | Data Type     | Render Type   |
| ======== | ============== | ====================== | ======================== | ============= | ============= |
| Yes      | series tag     | case                   | Case #                   | text          | text          |
| Yes      | time           | date                   | Date                     | calendar_date | calendar_date |
| Yes      | series tag     | officer_name           | Officer Name             | text          | text          |
| Yes      | series tag     | rank                   | Rank                     | text          | text          |
| Yes      | series tag     | officer_race_ethnicity | Officer Race/Ethnicity   | text          | text          |
| Yes      | series tag     | officer_gender         | Officer Gender           | text          | text          |
| Yes      | numeric metric | officer_age            | Officer Age              | number        | number        |
| Yes      | series tag     | pd_jurisdiction        | PD Jurisdiction          | text          | text          |
| Yes      | numeric metric | years_le_experience    | Years LE Experience      | number        | number        |
| Yes      | series tag     | prev_ois               | Prev OIS                 | text          | text          |
| Yes      | numeric metric | officer_weapon_caliber | Officer Weapon Caliber   | number        | number        |
| Yes      | series tag     | officer_weapon_type    | Officer Weapon Type      | text          | text          |
| Yes      | numeric metric | shots_fired_by_officer | # Shots Fired by Officer | number        | number        |
| Yes      | series tag     | how_cleared            | How Cleared              | text          | text          |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:vhr5-vvw2 d:2015-07-05T00:00:00.000Z t:rank=ofc t:officer_name="Ofc. Carlos Lopez" t:pd_jurisdiction=APD t:prev_ois=No t:officer_weapon_type="semi-auto / shotgun" t:officer_gender=Male t:case="15-1860826
15-5029094
15-5030656" t:how_cleared=pending t:officer_race_ethnicity=Hispanic m:years_le_experience=9.6 m:officer_age=36 m:shots_fired_by_officer=16

series e:vhr5-vvw2 d:2013-07-26T00:00:00.000Z t:rank=det t:officer_name="Det. Charles ""Trey"" Kleinert" t:pd_jurisdiction=APD t:prev_ois=No t:officer_weapon_type=semi-auto t:officer_gender=Male t:case="13-5033792
13-2071392" t:how_cleared="True Billed on 5/12/2014 (pending further)" t:officer_race_ethnicity=White m:years_le_experience=19 m:officer_weapon_caliber=0.4 m:officer_age=49 m:shots_fired_by_officer=1

series e:vhr5-vvw2 d:2012-04-05T00:00:00.000Z t:rank=ofc t:officer_name="Ofc. Eric Copeland" t:pd_jurisdiction=APD t:prev_ois=No t:officer_weapon_type=semi-auto t:officer_gender=Male t:case="12-5016942
12-0961610" t:how_cleared="No Billed by Grand Jury" t:officer_race_ethnicity=White m:years_le_experience=2 m:officer_weapon_caliber=0.4 m:officer_age=36 m:shots_fired_by_officer=3
```

## Meta Commands

```ls
metric m:officer_age p:integer l:"Officer Age" t:dataTypeName=number

metric m:years_le_experience p:double l:"Years LE Experience" t:dataTypeName=number

metric m:officer_weapon_caliber p:float l:"Officer Weapon Caliber" t:dataTypeName=number

metric m:shots_fired_by_officer p:integer l:"# Shots Fired by Officer" t:dataTypeName=number

entity e:vhr5-vvw2 l:"OIS Dataset 2006-15 - Officers" t:url=https://data.austintexas.gov/api/views/vhr5-vvw2

property e:vhr5-vvw2 t:meta.view v:id=vhr5-vvw2 v:category="Public Safety" v:averageRating=0 v:name="OIS Dataset 2006-15 - Officers"

property e:vhr5-vvw2 t:meta.view.owner v:id=q374-e9d9 v:screenName="Ron MacKay" v:displayName="Ron MacKay"

property e:vhr5-vvw2 t:meta.view.tableauthor v:id=q374-e9d9 v:screenName="Ron MacKay" v:roleName=publisher_stories v:displayName="Ron MacKay"
```

## Top Records

```ls
| case                                        | date                | officer_name                 | rank        | officer_race_ethnicity | officer_gender | officer_age | pd_jurisdiction | years_le_experience | prev_ois | officer_weapon_caliber | officer_weapon_type | shots_fired_by_officer | how_cleared                                | 
| =========================================== | =================== | ============================ | =========== | ====================== | ============== | =========== | =============== | =================== | ======== | ====================== | =================== | ====================== | ========================================== | 
| 15-1860826 15-5029094 15-5030656            | 2015-07-05T00:00:00 | Ofc. Carlos Lopez            | ofc         | Hispanic               | Male           | 36          | APD             | 9.6                 | No       |                        | semi-auto / shotgun | 16                     | pending                                    | 
| 13-5033792 13-2071392                       | 2013-07-26T00:00:00 | Det. Charles "Trey" Kleinert | det         | White                  | Male           | 49          | APD             | 19                  | No       | 0.40                   | semi-auto           | 1                      | True Billed on 5/12/2014 (pending further) | 
| 12-5016942 12-0961610                       | 2012-04-05T00:00:00 | Ofc. Eric Copeland           | ofc         | White                  | Male           | 36          | APD             | 2                   | No       | 0.40                   | semi-auto           | 3                      | No Billed by Grand Jury                    | 
| 09-5052963 09-2280484                       | 2009-08-16T00:00:00 | Agt. John Altum (TABC)       | other - agt | White                  | Male           | 36          | TABC            | 16                  | No       | 0.40                   | semi-auto           | 16                     | No Billed by Grand Jury                    | 
| 13-5052096 13-3141499                       | 2013-11-10T00:00:00 | Ofc. Leonardo Cardenas       | ofc         | Hispanic               | Male           | 34          | APD             | 4                   | No       | 0.223                  | rifle               | 1                      | No Billed by Grand Jury                    | 
| 12-5043966 12-2691696                       | 2012-09-25T00:00:00 | Ofc. George Blanch           | ofc         | White                  | Male           | 36          | APD             | 8                   | No       | 0.40                   | semi-auto           | 6                      | No Billed by Grand Jury                    | 
| 07-1121670                                  | 2007-04-22T00:00:00 | Cpl. Michael Barger          | cpl         | White                  | Male           | 40          | APD             | 14                  | No       |                        | semi-auto           | 4                      | No Billed by Grand Jury                    | 
| 10-5058733 10-5058741 10-5058742 10-3060261 | 2010-11-02T00:00:00 | Ofc. Will Ray                | ofc         | White                  | Male           | 25          | APD             | 3                   | Yes      |                        | shotgun             | 4                      | No Billed by Grand Jury                    | 
| 10-5058733 10-5058741 10-5058742 10-3060261 | 2010-11-02T00:00:00 | Ofc. Jason Martin            | ofc         | White                  | Male           | 30          | APD             | 3                   | No       | 0.40                   | semi-auto           | 2                      | No Billed by Grand Jury                    | 
| 15-1860670 15-5029092 15-5030645            | 2015-07-05T00:00:00 | Ofc. Stephen Johnson         | ofc         | White                  | Male           | 24          | APD             | 0.6                 | No       | 0.40                   | semi-auto           | 3                      | pending                                    | 
```