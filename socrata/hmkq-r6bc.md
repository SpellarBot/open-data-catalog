# Cook County Public Health Flu Vaccination Partners - Historical

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cook-county-public-health-flu-vaccination-partners-historical) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/hmkq-r6bc) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/hmkq-r6bc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/hmkq-r6bc/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | hmkq-r6bc |
| Name | Cook County Public Health Flu Vaccination Partners - Historical |
| Category | Healthcare |
| Tags | health |
| Created | 2012-11-01T21:41:36Z |
| Publication Date | 2014-10-27T16:39:05Z |

## Description

This dataset contains historical data from 2012.

## Columns

```ls
| Included | Schema Type | Field Name                       | Name                             | Data Type | Render Type |
| ======== | =========== | ================================ | ================================ | ========= | =========== |
| No       | time        | :updated_at                      | updated_at                       | meta_data | meta_data   |
| Yes      | series tag  | site_location                    | Site/Location                    | text      | text        |
| Yes      | series tag  | contact_information_and_schedule | Contact information and Schedule | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:hmkq-r6bc d:2012-11-01T14:41:45.000Z t:site_location="Howard Mohr Community Center
Community Center" t:contact_information_and_schedule="phone (708) 771-7737, Please call for schedule" m:row_number.hmkq-r6bc=1

series e:hmkq-r6bc d:2012-11-01T14:41:45.000Z t:site_location="Lincolnwood Fire Dept" t:contact_information_and_schedule="phone (847)673-1545; Only 90 doses available, please call for schedule" m:row_number.hmkq-r6bc=2

series e:hmkq-r6bc d:2012-11-01T14:41:45.000Z t:site_location="Palos Township Health Services" t:contact_information_and_schedule="Phone (708)598-2441; Starting Sep 12, until supply is exhausted" m:row_number.hmkq-r6bc=3
```

## Meta Commands

```ls
metric m:row_number.hmkq-r6bc p:long l:"Row Number"

entity e:hmkq-r6bc l:"Cook County Public Health Flu Vaccination Partners - Historical" t:url=https://datacatalog.cookcountyil.gov/api/views/hmkq-r6bc

property e:hmkq-r6bc t:meta.view v:id=hmkq-r6bc v:category=Healthcare v:averageRating=0 v:name="Cook County Public Health Flu Vaccination Partners - Historical"

property e:hmkq-r6bc t:meta.view.license v:name="Public Domain"

property e:hmkq-r6bc t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:hmkq-r6bc t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| :updated_at | site_location                                 | contact_information_and_schedule                                                                | 
| =========== | ============================================= | =============================================================================================== | 
| 1351780905  | Howard Mohr Community Center Community Center | phone (708) 771-7737, Please call for schedule                                                  | 
| 1351780905  | Lincolnwood Fire Dept                         | phone (847)673-1545; Only 90 doses available, please call for schedule                          | 
| 1351780905  | Palos Township Health Services                | Phone (708)598-2441; Starting Sep 12, until supply is exhausted                                 | 
| 1351780905  | Carl Fiorito Senior Ctr                       | Call RHAMC @(312) 243-2000; Oct 17, Wed 9am ? 12pm                                              | 
| 1351780905  | Calumet Township                              | Call RHAMC @(312) 243-2000, Oct 19, Wed 11am-12pm                                               | 
| 1351780905  | Stickney Township                             | phone (708) 424-9200, Starting Oct 4, Mon-Fri, please call for times                            | 
| 1351780905  | St. Germaine Church                           | Call RHAMC @(312) 243-2000, Oct 14, Sun 8am-12pm                                                | 
| 1351780905  | Berwyn Health Dept                            | phone (708) 788-6600; Sep? Dec, 2012 every Tues & Fri 10am-4pm                                  | 
| 1351780905  | Cicero Health Dept                            | phone (708) 656-3600 Starting October 6, Sat 9am-4pm, then every Mon, Tues, Wed, Thurs 9am -6pm | 
| 1351780905  | Village of Elmwood Park                       | Call RHAMC @(312) 243-2000; Oct 15, Mon 10am-1:30pm                                             | 
```