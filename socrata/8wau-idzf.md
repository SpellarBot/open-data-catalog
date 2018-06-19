# PreK Vendors by Transportation Site

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/prek-vendors-by-transportation-site) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/8wau-idzf) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/8wau-idzf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/8wau-idzf/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 8wau-idzf |
| Name | PreK Vendors by Transportation Site |
| Attribution | Department of Education (DOE) |
| Category | Transportation |
| Created | 2016-01-11T22:59:48Z |
| Publication Date | 2016-05-03T23:20:11Z |

## Description

Summary of documented students by school/site

## Columns

```ls
| Included | Schema Type | Field Name  | Name        | Data Type | Render Type |
| ======== | =========== | =========== | =========== | ========= | =========== |
| No       | time        | :updated_at | updated_at  | meta_data | meta_data   |
| Yes      | series tag  | school_year | School_Year | text      | text        |
| Yes      | series tag  | opt_code    | OPT_Code    | text      | text        |
| Yes      | series tag  | site_name   | Site_Name   | text      | text        |
| Yes      | series tag  | school_name | School_Name | text      | text        |
| Yes      | series tag  | vendor_name | Vendor_Name | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:8wau-idzf d:2016-10-01T11:07:43.000Z t:school_name="Child Study Center of N.Y." t:opt_code=C141 t:site_name="Child Study Center of N.Y. - (Staten Island)" t:school_year=2015-2016 t:vendor_name="IC BUS INC. (PRE-K)" m:row_number.8wau-idzf=1

series e:8wau-idzf d:2016-10-01T11:07:43.000Z t:school_name="AMES CENTER" t:opt_code=C143 t:site_name="LEAKE AND WATTS (CAROL AND FRANK BIONDI EDUCATIONAL CENTER)" t:school_year=2015-2016 t:vendor_name="FIRST STEPS" m:row_number.8wau-idzf=2

series e:8wau-idzf d:2016-10-01T11:07:43.000Z t:school_name="Child Study Center of N.Y." t:opt_code=C147 t:site_name="The Child Learning Center of N.Y./Brooklyn" t:school_year=2015-2016 t:vendor_name="FORTUNA BUS COMPANY" m:row_number.8wau-idzf=3
```

## Meta Commands

```ls
metric m:row_number.8wau-idzf p:long l:"Row Number"

entity e:8wau-idzf l:"PreK Vendors by Transportation Site" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/8wau-idzf

property e:8wau-idzf t:meta.view v:id=8wau-idzf v:category=Transportation v:averageRating=0 v:name="PreK Vendors by Transportation Site" v:attribution="Department of Education (DOE)"

property e:8wau-idzf t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:8wau-idzf t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | school_year | opt_code | site_name                                                   | school_name                         | vendor_name              | 
| =========== | =========== | ======== | =========================================================== | =================================== | ======================== | 
| 1475320063  | 2015-2016   | C141     | Child Study Center of N.Y. - (Staten Island)                | Child Study Center of N.Y.          | IC BUS INC. (PRE-K)      | 
| 1475320063  | 2015-2016   | C143     | LEAKE AND WATTS (CAROL AND FRANK BIONDI EDUCATIONAL CENTER) | AMES CENTER                         | FIRST STEPS              | 
| 1475320063  | 2015-2016   | C147     | The Child Learning Center of N.Y./Brooklyn                  | Child Study Center of N.Y.          | FORTUNA BUS COMPANY      | 
| 1475320063  | 2015-2016   | S326     | P326K                                                       | P326K                               | I & Y TRANSIT CORP       | 
| 1475320063  | 2015-2016   | C007     | Sesame Sprout Preschool                                     | Sesame Sprout Preschool             | ROYAL EXPRESS LINE CORP. | 
| 1475320063  | 2015-2016   | C008     | HC/HC-Ace Progam-Hospital Clinic Home Center                | HC/HC-Ace Progam                    | L & M BUS CORP.          | 
| 1475320063  | 2015-2016   | C009     | Auditory/Oral School of N.Y.                                | Auditory/Oral School of N.Y.        | I & Y TRANSIT CORP       | 
| 1475320063  | 2015-2016   | C026     | (Preschool students funded under section 4410)              | Lavelle School for the Blind (4410) | G.V.C., LTD.             | 
| 1475320063  | 2015-2016   | C394     | Strong Place Day Care                                       | Theracare Preschool Services, Inc.  | FIRST STEPS              | 
| 1475320063  | 2015-2016   | S255     | P255K                                                       | P255K                               | SMART PICK               | 
```