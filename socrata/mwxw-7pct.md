# 2013 Proposed Budget - Expenditure Allowance by Budget Control Level (BCL)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2013-proposed-budget-expenditure-allowance-by-budget-control-level-bcl-e9716) |
| Metadata | [Link](https://data.seattle.gov/api/views/mwxw-7pct) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/mwxw-7pct/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/mwxw-7pct/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | mwxw-7pct |
| Name | 2013 Proposed Budget - Expenditure Allowance by Budget Control Level (BCL) |
| Attribution | City Budget Office - Brandon Johns |
| Category | Finance |
| Tags | 2013 proposed budget |
| Created | 2012-09-25T17:15:44Z |
| Publication Date | 2012-09-25T17:17:42Z |

## Description

September 24, 2012

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                       | Data Type | Render Type |
| ======== | ============== | ===================== | ========================== | ========= | =========== |
| Yes      | series tag     | fund                  | Fund                       | text      | text        |
| Yes      | series tag     | department            | Department                 | text      | text        |
| Yes      | series tag     | bcl_code              | BCL Code                   | text      | text        |
| Yes      | series tag     | bcl_name              | BCL Name                   | text      | text        |
| Yes      | series tag     | bcl_purpose           | BCL Purpose                | text      | text        |
| Yes      | numeric metric | expenditure_allowance | 2013 Expenditure Allowance | number    | number      |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:mwxw-7pct d:2013-01-01T00:00:00.000Z t:bcl_code=2QA00 t:bcl_purpose="The purpose of the Appropriation to General Fund Subfunds and Special Funds Budget Control Level is to appropriate General Subfund resources, several of which are based upon the performance of certain City revenues, to bond redemption or special purpose funds.  These appropriations are implemented as operating transfers to the funds, subfunds, or accounts they support." t:department="Finance General" t:fund="General Subfund" t:bcl_name="Appropriation to General Fund Subfunds and Special Funds" m:expenditure_allowance=57706023

series e:mwxw-7pct d:2013-01-01T00:00:00.000Z t:bcl_code=2QD00 t:bcl_purpose="The purpose of the Reserves Budget Control Level is to provide appropriation authority to those programs for which there is no single appropriate managing department, or for which there is Council and/or Mayor desire for additional budget oversight." t:department="Finance General" t:fund="General Subfund" t:bcl_name=Reserves m:expenditure_allowance=36818259

series e:mwxw-7pct d:2013-01-01T00:00:00.000Z t:bcl_code=2QE00 t:bcl_purpose="The purpose of the Support to Operating Funds Budget Control Level is to appropriate General Subfund resources to support the operating costs of line departments that have their own operating funds.  These appropriations are implemented as operating transfers to the funds or subfunds they support." t:department="Finance General" t:fund="General Subfund" t:bcl_name="Support to Operating Funds" m:expenditure_allowance=293281640
```

## Meta Commands

```ls
metric m:expenditure_allowance p:integer l:"2013 Expenditure Allowance" t:dataTypeName=number

entity e:mwxw-7pct l:"2013 Proposed Budget - Expenditure Allowance by Budget Control Level (BCL)" t:attribution="City Budget Office - Brandon Johns" t:url=https://data.seattle.gov/api/views/mwxw-7pct

property e:mwxw-7pct t:meta.view v:id=mwxw-7pct v:category=Finance v:averageRating=0 v:name="2013 Proposed Budget - Expenditure Allowance by Budget Control Level (BCL)" v:attribution="City Budget Office - Brandon Johns"

property e:mwxw-7pct t:meta.view.owner v:id=tdaq-haqd v:screenName="Brandon Johns" v:displayName="Brandon Johns"

property e:mwxw-7pct t:meta.view.tableauthor v:id=tdaq-haqd v:screenName="Brandon Johns" v:roleName=publisher v:displayName="Brandon Johns"
```

## Top Records

```ls
| fund                         | department               | bcl_code | bcl_name                                                 | bcl_purpose                                                                                                                                                                                                                                                                                                                                                                        | expenditure_allowance | 
| ============================ | ======================== | ======== | ======================================================== | ================================================================================================================================================================================================================================================================================================================================================================================== | ===================== | 
| General Subfund              | Finance General          | 2QA00    | Appropriation to General Fund Subfunds and Special Funds | The purpose of the Appropriation to General Fund Subfunds and Special Funds Budget Control Level is to appropriate General Subfund resources, several of which are based upon the performance of certain City revenues, to bond redemption or special purpose funds. These appropriations are implemented as operating transfers to the funds, subfunds, or accounts they support. | 57706023              | 
| General Subfund              | Finance General          | 2QD00    | Reserves                                                 | The purpose of the Reserves Budget Control Level is to provide appropriation authority to those programs for which there is no single appropriate managing department, or for which there is Council and/or Mayor desire for additional budget oversight.                                                                                                                          | 36818259              | 
| General Subfund              | Finance General          | 2QE00    | Support to Operating Funds                               | The purpose of the Support to Operating Funds Budget Control Level is to appropriate General Subfund resources to support the operating costs of line departments that have their own operating funds. These appropriations are implemented as operating transfers to the funds or subfunds they support.                                                                          | 293281640             | 
| General Subfund              | Executive                | CZ000    | City Budget Office                                       | The purpose of the City Budget Office Budget Control Level is to develop and monitor the budget, carrying out budget-related functions, oversee financial policies and plans, and provide financial and other strategic analysis.                                                                                                                                                  | 4085671               | 
| Drainage and Wastewater Fund | Seattle Public Utilities | N100B-DW | Administration                                           | The purpose of the Drainage and Wastewater Utility Administration Budget Control Level is to provide overall management and policy direction for Seattle Public Utilities and, more specifically, for the Drainage and Wastewater Utility, and to provide core financial, human resource, and information technology services.                                                     | 5135857               | 
| General Subfund              | Seattle Fire Department  | F1000    | Administration                                           | The purpose of the Administration Budget Control Level is to provide management information and to allocate and manage available resources needed to achieve the Department?s mission.                                                                                                                                                                                             | 7369739               | 
| General Subfund              | Law Department           | J1100    | Administration                                           | The purpose of the Administration Budget Control Level is to provide the financial, technological, administrative and managerial support for the Department.                                                                                                                                                                                                                       | 1893005               | 
| Solid Waste Fund             | Seattle Public Utilities | N100B-SW | Administration                                           | The purpose of the Solid Waste Utility Administration Budget Control Level is to provide overall management and policy direction for Seattle Public Utilities, and, more specifically, for the Solid Waste Utility, and to provide core financial, human resource, and information technology services.                                                                            | 4536121               | 
| Water Fund                   | Seattle Public Utilities | N100B-WU | Administration                                           | The purpose of the Water Utility Administration Budget Control Level is to provide overall management and policy direction for Seattle Public Utilities, and, more specifically, for the Water Utility, and to provide core financial, human resource, and information technology services.                                                                                        | 9563508               | 
| General Subfund              | Seattle Fire Department  | F2000    | Resource Management                                      | The purpose of the Resource Management Budget Control Level (formerly known as Risk Management) is to recruit and train uniformed staff, reduce injuries by identifying and changing practices that place firefighters at greater risk, provide services to enhance firefighter health and wellness, and provide communication services and logistical support.                    | 10901977              | 
```