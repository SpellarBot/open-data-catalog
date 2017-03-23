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
| Rows Updated | 2016-09-16T10:25:52Z |

## Description

A Certified Agricultural Producer, or representative thereof, is an individual who wishes to sell regionally-grown products in the public right-of-way.  A Certified Agricultural Producer, or representative thereof, may sell only fresh fruits, vegetables, herbs, cut flowers, small trees, or plants, which he or she has produced. A Certified Agricultural Producer may also sell non-potentially-hazardous prepackaged goods (including eggs), with the approval of the Licensure and Regulatory Services Section of the Department of Health and Human Services.  The dataset contains information for active Agricultural Producer certificates (not voided, not Stop Work Order).
Data Refresh Frequency - Daily

## Columns

```ls
| Included | Schema Type | Field Name        | Name                         | Data Type | Render Type   |
| ======== | =========== | ================= | ============================ | ========= | ============= |
| No       | time        | :updated_at       | updated_at                   | meta_data | meta_data     |
| Yes      | series tag  | applicationtype   | Application Type             | text      | text          |
| Yes      | series tag  | license_no        | License Number               | text      | text          |
| No       |             | processed_date    | Processed Date               | text      | calendar_date |
| Yes      | series tag  | license_date      | License Date                 | text      | calendar_date |
| No       |             | issued_date       | Issued Date                  | text      | calendar_date |
| No       |             | last_renewal_date | Last Renewal Date            | text      | calendar_date |
| No       |             | next_renewal_date | Next Renewal Date            | text      | calendar_date |
| No       |             | expire_date       | License Expiration Date      | text      | calendar_date |
| Yes      | series tag  | in_county         | IN_COUNTY                    | text      | text          |
| Yes      | series tag  | out_county        | OUT_COUNTY                   | text      | text          |
| Yes      | series tag  | product_sold      | PRODUCT_SOLD                 | text      | text          |
| Yes      | series tag  | farm_name         | Farm name                    | text      | text          |
| Yes      | series tag  | stno              | Street Number                | text      | text          |
| Yes      | series tag  | predir            | Pre-direction                | text      | text          |
| Yes      | series tag  | stname            | Street name of work location | text      | text          |
| Yes      | series tag  | suffix            | Street Suffix                | text      | text          |
| Yes      | series tag  | postdir           | Post-direction               | text      | text          |
| Yes      | series tag  | city              | City                         | text      | text          |
| Yes      | series tag  | state             | State                        | text      | text          |
| Yes      | series tag  | zip               | ZIP code                     | text      | text          |
| Yes      | series tag  | location          | Work Location                | text      | text          |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = processed_date,issued_date,last_renewal_date,next_renewal_date,expire_date
```

## Data Commands

```ls
series e:q9df-sa9r d:2016-02-17T08:30:33.000Z t:stno=11918 t:zip=20854 t:license_no=203907 t:state=MD t:out_county=N t:in_county=Y t:stname="GLEN MILL" t:suffix=RD t:city=POTOMAC t:applicationtype="AGRICULTURAL PRODUCERS CERTIF" t:product_sold=PRODUCE t:license_date=2004-06-17T02:06:00 t:farm_name="LEWIS ORCHARD" m:row_number.q9df-sa9r=1

series e:q9df-sa9r d:2016-02-17T08:30:33.000Z t:stno=23830 t:zip=20842 t:license_no=203032 t:state=MD t:out_county=N t:in_county=Y t:stname="OLD HUNDRED" t:suffix=RD t:city=DICKERSON t:applicationtype="AGRICULTURAL PRODUCERS CERTIF" t:product_sold=PRODUCE t:license_date=2003-10-01T03:10:00 t:farm_name="HEISLER FARM" m:row_number.q9df-sa9r=2

series e:q9df-sa9r d:2016-02-17T08:30:33.000Z t:stno=1500 t:zip=20910 t:license_no=221024 t:state=MD t:out_county=N t:in_county=Y t:stname="FOREST GLEN" t:suffix=RD t:city="SILVER SPRING" t:applicationtype="AGRICULTURAL PRODUCERS CERTIF" t:product_sold=PRODUCE t:license_date=2014-04-10T09:04:50 t:farm_name="CALVERT FARM" m:row_number.q9df-sa9r=3
```

## Meta Commands

```ls
metric m:row_number.q9df-sa9r p:long l:"Row Number"

entity e:q9df-sa9r l:"Agricultural Producer  Certificates" t:attribution="Montgomery County, MD" t:url=https://data.montgomerycountymd.gov/api/views/q9df-sa9r

property e:q9df-sa9r t:meta.view v:id=q9df-sa9r v:category=Licenses/Permits v:averageRating=0 v:name="Agricultural Producer  Certificates" v:attribution="Montgomery County, MD"

property e:q9df-sa9r t:meta.view.license v:name="Public Domain"

property e:q9df-sa9r t:meta.view.owner v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:displayName="MCG ESB Service"

property e:q9df-sa9r t:meta.view.tableauthor v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:roleName=administrator v:displayName="MCG ESB Service"
```