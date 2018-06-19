# Currently Licensed Real Estate Appraisers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/currently-licensed-real-estate-appraisers) |
| Metadata | [Link](https://data.ny.gov/api/views/3nr4-s9yt) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/3nr4-s9yt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/3nr4-s9yt/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 3nr4-s9yt |
| Name | Currently Licensed Real Estate Appraisers |
| Attribution | New York State Department of State |
| Category | Economic Development |
| Tags | appraisers, real estate, property value, valuation |
| Created | 2016-06-06T14:46:42Z |
| Publication Date | 2017-04-20T10:09:27Z |

## Description

This data contains information for all currently active Real Estate Appraiser licensees.  Each record will be for an individual licensee, and will contain their Name, Unique Identification Number, License Type, Original Certification Date, Current Certification and Expiration Dates, Reciprocal State (if any), the Name of the Business they are associated with, and the Business?s Address.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name                        | Data Type     | Render Type   |
| ======== | ============== | ============== | =========================== | ============= | ============= |
| Yes      | series tag     | prin_bus_name  | Principal Business Name     | text          | text          |
| No       |                | prin_bus_addr1 | Principal Business Address  | text          | text          |
| No       |                | apt            | Additional Address          | text          | text          |
| Yes      | series tag     | business_city  | Business City               | text          | text          |
| No       |                | st             | Business State              | text          | text          |
| Yes      | series tag     | zip_code       | Business Zip                | text          | text          |
| Yes      | series tag     | county         | Business County             | text          | text          |
| Yes      | series tag     | applicant_name | Applicant Name              | text          | text          |
| Yes      | time           | org_date       | Original Certification Date | calendar_date | calendar_date |
| No       |                | cert_date      | Certification Date          | calendar_date | calendar_date |
| No       |                | exp_date       | Expiration Date             | calendar_date | calendar_date |
| Yes      | numeric metric | uid            | Unique ID                   | number        | number        |
| Yes      | series tag     | license_type   | License Type                | text          | text          |
| Yes      | series tag     | reciprocal_st  | Reciprocal State            | text          | text          |
```

## Time Field

```ls
Value = org_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = prin_bus_addr1,apt,st,cert_date,exp_date
```

## Data Commands

```ls
series e:3nr4-s9yt d:2003-12-22T00:00:00.000Z t:license_type="LICENSED REAL ESTATE APPRAISER ASSISTANT" t:zip_code=11733 t:county=SUFFOLK t:prin_bus_name="A & R APPRAISAL" t:business_city="EAST STAUKET" t:applicant_name="RUSSO STEPHANIE M" m:uid=48000043292

series e:3nr4-s9yt d:2010-04-19T00:00:00.000Z t:license_type="CERTIFIED RESIDENTIAL REAL ESTATE APPRAISER" t:zip_code=11435 t:county=QUEENS t:prin_bus_name="A & S APPRAISAL AND EVALUATION SERVICES LLC" t:business_city=JAMAICA t:applicant_name="DYER SEBERT" m:uid=45000049673

series e:3nr4-s9yt d:2006-09-18T00:00:00.000Z t:license_type="CERTIFIED RESIDENTIAL REAL ESTATE APPRAISER" t:zip_code=11787 t:county=SUFFOLK t:prin_bus_name="A & S REAL ESTATE APPRAISALS" t:business_city=SMITHTOWN t:applicant_name="SARIN ROHIT" m:uid=45000047061
```

## Meta Commands

```ls
metric m:uid p:long l:"Unique ID" d:"Appraiser?s unique identification number assigned by DOS" t:dataTypeName=number

entity e:3nr4-s9yt l:"Currently Licensed Real Estate Appraisers" t:attribution="New York State Department of State" t:url=https://data.ny.gov/api/views/3nr4-s9yt

property e:3nr4-s9yt t:meta.view v:id=3nr4-s9yt v:category="Economic Development" v:attributionLink=http://www.dos.ny.gov/licensing/ v:averageRating=0 v:name="Currently Licensed Real Estate Appraisers" v:attribution="New York State Department of State"

property e:3nr4-s9yt t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:3nr4-s9yt t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| prin_bus_name                               | prin_bus_addr1      | apt       | business_city | st | zip_code   | county    | applicant_name    | org_date            | cert_date           | exp_date            | uid         | license_type                                | reciprocal_st | 
| =========================================== | =================== | ========= | ============= | == | ========== | ========= | ================= | =================== | =================== | =================== | =========== | =========================================== | ============= | 
| A & R APPRAISAL                             | 12 BRANCH LN        |           | EAST STAUKET  | NY | 11733      | SUFFOLK   | RUSSO STEPHANIE M | 2003-12-22T00:00:00 | 2015-12-22T00:00:00 | 2017-12-21T00:00:00 | 48000043292 | LICENSED REAL ESTATE APPRAISER ASSISTANT    |               | 
| A & S APPRAISAL AND EVALUATION SERVICES LLC | 110 14 STUPHIN BLVD |           | JAMAICA       | NY | 11435      | QUEENS    | DYER SEBERT       | 2010-04-19T00:00:00 | 2016-04-19T00:00:00 | 2018-04-18T00:00:00 | 45000049673 | CERTIFIED RESIDENTIAL REAL ESTATE APPRAISER |               | 
| A & S REAL ESTATE APPRAISALS                | 114 REDAN DR        |           | SMITHTOWN     | NY | 11787      | SUFFOLK   | SARIN ROHIT       | 2006-09-18T00:00:00 | 2016-09-18T00:00:00 | 2018-09-17T00:00:00 | 45000047061 | CERTIFIED RESIDENTIAL REAL ESTATE APPRAISER |               | 
| A & S REAL ESTATE APPRAISALS INC            | 114 REDAN DR        |           | SMITHTOWN     | NY | 11787-4408 | SUFFOLK   | SARIN ASHWIN      | 2007-09-10T00:00:00 | 2015-09-10T00:00:00 | 2017-09-09T00:00:00 | 45000048263 | CERTIFIED RESIDENTIAL REAL ESTATE APPRAISER |               | 
| A AMZALLAG REALTY                           | 345 E 80TH ST       |           | NEW YORK      | NY | 10021      | NEW YORK  | AMZALLAG ARMAND   | 1991-11-18T00:00:00 | 2015-11-19T00:00:00 | 2017-11-18T00:00:00 | 46000000038 | CERTIFIED GENERAL REAL ESTATE APPRAISER     |               | 
| A AND S REAL ESTATE APPRAISALS INC          | 114 REDAN DR        |           | SMITHTOWN     | NY | 11787      | SUFFOLK   | SARIN ASHOK       | 2001-12-10T00:00:00 | 2015-12-10T00:00:00 | 2017-12-09T00:00:00 | 48000040180 | LICENSED REAL ESTATE APPRAISER ASSISTANT    |               | 
| A BRYANT APPRAISALS INC                     | 66 COREY AVE        |           | BLUE POINT    | NY | 11715      | SUFFOLK   | BRYANT AMANDA L   | 2006-05-08T00:00:00 | 2016-05-08T00:00:00 | 2018-05-07T00:00:00 | 45000046504 | CERTIFIED RESIDENTIAL REAL ESTATE APPRAISER |               | 
| A C APPRAISALS SERVICES CO                  | 18 WILSON BLVD      |           | ISLIP         | NY | 11751      | SUFFOLK   | COLE ANDREW M     | 2007-08-06T00:00:00 | 2015-08-06T00:00:00 | 2017-08-05T00:00:00 | 45000047548 | CERTIFIED RESIDENTIAL REAL ESTATE APPRAISER |               | 
| A F LAMA REALTY SERVICES INC                | 640 PARK AVENUE     |           | HOBOKEN       | NJ | 07030      | N/A       | LAMA ANTHONY F    | 1992-02-10T00:00:00 | 2016-02-11T00:00:00 | 2018-02-10T00:00:00 | 46000005807 | CERTIFIED GENERAL REAL ESTATE APPRAISER     | NJ            | 
| A MARVIN APPRAISALS LLC                     | 311 BROWN BLVD      | PO BOX 55 | BROWNVILLE    | NY | 13615      | JEFFERSON | MARVIN APRIL L    | 2015-01-09T00:00:00 | 2017-01-09T00:00:00 | 2019-01-08T00:00:00 | 45000051139 | CERTIFIED RESIDENTIAL REAL ESTATE APPRAISER |               | 
```