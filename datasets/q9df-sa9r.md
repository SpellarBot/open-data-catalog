# Agricultural Producer Certificates

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/agricultural-producer-certificates) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/q9df-sa9r) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/q9df-sa9r/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/q9df-sa9r/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | q9df-sa9r |
| Name | Agricultural Producer Certificates |
| Attribution | Montgomery County, MD |
| Category | Licenses/Permits |
| Tags | agricultural, producer, certificates |
| Created | 2016-02-16T23:25:55Z |
| Publication Date | 2016-02-19T13:33:41Z |

## Description

A Certified Agricultural Producer, or representative thereof, is an individual who wishes to sell regionally-grown products in the public right-of-way.  A Certified Agricultural Producer, or representative thereof, may sell only fresh fruits, vegetables, herbs, cut flowers, small trees, or plants, which he or she has produced. A Certified Agricultural Producer may also sell non-potentially-hazardous prepackaged goods (including eggs), with the approval of the Licensure and Regulatory Services Section of the Department of Health and Human Services.  The dataset contains information for active Agricultural Producer certificates (not voided, not Stop Work Order).
Data Refresh Frequency - Daily

## Columns

```ls
| Included | Schema Type | Field Name        | Name                         | Data Type     | Render Type   |
| ======== | =========== | ================= | ============================ | ============= | ============= |
| Yes      | series tag  | applicationtype   | Application Type             | text          | text          |
| Yes      | series tag  | license_no        | License Number               | text          | text          |
| Yes      | time        | processed_date    | Processed Date               | calendar_date | calendar_date |
| No       |             | license_date      | License Date                 | calendar_date | calendar_date |
| No       |             | issued_date       | Issued Date                  | calendar_date | calendar_date |
| No       |             | last_renewal_date | Last Renewal Date            | calendar_date | calendar_date |
| No       |             | next_renewal_date | Next Renewal Date            | calendar_date | calendar_date |
| No       |             | expire_date       | License Expiration Date      | calendar_date | calendar_date |
| Yes      | series tag  | in_county         | IN_COUNTY                    | text          | text          |
| Yes      | series tag  | out_county        | OUT_COUNTY                   | text          | text          |
| Yes      | series tag  | product_sold      | PRODUCT_SOLD                 | text          | text          |
| Yes      | series tag  | farm_name         | Farm name                    | text          | text          |
| Yes      | series tag  | stno              | Street Number                | text          | text          |
| Yes      | series tag  | predir            | Pre-direction                | text          | text          |
| Yes      | series tag  | stname            | Street name of work location | text          | text          |
| Yes      | series tag  | suffix            | Street Suffix                | text          | text          |
| Yes      | series tag  | postdir           | Post-direction               | text          | text          |
| Yes      | series tag  | city              | City                         | text          | text          |
| Yes      | series tag  | state             | State                        | text          | text          |
| Yes      | series tag  | zip               | ZIP code                     | text          | text          |
| Yes      | series tag  | location          | Work Location                | text          | text          |
```

## Time Field

```ls
Value = processed_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = license_date,issued_date,last_renewal_date,next_renewal_date,expire_date
```

## Data Commands

```ls
series e:q9df-sa9r d:2004-06-16T09:06:18.000Z t:stno=11918 t:zip=20854 t:license_no=203907 t:applicationtype="AGRICULTURAL PRODUCERS CERTIF" t:product_sold=PRODUCE t:state=MD t:farm_name="LEWIS ORCHARD" t:stname="GLEN MILL" t:in_county=Y t:out_county=N t:suffix=RD t:city=POTOMAC m:row_number.q9df-sa9r=1

series e:q9df-sa9r d:2003-10-01T03:10:24.000Z t:stno=23830 t:zip=20842 t:license_no=203032 t:applicationtype="AGRICULTURAL PRODUCERS CERTIF" t:product_sold=PRODUCE t:state=MD t:farm_name="HEISLER FARM" t:stname="OLD HUNDRED" t:in_county=Y t:out_county=N t:suffix=RD t:city=DICKERSON m:row_number.q9df-sa9r=2

series e:q9df-sa9r d:2014-04-10T09:04:35.000Z t:stno=1500 t:zip=20910 t:license_no=221024 t:applicationtype="AGRICULTURAL PRODUCERS CERTIF" t:product_sold=PRODUCE t:state=MD t:farm_name="CALVERT FARM" t:stname="FOREST GLEN" t:in_county=Y t:out_county=N t:suffix=RD t:city="SILVER SPRING" m:row_number.q9df-sa9r=3
```

## Meta Commands

```ls
metric m:row_number.q9df-sa9r p:long l:"Row Number"

entity e:q9df-sa9r l:"Agricultural Producer  Certificates" t:attribution="Montgomery County, MD" t:url=https://data.montgomerycountymd.gov/api/views/q9df-sa9r

property e:q9df-sa9r t:meta.view d:2017-06-09T13:51:43.342Z v:id=q9df-sa9r v:category=Licenses/Permits v:averageRating=0 v:name="Agricultural Producer  Certificates" v:attribution="Montgomery County, MD"

property e:q9df-sa9r t:meta.view.license d:2017-06-09T13:51:43.342Z v:name="Public Domain"

property e:q9df-sa9r t:meta.view.owner d:2017-06-09T13:51:43.342Z v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"

property e:q9df-sa9r t:meta.view.tableauthor d:2017-06-09T13:51:43.342Z v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:roleName=administrator v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"
```

