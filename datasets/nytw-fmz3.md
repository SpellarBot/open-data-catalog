# Missouri Alcohol Licenses Out of Business

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/missouri-alcohol-licenses-out-of-business-073b0) |
| Metadata | [Link](https://data.mo.gov/api/views/nytw-fmz3) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/nytw-fmz3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/nytw-fmz3/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | nytw-fmz3 |
| Name | Missouri Alcohol Licenses Out of Business |
| Attribution | Missouri Division of Alcohol and Tobacco Control |
| Category | Regulatory |
| Tags | missouri, liquor, alcohol, license, out of business |
| Created | 2012-07-12T13:50:53Z |
| Publication Date | 2017-04-20T12:55:27Z |

## Description

List of alcohol licenses of businesses who have gone out of business

## Columns

```ls
| Included | Schema Type | Field Name             | Name                   | Data Type     | Render Type   |
| ======== | =========== | ====================== | ====================== | ============= | ============= |
| Yes      | series tag  | license_number         | License Number         | text          | number        |
| Yes      | series tag  | licensee_name          | Licensee Name          | text          | text          |
| Yes      | series tag  | dba_name               | DBA Name               | text          | text          |
| Yes      | series tag  | business_type          | Business Type          | text          | text          |
| Yes      | series tag  | license_type           | License Type           | text          | text          |
| Yes      | series tag  | license_current_status | License Current Status | text          | text          |
| Yes      | time        | status_effective_date  | Status Effective Date  | calendar_date | calendar_date |
| Yes      | series tag  | district               | District               | text          | text          |
| Yes      | series tag  | sub_district           | Sub District           | text          | text          |
| Yes      | series tag  | county_number          | County Number          | text          | text          |
| Yes      | series tag  | street_number          | Street Number          | text          | number        |
| Yes      | series tag  | street_name            | Street Name            | text          | text          |
| Yes      | series tag  | city                   | City                   | text          | text          |
| Yes      | series tag  | state                  | State                  | text          | text          |
| Yes      | series tag  | zip_code               | Zip Code               | text          | number        |
```

## Time Field

```ls
Value = status_effective_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:nytw-fmz3 d:2017-02-21T00:00:00.000Z t:sub_district=00 t:license_type=RBD t:county_number=FRANKLIN t:zip_code=630841802 t:license_number=2796 t:street_name="S. CHURCH" t:state=MO t:dba_name="ELMER'S TAVERN" t:license_current_status=OB t:city=UNION t:licensee_name="OVERSCHMIDT, FRANCIS" t:street_number=2 t:business_type=O t:district=2 m:row_number.nytw-fmz3=1

series e:nytw-fmz3 d:2017-02-27T00:00:00.000Z t:sub_district=00 t:license_type=RBD t:county_number=JACKSON t:zip_code=64106 t:license_number=4317 t:street_name="GRAND AVENUE" t:state=MO t:dba_name="ANTHONY'S RESTAURANT & LOUNGE" t:license_current_status=OB t:city="KANSAS CITY" t:licensee_name="SPINO, ANTHONY J." t:street_number=701 t:business_type=O t:district=1 m:row_number.nytw-fmz3=2

series e:nytw-fmz3 d:2017-03-28T00:00:00.000Z t:sub_district=00 t:license_type=OPL t:county_number="ST. LOUIS CO." t:zip_code=63121 t:license_number=11187 t:street_name="S FLORISSANT ROAD" t:state=MO t:dba_name="SCHNUCK MARKETS #140" t:license_current_status=OB t:city="COOL VALLEY" t:licensee_name="SCHNUCK MARKETS INC." t:street_number=1225 t:business_type=C t:district=3 m:row_number.nytw-fmz3=3
```

## Meta Commands

```ls
metric m:row_number.nytw-fmz3 p:long l:"Row Number"

entity e:nytw-fmz3 l:"Missouri Alcohol Licenses Out of Business" t:attribution="Missouri Division of Alcohol and Tobacco Control" t:url=https://data.mo.gov/api/views/nytw-fmz3

property e:nytw-fmz3 t:meta.view v:id=nytw-fmz3 v:category=Regulatory v:attributionLink=http://www.atc.dps.mo.gov v:averageRating=0 v:name="Missouri Alcohol Licenses Out of Business" v:attribution="Missouri Division of Alcohol and Tobacco Control"

property e:nytw-fmz3 t:meta.view.owner v:id=gytm-8bsj v:screenName="Rob Gourley" v:displayName="Rob Gourley"

property e:nytw-fmz3 t:meta.view.tableauthor v:id=gytm-8bsj v:screenName="Rob Gourley" v:roleName=editor v:displayName="Rob Gourley"
```

## Top Records

```ls
| license_number | licensee_name                   | dba_name                                | business_type | license_type | license_current_status | status_effective_date | district | sub_district | county_number  | street_number | street_name       | city           | state | zip_code  | 
| ============== | =============================== | ======================================= | ============= | ============ | ====================== | ===================== | ======== | ============ | ============== | ============= | ================= | ============== | ===== | ========= | 
| 2796           | OVERSCHMIDT, FRANCIS            | ELMER'S TAVERN                          | O             | RBD          | OB                     | 2017-02-21T00:00:00   | 2        | 00           | FRANKLIN       | 2             | S. CHURCH         | UNION          | MO    | 630841802 | 
| 4317           | SPINO, ANTHONY J.               | ANTHONY'S RESTAURANT & LOUNGE           | O             | RBD          | OB                     | 2017-02-27T00:00:00   | 1        | 00           | JACKSON        | 701           | GRAND AVENUE      | KANSAS CITY    | MO    | 64106     | 
| 11187          | SCHNUCK MARKETS INC.            | SCHNUCK MARKETS #140                    | C             | OPL          | OB                     | 2017-03-28T00:00:00   | 3        | 00           | ST. LOUIS CO.  | 1225          | S FLORISSANT ROAD | COOL VALLEY    | MO    | 63121     | 
| 12417          | HURNS, JUDGE                    | HURNS LOUNGE                            | O             | RBD          | OB                     | 2017-03-28T00:00:00   | 3        | 00           | ST. LOUIS CITY | 3648          | HEBERT STREET     | ST LOUIS       | MO    | 63107     | 
| 35783          | MOFFATT, RICHARD L. & PAMELA S. | STAR LANES                              | P             | 5BDW         | OB                     | 2017-03-10T00:00:00   | 5        | 00           | JASPER         | 219           | E 3RD STREET      | CARTHAGE       | MO    | 64836     | 
| 36091          | MFA PETROLEUM COMPANY           | BREAK TIME #3023                        | C             | OPL          | OB                     | 2017-04-11T00:00:00   | 2        | 00           | BOONE          | 200           | N PROVIDENCE ROAD | COLUMBIA       | MO    | 65201     | 
| 54029          | ROZIER MERCANTILE COMPANY       | ROZIERS FOOD CENTER                     | C             | OPL          | OB                     | 2017-04-07T00:00:00   | 4        | 00           | PERRY          | 217           | N MAIN STREET     | PERRYVILLE     | MO    | 63775     | 
| 64547          | C MART INC.                     | PARK HILLS C MART                       | C             | OPL          | OB                     | 2017-03-22T00:00:00   | 4        | 00           | ST. FRANCOIS   | 900           | E MAIN STREET     | PARK HILLS     | MO    | 636012718 | 
| 76126          | SMITH, JERRY L.                 | RIVER RIDGE WINERY                      | O             | DOMW         | OB                     | 2017-04-17T00:00:00   | 4        | 00           | SCOTT          | 883           | C.R. 321          | COMMERCE       | MO    | 637420000 | 
| 81242          | JEFF CATERING COMPANY INC.      | CAPITAL PLAZA HOTEL & CONVENTION CENTER | C             | RBD          | OB                     | 2017-04-07T00:00:00   | 2        | 00           | COLE           | 415           | W MCCARTY STREET  | JEFFERSON CITY | MO    | 65101     | 
```