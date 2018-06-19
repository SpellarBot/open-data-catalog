# COS DO- IT Phone And Online Survey Data 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cos-do-it-phone-and-online-survey-data-2013-9d52c) |
| Metadata | [Link](https://data.seattle.gov/api/views/s98k-8imb) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/s98k-8imb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/s98k-8imb/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | s98k-8imb |
| Name | COS DO- IT Phone And Online Survey Data 2013 |
| Attribution | Department of Information Technology |
| Category | Community |
| Created | 2014-04-25T20:34:52Z |
| Publication Date | 2014-04-25T21:39:39Z |

## Description

Before using this data set, refer to instructions below! 
Since 2000, the City's Information Technology Indicators project has been collecting extensive and statistically valid data on residential use of cable tv, broadband adoption and uses (including health, work, education, finance and civic engagement), barriers to broadband adoption, and customer service needs. This project is managed by our Community Technology Program with technical advice from our Citizens Telecommunications and Technology Advisory Board (CTTAB).  
INSTRUCTIONS FOR USING DATA SET
Do not pull down the data set and use it without using the code book. When you run the data set, be sure to refer to the Code Book for invalid or missing values for each question item (variables). 
You must recognize that the data here is unweighted; to replicate the figures in the City?s Information Technology Access and Adoption Report and get values that are representative of Seattle population, you should use the weights. There are 2 weighting variables, one that allows you to use the phone and online survey together (labeled "weightfin") and one that is for only the phone survey (labeled "wgtphoneonly", which excludes or zeros out everyone in the online survey).

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| No       |                | id                  | ID                  | text      | number      |
| Yes      | numeric metric | weightfin           | weightfin           | number    | number      |
| Yes      | numeric metric | wgtphoneonly        | wgtphoneonly        | number    | number      |
| Yes      | numeric metric | survey              | survey              | number    | number      |
| Yes      | numeric metric | sample              | sample              | number    | number      |
| Yes      | series tag     | fonetype            | FONETYPE            | text      | number      |
| Yes      | numeric metric | langpref            | LANGPREF            | number    | number      |
| Yes      | numeric metric | gender              | GENDER              | number    | number      |
| No       |                | s1                  | S1                  | number    | number      |
| Yes      | numeric metric | dem4                | DEM4                | number    | number      |
| Yes      | numeric metric | dem7                | DEM7                | number    | number      |
| Yes      | numeric metric | dem5                | DEM5                | number    | number      |
| Yes      | numeric metric | dem10               | DEM10               | number    | number      |
| Yes      | numeric metric | tc3_summary         | TC3.summary         | number    | number      |
| Yes      | numeric metric | tc3_any             | TC3.any             | number    | number      |
| Yes      | numeric metric | inet1_1             | INET1.1             | number    | number      |
| Yes      | numeric metric | inet1_2             | INET1.2             | number    | number      |
| Yes      | numeric metric | anycable            | anycable            | number    | number      |
| Yes      | numeric metric | tc1_1               | TC1.1               | number    | number      |
| Yes      | numeric metric | tc1_2               | TC1.2               | number    | number      |
| Yes      | numeric metric | tc2                 | TC2                 | number    | number      |
| Yes      | numeric metric | tc3_1               | TC3.1               | number    | number      |
| Yes      | numeric metric | tc3_2               | TC3.2               | number    | number      |
| Yes      | numeric metric | tc3_4               | TC3.4               | number    | number      |
| Yes      | numeric metric | laptopnetbook       | laptopnetbook       | number    | number      |
| Yes      | numeric metric | tc3_0               | TC3.0               | number    | number      |
| Yes      | numeric metric | tc3_8               | TC3.8               | number    | number      |
| Yes      | series tag     | tc3_other           | TC3.other           | text      | text        |
| Yes      | numeric metric | tc4_1               | TC4.1               | number    | number      |
| Yes      | numeric metric | tc4_2               | TC4.2               | number    | number      |
| Yes      | numeric metric | tc4_3               | TC4.3               | number    | number      |
| Yes      | numeric metric | tc4_any             | TC4.any             | number    | number      |
| Yes      | numeric metric | tc4_0               | TC4.0               | number    | number      |
| Yes      | numeric metric | tc4_8               | TC4.8               | number    | number      |
| Yes      | numeric metric | tc5_1               | TC5.1               | number    | number      |
| Yes      | numeric metric | tc5_2               | TC5.2               | number    | number      |
| Yes      | numeric metric | tc6                 | TC6                 | number    | number      |
| Yes      | numeric metric | anymobile           | anymobile           | number    | number      |
| Yes      | numeric metric | numinternetdev      | NumInternetDev      | number    | number      |
| Yes      | numeric metric | multinternetdev     | MultInternetDev     | number    | number      |
| Yes      | numeric metric | anyinternetdev      | AnyInternetDev      | number    | number      |
| Yes      | numeric metric | smartnetonly        | smartnetonly        | number    | number      |
| Yes      | numeric metric | numplace            | NUMPLACE            | number    | number      |
| Yes      | numeric metric | inet2_88            | INET2.88            | number    | number      |
| Yes      | numeric metric | inet2_1             | INET2.1             | number    | number      |
| Yes      | numeric metric | inet2_2             | INET2.2             | number    | number      |
| Yes      | numeric metric | inet2_3             | INET2.3             | number    | number      |
| Yes      | numeric metric | inet2_4             | INET2.4             | number    | number      |
| Yes      | numeric metric | inet2_5             | INET2.5             | number    | number      |
| Yes      | numeric metric | inet2_6             | INET2.6             | number    | number      |
| Yes      | numeric metric | inet2_7             | INET2.7             | number    | number      |
| Yes      | numeric metric | inet2_8             | INET2.8             | number    | number      |
| Yes      | numeric metric | inet2_travel        | INET2.travel        | number    | number      |
| Yes      | numeric metric | inet2_store         | INET2.store         | number    | number      |
| Yes      | numeric metric | inet2_9             | INET2.9             | number    | number      |
| Yes      | numeric metric | inet2_med           | INET2.med           | number    | number      |
| Yes      | numeric metric | inet2_anywifi       | INET2.anywifi       | number    | number      |
| Yes      | series tag     | inet2_other         | INET2.other         | text      | text        |
| Yes      | numeric metric | highspeed           | highspeed           | number    | number      |
| Yes      | numeric metric | homenet             | homenet             | number    | number      |
| Yes      | numeric metric | dslcablewifi        | dslcablewifi        | number    | number      |
| Yes      | numeric metric | dslcableallwificell | dslcableallwificell | number    | number      |
| Yes      | numeric metric | r_inet3             | r.INET3             | number    | number      |
| Yes      | numeric metric | inet3               | INET3               | number    | number      |
| Yes      | numeric metric | inet3_2             | INET3.2             | number    | number      |
| Yes      | numeric metric | inet3_3             | INET3.3             | number    | number      |
| Yes      | numeric metric | inet3_4             | INET3.4             | number    | number      |
| Yes      | numeric metric | inet3_5             | INET3.5             | number    | number      |
| Yes      | numeric metric | inet3_6             | INET3.6             | number    | number      |
| Yes      | numeric metric | inet3_14            | INET3.14            | number    | number      |
| Yes      | numeric metric | inet3_1             | INET3.1             | number    | number      |
| Yes      | numeric metric | inet3_7             | INET3.7             | number    | number      |
| Yes      | numeric metric | inet3_0             | INET3.0             | number    | number      |
| Yes      | numeric metric | inet3_8             | INET3.8             | number    | number      |
| Yes      | series tag     | inet3_other         | INET3.other         | text      | text        |
| Yes      | numeric metric | inet3_oth           | INET3.oth#          | number    | number      |
| Yes      | numeric metric | rinet4              | rINET4              | number    | number      |
| Yes      | numeric metric | inet4               | INET4               | number    | number      |
| Yes      | numeric metric | inet4_oth           | INET4.oth#          | number    | number      |
| Yes      | series tag     | inet4oth            | INET4OTH            | text      | text        |
| Yes      | numeric metric | inet5               | INET5               | number    | number      |
| Yes      | numeric metric | inet6               | INET6               | number    | number      |
| Yes      | series tag     | inet6whence         | inet6whence         | text      | text        |
| Yes      | numeric metric | p_inet7             | P.INET7             | number    | number      |
| Yes      | numeric metric | inet7_1             | INET7.1             | number    | number      |
| Yes      | numeric metric | inet7_2             | INET7.2             | number    | number      |
| Yes      | numeric metric | inet7_3             | INET7.3             | number    | number      |
| Yes      | numeric metric | inet7_4             | INET7.4             | number    | number      |
| Yes      | numeric metric | inet7_5             | INET7.5             | number    | number      |
| Yes      | numeric metric | inet7_6             | INET7.6             | number    | number      |
| Yes      | numeric metric | inet7_7             | INET7.7             | number    | number      |
| Yes      | numeric metric | inet7_8             | INET7.8             | number    | number      |
| Yes      | numeric metric | inet7_9             | INET7.9             | number    | number      |
| Yes      | numeric metric | inet7_88            | INET7.88            | number    | number      |
| Yes      | numeric metric | inet7_freewifi      | INET7.freewifi      | number    | number      |
| Yes      | series tag     | inet7oth            | INET7OTH            | text      | text        |
| Yes      | numeric metric | inet7_oth           | INET7.oth#          | number    | number      |
| Yes      | numeric metric | inet8_any           | INET8.any           | number    | number      |
| Yes      | numeric metric | inet8               | INET8               | number    | number      |
| Yes      | numeric metric | r_use1              | r.use1              | number    | number      |
| Yes      | numeric metric | r_use2              | r.use2              | number    | number      |
| Yes      | numeric metric | r_use3              | r.use3              | number    | number      |
| Yes      | numeric metric | r_use4              | r.use4              | number    | number      |
| Yes      | numeric metric | r_use5              | r.use5              | number    | number      |
| Yes      | numeric metric | r_use6              | r.use6              | number    | number      |
| Yes      | numeric metric | r_use7              | r.use7              | number    | number      |
| Yes      | numeric metric | r_use8              | r.use8              | number    | number      |
| Yes      | numeric metric | r_use9              | r.use9              | number    | number      |
| Yes      | numeric metric | r_use10             | r.use10             | number    | number      |
| Yes      | numeric metric | r_use11             | r.use11             | number    | number      |
| Yes      | numeric metric | r_use12             | r.use12             | number    | number      |
| Yes      | numeric metric | r_use13             | r.use13             | number    | number      |
| Yes      | numeric metric | r_use14             | r.use14             | number    | number      |
| Yes      | numeric metric | r_use15             | r.use15             | number    | number      |
| Yes      | numeric metric | r_lit1              | r.lit1              | number    | number      |
| Yes      | numeric metric | r_lit2              | r.lit2              | number    | number      |
| Yes      | numeric metric | r_lit3              | r.lit3              | number    | number      |
| Yes      | numeric metric | numcompuse          | numcompuse          | number    | number      |
| Yes      | numeric metric | use1                | USE1                | number    | number      |
| Yes      | numeric metric | use2                | USE2                | number    | number      |
| Yes      | numeric metric | use3                | USE3                | number    | number      |
| Yes      | numeric metric | use4                | USE4                | number    | number      |
| Yes      | numeric metric | use5                | USE5                | number    | number      |
| Yes      | numeric metric | use6                | USE6                | number    | number      |
| Yes      | numeric metric | use7                | USE7                | number    | number      |
| Yes      | numeric metric | use8                | USE8                | number    | number      |
| Yes      | numeric metric | use9                | USE9                | number    | number      |
| Yes      | numeric metric | use10               | USE10               | number    | number      |
| Yes      | numeric metric | use11               | USE11               | number    | number      |
| Yes      | numeric metric | o_usesellgoods      | O.usesellgoods      | number    | number      |
| Yes      | numeric metric | o_usepostvid        | O.usepostvid        | number    | number      |
| Yes      | numeric metric | o_usepodcast        | O.usepodcast        | number    | number      |
| Yes      | numeric metric | o_usenone           | O.usenone           | number    | number      |
| Yes      | series tag     | o_otheruse          | O.otheruse          | text      | text        |
| Yes      | numeric metric | use12               | use12               | number    | number      |
| Yes      | numeric metric | use13               | use13               | number    | number      |
| Yes      | numeric metric | use14               | use14               | number    | number      |
| Yes      | series tag     | othersocnw          | othersocnw          | text      | text        |
| Yes      | numeric metric | use15               | use15               | number    | number      |
| Yes      | numeric metric | lit1                | LIT1                | number    | number      |
| Yes      | numeric metric | lit2                | LIT2                | number    | number      |
| Yes      | numeric metric | lit3                | LIT3                | number    | number      |
| Yes      | numeric metric | numhsapps           | numhsapps           | number    | number      |
| Yes      | numeric metric | hs1                 | HS1                 | number    | number      |
| Yes      | numeric metric | hs2_1               | HS2.1               | number    | number      |
| Yes      | numeric metric | hs2_2               | HS2.2               | number    | number      |
| Yes      | numeric metric | hs2_3               | HS2.3               | number    | number      |
| Yes      | numeric metric | hs2_4               | HS2.4               | number    | number      |
| Yes      | numeric metric | hs2_5               | HS2.5               | number    | number      |
| Yes      | numeric metric | hs2_6               | HS2.6               | number    | number      |
| Yes      | numeric metric | hs2_7               | HS2.7               | number    | number      |
| Yes      | numeric metric | hs2_9               | HS2.9               | number    | number      |
| Yes      | numeric metric | hs2_88              | HS2.88              | number    | number      |
| Yes      | series tag     | hs2_other           | HS2.other           | text      | text        |
| Yes      | numeric metric | hs2_oth             | HS2.oth#            | number    | number      |
| Yes      | numeric metric | hs2_oth1            | HS2.oth1            | number    | number      |
| Yes      | numeric metric | hs2_oth2            | HS2.oth2            | number    | number      |
| Yes      | numeric metric | hs2_oth3            | HS2.oth3            | number    | number      |
| Yes      | numeric metric | hs3_1               | HS3.1               | number    | number      |
| Yes      | numeric metric | hs3_2               | HS3.2               | number    | number      |
| Yes      | numeric metric | hs3_3               | HS3.3               | number    | number      |
| Yes      | numeric metric | hs3_5               | HS3.5               | number    | number      |
| Yes      | numeric metric | hs3_4               | HS3.4               | number    | number      |
| Yes      | numeric metric | hs3_6               | HS3.6               | number    | number      |
| Yes      | numeric metric | hs3_0               | HS3.0               | number    | number      |
| Yes      | series tag     | hs3_other           | HS3.other           | text      | text        |
| Yes      | numeric metric | hsgoodenuf          | hsgoodenuf          | number    | number      |
| Yes      | numeric metric | hsfastenuf          | hsfastenuf          | number    | number      |
| Yes      | numeric metric | hs3_oth             | HS3.oth#            | number    | number      |
| Yes      | numeric metric | hs3_oth1            | HS3.oth1            | number    | number      |
| Yes      | numeric metric | hs3_oth2            | HS3.oth2            | number    | number      |
| Yes      | numeric metric | hs3_oth3            | HS3.oth3            | number    | number      |
| Yes      | numeric metric | hs3_oth4            | HS3.oth4            | number    | number      |
| Yes      | numeric metric | hs3_oth5            | HS3.oth5            | number    | number      |
| Yes      | numeric metric | cable1              | CABLE1              | number    | number      |
| Yes      | numeric metric | cable2              | CABLE2              | number    | number      |
| Yes      | numeric metric | cable3_1            | CABLE3.1            | number    | number      |
| Yes      | numeric metric | cable3_2            | CABLE3.2            | number    | number      |
| Yes      | numeric metric | cable3_3            | CABLE3.3            | number    | number      |
| Yes      | numeric metric | cable3_4            | CABLE3.4            | number    | number      |
| Yes      | numeric metric | cable3_14           | CABLE3.14           | number    | number      |
| Yes      | series tag     | cable3oth           | CABLE3OTH           | text      | text        |
| Yes      | numeric metric | cable3_oth          | CABLE3.OTH#         | number    | number      |
| Yes      | numeric metric | cable3_oth1         | CABLE3.OTH1         | number    | number      |
| Yes      | numeric metric | cable3_oth2         | CABLE3.OTH2         | number    | number      |
| Yes      | numeric metric | cable3_oth3         | CABLE3.OTH3         | number    | number      |
| Yes      | numeric metric | cable3_oth4         | CABLE3.OTH4         | number    | number      |
| Yes      | numeric metric | cable3_oth5         | CABLE3.OTH5         | number    | number      |
| Yes      | numeric metric | cable3_0            | CABLE3.0            | number    | number      |
| Yes      | numeric metric | cable4              | CABLE4              | number    | number      |
| Yes      | series tag     | cable5              | CABLE5              | text      | text        |
| Yes      | numeric metric | cab_quote           | CAB.quote           | number    | number      |
| Yes      | numeric metric | cab_local           | CAB.local           | number    | number      |
| Yes      | numeric metric | cab_educ            | CAB.educ            | number    | number      |
| Yes      | numeric metric | cab_arts            | CAB.arts            | number    | number      |
| Yes      | numeric metric | cab_env             | CAB.env             | number    | number      |
| Yes      | numeric metric | cab_diverse         | CAB.diverse         | number    | number      |
| Yes      | numeric metric | cab_fam             | CAB.fam             | number    | number      |
| Yes      | numeric metric | cab_news            | CAB.news            | number    | number      |
| Yes      | numeric metric | cab_cn              | CAB.cn              | number    | number      |
| Yes      | numeric metric | cab_none            | CAB.none            | number    | number      |
| Yes      | numeric metric | cab_dk              | CAB.dk              | number    | number      |
| Yes      | numeric metric | cab_na              | CAB.na              | number    | number      |
| Yes      | numeric metric | cab_other           | CAB.other#          | number    | number      |
| Yes      | numeric metric | cab_movies          | CAB.movies          | number    | number      |
| Yes      | numeric metric | cab_noads           | CAB.noads           | number    | number      |
| Yes      | numeric metric | cab_sci             | CAB.sci             | number    | number      |
| Yes      | numeric metric | cab_travel          | CAB.travel          | number    | number      |
| Yes      | numeric metric | cab_lifestyle       | CAB.lifestyle       | number    | number      |
| Yes      | numeric metric | cab_doc             | CAB.doc             | number    | number      |
| Yes      | numeric metric | cab_sports          | CAB.sports          | number    | number      |
| Yes      | numeric metric | cab_hx              | CAB.hx              | number    | number      |
| Yes      | numeric metric | cab_specific        | CAB.specific        | number    | number      |
| Yes      | numeric metric | cab_relig           | CAB.relig           | number    | number      |
| Yes      | numeric metric | cab_pbs             | CAB.pbs             | number    | number      |
| Yes      | numeric metric | cab_comedy          | CAB.comedy          | number    | number      |
| Yes      | numeric metric | cab_drama           | CAB.drama           | number    | number      |
| Yes      | numeric metric | cable6              | CABLE6              | number    | number      |
| Yes      | numeric metric | cable7              | CABLE7              | number    | number      |
| Yes      | numeric metric | cable8              | CABLE8              | number    | number      |
| Yes      | series tag     | cable8oth           | CABLE8OTH           | text      | text        |
| Yes      | numeric metric | cable8_oth          | CABLE8.oth#         | number    | number      |
| Yes      | numeric metric | cable9              | CABLE9              | number    | number      |
| Yes      | numeric metric | cnot1               | CNOT1               | number    | number      |
| Yes      | series tag     | cnot2_other1        | CNOT2.other1        | text      | text        |
| Yes      | series tag     | cnot2_other2        | CNOT2.other2        | text      | text        |
| Yes      | numeric metric | cnot2_1             | CNOT2.1             | number    | number      |
| Yes      | numeric metric | cnot2_2             | CNOT2.2             | number    | number      |
| Yes      | numeric metric | cnot2_3             | CNOT2.3             | number    | number      |
| Yes      | numeric metric | cnot2_4             | CNOT2.4             | number    | number      |
| Yes      | numeric metric | cnot2_5             | CNOT2.5             | number    | number      |
| Yes      | numeric metric | cnot2_6             | CNOT2.6             | number    | number      |
| Yes      | numeric metric | cnot2_7             | CNOT2.7             | number    | number      |
| Yes      | numeric metric | cnot2_8             | CNOT2.8             | number    | number      |
| Yes      | numeric metric | cnot2_9             | CNOT2.9             | number    | number      |
| Yes      | numeric metric | cnot2_10            | CNOT2.10            | number    | number      |
| Yes      | numeric metric | cnot2_11            | CNOT2.11            | number    | number      |
| Yes      | numeric metric | cnot2_88            | CNOT2.88            | number    | number      |
| Yes      | numeric metric | cnot2_12            | CNOT2.12            | number    | number      |
| Yes      | numeric metric | cnot2_oth1          | CNOT2.oth1          | number    | number      |
| Yes      | numeric metric | cnot2_oth2          | CNOT2.oth2          | number    | number      |
| Yes      | numeric metric | cnot2_oth3          | CNOT2.oth3          | number    | number      |
| Yes      | numeric metric | cnot2_oth4          | CNOT2.oth4          | number    | number      |
| Yes      | numeric metric | cnot2_oth5          | CNOT2.oth5          | number    | number      |
| Yes      | numeric metric | cnot2_oth6          | CNOT2.oth6          | number    | number      |
| Yes      | numeric metric | cnot2_oth7          | CNOT2.oth7          | number    | number      |
| Yes      | numeric metric | cnot2_oth8          | CNOT2.oth8          | number    | number      |
| Yes      | numeric metric | cnot2_any           | CNOT2.any           | number    | number      |
| Yes      | numeric metric | cb1                 | CB1                 | number    | number      |
| Yes      | numeric metric | o_cb1print          | O.cb1print          | number    | number      |
| Yes      | numeric metric | o_cb1meeting        | O.cb1meeting        | number    | number      |
| Yes      | series tag     | o_cb1phone          | O.cb1phone          | text      | number      |
| Yes      | numeric metric | o_cb1email          | O.cb1email          | number    | number      |
| Yes      | numeric metric | o_cb1fb             | O.cb1fb             | number    | number      |
| Yes      | numeric metric | o_cb1twitter        | O.cb1twitter        | number    | number      |
| Yes      | numeric metric | o_cb1website        | O.cb1website        | number    | number      |
| Yes      | numeric metric | o_cb1text           | O.cb1text           | number    | number      |
| Yes      | numeric metric | o_cb1rss            | O.cb1rss            | number    | number      |
| Yes      | numeric metric | o_cb1calendar       | O.cb1calendar       | number    | number      |
| Yes      | numeric metric | o_cb1blog           | O.cb1blog           | number    | number      |
| Yes      | numeric metric | o_cb1dk             | O.cb1dk             | number    | number      |
| Yes      | numeric metric | o_anycb1oth         | O.anycb1oth         | number    | number      |
| Yes      | series tag     | o_cb1oth            | O.cb1oth            | text      | text        |
| Yes      | numeric metric | civic1_1            | CIVIC1.1            | number    | number      |
| Yes      | numeric metric | civic1_2            | CIVIC1.2            | number    | number      |
| Yes      | numeric metric | civic1_3            | CIVIC1.3            | number    | number      |
| Yes      | numeric metric | civic1_4            | CIVIC1.4            | number    | number      |
| Yes      | numeric metric | civic1_5            | CIVIC1.5            | number    | number      |
| Yes      | numeric metric | civic1_6            | CIVIC1.6            | number    | number      |
| Yes      | numeric metric | civic1_7            | CIVIC1.7            | number    | number      |
| Yes      | numeric metric | civic1_8            | CIVIC1.8            | number    | number      |
| Yes      | numeric metric | civic1_9            | CIVIC1.9            | number    | number      |
| Yes      | numeric metric | civic1_10           | CIVIC1.10           | number    | number      |
| Yes      | numeric metric | civic1_11           | CIVIC1.11           | number    | number      |
| Yes      | numeric metric | civic1_12           | CIVIC1.12           | number    | number      |
| Yes      | numeric metric | civic1_anyelec      | CIVIC1.anyelec      | number    | number      |
| Yes      | series tag     | civic1_other        | CIVIC1.other        | text      | text        |
| Yes      | numeric metric | civic1_oth          | CIVIC1.oth#         | number    | number      |
| Yes      | numeric metric | civic1_oth1         | CIVIC1.oth1         | number    | number      |
| Yes      | numeric metric | civic1_oth2         | CIVIC1.oth2         | number    | number      |
| Yes      | numeric metric | civic1_oth3         | CIVIC1.oth3         | number    | number      |
| Yes      | numeric metric | civic1_oth4         | CIVIC1.oth4         | number    | number      |
| Yes      | numeric metric | civic1_na           | CIVIC1.na           | number    | number      |
| Yes      | numeric metric | civic2              | CIVIC2              | number    | number      |
| Yes      | numeric metric | civic2_1            | CIVIC2.1            | number    | number      |
| Yes      | numeric metric | civic2_2            | CIVIC2.2            | number    | number      |
| Yes      | numeric metric | civic2_3            | CIVIC2.3            | number    | number      |
| Yes      | numeric metric | civic2_4            | CIVIC2.4            | number    | number      |
| Yes      | numeric metric | civic2_5            | CIVIC2.5            | number    | number      |
| Yes      | numeric metric | civic2_6            | CIVIC2.6            | number    | number      |
| Yes      | numeric metric | civic2_7            | CIVIC2.7            | number    | number      |
| Yes      | numeric metric | civic2_88           | CIVIC2.88           | number    | number      |
| Yes      | series tag     | civic2_other        | CIVIC2.other        | text      | text        |
| Yes      | numeric metric | civic2_oth          | CIVIC2.oth#         | number    | number      |
| Yes      | numeric metric | numciv3             | numciv3             | number    | number      |
| Yes      | numeric metric | civic3_1            | CIVIC3.1            | number    | number      |
| Yes      | numeric metric | civic3_2            | CIVIC3.2            | number    | number      |
| Yes      | numeric metric | civic3_3            | CIVIC3.3            | number    | number      |
| Yes      | numeric metric | civic3_4            | CIVIC3.4            | number    | number      |
| Yes      | numeric metric | civic3_5            | CIVIC3.5            | number    | number      |
| Yes      | numeric metric | civic3_6            | CIVIC3.6            | number    | number      |
| Yes      | numeric metric | civic3_7            | CIVIC3.7            | number    | number      |
| Yes      | numeric metric | civic3_8            | CIVIC3.8            | number    | number      |
| Yes      | numeric metric | civic3_9            | CIVIC3.9            | number    | number      |
| Yes      | numeric metric | civic3_0            | CIVIC3.0            | number    | number      |
| Yes      | series tag     | civic3_other        | CIVIC3.other        | text      | text        |
| Yes      | numeric metric | civic3_oth          | CIVIC3.oth#         | number    | number      |
| Yes      | numeric metric | civic3_oth1         | CIVIC3.oth1         | number    | number      |
| Yes      | numeric metric | civic3_oth2         | CIVIC3.oth2         | number    | number      |
| Yes      | numeric metric | civic3_oth3         | CIVIC3.oth3         | number    | number      |
| Yes      | numeric metric | civic3_oth4         | CIVIC3.oth4         | number    | number      |
| Yes      | numeric metric | civic3_oth5         | CIVIC3.oth5         | number    | number      |
| Yes      | numeric metric | civic3_oth6         | CIVIC3.oth6         | number    | number      |
| Yes      | numeric metric | civic3_oth7         | CIVIC3.oth7         | number    | number      |
| Yes      | numeric metric | civic3_oth8         | CIVIC3.oth8         | number    | number      |
| Yes      | numeric metric | civic3_oth9         | CIVIC3.oth9         | number    | number      |
| Yes      | numeric metric | civic3_oth10        | CIVIC3.oth10        | number    | number      |
| Yes      | numeric metric | numciv4             | numciv4             | number    | number      |
| Yes      | numeric metric | civic4_1            | CIVIC4.1            | number    | number      |
| Yes      | numeric metric | civic4_2            | CIVIC4.2            | number    | number      |
| Yes      | numeric metric | civic4_3            | CIVIC4.3            | number    | number      |
| Yes      | numeric metric | civic4_4            | CIVIC4.4            | number    | number      |
| Yes      | numeric metric | civic4_5            | CIVIC4.5            | number    | number      |
| Yes      | numeric metric | civic4_6            | CIVIC4.6            | number    | number      |
| Yes      | numeric metric | civic4_7            | CIVIC4.7            | number    | number      |
| Yes      | numeric metric | civic4_0            | CIVIC4.0            | number    | number      |
| Yes      | numeric metric | civic4_1_2_4        | CIVIC4.1_2_4        | number    | number      |
| Yes      | numeric metric | civic4_1_4          | CIVIC4.1_4          | number    | number      |
| Yes      | numeric metric | civic4_2_4          | CIVIC4.2_4          | number    | number      |
| Yes      | numeric metric | civic4_1_2          | CIVIC4.1_2          | number    | number      |
| Yes      | numeric metric | civic4_person       | CIVIC4.person       | number    | number      |
| Yes      | series tag     | civic4_oth_1        | CIVIC4.oth          | text      | text        |
| Yes      | numeric metric | civic4_oth_2        | CIVIC4.oth#         | number    | number      |
| Yes      | numeric metric | civic4_oth1         | CIVIC4.oth1         | number    | number      |
| Yes      | numeric metric | civic4_oth2         | CIVIC4.oth2         | number    | number      |
| Yes      | numeric metric | civic4_oth3         | CIVIC4.oth3         | number    | number      |
| Yes      | numeric metric | civic4_oth4         | CIVIC4.oth4         | number    | number      |
| Yes      | numeric metric | civic4_oth5         | CIVIC4.oth5         | number    | number      |
| Yes      | numeric metric | civic4_oth6         | CIVIC4.oth6         | number    | number      |
| Yes      | numeric metric | web1_any            | WEB1.any            | number    | number      |
| Yes      | numeric metric | web1_freq           | WEB1.freq           | number    | number      |
| Yes      | numeric metric | web2                | WEB2                | number    | number      |
| Yes      | series tag     | web2_other          | WEB2.other          | text      | text        |
| Yes      | numeric metric | web2_oth            | WEB2.oth#           | number    | number      |
| Yes      | numeric metric | sea1_ever           | SEA1.ever           | number    | number      |
| Yes      | numeric metric | sea1_how            | SEA1.how            | number    | number      |
| Yes      | numeric metric | sea2                | SEA2                | number    | number      |
| Yes      | numeric metric | sea3                | SEA3                | number    | number      |
| Yes      | series tag     | sea4_1              | SEA4                | text      | text        |
| Yes      | numeric metric | sea4_2              | SEA4#               | number    | number      |
| Yes      | series tag     | sea4new             | SEA4new             | text      | text        |
| Yes      | numeric metric | sea4dk              | SEA4DK              | number    | number      |
| Yes      | numeric metric | sea4nothing         | SEA4NOTHING         | number    | number      |
| Yes      | numeric metric | sea4other           | SEA4OTHER           | number    | number      |
| Yes      | numeric metric | sea4oknow           | SEA4OKNOW           | number    | number      |
| Yes      | numeric metric | sea4quote           | SEA4QUOTE           | number    | number      |
| Yes      | numeric metric | sea4pers            | SEA4PERS            | number    | number      |
| Yes      | numeric metric | sea4infra           | SEA4INFRA           | number    | number      |
| Yes      | numeric metric | sea4event           | SEA4EVENT           | number    | number      |
| Yes      | numeric metric | sea4alert           | SEA4ALERT           | number    | number      |
| Yes      | numeric metric | sea4engage          | SEA4ENGAGE          | number    | number      |
| Yes      | numeric metric | sea4current         | SEA4CURRENT         | number    | number      |
| Yes      | numeric metric | sea4trans           | SEA4TRANS           | number    | number      |
| Yes      | numeric metric | sea4culture         | SEA4CULTURE         | number    | number      |
| Yes      | numeric metric | sea4seainfo         | SEA4SEAINFO         | number    | number      |
| Yes      | numeric metric | sea4gov             | SEA4GOV             | number    | number      |
| Yes      | numeric metric | sea4commissue       | SEA4COMMISSUE       | number    | number      |
| Yes      | numeric metric | sea4howto           | SEA4HOWTO           | number    | number      |
| Yes      | numeric metric | sea4pubwrk          | SEA4PUBWRK          | number    | number      |
| Yes      | numeric metric | sea4opp             | SEA4OPP             | number    | number      |
| Yes      | numeric metric | sea4crime           | SEA4CRIME           | number    | number      |
| Yes      | numeric metric | sea4budget          | SEA4BUDGET          | number    | number      |
| Yes      | numeric metric | sea4disaster        | SEA4DISASTER        | number    | number      |
| Yes      | numeric metric | sea4service         | SEA4SERVICE         | number    | number      |
| Yes      | numeric metric | sea4envir           | SEA4ENVIR           | number    | number      |
| Yes      | numeric metric | sea4input           | SEA4INPUT           | number    | number      |
| Yes      | numeric metric | sea4people          | SEA4PEOPLE          | number    | number      |
| Yes      | numeric metric | sea4educ            | SEA4EDUC            | number    | number      |
| Yes      | numeric metric | sea4schools         | SEA4SCHOOLS         | number    | number      |
| Yes      | numeric metric | sea4biz             | SEA4BIZ             | number    | number      |
| Yes      | numeric metric | sea4discuss         | SEA4DISCUSS         | number    | number      |
| Yes      | numeric metric | sea4housing         | SEA4HOUSING         | number    | number      |
| Yes      | series tag     | sea4notcode         | SEA4NOTCODE         | text      | number      |
| Yes      | numeric metric | dem1                | DEM1                | number    | number      |
| Yes      | numeric metric | dem2                | DEM2                | number    | number      |
| Yes      | numeric metric | dem3                | DEM3                | number    | number      |
| Yes      | numeric metric | dem6                | DEM6                | number    | number      |
| Yes      | series tag     | dem6_other          | DEM6.other          | text      | text        |
| Yes      | numeric metric | dem7_1              | DEM7_1              | number    | number      |
| Yes      | numeric metric | dem7_2              | DEM7_2              | number    | number      |
| Yes      | series tag     | dem7oth             | DEM7OTH             | text      | text        |
| Yes      | numeric metric | dem7prim            | DEM7PRIM            | number    | number      |
| Yes      | numeric metric | dem7a               | DEM7A               | number    | number      |
| Yes      | numeric metric | dem7_cat            | DEM7.cat            | number    | number      |
| Yes      | numeric metric | afamer_blk          | AFAMER.BLK          | number    | number      |
| Yes      | numeric metric | asian_pi            | ASIAN.PI            | number    | number      |
| Yes      | numeric metric | cauc_wht            | CAUC.WHT            | number    | number      |
| No       |                | hisp_lat            | HISP.LAT            | number    | number      |
| Yes      | numeric metric | dem8                | DEM8                | number    | number      |
| Yes      | numeric metric | dem8b_1             | DEM8b.1             | number    | number      |
| Yes      | numeric metric | dem8b_2             | DEM8b.2             | number    | number      |
| Yes      | numeric metric | dem8b_3             | DEM8b.3             | number    | number      |
| Yes      | numeric metric | anyemp              | anyemp              | number    | number      |
| Yes      | numeric metric | dem8a_4             | DEM8a.4             | number    | number      |
| Yes      | numeric metric | dem8a_5             | DEM8a.5             | number    | number      |
| Yes      | numeric metric | dem8a_6             | DEM8a.6             | number    | number      |
| Yes      | numeric metric | dem8a_7             | DEM8a.7             | number    | number      |
| Yes      | numeric metric | dem8a_9             | DEM8a.9             | number    | number      |
| Yes      | numeric metric | dem9                | DEM9                | number    | number      |
| Yes      | numeric metric | pwd                 | PWD                 | number    | number      |
| Yes      | numeric metric | language            | LANGUAGE            | number    | number      |
| Yes      | numeric metric | tlength             | TLENGTH             | number    | number      |
| Yes      | numeric metric | weight_ed           | weight.ed           | number    | number      |
| Yes      | numeric metric | wgt1                | wgt1                | number    | number      |
| Yes      | numeric metric | weight_age          | weight.age          | number    | number      |
| Yes      | numeric metric | wgt2                | wgt2                | number    | number      |
| Yes      | numeric metric | weight              | weight.$            | number    | number      |
| Yes      | numeric metric | wgt3                | wgt3                | number    | number      |
| Yes      | numeric metric | weight_eth          | weight.eth          | number    | number      |
| Yes      | numeric metric | wgt4                | wgt4                | number    | number      |
| Yes      | series tag     | weight_zip          | weight.zip          | text      | number      |
| Yes      | numeric metric | wgt5                | wgt5                | number    | number      |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = id,s1,hisp_lat
```

## Data Commands

```ls
series e:s98k-8imb d:2013-01-01T00:00:00.000Z t:sea4notcode=0 t:fonetype=1 t:sea4new="I WOULDN'T KNOW." m:highspeed=3 m:sea4envir=0 m:civic4_oth_2=1 m:inet3=3 m:laptopnetbook=1 m:sea4other=0 m:anymobile=0 m:sea4gov=0 m:rinet4=2 m:numplace=2 m:sea4infra=0 m:cab_hx=-1 m:weightfin=0.62 m:inet6=4 m:civic4_oth3=8 m:dem7_cat=3 m:civic4_oth2=8 m:civic4_oth5=8 m:inet4=2 m:civic4_oth4=8 m:inet5=4 m:cab_specific=-1 m:civic4_oth1=8 m:cab_movies=-1 m:inet2_travel=0 m:sea4alert=0 m:civic4_oth6=8 m:cnot2_oth4=0 m:cnot2_oth5=0 m:sea4educ=0 m:cnot2_oth2=0 m:cnot2_oth3=0 m:sea4quote=0 m:cnot2_oth1=0 m:civic1_na=0 m:sea4crime=0 m:tlength=18 m:cable3_oth1=-1 m:cab_sci=-1 m:cab_drama=-1 m:sea4input=0 m:tc4_any=0 m:cab_none=-1 m:cable3_oth4=-1 m:cnot2_oth8=0 m:cable3_oth=1 m:cable3_oth5=-1 m:cable3_oth2=-9 m:cnot2_oth7=0 m:cable3_oth3=-1 m:cnot2_oth6=0 m:civic1_12=0 m:hs3_oth1=8 m:civic1_11=0 m:hs3_oth2=8 m:hs3_oth3=8 m:cnot2_any=1 m:cnot1=1 m:dslcablewifi=1 m:sea4budget=0 m:hs3_oth4=8 m:hs3_oth5=8 m:civic1_10=0 m:civic3_oth10=0 m:tc3_summary=3 m:sea4pubwrk=0 m:cab_doc=-1 m:r_inet3=3 m:cab_diverse=-1 m:weight_ed=0.84 m:cauc_wht=1 m:cnot2_12=0 m:cnot2_11=0 m:cnot2_10=0 m:langpref=2 m:multinternetdev=2 m:sea4housing=0 m:gender=0 m:civic1_anyelec=1 m:cb1=1 m:sea4discuss=0 m:cable3_0=-1 m:cable3_2=-1 m:cable3_1=-1 m:cable3_4=-1 m:cable3_3=-1 m:cab_news=-1 m:tc4_1=0 m:tc3_4=0 m:numinternetdev=2 m:dem7a=3 m:hsgoodenuf=8 m:r_use1=0 m:r_use3=1 m:r_use2=0 m:r_use5=0 m:r_use4=0 m:r_use7=0 m:tc3_2=1 m:r_use6=0 m:tc3_1=1 m:hs2_oth=1 m:r_use9=0 m:tc4_3=0 m:r_use8=0 m:inet8_any=-2 m:tc4_2=0 m:civic1_oth3=0 m:civic3_7=0 m:civic1_oth4=0 m:civic3_6=0 m:dslcableallwificell=1 m:civic3_9=0 m:weight=0.98 m:civic3_8=0 m:asian_pi=0 m:use11=1 m:use10=1 m:sea4engage=0 m:use15=1 m:use14=1 m:use13=2 m:use12=3 m:inet4_oth=1 m:civic1_oth1=0 m:civic1_oth2=0 m:cab_local=-1 m:cab_noads=-1 m:sea4people=0 m:web2=-1 m:sample=1 m:inet1_2=1 m:inet7_8=-2 m:inet7_9=-2 m:inet7_6=-2 m:sea4oknow=0 m:inet7_7=-2 m:inet7_4=-2 m:inet7_5=-2 m:inet7_2=-2 m:inet7_3=-2 m:cab_arts=-1 m:inet7_1=-2 m:cab_educ=-1 m:cab_fam=-1 m:inet2_6=0 m:inet2_5=0 m:inet3_8=0 m:inet2_8=0 m:inet2_7=0 m:inet2_2=1 m:inet2_1=1 m:inet2_4=0 m:inet2_3=0 m:inet3_1=0 m:inet3_0=0 m:inet3_3=0 m:inet3_2=0 m:inet3_5=1 m:inet2_9=0 m:inet3_4=0 m:inet3_7=0 m:inet1_1=1 m:hs1=1 m:inet3_6=0 m:civic2_2=0 m:lit2=5 m:hs3_5=8 m:civic2_1=0 m:lit1=5 m:hs3_6=8 m:hs3_3=8 m:hs3_4=0 m:dem7prim=3 m:civic2_6=1 m:hs3_1=8 m:civic2_5=0 m:hs3_2=8 m:civic2_4=0 m:cab_sports=-1 m:civic2_3=0 m:lit3=-1 m:hs3_0=8 m:civic1_7=0 m:hs2_2=0 m:civic1_6=0 m:cab_lifestyle=-1 m:hs2_3=0 m:civic1_5=0 m:weight_eth=0.95 m:civic1_4=0 m:hs2_1=1 m:hs2_6=1 m:civic1_3=0 m:hs2_7=1 m:civic1_2=0 m:hs2_4=0 m:sea4event=0 m:civic1_1=0 m:dem7_1=3 m:hs2_5=0 m:r_lit1=5 m:web1_any=0 m:sea4howto=0 m:r_lit3=0 m:r_lit2=5 m:sea4biz=0 m:civic3_oth8=0 m:sea4nothing=0 m:civic3_3=0 m:civic3_oth7=0 m:civic3_2=0 m:civic3_oth6=0 m:civic3_5=0 m:civic3_oth5=0 m:civic3_4=0 m:civic3_1=1 m:civic3_oth9=0 m:civic3_0=0 m:numcompuse=3 m:numciv3=1 m:civic3_oth4=0 m:civic4_2=8 m:civic3_oth3=0 m:civic4_1=8 m:civic3_oth2=0 m:civic4_4=8 m:civic3_oth1=0 m:sea4trans=0 m:civic4_3=8 m:cable2=-9 m:cable1=-9 m:cable4=-1 m:sea4schools=0 m:hs2_oth2=0 m:hs2_oth1=0 m:sea4dk=1 m:tc6=0 m:cable9=-1 m:cab_na=-1 m:anyemp=1 m:hs2_oth3=0 m:language=1 m:cable6=-1 m:tc2=0 m:cable8=-1 m:cable7=-1 m:dem3=-8 m:dem2=0 m:sea4service=0 m:dem1=3 m:hsfastenuf=8 m:civic1_oth=1 m:sea4pers=0 m:civic3_oth=1 m:dem9=0 m:dem8=1 m:dem7=3 m:dem6=1 m:dem5=4 m:dem4=4 m:inet3_14=0 m:civic4_7=8 m:civic4_5=8 m:civic4_6=8 m:anycable=0 m:numhsapps=3 m:anyinternetdev=1 m:dem10=4 m:sea4seainfo=0 m:sea4opp=0 m:cable8_oth=1 m:cab_other=-1 m:afamer_blk=0 m:pwd=0 m:homenet=1 m:inet7_oth=1 m:cab_comedy=-1 m:civic2=6 m:civic2_7=0 m:sea4disaster=0 m:r_use12=3 m:r_use11=1 m:r_use10=1 m:wgt2=0.66 m:r_use15=1 m:wgt3=0.65 m:tc1_2=0 m:r_use14=1 m:tc1_1=0 m:r_use13=2 m:wgt1=0.84 m:hs3_oth=1 m:sea4current=0 m:smartnetonly=0 m:cab_travel=-1 m:cab_cn=-999 m:web2_oth=1 m:sea4commissue=0 m:survey=1 m:wgt4=0.62 m:tc5_1=1 m:tc5_2=1 m:civic2_oth=1 m:use9=0 m:use8=0 m:sea1_ever=0 m:use7=0 m:cab_pbs=-1 m:inet3_oth=1 m:cab_dk=-1 m:use1=0 m:use2=0 m:use5=0 m:use6=0 m:use3=1 m:use4=0 m:cab_relig=-1 m:tc3_any=1 m:cab_env=-1 m:wgtphoneonly=0.62 m:dem8b_1=0 m:dem8b_2=1 m:dem8b_3=0 m:weight_age=0.78 m:sea1_how=8 m:sea2=7 m:inet2_store=0 m:sea3=9 m:sea4culture=0 m:cnot2_7=0 m:cnot2_8=0 m:cnot2_5=0 m:cnot2_6=0 m:cnot2_88=0 m:cnot2_9=0 m:civic1_9=1 m:inet2_anywifi=0 m:civic1_8=0 m:inet2_med=0 m:cnot2_3=0 m:hs2_9=0 m:web1_freq=0 m:cnot2_4=0 m:cnot2_1=1 m:cnot2_2=0

series e:s98k-8imb d:2013-01-01T00:00:00.000Z t:cnot2_other2="MAINLY BECAUSE MY KIDS WILL BE MOVING OUT AND I'M NOT A BIG USER OF IT." t:sea4notcode=0 t:cable3oth="POOR CUSTOMER SERVICE." t:civic4_oth_1="TV ALERTS" t:fonetype=1 t:cable5="NOTHING SPRINGS TO MIND." t:civic3_other="PRETTY MUCH DON'T CALL ME, I'LL CALL YOU." t:sea4new=NOTHING m:highspeed=2 m:sea4envir=0 m:civic4_oth_2=66 m:inet3=2 m:laptopnetbook=1 m:sea4other=0 m:anymobile=1 m:sea4gov=0 m:rinet4=1 m:numplace=4 m:sea4infra=0 m:cab_hx=0 m:weightfin=0.67 m:inet6=2 m:civic4_oth3=0 m:dem7_cat=3 m:civic4_oth2=0 m:civic4_oth5=1 m:inet4=1 m:civic4_oth4=0 m:inet5=2 m:cab_specific=0 m:civic4_oth1=0 m:cab_movies=0 m:inet2_travel=0 m:sea4alert=0 m:civic4_oth6=0 m:cnot2_oth4=0 m:sea4educ=0 m:cnot2_oth5=0 m:cnot2_oth2=0 m:cnot2_oth3=0 m:sea4quote=0 m:cnot2_oth1=0 m:civic1_na=0 m:civic4_person=0 m:tlength=17 m:sea4crime=0 m:cab_sci=0 m:cable3_oth1=0 m:cab_drama=0 m:sea4input=0 m:tc4_any=0 m:cab_none=1 m:cable3_oth4=0 m:cnot2_oth8=0 m:cable3_oth=56 m:cable3_oth5=1 m:cable3_oth2=3 m:cnot2_oth7=0 m:cable3_oth3=0 m:cnot2_oth6=0 m:civic1_12=0 m:hs3_oth1=0 m:civic1_11=0 m:hs3_oth2=0 m:hs3_oth3=0 m:cnot2_any=1 m:cnot1=-1 m:dslcablewifi=1 m:sea4budget=0 m:hs3_oth4=0 m:hs3_oth5=0 m:civic1_10=0 m:civic3_oth10=0 m:tc3_summary=3 m:sea4pubwrk=0 m:cab_doc=0 m:r_inet3=2 m:cab_diverse=0 m:weight_ed=0.84 m:cauc_wht=1 m:cnot2_12=0 m:cnot2_11=0 m:cnot2_10=0 m:langpref=2 m:multinternetdev=2 m:sea4housing=0 m:gender=1 m:civic1_anyelec=0 m:cb1=1 m:sea4discuss=0 m:cable3_0=0 m:cable3_2=1 m:cable3_1=1 m:cable3_4=0 m:cable3_3=1 m:cab_news=0 m:tc4_1=0 m:tc3_4=0 m:numinternetdev=3 m:dem7a=3 m:hsgoodenuf=0 m:r_use1=1 m:r_use3=1 m:r_use2=1 m:r_use5=0 m:r_use4=1 m:r_use7=1 m:tc3_2=1 m:r_use6=0 m:tc3_1=1 m:hs2_oth=1 m:r_use9=1 m:tc4_3=0 m:r_use8=1 m:inet8_any=-2 m:tc4_2=0 m:civic1_oth3=0 m:civic3_7=0 m:civic1_oth4=0 m:civic3_6=0 m:dslcableallwificell=1 m:civic3_9=0 m:weight=0.99 m:civic3_8=0 m:asian_pi=0 m:use11=0 m:use10=0 m:sea4engage=0 m:use15=1 m:use14=0 m:use13=1 m:use12=3 m:inet4_oth=1 m:civic1_oth1=0 m:civic1_oth2=0 m:cab_local=0 m:cab_noads=0 m:sea4people=0 m:web2=2 m:sample=1 m:inet1_2=1 m:inet7_8=-2 m:inet7_9=-2 m:inet7_6=-2 m:sea4oknow=0 m:inet7_7=-2 m:inet7_4=-2 m:inet7_5=-2 m:inet7_2=-2 m:inet7_3=-2 m:cab_arts=0 m:inet7_1=-2 m:cab_educ=0 m:cab_fam=0 m:inet2_6=1 m:inet2_5=0 m:inet3_8=0 m:inet2_8=0 m:inet2_7=1 m:inet2_2=1 m:inet2_1=1 m:inet2_4=0 m:inet2_3=0 m:inet3_1=0 m:inet3_0=0 m:inet3_3=1 m:inet3_2=0 m:inet3_5=0 m:inet3_4=0 m:inet2_9=0 m:inet3_7=0 m:inet1_1=1 m:hs1=0 m:inet3_6=0 m:civic2_2=0 m:lit2=5 m:hs3_5=0 m:civic2_1=1 m:lit1=5 m:hs3_6=0 m:hs3_3=0 m:dem7prim=3 m:civic2_6=0 m:hs3_1=0 m:civic2_5=0 m:hs3_2=1 m:civic2_4=0 m:cab_sports=0 m:civic2_3=0 m:lit3=5 m:hs3_0=0 m:civic1_7=0 m:hs2_2=-1 m:civic1_6=0 m:cab_lifestyle=0 m:hs2_3=-1 m:civic1_5=0 m:weight_eth=0.95 m:civic1_4=0 m:hs2_1=-1 m:hs2_6=-1 m:civic1_3=0 m:hs2_7=-1 m:civic1_2=1 m:hs2_4=-1 m:sea4event=0 m:civic1_1=0 m:dem7_1=3 m:hs2_5=-1 m:r_lit1=5 m:web1_any=1 m:sea4howto=0 m:r_lit3=5 m:r_lit2=5 m:sea4biz=0 m:civic3_oth8=0 m:sea4nothing=1 m:civic3_3=0 m:civic3_oth7=0 m:civic3_2=0 m:civic3_oth6=0 m:civic3_5=0 m:civic3_oth5=0 m:civic3_4=0 m:civic3_1=0 m:civic3_oth9=0 m:civic3_0=1 m:numciv4=2 m:numcompuse=7 m:numciv3=1 m:civic3_oth4=0 m:civic4_2=1 m:civic3_oth3=0 m:civic4_1=0 m:civic3_oth2=0 m:civic4_4=0 m:civic3_oth1=0 m:sea4trans=0 m:civic4_3=0 m:cable2=3 m:cable1=2 m:cable4=3 m:sea4schools=0 m:hs2_oth2=-1 m:hs2_oth1=-1 m:sea4dk=0 m:tc6=1 m:cable9=3 m:cab_na=0 m:anyemp=1 m:hs2_oth3=-1 m:language=1 m:cable6=0 m:tc2=0 m:cable8=3 m:cable7=1 m:dem3=0 m:dem2=1 m:sea4service=0 m:dem1=4 m:hsfastenuf=0 m:civic1_oth=1 m:sea4pers=0 m:civic3_oth=51 m:dem9=0 m:dem8=1 m:dem7=3 m:dem6=1 m:dem5=4 m:dem4=3 m:inet3_14=0 m:civic4_7=0 m:civic4_5=0 m:civic4_6=0 m:anycable=1 m:anyinternetdev=1 m:dem10=7 m:sea4seainfo=0 m:sea4opp=0 m:cable8_oth=1 m:cab_other=0 m:afamer_blk=0 m:pwd=0 m:homenet=1 m:inet7_oth=1 m:cab_comedy=0 m:civic2=1 m:civic2_7=0 m:sea4disaster=0 m:r_use12=3 m:r_use11=0 m:r_use10=0 m:wgt2=0.71 m:r_use15=1 m:wgt3=0.71 m:tc1_2=1 m:r_use14=0 m:tc1_1=1 m:r_use13=1 m:wgt1=0.84 m:hs3_oth=1 m:sea4current=0 m:cab_quote=0 m:smartnetonly=0 m:cab_travel=0 m:cab_cn=-999 m:web2_oth=1 m:sea4commissue=0 m:survey=1 m:wgt4=0.67 m:tc5_1=1 m:tc5_2=1 m:civic2_oth=1 m:use9=1 m:use8=1 m:sea1_ever=0 m:use7=1 m:cab_pbs=0 m:inet3_oth=1 m:cab_dk=0 m:use1=1 m:use2=1 m:use5=0 m:use6=0 m:use3=1 m:use4=1 m:cab_relig=0 m:tc3_any=1 m:civic4_1_2=1 m:cab_env=0 m:wgtphoneonly=0.67 m:dem8b_1=1 m:civic4_1_2_4=1 m:dem8b_2=0 m:dem8b_3=0 m:civic4_1_4=0 m:civic4_2_4=1 m:weight_age=0.84 m:sea1_how=8 m:sea2=7 m:inet2_store=0 m:sea3=9 m:sea4culture=0 m:cnot2_7=0 m:cnot2_8=0 m:cnot2_5=0 m:cnot2_6=0 m:cnot2_88=0 m:cnot2_9=1 m:civic1_9=0 m:inet2_anywifi=0 m:civic1_8=0 m:inet2_med=0 m:cnot2_3=0 m:hs2_9=-1 m:web1_freq=3 m:cnot2_4=0 m:cnot2_1=0 m:cnot2_2=0

series e:s98k-8imb d:2013-01-01T00:00:00.000Z t:sea4notcode=0 t:fonetype=1 t:sea4new="I DON'T KNOW" m:highspeed=6 m:sea4envir=0 m:civic4_oth_2=1 m:inet3=4 m:laptopnetbook=1 m:sea4other=0 m:anymobile=0 m:sea4gov=0 m:rinet4=1 m:numplace=2 m:sea4infra=0 m:cab_hx=-1 m:weightfin=0.67 m:inet6=3 m:civic4_oth3=0 m:dem7_cat=3 m:civic4_oth2=0 m:civic4_oth5=0 m:inet4=1 m:civic4_oth4=0 m:inet5=9 m:cab_specific=-1 m:civic4_oth1=0 m:cab_movies=-1 m:inet2_travel=0 m:sea4alert=0 m:civic4_oth6=0 m:cnot2_oth4=0 m:cnot2_oth5=0 m:sea4educ=0 m:cnot2_oth2=0 m:cnot2_oth3=0 m:sea4quote=0 m:cnot2_oth1=0 m:civic1_na=0 m:civic4_person=0 m:tlength=18 m:sea4crime=0 m:cab_sci=-1 m:cable3_oth1=-1 m:cab_drama=-1 m:sea4input=0 m:tc4_any=0 m:cab_none=-1 m:cable3_oth4=-1 m:cnot2_oth8=0 m:cable3_oth=1 m:cable3_oth5=-1 m:cable3_oth2=-9 m:cnot2_oth7=0 m:cable3_oth3=-1 m:cnot2_oth6=0 m:civic1_12=0 m:hs3_oth1=0 m:civic1_11=0 m:hs3_oth2=0 m:hs3_oth3=0 m:cnot2_any=1 m:cnot1=0 m:dslcablewifi=0 m:sea4budget=0 m:hs3_oth4=0 m:hs3_oth5=0 m:civic1_10=0 m:civic3_oth10=0 m:tc3_summary=2 m:sea4pubwrk=0 m:cab_doc=-1 m:r_inet3=3 m:cab_diverse=-1 m:weight_ed=0.84 m:cauc_wht=1 m:cnot2_12=0 m:cnot2_11=0 m:cnot2_10=0 m:langpref=2 m:multinternetdev=1 m:sea4housing=0 m:gender=0 m:civic1_anyelec=0 m:cb1=1 m:sea4discuss=0 m:cable3_0=-1 m:cable3_2=-1 m:cable3_1=-1 m:cable3_4=-1 m:cable3_3=-1 m:cab_news=-1 m:tc4_1=0 m:tc3_4=0 m:numinternetdev=1 m:dem7a=3 m:hsgoodenuf=0 m:r_use1=1 m:r_use3=1 m:r_use2=0 m:r_use5=0 m:r_use4=1 m:r_use7=0 m:tc3_2=1 m:r_use6=1 m:tc3_1=0 m:hs2_oth=1 m:r_use9=1 m:tc4_3=0 m:r_use8=0 m:inet8_any=-2 m:tc4_2=0 m:civic1_oth3=0 m:civic3_7=0 m:civic1_oth4=0 m:civic3_6=0 m:dslcableallwificell=1 m:civic3_9=0 m:weight=0.99 m:civic3_8=0 m:asian_pi=0 m:use11=1 m:use10=1 m:sea4engage=0 m:use15=0 m:use14=0 m:use13=2 m:use12=3 m:inet4_oth=1 m:civic1_oth1=0 m:civic1_oth2=0 m:cab_local=-1 m:cab_noads=-1 m:sea4people=0 m:web2=-1 m:sample=1 m:inet1_2=1 m:inet7_8=-2 m:inet7_9=-2 m:inet7_6=-2 m:sea4oknow=0 m:inet7_7=-2 m:inet7_4=-2 m:inet7_5=-2 m:inet7_2=-2 m:inet7_3=-2 m:cab_arts=-1 m:inet7_1=-2 m:cab_educ=-1 m:cab_fam=-1 m:inet2_6=0 m:inet2_5=0 m:inet3_8=0 m:inet2_8=0 m:inet2_7=0 m:inet2_2=1 m:inet2_1=1 m:inet2_4=0 m:inet2_3=0 m:inet3_1=0 m:inet3_0=0 m:inet3_3=0 m:inet3_2=0 m:inet3_5=0 m:inet3_4=0 m:inet2_9=0 m:inet3_7=0 m:inet1_1=1 m:hs1=9 m:inet3_6=1 m:civic2_2=0 m:lit2=5 m:hs3_5=0 m:civic2_1=0 m:lit1=5 m:hs3_6=0 m:hs3_3=0 m:dem7prim=3 m:civic2_6=1 m:hs3_1=1 m:civic2_5=0 m:hs3_2=0 m:civic2_4=0 m:cab_sports=-1 m:civic2_3=0 m:lit3=-1 m:hs3_0=0 m:civic1_7=0 m:hs2_2=-1 m:civic1_6=0 m:cab_lifestyle=-1 m:hs2_3=-1 m:civic1_5=0 m:weight_eth=0.95 m:civic1_4=0 m:hs2_1=-1 m:hs2_6=-1 m:civic1_3=0 m:hs2_7=-1 m:civic1_2=0 m:hs2_4=-1 m:sea4event=0 m:civic1_1=1 m:dem7_1=3 m:hs2_5=-1 m:r_lit1=5 m:web1_any=1 m:sea4howto=0 m:r_lit3=0 m:r_lit2=5 m:sea4biz=0 m:civic3_oth8=0 m:sea4nothing=0 m:civic3_3=0 m:civic3_oth7=0 m:civic3_2=0 m:civic3_oth6=0 m:civic3_5=0 m:civic3_oth5=0 m:civic3_4=0 m:civic3_1=1 m:civic3_oth9=0 m:civic3_0=0 m:numciv4=1 m:numcompuse=7 m:numciv3=1 m:civic3_oth4=0 m:civic4_2=0 m:civic3_oth3=0 m:civic4_1=0 m:civic3_oth2=0 m:civic4_4=1 m:civic3_oth1=0 m:sea4trans=0 m:civic4_3=0 m:cable2=-9 m:cable1=-9 m:cable4=-1 m:sea4schools=0 m:hs2_oth2=-1 m:hs2_oth1=-1 m:sea4dk=1 m:tc6=0 m:cable9=-1 m:cab_na=-1 m:anyemp=1 m:hs2_oth3=-1 m:language=1 m:cable6=-1 m:tc2=0 m:cable8=-1 m:cable7=-1 m:dem3=1 m:dem2=2 m:sea4service=0 m:dem1=4 m:hsfastenuf=0 m:civic1_oth=1 m:sea4pers=0 m:civic3_oth=1 m:dem9=0 m:dem8=1 m:dem7=3 m:dem6=1 m:dem5=4 m:dem4=3 m:inet3_14=0 m:civic4_7=0 m:civic4_5=0 m:civic4_6=0 m:anycable=0 m:anyinternetdev=1 m:dem10=7 m:sea4seainfo=0 m:sea4opp=0 m:cable8_oth=1 m:cab_other=-1 m:afamer_blk=0 m:pwd=0 m:homenet=1 m:inet7_oth=1 m:cab_comedy=-1 m:civic2=6 m:civic2_7=0 m:sea4disaster=0 m:r_use12=3 m:r_use11=1 m:r_use10=1 m:wgt2=0.71 m:r_use15=0 m:wgt3=0.71 m:tc1_2=0 m:r_use14=0 m:tc1_1=0 m:r_use13=2 m:wgt1=0.84 m:hs3_oth=1 m:sea4current=0 m:cab_travel=-1 m:cab_cn=-999 m:web2_oth=1 m:sea4commissue=0 m:survey=1 m:wgt4=0.67 m:tc5_1=1 m:tc5_2=1 m:civic2_oth=1 m:use9=1 m:use8=0 m:sea1_ever=0 m:use7=0 m:cab_pbs=-1 m:inet3_oth=1 m:cab_dk=-1 m:use1=1 m:use2=0 m:use5=0 m:use6=1 m:use3=1 m:use4=1 m:cab_relig=-1 m:tc3_any=1 m:civic4_1_2=0 m:cab_env=-1 m:wgtphoneonly=0.67 m:dem8b_1=0 m:civic4_1_2_4=1 m:dem8b_2=1 m:dem8b_3=0 m:civic4_1_4=1 m:civic4_2_4=1 m:weight_age=0.84 m:sea1_how=8 m:sea2=7 m:inet2_store=0 m:sea3=9 m:sea4culture=0 m:cnot2_7=0 m:cnot2_8=0 m:cnot2_5=0 m:cnot2_6=0 m:cnot2_88=0 m:cnot2_9=1 m:civic1_9=0 m:inet2_anywifi=0 m:civic1_8=0 m:inet2_med=0 m:cnot2_3=0 m:hs2_9=-1 m:web1_freq=1 m:cnot2_4=0 m:cnot2_1=0 m:cnot2_2=0
```

## Meta Commands

```ls
metric m:weightfin p:float l:weightfin t:dataTypeName=number

metric m:wgtphoneonly p:float l:wgtphoneonly t:dataTypeName=number

metric m:survey p:float l:survey t:dataTypeName=number

metric m:sample p:float l:sample t:dataTypeName=number

metric m:langpref p:integer l:LANGPREF t:dataTypeName=number

metric m:gender p:integer l:GENDER t:dataTypeName=number

metric m:dem4 p:float l:DEM4 t:dataTypeName=number

metric m:dem7 p:float l:DEM7 t:dataTypeName=number

metric m:dem5 p:integer l:DEM5 t:dataTypeName=number

metric m:dem10 p:integer l:DEM10 t:dataTypeName=number

metric m:tc3_summary p:float l:TC3.summary t:dataTypeName=number

metric m:tc3_any p:float l:TC3.any t:dataTypeName=number

metric m:inet1_1 p:float l:INET1.1 t:dataTypeName=number

metric m:inet1_2 p:float l:INET1.2 t:dataTypeName=number

metric m:anycable p:float l:anycable t:dataTypeName=number

metric m:tc1_1 p:float l:TC1.1 t:dataTypeName=number

metric m:tc1_2 p:float l:TC1.2 t:dataTypeName=number

metric m:tc2 p:integer l:TC2 t:dataTypeName=number

metric m:tc3_1 p:float l:TC3.1 t:dataTypeName=number

metric m:tc3_2 p:float l:TC3.2 t:dataTypeName=number

metric m:tc3_4 p:float l:TC3.4 t:dataTypeName=number

metric m:laptopnetbook p:float l:laptopnetbook t:dataTypeName=number

metric m:tc3_0 p:float l:TC3.0 t:dataTypeName=number

metric m:tc3_8 p:float l:TC3.8 t:dataTypeName=number

metric m:tc4_1 p:float l:TC4.1 t:dataTypeName=number

metric m:tc4_2 p:float l:TC4.2 t:dataTypeName=number

metric m:tc4_3 p:float l:TC4.3 t:dataTypeName=number

metric m:tc4_any p:float l:TC4.any t:dataTypeName=number

metric m:tc4_0 p:float l:TC4.0 t:dataTypeName=number

metric m:tc4_8 p:float l:TC4.8 t:dataTypeName=number

metric m:tc5_1 p:float l:TC5.1 t:dataTypeName=number

metric m:tc5_2 p:float l:TC5.2 t:dataTypeName=number

metric m:tc6 p:integer l:TC6 t:dataTypeName=number

metric m:anymobile p:float l:anymobile t:dataTypeName=number

metric m:numinternetdev p:float l:NumInternetDev t:dataTypeName=number

metric m:multinternetdev p:float l:MultInternetDev t:dataTypeName=number

metric m:anyinternetdev p:float l:AnyInternetDev t:dataTypeName=number

metric m:smartnetonly p:float l:smartnetonly t:dataTypeName=number

metric m:numplace p:float l:NUMPLACE t:dataTypeName=number

metric m:inet2_88 p:float l:INET2.88 t:dataTypeName=number

metric m:inet2_1 p:float l:INET2.1 t:dataTypeName=number

metric m:inet2_2 p:float l:INET2.2 t:dataTypeName=number

metric m:inet2_3 p:float l:INET2.3 t:dataTypeName=number

metric m:inet2_4 p:float l:INET2.4 t:dataTypeName=number

metric m:inet2_5 p:float l:INET2.5 t:dataTypeName=number

metric m:inet2_6 p:float l:INET2.6 t:dataTypeName=number

metric m:inet2_7 p:float l:INET2.7 t:dataTypeName=number

metric m:inet2_8 p:float l:INET2.8 t:dataTypeName=number

metric m:inet2_travel p:integer l:INET2.travel t:dataTypeName=number

metric m:inet2_store p:float l:INET2.store t:dataTypeName=number

metric m:inet2_9 p:float l:INET2.9 t:dataTypeName=number

metric m:inet2_med p:float l:INET2.med t:dataTypeName=number

metric m:inet2_anywifi p:float l:INET2.anywifi t:dataTypeName=number

metric m:highspeed p:float l:highspeed t:dataTypeName=number

metric m:homenet p:float l:homenet t:dataTypeName=number

metric m:dslcablewifi p:float l:dslcablewifi t:dataTypeName=number

metric m:dslcableallwificell p:float l:dslcableallwificell t:dataTypeName=number

metric m:r_inet3 p:float l:r.INET3 t:dataTypeName=number

metric m:inet3 p:float l:INET3 t:dataTypeName=number

metric m:inet3_2 p:float l:INET3.2 t:dataTypeName=number

metric m:inet3_3 p:float l:INET3.3 t:dataTypeName=number

metric m:inet3_4 p:float l:INET3.4 t:dataTypeName=number

metric m:inet3_5 p:float l:INET3.5 t:dataTypeName=number

metric m:inet3_6 p:float l:INET3.6 t:dataTypeName=number

metric m:inet3_14 p:float l:INET3.14 t:dataTypeName=number

metric m:inet3_1 p:float l:INET3.1 t:dataTypeName=number

metric m:inet3_7 p:float l:INET3.7 t:dataTypeName=number

metric m:inet3_0 p:float l:INET3.0 t:dataTypeName=number

metric m:inet3_8 p:float l:INET3.8 t:dataTypeName=number

metric m:inet3_oth p:integer l:INET3.oth# t:dataTypeName=number

metric m:rinet4 p:float l:rINET4 t:dataTypeName=number

metric m:inet4 p:integer l:INET4 t:dataTypeName=number

metric m:inet4_oth p:integer l:INET4.oth# t:dataTypeName=number

metric m:inet5 p:float l:INET5 t:dataTypeName=number

metric m:inet6 p:float l:INET6 t:dataTypeName=number

metric m:p_inet7 p:integer l:P.INET7 t:dataTypeName=number

metric m:inet7_1 p:float l:INET7.1 t:dataTypeName=number

metric m:inet7_2 p:float l:INET7.2 t:dataTypeName=number

metric m:inet7_3 p:float l:INET7.3 t:dataTypeName=number

metric m:inet7_4 p:float l:INET7.4 t:dataTypeName=number

metric m:inet7_5 p:float l:INET7.5 t:dataTypeName=number

metric m:inet7_6 p:float l:INET7.6 t:dataTypeName=number

metric m:inet7_7 p:float l:INET7.7 t:dataTypeName=number

metric m:inet7_8 p:float l:INET7.8 t:dataTypeName=number

metric m:inet7_9 p:float l:INET7.9 t:dataTypeName=number

metric m:inet7_88 p:float l:INET7.88 t:dataTypeName=number

metric m:inet7_freewifi p:float l:INET7.freewifi t:dataTypeName=number

metric m:inet7_oth p:integer l:INET7.oth# t:dataTypeName=number

metric m:inet8_any p:float l:INET8.any t:dataTypeName=number

metric m:inet8 p:integer l:INET8 t:dataTypeName=number

metric m:r_use1 p:float l:r.use1 t:dataTypeName=number

metric m:r_use2 p:float l:r.use2 t:dataTypeName=number

metric m:r_use3 p:float l:r.use3 t:dataTypeName=number

metric m:r_use4 p:float l:r.use4 t:dataTypeName=number

metric m:r_use5 p:float l:r.use5 t:dataTypeName=number

metric m:r_use6 p:float l:r.use6 t:dataTypeName=number

metric m:r_use7 p:float l:r.use7 t:dataTypeName=number

metric m:r_use8 p:float l:r.use8 t:dataTypeName=number

metric m:r_use9 p:float l:r.use9 t:dataTypeName=number

metric m:r_use10 p:float l:r.use10 t:dataTypeName=number

metric m:r_use11 p:float l:r.use11 t:dataTypeName=number

metric m:r_use12 p:float l:r.use12 t:dataTypeName=number

metric m:r_use13 p:float l:r.use13 t:dataTypeName=number

metric m:r_use14 p:float l:r.use14 t:dataTypeName=number

metric m:r_use15 p:float l:r.use15 t:dataTypeName=number

metric m:r_lit1 p:float l:r.lit1 t:dataTypeName=number

metric m:r_lit2 p:float l:r.lit2 t:dataTypeName=number

metric m:r_lit3 p:float l:r.lit3 t:dataTypeName=number

metric m:numcompuse p:float l:numcompuse t:dataTypeName=number

metric m:use1 p:integer l:USE1 t:dataTypeName=number

metric m:use2 p:integer l:USE2 t:dataTypeName=number

metric m:use3 p:integer l:USE3 t:dataTypeName=number

metric m:use4 p:integer l:USE4 t:dataTypeName=number

metric m:use5 p:integer l:USE5 t:dataTypeName=number

metric m:use6 p:integer l:USE6 t:dataTypeName=number

metric m:use7 p:integer l:USE7 t:dataTypeName=number

metric m:use8 p:integer l:USE8 t:dataTypeName=number

metric m:use9 p:integer l:USE9 t:dataTypeName=number

metric m:use10 p:integer l:USE10 t:dataTypeName=number

metric m:use11 p:integer l:USE11 t:dataTypeName=number

metric m:o_usesellgoods p:float l:O.usesellgoods t:dataTypeName=number

metric m:o_usepostvid p:float l:O.usepostvid t:dataTypeName=number

metric m:o_usepodcast p:float l:O.usepodcast t:dataTypeName=number

metric m:o_usenone p:float l:O.usenone t:dataTypeName=number

metric m:use12 p:float l:use12 t:dataTypeName=number

metric m:use13 p:float l:use13 t:dataTypeName=number

metric m:use14 p:float l:use14 t:dataTypeName=number

metric m:use15 p:float l:use15 t:dataTypeName=number

metric m:lit1 p:integer l:LIT1 t:dataTypeName=number

metric m:lit2 p:integer l:LIT2 t:dataTypeName=number

metric m:lit3 p:integer l:LIT3 t:dataTypeName=number

metric m:numhsapps p:float l:numhsapps t:dataTypeName=number

metric m:hs1 p:float l:HS1 t:dataTypeName=number

metric m:hs2_1 p:float l:HS2.1 t:dataTypeName=number

metric m:hs2_2 p:float l:HS2.2 t:dataTypeName=number

metric m:hs2_3 p:float l:HS2.3 t:dataTypeName=number

metric m:hs2_4 p:float l:HS2.4 t:dataTypeName=number

metric m:hs2_5 p:float l:HS2.5 t:dataTypeName=number

metric m:hs2_6 p:float l:HS2.6 t:dataTypeName=number

metric m:hs2_7 p:float l:HS2.7 t:dataTypeName=number

metric m:hs2_9 p:float l:HS2.9 t:dataTypeName=number

metric m:hs2_88 p:float l:HS2.88 t:dataTypeName=number

metric m:hs2_oth p:integer l:HS2.oth# t:dataTypeName=number

metric m:hs2_oth1 p:float l:HS2.oth1 t:dataTypeName=number

metric m:hs2_oth2 p:float l:HS2.oth2 t:dataTypeName=number

metric m:hs2_oth3 p:float l:HS2.oth3 t:dataTypeName=number

metric m:hs3_1 p:float l:HS3.1 t:dataTypeName=number

metric m:hs3_2 p:float l:HS3.2 t:dataTypeName=number

metric m:hs3_3 p:float l:HS3.3 t:dataTypeName=number

metric m:hs3_5 p:float l:HS3.5 t:dataTypeName=number

metric m:hs3_4 p:float l:HS3.4 t:dataTypeName=number

metric m:hs3_6 p:float l:HS3.6 t:dataTypeName=number

metric m:hs3_0 p:float l:HS3.0 t:dataTypeName=number

metric m:hsgoodenuf p:float l:hsgoodenuf t:dataTypeName=number

metric m:hsfastenuf p:float l:hsfastenuf t:dataTypeName=number

metric m:hs3_oth p:integer l:HS3.oth# t:dataTypeName=number

metric m:hs3_oth1 p:float l:HS3.oth1 t:dataTypeName=number

metric m:hs3_oth2 p:float l:HS3.oth2 t:dataTypeName=number

metric m:hs3_oth3 p:float l:HS3.oth3 t:dataTypeName=number

metric m:hs3_oth4 p:float l:HS3.oth4 t:dataTypeName=number

metric m:hs3_oth5 p:float l:HS3.oth5 t:dataTypeName=number

metric m:cable1 p:float l:CABLE1 t:dataTypeName=number

metric m:cable2 p:float l:CABLE2 t:dataTypeName=number

metric m:cable3_1 p:float l:CABLE3.1 t:dataTypeName=number

metric m:cable3_2 p:float l:CABLE3.2 t:dataTypeName=number

metric m:cable3_3 p:float l:CABLE3.3 t:dataTypeName=number

metric m:cable3_4 p:float l:CABLE3.4 t:dataTypeName=number

metric m:cable3_14 p:float l:CABLE3.14 t:dataTypeName=number

metric m:cable3_oth p:integer l:CABLE3.OTH# t:dataTypeName=number

metric m:cable3_oth1 p:float l:CABLE3.OTH1 t:dataTypeName=number

metric m:cable3_oth2 p:float l:CABLE3.OTH2 t:dataTypeName=number

metric m:cable3_oth3 p:float l:CABLE3.OTH3 t:dataTypeName=number

metric m:cable3_oth4 p:float l:CABLE3.OTH4 t:dataTypeName=number

metric m:cable3_oth5 p:float l:CABLE3.OTH5 t:dataTypeName=number

metric m:cable3_0 p:float l:CABLE3.0 t:dataTypeName=number

metric m:cable4 p:integer l:CABLE4 t:dataTypeName=number

metric m:cab_quote p:integer l:CAB.quote t:dataTypeName=number

metric m:cab_local p:integer l:CAB.local t:dataTypeName=number

metric m:cab_educ p:integer l:CAB.educ t:dataTypeName=number

metric m:cab_arts p:integer l:CAB.arts t:dataTypeName=number

metric m:cab_env p:integer l:CAB.env t:dataTypeName=number

metric m:cab_diverse p:integer l:CAB.diverse t:dataTypeName=number

metric m:cab_fam p:integer l:CAB.fam t:dataTypeName=number

metric m:cab_news p:integer l:CAB.news t:dataTypeName=number

metric m:cab_cn p:float l:CAB.cn t:dataTypeName=number

metric m:cab_none p:integer l:CAB.none t:dataTypeName=number

metric m:cab_dk p:integer l:CAB.dk t:dataTypeName=number

metric m:cab_na p:integer l:CAB.na t:dataTypeName=number

metric m:cab_other p:integer l:CAB.other# t:dataTypeName=number

metric m:cab_movies p:integer l:CAB.movies t:dataTypeName=number

metric m:cab_noads p:integer l:CAB.noads t:dataTypeName=number

metric m:cab_sci p:integer l:CAB.sci t:dataTypeName=number

metric m:cab_travel p:integer l:CAB.travel t:dataTypeName=number

metric m:cab_lifestyle p:integer l:CAB.lifestyle t:dataTypeName=number

metric m:cab_doc p:integer l:CAB.doc t:dataTypeName=number

metric m:cab_sports p:integer l:CAB.sports t:dataTypeName=number

metric m:cab_hx p:integer l:CAB.hx t:dataTypeName=number

metric m:cab_specific p:integer l:CAB.specific t:dataTypeName=number

metric m:cab_relig p:integer l:CAB.relig t:dataTypeName=number

metric m:cab_pbs p:integer l:CAB.pbs t:dataTypeName=number

metric m:cab_comedy p:integer l:CAB.comedy t:dataTypeName=number

metric m:cab_drama p:integer l:CAB.drama t:dataTypeName=number

metric m:cable6 p:integer l:CABLE6 t:dataTypeName=number

metric m:cable7 p:integer l:CABLE7 t:dataTypeName=number

metric m:cable8 p:integer l:CABLE8 t:dataTypeName=number

metric m:cable8_oth p:integer l:CABLE8.oth# t:dataTypeName=number

metric m:cable9 p:float l:CABLE9 t:dataTypeName=number

metric m:cnot1 p:integer l:CNOT1 t:dataTypeName=number

metric m:cnot2_1 p:float l:CNOT2.1 t:dataTypeName=number

metric m:cnot2_2 p:float l:CNOT2.2 t:dataTypeName=number

metric m:cnot2_3 p:float l:CNOT2.3 t:dataTypeName=number

metric m:cnot2_4 p:float l:CNOT2.4 t:dataTypeName=number

metric m:cnot2_5 p:float l:CNOT2.5 t:dataTypeName=number

metric m:cnot2_6 p:float l:CNOT2.6 t:dataTypeName=number

metric m:cnot2_7 p:float l:CNOT2.7 t:dataTypeName=number

metric m:cnot2_8 p:float l:CNOT2.8 t:dataTypeName=number

metric m:cnot2_9 p:float l:CNOT2.9 t:dataTypeName=number

metric m:cnot2_10 p:float l:CNOT2.10 t:dataTypeName=number

metric m:cnot2_11 p:float l:CNOT2.11 t:dataTypeName=number

metric m:cnot2_88 p:float l:CNOT2.88 t:dataTypeName=number

metric m:cnot2_12 p:float l:CNOT2.12 t:dataTypeName=number

metric m:cnot2_oth1 p:float l:CNOT2.oth1 t:dataTypeName=number

metric m:cnot2_oth2 p:float l:CNOT2.oth2 t:dataTypeName=number

metric m:cnot2_oth3 p:float l:CNOT2.oth3 t:dataTypeName=number

metric m:cnot2_oth4 p:float l:CNOT2.oth4 t:dataTypeName=number

metric m:cnot2_oth5 p:float l:CNOT2.oth5 t:dataTypeName=number

metric m:cnot2_oth6 p:float l:CNOT2.oth6 t:dataTypeName=number

metric m:cnot2_oth7 p:float l:CNOT2.oth7 t:dataTypeName=number

metric m:cnot2_oth8 p:float l:CNOT2.oth8 t:dataTypeName=number

metric m:cnot2_any p:float l:CNOT2.any t:dataTypeName=number

metric m:cb1 p:integer l:CB1 t:dataTypeName=number

metric m:o_cb1print p:float l:O.cb1print t:dataTypeName=number

metric m:o_cb1meeting p:float l:O.cb1meeting t:dataTypeName=number

metric m:o_cb1email p:float l:O.cb1email t:dataTypeName=number

metric m:o_cb1fb p:float l:O.cb1fb t:dataTypeName=number

metric m:o_cb1twitter p:float l:O.cb1twitter t:dataTypeName=number

metric m:o_cb1website p:float l:O.cb1website t:dataTypeName=number

metric m:o_cb1text p:float l:O.cb1text t:dataTypeName=number

metric m:o_cb1rss p:float l:O.cb1rss t:dataTypeName=number

metric m:o_cb1calendar p:float l:O.cb1calendar t:dataTypeName=number

metric m:o_cb1blog p:float l:O.cb1blog t:dataTypeName=number

metric m:o_cb1dk p:float l:O.cb1dk t:dataTypeName=number

metric m:o_anycb1oth p:float l:O.anycb1oth t:dataTypeName=number

metric m:civic1_1 p:float l:CIVIC1.1 t:dataTypeName=number

metric m:civic1_2 p:float l:CIVIC1.2 t:dataTypeName=number

metric m:civic1_3 p:float l:CIVIC1.3 t:dataTypeName=number

metric m:civic1_4 p:float l:CIVIC1.4 t:dataTypeName=number

metric m:civic1_5 p:float l:CIVIC1.5 t:dataTypeName=number

metric m:civic1_6 p:float l:CIVIC1.6 t:dataTypeName=number

metric m:civic1_7 p:float l:CIVIC1.7 t:dataTypeName=number

metric m:civic1_8 p:float l:CIVIC1.8 t:dataTypeName=number

metric m:civic1_9 p:float l:CIVIC1.9 t:dataTypeName=number

metric m:civic1_10 p:float l:CIVIC1.10 t:dataTypeName=number

metric m:civic1_11 p:float l:CIVIC1.11 t:dataTypeName=number

metric m:civic1_12 p:float l:CIVIC1.12 t:dataTypeName=number

metric m:civic1_anyelec p:float l:CIVIC1.anyelec t:dataTypeName=number

metric m:civic1_oth p:integer l:CIVIC1.oth# t:dataTypeName=number

metric m:civic1_oth1 p:float l:CIVIC1.oth1 t:dataTypeName=number

metric m:civic1_oth2 p:float l:CIVIC1.oth2 t:dataTypeName=number

metric m:civic1_oth3 p:float l:CIVIC1.oth3 t:dataTypeName=number

metric m:civic1_oth4 p:float l:CIVIC1.oth4 t:dataTypeName=number

metric m:civic1_na p:float l:CIVIC1.na t:dataTypeName=number

metric m:civic2 p:float l:CIVIC2 t:dataTypeName=number

metric m:civic2_1 p:float l:CIVIC2.1 t:dataTypeName=number

metric m:civic2_2 p:float l:CIVIC2.2 t:dataTypeName=number

metric m:civic2_3 p:float l:CIVIC2.3 t:dataTypeName=number

metric m:civic2_4 p:float l:CIVIC2.4 t:dataTypeName=number

metric m:civic2_5 p:float l:CIVIC2.5 t:dataTypeName=number

metric m:civic2_6 p:float l:CIVIC2.6 t:dataTypeName=number

metric m:civic2_7 p:float l:CIVIC2.7 t:dataTypeName=number

metric m:civic2_88 p:float l:CIVIC2.88 t:dataTypeName=number

metric m:civic2_oth p:integer l:CIVIC2.oth# t:dataTypeName=number

metric m:numciv3 p:float l:numciv3 t:dataTypeName=number

metric m:civic3_1 p:float l:CIVIC3.1 t:dataTypeName=number

metric m:civic3_2 p:float l:CIVIC3.2 t:dataTypeName=number

metric m:civic3_3 p:float l:CIVIC3.3 t:dataTypeName=number

metric m:civic3_4 p:float l:CIVIC3.4 t:dataTypeName=number

metric m:civic3_5 p:float l:CIVIC3.5 t:dataTypeName=number

metric m:civic3_6 p:float l:CIVIC3.6 t:dataTypeName=number

metric m:civic3_7 p:float l:CIVIC3.7 t:dataTypeName=number

metric m:civic3_8 p:float l:CIVIC3.8 t:dataTypeName=number

metric m:civic3_9 p:float l:CIVIC3.9 t:dataTypeName=number

metric m:civic3_0 p:float l:CIVIC3.0 t:dataTypeName=number

metric m:civic3_oth p:integer l:CIVIC3.oth# t:dataTypeName=number

metric m:civic3_oth1 p:float l:CIVIC3.oth1 t:dataTypeName=number

metric m:civic3_oth2 p:float l:CIVIC3.oth2 t:dataTypeName=number

metric m:civic3_oth3 p:float l:CIVIC3.oth3 t:dataTypeName=number

metric m:civic3_oth4 p:float l:CIVIC3.oth4 t:dataTypeName=number

metric m:civic3_oth5 p:float l:CIVIC3.oth5 t:dataTypeName=number

metric m:civic3_oth6 p:float l:CIVIC3.oth6 t:dataTypeName=number

metric m:civic3_oth7 p:float l:CIVIC3.oth7 t:dataTypeName=number

metric m:civic3_oth8 p:float l:CIVIC3.oth8 t:dataTypeName=number

metric m:civic3_oth9 p:float l:CIVIC3.oth9 t:dataTypeName=number

metric m:civic3_oth10 p:float l:CIVIC3.oth10 t:dataTypeName=number

metric m:numciv4 p:float l:numciv4 t:dataTypeName=number

metric m:civic4_1 p:float l:CIVIC4.1 t:dataTypeName=number

metric m:civic4_2 p:float l:CIVIC4.2 t:dataTypeName=number

metric m:civic4_3 p:float l:CIVIC4.3 t:dataTypeName=number

metric m:civic4_4 p:float l:CIVIC4.4 t:dataTypeName=number

metric m:civic4_5 p:float l:CIVIC4.5 t:dataTypeName=number

metric m:civic4_6 p:float l:CIVIC4.6 t:dataTypeName=number

metric m:civic4_7 p:float l:CIVIC4.7 t:dataTypeName=number

metric m:civic4_0 p:float l:CIVIC4.0 t:dataTypeName=number

metric m:civic4_1_2_4 p:float l:CIVIC4.1_2_4 t:dataTypeName=number

metric m:civic4_1_4 p:float l:CIVIC4.1_4 t:dataTypeName=number

metric m:civic4_2_4 p:float l:CIVIC4.2_4 t:dataTypeName=number

metric m:civic4_1_2 p:float l:CIVIC4.1_2 t:dataTypeName=number

metric m:civic4_person p:float l:CIVIC4.person t:dataTypeName=number

metric m:civic4_oth_2 p:integer l:CIVIC4.oth# t:dataTypeName=number

metric m:civic4_oth1 p:float l:CIVIC4.oth1 t:dataTypeName=number

metric m:civic4_oth2 p:float l:CIVIC4.oth2 t:dataTypeName=number

metric m:civic4_oth3 p:float l:CIVIC4.oth3 t:dataTypeName=number

metric m:civic4_oth4 p:float l:CIVIC4.oth4 t:dataTypeName=number

metric m:civic4_oth5 p:float l:CIVIC4.oth5 t:dataTypeName=number

metric m:civic4_oth6 p:float l:CIVIC4.oth6 t:dataTypeName=number

metric m:web1_any p:float l:WEB1.any t:dataTypeName=number

metric m:web1_freq p:float l:WEB1.freq t:dataTypeName=number

metric m:web2 p:float l:WEB2 t:dataTypeName=number

metric m:web2_oth p:integer l:WEB2.oth# t:dataTypeName=number

metric m:sea1_ever p:float l:SEA1.ever t:dataTypeName=number

metric m:sea1_how p:float l:SEA1.how t:dataTypeName=number

metric m:sea2 p:float l:SEA2 t:dataTypeName=number

metric m:sea3 p:float l:SEA3 t:dataTypeName=number

metric m:sea4_2 p:integer l:SEA4# t:dataTypeName=number

metric m:sea4dk p:integer l:SEA4DK t:dataTypeName=number

metric m:sea4nothing p:integer l:SEA4NOTHING t:dataTypeName=number

metric m:sea4other p:integer l:SEA4OTHER t:dataTypeName=number

metric m:sea4oknow p:integer l:SEA4OKNOW t:dataTypeName=number

metric m:sea4quote p:integer l:SEA4QUOTE t:dataTypeName=number

metric m:sea4pers p:integer l:SEA4PERS t:dataTypeName=number

metric m:sea4infra p:integer l:SEA4INFRA t:dataTypeName=number

metric m:sea4event p:integer l:SEA4EVENT t:dataTypeName=number

metric m:sea4alert p:integer l:SEA4ALERT t:dataTypeName=number

metric m:sea4engage p:integer l:SEA4ENGAGE t:dataTypeName=number

metric m:sea4current p:integer l:SEA4CURRENT t:dataTypeName=number

metric m:sea4trans p:integer l:SEA4TRANS t:dataTypeName=number

metric m:sea4culture p:integer l:SEA4CULTURE t:dataTypeName=number

metric m:sea4seainfo p:integer l:SEA4SEAINFO t:dataTypeName=number

metric m:sea4gov p:integer l:SEA4GOV t:dataTypeName=number

metric m:sea4commissue p:integer l:SEA4COMMISSUE t:dataTypeName=number

metric m:sea4howto p:integer l:SEA4HOWTO t:dataTypeName=number

metric m:sea4pubwrk p:integer l:SEA4PUBWRK t:dataTypeName=number

metric m:sea4opp p:integer l:SEA4OPP t:dataTypeName=number

metric m:sea4crime p:integer l:SEA4CRIME t:dataTypeName=number

metric m:sea4budget p:integer l:SEA4BUDGET t:dataTypeName=number

metric m:sea4disaster p:integer l:SEA4DISASTER t:dataTypeName=number

metric m:sea4service p:integer l:SEA4SERVICE t:dataTypeName=number

metric m:sea4envir p:integer l:SEA4ENVIR t:dataTypeName=number

metric m:sea4input p:integer l:SEA4INPUT t:dataTypeName=number

metric m:sea4people p:integer l:SEA4PEOPLE t:dataTypeName=number

metric m:sea4educ p:integer l:SEA4EDUC t:dataTypeName=number

metric m:sea4schools p:integer l:SEA4SCHOOLS t:dataTypeName=number

metric m:sea4biz p:integer l:SEA4BIZ t:dataTypeName=number

metric m:sea4discuss p:integer l:SEA4DISCUSS t:dataTypeName=number

metric m:sea4housing p:integer l:SEA4HOUSING t:dataTypeName=number

metric m:dem1 p:integer l:DEM1 t:dataTypeName=number

metric m:dem2 p:integer l:DEM2 t:dataTypeName=number

metric m:dem3 p:integer l:DEM3 t:dataTypeName=number

metric m:dem6 p:integer l:DEM6 t:dataTypeName=number

metric m:dem7_1 p:integer l:DEM7_1 t:dataTypeName=number

metric m:dem7_2 p:integer l:DEM7_2 t:dataTypeName=number

metric m:dem7prim p:integer l:DEM7PRIM t:dataTypeName=number

metric m:dem7a p:integer l:DEM7A t:dataTypeName=number

metric m:dem7_cat p:float l:DEM7.cat t:dataTypeName=number

metric m:afamer_blk p:float l:AFAMER.BLK t:dataTypeName=number

metric m:asian_pi p:float l:ASIAN.PI t:dataTypeName=number

metric m:cauc_wht p:float l:CAUC.WHT t:dataTypeName=number

metric m:dem8 p:integer l:DEM8 t:dataTypeName=number

metric m:dem8b_1 p:float l:DEM8b.1 t:dataTypeName=number

metric m:dem8b_2 p:float l:DEM8b.2 t:dataTypeName=number

metric m:dem8b_3 p:float l:DEM8b.3 t:dataTypeName=number

metric m:anyemp p:float l:anyemp t:dataTypeName=number

metric m:dem8a_4 p:float l:DEM8a.4 t:dataTypeName=number

metric m:dem8a_5 p:float l:DEM8a.5 t:dataTypeName=number

metric m:dem8a_6 p:float l:DEM8a.6 t:dataTypeName=number

metric m:dem8a_7 p:float l:DEM8a.7 t:dataTypeName=number

metric m:dem8a_9 p:float l:DEM8a.9 t:dataTypeName=number

metric m:dem9 p:integer l:DEM9 t:dataTypeName=number

metric m:pwd p:float l:PWD t:dataTypeName=number

metric m:language p:integer l:LANGUAGE t:dataTypeName=number

metric m:tlength p:integer l:TLENGTH t:dataTypeName=number

metric m:weight_ed p:float l:weight.ed t:dataTypeName=number

metric m:wgt1 p:float l:wgt1 t:dataTypeName=number

metric m:weight_age p:float l:weight.age t:dataTypeName=number

metric m:wgt2 p:float l:wgt2 t:dataTypeName=number

metric m:weight p:float l:weight.$ t:dataTypeName=number

metric m:wgt3 p:float l:wgt3 t:dataTypeName=number

metric m:weight_eth p:float l:weight.eth t:dataTypeName=number

metric m:wgt4 p:float l:wgt4 t:dataTypeName=number

metric m:wgt5 p:float l:wgt5 t:dataTypeName=number

entity e:s98k-8imb l:"COS DO- IT Phone And Online Survey Data 2013" t:attribution="Department of Information Technology" t:url=https://data.seattle.gov/api/views/s98k-8imb

property e:s98k-8imb t:meta.view v:id=s98k-8imb v:category=Community v:attributionLink=http://www.seattle.gov/tech/indicators v:averageRating=0 v:name="COS DO- IT Phone And Online Survey Data 2013" v:attribution="Department of Information Technology"

property e:s98k-8imb t:meta.view.license v:name="Public Domain"

property e:s98k-8imb t:meta.view.owner v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:displayName="Seattle IT"

property e:s98k-8imb t:meta.view.tableauthor v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:roleName=administrator v:displayName="Seattle IT"
```

## Top Records

```ls
| id         | weightfin | wgtphoneonly | survey | sample | fonetype | langpref | gender | s1       | dem4 | dem7 | dem5 | dem10 | tc3_summary | tc3_any | inet1_1 | inet1_2 | anycable | tc1_1   | tc1_2 | tc2 | tc3_1 | tc3_2 | tc3_4 | laptopnetbook | tc3_0 | tc3_8 | tc3_other | tc4_1 | tc4_2 | tc4_3 | tc4_any | tc4_0 | tc4_8 | tc5_1 | tc5_2 | tc6 | anymobile | numinternetdev | multinternetdev | anyinternetdev | smartnetonly | numplace | inet2_88 | inet2_1 | inet2_2 | inet2_3 | inet2_4 | inet2_5 | inet2_6 | inet2_7 | inet2_8 | inet2_travel | inet2_store | inet2_9 | inet2_med | inet2_anywifi | inet2_other | highspeed | homenet | dslcablewifi | dslcableallwificell | r_inet3 | inet3 | inet3_2 | inet3_3 | inet3_4 | inet3_5 | inet3_6 | inet3_14 | inet3_1 | inet3_7 | inet3_0 | inet3_8 | inet3_other | inet3_oth | rinet4 | inet4 | inet4_oth | inet4oth | inet5 | inet6 | inet6whence | p_inet7 | inet7_1 | inet7_2 | inet7_3 | inet7_4 | inet7_5 | inet7_6 | inet7_7 | inet7_8 | inet7_9 | inet7_88 | inet7_freewifi | inet7oth                                                             | inet7_oth | inet8_any | inet8 | r_use1 | r_use2 | r_use3 | r_use4 | r_use5 | r_use6 | r_use7 | r_use8 | r_use9 | r_use10 | r_use11 | r_use12 | r_use13 | r_use14 | r_use15 | r_lit1 | r_lit2 | r_lit3 | numcompuse | use1 | use2 | use3 | use4 | use5 | use6 | use7 | use8 | use9 | use10 | use11 | o_usesellgoods | o_usepostvid | o_usepodcast | o_usenone | o_otheruse | use12 | use13 | use14 | othersocnw | use15 | lit1 | lit2 | lit3 | numhsapps | hs1   | hs2_1 | hs2_2 | hs2_3 | hs2_4 | hs2_5 | hs2_6 | hs2_7 | hs2_9 | hs2_88 | hs2_other                              | hs2_oth | hs2_oth1 | hs2_oth2 | hs2_oth3 | hs3_1 | hs3_2 | hs3_3 | hs3_5 | hs3_4 | hs3_6 | hs3_0 | hs3_other   | hsgoodenuf | hsfastenuf | hs3_oth | hs3_oth1 | hs3_oth2 | hs3_oth3 | hs3_oth4 | hs3_oth5 | cable1 | cable2 | cable3_1 | cable3_2 | cable3_3 | cable3_4 | cable3_14 | cable3oth                                                                                                                                                                                             | cable3_oth | cable3_oth1 | cable3_oth2 | cable3_oth3 | cable3_oth4 | cable3_oth5 | cable3_0 | cable4 | cable5                                                                                                                                                                                  | cab_quote | cab_local | cab_educ | cab_arts | cab_env | cab_diverse | cab_fam | cab_news | cab_cn  | cab_none | cab_dk | cab_na | cab_other | cab_movies | cab_noads | cab_sci | cab_travel | cab_lifestyle | cab_doc | cab_sports | cab_hx | cab_specific | cab_relig | cab_pbs | cab_comedy | cab_drama | cable6 | cable7 | cable8 | cable8oth | cable8_oth | cable9 | cnot1 | cnot2_other1 | cnot2_other2                                                            | cnot2_1 | cnot2_2 | cnot2_3 | cnot2_4 | cnot2_5 | cnot2_6 | cnot2_7 | cnot2_8 | cnot2_9 | cnot2_10 | cnot2_11 | cnot2_88 | cnot2_12 | cnot2_oth1 | cnot2_oth2 | cnot2_oth3 | cnot2_oth4 | cnot2_oth5 | cnot2_oth6 | cnot2_oth7 | cnot2_oth8 | cnot2_any | cb1 | o_cb1print | o_cb1meeting | o_cb1phone | o_cb1email | o_cb1fb | o_cb1twitter | o_cb1website | o_cb1text | o_cb1rss | o_cb1calendar | o_cb1blog | o_cb1dk | o_anycb1oth | o_cb1oth | civic1_1 | civic1_2 | civic1_3 | civic1_4 | civic1_5 | civic1_6 | civic1_7 | civic1_8 | civic1_9 | civic1_10 | civic1_11 | civic1_12 | civic1_anyelec | civic1_other | civic1_oth | civic1_oth1 | civic1_oth2 | civic1_oth3 | civic1_oth4 | civic1_na | civic2 | civic2_1 | civic2_2 | civic2_3 | civic2_4 | civic2_5 | civic2_6 | civic2_7 | civic2_88 | civic2_other | civic2_oth | numciv3 | civic3_1 | civic3_2 | civic3_3 | civic3_4 | civic3_5 | civic3_6 | civic3_7 | civic3_8 | civic3_9 | civic3_0 | civic3_other                              | civic3_oth | civic3_oth1 | civic3_oth2 | civic3_oth3 | civic3_oth4 | civic3_oth5 | civic3_oth6 | civic3_oth7 | civic3_oth8 | civic3_oth9 | civic3_oth10 | numciv4 | civic4_1 | civic4_2 | civic4_3 | civic4_4 | civic4_5 | civic4_6 | civic4_7 | civic4_0 | civic4_1_2_4 | civic4_1_4 | civic4_2_4 | civic4_1_2 | civic4_person | civic4_oth_1        | civic4_oth_2 | civic4_oth1 | civic4_oth2 | civic4_oth3 | civic4_oth4 | civic4_oth5 | civic4_oth6 | web1_any | web1_freq | web2  | web2_other | web2_oth | sea1_ever | sea1_how | sea2 | sea3 | sea4_1 | sea4_2 | sea4new                                                                                                                                               | sea4dk | sea4nothing | sea4other | sea4oknow | sea4quote | sea4pers | sea4infra | sea4event | sea4alert | sea4engage | sea4current | sea4trans | sea4culture | sea4seainfo | sea4gov | sea4commissue | sea4howto | sea4pubwrk | sea4opp | sea4crime | sea4budget | sea4disaster | sea4service | sea4envir | sea4input | sea4people | sea4educ | sea4schools | sea4biz | sea4discuss | sea4housing | sea4notcode | dem1 | dem2 | dem3 | dem6 | dem6_other | dem7_1 | dem7_2 | dem7oth | dem7prim | dem7a | dem7_cat | afamer_blk | asian_pi | cauc_wht | hisp_lat | dem8 | dem8b_1 | dem8b_2 | dem8b_3 | anyemp | dem8a_4 | dem8a_5 | dem8a_6 | dem8a_7 | dem8a_9 | dem9 | pwd  | language | tlength | weight_ed | wgt1 | weight_age | wgt2 | weight | wgt3 | weight_eth | wgt4 | weight_zip | wgt5 | 
| ========== | ========= | ============ | ====== | ====== | ======== | ======== | ====== | ======== | ==== | ==== | ==== | ===== | =========== | ======= | ======= | ======= | ======== | ======= | ===== | === | ===== | ===== | ===== | ============= | ===== | ===== | ========= | ===== | ===== | ===== | ======= | ===== | ===== | ===== | ===== | === | ========= | ============== | =============== | ============== | ============ | ======== | ======== | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ============ | =========== | ======= | ========= | ============= | =========== | ========= | ======= | ============ | =================== | ======= | ===== | ======= | ======= | ======= | ======= | ======= | ======== | ======= | ======= | ======= | ======= | =========== | ========= | ====== | ===== | ========= | ======== | ===== | ===== | =========== | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======== | ============== | ==================================================================== | ========= | ========= | ===== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ======= | ======= | ======= | ======= | ======= | ======= | ====== | ====== | ====== | ========== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ===== | ===== | ============== | ============ | ============ | ========= | ========== | ===== | ===== | ===== | ========== | ===== | ==== | ==== | ==== | ========= | ===== | ===== | ===== | ===== | ===== | ===== | ===== | ===== | ===== | ====== | ====================================== | ======= | ======== | ======== | ======== | ===== | ===== | ===== | ===== | ===== | ===== | ===== | =========== | ========== | ========== | ======= | ======== | ======== | ======== | ======== | ======== | ====== | ====== | ======== | ======== | ======== | ======== | ========= | ===================================================================================================================================================================================================== | ========== | =========== | =========== | =========== | =========== | =========== | ======== | ====== | ======================================================================================================================================================================================= | ========= | ========= | ======== | ======== | ======= | =========== | ======= | ======== | ======= | ======== | ====== | ====== | ========= | ========== | ========= | ======= | ========== | ============= | ======= | ========== | ====== | ============ | ========= | ======= | ========== | ========= | ====== | ====== | ====== | ========= | ========== | ====== | ===== | ============ | ======================================================================= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======== | ======== | ======== | ======== | ========== | ========== | ========== | ========== | ========== | ========== | ========== | ========== | ========= | === | ========== | ============ | ========== | ========== | ======= | ============ | ============ | ========= | ======== | ============= | ========= | ======= | =========== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ========= | ========= | ========= | ============== | ============ | ========== | =========== | =========== | =========== | =========== | ========= | ====== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ========= | ============ | ========== | ======= | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ========================================= | ========== | =========== | =========== | =========== | =========== | =========== | =========== | =========== | =========== | =========== | ============ | ======= | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ============ | ========== | ========== | ========== | ============= | =================== | ============ | =========== | =========== | =========== | =========== | =========== | =========== | ======== | ========= | ===== | ========== | ======== | ========= | ======== | ==== | ==== | ====== | ====== | ===================================================================================================================================================== | ====== | =========== | ========= | ========= | ========= | ======== | ========= | ========= | ========= | ========== | =========== | ========= | =========== | =========== | ======= | ============= | ========= | ========== | ======= | ========= | ========== | ============ | =========== | ========= | ========= | ========== | ======== | =========== | ======= | =========== | =========== | =========== | ==== | ==== | ==== | ==== | ========== | ====== | ====== | ======= | ======== | ===== | ======== | ========== | ======== | ======== | ======== | ==== | ======= | ======= | ======= | ====== | ======= | ======= | ======= | ======= | ======= | ==== | ==== | ======== | ======= | ========= | ==== | ========== | ==== | ====== | ==== | ========== | ==== | ========== | ==== | 
| 1          | 0.62      | 0.62         | 1.00   | 1.00   | 1        | 2        | 0      | 98199.00 | 4.00 | 3.00 | 4    | 4     | 3.00        | 1.00    | 1.00    | 1.00    | 0.00     | 0.00    | 0.00  | 0   | 1.00  | 1.00  | 0.00  | 1.00          |       |       |           | 0.00  | 0.00  | 0.00  | 0.00    |       |       | 1.00  | 1.00  | 0   | 0.00      | 2.00           | 2.00            | 1.00           | 0.00         | 2.00     |          | 1.00    | 1.00    | 0.00    | 0.00    | 0.00    | 0.00    | 0.00    | 0.00    | 0            | 0.00        | 0.00    | 0.00      | 0.00          |             | 3.00      | 1.00    | 1.00         | 1.00                | 3.00    | 3.00  | 0.00    | 0.00    | 0.00    | 1.00    | 0.00    | 0.00     | 0.00    | 0.00    | 0.00    | 0.00    |             | 1         | 2.00   | 2     | 1         |          | 4.00  | 4.00  |             |         | -2.00   | -2.00   | -2.00   | -2.00   | -2.00   | -2.00   | -2.00   | -2.00   | -2.00   |          |                |                                                                      | 1         | -2.00     |       | 0.00   | 0.00   | 1.00   | 0.00   | 0.00   | 0.00   | 0.00   | 0.00   | 0.00   | 1.00    | 1.00    | 3.00    | 2.00    | 1.00    | 1.00    | 5.00   | 5.00   | 0.00   | 3.00       | 0    | 0    | 1    | 0    | 0    | 0    | 0    | 0    | 0    | 1     | 1     |                |              |              |           |            | 3.00  | 2.00  | 1.00  |            | 1.00  | 5    | 5    | -1   | 3.00      | 1.00  | 1.00  | 0.00  | 0.00  | 0.00  | 0.00  | 1.00  | 1.00  | 0.00  |        |                                        | 1       | 0.00     | 0.00     | 0.00     | 8.00  | 8.00  | 8.00  | 8.00  | 0.00  | 8.00  | 8.00  |             | 8.00       | 8.00       | 1       | 8.00     | 8.00     | 8.00     | 8.00     | 8.00     | -9.00  | -9.00  | -1.00    | -1.00    | -1.00    | -1.00    |           |                                                                                                                                                                                                       | 1          | -1.00       | -9.00       | -1.00       | -1.00       | -1.00       | -1.00    | -1     |                                                                                                                                                                                         |           | -1        | -1       | -1       | -1      | -1          | -1      | -1       | -999.00 | -1       | -1     | -1     | -1        | -1         | -1        | -1      | -1         | -1            | -1      | -1         | -1     | -1           | -1        | -1      | -1         | -1        | -1     | -1     | -1     |           | 1          | -1.00  | 1     |              |                                                                         | 1.00    | 0.00    | 0.00    | 0.00    | 0.00    | 0.00    | 0.00    | 0.00    | 0.00    | 0.00     | 0.00     | 0.00     | 0.00     | 0.00       | 0.00       | 0.00       | 0.00       | 0.00       | 0.00       | 0.00       | 0.00       | 1.00      | 1   |            |              |            |            |         |              |              |           |          |               |           |         |             |          | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 1.00     | 0.00      | 0.00      | 0.00      | 1.00           |              | 1          | 0.00        | 0.00        | 0.00        | 0.00        | 0.00      | 6.00   | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 1.00     | 0.00     |           |              | 1          | 1.00    | 1.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     |                                           | 1          | 0.00        | 0.00        | 0.00        | 0.00        | 0.00        | 0.00        | 0.00        | 0.00        | 0.00        | 0.00         |         | 8.00     | 8.00     | 8.00     | 8.00     | 8.00     | 8.00     | 8.00     |          |              |            |            |            |               |                     | 1            | 8.00        | 8.00        | 8.00        | 8.00        | 8.00        | 8.00        | 0.00     | 0.00      | -1.00 |            | 1        | 0.00      | 8.00     | 7.00 | 9.00 |        |        | I WOULDN'T KNOW.                                                                                                                                      | 1      | 0           | 0         | 0         | 0         | 0        | 0         | 0         | 0         | 0          | 0           | 0         | 0           | 0           | 0       | 0             | 0         | 0          | 0       | 0         | 0          | 0            | 0           | 0         | 0         | 0          | 0        | 0           | 0       | 0           | 0           | 0           | 3    | 0    | -8   | 1    |            | 3      |        |         | 3        | 3     | 3.00     | 0.00       | 0.00     | 1.00     | 0.00     | 1    | 0.00    | 1.00    | 0.00    | 1.00   |         |         |         |         |         | 0    | 0.00 | 1        | 18      | 0.84      | 0.84 | 0.78       | 0.66 | 0.98   | 0.65 | 0.95       | 0.62 |            |      | 
| 2          | 0.67      | 0.67         | 1.00   | 1.00   | 1        | 2        | 1      | 98125.00 | 3.00 | 3.00 | 4    | 7     | 3.00        | 1.00    | 1.00    | 1.00    | 1.00     | 1.00    | 1.00  | 0   | 1.00  | 1.00  | 0.00  | 1.00          |       |       |           | 0.00  | 0.00  | 0.00  | 0.00    |       |       | 1.00  | 1.00  | 1   | 1.00      | 3.00           | 2.00            | 1.00           | 0.00         | 4.00     |          | 1.00    | 1.00    | 0.00    | 0.00    | 0.00    | 1.00    | 1.00    | 0.00    | 0            | 0.00        | 0.00    | 0.00      | 0.00          |             | 2.00      | 1.00    | 1.00         | 1.00                | 2.00    | 2.00  | 0.00    | 1.00    | 0.00    | 0.00    | 0.00    | 0.00     | 0.00    | 0.00    | 0.00    | 0.00    |             | 1         | 1.00   | 1     | 1         |          | 2.00  | 2.00  |             |         | -2.00   | -2.00   | -2.00   | -2.00   | -2.00   | -2.00   | -2.00   | -2.00   | -2.00   |          |                |                                                                      | 1         | -2.00     |       | 1.00   | 1.00   | 1.00   | 1.00   | 0.00   | 0.00   | 1.00   | 1.00   | 1.00   | 0.00    | 0.00    | 3.00    | 1.00    | 0.00    | 1.00    | 5.00   | 5.00   | 5.00   | 7.00       | 1    | 1    | 1    | 1    | 0    | 0    | 1    | 1    | 1    | 0     | 0     |                |              |              |           |            | 3.00  | 1.00  | 0.00  |            | 1.00  | 5    | 5    | 5    |           | 0.00  | -1.00 | -1.00 | -1.00 | -1.00 | -1.00 | -1.00 | -1.00 | -1.00 |        |                                        | 1       | -1.00    | -1.00    | -1.00    | 0.00  | 1.00  | 0.00  | 0.00  |       | 0.00  | 0.00  |             | 0.00       | 0.00       | 1       | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 2.00   | 3.00   | 1.00     | 1.00     | 1.00     | 0.00     |           | POOR CUSTOMER SERVICE.                                                                                                                                                                                | 56         | 0.00        | 3.00        | 0.00        | 0.00        | 1.00        | 0.00     | 3      | NOTHING SPRINGS TO MIND.                                                                                                                                                                | 0         | 0         | 0        | 0        | 0       | 0           | 0       | 0        | -999.00 | 1        | 0      | 0      | 0         | 0          | 0         | 0       | 0          | 0             | 0       | 0          | 0      | 0            | 0         | 0       | 0          | 0         | 0      | 1      | 3      |           | 1          | 3.00   | -1    |              | MAINLY BECAUSE MY KIDS WILL BE MOVING OUT AND I'M NOT A BIG USER OF IT. | 0.00    | 0.00    | 0.00    | 0.00    | 0.00    | 0.00    | 0.00    | 0.00    | 1.00    | 0.00     | 0.00     | 0.00     | 0.00     | 0.00       | 0.00       | 0.00       | 0.00       | 0.00       | 0.00       | 0.00       | 0.00       | 1.00      | 1   |            |              |            |            |         |              |              |           |          |               |           |         |             |          | 0.00     | 1.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00      | 0.00      | 0.00      | 0.00           |              | 1          | 0.00        | 0.00        | 0.00        | 0.00        | 0.00      | 1.00   | 1.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     |           |              | 1          | 1.00    | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 1.00     | PRETTY MUCH DON'T CALL ME, I'LL CALL YOU. | 51         | 0.00        | 0.00        | 0.00        | 0.00        | 0.00        | 0.00        | 0.00        | 0.00        | 0.00        | 0.00         | 2.00    | 0.00     | 1.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     |          | 1.00         | 0.00       | 1.00       | 1.00       | 0.00          | TV ALERTS           | 66           | 0.00        | 0.00        | 0.00        | 0.00        | 1.00        | 0.00        | 1.00     | 3.00      | 2.00  |            | 1        | 0.00      | 8.00     | 7.00 | 9.00 |        |        | NOTHING                                                                                                                                               | 0      | 1           | 0         | 0         | 0         | 0        | 0         | 0         | 0         | 0          | 0           | 0         | 0           | 0           | 0       | 0             | 0         | 0          | 0       | 0         | 0          | 0            | 0           | 0         | 0         | 0          | 0        | 0           | 0       | 0           | 0           | 0           | 4    | 1    | 0    | 1    |            | 3      |        |         | 3        | 3     | 3.00     | 0.00       | 0.00     | 1.00     | 0.00     | 1    | 1.00    | 0.00    | 0.00    | 1.00   |         |         |         |         |         | 0    | 0.00 | 1        | 17      | 0.84      | 0.84 | 0.84       | 0.71 | 0.99   | 0.71 | 0.95       | 0.67 |            |      | 
| 3          | 0.67      | 0.67         | 1.00   | 1.00   | 1        | 2        | 0      | 98116.00 | 3.00 | 3.00 | 4    | 7     | 2.00        | 1.00    | 1.00    | 1.00    | 0.00     | 0.00    | 0.00  | 0   | 0.00  | 1.00  | 0.00  | 1.00          |       |       |           | 0.00  | 0.00  | 0.00  | 0.00    |       |       | 1.00  | 1.00  | 0   | 0.00      | 1.00           | 1.00            | 1.00           |              | 2.00     |          | 1.00    | 1.00    | 0.00    | 0.00    | 0.00    | 0.00    | 0.00    | 0.00    | 0            | 0.00        | 0.00    | 0.00      | 0.00          |             | 6.00      | 1.00    | 0.00         | 1.00                | 3.00    | 4.00  | 0.00    | 0.00    | 0.00    | 0.00    | 1.00    | 0.00     | 0.00    | 0.00    | 0.00    | 0.00    |             | 1         | 1.00   | 1     | 1         |          | 9.00  | 3.00  |             |         | -2.00   | -2.00   | -2.00   | -2.00   | -2.00   | -2.00   | -2.00   | -2.00   | -2.00   |          |                |                                                                      | 1         | -2.00     |       | 1.00   | 0.00   | 1.00   | 1.00   | 0.00   | 1.00   | 0.00   | 0.00   | 1.00   | 1.00    | 1.00    | 3.00    | 2.00    | 0.00    | 0.00    | 5.00   | 5.00   | 0.00   | 7.00       | 1    | 0    | 1    | 1    | 0    | 1    | 0    | 0    | 1    | 1     | 1     |                |              |              |           |            | 3.00  | 2.00  | 0.00  |            | 0.00  | 5    | 5    | -1   |           | 9.00  | -1.00 | -1.00 | -1.00 | -1.00 | -1.00 | -1.00 | -1.00 | -1.00 |        |                                        | 1       | -1.00    | -1.00    | -1.00    | 1.00  | 0.00  | 0.00  | 0.00  |       | 0.00  | 0.00  |             | 0.00       | 0.00       | 1       | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | -9.00  | -9.00  | -1.00    | -1.00    | -1.00    | -1.00    |           |                                                                                                                                                                                                       | 1          | -1.00       | -9.00       | -1.00       | -1.00       | -1.00       | -1.00    | -1     |                                                                                                                                                                                         |           | -1        | -1       | -1       | -1      | -1          | -1      | -1       | -999.00 | -1       | -1     | -1     | -1        | -1         | -1        | -1      | -1         | -1            | -1      | -1         | -1     | -1           | -1        | -1      | -1         | -1        | -1     | -1     | -1     |           | 1          | -1.00  | 0     |              |                                                                         | 0.00    | 0.00    | 0.00    | 0.00    | 0.00    | 0.00    | 0.00    | 0.00    | 1.00    | 0.00     | 0.00     | 0.00     | 0.00     | 0.00       | 0.00       | 0.00       | 0.00       | 0.00       | 0.00       | 0.00       | 0.00       | 1.00      | 1   |            |              |            |            |         |              |              |           |          |               |           |         |             |          | 1.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00      | 0.00      | 0.00      | 0.00           |              | 1          | 0.00        | 0.00        | 0.00        | 0.00        | 0.00      | 6.00   | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 1.00     | 0.00     |           |              | 1          | 1.00    | 1.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     |                                           | 1          | 0.00        | 0.00        | 0.00        | 0.00        | 0.00        | 0.00        | 0.00        | 0.00        | 0.00        | 0.00         | 1.00    | 0.00     | 0.00     | 0.00     | 1.00     | 0.00     | 0.00     | 0.00     |          | 1.00         | 1.00       | 1.00       | 0.00       | 0.00          |                     | 1            | 0.00        | 0.00        | 0.00        | 0.00        | 0.00        | 0.00        | 1.00     | 1.00      | -1.00 |            | 1        | 0.00      | 8.00     | 7.00 | 9.00 |        |        | I DON'T KNOW                                                                                                                                          | 1      | 0           | 0         | 0         | 0         | 0        | 0         | 0         | 0         | 0          | 0           | 0         | 0           | 0           | 0       | 0             | 0         | 0          | 0       | 0         | 0          | 0            | 0           | 0         | 0         | 0          | 0        | 0           | 0       | 0           | 0           | 0           | 4    | 2    | 1    | 1    |            | 3      |        |         | 3        | 3     | 3.00     | 0.00       | 0.00     | 1.00     | 0.00     | 1    | 0.00    | 1.00    | 0.00    | 1.00   |         |         |         |         |         | 0    | 0.00 | 1        | 18      | 0.84      | 0.84 | 0.84       | 0.71 | 0.99   | 0.71 | 0.95       | 0.67 |            |      | 
| 4          | 0.73      | 0.73         | 1.00   | 1.00   | 1        | 2        | 0      | 98126.00 | 4.00 | 3.00 | 3    | 2     | 1.00        | 1.00    | 1.00    | 1.00    | 1.00     | 1.00    | 1.00  | 0   | 1.00  | 0.00  | 0.00  | 0.00          |       |       |           | 1.00  | 0.00  | 0.00  | 1.00    |       |       | 1.00  | 1.00  | 0   | 2.00      | 2.00           | 2.00            | 1.00           |              | 2.00     |          | 1.00    | 1.00    | 0.00    | 0.00    | 0.00    | 0.00    | 0.00    | 0.00    | 0            | 0.00        | 0.00    | 0.00      | 0.00          |             | 8.00      | 1.00    | 0.00         | -9.00               |         | -9.00 | 8.00    | 8.00    | 8.00    | 8.00    | 8.00    | 8.00     | 8.00    | 8.00    | 0.00    | 0.00    |             | 1         | 2.00   | 2     | 1         |          | 3.00  | 2.00  |             |         | -2.00   | -2.00   | -2.00   | -2.00   | -2.00   | -2.00   | -2.00   | -2.00   | -2.00   |          |                |                                                                      | 1         | -2.00     |       | 1.00   | 1.00   | 1.00   | 1.00   | 1.00   | 1.00   | 0.00   | 1.00   | 1.00   | 0.00    | 1.00    | 2.00    | 2.00    | 0.00    | 1.00    | 5.00   | 5.00   | 5.00   | 9.00       | 1    | 1    | 1    | 1    | 1    | 1    | 0    | 1    | 1    | 0     | 1     |                |              |              |           |            | 2.00  | 2.00  | 0.00  |            | 1.00  | 5    | 5    | 5    | 1.00      | 1.00  | 0.00  | 0.00  | 0.00  | 0.00  | 0.00  | 0.00  | 1.00  | 0.00  |        | PURCHASES AND LOOKING UP DESTINATIONS. | 12      | 1.00     | 0.00     | 0.00     | 0.00  | 1.00  | 0.00  | 0.00  | 0.00  | 0.00  | 0.00  |             | 0.00       | 0.00       | 1       | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 2.00   | 2.00   | 1.00     | 0.00     | 1.00     | 1.00     |           | WE KEEP WANTING TO UPGRADE SERVICE AND WE HAVE TO KEEP ADDING BOXES AND CALL THEM BACK AND GIVE THEM NUMBER TO MY BOX AND LET THEM ACTIVATE. THIS IS DUE TO THEM HAVING ABILITY TO SCRAMBLE CHANNELS. | 97         | 0.00        | 4.00        | 0.00        | 0.00        | 1.00        | 0.00     | 4      | TBS, DISCOVERY, HISTORY CHANNEL, SCIENCE                                                                                                                                                | 0         | 0         | 0        | 0        | 0       | 0           | 0       | 0        | -999.00 | 0        | 0      | 0      | 0         | 0          | 0         | 1       | 0          | 0             | 0       | 0          | 1      | 1            | 0         | 0       | 0          | 0         | 0      | 1      | 2      |           | 1          | 3.00   | -1    |              | UPGRADES THAT I'M FORCED TO DO.                                         | 0.00    | 0.00    | 0.00    | 0.00    | 0.00    | 0.00    | 1.00    | 0.00    | 0.00    | 0.00     | 0.00     | 0.00     | 1.00     | 0.00       | 0.00       | 0.00       | 0.00       | 0.00       | 0.00       | 0.00       | 0.00       | 1.00      | 0   |            |              |            |            |         |              |              |           |          |               |           |         |             |          | 0.00     | 0.00     | 0.00     | 1.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00      | 0.00      | 0.00      | 1.00           |              | 1          | 0.00        | 0.00        | 0.00        | 0.00        | 0.00      | 1.00   | 1.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     |           |              | 1          | 2.00    | 1.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | NEWSLETTER                                | 40         | 0.00        | 0.00        | 0.00        | 1.00        | 0.00        | 0.00        | 0.00        | 0.00        | 0.00        | 0.00         | 1.00    | 0.00     | 0.00     | 0.00     | 1.00     | 0.00     | 0.00     | 0.00     |          | 1.00         | 1.00       | 1.00       | 0.00       | 0.00          |                     | 1            | 0.00        | 0.00        | 0.00        | 0.00        | 0.00        | 0.00        | 1.00     | 1.00      | 8.00  |            | 1        | 0.00      | 8.00     | 7.00 | 9.00 |        |        | IF THEY'RE BULLETINS THEN I WOULD KNOW TO GO TO THEIR WEBSITE LIKE EMERGENCY BULLETINS. THE PARKS DEPARTMENT COMMUNITY PROGRAMS I CAN TAKE A LOOK AT. | 0      | 0           | 0         | 0         | 0         | 0        | 0         | 0         | 1         | 0          | 0           | 0         | 0           | 1           | 0       | 0             | 0         | 0          | 0       | 0         | 0          | 0            | 0           | 0         | 0         | 0          | 0        | 0           | 0       | 0           | 0           | 0           | 2    | 0    | -8   | 1    |            | 3      |        |         | 3        | 3     | 3.00     | 0.00       | 0.00     | 1.00     | 0.00     | 0    |         |         |         |        | 0.00    | 0.00    | 0.00    | 1.00    | 0.00    |      | 0.00 | 1        | 21      | 1.18      | 1.18 | 0.78       | 0.92 | 0.83   | 0.76 | 0.95       | 0.73 |            |      | 
| 2557575257 | 0.00      | 0.00         | 2.00   |        |          |          | 8      | -9.00    | 9.00 | 9.00 | 9    | 9     | -9.00       | 8.00    | 9.00    | 9.00    | 8.00     | -999.00 | 9.00  |     | 8.00  | 8.00  | 8.00  | 8.00          |       |       |           |       |       |       | 8.00    |       |       | 8.00  | 8.00  | 8   |           | 0.00           | 0.00            | 0.00           |              |          |          |         |         |         |         |         |         |         |         |              |             |         |           |               |             | 0.00      | 0.00    | 0.00         | 0.00                | 0.00    | 0.00  | 0.00    | 0.00    | 0.00    | 0.00    | 0.00    | 0.00     | 0.00    | 0.00    | 0.00    | 0.00    |             |           | -1.00  | -1    |           |          | 9.00  | 8.00  |             |         | 8.00    | 8.00    | 8.00    | 8.00    | 8.00    | 8.00    | 8.00    | 8.00    | 8.00    |          |                |                                                                      | 1         | -9.00     |       | 8.00   | 8.00   | 8.00   | 8.00   | 8.00   | 8.00   | 8.00   | 8.00   | 8.00   | 8.00    | 8.00    | 8.00    | 8.00    | 8.00    | 8.00    | 8.00   | 8.00   | 8.00   | 0.00       | 8    | 8    | 8    | 8    | 8    | 8    | 8    | 8    | 8    | 8     | 8     |                |              |              |           |            | 8.00  | 8.00  | 8.00  |            | 8.00  | 8    | 8    | 8    |           | 9.00  | 8.00  | 8.00  | 8.00  | 8.00  | 8.00  | 8.00  | 8.00  | 8.00  |        |                                        |         |          |          |          | 8.00  | 8.00  | 8.00  | 8.00  | 0.00  | 8.00  | 8.00  |             | 8.00       |            |         |          |          |          |          |          | -9.00  | -9.00  | -1.00    | -1.00    | -1.00    | -1.00    |           |                                                                                                                                                                                                       | 1          |             | -9.00       |             |             |             | -1.00    | -1     |                                                                                                                                                                                         |           | -1        | -1       | -1       | -1      | -1          | -1      | -1       | -999.00 | -1       | -999   | -999   | -999      | -999       | -999      | -999    | -999       | -999          | -999    | -999       | -999   | -999         | -999      | -999    | -999       | -999      | 8      | 8      | -1     |           | 1          | -1.00  | -1    |              |                                                                         | 8.00    | 8.00    | 8.00    | 8.00    | 8.00    | 8.00    | 8.00    | 8.00    | 8.00    | 8.00     | 8.00     |          |          |            |            |            |            |            |            |            |            |           | 8   |            |              |            |            |         |              |              |           |          |               |           |         | 1.00        |          | 8.00     | 8.00     | 8.00     | 8.00     | 8.00     | 8.00     | 8.00     | 8.00     | 8.00     | 8.00      |           |           |                |              | 1          |             |             |             |             |           |        | 9.00     | 9.00     | 9.00     | 9.00     | 9.00     | 9.00     |          |           |              | 1          |         | 8.00     | 8.00     | 8.00     | 8.00     | 8.00     | 8.00     | 8.00     | 8.00     | 8.00     | 8.00     |                                           | 1          |             |             |             |             |             |             |             |             |             |              |         | 8.00     | 8.00     | 8.00     | 8.00     | 8.00     | 8.00     | 8.00     |          |              |            |            |            |               |                     | 1            | 8.00        | 8.00        | 8.00        | 8.00        | 8.00        | 8.00        | 8.00     |           | 8.00  |            |          | 8.00      | 8.00     | 7.00 | 9.00 |        | 1      |                                                                                                                                                       |        |             |           |           |           |          |           |           |           |            |             |           |             |             |         |               |           |            |         |           |            |              |             |           |           |            |          |             |         |             |             |             |      | -9   |      |      |            |        |        |         |          |       | 9.00     | 0.00       | 0.00     | 0.00     | 0.00     |      |         |         |         |        |         |         |         |         |         |      | 0.00 |          |         | 1.00      | 0.00 | 1.00       | 0.00 | 1.00   | 0.00 | 1.00       | 0.00 |            | 0.00 | 
| 5          | 0.82      | 0.82         | 1.00   | 1.00   | 1        | 2        | 0      | 98102.00 | 4.00 | 3.00 | 3    | 1     | 2.00        | 1.00    | 1.00    | 1.00    | 1.00     | 1.00    | 1.00  | 0   | 0.00  | 1.00  | 0.00  | 1.00          |       |       |           | 0.00  | 0.00  | 0.00  | 0.00    |       |       | 0.00  | 1.00  | 0   | 0.00      | 1.00           | 1.00            | 1.00           | 0.00         | 1.00     |          | 1.00    | 0.00    | 0.00    | 0.00    | 0.00    | 0.00    | 0.00    | 0.00    | 0            | 0.00        | 0.00    | 0.00      | 0.00          |             | 1.00      | 1.00    | 1.00         | 1.00                | 1.00    | 1.00  | 1.00    | 0.00    | 0.00    | 0.00    | 0.00    | 0.00     | 0.00    | 0.00    | 0.00    | 0.00    |             | 1         | 2.00   | 2     | 1         |          | 3.00  | 1.00  |             |         | -2.00   | -2.00   | -2.00   | -2.00   | -2.00   | -2.00   | -2.00   | -2.00   | -2.00   |          |                |                                                                      | 1         | -2.00     |       | 1.00   | 0.00   | 0.00   | 0.00   | 1.00   | 0.00   | 0.00   | 1.00   | 1.00   | 1.00    | 0.00    | 3.00    | 2.00    | 0.00    | 3.00    | 5.00   | 5.00   | 0.00   | 5.00       | 1    | 0    | 0    | 0    | 1    | 0    | 0    | 1    | 1    | 1     | 0     |                |              |              |           |            | 3.00  | 2.00  | 0.00  |            | 3.00  | 5    | 5    | -1   | 4.00      | 1.00  | 1.00  | 0.00  | 0.00  | 1.00  | 0.00  | 1.00  | 1.00  | 0.00  |        |                                        | 1       | 0.00     | 0.00     | 0.00     | 0.00  | 0.00  | 0.00  | 0.00  | 1.00  | 0.00  | 0.00  | POLITICS    | 1.00       | 0.00       | 58      | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 2.00   | 3.00   | 1.00     | 0.00     | 1.00     | 0.00     |           | VERY BAD RECEPTION AND GETTING THEM TO GET SOMETHING DONE.                                                                                                                                            | 93         | 0.00        | 2.00        | 0.00        | 0.00        | 1.00        | 0.00     | 2      | EDUCATIONAL, SCIENCE, DRAMA                                                                                                                                                             | 0         | 0         | 1        | 0        | 0       | 0           | 0       | 0        | -999.00 | 0        | 0      | 0      | 0         | 0          | 0         | 1       | 0          | 0             | 0       | 0          | 0      | 0            | 0         | 0       | 0          | 1         | 1      | 1      | 1      |           | 1          | 1.00   | -1    |              |                                                                         | -2.00   | -2.00   | -2.00   | -2.00   | -2.00   | -2.00   | -2.00   | -2.00   | -2.00   | -2.00    | -2.00    |          | -2.00    | -2.00      | -2.00      | -2.00      | -2.00      | -2.00      | -2.00      | -2.00      | -2.00      | 0.00      | 1   |            |              |            |            |         |              |              |           |          |               |           |         |             |          | 1.00     | 1.00     | 0.00     | 1.00     | 0.00     | 0.00     | 0.00     | 0.00     | 1.00     | 0.00      | 0.00      | 0.00      | 1.00           |              | 1          | 0.00        | 0.00        | 0.00        | 0.00        | 0.00      | 1.00   | 1.00     | 0.00     | 0.00     | 0.00     | 0.00     | 1.00     | 0.00     |           |              | 1          | 3.00    | 1.00     | 0.00     | 0.00     | 0.00     | 0.00     | 1.00     | 0.00     | 1.00     | 0.00     | 0.00     |                                           | 1          | 0.00        | 0.00        | 0.00        | 0.00        | 0.00        | 0.00        | 0.00        | 0.00        | 0.00        | 0.00         |         | 8.00     | 8.00     | 8.00     | 8.00     | 8.00     | 8.00     | 8.00     |          |              |            |            |            |               |                     | 1            | 8.00        | 8.00        | 8.00        | 8.00        | 8.00        | 8.00        | 1.00     | 3.00      | -1.00 |            | 1        | 1.00      | 3.00     | 2.00 | 2.00 |        |        | HELPFUL INFORMATION THAT TEACHES ABOUT THE ENVIRONMENT. ENVIRONMENTAL SHOWS.                                                                          | 0      | 0           | 0         | 0         | 0         | 0        | 0         | 0         | 0         | 0          | 0           | 0         | 0           | 0           | 0       | 0             | 0         | 0          | 0       | 0         | 0          | 0            | 0           | 1         | 0         | 0          | 0        | 0           | 0       | 0           | 0           | 0           | 1    | 0    | -8   | 1    |            | 3      |        |         | 3        | 3     | 3.00     | 0.00       | 0.00     | 1.00     | 0.00     | 0    |         |         |         |        | 0.00    | 0.00    | 0.00    | 0.00    | 1.00    | 3    | 1.00 | 1        | 29      | 1.18      | 1.18 | 0.78       | 0.92 | 0.93   | 0.86 | 0.95       | 0.82 |            |      | 
| 6          | 0.57      | 0.57         | 1.00   | 1.00   | 1        | 2        | 0      | 98117.00 | 5.00 | 3.00 | 4    | 6     | 2.00        | 1.00    | 1.00    | 1.00    | 1.00     | 1.00    | 1.00  | 0   | 0.00  | 1.00  | 0.00  | 1.00          |       |       |           | 0.00  | 0.00  | 0.00  | 0.00    |       |       | 1.00  | 1.00  | 1   | 1.00      | 2.00           | 2.00            | 1.00           | 0.00         | 1.00     |          | 1.00    | 0.00    | 0.00    | 0.00    | 0.00    | 0.00    | 0.00    | 0.00    | 0            | 0.00        | 0.00    | 0.00      | 0.00          |             | 1.00      | 1.00    | 1.00         | 1.00                | 1.00    | 1.00  | 1.00    | 0.00    | 0.00    | 0.00    | 0.00    | 0.00     | 0.00    | 0.00    | 0.00    | 0.00    |             | 1         | 2.00   | 2     | 1         |          | 3.00  | 2.00  |             |         | -2.00   | -2.00   | -2.00   | -2.00   | -2.00   | -2.00   | -2.00   | -2.00   | -2.00   |          |                |                                                                      | 1         | -2.00     |       | 0.00   | 0.00   | 1.00   | 0.00   | 0.00   | 0.00   | 0.00   | 0.00   | 0.00   | 0.00    | 0.00    | 2.00    | 0.00    | 0.00    | 0.00    | 3.00   | 2.00   | 1.00   | 1.00       | 0    | 0    | 1    | 0    | 0    | 0    | 0    | 0    | 0    | 0     | 0     |                |              |              |           |            | 2.00  | 0.00  | 0.00  |            | 0.00  | 3    | 2    | 1    |           | 0.00  | -1.00 | -1.00 | -1.00 | -1.00 | -1.00 | -1.00 | -1.00 | -1.00 |        |                                        | 1       | -1.00    | -1.00    | -1.00    | 0.00  | 0.00  | 1.00  | 0.00  |       | 0.00  | 0.00  | IN PERSON   | 0.00       | 0.00       | 34      | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 2.00   | 4.00   | 0.00     | 0.00     | 0.00     | 0.00     |           |                                                                                                                                                                                                       | 1          | 0.00        | 3.00        | 0.00        | 0.00        | 0.00        | 1.00     | 3      | NEWS, GOOD DRAMA, TECHNICAL, CRIME SHOWS                                                                                                                                                | 0         | 0         | 0        | 0        | 0       | 0           | 0       | 1        | -999.00 | 0        | 0      | 0      | 1         | 0          | 0         | 0       | 0          | 0             | 0       | 0          | 0      | 0            | 0         | 0       | 0          | 1         | 8      | 0      | 2      |           | 1          | 3.00   | -1    |              |                                                                         | 1.00    | 0.00    | 0.00    | 0.00    | 0.00    | 0.00    | 0.00    | 0.00    | 0.00    | 0.00     | 0.00     | 0.00     | 0.00     | 0.00       | 0.00       | 0.00       | 0.00       | 0.00       | 0.00       | 0.00       | 0.00       | 1.00      | 0   |            |              |            |            |         |              |              |           |          |               |           |         |             |          | 1.00     | 1.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 1.00     | 0.00      | 0.00      | 0.00      | 1.00           |              | 1          | 0.00        | 0.00        | 0.00        | 0.00        | 0.00      | 6.00   | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 1.00     | 0.00     |           |              | 1          | 2.00    | 1.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 1.00     | 0.00     | 0.00     |                                           | 1          | 0.00        | 0.00        | 0.00        | 0.00        | 0.00        | 0.00        | 0.00        | 0.00        | 0.00        | 0.00         | 1.00    | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     |          | 0.00         | 0.00       | 0.00       | 0.00       | 1.00          | PERSONAL EXPERIENCE | 35           | 0.00        | 1.00        | 0.00        | 0.00        | 0.00        | 0.00        | 1.00     | 1.00      | 8.00  |            | 1        | 0.00      | 8.00     | 7.00 | 9.00 |        |        | NEWSPAPER                                                                                                                                             |        |             |           |           |           |          |           |           |           |            |             |           |             |             |         |               |           |            |         |           |            |              |             |           |           |            |          |             |         |             |             | 1           | 1    | 0    | -8   | 1    |            | 3      |        |         | 3        | 3     | 3.00     | 0.00       | 0.00     | 1.00     | 0.00     | 1    | 1.00    | 0.00    | 0.00    | 1.00   |         |         |         |         |         | 0    | 0.00 | 1        | 28      | 0.84      | 0.84 | 0.72       | 0.61 | 0.98   | 0.60 | 0.95       | 0.57 |            |      | 
| 7          | 2.02      | 2.02         | 1.00   | 1.00   | 1        | 2        | 0      | 98112.00 | 4.00 | 7.00 | 4    | 3     | 2.00        | 1.00    | 1.00    | 1.00    | 1.00     | 1.00    | 1.00  | 0   | 0.00  | 0.00  | 1.00  | 1.00          |       |       |           | 0.00  | 0.00  | 0.00  | 0.00    |       |       | 1.00  | 1.00  | 0   | 0.00      | 1.00           | 1.00            | 1.00           | 0.00         | 1.00     |          | 1.00    | 0.00    | 0.00    | 0.00    | 0.00    | 0.00    | 0.00    | 0.00    | 0            | 0.00        | 0.00    | 0.00      | 0.00          |             | 1.00      | 1.00    | 1.00         | 1.00                | 1.00    | 1.00  | 1.00    | 0.00    | 0.00    | 0.00    | 0.00    | 0.00     | 0.00    | 0.00    | 0.00    | 0.00    |             | 1         | 3.00   | 5     | 1         |          | 3.00  | 3.00  |             |         | -2.00   | -2.00   | -2.00   | -2.00   | -2.00   | -2.00   | -2.00   | -2.00   | -2.00   |          |                |                                                                      | 1         | -2.00     |       | 1.00   | 0.00   | 1.00   | 1.00   | 1.00   | 0.00   | 0.00   | 0.00   | 0.00   | 0.00    | 0.00    | 1.00    | 1.00    | 1.00    | 0.00    | 5.00   | 3.00   | 0.00   | 4.00       | 1    | 0    | 1    | 1    | 1    | 0    | 0    | 0    | 0    | 0     | 0     |                |              |              |           |            | 1.00  | 1.00  | 1.00  |            | 0.00  | 5    | 3    | -1   |           | 0.00  | -1.00 | -1.00 | -1.00 | -1.00 | -1.00 | -1.00 | -1.00 | -1.00 |        |                                        | 1       | -1.00    | -1.00    | -1.00    | 0.00  | 1.00  | 0.00  | 0.00  |       | 0.00  | 0.00  |             | 0.00       | 0.00       | 1       | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 1.00   | 3.00   | 1.00     | 0.00     | 1.00     | 1.00     |           | I HAVE A REMOTE I CAN'T GET REPLACED. THEY TELL ME IT'S 5 MINUTES AWAY AND I DON'T DRIVE. I TAKE THE BUS AND IT'S VERY INCONVENIENT. I DON'T LIKE THEIR ATTITUDE. IT'S VERY CONDESCENDING.            | 32         | 0.00        | 4.00        | 0.00        | 0.00        | 1.00        | 0.00     | 4      | I LIKE THE SCIENCE AND THE HISTORY.                                                                                                                                                     | 0         | 0         | 0        | 0        | 0       | 0           | 0       | 0        | -999.00 | 0        | 0      | 0      | 0         | 0          | 0         | 1       | 0          | 0             | 0       | 0          | 1      | 0            | 0         | 0       | 0          | 0         | 1      | 1      | 1      |           | 1          | 2.00   | -1    |              |                                                                         | -2.00   | -2.00   | -2.00   | -2.00   | -2.00   | -2.00   | -2.00   | -2.00   | -2.00   | -2.00    | -2.00    |          | -2.00    | -2.00      | -2.00      | -2.00      | -2.00      | -2.00      | -2.00      | -2.00      | -2.00      | 0.00      | 1   |            |              |            |            |         |              |              |           |          |               |           |         |             |          | 0.00     | 0.00     | 1.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00      | 0.00      | 0.00      | 1.00           |              | 1          | 0.00        | 0.00        | 0.00        | 0.00        | 0.00      | 1.00   | 1.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     |           |              | 1          | 1.00    | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 1.00     | 0.00     |                                           | 1          | 0.00        | 0.00        | 0.00        | 0.00        | 0.00        | 0.00        | 0.00        | 0.00        | 0.00        | 0.00         | 1.00    | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     |          | 0.00         | 0.00       | 0.00       | 0.00       | 0.00          | TV                  | 65           | 0.00        | 0.00        | 0.00        | 0.00        | 1.00        | 0.00        | 0.00     | 0.00      | -1.00 |            | 1        | 1.00      | 1.00     | 1.00 | 2.00 |        |        | CABLE, VARIOUS ISSUES LIKE POD BUILDING. GETTING RID OF PARKING IN SEATTLE. I DON'T LIKE THE MAYOR.                                                   | 0      | 0           | 0         | 0         | 0         | 0        | 0         | 0         | 0         | 0          | 1           | 0         | 0           | 0           | 0       | 0             | 0         | 0          | 0       | 0         | 0          | 0            | 0           | 0         | 0         | 0          | 0        | 0           | 0       | 0           | 0           | 0           | 2    | 0    | -8   | 1    |            | 5      | 3      |         | 7        | 7     | 8.00     | 0.00       | 0.00     | 0.00     | 0.00     | 1    | 0.00    | 1.00    | 0.00    | 1.00   |         |         |         |         |         | 0    | 0.00 | 1        | 18      | 0.84      | 0.84 | 0.78       | 0.66 | 1.06   | 0.70 | 2.86       | 2.02 |            |      | 
| 8          | 0.54      | 0.54         | 1.00   | 1.00   | 1        | 2        | 1      | 98115.00 | 5.00 | 3.00 | 4    | 1     | 0.00        | 0.00    | 0.00    | 0.00    | 1.00     | 1.00    | 1.00  | 0   | 0.00  | 0.00  | 0.00  | 0.00          |       |       |           | -1.00 | -1.00 | -1.00 | -1.00   |       |       | 0.00  | 1.00  | 0   | -1.00     | 0.00           | 0.00            | 0.00           |              |          |          | -1.00   | -1.00   | -1.00   | -1.00   | -1.00   | -1.00   | -1.00   | -1.00   | -1           | -1.00       | -1.00   | -1.00     | -1.00         |             | -1.00     | 0.00    | 0.00         | 0.00                | 0.00    | 0.00  | -1.00   | -1.00   | -1.00   | -1.00   | -1.00   | -1.00    | -1.00   | -1.00   | 0.00    | 0.00    |             | 1         | -1.00  | -1    | 1         |          | 3.00  | 2.00  |             | 1       | 0.00    | 0.00    | 1.00    | 0.00    | 0.00    | 0.00    | 0.00    | 0.00    | 0.00    | 0.00     | 0.00           | JUST BECAUSE THE REST OF THE PEOPLE HAVE IT, DOESN'T MEAN I HAVE TO. | 31        | 1.00      | 20    | 0.00   | 0.00   | 0.00   | 0.00   | 0.00   | 0.00   | 0.00   | 0.00   | 0.00   | 0.00    | 0.00    | 0.00    | 0.00    | 0.00    | 0.00    | 0.00   | 0.00   | 0.00   | 0.00       | -3   | -3   | -3   | -3   | -3   | -3   | -3   | -3   | -3   | -3    | -3    |                |              |              |           |            | -3.00 | -2.00 | -2.00 |            | -2.00 | -1   | -3   | -1   |           | -9.00 | -1.00 | -1.00 | -1.00 | -1.00 | -1.00 | -1.00 | -1.00 | -1.00 |        |                                        | 1       | -1.00    | -1.00    | -1.00    | -1.00 | -1.00 | -1.00 | -1.00 |       | -1.00 | -1.00 |             | -1.00      | -1.00      | 1       | -1.00    | -1.00    | -1.00    | -1.00    | -1.00    | 4.00   | 4.00   | 1.00     | 0.00     | 0.00     | 0.00     |           | I DON'T KNOW                                                                                                                                                                                          | 31         | 0.00        | 2.00        | 0.00        | 0.00        | 0.00        | 0.00     | 2      | I WATCH A LOT OF SPORTS, I'VE BEEN WATCHING BALL GAMES, I LIKE NEWS AND LIKE BASKETBALL, MSNBC I LIKE THAT ONE REAL WELL. MAYBE MORE SPORTS, THEY'RE GOING TO HAVE THE NCAA BASKETBALL. | 0         | 0         | 0        | 0        | 0       | 0           | 0       | 0        | -999.00 | 0        | 0      | 0      | 0         | 0          | 0         | 0       | 0          | 0             | 0       | 1          | 0      | 0            | 0         | 0       | 0          | 0         | 0      | 1      | 1      |           | 1          | 1.00   | -1    |              |                                                                         | -2.00   | -2.00   | -2.00   | -2.00   | -2.00   | -2.00   | -2.00   | -2.00   | -2.00   | -2.00    | -2.00    |          | -2.00    | -2.00      | -2.00      | -2.00      | -2.00      | -2.00      | -2.00      | -2.00      | -2.00      | 0.00      | 0   |            |              |            |            |         |              |              |           |          |               |           |         |             |          | 0.00     | 1.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00      | 0.00      | 0.00      | 0.00           |              | 1          | 0.00        | 0.00        | 0.00        | 0.00        | 0.00      | 9.00   | 8.00     | 8.00     | 8.00     | 8.00     | 8.00     | 8.00     |          |           |              | 1          | 2.00    | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 1.00     | 0.00     | THE NEWSPAPER                             | 62         | 0.00        | 0.00        | 0.00        | 0.00        | 0.00        | 0.00        | 0.00        | 1.00        | 0.00        | 0.00         | 1.00    | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     |          | 0.00         | 0.00       | 0.00       | 0.00       | 0.00          | TELEVISION          | 57           | 0.00        | 0.00        | 0.00        | 0.00        | 1.00        | 0.00        | 0.00     | 0.00      | -1.00 |            | 1        | 1.00      | 1.00     | 0.00 | 1.00 |        |        | POLITICS MAYBE, I'D KIND OF LIKE TO SEE HOW THE POLITICAL SYSTEMS RUN.                                                                                | 0      | 0           | 0         | 0         | 0         | 0        | 0         | 0         | 0         | 0          | 0           | 0         | 0           | 0           | 1       | 0             | 0         | 0          | 0       | 0         | 0          | 0            | 0           | 0         | 0         | 0          | 0        | 0           | 0       | 0           | 0           | 0           | 1    | 0    | -8   | 1    |            | 3      |        |         | 3        | 3     | 3.00     | 0.00       | 0.00     | 1.00     | 0.00     | 0    |         |         |         |        | 0.00    | 0.00    | 0.00    | 1.00    | 0.00    |      | 0.00 | 1        | 23      | 0.84      | 0.84 | 0.72       | 0.61 | 0.93   | 0.56 | 0.95       | 0.54 |            |      | 
| 10         | 0.63      | 0.63         | 1.00   | 1.00   | 1        | 2        | 1      | 98122.00 | 4.00 | 3.00 | 4    | 7     | 1.00        | 1.00    | 1.00    | 1.00    | 1.00     | 1.00    | 1.00  | 0   | 1.00  | 0.00  | 0.00  | 0.00          |       |       |           | 0.00  | 0.00  | 0.00  | 0.00    |       |       | 1.00  | 1.00  | 1   | 1.00      | 2.00           | 2.00            | 1.00           | 0.00         | 2.00     |          | 1.00    | 1.00    | 0.00    | 0.00    | 0.00    | 0.00    | 0.00    | 0.00    | 1            | 0.00        | 0.00    | 0.00      | 0.00          | HOTELS      | 1.00      | 1.00    | 1.00         | 1.00                | 1.00    | 1.00  | 1.00    | 0.00    | 0.00    | 0.00    | 0.00    | 0.00     | 0.00    | 0.00    | 0.00    | 0.00    |             | 1         | 2.00   | 2     | 1         |          | 3.00  | 4.00  |             |         | -2.00   | -2.00   | -2.00   | -2.00   | -2.00   | -2.00   | -2.00   | -2.00   | -2.00   |          |                |                                                                      | 1         | -2.00     |       | 1.00   | 0.00   | 1.00   | 1.00   | 1.00   | 0.00   | 1.00   | 1.00   | 1.00   | 0.00    | 0.00    | 3.00    | 3.00    | 2.00    | 2.00    | 5.00   | 5.00   | 5.00   | 7.00       | 1    | 0    | 1    | 1    | 1    | 0    | 1    | 1    | 1    | 0     | 0     |                |              |              |           |            | 3.00  | 3.00  | 2.00  |            | 2.00  | 5    | 5    | 5    | 2.00      | 1.00  | 0.00  | 0.00  | 0.00  | 0.00  | 0.00  | 1.00  | 1.00  | 0.00  |        |                                        | 1       | 0.00     | 0.00     | 0.00     | 0.00  | 1.00  | 0.00  | 0.00  | 0.00  | 0.00  | 0.00  | RELIABILITY | 0.00       | 0.00       | 60      | 0.00     | 0.00     | 0.00     | 1.00     | 0.00     | 3.00   | 2.00   | 1.00     | 0.00     | 0.00     | 0.00     |           | DIFFICULTY SETTING UP.                                                                                                                                                                                | 17         | 0.00        | 4.00        | 0.00        | 1.00        | 0.00        | 0.00     | 4      | A BIGGER VARIETY OF MOVIES.                                                                                                                                                             | 0         | 0         | 0        | 0        | 0       | 0           | 0       | 0        | -999.00 | 0        | 0      | 0      | 0         | 1          | 0         | 0       | 0          | 0             | 0       | 0          | 0      | 0            | 0         | 0       | 0          | 0         | 0      | 0      | 1      |           | 1          | 2.00   | -1    |              |                                                                         | -2.00   | -2.00   | -2.00   | -2.00   | -2.00   | -2.00   | -2.00   | -2.00   | -2.00   | -2.00    | -2.00    |          | -2.00    | -2.00      | -2.00      | -2.00      | -2.00      | -2.00      | -2.00      | -2.00      | -2.00      | 0.00      | 0   |            |              |            |            |         |              |              |           |          |               |           |         |             |          | 0.00     | 0.00     | 1.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00      | 0.00      | 0.00      | 1.00           |              | 1          | 0.00        | 0.00        | 0.00        | 0.00        | 0.00      | 1.00   | 1.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     |           |              | 1          | 1.00    | 1.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     |                                           | 1          | 0.00        | 0.00        | 0.00        | 0.00        | 0.00        | 0.00        | 0.00        | 0.00        | 0.00        | 0.00         | 1.00    | 0.00     | 1.00     | 0.00     | 0.00     | 0.00     | 0.00     | 0.00     |          | 1.00         | 0.00       | 1.00       | 1.00       | 0.00          |                     | 1            | 0.00        | 0.00        | 0.00        | 0.00        | 0.00        | 0.00        | 1.00     | 2.00      | 2.00  |            | 1        | 1.00      | 1.00     | 0.00 | 2.00 |        |        | RECYCLING INFORMATION, INFORMATION ABOUT CITY SOURCES.                                                                                                | 0      | 0           | 0         | 0         | 0         | 0        | 0         | 0         | 0         | 0          | 0           | 0         | 0           | 0           | 0       | 0             | 0         | 0          | 0       | 0         | 0          | 0            | 1           | 1         | 0         | 0          | 0        | 0           | 0       | 0           | 0           | 0           | 2    | 0    | -8   | 1    |            | 3      |        |         | 3        | 3     | 3.00     | 0.00       | 0.00     | 1.00     | 0.00     | 1    | 1.00    | 0.00    | 0.00    | 1.00   |         |         |         |         |         | 0    | 0.00 | 1        | 15      | 0.84      | 0.84 | 0.78       | 0.66 | 0.99   | 0.66 | 0.95       | 0.63 |            |      | 
```