# Demolition Permits

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/demolition-permits) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/b6ht-fw3x) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/b6ht-fw3x/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/b6ht-fw3x/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | b6ht-fw3x |
| Name | Demolition Permits |
| Category | Licenses/Permits |
| Tags | permits, demolition, residential |
| Created | 2013-06-11T17:28:49Z |
| Publication Date | 2013-11-13T06:32:53Z |

## Description

Data for all Demolition Permit applications, including status and work performed. Update Frequency: Daily

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
| Yes      | series tag  | zip             | Zip code         | text          | number        |
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
series e:b6ht-fw3x d:2000-10-18T02:10:55.000Z t:stno=5918 t:zip=20814 t:applicationtype="DEMOLITION OR MOVE PERMIT" t:permitno=232729 t:status=Finaled t:description=PS1B6585 t:state=MD t:usecode="SINGLE FAMILY DWELLING" t:stname=IPSWICH t:worktype=DEMOLISH t:suffix=RD t:city=BETHESDA m:row_number.b6ht-fw3x=1

series e:b6ht-fw3x d:2000-10-18T02:10:34.000Z t:stno=5914 t:zip=20814 t:applicationtype="DEMOLITION OR MOVE PERMIT" t:permitno=232730 t:status=Finaled t:state=MD t:usecode="SINGLE FAMILY DWELLING" t:stname=IPSWICH t:worktype=DEMOLISH t:suffix=RD t:city=BETHESDA m:row_number.b6ht-fw3x=2

series e:b6ht-fw3x d:2000-01-06T09:01:43.000Z t:stno=14601 t:zip=20874 t:applicationtype="DEMOLITION OR MOVE PERMIT" t:permitno=208968 t:status=Completed t:state=MD t:usecode="SINGLE FAMILY DWELLING" t:stname=SCHAEFER t:worktype=DEMOLISH t:suffix=RD t:city=GERMANTOWN m:row_number.b6ht-fw3x=3
```

## Meta Commands

```ls
metric m:row_number.b6ht-fw3x p:long l:"Row Number"

entity e:b6ht-fw3x l:"Demolition Permits" t:url=https://data.montgomerycountymd.gov/api/views/b6ht-fw3x

property e:b6ht-fw3x t:meta.view v:id=b6ht-fw3x v:category=Licenses/Permits v:averageRating=0 v:name="Demolition Permits"

property e:b6ht-fw3x t:meta.view.owner v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"

property e:b6ht-fw3x t:meta.view.tableauthor v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:roleName=administrator v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"
```

## Top Records

```ls
| permitno | status    | stno  | predir | stname     | suffix | postdir | city          | state | zip   | worktype | usecode                | addeddate           | issueddate          | finaleddate         | description                                                                                                                                             | applicationtype           | 
| ======== | ========= | ===== | ====== | ========== | ====== | ======= | ============= | ===== | ===== | ======== | ====================== | =================== | =================== | =================== | ======================================================================================================================================================= | ========================= | 
| 232729   | Finaled   | 5918  |        | IPSWICH    | RD     |         | BETHESDA      | MD    | 20814 | DEMOLISH | SINGLE FAMILY DWELLING | 2000-10-18T02:10:55 | 2000-12-14T01:12:00 | 2000-12-27T01:12:00 | PS1B6585                                                                                                                                                | DEMOLITION OR MOVE PERMIT | 
| 232730   | Finaled   | 5914  |        | IPSWICH    | RD     |         | BETHESDA      | MD    | 20814 | DEMOLISH | SINGLE FAMILY DWELLING | 2000-10-18T02:10:34 | 2000-12-14T10:12:00 | 2000-12-27T01:12:00 |                                                                                                                                                         | DEMOLITION OR MOVE PERMIT | 
| 208968   | Completed | 14601 |        | SCHAEFER   | RD     |         | GERMANTOWN    | MD    | 20874 | DEMOLISH | SINGLE FAMILY DWELLING | 2000-01-06T09:01:43 | 2000-02-07T10:02:00 | 2011-03-11T09:03:10 |                                                                                                                                                         | DEMOLITION OR MOVE PERMIT | 
| 236562   | Completed | 7108  |        | 44TH       | ST     |         | CHEVY CHASE   | MD    | 20815 | DEMOLISH | SINGLE FAMILY DWELLING | 2000-12-08T02:12:52 | 2000-12-08T02:12:00 | 2001-02-12T03:02:00 | PS1A6506                                                                                                                                                | DEMOLITION OR MOVE PERMIT | 
| 237007   | Finaled   | 6730  |        | WILSON     | LN     |         | BETHESDA      | MD    | 20817 | DEMOLISH | SINGLE FAMILY DWELLING | 2000-12-15T10:12:31 | 2001-01-08T09:01:00 | 2001-02-20T01:02:00 | Bond tracking # PS1A-6590                                                                                                                               | DEMOLITION OR MOVE PERMIT | 
| 789067   | Open      | 12422 |        | VEIRS MILL | RD     |         | SILVER SPRING | MD    | 20906 | DEMOLISH | SINGLE FAMILY DWELLING | 2017-02-09T02:02:47 |                     |                     | This structure is being demolished as part of the Montrose Parkway East CIP. No Sediment Control required, less than 5,000 SF of disturbance.           | DEMOLITION OR MOVE PERMIT | 
| 789069   | Open      | 4506  |        | GAYNOR     | RD     |         | SILVER SPRING | MD    | 20906 | DEMOLISH | SINGLE FAMILY DWELLING | 2017-02-09T02:02:06 |                     |                     | This structure is being demolished as part of the Montrose Parkway East CIP. No sediment control permit is required, less than 5,000 SF of disturbance. | DEMOLITION OR MOVE PERMIT | 
| 240064   | Finaled   | 9139  |        | MCDONALD   | DR     |         | BETHESDA      | MD    | 20817 | DEMOLISH | SINGLE FAMILY DWELLING | 2001-02-07T02:02:33 | 2001-05-09T02:05:00 | 2001-05-25T01:05:01 | PS1A7373                                                                                                                                                | DEMOLITION OR MOVE PERMIT | 
| 789071   | Open      | 5515  |        | RANDOLPH   | RD     |         | ROCKVILLE     | MD    | 20852 | DEMOLISH | BUSINESS BUILDING      | 2017-02-09T02:02:03 |                     |                     | This structure is being demolished as part of the Montrose Parkway East CIP. An SLDA will be applied for this project.                                  | DEMOLITION OR MOVE PERMIT | 
| 241270   | Finaled   | 6016  |        | NAMAKAGAN  | RD     |         | BETHESDA      | MD    | 20816 | DEMOLISH | SINGLE FAMILY DWELLING | 2001-02-23T11:02:43 | 2001-07-16T07:07:00 | 2001-09-19T01:09:00 |                                                                                                                                                         | DEMOLITION OR MOVE PERMIT | 
```