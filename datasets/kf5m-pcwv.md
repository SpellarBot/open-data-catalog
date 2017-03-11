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
| Rows Updated | 2015-08-20T21:58:19Z |

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
| Yes      | series tag     | address_2                          | Address 2                          | text          | text          |
| Yes      | series tag     | address_3                          | Address 3                          | text          | text          |
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
| Yes      | numeric metric | census_tract                       | Census Tract                       | number        | text          |
| Yes      | numeric metric | census_block                       | Census Block                       | number        | text          |
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
Excluded Fields = fiscal_year,address
```

## Data Commands

```ls
series e:kf5m-pcwv d:2000-03-30T00:00:00.000Z t:mcd_code=1615 t:place_code=80770 t:program_type=IA t:log_number=IA-00-00-0001-00 t:zip_code=99685-0648 t:state=AK t:organization_type="General museum" t:city=Unalaska t:first_name=Richard t:program="Conservation Assessment Prog." t:last_name=Knecht t:title_of_principal_investigator=Dr. t:county_code=16 t:institution="Museum of the Aleutians" m:requested_matching_amount=0 m:requested_award_amount=3390 m:total_amount_originally_awarded=3390 m:census_block=2014 m:total_amount_awarded_and_disbursed=3390 m:census_tract=200

series e:kf5m-pcwv d:2000-03-30T00:00:00.000Z t:mcd_code=91206 t:place_code=27616 t:program_type=IA t:log_number=IA-00-00-0002-00 t:zip_code=35967 t:state=AL t:organization_type=Museum t:city="Fort Payne" t:first_name=Emma t:program="Conservation Assessment Prog." t:last_name=Jordan t:title_of_principal_investigator=Ms. t:county_code=49 t:institution="Depot Museum, Inc." m:requested_matching_amount=0 m:requested_award_amount=6030 m:total_amount_originally_awarded=6030 m:census_block=2013 m:total_amount_awarded_and_disbursed=6030 m:census_tract=961000

series e:kf5m-pcwv d:2000-03-30T00:00:00.000Z t:first_name=Rita t:program_type=IA t:log_number=IA-00-00-0004-00 t:zip_code=85273-0613 t:program="Conservation Assessment Prog." t:last_name=Wentzel t:state=AZ t:title_of_principal_investigator=Miss t:organization_type=Museum t:institution="Bob Jones Museum" t:city=Superior m:requested_matching_amount=0 m:requested_award_amount=6350 m:total_amount_originally_awarded=6350 m:total_amount_awarded_and_disbursed=6350
```

## Meta Commands

```ls
metric m:census_tract p:integer l:"Census Tract" t:dataTypeName=number

metric m:census_block p:integer l:"Census Block" t:dataTypeName=number

entity e:kf5m-pcwv l:"Administrative Discretionary Grants (FY 1996-2014)" t:attribution=IMLS t:url=https://data.imls.gov/api/views/kf5m-pcwv

property e:kf5m-pcwv t:meta.view v:id=kf5m-pcwv v:category="Administrative Data" v:attributionLink=https://www.imls.gov/research-evaluation/data-collection/administrative-discretionary-grant-data v:averageRating=0 v:name="Administrative Discretionary Grants (FY 1996-2014)" v:attribution=IMLS

property e:kf5m-pcwv t:meta.view.license v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:kf5m-pcwv t:meta.view.owner v:id=b4ig-itd5 v:screenName=Ammie v:displayName=Ammie

property e:kf5m-pcwv t:meta.view.tableauthor v:id=b4ig-itd5 v:screenName=Ammie v:displayName=Ammie

property e:kf5m-pcwv t:meta.view.metadata.custom_fields.common_core v:Contact_Email=imlsinfo@imls.gov v:Contact_Name="Office of Digital and Information Strategy" v:Bureau_Code=474:00 v:Program_Code=000:000
```