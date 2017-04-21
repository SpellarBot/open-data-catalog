# Homeland Security Grant Awards

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/homeland-security-grant-awards) |
| Metadata | [Link](https://data.maryland.gov/api/views/sw28-ginq) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/sw28-ginq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/sw28-ginq/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | sw28-ginq |
| Name | Homeland Security Grant Awards |
| Attribution | GOHS |
| Category | Public Safety |
| Tags | gohs, homeland security, governor's office of homeland security, public safety |
| Created | 2012-10-31T15:40:17Z |
| Publication Date | 2015-09-09T13:45:58Z |

## Description

This data set shows four sources of grant funding for the Governor's Office of Homeland Security (GOHS) and respective awards from 2003 to present.

## Columns

```ls
| Included | Schema Type    | Field Name                            | Name                                                 | Data Type | Render Type |
| ======== | ============== | ===================================== | ==================================================== | ========= | =========== |
| Yes      | time           | year                                  | Year                                                 | number    | text        |
| Yes      | numeric metric | urban_area_security_initiative        | Urban Area Security Initiative                       | money     | money       |
| Yes      | numeric metric | state_homeland_security_grant_program | State Homeland Security Grant Program                | money     | money       |
| Yes      | numeric metric | baltimore_uasi                        | Urban Area Security Initiative: Awarded to Balt.     | money     | money       |
| Yes      | numeric metric | maryland_shsgp                        | State Homeland Security Grant Program: Awarded to MD | money     | money       |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:sw28-ginq d:2003-01-01T00:00:00.000Z m:state_homeland_security_grant_program=2066000000 m:maryland_shsgp=39000000 m:urban_area_security_initiative=602000000 m:baltimore_uasi=13000000

series e:sw28-ginq d:2004-01-01T00:00:00.000Z m:state_homeland_security_grant_program=1685000000 m:maryland_shsgp=31000000 m:urban_area_security_initiative=725000000 m:baltimore_uasi=18000000

series e:sw28-ginq d:2005-01-01T00:00:00.000Z m:state_homeland_security_grant_program=1062000000 m:maryland_shsgp=20000000 m:urban_area_security_initiative=860000000 m:baltimore_uasi=11000000
```

## Meta Commands

```ls
metric m:urban_area_security_initiative p:integer l:"Urban Area Security Initiative" t:dataTypeName=money

metric m:state_homeland_security_grant_program p:integer l:"State Homeland Security Grant Program" t:dataTypeName=money

metric m:baltimore_uasi p:integer l:"Urban Area Security Initiative: Awarded to Balt." t:dataTypeName=money

metric m:maryland_shsgp p:integer l:"State Homeland Security Grant Program: Awarded to MD" t:dataTypeName=money

entity e:sw28-ginq l:"Homeland Security Grant Awards" t:attribution=GOHS t:url=https://data.maryland.gov/api/views/sw28-ginq

property e:sw28-ginq t:meta.view v:id=sw28-ginq v:category="Public Safety" v:attributionLink=http://gohs.maryland.gov/ v:averageRating=0 v:name="Homeland Security Grant Awards" v:attribution=GOHS

property e:sw28-ginq t:meta.view.license v:name="Public Domain"

property e:sw28-ginq t:meta.view.owner v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"

property e:sw28-ginq t:meta.view.tableauthor v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"
```

## Top Records

```ls
| year | urban_area_security_initiative | state_homeland_security_grant_program | baltimore_uasi | maryland_shsgp | 
| ==== | ============================== | ===================================== | ============== | ============== | 
| 2003 | 602000000                      | 2066000000                            | 13000000       | 39000000       | 
| 2004 | 725000000                      | 1685000000                            | 18000000       | 31000000       | 
| 2005 | 860000000                      | 1062000000                            | 11000000       | 20000000       | 
| 2006 | 740000000                      | 550000000                             | 10000000       | 8000000        | 
| 2007 | 746000000                      | 509000000                             | 12000000       | 12000000       | 
| 2008 | 782000000                      | 861000000                             | 12000000       | 18000000       | 
| 2009 | 838000000                      | 890000000                             | 11000000       | 17000000       | 
| 2010 | 833000000                      | 842000000                             | 11000000       | 16000000       | 
| 2011 | 663000000                      | 527000000                             | 8000000        | 8000000        | 
| 2012 | 490000000                      | 294000000                             | 4000000        | 4000000        | 
```