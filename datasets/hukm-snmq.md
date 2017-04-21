# NYC Independent Budget Office (IBO) Capital Expenditures Since 1985

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nyc-independent-budget-office-ibo-capital-expenditures-since-1985-2664c) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/hukm-snmq) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/hukm-snmq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/hukm-snmq/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | hukm-snmq |
| Name | NYC Independent Budget Office (IBO) Capital Expenditures Since 1985 |
| Attribution | NYC Independent Budget Office (IBO) |
| Category | City Government |
| Tags | nyc independent budget office (ibo) capital expenditures since 1985, environmental protection and sanitation education, transportation services, housing and economic development |
| Created | 2014-03-03T21:55:57Z |
| Publication Date | 2014-03-06T16:15:52Z |

## Description

Annual capital expenditures, by capital budget area and agency, from FY 1985 - 2013. Source: Comprehensive Annual Financial Reports of the Comptroller

## Columns

```ls
| Included | Schema Type    | Field Name                             | Name                                   | Data Type | Render Type |
| ======== | ============== | ====================================== | ====================================== | ========= | =========== |
| Yes      | series tag     | agency_capital_expenditures_by_purpose | AGENCY CAPITAL EXPENDITURES BY PURPOSE | text      | text        |
| Yes      | series tag     | category                               | CATEGORY                               | text      | text        |
| Yes      | numeric metric | fy_2013                                | FY 2013                                | number    | number      |
| Yes      | numeric metric | fy_2012                                | FY 2012                                | number    | number      |
| Yes      | numeric metric | fy_2011                                | FY 2011                                | number    | number      |
| Yes      | numeric metric | fy_2010                                | FY 2010                                | money     | money       |
| Yes      | numeric metric | fy_2009                                | FY 2009                                | money     | money       |
| Yes      | numeric metric | fy_2008                                | FY 2008                                | money     | money       |
| Yes      | numeric metric | fy_2007                                | FY 2007                                | number    | number      |
| Yes      | numeric metric | fy_2006                                | FY 2006                                | number    | number      |
| Yes      | numeric metric | fy_2005                                | FY 2005                                | number    | number      |
| Yes      | numeric metric | fy_2004                                | FY 2004                                | number    | number      |
| Yes      | numeric metric | fy_2003                                | FY 2003                                | number    | number      |
| Yes      | numeric metric | fy_2002                                | FY 2002                                | number    | number      |
| Yes      | numeric metric | fy_2001                                | FY 2001                                | number    | number      |
| Yes      | numeric metric | fy_2000                                | FY 2000                                | number    | number      |
| Yes      | numeric metric | fy_1999                                | FY 1999                                | number    | number      |
| Yes      | numeric metric | fy_1998                                | FY 1998                                | number    | number      |
| Yes      | numeric metric | fy_1997                                | FY 1997                                | number    | number      |
| Yes      | numeric metric | fy_1996                                | FY 1996                                | number    | number      |
| Yes      | numeric metric | fy_1995                                | FY 1995                                | number    | number      |
| Yes      | numeric metric | fy_1994                                | FY 1994                                | number    | number      |
| Yes      | numeric metric | fy_1993                                | FY 1993                                | number    | number      |
| Yes      | numeric metric | fy_1992                                | FY 1992                                | number    | number      |
| Yes      | numeric metric | fy_1991                                | FY 1991                                | money     | money       |
| Yes      | numeric metric | fy_1990                                | FY 1990                                | number    | number      |
| Yes      | numeric metric | fy_1989                                | FY 1989                                | number    | number      |
| Yes      | numeric metric | fy_1988                                | FY 1988                                | number    | number      |
| Yes      | numeric metric | fy_1987                                | FY 1987                                | number    | number      |
| Yes      | numeric metric | fy_1986                                | FY 1986                                | number    | number      |
| Yes      | numeric metric | fy_1985                                | FY 1985                                | number    | number      |
```

## Time Field

