# Monthly Medicaid Payments & Recipients By County

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/monthly-medicaid-payments-recipients-by-county) |
| Metadata | [Link](https://data.iowa.gov/api/views/jmyd-wk9g) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/jmyd-wk9g/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/jmyd-wk9g/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | jmyd-wk9g |
| Name | Monthly Medicaid Payments & Recipients By County |
| Attribution | Iowa Department of Human Services, Medicaid Management Information System - Report IAMM1800-R002 |
| Category | Health |
| Tags | medicaid, health care, public assistance |
| Created | 2014-12-01T19:10:50Z |
| Publication Date | 2016-11-29T14:00:33Z |

## Description

This dataset contains aggregate Medicaid payments, and counts for eligible recipients and recipients served by month and county, starting with month ending 1/31/2011.

Eligibility groups are a category of people who meet certain common eligibility requirements. Some Medicaid eligibility groups cover additional services, such as nursing facility care and care received in the home. Others have higher income and resource limits, charge a premium, only pay the Medicare premium or cover only expenses also paid by Medicare, or require the recipient to pay a specific dollar amount of their medical expenses. Eligible Medicaid recipients may be considered medically needy if their medical costs are so high that they use up most of their income. Those considered medically needy are responsible for paying some of their medical expenses. This is called meeting a spend down. Then Medicaid would start to pay for the rest. Think of the spend down like a deductible that people pay as part of a private insurance plan.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name            | Data Type     | Render Type   |
| ======== | ============== | ================= | =============== | ============= | ============= |
| Yes      | time           | report_as_of_date | Report Date     | calendar_date | calendar_date |
| Yes      | series tag     | county            | County          | text          | text          |
| Yes      | numeric metric | county_fip        | County FIP      | number        | number        |
| Yes      | series tag     | gnis_feature_id   | GNIS Feature ID | text          | number        |
| Yes      | numeric metric | medneedy_elig     | MedNeedy_Elig   | number        | number        |
| Yes      | numeric metric | medneedy_recip    | MedNeedy_Recip  | number        | number        |
| Yes      | numeric metric | medneedy_pmt      | MedNeedy_Pmt    | money         | money         |
| Yes      | numeric metric | othertxix_elig    | OtherTXIX_Elig  | number        | number        |
| Yes      | numeric metric | othertxix_recip   | OtherTXIX_Recip | number        | number        |
| Yes      | numeric metric | othertxix_pmt     | OtherTXIX_Pmt   | money         | money         |
| Yes      | numeric metric | totaltxix_elig    | TotalTXIX_Elig  | number        | number        |
| Yes      | numeric metric | totaltxix_recip   | TotalTXIX_Recip | number        | number        |
| Yes      | numeric metric | totaltxix_pmt     | TotalTXIX_Pmt   | money         | money         |
| No       |                | prim_lat_dec      | PRIM_LAT_DEC    | number        | number        |
| No       |                | prim_long_dec     | PRIM_LONG_DEC   | number        | number        |
```

## Time Field

```ls
Value = report_as_of_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = prim_lat_dec,prim_long_dec
```

## Data Commands

```ls
series e:jmyd-wk9g d:2011-01-31T00:00:00.000Z t:gnis_feature_id=465190 t:county=ADAIR m:othertxix_pmt=618890 m:county_fip=19001 m:medneedy_elig=6 m:totaltxix_elig=924 m:totaltxix_pmt=619799 m:medneedy_pmt=909 m:totaltxix_recip=936 m:othertxix_elig=918 m:medneedy_recip=11 m:othertxix_recip=927

series e:jmyd-wk9g d:2011-01-31T00:00:00.000Z t:gnis_feature_id=465191 t:county=ADAMS m:othertxix_pmt=548915 m:county_fip=19003 m:medneedy_elig=5 m:totaltxix_elig=643 m:totaltxix_pmt=550999 m:medneedy_pmt=2083 m:totaltxix_recip=664 m:othertxix_elig=638 m:medneedy_recip=8 m:othertxix_recip=659

series e:jmyd-wk9g d:2011-01-31T00:00:00.000Z t:gnis_feature_id=465192 t:county=ALLAMAKEE m:othertxix_pmt=1293348 m:county_fip=19005 m:medneedy_elig=8 m:totaltxix_elig=2241 m:totaltxix_pmt=1301657 m:medneedy_pmt=8309 m:totaltxix_recip=2259 m:othertxix_elig=2233 m:medneedy_recip=10 m:othertxix_recip=2249
```

## Meta Commands

```ls
metric m:county_fip p:integer l:"County FIP" d:"A five-digit code for counties based on Federal Information Processing Standards Publication - FIPS 55-DC3 (December 1994) , Guideline: Codes for Named Populated Places, Primary County Divisions, and Other Locational Entities of the United States, Puerto Rico, and the Outlying Areas (withdrawn February 8, 2005)" t:dataTypeName=number

metric m:medneedy_elig p:integer l:MedNeedy_Elig d:"Number of Medically Needy Eligible Recipients" t:dataTypeName=number

metric m:medneedy_recip p:integer l:MedNeedy_Recip d:"Number of Medically Needy Recipients Served" t:dataTypeName=number

metric m:medneedy_pmt p:double l:MedNeedy_Pmt d:"Total claims reimbursed for the Medically Needy recipients" t:dataTypeName=money

metric m:othertxix_elig p:integer l:OtherTXIX_Elig d:"Number of non-Medically Needy Eligible Medicaid recipients" t:dataTypeName=number

metric m:othertxix_recip p:integer l:OtherTXIX_Recip d:"Number of non-Medically Needy Medicaid recipients served" t:dataTypeName=number

metric m:othertxix_pmt p:integer l:OtherTXIX_Pmt d:"Total claims reimbursed for the non-Medically Needy Medicaid recipients" t:dataTypeName=money

metric m:totaltxix_elig p:integer l:TotalTXIX_Elig d:"Number of total eligible Medicaid recipients" t:dataTypeName=number

metric m:totaltxix_recip p:integer l:TotalTXIX_Recip d:"Number of total Medicaid recipients served" t:dataTypeName=number

metric m:totaltxix_pmt p:integer l:TotalTXIX_Pmt d:"Total claims reimbursed for Medicaid recipients" t:dataTypeName=money

entity e:jmyd-wk9g l:"Monthly Medicaid Payments & Recipients By County" t:attribution="Iowa Department of Human Services, Medicaid Management Information System - Report IAMM1800-R002" t:url=https://data.iowa.gov/api/views/jmyd-wk9g

property e:jmyd-wk9g t:meta.view v:id=jmyd-wk9g v:category=Health v:averageRating=0 v:name="Monthly Medicaid Payments & Recipients By County" v:attribution="Iowa Department of Human Services, Medicaid Management Information System - Report IAMM1800-R002"

property e:jmyd-wk9g t:meta.view.license v:name="Public Domain"

property e:jmyd-wk9g t:meta.view.owner v:id=grmb-3z9d v:profileImageUrlMedium=/api/users/grmb-3z9d/profile_images/THUMB v:profileImageUrlLarge=/api/users/grmb-3z9d/profile_images/LARGE v:screenName="Iowa Department of Human Services" v:profileImageUrlSmall=/api/users/grmb-3z9d/profile_images/TINY v:displayName="Iowa Department of Human Services"

property e:jmyd-wk9g t:meta.view.tableauthor v:id=grmb-3z9d v:profileImageUrlMedium=/api/users/grmb-3z9d/profile_images/THUMB v:profileImageUrlLarge=/api/users/grmb-3z9d/profile_images/LARGE v:screenName="Iowa Department of Human Services" v:profileImageUrlSmall=/api/users/grmb-3z9d/profile_images/TINY v:roleName=editor v:displayName="Iowa Department of Human Services"
```

## Top Records

```ls
| report_as_of_date   | county     | county_fip | gnis_feature_id | medneedy_elig | medneedy_recip | medneedy_pmt | othertxix_elig | othertxix_recip | othertxix_pmt | totaltxix_elig | totaltxix_recip | totaltxix_pmt | prim_lat_dec | prim_long_dec | 
| =================== | ========== | ========== | =============== | ============= | ============== | ============ | ============== | =============== | ============= | ============== | =============== | ============= | ============ | ============= | 
| 2011-01-31T00:00:00 | ADAIR      | 19001      | 465190          | 6             | 11             | 909.00       | 918            | 927             | 618890.00     | 924            | 936             | 619799.00     | 41.3307464   | -94.4709413   | 
| 2011-01-31T00:00:00 | ADAMS      | 19003      | 465191          | 5             | 8              | 2083.00      | 638            | 659             | 548915.00     | 643            | 664             | 550999.00     | 41.0289839   | -94.6991849   | 
| 2011-01-31T00:00:00 | ALLAMAKEE  | 19005      | 465192          | 8             | 10             | 8309.00      | 2233           | 2249            | 1293348.00    | 2241           | 2259            | 1301657.00    | 43.2842838   | -91.3780923   | 
| 2011-01-31T00:00:00 | APPANOOSE  | 19007      | 465193          | 10            | 16             | 43480.00     | 2758           | 2759            | 1734522.00    | 2768           | 2772            | 1778003.00    | 40.7431635   | -92.8686104   | 
| 2011-01-31T00:00:00 | AUDUBON    | 19009      | 465194          | 1             | 2              | 107.00       | 648            | 671             | 423049.00     | 649            | 672             | 423156.00     | 41.6845893   | -94.9058222   | 
| 2011-01-31T00:00:00 | BENTON     | 19011      | 465195          | 19            | 37             | 19461.00     | 3023           | 2973            | 1633910.00    | 3042           | 3005            | 1653371.00    | 42.0801864   | -92.0656912   | 
| 2011-01-31T00:00:00 | BLACK HAWK | 19013      | 465196          | 86            | 170            | 59217.00     | 22658          | 21648           | 12538335.00   | 22744          | 21778           | 12597553.00   | 42.4700957   | -92.3088197   | 
| 2011-01-31T00:00:00 | BOONE      | 19015      | 465197          | 17            | 25             | 3542.00      | 3452           | 3940            | 7248063.00    | 3469           | 3960            | 7251605.00    | 42.0365493   | -93.931671    | 
| 2011-01-31T00:00:00 | BREMER     | 19017      | 465198          | 4             | 13             | 2920.00      | 1847           | 1814            | 1261610.00    | 1851           | 1826            | 1264530.00    | 42.7745873   | -92.3180548   | 
| 2011-01-31T00:00:00 | BUCHANAN   | 19019      | 465199          | 26            | 47             | 48036.00     | 2746           | 2750            | 1633210.00    | 2772           | 2789            | 1681246.00    | 42.4707777   | -91.8378392   | 
```