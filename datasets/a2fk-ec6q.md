# Census Data - Languages spoken in Chicago, 2008 ? 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/census-data-languages-spoken-in-chicago-2008-2012-9ad5d) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/a2fk-ec6q) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/a2fk-ec6q/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/a2fk-ec6q/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | a2fk-ec6q |
| Name | Census Data - Languages spoken in Chicago, 2008 ? 2012 |
| Attribution | U.S. Census Bureau |
| Category | Health & Human Services |
| Tags | english, spanish, language, census |
| Created | 2012-01-05T15:40:35Z |
| Publication Date | 2014-09-12T21:12:42Z |

## Description

This dataset contains estimates of the number of residents aged 5 years or older in Chicago who ?speak English less than very well,? by the non-English language spoken at home and community area of residence, for the years 2008 ? 2012.  See the full dataset description for more information at: https://data.cityofchicago.org/api/views/fpup-mc9v/files/dK6ZKRQZJ7XEugvUavf5MNrGNW11AjdWw0vkpj9EGjg?download=true&filename=P:\EPI\OEPHI\MATERIALS\REFERENCES\ECONOMIC_INDICATORS\Dataset_Description_Languages_2012_FOR_PORTAL_ONLY.pdf

## Columns

```ls
| Included | Schema Type    | Field Name                        | Name                                 | Data Type | Render Type |
| ======== | ============== | ================================= | ==================================== | ========= | =========== |
| Yes      | series tag     | community_area                    | Community Area                       | text      | number      |
| Yes      | series tag     | community_area_name               | Community Area Name                  | text      | text        |
| Yes      | series tag     | predominant_non_english_language_ | PREDOMINANT NON-ENGLISH LANGUAGE (%) | text      | text        |
| Yes      | numeric metric | african_languages                 | AFRICAN LANGUAGES                    | number    | number      |
| Yes      | numeric metric | arabic                            | ARABIC                               | number    | number      |
| Yes      | numeric metric | armenian                          | ARMENIAN                             | number    | number      |
| Yes      | numeric metric | cambodian_mon_khmer_              | CAMBODIAN (MON-KHMER)                | number    | number      |
| Yes      | numeric metric | chinese                           | CHINESE                              | number    | number      |
| Yes      | numeric metric | creole                            | CREOLE                               | number    | number      |
| Yes      | numeric metric | french                            | FRENCH                               | number    | number      |
| Yes      | numeric metric | german                            | GERMAN                               | number    | number      |
| Yes      | numeric metric | greek                             | GREEK                                | number    | number      |
| Yes      | numeric metric | gujarati                          | GUJARATI                             | number    | number      |
| Yes      | numeric metric | hebrew                            | HEBREW                               | number    | number      |
| Yes      | numeric metric | hindi                             | HINDI                                | number    | number      |
| Yes      | numeric metric | hmong                             | HMONG                                | number    | number      |
| Yes      | numeric metric | hungarian                         | HUNGARIAN                            | number    | number      |
| Yes      | numeric metric | italian                           | ITALIAN                              | number    | number      |
| Yes      | numeric metric | japanese                          | JAPANESE                             | number    | number      |
| Yes      | numeric metric | korean                            | KOREAN                               | number    | number      |
| Yes      | numeric metric | laotian                           | LAOTIAN                              | number    | number      |
| Yes      | numeric metric | navajo                            | NAVAJO                               | number    | number      |
| Yes      | numeric metric | other_asian                       | OTHER ASIAN                          | number    | number      |
| Yes      | numeric metric | other_indic                       | OTHER INDIC                          | number    | number      |
| Yes      | numeric metric | other_indo_eurpoean               | OTHER INDO EURPOEAN                  | number    | number      |
| Yes      | numeric metric | other_native_north_american       | OTHER NATIVE NORTH AMERICAN          | number    | number      |
| Yes      | numeric metric | other_pacific_island              | OTHER PACIFIC ISLAND                 | number    | number      |
| Yes      | numeric metric | other_slavic                      | OTHER SLAVIC                         | number    | number      |
| Yes      | numeric metric | other_west_germanic               | OTHER WEST GERMANIC                  | number    | number      |
| Yes      | numeric metric | persian                           | PERSIAN                              | number    | number      |
| Yes      | numeric metric | polish                            | POLISH                               | number    | number      |
| Yes      | numeric metric | portuguese                        | PORTUGUESE                           | number    | number      |
| Yes      | numeric metric | russian                           | RUSSIAN                              | number    | number      |
| Yes      | numeric metric | scandinavian                      | SCANDINAVIAN                         | number    | number      |
| Yes      | numeric metric | serbo_croatian                    | SERBO-CROATIAN                       | number    | number      |
| Yes      | numeric metric | spanish                           | SPANISH                              | number    | number      |
| Yes      | numeric metric | tagalog                           | TAGALOG                              | number    | number      |
| Yes      | numeric metric | thai                              | THAI                                 | number    | number      |
| Yes      | numeric metric | unspecified                       | UNSPECIFIED                          | number    | number      |
| Yes      | numeric metric | urdu                              | URDU                                 | number    | number      |
| Yes      | numeric metric | vietnamese                        | VIETNAMESE                           | number    | number      |
| Yes      | numeric metric | yiddish                           | YIDDISH                              | number    | number      |
```

