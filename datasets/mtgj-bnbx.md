# Missouri Alcohol Licenses Not Renewed for the New License Year

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/missouri-alcohol-licenses-not-renewed-4eb86) |
| Metadata | [Link](https://data.mo.gov/api/views/mtgj-bnbx) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/mtgj-bnbx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/mtgj-bnbx/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | mtgj-bnbx |
| Name | Missouri Alcohol Licenses Not Renewed for the New License Year |
| Attribution | Missouri Division of Alcohol and Tobacco Control |
| Category | Regulatory |
| Tags | missouri, alcohol, liquor, licenses, renew |
| Created | 2012-07-12T14:06:21Z |
| Publication Date | 2017-04-20T13:16:33Z |

## Description

List of Missouri alcohol licenses not yet renewed for the next license year.  License year begins July 1.  This dataset is generated nightly during the months of April through July for the license renewal period.  This dataset will be empty the rest of the year.

## Columns

```ls
| Included | Schema Type | Field Name     | Name           | Data Type | Render Type |
| ======== | =========== | ============== | ============== | ========= | =========== |
| No       | time        | :updated_at    | updated_at     | meta_data | meta_data   |
| Yes      | series tag  | license_number | License Number | text      | number      |
| Yes      | series tag  | licensee_name  | Licensee Name  | text      | text        |
| Yes      | series tag  | dba_name       | DBA Name       | text      | text        |
| Yes      | series tag  | license_type   | License Type   | text      | text        |
| Yes      | series tag  | district       | District       | text      | text        |
| Yes      | series tag  | sub_district   | Sub District   | text      | text        |
| Yes      | series tag  | county         | County         | text      | text        |
| Yes      | series tag  | street_number  | Street Number  | text      | number      |
| Yes      | series tag  | street_name    | Street Name    | text      | text        |
| Yes      | series tag  | city           | City           | text      | text        |
| Yes      | series tag  | state          | State          | text      | text        |
| Yes      | series tag  | zip_code       | Zip Code       | text      | number      |
| Yes      | series tag  | last_name      | Last Name      | text      | text        |
| Yes      | series tag  | first_name     | First Name     | text      | text        |
| Yes      | series tag  | business_phone | Business Phone | text      | text        |
| No       |             | renewal_date   | Renewal Date   | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = renewal_date
```

## Data Commands

```ls
series e:mtgj-bnbx d:2017-04-20T13:16:12.000Z t:sub_district=00 t:license_type=RBD t:zip_code=63501 t:license_number=16 t:street_name="E ILLINOIS" t:state=MO t:dba_name="LODGE 1751" t:city=KIRKSVILLE t:first_name=JAMES t:licensee_name="LOYAL ORDER OF MOOSE 1751" t:county=001 t:last_name=VANSICKEL t:street_number=2405 t:district=2 m:row_number.mtgj-bnbx=1

series e:mtgj-bnbx d:2017-04-20T13:16:12.000Z t:sub_district=00 t:license_type=COL t:zip_code=644851652 t:license_number=70 t:street_name="E DUNCAN DRIVE" t:state=MO t:dba_name="CLASBEY COMMUNITY CENTER" t:city=SAVANNAH t:first_name=BETH t:licensee_name="CLASBEY COMMUNITY CENTER" t:county=002 t:last_name=KAR t:street_number=400 t:district=1 m:row_number.mtgj-bnbx=2

series e:mtgj-bnbx d:2017-04-20T13:16:12.000Z t:sub_district=00 t:license_type=RBD t:zip_code=65265 t:license_number=148 t:street_name="E LIBERTY" t:state=MO t:dba_name="MEXICO COUNTRY CLUB" t:city=MEXICO t:first_name=JOSEPH t:licensee_name="MEXICO COUNTRY CLUB" t:county=004 t:last_name=HENDRIX t:street_number=1801 t:district=2 m:row_number.mtgj-bnbx=3
```

## Meta Commands

```ls
metric m:row_number.mtgj-bnbx p:long l:"Row Number"

entity e:mtgj-bnbx l:"Missouri Alcohol Licenses Not Renewed for the New License Year" t:attribution="Missouri Division of Alcohol and Tobacco Control" t:url=https://data.mo.gov/api/views/mtgj-bnbx

property e:mtgj-bnbx t:meta.view v:id=mtgj-bnbx v:category=Regulatory v:attributionLink=http://www.atc.dps.mo.gov v:averageRating=0 v:name="Missouri Alcohol Licenses Not Renewed for the New License Year" v:attribution="Missouri Division of Alcohol and Tobacco Control"

property e:mtgj-bnbx t:meta.view.owner v:id=gytm-8bsj v:screenName="Rob Gourley" v:displayName="Rob Gourley"

property e:mtgj-bnbx t:meta.view.tableauthor v:id=gytm-8bsj v:screenName="Rob Gourley" v:roleName=editor v:displayName="Rob Gourley"
```

## Top Records

```ls
| :updated_at | license_number | licensee_name                           | dba_name                  | license_type | district | sub_district | county | street_number | street_name       | city       | state | zip_code  | last_name | first_name | business_phone | renewal_date | 
| =========== | ============== | ======================================= | ========================= | ============ | ======== | ============ | ====== | ============= | ================= | ========== | ===== | ========= | ========= | ========== | ============== | ============ | 
| 1492694172  | 16             | LOYAL ORDER OF MOOSE 1751               | LODGE 1751                | RBD          | 2        | 00           | 001    | 2405          | E ILLINOIS        | KIRKSVILLE | MO    | 63501     | VANSICKEL | JAMES      |                | 04/08/2016   | 
| 1492694172  | 70             | CLASBEY COMMUNITY CENTER                | CLASBEY COMMUNITY CENTER  | COL          | 1        | 00           | 002    | 400           | E DUNCAN DRIVE    | SAVANNAH   | MO    | 644851652 | KAR       | BETH       |                | 05/06/2016   | 
| 1492694172  | 148            | MEXICO COUNTRY CLUB                     | MEXICO COUNTRY CLUB       | RBD          | 2        | 00           | 004    | 1801          | E LIBERTY         | MEXICO     | MO    | 65265     | HENDRIX   | JOSEPH     |                | 05/04/2016   | 
| 1492694172  | 150            | LOYAL ORDER OF MOOSE 1706               | LODGE 1706                | RBD          | 2        | 00           | 004    | 205           | S ELMWOOD DRIVE   | MEXICO     | MO    | 65265     | SHAW      | PATRICK    |                | 04/21/2016   | 
| 1492694172  | 464            | BENEVOLENT PROTECTIVE ORDER OF ELKS 594 | LODGE 594                 | RBDE         | 2        | 00           | 010    | 4747          | E. ELK PARK DRIVE | COLUMBIA   | MO    | 65201     | FISCHBACH | DANIEL     |                | 05/10/2016   | 
| 1492694172  | 467            | FRATERNAL ORDER OF EAGLES 2730          | AERIE 2730                | RBD          | 2        | 00           | 010    | 2513          | STADIUM BLVD      | COLUMBIA   | MO    | 65202     | WHEELER   | CHARLES    |                | 06/17/2016   | 
| 1492694172  | 493            | MARANATHA INNS INC.                     | JACK'S GOURMET RESTAURANT | RBD          | 2        | 00           | 010    | 1903          | BUS LOOP 70 EAST  | COLUMBIA   | MO    | 652015558 | NAYLOR    | MELISSA    |                | 05/05/2016   | 
| 1492694172  | 506            | VETERANS OF FOREIGN WARS                | BOONE COUNTY POST 280     | RBD          | 2        | 00           | 010    | 1509          | ASHLEY ST.        | COLUMBIA   | MO    | 652014602 | BRIGGS    | DONALD     |                | 07/29/2016   | 
| 1492694172  | 546            | DILLON STORES DIVISION INC.             | GERBES SUPER MARKET #125  | OPL          | 2        | 00           | 010    | 2900          | N PARIS ROAD      | COLUMBIA   | MO    | 65201     | MAULLER   | CONNIE     |                | 04/22/2016   | 
| 1492694172  | 681            | AMERICAN LEGION 359                     | PONY EXPRESS POST 359     | RBD          | 1        | 00           | 011    | 2414          | S. 4TH ST.        | ST. JOSEPH | MO    | 645013718 | PARKER    | BLAKELEY   |                | 04/28/2016   | 
```