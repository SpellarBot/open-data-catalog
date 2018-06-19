# Commerce Contracts

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/commerce-contracts) |
| Metadata | [Link](https://data.wa.gov/api/views/txep-7uqx) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/txep-7uqx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/txep-7uqx/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | txep-7uqx |
| Name | Commerce Contracts |
| Attribution | WA State Department of Commerce |
| Category | Procurements and Contracts |
| Tags | commerce, contracts, grants |
| Created | 2016-01-20T19:15:32Z |
| Publication Date | 2016-01-20T19:22:45Z |

## Description

Contracts between WA State Department of Commerce and all other entities. Includes public and private sector entities

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type     | Render Type   |
| ======== | ============== | ==================== | ==================== | ============= | ============= |
| Yes      | time           | start_date           | Start Date           | calendar_date | calendar_date |
| No       |                | end_date             | End Date             | calendar_date | calendar_date |
| Yes      | series tag     | division             | Division             | text          | text          |
| Yes      | series tag     | unit                 | Unit                 | text          | text          |
| Yes      | series tag     | contract             | Contract #           | text          | text          |
| Yes      | series tag     | project_name         | Project Name         | text          | text          |
| Yes      | series tag     | com_vendor_name      | COM Vendor Name      | text          | text          |
| Yes      | series tag     | vendor_type          | Vendor Type          | text          | text          |
| Yes      | series tag     | status               | Status               | text          | text          |
| Yes      | series tag     | contract_type        | Contract Type        | text          | text          |
| Yes      | numeric metric | contract_total       | Contract Total $     | money         | money         |
| No       |                | expenditures_to_date | Expenditures to Date | text          | money         |
| Yes      | series tag     | county               | County               | text          | text          |
| Yes      | series tag     | jurisdiction_1       | Jurisdiction         | text          | text          |
| Yes      | numeric metric | jurisdiction_2       | Jurisdiction %       | percent       | percent       |
```

## Time Field

```ls
Value = start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = end_date,expenditures_to_date
```

## Data Commands

```ls
series e:txep-7uqx d:2010-01-01T00:00:00.000Z t:unit="Administrative Services" t:division=ASD t:project_name="Governor's Special Advisor" t:contract_type="Interagency (Governmental) - Payable" t:contract="10-11100-200 K709" t:status=Closed t:com_vendor_name="OFM Governors Off Acct Unit" t:jurisdiction_1="WA-State of" t:vendor_type="WA State Agency" m:jurisdiction_2=10 m:contract_total=145000

series e:txep-7uqx d:2010-01-01T00:00:00.000Z t:unit="Administrative Services" t:division=ASD t:project_name="Governor's Special Advisor" t:contract_type="Interagency (Governmental) - Payable" t:contract="10-11100-200 K709" t:status=Closed t:com_vendor_name="OFM Governors Off Acct Unit" t:jurisdiction_1="WA-State of" t:vendor_type="WA State Agency" m:jurisdiction_2=90 m:contract_total=145000

series e:txep-7uqx d:2010-01-01T00:00:00.000Z t:unit="Community Economic Opportunities" t:division=CSHD t:project_name="Community Services Block Grant" t:contract_type=Grant t:county=King t:contract=F10-32100-017 t:status=Closed t:com_vendor_name="Multi Service Center" t:jurisdiction_1="King-County of" t:vendor_type=CAAs m:jurisdiction_2=100 m:contract_total=679088
```

## Meta Commands

```ls
metric m:contract_total p:double l:"Contract Total $" t:dataTypeName=money

metric m:jurisdiction_2 p:integer l:"Jurisdiction %" t:dataTypeName=percent

entity e:txep-7uqx l:"Commerce Contracts" t:attribution="WA State Department of Commerce" t:url=https://data.wa.gov/api/views/txep-7uqx

property e:txep-7uqx t:meta.view v:id=txep-7uqx v:category="Procurements and Contracts" v:attributionLink=http://commerce.wa.gov v:averageRating=0 v:name="Commerce Contracts" v:attribution="WA State Department of Commerce"

property e:txep-7uqx t:meta.view.license v:name="Public Domain"

property e:txep-7uqx t:meta.view.owner v:id=h2ue-vnnt v:profileImageUrlMedium=/api/users/h2ue-vnnt/profile_images/THUMB v:profileImageUrlLarge=/api/users/h2ue-vnnt/profile_images/LARGE v:screenName="OCIO-Will Saunders" v:profileImageUrlSmall=/api/users/h2ue-vnnt/profile_images/TINY v:displayName="OCIO-Will Saunders"

property e:txep-7uqx t:meta.view.tableauthor v:id=h2ue-vnnt v:profileImageUrlMedium=/api/users/h2ue-vnnt/profile_images/THUMB v:profileImageUrlLarge=/api/users/h2ue-vnnt/profile_images/LARGE v:screenName="OCIO-Will Saunders" v:profileImageUrlSmall=/api/users/h2ue-vnnt/profile_images/TINY v:roleName=publisher v:displayName="OCIO-Will Saunders"
```

## Top Records

```ls
| start_date          | end_date            | division | unit                             | contract          | project_name                   | com_vendor_name                                | vendor_type      | status | contract_type                        | contract_total | expenditures_to_date | county    | jurisdiction_1      | jurisdiction_2 | 
| =================== | =================== | ======== | ================================ | ================= | ============================== | ============================================== | ================ | ====== | ==================================== | ============== | ==================== | ========= | =================== | ============== | 
| 2010-01-01T00:00:00 | 2011-09-30T00:00:00 | ASD      | Administrative Services          | 10-11100-200 K709 | Governor's Special Advisor     | OFM Governors Off Acct Unit                    | WA State Agency  | Closed | Interagency (Governmental) - Payable | 145000.00      | 141133.40            |           | WA-State of         | 10             | 
| 2010-01-01T00:00:00 | 2011-09-30T00:00:00 | ASD      | Administrative Services          | 10-11100-200 K709 | Governor's Special Advisor     | OFM Governors Off Acct Unit                    | WA State Agency  | Closed | Interagency (Governmental) - Payable | 145000.00      | 141133.40            |           | WA-State of         | 90             | 
| 2010-01-01T00:00:00 | 2011-09-30T00:00:00 | CSHD     | Community Economic Opportunities | F10-32100-017     | Community Services Block Grant | Multi Service Center                           | CAAs             | Closed | Grant                                | 679088.00      | 679088.00            | King      | King-County of      | 100            | 
| 2010-01-01T00:00:00 | 2011-09-30T00:00:00 | CSHD     | Community Economic Opportunities | F10-32100-004     | Community Services Block Grant | Chelan-Douglas Community Action Council        | Non-Profit       | Closed | Grant                                | 240233.00      | 240233.00            | Chelan    | Chelan-County of    | 50             | 
| 2010-01-01T00:00:00 | 2011-09-30T00:00:00 | CSHD     | Community Economic Opportunities | F10-32100-004     | Community Services Block Grant | Chelan-Douglas Community Action Council        | Non-Profit       | Closed | Grant                                | 240233.00      | 240233.00            | Douglas   | Douglas-County of   | 50             | 
| 2010-01-01T00:00:00 | 2011-09-30T00:00:00 | CSHD     | Community Economic Opportunities | F10-32100-024     | Community Services Block Grant | Pierce County Department of Community Services | Local Government | Closed | Grant                                | 532996.00      | 532996.00            | Pierce    | Pierce-County of    | 100            | 
| 2010-01-01T00:00:00 | 2011-09-30T00:00:00 | CSHD     | Community Economic Opportunities | F10-32100-018     | Community Services Block Grant | Neighborhood House Inc                         | CAAs             | Closed | Grant                                | 211392.00      | 211392.00            | King      | King-County of      | 100            | 
| 2010-01-01T00:00:00 | 2011-09-30T00:00:00 | CSHD     | Community Economic Opportunities | F10-32100-029     | Community Services Block Grant | Spokane Neighborhood Action Partners           | CAAs             | Closed | Grant                                | 633531.00      | 633531.00            | Spokane   | Spokane-County of   | 100            | 
| 2010-01-01T00:00:00 | 2011-09-30T00:00:00 | CSHD     | Community Economic Opportunities | F10-32100-021     | Community Services Block Grant | Olympic Community Action Programs              | CAAs             | Closed | Grant                                | 77228.00       | 77228.00             | Clallam   | Clallam-County of   | 50             | 
| 2010-01-01T00:00:00 | 2011-09-30T00:00:00 | CSHD     | Community Economic Opportunities | F10-32100-021     | Community Services Block Grant | Olympic Community Action Programs              | CAAs             | Closed | Grant                                | 77228.00       | 77228.00             | Jefferson | Jefferson-County of | 50             | 
```