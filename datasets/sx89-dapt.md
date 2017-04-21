# SICL Intersections - All Top 1000

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sicl-intersections-all-top-1000) |
| Metadata | [Link](https://data.iowa.gov/api/views/sx89-dapt) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/sx89-dapt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/sx89-dapt/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | sx89-dapt |
| Name | SICL Intersections - All Top 1000 |
| Attribution | Iowa Department of Transportation - Office of Traffic & Safety |
| Category | Transportation & Utilities |
| Tags | crash, asset, improvement, sicl, intersection, safety, iowa dot, iowa department of transportation, crash analysis |
| Created | 2016-06-09T21:21:52Z |
| Publication Date | 2016-06-09T21:23:54Z |

## Description

The Iowa DOT's Office of Traffic and Safety list of the top 1000 intersection safety improvement candidate locations (SICL) in Iowa. This list is supplemental to Iowa DOT's primary focus, Iowa's 5 Percent Safety Report. To develop this list, all crashes in Iowa are used to determine an initial cut of intersections that meet the criteria of at least one crash. The intersections identified are then ranked according to the number of crashes, the severity of the crashes, and the rate at which crashes occur. To read more details regarding Iowa's SICL, see Iowa SICL method. The Iowa DOT utilizes crash reports filed by city police departments, county sheriffs, the Iowa State Patrol and individual drivers in determining the listings. The locations identified are eligible for funding assistance to develop safety improvements under the Iowa Traffic Safety Fund Program. Grant applications for funding are competitive and subject to comparison with the 5 percent severe safety needs list. The Iowa DOT will select proposals that provide the greatest safety return on the dollars invested. Proposals must be submitted to the Iowa DOT by June 15th each year to qualify for funding the following year. The Iowa Transportation Commission will consider and approve funding for selected locations during November and December.?For more detail, please see: http://www.iowadot.gov/crashanalysis/top200.htm

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
series e:sx89-dapt d:2016-06-09T21:21:52.000Z t:ruralurban=Urban t:routes="US 6 / Local" t:intclass="US / Local" t:exprint=N t:schdst1011=DAVENPORT t:objectid=1 t:literal="US 6/W KIMBERLY RD & MARQUETTE ST" t:coname=Scott t:city=Davenport m:poscrash=9 m:majinj09=0 m:comprank=1 m:mpo=4 m:crashes12=6 m:crashes13=13 m:crashes10=10 m:crashes11=11 m:freqrank=123 m:majcrash09=0 m:injs=30 m:rpa=9 m:sevnorm=1 m:sevrank=1 m:unkinjur=2 m:crashes09=5 m:ratenorm=0.002 m:composite=0.6904 m:majinj13=0 m:majinj12=0 m:fatcrash09=0 m:majinj10=6 m:mininjur=6 m:majinj11=0 m:majcrash11=0 m:majcrash10=1 m:fatinj09=0 m:majcrash13=0 m:majcrash12=0 m:fatinj10=2 m:pdocrash=25 m:majinjur=6 m:dev=27500 m:fatinj13=0 m:fatinj12=0 m:fatinj11=0 m:fatcrash=2 m:majcrash=1 m:frequency=45 m:raterank=9097 m:possinjur=14 m:mincrash=6 m:fatcrash10=2 m:fatcrash11=0 m:fatcrash12=0 m:fatcrash13=0 m:rate=0.8966000000000001 m:fatalities=2 m:aadtzero=0 m:ispdstrct=12 m:links=4 m:severity=1052 m:unkcrash=2 m:volume=55000 m:dotdstrct=6 m:freqnorm=0.44999999

series e:sx89-dapt d:2016-06-09T21:21:52.000Z t:ruralurban=Urban t:routes="US 61 / Local" t:intclass="US / Local" t:exprint=N t:schdst1011=DAVENPORT t:objectid=2 t:literal="US 61/HARRISON ST & W LOCUST ST" t:coname=Scott t:city=Davenport m:poscrash=13 m:majinj09=6 m:comprank=2 m:mpo=4 m:crashes12=14 m:crashes13=9 m:crashes10=11 m:crashes11=17 m:freqrank=41 m:majcrash09=1 m:injs=30 m:rpa=9 m:sevnorm=0.92400002 m:sevrank=3 m:unkinjur=0 m:crashes09=12 m:ratenorm=0.0025 m:composite=0.6809000000000001 m:majinj13=0 m:majinj12=0 m:fatcrash09=0 m:majinj10=1 m:mininjur=7 m:majinj11=1 m:majcrash11=1 m:majcrash10=1 m:fatinj09=0 m:majcrash13=0 m:majcrash12=0 m:fatinj10=0 m:pdocrash=44 m:majinjur=8 m:dev=31900 m:fatinj13=0 m:fatinj12=0 m:fatinj11=0 m:fatcrash=0 m:majcrash=3 m:frequency=63 m:raterank=7197 m:possinjur=15 m:mincrash=3 m:fatcrash10=0 m:fatcrash11=0 m:fatcrash12=0 m:fatcrash13=0 m:rate=1.0821 m:fatalities=0 m:aadtzero=0 m:ispdstrct=12 m:links=4 m:severity=972 m:unkcrash=0 m:volume=63800 m:dotdstrct=6 m:freqnorm=0.63

series e:sx89-dapt d:2016-06-09T21:21:52.000Z t:ruralurban=Rural t:routes="US 30 / R18" t:intclass="US / Local" t:exprint=Y t:schdst1011=BOONE t:objectid=3 t:literal="US 30/220TH ST & Co Rd R18/L AVE" t:coname=Boone m:poscrash=4 m:majinj09=0 m:comprank=3 m:mpo=0 m:crashes12=8 m:crashes13=3 m:crashes10=7 m:crashes11=4 m:freqrank=401 m:majcrash09=0 m:injs=27 m:rpa=11 m:sevnorm=0.9876000300000001 m:sevrank=2 m:unkinjur=1 m:crashes09=6 m:ratenorm=0.0043 m:composite=0.6495000000000001 m:majinj13=2 m:majinj12=1 m:fatcrash09=0 m:majinj10=1 m:mininjur=14 m:majinj11=3 m:majcrash11=1 m:majcrash10=1 m:fatinj09=0 m:majcrash13=1 m:majcrash12=1 m:fatinj10=1 m:pdocrash=15 m:majinjur=7 m:dev=8075 m:fatinj13=0 m:fatinj12=0 m:fatinj11=0 m:fatcrash=1 m:majcrash=4 m:frequency=28 m:raterank=3802 m:possinjur=4 m:mincrash=3 m:fatcrash10=1 m:fatcrash11=0 m:fatcrash12=0 m:fatcrash13=0 m:rate=1.9000000000000001 m:fatalities=1 m:aadtzero=0 m:ispdstrct=1 m:links=4 m:severity=1039 m:unkcrash=1 m:volume=16150 m:dotdstrct=1 m:freqnorm=0.28
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

metric m:composite p:float l:COMPOSITE d:"Individual Rank Values - Composite Normalized Total" t:dataTypeName=number

metric m:frequency p:integer l:FREQUENCY d:"Frequency - Crash Frequency" t:dataTypeName=number

metric m:freqnorm p:double l:FREQNORM d:"Frequency - Crash Frequency Normalized" t:dataTypeName=number

metric m:fatcrash p:integer l:FATCRASH d:"Frequency - Fatal Crashes" t:dataTypeName=number

metric m:majcrash p:integer l:MAJCRASH d:"Frequency - Major Injury Crashes" t:dataTypeName=number

metric m:mincrash p:integer l:MINCRASH d:"Frequency - Minor Injury Crashes" t:dataTypeName=number

metric m:poscrash p:integer l:POSCRASH d:"Frequency - Possible Injury Crashes" t:dataTypeName=number

metric m:unkcrash p:integer l:UNKCRASH d:"Frequency - Unknown Injury Crashes" t:dataTypeName=number

metric m:pdocrash p:integer l:PDOCRASH d:"Frequency - Property Damage Only Crashes" t:dataTypeName=number

metric m:severity p:integer l:SEVERITY d:"Severity Values - Injury Severity Index" t:dataTypeName=number

metric m:sevnorm p:double l:SEVNORM d:"Severity Values - Injury Severity Index Normalized" t:dataTypeName=number

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

entity e:sx89-dapt l:"SICL Intersections - All Top 1000" t:attribution="Iowa Department of Transportation - Office of Traffic & Safety" t:url=https://data.iowa.gov/api/views/sx89-dapt

property e:sx89-dapt t:meta.view v:id=sx89-dapt v:category="Transportation & Utilities" v:attributionLink=https://gis.iowadot.gov/public/rest/services/Traffic_Safety/SICL/MapServer/5 v:averageRating=0 v:name="SICL Intersections - All Top 1000" v:attribution="Iowa Department of Transportation - Office of Traffic & Safety"

property e:sx89-dapt t:meta.view.owner v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:displayName="Iowa Department of Transportation"

property e:sx89-dapt t:meta.view.tableauthor v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"
```

## Top Records

```ls
| :updated_at | x                                          | y                                      | comprank | tie | co | coname        | ruralurban | city           | ua  | dotdstrct | ispdstrct | rpa | mpo | schdst1011             | routes                | literal                                       | intclass                   | id     | exprint | freqrank | raterank | sevrank | composite                                                | frequency | freqnorm                                                  | fatcrash | majcrash | mincrash | poscrash | unkcrash | pdocrash | severity | sevnorm                                                 | injs | fatalities | majinjur | mininjur | possinjur | unkinjur | rate                                                    | ratenorm                                                        | volume | dev     | links | aadtzero | crashes13 | crashes09 | crashes10 | crashes11 | crashes12 | fatcrash13 | fatcrash09 | fatcrash10 | fatcrash11 | fatcrash12 | majcrash13 | majcrash09 | majcrash10 | majcrash11 | majcrash12 | fatinj13 | fatinj09 | fatinj10 | fatinj11 | fatinj12 | majinj13 | majinj09 | majinj10 | majinj11 | majinj12 | objectid | 
| =========== | ========================================== | ====================================== | ======== | === | == | ============= | ========== | ============== | === | ========= | ========= | === | === | ====================== | ===================== | ============================================= | ========================== | ====== | ======= | ======== | ======== | ======= | ======================================================== | ========= | ========================================================= | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======================================================= | ==== | ========== | ======== | ======== | ========= | ======== | ======================================================= | =============================================================== | ====== | ======= | ===== | ======== | ========= | ========= | ========= | ========= | ========= | ========== | ========== | ========== | ========== | ========== | ========== | ========== | ========== | ========== | ========== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | 
| 0           | 700879.170000000041909515857696533203125   | 4603739.200000000186264514923095703125 | 1        |     | 82 | Scott         | Urban      | Davenport      | 74  | 6         | 12        | 9   | 4   | DAVENPORT              | US 6 / Local          | US 6/W KIMBERLY RD & MARQUETTE ST             | US / Local                 | 692162 | N       | 123      | 9097     | 1       | 0.69040000000000001367794766338192857801914215087890625  | 45        | 0.4499999900000000163657887242152355611324310302734375    | 2        | 1        | 6        | 9        | 2        | 25       | 1052     | 1                                                       | 30   | 2          | 6        | 6        | 14        | 2        | 0.8966000000000000635935748505289666354656219482421875  | 0.00200000000000000004163336342344337026588618755340576171875   | 55000  | 27500   | 4     | 0        | 13        | 5         | 10        | 11        | 6         | 0          | 0          | 2          | 0          | 0          | 0          | 0          | 1          | 0          | 0          | 0        | 0        | 2        | 0        | 0        | 0        | 0        | 6        | 0        | 0        | 1        | 
| 0           | 702099.042000000015832483768463134765625   | 4601348.75                             | 2        |     | 82 | Scott         | Urban      | Davenport      | 74  | 6         | 12        | 9   | 4   | DAVENPORT              | US 61 / Local         | US 61/HARRISON ST & W LOCUST ST               | US / Local                 | 484152 | N       | 41       | 7197     | 3       | 0.6809000000000000607514039074885658919811248779296875   | 63        | 0.63000000000000000444089209850062616169452667236328125   | 0        | 3        | 3        | 13       | 0        | 44       | 972      | 0.9240000200000000329936256093787960708141326904296875  | 30   | 0          | 8        | 7        | 15        | 0        | 1.082100000000000061817218011128716170787811279296875   | 0.0025000000000000000520417042793042128323577344417572021484375 | 63800  | 31900   | 4     | 0        | 9         | 12        | 11        | 17        | 14        | 0          | 0          | 0          | 0          | 0          | 0          | 1          | 1          | 1          | 0          | 0        | 0        | 0        | 0        | 0        | 0        | 6        | 1        | 1        | 0        | 2        | 
| 0           | 421296.5040000000153668224811553955078125  | 4653952.34999999962747097015380859375  | 3        |     | 8  | Boone         | Rural      |                | 0   | 1         | 1         | 11  | 0   | BOONE                  | US 30 / R18           | US 30/220TH ST & Co Rd R18/L AVE              | US / Local                 | 42879  | Y       | 401      | 3802     | 2       | 0.64950000000000007727152251391089521348476409912109375  | 28        | 0.2800000000000000266453525910037569701671600341796875    | 1        | 4        | 3        | 4        | 1        | 15       | 1039     | 0.9876000300000000731159843780915252864360809326171875  | 27   | 1          | 7        | 14       | 4         | 1        | 1.9000000000000001332267629550187848508358001708984375  | 0.00430000000000000000277555756156289135105907917022705078125   | 16150  | 8075    | 4     | 0        | 3         | 6         | 7         | 4         | 8         | 0          | 0          | 1          | 0          | 0          | 1          | 0          | 1          | 1          | 1          | 0        | 0        | 1        | 0        | 0        | 2        | 0        | 1        | 3        | 1        | 3        | 
| 0           | 328294.4550000000162981450557708740234375  | 4778710.84999999962747097015380859375  | 4        |     | 21 | Clay          | Urban      |                | 0   | 3         | 6         | 3   | 0   | SPENCER                | B24 / M50             | Co Rd B24/350 ST & Co Rd M50/240 AVE          | Local                      | 110950 | N       | 1155     | 2852     | 4       | 0.564200000000000034816594052244909107685089111328125    | 16        | 0.1600000000000000033306690738754696212708950042724609375 | 1        | 2        | 3        | 3        | 0        | 7        | 931      | 0.8849999900000000696564939062227495014667510986328125  | 18   | 2          | 5        | 6        | 5         | 0        | 2.64470000000000027284841053187847137451171875          | 0.00600000000000000012490009027033011079765856266021728515625   | 6630   | 3315    | 4     | 0        | 1         | 1         | 3         | 7         | 4         | 0          | 0          | 0          | 1          | 0          | 0          | 0          | 0          | 0          | 2          | 0        | 0        | 0        | 2        | 0        | 0        | 0        | 0        | 2        | 3        | 4        | 
| 0           | 545556.084999999962747097015380859375      | 4703669.3399999998509883880615234375   | 5        |     | 7  | Black Hawk    | Urban      | Cedar Falls    | 150 | 2         | 9         | 7   | 9   | CEDAR FALLS            | IA 27 / Local         | IA 27/IOWA 58 & VIKING RD                     | State / Local              | 30885  | N       | 37       | 7019     | 15      | 0.5403000000000000024868995751603506505489349365234375   | 66        | 0.66000002999999995978441802435554563999176025390625      | 2        | 2        | 5        | 12       | 3        | 42       | 715      | 0.67970001999999996034063087790855206549167633056640625 | 30   | 2          | 3        | 5        | 14        | 6        | 1.1059000000000001051603248924948275089263916015625     | 0.0025000000000000000520417042793042128323577344417572021484375 | 65400  | 32700   | 4     | 0        | 16        | 10        | 15        | 15        | 10        | 0          | 0          | 0          | 1          | 1          | 1          | 0          | 0          | 0          | 1          | 0        | 0        | 0        | 1        | 1        | 2        | 0        | 0        | 0        | 1        | 5        | 
| 0           | 261022.79500000001280568540096282958984375 | 4568285.16999999992549419403076171875  | 6        |     | 78 | Pottawattamie | Urban      | Council Bluffs | 46  | 4         | 3         | 18  | 3   | LEWIS CENTRAL          | I-29 / IA 192 / Local | I-29 & IA 192/S EXPRESSWAY & 30TH AVE         | Interstate / State / Local | 455265 | N       | 1        | 4775     | 38      | 0.51440000000000007940315072119119577109813690185546875  | 100       | 1                                                         | 0        | 4        | 4        | 24       | 1        | 67       | 550      | 0.52280002999999997115310179651714861392974853515625    | 44   | 0          | 4        | 7        | 31        | 2        | 1.5332000000000001183053655040566809475421905517578125  | 0.0035000000000000000728583859910258979653008282184600830078125 | 71475  | 35737.5 | 5     | 0        | 23        | 23        | 15        | 17        | 22        | 0          | 0          | 0          | 0          | 0          | 1          | 1          | 1          | 0          | 1          | 0        | 0        | 0        | 0        | 0        | 1        | 1        | 1        | 0        | 1        | 6        | 
| 0           | 449978.1410000000032596290111541748046875  | 4608616.870000000111758708953857421875 | 7        |     | 77 | Polk          | Urban      | Des Moines     | 71  | 1         | 1         | 11  | 5   | DES MOINES INDEPENDENT | US 6 / US 69          | US 6/E EUCLID AVE & US 69/E 14TH ST           | US / US                    | 428959 | N       | 28       | 6995     | 22      | 0.5138000000000000344613226843648590147495269775390625   | 69        | 0.69000000000000005773159728050814010202884674072265625   | 0        | 4        | 6        | 22       | 0        | 37       | 658      | 0.625500020000000045428123485180549323558807373046875   | 43   | 0          | 5        | 7        | 31        | 0        | 1.10709999999999997299937604111619293689727783203125    | 0.0025000000000000000520417042793042128323577344417572021484375 | 68300  | 34150   | 4     | 0        | 9         | 14        | 16        | 14        | 16        | 0          | 0          | 0          | 0          | 0          | 2          | 1          | 1          | 0          | 0          | 0        | 0        | 0        | 0        | 0        | 2        | 2        | 1        | 0        | 0        | 7        | 
| 0           | 454712.7150000000256113708019256591796875  | 4608794.56000000052154064178466796875  | 8        |     | 77 | Polk          | Urban      | Des Moines     | 71  | 1         | 1         | 11  | 5   | DES MOINES INDEPENDENT | US 6 / Local          | US 6/FREDERICK M HUBBELL AVE & E DOUGLAS AVE  | US / Local                 | 429101 | N       | 109      | 5831     | 12      | 0.51090000000000002078337502098293043673038482666015625  | 47        | 0.470000000000000028865798640254070051014423370361328125  | 0        | 4        | 5        | 9        | 0        | 29       | 730      | 0.6938999900000000220501306102960370481014251708984375  | 26   | 0          | 6        | 5        | 15        | 0        | 1.27780000000000004689582056016661226749420166015625    | 0.0029000000000000002338407245616735963267274200916290283203125 | 40310  | 20155   | 4     | 0        | 8         | 8         | 10        | 10        | 11        | 0          | 0          | 0          | 0          | 0          | 1          | 1          | 0          | 1          | 1          | 0        | 0        | 0        | 0        | 0        | 2        | 2        | 0        | 1        | 1        | 8        | 
| 0           | 453467.02399999997578561305999755859375    | 4605575                                | 9        |     | 77 | Polk          | Urban      | Des Moines     | 71  | 1         | 1         | 11  | 5   | DES MOINES INDEPENDENT | IA 163 / Local        | IA 163/E UNIVERSITY AVE & E 30TH ST           | State / Local              | 431271 | N       | 18       | 5883     | 26      | 0.50870000000000004103384299014578573405742645263671875  | 73        | 0.73000001999999997170931465007015503942966461181640625   | 0        | 4        | 11       | 11       | 0        | 47       | 635      | 0.60360003000000006512237860079039819538593292236328125 | 39   | 0          | 4        | 16       | 19        | 0        | 1.2670000000000001261213355974177829921245574951171875  | 0.0029000000000000002338407245616735963267274200916290283203125 | 63140  | 31570   | 4     | 0        | 15        | 9         | 16        | 18        | 15        | 0          | 0          | 0          | 0          | 0          | 2          | 1          | 0          | 0          | 1          | 0        | 0        | 0        | 0        | 0        | 2        | 1        | 0        | 0        | 1        | 9        | 
| 0           | 261759.03400000001420266926288604736328125 | 4572080.620000000111758708953857421875 | 10       |     | 78 | Pottawattamie | Urban      | Council Bluffs | 46  | 4         | 3         | 18  | 3   | COUNCIL BLUFFS         | US 6 / Local          | US 6/KANESVILLE BLVD & S 1ST ST & HARRISON ST | US / Local                 | 688554 | N       | 227      | 15466    | 10      | 0.498300000000000020694557179012917913496494293212890625 | 36        | 0.360000009999999981413765226534451358020305633544921875  | 0        | 5        | 4        | 5        | 0        | 22       | 747      | 0.71010000000000006448175327022909186780452728271484375 | 23   | 0          | 6        | 7        | 9         | 1        | 0.53100000000000002753353101070388220250606536865234375 | 0.0012000000000000001117161918529063768801279366016387939453125 | 74300  | 37150   | 4     | 0        | 11        | 5         | 8         | 7         | 5         | 0          | 0          | 0          | 0          | 0          | 1          | 0          | 2          | 2          | 0          | 0        | 0        | 0        | 0        | 0        | 1        | 0        | 3        | 2        | 0        | 10       | 
```