# City of Rockford Crime Offenses 2011-Present

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/city-of-rockford-crime-offenses-2016-ytd) |
| Metadata | [Link](https://data.illinois.gov/api/views/x8xk-7uvk) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/x8xk-7uvk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/x8xk-7uvk/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | x8xk-7uvk |
| Name | City of Rockford Crime Offenses 2011-Present |
| Category | Public Safety |
| Tags | rockford, crime, public safety |
| Created | 2016-04-12T18:11:21Z |
| Publication Date | 2016-04-12T18:11:45Z |

## Description

City of Rockford Police Department Open Data Disclaimer:

The purpose of this dataset is to depict the City of Rockford, IL and to show multiple offenses in criminal incidents that occur within the City of Rockford Police Department jurisdiction. The data is illustrative and not an official crime report/reporting mechanism and is provided for informational purposes only. Although this dataset has been reviewed to ensure data accuracy, the City of Rockford provides this data "as is" and makes no guarantee or warranty concerning the accuracy of information contained within. The City of Rockford shall assume no liability for any errors, omissions, or inaccuracies in the information provided, regardless of how caused or any decision made or action taken, or not taken, by the reader in reliance upon any information or data furnished herein.

All data contained on this site has been gathered through legitimate means and with the knowledge and approval of the Rockford Police Department. All data has been extracted, processed and presented through appropriate channels. 

Data and Information: 
All offense data is obtained from NetRMS records management system as reported and reflects the current date. Information is preliminary and subject to change as police reports are submitted. Media outlets are advised to confirm any information not already verified through department issued press releases. Data is illustrative, not an official crime report, and should not be used for comparative reporting. The Rockford Police Department is not responsible for any error or omission, misuse, or results obtained from the use of this information. Although no personal information is disseminated through data.illinois.gov, remember that all subjects are presumed innocent until proven guilty in a court of law.

Offenses Reflected: 
Offenses displayed reflect all National Incident-Based Reporting System (NIBRS) offenses in an incident. NIBRS offenses represent the number of total offenses in an incident, not just the most serious offense. NIBRS Group A Offenses are 24 offense categories made up of 52 offenses considered to be the most serious and may be a crime against person, property, or society. Group B Offenses are 10 offenses that encompass all crimes that are not Group A Offenses and may be a crime against person, property or society. For Additional information on NIBRS, please visit https://www.fbi.gov/about-us/cjis/ucr/nibrs-quick-facts

Although all NIBRS Offense categories reported are captured by the Rockford Police Department, the dissemination of certain specific offenses are not reflected in the Offense Dataset published to Socrata?s Open Data Portal. Specific offenses that are potentially sensitive and confidential will not be displayed on data.illinois.gov and are excluded prior to being made available to the public. 

NIBRS offenses that are reported to Rockford Police but will not appear are: 

100 Kidnapping/Abduction/Unlawful Restraint 
11A Forcible Rape
11B Forcible Sodomy
11C Sexual Assault with an Object
11D Forcible Fondling
36A Incest
36B Statutory Rape
39A Betting/Wagering
39B Operating/Promoting/Assisting Gambling
39C Gambling Equipment Violations
39D Sports Tampering
64A Commercial Sex Acts
64B Involuntary Servitude
90F Non-Violent Family Offenses 
90Z All Other Offenses

## Columns

```ls
| Included | Schema Type | Field Name          | Name                | Data Type | Render Type |
| ======== | =========== | =================== | =================== | ========= | =========== |
| Yes      | series tag  | case_number         | Case Number         | text      | text        |
| Yes      | series tag  | offense_description | Offense Description | text      | text        |
| No       |             | occurred_on_date    | Occurred On Date    | text      | text        |
| Yes      | series tag  | occurred_on_time    | Occurred On Time    | text      | text        |
| Yes      | series tag  | crime_against       | Crime Against       | text      | text        |
| Yes      | series tag  | nibrs_group_type    | NIBRS Group Type    | text      | text        |
| Yes      | series tag  | patrol_area         | Patrol Area         | text      | text        |
| Yes      | series tag  | ward                | Ward                | text      | number      |
| No       |             | xcoord              | XCoord              | number    | number      |
| No       |             | ycoord              | YCoord              | number    | number      |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = occurred_on_date,xcoord,ycoord
```

## Data Commands

```ls
series e:x8xk-7uvk d:2011-01-01T00:00:00.000Z t:offense_description="90C - Disorderly Conduct" t:case_number=16-009615 t:ward=7 t:occurred_on_time=10:06:00 m:row_number.x8xk-7uvk=1

series e:x8xk-7uvk d:2011-01-01T00:00:00.000Z t:offense_description="90C - Disorderly Conduct" t:case_number=16-014351 t:ward=11 t:occurred_on_time=19:06:00 m:row_number.x8xk-7uvk=2

series e:x8xk-7uvk d:2011-01-01T00:00:00.000Z t:offense_description="13B - Simple Assault" t:case_number=16-016247 t:ward=8 t:occurred_on_time=15:50:00 m:row_number.x8xk-7uvk=3
```

## Meta Commands

```ls
metric m:row_number.x8xk-7uvk p:long l:"Row Number"

entity e:x8xk-7uvk l:"City of Rockford Crime Offenses 2011-Present" t:url=https://data.illinois.gov/api/views/x8xk-7uvk

property e:x8xk-7uvk t:meta.view v:id=x8xk-7uvk v:category="Public Safety" v:averageRating=0 v:name="City of Rockford Crime Offenses 2011-Present"

property e:x8xk-7uvk t:meta.view.owner v:id=hdqp-matg v:profileImageUrlMedium=/api/users/hdqp-matg/profile_images/THUMB v:profileImageUrlLarge=/api/users/hdqp-matg/profile_images/LARGE v:screenName=Glenn v:profileImageUrlSmall=/api/users/hdqp-matg/profile_images/TINY v:displayName=Glenn

property e:x8xk-7uvk t:meta.view.tableauthor v:id=hdqp-matg v:profileImageUrlMedium=/api/users/hdqp-matg/profile_images/THUMB v:profileImageUrlLarge=/api/users/hdqp-matg/profile_images/LARGE v:screenName=Glenn v:profileImageUrlSmall=/api/users/hdqp-matg/profile_images/TINY v:roleName=publisher v:displayName=Glenn
```

## Top Records

```ls
| case_number | offense_description                            | occurred_on_date | occurred_on_time | crime_against | nibrs_group_type | patrol_area | ward | xcoord           | ycoord           | 
| =========== | ============================================== | ================ | ================ | ============= | ================ | =========== | ==== | ================ | ================ | 
| 16-009615   | 90C - Disorderly Conduct                       | 2016-01-25       | 10:06:00         |               |                  |             | 7    | 2578625.53559681 | 2047778.23653586 | 
| 16-014351   | 90C - Disorderly Conduct                       | 2016-02-05       | 19:06:00         |               |                  |             | 11   | 2593358.24       | 2037258.68       | 
| 16-016247   | 13B - Simple Assault                           | 2016-02-09       | 15:50:00         |               |                  |             | 8    | 2601108.82899958 | 2031313.92153583 | 
| 16-016181   | 290 - Destruction/Damage/Vandalism of Property | 2016-02-10       | 11:38:00         |               |                  |             | 14   | 2604612.44       | 2032558.08       | 
| 16-023111   | 23H - All Other Larceny                        | 2016-02-06       | 01:00:00         |               |                  |             | 14   | 2604728.711825   | 2021502.9539031  | 
| 16-017792   | 23H - All Other Larceny                        | 2016-02-03       | 08:00:00         |               |                  |             | 6    | 2592611.26       | 2025707.02       | 
| 16-017892   | 90C - Disorderly Conduct                       | 2016-02-14       | 23:20:00         |               |                  |             | 14   | 2604794.05528577 | 2021223.76598708 | 
| 16-012713   | 13A - Aggravated Assault                       | 2016-02-01       | 13:45:00         |               |                  |             | 11   | 2589631.4        | 2040135.6        | 
| 16-019374   | 13C - Intimidation                             | 2016-02-18       | 19:26:00         |               |                  |             | 2    | 2595465.16       | 2040362.82       | 
| 16-015670   | 120 - Robbery                                  | 2016-02-08       | 23:42:00         |               |                  |             | 10   | 2604716.26       | 2040556.78       | 
```