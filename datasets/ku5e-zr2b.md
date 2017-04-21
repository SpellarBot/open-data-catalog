# Museum Universe Data File FY 2015 Q3

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/museum-universe-data-file-fy-2015-q3) |
| Metadata | [Link](https://data.imls.gov/api/views/ku5e-zr2b) |
| Data: JSON | [100 Rows](https://data.imls.gov/api/views/ku5e-zr2b/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.imls.gov/api/views/ku5e-zr2b/rows.csv?max_rows=100) |
| Host | data.imls.gov |
| Id | ku5e-zr2b |
| Name | Museum Universe Data File FY 2015 Q3 |
| Attribution | IMLS |
| Category | Museum Universe Data File |
| Tags | museums, mudf |
| Created | 2015-10-23T20:04:11Z |
| Publication Date | 2016-06-16T14:19:23Z |

## Description

Browse a list of known museums and related organizations in the United States as of the third quarter of FY 2015. This list contains descriptive information about museums in the 50 states and the District of Columbia based on public records and administrative data.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| Yes      | series tag     | mid         | MID         | text      | number      |
| Yes      | series tag     | commonname  | COMMONNAME  | text      | text        |
| Yes      | series tag     | legalname   | LEGALNAME   | text      | text        |
| Yes      | series tag     | altname     | ALTNAME     | text      | text        |
| Yes      | series tag     | akadba      | AKADBA      | text      | text        |
| Yes      | series tag     | adzip5      | ADZIP5      | text      | number      |
| Yes      | series tag     | phzip5      | PHZIP5      | text      | number      |
| Yes      | series tag     | phone       | PHONE       | text      | number      |
| Yes      | series tag     | weburl      | WEBURL      | url       | url         |
| Yes      | series tag     | discipl     | DISCIPL     | text      | text        |
| Yes      | numeric metric | ein         | EIN         | number    | number      |
| Yes      | series tag     | nteec       | NTEEC       | text      | text        |
| Yes      | numeric metric | taxper      | TAXPER      | number    | number      |
| Yes      | numeric metric | incomecd    | INCOMECD    | number    | number      |
| Yes      | numeric metric | income      | INCOME      | money     | money       |
| Yes      | numeric metric | revenue     | REVENUE     | money     | money       |
| Yes      | numeric metric | ipeds       | IPEDS       | number    | number      |
| Yes      | series tag     | instname    | INSTNAME    | text      | text        |
| Yes      | numeric metric | naics       | NAICS       | number    | number      |
| Yes      | numeric metric | aamreg      | AAMREG      | number    | number      |
| Yes      | numeric metric | beareg      | BEAREG      | number    | number      |
| Yes      | numeric metric | locale4     | LOCALE4     | number    | number      |
| Yes      | series tag     | fipsst      | FIPSST      | text      | number      |
| Yes      | series tag     | fipsco      | FIPSCO      | text      | number      |
| Yes      | numeric metric | centract    | CENTRACT    | number    | number      |
| Yes      | numeric metric | cenblock    | CENBLOCK    | number    | number      |
| Yes      | numeric metric | congdist    | CONGDIST    | number    | number      |
| Yes      | series tag     | fullfips    | FULLFIPS    | text      | number      |
| Yes      | numeric metric | bmf15_f     | BMF15_F     | number    | number      |
| Yes      | numeric metric | primarylast | PrimaryLast | number    | number      |
| Yes      | series tag     | aams_id     | AAMS_ID     | text      | number      |
| Yes      | series tag     | factual_id  | FACTUAL_ID  | text      | text        |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ku5e-zr2b d:2015-01-01T00:00:00.000Z t:fullfips=121079514022010 t:discipl=GMU t:adzip5=32112 t:legalname="MOUNT ROYAL MUSEUM & CULT" t:commonname="MOUNT ROYAL MUSEUM & CULT" t:mid=8401201035 t:fipsst=12 t:fipsco=107 m:locale4=4 m:bmf15_f=0 m:beareg=5 m:cenblock=2010 m:ein=593654187 m:congdist=6 m:centract=951402 m:primarylast=1 m:aamreg=3

series e:ku5e-zr2b d:2015-01-01T00:00:00.000Z t:phone=2023571300 t:fullfips=110010048021000 t:discipl=HST t:adzip5=20001 t:legalname="NATIONAL HISTORY MUSEUM" t:commonname="NATIONAL HISTORY MUSEUM" t:mid=8401100019 t:fipsst=11 t:fipsco=1 t:factual_id=43612ca8-ef29-4ef0-a309-9f074538b269 m:locale4=1 m:bmf15_f=0 m:beareg=2 m:cenblock=1000 m:congdist=98 m:centract=4802 m:primarylast=1 m:aamreg=2

series e:ku5e-zr2b d:2015-01-01T00:00:00.000Z t:fullfips=420691126004039 t:discipl=HSC t:adzip5=18518 t:legalname="OLD FORGE COAL MINE" t:commonname="OLD FORGE COAL MINE" t:mid=8404201448 t:fipsst=42 t:fipsco=69 t:nteec=A80 m:locale4=2 m:bmf15_f=0 m:beareg=2 m:cenblock=4039 m:ein=263567060 m:congdist=17 m:centract=112600 m:primarylast=1 m:aamreg=2
```

## Meta Commands

```ls
metric m:ein p:integer l:EIN d:"Federal Employer Identification Number (EIN) number of organization" t:dataTypeName=number

metric m:taxper p:integer l:TAXPER d:"Tax period of the latest return filed (YYYYMM)." t:dataTypeName=number

metric m:incomecd p:integer l:INCOMECD d:"Income Codes relate to the amount of income shown on the most recent Form 990 series return filed by the organization. Information comes from Internal Revenue Service (IRS) Business Master File." t:dataTypeName=number

metric m:income p:long l:INCOME d:"Total revenue from most recent Internal Revenue Service (IRS) 990 Form. Information comes from Internal Revenue Service (IRS) Business Master File." t:dataTypeName=money

metric m:revenue p:long l:REVENUE d:"Total revenue from most recent Internal Revenue Service (IRS) 990 Form. Information comes from Internal Revenue Service (IRS) Business Master File." t:dataTypeName=money

metric m:ipeds p:integer l:IPEDS d:"Unique identifier from Integrated Postsecondary Education Data System, which is the primary source for postsecondary education data (if applicable). For more information see National Center for Education Statistics http://nces.ed.gov/ipeds/" t:dataTypeName=number

metric m:naics p:integer l:NAICS d:"North American Industrial Classification System (NAICS), a classification system used by the federal government to classify business establishments for the purpose of collecting, analyzing, and publishing statistical data related to the U.S. business economy. NAICS was developed under the auspices of the Office of Management and Budget (OMB), and adopted in 1997 to replace the Standard Industrial Classification (SIC) system. For more information about NAICS see: http://www.census.gov/eos/www/naics/" t:dataTypeName=number

metric m:aamreg p:integer l:AAMREG d:"Museum region, regions are determined by the American Alliance of Museums (AAM). Additional information can be found at the following site: http://www.aam-us.org/." t:dataTypeName=number

metric m:beareg p:integer l:BEAREG d:"Bureau of Economic Analysis regions. For more information see U.S. Department of Commerce Bureau of Economic Analysis http://www.bea.gov/regional/docs/regions.cfm." t:dataTypeName=number

metric m:locale4 p:integer l:LOCALE4 d:"National Center for Education Statistics (NCES) Urban-Centric Locale Codes classification; based on geocoded address of institution. Additional information can be found at the following site: https://nces.ed.gov/ccd/rural_locales.asp" t:dataTypeName=number

metric m:centract p:integer l:CENTRACT d:"US Census Tract (2010); based on geocoded address of institution." t:dataTypeName=number

metric m:cenblock p:integer l:CENBLOCK d:"US Census Block (2010); based on geocoded address of institution." t:dataTypeName=number

metric m:congdist p:integer l:CONGDIST d:"Congressional District. ANSI code based on the location of the administrative entity/outlet. Legislatively defined subdivisions of the state for the purpose of electing representatives to the House of Representatives of the U.S. Congress." t:dataTypeName=number

metric m:bmf15_f p:integer l:BMF15_F d:"Internal Revenue Service?s Business Master File May 2015 flag. This flag indicates that this record was found in the most recent IRS 990 Business Master File data. The IRS Business Master File (BMF) contain descriptive information for all active organizations (public charities, private foundations, etc) that have registered for tax-exempt status for the IRS." t:dataTypeName=number

metric m:primarylast p:integer l:PrimaryLast t:dataTypeName=number

entity e:ku5e-zr2b l:"Museum Universe Data File FY 2015 Q3" t:attribution=IMLS t:url=https://data.imls.gov/api/views/ku5e-zr2b

property e:ku5e-zr2b t:meta.view v:id=ku5e-zr2b v:category="Museum Universe Data File" v:attributionLink=https://www.imls.gov/research-evaluation/data-collection/museum-universe-data-file v:averageRating=0 v:name="Museum Universe Data File FY 2015 Q3" v:attribution=IMLS

property e:ku5e-zr2b t:meta.view.license v:name="Public Domain"

property e:ku5e-zr2b t:meta.view.owner v:id=b4ig-itd5 v:screenName=Ammie v:displayName=Ammie

property e:ku5e-zr2b t:meta.view.tableauthor v:id=b4ig-itd5 v:screenName=Ammie v:displayName=Ammie

property e:ku5e-zr2b t:meta.view.metadata.custom_fields.common_core v:Contact_Email=imlsinfo@imls.gov v:Contact_Name="Office of Digital and Information Strategy" v:Bureau_Code=474:00 v:Program_Code=000:000
```

## Top Records

```ls
| mid        | commonname                       | legalname                            | altname | akadba | adzip5 | phzip5 | phone      | weburl       | discipl | ein       | nteec | taxper | incomecd | income | revenue | ipeds | instname | naics | aamreg | beareg | locale4 | fipsst | fipsco | centract | cenblock | congdist | fullfips        | bmf15_f | primarylast | aams_id | factual_id                           | 
| ========== | ================================ | ==================================== | ======= | ====== | ====== | ====== | ========== | ============ | ======= | ========= | ===== | ====== | ======== | ====== | ======= | ===== | ======== | ===== | ====== | ====== | ======= | ====== | ====== | ======== | ======== | ======== | =============== | ======= | =========== | ======= | ==================================== | 
| 8401201035 | MOUNT ROYAL MUSEUM & CULT        | MOUNT ROYAL MUSEUM & CULT            |         |        | 32112  |        |            | [null, null] | GMU     | 593654187 |       |        |          |        |         |       |          |       | 3      | 5      | 4       | 12     | 107    | 951402   | 2010     | 6        | 121079514022010 | 0       | 1           |         |                                      | 
| 8401100019 | NATIONAL HISTORY MUSEUM          | NATIONAL HISTORY MUSEUM              |         |        | 20001  |        | 2023571300 | [null, null] | HST     |           |       |        |          |        |         |       |          |       | 2      | 2      | 1       | 11     | 1      | 4802     | 1000     | 98       | 110010048021000 | 0       | 1           |         | 43612ca8-ef29-4ef0-a309-9f074538b269 | 
| 8404201448 | OLD FORGE COAL MINE              | OLD FORGE COAL MINE                  |         |        | 18518  |        |            | [null, null] | HSC     | 263567060 | A80   |        |          |        |         |       |          |       | 2      | 2      | 2       | 42     | 69     | 112600   | 4039     | 17       | 420691126004039 | 0       | 1           |         |                                      | 
| 8403700724 | SEVEN OF SEVENATE                | SEVEN OF SEVENATE INC                |         |        | 27513  |        | 9194607942 | [null, null] | GMU     | 562242811 |       |        |          |        |         |       |          |       | 3      | 5      | 1       | 37     | 183    | 53424    | 2019     | 2        | 371830534242019 | 0       | 1           |         |                                      | 
| 8401600200 | VAN SLYKE MUSEUM                 | VAN SLYKE MUSEUM                     |         |        | 83606  |        |            | [null, null] | GMU     | 943175307 | A50   |        |          |        |         |       |          |       | 6      | 7      | 4       | 16     | 27     | 21904    | 1236     | 1        | 160270219041236 | 0       | 1           |         |                                      | 
| 8401800590 | SOUTHERN INDIANA RAILROAD MUSEUM | SOUTHERN INDIANA RAILROAD MUSEUM INC |         |        | 47274  |        |            | [null, null] | GMU     | 352085042 |       |        |          |        |         |       |          |       | 4      | 3      | 4       | 18     | 71     | 967500   | 3028     | 9        | 180719675003028 | 0       | 1           |         |                                      | 
| 8400600577 | ALVARADO PARK                    | ALVARADO PARK                        |         |        | 94605  |        |            | [null, null] | BOT     |           |       |        |          |        |         |       |          |       | 6      | 8      | 1       | 6      |        | 408300   | 4003     | 0        | 60014083004003  | 0       | 1           |         |                                      | 
| 8403800186 | BRENORSOME HISTORICAL SOCIETY    | BRENORSOME HISTORICAL SOCIETY        |         |        | 58379  |        |            | [null, null] | HSC     |           |       |        |          |        |         |       |          |       | 5      | 4      | 4       | 38     | 5      | 940200   | 2152     | 0        | 380059402002152 | 0       | 1           |         |                                      | 
| 8403800273 | SCHULSTAD STONE HOUSE MUSEUM     | SCHULSTAD STONE HOUSE MUSEUM         |         |        | 58439  |        |            | [null, null] | GMU     |           |       |        |          |        |         |       |          |       | 5      | 4      | 4       | 38     |        | 973300   | 2407     | 0        | 380219733002407 | 0       | 1           |         |                                      | 
| 8409501750 | READINGTON MUSEUMS               | READINGTON MUSEUMS                   |         |        | 8885   |        | 9082362376 | [null, null] | GMU     |           |       |        |          |        |         |       |          |       | 2      | 2      | 4       | 34     | 19     | 11201    | 1023     | 7        | 340190112011023 | 0       | 1           |         |                                      | 
```