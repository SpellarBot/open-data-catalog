# IEMA Non-Dental Facilities in Illinois with Radiation Producing Equipment

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/iema-non-dental-facilities-in-illinois-with-radiation-producing-equipment-0d38b) |
| Metadata | [Link](https://data.illinois.gov/api/views/2vu9-bjjt) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/2vu9-bjjt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/2vu9-bjjt/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 2vu9-bjjt |
| Name | IEMA Non-Dental Facilities in Illinois with Radiation Producing Equipment |
| Category | Public Health |
| Tags | radiation, x-ray, laser, health, radiation producing machines |
| Created | 2011-09-29T16:27:37Z |
| Publication Date | 2011-10-21T21:06:09Z |

## Description

A list of non-dental facilities (equipment is not included in this data set) in Illinois that currently possess radiation producing equipment.  There is a separate data set that includes the dental facilities with radiation producing equipment.

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | admin       | ADMIN      | text      | text        |
| Yes      | series tag  | facility    | FACILITY   | text      | text        |
| Yes      | series tag  | category    | CATEGORY   | text      | text        |
| Yes      | series tag  | county      | COUNTY     | text      | text        |
| Yes      | series tag  | email       | EMAIL      | text      | text        |
| Yes      | series tag  | lsoname     | LSONAME    | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:2vu9-bjjt d:2011-09-29T09:27:39.000Z t:category="Laser Light Show" t:facility="Laser Design Productions" t:email=victor@pyrotekfx.com t:county="Out Of State" t:admin="Mr. Douglas Adams" t:lsoname="Mr. Chirs Stuart" m:row_number.2vu9-bjjt=1

series e:2vu9-bjjt d:2011-09-29T09:29:43.000Z t:category=Portable-Business t:facility="Livito, LLC" t:email=vito@livito.org t:county="Out Of State" t:admin="Vito Ciparis, President" m:row_number.2vu9-bjjt=2

series e:2vu9-bjjt d:2011-09-29T09:27:39.000Z t:category="Laser only-Industrial" t:facility=Lasertech t:county=Lake t:admin="Michael F. Werner, Chief LSO" t:lsoname="Michael F. Werner, Chief LSO" m:row_number.2vu9-bjjt=3
```

## Meta Commands

```ls
metric m:row_number.2vu9-bjjt p:long l:"Row Number"

entity e:2vu9-bjjt l:"IEMA Non-Dental Facilities in Illinois with Radiation Producing Equipment" t:url=https://data.illinois.gov/api/views/2vu9-bjjt

property e:2vu9-bjjt t:meta.view v:id=2vu9-bjjt v:category="Public Health" v:averageRating=0 v:name="IEMA Non-Dental Facilities in Illinois with Radiation Producing Equipment"

property e:2vu9-bjjt t:meta.view.owner v:id=fx6u-bzri v:screenName=Paul v:displayName=Paul

property e:2vu9-bjjt t:meta.view.tableauthor v:id=fx6u-bzri v:screenName=Paul v:roleName=publisher v:displayName=Paul
```

## Top Records

```ls
| :updated_at | admin                                    | facility                                  | category              | county       | email                      | lsoname                      | 
| =========== | ======================================== | ========================================= | ===================== | ============ | ========================== | ============================ | 
| 1317288459  | Mr. Douglas Adams                        | Laser Design Productions                  | Laser Light Show      | Out Of State | victor@pyrotekfx.com       | Mr. Chirs Stuart             | 
| 1317288583  | Vito Ciparis, President                  | Livito, LLC                               | Portable-Business     | Out Of State | vito@livito.org            |                              | 
| 1317288459  | Michael F. Werner, Chief LSO             | Lasertech                                 | Laser only-Industrial | Lake         |                            | Michael F. Werner, Chief LSO | 
| 1317288460  | Kristin K. Wojcik, D.V.M.                | Skycrest Animal Clinic                    | Veterinary Clinic     | Lake         | skycrestanimal@comcast.net |                              | 
| 1317288461  | Michele M. Crase, Associate Director EHS | Northern Illinois University              | School                | De Kalb      | dscharenberg@niu.edu       | David E. Scharenberg, L.S.O. | 
| 1317288461  | Wayne O. Larson, D.V.M.                  | Kaneville Veterinary Service              | Veterinary Clinic     | Kane         |                            |                              | 
| 1317288461  | Mark A. Thompson, D.V.M.                 | Dundee Animal Hospital of Elgin           | Veterinary Clinic     | Kane         |                            |                              | 
| 1317288461  | Cynthia Charlier, DVM                    | Fox Valley Veterinary Dentistry & Surgery | Veterinary Clinic     | Kane         | ccharlier@sbcglobal.net    |                              | 
| 1317288461  | Daniel T. O'Carroll, D.P.M.              | O'Carroll & Associates                    | Podiatry Clinic       | Du Page      | deana@drocarroll.com       |                              | 
| 1317288461  | Arvind Thakkar                           | Swaminarayan Temple                       | Medical Clinic        | Du Page      |                            |                              | 
```