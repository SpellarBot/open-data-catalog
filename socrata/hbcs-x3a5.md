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

## Description

Current as of January 2017

## Columns

```ls
| Included | Schema Type | Field Name        | Name                    | Data Type | Render Type |
| ======== | =========== | ================= | ======================= | ========= | =========== |
| No       | time        | :updated_at       | updated_at              | meta_data | meta_data   |
| Yes      | series tag  | hospice_residence | Hospice Residence       | text      | text        |
| No       |             | address           | Address                 | text      | text        |
| Yes      | series tag  | city              | City                    | text      | text        |
| Yes      | series tag  | zip               | County                  | text      | text        |
| Yes      | series tag  | county            | Zip                     | text      | text        |
| Yes      | series tag  | phone             | Contact Number          | phone     | phone       |
| Yes      | series tag  | license           | License #               | text      | text        |
| Yes      | series tag  | dba               | License Expiration Date | html      | html        |
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
series e:hbcs-x3a5 d:2017-01-06T18:36:56.000Z t:zip=Cook t:phone_number="(630) 233-5010" t:county=60007 t:dba=03/31/17 t:hospice_residence="Alexian Brothers Hospice" t:license=2002732 t:city="Elk Grove Village" m:row_number.hbcs-x3a5=1

series e:hbcs-x3a5 d:2017-01-06T18:36:56.000Z t:zip=Will t:phone_number="(815) 740-4104" t:county=60431 t:dba=04/30/17 t:hospice_residence="Joliet Area Community Hospice, Inc." t:license=2000340 t:city=Joliet m:row_number.hbcs-x3a5=2

series e:hbcs-x3a5 d:2017-01-06T18:36:56.000Z t:zip="Mc Henry" t:phone_number="(847) 381-5599" t:county=60098 t:dba=07/31/17 t:hospice_residence="JourneyCare, Inc." t:license=2000920 t:city=Woodstock m:row_number.hbcs-x3a5=3
```

## Meta Commands

```ls
metric m:row_number.hbcs-x3a5 p:long l:"Row Number"

entity e:hbcs-x3a5 l:"IDPH Hospice Residence Facilities" t:attribution="Division of Health Care Facilities and Programs" t:url=https://data.illinois.gov/api/views/hbcs-x3a5

property e:hbcs-x3a5 t:meta.view v:id=hbcs-x3a5 v:category="Public Health" v:attributionLink=http://www.idph.state.il.us/about/ohcr.htm v:averageRating=0 v:name="IDPH Hospice Residence Facilities" v:attribution="Division of Health Care Facilities and Programs"

property e:hbcs-x3a5 t:meta.view.owner v:id=e75b-y6hv v:screenName=Jenny v:displayName=Jenny

property e:hbcs-x3a5 t:meta.view.tableauthor v:id=e75b-y6hv v:screenName=Jenny v:roleName=publisher v:displayName=Jenny
```

## Top Records

```ls
| :updated_at | hospice_residence                                                           | address                  | city              | zip      | county | phone                  | license | dba      | 
| =========== | =========================================================================== | ======================== | ================= | ======== | ====== | ====================== | ======= | ======== | 
| 1483727816  | Alexian Brothers Hospice                                                    | 901 Martha Street        | Elk Grove Village | Cook     | 60007  | [(630) 233-5010, null] | 2002732 | 03/31/17 | 
| 1483727816  | Joliet Area Community Hospice, Inc.                                         | 250 Water Stone Circle   | Joliet            | Will     | 60431  | [(815) 740-4104, null] | 2000340 | 04/30/17 | 
| 1483727816  | JourneyCare, Inc.                                                           | 527 W South Street       | Woodstock         | Mc Henry | 60098  | [(847) 381-5599, null] | 2000920 | 07/31/17 | 
| 1483727816  | JourneyCare, Inc.                                                           | 405 Lake Zurich Road     | Barrington        | Lake     | 60010  | [(847) 381-5599, null] | 2000919 | 07/31/17 | 
| 1483727816  | Midwest Palliative & Hospice Care Center                                    | 2050 Claire Court        | Glenview          | Cook     | 60025  | [(224) 770-2418, null] | 2003132 | 06/30/17 | 
| 1483727816  | OSF Richard L Owens Hospice Home                                            | 8630 N Route 91          | Peoria            | Peoria   | 61615  | [(309) 683-7748, null] | 2001107 | 01/31/18 | 
| 1483727816  | Seasons Hospice, Inc. - DBA Seasons Hospice & Palliative Care-Hospice House | 2195 Diehl Road          | Naperville        | Du Page  | 60563  | [(800) 570-8809, null] | 2002014 | 12/31/17 | 
| 1483727816  | Serenity Hospice and Home                                                   | 1658 S. Illinois Route 2 | Oregon            | Ogle     | 61061  | [(815) 732-2499, null] | 2000298 | 03/31/17 | 
```