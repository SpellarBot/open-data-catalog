# BusinessesWithBusinessTaxCertificates

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/businesseswithbusinesstaxcertificates) |
| Metadata | [Link](https://data.srcity.org/api/views/fzpk-irzm) |
| Data: JSON | [100 Rows](https://data.srcity.org/api/views/fzpk-irzm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.srcity.org/api/views/fzpk-irzm/rows.csv?max_rows=100) |
| Host | data.srcity.org |
| Id | fzpk-irzm |
| Name | BusinessesWithBusinessTaxCertificates |
| Created | 2016-12-23T00:12:08Z |
| Publication Date | 2017-01-20T15:38:37Z |

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| Yes      | numeric metric | cert                    | Cert #                  | number    | number      |
| Yes      | series tag     | business_name           | Business Name           | text      | text        |
| Yes      | series tag     | dba                     | DBA                     | text      | text        |
| Yes      | series tag     | business_location1      | Business Location1      | text      | text        |
| Yes      | series tag     | business_location_2     | Business Location 2     | text      | text        |
| Yes      | series tag     | business_location_city  | Business Location City  | text      | text        |
| Yes      | series tag     | business_location_state | Business Location State | text      | text        |
| Yes      | series tag     | business_zip_code       | Business Zip Code       | text      | number      |
| Yes      | time           | cert_exp_date           | Cert Exp Date           | date      | date        |
| Yes      | series tag     | business_category       | Business Category       | text      | text        |
```

## Time Field

```ls
Value = cert_exp_date
Format & Zone = seconds
```

## Data Commands

```ls
series e:fzpk-irzm d:2016-12-31T00:00:00.000Z t:business_name="SHADOW CREEK APARTMENTS" t:business_zip_code=954050000 t:business_location1="4145 SHADOW LN" t:business_category="PROP RENTAL-RESIDENTIAL" t:business_location_city="SANTA ROSA" t:business_location_state=CA m:cert=9997039587

series e:fzpk-irzm d:2016-12-31T00:00:00.000Z t:business_name="LUSTIG AL" t:business_zip_code=95419 t:business_location1="88 SYLVANIA AVENUE" t:business_category="CONTRACTORS - MISCELLANEOUS" t:business_location_city="CAMP MEEKER" t:dba="AL LUSTIG REMODELING COMPANY" t:business_location_state=CA m:cert=9997048887

series e:fzpk-irzm d:2016-12-31T00:00:00.000Z t:business_name="M K M LLC" t:business_zip_code=95403 t:business_location1="2002 RED OAK CIRCLE" t:business_category="RETAIL - MISCELLANEOUS" t:business_location_city="SANTA ROSA" t:dba="M.K.M LLC" t:business_location_state=CA m:cert=9997035393
```

## Meta Commands

```ls
metric m:cert p:long l:"Cert #" t:dataTypeName=number

entity e:fzpk-irzm l:BusinessesWithBusinessTaxCertificates t:url=https://data.srcity.org/api/views/fzpk-irzm

property e:fzpk-irzm t:meta.view v:id=fzpk-irzm v:averageRating=0 v:name=BusinessesWithBusinessTaxCertificates

property e:fzpk-irzm t:meta.view.owner v:id=v4p4-re39 v:screenName="OpenData, RO" v:displayName="OpenData, RO"

property e:fzpk-irzm t:meta.view.tableauthor v:id=v4p4-re39 v:screenName="OpenData, RO" v:roleName=administrator v:displayName="OpenData, RO"
```

## Top Records

```ls
| cert       | business_name                     | dba                                   | business_location1      | business_location_2 | business_location_city | business_location_state | business_zip_code | cert_exp_date | business_category           | 
| ========== | ================================= | ===================================== | ======================= | =================== | ====================== | ======================= | ================= | ============= | =========================== | 
| 9997039587 | SHADOW CREEK APARTMENTS           |                                       | 4145 SHADOW LN          |                     | SANTA ROSA             | CA                      | 954050000         | 1483142400    | PROP RENTAL-RESIDENTIAL     | 
| 9997048887 | LUSTIG AL                         | AL LUSTIG REMODELING COMPANY          | 88 SYLVANIA AVENUE      |                     | CAMP MEEKER            | CA                      | 95419             | 1483142400    | CONTRACTORS - MISCELLANEOUS | 
| 9997035393 | M K M LLC                         | M.K.M LLC                             | 2002 RED OAK CIRCLE     |                     | SANTA ROSA             | CA                      | 95403             | 1483142400    | RETAIL - MISCELLANEOUS      | 
| 9997048246 | KETRON, BRUCE                     | KETRON AND ASSC, LAW OFFICES OF BRUCE | 1700 SECOND STREET      |                     | NAPA                   | CA                      | 94559             | 1483142400    | ATTORNEYS                   | 
| 9997035008 | SIVCEVIC IREMA                    | SIVCEVIC IREMA                        | 2125 CONTRA COSTA DRIVE |                     | SANTA ROSA             | CA                      | 95405             | 1483142400    | CONSULTANT                  | 
| 9997045763 | BRACEWELL, KELLY                  | BY DESIGN                             | 1911 LYON COURT         |                     | SANTA ROSA             | CA                      | 95403             | 1483142400    | INTERIOR DECORATIONS/DESIGN | 
| 9997037440 | F H BERRY ENTERPRISES INC         | LITTLE CAESARS PIZZA                  | 750 STONY POINT ROAD    |                     | SANTA ROSA             | CA                      | 95407             | 1483142400    | PIZZA PARLOR                | 
| 9997041554 | PSYCHOLOGICAL SERVICES            | PSYCHOLOGICAL SERVICES                | 160 WIKIUP DRIVE #206   |                     | SANTA ROSA             | CA                      | 95403             | 1483142400    | MISCELLANEOUS SERVICE       | 
| 9997045856 | TWIN BRIDGES BEVERAGE COMPANY LLC | SANTA ROSA CELLARS                    | 2341 VENNIE COURT       |                     | SANTA ROSA             | CA                      | 95401             | 1483142400    | RETAIL - MISCELLANEOUS      | 
| 9997035257 | UBIQUITOUS BUSINESS OPERATIONS    | UBO                                   | 5345 ALYSSUM CT         |                     | SANTA ROSA             | CA                      | 95403             | 1483142400    | CORPORATE HEADQUARTERS      | 
```