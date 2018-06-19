# Content Config

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/content-config-950a8) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/6yf4-3awu) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/6yf4-3awu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/6yf4-3awu/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | 6yf4-3awu |
| Name | Content Config |
| Tags | content, config |
| Created | 2014-09-17T18:13:30Z |
| Publication Date | 2016-03-16T18:13:06Z |

## Description

Dataset created for budgetMontgomery

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | homepage    | Homepage   | text      | text        |
| Yes      | series tag  | about_page  | About Page | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:6yf4-3awu d:2014-09-17T11:13:32.000Z t:about_page="* Interactive charts, tables, maps and video
 * A Search Engine
 * Translatable into 90+ languages
 * Archiving Previous Years Data / Content
 * Sharing of datasets / tables and visualizations across departments and the public
 * Mobility (works on Smartphones, tablets and desktops)
 * American with Disabilities Act (ADA) Compliance" m:row_number.6yf4-3awu=1

series e:6yf4-3awu d:2014-09-17T11:13:32.000Z t:about_page="The Online Budget Publication is located at reports.data.montgomerycountymd.gov/omb

For questions about budgetMontgomery or the Online Publication, please contact our 311 Customer Service Center at 240-777-0311 (7AM ? 7PM | Monday-Wednesday) or visit the 311 Self Services Portal at mc311.com.

See budgetMontgomery Navigation Tutorial Below:" m:row_number.6yf4-3awu=2

series e:6yf4-3awu d:2014-09-17T11:13:32.000Z t:about_page="Click here to view budgetMontgomery Navigation Tutorial" m:row_number.6yf4-3awu=3
```

## Meta Commands

```ls
metric m:row_number.6yf4-3awu p:long l:"Row Number"

entity e:6yf4-3awu l:"Content Config" t:url=https://data.montgomerycountymd.gov/api/views/6yf4-3awu

property e:6yf4-3awu t:meta.view v:id=6yf4-3awu v:averageRating=0 v:name="Content Config"

property e:6yf4-3awu t:meta.view.owner v:id=qzhb-tftn v:screenName="Kathy Luh" v:displayName="Kathy Luh"

property e:6yf4-3awu t:meta.view.tableauthor v:id=qzhb-tftn v:screenName="Kathy Luh" v:roleName=administrator v:displayName="Kathy Luh"
```

## Top Records

```ls
| :updated_at | homepage                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | about_page                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | 
| =========== | ======================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================= | ==================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================== | 
| 1410952412  |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | * Interactive charts, tables, maps and video * A Search Engine * Translatable into 90+ languages * Archiving Previous Years Data / Content * Sharing of datasets / tables and visualizations across departments and the public * Mobility (works on Smartphones, tablets and desktops) * American with Disabilities Act (ADA) Compliance                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | 
| 1410952412  |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | The Online Budget Publication is located at reports.data.montgomerycountymd.gov/omb For questions about budgetMontgomery or the Online Publication, please contact our 311 Customer Service Center at 240-777-0311 (7AM ? 7PM | Monday-Wednesday) or visit the 311 Self Services Portal at mc311.com. See budgetMontgomery Navigation Tutorial Below:                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 
| 1410952412  |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | Click here to view budgetMontgomery Navigation Tutorial                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | 
| 1458126760  | In 2012, Montgomery County launched dataMontgomery as part of its openMontgomery initiative, a program designed to promote greater transparency and accessibility to residents. Our next step was to provide a guided view to complex financial information, such as budget data. This site, budgetMontgomery, will provide you with a way to understand how our budget is structured and get the answers you need. It has rich content to view our budget from different levels, such as how much we budget for services, Departments, programs and capital improvement programs. You also have the ability to convert graphs to table views and download data.
Simply click on a bar chart to drill down for further information, or click on one of the map bubbles to view project details from the Capital Budget. | Please note that the operating budget data is only for Montgomery County Government; it does not contain other agencies? budgets. Also, budgetMontgomery compares the County Council Approved budget and the County Executive Recommended budget (Operating). For the capital budget data, it includes all agencies (Montgomery County Government, Montgomery County Public Schools, Montgomery College, Maryland-National Capital Park and Planning Commission, Revenue Authority, and the Housing Opportunities Commission). It only contains the County Council Approved budget and project statuses for Department of General Services and Department of Transportation administered projects. In additional to budgetMontgomery, the Office of Management and Budget (OMB) is producing an Online Publication of the Operating Budget leveraging Montgomery County?s Open Data platform. No longer bound by the limitations of a paper-based publication, this new online publication will bring a dramatically improved experience for our readers, including: | 
```