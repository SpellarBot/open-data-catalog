# State of Iowa - Monthly Voter Registration Totals by County

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-of-iowa-monthly-voter-registration-totals-by-county) |
| Metadata | [Link](https://data.iowa.gov/api/views/cp55-uurs) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/cp55-uurs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/cp55-uurs/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | cp55-uurs |
| Name | State of Iowa - Monthly Voter Registration Totals by County |
| Attribution | Iowa Secretary of State, Monthly Voter Registration Totals, Report VR-019 |
| Category | Communities & People |
| Tags | voters, registrations, democrat, republican, libertarian |
| Created | 2015-03-06T13:39:01Z |
| Publication Date | 2017-03-01T21:43:00Z |

## Description

This dataset contains voter registration data by month and county starting with January 2000.  It identifies the number of voters registered as Democrats, Republicans, other party or no party.  Beginning March 2017, Libertarians were reported separately.   The dataset also identifies the number of active and inactive voter registrations.  Inactive voters are those to whom official mailings have been sent from the county auditor?s office, the notice was returned as undeliverable by the United States Postal Service and the voter has not responded to a follow up confirmation notice. [?48A.37]

## Columns

```ls
| Included | Schema Type    | Field Name        | Name                   | Data Type     | Render Type   |
| ======== | ============== | ================= | ====================== | ============= | ============= |
| Yes      | time           | date              | Date                   | calendar_date | calendar_date |
| Yes      | series tag     | fips              | FIPS                   | text          | text          |
| Yes      | series tag     | county            | County                 | text          | text          |
| Yes      | numeric metric | dem_active        | Democrat - Active      | number        | number        |
| Yes      | numeric metric | rep_active        | Republican - Active    | number        | number        |
| Yes      | numeric metric | lib_active        | Libertarian - Active   | number        | number        |
| Yes      | numeric metric | no_party_active   | No Party - Active      | number        | number        |
| Yes      | numeric metric | other_active      | Other - Active         | number        | number        |
| Yes      | numeric metric | total_active      | Total - Active         | number        | number        |
| Yes      | numeric metric | dem_inactive      | Democrat - Inactive    | number        | number        |
| Yes      | numeric metric | rep_inactive      | Republican - Inactive  | number        | number        |
| Yes      | numeric metric | lib_inactive      | Libertarian - Inactive | number        | number        |
| Yes      | numeric metric | no_party_inactive | No Party - Inactive    | number        | number        |
| Yes      | numeric metric | other_inactive    | Other - Inactive       | number        | number        |
| Yes      | numeric metric | total_inactive    | Total - Inactive       | number        | number        |
| Yes      | numeric metric | grand_total       | Grand Total            | number        | number        |
| No       |                | primary_lat_dec   | Primary Lat Dec        | number        | number        |
| No       |                | primary_long_dec  | Primary Long Dec       | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = primary_lat_dec,primary_long_dec
```

## Data Commands

```ls
series e:cp55-uurs d:2015-03-01T00:00:00.000Z t:county=Adair t:fips=19001 m:total_active=4987 m:rep_inactive=61 m:no_party_active=2032 m:total_inactive=284 m:rep_active=1906 m:dem_active=1041 m:no_party_inactive=157 m:dem_inactive=66 m:grand_total=5271 m:other_active=8 m:other_inactive=0

series e:cp55-uurs d:2015-03-01T00:00:00.000Z t:county=Adams t:fips=19003 m:total_active=2741 m:rep_inactive=29 m:no_party_active=1165 m:total_inactive=156 m:rep_active=965 m:dem_active=608 m:no_party_inactive=100 m:dem_inactive=27 m:grand_total=2897 m:other_active=3 m:other_inactive=0

series e:cp55-uurs d:2015-03-01T00:00:00.000Z t:county=Allamakee t:fips=19005 m:total_active=9530 m:rep_inactive=122 m:no_party_active=3192 m:total_inactive=416 m:rep_active=4196 m:dem_active=2132 m:no_party_inactive=192 m:dem_inactive=102 m:grand_total=9946 m:other_active=10 m:other_inactive=0
```

## Meta Commands

```ls
metric m:dem_active p:integer l:"Democrat - Active" d:"Number of active Democrat registrations for month and county" t:dataTypeName=number

metric m:rep_active p:integer l:"Republican - Active" d:"Number of active Republican registrations for month and county" t:dataTypeName=number

metric m:lib_active p:integer l:"Libertarian - Active" d:"Number of active Libertarian registrations for month and county. Started reporting separately March 2017. Before March 2017, they were included in ""Other - Active""." t:dataTypeName=number

metric m:no_party_active p:integer l:"No Party - Active" d:"Number of active registrations for month and county with no party affiliation." t:dataTypeName=number

metric m:other_active p:integer l:"Other - Active" d:"Number of active registrations for month and county affiliated with a political party other than Democrat or Republican" t:dataTypeName=number

metric m:total_active p:integer l:"Total - Active" d:"Number of active registrations for month and county" t:dataTypeName=number

metric m:dem_inactive p:integer l:"Democrat - Inactive" d:"Number of inactive Democrat registrations for month and county. Inactive voters are those to whom official mailings have been sent from the county auditor?s office, the notice was returned as undeliverable by the United States Postal Service and the voter has not responded to a follow up confirmation notice. [?48A.37]" t:dataTypeName=number

metric m:rep_inactive p:integer l:"Republican - Inactive" d:"Number of inactive Republican registrations for month and county. Inactive voters are those to whom official mailings have been sent from the county auditor?s office, the notice was returned as undeliverable by the United States Postal Service and the voter has not responded to a follow up confirmation notice. [?48A.37]" t:dataTypeName=number

metric m:lib_inactive p:integer l:"Libertarian - Inactive" d:"Number of inactive Libertarian registrations for month and county. Inactive voters are those to whom official mailings have been sent from the county auditor?s office, the notice was returned as undeliverable by the United States Postal Service and the voter has not responded to a follow up confirmation notice. [?48A.37]. Started reporting separately March 2017. Before March 2017, they were included in ""Other - Inactive""." t:dataTypeName=number

metric m:no_party_inactive p:integer l:"No Party - Inactive" d:"Number of inactive registrations for month and county with no political party affiliation. Inactive voters are those to whom official mailings have been sent from the county auditor?s office, the notice was returned as undeliverable by the United States Postal Service and the voter has not responded to a follow up confirmation notice. [?48A.37]" t:dataTypeName=number

metric m:other_inactive p:integer l:"Other - Inactive" d:"Number of inactive registrations for month and county affiliated with a political party other than Democrat or Republican. Inactive voters are those to whom official mailings have been sent from the county auditor?s office, the notice was returned as undeliverable by the United States Postal Service and the voter has not responded to a follow up confirmation notice. [?48A.37]" t:dataTypeName=number

metric m:total_inactive p:integer l:"Total - Inactive" d:"Number of inactive registrations for month and county. Inactive voters are those to whom official mailings have been sent from the county auditor?s office, the notice was returned as undeliverable by the United States Postal Service and the voter has not responded to a follow up confirmation notice. [?48A.37]" t:dataTypeName=number

metric m:grand_total p:integer l:"Grand Total" d:"Number of active and inactive voter registration totals for month and county" t:dataTypeName=number

entity e:cp55-uurs l:"State of Iowa - Monthly Voter Registration Totals by County" t:attribution="Iowa Secretary of State, Monthly Voter Registration Totals, Report VR-019" t:url=https://data.iowa.gov/api/views/cp55-uurs

property e:cp55-uurs t:meta.view v:id=cp55-uurs v:category="Communities & People" v:averageRating=0 v:name="State of Iowa - Monthly Voter Registration Totals by County" v:attribution="Iowa Secretary of State, Monthly Voter Registration Totals, Report VR-019"

property e:cp55-uurs t:meta.view.owner v:id=pm4d-54qc v:profileImageUrlMedium=/api/users/pm4d-54qc/profile_images/THUMB v:profileImageUrlLarge=/api/users/pm4d-54qc/profile_images/LARGE v:screenName="Iowa Secretary of State" v:profileImageUrlSmall=/api/users/pm4d-54qc/profile_images/TINY v:displayName="Iowa Secretary of State"

property e:cp55-uurs t:meta.view.tableauthor v:id=pm4d-54qc v:profileImageUrlMedium=/api/users/pm4d-54qc/profile_images/THUMB v:profileImageUrlLarge=/api/users/pm4d-54qc/profile_images/LARGE v:screenName="Iowa Secretary of State" v:profileImageUrlSmall=/api/users/pm4d-54qc/profile_images/TINY v:roleName=editor v:displayName="Iowa Secretary of State"
```

## Top Records

```ls
| date                | fips  | county     | dem_active | rep_active | lib_active | no_party_active | other_active | total_active | dem_inactive | rep_inactive | lib_inactive | no_party_inactive | other_inactive | total_inactive | grand_total | primary_lat_dec | primary_long_dec | 
| =================== | ===== | ========== | ========== | ========== | ========== | =============== | ============ | ============ | ============ | ============ | ============ | ================= | ============== | ============== | =========== | =============== | ================ | 
| 2015-03-01T00:00:00 | 19001 | Adair      | 1041       | 1906       |            | 2032            | 8            | 4987         | 66           | 61           |              | 157               | 0              | 284            | 5271        | 41.3307464      | -94.4709413      | 
| 2015-03-01T00:00:00 | 19003 | Adams      | 608        | 965        |            | 1165            | 3            | 2741         | 27           | 29           |              | 100               | 0              | 156            | 2897        | 41.0289839      | -94.6991849      | 
| 2015-03-01T00:00:00 | 19005 | Allamakee  | 2132       | 4196       |            | 3192            | 10           | 9530         | 102          | 122          |              | 192               | 0              | 416            | 9946        | 43.2842838      | -91.3780923      | 
| 2015-03-01T00:00:00 | 19007 | Appanoose  | 2437       | 2793       |            | 3007            | 7            | 8244         | 212          | 179          |              | 364               | 0              | 755            | 8999        | 40.7431635      | -92.8686104      | 
| 2015-03-01T00:00:00 | 19009 | Audubon    | 1228       | 1540       |            | 1393            | 8            | 4169         | 41           | 51           |              | 106               | 0              | 198            | 4367        | 41.6845893      | -94.9058222      | 
| 2015-03-01T00:00:00 | 19011 | Benton     | 4295       | 4979       |            | 7491            | 33           | 16798        | 261          | 191          |              | 561               | 3              | 1016           | 17814       | 42.0801864      | -92.0656912      | 
| 2015-03-01T00:00:00 | 19013 | Black Hawk | 28502      | 20284      |            | 31471           | 334          | 80591        | 1793         | 971          |              | 2226              | 31             | 5021           | 85612       | 42.4700957      | -92.3088197      | 
| 2015-03-01T00:00:00 | 19015 | Boone      | 5129       | 5447       |            | 7035            | 49           | 17660        | 220          | 252          |              | 490               | 2              | 964            | 18624       | 42.0365493      | -93.931671       | 
| 2015-03-01T00:00:00 | 19017 | Bremer     | 3608       | 4960       |            | 7451            | 38           | 16057        | 193          | 191          |              | 467               | 4              | 855            | 16912       | 42.7745873      | -92.3180548      | 
| 2015-03-01T00:00:00 | 19019 | Buchanan   | 3662       | 3063       |            | 6410            | 16           | 13151        | 179          | 126          |              | 425               | 0              | 730            | 13881       | 42.4707777      | -91.8378392      | 
```