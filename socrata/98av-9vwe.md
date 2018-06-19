# Budget Management - Department General Fund 2012 Year End Expenses And 2013 Preliminary Estimates

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/budget-management-department-general-fund-2012-year-end-expenses-and-2013-preliminary-esti-0ab4a) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/98av-9vwe) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/98av-9vwe/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/98av-9vwe/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | 98av-9vwe |
| Name | Budget Management - Department General Fund 2012 Year End Expenses And 2013 Preliminary Estimates |
| Attribution | Cook County Department of Budget and Management Services |
| Category | Finance & Administration |
| Created | 2012-09-04T17:44:24Z |
| Publication Date | 2014-10-09T21:22:19Z |

## Columns

```ls
| Included | Schema Type    | Field Name                            | Name                                       | Data Type | Render Type |
| ======== | ============== | ===================================== | ========================================== | ========= | =========== |
| Yes      | series tag     | department_no                         | Department No.                             | text      | number      |
| Yes      | series tag     | description                           | Description                                | text      | text        |
| Yes      | numeric metric | approved_adopted                      | Approved & Adopted                         | number    | number      |
| Yes      | numeric metric | projected_adjusted_appropriation      | Projected Adjusted Appropriation*          | number    | number      |
| Yes      | numeric metric | expenditures_and_encumbrances_dec_may | Expenditures and Encumbrances, Dec - May** | number    | number      |
| Yes      | numeric metric | estimated_expenditures_jun_nov        | Estimated Expenditures Jun - Nov           | number    | number      |
| Yes      | numeric metric | total_2012_projected_expenditures     | Total 2012 Projected Expenditures          | number    | number      |
| Yes      | series tag     | department_2013_preliminary_estimate  | Department 2013 Preliminary Estimate       | text      | number      |
| Yes      | numeric metric | executive_2013_preliminary_estimate   | Executive 2013 Preliminary Estimate        | number    | number      |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:98av-9vwe d:2012-01-01T00:00:00.000Z t:description="Department of Human Rights, Ethics, Women's Issues" t:department_2013_preliminary_estimate=888657 t:department_no=2 m:expenditures_and_encumbrances_dec_may=371283 m:executive_2013_preliminary_estimate=888657 m:total_2012_projected_expenditures=735469 m:approved_adopted=776305 m:projected_adjusted_appropriation=779878 m:estimated_expenditures_jun_nov=364186

series e:98av-9vwe d:2012-01-01T00:00:00.000Z t:description=Revenue t:department_2013_preliminary_estimate=2552705 t:department_no=7 m:expenditures_and_encumbrances_dec_may=1332782 m:executive_2013_preliminary_estimate=2552705 m:total_2012_projected_expenditures=2166525 m:approved_adopted=2443424 m:projected_adjusted_appropriation=2441021 m:estimated_expenditures_jun_nov=833743

series e:98av-9vwe d:2012-01-01T00:00:00.000Z t:description="Risk Management" t:department_2013_preliminary_estimate=1065167 t:department_no=8 m:expenditures_and_encumbrances_dec_may=729059 m:executive_2013_preliminary_estimate=1065167 m:total_2012_projected_expenditures=812860 m:approved_adopted=827214 m:projected_adjusted_appropriation=833474 m:estimated_expenditures_jun_nov=83801
```

## Meta Commands

```ls
metric m:approved_adopted p:long l:"Approved & Adopted" t:dataTypeName=number

metric m:projected_adjusted_appropriation p:long l:"Projected Adjusted Appropriation*" t:dataTypeName=number

metric m:expenditures_and_encumbrances_dec_may p:integer l:"Expenditures and Encumbrances, Dec - May**" t:dataTypeName=number

metric m:estimated_expenditures_jun_nov p:integer l:"Estimated Expenditures Jun - Nov" t:dataTypeName=number

metric m:total_2012_projected_expenditures p:long l:"Total 2012 Projected Expenditures" t:dataTypeName=number

metric m:executive_2013_preliminary_estimate p:long l:"Executive 2013 Preliminary Estimate" t:dataTypeName=number

entity e:98av-9vwe l:"Budget Management - Department General Fund 2012 Year End Expenses And 2013 Preliminary Estimates" t:attribution="Cook County Department of Budget and Management Services" t:url=https://datacatalog.cookcountyil.gov/api/views/98av-9vwe

property e:98av-9vwe t:meta.view v:id=98av-9vwe v:category="Finance & Administration" v:attributionLink=http://home.cookcountyil.gov/budget/ v:averageRating=0 v:name="Budget Management - Department General Fund 2012 Year End Expenses And 2013 Preliminary Estimates" v:attribution="Cook County Department of Budget and Management Services"

property e:98av-9vwe t:meta.view.license v:name="Public Domain"

property e:98av-9vwe t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:98av-9vwe t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| department_no | description                                           | approved_adopted | projected_adjusted_appropriation | expenditures_and_encumbrances_dec_may | estimated_expenditures_jun_nov | total_2012_projected_expenditures | department_2013_preliminary_estimate | executive_2013_preliminary_estimate | 
| ============= | ===================================================== | ================ | ================================ | ===================================== | ============================== | ================================= | ==================================== | =================================== | 
| 2             | Department of Human Rights, Ethics, Women's Issues    | 776305           | 779878                           | 371283                                | 364186                         | 735469                            | 888657                               | 888657                              | 
| 7             | Revenue                                               | 2443424          | 2441021                          | 1332782                               | 833743                         | 2166525                           | 2552705                              | 2552705                             | 
| 8             | Risk Management                                       | 827214           | 833474                           | 729059                                | 83801                          | 812860                            | 1065167                              | 1065167                             | 
| 9             | Technology Policy and Planning                        | 4949301          | 5064852                          | 2425823                               | 3361645                        | 5787468                           | 4210468                              | 4210468                             | 
| 10            | Office of the President                               | 1611196          | 1610539                          | 672992                                | 557759                         | 1230751                           | 1658725                              | 1658725                             | 
| 11            | Office of the Chief Administrative Officer            | 2570975          | 2724515                          | 1753878                               | 959061                         | 2712938                           | 2752492                              | 2752492                             | 
| 13            | Planning and Development                              | 314882           | 320809                           | 201627                                | 70856                          | 272483                            | 500358                               | 500358                              | 
| 14            | Budget and Management Services                        | 1154277          | 1186393                          | 580694                                | 605307                         | 1186000                           | 1403492                              | 1403492                             | 
| 16            | IT Solutions & Services                               | 5063644          | 5117409                          | 2252503                               | 2400783                        | 4653286                           | 6716125                              | 6716125                             | 
| 18            | Office of the Secretary to the Board of Commissioners | 1037415          | 1039436                          | 519403                                | 419454                         | 938857                            | 1201101                              | 1201101                             | 
```