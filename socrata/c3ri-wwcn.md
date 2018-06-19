# 2011 Active Business License Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2011-active-business-license-data-d8e86) |
| Metadata | [Link](https://data.seattle.gov/api/views/c3ri-wwcn) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/c3ri-wwcn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/c3ri-wwcn/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | c3ri-wwcn |
| Name | 2011 Active Business License Data |
| Attribution | City of Seattle - Dept of Finance and Administrative Services |
| Category | Finance |
| Tags | business license |
| Created | 2011-10-26T17:47:44Z |
| Publication Date | 2015-05-11T19:05:08Z |

## Description

Dataset contains active business license data for the City of Seattle for 2011.

## Columns

```ls
| Included | Schema Type | Field Name          | Name                | Data Type     | Render Type   |
| ======== | =========== | =================== | =================== | ============= | ============= |
| Yes      | series tag  | business_legal_name | Business Legal Name | text          | text          |
| Yes      | series tag  | ownership_type      | Ownership Type      | text          | text          |
| Yes      | series tag  | trade_name          | Trade Name          | text          | text          |
| Yes      | series tag  | naics_code          | NAICS Code          | text          | number        |
| Yes      | series tag  | naics_description   | NAICS Description   | text          | text          |
| Yes      | time        | license_start_date  | License Start Date  | calendar_date | calendar_date |
| Yes      | series tag  | city_state_zip      | City, State, Zip    | text          | text          |
```

## Time Field

```ls
Value = license_start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:c3ri-wwcn d:2010-02-01T08:00:00.000Z t:city_state_zip="SEATTLE, WA   98178" t:ownership_type="Sole Proprietor" t:business_legal_name="FATUR ELIZABETH" t:naics_description="Nonstore Retailers" t:trade_name=WHOLESOULART t:naics_code=454 m:row_number.c3ri-wwcn=1

series e:c3ri-wwcn d:2009-01-01T08:00:00.000Z t:city_state_zip="SEATTLE, WA   98101" t:ownership_type=Corporation t:business_legal_name="MARK A BROWN PS" t:naics_description="Offices of Lawyers" t:trade_name="MARK A BROWN P.S." t:naics_code=541110 m:row_number.c3ri-wwcn=2

series e:c3ri-wwcn d:2010-05-15T07:00:00.000Z t:city_state_zip="SEATTLE, WA   98106" t:ownership_type=Corporation t:business_legal_name="VMC LLC" t:naics_description="Mobile Food Services" t:trade_name="CHARLIE'S DOG HOUSE" t:naics_code=722330 m:row_number.c3ri-wwcn=3
```

## Meta Commands

```ls
metric m:row_number.c3ri-wwcn p:long l:"Row Number"

entity e:c3ri-wwcn l:"2011 Active Business License Data" t:attribution="City of Seattle - Dept of Finance and Administrative Services" t:url=https://data.seattle.gov/api/views/c3ri-wwcn

property e:c3ri-wwcn t:meta.view v:id=c3ri-wwcn v:category=Finance v:averageRating=0 v:name="2011 Active Business License Data" v:attribution="City of Seattle - Dept of Finance and Administrative Services"

property e:c3ri-wwcn t:meta.view.license v:name="Public Domain"

property e:c3ri-wwcn t:meta.view.owner v:id=n3fs-imjt v:screenName=JLCarnell v:displayName=JLCarnell

property e:c3ri-wwcn t:meta.view.tableauthor v:id=n3fs-imjt v:screenName=JLCarnell v:roleName=publisher v:displayName=JLCarnell
```

## Top Records

```ls
| business_legal_name | ownership_type           | trade_name          | naics_code | naics_description    | license_start_date  | city_state_zip         | 
| =================== | ======================== | =================== | ========== | ==================== | =================== | ====================== | 
| FATUR ELIZABETH     | Sole Proprietor          | WHOLESOULART        | 454        | Nonstore Retailers   | 2010-02-01T08:00:00 | SEATTLE, WA 98178      | 
| MARK A BROWN PS     | Corporation              | MARK A BROWN P.S.   | 541110     | Offices of Lawyers   | 2009-01-01T08:00:00 | SEATTLE, WA 98101      | 
| VMC LLC             | Corporation              | CHARLIE'S DOG HOUSE | 722330     | Mobile Food Services | 2010-05-15T07:00:00 | SEATTLE, WA 98106      | 
| GOBEZE ZERADAWIT G  | Sole Proprietor          | ZERADAWIT GOBEZE    | 485310     | Taxi Service         | 2010-05-11T07:00:00 | SEA TAC, WA 98188      | 
| NOLAN PRIOR LLC     | LLC*Limited Liability Co | NOLAN PRIOR LLC     | 525930     |                      | 2010-05-01T07:00:00 | SEATTLE, WA 98136-1872 | 
| SINGH PAWANDEEP     | Sole Proprietor          | STITA CAB           | 485310     | Taxi Service         | 2010-05-20T07:00:00 | SEA TAC, WA 98168      | 
| QUINN AMANDA        | Sole Proprietor          | AG QUINN            | 453920     | Art Dealers          | 2009-12-12T08:00:00 | SEATTLE, WA 98144      | 
| NEWMAN JESSICA      | Sole Proprietor          | JESKA NEWMAN HAIR   | 812112     | Beauty Salons        | 2010-06-07T07:00:00 | SEATTLE, WA 98115-6616 | 
| LEWIS DAVID J       | Sole Proprietor          | DRIVER DAVE         | 485310     | Taxi Service         | 2010-06-29T07:00:00 | SEATTLE, WA 98105      | 
| UNEEK USA INC       | Corporation              | SMOKE SHOP          | 453991     | Tobacco Stores       | 2010-07-01T07:00:00 | SEATTLE, WA 98101      | 
```