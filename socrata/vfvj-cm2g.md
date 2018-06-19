# IEMA Non-Dental Facilities in Illinois with Radiation Producing Equipment (includes list of equip.)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/iema-non-dental-facilities-in-illinois-with-radiation-producing-equipment-includes-list-of-409e3) |
| Metadata | [Link](https://data.illinois.gov/api/views/vfvj-cm2g) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/vfvj-cm2g/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/vfvj-cm2g/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | vfvj-cm2g |
| Name | IEMA Non-Dental Facilities in Illinois with Radiation Producing Equipment (includes list of equip.) |
| Category | Social/Healthcare |
| Tags | x-ray, laser, radiation producing equipment, radiation, health care. |
| Created | 2011-09-29T16:43:02Z |
| Publication Date | 2011-10-21T21:05:15Z |

## Description

A list of all Non-Dental Facilities in Illinois with Radiation Producing Equipment (including a list of each piece of equipment possessed by the facility).  There is a separate data set for Dental facilities along with their current equipment.

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
series e:vfvj-cm2g d:2009-09-15T07:00:00.000Z t:eqptmanufacturer=OPS t:category="Laser Light Show" t:eqptapplicationclass="4 Entertainment Laser" t:facility="Laser Design Productions" t:county="Out Of State" t:email=victor@pyrotekfx.com t:admin="Mr. Douglas Adams" t:lsoname="Mr. Chirs Stuart" m:row_number.vfvj-cm2g=1

series e:vfvj-cm2g d:2009-09-15T07:00:00.000Z t:eqptmanufacturer=OPS t:category="Laser Light Show" t:eqptapplicationclass="4 Entertainment Laser" t:facility="Laser Design Productions" t:county="Out Of State" t:email=victor@pyrotekfx.com t:admin="Mr. Douglas Adams" t:lsoname="Mr. Chirs Stuart" m:row_number.vfvj-cm2g=2

series e:vfvj-cm2g d:2009-01-29T08:00:00.000Z t:eqptmanufacturer=Arctos t:category="Laser Light Show" t:eqptapplicationclass="4 Entertainment Laser" t:facility="Laser Design Productions" t:county="Out Of State" t:email=victor@pyrotekfx.com t:admin="Mr. Douglas Adams" t:lsoname="Mr. Chirs Stuart" m:row_number.vfvj-cm2g=3
```

## Meta Commands

```ls
metric m:row_number.vfvj-cm2g p:long l:"Row Number"

entity e:vfvj-cm2g l:"IEMA Non-Dental Facilities in Illinois with Radiation Producing Equipment (includes list of equip.)" t:url=https://data.illinois.gov/api/views/vfvj-cm2g

property e:vfvj-cm2g t:meta.view v:id=vfvj-cm2g v:category=Social/Healthcare v:averageRating=0 v:name="IEMA Non-Dental Facilities in Illinois with Radiation Producing Equipment (includes list of equip.)"

property e:vfvj-cm2g t:meta.view.owner v:id=fx6u-bzri v:screenName=Paul v:displayName=Paul

property e:vfvj-cm2g t:meta.view.tableauthor v:id=fx6u-bzri v:screenName=Paul v:roleName=publisher v:displayName=Paul
```

## Top Records

```ls
| admin             | facility                 | category         | county       | email                | eqptregisterdate | eqptapplicationclass  | eqptmanufacturer | eqptmodelnumber | eqptserialnumber | lsoname          | eqptaquiredate | 
| ================= | ======================== | ================ | ============ | ==================== | ================ | ===================== | ================ | =============== | ================ | ================ | ============== | 
| Mr. Douglas Adams | Laser Design Productions | Laser Light Show | Out Of State | victor@pyrotekfx.com | 1252998000       | 4 Entertainment Laser | OPS              |                 |                  | Mr. Chirs Stuart | 1246431600     | 
| Mr. Douglas Adams | Laser Design Productions | Laser Light Show | Out Of State | victor@pyrotekfx.com | 1252998000       | 4 Entertainment Laser | OPS              |                 |                  | Mr. Chirs Stuart | 1246431600     | 
| Mr. Douglas Adams | Laser Design Productions | Laser Light Show | Out Of State | victor@pyrotekfx.com | 1233216000       | 4 Entertainment Laser | Arctos           |                 |                  | Mr. Chirs Stuart | 1217314800     | 
| Mr. Douglas Adams | Laser Design Productions | Laser Light Show | Out Of State | victor@pyrotekfx.com | 1233216000       | 4 Entertainment Laser | Arctos           |                 |                  | Mr. Chirs Stuart | 1217314800     | 
| Mr. Douglas Adams | Laser Design Productions | Laser Light Show | Out Of State | victor@pyrotekfx.com | 1252998000       | 4 Entertainment Laser | OPS              |                 |                  | Mr. Chirs Stuart | 1246431600     | 
| Mr. Douglas Adams | Laser Design Productions | Laser Light Show | Out Of State | victor@pyrotekfx.com | 1233216000       | 4 Entertainment Laser | Arctos           |                 |                  | Mr. Chirs Stuart | 1217314800     | 
| Mr. Douglas Adams | Laser Design Productions | Laser Light Show | Out Of State | victor@pyrotekfx.com | 1233216000       | 4 Entertainment Laser | Arctos           |                 |                  | Mr. Chirs Stuart | 1217314800     | 
| Mr. Douglas Adams | Laser Design Productions | Laser Light Show | Out Of State | victor@pyrotekfx.com | 1233216000       | 4 Entertainment Laser | Arctos           |                 |                  | Mr. Chirs Stuart | 1217314800     | 
| Mr. Douglas Adams | Laser Design Productions | Laser Light Show | Out Of State | victor@pyrotekfx.com | 1185346800       | 4 Entertainment Laser | Laserscope       | 800             | 1901987          | Mr. Chirs Stuart | 1185346800     | 
| Mr. Douglas Adams | Laser Design Productions | Laser Light Show | Out Of State | victor@pyrotekfx.com | 1185346800       | 4 Entertainment Laser | Laserscope       | 800             | 19041151         | Mr. Chirs Stuart | 1185346800     | 
```