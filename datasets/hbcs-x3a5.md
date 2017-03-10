# IDPH Hospice Residence Facilities

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idph-hospice-residence-facilities-6a201) |
| Metadata | [Link](https://data.illinois.gov/api/views/hbcs-x3a5) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/hbcs-x3a5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/hbcs-x3a5/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | hbcs-x3a5 |
| Name | IDPH Hospice Residence Facilities |
| Attribution | Division of Health Care Facilities and Programs |
| Category | Public Health |
| Tags | hospice, residence, residential, facilities, facility |
| Created | 2012-10-11T18:10:20Z |
| Publication Date | 2017-01-06T18:37:44Z |
| Rows Updated | 2017-01-06T18:37:05Z |

## Description

Current as of January 2017

## Columns

```ls
| Included | Schema Type    | Field Name        | Name                    | Data Type | Render Type |
| ======== | ============== | ================= | ======================= | ========= | =========== |
| No       | time           | :updated_at       | updated_at              | meta_data | meta_data   |
| Yes      | series tag     | hospice_residence | Hospice Residence       | text      | text        |
| No       |                | address           | Address                 | text      | text        |
| Yes      | series tag     | city              | City                    | text      | text        |
| Yes      | series tag     | zip               | County                  | text      | text        |
| Yes      | numeric metric | county            | Zip                     | number    | text        |
| Yes      | series tag     | phone             | Contact Number          | phone     | phone       |
| Yes      | numeric metric | license           | License #               | number    | text        |
| Yes      | series tag     | dba               | License Expiration Date | html      | html        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:hbcs-x3a5 d:2017-01-06T18:36:56.000Z t:zip=Cook t:phone_number="(630) 233-5010" t:dba=03/31/17 t:hospice_residence="Alexian Brothers Hospice" t:city="Elk Grove Village" m:county=60007 m:license=2002732

series e:hbcs-x3a5 d:2017-01-06T18:36:56.000Z t:zip=Will t:phone_number="(815) 740-4104" t:dba=04/30/17 t:hospice_residence="Joliet Area Community Hospice, Inc." t:city=Joliet m:county=60431 m:license=2000340

series e:hbcs-x3a5 d:2017-01-06T18:36:56.000Z t:zip="Mc Henry" t:phone_number="(847) 381-5599" t:dba=07/31/17 t:hospice_residence="JourneyCare, Inc." t:city=Woodstock m:county=60098 m:license=2000920
```

## Meta Commands

```ls
metric m:county p:integer l:Zip t:dataTypeName=number

metric m:license p:integer l:"License #" t:dataTypeName=number

entity e:hbcs-x3a5 l:"IDPH Hospice Residence Facilities" t:attribution="Division of Health Care Facilities and Programs" t:url=https://data.illinois.gov/api/views/hbcs-x3a5

property e:hbcs-x3a5 t:meta.view d:2017-03-10T16:15:35.656Z v:id=hbcs-x3a5 v:category="Public Health" v:attributionLink=http://www.idph.state.il.us/about/ohcr.htm v:averageRating=0 v:name="IDPH Hospice Residence Facilities" v:attribution="Division of Health Care Facilities and Programs"

property e:hbcs-x3a5 t:meta.view.owner d:2017-03-10T16:15:35.656Z v:id=e75b-y6hv v:screenName=Jenny v:roleName=publisher v:displayName=Jenny

property e:hbcs-x3a5 t:meta.view.tableauthor d:2017-03-10T16:15:35.656Z v:id=e75b-y6hv v:screenName=Jenny v:roleName=publisher v:displayName=Jenny
```