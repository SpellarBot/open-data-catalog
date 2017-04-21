# Electrical Building Permits

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/electrical-building-permits-09268) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/qxie-8qnp) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/qxie-8qnp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/qxie-8qnp/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | qxie-8qnp |
| Name | Electrical Building Permits |
| Category | Licenses/Permits |
| Tags | permit, residential, status |
| Created | 2013-06-11T17:57:28Z |
| Publication Date | 2014-02-04T18:59:29Z |

## Description

Data for all Electrical Permit applications, including status and work performed.

## Columns

```ls
| Included | Schema Type | Field Name      | Name             | Data Type     | Render Type   |
| ======== | =========== | =============== | ================ | ============= | ============= |
| Yes      | series tag  | permitno        | Permit Number    | text          | text          |
| Yes      | series tag  | status          | Status           | text          | text          |
| Yes      | series tag  | stno            | Street Number    | text          | text          |
| Yes      | series tag  | predir          | Pre-direction    | text          | text          |
| Yes      | series tag  | stname          | Street Name      | text          | text          |
| Yes      | series tag  | suffix          | Street Suffix    | text          | text          |
| Yes      | series tag  | postdir         | Post-direction   | text          | text          |
| Yes      | series tag  | city            | City             | text          | text          |
| Yes      | series tag  | state           | State            | text          | text          |
| Yes      | series tag  | zip             | ZIP code         | text          | number        |
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
series e:qxie-8qnp d:2000-01-03T08:01:35.000Z t:stno=10251 t:zip=20895 t:applicationtype="ELECTRICAL PERMIT" t:permitno=208673 t:status=Finaled t:state=MD t:usecode=SIGN t:stname=KENSINGTON t:worktype=INSTALL t:suffix=PKWY t:city=KENSINGTON m:row_number.qxie-8qnp=1

series e:qxie-8qnp d:2000-02-11T10:02:05.000Z t:stno=5316 t:zip=20817 t:applicationtype="ELECTRICAL PERMIT" t:permitno=211329 t:status=Finaled t:state=MD t:usecode="SINGLE FAMILY DWELLING" t:stname=BRADLEY t:worktype=INSTALL t:suffix=BLVD t:city=BETHESDA m:row_number.qxie-8qnp=2

series e:qxie-8qnp d:2000-01-03T09:01:15.000Z t:stno=7924 t:zip=20814 t:applicationtype="ELECTRICAL PERMIT" t:permitno=208675 t:status=Issued t:state=MD t:usecode=SIGN t:stname=WISCONSIN t:worktype=INSTALL t:suffix=AVE t:city=BETHESDA m:row_number.qxie-8qnp=3
```

## Meta Commands

```ls
metric m:row_number.qxie-8qnp p:long l:"Row Number"

entity e:qxie-8qnp l:"Electrical Building Permits" t:url=https://data.montgomerycountymd.gov/api/views/qxie-8qnp

property e:qxie-8qnp t:meta.view v:id=qxie-8qnp v:category=Licenses/Permits v:averageRating=0 v:name="Electrical Building Permits"

property e:qxie-8qnp t:meta.view.owner v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"

property e:qxie-8qnp t:meta.view.tableauthor v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:roleName=administrator v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"
```

## Top Records

```ls
| permitno | status  | stno  | predir | stname     | suffix | postdir | city        | state | zip   | worktype | usecode                | addeddate           | issueddate          | finaleddate         | description                                  | applicationtype   | 
| ======== | ======= | ===== | ====== | ========== | ====== | ======= | =========== | ===== | ===== | ======== | ====================== | =================== | =================== | =================== | ============================================ | ================= | 
| 208673   | Finaled | 10251 |        | KENSINGTON | PKWY   |         | KENSINGTON  | MD    | 20895 | INSTALL  | SIGN                   | 2000-01-03T08:01:35 | 2000-01-03T08:01:00 | 2012-12-11T01:12:41 |                                              | ELECTRICAL PERMIT | 
| 211329   | Finaled | 5316  |        | BRADLEY    | BLVD   |         | BETHESDA    | MD    | 20817 | INSTALL  | SINGLE FAMILY DWELLING | 2000-02-11T10:02:05 | 2000-02-11T10:02:00 | 2001-04-26T01:04:00 |                                              | ELECTRICAL PERMIT | 
| 208675   | Issued  | 7924  |        | WISCONSIN  | AVE    |         | BETHESDA    | MD    | 20814 | INSTALL  | SIGN                   | 2000-01-03T09:01:15 | 2000-01-03T09:01:00 |                     |                                              | ELECTRICAL PERMIT | 
| 210721   | Issued  | 5311  |        | OAKLAND    | RD     |         | CHEVY CHASE | MD    | 20815 | INSTALL  | SINGLE FAMILY DWELLING | 2000-02-03T10:02:14 | 2000-02-03T10:02:00 |                     |                                              | ELECTRICAL PERMIT | 
| 211326   | Issued  | 13710 |        | MILLS FARM | RD     |         | ROCKVILLE   | MD    | 20850 | INSTALL  | SINGLE FAMILY DWELLING | 2000-02-11T09:02:34 | 2000-02-11T10:02:44 |                     | site lighting 13710-A                        | ELECTRICAL PERMIT | 
| 211327   | Issued  | 13709 |        | MILLS FARM | RD     |         | ROCKVILLE   | MD    | 20850 | INSTALL  | SINGLE FAMILY DWELLING | 2000-02-11T10:02:03 | 2000-02-11T10:02:30 |                     | site lighting 13709-A                        | ELECTRICAL PERMIT | 
| 211862   | Issued  | 13501 |        | CAVANAUGH  | DR     |         | ROCKVILLE   | MD    | 20850 | INSTALL  | STREET LIGHT           | 2000-02-22T10:02:36 | 2000-02-22T10:02:00 |                     | SITE LIGHTING ONLY                           | ELECTRICAL PERMIT | 
| 211865   | Issued  | 4109  |        | DEBENHAM   | CT     |         | ROCKVILLE   | MD    | 20853 | INSTALL  | SINGLE FAMILY DWELLING | 2000-02-22T10:02:48 | 2000-02-22T10:02:08 |                     | BLDG #206766                                 | ELECTRICAL PERMIT | 
| 486700   | Issued  | 10900 |        | ROCKVILLE  | PIKE   |         | ROCKVILLE   | MD    | 20852 | INSTALL  | SINGLE FAMILY DWELLING | 2008-06-03T09:06:21 | 2008-06-03T09:06:00 |                     | TEMP. 800 AMP POLE SERVICE FOR CONSTRUCTION. | ELECTRICAL PERMIT | 
| 212257   | Finaled | 11709 |        | TALL PINES | DR     |         | GERMANTOWN  | MD    | 20876 | INSTALL  | SINGLE FAMILY DWELLING | 2000-02-28T09:02:00 | 2000-02-28T09:02:42 | 2000-05-24T02:05:00 |                                              | ELECTRICAL PERMIT | 
```