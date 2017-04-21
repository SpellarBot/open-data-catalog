# Care 4 Kids Children Preschool Age By Setting SFY 2016 Monthly Average

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/care-4-kids-children-preschool-age-by-setting-sfy-2016-monthly-average) |
| Metadata | [Link](https://data.ct.gov/api/views/nj44-rjue) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/nj44-rjue/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/nj44-rjue/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | nj44-rjue |
| Name | Care 4 Kids Children Preschool Age By Setting SFY 2016 Monthly Average |
| Attribution | Connecticut Office of Early Childhood, Care 4 Kids |
| Category | Education |
| Tags | education, child care, c4k, care 4 kids, child care subsidy, preschool |
| Created | 2017-01-16T15:50:43Z |
| Publication Date | 2017-01-16T16:01:24Z |

## Description

Care 4 Kids Number of Children, Preschool Age, by Setting Type and Town, SFY 2016 Monthly Average. Care 4 Kids (C4K) is Connecticut's Child Care subsidy program.

## Columns

```ls
| Included | Schema Type    | Field Name                                                                   | Name                                                                           | Data Type | Render Type |
| ======== | ============== | ============================================================================ | ============================================================================== | ========= | =========== |
| Yes      | series tag     | care_4_kids_number_of_children_paid_by_age_category_and_service_setting      | Care 4 Kids Number of Children Paid by Age Category and Service Setting        | text      | text        |
| Yes      | numeric metric | preschool_center_regulated_sfy_2016_monthly_average                          | Preschool Center (Regulated) SFY 2016 Monthly Average                          | number    | text        |
| Yes      | numeric metric | preschool_group_home_regulated_sfy_2016_monthly_average                      | Preschool Group Home (Regulated) SFY 2016 Monthly Average                      | number    | text        |
| Yes      | numeric metric | preschool_family_home_regulated_sfy_2016_monthly_average                     | Preschool Family Home (Regulated) SFY 2016 Monthly Average                     | number    | text        |
| Yes      | numeric metric | preschool_exempt_school_sfy_2016_monthly_average                             | Preschool Exempt School SFY 2016 Monthly Average                               | number    | text        |
| Yes      | numeric metric | preschool_exempt_program_sfy_2016_monthly_average                            | Preschool Exempt Program SFY 2016 Monthly Average                              | number    | text        |
| Yes      | numeric metric | preschool_relative_care_in_child_s_home_unregulated_sfy_2016_monthly_average | Preschool Relative Care in Child's Home (Unregulated) SFY 2016 Monthly Average | number    | text        |
| Yes      | numeric metric | preschool_total_sfy_2016_monthly_average                                     | Preschool Total SFY 2016 Monthly Average                                       | number    | text        |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:nj44-rjue d:2016-01-01T00:00:00.000Z t:care_4_kids_number_of_children_paid_by_age_category_and_service_setting=ANDOVER m:preschool_exempt_program_sfy_2016_monthly_average=0 m:preschool_total_sfy_2016_monthly_average=0 m:preschool_relative_care_in_child_s_home_unregulated_sfy_2016_monthly_average=0 m:preschool_exempt_school_sfy_2016_monthly_average=0 m:preschool_center_regulated_sfy_2016_monthly_average=0 m:preschool_group_home_regulated_sfy_2016_monthly_average=0 m:preschool_family_home_regulated_sfy_2016_monthly_average=0

series e:nj44-rjue d:2016-01-01T00:00:00.000Z t:preschool_exempt_program_sfy_2016_monthly_average=* t:preschool_exempt_school_sfy_2016_monthly_average=* t:care_4_kids_number_of_children_paid_by_age_category_and_service_setting=ANSONIA m:preschool_total_sfy_2016_monthly_average=69 m:preschool_relative_care_in_child_s_home_unregulated_sfy_2016_monthly_average=14 m:preschool_center_regulated_sfy_2016_monthly_average=42 m:preschool_group_home_regulated_sfy_2016_monthly_average=0 m:preschool_family_home_regulated_sfy_2016_monthly_average=11

series e:nj44-rjue d:2016-01-01T00:00:00.000Z t:preschool_total_sfy_2016_monthly_average=* t:preschool_relative_care_in_child_s_home_unregulated_sfy_2016_monthly_average=* t:care_4_kids_number_of_children_paid_by_age_category_and_service_setting=ASHFORD m:preschool_exempt_program_sfy_2016_monthly_average=0 m:preschool_exempt_school_sfy_2016_monthly_average=0 m:preschool_center_regulated_sfy_2016_monthly_average=0 m:preschool_group_home_regulated_sfy_2016_monthly_average=0 m:preschool_family_home_regulated_sfy_2016_monthly_average=0
```

## Meta Commands

```ls
entity e:nj44-rjue l:"Care 4 Kids Children Preschool Age By Setting SFY 2016 Monthly Average" t:attribution="Connecticut Office of Early Childhood, Care 4 Kids" t:url=https://data.ct.gov/api/views/nj44-rjue

property e:nj44-rjue t:meta.view v:id=nj44-rjue v:category=Education v:attributionLink=http://www.ctcare4kids.com/care-4-kids-program/reports/ v:averageRating=0 v:name="Care 4 Kids Children Preschool Age By Setting SFY 2016 Monthly Average" v:attribution="Connecticut Office of Early Childhood, Care 4 Kids"

property e:nj44-rjue t:meta.view.owner v:id=6maf-a7j9 v:screenName="Julie Bisi" v:displayName="Julie Bisi"

property e:nj44-rjue t:meta.view.tableauthor v:id=6maf-a7j9 v:screenName="Julie Bisi" v:roleName=editor v:displayName="Julie Bisi"
```

## Top Records

```ls
| care_4_kids_number_of_children_paid_by_age_category_and_service_setting | preschool_center_regulated_sfy_2016_monthly_average | preschool_group_home_regulated_sfy_2016_monthly_average | preschool_family_home_regulated_sfy_2016_monthly_average | preschool_exempt_school_sfy_2016_monthly_average | preschool_exempt_program_sfy_2016_monthly_average | preschool_relative_care_in_child_s_home_unregulated_sfy_2016_monthly_average | preschool_total_sfy_2016_monthly_average | 
| ======================================================================= | =================================================== | ======================================================= | ======================================================== | ================================================ | ================================================= | ============================================================================ | ======================================== | 
| ANDOVER                                                                 | 0                                                   | 0                                                       | 0                                                        | 0                                                | 0                                                 | 0                                                                            | 0                                        | 
| ANSONIA                                                                 | 42                                                  | 0                                                       | 11                                                       | *                                                | *                                                 | 14                                                                           | 69                                       | 
| ASHFORD                                                                 | 0                                                   | 0                                                       | 0                                                        | 0                                                | 0                                                 | *                                                                            | *                                        | 
| AVON                                                                    | *                                                   | 0                                                       | 0                                                        | 0                                                | 0                                                 | 0                                                                            | *                                        | 
| BARKHAMSTED                                                             | *                                                   | 0                                                       | 0                                                        | 0                                                | 0                                                 | 0                                                                            | *                                        | 
| BEACON FALLS                                                            | 8                                                   | 0                                                       | 0                                                        | 0                                                | 0                                                 | 0                                                                            | 8                                        | 
| BERLIN                                                                  | 12                                                  | 0                                                       | 0                                                        | *                                                | 0                                                 | *                                                                            | 13                                       | 
| BETHANY                                                                 | *                                                   | 0                                                       | 0                                                        | 0                                                | 0                                                 | 0                                                                            | *                                        | 
| BETHEL                                                                  | 16                                                  | 0                                                       | *                                                        | *                                                | 0                                                 | *                                                                            | 19                                       | 
| BETHLEHEM                                                               | *                                                   | 0                                                       | 0                                                        | 0                                                | 0                                                 | 0                                                                            | *                                        | 
```