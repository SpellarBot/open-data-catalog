# Missouri Active Alcohol License Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/missouri-active-alcohol-license-data-af6fa) |
| Metadata | [Link](https://data.mo.gov/api/views/yyhn-562y) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/yyhn-562y/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/yyhn-562y/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | yyhn-562y |
| Name | Missouri Active Alcohol License Data |
| Category | Regulatory |
| Tags | alcohol, wine, beer, license, shipping, manufacturer, missouri, atc, alcohol and tobacco control |
| Created | 2012-05-07T13:37:44Z |
| Publication Date | 2017-04-21T02:09:12Z |

## Description

Current license information of businesses involved in the manufacture, shipping, and/or sale of alcohol in the State of Missouri

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| No       | time           | :updated_at       | updated_at        | meta_data | meta_data   |
| Yes      | series tag     | licensee          | LICENSEE          | text      | text        |
| Yes      | series tag     | dbaname           | DBANAME           | text      | text        |
| Yes      | series tag     | street_number     | STREET NUMBER     | text      | text        |
| Yes      | series tag     | street            | STREET            | text      | text        |
| Yes      | series tag     | city              | CITY              | text      | text        |
| Yes      | series tag     | state             | STATE             | text      | text        |
| Yes      | series tag     | zipcode           | ZIPCODE           | text      | text        |
| Yes      | series tag     | phone_number      | PHONE NUMBER      | text      | text        |
| Yes      | numeric metric | primary_license   | PRIMARY LICENSE   | number    | number      |
| Yes      | numeric metric | secondary_license | SECONDARY LICENSE | number    | number      |
| Yes      | series tag     | primary_type      | PRIMARY TYPE      | text      | text        |
| Yes      | series tag     | secondary_type    | SECONDARY TYPE    | text      | text        |
| Yes      | series tag     | county            | COUNTY            | text      | text        |
| Yes      | series tag     | district          | DISTRICT          | text      | text        |
| Yes      | series tag     | subdist           | SUBDIST           | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:yyhn-562y d:2017-04-21T02:06:47.000Z t:phone_number=6606653312 t:county=ADAIR t:street="S BALTIMORE" t:zipcode=63501 t:state=MO t:primary_type=RBD t:street_number=2401 t:district=2 t:licensee="EL KADIR SHRINE ASSN. INC." t:subdist=00 t:city=KIRKSVILLE m:secondary_license=0 m:primary_license=7

series e:yyhn-562y d:2017-04-21T02:06:47.000Z t:phone_number=6606658300 t:county=ADAIR t:street="E ILLINOIS" t:zipcode=63501 t:state=MO t:primary_type=RBD t:street_number=2405 t:district=2 t:licensee="LOYAL ORDER OF MOOSE 1751" t:subdist=00 t:dbaname="LODGE 1751" t:city=KIRKSVILLE m:secondary_license=0 m:primary_license=16

series e:yyhn-562y d:2017-04-21T02:06:47.000Z t:phone_number=8163243315 t:county=ANDREW t:street="E DUNCAN DRIVE" t:zipcode=644851652 t:state=MO t:primary_type=COL t:street_number=400 t:district=1 t:licensee="CLASBEY COMMUNITY CENTER" t:subdist=00 t:dbaname="CLASBEY COMMUNITY CENTER" t:city=SAVANNAH m:secondary_license=0 m:primary_license=70
```

## Meta Commands

```ls
metric m:primary_license p:long l:"PRIMARY LICENSE" t:dataTypeName=number

metric m:secondary_license p:long l:"SECONDARY LICENSE" t:dataTypeName=number

entity e:yyhn-562y l:"Missouri Active Alcohol License Data" t:url=https://data.mo.gov/api/views/yyhn-562y

property e:yyhn-562y t:meta.view v:id=yyhn-562y v:category=Regulatory v:averageRating=0 v:name="Missouri Active Alcohol License Data"

property e:yyhn-562y t:meta.view.owner v:id=gytm-8bsj v:screenName="Rob Gourley" v:displayName="Rob Gourley"

property e:yyhn-562y t:meta.view.tableauthor v:id=gytm-8bsj v:screenName="Rob Gourley" v:roleName=editor v:displayName="Rob Gourley"
```

## Top Records

```ls
| :updated_at | licensee                                | dbaname                  | street_number | street            | city       | state | zipcode   | phone_number | primary_license | secondary_license | primary_type | secondary_type | county  | district | subdist | 
| =========== | ======================================= | ======================== | ============= | ================= | ========== | ===== | ========= | ============ | =============== | ================= | ============ | ============== | ======= | ======== | ======= | 
| 1492740407  | EL KADIR SHRINE ASSN. INC.              |                          | 2401          | S BALTIMORE       | KIRKSVILLE | MO    | 63501     | 6606653312   | 7               | 0                 | RBD          |                | ADAIR   | 2        | 00      | 
| 1492740407  | LOYAL ORDER OF MOOSE 1751               | LODGE 1751               | 2405          | E ILLINOIS        | KIRKSVILLE | MO    | 63501     | 6606658300   | 16              | 0                 | RBD          |                | ADAIR   | 2        | 00      | 
| 1492740407  | CLASBEY COMMUNITY CENTER                | CLASBEY COMMUNITY CENTER | 400           | E DUNCAN DRIVE    | SAVANNAH   | MO    | 644851652 | 8163243315   | 70              | 0                 | COL          |                | ANDREW  | 1        | 00      | 
| 1492740407  | KNIGHTS OF COLUMBUS                     | JOHN J. DILLON KC CLUB   |               | HWY 15 NORTH      | MEXICO     | MO    | 65265     | 5735811550   | 135             | 0                 | COL          |                | AUDRAIN | 2        | 00      | 
| 1492740407  | MEXICO COUNTRY CLUB                     | MEXICO COUNTRY CLUB      | 1801          | E LIBERTY         | MEXICO     | MO    | 65265     | 5735815374   | 148             | 157               | RBD          | SBD            | AUDRAIN | 2        | 00      | 
| 1492740407  | LOYAL ORDER OF MOOSE 1706               | LODGE 1706               | 205           | S ELMWOOD DRIVE   | MEXICO     | MO    | 65265     | 5735812288   | 150             | 0                 | RBD          |                | AUDRAIN | 2        | 00      | 
| 1492740407  | CANA INC.                               | STELL'S PACKAGE STORE    | 1305          | E CLEVELAND AVE   | MONETT     | MO    | 657081852 | 4172357949   | 219             | 0                 | OPL          |                | BARRY   | 5        | 00      | 
| 1492740407  | BOWERS, EMERY L. JR.                    | BOWERS TOBACCO STORE     |               | MAIN STREET       | AMORET     | MO    | 64722     | 6609253333   | 294             | 0                 | OPL          |                | BATES   | 5        | 00      | 
| 1492740407  | COUNTRY CLUB OF MISSOURI                |                          | 1300          | WOODRAIL AVE      | COLUMBIA   | MO    | 652030920 | 5734497201   | 463             | 519               | RBD          | SBD            | BOONE   | 2        | 00      | 
| 1492740407  | BENEVOLENT PROTECTIVE ORDER OF ELKS 594 | LODGE 594                | 4747          | E. ELK PARK DRIVE | COLUMBIA   | MO    | 65201     | 5734426416   | 464             | 28639             | RBDE         | SBD            | BOONE   | 2        | 00      | 
```