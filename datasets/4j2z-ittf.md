# IDPH Home Services Placement Agencies Directory

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idph-home-services-placement-agencies-directory-3603a) |
| Metadata | [Link](https://data.illinois.gov/api/views/4j2z-ittf) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/4j2z-ittf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/4j2z-ittf/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 4j2z-ittf |
| Name | IDPH Home Services Placement Agencies Directory |
| Attribution | Division of Health Care Facilities and Programs |
| Category | Public Health |
| Tags | home, services, placement |
| Created | 2012-01-30T20:14:16Z |
| Publication Date | 2017-01-06T18:25:25Z |

## Description

Current as of January 2017

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                           | Data Type | Render Type |
| ======== | ============== | ============================== | ============================== | ========= | =========== |
| No       | time           | :updated_at                    | updated_at                     | meta_data | meta_data   |
| Yes      | series tag     | home_services_placement_agency | Home Services Placement Agency | text      | text        |
| No       |                | address                        | Address                        | text      | text        |
| Yes      | series tag     | city                           | City                           | text      | text        |
| Yes      | series tag     | zip                            | Zip                            | text      | number      |
| Yes      | series tag     | county                         | County                         | text      | text        |
| Yes      | series tag     | phone                          | Phone                          | phone     | phone       |
| Yes      | numeric metric | license_                       | License #                      | number    | number      |
| Yes      | series tag     | license_expiration_date        | License Expiration Date        | html      | html        |
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
series e:4j2z-ittf d:2017-01-06T18:24:38.000Z t:zip=60515 t:license_expiration_date=03/31/17 t:phone_number="(630) 515-1672" t:county="Du Page" t:home_services_placement_agency="A Gold Coast Domestic Agency, Inc." t:city="Downers Grove" m:license_=8000125

series e:4j2z-ittf d:2017-01-06T18:24:38.000Z t:zip=60201 t:license_expiration_date=05/31/17 t:phone_number="(847) 570-4455" t:county=Cook t:home_services_placement_agency="Accurate Private Care, Inc." t:city=Evanston m:license_=8000308

series e:4j2z-ittf d:2017-01-06T18:24:38.000Z t:zip=60646 t:license_expiration_date=03/31/17 t:phone_number="(773) 355-5417" t:county=Cook t:home_services_placement_agency="All Help Health Services, Inc." t:city=Chicago m:license_=8000137
```

## Meta Commands

```ls
metric m:license_ p:integer l:"License #" t:dataTypeName=number

entity e:4j2z-ittf l:"IDPH Home Services Placement Agencies Directory" t:attribution="Division of Health Care Facilities and Programs" t:url=https://data.illinois.gov/api/views/4j2z-ittf

property e:4j2z-ittf t:meta.view v:id=4j2z-ittf v:category="Public Health" v:attributionLink=http://www.idph.state.il.us/about/ohcr.htm v:averageRating=0 v:name="IDPH Home Services Placement Agencies Directory" v:attribution="Division of Health Care Facilities and Programs"

property e:4j2z-ittf t:meta.view.owner v:id=e75b-y6hv v:screenName=Jenny v:displayName=Jenny

property e:4j2z-ittf t:meta.view.tableauthor v:id=e75b-y6hv v:screenName=Jenny v:roleName=publisher v:displayName=Jenny
```

## Top Records

```ls
| :updated_at | home_services_placement_agency            | address                               | city          | zip   | county  | phone                  | license_ | license_expiration_date | 
| =========== | ========================================= | ===================================== | ============= | ===== | ======= | ====================== | ======== | ======================= | 
| 1483727078  | A Gold Coast Domestic Agency, Inc.        | 800 Ogden Avenue, Suite 3             | Downers Grove | 60515 | Du Page | [(630) 515-1672, null] | 8000125  | 03/31/17                | 
| 1483727078  | Accurate Private Care, Inc.               | 1611 Chicago Avenue                   | Evanston      | 60201 | Cook    | [(847) 570-4455, null] | 8000308  | 05/31/17                | 
| 1483727078  | All Help Health Services, Inc.            | 6160 N. Cicero Ave., Ste. 303         | Chicago       | 60646 | Cook    | [(773) 355-5417, null] | 8000137  | 03/31/17                | 
| 1483727078  | All-Care Employment Agency                | 4955 N. Milwaukee Ave., Suite 5       | Chicago       | 60630 | Cook    | [(800) 850-1444, null] | 8000193  | 02/28/17                | 
| 1483727078  | Almost Angels, Inc.                       | 4747 W. Peterson, Suite #305          | Chicago       | 60646 | Cook    | [(773) 777-8777, null] | 8000115  | 01/31/18                | 
| 1483727078  | AP Homecare Services                      | 3063 North Milwaukee Ave.             | Chicago       | 60618 | Cook    | [(773) 267-9201, null] | 8000197  | 03/31/17                | 
| 1483727078  | At Home With You, LLC                     | 720 Heath Court                       | Westmont      | 60559 | Du Page | [(630) 786-6070, null] | 8000249  | 10/31/17                | 
| 1483727078  | At Your Service Eurocare                  | 181 Waukegan Rd., Ste. 201            | Northfield    | 60093 | Cook    | [(773) 545-5100, null] | 8000147  | 04/30/17                | 
| 1483727078  | Axxus Group, Inc - DBA Affinity Home Care | 401 S. Milwaukee Ave. #250            | Wheeling      | 60090 | Cook    | [(847) 282-0256, null] | 8000289  | 11/30/17                | 
| 1483727078  | Best Care For You, Inc.                   | 4701 North Cumberland Avenue Suite 12 | Norridge      | 60706 | Cook    | [(708) 452-8800, null] | 8000320  | 08/31/17                | 
```