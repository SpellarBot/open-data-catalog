# Youth Admission and Discharge Demographics: Beginning 2003

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/youth-admission-and-discharge-demographics-beginning-2003) |
| Metadata | [Link](https://data.ny.gov/api/views/9vgs-jnha) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/9vgs-jnha/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/9vgs-jnha/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 9vgs-jnha |
| Name | Youth Admission and Discharge Demographics: Beginning 2003 |
| Attribution | Office of Children and Family Services (OCFS) |
| Category | Human Services |
| Tags | juvenile justice, djjoy, admissions, discharges |
| Created | 2014-10-30T11:41:10Z |
| Publication Date | 2016-06-07T14:44:15Z |

## Description

This dataset provides county-level demographic data (sex, adjudication, age, race/ethnicity, and service setting) for youth admitted to and discharged from the care and custody of the Office of Children and Family Services (OCFS) each year. Data are counted using a youth?s first admission or discharge in a calendar year. Admissions data are aggregate based on the responsible (court) county. Discharges data are aggregate based on the county of residence.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| Yes      | time           | year        | Year        | number    | number      |
| Yes      | series tag     | county      | County      | text      | text        |
| Yes      | series tag     | transaction | Transaction | text      | text        |
| Yes      | series tag     | group       | Group       | text      | text        |
| Yes      | numeric metric | number      | Number      | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:9vgs-jnha d:2003-01-01T00:00:00.000Z t:transaction=Admission t:county=Albany t:group="Age 15" m:number=5

series e:9vgs-jnha d:2003-01-01T00:00:00.000Z t:transaction=Admission t:county=Albany t:group="Age Over 15" m:number=5

series e:9vgs-jnha d:2003-01-01T00:00:00.000Z t:transaction=Admission t:county=Albany t:group="Age Under 15" m:number=4
```

## Meta Commands

```ls
metric m:number p:integer l:Number d:"Count of youth in transaction category for each group" t:dataTypeName=number

entity e:9vgs-jnha l:"Youth Admission and Discharge Demographics:  Beginning 2003" t:attribution="Office of Children and Family Services (OCFS)" t:url=https://data.ny.gov/api/views/9vgs-jnha

property e:9vgs-jnha t:meta.view v:id=9vgs-jnha v:category="Human Services" v:attributionLink=http://ocfs.ny.gov/main/rehab/ v:averageRating=0 v:name="Youth Admission and Discharge Demographics:  Beginning 2003" v:attribution="Office of Children and Family Services (OCFS)"

property e:9vgs-jnha t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:9vgs-jnha t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:9vgs-jnha t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| year | county | transaction | group               | number | 
| ==== | ====== | =========== | =================== | ====== | 
| 2003 | Albany | Admission   | Age 15              | 5      | 
| 2003 | Albany | Admission   | Age Over 15         | 5      | 
| 2003 | Albany | Admission   | Age Under 15        | 4      | 
| 2003 | Albany | Admission   | Black               | 13     | 
| 2003 | Albany | Admission   | Community           | 0      | 
| 2003 | Albany | Admission   | Female              | 3      | 
| 2003 | Albany | Admission   | Foster Care         | 0      | 
| 2003 | Albany | Admission   | Hispanic            | 1      | 
| 2003 | Albany | Admission   | Juvenile Delinquent | 9      | 
| 2003 | Albany | Admission   | Juvenile Offender   | 5      | 
```