# Museum Universe Data File FY 2014 Q3

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/museum-universe-data-file-fy-2014-q3) |
| Metadata | [Link](https://data.imls.gov/api/views/5rw9-2vgh) |
| Data: JSON | [100 Rows](https://data.imls.gov/api/views/5rw9-2vgh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.imls.gov/api/views/5rw9-2vgh/rows.csv?max_rows=100) |
| Host | data.imls.gov |
| Id | 5rw9-2vgh |
| Name | Museum Universe Data File FY 2014 Q3 |
| Attribution | IMLS |
| Category | Museum Universe Data File |
| Tags | museums, mudf |
| Created | 2014-06-05T21:31:40Z |
| Publication Date | 2014-06-10T15:29:33Z |

## Description

Browse a list of known museums and related organizations in the United States as of the third quarter of FY 2014. This list contains descriptive information about museums in the 50 states and the District of Columbia based on public records and administrative data.

## Columns

```ls
| Included | Schema Type    | Field Name                                | Name                                      | Data Type     | Render Type   |
| ======== | ============== | ========================================= | ========================================= | ============= | ============= |
| Yes      | series tag     | museum_id                                 | Museum ID                                 | text          | text          |
| Yes      | series tag     | name_of_institution                       | Name of Institution                       | text          | text          |
| Yes      | series tag     | alternative_name_of_institution           | Alternative Name of Institution           | text          | text          |
| Yes      | numeric metric | phone                                     | Phone                                     | number        | text          |
| Yes      | series tag     | web_url                                   | Web URL                                   | url           | url           |
| Yes      | series tag     | museum_type                               | Museum Type                               | text          | text          |
| Yes      | numeric metric | ein                                       | EIN                                       | number        | text          |
| Yes      | series tag     | nteecc                                    | NTEECC                                    | text          | text          |
| Yes      | time           | tax_period_of_latest_return_filled        | Tax Period of Latest Return Filled        | calendar_date | calendar_date |
| Yes      | numeric metric | gross_income                              | Gross Income                              | money         | money         |
| Yes      | numeric metric | total_revenue                             | Total Revenue                             | money         | money         |
| Yes      | series tag     | income_code                               | Income Code                               | text          | text          |
| Yes      | series tag     | nces_locale_code                          | NCES Locale Code                          | text          | text          |
| Yes      | numeric metric | aam_museum_region                         | AAM Museum Region                         | number        | text          |
| Yes      | series tag     | state_code                                | State Code                                | text          | text          |
| Yes      | series tag     | county_code                               | County Code                               | text          | text          |
| Yes      | numeric metric | tract                                     | Tract                                     | number        | text          |
| Yes      | series tag     | block                                     | Block                                     | text          | text          |
| Yes      | numeric metric | minor_civil_division                      | Minor Civil Division                      | number        | text          |
| Yes      | series tag     | place_code                                | Place Code                                | text          | text          |
| Yes      | series tag     | cbsa_code                                 | CBSA Code                                 | text          | text          |
| Yes      | series tag     | msad_code                                 | MSAD Code                                 | text          | text          |
| Yes      | series tag     | micropolitan_area_flag                    | Micropolitan Area Flag                    | text          | text          |
| Yes      | series tag     | country_code                              | Country Code                              | text          | text          |
| Yes      | series tag     | irs_990_flag                              | IRS 990 Flag                              | text          | text          |
| Yes      | series tag     | imls_admin_data_source_flag               | IMLS Admin Data Source Flag               | text          | text          |
| Yes      | series tag     | third_party_source_flag                   | Third Party Source Flag                   | text          | text          |
| Yes      | series tag     | private_grant_foundation_data_source_flag | Private Grant Foundation Data Source Flag | text          | text          |
| No       |                | address                                   | Address                                   | text          | text          |
| Yes      | series tag     | city                                      | City                                      | text          | text          |
| Yes      | series tag     | state                                     | State                                     | text          | text          |
| Yes      | series tag     | zip_code                                  | Zip Code                                  | text          | text          |
```

## Time Field

```ls
Value = tax_period_of_latest_return_filled
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:5rw9-2vgh d:201212-01-01T00:00:00.000Z t:place_code=26895 t:state_code=19 t:zip_code=52626 t:private_grant_foundation_data_source_flag=0 t:micropolitan_area_flag=0 t:state=IA t:block=4114 t:museum_type=HSC t:third_party_source_flag=0 t:imls_admin_data_source_flag=0 t:irs_990_flag=1 t:country_code=840 t:city=FARMINGTON t:name_of_institution="PIONEER HISTORICAL SOCIETY INC" t:museum_id=8401900496 t:income_code=0 t:nces_locale_code=4 t:county_code=177 m:total_revenue=0 m:tract=950200 m:minor_civil_division=91320 m:ein=421396728 m:aam_museum_region=4 m:gross_income=0

series e:5rw9-2vgh d:201212-01-01T00:00:00.000Z t:place_code=12476 t:state_code=39 t:zip_code=44824-0392 t:private_grant_foundation_data_source_flag=0 t:micropolitan_area_flag=1 t:state=OH t:block=6027 t:museum_type=HSC t:cbsa_code=41780 t:third_party_source_flag=0 t:imls_admin_data_source_flag=0 t:irs_990_flag=1 t:country_code=840 t:nteecc=A80 t:city=CASTALIA t:name_of_institution="CASTALIA AREA HISTORICAL SOCIETY INC" t:museum_id=8403901367 t:income_code=0 t:nces_locale_code=3 t:county_code=43 m:total_revenue=0 m:tract=41700 m:minor_civil_division=47572 m:ein=510673158 m:aam_museum_region=4 m:gross_income=0

series e:5rw9-2vgh d:201306-01-01T00:00:00.000Z t:place_code=48000 t:state_code=55 t:zip_code=53703 t:private_grant_foundation_data_source_flag=1 t:micropolitan_area_flag=0 t:web_url=http://www.wisconsinhistory.org t:state=WI t:block=1005 t:museum_type=HSC t:cbsa_code=31540 t:third_party_source_flag=1 t:imls_admin_data_source_flag=0 t:irs_990_flag=0 t:country_code=840 t:nteecc=A82 t:alternative_name_of_institution="WISCONSIN HISTORICAL MUSEUM" t:city=MADISON t:name_of_institution="WISCONSIN HISTORICAL FOUNDATION" t:museum_id=8405500351 t:income_code=7 t:nces_locale_code=1 t:county_code=25 m:total_revenue=5150257 m:phone=6082646555 m:tract=1704 m:minor_civil_division=48000 m:ein=390921093 m:aam_museum_region=4 m:gross_income=5150257
```

## Meta Commands

```ls
metric m:phone p:long l:Phone t:dataTypeName=number

metric m:ein p:integer l:EIN t:dataTypeName=number

metric m:gross_income p:long l:"Gross Income" t:dataTypeName=money

metric m:total_revenue p:long l:"Total Revenue" t:dataTypeName=money

metric m:aam_museum_region p:integer l:"AAM Museum Region" t:dataTypeName=number

metric m:tract p:integer l:Tract t:dataTypeName=number

metric m:minor_civil_division p:integer l:"Minor Civil Division" t:dataTypeName=number

entity e:5rw9-2vgh l:"Museum Universe Data File FY 2014 Q3" t:attribution=IMLS t:url=https://data.imls.gov/api/views/5rw9-2vgh

property e:5rw9-2vgh t:meta.view v:id=5rw9-2vgh v:category="Museum Universe Data File" v:attributionLink=https://www.imls.gov/research-evaluation/data-collection/museum-universe-data-file v:averageRating=0 v:name="Museum Universe Data File FY 2014 Q3" v:attribution=IMLS

property e:5rw9-2vgh t:meta.view.license v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:5rw9-2vgh t:meta.view.owner v:id=b4ig-itd5 v:screenName=Ammie v:displayName=Ammie

property e:5rw9-2vgh t:meta.view.tableauthor v:id=b4ig-itd5 v:screenName=Ammie v:displayName=Ammie

property e:5rw9-2vgh t:meta.view.metadata.custom_fields.common_core v:Contact_Email=imlsinfo@imls.gov v:Contact_Name="Office of Digital and Information Strategy" v:Bureau_Code=474:00 v:Program_Code=000:000
```

## Top Records

```ls
| museum_id  | name_of_institution                                          | alternative_name_of_institution | phone      | web_url                                      | museum_type | ein       | nteecc | tax_period_of_latest_return_filled | gross_income | total_revenue | income_code | nces_locale_code | aam_museum_region | state_code | county_code | tract  | block | minor_civil_division | place_code | cbsa_code | msad_code | micropolitan_area_flag | country_code | irs_990_flag | imls_admin_data_source_flag | third_party_source_flag | private_grant_foundation_data_source_flag | address         | city         | state | zip_code   | 
| ========== | ============================================================ | =============================== | ========== | ============================================ | =========== | ========= | ====== | ================================== | ============ | ============= | =========== | ================ | ================= | ========== | =========== | ====== | ===== | ==================== | ========== | ========= | ========= | ====================== | ============ | ============ | =========================== | ======================= | ========================================= | =============== | ============ | ===== | ========== | 
| 8401900496 | PIONEER HISTORICAL SOCIETY INC                               |                                 |            | [null, null]                                 | HSC         | 421396728 |        | 201212-01-01T00:00:00              | 0            | 0             | 0           | 4                | 4                 | 19         | 177         | 950200 | 4114  | 91320                | 26895      |           |           | 0                      | 840          | 1            | 0                           | 0                       | 0                                         | PO BOX 132      | FARMINGTON   | IA    | 52626      | 
| 8403901367 | CASTALIA AREA HISTORICAL SOCIETY INC                         |                                 |            | [null, null]                                 | HSC         | 510673158 | A80    | 201212-01-01T00:00:00              | 0            | 0             | 0           | 3                | 4                 | 39         | 43          | 41700  | 6027  | 47572                | 12476      | 41780     |           | 1                      | 840          | 1            | 0                           | 0                       | 0                                         | PO BOX 392      | CASTALIA     | OH    | 44824-0392 | 
| 8405500351 | WISCONSIN HISTORICAL FOUNDATION                              | WISCONSIN HISTORICAL MUSEUM     | 6082646555 | [http://www.wisconsinhistory.org, null]      | HSC         | 390921093 | A82    | 201306-01-01T00:00:00              | 5150257      | 5150257       | 7           | 1                | 4                 | 55         | 25          | 1704   | 1005  | 48000                | 48000      | 31540     |           | 0                      | 840          | 0            | 0                           | 1                       | 1                                         | 30 N CARROLL ST | MADISON      | WI    | 53703      | 
| 8405500356 | BERGSTROM-MAHLER MUSEUM INC                                  | BERGSTROM-MAHLER MUSEUM         |            | [http://bergstrom-mahlermuseum.com, null]    | ART         | 390958257 | A51    | 201306-01-01T00:00:00              | 1208142      | 939973        | 6           | 1                | 4                 | 55         | 139         | 3200   | 1005  | 55750                | 55750      | 36780     |           | 0                      | 840          | 1            | 1                           | 1                       | 0                                         | 165 N PARK AVE  | NEENAH       | WI    | 54956-2956 | 
| 8404600051 | WEST RIVER HISTORY CONFERENCE                                |                                 |            | [null, null]                                 | HSC         | 200192264 | A80    | 201212-01-01T00:00:00              | 0            | 0             | 0           | 1                | 5                 | 46         | 103         | 10200  | 2019  | 52980                | 52980      | 39660     |           | 0                      | 840          | 1            | 0                           | 0                       | 0                                         | PO BOX 9276     | RAPID CITY   | SD    | 57709-9276 | 
| 8400400352 | FOUNTAIN HILLS AND LOWER VERDE RIVER VALLEY HISTORICAL SOCIE |                                 |            | [null, null]                                 | HSC         | 860670640 | A82    | 201212-01-01T00:00:00              | 87209        | 67619         | 3           | 2                | 6                 | 4          | 13          | 216818 | 4009  | 92601                | 25300      | 38060     |           | 0                      | 840          | 1            | 0                           | 0                       | 0                                         | PO BOX 17445    | FOUNTAIN HLS | AZ    | 85269-7445 | 
| 8402500192 | ATHENEUM SOCIETY OF WILBRAHAM                                |                                 | 4135964097 | [http://www.wilbrahamatheneum.org, null]     | HSC         |           |        |                                    |              |               |             | 4                | 1                 | 25         | 13          | 813602 | 2006  | 79740                | 79705      | 44140     |           | 0                      | 840          | 0            | 0                           | 1                       | 0                                         | 450 MAIN ST     | WILBRAHAM    | MA    | 1095       | 
| 8404200493 | COLONIAL FLYING CORPS MUSEUM INC                             |                                 |            | [null, null]                                 | GMU         | 231685135 | A50    | 201106-01-01T00:00:00              | 5376         | 2197          | 3           | 2                | 2                 | 42         | 29          | 306503 | 2014  | 53608                | 77144      | 37980     | 33874     | 0                      | 840          | 1            | 0                           | 0                       | 0                                         | PO BOX 481      | TOUGHKENAMON | PA    | 19374-0481 | 
| 8404500077 | CHEROKEE COUNTY HISTORY AND ARTS MUSEUM                      |                                 | 8644893988 | [http://www.cherokeecountyhistory.org, null] | GMU         |           |        |                                    |              |               |             | 3                | 3                 | 45         | 21          | 970601 | 1011  | 91235                | 28060      | 23500     |           | 1                      | 840          | 0            | 0                           | 1                       | 0                                         | 301 COLLEGE DR  | GAFFNEY      | SC    | 29340      | 
| 8400800212 | LINCOLN COUNTY HISTORICAL SOCIETY INC                        |                                 |            | [null, null]                                 | HSC         | 237219469 | A82    | 201212-01-01T00:00:00              | 0            | 0             | 0           | 4                | 5                 | 8          | 73          | 961800 | 2387  | 91824                |            |           |           | 0                      | 840          | 1            | 0                           | 0                       | 0                                         | PO BOX 124      | HUGO         | CO    | 80821-8082 | 
```