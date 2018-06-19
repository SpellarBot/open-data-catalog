# Active Iowa Business Entities

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/active-iowa-business-entities) |
| Metadata | [Link](https://data.iowa.gov/api/views/ez5t-3qay) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/ez5t-3qay/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/ez5t-3qay/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | ez5t-3qay |
| Name | Active Iowa Business Entities |
| Attribution | State of Iowa, Secretary of State |
| Category | Economy |
| Tags | corporations, limited liability company, general partnerships, limited liability partnership, non-profit, profit, cooperative, banks, savings & loans, trademarks |
| Created | 2014-11-10T15:20:00Z |
| Publication Date | 2015-08-25T18:08:40Z |

## Description

This dataset provides a list of active business entities, both domestic business organizations (organized under and subject to the laws of Iowa), and foreign business organizations (organized under a law other than Iowa) who are authorized to transact business in the State of Iowa at time of update. The dataset includes the business' legal name, type, effective date, name and address of registered agent, and address of principal office.

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type     | Render Type   |
| ======== | =========== | ================ | ================ | ============= | ============= |
| Yes      | series tag  | corp_number      | Corp Number      | text          | text          |
| Yes      | series tag  | legal_name       | Legal Name       | text          | text          |
| Yes      | series tag  | corporation_type | Corporation Type | text          | text          |
| Yes      | time        | effective_date   | Effective Date   | calendar_date | calendar_date |
| Yes      | series tag  | registered_agent | Registered Agent | text          | text          |
| No       |             | ra_address_1     | RA Address 1     | text          | text          |
| No       |             | ra_address_2     | RA Address 2     | text          | text          |
| Yes      | series tag  | ra_city          | RA City          | text          | text          |
| Yes      | series tag  | ra_state         | RA State         | text          | text          |
| Yes      | series tag  | ra_zip           | RA Zip           | text          | text          |
| Yes      | series tag  | home_office      | Home Office      | text          | text          |
| No       |             | ho_address_1     | HO Address 1     | text          | text          |
| No       |             | ho_address_2     | HO Address 2     | text          | text          |
| Yes      | series tag  | ho_city          | HO City          | text          | text          |
| Yes      | series tag  | ho_state         | HO State         | text          | text          |
| Yes      | series tag  | ho_zip           | HO Zip           | text          | text          |
| Yes      | series tag  | ho_country       | HO Country       | text          | text          |
```

## Time Field

```ls
Value = effective_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = ra_address_1,ra_address_2,ho_address_1,ho_address_2
```

## Data Commands

```ls
series e:ez5t-3qay d:1866-03-19T00:00:00.000Z t:legal_name="ST. PAUL UNITED CHURCH OF CHRIST, DENVER, IOWA" t:ra_city=DENVER t:ra_zip=50622 t:home_office="ST. PAUL UNITED CHURCH OF CHRIST, DENVER, IA" t:ho_city=DENVER t:ho_country=USA t:corporation_type="REVISED DOMESTIC NON-PROFIT" t:registered_agent="CRAIG RADDEN HENDERSON" t:corp_number=087557 t:ra_state=IA t:ho_state=IA t:ho_zip=50622 m:row_number.ez5t-3qay=1

series e:ez5t-3qay d:1992-09-09T00:00:00.000Z t:legal_name="LINDEN INVESTMENTS, L.C." t:ra_city="CEDAR RAPIDS" t:ra_zip=52404 t:ho_city="CEDAR RAPIDS" t:ho_country=USA t:corporation_type="DOMESTIC LIMITED LIABILITY COMPANY" t:registered_agent="MICHAEL K DENNEY" t:corp_number=160645 t:ra_state=IA t:ho_state=IA t:ho_zip=52406 m:row_number.ez5t-3qay=2

series e:ez5t-3qay d:1994-08-24T00:00:00.000Z t:legal_name="FIRST STANDARD, L.C." t:ra_city="CEDAR RAPIDS" t:ra_zip=52404 t:ho_city="CEDAR RAPIDS" t:ho_country=USA t:corporation_type="DOMESTIC LIMITED LIABILITY COMPANY" t:registered_agent="MICHAEL K DENNEY" t:corp_number=178147 t:ra_state=IA t:ho_state=IA t:ho_zip=52406 m:row_number.ez5t-3qay=3
```

## Meta Commands

```ls
metric m:row_number.ez5t-3qay p:long l:"Row Number"

entity e:ez5t-3qay l:"Active Iowa Business Entities" t:attribution="State of Iowa, Secretary of State" t:url=https://data.iowa.gov/api/views/ez5t-3qay

property e:ez5t-3qay t:meta.view v:id=ez5t-3qay v:category=Economy v:averageRating=0 v:name="Active Iowa Business Entities" v:attribution="State of Iowa, Secretary of State"

property e:ez5t-3qay t:meta.view.license v:name="Public Domain"

property e:ez5t-3qay t:meta.view.owner v:id=pm4d-54qc v:profileImageUrlMedium=/api/users/pm4d-54qc/profile_images/THUMB v:profileImageUrlLarge=/api/users/pm4d-54qc/profile_images/LARGE v:screenName="Iowa Secretary of State" v:profileImageUrlSmall=/api/users/pm4d-54qc/profile_images/TINY v:displayName="Iowa Secretary of State"

property e:ez5t-3qay t:meta.view.tableauthor v:id=wnph-iazk v:profileImageUrlMedium=/api/users/wnph-iazk/profile_images/THUMB v:profileImageUrlLarge=/api/users/wnph-iazk/profile_images/LARGE v:screenName="Iowa Secretary of State" v:profileImageUrlSmall=/api/users/wnph-iazk/profile_images/TINY v:displayName="Iowa Secretary of State"
```

## Top Records

```ls
| corp_number | legal_name                                     | corporation_type                   | effective_date      | registered_agent            | ra_address_1           | ra_address_2               | ra_city      | ra_state | ra_zip | home_office                                  | ho_address_1                    | ho_address_2                  | ho_city      | ho_state | ho_zip    | ho_country | 
| =========== | ============================================== | ================================== | =================== | =========================== | ====================== | ========================== | ============ | ======== | ====== | ============================================ | =============================== | ============================= | ============ | ======== | ========= | ========== | 
| 087557      | ST. PAUL UNITED CHURCH OF CHRIST, DENVER, IOWA | REVISED DOMESTIC NON-PROFIT        | 1866-03-19T00:00:00 | CRAIG RADDEN HENDERSON      | 300 WASHINGTON ST      |                            | DENVER       | IA       | 50622  | ST. PAUL UNITED CHURCH OF CHRIST, DENVER, IA | 300 WASHINGTON ST               | BOX 382                       | DENVER       | IA       | 50622     | USA        | 
| 160645      | LINDEN INVESTMENTS, L.C.                       | DOMESTIC LIMITED LIABILITY COMPANY | 1992-09-09T00:00:00 | MICHAEL K DENNEY            | 4150 C STREET SW       |                            | CEDAR RAPIDS | IA       | 52404  |                                              | 4150 C STREET SW                | PO BOX 122                    | CEDAR RAPIDS | IA       | 52406     | USA        | 
| 178147      | FIRST STANDARD, L.C.                           | DOMESTIC LIMITED LIABILITY COMPANY | 1994-08-24T00:00:00 | MICHAEL K DENNEY            | 4150 C STREET SW       |                            | CEDAR RAPIDS | IA       | 52404  |                                              | 4150 C STREET SW                | PO BOX 122                    | CEDAR RAPIDS | IA       | 52406     | USA        | 
| 184874      | LOMBARD INTERNATIONAL DISTRIBUTION COMPANY     | FOREIGN PROFIT                     | 1995-04-07T00:00:00 | C T CORPORATION SYSTEM      | 400 E COURT AVE        |                            | DES MOINES   | IA       | 50309  |                                              | ONE LIBERTY PLACE               | 1650 MARKET STREET 54TH FLOOR | PHILADELPHIA | PA       | 19103     | USA        | 
| 184942      | CAPITOL CITY INVESTMENTS, L.P.                 | DOMESTIC LIMITED PARTNERSHIP       | 1995-03-31T00:00:00 | TIMOTHY C HOGAN             | HOGAN LAW OFFICE       | 3101 INGERSOLL AVE STE 103 | DES MOINES   | IA       | 50312  |                                              | 4455 SE CAPITOL CIRCLE          |                               | GRIMES       | IA       | 50111     | USA        | 
| 209794      | TECHNOLOGY ASSOCIATION OF IOWA                 | REVISED DOMESTIC NON-PROFIT        | 1997-09-17T00:00:00 | HOPE WOOD                   | 505 5TH AVE STE 535    |                            | DES MOINES   | IA       | 50309  |                                              | 500 EAST COURT AVENUE           | SUITE 100                     | DES MOINES   | IA       | 50309     | USA        | 
| 190796      | J L YORK, INC.                                 | DOMESTIC PROFIT                    | 1995-11-29T00:00:00 | JERRY L YORK                | 16299 189TH ST         |                            | MANCHESTER   | IA       | 52057  | JL YORK INC                                  | 16299 189TH ST.                 |                               | MANCHESTER   | IA       | 52057     | USA        | 
| 209045      | CORELOGIC VALUATION SOLUTIONS, INC.            | FOREIGN PROFIT                     | 1997-08-20T00:00:00 | CORPORATION SERVICE COMPANY | 505 5TH AVE STE 729    |                            | DES MOINES   | IA       | 50309  |                                              | 7105 CORPORATE DRIVE TX29730330 |                               | PLANO        | TX       | 75024     | USA        | 
| 062426      | IMPACT COMMUNITY ACTION PARTNERSHIP, INC.      | REVISED DOMESTIC NON-PROFIT        | 1976-08-11T00:00:00 | S CHRISTIAN NELSON          | 666 WALNUT ST STE 2000 |                            | DES MOINES   | IA       | 50309  |                                              | 3226 UNIVERSITY AVE             |                               | DES MOINES   | IA       | 50311     | USA        | 
| 528565      | PEPPERWOOD PLAZA LLC                           | DOMESTIC LIMITED LIABILITY COMPANY | 2016-08-12T00:00:00 | C JEREMIAH WADDILOVE        | 755 MORMON TREK BLVD   |                            | IOWA CITY    | IA       | 52246  |                                              | 755 MORMON TREK BLVD            | PO BOX 1907                   | IOWA CITY    | IA       | 52244-190 | USA        | 
```