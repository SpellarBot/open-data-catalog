# Officer Involved Shooting 2000-2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/officer-involved-shooting-2000-2014) |
| Metadata | [Link](https://data.austintexas.gov/api/views/63p6-iegi) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/63p6-iegi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/63p6-iegi/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | 63p6-iegi |
| Name | Officer Involved Shooting 2000-2014 |
| Created | 2015-10-29T21:52:15Z |
| Publication Date | 2015-11-02T13:42:14Z |

## Columns

```ls
| Included | Schema Type    | Field Name                        | Name                                | Data Type     | Render Type   |
| ======== | ============== | ================================= | =================================== | ============= | ============= |
| Yes      | series tag     | offense                           | Offense #                           | text          | text          |
| Yes      | time           | date                              | Date                                | calendar_date | calendar_date |
| No       |                | day_of_week                       | Day of Week                         | text          | text          |
| Yes      | series tag     | time                              | Time                                | text          | text          |
| Yes      | series tag     | day_part                          | Day Part                            | text          | text          |
| No       |                | location_address                  | Location/Address                    | text          | text          |
| Yes      | series tag     | premise_category                  | Premise Category                    | text          | text          |
| Yes      | series tag     | inside_outside                    | Inside/ Outside                     | text          | text          |
| Yes      | series tag     | call_type_categories              | Call Type Categories                | text          | text          |
| Yes      | series tag     | race_ethnicity_subj               | Race/Ethnicity [subj]               | text          | text          |
| Yes      | series tag     | gender_subj                       | Gender [subj]                       | text          | text          |
| Yes      | numeric metric | age_subj                          | Age [subj]                          | number        | number        |
| Yes      | series tag     | injuries_subj                     | Injuries [subj]                     | text          | text          |
| Yes      | series tag     | weapon_subj                       | Weapon [subj]                       | text          | text          |
| Yes      | numeric metric | officers_present_when_shots_fired | # Officers Present When Shots Fired | number        | number        |
| Yes      | numeric metric | number_of_ofc_shooters            | Number of (ofc) Shooters            | number        | number        |
| Yes      | series tag     | officer_name                      | Officer Name                        | text          | text          |
| Yes      | series tag     | rank                              | Rank                                | text          | text          |
| Yes      | series tag     | race_ethnicity_ofc                | Race/Ethnicity [ofc]                | text          | text          |
| Yes      | series tag     | gender_ofc                        | Gender [ofc]                        | text          | text          |
| Yes      | numeric metric | age_ofc                           | Age [ofc]                           | number        | number        |
| Yes      | series tag     | pd_jurisdiction                   | PD Jurisdiction                     | text          | text          |
| Yes      | numeric metric | years_le_experience               | Years LE Experience                 | number        | number        |
| Yes      | numeric metric | weapon_caliber_ofc                | Weapon Caliber [ofc]                | number        | number        |
| Yes      | series tag     | weapon_type_ofc                   | Weapon Type [ofc]                   | text          | text          |
| Yes      | numeric metric | shots_fired_ofc                   | # Shots Fired [ofc]                 | number        | number        |
| Yes      | numeric metric | hits_incident_based               | # Hits [incident based]             | number        | number        |
| Yes      | series tag     | how_cleared                       | How Cleared                         | text          | text          |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = day_of_week,location_address
```

## Data Commands

```ls
series e:63p6-iegi d:2013-05-17T00:00:00.000Z t:call_type_categories="shots fired" t:officer_name="Ofc. Robert Barger" t:race_ethnicity_ofc=White t:day_part=Night t:weapon_subj=gun t:gender_ofc=Male t:race_ethnicity_subj=White t:weapon_type_ofc=semi-auto t:premise_category=Yard/Courtyard t:gender_subj=Male t:rank=ofc t:time=3:27 t:pd_jurisdiction=APD t:inside_outside=Outside t:injuries_subj=None t:offense="13-5021565
13-1370254" t:how_cleared="No Billed by Grand Jury" m:age_subj=26 m:number_of_ofc_shooters=1 m:years_le_experience=2 m:age_ofc=45 m:weapon_caliber_ofc=0.4 m:shots_fired_ofc=1 m:hits_incident_based=0 m:officers_present_when_shots_fired=3

series e:63p6-iegi d:2013-07-26T00:00:00.000Z t:call_type_categories=onscene t:officer_name="Det. Charles ""Trey"" Kleinert" t:race_ethnicity_ofc=White t:day_part=Evening t:weapon_subj=none t:gender_ofc=Male t:race_ethnicity_subj=Black t:weapon_type_ofc=semi-auto t:premise_category="Under Bridge" t:gender_subj=Male t:rank=det t:time=16:10 t:pd_jurisdiction=APD t:inside_outside=Outside t:injuries_subj=killed t:offense="13-5033792
13-2071392" t:how_cleared="True Billed on 5/12/2014 (pending further)" m:age_subj=32 m:number_of_ofc_shooters=1 m:years_le_experience=19 m:age_ofc=49 m:weapon_caliber_ofc=0.4 m:shots_fired_ofc=1 m:hits_incident_based=1 m:officers_present_when_shots_fired=1

series e:63p6-iegi d:2012-04-05T00:00:00.000Z t:call_type_categories="traffic stop" t:officer_name="Ofc. Eric Copeland" t:race_ethnicity_ofc=White t:day_part=Evening t:weapon_subj="mic cord" t:gender_ofc=Male t:race_ethnicity_subj=Black t:weapon_type_ofc=semi-auto t:premise_category=Yard/Courtyard t:gender_subj=Male t:rank=ofc t:time=18:40 t:pd_jurisdiction=APD t:inside_outside=Outside t:injuries_subj=killed t:offense="12-5016942
12-0961610" t:how_cleared="No Billed by Grand Jury" m:age_subj=35 m:number_of_ofc_shooters=1 m:years_le_experience=2 m:age_ofc=36 m:weapon_caliber_ofc=0.4 m:shots_fired_ofc=3 m:hits_incident_based=3 m:officers_present_when_shots_fired=1
```

## Meta Commands

```ls
metric m:age_subj p:integer l:"Age [subj]" t:dataTypeName=number

metric m:officers_present_when_shots_fired p:integer l:"# Officers Present When Shots Fired" t:dataTypeName=number

metric m:number_of_ofc_shooters p:integer l:"Number of (ofc) Shooters" t:dataTypeName=number

metric m:age_ofc p:integer l:"Age [ofc]" t:dataTypeName=number

metric m:years_le_experience p:double l:"Years LE Experience" t:dataTypeName=number

metric m:weapon_caliber_ofc p:float l:"Weapon Caliber [ofc]" t:dataTypeName=number

metric m:shots_fired_ofc p:integer l:"# Shots Fired [ofc]" t:dataTypeName=number

metric m:hits_incident_based p:integer l:"# Hits [incident based]" t:dataTypeName=number

entity e:63p6-iegi l:"Officer Involved Shooting 2000-2014" t:url=https://data.austintexas.gov/api/views/63p6-iegi

property e:63p6-iegi t:meta.view v:id=63p6-iegi v:averageRating=0 v:name="Officer Involved Shooting 2000-2014"

property e:63p6-iegi t:meta.view.owner v:id=cjgf-k7fr v:screenName="Peter Moore" v:lastNotificationSeenAt=1491399715 v:displayName="Peter Moore"

property e:63p6-iegi t:meta.view.tableauthor v:id=cjgf-k7fr v:screenName="Peter Moore" v:lastNotificationSeenAt=1491399715 v:displayName="Peter Moore"
```

## Top Records

```ls
| offense               | date                | day_of_week | time  | day_part | location_address                        | premise_category | inside_outside | call_type_categories   | race_ethnicity_subj | gender_subj | age_subj | injuries_subj       | weapon_subj | officers_present_when_shots_fired | number_of_ofc_shooters | officer_name                 | rank | race_ethnicity_ofc | gender_ofc | age_ofc | pd_jurisdiction | years_le_experience | weapon_caliber_ofc | weapon_type_ofc | shots_fired_ofc | hits_incident_based | how_cleared                                | 
| ===================== | =================== | =========== | ===== | ======== | ======================================= | ================ | ============== | ====================== | =================== | =========== | ======== | =================== | =========== | ================================= | ====================== | ============================ | ==== | ================== | ========== | ======= | =============== | =================== | ================== | =============== | =============== | =================== | ========================================== | 
| 13-5021565 13-1370254 | 2013-05-17T00:00:00 | Fri         | 3:27  | Night    | 6855 E US 290 Hwy SVRD EB               | Yard/Courtyard   | Outside        | shots fired            | White               | Male        | 26       | None                | gun         | 3                                 | 1                      | Ofc. Robert Barger           | ofc  | White              | Male       | 45      | APD             | 2                   | 0.4                | semi-auto       | 1               | 0                   | No Billed by Grand Jury                    | 
| 13-5033792 13-2071392 | 2013-07-26T00:00:00 | Fri         | 16:10 | Evening  | W 35th St/W 34th St (3500 CRAWFORD AVE) | Under Bridge     | Outside        | onscene                | Black               | Male        | 32       | killed              | none        | 1                                 | 1                      | Det. Charles "Trey" Kleinert | det  | White              | Male       | 49      | APD             | 19                  | 0.4                | semi-auto       | 1               | 1                   | True Billed on 5/12/2014 (pending further) | 
| 12-5016942 12-0961610 | 2012-04-05T00:00:00 | Thur        | 18:40 | Evening  | 5200 Block Overbrook Dr                 | Yard/Courtyard   | Outside        | traffic stop           | Black               | Male        | 35       | killed              | mic cord    | 1                                 | 1                      | Ofc. Eric Copeland           | ofc  | White              | Male       | 36      | APD             | 2                   | 0.4                | semi-auto       | 3               | 3                   | No Billed by Grand Jury                    | 
| 12-5043966 12-2691696 | 2012-09-25T00:00:00 | Tues        | 20:39 | Evening  | 2915 S IH 35 Svrd NB                    | Parking Lot      | Outside        | stolen vehicle         | White               | Male        | 42       | killed              | gun         | 2                                 | 1                      | Ofc. George Blanch           | ofc  | White              | Male       | 36      | APD             | 8                   | 0.4                | semi-auto       | 6               | 1                   | No Billed by Grand Jury                    | 
| 12-5047326 12-2940313 | 2012-10-20T00:00:00 | Sat         | 2:10  | Night    | 300 Blk E 6th St                        | Street           | Outside        | onscene                | Black               | Female      | 24       | None                | vehicle     | 3                                 | 1                      | Ofc. Robert Krummel          | ofc  | White              | Male       | 27      | APD             | 3                   | 0.4                | semi-auto       | 4               | 0                   | No Billed by Grand Jury                    | 
| 11-5028251 11-1502313 | 2011-05-30T00:00:00 | Mon         | 23:07 | Night    | 800 Block E 8th St                      | Street           | Outside        | suspicious person/call | Black               | Male        | 20       | killed              | vehicle     | 2                                 | 1                      | Ofc. Nathan Wagner           | ofc  | White              | Male       | 28      | APD             | 3                   | 0.4                | semi-auto       | 5               | 4                   | No Billed by Grand Jury                    | 
| 11-5028251 11-1502313 | 2011-05-30T00:00:00 | Mon         | 23:07 | Night    | 800 Block E 8th St                      | Street           | Outside        | suspicious person/call | Black               | Male        | 16       | shot (injured only) | vehicle     | 2                                 | 1                      | Ofc. Nathan Wagner           | ofc  | White              | Male       | 0       | APD             | 3                   | 0.4                | semi-auto       | 5               | 4                   | No Billed by Grand Jury                    | 
| 11-5060110 11-3621220 | 2011-12-28T00:00:00 | Wed         | 17:19 | Evening  | 7800 N IH 35 Svrd SB                    | Parking Lot      | Outside        | narcotics              | Black               | Male        | 32       | None                | vehicle     | 4                                 | 1                      | Det. Tom Hugonnett           | det  | White              | Male       | 44      | APD             | 18                  | 0.4                | semi-auto       | 2               | 0                   | No Billed by Grand Jury                    | 
| 07-3110298            | 2007-11-07T00:00:00 | Wed         | 4:29  | Night    | 4509 E St Elmo Apt 3304                 | Residence        | Inside         | hostage/barricade      | White               | Male        | 37       | shot (injured only) | gun         | 2                                 | 1                      | Ofc. James Alexander         | ofc  | White              | Male       | 39      | APD             | 9                   | 0.308              | rifle           | 2               | 1                   | No Billed by Grand Jury                    | 
| 06-0151964            | 2006-01-15T00:00:00 | Sun         | 22:22 | Night    | 500 Block E 9th St                      | Street           | Outside        | robbery                | Black               | Male        | 20       | None                | gun         | 1                                 | 1                      | Ofc. James Harvel            | ofc  | White              | Male       | 31      | APD             | 5                   | 0.4                | semi-auto       | 1               | 1                   | not presented to grand jury (DA declined)  | 
```