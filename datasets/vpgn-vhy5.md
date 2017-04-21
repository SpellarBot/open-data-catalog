# IEMA Licensed Industrial Radiation Technicians

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/iema-licensed-industrial-radiation-technicians-c8ada) |
| Metadata | [Link](https://data.illinois.gov/api/views/vpgn-vhy5) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/vpgn-vhy5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/vpgn-vhy5/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | vpgn-vhy5 |
| Name | IEMA Licensed Industrial Radiation Technicians |
| Category | Public Health |
| Tags | radiation, technician, industrial, x-ray |
| Created | 2011-09-29T15:32:21Z |
| Publication Date | 2011-10-21T21:09:01Z |

## Description

A list of licensed Industrial Radiation Technicians in the state of Illinois

## Columns

```ls
| Included | Schema Type | Field Name | Name      | Data Type | Render Type |
| ======== | =========== | ========== | ========= | ========= | =========== |
| Yes      | series tag  | lastname   | LASTNAME  | text      | text        |
| Yes      | series tag  | firstname  | FIRSTNAME | text      | text        |
| Yes      | series tag  | category   | CATEGORY  | text      | text        |
| Yes      | series tag  | class      | CLASS     | text      | text        |
| Yes      | series tag  | county     | COUNTY    | text      | text        |
| Yes      | time        | expdate    | EXPDATE   | date      | date        |
| Yes      | series tag  | email      | EMAIL     | text      | text        |
```

## Time Field

```ls
Value = expdate
Format & Zone = seconds
```

## Data Commands

```ls
series e:vpgn-vhy5 d:2015-08-31T07:00:00.000Z t:category=RADIOGRAPHER t:email=James.Ludowissi@slemens.com t:county="Out Of State" t:class=MATL/MACH t:lastname=Ludowissi t:firstname=James m:row_number.vpgn-vhy5=1

series e:vpgn-vhy5 d:2014-04-30T07:00:00.000Z t:category=RADIOGRAPHER t:county="Out Of State" t:class=MATL/MACH t:lastname=Raduege t:firstname=Dale m:row_number.vpgn-vhy5=2

series e:vpgn-vhy5 d:2012-10-31T07:00:00.000Z t:category=TRAINEE t:county="Du Page" t:class=MATERIALS t:lastname=Monroe t:firstname=Michael m:row_number.vpgn-vhy5=3
```

## Meta Commands

```ls
metric m:row_number.vpgn-vhy5 p:long l:"Row Number"

entity e:vpgn-vhy5 l:"IEMA Licensed Industrial Radiation Technicians" t:url=https://data.illinois.gov/api/views/vpgn-vhy5

property e:vpgn-vhy5 t:meta.view v:id=vpgn-vhy5 v:category="Public Health" v:averageRating=0 v:name="IEMA Licensed Industrial Radiation Technicians"

property e:vpgn-vhy5 t:meta.view.owner v:id=fx6u-bzri v:screenName=Paul v:displayName=Paul

property e:vpgn-vhy5 t:meta.view.tableauthor v:id=fx6u-bzri v:screenName=Paul v:roleName=publisher v:displayName=Paul
```

## Top Records

```ls
| lastname   | firstname  | category     | class     | county       | expdate    | email                       | 
| ========== | ========== | ============ | ========= | ============ | ========== | =========================== | 
| Ludowissi  | James      | RADIOGRAPHER | MATL/MACH | Out Of State | 1441004400 | James.Ludowissi@slemens.com | 
| Raduege    | Dale       | RADIOGRAPHER | MATL/MACH | Out Of State | 1398841200 |                             | 
| Monroe     | Michael    | TRAINEE      | MATERIALS | Du Page      | 1351666800 |                             | 
| Brydon     | John       | TRAINEE      | MATL/MACH | Du Page      | 1372575600 | panheadjohn64@sbcglobal.net | 
| Fay        | Stephen    | RADIOGRAPHER | MATL/MACH | Du Page      | 1414738800 |                             | 
| Slack      | Robert     | RADIOGRAPHER | MATL/MACH | Du Page      | 1335769200 |                             | 
| Symeonides | Charles    | RADIOGRAPHER | MATL/MACH | Du Page      | 1409468400 |                             | 
| Razi       | Salahuddin | RADIOGRAPHER | MATL/MACH | Du Page      | 1461999600 | salrazi11@gmail.com         | 
| Maslowski  | John       | RADIOGRAPHER | MATERIALS | Out Of State | 1430377200 |                             | 
| Perkins    | Terry      | RADIOGRAPHER | MATL/MACH | Out Of State | 1398841200 | terrylee_1951@yahoo.com     | 
```