## Time Field

```ls
Value = 2008
Format & Zone = yyyy
```

## Data Commands

```ls
series e:a2fk-ec6q d:2008-01-01T00:00:00.000Z t:community_area_name="Rogers Park" t:community_area=1 t:predominant_non_english_language_="SPANISH (9.9%)" m:arabic=165 m:urdu=85 m:italian=0 m:persian=9 m:hebrew=0 m:african_languages=332 m:cambodian_mon_khmer_=19 m:thai=0 m:vietnamese=0 m:french=94 m:chinese=215 m:navajo=0 m:tagalog=106 m:other_indic=503 m:portuguese=38 m:other_native_north_american=0 m:laotian=0 m:hindi=79 m:scandinavian=0 m:other_slavic=196 m:other_west_germanic=0 m:armenian=65 m:spanish=5302 m:greek=0 m:other_indo_eurpoean=201 m:german=41 m:creole=271 m:japanese=39 m:hungarian=0 m:other_pacific_island=13 m:korean=26 m:gujarati=70 m:yiddish=5 m:russian=201 m:unspecified=14 m:other_asian=240 m:hmong=0 m:polish=173 m:serbo_croatian=66

series e:a2fk-ec6q d:2008-01-01T00:00:00.000Z t:community_area_name="West Ridge" t:community_area=2 t:predominant_non_english_language_="SPANISH (8.7%)" m:arabic=1500 m:urdu=1539 m:italian=74 m:persian=0 m:hebrew=114 m:african_languages=374 m:cambodian_mon_khmer_=0 m:thai=69 m:vietnamese=1028 m:french=115 m:chinese=939 m:navajo=0 m:tagalog=323 m:other_indic=680 m:portuguese=0 m:other_native_north_american=0 m:laotian=0 m:hindi=825 m:scandinavian=0 m:other_slavic=276 m:other_west_germanic=0 m:armenian=2 m:spanish=5889 m:greek=274 m:other_indo_eurpoean=708 m:german=19 m:creole=110 m:japanese=31 m:hungarian=51 m:other_pacific_island=124 m:korean=332 m:gujarati=639 m:yiddish=121 m:russian=486 m:unspecified=846 m:other_asian=318 m:hmong=0 m:polish=245 m:serbo_croatian=1034

series e:a2fk-ec6q d:2008-01-01T00:00:00.000Z t:community_area_name=Uptown t:community_area=3 t:predominant_non_english_language_="SPANISH (4.9%)" m:arabic=58 m:urdu=287 m:italian=31 m:persian=15 m:hebrew=0 m:african_languages=750 m:cambodian_mon_khmer_=13 m:thai=72 m:vietnamese=548 m:french=79 m:chinese=462 m:navajo=0 m:tagalog=343 m:other_indic=42 m:portuguese=0 m:other_native_north_american=0 m:laotian=0 m:hindi=47 m:scandinavian=0 m:other_slavic=0 m:other_west_germanic=0 m:armenian=0 m:spanish=2584 m:greek=5 m:other_indo_eurpoean=157 m:german=22 m:creole=0 m:japanese=8 m:hungarian=0 m:other_pacific_island=68 m:korean=378 m:gujarati=0 m:yiddish=0 m:russian=603 m:unspecified=0 m:other_asian=257 m:hmong=0 m:polish=92 m:serbo_croatian=233
```

## Meta Commands

