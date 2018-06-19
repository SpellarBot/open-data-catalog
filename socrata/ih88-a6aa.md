# Mechanical Permits

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/mechanical-permits-492b8) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/ih88-a6aa) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/ih88-a6aa/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/ih88-a6aa/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | ih88-a6aa |
| Name | Mechanical Permits |
| Category | Licenses/Permits |
| Tags | mechanical, permit, residential |
| Created | 2013-06-12T02:02:24Z |
| Publication Date | 2013-11-12T07:38:15Z |

## Description

Data for all Mechanical Permit applications, including status and work performed. Update Frequency: Daily

## Columns

```ls
| Included | Schema Type | Field Name      | Name             | Data Type     | Render Type   |
| ======== | =========== | =============== | ================ | ============= | ============= |
| Yes      | series tag  | permitno        | Permit Number    | text          | text          |
| Yes      | series tag  | status          | Status           | text          | text          |
| Yes      | series tag  | stno            | Street Number    | text          | text          |
| Yes      | series tag  | pre_direction   | Pre-direction    | text          | text          |
| Yes      | series tag  | stname          | Street Name      | text          | text          |
| Yes      | series tag  | suffix          | Street Suffix    | text          | text          |
| Yes      | series tag  | postdir         | Post-direction   | text          | text          |
| Yes      | series tag  | city            | City             | text          | text          |
| Yes      | series tag  | state           | State            | text          | text          |
| Yes      | series tag  | zip             | ZIP Code         | text          | number        |
| Yes      | series tag  | worktype        | Work Type        | text          | text          |
| Yes      | series tag  | usecode         | Use Code         | text          | text          |
| Yes      | time        | addeddate       | Added Date       | calendar_date | calendar_date |
| No       |             | issueddate      | Issue Date       | calendar_date | calendar_date |
| No       |             | finaleddate     | Final Date       | calendar_date | calendar_date |
| Yes      | series tag  | description     | Description      | text          | text          |
| Yes      | series tag  | applicationtype | Application Type | text          | text          |
```

## Time Field

```ls
Value = addeddate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = issueddate,finaleddate
```

## Data Commands

```ls
series e:ih88-a6aa d:2003-02-04T09:02:48.000Z t:stno=14011 t:zip=20904 t:applicationtype="MECHANICAL PERMIT" t:permitno=297483 t:status=Issued t:state=MD t:usecode="SINGLE FAMILY DWELLING" t:stname=NORTHWYN t:worktype=REPLACE t:suffix=DR t:city="SILVER SPRING" m:row_number.ih88-a6aa=1

series e:ih88-a6aa d:2015-10-30T11:10:16.000Z t:stno=4350 t:zip=20814 t:applicationtype="MECHANICAL PERMIT" t:permitno=734390 t:status=Finaled t:state=MD t:usecode="BUSINESS BUILDING" t:stname="EAST WEST" t:worktype=INSTALL t:suffix=HWY t:city=BETHESDA m:row_number.ih88-a6aa=2

series e:ih88-a6aa d:2003-02-11T09:02:51.000Z t:stno=11224 t:zip=20902 t:applicationtype="MECHANICAL PERMIT" t:permitno=297969 t:status=Issued t:state=MD t:usecode="SINGLE FAMILY DWELLING" t:stname=BYBEE t:worktype=REPLACE t:suffix=ST t:city="SILVER SPRING" m:row_number.ih88-a6aa=3
```

## Meta Commands

```ls
metric m:row_number.ih88-a6aa p:long l:"Row Number"

entity e:ih88-a6aa l:"Mechanical Permits" t:url=https://data.montgomerycountymd.gov/api/views/ih88-a6aa

property e:ih88-a6aa t:meta.view v:id=ih88-a6aa v:category=Licenses/Permits v:averageRating=0 v:name="Mechanical Permits"

property e:ih88-a6aa t:meta.view.owner v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"

property e:ih88-a6aa t:meta.view.tableauthor v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:roleName=administrator v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"
```

## Top Records

```ls
| permitno | status  | stno  | pre_direction | stname       | suffix | postdir | city          | state | zip   | worktype | usecode                | addeddate           | issueddate          | finaleddate         | description               | applicationtype   | 
| ======== | ======= | ===== | ============= | ============ | ====== | ======= | ============= | ===== | ===== | ======== | ====================== | =================== | =================== | =================== | ========================= | ================= | 
| 297483   | Issued  | 14011 |               | NORTHWYN     | DR     |         | SILVER SPRING | MD    | 20904 | REPLACE  | SINGLE FAMILY DWELLING | 2003-02-04T09:02:48 | 2003-02-04T09:02:00 |                     |                           | MECHANICAL PERMIT | 
| 734390   | Finaled | 4350  |               | EAST WEST    | HWY    |         | BETHESDA      | MD    | 20814 | INSTALL  | BUSINESS BUILDING      | 2015-10-30T11:10:16 | 2015-10-30T11:10:34 | 2016-11-02T07:11:59 |                           | MECHANICAL PERMIT | 
| 297969   | Issued  | 11224 |               | BYBEE        | ST     |         | SILVER SPRING | MD    | 20902 | REPLACE  | SINGLE FAMILY DWELLING | 2003-02-11T09:02:51 | 2003-02-11T10:02:00 |                     |                           | MECHANICAL PERMIT | 
| 300852   | Issued  | 11965 |               | OLD COLUMBIA | PIKE   |         | SILVER SPRING | MD    | 20904 | REPLACE  | SINGLE FAMILY DWELLING | 2003-03-25T11:03:20 | 2003-03-25T11:03:00 |                     |                           | MECHANICAL PERMIT | 
| 404340   | Finaled | 3815  |               | WILLIAMS     | LN     |         | CHEVY CHASE   | MD    | 20815 | REPLACE  | SINGLE FAMILY DWELLING | 2005-11-17T01:11:24 | 2005-11-17T01:11:00 | 2016-12-16T09:12:30 | replace oil boilers       | MECHANICAL PERMIT | 
| 761320   | Finaled | 9909  |               | HURST        | ST     |         | BETHESDA      | MD    | 20814 | INSTALL  | SINGLE FAMILY DWELLING | 2016-06-24T11:06:04 | 2016-06-24T01:06:39 | 2016-12-16T08:12:22 | New unit                  | MECHANICAL PERMIT | 
| 301372   | Issued  | 109   |               | CHERRYWOOD   | DR     |         | GAITHERSBURG  | MD    | 20878 | REPLACE  | SINGLE FAMILY DWELLING | 2003-03-31T01:03:09 | 2003-03-31T01:03:00 |                     |                           | MECHANICAL PERMIT | 
| 303631   | Issued  | 11300 |               | ROCKVILLE    | PIKE   |         | ROCKVILLE     | MD    | 20852 | REPLACE  | BUSINESS BUILDING      | 2003-04-22T11:04:17 | 2003-04-22T11:04:00 |                     | Rework Flex and Diffusers | MECHANICAL PERMIT | 
| 303669   | Issued  | 41    |               | SCARLET SAGE | CT     |         | BURTONSVILLE  | MD    | 20866 | REPLACE  | SINGLE FAMILY DWELLING | 2003-04-22T02:04:57 | 2003-04-22T02:04:00 |                     |                           | MECHANICAL PERMIT | 
| 303936   | Issued  | 12250 |               | ROCKVILLE    | PIKE   |         | ROCKVILLE     | MD    | 20852 | INSTALL  | BUSINESS BUILDING      | 2003-04-24T03:04:07 | 2003-04-24T03:04:00 |                     |                           | MECHANICAL PERMIT | 
```