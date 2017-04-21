# 2012 SFO Customer Survey Data Set + Dictionary

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sfo-2012-data-file-final-weighted-datasf-ca53d) |
| Metadata | [Link](https://data.sfgov.org/api/views/ckai-dve4) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/ckai-dve4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/ckai-dve4/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | ckai-dve4 |
| Name | 2012 SFO Customer Survey Data Set + Dictionary |
| Category | Transportation |
| Tags | sfo, airport, customer, survey |
| Created | 2013-02-06T23:17:47Z |
| Publication Date | 2013-02-06T23:26:08Z |

## Description

SFO conducts a yearly comprehensive survey of our guests to gauge satisfaction with our facilities, services, and amenities.  SFO compares results to previous surveys to look for areas of improvement and discover elements of the guest experience that are not satisfactory.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type   |
| ======== | ============== | ================ | ================ | ========= | ============= |
| Yes      | numeric metric | respnum          | RESPNUM          | number    | number        |
| Yes      | series tag     | ccgid            | CCGID            | text      | number        |
| Yes      | series tag     | barea            | BAREA            | text      | text          |
| Yes      | numeric metric | gate             | GATE             | number    | number        |
| Yes      | numeric metric | strata           | STRATA           | number    | number        |
| Yes      | numeric metric | category         | CATEGORY         | number    | number        |
| Yes      | numeric metric | intdate          | INTDATE          | number    | number        |
| Yes      | numeric metric | airline          | AIRLINE          | number    | number        |
| Yes      | numeric metric | flight           | FLIGHT           | number    | number        |
| Yes      | numeric metric | dest             | DEST             | number    | number        |
| Yes      | numeric metric | destgeo          | DESTGEO          | number    | number        |
| Yes      | numeric metric | destmark         | DESTMARK         | number    | number        |
| Yes      | series tag     | arrtime          | ARRTIME          | text      | text          |
| Yes      | series tag     | deptime          | DEPTIME          | text      | text          |
| Yes      | numeric metric | minutes          | MINUTES          | number    | number        |
| Yes      | numeric metric | q2purp1          | Q2PURP1          | number    | number        |
| Yes      | numeric metric | q3getto1         | Q3GETTO1         | number    | number        |
| Yes      | numeric metric | q3park           | Q3PARK           | number    | number        |
| Yes      | numeric metric | q4bags           | Q4BAGS           | number    | number        |
| Yes      | numeric metric | q4buy            | Q4BUY            | number    | number        |
| Yes      | numeric metric | q4food           | Q4FOOD           | number    | number        |
| Yes      | numeric metric | q5notbuy         | Q5NOTBUY         | number    | number        |
| Yes      | numeric metric | q6nofood         | Q6NOFOOD         | number    | number        |
| Yes      | numeric metric | q7flyperyr       | Q7FLYPERYR       | number    | number        |
| Yes      | numeric metric | saq              | SAQ              | number    | number        |
| Yes      | numeric metric | q8a_art          | Q8A_ART          | number    | number        |
| Yes      | numeric metric | q8b_food         | Q8B_FOOD         | number    | number        |
| Yes      | numeric metric | q8c_shop         | Q8C_SHOP         | number    | number        |
| Yes      | numeric metric | q8d_signs        | Q8D_SIGNS        | number    | number        |
| Yes      | numeric metric | q8e_walk         | Q8E_WALK         | number    | number        |
| Yes      | numeric metric | q8f_screens      | Q8F_SCREENS      | number    | number        |
| Yes      | numeric metric | q8g_infoarr      | Q8G_INFOARR      | number    | number        |
| Yes      | numeric metric | q8h_infodep      | Q8H_INFODEP      | number    | number        |
| Yes      | numeric metric | q8i_road         | Q8I_ROAD         | number    | number        |
| Yes      | numeric metric | q8j_park         | Q8J_PARK         | number    | number        |
| Yes      | numeric metric | q8k_airtrain     | Q8K_AIRTRAIN     | number    | number        |
| Yes      | numeric metric | q8l_ltpark       | Q8L_LTPARK       | number    | number        |
| Yes      | numeric metric | q8m_rental       | Q8M_RENTAL       | number    | number        |
| Yes      | numeric metric | q8n_whole        | Q8N_WHOLE        | number    | number        |
| Yes      | numeric metric | q10a_clnboard    | Q10A_CLNBOARD    | number    | number        |
| Yes      | numeric metric | q10b_clnpark     | Q10B_CLNPARK     | number    | number        |
| Yes      | numeric metric | q10c_clnairtrain | Q10C_CLNAIRTRAIN | number    | number        |
| Yes      | numeric metric | q10d_clnrent     | Q10D_CLNRENT     | number    | number        |
| Yes      | numeric metric | q10e_clnfood     | Q10E_CLNFOOD     | number    | number        |
| Yes      | numeric metric | q10f_clnbath     | Q10F_CLNBATH     | number    | number        |
| Yes      | numeric metric | q11safe          | Q11SAFE          | number    | number        |
| Yes      | numeric metric | q12_useweb       | Q12_USEWEB       | number    | number        |
| Yes      | numeric metric | q13_rateweb      | Q13_RATEWEB      | number    | number        |
| Yes      | numeric metric | q14wheredepart   | Q14WHEREDEPART   | number    | number        |
| Yes      | numeric metric | q14rategetto     | Q14RATEGETTO     | number    | number        |
| Yes      | numeric metric | q15a_find        | Q15A_FIND        | number    | number        |
| Yes      | numeric metric | q15b_security    | Q15B_SECURITY    | number    | number        |
| Yes      | numeric metric | q16_problem      | Q16_PROBLEM      | number    | number        |
| Yes      | numeric metric | q17region        | Q17REGION        | number    | number        |
| Yes      | series tag     | q18zip           | Q18ZIP           | text      | calendar_date |
| Yes      | series tag     | q18country       | Q18COUNTRY       | text      | text          |
| Yes      | numeric metric | home             | HOME             | number    | number        |
| Yes      | numeric metric | q19_age          | Q19_AGE          | number    | number        |
| Yes      | numeric metric | q20_sex          | Q20_SEX          | number    | number        |
| Yes      | numeric metric | q21_income       | Q21_INCOME       | number    | number        |
| Yes      | numeric metric | lang             | LANG             | number    | number        |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ckai-dve4 d:2012-01-01T00:00:00.000Z t:deptime=11:45 t:arrtime=9:00 t:ccgid=3462 t:q18country=ARGENTINA t:barea=D m:q8f_screens=5 m:respnum=2686 m:q10b_clnpark=6 m:q6nofood=2 m:q8e_walk=4 m:q10e_clnfood=5 m:q4bags=1 m:q10a_clnboard=5 m:q2purp1=5 m:q8m_rental=6 m:gate=57 m:saq=2 m:intdate=2 m:q10d_clnrent=5 m:category=1 m:q17region=3 m:q8h_infodep=4 m:strata=2 m:destgeo=3 m:q8n_whole=4 m:q4buy=2 m:q16_problem=2 m:home=14 m:q3getto1=5 m:q10f_clnbath=5 m:q8i_road=4 m:q14rategetto=4 m:lang=1 m:q8c_shop=3 m:q14wheredepart=12 m:q8l_ltpark=5 m:q4food=1 m:q19_age=3 m:q20_sex=1 m:q10c_clnairtrain=5 m:airline=9 m:q8j_park=6 m:q8a_art=4 m:minutes=165 m:q7flyperyr=3 m:q8d_signs=4 m:q21_income=2 m:q8k_airtrain=5 m:q12_useweb=2 m:q11safe=5 m:q8g_infoarr=4 m:q15a_find=5 m:flight=2090 m:q5notbuy=2 m:destmark=4 m:q8b_food=4 m:dest=24 m:q15b_security=3

series e:ckai-dve4 d:2012-01-01T00:00:00.000Z t:deptime=11:45 t:arrtime=9:00 t:ccgid=3464 t:q18country=ARGENTINA t:barea=D m:q8f_screens=5 m:respnum=2688 m:q10b_clnpark=5 m:q6nofood=1 m:q8e_walk=5 m:q10e_clnfood=5 m:q4bags=0 m:q10a_clnboard=5 m:q2purp1=2 m:q8m_rental=0 m:gate=57 m:saq=2 m:intdate=2 m:q10d_clnrent=0 m:category=1 m:q17region=3 m:q8h_infodep=5 m:strata=2 m:destgeo=3 m:q8n_whole=5 m:q4buy=2 m:q16_problem=2 m:home=14 m:q3getto1=2 m:q10f_clnbath=5 m:q8i_road=5 m:q14rategetto=5 m:lang=2 m:q8c_shop=0 m:q14wheredepart=7 m:q8l_ltpark=0 m:q4food=2 m:q19_age=7 m:q20_sex=1 m:q10c_clnairtrain=0 m:airline=9 m:q8j_park=5 m:q8a_art=3 m:minutes=165 m:q7flyperyr=1 m:q8d_signs=0 m:q21_income=0 m:q8k_airtrain=0 m:q12_useweb=3 m:q11safe=5 m:q8g_infoarr=5 m:q15a_find=0 m:flight=2090 m:q5notbuy=1 m:destmark=4 m:q8b_food=4 m:dest=24 m:q15b_security=5

series e:ckai-dve4 d:2012-01-01T00:00:00.000Z t:deptime=12:45 t:arrtime=8:30 t:ccgid=1135 t:q18country=ARGENTINA t:barea=A m:q8f_screens=5 m:respnum=2897 m:q10b_clnpark=6 m:q6nofood=1 m:q8e_walk=5 m:q10e_clnfood=6 m:q4bags=1 m:q10a_clnboard=5 m:q2purp1=2 m:q8m_rental=5 m:gate=4 m:saq=2 m:intdate=5 m:q10d_clnrent=5 m:category=3 m:q17region=3 m:q8h_infodep=5 m:strata=2 m:destgeo=5 m:q8n_whole=5 m:q4buy=2 m:q16_problem=2 m:home=14 m:q3getto1=7 m:q10f_clnbath=5 m:q8i_road=5 m:q14rategetto=5 m:lang=2 m:q8c_shop=6 m:q14wheredepart=5 m:q8l_ltpark=6 m:q4food=2 m:q19_age=6 m:q20_sex=2 m:q10c_clnairtrain=5 m:airline=24 m:q8j_park=4 m:q8a_art=6 m:minutes=255 m:q7flyperyr=1 m:q8d_signs=5 m:q21_income=0 m:q8k_airtrain=5 m:q12_useweb=1 m:q11safe=4 m:q13_rateweb=5 m:q8g_infoarr=5 m:q15a_find=5 m:flight=2609 m:q5notbuy=1 m:destmark=2 m:q8b_food=6 m:dest=47 m:q15b_security=5
```

## Meta Commands

```ls
metric m:respnum p:integer l:RESPNUM t:dataTypeName=number

metric m:gate p:integer l:GATE t:dataTypeName=number

metric m:strata p:integer l:STRATA t:dataTypeName=number

metric m:category p:integer l:CATEGORY t:dataTypeName=number

metric m:intdate p:integer l:INTDATE t:dataTypeName=number

metric m:airline p:integer l:AIRLINE t:dataTypeName=number

metric m:flight p:integer l:FLIGHT t:dataTypeName=number

metric m:dest p:integer l:DEST t:dataTypeName=number

metric m:destgeo p:integer l:DESTGEO t:dataTypeName=number

metric m:destmark p:integer l:DESTMARK t:dataTypeName=number

metric m:minutes p:integer l:MINUTES t:dataTypeName=number

metric m:q2purp1 p:integer l:Q2PURP1 t:dataTypeName=number

metric m:q3getto1 p:integer l:Q3GETTO1 t:dataTypeName=number

metric m:q3park p:integer l:Q3PARK t:dataTypeName=number

metric m:q4bags p:integer l:Q4BAGS t:dataTypeName=number

metric m:q4buy p:integer l:Q4BUY t:dataTypeName=number

metric m:q4food p:integer l:Q4FOOD t:dataTypeName=number

metric m:q5notbuy p:integer l:Q5NOTBUY t:dataTypeName=number

metric m:q6nofood p:integer l:Q6NOFOOD t:dataTypeName=number

metric m:q7flyperyr p:integer l:Q7FLYPERYR t:dataTypeName=number

metric m:saq p:integer l:SAQ t:dataTypeName=number

metric m:q8a_art p:integer l:Q8A_ART t:dataTypeName=number

metric m:q8b_food p:integer l:Q8B_FOOD t:dataTypeName=number

metric m:q8c_shop p:integer l:Q8C_SHOP t:dataTypeName=number

metric m:q8d_signs p:integer l:Q8D_SIGNS t:dataTypeName=number

metric m:q8e_walk p:integer l:Q8E_WALK t:dataTypeName=number

metric m:q8f_screens p:integer l:Q8F_SCREENS t:dataTypeName=number

metric m:q8g_infoarr p:integer l:Q8G_INFOARR t:dataTypeName=number

metric m:q8h_infodep p:integer l:Q8H_INFODEP t:dataTypeName=number

metric m:q8i_road p:integer l:Q8I_ROAD t:dataTypeName=number

metric m:q8j_park p:integer l:Q8J_PARK t:dataTypeName=number

metric m:q8k_airtrain p:integer l:Q8K_AIRTRAIN t:dataTypeName=number

metric m:q8l_ltpark p:integer l:Q8L_LTPARK t:dataTypeName=number

metric m:q8m_rental p:integer l:Q8M_RENTAL t:dataTypeName=number

metric m:q8n_whole p:integer l:Q8N_WHOLE t:dataTypeName=number

metric m:q10a_clnboard p:integer l:Q10A_CLNBOARD t:dataTypeName=number

metric m:q10b_clnpark p:integer l:Q10B_CLNPARK t:dataTypeName=number

metric m:q10c_clnairtrain p:integer l:Q10C_CLNAIRTRAIN t:dataTypeName=number

metric m:q10d_clnrent p:integer l:Q10D_CLNRENT t:dataTypeName=number

metric m:q10e_clnfood p:integer l:Q10E_CLNFOOD t:dataTypeName=number

metric m:q10f_clnbath p:integer l:Q10F_CLNBATH t:dataTypeName=number

metric m:q11safe p:integer l:Q11SAFE t:dataTypeName=number

metric m:q12_useweb p:integer l:Q12_USEWEB t:dataTypeName=number

metric m:q13_rateweb p:integer l:Q13_RATEWEB t:dataTypeName=number

metric m:q14wheredepart p:integer l:Q14WHEREDEPART t:dataTypeName=number

metric m:q14rategetto p:integer l:Q14RATEGETTO t:dataTypeName=number

metric m:q15a_find p:integer l:Q15A_FIND t:dataTypeName=number

metric m:q15b_security p:integer l:Q15B_SECURITY t:dataTypeName=number

metric m:q16_problem p:integer l:Q16_PROBLEM t:dataTypeName=number

metric m:q17region p:integer l:Q17REGION t:dataTypeName=number

metric m:home p:integer l:HOME t:dataTypeName=number

metric m:q19_age p:integer l:Q19_AGE t:dataTypeName=number

metric m:q20_sex p:integer l:Q20_SEX t:dataTypeName=number

metric m:q21_income p:integer l:Q21_INCOME t:dataTypeName=number

metric m:lang p:integer l:LANG t:dataTypeName=number

entity e:ckai-dve4 l:"2012 SFO Customer Survey Data Set + Dictionary" t:url=https://data.sfgov.org/api/views/ckai-dve4

property e:ckai-dve4 t:meta.view v:id=ckai-dve4 v:category=Transportation v:averageRating=0 v:name="2012 SFO Customer Survey Data Set + Dictionary"

property e:ckai-dve4 t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:ckai-dve4 t:meta.view.owner v:id=mf3h-st4n v:profileImageUrlMedium=/api/users/mf3h-st4n/profile_images/THUMB v:profileImageUrlLarge=/api/users/mf3h-st4n/profile_images/LARGE v:screenName=Chris v:profileImageUrlSmall=/api/users/mf3h-st4n/profile_images/TINY v:displayName=Chris

property e:ckai-dve4 t:meta.view.tableauthor v:id=mf3h-st4n v:profileImageUrlMedium=/api/users/mf3h-st4n/profile_images/THUMB v:profileImageUrlLarge=/api/users/mf3h-st4n/profile_images/LARGE v:screenName=Chris v:profileImageUrlSmall=/api/users/mf3h-st4n/profile_images/TINY v:roleName=editor v:displayName=Chris
```

## Top Records

```ls
| respnum | ccgid | barea | gate | strata | category | intdate | airline | flight | dest | destgeo | destmark | arrtime | deptime | minutes | q2purp1 | q3getto1 | q3park | q4bags | q4buy | q4food | q5notbuy | q6nofood | q7flyperyr | saq | q8a_art | q8b_food | q8c_shop | q8d_signs | q8e_walk | q8f_screens | q8g_infoarr | q8h_infodep | q8i_road | q8j_park | q8k_airtrain | q8l_ltpark | q8m_rental | q8n_whole | q10a_clnboard | q10b_clnpark | q10c_clnairtrain | q10d_clnrent | q10e_clnfood | q10f_clnbath | q11safe | q12_useweb | q13_rateweb | q14wheredepart | q14rategetto | q15a_find | q15b_security | q16_problem | q17region | q18zip | q18country | home | q19_age | q20_sex | q21_income | lang | 
| ======= | ===== | ===== | ==== | ====== | ======== | ======= | ======= | ====== | ==== | ======= | ======== | ======= | ======= | ======= | ======= | ======== | ====== | ====== | ===== | ====== | ======== | ======== | ========== | === | ======= | ======== | ======== | ========= | ======== | =========== | =========== | =========== | ======== | ======== | ============ | ========== | ========== | ========= | ============= | ============ | ================ | ============ | ============ | ============ | ======= | ========== | =========== | ============== | ============ | ========= | ============= | =========== | ========= | ====== | ========== | ==== | ======= | ======= | ========== | ==== | 
| 2686    | 3462  | D     | 57   | 2      | 1        | 2       | 9       | 2090   | 24   | 3       | 4        | 9:00    | 11:45   | 165     | 5       | 5        |        | 1      | 2     | 1      | 2        | 2        | 3          | 2   | 4       | 4        | 3        | 4         | 4        | 5           | 4           | 4           | 4        | 6        | 5            | 5          | 6          | 4         | 5             | 6            | 5                | 5            | 5            | 5            | 5       | 2          |             | 12             | 4            | 5         | 3             | 2           | 3         |        | ARGENTINA  | 14   | 3       | 1       | 2          | 1    | 
| 2688    | 3464  | D     | 57   | 2      | 1        | 2       | 9       | 2090   | 24   | 3       | 4        | 9:00    | 11:45   | 165     | 2       | 2        |        | 0      | 2     | 2      | 1        | 1        | 1          | 2   | 3       | 4        | 0        | 0         | 5        | 5           | 5           | 5           | 5        | 5        | 0            | 0          | 0          | 5         | 5             | 5            | 0                | 0            | 5            | 5            | 5       | 3          |             | 7              | 5            | 0         | 5             | 2           | 3         |        | ARGENTINA  | 14   | 7       | 1       | 0          | 2    | 
| 2897    | 1135  | A     | 4    | 2      | 3        | 5       | 24      | 2609   | 47   | 5       | 2        | 8:30    | 12:45   | 255     | 2       | 7        |        | 1      | 2     | 2      | 1        | 1        | 1          | 2   | 6       | 6        | 6        | 5         | 5        | 5           | 5           | 5           | 5        | 4        | 5            | 6          | 5          | 5         | 5             | 6            | 5                | 5            | 6            | 5            | 4       | 1          | 5           | 5              | 5            | 5         | 5             | 2           | 3         |        | ARGENTINA  | 14   | 6       | 2       | 0          | 2    | 
| 2902    | 1140  | A     | 4    | 2      | 3        | 5       | 24      | 2609   | 47   | 5       | 2        | 9:30    | 12:45   | 195     | 2       | 6        |        | 1      | 2     | 2      | 1        | 2        | 1          | 2   | 6       | 6        | 6        | 6         | 6        | 6           | 6           | 6           | 6        | 6        | 6            | 6          | 6          | 6         | 0             | 0            | 0                | 0            | 0            | 5            | 0       | 2          |             | 12             | 0            | 0         | 0             | 0           | 3         |        | ARGENTINA  | 14   | 3       | 2       | 0          | 1    | 
| 2903    | 1141  | A     | 4    | 2      | 3        | 5       | 24      | 2609   | 47   | 5       | 2        | 9:45    | 12:45   | 180     | 5       | 8        |        | 1      | 2     | 2      | 1        | 2        | 1          | 2   | 4       | 4        | 2        | 4         | 4        | 5           | 6           | 6           | 6        | 6        | 6            | 6          | 6          | 4         | 5             | 5            | 6                | 6            | 5            | 5            | 5       | 2          |             | 5              | 5            | 5         | 3             | 2           | 3         |        | ARGENTINA  | 14   | 5       | 1       | 3          | 1    | 
| 1275    | 2125  | F     | 68   | 2      | 3        | 11      | 33      | 871    | 95   | 4       | 3        | 11:30   | 16:02   | 272     | 2       | 3        |        | 1      | 1     | 2      | 0        | 2        | 1          | 2   | 6       | 6        | 4        | 5         | 5        | 5           | 6           | 6           | 6        | 6        | 6            | 6          | 6          | 4         | 5             | 6            | 6                | 6            | 6            | 5            | 5       | 2          |             | 11             | 6            | 5         | 3             | 2           | 4         |        | AUSTRAILA  | 19   | 4       | 1       | 0          | 1    | 
| 2643    | 1266  | C     | 44   | 2      | 2        | 2       | 15      | 4683   | 50   | 1       | 4        | N       | 16:50   |         | 2       | 4        |        | 1      | 1     | 1      | 2        | 1        | 1          | 2   | 4       | 4        | 4        | 0         | 0        | 0           | 0           | 0           | 6        | 6        | 6            | 6          | 6          | 4         | 5             | 0            | 0                | 0            | 0            | 5            | 5       | 2          |             | 5              | 4            | 5         | 5             | 2           | 3         |        | AUSTRAILA  | 19   | 7       | 1       | 2          | 1    | 
| 136     | 261   | D     | 54   | 3      | 2        | 3       | 35      | 30     | 60   | 2       | 4        | 19:30   | 21:20   | 110     | 2       | 9        |        | 1      | 1     | 2      | 2        | 2        | 1          | 2   | 6       | 6        | 4        | 5         | 5        | 6           | 6           | 6           | 4        | 6        | 5            | 6          | 5          | 5         | 5             | 6            | 5                | 5            | 6            | 5            | 5       | 2          |             | 5              | 0            | 5         | 5             | 2           | 3         |        | AUSTRALIA  | 19   | 3       | 2       | 4          | 1    | 
| 137     | 262   | D     | 54   | 3      | 2        | 3       | 35      | 30     | 60   | 2       | 4        | 19:30   | 21:20   | 110     | 2       | 9        |        | 1      | 1     | 2      | 2        | 2        | 1          | 2   | 6       | 6        | 3        | 4         | 3        | 4           | 6           | 6           | 6        | 6        | 5            | 6          | 5          | 4         | 5             | 5            | 5                | 5            | 6            | 4            | 5       | 2          |             | 6              | 5            | 5         | 5             | 2           | 3         |        | AUSTRALIA  | 19   | 3       | 1       | 4          | 1    | 
| 167     | 252   | D     | 58   | 1      | 1        | 5       | 9       | 802    | 24   | 3       | 4        | 7:00    | 8:20    | 80      | 1       | 8        |        | 1      | 2     | 2      | 2        | 2        | 1          | 2   | 4       | 6        | 6        | 4         | 6        | 4           | 6           | 6           | 0        | 0        | 0            | 0          | 0          | 0         | 5             | 6            | 6                | 6            | 6            | 5            | 5       | 2          |             | 5              | 5            | 5         | 1             | 2           | 3         |        | AUSTRALIA  | 19   | 3       | 1       | 3          | 1    | 
```