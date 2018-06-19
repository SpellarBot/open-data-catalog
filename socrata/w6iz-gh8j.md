# Detention Population by Gender January 1st Through December 31st, 2004-2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/detention-population-by-gender-january-1st-through-december-31st-2004-2013) |
| Metadata | [Link](https://data.wa.gov/api/views/w6iz-gh8j) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/w6iz-gh8j/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/w6iz-gh8j/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | w6iz-gh8j |
| Name | Detention Population by Gender January 1st Through December 31st, 2004-2013 |
| Attribution | Office of Juvenile Justice |
| Category | Public Safety |
| Tags | juvenile justice, annual report, wa-pcjj report, office of juvenile justice, dshs, gender, youth |
| Created | 2015-12-27T05:59:12Z |
| Publication Date | 2016-01-12T20:05:02Z |

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                      | Data Type | Render Type |
| ======== | ============== | ======================= | ========================= | ========= | =========== |
| Yes      | series tag     | facility_also_holds_for | Facility (Also Holds For) | text      | text        |
| Yes      | numeric metric | male_2013               | Male 2013                 | number    | number      |
| Yes      | numeric metric | female_2013             | Female 2013               | number    | number      |
| Yes      | numeric metric | total_2013              | Total 2013                | number    | number      |
| Yes      | numeric metric | 2013                    | % 2013                    | number    | number      |
| Yes      | numeric metric | 2012                    | % 2012                    | number    | number      |
| Yes      | numeric metric | 2011                    | % 2011                    | number    | number      |
| Yes      | numeric metric | 2010                    | % 2010                    | number    | number      |
| Yes      | numeric metric | 2009                    | % 2009                    | number    | number      |
| Yes      | numeric metric | 2008                    | % 2008                    | number    | number      |
| Yes      | numeric metric | 2007                    | % 2007                    | number    | number      |
| Yes      | numeric metric | 2006                    | % 2006                    | number    | number      |
| Yes      | numeric metric | 2005                    | % 2005                    | number    | number      |
| Yes      | numeric metric | 2004                    | % 2004                    | number    | number      |
| Yes      | numeric metric | change_female_2012_2013 | % Change Female 2012-2013 | number    | number      |
| Yes      | numeric metric | change_female_2004_2013 | % Change Female 2004-2013 | number    | number      |
```

## Time Field

```ls
Value = 2004
Format & Zone = yyyy
```

## Data Commands

```ls
series e:w6iz-gh8j d:2004-01-01T00:00:00.000Z t:facility_also_holds_for="BENTON/FRANKLIN (Klickitat, Umatillo, Morrow, OR)" m:2008=23.29 m:2009=24.07 m:change_female_2004_2013=10.4 m:2006=25.7 m:2007=24.9 m:male_2013=928 m:2013=25.7 m:2004=23.3 m:female_2013=321 m:2005=26.9 m:2012=25.56 m:2011=21.06 m:2010=21.7 m:total_2013=1249 m:change_female_2012_2013=0.6

series e:w6iz-gh8j d:2004-01-01T00:00:00.000Z t:facility_also_holds_for=CHELAN m:2008=27.46 m:2009=29.83 m:change_female_2004_2013=1.1 m:2006=28.9 m:2007=27.6 m:male_2013=333 m:2013=30.77 m:2004=30.4 m:female_2013=148 m:2005=31.9 m:2012=35.91 m:2011=27.15 m:2010=33.2 m:total_2013=481 m:change_female_2012_2013=-14.3

series e:w6iz-gh8j d:2004-01-01T00:00:00.000Z t:facility_also_holds_for="CLALLAM (San Juan, Jefferson Point No Point)" m:2008=36.47 m:2009=39.58 m:change_female_2004_2013=11.7 m:2006=35.5 m:2007=32.3 m:male_2013=385 m:2013=38.79 m:2004=34.7 m:female_2013=244 m:2005=35.8 m:2012=39.57 m:2011=38.75 m:2010=40.4 m:total_2013=629 m:change_female_2012_2013=-2
```

## Meta Commands

```ls
metric m:male_2013 p:integer l:"Male 2013" t:dataTypeName=number

metric m:female_2013 p:integer l:"Female 2013" t:dataTypeName=number

metric m:total_2013 p:integer l:"Total 2013" t:dataTypeName=number

metric m:2013 p:float l:"% 2013" t:dataTypeName=number

metric m:2012 p:float l:"% 2012" t:dataTypeName=number

metric m:2011 p:float l:"% 2011" t:dataTypeName=number

metric m:2010 p:float l:"% 2010" t:dataTypeName=number

metric m:2009 p:float l:"% 2009" t:dataTypeName=number

metric m:2008 p:float l:"% 2008" t:dataTypeName=number

metric m:2007 p:float l:"% 2007" t:dataTypeName=number

metric m:2006 p:float l:"% 2006" t:dataTypeName=number

metric m:2005 p:float l:"% 2005" t:dataTypeName=number

metric m:2004 p:float l:"% 2004" t:dataTypeName=number

metric m:change_female_2012_2013 p:float l:"% Change Female 2012-2013" t:dataTypeName=number

metric m:change_female_2004_2013 p:float l:"% Change Female 2004-2013" t:dataTypeName=number

entity e:w6iz-gh8j l:"Detention Population by Gender January 1st Through December 31st, 2004-2013" t:attribution="Office of Juvenile Justice" t:url=https://data.wa.gov/api/views/w6iz-gh8j

property e:w6iz-gh8j t:meta.view v:id=w6iz-gh8j v:category="Public Safety" v:attributionLink=https://dshs.wa.gov/ra/office-juvenile-justice/washington-state-juvenile-justice-annual-report v:averageRating=0 v:name="Detention Population by Gender January 1st Through December 31st, 2004-2013" v:attribution="Office of Juvenile Justice"

property e:w6iz-gh8j t:meta.view.license v:name="Public Domain"

property e:w6iz-gh8j t:meta.view.owner v:id=6p7r-jviv v:profileImageUrlMedium=/api/users/6p7r-jviv/profile_images/THUMB v:profileImageUrlLarge=/api/users/6p7r-jviv/profile_images/LARGE v:screenName="Alysa Kipersztok" v:profileImageUrlSmall=/api/users/6p7r-jviv/profile_images/TINY v:displayName="Alysa Kipersztok"

property e:w6iz-gh8j t:meta.view.tableauthor v:id=6p7r-jviv v:profileImageUrlMedium=/api/users/6p7r-jviv/profile_images/THUMB v:profileImageUrlLarge=/api/users/6p7r-jviv/profile_images/LARGE v:screenName="Alysa Kipersztok" v:profileImageUrlSmall=/api/users/6p7r-jviv/profile_images/TINY v:roleName=viewer v:displayName="Alysa Kipersztok"
```

## Top Records

```ls
| facility_also_holds_for                                  | male_2013 | female_2013 | total_2013 | 2013  | 2012  | 2011  | 2010 | 2009  | 2008  | 2007 | 2006 | 2005 | 2004 | change_female_2012_2013 | change_female_2004_2013 | 
| ======================================================== | ========= | =========== | ========== | ===== | ===== | ===== | ==== | ===== | ===== | ==== | ==== | ==== | ==== | ======================= | ======================= | 
| BENTON/FRANKLIN (Klickitat, Umatillo, Morrow, OR)        | 928       | 321         | 1249       | 25.70 | 25.56 | 21.06 | 21.7 | 24.07 | 23.29 | 24.9 | 25.7 | 26.9 | 23.3 | 0.6                     | 10.4                    | 
| CHELAN                                                   | 333       | 148         | 481        | 30.77 | 35.91 | 27.15 | 33.2 | 29.83 | 27.46 | 27.6 | 28.9 | 31.9 | 30.4 | -14.3                   | 1.1                     | 
| CLALLAM (San Juan, Jefferson Point No Point)             | 385       | 244         | 629        | 38.79 | 39.57 | 38.75 | 40.4 | 39.58 | 36.47 | 32.3 | 35.5 | 35.8 | 34.7 | -2.0                    | 11.7                    | 
| CLARK (Skamania)                                         | 1104      | 363         | 1467       | 24.74 | 23.27 | 27.98 | 25.8 | 23.95 | 25.59 | 23.4 | 27.3 | 25.2 | 23.9 | 6.3                     | 3.7                     | 
| COWLITZ (Wahkiakum, Skamania, Columbia, OR. Clatsop, OR) | 641       | 257         | 898        | 28.62 | 27.56 | 24.33 | 29.8 | 30.36 | 28.85 | 31.2 | 28.8 | 36.0 | 33.5 | 3.8                     | -14.6                   | 
| GRANT (Adams, Lincoln, Kittitas)                         | 296       | 106         | 402        | 26.37 | 26.64 | 28.03 | 31.8 | 30.35 | 30.00 | 25.5 | 31.4 | 26.9 | 25.4 | -1.0                    | 3.9                     | 
| GRAYS HARBOR (Adams, Pacific, Wahkiakum)                 | 462       | 270         | 732        | 36.89 | 30.30 | 38.55 | 29.9 | 30.00 | 32.45 | 31.1 | 34.4 | 29.3 | 34.4 | 21.8                    | 7.2                     | 
| ISLAND                                                   | 133       | 43          | 176        | 24.43 | 26.42 | 23.90 | 36.2 | 32.37 | 27.60 | 26.7 | 30.0 |      |      | -7.5                    |                         | 
| KING **                                                  | 1480      | 659         | 2139       | 30.81 | 29.07 | 30.07 | 27.4 | 27.30 | 27.42 | 28.4 | 28.4 | 27.3 | 28.3 | 6.0                     | 8.8                     | 
| LEWIS (Skamania, Pacific)                                | 242       | 95          | 337        | 28.19 | 25.75 | 20.57 | 27.4 | 26.11 | 30.27 | 28.8 | 34.5 | 35.3 | 32.4 | 9.5                     | -13.1                   | 
```