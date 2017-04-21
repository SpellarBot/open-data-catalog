# IPERS-Covered Wages and Contributions by Membership Group, Employer and FY

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ipers-covered-wages-and-contributions-by-membership-group-employer-and-fy) |
| Metadata | [Link](https://data.iowa.gov/api/views/xxuu-vrtq) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/xxuu-vrtq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/xxuu-vrtq/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | xxuu-vrtq |
| Name | IPERS-Covered Wages and Contributions by Membership Group, Employer and FY |
| Attribution | Iowa Public Employees' Retirement System |
| Category | Government |
| Tags | covered wages, employer contributions, employee contributions |
| Created | 2015-11-12T15:09:00Z |
| Publication Date | 2017-03-14T21:14:38Z |

## Description

The dataset contains information on IPERS-covered wages, employer contributions and employee contributions by membership group, employer and fiscal year.  An employer may have more than one membership group.  Count of employers is before modifications due to GASB 68.

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                   | Data Type | Render Type |
| ======== | ============== | ============================= | ====================== | ========= | =========== |
| Yes      | time           | financial_year                | Fiscal Year            | number    | number      |
| Yes      | series tag     | employer_code                 | Employer Code          | text      | number      |
| Yes      | series tag     | membership_group              | Membership Group       | text      | text        |
| Yes      | series tag     | employer_type                 | Employer Type          | text      | text        |
| Yes      | series tag     | employer_name                 | Employer Name          | text      | text        |
| No       |                | employer_location             | Address                | text      | text        |
| Yes      | series tag     | city                          | City                   | text      | text        |
| Yes      | series tag     | state                         | State                  | text      | text        |
| Yes      | series tag     | zip_code                      | Zip Code               | text      | text        |
| Yes      | series tag     | county_fips                   | County FIPS            | text      | text        |
| Yes      | series tag     | county_name                   | County Name            | text      | text        |
| Yes      | numeric metric | covered_wages_by_grp          | Covered Wages          | money     | money       |
| Yes      | numeric metric | employer_contributions_by_grp | Employer Contributions | money     | money       |
| Yes      | numeric metric | employee_contributions_by_grp | Employee Contributions | money     | money       |
```

## Time Field

```ls
Value = financial_year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = employer_location
```

## Data Commands

```ls
series e:xxuu-vrtq d:2015-01-01T00:00:00.000Z t:membership_group=Regular t:employer_code=109 t:county_fips=19095 t:zip_code=52236 t:employer_name="REGIONAL ENVIRONMENTAL IMPROVEMENT COMM (REIC)" t:state=IA t:county_name=IOWA t:employer_type=Other t:city=HOMESTEAD m:employer_contributions_by_grp=20971.25 m:covered_wages_by_grp=234840.39 m:employee_contributions_by_grp=13973.01

series e:xxuu-vrtq d:2015-01-01T00:00:00.000Z t:membership_group=Regular t:employer_code=110 t:county_fips=19003 t:zip_code=50841 t:employer_name="ADAMS COUNTY SOIL & WATER CONSERVATION" t:state=IA t:county_name=ADAMS t:employer_type=Counties t:city=CORNING m:employer_contributions_by_grp=1142.17 m:covered_wages_by_grp=12790.25 m:employee_contributions_by_grp=761.03

series e:xxuu-vrtq d:2015-01-01T00:00:00.000Z t:membership_group=Regular t:employer_code=116 t:county_fips=19001 t:zip_code=50849 t:employer_name="ADAIR CO SOIL & WATER CONSERVATION DIST" t:state=IA t:county_name=ADAIR t:employer_type=Counties t:city=GREENFIELD m:employer_contributions_by_grp=2812.12 m:covered_wages_by_grp=31490.88 m:employee_contributions_by_grp=1873.71
```

## Meta Commands

```ls
metric m:covered_wages_by_grp p:double l:"Covered Wages" d:"Sum of covered wages within membership group and employer for the fiscal year." t:dataTypeName=money

metric m:employer_contributions_by_grp p:double l:"Employer Contributions" d:"Sum of employer contributions during fiscal year for employees within the membership group" t:dataTypeName=money

metric m:employee_contributions_by_grp p:double l:"Employee Contributions" d:"Sum of employee contributions within membership group for the fiscal year." t:dataTypeName=money

entity e:xxuu-vrtq l:"IPERS-Covered Wages and Contributions by Membership Group, Employer and FY" t:attribution="Iowa Public Employees' Retirement System" t:url=https://data.iowa.gov/api/views/xxuu-vrtq

property e:xxuu-vrtq t:meta.view v:id=xxuu-vrtq v:category=Government v:averageRating=0 v:name="IPERS-Covered Wages and Contributions by Membership Group, Employer and FY" v:attribution="Iowa Public Employees' Retirement System"

property e:xxuu-vrtq t:meta.view.license v:name="Public Domain"

property e:xxuu-vrtq t:meta.view.owner v:id=3qea-rfi2 v:profileImageUrlMedium=/api/users/3qea-rfi2/profile_images/THUMB v:profileImageUrlLarge=/api/users/3qea-rfi2/profile_images/LARGE v:screenName="Iowa Public Employees' Retirement System" v:profileImageUrlSmall=/api/users/3qea-rfi2/profile_images/TINY v:displayName="Iowa Public Employees' Retirement System"

property e:xxuu-vrtq t:meta.view.tableauthor v:id=3qea-rfi2 v:profileImageUrlMedium=/api/users/3qea-rfi2/profile_images/THUMB v:profileImageUrlLarge=/api/users/3qea-rfi2/profile_images/LARGE v:screenName="Iowa Public Employees' Retirement System" v:profileImageUrlSmall=/api/users/3qea-rfi2/profile_images/TINY v:roleName=editor v:displayName="Iowa Public Employees' Retirement System"
```

## Top Records

```ls
| financial_year | employer_code | membership_group | employer_type | employer_name                                  | employer_location            | city           | state | zip_code | county_fips | county_name | covered_wages_by_grp | employer_contributions_by_grp | employee_contributions_by_grp | 
| ============== | ============= | ================ | ============= | ============================================== | ============================ | ============== | ===== | ======== | =========== | =========== | ==================== | ============================= | ============================= | 
| 2015           | 109           | Regular          | Other         | REGIONAL ENVIRONMENTAL IMPROVEMENT COMM (REIC) | 3369 HWY 6 TRAIL             | HOMESTEAD      | IA    | 52236    | 19095       | IOWA        | 234840.39            | 20971.25                      | 13973.01                      | 
| 2015           | 110           | Regular          | Counties      | ADAMS COUNTY SOIL & WATER CONSERVATION         | 2243 LOOMIS AVENUE EXT STE 2 | CORNING        | IA    | 50841    | 19003       | ADAMS       | 12790.25             | 1142.17                       | 761.03                        | 
| 2015           | 116           | Regular          | Counties      | ADAIR CO SOIL & WATER CONSERVATION DIST        | 705 NE 6TH ST STE E          | GREENFIELD     | IA    | 50849    | 19001       | ADAIR       | 31490.88             | 2812.12                       | 1873.71                       | 
| 2015           | 132           | Regular          | Counties      | FREMONT COUNTY SOIL & WATER CONS DIST          | 610 CASS ST                  | SIDNEY         | IA    | 51652    | 19071       | FREMONT     | 21810.29             | 1947.67                       | 1297.72                       | 
| 2015           | 137           | Regular          | Cities        | CITY OF WESTWOOD                               | 3952 SYCAMORE DRIVE          | MOUNT PLEASANT | IA    | 52641    | 19087       | HENRY       | 3420.00              | 305.39                        | 203.52                        | 
| 2015           | 298           | Regular          | Counties      | HANCOCK SOIL & WATER CONSERVATION DIST         | 255 HIGHWAY 69 STE 1         | GARNER         | IA    | 50438    | 19081       | HANCOCK     | 44087.10             | 3937.00                       | 2623.18                       | 
| 2015           | 321           | Regular          | Education     | GEORGE-LITTLE ROCK COMMUNITY SCHOOL            | 500 E INDIANA AVE            | GEORGE         | IA    | 51237    | 19119       | LYON        | 2842101.16           | 253799.53                     | 169104.95                     | 
| 2015           | 324           | Regular          | Utilities     | MONONA COUNTY SANITARY LANDFILL                | 31342 HIGHWAY 37             | TURIN          | IA    | 51040    | 19133       | MONONA      | 146489.15            | 13081.45                      | 8716.11                       | 
| 2015           | 330           | Regular          | Education     | SOUTHEAST WEBSTER-GRAND COMMUNITY SCHOOL       | 30850 PARAGON AVE            | BURNSIDE       | IA    | 50521    | 19187       | WEBSTER     | 3499918.09           | 312543.01                     | 208245.26                     | 
| 2015           | 4207          | Regular          | Counties      | APPANOOSE CO SECONDARY RD DEPT                 | 1200 W HIGHWAY 2             | CENTERVILLE    | IA    | 52544    | 19007       | APPANOOSE   | 1097901.05           | 98042.63                      | 65325.10                      | 
```