```ls
metric m:african_languages p:integer l:"AFRICAN LANGUAGES" t:dataTypeName=number

metric m:arabic p:integer l:ARABIC t:dataTypeName=number

metric m:armenian p:integer l:ARMENIAN t:dataTypeName=number

metric m:cambodian_mon_khmer_ p:integer l:"CAMBODIAN (MON-KHMER)" t:dataTypeName=number

metric m:chinese p:integer l:CHINESE t:dataTypeName=number

metric m:creole p:integer l:CREOLE t:dataTypeName=number

metric m:french p:integer l:FRENCH t:dataTypeName=number

metric m:german p:integer l:GERMAN t:dataTypeName=number

metric m:greek p:integer l:GREEK t:dataTypeName=number

metric m:gujarati p:integer l:GUJARATI t:dataTypeName=number

metric m:hebrew p:integer l:HEBREW t:dataTypeName=number

metric m:hindi p:integer l:HINDI t:dataTypeName=number

metric m:hmong p:integer l:HMONG t:dataTypeName=number

metric m:hungarian p:integer l:HUNGARIAN t:dataTypeName=number

metric m:italian p:integer l:ITALIAN t:dataTypeName=number

metric m:japanese p:integer l:JAPANESE t:dataTypeName=number

metric m:korean p:integer l:KOREAN t:dataTypeName=number

metric m:laotian p:integer l:LAOTIAN t:dataTypeName=number

metric m:navajo p:integer l:NAVAJO t:dataTypeName=number

metric m:other_asian p:integer l:"OTHER ASIAN" t:dataTypeName=number

metric m:other_indic p:integer l:"OTHER INDIC" t:dataTypeName=number

metric m:other_indo_eurpoean p:integer l:"OTHER INDO EURPOEAN" t:dataTypeName=number

metric m:other_native_north_american p:integer l:"OTHER NATIVE NORTH AMERICAN" t:dataTypeName=number

metric m:other_pacific_island p:integer l:"OTHER PACIFIC ISLAND" t:dataTypeName=number

metric m:other_slavic p:integer l:"OTHER SLAVIC" t:dataTypeName=number

metric m:other_west_germanic p:integer l:"OTHER WEST GERMANIC" t:dataTypeName=number

metric m:persian p:integer l:PERSIAN t:dataTypeName=number

metric m:polish p:integer l:POLISH t:dataTypeName=number

metric m:portuguese p:integer l:PORTUGUESE t:dataTypeName=number

metric m:russian p:integer l:RUSSIAN t:dataTypeName=number

metric m:scandinavian p:integer l:SCANDINAVIAN t:dataTypeName=number

metric m:serbo_croatian p:integer l:SERBO-CROATIAN t:dataTypeName=number

metric m:spanish p:integer l:SPANISH t:dataTypeName=number

metric m:tagalog p:integer l:TAGALOG t:dataTypeName=number

metric m:thai p:integer l:THAI t:dataTypeName=number

metric m:unspecified p:integer l:UNSPECIFIED t:dataTypeName=number

metric m:urdu p:integer l:URDU t:dataTypeName=number

metric m:vietnamese p:integer l:VIETNAMESE t:dataTypeName=number

metric m:yiddish p:integer l:YIDDISH t:dataTypeName=number

entity e:a2fk-ec6q l:"Census Data - Languages spoken in Chicago, 2008 ? 2012" t:attribution="U.S. Census Bureau" t:url=https://data.cityofchicago.org/api/views/a2fk-ec6q

property e:a2fk-ec6q t:meta.view v:id=a2fk-ec6q v:category="Health & Human Services" v:attributionLink=http://factfinder2.census.gov/ v:averageRating=0 v:name="Census Data - Languages spoken in Chicago, 2008 ? 2012" v:attribution="U.S. Census Bureau"

property e:a2fk-ec6q t:meta.view.owner v:id=is6y-5c5n v:screenName=Jamyia v:displayName=Jamyia

property e:a2fk-ec6q t:meta.view.tableauthor v:id=is6y-5c5n v:screenName=Jamyia v:displayName=Jamyia
```

## Top Records