```ls
Value = 1985
Format & Zone = yyyy
```

## Data Commands

```ls
series e:hukm-snmq d:1985-01-01T00:00:00.000Z t:agency_capital_expenditures_by_purpose="Department of Environmental Protection" m:fy_2001=830009738 m:fy_2000=796865009 m:fy_2005=1679394109 m:fy_2004=1630607201 m:fy_2003=1301779898 m:fy_2002=1036705764 m:fy_2008=2313038722 m:fy_2009=2700236388 m:fy_2006=1841278686 m:fy_1988=567085283 m:fy_2007=1948836326 m:fy_1989=621770158 m:fy_1986=564968375 m:fy_1987=562163938 m:fy_1985=498475715 m:fy_1992=893639535 m:fy_2013=1843947453 m:fy_1991=826139905 m:fy_1994=616392666 m:fy_1993=745534529 m:fy_2010=2625317710 m:fy_2012=2405599562 m:fy_1990=636874169 m:fy_2011=2824135363 m:fy_1999=787928245 m:fy_1995=705398608 m:fy_1996=1004251889 m:fy_1997=977555046 m:fy_1998=764767187

series e:hukm-snmq d:1985-01-01T00:00:00.000Z t:category="Sewage Collection and Treatment" m:fy_2001=465302117 m:fy_2000=485352807 m:fy_2005=1026980915 m:fy_2004=1028832860 m:fy_2003=815280838 m:fy_2002=540055147 m:fy_2008=1094743184 m:fy_2009=1342826997 m:fy_2006=1027913991 m:fy_1988=397428543 m:fy_2007=1065666287 m:fy_1989=431270960 m:fy_1986=407948120 m:fy_1987=410829792 m:fy_1985=356499516 m:fy_1992=717335346 m:fy_2013=953371696 m:fy_1991=639502160 m:fy_1994=393502317 m:fy_1993=498388858 m:fy_2010=1041023183 m:fy_2012=1195170589 m:fy_1990=455579594 m:fy_2011=1303130966 m:fy_1999=469587367 m:fy_1995=387874556 m:fy_1996=363907447 m:fy_1997=403288236 m:fy_1998=408723581

series e:hukm-snmq d:1985-01-01T00:00:00.000Z t:category="Water Supply and Distribution" m:fy_2001=290092707 m:fy_2000=243727203 m:fy_2005=567214779 m:fy_2004=503845118 m:fy_2003=377006353 m:fy_2002=424331529 m:fy_2008=1155019868 m:fy_2009=1267593992 m:fy_2006=712373453 m:fy_1988=164421240 m:fy_2007=789792849 m:fy_1989=182407125 m:fy_1986=154387007 m:fy_1987=146494129 m:fy_1985=139084929 m:fy_1992=153573632 m:fy_2013=798383306 m:fy_1991=165373668 m:fy_1994=172540323 m:fy_1993=223111287 m:fy_2010=1414683775 m:fy_2012=1041481264 m:fy_1990=169262689 m:fy_2011=1280909413 m:fy_1999=260548602 m:fy_1995=209887645 m:fy_1996=445796304 m:fy_1997=398125916 m:fy_1998=303067694
```

## Meta Commands

