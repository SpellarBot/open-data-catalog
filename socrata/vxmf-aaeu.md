# Probationers Under Supervision: Beginning 2006

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/probationers-under-supervision-beginning-2006) |
| Metadata | [Link](https://data.ny.gov/api/views/vxmf-aaeu) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/vxmf-aaeu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/vxmf-aaeu/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | vxmf-aaeu |
| Name | Probationers Under Supervision: Beginning 2006 |
| Attribution | New York State Division of Criminal Justice Services |
| Category | Public Safety |
| Tags | public safety, probation, probationers |
| Created | 2014-05-12T15:45:06Z |
| Publication Date | 2016-04-21T22:02:19Z |

## Description

The Division of Criminal Justice Services (DCJS) collects information regarding Probationers Under Supervision from New York City Probation and the 57 county probation departments outside New York City.  This datasets shows the number of probationers, by county, by conviction category and by type of offense.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                               | Data Type | Render Type |
| ======== | ============== | =================== | ================================== | ========= | =========== |
| Yes      | time           | year_supervised     | Year Supervised                    | number    | number      |
| Yes      | series tag     | supervision_county  | Supervision County                 | text      | text        |
| Yes      | series tag     | conviction_category | Conviction Category                | text      | text        |
| Yes      | numeric metric | vfo                 | Violent Felony Offense             | number    | number      |
| Yes      | numeric metric | drugs               | Drugs                              | number    | number      |
| Yes      | numeric metric | dwi                 | Driving While Intoxicated Offenses | number    | number      |
| Yes      | numeric metric | property            | Property                           | number    | number      |
| Yes      | numeric metric | other               | Other                              | number    | number      |
```

## Time Field

```ls
Value = year_supervised
Format & Zone = yyyy
```

## Data Commands

```ls
series e:vxmf-aaeu d:2006-01-01T00:00:00.000Z t:supervision_county=ALBANY t:conviction_category=FELONY m:dwi=196 m:other=235 m:drugs=286 m:vfo=150 m:property=252

series e:vxmf-aaeu d:2006-01-01T00:00:00.000Z t:supervision_county=ALBANY t:conviction_category=MISDEMEANOR m:dwi=143 m:other=794 m:drugs=195 m:vfo=0 m:property=664

series e:vxmf-aaeu d:2006-01-01T00:00:00.000Z t:supervision_county=ALBANY t:conviction_category="OUT OF STATE" m:dwi=0 m:other=40 m:drugs=0 m:vfo=0 m:property=1
```

## Meta Commands

```ls
metric m:vfo p:integer l:"Violent Felony Offense" d:"Indicates the number of Violent Felony Offense (VFO) convictions for which probationers were under supervision, as defined by PL 70.02, includes the following: PL 120.02, 120.05 thru 120.11, 120.18, 120.60, 121.12, 121.13, 125.11, 125.20 thru 125.27, 130.30, 130.35, 130.45, 130.50, 130.53, 130.65 thru 130.80, 130.90, 130.95, 130.96, 135.20, 135.25, 140.25, 140.30, 150.15, 150.20, 160.10, 160.15, 215.16, 215.17, 240.55, 240.60 thru 240.63, 225.27, 265.02 thru 265.04, 265.08, 265.09, 265.12 thru 265.14, 265.19, 405.18, 490.10, 490.15, 490.20, 490.30 thru 490.37, 490.40, 490.47, 490.50 and 490.55. Note: Due to the nature of a VFO, there will be ?zero? misdemeanor Violent Felony Offenses." t:dataTypeName=number

metric m:drugs p:integer l:Drugs d:"Indicates the number of Drug convictions for which probationers were under supervision, includes PL 220 and 221." t:dataTypeName=number

metric m:dwi p:integer l:"Driving While Intoxicated Offenses" d:"Indicates the number of Driving While Intoxicated (DWI)convictions for which probationers were under supervision, includes VTL 1192." t:dataTypeName=number

metric m:property p:integer l:Property d:"Indicates the number Property convictions for which probationers were under supervision." t:dataTypeName=number

metric m:other p:integer l:Other d:"IIndicates the number of probationers under supervision for offenses other than VFO, Drug, DWI or Property offenses, such as criminal mischief and other crimes against public order. Also includes probationers transferred to New York State probation caseloads who have a conviction from another state." t:dataTypeName=number

entity e:vxmf-aaeu l:"Probationers Under Supervision:  Beginning 2006" t:attribution="New York State Division of Criminal Justice Services" t:url=https://data.ny.gov/api/views/vxmf-aaeu

property e:vxmf-aaeu t:meta.view v:id=vxmf-aaeu v:category="Public Safety" v:attributionLink=http://www.criminaljustice.ny.gov/crimnet/ojsa/stats.htm v:averageRating=0 v:name="Probationers Under Supervision:  Beginning 2006" v:attribution="New York State Division of Criminal Justice Services"

property e:vxmf-aaeu t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:vxmf-aaeu t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:vxmf-aaeu t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| year_supervised | supervision_county | conviction_category | vfo | drugs | dwi | property | other | 
| =============== | ================== | =================== | === | ===== | === | ======== | ===== | 
| 2006            | ALBANY             | FELONY              | 150 | 286   | 196 | 252      | 235   | 
| 2006            | ALBANY             | MISDEMEANOR         | 0   | 195   | 143 | 664      | 794   | 
| 2006            | ALBANY             | OUT OF STATE        | 0   | 0     | 0   | 1        | 40    | 
| 2007            | ALBANY             | FELONY              | 143 | 293   | 215 | 218      | 226   | 
| 2007            | ALBANY             | MISDEMEANOR         | 0   | 181   | 144 | 646      | 779   | 
| 2007            | ALBANY             | OUT OF STATE        | 0   | 0     | 0   | 1        | 36    | 
| 2008            | ALBANY             | FELONY              | 132 | 259   | 235 | 208      | 219   | 
| 2008            | ALBANY             | MISDEMEANOR         | 0   | 173   | 148 | 634      | 695   | 
| 2008            | ALBANY             | OUT OF STATE        | 0   | 0     | 0   | 1        | 40    | 
| 2009            | ALBANY             | FELONY              | 119 | 242   | 263 | 190      | 210   | 
```