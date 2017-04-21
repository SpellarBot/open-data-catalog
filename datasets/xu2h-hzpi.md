# SICL Intersections - Top 201-400

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sicl-intersections-top-201-400) |
| Metadata | [Link](https://data.iowa.gov/api/views/xu2h-hzpi) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/xu2h-hzpi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/xu2h-hzpi/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | xu2h-hzpi |
| Name | SICL Intersections - Top 201-400 |
| Attribution | Iowa Department of Transportation - Office of Traffic & Safety |
| Category | Transportation & Utilities |
| Tags | crash, asset, improvement, sicl, intersection, safety, iowa dot, iowa department of transportation, crash analysis |
| Created | 2016-06-09T21:00:19Z |
| Publication Date | 2016-06-09T21:02:27Z |

## Description

Locations 201 - 400 of the intersection safety improvement candidate locations in Iowa (composite rank). The Iowa DOT's Office of Traffic and Safety has updated a list of the top 1000 intersection safety improvement candidate locations (SICL) in Iowa. This list is supplemental to Iowa DOT's primary focus, Iowa's 5 Percent Safety Report. To develop this list, all crashes in Iowa are used to determine an initial cut of intersections that meet the criteria of at least one crash. The intersections identified are then ranked according to the number of crashes, the severity of the crashes, and the rate at which crashes occur. To read more details regarding Iowa's SICL, see Iowa SICL method. The Iowa DOT utilizes crash reports filed by city police departments, county sheriffs, the Iowa State Patrol and individual drivers in determining the listings. The locations identified are eligible for funding assistance to develop safety improvements under the Iowa Traffic Safety Fund Program. Grant applications for funding are competitive and subject to comparison with the 5 percent severe safety needs list. The Iowa DOT will select proposals that provide the greatest safety return on the dollars invested. Proposals must be submitted to the Iowa DOT by June 15th each year to qualify for funding the following year. The Iowa Transportation Commission will consider and approve funding for selected locations during November and December.?For more detail, please see: http://www.iowadot.gov/crashanalysis/top200.htm

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| No       |                | x           | X          | number    | number      |
| No       |                | y           | Y          | number    | number      |
| Yes      | numeric metric | comprank    | COMPRANK   | number    | number      |
| Yes      | series tag     | tie         | TIE        | text      | text        |
| No       |                | co          | CO         | number    | number      |
| Yes      | series tag     | coname      | CONAME     | text      | text        |
| Yes      | series tag     | ruralurban  | RURALURBAN | text      | text        |
| Yes      | series tag     | city        | CITY       | text      | text        |
| No       |                | ua          | UA         | number    | number      |
| Yes      | numeric metric | dotdstrct   | DOTDSTRCT  | number    | number      |
| Yes      | numeric metric | ispdstrct   | ISPDSTRCT  | number    | number      |
| Yes      | numeric metric | rpa         | RPA        | number    | number      |
| Yes      | numeric metric | mpo         | MPO        | number    | number      |
| Yes      | series tag     | schdst1011  | SCHDST1011 | text      | text        |
| Yes      | series tag     | routes      | ROUTES     | text      | text        |
| Yes      | series tag     | literal     | LITERAL    | text      | text        |
| Yes      | series tag     | intclass    | INTCLASS   | text      | text        |
| No       |                | id          | ID         | text      | number      |
| Yes      | series tag     | exprint     | EXPRINT    | text      | text        |
| Yes      | numeric metric | freqrank    | FREQRANK   | number    | number      |
| Yes      | numeric metric | raterank    | RATERANK   | number    | number      |
| Yes      | numeric metric | sevrank     | SEVRANK    | number    | number      |
| Yes      | numeric metric | composite   | COMPOSITE  | number    | number      |
| Yes      | numeric metric | frequency   | FREQUENCY  | number    | number      |
| Yes      | numeric metric | freqnorm    | FREQNORM   | number    | number      |
| Yes      | numeric metric | fatcrash    | FATCRASH   | number    | number      |
| Yes      | numeric metric | majcrash    | MAJCRASH   | number    | number      |
| Yes      | numeric metric | mincrash    | MINCRASH   | number    | number      |
| Yes      | numeric metric | poscrash    | POSCRASH   | number    | number      |
| Yes      | numeric metric | unkcrash    | UNKCRASH   | number    | number      |
| Yes      | numeric metric | pdocrash    | PDOCRASH   | number    | number      |
| Yes      | numeric metric | severity    | SEVERITY   | number    | number      |
| Yes      | numeric metric | sevnorm     | SEVNORM    | number    | number      |
| Yes      | numeric metric | injs        | INJS       | number    | number      |
| Yes      | numeric metric | fatalities  | FATALITIES | number    | number      |
| Yes      | numeric metric | majinjur    | MAJINJUR   | number    | number      |
| Yes      | numeric metric | mininjur    | MININJUR   | number    | number      |
| Yes      | numeric metric | possinjur   | POSSINJUR  | number    | number      |
| Yes      | numeric metric | unkinjur    | UNKINJUR   | number    | number      |
| Yes      | numeric metric | rate        | RATE       | number    | number      |
| Yes      | numeric metric | ratenorm    | RATENORM   | number    | number      |
| Yes      | numeric metric | volume      | VOLUME     | number    | number      |
| Yes      | numeric metric | dev         | DEV        | number    | number      |
| Yes      | numeric metric | links       | LINKS      | number    | number      |
| Yes      | numeric metric | aadtzero    | AADTZERO   | number    | number      |
| Yes      | numeric metric | crashes13   | CRASHES13  | number    | number      |
| Yes      | numeric metric | crashes09   | CRASHES09  | number    | number      |
| Yes      | numeric metric | crashes10   | CRASHES10  | number    | number      |
| Yes      | numeric metric | crashes11   | CRASHES11  | number    | number      |
| Yes      | numeric metric | crashes12   | CRASHES12  | number    | number      |
| Yes      | numeric metric | fatcrash13  | FATCRASH13 | number    | number      |
| Yes      | numeric metric | fatcrash09  | FATCRASH09 | number    | number      |
| Yes      | numeric metric | fatcrash10  | FATCRASH10 | number    | number      |
| Yes      | numeric metric | fatcrash11  | FATCRASH11 | number    | number      |
| Yes      | numeric metric | fatcrash12  | FATCRASH12 | number    | number      |
| Yes      | numeric metric | majcrash13  | MAJCRASH13 | number    | number      |
| Yes      | numeric metric | majcrash09  | MAJCRASH09 | number    | number      |
| Yes      | numeric metric | majcrash10  | MAJCRASH10 | number    | number      |
| Yes      | numeric metric | majcrash11  | MAJCRASH11 | number    | number      |
| Yes      | numeric metric | majcrash12  | MAJCRASH12 | number    | number      |
| Yes      | numeric metric | fatinj13    | FATINJ13   | number    | number      |
| Yes      | numeric metric | fatinj09    | FATINJ09   | number    | number      |
| Yes      | numeric metric | fatinj10    | FATINJ10   | number    | number      |
| Yes      | numeric metric | fatinj11    | FATINJ11   | number    | number      |
| Yes      | numeric metric | fatinj12    | FATINJ12   | number    | number      |
| Yes      | numeric metric | majinj13    | MAJINJ13   | number    | number      |
| Yes      | numeric metric | majinj09    | MAJINJ09   | number    | number      |
| Yes      | numeric metric | majinj10    | MAJINJ10   | number    | number      |
| Yes      | numeric metric | majinj11    | MAJINJ11   | number    | number      |
| Yes      | numeric metric | majinj12    | MAJINJ12   | number    | number      |
| Yes      | series tag     | objectid    | OBJECTID   | text      | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = x,y,co,ua,id
```

## Data Commands

```ls
series e:xu2h-hzpi d:2016-06-09T21:00:19.000Z t:ruralurban=Rural t:routes="US 65 / Local" t:intclass="US / Local" t:exprint=N t:schdst1011=CARLISLE t:objectid=201 t:literal="US 65/SW RAMP/NW RAMP/SW LOOP & E ARMY POST RD" t:coname=Polk m:poscrash=1 m:majinj09=0 m:comprank=201 m:mpo=5 m:crashes12=3 m:crashes13=2 m:crashes10=5 m:crashes11=2 m:freqrank=1272 m:majcrash09=0 m:injs=9 m:rpa=11 m:sevnorm=0.33840001000000003 m:sevrank=144 m:unkinjur=3 m:crashes09=3 m:ratenorm=0.002 m:composite=0.23340000000000002 m:majinj13=0 m:majinj12=3 m:fatcrash09=0 m:majinj10=0 m:mininjur=2 m:majinj11=0 m:majcrash11=0 m:majcrash10=0 m:fatinj09=0 m:majcrash13=1 m:majcrash12=2 m:fatinj10=0 m:pdocrash=9 m:majinjur=3 m:dev=9215 m:fatinj13=0 m:fatinj12=0 m:fatinj11=0 m:fatcrash=0 m:majcrash=3 m:frequency=15 m:raterank=9132 m:possinjur=1 m:mincrash=1 m:fatcrash10=0 m:fatcrash11=0 m:fatcrash12=0 m:fatcrash13=0 m:rate=0.8919 m:fatalities=0 m:aadtzero=0 m:ispdstrct=1 m:links=5 m:severity=356 m:unkcrash=1 m:volume=18430 m:dotdstrct=1 m:freqnorm=0.15000001000000002

series e:xu2h-hzpi d:2016-06-09T21:00:19.000Z t:ruralurban=Urban t:routes=Local t:intclass=Local t:exprint=N t:schdst1011="CEDAR RAPIDS" t:objectid=202 t:literal="16TH AVE SW & WILEY BLVD SW" t:coname=Linn t:city="Cedar Rapids" m:poscrash=7 m:majinj09=0 m:comprank=202 m:mpo=2 m:crashes12=8 m:crashes13=8 m:crashes10=7 m:crashes11=2 m:freqrank=259 m:majcrash09=0 m:injs=19 m:rpa=10 m:sevnorm=0.2728 m:sevrank=290 m:unkinjur=0 m:crashes09=9 m:ratenorm=0.0018000000000000002 m:composite=0.2321 m:majinj13=2 m:majinj12=0 m:fatcrash09=0 m:majinj10=0 m:mininjur=5 m:majinj11=0 m:majcrash11=0 m:majcrash10=0 m:fatinj09=0 m:majcrash13=2 m:majcrash12=0 m:fatinj10=0 m:pdocrash=20 m:majinjur=2 m:dev=23080 m:fatinj13=0 m:fatinj12=0 m:fatinj11=0 m:fatcrash=0 m:majcrash=2 m:frequency=34 m:raterank=10268 m:possinjur=12 m:mincrash=5 m:fatcrash10=0 m:fatcrash11=0 m:fatcrash12=0 m:fatcrash13=0 m:rate=0.8072 m:fatalities=0 m:aadtzero=0 m:ispdstrct=11 m:links=4 m:severity=287 m:unkcrash=0 m:volume=46160 m:dotdstrct=6 m:freqnorm=0.34

series e:xu2h-hzpi d:2016-06-09T21:00:19.000Z t:ruralurban=Urban t:routes="US 69 / Local" t:intclass="US / Local" t:exprint=N t:schdst1011="DES MOINES INDEPENDENT" t:objectid=203 t:literal="US 69/E 14TH ST & E GRAND AVE" t:coname=Polk t:city="Des Moines" m:poscrash=11 m:majinj09=0 m:comprank=203 m:mpo=5 m:crashes12=18 m:crashes13=7 m:crashes10=7 m:crashes11=11 m:freqrank=77 m:majcrash09=0 m:injs=24 m:rpa=11 m:sevnorm=0.21200000000000002 m:sevrank=540 m:unkinjur=0 m:crashes09=9 m:ratenorm=0.0022 m:composite=0.2316 m:majinj13=0 m:majinj12=1 m:fatcrash09=0 m:majinj10=0 m:mininjur=9 m:majinj11=0 m:majcrash11=0 m:majcrash10=0 m:fatinj09=0 m:majcrash13=0 m:majcrash12=1 m:fatinj10=0 m:pdocrash=33 m:majinjur=1 m:dev=29400 m:fatinj13=0 m:fatinj12=0 m:fatinj11=0 m:fatcrash=0 m:majcrash=1 m:frequency=52 m:raterank=8094 m:possinjur=14 m:mincrash=7 m:fatcrash10=0 m:fatcrash11=0 m:fatcrash12=0 m:fatcrash13=0 m:rate=0.9692000000000001 m:fatalities=0 m:aadtzero=0 m:ispdstrct=1 m:links=4 m:severity=223 m:unkcrash=0 m:volume=58800 m:dotdstrct=1 m:freqnorm=0.51999998
```

## Meta Commands

```ls
metric m:comprank p:integer l:COMPRANK d:"Statewide Candidate Listing" t:dataTypeName=number

metric m:dotdstrct p:integer l:DOTDSTRCT d:"DOT District" t:dataTypeName=number

metric m:ispdstrct p:integer l:ISPDSTRCT d:"ISP District" t:dataTypeName=number

metric m:rpa p:integer l:RPA d:RPA t:dataTypeName=number

metric m:mpo p:integer l:MPO d:MPO t:dataTypeName=number

metric m:freqrank p:integer l:FREQRANK d:"Individual Rank Values - Frequency Rank" t:dataTypeName=number

metric m:raterank p:integer l:RATERANK d:"Individual Rank Values - Rate Rank" t:dataTypeName=number

metric m:sevrank p:integer l:SEVRANK d:"Individual Rank Values - Severity Rank" t:dataTypeName=number

metric m:composite p:decimal l:COMPOSITE d:"Individual Rank Values - Composite Normalized Total" t:dataTypeName=number

metric m:frequency p:integer l:FREQUENCY d:"Frequency - Crash Frequency" t:dataTypeName=number

metric m:freqnorm p:decimal l:FREQNORM d:"Frequency - Crash Frequency Normalized" t:dataTypeName=number

metric m:fatcrash p:integer l:FATCRASH d:"Frequency - Fatal Crashes" t:dataTypeName=number

metric m:majcrash p:integer l:MAJCRASH d:"Frequency - Major Injury Crashes" t:dataTypeName=number

metric m:mincrash p:integer l:MINCRASH d:"Frequency - Minor Injury Crashes" t:dataTypeName=number

metric m:poscrash p:integer l:POSCRASH d:"Frequency - Possible Injury Crashes" t:dataTypeName=number

metric m:unkcrash p:integer l:UNKCRASH d:"Frequency - Unknown Injury Crashes" t:dataTypeName=number

metric m:pdocrash p:integer l:PDOCRASH d:"Frequency - Property Damage Only Crashes" t:dataTypeName=number

metric m:severity p:integer l:SEVERITY d:"Severity Values - Injury Severity Index" t:dataTypeName=number

metric m:sevnorm p:float l:SEVNORM d:"Severity Values - Injury Severity Index Normalized" t:dataTypeName=number

metric m:injs p:integer l:INJS d:"Severity Values - Total Injuries" t:dataTypeName=number

metric m:fatalities p:integer l:FATALITIES d:"Severity Values - Total Fatalities" t:dataTypeName=number

metric m:majinjur p:integer l:MAJINJUR d:"Severity Values - Major Injuries" t:dataTypeName=number

metric m:mininjur p:integer l:MININJUR d:"Severity Values - Minor Injuries" t:dataTypeName=number

metric m:possinjur p:integer l:POSSINJUR d:"Severity Values - Possible Injuries" t:dataTypeName=number

metric m:unkinjur p:integer l:UNKINJUR d:"Severity Values - Unknown Injuries" t:dataTypeName=number

metric m:rate p:float l:RATE d:"Rate Values - Crash Rate" t:dataTypeName=number

metric m:ratenorm p:double l:RATENORM d:"Rate Values - Crash Rate Normalized" t:dataTypeName=number

metric m:volume p:integer l:VOLUME d:"Rate Values - Volume" t:dataTypeName=number

metric m:dev p:double l:DEV d:"Rate Values - Daily Entering Vehicles" t:dataTypeName=number

metric m:links p:integer l:LINKS d:"Rate Values - Number of Legs/Links" t:dataTypeName=number

metric m:aadtzero p:integer l:AADTZERO d:"Rate Values - No of Links with AADT = 0" t:dataTypeName=number

metric m:crashes13 p:integer l:CRASHES13 d:"Crash Frequency (2013)" t:dataTypeName=number

metric m:crashes09 p:integer l:CRASHES09 d:"Crash Frequency (2009)" t:dataTypeName=number

metric m:crashes10 p:integer l:CRASHES10 d:"Crash Frequency (2010)" t:dataTypeName=number

metric m:crashes11 p:integer l:CRASHES11 d:"Crash Frequency (2011)" t:dataTypeName=number

metric m:crashes12 p:integer l:CRASHES12 d:"Crash Frequency (2012)" t:dataTypeName=number

metric m:fatcrash13 p:integer l:FATCRASH13 d:"Fatal Crashes (2013)" t:dataTypeName=number

metric m:fatcrash09 p:integer l:FATCRASH09 d:"Fatal Crashes (2009)" t:dataTypeName=number

metric m:fatcrash10 p:integer l:FATCRASH10 d:"Fatal Crashes (2010)" t:dataTypeName=number

metric m:fatcrash11 p:integer l:FATCRASH11 d:"Fatal Crashes (2011)" t:dataTypeName=number

metric m:fatcrash12 p:integer l:FATCRASH12 d:"Fatal Crashes (2012)" t:dataTypeName=number

metric m:majcrash13 p:integer l:MAJCRASH13 d:"Major Injury Crashes (2013)" t:dataTypeName=number

metric m:majcrash09 p:integer l:MAJCRASH09 d:"Major Injury Crashes (2009)" t:dataTypeName=number

metric m:majcrash10 p:integer l:MAJCRASH10 d:"Major Injury Crashes (2010)" t:dataTypeName=number

metric m:majcrash11 p:integer l:MAJCRASH11 d:"Major Injury Crashes (2011)" t:dataTypeName=number

metric m:majcrash12 p:integer l:MAJCRASH12 d:"Major Injury Crashes (2012)" t:dataTypeName=number

metric m:fatinj13 p:integer l:FATINJ13 d:"Fatalities (2013)" t:dataTypeName=number

metric m:fatinj09 p:integer l:FATINJ09 d:"Fatalities (2009)" t:dataTypeName=number

metric m:fatinj10 p:integer l:FATINJ10 d:"Fatalities (2010)" t:dataTypeName=number

metric m:fatinj11 p:integer l:FATINJ11 d:"Fatalities (2011)" t:dataTypeName=number

metric m:fatinj12 p:integer l:FATINJ12 d:"Fatalities (2012)" t:dataTypeName=number

metric m:majinj13 p:integer l:MAJINJ13 d:"Major Injuries (2013)" t:dataTypeName=number

metric m:majinj09 p:integer l:MAJINJ09 d:"Major Injuries (2009)" t:dataTypeName=number

metric m:majinj10 p:integer l:MAJINJ10 d:"Major Injuries (2010)" t:dataTypeName=number

metric m:majinj11 p:integer l:MAJINJ11 d:"Major Injuries (2011)" t:dataTypeName=number

metric m:majinj12 p:integer l:MAJINJ12 d:"Major Injuries (2012)" t:dataTypeName=number

entity e:xu2h-hzpi l:"SICL Intersections - Top 201-400" t:attribution="Iowa Department of Transportation - Office of Traffic & Safety" t:url=https://data.iowa.gov/api/views/xu2h-hzpi

property e:xu2h-hzpi t:meta.view v:id=xu2h-hzpi v:category="Transportation & Utilities" v:attributionLink=https://gis.iowadot.gov/public/rest/services/Traffic_Safety/SICL/MapServer/1 v:averageRating=0 v:name="SICL Intersections - Top 201-400" v:attribution="Iowa Department of Transportation - Office of Traffic & Safety"

property e:xu2h-hzpi t:meta.view.owner v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:displayName="Iowa Department of Transportation"

property e:xu2h-hzpi t:meta.view.tableauthor v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"
```

## Top Records

```ls
| :updated_at | x                                         | y                                      | comprank | tie | co | coname  | ruralurban | city         | ua  | dotdstrct | ispdstrct | rpa | mpo | schdst1011             | routes               | literal                                        | intclass           | id      | exprint | freqrank | raterank | sevrank | composite                                                 | frequency | freqnorm                                                   | fatcrash | majcrash | mincrash | poscrash | unkcrash | pdocrash | severity | sevnorm                                                   | injs | fatalities | majinjur | mininjur | possinjur | unkinjur | rate                                                     | ratenorm                                                          | volume | dev     | links | aadtzero | crashes13 | crashes09 | crashes10 | crashes11 | crashes12 | fatcrash13 | fatcrash09 | fatcrash10 | fatcrash11 | fatcrash12 | majcrash13 | majcrash09 | majcrash10 | majcrash11 | majcrash12 | fatinj13 | fatinj09 | fatinj10 | fatinj11 | fatinj12 | majinj13 | majinj09 | majinj10 | majinj11 | majinj12 | objectid | 
| =========== | ========================================= | ====================================== | ======== | === | == | ======= | ========== | ============ | === | ========= | ========= | === | === | ====================== | ==================== | ============================================== | ================== | ======= | ======= | ======== | ======== | ======= | ========================================================= | ========= | ========================================================== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ========================================================= | ==== | ========== | ======== | ======== | ========= | ======== | ======================================================== | ================================================================= | ====== | ======= | ===== | ======== | ========= | ========= | ========= | ========= | ========= | ========== | ========== | ========== | ========== | ========== | ========== | ========== | ========== | ========== | ========== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | 
| 0           | 456548.488000000012107193470001220703125  | 4597170.4800000004470348358154296875   | 201      |     | 77 | Polk    | Rural      |              | 0   | 1         | 1         | 11  | 5   | CARLISLE               | US 65 / Local        | US 65/SW RAMP/NW RAMP/SW LOOP & E ARMY POST RD | US / Local         | 5003887 | N       | 1272     | 9132     | 144     | 0.2334000000000000241140440948584000580012798309326171875 | 15        | 0.150000010000000016940902014539460651576519012451171875   | 0        | 3        | 1        | 1        | 1        | 9        | 356      | 0.338400010000000028842492838521138764917850494384765625  | 9    | 0          | 3        | 2        | 1         | 3        | 0.89190000000000002611244553918368183076381683349609375  | 0.00200000000000000004163336342344337026588618755340576171875     | 18430  | 9215    | 5     | 0        | 2         | 3         | 5         | 2         | 3         | 0          | 0          | 0          | 0          | 0          | 1          | 0          | 0          | 0          | 2          | 0        | 0        | 0        | 0        | 0        | 0        | 0        | 0        | 0        | 3        | 201      | 
| 0           | 605578.457000000053085386753082275390625  | 4646534.690000000409781932830810546875 | 202      |     | 57 | Linn    | Urban      | Cedar Rapids | 148 | 6         | 11        | 10  | 2   | CEDAR RAPIDS           | Local                | 16TH AVE SW & WILEY BLVD SW                    | Local              | 666820  | N       | 259      | 10268    | 290     | 0.2321000000000000007549516567451064474880695343017578125 | 34        | 0.340000000000000024424906541753443889319896697998046875   | 0        | 2        | 5        | 7        | 0        | 20       | 287      | 0.272799999999999986943777230408159084618091583251953125  | 19   | 0          | 2        | 5        | 12        | 0        | 0.80720000000000002859934511434403248131275177001953125  | 0.00180000000000000016757428777935956532019190490245819091796875  | 46160  | 23080   | 4     | 0        | 8         | 9         | 7         | 2         | 8         | 0          | 0          | 0          | 0          | 0          | 2          | 0          | 0          | 0          | 0          | 0        | 0        | 0        | 0        | 0        | 2        | 0        | 0        | 0        | 0        | 202      | 
| 0           | 450161.8030000000144354999065399169921875 | 4604806.5199999995529651641845703125   | 203      |     | 77 | Polk    | Urban      | Des Moines   | 71  | 1         | 1         | 11  | 5   | DES MOINES INDEPENDENT | US 69 / Local        | US 69/E 14TH ST & E GRAND AVE                  | US / Local         | 429974  | N       | 77       | 8094     | 540     | 0.2316000000000000003108624468950438313186168670654296875 | 52        | 0.51999998000000002829068534992984496057033538818359375    | 0        | 1        | 7        | 11       | 0        | 33       | 223      | 0.212000000000000021760371282653068192303180694580078125  | 24   | 0          | 1        | 9        | 14        | 0        | 0.9692000000000000614619466432486660778522491455078125   | 0.0022000000000000001325328735646280620130710303783416748046875   | 58800  | 29400   | 4     | 0        | 7         | 9         | 7         | 11        | 18        | 0          | 0          | 0          | 0          | 0          | 0          | 0          | 0          | 0          | 1          | 0        | 0        | 0        | 0        | 0        | 0        | 0        | 0        | 0        | 1        | 203      | 
| 0           | 435473.319000000017695128917694091796875  | 4612151.929999999701976776123046875    | 204      |     | 77 | Polk    | Urban      | Grimes       | 71  | 1         | 1         | 11  | 5   | JOHNSTON               | IA 141 / Local       | IA 141/IOWA 141 & NW 54TH AVE                  | State / Local      | 431084  | Y       | 33       | 9954     | 772     | 0.231300000000000005595524044110788963735103607177734375  | 67        | 0.6700000200000000294409119305782951414585113525390625     | 0        | 1        | 4        | 10       | 1        | 51       | 170      | 0.1615999899999999989130827771077747456729412078857421875 | 21   | 0          | 1        | 4        | 13        | 3        | 0.83340000000000002966515921798418276011943817138671875  | 0.00189999999999999999618360835285102439229376614093780517578125  | 88100  | 44050   | 4     | 0        | 23        | 12        | 14        | 8         | 10        | 0          | 0          | 0          | 0          | 0          | 1          | 0          | 0          | 0          | 0          | 0        | 0        | 0        | 0        | 0        | 1        | 0        | 0        | 0        | 0        | 204      | 
| 0           | 449960.84100000001490116119384765625      | 4606105.280000000260770320892333984375 | 205      |     | 77 | Polk    | Urban      | Des Moines   | 71  | 1         | 1         | 11  | 5   | DES MOINES INDEPENDENT | US 69 / Local        | US 69/E 14TH ST & CLEVELAND AVE                | US / Local         | 680615  | N       | 104      | 5416     | 437     | 0.231200000000000016608936448392341844737529754638671875  | 48        | 0.479999989999999987499990083961165510118007659912109375   | 0        | 1        | 7        | 12       | 0        | 28       | 236      | 0.224299999999999999378275106209912337362766265869140625  | 27   | 0          | 1        | 10       | 16        | 0        | 1.3663000000000000699884594723698683083057403564453125   | 0.00310000000000000032474023470285828807391226291656494140625     | 38500  | 19250   | 4     | 0        | 13        | 12        | 9         | 4         | 10        | 0          | 0          | 0          | 0          | 0          | 0          | 1          | 0          | 0          | 0          | 0        | 0        | 0        | 0        | 0        | 0        | 1        | 0        | 0        | 0        | 205      | 
| 0           | 701006.04399999999441206455230712890625   | 4599672.040000000037252902984619140625 | 206      |     | 82 | Scott   | Urban      | Davenport    | 74  | 6         | 12        | 9   | 4   | DAVENPORT              | Local                | W 4TH ST & MARQUETTE ST                        | Local              | 693408  | N       | 141      | 4240     | 358     | 0.2310999999999999998667732370449812151491641998291015625 | 43        | 0.43000000999999998807510337428539060056209564208984375    | 0        | 1        | 9        | 8        | 0        | 25       | 253      | 0.2405000000000000193178806284777238033711910247802734375 | 24   | 0          | 1        | 12       | 11        | 0        | 1.713600000000000012079226507921703159809112548828125    | 0.0039000000000000002546574062733952814596705138683319091796875   | 27500  | 13750   | 4     | 0        | 11        | 3         | 6         | 9         | 14        | 0          | 0          | 0          | 0          | 0          | 0          | 0          | 0          | 0          | 1          | 0        | 0        | 0        | 0        | 0        | 0        | 0        | 0        | 0        | 1        | 206      | 
| 0           | 680886.163999999989755451679229736328125  | 4700958.4800000004470348358154296875   | 207      |     | 31 | Dubuque | Rural      |              | 0   | 6         | 10        | 8   | 6   | DUBUQUE                | US 20 / Local        | US 20 & COTTINGHAM RD                          | US / Local         | 170125  | Y       | 1964     | 21858    | 129     | 0.2309000000000000218935980456080869771540164947509765625 | 11        | 0.11000000000000000055511151231257827021181583404541015625 | 0        | 1        | 1        | 2        | 0        | 7        | 366      | 0.347900000000000042543746303635998629033565521240234375  | 9    | 0          | 3        | 3        | 3         | 0        | 0.344299999999999994937383007709286175668239593505859375 | 0.000800000000000000038337388819087436786503531038761138916015625 | 35010  | 17505   | 4     | 0        | 3         | 0         | 4         | 2         | 2         | 0          | 0          | 0          | 0          | 0          | 0          | 0          | 0          | 0          | 1          | 0        | 0        | 0        | 0        | 0        | 0        | 0        | 0        | 0        | 3        | 207      | 
| 0           | 702402.7639999999664723873138427734375    | 4599959.959999999962747097015380859375 | 208      |     | 82 | Scott   | Urban      | Davenport    | 74  | 6         | 12        | 9   | 4   | DAVENPORT              | US 61 / Local        | US 61/BRADY ST & W 6TH ST & E 6TH ST           | US / Local         | 692212  | N       | 642      | 10371    | 232     | 0.2309000000000000218935980456080869771540164947509765625 | 22        | 0.2200000000000000011102230246251565404236316680908203125  | 2        | 0        | 1        | 3        | 0        | 16       | 327      | 0.310799990000000025958115656976588070392608642578125     | 9    | 2          | 0        | 1        | 6         | 0        | 0.79920000000000002149391775674303062260150909423828125  | 0.00180000000000000016757428777935956532019190490245819091796875  | 30167  | 15083.5 | 4     | 0        | 4         | 6         | 3         | 5         | 4         | 1          | 1          | 0          | 0          | 0          | 0          | 0          | 0          | 0          | 0          | 1        | 1        | 0        | 0        | 0        | 0        | 0        | 0        | 0        | 0        | 208      | 
| 0           | 446226.95600000000558793544769287109375   | 4606018.129999999888241291046142578125 | 209      |     | 77 | Polk    | Urban      | Des Moines   | 71  | 1         | 1         | 11  | 5   | DES MOINES INDEPENDENT | Local                | FOREST AVE & 21ST ST                           | Local              | 683463  | N       | 1155     | 9469     | 161     | 0.2297000000000000152766688188421539962291717529296875    | 16        | 0.1600000000000000033306690738754696212708950042724609375  | 0        | 2        | 0        | 5        | 0        | 9        | 346      | 0.32890001000000002040479785136994905769824981689453125   | 9    | 0          | 3        | 1        | 5         | 0        | 0.86350000000000004529709940470638684928417205810546875  | 0.00200000000000000004163336342344337026588618755340576171875     | 20306  | 10153   | 4     | 0        | 0         | 6         | 2         | 1         | 7         | 0          | 0          | 0          | 0          | 0          | 0          | 2          | 0          | 0          | 0          | 0        | 0        | 0        | 0        | 0        | 0        | 3        | 0        | 0        | 0        | 209      | 
| 0           | 441877.6240000000107102096080780029296875 | 4608866.90000000037252902984619140625  | 210      |     | 77 | Polk    | Urban      | Des Moines   | 71  | 1         | 1         | 11  | 5   | DES MOINES INDEPENDENT | US 6 / IA 28 / Local | US 6/MERLE HAY RD/DOUGLAS AVE & IA 28          | US / State / Local | 428853  | N       | 65       | 12034    | 696     | 0.229200000000000014832579608992091380059719085693359375  | 54        | 0.54000002000000002500001983207766897976398468017578125    | 0        | 1        | 6        | 9        | 1        | 37       | 212      | 0.2015000000000000124344978758017532527446746826171875    | 23   | 0          | 1        | 8        | 12        | 2        | 0.68330000000000001847411112976260483264923095703125     | 0.00160000000000000007667477763817487357300706207752227783203125  | 86600  | 43300   | 4     | 0        | 7         | 10        | 14        | 12        | 11        | 0          | 0          | 0          | 0          | 0          | 0          | 0          | 0          | 0          | 1          | 0        | 0        | 0        | 0        | 0        | 0        | 0        | 0        | 0        | 1        | 210      | 
```