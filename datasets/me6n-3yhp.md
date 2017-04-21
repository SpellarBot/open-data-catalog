# DAS Procurement Supplier Diversity Certifications

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/das-procurement-supplier-diversity-certifications) |
| Metadata | [Link](https://data.ct.gov/api/views/me6n-3yhp) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/me6n-3yhp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/me6n-3yhp/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | me6n-3yhp |
| Name | DAS Procurement Supplier Diversity Certifications |
| Attribution | DAS Procurement |
| Category | Business |
| Tags | procurement |
| Created | 2015-08-14T17:08:26Z |
| Publication Date | 2015-08-24T18:31:37Z |

## Description

Small, women, minority and disabled-owned businesses certified to participate in the Connecticut's Set-Aside Program. Updated Nightly

## Columns

```ls
| Included | Schema Type | Field Name        | Name              | Data Type     | Render Type   |
| ======== | =========== | ================= | ================= | ============= | ============= |
| Yes      | series tag  | vendorid          | VendorId          | text          | number        |
| Yes      | series tag  | vendorname        | VendorName        | text          | text          |
| No       |             | businessaddress1  | BusinessAddress1  | text          | text          |
| No       |             | businessaddress2  | BusinessAddress2  | text          | text          |
| Yes      | series tag  | businessstate     | BusinessState     | text          | text          |
| Yes      | series tag  | businesscity      | BusinessCity      | text          | text          |
| Yes      | series tag  | businesszipcode   | BusinessZipCode   | text          | text          |
| Yes      | series tag  | certificationtype | CertificationType | text          | text          |
| Yes      | series tag  | classdescription  | ClassDescription  | text          | text          |
| Yes      | series tag  | woman             | Woman             | text          | text          |
| Yes      | series tag  | disabled          | Disabled          | text          | text          |
| Yes      | time        | activedate        | ActiveDate        | calendar_date | calendar_date |
| No       |             | expirationdate    | ExpirationDate    | calendar_date | calendar_date |
| Yes      | series tag  | details           | Details           | url           | url           |
| No       |             | datemodified      | DateModified      | calendar_date | calendar_date |
```

## Time Field

```ls
Value = activedate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = businessaddress1,businessaddress2,expirationdate,datemodified
```

## Data Commands

```ls
series e:me6n-3yhp d:2014-11-20T00:00:00.000Z t:vendorname="A.J. PENNA & SON CONSTRUCTION, INC" t:businessstate=CT t:details="https://www.biznet.ct.gov/SDSearch/SDSearchDetails.aspx?CID=24289" t:vendorid=12826 t:certificationtype=SBE t:woman=No t:businesszipcode=06880 t:classdescription=None t:disabled=No t:businesscity=Westport m:row_number.me6n-3yhp=1

series e:me6n-3yhp d:2014-09-09T00:00:00.000Z t:vendorname="Champion Maintenance Services" t:businessstate=CT t:details="https://www.biznet.ct.gov/SDSearch/SDSearchDetails.aspx?CID=31890" t:vendorid=18051 t:certificationtype=SBE t:woman=No t:businesszipcode=06825 t:classdescription=None t:disabled=No t:businesscity=Fairfeld m:row_number.me6n-3yhp=2

series e:me6n-3yhp d:2016-05-06T00:00:00.000Z t:vendorname="Axela Kitchens LLC" t:businessstate=CT t:vendorid=20608 t:certificationtype=MBE t:woman=Yes t:businesszipcode=06712 t:classdescription=None t:disabled=No t:businesscity=Prospect m:row_number.me6n-3yhp=3
```

## Meta Commands

```ls
metric m:row_number.me6n-3yhp p:long l:"Row Number"

entity e:me6n-3yhp l:"DAS Procurement Supplier Diversity Certifications" t:attribution="DAS Procurement" t:url=https://data.ct.gov/api/views/me6n-3yhp

property e:me6n-3yhp t:meta.view v:id=me6n-3yhp v:category=Business v:averageRating=0 v:name="DAS Procurement Supplier Diversity Certifications" v:attribution="DAS Procurement"

property e:me6n-3yhp t:meta.view.license v:name="Public Domain"

property e:me6n-3yhp t:meta.view.owner v:id=ksrh-ut6b v:screenName="Open Data Hub" v:displayName="Open Data Hub"

property e:me6n-3yhp t:meta.view.tableauthor v:id=ksrh-ut6b v:screenName="Open Data Hub" v:roleName=publisher v:displayName="Open Data Hub"
```

## Top Records

```ls
| vendorid | vendorname                              | businessaddress1         | businessaddress2 | businessstate | businesscity      | businesszipcode | certificationtype | classdescription | woman | disabled | activedate          | expirationdate      | details                                                                   | datemodified        | 
| ======== | ======================================= | ======================== | ================ | ============= | ================= | =============== | ================= | ================ | ===== | ======== | =================== | =================== | ========================================================================= | =================== | 
| 12826    | A.J. PENNA & SON CONSTRUCTION, INC      | 46 Indian Hill Road      |                  | CT            | Westport          | 06880           | SBE               | None             | No    | No       | 2014-11-20T00:00:00 | 2016-11-20T00:00:00 | [https://www.biznet.ct.gov/SDSearch/SDSearchDetails.aspx?CID=24289, null] | 2016-10-21T00:00:00 | 
| 18051    | Champion Maintenance Services           | 301 Commerce Drive       |                  | CT            | Fairfeld          | 06825           | SBE               | None             | No    | No       | 2014-09-09T00:00:00 | 2016-09-09T00:00:00 | [https://www.biznet.ct.gov/SDSearch/SDSearchDetails.aspx?CID=31890, null] | 2016-08-10T00:00:00 | 
| 20608    | Axela Kitchens LLC                      | 34 Waterbury Road        | #1               | CT            | Prospect          | 06712           | MBE               | None             | Yes   | No       | 2016-05-06T00:00:00 | 2018-04-26T00:00:00 | [null, null]                                                              | 2016-05-05T00:00:00 | 
| 11242    | Advanced Construction Technologies, LLC | 30 Hazel Terrace Suite 2 |                  | CT            | Woodbridge        | 06525           | MBE               | African-American | No    | No       | 2014-07-15T00:00:00 | 2016-07-15T00:00:00 | [https://www.biznet.ct.gov/SDSearch/SDSearchDetails.aspx?CID=32419, null] | 2016-06-15T00:00:00 | 
| 18342    | Connecticut Combustion Corporation      | 40 Whittemore Road       |                  | CT            | Middlebury        | 06762           | SBE               | None             | No    | No       | 2015-02-04T00:00:00 | 2017-02-04T00:00:00 | [https://www.biznet.ct.gov/SDSearch/SDSearchDetails.aspx?CID=34685, null] | 2017-01-05T00:00:00 | 
| 28753    | Michael's painting services             | Dunfey lane              |                  | CT            | Windsor           | 06095           | MBE               | African-American | No    | No       | 2016-05-03T00:00:00 | 2018-05-03T00:00:00 | [null, null]                                                              | 2016-05-03T00:00:00 | 
| 13637    | CTR, LLC                                | 23 Eastford Road         |                  | CT            | Eastford          | 06242           | SBE               | None             | No    | No       | 2015-12-19T00:00:00 | 2017-12-18T00:00:00 | [null, null]                                                              | 2015-12-07T00:00:00 | 
| 21517    | Mark O. Weeks Inc                       | 13 Lisbon Rd             |                  | CT            | Canterbury, 06331 | 06331           | SBE               | None             | No    | No       | 2015-09-13T00:00:00 | 2017-09-13T00:00:00 | [null, null]                                                              | 2015-10-07T00:00:00 | 
| 19580    | ColorFuzion Web Designs LLC             | 6 Timber lane            |                  | CT            | Guilford          | 06437           | MBE               | None             | Yes   | No       | 2014-04-25T00:00:00 | 2016-04-25T00:00:00 | [null, null]                                                              | 2016-03-26T00:00:00 | 
| 13672    | DWoodward LLC                           | 682 Bloomfield Ave.      |                  | CT            | Bloomfield        | 06002           | SBE               | None             | No    | No       | 2014-04-28T00:00:00 | 2016-04-28T00:00:00 | [null, null]                                                              | 2016-03-29T00:00:00 | 
```