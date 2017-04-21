# Special Event Permits

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/special-event-permits) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/cdz5-3y2u) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/cdz5-3y2u/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/cdz5-3y2u/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | cdz5-3y2u |
| Name | Special Event Permits |
| Attribution | Baltimore City Department of General Services |
| Category | Public Works |
| Tags | permits |
| Created | 2014-08-28T15:03:29Z |
| Publication Date | 2015-07-15T17:25:59Z |

## Description

Right-of-Way Services oversees the issuance and enforcement of Right-of-Way (ROW) permits. Call (410)396-4508 for information.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type     | Render Type   |
| ======== | ============== | ========================== | ========================== | ============= | ============= |
| Yes      | series tag     | permit_id                  | permit_id                  | text          | text          |
| Yes      | series tag     | permit_name_full           | permit_name_full           | text          | text          |
| Yes      | series tag     | intermediate_location_text | intermediate_location_text | text          | text          |
| Yes      | time           | start_date                 | start_date                 | calendar_date | calendar_date |
| Yes      | numeric metric | duration                   | duration                   | number        | number        |
| No       |                | end_date                   | end_date                   | calendar_date | calendar_date |
| Yes      | series tag     | facility_type              | facility_type              | text          | text          |
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
series e:cdz5-3y2u d:2015-04-10T08:00:00.000Z t:permit_id=ROW2015-SE1007308 t:permit_name_full="PRATT STREET ALE HOUSE Orioles Opening Day" t:intermediate_location_text="W Pratt St & Hopkins Pl, Baltimore, Maryland, 21201 : 156 Hopkins Pl" m:duration=1

