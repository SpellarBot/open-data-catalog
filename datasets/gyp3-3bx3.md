# City of Austin Demographics Current Representation By Quarter

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/city-of-austin-demographics-current-representation-by-quarter) |
| Metadata | [Link](https://data.austintexas.gov/api/views/gyp3-3bx3) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/gyp3-3bx3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/gyp3-3bx3/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | gyp3-3bx3 |
| Name | City of Austin Demographics Current Representation By Quarter |
| Attribution | City of Austin, Human Resources Information Systems |
| Category | Workforce Development |
| Tags | gender, ethnicity, eeoc |
| Created | 2015-11-02T21:17:58Z |
| Publication Date | 2015-11-02T21:44:16Z |

## Description

Current representation at the City of Austin budgeted employees as of the last day of each quarter of the fiscal year.

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type | Render Type |
| ======== | ============== | ======================== | ======================== | ========= | =========== |
| No       | time           | :updated_at              | updated_at               | meta_data | meta_data   |
| Yes      | series tag     | department_name          | Department Name          | text      | text        |
| Yes      | numeric metric | eeo_category             | EEO Category             | number    | text        |
| Yes      | series tag     | eeo_category_description | EEO Category Description | text      | text        |
| Yes      | series tag     | ethnicity                | Ethnicity                | text      | text        |
| Yes      | series tag     | gender                   | Gender                   | text      | text        |
| Yes      | series tag     | quarter_number           | Quarter Number           | text      | text        |
| Yes      | numeric metric | number_of_employees      | Number of Employees      | number    | number      |
| Yes      | series tag     | employee_category        | Employee Category        | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:gyp3-3bx3 d:2015-11-02T13:18:00.000Z t:quarter_number=Q1 t:gender=F t:employee_category="Municipal Civil Service" t:department_name="Animal Services" t:ethnicity=White t:eeo_category_description=Official/Adm m:number_of_employees=1 m:eeo_category=10

series e:gyp3-3bx3 d:2015-11-02T13:18:00.000Z t:quarter_number=Q4 t:gender=F t:employee_category="Municipal Civil Service" t:department_name="Animal Services" t:ethnicity=White t:eeo_category_description=Official/Adm m:number_of_employees=1 m:eeo_category=10

series e:gyp3-3bx3 d:2015-11-02T13:18:00.000Z t:quarter_number=Q1 t:gender=F t:employee_category="Municipal Civil Service" t:department_name="Animal Services" t:ethnicity="Asian/Pacific Islander" t:eeo_category_description=Professionals m:number_of_employees=1 m:eeo_category=20
```

## Meta Commands

```ls
metric m:eeo_category p:integer l:"EEO Category" d:"Equal Employment Opportunity Category" t:dataTypeName=number

metric m:number_of_employees p:float l:"Number of Employees" t:dataTypeName=number

entity e:gyp3-3bx3 l:"City of Austin Demographics Current Representation By Quarter" t:attribution="City of Austin, Human Resources Information Systems" t:url=https://data.austintexas.gov/api/views/gyp3-3bx3

property e:gyp3-3bx3 t:meta.view v:id=gyp3-3bx3 v:category="Workforce Development" v:averageRating=0 v:name="City of Austin Demographics Current Representation By Quarter" v:attribution="City of Austin, Human Resources Information Systems"

property e:gyp3-3bx3 t:meta.view.license v:name="Public Domain"

property e:gyp3-3bx3 t:meta.view.owner v:id=ib7z-phrj v:screenName=Claudia v:displayName=Claudia

property e:gyp3-3bx3 t:meta.view.tableauthor v:id=ib7z-phrj v:screenName=Claudia v:roleName=publisher v:displayName=Claudia
```

## Top Records

```ls
| :updated_at | department_name | eeo_category | eeo_category_description | ethnicity              | gender | quarter_number | number_of_employees | employee_category       | 
| =========== | =============== | ============ | ======================== | ====================== | ====== | ============== | =================== | ======================= | 
| 1446470280  | Animal Services | 10           | Official/Adm             | White                  | F      | Q1             | 1.00                | Municipal Civil Service | 
| 1446470280  | Animal Services | 10           | Official/Adm             | White                  | F      | Q4             | 1.00                | Municipal Civil Service | 
| 1446470280  | Animal Services | 20           | Professionals            | Asian/Pacific Islander | F      | Q1             | 1.00                | Municipal Civil Service | 
| 1446470280  | Animal Services | 20           | Professionals            | Asian/Pacific Islander | F      | Q2             | 1.00                | Municipal Civil Service | 
| 1446470280  | Animal Services | 20           | Professionals            | Asian/Pacific Islander | F      | Q3             | 1.00                | Municipal Civil Service | 
| 1446470280  | Animal Services | 20           | Professionals            | Asian/Pacific Islander | F      | Q4             | 1.00                | Municipal Civil Service | 
| 1446470280  | Animal Services | 20           | Professionals            | Black                  | M      | Q1             | 1.00                | Municipal Civil Service | 
| 1446470280  | Animal Services | 20           | Professionals            | Black                  | M      | Q2             | 1.00                | Municipal Civil Service | 
| 1446470280  | Animal Services | 20           | Professionals            | Black                  | M      | Q3             | 1.00                | Municipal Civil Service | 
| 1446470280  | Animal Services | 20           | Professionals            | Black                  | M      | Q4             | 1.00                | Municipal Civil Service | 
```