## Top Records

```ls
| applicationtype               | license_no | processed_date      | license_date        | issued_date         | last_renewal_date   | next_renewal_date   | expire_date         | in_county | out_county | product_sold      | farm_name                   | stno  | predir | stname       | suffix | postdir | city          | state | zip   | location      | 
| ============================= | ========== | =================== | =================== | =================== | =================== | =================== | =================== | ========= | ========== | ================= | =========================== | ===== | ====== | ============ | ====== | ======= | ============= | ===== | ===== | ============= | 
| AGRICULTURAL PRODUCERS CERTIF | 203907     | 2004-06-16T09:06:18 | 2004-06-17T02:06:00 | 2004-06-17T02:06:00 | 2007-04-30T07:04:47 | 2008-04-25T12:04:00 | 2008-04-25T12:04:00 | Y         | N          | PRODUCE           | LEWIS ORCHARD               | 11918 |        | GLEN MILL    | RD     |         | POTOMAC       | MD    | 20854 |               | 
| AGRICULTURAL PRODUCERS CERTIF | 203032     | 2003-10-01T03:10:24 | 2003-10-01T03:10:00 | 2003-10-23T09:10:00 | 2005-09-27T01:09:00 | 2006-09-27T12:09:00 | 2006-09-27T12:09:00 | Y         | N          | PRODUCE           | HEISLER FARM                | 23830 |        | OLD HUNDRED  | RD     |         | DICKERSON     | MD    | 20842 |               | 
| AGRICULTURAL PRODUCERS CERTIF | 221024     | 2014-04-10T09:04:35 | 2014-04-10T09:04:50 |                     |                     |                     |                     | Y         | N          | PRODUCE           | CALVERT FARM                | 1500  |        | FOREST GLEN  | RD     |         | SILVER SPRING | MD    | 20910 |               | 
| AGRICULTURAL PRODUCERS CERTIF | 202559     | 2003-06-23T10:06:36 | 2003-06-23T10:06:40 | 2005-02-02T02:02:17 |                     | 2006-02-02T12:02:00 | 2006-02-02T12:02:00 | N         | Y          | PRODUCE AND TREES | NEW HAMPSHIRE FARMS         | 4200  |        | SANDY SPRING | RD     |         | BURTONSVILLE  | MD    | 20866 |               | 
| AGRICULTURAL PRODUCERS CERTIF | 207000     | 2006-07-07T11:07:21 | 2006-07-07T12:07:00 |                     |                     |                     |                     | Y         | N          | PRODUCE           | THE FARMER'S MARKET         |       |        |              |        |         |               |       |       | SEVERAL SITES | 
| AGRICULTURAL PRODUCERS CERTIF | 224565     | 2016-01-04T02:01:09 | 2016-01-04T02:01:12 | 2016-01-07T07:01:28 |                     | 2017-01-07T07:01:28 | 2017-01-07T07:01:28 | Y         | N          | PRODUCE           | PLEASANT VALLEY FARM        | 27130 |        | RIDGE        | RD     |         | DAMASCUS      | MD    | 20872 |               | 
| AGRICULTURAL PRODUCERS CERTIF | 215615     | 2011-05-20T09:05:30 | 2011-05-20T09:05:53 | 2011-05-26T03:05:38 |                     | 2012-05-26T12:05:00 | 2012-05-26T12:05:00 | N         | Y          | PRODUCE           | VINCENT FARMS               | 25810 |        | FREDERICK    | RD     |         | CLARKSBURG    | MD    | 20871 |               | 
| AGRICULTURAL PRODUCERS CERTIF | 200061     | 1999-11-19T02:11:50 | 1999-11-19T02:11:00 | 1999-12-01T11:12:28 | 2000-11-17T12:11:00 | 2001-11-17T12:11:00 | 2001-11-17T12:11:00 | N         | Y          | TREES             | AHEARN & CANNON             | 2601  |        | COLSTON      | DR     |         | CHEVY CHASE   | MD    | 20815 |               | 
| AGRICULTURAL PRODUCERS CERTIF | 210300     | 2008-07-18T12:07:45 | 2008-07-18T12:07:43 | 2008-07-18T12:07:07 |                     | 2009-07-18T12:07:00 | 2009-07-18T12:07:00 | Y         | N          | PRODUCE           | ELLIOT'S FARM FRESH PRODUCE | 9600  |        | BRINK        | RD     |         | GAITHERSBURG  | MD    | 20882 |               | 
| AGRICULTURAL PRODUCERS CERTIF | 200070     | 1999-11-24T10:11:41 | 1999-11-24T10:11:00 |                     |                     | 2001-11-24T12:11:00 | 2001-11-24T12:11:00 | N         | Y          | TREES             | WEAVER TREE FARM            | 3100  |        | HOLIDAY      | DR     |         | BROOKEVILLE   | MD    | 20833 |               | 
```