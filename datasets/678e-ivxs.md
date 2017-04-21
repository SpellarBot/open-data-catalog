# IEMA Dental Facilities in Illinois

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/iema-dental-facilities-in-illinois-68236) |
| Metadata | [Link](https://data.illinois.gov/api/views/678e-ivxs) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/678e-ivxs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/678e-ivxs/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 678e-ivxs |
| Name | IEMA Dental Facilities in Illinois |
| Category | Social/Healthcare |
| Tags | health |
| Created | 2011-09-29T15:46:45Z |
| Publication Date | 2011-10-21T21:07:58Z |

## Description

Dental facilities in Illinois who currently posses radiation producing equipment (x-ray or laser).

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
series e:678e-ivxs d:2011-09-29T08:46:49.000Z t:category="Dental Clinic" t:facility="Mill Creek Dental Care" t:email=drskidmore@mchsi.com t:county=Kane t:admin="Timothy E. Skidmore, D.D.S." m:row_number.678e-ivxs=1

series e:678e-ivxs d:2011-09-29T08:46:50.000Z t:category="Dental Clinic" t:facility="Penniall Family Dental" t:email=docpenniall@yahoo.com t:county=Kane t:admin="Brian M. Penniall, D.D.S." m:row_number.678e-ivxs=2

series e:678e-ivxs d:2011-09-29T08:46:50.000Z t:category=Dentist t:facility="Adam, Andrea M., D.D.S." t:email=aadds5105@sbcglobal.net t:county=Kane t:admin="Andrea M. Adam, D.D.S." m:row_number.678e-ivxs=3
```

## Meta Commands

```ls
metric m:row_number.678e-ivxs p:long l:"Row Number"

entity e:678e-ivxs l:"IEMA Dental Facilities in Illinois" t:url=https://data.illinois.gov/api/views/678e-ivxs

property e:678e-ivxs t:meta.view v:id=678e-ivxs v:category=Social/Healthcare v:averageRating=0 v:name="IEMA Dental Facilities in Illinois"

property e:678e-ivxs t:meta.view.owner v:id=fx6u-bzri v:screenName=Paul v:displayName=Paul

property e:678e-ivxs t:meta.view.tableauthor v:id=fx6u-bzri v:screenName=Paul v:roleName=publisher v:displayName=Paul
```

## Top Records

```ls
| :updated_at | admin                       | facility                        | category      | county  | email                               | lsoname | 
| =========== | =========================== | =============================== | ============= | ======= | =================================== | ======= | 
| 1317286009  | Timothy E. Skidmore, D.D.S. | Mill Creek Dental Care          | Dental Clinic | Kane    | drskidmore@mchsi.com                |         | 
| 1317286010  | Brian M. Penniall, D.D.S.   | Penniall Family Dental          | Dental Clinic | Kane    | docpenniall@yahoo.com               |         | 
| 1317286010  | Andrea M. Adam, D.D.S.      | Adam, Andrea M., D.D.S.         | Dentist       | Kane    | aadds5105@sbcglobal.net             |         | 
| 1317286010  | Phyllis A. Dixon, D.D.S.    | Dixon, Phyllis A., D.D.S.       | Dentist       | Du Page | padixondds@yahoo.com                |         | 
| 1317286010  | Wendy C. Yeh, D.D.S., M.S.  | Yeh, Wendy C., D.D.S., M.S.     | Dentist       | Du Page |                                     |         | 
| 1317286010  | Douglas L. Kay, D.D.S.      | Kay, Douglas L., D.D.S.         | Dentist       | Du Page | dkbusters@aol.com                   |         | 
| 1317286010  | George Rivera, D.D.S.       | Rivera, George, D.D.S.          | Dentist       | Du Page | gr1957@att.net                      |         | 
| 1317286010  | Amarik Singh, D.D.S.        | Periodontal Implant Specialists | Dental Clinic | Du Page | drsingh@perioimplantspecialists.com |         | 
| 1317286010  | Rebecca Hausten, D.D.S.     | Hausten, Rebecca, D.D.S.        | Dentist       | Du Page |                                     |         | 
| 1317286010  | Evelyn R. Wiley, D.D.S.     | Wiley, Evelyn R., D.D.S.        | Dentist       | Du Page |                                     |         | 
```