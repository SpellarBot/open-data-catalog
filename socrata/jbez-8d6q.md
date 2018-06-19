# Table 18.07 MOTOR VEHICLES REGISTERED, BY COUNTY 1995 TO 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/table-18-07-motor-vehicles-registered-by-county-1995-to-2013) |
| Metadata | [Link](https://data.hawaii.gov/api/views/jbez-8d6q) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/jbez-8d6q/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/jbez-8d6q/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | jbez-8d6q |
| Name | Table 18.07 MOTOR VEHICLES REGISTERED, BY COUNTY 1995 TO 2014 |
| Attribution | Department of Economic Development and Tourism |
| Category | Economic Development |
| Tags | cars, vehicles |
| Created | 2012-08-28T00:04:58Z |
| Publication Date | 2015-10-13T02:15:51Z |

## Description

* Taxable and exempt vehicles.  							
* Includes passenger cars, ambulances, buses, trucks, motorcycles and vehicles registered but subsequently scrapped or shipped out of State.  							
* Exclude trailers and semi-trailers							
     Source:  Hawaii State Department of Transportation, Safe Communities Program, records.

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                        | Data Type | Render Type |
| ======== | ============== | =========================== | =========================== | ========= | =========== |
| Yes      | time           | year                        | Year                        | number    | text        |
| Yes      | numeric metric | state_total                 | State total                 | number    | number      |
| Yes      | numeric metric | city_and_county_of_honolulu | City and County of Honolulu | number    | number      |
| Yes      | numeric metric | county_of_hawaii            | County of Hawaii            | number    | number      |
| Yes      | numeric metric | county_of_kauai             | County of Kauai             | number    | number      |
| Yes      | numeric metric | county_of_maui              | County of Maui              | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:jbez-8d6q d:1995-01-01T00:00:00.000Z m:state_total=877756 m:county_of_hawaii=111624 m:city_and_county_of_honolulu=601239 m:county_of_kauai=52364 m:county_of_maui=112529

series e:jbez-8d6q d:1996-01-01T00:00:00.000Z m:state_total=884617 m:county_of_hawaii=115647 m:city_and_county_of_honolulu=598772 m:county_of_kauai=52984 m:county_of_maui=117214

series e:jbez-8d6q d:1997-01-01T00:00:00.000Z m:state_total=884267 m:county_of_hawaii=118364 m:city_and_county_of_honolulu=595121 m:county_of_kauai=53904 m:county_of_maui=116878
```

## Meta Commands

```ls
metric m:state_total p:integer l:"State total" t:dataTypeName=number

metric m:city_and_county_of_honolulu p:integer l:"City and County of Honolulu" t:dataTypeName=number

metric m:county_of_hawaii p:integer l:"County of Hawaii" t:dataTypeName=number

metric m:county_of_kauai p:integer l:"County of Kauai" t:dataTypeName=number

metric m:county_of_maui p:integer l:"County of Maui" t:dataTypeName=number

entity e:jbez-8d6q l:"Table 18.07  MOTOR VEHICLES REGISTERED, BY COUNTY 1995 TO 2014" t:attribution="Department of Economic Development and Tourism" t:url=https://data.hawaii.gov/api/views/jbez-8d6q

property e:jbez-8d6q t:meta.view v:id=jbez-8d6q v:category="Economic Development" v:attributionLink=http://hawaii.gov/dbedt/economic/databook v:averageRating=0 v:name="Table 18.07  MOTOR VEHICLES REGISTERED, BY COUNTY 1995 TO 2014" v:attribution="Department of Economic Development and Tourism"

property e:jbez-8d6q t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:jbez-8d6q t:meta.view.owner v:id=6k8y-ahyw v:screenName="Yang-Seon Kim" v:displayName="Yang-Seon Kim"

property e:jbez-8d6q t:meta.view.tableauthor v:id=6k8y-ahyw v:screenName="Yang-Seon Kim" v:roleName=editor v:displayName="Yang-Seon Kim"
```

## Top Records

```ls
| year | state_total | city_and_county_of_honolulu | county_of_hawaii | county_of_kauai | county_of_maui | 
| ==== | =========== | =========================== | ================ | =============== | ============== | 
| 1995 | 877756      | 601239                      | 111624           | 52364           | 112529         | 
| 1996 | 884617      | 598772                      | 115647           | 52984           | 117214         | 
| 1997 | 884267      | 595121                      | 118364           | 53904           | 116878         | 
| 1998 | 893427      | 594096                      | 121959           | 56554           | 120818         | 
| 1999 | 906935      | 597610                      | 126039           | 57882           | 125404         | 
| 2000 | 941242      | 614985                      | 132305           | 61316           | 132636         | 
| 2001 | 967146      | 631232                      | 136786           | 62655           | 136473         | 
| 2002 | 987598      | 643810                      | 142150           | 63580           | 138058         | 
| 2003 | 1030845     | 667565                      | 150983           | 67312           | 144985         | 
| 2004 | 1072211     | 688163                      | 159627           | 71517           | 152904         | 
```