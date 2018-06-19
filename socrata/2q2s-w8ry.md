# Oregon State Owned/Leased Buildings

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/oregon-state-owned-leased-buildings-7d155) |
| Metadata | [Link](https://data.oregon.gov/api/views/2q2s-w8ry) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/2q2s-w8ry/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/2q2s-w8ry/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 2q2s-w8ry |
| Name | Oregon State Owned/Leased Buildings |
| Attribution | State of Oregon Dept. of Administrative Services |
| Tags | assets, buildings, leased, owned, oregon |
| Created | 2010-10-25T18:43:46Z |
| Publication Date | 2011-04-17T00:03:09Z |

## Description

Locations of buildings owned and leased by the State of Oregon.

[Note: This dataset does not contain a complete list of state owned and leased buildings, a updated dataset will be uploaded shortly.]

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type | Render Type |
| ======== | ============== | ========== | ========== | ========= | =========== |
| Yes      | series tag     | name       | Name       | text      | text        |
| No       |                | address    | Address    | text      | text        |
| Yes      | series tag     | city       | City       | text      | text        |
| Yes      | series tag     | zipcode    | ZipCode    | text      | text        |
| Yes      | series tag     | type       | Type       | text      | text        |
| Yes      | series tag     | webpage    | webpage    | url       | url         |
| Yes      | numeric metric | sqft       | SqFt       | number    | number      |
| Yes      | time           | expdate    | EXPdate    | text      | text        |
| Yes      | series tag     | directions | Directions | url       | url         |
```

## Time Field

```ls
Value = expdate
Format & Zone = MM/dd/yyyy
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:2q2s-w8ry d:2011-09-03T00:00:00.000Z t:directions="http://maps.google.com/maps?f=q&source=s_q&hl=en&geocode=&q=635+CAPITOL+ST+NE+Salem+97301" t:webpage=http://sustainability.oregon.gov/DAS/FAC/Building_Info/agriculture.shtml t:name="Agriculture Building" t:type=Owned t:city=Salem m:sqft=76817

series e:2q2s-w8ry d:2009-10-31T00:00:00.000Z t:directions="http://maps.google.com/maps?f=q&source=s_q&hl=en&geocode=&q=811+SW+Sixth+Avenue+Portland+97204" t:webpage=http://sustainability.oregon.gov/DAS/FAC/Building_Info t:name="Consumer & Bus Services" t:type=Leased t:city=Portland m:sqft=90

series e:2q2s-w8ry d:2012-01-31T00:00:00.000Z t:directions="http://maps.google.com/maps?f=q&source=s_q&hl=en&geocode=&q=2757+22nd+Street+SE+Salem+97302" t:webpage=http://sustainability.oregon.gov/DAS/FAC/Building_Info t:name="Corrections, Dept" t:type=Leased t:city=Salem m:sqft=12000
```

## Meta Commands

```ls
metric m:sqft p:integer l:SqFt t:dataTypeName=number

entity e:2q2s-w8ry l:"Oregon State Owned/Leased Buildings" t:attribution="State of Oregon Dept. of Administrative Services" t:url=https://data.oregon.gov/api/views/2q2s-w8ry

property e:2q2s-w8ry t:meta.view v:id=2q2s-w8ry v:averageRating=0 v:name="Oregon State Owned/Leased Buildings" v:attribution="State of Oregon Dept. of Administrative Services"

property e:2q2s-w8ry t:meta.view.owner v:id=n7yg-3wp3 v:profileImageUrlMedium=/api/users/n7yg-3wp3/profile_images/THUMB v:profileImageUrlLarge=/api/users/n7yg-3wp3/profile_images/LARGE v:screenName="Erik Endrulat" v:profileImageUrlSmall=/api/users/n7yg-3wp3/profile_images/TINY v:displayName="Erik Endrulat"

property e:2q2s-w8ry t:meta.view.tableauthor v:id=n7yg-3wp3 v:profileImageUrlMedium=/api/users/n7yg-3wp3/profile_images/THUMB v:profileImageUrlLarge=/api/users/n7yg-3wp3/profile_images/LARGE v:screenName="Erik Endrulat" v:profileImageUrlSmall=/api/users/n7yg-3wp3/profile_images/TINY v:displayName="Erik Endrulat"
```

## Top Records

```ls
| name                              | address              | city     | zipcode | type   | webpage                                                                          | sqft  | expdate    | directions                                                                                             | 
| ================================= | ==================== | ======== | ======= | ====== | ================================================================================ | ===== | ========== | ====================================================================================================== | 
| Agriculture Building              | 635 CAPITOL ST NE    | Salem    |         | Owned  | [http://sustainability.oregon.gov/DAS/FAC/Building_Info/agriculture.shtml, null] | 76817 |            | [http://maps.google.com/maps?f=q&source=s_q&hl=en&geocode=&q=635+CAPITOL+ST+NE+Salem+97301, null]      | 
| Consumer & Bus Services           | 811 SW Sixth Avenue  | Portland |         | Leased | [http://sustainability.oregon.gov/DAS/FAC/Building_Info, null]                   | 90    | 10/31/2009 | [http://maps.google.com/maps?f=q&source=s_q&hl=en&geocode=&q=811+SW+Sixth+Avenue+Portland+97204, null] | 
| Corrections, Dept                 | 2757 22nd Street SE  | Salem    |         | Leased | [http://sustainability.oregon.gov/DAS/FAC/Building_Info, null]                   | 12000 | 1/31/2012  | [http://maps.google.com/maps?f=q&source=s_q&hl=en&geocode=&q=2757+22nd+Street+SE+Salem+97302, null]    | 
| Children & Family Comm            | 530 Center Street NE | Salem    |         | Leased | [http://sustainability.oregon.gov/DAS/FAC/Building_Info, null]                   | 400   | 1/31/2011  | [http://maps.google.com/maps?f=q&source=s_q&hl=en&geocode=&q=530+Center+Street+NE+Salem+97301, null]   | 
| Lottery                           | 500 AIRPORT RD SE    | Salem    |         | Owned  | [http://sustainability.oregon.gov/DAS/FAC/Building_Info, null]                   | 0     |            | [http://maps.google.com/maps?f=q&source=s_q&hl=en&geocode=&q=500+AIRPORT+RD+SE+Salem+97301, null]      | 
| Justice Building                  | 1162 COURT ST NE     | Salem    |         | Owned  | [http://sustainability.oregon.gov/DAS/FAC/Building_Info/justice.shtml, null]     | 94644 |            | [http://maps.google.com/maps?f=q&source=s_q&hl=en&geocode=&q=1162+COURT+ST+NE+Salem+97301, null]       | 
| Human Services, Dept              | 122nd & Powell Blvd  | Portland |         | Leased | [http://sustainability.oregon.gov/DAS/FAC/Building_Info, null]                   | 31214 | 4/30/2010  | [http://maps.google.com/maps?f=q&source=s_q&hl=en&geocode=&q=122nd+&+Powell+Blvd+Portland+97216, null] | 
| Justice, Dept                     | 494 State St 3rd Fl  | Salem    |         | Leased | [http://sustainability.oregon.gov/DAS/FAC/Building_Info, null]                   | 7000  | 6/30/2012  | [http://maps.google.com/maps?f=q&source=s_q&hl=en&geocode=&q=494+State+St+3rd+Fl+Salem+97305, null]    | 
| Energy, Office                    | 625 Marion St NE     | Salem    |         | Leased | [http://sustainability.oregon.gov/DAS/FAC/Building_Info, null]                   | 19600 | 7/31/2013  | [http://maps.google.com/maps?f=q&source=s_q&hl=en&geocode=&q=625+Marion+St+NE+Salem+97301, null]       | 
| Robertson Building (And Addition) | 1215 & 1241 STATE ST | Salem    |         | Leased | [http://sustainability.oregon.gov/DAS/FAC/Building_Info, null]                   | 0     |            | [http://maps.google.com/maps?f=q&source=s_q&hl=en&geocode=&q=1215+&+1241+STATE+ST+Salem+97301, null]   | 
```