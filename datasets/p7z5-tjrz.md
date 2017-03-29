# Tuition Assistance

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/tuition-assistance-5fc94) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/p7z5-tjrz) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/p7z5-tjrz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/p7z5-tjrz/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | p7z5-tjrz |
| Name | Tuition Assistance |
| Category | Education |
| Tags | tuition assistance, course, school, class curriculum, reimburse, employee |
| Created | 2013-08-14T13:48:25Z |
| Publication Date | 2015-08-15T07:34:25Z |

## Description

This dataset includes a list of classes approved and paid through the County tuition assistance program, including the title and description of the course, the school the course will be taken at, the degree this class curriculum is a part of, the Department and title of the requester, the dollar amount reimbursed to the employee.  Update Frequency:  Twice a Year

## Columns

```ls
| Included | Schema Type    | Field Name   | Name               | Data Type | Render Type |
| ======== | ============== | ============ | ================== | ========= | =========== |
| No       | time           | :updated_at  | updated_at         | meta_data | meta_data   |
| Yes      | series tag     | department   | Department         | text      | text        |
| Yes      | series tag     | major_desc   | Major              | text      | text        |
| Yes      | series tag     | degree_desc  | Degree             | text      | text        |
| Yes      | series tag     | school_desc  | School             | text      | text        |
| Yes      | series tag     | course_title | Course Title       | text      | text        |
| Yes      | series tag     | course_desc  | Course Description | text      | text        |
| Yes      | numeric metric | cost         | Cost               | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:p7z5-tjrz d:2015-08-15T00:33:50.000Z t:degree_desc=AA t:major_desc=Business/Admin./Mgmt. t:course_title="INTRODUCTION TO BUSINESS" t:department=Police t:school_desc="Montgomery College Rockville Campus" t:course_desc="An introductory course designed to survey the field of business and its environment in order to give the student a broad overview of the principles, practices, institutions, and functions of business." m:cost=392

series e:p7z5-tjrz d:2015-08-15T00:33:50.000Z t:degree_desc=AA t:major_desc=Business/Admin./Mgmt. t:course_title="MA 160" t:department=Police t:school_desc="Montgomery College Rockville Campus" t:course_desc="A general calculus course primarily for business students. Topics include algebraic, exponential, and logarithmic functions and their graphs; an intuitive approach to limits; differentiation; integration; and functions of several variables. Major emphasis" m:cost=392

series e:p7z5-tjrz d:2015-08-15T00:33:50.000Z t:degree_desc=AA t:major_desc=Business/Admin./Mgmt. t:course_title="INTRO TO AMERICAN MUSIC" t:department=Police t:school_desc="Montgomery College Rockville Campus" t:course_desc="A survey of American popular music from the turn of the 20th century to the present with an emphasis on rock music." m:cost=392
```

## Meta Commands

```ls
metric m:cost p:double l:Cost t:dataTypeName=money

entity e:p7z5-tjrz l:"Tuition Assistance" t:url=https://data.montgomerycountymd.gov/api/views/p7z5-tjrz

property e:p7z5-tjrz t:meta.view v:id=p7z5-tjrz v:category=Education v:averageRating=0 v:name="Tuition Assistance"

property e:p7z5-tjrz t:meta.view.owner v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:displayName="MCG ESB Service"

property e:p7z5-tjrz t:meta.view.tableauthor v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:roleName=administrator v:displayName="MCG ESB Service"
```

## Top Records

```ls
| :updated_at | department              | major_desc              | degree_desc              | school_desc                                 | course_title                                 | course_desc                                                                                                                                                                                                                                                     | cost    | 
| =========== | ======================= | ======================= | ======================== | =========================================== | ============================================ | =============================================================================================================================================================================================================================================================== | ======= | 
| 1439598830  | Police                  | Business/Admin./Mgmt.   | AA                       | Montgomery College Rockville Campus         | INTRODUCTION TO BUSINESS                     | An introductory course designed to survey the field of business and its environment in order to give the student a broad overview of the principles, practices, institutions, and functions of business.                                                        | 392.00  | 
| 1439598830  | Police                  | Business/Admin./Mgmt.   | AA                       | Montgomery College Rockville Campus         | MA 160                                       | A general calculus course primarily for business students. Topics include algebraic, exponential, and logarithmic functions and their graphs; an intuitive approach to limits; differentiation; integration; and functions of several variables. Major emphasis | 392.00  | 
| 1439598830  | Police                  | Business/Admin./Mgmt.   | AA                       | Montgomery College Rockville Campus         | INTRO TO AMERICAN MUSIC                      | A survey of American popular music from the turn of the 20th century to the present with an emphasis on rock music.                                                                                                                                             | 392.00  | 
| 1439598830  | Health & Human Services | Business/Admin./Mgmt.   | Masters (MA/MS/MPH/etc.) | BOWIE STATE UNIVERSITY                      | PUBLIC POLICY ANALYSIS                       | Focus is on the analysis of costs and benefits in the selection of the public policy choices. Students analyze public policy alternatives, factors, and process involved in policy development, including the rulemaking that occurs after legislative enactmen | 1062.00 | 
| 1439598830  | Health & Human Services | Other/Misc.             | Masters (MA/MS/MPH/etc.) | Mount St Mary's University                  | MHA 500 CONTEMPORARY ISSUES IN HEALTH CARE   | The historical, current, and future organization and delivery of the United States health care system is studied. Concepts and applications of the system are explored as well as comparisons with international health care paradigms. Introduction to the s   | 1569.00 | 
| 1439598830  | Finance                 | Accounting (Business)   | Masters (MA/MS/MPH/etc.) | University of Maryland - University College | ACCT FINANCIAL MGMT CAPSTONE                 | A synthesis of material from all previous study in financial management and information systems that reflects the importance of information systems in modern organizations and the role of the CFO/CIO in managing this resource to maximize value. Simulation | 870.00  | 
| 1439598830  | Police                  | Business/Admin./Mgmt.   | AA                       | Montgomery College Rockville Campus         | ACCOUNTING 202                               | The study and analysis of managerial accounting. Topics include cost accumulation, evaluation, and analysis for decision making, as well as coverage of the statement of cash flows and financial statement analysis.                                           | 392.00  | 
| 1439598830  | Health & Human Services | Pre-Nursing             | AA                       | PRINCE GEORGE'S COMMUNITY COLLEGE           | NUTRITION ONLINE                             | Addresses basic information about essential nutrients and their functions in the body as well as known and hypothesized relationships between long-term diets and development of chronic diseases. The course addresses current issues in nutrition and food sa | 294.00  | 
| 1439598830  | County Attorney         | Health & Human Services | Bachelors (BA/BS)        | University of Maryland - University College | WRTG 101, INTRODUCTION TO WRITING            | practice in effective writing and clear thinking at all levels, including the sentence and paragraph, with emphasis on the essay and research report. The objective is to apply specific steps within the writing process, including formulating purpose, ident | 0.00    | 
| 1439598830  | Health & Human Services | Not Listed              | Masters (MA/MS/MPH/etc.) | University of Maryland - Baltimore          | CLINICAL ADV FIELD PRACTICUM - SWCL 794 - 01 | Two semesters in the Advanced Curriculum. Assignment to agencies and organizations for practice responsibilities and instruction in clinical social work.                                                                                                       | 1830.00 | 
```