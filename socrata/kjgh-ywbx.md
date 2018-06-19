# PreK Riders by Transportation Site

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/prek-riders-by-transportation-site) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/kjgh-ywbx) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/kjgh-ywbx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/kjgh-ywbx/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | kjgh-ywbx |
| Name | PreK Riders by Transportation Site |
| Attribution | Department of Education (DOE) |
| Category | Transportation |
| Created | 2016-01-11T22:59:54Z |
| Publication Date | 2016-05-03T23:18:17Z |

## Description

Summary of documented students by school/site

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| No       | time           | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | series tag     | school_year      | School_Year      | text      | text        |
| Yes      | series tag     | opt_code         | OPT_Code         | text      | text        |
| Yes      | series tag     | site_name        | Site_Name        | text      | text        |
| Yes      | series tag     | school_name      | School_Name      | text      | text        |
| Yes      | numeric metric | number_of_riders | Number_of_Riders | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:kjgh-ywbx d:2016-10-01T11:06:36.000Z t:school_name="Little Wonders" t:opt_code=E044 t:site_name="Little Wonders" t:school_year=2015-2016 m:number_of_riders=90

series e:kjgh-ywbx d:2016-10-01T11:06:36.000Z t:school_name="HC/HC-Ace Progam" t:opt_code=C008 t:site_name="HC/HC-Ace Progam-Hospital Clinic Home Center" t:school_year=2015-2016 m:number_of_riders=57

series e:kjgh-ywbx d:2016-10-01T11:06:36.000Z t:school_name="Auditory/Oral School of N.Y." t:opt_code=C009 t:site_name="Auditory/Oral School of N.Y." t:school_year=2015-2016 m:number_of_riders=114
```

## Meta Commands

```ls
metric m:number_of_riders p:integer l:Number_of_Riders d:"Total number of children authorized for bus service and indicated by the site as requiring bus service." t:dataTypeName=number

entity e:kjgh-ywbx l:"PreK Riders by Transportation Site" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/kjgh-ywbx

property e:kjgh-ywbx t:meta.view v:id=kjgh-ywbx v:category=Transportation v:averageRating=0 v:name="PreK Riders by Transportation Site" v:attribution="Department of Education (DOE)"

property e:kjgh-ywbx t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:kjgh-ywbx t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | school_year | opt_code | site_name                                      | school_name                                     | number_of_riders | 
| =========== | =========== | ======== | ============================================== | =============================================== | ================ | 
| 1475319996  | 2015-2016   | E044     | Little Wonders                                 | Little Wonders                                  | 90               | 
| 1475319996  | 2015-2016   | C008     | HC/HC-Ace Progam-Hospital Clinic Home Center   | HC/HC-Ace Progam                                | 57               | 
| 1475319996  | 2015-2016   | C009     | Auditory/Oral School of N.Y.                   | Auditory/Oral School of N.Y.                    | 114              | 
| 1475319996  | 2015-2016   | C026     | (Preschool students funded under section 4410) | Lavelle School for the Blind (4410)             | 42               | 
| 1475319996  | 2015-2016   | C027     | BLOCK ACADEMY                                  | BLOCK INSTITUTE SCHOOL                          | 80               | 
| 1475319996  | 2015-2016   | S004     | CSE 7/District 31-P004                         | New York City SCIS                              | 4                | 
| 1475319996  | 2015-2016   | C028     | Positive Beginnings Preschool                  | Positive Beginnings Preschool                   | 212              | 
| 1475319996  | 2015-2016   | C037     | Astor Lawrence Hickey Center                   | Lawrence F. Hickey Center for Child Development | 42               | 
| 1475319996  | 2015-2016   | C040     | Merricat's Castle School                       | ABC                                             | 12               | 
| 1475319996  | 2015-2016   | C041     | Birch, Herbert G. Early Childhood Center       | Birch, Herbert G. Early Childhood Center        | 142              | 
```