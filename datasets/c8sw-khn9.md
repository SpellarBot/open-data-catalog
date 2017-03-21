# County Lottery Fund Expenditures: 2015-2016 Composite

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/county-lottery-fund-expenditures-2016-2015-composite) |
| Metadata | [Link](https://data.oregon.gov/api/views/c8sw-khn9) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/c8sw-khn9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/c8sw-khn9/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | c8sw-khn9 |
| Name | County Lottery Fund Expenditures: 2015-2016 Composite |
| Category | Revenue & Expense |
| Tags | county lottery expenditure reporting; hb 3188 (2011); lottery expenditures; expenditures; 2015; 2016 |
| Created | 2016-11-20T02:32:25Z |
| Publication Date | 2016-11-20T02:38:05Z |
| Rows Updated | 2016-11-20T02:32:32Z |

## Description

Oregon County Expenditures of State Lottery Funds Reporting: Data Required under House Bill 3188 (2011) https://www.oregonlegislature.gov/bills_laws/lawsstatutes/2011orLaw0385.html. The Oregon Legislature passed House Bill 3188 during the 2011 Legislative Session. The Bill requires the 36 Oregon Counties to report on a variety of expenditure information, related to the use of Lottery Funds for the purposes of economic development. For more information, see the Oregon Transparency Website. http://www.oregon.gov/transparency/Pages/expenditures.aspx
For additional questions regarding this information, please contact Lara Cleland (lcleland@aocweb.org) Association of Oregon Counties.

## Columns

```ls
| Included | Schema Type    | Field Name                                              | Name                                                      | Data Type     | Render Type   |
| ======== | ============== | ======================================================= | ========================================================= | ============= | ============= |
| No       |                | year_reported                                           | Year Reported                                             | number        | number        |
| Yes      | series tag     | county                                                  | County                                                    | text          | text          |
| Yes      | time           | report_period_end_date                                  | Report Period End Date                                    | calendar_date | calendar_date |
| Yes      | numeric metric | amount_of_money_received                                | Amount of Money Received ($)                              | money         | money         |
| Yes      | numeric metric | amount_of_money_expended                                | Amount of Money Expended ($)                              | money         | money         |
| Yes      | numeric metric | amount_of_money_expended_on_administration              | Amount of Money Expended on Administration ($)            | money         | money         |
| Yes      | series tag     | purpose_and_use_of_moneys_narrative                     | Purpose and Use of Moneys (Narrative)                     | text          | text          |
| Yes      | series tag     | work_and_services_provided_by_employed_person_narrative | Work and Services Provided by Employed Person (Narrative) | text          | text          |
```

## Time Field

```ls
Value = report_period_end_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = year_reported
```

## Data Commands

```ls
series e:c8sw-khn9 d:2016-06-30T00:00:00.000Z t:county=Baker t:purpose_and_use_of_moneys_narrative="All of the Lottery funds Baker County received were spent on Economic Development expenses." m:amount_of_money_expended_on_administration=0 m:amount_of_money_received=108718 m:amount_of_money_expended=108718

series e:c8sw-khn9 d:2016-06-30T00:00:00.000Z t:county=Benton t:purpose_and_use_of_moneys_narrative="$105,000 to Corvallis-Benton County Economic Development Office to provide services marketing for business development. $20,000 to support the efforts of the Regional Accelerator and Innovation Network (RAIN). $15,000 to support expenses of re-establishing Da Vinci Days, a local series of activities and events promoting Science, Technology, Engineering, Acts and Mathematics." t:work_and_services_provided_by_employed_person_narrative=N/A m:amount_of_money_expended_on_administration=792 m:amount_of_money_received=212515 m:amount_of_money_expended=140792

series e:c8sw-khn9 d:2016-06-30T00:00:00.000Z t:county=Clackamas t:purpose_and_use_of_moneys_narrative="Willamette Falls Legacy Project (WFLP):  Provided financial and staff support for multi-agency efforts towards redevelopment of the Willamette Falls Legacy site, and provided local match required for state funding contribution.; North Milwaukie Industrial Area (NMIA):  Led a multi-agency initiative to study redevelopment opportunities in NMIA, providing match funding for Metro grant.; Business Retention, Recruitment, and Expansion: Assisted businesses, property owners and local jurisdictions with outreach to existing businesses to retain jobs, respond to state, regional, and local leads for business recruitment and assisting business and property owners with expansion of existing facilities.; Clackamas County Community Economic Preparedness (CEP): Provided assistance to communities with business retention, expansion and new business prospect inquiries. ; Employment Lands: Continued Employment Lands Assessment which included inventory tracking, economic analysis and an infrastructure needs assessment for available employment lands. Maintained updates to the ‘Site Search’ online mapping tool, ensuring that the list of available properties and buildings in Clackamas County is current.; Clackamas County Economic Landscape Project: Provided updates to Clackamas County’s 11 key clusters which included tracking economic trends and emerging industries. ; Clackamas County Industry Cluster Development: Using the work of the Economic Landscape Project, staff focused on a variety of programs to expand business opportunities, job growth, and increase GDP.; Clackamas County Export Initiative: Hosted the 5th annual Export Summit for businesses and leaders in the region. ; Clackamas County Software and Media Production: Continued working with production companies to assist with permitting and locations for film, television, and commercial producers for projects. ; Regional Partnerships: Hosted and attended meetings to further economic development throughout the region with Oregon Economic Development Association, Greater Portland Inc., etc. ; Clackamas County Food System ONEStop: Designed a concept for a virtual public, private and non-profit partnership through which local growers and producers can access the technical and financial resources they need to be successful. Secured a USDA Specialty Crop Grant to take the design concept and build the virtual ONEStop platform and website. ; Pacific Northwest Manufacturing Partnership (PNMP): Developed a detailed supply chain analysis to identify gaps and opportunities for Clackamas County as a part of PNMP’s catalytic project related to the commercialization of cross laminated timber (CLT) in the Northwest. CLT and associated advanced wood products manufacturing technologies combine the region’s traditional competitive advantage in softwood timber supply from Oregon forests with advanced material science to help create/retain high wage jobs. ; Project PRIDE: Workforce development staff worked closely with County businesses assisting them to meet recruitment, hiring, placement, training and retention goals which reduced expensive employee turnover costs." t:work_and_services_provided_by_employed_person_narrative="The Economic Development Administrative Staff consisted of the Director of Business & Community Services, the Deputy Director of Business & Community Services and Financial Analyst.  This group managed all financial aspects of the program including budget and audit requirements, to ensure compliance with Oregon revised statutes and other regulations. The Business and Economic Development Team consisted of an Economic Development Manager, a portion of the Agriculture and Forest Economic Development Manager, two Economic Development Coordinators, and one Administrative Assistant.  This group managed the day to day operations of the economic development program." m:amount_of_money_expended_on_administration=184481 m:amount_of_money_received=1823050 m:amount_of_money_expended=1536667.4
```

## Meta Commands

```ls
metric m:amount_of_money_received p:double l:"Amount of Money Received ($)" t:dataTypeName=money

metric m:amount_of_money_expended p:double l:"Amount of Money Expended ($)" t:dataTypeName=money

metric m:amount_of_money_expended_on_administration p:double l:"Amount of Money Expended on Administration ($)" t:dataTypeName=money

entity e:c8sw-khn9 l:"County Lottery Fund Expenditures: 2015-2016 Composite" t:url=https://data.oregon.gov/api/views/c8sw-khn9

property e:c8sw-khn9 t:meta.view v:id=c8sw-khn9 v:category="Revenue & Expense" v:averageRating=0 v:name="County Lottery Fund Expenditures: 2015-2016 Composite"

property e:c8sw-khn9 t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:displayName="Paula N."

property e:c8sw-khn9 t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:displayName="Paula N."
```