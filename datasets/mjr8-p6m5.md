# 2013 SFO Customer Survey Data Set + Dictionary

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2013-sfo-customer-survey-d3541) |
| Metadata | [Link](https://data.sfgov.org/api/views/mjr8-p6m5) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/mjr8-p6m5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/mjr8-p6m5/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | mjr8-p6m5 |
| Name | 2013 SFO Customer Survey Data Set + Dictionary |
| Category | Transportation |
| Tags | sfo, airport, customer, survey |
| Created | 2014-01-02T22:27:41Z |
| Publication Date | 2014-01-02T23:03:22Z |

## Description

SFO conducts a yearly comprehensive survey of our guests to gauge satisfaction with our facilities, services, and amenities.  SFO compares results to previous surveys to look for areas of improvement and discover elements of the guest experience that are not satisfactory.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| Yes      | numeric metric | respnum         | RESPNUM         | number    | number      |
| Yes      | series tag     | ccgid           | CCGID           | text      | number      |
| Yes      | numeric metric | run             | RUN             | number    | number      |
| Yes      | numeric metric | intdate         | INTDATE         | number    | number      |
| Yes      | numeric metric | gate            | GATE            | number    | number      |
| Yes      | numeric metric | strata          | STRATA          | number    | number      |
| Yes      | numeric metric | peak            | PEAK            | number    | number      |
| Yes      | numeric metric | method          | METHOD          | number    | number      |
| Yes      | numeric metric | airline         | AIRLINE         | number    | number      |
| Yes      | numeric metric | flight          | FLIGHT          | number    | number      |
| Yes      | numeric metric | dest            | DEST            | number    | number      |
| Yes      | numeric metric | destgeo         | DESTGEO         | number    | number      |
| Yes      | numeric metric | destmark        | DESTMARK        | number    | number      |
| Yes      | series tag     | arrtime         | ARRTIME         | text      | text        |
| Yes      | series tag     | deptime         | DEPTIME         | text      | text        |
| Yes      | numeric metric | q2purp1         | Q2PURP1         | number    | number      |
| Yes      | numeric metric | q2purp2         | Q2PURP2         | number    | number      |
| Yes      | numeric metric | q2purp3         | Q2PURP3         | number    | number      |
| Yes      | numeric metric | q2purp4         | Q2PURP4         | number    | number      |
| Yes      | numeric metric | q2purp5         | Q2PURP5         | number    | number      |
| Yes      | series tag     | q2purp6         | Q2PURP6         | text      | text        |
| Yes      | numeric metric | q3getto1        | Q3GETTO1        | number    | number      |
| Yes      | numeric metric | q3getto2        | Q3GETTO2        | number    | number      |
| Yes      | numeric metric | q3getto3        | Q3GETTO3        | number    | number      |
| Yes      | numeric metric | q3getto4        | Q3GETTO4        | number    | number      |
| Yes      | series tag     | q3getto5        | Q3GETTO5        | text      | text        |
| Yes      | series tag     | q3getto6        | Q3GETTO6        | text      | text        |
| Yes      | numeric metric | q3park          | Q3PARK          | number    | number      |
| Yes      | numeric metric | q4bags          | Q4BAGS          | number    | number      |
| Yes      | numeric metric | q4buy           | Q4BUY           | number    | number      |
| Yes      | numeric metric | q4food          | Q4FOOD          | number    | number      |
| Yes      | numeric metric | q4wifi          | Q4WIFI          | number    | number      |
| Yes      | numeric metric | q5flyperyr      | Q5FLYPERYR      | number    | number      |
| Yes      | numeric metric | q6tenure        | Q6TENURE        | number    | number      |
| Yes      | numeric metric | saq             | SAQ             | number    | number      |
| Yes      | numeric metric | q7a_art         | Q7A_ART         | number    | number      |
| Yes      | numeric metric | q7b_food        | Q7B_FOOD        | number    | number      |
| Yes      | numeric metric | q7c_shops       | Q7C_SHOPS       | number    | number      |
| Yes      | numeric metric | q7d_signs       | Q7D_SIGNS       | number    | number      |
| Yes      | numeric metric | q7e_walk        | Q7E_WALK        | number    | number      |
| Yes      | numeric metric | q7f_screens     | Q7F_SCREENS     | number    | number      |
| Yes      | numeric metric | q7g_infoarr     | Q7G_INFOARR     | number    | number      |
| Yes      | numeric metric | q7h_infodep     | Q7H_INFODEP     | number    | number      |
| Yes      | numeric metric | q7i_wifi        | Q7I_WIFI        | number    | number      |
| Yes      | numeric metric | q7j_road        | Q7J_ROAD        | number    | number      |
| Yes      | numeric metric | q7k_park        | Q7K_PARK        | number    | number      |
| Yes      | numeric metric | q7l_airtrain    | Q7L_AIRTRAIN    | number    | number      |
| Yes      | numeric metric | q7m_ltpark      | Q7M_LTPARK      | number    | number      |
| Yes      | numeric metric | q7n_rental      | Q7N_RENTAL      | number    | number      |
| Yes      | numeric metric | q7o_whole       | Q7O_WHOLE       | number    | number      |
| Yes      | numeric metric | q8com1          | Q8COM1          | number    | number      |
| Yes      | numeric metric | q8com2          | Q8COM2          | number    | number      |
| Yes      | numeric metric | q8com3          | Q8COM3          | number    | number      |
| Yes      | numeric metric | q9a_clnboard    | Q9A_CLNBOARD    | number    | number      |
| Yes      | numeric metric | q9b_clnairtrain | Q9B_CLNAIRTRAIN | number    | number      |
| Yes      | numeric metric | q9c_clnrent     | Q9C_CLNRENT     | number    | number      |
| Yes      | numeric metric | q9d_clnfood     | Q9D_CLNFOOD     | number    | number      |
| Yes      | numeric metric | q9e_clnbath     | Q9E_CLNBATH     | number    | number      |
| Yes      | numeric metric | q9f_clnwhole    | Q9F_CLNWHOLE    | number    | number      |
| Yes      | numeric metric | q9com1          | Q9COM1          | number    | number      |
| Yes      | numeric metric | q9com2          | Q9COM2          | number    | number      |
| Yes      | numeric metric | q9com3          | Q9COM3          | number    | number      |
| Yes      | numeric metric | q10safe         | Q10SAFE         | number    | number      |
| Yes      | numeric metric | q10com1         | Q10COM1         | number    | number      |
| Yes      | numeric metric | q10com2         | Q10COM2         | number    | number      |
| Yes      | numeric metric | q10com3         | Q10COM3         | number    | number      |
| Yes      | numeric metric | q11a_useweb     | Q11A_USEWEB     | number    | number      |
| Yes      | numeric metric | q11b_usesfoapp  | Q11B_USESFOAPP  | number    | number      |
| Yes      | numeric metric | q11c_useothapp  | Q11C_USEOTHAPP  | number    | number      |
| Yes      | numeric metric | q11d_usesocmed  | Q11D_USESOCMED  | number    | number      |
| Yes      | numeric metric | q11e_usewifi    | Q11E_USEWIFI    | number    | number      |
| Yes      | numeric metric | q12com1         | Q12COM1         | number    | number      |
| Yes      | numeric metric | q12com2         | Q12COM2         | number    | number      |
| Yes      | numeric metric | q12com3         | Q12COM3         | number    | number      |
| Yes      | numeric metric | q13_wheredepart | Q13_WHEREDEPART | number    | number      |
| Yes      | numeric metric | q13_rategetto   | Q13_RATEGETTO   | number    | number      |
| Yes      | numeric metric | q14a_find       | Q14A_FIND       | number    | number      |
| Yes      | numeric metric | q14b_security   | Q14B_SECURITY   | number    | number      |
| Yes      | numeric metric | q15_problems    | Q15_PROBLEMS    | number    | number      |
| Yes      | numeric metric | q15com1         | Q15COM1         | number    | number      |
| Yes      | numeric metric | q15com2         | Q15COM2         | number    | number      |
| Yes      | numeric metric | q15com3         | Q15COM3         | number    | number      |
| Yes      | numeric metric | q16_region      | Q16_REGION      | number    | number      |
| Yes      | series tag     | q17_city        | Q17_CITY        | text      | text        |
| Yes      | series tag     | q17_zip         | Q17_ZIP         | text      | number      |
| Yes      | series tag     | q17_country     | Q17_COUNTRY     | text      | text        |
| Yes      | numeric metric | home            | HOME            | number    | number      |
| Yes      | numeric metric | q18_age         | Q18_AGE         | number    | number      |
| Yes      | numeric metric | q19_sex         | Q19_SEX         | number    | number      |
| Yes      | numeric metric | q20_income      | Q20_INCOME      | number    | number      |
| Yes      | numeric metric | q21_hiflyer     | Q21_HIFLYER     | number    | number      |
| Yes      | numeric metric | q22a_usesjc     | Q22A_USESJC     | number    | number      |
| Yes      | numeric metric | q22b_useoak     | Q22B_USEOAK     | number    | number      |
| Yes      | numeric metric | lang            | LANG            | number    | number      |
| Yes      | numeric metric | weight          | WEIGHT          | number    | number      |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:mjr8-p6m5 d:2013-01-01T00:00:00.000Z t:q17_city="SAN FRANCISCO" t:q17_country=US t:deptime="9:25 AM" t:arrtime="8:34 AM" t:ccgid=1 t:q17_zip=94131 m:respnum=1 m:q11a_useweb=2 m:q7o_whole=3 m:q7g_infoarr=3 m:q7a_art=3 m:q7k_park=3 m:q4wifi=2 m:q6tenure=2 m:q7i_wifi=3 m:q7d_signs=3 m:q7j_road=3 m:q7c_shops=3 m:q21_hiflyer=2 m:q22a_usesjc=2 m:q4bags=2 m:q10com1=1 m:q2purp1=1 m:q9b_clnairtrain=3 m:gate=12 m:q2purp2=8 m:q11e_usewifi=2 m:q20_income=1 m:saq=1 m:intdate=2 m:q11d_usesocmed=2 m:q7n_rental=3 m:strata=1 m:destgeo=1 m:q9a_clnboard=3 m:q9c_clnrent=3 m:q11c_useothapp=2 m:q5flyperyr=6 m:q4buy=1 m:q19_sex=1 m:q15_problems=2 m:q14b_security=3 m:home=1 m:q18_age=2 m:weight=0.553675 m:q7f_screens=3 m:q3getto1=2 m:peak=1 m:q3getto2=10 m:q10safe=5 m:q9f_clnwhole=4 m:q7h_infodep=3 m:run=1215 m:lang=1 m:q7m_ltpark=3 m:q4food=2 m:q9d_clnfood=3 m:airline=21 m:q22b_useoak=1 m:q11b_usesfoapp=2 m:q16_region=1 m:q9e_clnbath=4 m:flight=1437 m:q14a_find=3 m:destmark=1 m:dest=49 m:q7l_airtrain=3 m:q7e_walk=3 m:method=1 m:q7b_food=4 m:q13_wheredepart=5 m:q13_rategetto=3

series e:mjr8-p6m5 d:2013-01-01T00:00:00.000Z t:q17_city=CONCORD t:q17_country=US t:deptime="9:25 AM" t:arrtime="8:00 AM" t:ccgid=2 t:q17_zip=94521 m:respnum=2 m:q11a_useweb=2 m:q7o_whole=4 m:q7g_infoarr=3 m:q7a_art=4 m:q7k_park=6 m:q4wifi=2 m:q6tenure=4 m:q7i_wifi=6 m:q7d_signs=4 m:q7j_road=4 m:q7c_shops=4 m:q21_hiflyer=3 m:q22a_usesjc=2 m:q4bags=2 m:q10com1=1 m:q2purp1=1 m:q9b_clnairtrain=6 m:gate=12 m:q2purp2=8 m:q11e_usewifi=3 m:q20_income=0 m:saq=1 m:intdate=2 m:q11d_usesocmed=2 m:q7n_rental=6 m:strata=1 m:destgeo=1 m:q9a_clnboard=4 m:q9c_clnrent=6 m:q11c_useothapp=2 m:q5flyperyr=6 m:q4buy=2 m:q19_sex=1 m:q15_problems=2 m:q14b_security=5 m:home=5 m:q18_age=6 m:weight=0.553675 m:q7f_screens=3 m:q3getto1=2 m:peak=1 m:q3getto2=10 m:q10safe=5 m:q9f_clnwhole=4 m:q7h_infodep=3 m:run=1215 m:lang=1 m:q7m_ltpark=6 m:q4food=2 m:q9d_clnfood=4 m:airline=21 m:q22b_useoak=1 m:q11b_usesfoapp=2 m:q16_region=1 m:q9e_clnbath=4 m:flight=1437 m:q14a_find=5 m:destmark=1 m:dest=49 m:q7l_airtrain=6 m:q7e_walk=4 m:method=1 m:q7b_food=4 m:q13_wheredepart=2 m:q13_rategetto=3

series e:mjr8-p6m5 d:2013-01-01T00:00:00.000Z t:q17_city="SAN FRANCISCO" t:q17_country=US t:deptime="9:25 AM" t:arrtime="7:00 AM" t:ccgid=3 t:q17_zip=94134 m:respnum=3 m:q11a_useweb=2 m:q7o_whole=0 m:q7g_infoarr=2 m:q7a_art=3 m:q7k_park=3 m:q4wifi=2 m:q6tenure=4 m:q7i_wifi=3 m:q7d_signs=2 m:q7j_road=2 m:q7c_shops=4 m:q21_hiflyer=3 m:q22a_usesjc=2 m:q4bags=2 m:q10com1=1 m:q2purp1=1 m:q9b_clnairtrain=3 m:gate=12 m:q2purp2=8 m:q11e_usewifi=2 m:q20_income=2 m:saq=1 m:intdate=2 m:q11d_usesocmed=2 m:q7n_rental=4 m:strata=1 m:destgeo=1 m:q9a_clnboard=3 m:q9c_clnrent=3 m:q11c_useothapp=2 m:q5flyperyr=4 m:q4buy=2 m:q19_sex=2 m:q15_problems=2 m:q14b_security=3 m:home=1 m:q18_age=4 m:weight=0.553675 m:q7f_screens=4 m:q3getto1=2 m:peak=1 m:q3getto2=10 m:q10safe=3 m:q9f_clnwhole=3 m:q7h_infodep=2 m:run=1215 m:lang=1 m:q7m_ltpark=6 m:q4food=2 m:q9d_clnfood=3 m:airline=21 m:q22b_useoak=2 m:q11b_usesfoapp=2 m:q16_region=1 m:q9e_clnbath=3 m:flight=1437 m:q14a_find=3 m:destmark=1 m:dest=49 m:q7l_airtrain=4 m:q7e_walk=4 m:method=1 m:q7b_food=4 m:q13_wheredepart=5 m:q13_rategetto=3
```

## Meta Commands

```ls
metric m:respnum p:integer l:RESPNUM t:dataTypeName=number

metric m:run p:integer l:RUN t:dataTypeName=number

metric m:intdate p:integer l:INTDATE t:dataTypeName=number

metric m:gate p:integer l:GATE t:dataTypeName=number

metric m:strata p:integer l:STRATA t:dataTypeName=number

metric m:peak p:integer l:PEAK t:dataTypeName=number

metric m:method p:integer l:METHOD t:dataTypeName=number

metric m:airline p:integer l:AIRLINE t:dataTypeName=number

metric m:flight p:integer l:FLIGHT t:dataTypeName=number

metric m:dest p:integer l:DEST t:dataTypeName=number

metric m:destgeo p:integer l:DESTGEO t:dataTypeName=number

metric m:destmark p:integer l:DESTMARK t:dataTypeName=number

metric m:q2purp1 p:integer l:Q2PURP1 t:dataTypeName=number

metric m:q2purp2 p:integer l:Q2PURP2 t:dataTypeName=number

metric m:q2purp3 p:integer l:Q2PURP3 t:dataTypeName=number

metric m:q2purp4 p:integer l:Q2PURP4 t:dataTypeName=number

metric m:q2purp5 p:integer l:Q2PURP5 t:dataTypeName=number

metric m:q3getto1 p:integer l:Q3GETTO1 t:dataTypeName=number

metric m:q3getto2 p:integer l:Q3GETTO2 t:dataTypeName=number

metric m:q3getto3 p:integer l:Q3GETTO3 t:dataTypeName=number

metric m:q3getto4 p:integer l:Q3GETTO4 t:dataTypeName=number

metric m:q3park p:integer l:Q3PARK t:dataTypeName=number

metric m:q4bags p:integer l:Q4BAGS t:dataTypeName=number

metric m:q4buy p:integer l:Q4BUY t:dataTypeName=number

metric m:q4food p:integer l:Q4FOOD t:dataTypeName=number

metric m:q4wifi p:integer l:Q4WIFI t:dataTypeName=number

metric m:q5flyperyr p:integer l:Q5FLYPERYR t:dataTypeName=number

metric m:q6tenure p:float l:Q6TENURE t:dataTypeName=number

metric m:saq p:integer l:SAQ t:dataTypeName=number

metric m:q7a_art p:integer l:Q7A_ART t:dataTypeName=number

metric m:q7b_food p:integer l:Q7B_FOOD t:dataTypeName=number

metric m:q7c_shops p:integer l:Q7C_SHOPS t:dataTypeName=number

metric m:q7d_signs p:integer l:Q7D_SIGNS t:dataTypeName=number

metric m:q7e_walk p:integer l:Q7E_WALK t:dataTypeName=number

metric m:q7f_screens p:integer l:Q7F_SCREENS t:dataTypeName=number

metric m:q7g_infoarr p:integer l:Q7G_INFOARR t:dataTypeName=number

metric m:q7h_infodep p:integer l:Q7H_INFODEP t:dataTypeName=number

metric m:q7i_wifi p:integer l:Q7I_WIFI t:dataTypeName=number

metric m:q7j_road p:integer l:Q7J_ROAD t:dataTypeName=number

metric m:q7k_park p:integer l:Q7K_PARK t:dataTypeName=number

metric m:q7l_airtrain p:integer l:Q7L_AIRTRAIN t:dataTypeName=number

metric m:q7m_ltpark p:integer l:Q7M_LTPARK t:dataTypeName=number

metric m:q7n_rental p:integer l:Q7N_RENTAL t:dataTypeName=number

metric m:q7o_whole p:integer l:Q7O_WHOLE t:dataTypeName=number

metric m:q8com1 p:integer l:Q8COM1 t:dataTypeName=number

metric m:q8com2 p:integer l:Q8COM2 t:dataTypeName=number

metric m:q8com3 p:integer l:Q8COM3 t:dataTypeName=number

metric m:q9a_clnboard p:integer l:Q9A_CLNBOARD t:dataTypeName=number

metric m:q9b_clnairtrain p:integer l:Q9B_CLNAIRTRAIN t:dataTypeName=number

metric m:q9c_clnrent p:integer l:Q9C_CLNRENT t:dataTypeName=number

metric m:q9d_clnfood p:integer l:Q9D_CLNFOOD t:dataTypeName=number

metric m:q9e_clnbath p:integer l:Q9E_CLNBATH t:dataTypeName=number

metric m:q9f_clnwhole p:integer l:Q9F_CLNWHOLE t:dataTypeName=number

metric m:q9com1 p:integer l:Q9COM1 t:dataTypeName=number

metric m:q9com2 p:integer l:Q9COM2 t:dataTypeName=number

metric m:q9com3 p:integer l:Q9COM3 t:dataTypeName=number

metric m:q10safe p:integer l:Q10SAFE t:dataTypeName=number

metric m:q10com1 p:integer l:Q10COM1 t:dataTypeName=number

metric m:q10com2 p:integer l:Q10COM2 t:dataTypeName=number

metric m:q10com3 p:integer l:Q10COM3 t:dataTypeName=number

metric m:q11a_useweb p:integer l:Q11A_USEWEB t:dataTypeName=number

metric m:q11b_usesfoapp p:integer l:Q11B_USESFOAPP t:dataTypeName=number

metric m:q11c_useothapp p:integer l:Q11C_USEOTHAPP t:dataTypeName=number

metric m:q11d_usesocmed p:integer l:Q11D_USESOCMED t:dataTypeName=number

metric m:q11e_usewifi p:integer l:Q11E_USEWIFI t:dataTypeName=number

metric m:q12com1 p:integer l:Q12COM1 t:dataTypeName=number

metric m:q12com2 p:integer l:Q12COM2 t:dataTypeName=number

metric m:q12com3 p:integer l:Q12COM3 t:dataTypeName=number

metric m:q13_wheredepart p:integer l:Q13_WHEREDEPART t:dataTypeName=number

metric m:q13_rategetto p:integer l:Q13_RATEGETTO t:dataTypeName=number

metric m:q14a_find p:integer l:Q14A_FIND t:dataTypeName=number

metric m:q14b_security p:integer l:Q14B_SECURITY t:dataTypeName=number

metric m:q15_problems p:integer l:Q15_PROBLEMS t:dataTypeName=number

metric m:q15com1 p:integer l:Q15COM1 t:dataTypeName=number

metric m:q15com2 p:integer l:Q15COM2 t:dataTypeName=number

metric m:q15com3 p:integer l:Q15COM3 t:dataTypeName=number

metric m:q16_region p:integer l:Q16_REGION t:dataTypeName=number

metric m:home p:integer l:HOME t:dataTypeName=number

metric m:q18_age p:integer l:Q18_AGE t:dataTypeName=number

metric m:q19_sex p:integer l:Q19_SEX t:dataTypeName=number

metric m:q20_income p:integer l:Q20_INCOME t:dataTypeName=number

metric m:q21_hiflyer p:integer l:Q21_HIFLYER t:dataTypeName=number

metric m:q22a_usesjc p:integer l:Q22A_USESJC t:dataTypeName=number

metric m:q22b_useoak p:integer l:Q22B_USEOAK t:dataTypeName=number

metric m:lang p:integer l:LANG t:dataTypeName=number

metric m:weight p:float l:WEIGHT t:dataTypeName=number

entity e:mjr8-p6m5 l:"2013 SFO Customer Survey Data Set + Dictionary" t:url=https://data.sfgov.org/api/views/mjr8-p6m5

property e:mjr8-p6m5 t:meta.view v:id=mjr8-p6m5 v:category=Transportation v:averageRating=0 v:name="2013 SFO Customer Survey Data Set + Dictionary"

property e:mjr8-p6m5 t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:mjr8-p6m5 t:meta.view.owner v:id=mf3h-st4n v:profileImageUrlMedium=/api/users/mf3h-st4n/profile_images/THUMB v:profileImageUrlLarge=/api/users/mf3h-st4n/profile_images/LARGE v:screenName=Chris v:profileImageUrlSmall=/api/users/mf3h-st4n/profile_images/TINY v:displayName=Chris

property e:mjr8-p6m5 t:meta.view.tableauthor v:id=mf3h-st4n v:profileImageUrlMedium=/api/users/mf3h-st4n/profile_images/THUMB v:profileImageUrlLarge=/api/users/mf3h-st4n/profile_images/LARGE v:screenName=Chris v:profileImageUrlSmall=/api/users/mf3h-st4n/profile_images/TINY v:roleName=editor v:displayName=Chris
```

## Top Records

```ls
| respnum | ccgid | run  | intdate | gate | strata | peak | method | airline | flight | dest | destgeo | destmark | arrtime | deptime  | q2purp1 | q2purp2 | q2purp3 | q2purp4 | q2purp5 | q2purp6 | q3getto1 | q3getto2 | q3getto3 | q3getto4 | q3getto5 | q3getto6 | q3park | q4bags | q4buy | q4food | q4wifi | q5flyperyr | q6tenure | saq | q7a_art | q7b_food | q7c_shops | q7d_signs | q7e_walk | q7f_screens | q7g_infoarr | q7h_infodep | q7i_wifi | q7j_road | q7k_park | q7l_airtrain | q7m_ltpark | q7n_rental | q7o_whole | q8com1 | q8com2 | q8com3 | q9a_clnboard | q9b_clnairtrain | q9c_clnrent | q9d_clnfood | q9e_clnbath | q9f_clnwhole | q9com1 | q9com2 | q9com3 | q10safe | q10com1 | q10com2 | q10com3 | q11a_useweb | q11b_usesfoapp | q11c_useothapp | q11d_usesocmed | q11e_usewifi | q12com1 | q12com2 | q12com3 | q13_wheredepart | q13_rategetto | q14a_find | q14b_security | q15_problems | q15com1 | q15com2 | q15com3 | q16_region | q17_city         | q17_zip | q17_country | home | q18_age | q19_sex | q20_income | q21_hiflyer | q22a_usesjc | q22b_useoak | lang | weight              | 
| ======= | ===== | ==== | ======= | ==== | ====== | ==== | ====== | ======= | ====== | ==== | ======= | ======== | ======= | ======== | ======= | ======= | ======= | ======= | ======= | ======= | ======== | ======== | ======== | ======== | ======== | ======== | ====== | ====== | ===== | ====== | ====== | ========== | ======== | === | ======= | ======== | ========= | ========= | ======== | =========== | =========== | =========== | ======== | ======== | ======== | ============ | ========== | ========== | ========= | ====== | ====== | ====== | ============ | =============== | =========== | =========== | =========== | ============ | ====== | ====== | ====== | ======= | ======= | ======= | ======= | =========== | ============== | ============== | ============== | ============ | ======= | ======= | ======= | =============== | ============= | ========= | ============= | ============ | ======= | ======= | ======= | ========== | ================ | ======= | =========== | ==== | ======= | ======= | ========== | =========== | =========== | =========== | ==== | =================== | 
| 1       | 1     | 1215 | 2       | 12   | 1      | 1    | 1      | 21      | 1437   | 49   | 1       | 1        | 8:34 AM | 9:25 AM  | 1       | 8       |         |         |         |         | 2        | 10       |          |          |          |          |        | 2      | 1     | 2      | 2      | 6          | 2        | 1   | 3       | 4        | 3         | 3         | 3        | 3           | 3           | 3           | 3        | 3        | 3        | 3            | 3          | 3          | 3         |        |        |        | 3            | 3               | 3           | 3           | 4           | 4            |        |        |        | 5       | 1       |         |         | 2           | 2              | 2              | 2              | 2            |         |         |         | 5               | 3             | 3         | 3             | 2            |         |         |         | 1          | SAN FRANCISCO    | 94131   | US          | 1    | 2       | 1       | 1          | 2           | 2           | 1           | 1    | 0.55367500000000003 | 
| 2       | 2     | 1215 | 2       | 12   | 1      | 1    | 1      | 21      | 1437   | 49   | 1       | 1        | 8:00 AM | 9:25 AM  | 1       | 8       |         |         |         |         | 2        | 10       |          |          |          |          |        | 2      | 2     | 2      | 2      | 6          | 4        | 1   | 4       | 4        | 4         | 4         | 4        | 3           | 3           | 3           | 6        | 4        | 6        | 6            | 6          | 6          | 4         |        |        |        | 4            | 6               | 6           | 4           | 4           | 4            |        |        |        | 5       | 1       |         |         | 2           | 2              | 2              | 2              | 3            |         |         |         | 2               | 3             | 5         | 5             | 2            |         |         |         | 1          | CONCORD          | 94521   | US          | 5    | 6       | 1       | 0          | 3           | 2           | 1           | 1    | 0.55367500000000003 | 
| 3       | 3     | 1215 | 2       | 12   | 1      | 1    | 1      | 21      | 1437   | 49   | 1       | 1        | 7:00 AM | 9:25 AM  | 1       | 8       |         |         |         |         | 2        | 10       |          |          |          |          |        | 2      | 2     | 2      | 2      | 4          | 4        | 1   | 3       | 4        | 4         | 2         | 4        | 4           | 2           | 2           | 3        | 2        | 3        | 4            | 6          | 4          | 0         |        |        |        | 3            | 3               | 3           | 3           | 3           | 3            |        |        |        | 3       | 1       |         |         | 2           | 2              | 2              | 2              | 2            |         |         |         | 5               | 3             | 3         | 3             | 2            |         |         |         | 1          | SAN FRANCISCO    | 94134   | US          | 1    | 4       | 2       | 2          | 3           | 2           | 2           | 1    | 0.55367500000000003 | 
| 4       | 4     | 1215 | 2       | 12   | 1      | 1    | 1      | 21      | 1437   | 49   | 1       | 1        | 7:30 AM | 9:25 AM  | 1       | 8       |         |         |         |         | 1        | 10       |          |          |          |          | 1      | 1      | 2     | 1      | 2      | 3          | 4        | 2   | 3       | 3        | 3         | 4         | 4        | 4           | 4           | 4           | 4        | 5        | 4        | 4            | 4          | 3          | 4         |        |        |        | 5            | 5               | 5           | 5           | 5           | 5            |        |        |        | 5       |         |         |         | 2           | 2              | 2              | 2              | 2            |         |         |         | 5               | 3             | 5         | 5             | 2            |         |         |         | 1          |                  |         | US          | 90   | 4       | 1       | 2          | 2           | 2           | 2           | 1    | 0.55367500000000003 | 
| 5       | 5     | 1215 | 2       | 12   | 1      | 1    | 1      | 21      | 1437   | 49   | 1       | 1        | 6:30 AM | 9:25 AM  | 1       | 8       |         |         |         |         | 8        | 10       |          |          |          |          |        | 2      | 1     | 1      | 1      | 2          | 3        | 2   | 3       | 3        | 2         | 3         | 5        | 5           | 6           | 6           | 5        | 5        | 6        | 5            | 6          | 4          | 4         | 162    |        |        | 5            | 5               | 5           | 5           | 5           | 5            | 87     |        |        | 5       | 5       |         |         | 2           | 2              | 2              | 2              | 1            | 1       | 5       |         | 3               | 5             | 4         | 3             | 2            |         |         |         | 3          | HUNTINGTON BEACH | 92646   | US          | 10   | 3       | 1       | 3          | 1           | 0           | 1           | 1    | 0.55367500000000003 | 
| 6       | 6     | 1215 | 2       | 12   | 1      | 1    | 1      | 21      | 1437   | 49   | 1       | 1        | 8:00 AM | 9:25 AM  | 2       | 8       |         |         |         |         | 2        | 10       |          |          |          |          |        | 1      | 2     | 2      | 2      | 3          | 4        | 2   | 4       | 3        | 2         | 3         | 3        | 3           | 6           | 6           | 1        | 2        | 3        | 4            | 3          | 6          | 4         | 200    |        |        | 3            | 3               | 6           | 3           | 3           | 3            |        |        |        | 5       | 5       |         |         | 2           | 2              | 2              | 2              | 2            | 1       |         |         | 5               | 3             | 5         | 4             | 2            |         |         |         | 1          | SAN FRANCISCO    | 94118   | US          | 1    | 5       | 1       | 4          | 2           | 1           | 1           | 1    | 0.55367500000000003 | 
| 7       | 32    | 1204 | 2       | 43   | 1      | 1    | 1      | 18      | 144    | 25   | 1       | 4        | 8:25 AM | 10:35 AM | 6       | 8       |         |         |         |         | 1        | 10       |          |          |          |          | 4      | 1      | 2     | 1      | 2      | 1          | 3        | 1   | 3       | 3        | 6         | 5         | 5        | 5           | 6           | 6           | 6        | 5        | 5        | 6            | 6          | 6          | 4         |        |        |        | 5            | 6               | 6           | 5           | 5           | 5            |        |        |        | 4       | 16      |         |         | 2           | 2              | 2              | 2              | 2            |         |         |         | 2               | 3             | 5         | 5             | 2            |         |         |         | 1          | RODEO            | 94572   | US          | 5    | 9       | 1       | 1          | 2           | 2           | 1           | 1    | 1.2667079999999999  | 
| 8       | 33    | 1204 | 2       | 43   | 1      | 1    | 1      | 18      | 144    | 25   | 1       | 4        | 9:25 AM | 10:35 AM | 2       | 8       |         |         |         |         | 2        | 10       |          |          |          |          |        | 1      | 2     | 2      | 2      | 3          | 4        | 1   | 5       | 4        | 5         | 4         | 5        | 5           | 4           | 4           | 5        | 5        | 5        | 5            | 5          | 6          | 5         | 71     | 240    |        | 5            | 5               | 6           | 5           | 5           | 5            | 91     |        |        | 5       | 1       |         |         | 2           | 2              | 2              | 2              | 1            |         |         |         | 6               | 5             | 5         | 5             | 2            |         |         |         | 1          | SAN BRUNO        | 94066   | US          | 2    | 5       | 2       | 5          | 3           | 2           | 2           | 1    | 1.2667079999999999  | 
| 9       | 34    | 1204 | 2       | 43   | 1      | 1    | 1      | 18      | 144    | 25   | 1       | 4        | 8:30 AM | 10:35 AM | 6       | 8       |         |         |         |         | 1        | 10       |          |          |          |          | 4      | 1      | 2     | 1      | 1      | 1          | 4        | 1   | 5       | 5        | 4         | 5         | 5        | 5           | 6           | 6           | 5        | 5        | 4        | 6            | 6          | 6          | 4         |        |        |        | 5            | 6               | 6           | 5           | 5           | 5            |        |        |        | 4       | 8       |         |         | 1           | 2              | 2              | 2              | 1            |         |         |         | 1               | 4             | 5         | 5             | 2            |         |         |         | 1          | NEWARK           | 94560   | US          | 3    | 5       | 1       | 5          | 2           | 2           | 1           | 1    | 1.2667079999999999  | 
| 10      | 35    | 1204 | 2       | 43   | 1      | 1    | 1      | 18      | 144    | 25   | 1       | 4        | 9:30 AM | 10:35 AM | 1       | 8       |         |         |         |         | 2        | 10       |          |          |          |          |        | 1      | 0     | 0      | 0      | 2          | 4        | 2   | 3       | 3        | 3         | 3         | 3        | 5           | 5           | 5           | 5        | 3        | 3        | 3            | 3          | 3          | 4         |        |        |        | 4            | 4               | 4           | 4           | 4           | 4            |        |        |        | 3       | 16      |         |         | 2           | 2              | 2              | 1              | 1            |         |         |         | 8               | 4             | 5         | 5             | 2            |         |         |         | 1          | VALLEJO          | 94589   | US          | 8    | 3       | 2       | 2          | 3           | 0           | 1           | 1    | 1.2667079999999999  | 
```