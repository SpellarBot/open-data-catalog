# IEMA Dental Facilities in illinois (includes equipment list)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/iema-dental-facilities-in-illinois-includes-equipment-list-1bf37) |
| Metadata | [Link](https://data.illinois.gov/api/views/3r4u-w4dc) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/3r4u-w4dc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/3r4u-w4dc/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 3r4u-w4dc |
| Name | IEMA Dental Facilities in illinois (includes equipment list) |
| Category | Social/Healthcare |
| Tags | dental, dentist, x-ray, lasers, radiation |
| Created | 2011-09-29T15:40:18Z |
| Publication Date | 2011-10-21T21:07:02Z |

## Description

Dental facilities in Illinois who currently posses radiation producing equipment (x-ray or laser). This data set also includes each piece of radiation producing equipment the facility currently has.

## Columns

```ls
| Included | Schema Type | Field Name           | Name                 | Data Type | Render Type |
| ======== | =========== | ==================== | ==================== | ========= | =========== |
| Yes      | series tag  | admin                | ADMIN                | text      | text        |
| Yes      | series tag  | facility             | FACILITY             | text      | text        |
| Yes      | series tag  | category             | CATEGORY             | text      | text        |
| Yes      | series tag  | county               | COUNTY               | text      | text        |
| Yes      | series tag  | email                | EMAIL                | text      | text        |
| Yes      | time        | eqptregisterdate     | EqptRegisterDate     | date      | date        |
| Yes      | series tag  | eqptapplicationclass | EQPTApplicationClass | text      | text        |
| Yes      | series tag  | eqptmanufacturer     | EQPTManufacturer     | text      | text        |
| Yes      | series tag  | eqptmodelnumber      | EQPTMODELNUMBER      | text      | text        |
| Yes      | series tag  | eqptserialnumber     | EQPTSERIALNUMBER     | text      | text        |
| Yes      | series tag  | lsoname              | LSOName              | text      | text        |
| No       |             | eqptaquiredate       | EqptAquireDate       | date      | date        |
```

## Time Field

```ls
Value = eqptregisterdate
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = eqptaquiredate
```

## Data Commands

```ls
series e:3r4u-w4dc d:2011-04-05T07:00:00.000Z t:eqptmanufacturer=Siemens t:eqptapplicationclass="Dental Rad" t:category=Dentist t:facility="Kravtsov, David S., D.D.S." t:county=Cook t:admin="David S. Kravtsov, D.D.S." m:row_number.3r4u-w4dc=1

series e:3r4u-w4dc d:1980-03-11T08:00:00.000Z t:eqptmanufacturer="S.S. White" t:eqptapplicationclass="Dental Rad" t:category=Dentist t:facility="Payant, John R, D.D.S." t:county=Lake t:admin="John R. Payant, D.D.S." t:eqptmodelnumber=Marksman t:eqptserialnumber=F6957E m:row_number.3r4u-w4dc=2

series e:3r4u-w4dc d:2009-10-22T07:00:00.000Z t:eqptmanufacturer=Progeny t:eqptapplicationclass="Dental Rad" t:category=Dentist t:facility="Faklaris, Maria, D.D.S." t:email=dr.faklaris@hotmail.com t:county=Cook t:admin="Maria Faklaris, D.D.S." t:eqptmodelnumber=A0010 t:eqptserialnumber=DR2097 m:row_number.3r4u-w4dc=3
```

## Meta Commands

```ls
metric m:row_number.3r4u-w4dc p:long l:"Row Number"

entity e:3r4u-w4dc l:"IEMA Dental Facilities in illinois (includes equipment list)" t:url=https://data.illinois.gov/api/views/3r4u-w4dc

property e:3r4u-w4dc t:meta.view v:id=3r4u-w4dc v:category=Social/Healthcare v:averageRating=0 v:name="IEMA Dental Facilities in illinois (includes equipment list)"

property e:3r4u-w4dc t:meta.view.owner v:id=fx6u-bzri v:screenName=Paul v:displayName=Paul

property e:3r4u-w4dc t:meta.view.tableauthor v:id=fx6u-bzri v:screenName=Paul v:roleName=publisher v:displayName=Paul
```

## Top Records

```ls
| admin                        | facility                    | category      | county | email                   | eqptregisterdate | eqptapplicationclass | eqptmanufacturer | eqptmodelnumber | eqptserialnumber | lsoname | eqptaquiredate | 
| ============================ | =========================== | ============= | ====== | ======================= | ================ | ==================== | ================ | =============== | ================ | ======= | ============== | 
| David S. Kravtsov, D.D.S.    | Kravtsov, David S., D.D.S.  | Dentist       | Cook   |                         | 1301986800       | Dental Rad           | Siemens          |                 |                  |         | 1291190400     | 
| John R. Payant, D.D.S.       | Payant, John R, D.D.S.      | Dentist       | Lake   |                         | 321609600        | Dental Rad           | S.S. White       | Marksman        | F6957E           |         | 182588400      | 
| Maria Faklaris, D.D.S.       | Faklaris, Maria, D.D.S.     | Dentist       | Cook   | dr.faklaris@hotmail.com | 1256194800       | Dental Rad           | Progeny          | A0010           | DR2097           |         | 1251442800     | 
| Michael J. McGrady, D.D.S.   | McGrady, Michael J., D.D.S. | Dentist       | Cook   |                         | 1020063600       | Dental Rad           | Ritter           |                 |                  |         | 1020063600     | 
| William C. Althoff, D.D.S.   | Althoff, William C., D.D.S. | Dentist       | Cook   | walthoff@aol.com        | 839833200        | Dental Rad           | Belmont          | 071a            | P03062R          |         | 838882800      | 
| Randall J. Butchness, D.D.S. | Sutton Lake Dental Care     | Dental Clinic | Cook   |                         | 1077264000       | Dental Rad           | Dent-x           |                 | 1002220          |         |                | 
| Timothy E. Skidmore, D.D.S.  | Mill Creek Dental Care      | Dental Clinic | Kane   | drskidmore@mchsi.com    | 1179817200       | Dental Rad           | Progeny          |                 | PS48120          |         | 1176793200     | 
| Timothy E. Skidmore, D.D.S.  | Mill Creek Dental Care      | Dental Clinic | Kane   | drskidmore@mchsi.com    | 1251702000       | Dental Rad           | Progeny          | Preva           | DU04117          |         | 1249887600     | 
| Mohammad H. Abbas, D.D.S.    | Abbas, Mohammad H., D.D.S.  | Dentist       | Cook   |                         | 756720000        | Dental Rad           | Tokyo-Emix       | Lumix 70ii      | B08544           |         |                | 
| Brian M. Penniall, D.D.S.    | Penniall Family Dental      | Dental Clinic | Kane   | docpenniall@yahoo.com   | 1282633200       | Dental Rad           | Progeny          | JB70            | JW74184          |         | 1281682800     | 
```