```ls
metric m:fy_2013 p:long l:"FY 2013" t:dataTypeName=number

metric m:fy_2012 p:long l:"FY 2012" t:dataTypeName=number

metric m:fy_2011 p:long l:"FY 2011" t:dataTypeName=number

metric m:fy_2010 p:long l:"FY 2010" t:dataTypeName=money

metric m:fy_2009 p:long l:"FY 2009" t:dataTypeName=money

metric m:fy_2008 p:long l:"FY 2008" t:dataTypeName=money

metric m:fy_2007 p:long l:"FY 2007" t:dataTypeName=number

metric m:fy_2006 p:long l:"FY 2006" t:dataTypeName=number

metric m:fy_2005 p:long l:"FY 2005" t:dataTypeName=number

metric m:fy_2004 p:long l:"FY 2004" t:dataTypeName=number

metric m:fy_2003 p:long l:"FY 2003" t:dataTypeName=number

metric m:fy_2002 p:long l:"FY 2002" t:dataTypeName=number

metric m:fy_2001 p:long l:"FY 2001" t:dataTypeName=number

metric m:fy_2000 p:long l:"FY 2000" t:dataTypeName=number

metric m:fy_1999 p:long l:"FY 1999" t:dataTypeName=number

metric m:fy_1998 p:long l:"FY 1998" t:dataTypeName=number

metric m:fy_1997 p:long l:"FY 1997" t:dataTypeName=number

metric m:fy_1996 p:long l:"FY 1996" t:dataTypeName=number

metric m:fy_1995 p:long l:"FY 1995" t:dataTypeName=number

metric m:fy_1994 p:long l:"FY 1994" t:dataTypeName=number

metric m:fy_1993 p:long l:"FY 1993" t:dataTypeName=number

metric m:fy_1992 p:long l:"FY 1992" t:dataTypeName=number

metric m:fy_1991 p:long l:"FY 1991" t:dataTypeName=money

metric m:fy_1990 p:long l:"FY 1990" t:dataTypeName=number

metric m:fy_1989 p:long l:"FY 1989" t:dataTypeName=number

metric m:fy_1988 p:long l:"FY 1988" t:dataTypeName=number

metric m:fy_1987 p:integer l:"FY 1987" t:dataTypeName=number

metric m:fy_1986 p:integer l:"FY 1986" t:dataTypeName=number

metric m:fy_1985 p:integer l:"FY 1985" t:dataTypeName=number

entity e:hukm-snmq l:"NYC Independent Budget Office (IBO) Capital Expenditures Since 1985" t:attribution="NYC Independent Budget Office (IBO)" t:url=https://data.cityofnewyork.us/api/views/hukm-snmq

property e:hukm-snmq t:meta.view v:id=hukm-snmq v:category="City Government" v:attributionLink=http://www.ibo.nyc.ny.us/ v:averageRating=0 v:name="NYC Independent Budget Office (IBO) Capital Expenditures Since 1985" v:attribution="NYC Independent Budget Office (IBO)"

property e:hukm-snmq t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:hukm-snmq t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| agency_capital_expenditures_by_purpose        | category                        | fy_2013    | fy_2012    | fy_2011    | fy_2010    | fy_2009    | fy_2008    | fy_2007    | fy_2006    | fy_2005    | fy_2004    | fy_2003    | fy_2002    | fy_2001    | fy_2000   | fy_1999   | fy_1998   | fy_1997    | fy_1996    | fy_1995   | fy_1994   | fy_1993   | fy_1992    | fy_1991   | fy_1990   | fy_1989   | fy_1988   | fy_1987   | fy_1986   | fy_1985   | 
| ============================================= | =============================== | ========== | ========== | ========== | ========== | ========== | ========== | ========== | ========== | ========== | ========== | ========== | ========== | ========== | ========= | ========= | ========= | ========== | ========== | ========= | ========= | ========= | ========== | ========= | ========= | ========= | ========= | ========= | ========= | ========= | 
| Environmental Protection and Sanitation       |                                 |            |            |            |            |            |            |            |            |            |            |            |            |            |           |           |           |            |            |           |           |           |            |           |           |           |           |           |           |           | 
| Department of Environmental Protection        |                                 | 1843947453 | 2405599562 | 2824135363 | 2625317710 | 2700236388 | 2313038722 | 1948836326 | 1841278686 | 1679394109 | 1630607201 | 1301779898 | 1036705764 | 830009738  | 796865009 | 787928245 | 764767187 | 977555046  | 1004251889 | 705398608 | 616392666 | 745534529 | 893639535  | 826139905 | 636874169 | 621770158 | 567085283 | 562163938 | 564968375 | 498475715 | 
|                                               | Sewage Collection and Treatment | 953371696  | 1195170589 | 1303130966 | 1041023183 | 1342826997 | 1094743184 | 1065666287 | 1027913991 | 1026980915 | 1028832860 | 815280838  | 540055147  | 465302117  | 485352807 | 469587367 | 408723581 | 403288236  | 363907447  | 387874556 | 393502317 | 498388858 | 717335346  | 639502160 | 455579594 | 431270960 | 397428543 | 410829792 | 407948120 | 356499516 | 
|                                               | Water Supply and Distribution   | 798383306  | 1041481264 | 1280909413 | 1414683775 | 1267593992 | 1155019868 | 789792849  | 712373453  | 567214779  | 503845118  | 377006353  | 424331529  | 290092707  | 243727203 | 260548602 | 303067694 | 398125916  | 445796304  | 209887645 | 172540323 | 223111287 | 153573632  | 165373668 | 169262689 | 182407125 | 164421240 | 146494129 | 154387007 | 139084929 | 
|                                               | Equipment                       | 92192451   | 168947709  | 240094984  | 169610752  | 89815399   | 63275670   | 93377190   | 100991242  | 85198415   | 97929223   | 109492707  | 72319088   | 74614914   | 67784999  | 57792276  | 52975912  | 176140894  | 194548138  | 107636407 | 50350026  | 24034377  | 22730557   | 21264077  | 12031886  | 8092073   | 5235500   | 4840017   | 2633248   | 2891270   | 
| Department of Sanitation                      |                                 | 352634675  | 322431663  | 233743208  | 346829234  | 229926053  | 187812015  | 131128988  | 93993887   | 158826056  | 173092620  | 113502181  | 185248832  | 178226329  | 118119448 | 71161276  | 116194433 | 213414358  | 131221056  | 113728293 | 151328011 | 188283482 | 152732523  | 172005980 | 222841645 | 209833906 | 140954837 | 165423790 | 174230227 | 139187821 | 
|                                               | Equipment                       | 128573756  | 108907654  | 60584167   | 147609184  | 172738378  | 108407893  | 43950547   | 21003344   | 52600025   | 40172200   | 57991485   | 142811554  | 131814524  | 28105343  | 25620835  | 17134213  | 17632936   | 40150499   | 53020683  | 29185752  | 21321064  | 29166557   | 78690232  | 48118229  | 100004339 | 44169796  | 64379326  | 30394141  | 62484493  | 
|                                               | Garages                         | 101736739  | 89711756   | 66610153   | 157578759  | 52258454   | 68829127   | 82271118   | 61739584   | 71086269   | 80344562   | 35093452   | 38032893   | 29758612   | 80346049  | 18000261  | 71235196  | 59022358   | 15426687   | 14333966  | 74152469  | 114852202 | 66435792   | 35877467  | 73889392  | 38352555  | 51099169  | 26757741  | 72396977  |           | 
|                                               | Waste Disposal Facilities       | 122324180  | 123812253  | 106548888  | 41641291   | 4929221    | 10574995   | 4907323    | 11250959   | 35139762   | 52575858   | 20417244   | 4404385    | 16653193   | 9668056   | 27540180  | 27825024  | 136759064  | 75643870   | 46373644  | 47989790  | 52110223  | 57130174   | 57438281  | 100834024 | 71477012  | 45685872  | 74286723  | 71439109  | 76703328  | 
| TOTAL ENVIRONMENTAL PROTECTION AND SANITATION |                                 | 2196582128 | 2728031225 | 3057878571 | 2972146944 | 2930162441 | 2500850737 | 2079965314 | 1935272573 | 1838220165 | 1803699821 | 1415282079 | 1221954596 | 1008236067 | 914984457 | 859089521 | 880961620 | 1190969404 | 1135472945 | 819126901 | 767720677 | 933818011 | 1046372058 | 998145885 | 859715814 | 831604064 | 708040120 | 727587728 | 739198602 | 637663536 | 
```