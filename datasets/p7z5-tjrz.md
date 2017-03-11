# Tuition Assistance

## Dataset

* [Dataset URL](https://data.montgomerycountymd.gov/api/views/p7z5-tjrz/rows.json?accessType=DOWNLOAD)
* [Catalog URL](https://catalog.data.gov/dataset/tuition-assistance-5fc94)
* Id = p7z5-tjrz
* Name = Tuition Assistance
* Category = Education
* Tags = [tuition assistance, course, school, class curriculum, reimburse, employee]
* Created = 2013-08-14T13:48:25Z
* Publication Date = 2015-08-15T07:34:25Z
* Rows Updated = 2017-02-15T08:30:29Z

## Description

This dataset includes a list of classes approved and paid through the County tuition assistance program, including the title and description of the course, the school the course will be taken at, the degree this class curriculum is a part of, the Department and title of the requester, the dollar amount reimbursed to the employee.  Update Frequency:  Twice a Year

## Columns

```ls
| Name               | Field Name   | Data Type | Render Type | Schema Type    | Included | 
| ================== | ============ | ========= | =========== | ============== | ======== | 
| updated_at         | :updated_at  | meta_data | meta_data   | time           | Yes      | 
| Department         | department   | text      | text        | series tag     | Yes      | 
| Major              | major_desc   | text      | text        | series tag     | Yes      | 
| Degree             | degree_desc  | text      | text        | series tag     | Yes      | 
| School             | school_desc  | text      | text        | series tag     | Yes      | 
| Course Title       | course_title | text      | text        | series tag     | Yes      | 
| Course Description | course_desc  | text      | text        | series tag     | Yes      | 
| Cost               | cost         | money     | money       | numeric metric | Yes      | 
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
```

## Data Commands

```ls
series e:p7z5-tjrz d:2015-08-15T00:33:50.000Z t:degree_desc=AA t:major_desc=Business/Admin./Mgmt. t:course_title="INTRODUCTION TO BUSINESS" t:department=Police t:school_desc="Montgomery College Rockville Campus" t:course_desc="An introductory course designed to survey the field of business and its environment in order to give the student a broad overview of the principles, practices, institutions, and functions of business." m:cost=392

series e:p7z5-tjrz d:2015-08-15T00:33:50.000Z t:degree_desc=AA t:major_desc=Business/Admin./Mgmt. t:course_title="MA 160" t:department=Police t:school_desc="Montgomery College Rockville Campus" t:course_desc="A general calculus course primarily for business students. Topics include algebraic, exponential, and logarithmic functions and their graphs; an intuitive approach to limits; differentiation; integration; and functions of several variables. Major emphasis" m:cost=392

series e:p7z5-tjrz d:2015-08-15T00:33:50.000Z t:degree_desc=AA t:major_desc=Business/Admin./Mgmt. t:course_title="INTRO TO AMERICAN MUSIC" t:department=Police t:school_desc="Montgomery College Rockville Campus" t:course_desc="A survey of American popular music from the turn of the 20th century to the present with an emphasis on rock music." m:cost=392
```

## Meta Commands

```ls
the United States health care system is studied. Concepts and 

applications of the system are explored as well as comparisons with international health care paradigms. Introduction to the s" m:cost=1569

network (WAN) projects using Cisco IOS command set." m:cost=0

network topologies, IP addressing, subnet masks, basic network 

design and cable installation." m:cost=363.33

include attitudes toward anxiety, issues of guilt, exi" m:cost=234

troubleshoot Cisco routers and components." m:cost=363.33

inclu" m:cost=915

entity e:p7z5-tjrz l:"Tuition Assistance" t:url=https://data.montgomerycountymd.gov/api/views/p7z5-tjrz

property e:p7z5-tjrz t:meta.view d:2017-03-03T14:08:36.055Z v:id=p7z5-tjrz v:category=Education v:averageRating=0 v:name="Tuition Assistance"

property e:p7z5-tjrz t:meta.view.owner d:2017-03-03T14:08:36.055Z v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:roleName=administrator v:displayName="MCG ESB Service"

property e:p7z5-tjrz t:meta.view.tableauthor d:2017-03-03T14:08:36.055Z v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:roleName=administrator v:displayName="MCG ESB Service"
```