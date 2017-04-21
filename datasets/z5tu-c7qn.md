# Courthouses

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/courthouses-86077) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/z5tu-c7qn) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/z5tu-c7qn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/z5tu-c7qn/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | z5tu-c7qn |
| Name | Courthouses |
| Attribution | City Of Baltimore |
| Category | City Government |
| Tags | court, courthouse |
| Created | 2011-12-14T15:39:58Z |
| Publication Date | 2014-04-03T23:46:11Z |

## Description

This data set shows the location of court houses within the City of Baltimore. This list does not include Federal Courthouses.

## Columns

```ls
| Included | Schema Type | Field Name      | Name            | Data Type | Render Type |
| ======== | =========== | =============== | =============== | ========= | =========== |
| No       | time        | :updated_at     | updated_at      | meta_data | meta_data   |
| Yes      | series tag  | name            | name            | text      | text        |
| Yes      | series tag  | type            | type            | text      | text        |
| Yes      | series tag  | zipcode         | zipCode         | text      | text        |
| Yes      | series tag  | neighborhood    | neighborhood    | text      | text        |
| Yes      | series tag  | councildistrict | councilDistrict | text      | number      |
| Yes      | series tag  | policedistrict  | policeDistrict  | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:z5tu-c7qn d:2011-12-14T07:40:27.000Z t:councildistrict=11 t:zipcode=21202 t:name="Civil Division" t:neighborhood=Downtown t:policedistrict=CENTRAL t:type="City District Court" m:row_number.z5tu-c7qn=1

series e:z5tu-c7qn d:2011-12-14T07:40:27.000Z t:councildistrict=11 t:zipcode=21202 t:name="Mitchell Courthouse" t:neighborhood=Downtown t:policedistrict=CENTRAL t:type="City Circuit Court" m:row_number.z5tu-c7qn=2

series e:z5tu-c7qn d:2011-12-14T07:40:27.000Z t:councildistrict=11 t:zipcode=21202 t:name="Post Office Courthouse" t:neighborhood=Downtown t:policedistrict=CENTRAL t:type="City Circuit Court" m:row_number.z5tu-c7qn=3
```

## Meta Commands

```ls
metric m:row_number.z5tu-c7qn p:long l:"Row Number"

entity e:z5tu-c7qn l:Courthouses t:attribution="City Of Baltimore" t:url=https://data.baltimorecity.gov/api/views/z5tu-c7qn

property e:z5tu-c7qn t:meta.view v:id=z5tu-c7qn v:category="City Government" v:attributionLink=http://www.baltimorecity.gov/ v:averageRating=0 v:name=Courthouses v:attribution="City Of Baltimore"

property e:z5tu-c7qn t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:z5tu-c7qn t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:z5tu-c7qn t:meta.view.tableauthor v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```

## Top Records

```ls
| :updated_at | name                               | type                | zipcode | neighborhood                 | councildistrict | policedistrict | 
| =========== | ================================== | =================== | ======= | ============================ | =============== | ============== | 
| 1323848427  | Civil Division                     | City District Court | 21202   | Downtown                     | 11              | CENTRAL        | 
| 1323848427  | Mitchell Courthouse                | City Circuit Court  | 21202   | Downtown                     | 11              | CENTRAL        | 
| 1323848427  | Post Office Courthouse             | City Circuit Court  | 21202   | Downtown                     | 11              | CENTRAL        | 
| 1323848427  | Southern District Court            | City District Court | 21225   | Middle Branch/Reedbird Parks | 10              | SOUTHERN       | 
| 1323848427  | John R. Hargrove, Sr. Building     | City District Court | 21225   | Fairfield Area               | 10              | SOUTHERN       | 
| 1323848427  | Eastside District Court Building   | City District Court | 21213   | East Baltimore Midway        | 12              | EASTERN        | 
| 1323848427  | Central Booking                    | City District Court | 21202   | Penn-Fallsway                | 12              | EASTERN        | 
| 1323848427  | Borgerding District Court Building | City District Court | 21215   | Seton Business Park          | 5               | NORTHWESTERN   | 
```