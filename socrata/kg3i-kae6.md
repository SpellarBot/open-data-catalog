# Statement of Economic Interests (SEI) (Form 700) - Filing Officers and Department Heads

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/statement-of-economic-interests-sei-form-700-filing-officers-and-department-heads-91aa3) |
| Metadata | [Link](https://data.sfgov.org/api/views/kg3i-kae6) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/kg3i-kae6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/kg3i-kae6/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | kg3i-kae6 |
| Name | Statement of Economic Interests (SEI) (Form 700) - Filing Officers and Department Heads |
| Attribution | San Francisco Ethics Commission |
| Category | City Management and Ethics |
| Tags | statement of economic interests, sei, form 700, ethics, conflict of interest |
| Created | 2014-07-21T18:03:54Z |
| Publication Date | 2015-01-21T00:55:19Z |

## Description

The current list of filing officers and department heads for departments/boards/commissions that file Statement of Economic Interests (SEI) (Form 700) forms with the Ethics Commission.

## Columns

```ls
| Included | Schema Type | Field Name                                     | Name                               | Data Type | Render Type |
| ======== | =========== | ============================================== | ================================== | ========= | =========== |
| No       | time        | :updated_at                                    | updated_at                         | meta_data | meta_data   |
| Yes      | series tag  | department_board_commission_name_based_on_code | Department/Board/Commission        | text      | text        |
| Yes      | series tag  | other_offices_under_the_department             | Other Offices Under the Department | text      | text        |
| Yes      | series tag  | filing_officer_or_staff_contact                | Filing Officer or Staff Contact    | text      | text        |
| Yes      | series tag  | department_head                                | Department Head                    | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:kg3i-kae6 d:2015-01-20T16:53:27.000Z t:filing_officer_or_staff_contact="Laura Hathhorn" t:department_head="Jay Xu" t:other_offices_under_the_department="Asian Art Museum Commission & Director" t:department_board_commission_name_based_on_code="Asian Art Museum" m:row_number.kg3i-kae6=1

series e:kg3i-kae6 d:2015-01-20T16:53:27.000Z t:filing_officer_or_staff_contact="Gigi Whitley" t:department_head="Carmen Chu" t:other_offices_under_the_department="Department Head" t:department_board_commission_name_based_on_code=Assessor-Recorder m:row_number.kg3i-kae6=2

series e:kg3i-kae6 d:2015-01-20T16:53:27.000Z t:filing_officer_or_staff_contact="Peggy Nevin / Rachel Gosiengfiao" t:department_head="Angela Cavillo" t:other_offices_under_the_department="Board of Supervisors" t:department_board_commission_name_based_on_code="Board of Supervisors" m:row_number.kg3i-kae6=3
```

## Meta Commands

```ls
metric m:row_number.kg3i-kae6 p:long l:"Row Number"

entity e:kg3i-kae6 l:"Statement of Economic Interests (SEI) (Form 700) - Filing Officers and Department Heads" t:attribution="San Francisco Ethics Commission" t:url=https://data.sfgov.org/api/views/kg3i-kae6

property e:kg3i-kae6 t:meta.view v:id=kg3i-kae6 v:category="City Management and Ethics" v:attributionLink=http://www.sfethics.org v:averageRating=0 v:name="Statement of Economic Interests (SEI) (Form 700) - Filing Officers and Department Heads" v:attribution="San Francisco Ethics Commission"

property e:kg3i-kae6 t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:kg3i-kae6 t:meta.view.owner v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:displayName="Steven Massey"

property e:kg3i-kae6 t:meta.view.tableauthor v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"
```

## Top Records

```ls
| :updated_at | department_board_commission_name_based_on_code    | other_offices_under_the_department     | filing_officer_or_staff_contact  | department_head | 
| =========== | ================================================= | ====================================== | ================================ | =============== | 
| 1421772807  | Asian Art Museum                                  | Asian Art Museum Commission & Director | Laura Hathhorn                   | Jay Xu          | 
| 1421772807  | Assessor-Recorder                                 | Department Head                        | Gigi Whitley                     | Carmen Chu      | 
| 1421772807  | Board of Supervisors                              | Board of Supervisors                   | Peggy Nevin / Rachel Gosiengfiao | Angela Cavillo  | 
| 1421772807  | Board of Supervisors                              | Assessment Appeals Board               | Dawn Duran / Alistair Gibson     | Angela Cavillo  | 
| 1421772807  | Board of Supervisors                              | Sunshine Ordinance Task Force          | Victor Young                     | Angela Cavillo  | 
| 1421772807  | Board of Supervisors (from PUC)                   | Revenue Bond Oversight Committee       | Derek Evans                      | Angela Cavillo  | 
| 1421772807  | Building Inspection, Department of                | Building Inspection Commission         | Sonya Harris                     | Tom C. Hui      | 
| 1421772807  | Building Inspection, Department of                | Executive Director                     | Carolyn Jayin                    | Tom C. Hui      | 
| 1421772807  | Children & Families First Commission              | Commission and Executive Director      | Kahala Drain                     | Laurel Kloomok  | 
| 1421772807  | Children, Youth and Their Families, Department of | Department Head                        | Emily Davis                      | Maria Su        | 
```