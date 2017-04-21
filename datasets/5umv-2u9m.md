# Department of Human Resources(DHR) Family Investment Administration Program Caseloads

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/department-of-human-resourcesdhr-family-investment-administration-program-caseloads) |
| Metadata | [Link](https://data.maryland.gov/api/views/5umv-2u9m) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/5umv-2u9m/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/5umv-2u9m/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | 5umv-2u9m |
| Name | Department of Human Resources(DHR) Family Investment Administration Program Caseloads |
| Attribution | Department of Human Resources |
| Category | Health and Human Services |
| Tags | food stamp, nutritional supplement, emergency food |
| Created | 2016-07-08T16:06:41Z |
| Publication Date | 2017-03-22T13:49:59Z |

## Description

Food Supplement Program (FSP) active cases are the number of total cases that are active at the end of the FSP benefit receiving month and for the following month. These cases are active because they are compliant with all FSP eligibility requirements.

Expedited Food Supplement Program approved cases are FSP cases that meet the expedited requirements and FSP eligibility requirements. 

Note: If expedited FSP cases remain active at the end of the application month, they will be included in the overall active FSP cases

## Columns

```ls
| Included | Schema Type    | Field Name                                                                                                                                                              | Name                                                                                                                                                                         | Data Type     | Render Type   |
| ======== | ============== | ======================================================================================================================================================================= | ============================================================================================================================================================================ | ============= | ============= |
| Yes      | time           | date                                                                                                                                                                    | Date                                                                                                                                                                         | calendar_date | calendar_date |
| Yes      | series tag     | month                                                                                                                                                                   | Month                                                                                                                                                                        | text          | text          |
| No       |                | fiscal_year                                                                                                                                                             | Calendar Year                                                                                                                                                                | calendar_date | calendar_date |
| Yes      | numeric metric | expedited_fs_approved_cases_expedited_fs_cases_are_included_in_the_overall_active_fsp_cases_if_the_expedited_fs_cases_are_still_active_at_the_end_of_the_calendar_month | Expedited FS - Approved Cases* *Expedited FS cases are included in the overall active FSP cases if the Expedited FS cases are still active at the end of the calendar month. | number        | number        |
| Yes      | numeric metric | number_of_cases_in_food_supplement_program                                                                                                                              | Number of Active Cases in the Food Supplement Program                                                                                                                        | number        | number        |
| Yes      | numeric metric | number_of_customers_served_through_tca                                                                                                                                  | Number of Active Cases in the Temporary Cash Assistance Program                                                                                                              | number        | number        |
| Yes      | series tag     | month_year                                                                                                                                                              | Month/Year                                                                                                                                                                   | text          | text          |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = fiscal_year
```

## Data Commands

```ls
series e:5umv-2u9m d:2011-05-31T00:00:00.000Z t:month=May t:month_year="May 2011" m:number_of_cases_in_food_supplement_program=330786 m:expedited_fs_approved_cases_expedited_fs_cases_are_included_in_the_overall_active_fsp_cases_if_the_expedited_fs_cases_are_still_active_at_the_end_of_the_calendar_month=9435 m:number_of_customers_served_through_tca=28542

series e:5umv-2u9m d:2011-06-30T00:00:00.000Z t:month=Jun. t:month_year="Jun 2011" m:number_of_cases_in_food_supplement_program=337265 m:expedited_fs_approved_cases_expedited_fs_cases_are_included_in_the_overall_active_fsp_cases_if_the_expedited_fs_cases_are_still_active_at_the_end_of_the_calendar_month=10677 m:number_of_customers_served_through_tca=28880

series e:5umv-2u9m d:2011-07-31T00:00:00.000Z t:month=Jul. t:month_year="Jul 2011" m:number_of_cases_in_food_supplement_program=340941 m:expedited_fs_approved_cases_expedited_fs_cases_are_included_in_the_overall_active_fsp_cases_if_the_expedited_fs_cases_are_still_active_at_the_end_of_the_calendar_month=10050 m:number_of_customers_served_through_tca=29105
```

## Meta Commands

```ls
metric m:expedited_fs_approved_cases_expedited_fs_cases_are_included_in_the_overall_active_fsp_cases_if_the_expedited_fs_cases_are_still_active_at_the_end_of_the_calendar_month p:integer l:"Expedited FS - Approved Cases* *Expedited FS cases are included in the overall active FSP cases if the Expedited FS cases are still active at the end of the calendar month." t:dataTypeName=number

metric m:number_of_cases_in_food_supplement_program p:integer l:"Number of Active Cases in the Food Supplement Program" t:dataTypeName=number

metric m:number_of_customers_served_through_tca p:integer l:"Number of Active Cases in the Temporary Cash Assistance Program" t:dataTypeName=number

entity e:5umv-2u9m l:"Department of Human Resources(DHR) Family Investment Administration Program Caseloads" t:attribution="Department of Human Resources" t:url=https://data.maryland.gov/api/views/5umv-2u9m

property e:5umv-2u9m t:meta.view v:id=5umv-2u9m v:category="Health and Human Services" v:attributionLink=http://www.dhr.state.md.us/blog/ v:averageRating=0 v:name="Department of Human Resources(DHR) Family Investment Administration Program Caseloads" v:attribution="Department of Human Resources"

property e:5umv-2u9m t:meta.view.license v:name="Public Domain"

property e:5umv-2u9m t:meta.view.owner v:id=84qh-8fvb v:screenName="Christa Linton" v:displayName="Christa Linton"

property e:5umv-2u9m t:meta.view.tableauthor v:id=84qh-8fvb v:screenName="Christa Linton" v:roleName=editor v:displayName="Christa Linton"
```

## Top Records

```ls
| date                | month | fiscal_year         | expedited_fs_approved_cases_expedited_fs_cases_are_included_in_the_overall_active_fsp_cases_if_the_expedited_fs_cases_are_still_active_at_the_end_of_the_calendar_month | number_of_cases_in_food_supplement_program | number_of_customers_served_through_tca | month_year | 
| =================== | ===== | =================== | ======================================================================================================================================================================= | ========================================== | ====================================== | ========== | 
| 2011-05-31T00:00:00 | May   | 2011-01-01T00:00:00 | 9435                                                                                                                                                                    | 330786                                     | 28542                                  | May 2011   | 
| 2011-06-30T00:00:00 | Jun.  | 2011-01-01T00:00:00 | 10677                                                                                                                                                                   | 337265                                     | 28880                                  | Jun 2011   | 
| 2011-07-31T00:00:00 | Jul.  | 2011-01-01T00:00:00 | 10050                                                                                                                                                                   | 340941                                     | 29105                                  | Jul 2011   | 
| 2011-08-31T00:00:00 | Aug.  | 2011-01-01T00:00:00 | 11153                                                                                                                                                                   | 346926                                     | 28960                                  | Aug 2011   | 
| 2011-09-30T00:00:00 | Sep.  | 2011-01-01T00:00:00 | 10130                                                                                                                                                                   | 349277                                     | 28742                                  | Sep 2011   | 
| 2011-10-31T00:00:00 | Oct.  | 2011-01-01T00:00:00 | 9700                                                                                                                                                                    | 353242                                     | 29334                                  | Oct 2011   | 
| 2011-11-30T00:00:00 | Nov.  | 2011-01-01T00:00:00 | 9627                                                                                                                                                                    | 354110                                     | 28996                                  | Nov 2011   | 
| 2011-12-31T00:00:00 | Dec.  | 2011-01-01T00:00:00 | 9307                                                                                                                                                                    | 355278                                     | 29446                                  | Dec 2011   | 
| 2012-01-31T00:00:00 | Jan.  | 2012-01-01T00:00:00 | 10700                                                                                                                                                                   | 356557                                     | 28567                                  | Jan 2012   | 
| 2012-02-29T00:00:00 | Feb.  | 2012-01-01T00:00:00 | 9013                                                                                                                                                                    | 356682                                     | 27968                                  | Feb 2012   | 
```