# Horse Racing Rulings: Beginning 1985

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/horse-racing-rulings) |
| Metadata | [Link](https://data.ny.gov/api/views/igam-2tkj) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/igam-2tkj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/igam-2tkj/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | igam-2tkj |
| Name | Horse Racing Rulings: Beginning 1985 |
| Attribution | New York State Gaming Commission |
| Category | Government & Finance |
| Tags | horse racing, rulings, fine, suspension |
| Created | 2013-02-20T17:37:28Z |
| Publication Date | 2017-04-20T10:21:42Z |

## Description

The Horse Racing Rulings report lists any fines and suspensions issued by the New York State Gaming Commission?s Division of Horse Racing and Pari-Mutuel Wagering.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type     | Render Type   |
| ======== | ============== | ================ | ================ | ============= | ============= |
| No       |                | fine_year        | Fine Year        | number        | number        |
| Yes      | series tag     | notice           | Notice           | text          | text          |
| Yes      | series tag     | full_name        | Full Name        | text          | text          |
| Yes      | series tag     | race_track       | Race Track       | text          | text          |
| Yes      | series tag     | race_type        | Race Type        | text          | text          |
| Yes      | series tag     | type             | Type             | text          | text          |
| Yes      | time           | notice_date      | Notice Date      | calendar_date | calendar_date |
| Yes      | series tag     | rules            | Rules            | text          | text          |
| Yes      | series tag     | ruling_text      | Ruling Text      | text          | text          |
| Yes      | series tag     | occ              | Occupation       | text          | text          |
| Yes      | numeric metric | fine_amount      | Fine Amount      | money         | money         |
| No       |                | suspension_start | Suspension Start | calendar_date | calendar_date |
| No       |                | suspension_end   | Suspension End   | calendar_date | calendar_date |
| Yes      | series tag     | days_suspended   | Days Suspended   | text          | text          |
```

## Time Field

```ls
Value = notice_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = suspension_start,suspension_end,fine_year
```

## Data Commands

```ls
series e:igam-2tkj d:2003-10-17T00:00:00.000Z t:race_track="Buffalo Raceway" t:race_type=Harness t:notice="BR 72-2003" t:type="Fine & Suspension" t:ruling_text="POST RACE POSITIVE 6/20/03 6TH RACE - MEPIVICAINE" t:occ=TRAINER t:rules="4120.2(F) 4120.4" t:days_suspended=45 t:full_name="BERNARD E. GRIGNOLA" m:fine_amount=500

series e:igam-2tkj d:2001-07-21T00:00:00.000Z t:race_track="Yonkers Raceway" t:race_type=? t:notice="YR 126-2001" t:type=Fine t:ruling_text="FAIL TO HAVE HORSE IN PADDOCK AT PRESCRIBED TIME 7/19" t:occ=TRAINER t:rules="4104.8 (a)" t:full_name="MICHAEL J. PETERS" m:fine_amount=100

series e:igam-2tkj d:1990-06-26T00:00:00.000Z t:race_track="Yonkers Raceway" t:race_type=? t:notice="YR 128-1990" t:type=Fine t:ruling_text="REPEATED POSITIVES IN QUAL. RACES" t:occ="Invalid Occupation  See Notes" t:rules=4120.6 t:days_suspended=0 t:full_name="FRANK B. KASYAN" m:fine_amount=200
```

## Meta Commands

```ls
metric m:fine_amount p:double l:"Fine Amount" d:"Fine amount in dollars" t:dataTypeName=money

entity e:igam-2tkj l:"Horse Racing Rulings: Beginning 1985" t:attribution="New York State Gaming Commission" t:url=https://data.ny.gov/api/views/igam-2tkj

property e:igam-2tkj t:meta.view v:id=igam-2tkj v:category="Government & Finance" v:attributionLink=http://rulings.gaming.ny.gov/ v:averageRating=0 v:name="Horse Racing Rulings: Beginning 1985" v:attribution="New York State Gaming Commission"

property e:igam-2tkj t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:igam-2tkj t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| fine_year | notice      | full_name             | race_track                           | race_type    | type              | notice_date         | rules                    | ruling_text                                                                   | occ                          | fine_amount | suspension_start    | suspension_end      | days_suspended | 
| ========= | =========== | ===================== | ==================================== | ============ | ================= | =================== | ======================== | ============================================================================= | ============================ | =========== | =================== | =================== | ============== | 
| 2003      | BR 72-2003  | BERNARD E. GRIGNOLA   | Buffalo Raceway                      | Harness      | Fine & Suspension | 2003-10-17T00:00:00 | 4120.2(F) 4120.4         | POST RACE POSITIVE 6/20/03 6TH RACE - MEPIVICAINE                             | TRAINER                      | 500.00      | 2003-10-10T00:00:00 | 2003-11-23T00:00:00 | 45             | 
| 2001      | YR 126-2001 | MICHAEL J. PETERS     | Yonkers Raceway                      | ?            | Fine              | 2001-07-21T00:00:00 | 4104.8 (a)               | FAIL TO HAVE HORSE IN PADDOCK AT PRESCRIBED TIME 7/19                         | TRAINER                      | 100.00      |                     |                     |                | 
| 1990      | YR 128-1990 | FRANK B. KASYAN       | Yonkers Raceway                      | ?            | Fine              | 1990-06-26T00:00:00 | 4120.6                   | REPEATED POSITIVES IN QUAL. RACES                                             | Invalid Occupation See Notes | 200.00      |                     |                     | 0              | 
| 1995      | NY 50-1995  | JOHN M. DE STEFANO JR | New York Racing Association          | ?            | Fine              | 1995-09-29T00:00:00 | 4043.2(f)--4022.12&13    | TWO POST RACE POSITIVES-05/03 05/04/95                                        | TRAINER                      | 1500.00     | 1995-10-03T00:00:00 | 1995-10-17T00:00:00 | 15             | 
| 2001      | NY 41-2001  | JOHN M. DE STEFANO JR | New York Racing Association          | ?            | Fine & Suspension | 2001-07-14T00:00:00 | 4043.2 .4 .5 4022.12 .13 | POST RACE POSITIVE-CLENBUTEROL 6/14/01 2ND RACE                               | TRAINER                      | 2000.00     | 2001-07-16T00:00:00 | 2001-07-30T00:00:00 | 15             | 
| 2004      | NY 22-2004  | JOHN M. DE STEFANO JR | New York Racing Association          | Thoroughbred | Fine              | 2004-04-16T00:00:00 | 4043.2 4 5 4022.12 13    | FINDING A DRUG IN THE POST RACE SAMPLES OF YOUR HORSE 9'TH RACE               | TRAINER                      | 3000.00     |                     |                     |                | 
| 2004      | YR 8-2004   | DONALD J. DANCER      | Yonkers Raceway                      | Harness      | Fine              | 2004-02-13T00:00:00 | 4117.4(M)                | BACKING OFF CAUSING CONFUSION BY EXVESSIVELY SLOWING DOWM THE FIELD 7'TH RACE | TRAINER-DRIVER               | 250.00      |                     |                     |                | 
| 2004      | MR 140-2004 | DONALD J. DANCER      | Monticello Raceway & Mighty M Gaming | Harness      | Suspension        | 2004-09-01T00:00:00 | 4117.4(H)                | WHILE DRIVING #7 YOU CARRIED #6 THREE WIDE NEAR THE 1/2 MILE POLE 8'TH RACE   | TRAINER-DRIVER               | 0.00        | 2004-09-02T00:00:00 | 2004-09-06T00:00:00 | 5              | 
| 1988      | RR 24-1988  | DONALD J. DANCER      | Roosevelt Raceway                    | ?            | Suspension        | 1988-02-10T00:00:00 | 4117.4(b)                | YOU HOOKED WHEELS WITH #1                                                     | TRAINER-DRIVER               | 0.00        | 1988-12-24T00:00:00 | 1988-12-31T00:00:00 | 8              | 
| 1988      | RR 45-1988  | DONALD J. DANCER      | Roosevelt Raceway                    | ?            | Suspension        | 1988-02-28T00:00:00 | 4117.4(a)                | CAUSE #3 TO GO OFFSTRIDE                                                      | TRAINER-DRIVER               | 0.00        | 1988-02-28T00:00:00 | 1988-03-06T00:00:00 | 8              | 
```