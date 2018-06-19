# Children in Foster Care Annually: Beginning 1994

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/children-in-foster-care-annually-beginning-1994) |
| Metadata | [Link](https://data.ny.gov/api/views/hfc5-3hsu) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/hfc5-3hsu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/hfc5-3hsu/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | hfc5-3hsu |
| Name | Children in Foster Care Annually: Beginning 1994 |
| Attribution | Office of Children and Family Services |
| Category | Human Services |
| Tags | foster care, cps, foster home, group home |
| Created | 2014-05-19T16:46:34Z |
| Publication Date | 2016-06-07T14:43:56Z |

## Description

The purpose of this data set is to provide information on the total number of admissions, discharges, and children in foster care, the type of care, and total Child Protective Services (CPS) reports indicated during period.

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                          | Data Type | Render Type |
| ======== | ============== | ============================= | ============================= | ========= | =========== |
| Yes      | series tag     | county                        | County                        | text      | text        |
| Yes      | time           | year                          | Year                          | number    | number      |
| Yes      | numeric metric | adoptive_home                 | Adoptive Home                 | number    | number      |
| Yes      | numeric metric | agency_operated_boarding_home | Agency Operated Boarding Home | number    | number      |
| Yes      | numeric metric | approved_relative_home        | Approved Relative Home        | number    | number      |
| Yes      | numeric metric | foster_boarding_home          | Foster Boarding Home          | number    | number      |
| Yes      | numeric metric | group_home                    | Group Home                    | number    | number      |
| Yes      | numeric metric | group_residence               | Group Residence               | number    | number      |
| Yes      | numeric metric | institution                   | Institution                   | number    | number      |
| Yes      | numeric metric | supervised_independent_living | Supervised Independent Living | number    | number      |
| Yes      | numeric metric | other                         | Other                         | number    | number      |
| Yes      | numeric metric | total_days_in_care            | Total Days In Care            | number    | number      |
| Yes      | numeric metric | admissions                    | Admissions                    | number    | number      |
| Yes      | numeric metric | discharges                    | Discharges                    | number    | number      |
| Yes      | numeric metric | children_in_care              | Children In Care              | number    | number      |
| Yes      | numeric metric | number_of_children_served     | Number of Children Served     | number    | number      |
| Yes      | numeric metric | indicated_cps_reports         | Indicated CPS Reports         | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:hfc5-3hsu d:2015-01-01T00:00:00.000Z t:county=ALBANY m:number_of_children_served=333 m:children_in_care=181 m:other=755 m:agency_operated_boarding_home=284 m:adoptive_home=0 m:admissions=167 m:total_days_in_care=67179 m:group_home=5684 m:indicated_cps_reports=698 m:foster_boarding_home=36175 m:group_residence=1107 m:supervised_independent_living=1514 m:approved_relative_home=3692 m:institution=17968 m:discharges=159

series e:hfc5-3hsu d:2015-01-01T00:00:00.000Z t:county=ALLEGANY m:number_of_children_served=133 m:children_in_care=77 m:other=840 m:agency_operated_boarding_home=1058 m:adoptive_home=0 m:admissions=38 m:total_days_in_care=33980 m:group_home=258 m:indicated_cps_reports=137 m:foster_boarding_home=18961 m:group_residence=0 m:supervised_independent_living=0 m:approved_relative_home=7801 m:institution=5062 m:discharges=57

series e:hfc5-3hsu d:2015-01-01T00:00:00.000Z t:county=BROOME m:number_of_children_served=352 m:children_in_care=218 m:other=1104 m:agency_operated_boarding_home=0 m:adoptive_home=0 m:admissions=105 m:total_days_in_care=85766 m:group_home=8359 m:indicated_cps_reports=1015 m:foster_boarding_home=57545 m:group_residence=275 m:supervised_independent_living=3332 m:approved_relative_home=3150 m:institution=12001 m:discharges=143
```

## Meta Commands

```ls
metric m:adoptive_home p:integer l:"Adoptive Home" d:"This is the total number of care days provided for children in an adoptive home. Adoptive homes include adoptive and/or adoption subsidized homes." t:dataTypeName=number

metric m:agency_operated_boarding_home p:integer l:"Agency Operated Boarding Home" d:"This is the total number of care days provided for children in foster care residing in an Agency Operated Boarding Home." t:dataTypeName=number

metric m:approved_relative_home p:integer l:"Approved Relative Home" d:"This is the total number of care days provided for children in foster care residing with a relative. The relative has been approved as a foster parent." t:dataTypeName=number

metric m:foster_boarding_home p:integer l:"Foster Boarding Home" d:"This is the total number of care days provided for children in foster care residing in a regular non-relative foster home." t:dataTypeName=number

metric m:group_home p:integer l:"Group Home" d:"This is the total number of care days provided for children in foster care residing in a Congregate Care home." t:dataTypeName=number

metric m:group_residence p:integer l:"Group Residence" d:"This is the total number of care days provided for children in foster care residing in a group residence. These are also considered congregate care for youth." t:dataTypeName=number

metric m:institution p:integer l:Institution d:"This is the total number of care days provided for children in foster care residing in an Institution. This facility type is a larger facility for congregate care." t:dataTypeName=number

metric m:supervised_independent_living p:integer l:"Supervised Independent Living" d:"This is the total number of care days provided for children in foster care, but living on their own. These young adults have been approved by OCFS to live on their own." t:dataTypeName=number

metric m:other p:integer l:Other d:"This is the total number of care days provided for children in foster care residing in residential treatment facilities, skilled nursing facilities, specialized schools, etc." t:dataTypeName=number

metric m:total_days_in_care p:integer l:"Total Days In Care" d:"This is the total number of care days provided for children in foster care residing in all facility types." t:dataTypeName=number

metric m:admissions p:integer l:Admissions d:"Total children admitted to foster care in the calendar year." t:dataTypeName=number

metric m:discharges p:integer l:Discharges d:"Total number of children discharged from care during the calendar year." t:dataTypeName=number

metric m:children_in_care p:integer l:"Children In Care" d:"Total number of children in Foster Care on December 31 of the calendar year. This is point in time data." t:dataTypeName=number

metric m:number_of_children_served p:integer l:"Number of Children Served" d:"Total number of children served during the year. This includes children that were admitted in previous years as well as those admitted during the given year. As a result, this is usually higher than both admissions and point in time in care." t:dataTypeName=number

metric m:indicated_cps_reports p:integer l:"Indicated CPS Reports" d:"This is the total number of Child Protective Services (CPS) reports that are indicated for abuse/maltreatment during a calendar year." t:dataTypeName=number

entity e:hfc5-3hsu l:"Children in Foster Care Annually:  Beginning 1994" t:attribution="Office of Children and Family Services" t:url=https://data.ny.gov/api/views/hfc5-3hsu

property e:hfc5-3hsu t:meta.view v:id=hfc5-3hsu v:category="Human Services" v:attributionLink=http://ocfs.ny.gov/main/Professionals_data_reports.asp v:averageRating=0 v:name="Children in Foster Care Annually:  Beginning 1994" v:attribution="Office of Children and Family Services"

property e:hfc5-3hsu t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:hfc5-3hsu t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:hfc5-3hsu t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| county      | year | adoptive_home | agency_operated_boarding_home | approved_relative_home | foster_boarding_home | group_home | group_residence | institution | supervised_independent_living | other | total_days_in_care | admissions | discharges | children_in_care | number_of_children_served | indicated_cps_reports | 
| =========== | ==== | ============= | ============================= | ====================== | ==================== | ========== | =============== | =========== | ============================= | ===== | ================== | ========== | ========== | ================ | ========================= | ===================== | 
| ALBANY      | 2015 | 0             | 284                           | 3692                   | 36175                | 5684       | 1107            | 17968       | 1514                          | 755   | 67179              | 167        | 159        | 181              | 333                       | 698                   | 
| ALLEGANY    | 2015 | 0             | 1058                          | 7801                   | 18961                | 258        | 0               | 5062        | 0                             | 840   | 33980              | 38         | 57         | 77               | 133                       | 137                   | 
| BROOME      | 2015 | 0             | 0                             | 3150                   | 57545                | 8359       | 275             | 12001       | 3332                          | 1104  | 85766              | 105        | 143        | 218              | 352                       | 1015                  | 
| CATTARAUGUS | 2015 | 0             | 1102                          | 5047                   | 21843                | 967        | 443             | 7398        | 169                           | 10    | 36979              | 58         | 55         | 94               | 163                       | 420                   | 
| CAYUGA      | 2015 | 0             | 84                            | 1974                   | 20074                | 92         | 177             | 3440        | 122                           | 217   | 26180              | 47         | 58         | 65               | 120                       | 175                   | 
| CHAUTAUQUA  | 2015 | 0             | 0                             | 3249                   | 28529                | 1036       | 267             | 6105        | 0                             | 165   | 39351              | 110        | 98         | 112              | 218                       | 654                   | 
| CHEMUNG     | 2015 | 44            | 0                             | 2399                   | 22768                | 1434       | 72              | 4420        | 473                           | 371   | 31981              | 63         | 49         | 96               | 150                       | 473                   | 
| CHENANGO    | 2015 | 0             | 0                             | 247                    | 10768                | 167        | 0               | 1513        | 0                             | 3058  | 15753              | 39         | 21         | 55               | 73                        | 294                   | 
| CLINTON     | 2015 | 0             | 0                             | 1665                   | 30870                | 2166       | 0               | 5695        | 0                             | 730   | 41126              | 50         | 51         | 109              | 157                       | 242                   | 
| COLUMBIA    | 2015 | 0             | 0                             | 2713                   | 18943                | 1632       | 974             | 7157        | 660                           | 483   | 32562              | 35         | 45         | 79               | 131                       | 163                   | 
```