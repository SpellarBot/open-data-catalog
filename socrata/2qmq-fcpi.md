# Incrementalchanges

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/incrementalchanges-b5c91) |
| Metadata | [Link](https://data.seattle.gov/api/views/2qmq-fcpi) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/2qmq-fcpi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/2qmq-fcpi/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | 2qmq-fcpi |
| Name | Incrementalchanges |
| Category | Finance |
| Created | 2013-09-17T16:35:00Z |
| Publication Date | 2013-10-08T19:49:12Z |

## Description

Incremental changes

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| No       | time           | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | series tag     | inc_change_id    | Inc Change ID    | text      | number      |
| Yes      | series tag     | dept_code        | Dept Code        | text      | text        |
| Yes      | series tag     | report_section   | Report Section   | text      | text        |
| Yes      | series tag     | icchange_name    | ICChange Name    | text      | text        |
| Yes      | series tag     | inc_change_descr | Inc Change Descr | text      | text        |
| Yes      | numeric metric | sum_of_amount    | Sum Of Amount    | number    | number      |
| Yes      | numeric metric | sum_of_fte       | Sum Of FTE       | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:2qmq-fcpi d:2013-10-08T12:22:41.000Z t:report_section="Total 2014 Endorsed Budget" t:dept_code=12LIBLEVY m:sum_of_amount=12658704

series e:2qmq-fcpi d:2013-10-08T12:22:41.000Z t:report_section="Total 2014 Endorsed Budget" t:dept_code=ARTS m:sum_of_fte=28.09 m:sum_of_amount=7243761

series e:2qmq-fcpi d:2013-10-08T12:22:41.000Z t:report_section="Proposed Changes" t:inc_change_id=946 t:icchange_name="Increase Funding for Arts Education" t:dept_code=ARTS t:inc_change_descr="Currently, access to arts education in Seattle Public Schools varies widely from school to school. In order to improve access to arts education, this funding will: 
<p>
<ul>
<li>Help implement the Seattle Public Schools K-12 Arts Plan ($40,000);
<li>Track the changes that are implemented and measure their impacts on student performance and behavior ($20,000); and
<li>Create a position to link community arts organizations with schools ($90,000)." m:sum_of_fte=1 m:sum_of_amount=149571
```

## Meta Commands

```ls
metric m:sum_of_amount p:integer l:"Sum Of Amount" t:dataTypeName=number

metric m:sum_of_fte p:float l:"Sum Of FTE" t:dataTypeName=number

entity e:2qmq-fcpi l:Incrementalchanges t:url=https://data.seattle.gov/api/views/2qmq-fcpi

property e:2qmq-fcpi t:meta.view v:id=2qmq-fcpi v:category=Finance v:averageRating=0 v:name=Incrementalchanges

property e:2qmq-fcpi t:meta.view.owner v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:displayName="Seattle IT"

property e:2qmq-fcpi t:meta.view.tableauthor v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:roleName=administrator v:displayName="Seattle IT"
```

## Top Records

```ls
| :updated_at | inc_change_id | dept_code | report_section             | icchange_name                                                | inc_change_descr                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | sum_of_amount | sum_of_fte | 
| =========== | ============= | ========= | ========================== | ============================================================ | ============================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================== | ============= | ========== | 
| 1381234961  |               | 12LIBLEVY | Total 2014 Endorsed Budget |                                                              |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 12658704      |            | 
| 1381234961  |               | ARTS      | Total 2014 Endorsed Budget |                                                              |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 7243761       | 28.09      | 
| 1381234961  | 946           | ARTS      | Proposed Changes           | Increase Funding for Arts Education                          | Currently, access to arts education in Seattle Public Schools varies widely from school to school. In order to improve access to arts education, this funding will:
Help implement the Seattle Public Schools K-12 Arts Plan ($40,000);
Track the changes that are implemented and measure their impacts on student performance and behavior ($20,000); and
Create a position to link community arts organizations with schools ($90,000).                                                                                     | 149571        | 1.00       | 
| 1381234961  | 947           | ARTS      | Proposed Changes           | Increase Cultural Space Investment                           | This change increases the part-time cultural space liaison to full-time, and adds $100,000 to the cultural facilities awards, bringing the total amount of award funding to $250,000. The increase in staff time will enable Arts to:
Work with the Department of Planning and Development to develop policy tools that would allow for the preservation and development of affordable spaces for arts and culture; and
Implement an online space-finder resource to connect arts users with space providers.                  | 145221        | 0.50       | 
| 1381234961  | 948           | ARTS      | Proposed Changes           | Increase Administrative Support                              | Arts has seen a 40% reduction (2.5 FTEs) in its administrative and accounting staff over the past four years as a result of budget challenges. At the same time, Arts has added or expanded its mix of programs, including LHPAI, Arts Education and Cultural Facilities programs, resulting in increased demands on administrative staff. This increase restores a 1.0 administrative specialist and a 0.25 accounting position, and provides a small amount of funding for program interns to support department operations. | 108551        | 1.25       | 
| 1381234961  | 1064          | ARTS      | Proposed Changes           | Temporary Transition Team Leader for Langston Hughes (LHPAI) | This increase funds a consultant to serve as a transition team leader to facilitate the shift of LHPAI from a city-operated organization to an independently operated non-profit. The team leader is expected to be on board for 12 to 18 months.                                                                                                                                                                                                                                                                              | 70000         | 0.00       | 
| 1381234961  | 1147          | ARTS      | Proposed Changes           | Historic Theater Improvements                                | This one-time funding supports capital improvements for two historic Seattle theaters: the Moore Theater will receive $80,000; and the Egyptian Theater will receive $75,000. This funding will help maintain and preserve these landmark facilities and allow for continued public access in future years.                                                                                                                                                                                                                    | 155000        | 0.00       | 
| 1381234961  | 991           | ARTS      | Proposed Technical Changes | Citywide Adjustments for Standard Cost Changes               | Citywide technical adjustments reflect changes due to inflation, central cost allocations, retirement, healthcare, workers' compensation and unemployment costs. These adjustments typically reflect updates to preliminary cost assumptions established in the 2014 Endorsed Budget.                                                                                                                                                                                                                                          | -63547        | 0.00       | 
| 1381234961  | 950           | ARTS      | Proposed Technical Changes | Align Public Art Expenditures with Revenues                  | Both the Seattle Department of Transportation and Seattle Public Utilities have significant increases in CIP project activity, and subsequently, their 1% for Art contribution. This expenditure increase tracks closely with increased Municipal Arts Fund revenues, and provides appropriation authority to develop the artwork related to new CIP projects.                                                                                                                                                                 | 500000        | 0.00       | 
| 1381234961  | 738           | ARTS      | Proposed Technical Changes | Technical Adjustments                                        | These adjustments align the Langston Hughes Performing Arts Institute budget with actual operating costs. Utility charges and Department of Information Technology costs were higher than anticipated when LHPAI was originally transferred from the Department of Parks and Recreation (Parks). The Parks budget includes a corresponding reduction making this change budget neutral.                                                                                                                                        | 45500         | 0.00       | 
```