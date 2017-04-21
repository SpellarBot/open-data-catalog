# C4K Children School Age By Setting SFY 2016 Monthly Average

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/c4k-children-school-age-by-setting-sfy-2016-monthly-average) |
| Metadata | [Link](https://data.ct.gov/api/views/9a8e-emi5) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/9a8e-emi5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/9a8e-emi5/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | 9a8e-emi5 |
| Name | C4K Children School Age By Setting SFY 2016 Monthly Average |
| Attribution | Connecticut Office of Early Childhood, Care 4 Kids |
| Category | Education |
| Tags | education, child care, c4k, care 4 kids, school age |
| Created | 2017-01-16T16:10:06Z |
| Publication Date | 2017-01-16T16:27:01Z |

## Description

Care 4 Kids Number of Children, Preschool Age, by Setting Type and Town, SFY 2016 Monthly Average. Care 4 Kids (C4K) is Connecticut's Child Care subsidy program.

## Columns

```ls
| Included | Schema Type    | Field Name                                                              | Name                                                                     | Data Type | Render Type |
| ======== | ============== | ======================================================================= | ======================================================================== | ========= | =========== |
| Yes      | series tag     | care_4_kids_number_of_children_paid_by_age_category_and_service_setting | Care 4 Kids Number of Children Paid by Age Category and Service Setting  | text      | text        |
| Yes      | numeric metric | school_age_group_home_regulated_sfy_2016_monthly_average                | School Age Group Home (Regulated) SFY 2016 Monthly Average               | number    | number      |
| Yes      | numeric metric | school_age_center_regulated_sfy_2016_monthly_average                    | School Age Center (Regulated) SFY 2016 Monthly Average                   | number    | text        |
| Yes      | numeric metric | school_age_family_home_regulated_sfy_2016_monthly_average               | School Age Family Home (Regulated) SFY 2016 Monthly Average              | number    | text        |
| Yes      | numeric metric | school_age_exempt_program_sfy_2016_monthly_average                      | School Age Exempt Program SFY 2016 Monthly Average                       | number    | text        |
| Yes      | numeric metric | school_age_exempt_school_sfy_2016_monthly_average                       | School Age Exempt School SFY 2016 Monthly Average                        | number    | text        |
| Yes      | numeric metric | school_age_relative_care_in_home_unregulated_sfy_2016_monthly_average   | School Age Relative Care, In Home (Unregulated) SFY 2016 Monthly Average | number    | text        |
| Yes      | numeric metric | school_age_total_sfy_2016_monthly_average                               | School Age Total SFY 2016 Monthly Average                                | number    | text        |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:9a8e-emi5 d:2016-01-01T00:00:00.000Z t:school_age_total_sfy_2016_monthly_average=* t:school_age_center_regulated_sfy_2016_monthly_average=* t:school_age_relative_care_in_home_unregulated_sfy_2016_monthly_average=* t:care_4_kids_number_of_children_paid_by_age_category_and_service_setting=ANDOVER t:school_age_family_home_regulated_sfy_2016_monthly_average=* m:school_age_exempt_program_sfy_2016_monthly_average=0 m:school_age_exempt_school_sfy_2016_monthly_average=0 m:school_age_group_home_regulated_sfy_2016_monthly_average=0

series e:9a8e-emi5 d:2016-01-01T00:00:00.000Z t:school_age_exempt_school_sfy_2016_monthly_average=* t:care_4_kids_number_of_children_paid_by_age_category_and_service_setting=ANSONIA m:school_age_exempt_program_sfy_2016_monthly_average=11 m:school_age_total_sfy_2016_monthly_average=69 m:school_age_center_regulated_sfy_2016_monthly_average=23 m:school_age_relative_care_in_home_unregulated_sfy_2016_monthly_average=24 m:school_age_family_home_regulated_sfy_2016_monthly_average=14 m:school_age_group_home_regulated_sfy_2016_monthly_average=0

series e:9a8e-emi5 d:2016-01-01T00:00:00.000Z t:school_age_total_sfy_2016_monthly_average=* t:school_age_center_regulated_sfy_2016_monthly_average=* t:school_age_relative_care_in_home_unregulated_sfy_2016_monthly_average=* t:care_4_kids_number_of_children_paid_by_age_category_and_service_setting=AVON m:school_age_exempt_program_sfy_2016_monthly_average=0 m:school_age_exempt_school_sfy_2016_monthly_average=0 m:school_age_family_home_regulated_sfy_2016_monthly_average=0 m:school_age_group_home_regulated_sfy_2016_monthly_average=0
```

## Meta Commands

```ls
metric m:school_age_group_home_regulated_sfy_2016_monthly_average p:integer l:"School Age Group Home (Regulated) SFY 2016 Monthly Average" d:"Numbers reflect initial payments in the reporting month and retroactive certificate payments or adjustment payments made during the subsequent two months. * Suppressed cells if 5 or less. Zero is shown as 0." t:dataTypeName=number

entity e:9a8e-emi5 l:"C4K Children School Age By Setting SFY 2016 Monthly Average" t:attribution="Connecticut Office of Early Childhood, Care 4 Kids" t:url=https://data.ct.gov/api/views/9a8e-emi5

property e:9a8e-emi5 t:meta.view v:id=9a8e-emi5 v:category=Education v:attributionLink=http://www.ctcare4kids.com/care-4-kids-program/reports/ v:averageRating=0 v:name="C4K Children School Age By Setting SFY 2016 Monthly Average" v:attribution="Connecticut Office of Early Childhood, Care 4 Kids"

property e:9a8e-emi5 t:meta.view.owner v:id=6maf-a7j9 v:screenName="Julie Bisi" v:displayName="Julie Bisi"

property e:9a8e-emi5 t:meta.view.tableauthor v:id=6maf-a7j9 v:screenName="Julie Bisi" v:roleName=editor v:displayName="Julie Bisi"
```

## Top Records

```ls
| care_4_kids_number_of_children_paid_by_age_category_and_service_setting | school_age_group_home_regulated_sfy_2016_monthly_average | school_age_center_regulated_sfy_2016_monthly_average | school_age_family_home_regulated_sfy_2016_monthly_average | school_age_exempt_program_sfy_2016_monthly_average | school_age_exempt_school_sfy_2016_monthly_average | school_age_relative_care_in_home_unregulated_sfy_2016_monthly_average | school_age_total_sfy_2016_monthly_average | 
| ======================================================================= | ======================================================== | ==================================================== | ========================================================= | ================================================== | ================================================= | ===================================================================== | ========================================= | 
| ANDOVER                                                                 | 0                                                        | *                                                    | *                                                         | 0                                                  | 0                                                 | *                                                                     | *                                         | 
| ANSONIA                                                                 | 0                                                        | 23                                                   | 14                                                        | 11                                                 | *                                                 | 24                                                                    | 69                                        | 
| AVON                                                                    | 0                                                        | *                                                    | 0                                                         | 0                                                  | 0                                                 | *                                                                     | *                                         | 
| BARKHAMSTED                                                             | 0                                                        | *                                                    | 0                                                         | 0                                                  | 0                                                 | 0                                                                     | *                                         | 
| BEACON FALLS                                                            | 0                                                        | *                                                    | 0                                                         | 0                                                  | 0                                                 | 0                                                                     | *                                         | 
| BERLIN                                                                  | 0                                                        | 7                                                    | 0                                                         | *                                                  | 0                                                 | *                                                                     | 11                                        | 
| BETHANY                                                                 | 0                                                        | 0                                                    | 0                                                         | 0                                                  | 0                                                 | 0                                                                     | 0                                         | 
| BETHEL                                                                  | 0                                                        | 7                                                    | *                                                         | *                                                  | *                                                 | *                                                                     | 11                                        | 
| BETHLEHEM                                                               | 0                                                        | *                                                    | 0                                                         | 0                                                  | 0                                                 | 0                                                                     | *                                         | 
| BLOOMFIELD                                                              | 0                                                        | 15                                                   | 7                                                         | 0                                                  | 9                                                 | 18                                                                    | 48                                        | 
```