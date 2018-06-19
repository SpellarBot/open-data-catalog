# Office Of Community Beautification - Graffiti Removal Totals And Response Rates - GOVSTAT

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/office-of-community-beautification-graffiti-removal-totals-and-response-rates-govstat-33065) |
| Metadata | [Link](https://data.lacity.org/api/views/gkcu-pvq9) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/gkcu-pvq9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/gkcu-pvq9/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | gkcu-pvq9 |
| Name | Office Of Community Beautification - Graffiti Removal Totals And Response Rates - GOVSTAT |
| Attribution | Office of Community Beautification |
| Tags | graffiti, office of community beautification, public works, cleanup, removal, response, 311, tagging, vandalism |
| Created | 2014-05-30T21:46:29Z |
| Publication Date | 2014-05-30T21:54:59Z |

## Description

Monthly figures for total square feet of graffiti removal and response times for requests through 311 or online.

## Columns

```ls
| Included | Schema Type    | Field Name                                | Name                                          | Data Type     | Render Type   |
| ======== | ============== | ========================================= | ============================================= | ============= | ============= |
| Yes      | series tag     | month_year                                | Month-Year                                    | text          | text          |
| Yes      | time           | date                                      | Date                                          | calendar_date | calendar_date |
| Yes      | numeric metric | square_ft_removed                         | Square Ft. Removed                            | number        | number        |
| Yes      | numeric metric | of_locations                              | # of Locations                                | number        | number        |
| Yes      | numeric metric | of_locations_requested_through_311_online | # of locations requested through 311 & online | number        | number        |
| Yes      | numeric metric | requested_through_311_online              | % requested through 311 & online              | percent       | percent       |
| Yes      | numeric metric | of_requests_completed_within_24_hrs       | # of requests completed within 24 hrs         | number        | number        |
| Yes      | numeric metric | requests_completed_within_24_hrs          | % requests completed within 24 hrs            | percent       | percent       |
| Yes      | numeric metric | of_requests_completed_within_24_48_hrs    | # of requests completed within 24-48 hrs      | number        | number        |
| Yes      | numeric metric | requests_completed_within_24_48_hrs       | % requests completed within 24-48 hrs         | percent       | percent       |
| Yes      | numeric metric | of_requests_completed_within_48_72_hrs    | # of requests completed within 48-72 hrs      | number        | number        |
| Yes      | numeric metric | requests_completed_within_48_72_hrs       | % requests completed within 48-72 hrs         | percent       | percent       |
| Yes      | numeric metric | of_requests_completed_within_4_7_days     | # of requests completed within 4-7 days       | number        | number        |
| Yes      | numeric metric | requests_completed_within_4_7_days        | % requests completed within 4-7 days          | percent       | percent       |
| Yes      | numeric metric | of_requests_completed_within_8_15_days    | # of requests completed within 8-15 days      | number        | number        |
| Yes      | numeric metric | requests_completed_8_15_days              | % requests completed 8-15 days                | percent       | percent       |
| Yes      | numeric metric | of_requests_completed_in_over_15_days     | # of requests completed in over 15 days       | number        | number        |
| Yes      | numeric metric | requests_completed_in_over_15_days        | % requests completed in over 15 days          | percent       | percent       |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:gkcu-pvq9 d:2013-04-30T00:00:00.000Z t:month_year=Apr-13 m:requests_completed_within_24_hrs=60.1 m:requests_completed_within_24_48_hrs=11.1 m:of_locations=51867 m:requested_through_311_online=17.4 m:requests_completed_within_4_7_days=13 m:requests_completed_within_48_72_hrs=6.2 m:of_requests_completed_within_8_15_days=725 m:of_requests_completed_within_24_hrs=5427 m:requests_completed_8_15_days=8 m:of_requests_completed_in_over_15_days=156 m:square_ft_removed=2482193 m:requests_completed_in_over_15_days=1.7 m:of_requests_completed_within_4_7_days=1172 m:of_requests_completed_within_48_72_hrs=556 m:of_locations_requested_through_311_online=9036 m:of_requests_completed_within_24_48_hrs=1000

series e:gkcu-pvq9 d:2013-05-31T00:00:00.000Z t:month_year=May-13 m:requests_completed_within_24_hrs=56.6 m:requests_completed_within_24_48_hrs=9.1 m:of_locations=30715 m:requested_through_311_online=28.8 m:requests_completed_within_4_7_days=19.1 m:requests_completed_within_48_72_hrs=7.8 m:of_requests_completed_within_8_15_days=499 m:of_requests_completed_within_24_hrs=5011 m:requests_completed_8_15_days=5.6 m:of_requests_completed_in_over_15_days=147 m:square_ft_removed=2151358 m:requests_completed_in_over_15_days=1.7 m:of_requests_completed_within_4_7_days=1695 m:of_requests_completed_within_48_72_hrs=695 m:of_locations_requested_through_311_online=8857 m:of_requests_completed_within_24_48_hrs=810

series e:gkcu-pvq9 d:2013-06-30T00:00:00.000Z t:month_year=Jun-13 m:requests_completed_within_24_hrs=59.9 m:requests_completed_within_24_48_hrs=11.9 m:of_locations=42458 m:requested_through_311_online=20.4 m:requests_completed_within_4_7_days=14.5 m:requests_completed_within_48_72_hrs=7.6 m:of_requests_completed_within_8_15_days=347 m:of_requests_completed_within_24_hrs=5184 m:requests_completed_8_15_days=4 m:of_requests_completed_in_over_15_days=188 m:square_ft_removed=2037298 m:requests_completed_in_over_15_days=2.2 m:of_requests_completed_within_4_7_days=1255 m:of_requests_completed_within_48_72_hrs=655 m:of_locations_requested_through_311_online=8656 m:of_requests_completed_within_24_48_hrs=1027
```

## Meta Commands

```ls
metric m:square_ft_removed p:integer l:"Square Ft. Removed" t:dataTypeName=number

metric m:of_locations p:integer l:"# of Locations" t:dataTypeName=number

metric m:of_locations_requested_through_311_online p:integer l:"# of locations requested through 311 & online" t:dataTypeName=number

metric m:requested_through_311_online p:float l:"% requested through 311 & online" t:dataTypeName=percent

metric m:of_requests_completed_within_24_hrs p:integer l:"# of requests completed within 24 hrs" t:dataTypeName=number

metric m:requests_completed_within_24_hrs p:float l:"% requests completed within 24 hrs" t:dataTypeName=percent

metric m:of_requests_completed_within_24_48_hrs p:integer l:"# of requests completed within 24-48 hrs" t:dataTypeName=number

metric m:requests_completed_within_24_48_hrs p:float l:"% requests completed within 24-48 hrs" t:dataTypeName=percent

metric m:of_requests_completed_within_48_72_hrs p:integer l:"# of requests completed within 48-72 hrs" t:dataTypeName=number

metric m:requests_completed_within_48_72_hrs p:float l:"% requests completed within 48-72 hrs" t:dataTypeName=percent

metric m:of_requests_completed_within_4_7_days p:integer l:"# of requests completed within 4-7 days" t:dataTypeName=number

metric m:requests_completed_within_4_7_days p:float l:"% requests completed within 4-7 days" t:dataTypeName=percent

metric m:of_requests_completed_within_8_15_days p:integer l:"# of requests completed within 8-15 days" t:dataTypeName=number

metric m:requests_completed_8_15_days p:double l:"% requests completed 8-15 days" t:dataTypeName=percent

metric m:of_requests_completed_in_over_15_days p:integer l:"# of requests completed in over 15 days" t:dataTypeName=number

metric m:requests_completed_in_over_15_days p:float l:"% requests completed in over 15 days" t:dataTypeName=percent

entity e:gkcu-pvq9 l:"Office Of Community Beautification - Graffiti Removal Totals And Response Rates - GOVSTAT" t:attribution="Office of Community Beautification" t:url=https://data.lacity.org/api/views/gkcu-pvq9

property e:gkcu-pvq9 t:meta.view v:id=gkcu-pvq9 v:attributionLink=http://www.laocb.org/ v:averageRating=0 v:name="Office Of Community Beautification - Graffiti Removal Totals And Response Rates - GOVSTAT" v:attribution="Office of Community Beautification"

property e:gkcu-pvq9 t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:gkcu-pvq9 t:meta.view.owner v:id=tgn6-4379 v:profileImageUrlMedium=/api/users/tgn6-4379/profile_images/THUMB v:profileImageUrlLarge=/api/users/tgn6-4379/profile_images/LARGE v:screenName="Mayor's Office OpenData" v:profileImageUrlSmall=/api/users/tgn6-4379/profile_images/TINY v:displayName="Mayor's Office OpenData"

property e:gkcu-pvq9 t:meta.view.tableauthor v:id=tgn6-4379 v:profileImageUrlMedium=/api/users/tgn6-4379/profile_images/THUMB v:profileImageUrlLarge=/api/users/tgn6-4379/profile_images/LARGE v:screenName="Mayor's Office OpenData" v:profileImageUrlSmall=/api/users/tgn6-4379/profile_images/TINY v:roleName=administrator v:displayName="Mayor's Office OpenData"
```

## Top Records

```ls
| month_year | date                | square_ft_removed | of_locations | of_locations_requested_through_311_online | requested_through_311_online | of_requests_completed_within_24_hrs | requests_completed_within_24_hrs | of_requests_completed_within_24_48_hrs | requests_completed_within_24_48_hrs | of_requests_completed_within_48_72_hrs | requests_completed_within_48_72_hrs | of_requests_completed_within_4_7_days | requests_completed_within_4_7_days | of_requests_completed_within_8_15_days | requests_completed_8_15_days | of_requests_completed_in_over_15_days | requests_completed_in_over_15_days | 
| ========== | =================== | ================= | ============ | ========================================= | ============================ | =================================== | ================================ | ====================================== | =================================== | ====================================== | =================================== | ===================================== | ================================== | ====================================== | ============================ | ===================================== | ================================== | 
| Apr-13     | 2013-04-30T00:00:00 | 2482193           | 51867        | 9036                                      | 17.4                         | 5427                                | 60.1                             | 1000                                   | 11.1                                | 556                                    | 6.2                                 | 1172                                  | 13                                 | 725                                    | 8                            | 156                                   | 1.7                                | 
| May-13     | 2013-05-31T00:00:00 | 2151358           | 30715        | 8857                                      | 28.8                         | 5011                                | 56.6                             | 810                                    | 9.1                                 | 695                                    | 7.8                                 | 1695                                  | 19.1                               | 499                                    | 5.6                          | 147                                   | 1.7                                | 
| Jun-13     | 2013-06-30T00:00:00 | 2037298           | 42458        | 8656                                      | 20.4                         | 5184                                | 59.9                             | 1027                                   | 11.9                                | 655                                    | 7.6                                 | 1255                                  | 14.5                               | 347                                    | 4                            | 188                                   | 2.2                                | 
| Jul-13     | 2013-07-31T00:00:00 | 2292272           | 46096        | 9434                                      | 20.5                         | 5408                                | 57.3                             | 993                                    | 10.5                                | 719                                    | 7.6                                 | 1764                                  | 18.7                               | 304                                    | 3.2                          | 246                                   | 2.6                                | 
| Aug-13     | 2013-08-31T00:00:00 | 2619763           | 43061        | 8752                                      | 20.3                         | 5283                                | 60.4                             | 790                                    | 9                                   | 531                                    | 6.1                                 | 1487                                  | 17                                 | 489                                    | 5.6                          | 172                                   | 2                                  | 
| Sep-13     | 2013-09-30T00:00:00 | 2524054           | 44253        | 7814                                      | 17.7                         | 3816                                | 48.8                             | 2574                                   | 32.9                                | 552                                    | 7.1                                 | 686                                   | 8.8                                | 113                                    | 1.4                          | 73                                    | 0.9                                | 
| Oct-13     | 2013-10-31T00:00:00 | 2363098           | 42046        | 7422                                      | 17.7                         | 4055                                | 54.6                             | 2466                                   | 33.2                                | 409                                    | 5.5                                 | 405                                   | 5.5                                | 67                                     | 0.9                          | 20                                    | 0.3                                | 
| Nov-13     | 2013-11-30T00:00:00 | 2497051           | 42043        | 6983                                      | 16.6                         | 4406                                | 63.1                             | 1027                                   | 14.7                                | 597                                    | 8.5                                 | 726                                   | 10.4                               | 212                                    | 3                            | 15                                    | 0.2                                | 
| Dec-13     | 2013-12-31T00:00:00 | 2675894           | 41148        | 7399                                      | 18                           | 4950                                | 66.9                             | 957                                    | 12.9                                | 566                                    | 7.6                                 | 773                                   | 10.4                               | 143                                    | 1.9                          | 10                                    | 0.1                                | 
| Jan-14     | 2013-01-31T00:00:00 | 3097760           | 42924        | 8990                                      | 20.9                         | 5895                                | 65.6                             | 1072                                   | 11.9                                | 636                                    | 7.1                                 | 934                                   | 10.4                               | 435                                    | 4.8                          | 18                                    | 0.2                                | 
```