series e:cdz5-3y2u d:2015-04-25T12:00:00.000Z t:permit_id=ROW2015-SE1007310 t:permit_name_full="""THE BAND"" MARCHING UNIT HOME COMING PARADE" t:intermediate_location_text="S Monastery Ave & Massachusetts Ave, Baltimore, Maryland, 21229 : 39.284146, -76.681058 (Closest Intersection) : 3561 Old Frederick Rd : 3435 Old Frederick Rd : 39.282993, -76.674117" t:facility_type=Parade m:duration=1

series e:cdz5-3y2u d:2015-10-31T05:30:00.000Z t:permit_id=ROW2015-SE1006847 t:permit_name_full="Walk to End Alzheimer's" t:intermediate_location_text="39.281917, -76.610977 : 39.282272, -76.611775 : 39.286025, -76.611737 : 39.285907, -76.609912 : 39.286321, -76.609798 : 39.286261, -76.609532 : 39.285995, -76.609532 : 39.286882, -76.609494 : 39.286882, -76.605995 : 39.283690, -76.605957 : 39.283247, -76.605082 : 39.283927, -76.605234 : 39.284045, -76.605957 : 39.286971, -76.605995 : 39.286941, -76.609494 : 39.285848, -76.609532 : 39.286350, -76.609608 : 39.286380, -76.609950 : 39.285670, -76.610064 : 39.286055, -76.611851 : 39.282213, -76.611737 : 39.281799, -76.610825" m:duration=1
```

## Meta Commands

```ls
metric m:duration p:float l:duration t:dataTypeName=number

entity e:cdz5-3y2u l:"Special Event Permits" t:attribution="Baltimore City Department of General Services" t:url=https://data.baltimorecity.gov/api/views/cdz5-3y2u

property e:cdz5-3y2u t:meta.view v:id=cdz5-3y2u v:category="Public Works" v:attributionLink=http://archive.baltimorecity.gov/Government/AgenciesDepartments/GeneralServices/PermitForms.aspx v:averageRating=0 v:name="Special Event Permits" v:attribution="Baltimore City Department of General Services"

property e:cdz5-3y2u t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:cdz5-3y2u t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:cdz5-3y2u t:meta.view.tableauthor v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```

## Top Records

```ls
| permit_id         | permit_name_full                               | intermediate_location_text                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | start_date          | duration | end_date            | facility_type | 
| ================= | ============================================== | ============================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================= | =================== | ======== | =================== | ============= | 
| ROW2015-SE1007308 | PRATT STREET ALE HOUSE Orioles Opening Day     | W Pratt St & Hopkins Pl, Baltimore, Maryland, 21201 : 156 Hopkins Pl                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | 2015-04-10T08:00:00 | 1.0      | 2015-04-10T23:00:00 |               | 
| ROW2015-SE1007310 | "THE BAND" MARCHING UNIT HOME COMING PARADE    | S Monastery Ave & Massachusetts Ave, Baltimore, Maryland, 21229 : 39.284146, -76.681058 (Closest Intersection) : 3561 Old Frederick Rd : 3435 Old Frederick Rd : 39.282993, -76.674117                                                                                                                                                                                                                                                                                                                                                        | 2015-04-25T12:00:00 | 1.0      | 2015-04-25T20:30:00 | Parade        | 
| ROW2015-SE1006847 | Walk to End Alzheimer's                        | 39.281917, -76.610977 : 39.282272, -76.611775 : 39.286025, -76.611737 : 39.285907, -76.609912 : 39.286321, -76.609798 : 39.286261, -76.609532 : 39.285995, -76.609532 : 39.286882, -76.609494 : 39.286882, -76.605995 : 39.283690, -76.605957 : 39.283247, -76.605082 : 39.283927, -76.605234 : 39.284045, -76.605957 : 39.286971, -76.605995 : 39.286941, -76.609494 : 39.285848, -76.609532 : 39.286350, -76.609608 : 39.286380, -76.609950 : 39.285670, -76.610064 : 39.286055, -76.611851 : 39.282213, -76.611737 : 39.281799, -76.610825 | 2015-10-31T05:30:00 | 1.0      | 2015-10-31T15:00:00 |               | 
| ROW2015-SE1007298 | DTK 3ON3                                       | 39.280420, -76.640771 : 39.278883, -76.639003 : 39.277287, -76.641513 : 39.279090, -76.643129 : 39.280450, -76.640771                                                                                                                                                                                                                                                                                                                                                                                                                         | 2015-08-07T07:00:00 | 10.0     | 2015-08-16T19:00:00 |               | 
| ROW2015-SE1007066 | BALTIMORE INVITATIONAL REGATTA                 | 39.257167, -76.630266 : 39.254210, -76.621633 : 39.252821, -76.627452 : 39.254979, -76.632205 : 39.257108, -76.630342                                                                                                                                                                                                                                                                                                                                                                                                                         | 2015-04-11T06:00:00 | 1.0      | 2015-04-11T16:00:00 |               | 
| ROW2015-SE1007133 | HEALTH FREEDOM CELEBRATION WALK                | 39.296705, -76.623872 : 39.296298, -76.624433 : 39.296609, -76.624813 : 39.298529, -76.622598 : 39.298596, -76.615667 : 39.287729, -76.615002 : 39.287884, -76.610733 : 39.287832, -76.610067 : 39.287684, -76.609202 : 39.287950, -76.605846 : 39.288202, -76.604924 : 39.284153, -76.602262 : 39.284145, -76.603479 : 39.286938, -76.604620 : 39.286251, -76.622056 : 39.296638, -76.622712 : 39.296616, -76.623377                                                                                                                         | 2015-06-06T06:00:00 | 1.0      | 2015-06-06T12:00:00 | Race          | 
| ROW2015-SE1007292 | Quigleys 1/2 Irish Pub Opening Day Celebration | Emory St & Portland St, Baltimore, Maryland, 21230 : 640 Portland St : Emory St & Portland St                                                                                                                                                                                                                                                                                                                                                                                                                                                 | 2015-04-10T00:00:00 | 1.0      | 2015-04-10T23:59:00 |               | 
| ROW2015-SE1006705 | BALTIMORE WALK TO DEFEAT ALS                   | 234 E Lombard St, Baltimore, Maryland, 21202                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | 2015-10-03T06:00:00 | 1.0      | 2015-10-03T15:30:00 | Race          | 
| ROW2015-SE1006761 | SAINT ANTHONY FESTIVAL                         | Stiles St & Lloyd St, Baltimore, Maryland, 21202 : Stiles St & S Exeter St : S Exeter St & Fawn St : S Exeter St & E Pratt St : S Exeter St & Stiles St : Stiles St & S President St                                                                                                                                                                                                                                                                                                                                                          | 2015-06-06T00:00:00 | 2.0      | 2015-06-07T23:59:00 |               | 
| ROW2015-SE1006740 | HENRY AND NEVATER SAMPSON FOUNDATION INC.      | N Eutaw St & W Saratoga St, Baltimore, Maryland, 21201 : 39.300209, -76.621560 (Closest Intersection) : 39.303053, -76.625030 (Closest Intersection) : 1267 Eutaw Pl, Baltimore, Maryland, 21217 : 39.310528, -76.634005 (Closest Intersection) : 39.315646, -76.638997 (Closest Intersection) : Druid Park Lake Dr & Eutaw Pl                                                                                                                                                                                                                | 2015-03-28T07:30:00 | 1.0      | 2015-03-28T12:00:00 |               | 
```