```ls
| community_area | community_area_name | predominant_non_english_language_ | african_languages | arabic | armenian | cambodian_mon_khmer_ | chinese | creole | french | german | greek | gujarati | hebrew | hindi | hmong | hungarian | italian | japanese | korean | laotian | navajo | other_asian | other_indic | other_indo_eurpoean | other_native_north_american | other_pacific_island | other_slavic | other_west_germanic | persian | polish | portuguese | russian | scandinavian | serbo_croatian | spanish | tagalog | thai | unspecified | urdu | vietnamese | yiddish | 
| ============== | =================== | ================================= | ================= | ====== | ======== | ==================== | ======= | ====== | ====== | ====== | ===== | ======== | ====== | ===== | ===== | ========= | ======= | ======== | ====== | ======= | ====== | =========== | =========== | =================== | =========================== | ==================== | ============ | =================== | ======= | ====== | ========== | ======= | ============ | ============== | ======= | ======= | ==== | =========== | ==== | ========== | ======= | 
| 1              | Rogers Park         | SPANISH (9.9%)                    | 332               | 165    | 65       | 19                   | 215     | 271    | 94     | 41     | 0     | 70       | 0      | 79    | 0     | 0         | 0       | 39       | 26     | 0       | 0      | 240         | 503         | 201                 | 0                           | 13                   | 196          | 0                   | 9       | 173    | 38         | 201     | 0            | 66             | 5302    | 106     | 0    | 14          | 85   | 0          | 5       | 
| 2              | West Ridge          | SPANISH (8.7%)                    | 374               | 1500   | 2        | 0                    | 939     | 110    | 115    | 19     | 274   | 639      | 114    | 825   | 0     | 51        | 74      | 31       | 332    | 0       | 0      | 318         | 680         | 708                 | 0                           | 124                  | 276          | 0                   | 0       | 245    | 0          | 486     | 0            | 1034           | 5889    | 323     | 69   | 846         | 1539 | 1028       | 121     | 
| 3              | Uptown              | SPANISH (4.9%)                    | 750               | 58     | 0        | 13                   | 462     | 0      | 79     | 22     | 5     | 0        | 0      | 47    | 0     | 0         | 31      | 8        | 378    | 0       | 0      | 257         | 42          | 157                 | 0                           | 68                   | 0            | 0                   | 15      | 92     | 0          | 603     | 0            | 233            | 2584    | 343     | 72   | 0           | 287  | 548        | 0       | 
| 4              | Lincoln Square      | SPANISH (8.4%)                    | 127               | 106    | 31       | 0                    | 117     | 12     | 40     | 35     | 347   | 0        | 0      | 0     | 9     | 6         | 0       | 12       | 304    | 31      | 13     | 0           | 14          | 414                 | 0                           | 30                   | 286          | 0                   | 0       | 38     | 11         | 88      | 0            | 250            | 2994    | 160     | 62   | 267         | 152  | 131        | 0       | 
| 5              | North Center        | SPANISH (4.2%)                    | 0                 | 0      | 0        | 0                    | 37      | 0      | 20     | 225    | 0     | 0        | 42     | 0     | 0     | 11        | 7       | 21       | 30     | 0       | 0      | 0           | 0           | 38                  | 0                           | 0                    | 0            | 0                   | 0       | 47     | 13         | 10      | 0            | 43             | 1260    | 76      | 0    | 9           | 0    | 10         | 0       | 
| 6              | Lake View           | SPANISH (1.9%)                    | 425               | 128    | 0        | 0                    | 281     | 0      | 103    | 140    | 22    | 48       | 0      | 6     | 0     | 23        | 11      | 140      | 131    | 0       | 0      | 12          | 38          | 65                  | 0                           | 13                   | 15           | 0                   | 23      | 159    | 41         | 422     | 14           | 73             | 1776    | 159     | 120  | 4           | 9    | 166        | 0       | 
| 7              | Lincoln Park        | SPANISH (1.2%)                    | 53                | 0      | 0        | 0                    | 127     | 0      | 197    | 12     | 28    | 39       | 15     | 7     | 0     | 0         | 38      | 92       | 57     | 0       | 0      | 21          | 0           | 121                 | 0                           | 0                    | 23           | 53                  | 6       | 61     | 0          | 55      | 0            | 164            | 740     | 20      | 0    | 28          | 0    | 0          | 0       | 
| 8              | Near North Side     | SPANISH (1.3%)                    | 51                | 125    | 0        | 14                   | 432     | 0      | 80     | 44     | 26    | 13       | 11     | 126   | 0     | 0         | 107     | 315      | 267    | 0       | 0      | 16          | 0           | 128                 | 0                           | 16                   | 0            | 14                  | 61      | 78     | 64         | 421     | 0            | 163            | 1005    | 90      | 163  | 129         | 6    | 54         | 0       | 
| 9              | Edison Park         | POLISH (2.3%)                     | 0                 | 0      | 0        | 0                    | 0       | 0      | 15     | 20     | 9     | 0        | 0      | 0     | 0     | 0         | 40      | 0        | 29     | 0       | 0      | 32          | 0           | 11                  | 0                           | 0                    | 60           | 0                   | 0       | 243    | 0          | 0       | 0            | 62             | 75      | 0       | 0    | 27          | 0    | 0          | 0       | 
| 10             | Norwood Park        | POLISH (6.5%)                     | 0                 | 117    | 0        | 26                   | 98      | 0      | 14     | 74     | 89    | 0        | 0      | 25    | 0     | 0         | 233     | 0        | 33     | 37      | 0      | 50          | 0           | 38                  | 0                           | 0                    | 78           | 0                   | 36      | 2299   | 18         | 12      | 0            | 228            | 937     | 178     | 0    | 14          | 0    | 79         | 0       | 
```