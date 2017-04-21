# Main Libraries, Branches, and Bookmobiles: FY 2014 Public Libraries Survey (Outlet Data)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/main-libraries-branches-and-bookmobiles-fy-2014-public-libraries-survey-outlet-data) |
| Metadata | [Link](https://data.imls.gov/api/views/ucdn-7aur) |
| Data: JSON | [100 Rows](https://data.imls.gov/api/views/ucdn-7aur/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.imls.gov/api/views/ucdn-7aur/rows.csv?max_rows=100) |
| Host | data.imls.gov |
| Id | ucdn-7aur |
| Name | Main Libraries, Branches, and Bookmobiles: FY 2014 Public Libraries Survey (Outlet Data) |
| Attribution | IMLS |
| Category | Public Libraries Survey |
| Tags | public library, 2014, outlet, fscs |
| Created | 2016-07-27T19:59:02Z |
| Publication Date | 2016-09-29T21:19:55Z |

## Description

Find key information on main libraries, branches, and bookmobiles, including FSCS IDs, square footage, locale code, and location. <br><br>These data include imputed values for libraries that did not submit information in the FY 2014 data collection. Imputation is a procedure for estimating a value for a specific data item where the response is missing.<br><br>Download PLS data files to see imputation flag variables or learn more on the imputation methods used in FY 2014 at <a href="https://www.imls.gov/research-evaluation/data-collection/public-libraries-survey/explore-pls-data/pls-data">https://www.imls.gov/research-evaluation/data-collection/public-libraries-survey/explore-pls-data/pls-data</a>

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| Yes      | series tag     | fscs_id           | FSCS ID           | text      | text        |
| Yes      | series tag     | fscs_id_seq       | FSCS ID_SEQ       | text      | text        |
| Yes      | series tag     | library_id        | LIBRARY ID        | text      | text        |
| Yes      | series tag     | library_name      | LIBRARY NAME      | text      | text        |
| Yes      | series tag     | phone             | PHONE             | text      | number      |
| Yes      | series tag     | county            | COUNTY            | text      | text        |
| Yes      | numeric metric | locale            | LOCALE            | number    | number      |
| Yes      | numeric metric | county_population | COUNTY POPULATION | number    | number      |
| Yes      | series tag     | outlet_type       | OUTLET TYPE       | text      | text        |
| Yes      | numeric metric | sq_feet           | SQ FEET           | number    | number      |
| Yes      | numeric metric | bookmobiles       | BOOKMOBILES       | number    | number      |
| Yes      | numeric metric | hours             | HOURS             | number    | number      |
| Yes      | numeric metric | wks_open          | WEEKS OPEN        | number    | number      |
| Yes      | series tag     | metro_status      | METRO STATUS      | text      | text        |
| Yes      | numeric metric | structure_change  | STRUCTURE CHANGE  | number    | number      |
| Yes      | numeric metric | name_change       | NAME CHANGE       | number    | number      |
| No       |                | address_change    | ADDRESS CHANGE    | number    | number      |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = address_change
```

## Data Commands

```ls
series e:ucdn-7aur d:2014-01-01T00:00:00.000Z t:library_name="ANCHOR POINT PUBLIC LIBRARY" t:phone=9072355692 t:fscs_id=AK0001 t:outlet_type=CE t:library_id=AK0001-002 t:county="KENAI PENINSULA" t:fscs_id_seq=002 t:metro_status=NO m:bookmobiles=0 m:county_population=57477 m:sq_feet=1287 m:hours=1377 m:locale=43 m:structure_change=0 m:name_change=0 m:wks_open=51

series e:ucdn-7aur d:2014-01-01T00:00:00.000Z t:library_name="CHUGIAK/EAGLE RIVER NEIGHBORHOOD LIBRARY" t:phone=9073431530 t:fscs_id=AK0002 t:outlet_type=BR t:library_id=AK0002-007 t:county=ANCHORAGE t:fscs_id_seq=007 t:metro_status=CC m:bookmobiles=0 m:county_population=301010 m:sq_feet=17888 m:hours=2028 m:locale=31 m:structure_change=0 m:name_change=0 m:wks_open=52

series e:ucdn-7aur d:2014-01-01T00:00:00.000Z t:library_name="MULDOON NEIGHBORHOOD LIBRARY" t:phone=9073434223 t:fscs_id=AK0002 t:outlet_type=BR t:library_id=AK0002-008 t:county=ANCHORAGE t:fscs_id_seq=008 t:metro_status=CC m:bookmobiles=0 m:county_population=301010 m:sq_feet=8232 m:hours=1768 m:locale=11 m:structure_change=0 m:name_change=0 m:wks_open=52
```

## Meta Commands

```ls
metric m:locale p:integer l:LOCALE d:"Urban-centric locale code. The geographic location in terms of the size of the community in which it is located and the proximity of that community to urban and metropolitan areas. 11 - City, Large: Territory inside an urbanized area and inside a principal city with population of 250,000 or more. 12 - City, Midsize: Territory inside an urbanized area and inside a principal city with population less than 250,000 and greater than or equal to 100,000. 13 - City, Small: Territory inside an urbanized area and inside a principal city with population less than 100,000. 21 - Suburb, Large: Territory outside a principal city and inside an urbanized area with population of 250,000 or more. 22 - Suburb, Midsize: Territory outside a principal city and inside an urbanized area with population less than 250,000 and greater than or equal to 100,000. 23 - Suburb, Small: Territory outside a principal city and inside an urbanized area with population less than 100,000. 31 - Town, Fringe: Territory inside an urban cluster that is less than or equal to 10 miles from an urbanized area. 32 - Town, Distant: Territory inside an urban cluster that is more than 10 miles and less than or equal to 35 miles from an urbanized area. 33 - Town, Remote: Territory inside an urban cluster that is more than 35 miles from an urbanized area. 41 - Rural, Fringe: Census-defined rural territory that is less than or equal to 5 miles from an urbanized area, as well as rural territory that is less than or equal to 2.5 miles from an urban cluster. 42 - Rural, Distant: Census-defined rural territory that is more than 5 miles but less than or equal to 25 miles from an urbanized area, as well as rural territory that is more than 2.5 miles but less than or equal to 10 miles from an urban cluster. 43 - Rural, Remote: Census-defined rural territory that is more than 25 miles from an urbanized area and is also more than 10 miles from an urban cluster." t:dataTypeName=number

metric m:county_population p:integer l:"COUNTY POPULATION" d:"County population (CNTYPOP)" t:dataTypeName=number

metric m:sq_feet p:integer l:"SQ FEET" d:"Area in square feet of the public library outlet -1 = Missing -3 = Not applicable (SQ_FEET)" t:dataTypeName=number

metric m:bookmobiles p:integer l:BOOKMOBILES d:"Number of bookmobiles (L_NUM_BM)" t:dataTypeName=number

metric m:hours p:integer l:HOURS d:"Public Service Hours Per Year (HOURS)" t:dataTypeName=number

metric m:wks_open p:integer l:"WEEKS OPEN" d:"Number of Weeks a Library is Open (WKS_OPEN)" t:dataTypeName=number

metric m:structure_change p:integer l:"STRUCTURE CHANGE" d:"Structure Change Code 00?No change from last year 01?Existing Administrative Entity or Outlet absorbs another Administrative Entity or Outlet 02?Newly created Administrative Entity or Outlet 03?Closed 04?Move Outlet to a newly created Administrative Entity 05?Merge two or more Administrative Entities or Outlets to form a new Administrative Entity or Outlet 06?(reserved) 07?(reserved) 08?Restored a closed Administrative Entity or Outlet record 09?Restored an incorrectly deleted Administrative Entity or Outlet 10?Delete an incorrect record 11?Outlet moved to a different previously existing Administrative Entity 12?(reserved) 13?Add an existing Administrative Entity or Outlet not previously reported 22?Future Administrative Entity FSCS ID Request 23?Temporary Closure 24?Restore/Undo Was a 23 (Reopen a Temporarily Closed Administrative Entity) (STATSTRU)" t:dataTypeName=number

metric m:name_change p:integer l:"NAME CHANGE" d:"Name Change Code 00?No change from last year 06?Official name change 14?Minor name change (STATNAME)" t:dataTypeName=number

entity e:ucdn-7aur l:"Main Libraries, Branches, and Bookmobiles: FY 2014 Public Libraries Survey (Outlet Data)" t:attribution=IMLS t:url=https://data.imls.gov/api/views/ucdn-7aur

property e:ucdn-7aur t:meta.view v:id=ucdn-7aur v:category="Public Libraries Survey" v:attributionLink=https://www.imls.gov/research-evaluation/data-collection/public-libraries-survey v:averageRating=0 v:name="Main Libraries, Branches, and Bookmobiles: FY 2014 Public Libraries Survey (Outlet Data)" v:attribution=IMLS

property e:ucdn-7aur t:meta.view.license v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:ucdn-7aur t:meta.view.owner v:id=879v-x7gf v:screenName=Marisa v:displayName=Marisa

property e:ucdn-7aur t:meta.view.tableauthor v:id=879v-x7gf v:screenName=Marisa v:roleName=administrator v:displayName=Marisa

property e:ucdn-7aur t:meta.view.metadata.custom_fields.common_core v:Contact_Email=imlsinfo@imls.gov v:Contact_Name="Office of Digital and Information Strategy" v:Bureau_Code=474:00 v:Program_Code=000:000
```

## Top Records

```ls
| fscs_id | fscs_id_seq | library_id | library_name                                  | phone      | county            | locale | county_population | outlet_type | sq_feet | bookmobiles | hours | wks_open | metro_status | structure_change | name_change | address_change | 
| ======= | =========== | ========== | ============================================= | ========== | ================= | ====== | ================= | =========== | ======= | =========== | ===== | ======== | ============ | ================ | =========== | ============== | 
| AK0001  | 002         | AK0001-002 | ANCHOR POINT PUBLIC LIBRARY                   | 9072355692 | KENAI PENINSULA   | 43     | 57477             | CE          | 1287    | 0           | 1377  | 51       | NO           | 0                | 0           | 0              | 
| AK0002  | 007         | AK0002-007 | CHUGIAK/EAGLE RIVER NEIGHBORHOOD LIBRARY      | 9073431530 | ANCHORAGE         | 31     | 301010            | BR          | 17888   | 0           | 2028  | 52       | CC           | 0                | 0           | 0              | 
| AK0002  | 008         | AK0002-008 | MULDOON NEIGHBORHOOD LIBRARY                  | 9073434223 | ANCHORAGE         | 11     | 301010            | BR          | 8232    | 0           | 1768  | 52       | CC           | 0                | 0           | 0              | 
| AK0002  | 010         | AK0002-010 | SCOTT AND WESLEY GERRISH NEIGHBORHOOD LIBRARY | 9073434024 | ANCHORAGE         | 42     | 301010            | BR          | 3938    | 0           | 1716  | 52       | CC           | 0                | 0           | 0              | 
| AK0002  | 011         | AK0002-011 | Z. J. LOUSSAC LIBRARY                         | 9073432975 | ANCHORAGE         | 11     | 301010            | CE          | 140000  | 0           | 3328  | 52       | CC           | 0                | 0           | 0              | 
| AK0002  | 012         | AK0002-012 | MOUNTAIN VIEW NEIGHBORHOOD LIBRARY            | 9073432818 | ANCHORAGE         | 11     | 301010            | BR          | 10704   | 0           | 1768  | 52       | CC           | 0                | 0           | 0              | 
| AK0003  | 002         | AK0003-002 | ANDERSON VILLAGE LIBRARY                      | 9075822628 | DENALI            | 43     | 1921              | CE          | 3041    | 0           | 480   | 48       | NO           | 0                | 0           | 0              | 
| AK0006  | 002         | AK0006-002 | KUSKOKWIM CONSORTIUM LIBRARY                  | 9075434516 | BETHEL            | 33     | 17868             | CE          | 3656    | 0           | 2912  | 52       | NO           | 0                | 0           | 0              | 
| AK0007  | 002         | AK0007-002 | BIG LAKE PUBLIC LIBRARY                       | 9078926475 | MATANUSKA-SUSITNA | 42     | 97882             | CE          | 6940    | 0           | 2548  | 52       | NO           | 0                | 0           | 0              | 
| AK0008  | 002         | AK0008-002 | CANTWELL COMMUNITY LIBRARY                    | 9077682372 | DENALI            | 43     | 1921              | CE          | 1363    | 0           | 750   | 48       | NO           | 0                | 0           | 0              | 
```