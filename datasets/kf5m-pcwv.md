# Administrative Discretionary Grants (FY 1996-2014)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/administrative-discretionary-grants-fy-1996-2014) |
| Metadata | [Link](https://data.imls.gov/api/views/kf5m-pcwv) |
| Data: JSON | [100 Rows](https://data.imls.gov/api/views/kf5m-pcwv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.imls.gov/api/views/kf5m-pcwv/rows.csv?max_rows=100) |
| Host | data.imls.gov |
| Id | kf5m-pcwv |
| Name | Administrative Discretionary Grants (FY 1996-2014) |
| Attribution | IMLS |
| Category | Administrative Data |
| Tags | imls, discretionary, grants |
| Created | 2014-06-05T21:47:21Z |
| Publication Date | 2015-08-20T22:03:04Z |

## Description

Review the administrative records for discretionary grant recipients who were awarded funds by IMLS from FY 1996 to FY 2014. Data include information on the institution, grant project name, grant award amount, matching funds, and the start and end dates of the grant. Geographic information is also included.

## Columns

```ls
| Included | Schema Type    | Field Name                         | Name                               | Data Type     | Render Type   |
| ======== | ============== | ================================== | ================================== | ============= | ============= |
| Yes      | series tag     | log_number                         | Log Number                         | text          | text          |
| Yes      | series tag     | institution                        | Institution                        | text          | text          |
| Yes      | series tag     | program                            | Program                            | text          | text          |
| Yes      | series tag     | program_type                       | Program Type                       | text          | text          |
| Yes      | series tag     | project_title                      | Project Title                      | text          | text          |
| Yes      | series tag     | project_type                       | Project Type                       | text          | text          |
| Yes      | time           | award_date                         | Award Date                         | calendar_date | calendar_date |
| No       |                | address                            | Address                            | text          | text          |
| No       |                | address_2                          | Address 2                          | text          | text          |
| No       |                | address_3                          | Address 3                          | text          | text          |
| Yes      | series tag     | city                               | City                               | text          | text          |
| Yes      | series tag     | state                              | State                              | text          | text          |
| Yes      | series tag     | zip_code                           | Zip Code                           | text          | text          |
| Yes      | numeric metric | total_amount_originally_awarded    | Total Amount Originally Awarded    | money         | money         |
| Yes      | numeric metric | total_amount_awarded_and_disbursed | Total Amount Awarded and Disbursed | money         | money         |
| Yes      | numeric metric | applicant_matching_amount          | Applicant Matching Amount          | money         | money         |
| Yes      | numeric metric | requested_award_amount             | Requested Award Amount             | money         | money         |
| Yes      | numeric metric | requested_matching_amount          | Requested Matching Amount          | money         | money         |
| Yes      | series tag     | title_of_principal_investigator    | Title of Principal Investigator    | text          | text          |
| Yes      | series tag     | first_name                         | First Name                         | text          | text          |
| Yes      | series tag     | last_name                          | Last Name                          | text          | text          |
| Yes      | series tag     | organization_type                  | Organization Type                  | text          | text          |
| No       |                | fiscal_year                        | Fiscal Year                        | number        | text          |
| Yes      | series tag     | award_period_from                  | Award Period From                  | text          | text          |
| Yes      | series tag     | award_period_to                    | Award Period To                    | text          | text          |
| Yes      | series tag     | organizational_unit                | Organizational Unit                | text          | text          |
| Yes      | series tag     | county_code                        | County Code                        | text          | text          |
| Yes      | series tag     | census_tract                       | Census Tract                       | text          | text          |
| Yes      | series tag     | census_block                       | Census Block                       | text          | text          |
| Yes      | series tag     | mcd_code                           | MCD Code                           | text          | text          |
| Yes      | series tag     | place_code                         | Place Code                         | text          | text          |
| Yes      | series tag     | cbsa_code                          | CBSA Code                          | text          | text          |
| Yes      | series tag     | msad_code                          | MSAD Code                          | text          | text          |
| Yes      | series tag     | description                        | Description                        | text          | text          |
```

## Time Field

```ls
Value = award_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address,address_2,address_3,fiscal_year
```

## Data Commands

```ls
series e:kf5m-pcwv d:2000-03-30T00:00:00.000Z t:mcd_code=1615 t:place_code=80770 t:program_type=IA t:log_number=IA-00-00-0001-00 t:zip_code=99685-0648 t:state=AK t:organization_type="General museum" t:city=Unalaska t:first_name=Richard t:census_block=2014 t:program="Conservation Assessment Prog." t:last_name=Knecht t:title_of_principal_investigator=Dr. t:census_tract=200 t:county_code=16 t:institution="Museum of the Aleutians" m:requested_matching_amount=0 m:total_amount_originally_awarded=3390 m:requested_award_amount=3390 m:total_amount_awarded_and_disbursed=3390

series e:kf5m-pcwv d:2000-03-30T00:00:00.000Z t:mcd_code=91206 t:place_code=27616 t:program_type=IA t:log_number=IA-00-00-0002-00 t:zip_code=35967 t:state=AL t:organization_type=Museum t:city="Fort Payne" t:first_name=Emma t:census_block=2013 t:program="Conservation Assessment Prog." t:last_name=Jordan t:title_of_principal_investigator=Ms. t:census_tract=961000 t:county_code=49 t:institution="Depot Museum, Inc." m:requested_matching_amount=0 m:total_amount_originally_awarded=6030 m:requested_award_amount=6030 m:total_amount_awarded_and_disbursed=6030

series e:kf5m-pcwv d:2000-03-30T00:00:00.000Z t:first_name=Rita t:program_type=IA t:log_number=IA-00-00-0004-00 t:zip_code=85273-0613 t:program="Conservation Assessment Prog." t:last_name=Wentzel t:state=AZ t:title_of_principal_investigator=Miss t:organization_type=Museum t:institution="Bob Jones Museum" t:city=Superior m:requested_matching_amount=0 m:total_amount_originally_awarded=6350 m:requested_award_amount=6350 m:total_amount_awarded_and_disbursed=6350
```

## Meta Commands

```ls
metric m:total_amount_originally_awarded p:double l:"Total Amount Originally Awarded" t:dataTypeName=money

metric m:total_amount_awarded_and_disbursed p:double l:"Total Amount Awarded and Disbursed" t:dataTypeName=money

metric m:applicant_matching_amount p:double l:"Applicant Matching Amount" t:dataTypeName=money

metric m:requested_award_amount p:double l:"Requested Award Amount" t:dataTypeName=money

metric m:requested_matching_amount p:double l:"Requested Matching Amount" t:dataTypeName=money

entity e:kf5m-pcwv l:"Administrative Discretionary Grants (FY 1996-2014)" t:attribution=IMLS t:url=https://data.imls.gov/api/views/kf5m-pcwv

property e:kf5m-pcwv t:meta.view d:2017-06-09T13:58:11.873Z v:id=kf5m-pcwv v:category="Administrative Data" v:attributionLink=https://www.imls.gov/research-evaluation/data-collection/administrative-discretionary-grant-data v:averageRating=0 v:name="Administrative Discretionary Grants (FY 1996-2014)" v:attribution=IMLS

property e:kf5m-pcwv t:meta.view.license d:2017-06-09T13:58:11.873Z v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:kf5m-pcwv t:meta.view.owner d:2017-06-09T13:58:11.873Z v:id=b4ig-itd5 v:screenName=Ammie v:displayName=Ammie

property e:kf5m-pcwv t:meta.view.tableauthor d:2017-06-09T13:58:11.873Z v:id=b4ig-itd5 v:screenName=Ammie v:displayName=Ammie

property e:kf5m-pcwv t:meta.view.metadata.custom_fields.common_core d:2017-06-09T13:58:11.873Z v:Contact_Email=imlsinfo@imls.gov v:Contact_Name="Office of Digital and Information Strategy" v:Bureau_Code=474:00 v:Program_Code=000:000
```

## Top Records

```ls
| log_number       | institution                          | program                       | program_type | project_title | project_type | award_date          | address         | address_2          | address_3 | city       | state | zip_code   | total_amount_originally_awarded | total_amount_awarded_and_disbursed | applicant_matching_amount | requested_award_amount | requested_matching_amount | title_of_principal_investigator | first_name | last_name | organization_type | fiscal_year | award_period_from | award_period_to | organizational_unit | county_code | census_tract | census_block | mcd_code | place_code | cbsa_code | msad_code | description | 
| ================ | ==================================== | ============================= | ============ | ============= | ============ | =================== | =============== | ================== | ========= | ========== | ===== | ========== | =============================== | ================================== | ========================= | ====================== | ========================= | =============================== | ========== | ========= | ================= | =========== | ================= | =============== | =================== | =========== | ============ | ============ | ======== | ========== | ========= | ========= | =========== | 
| IA-00-00-0001-00 | Museum of the Aleutians              | Conservation Assessment Prog. | IA           |               |              | 2000-03-30T00:00:00 | P.O. Box 648    |                    |           | Unalaska   | AK    | 99685-0648 | 3390.00                         | 3390.00                            |                           | 3390.00                | 0.00                      | Dr.                             | Richard    | Knecht    | General museum    | 2000        |                   |                 |                     | 16          | 200          | 2014         | 1615     | 80770      |           |           |             | 
| IA-00-00-0002-00 | Depot Museum, Inc.                   | Conservation Assessment Prog. | IA           |               |              | 2000-03-30T00:00:00 | P.O. Box 681420 |                    |           | Fort Payne | AL    | 35967      | 6030.00                         | 6030.00                            |                           | 6030.00                | 0.00                      | Ms.                             | Emma       | Jordan    | Museum            | 2000        |                   |                 |                     | 49          | 961000       | 2013         | 91206    | 27616      |           |           |             | 
| IA-00-00-0004-00 | Bob Jones Museum                     | Conservation Assessment Prog. | IA           |               |              | 2000-03-30T00:00:00 | P.O. Box 613    |                    |           | Superior   | AZ    | 85273-0613 | 6350.00                         | 6350.00                            |                           | 6350.00                | 0.00                      | Miss                            | Rita       | Wentzel   | Museum            | 2000        |                   |                 |                     |             |              |              |          |            |           |           |             | 
| IA-00-00-0008-00 | Coachella Valley Historical Society  | Conservation Assessment Prog. | IA           |               |              | 2000-03-30T00:00:00 | P.O. Box 595    |                    |           | Indio      | CA    | 92201      | 6350.00                         | 6350.00                            |                           | 6350.00                | 0.00                      | Mr.                             | Arthur     | LaLonde   | Museum            | 2000        |                   |                 |                     | 65          | 45207        | 1000         | 90520    | 36448      | 40140     |           |             | 
| IA-00-00-0009-00 | Los Gatos Museum                     | Conservation Assessment Prog. | IA           |               |              | 2000-03-30T00:00:00 | P.O. Box 1904   |                    |           | Los Gatos  | CA    | 95031      | 6190.00                         | 6190.00                            |                           | 6190.00                | 0.00                      | Ms.                             | Laura      | Bajuk     | Museum            | 2000        |                   |                 |                     | 85          | 507001       | 2059         | 92830    | 44112      | 41940     |           |             | 
| IA-00-00-0010-00 | Gold Nugget Museum                   | Conservation Assessment Prog. | IA           |               |              | 2000-03-30T00:00:00 | P.O. Box 949    |                    |           | Paradise   | CA    | 95967      | 3480.00                         | 3480.00                            |                           | 3480.00                | 0.00                      | Miss                            | Frances    | Mantonya  | Museum            | 2000        |                   |                 |                     | 7           | 1900         | 3002         | 92380    | 55520      | 17020     |           |             | 
| IA-00-00-0011-00 | Kimberly Crest House and Gardens     | Conservation Assessment Prog. | IA           |               |              | 2000-03-30T00:00:00 | P.O. Box 206    |                    |           | Redlands   | CA    | 92373      | 6030.00                         | 6030.00                            |                           | 6030.00                | 0.00                      | Mr.                             | Steven     | Spiller   | Museum            | 2000        |                   |                 |                     | 71          | 8301         | 2011         | 92770    | 59962      | 40140     |           |             | 
| IA-00-00-0013-00 | Los Angeles Maritime Museum          | Conservation Assessment Prog. | IA           |               |              | 2000-03-30T00:00:00 | Berth 84        | Foot of 6th Street |           | San Pedro  | CA    | 90731      | 5870.00                         | 5870.00                            |                           | 5870.00                | 0.00                      | Professor                       | William    | Lee       | Museum            | 2000        |                   |                 |                     | 37          | 296902       | 1007         | 91750    | 44000      | 31080     | 31084     |             | 
| IA-00-00-0015-00 | Santa Ynez Valley Historical Society | Conservation Assessment Prog. | IA           |               |              | 2000-03-30T00:00:00 | P.O. Box 181    |                    |           | Santa Ynez | CA    | 93460      | 6030.00                         | 6030.00                            |                           | 6030.00                | 0.00                      | Ms.                             | Debra      | Argel     | Museum            | 2000        |                   |                 |                     | 83          | 1905         | 3041         | 93065    |            | 42200     |           |             | 
| IA-00-00-0019-00 | Guilford Keeping Society             | Conservation Assessment Prog. | IA           |               |              | 2000-03-30T00:00:00 | P.O. Box 363    |                    |           | Guilford   | CT    | 06437      | 6190.00                         | 6190.00                            |                           | 6190.00                | 0.00                      | Miss                            | Sandra     | Rux       | Museum            | 2000        |                   |                 |                     | 9           | 190301       | 2004         | 34950    |            | 35300     |           |             | 
```