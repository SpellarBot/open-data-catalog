# Foreclosure Lis Pendens 1/1/2006 to Current

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/foreclosure-lis-pendens-01012006-to-current) |
| Metadata | [Link](https://data.hartford.gov/api/views/fz26-vcxr) |
| Data: JSON | [100 Rows](https://data.hartford.gov/api/views/fz26-vcxr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hartford.gov/api/views/fz26-vcxr/rows.csv?max_rows=100) |
| Host | data.hartford.gov |
| Id | fz26-vcxr |
| Name | Foreclosure Lis Pendens 1/1/2006 to Current |
| Attribution | City of Hartford |
| Category | Housing / Development |
| Tags | housing, foreclosure, lis pendens, city clerk, hartford, city of hartford |
| Created | 2015-04-01T18:55:38Z |
| Publication Date | 2015-06-02T23:31:20Z |

## Description

Data is extracted from the City Clerk land record database on a monthly basis. The data is updated on the first work week of each month.  Each foreclosure and lis pendens has multiple deeds filed for each transaction, we have summarized the documents to show only one record per property. Some properties we were unable to locate from the City Clerks records.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| Yes      | series tag     | first_grantor_name  | First_GRANTOR_NAME  | text      | text        |
| Yes      | series tag     | first_grantee_name  | First_GRANTEE_NAME  | text      | text        |
| Yes      | series tag     | first_document_type | First_DOCUMENT_TYPE | text      | text        |
| Yes      | series tag     | first_volume        | First_VOLUME        | text      | text        |
| Yes      | series tag     | first_page          | First_PAGE          | text      | text        |
| No       |                | first_deed_address  | First_DEED_ADDRESS  | text      | text        |
| No       |                | gis_address         | GIS_ADDRESS         | text      | text        |
| Yes      | series tag     | gispin              | GISPIN              | text      | text        |
| Yes      | series tag     | luc_description     | LUC_DESCRIPTION     | text      | text        |
| Yes      | series tag     | neighborhood        | NEIGHBORHOOD        | text      | text        |
| No       |                | x                   | X                   | number    | number      |
| No       |                | y                   | Y                   | number    | number      |
| Yes      | numeric metric | livingunits         | LivingUnits         | number    | number      |
| Yes      | time           | recorded_date       | RECORDED_DATE       | text      | text        |
```

## Time Field

```ls
Value = recorded_date
Format & Zone = MM/dd/yyyy
```

## Series Fields

```ls
Excluded Fields = first_deed_address,gis_address,x,y
```

## Data Commands

```ls
series e:fz26-vcxr d:2007-01-02T00:00:00.000Z t:luc_description="RESIDENTIAL ONE FAMILY" t:first_page=0090 t:first_grantor_name="BUTLER AARON" t:gispin=150137007 t:neighborhood="BLUE HILLS" t:first_volume=05805 t:first_document_type="LIS PENDENS" t:first_grantee_name="CONNECTICUT HOUSING FINANCE AUTHORITY" m:livingunits=1

series e:fz26-vcxr d:2007-01-02T00:00:00.000Z t:luc_description="RESIDENTIAL ONE FAMILY" t:first_page=0093 t:first_grantor_name="CLACHAR ANTHONY" t:gispin=218155113 t:neighborhood=NORTHEAST t:first_volume=05805 t:first_document_type="LIS PENDENS" t:first_grantee_name="H S B C BANK USA TRUS" m:livingunits=1

series e:fz26-vcxr d:2007-01-02T00:00:00.000Z t:luc_description="RESIDENTIAL THREE FAMILY" t:first_page=0096 t:first_grantor_name="PEREZ EDWIN" t:gispin=185620091 t:neighborhood="BEHIND THE ROCKS" t:first_volume=05805 t:first_document_type="LIS PENDENS" t:first_grantee_name="OLIVEIRA MANUEL" m:livingunits=3
```

## Meta Commands

```ls
metric m:livingunits p:integer l:LivingUnits t:dataTypeName=number

entity e:fz26-vcxr l:"Foreclosure Lis Pendens 1/1/2006 to Current" t:attribution="City of Hartford" t:url=https://data.hartford.gov/api/views/fz26-vcxr

property e:fz26-vcxr t:meta.view v:id=fz26-vcxr v:category="Housing / Development" v:attributionLink=http://www.hartford.gov v:averageRating=0 v:name="Foreclosure Lis Pendens 1/1/2006 to Current" v:attribution="City of Hartford"

property e:fz26-vcxr t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:fz26-vcxr t:meta.view.owner v:id=cdqe-xcn5 v:screenName=Brett v:displayName=Brett

property e:fz26-vcxr t:meta.view.tableauthor v:id=cdqe-xcn5 v:screenName=Brett v:roleName=administrator v:displayName=Brett
```

## Top Records

```ls
| first_grantor_name         | first_grantee_name                    | first_document_type | first_volume | first_page | first_deed_address       | gis_address           | gispin    | luc_description               | neighborhood     | x       | y      | livingunits | recorded_date | 
| ========================== | ===================================== | =================== | ============ | ========== | ======================== | ===================== | ========= | ============================= | ================ | ======= | ====== | =========== | ============= | 
| FAUSTIN NATHAN             | AVELO MORTGAGE LLC                    | LIS PENDENS         | 06030        | 0252       | MAPLES CONDO UNIT 304    | MAPLES CONDO UNIT 304 |           |                               |                  |         |        |             | 01/02/2008    | 
| BUTLER AARON               | CONNECTICUT HOUSING FINANCE AUTHORITY | LIS PENDENS         | 05805        | 0090       | 151 GRANBY ST LT 2       | 151 GRANBY ST         | 150137007 | RESIDENTIAL ONE FAMILY        | BLUE HILLS       | 1012173 | 848915 | 1           | 01/02/2007    | 
| CLACHAR ANTHONY            | H S B C BANK USA TRUS                 | LIS PENDENS         | 05805        | 0093       | 35 ROCKVILLE ST LT 34 35 | 35 ROCKVILLE ST       | 218155113 | RESIDENTIAL ONE FAMILY        | NORTHEAST        | 1017658 | 848472 | 1           | 01/02/2007    | 
| PEREZ EDWIN                | OLIVEIRA MANUEL                       | LIS PENDENS         | 05805        | 0096       | 93-95 FLATBUSH AV LT 41  | 93 FLATBUSH AV        | 185620091 | RESIDENTIAL THREE FAMILY      | BEHIND THE ROCKS | 1014276 | 831919 | 3           | 01/02/2007    | 
| BANK OF AMERICA            | AMERICAN HOME MORTGAGE SERVICING INC  | LIS PENDENS         | 06174        | 0061       | 399-401 BELLEVUE ST      | 399 BELLEVUE ST       | 263168051 | RESIDENTIAL ONE FAMILY        | CLAY-ARSENAL     | 1021155 | 847297 | 1           | 01/02/2009    | 
| ARZOLA MARIA               | U S BANK NATIONAL ASSOCIATION         | LIS PENDENS         | 06631        | 0274       | 162 NILAN ST LT 37B      | 162 NILAN ST          | 163595008 | RESIDENTIAL ONE FAMILY        | BEHIND THE ROCKS | 1012301 | 830309 | 1           | 01/02/2013    | 
| METROPOLITAN DISTRICT      | ASTORIA FEDERAL MORTGAGE CORP         | LIS PENDENS         | 06770        | 0257       | 12-14-16 SOUTH ST        | 12 SOUTH ST           | 276803010 | APARTMENT BUILDING OR COMPLEX | SOUTH END        | 1021430 | 828953 | 12          | 01/02/2014    | 
| DEJESUS BENICIO            | WEST COAST REALTY SERVICES INC        | LIS PENDENS         | 06770        | 0259       | 42 NEPAUG ST LT 83       | 42 NEPAUG ST          | 143713147 | RESIDENTIAL ONE FAMILY        | SOUTH WEST       | 1011110 | 826938 | 1           | 01/02/2014    | 
| BENEFICIAL FINANCIAL 1 INC | AMERICAN TAX FUNDING LLC              | LIS PENDENS         | 06631        | 0296       | 202 SIGOURNEY ST         | 202 SIGOURNEY ST      | 200264008 | RESIDENTIAL ONE FAMILY        | ASYLUM HILL      | 1015617 | 842318 | 1           | 01/02/2013    | 
| BANK OF AMERICA            | AMERICAN TAX FUNDING LLC              | LIS PENDENS         | 06631        | 0297       | 216-218 VINE ST LT 4     | 216 VINE ST           | 196210080 | RESIDENTIAL TWO FAMILY        | NORTHEAST        | 1016967 | 847270 | 2           | 01/02/2013    | 
```