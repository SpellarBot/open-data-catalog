# Financial Integrity Benchmarks

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/financial-integrity-benchmarks) |
| Metadata | [Link](https://data.jacksonms.gov/api/views/wczt-d4tz) |
| Data: JSON | [100 Rows](https://data.jacksonms.gov/api/views/wczt-d4tz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.jacksonms.gov/api/views/wczt-d4tz/rows.csv?max_rows=100) |
| Host | data.jacksonms.gov |
| Id | wczt-d4tz |
| Name | Financial Integrity Benchmarks |
| Attribution | City of Jackson |
| Category | Budget and Finance |
| Tags | budget, bond ratings, debt ratio, city of jackson, finance, fiscal integrity, benchmarks, money |
| Created | 2016-03-08T17:11:08Z |
| Publication Date | 2016-12-02T16:27:33Z |

## Description

This data compiles standard financial integrity benchmarks that allow the City to measure its financial standing. It measure the City's debt ratio and bond ratings.  This information is updated quarterly and after any major financial assessment.

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type     | Render Type   |
| ======== | ============== | ====================== | ====================== | ============= | ============= |
| Yes      | time           | fiscal_year            | Fiscal Year            | calendar_date | calendar_date |
| Yes      | series tag     | moody_s_g_o_bonds      | Moody's G.O. Bonds     | text          | text          |
| Yes      | series tag     | moody_s_revenue_bonds  | Moody's Revenue Bonds  | text          | text          |
| Yes      | series tag     | s_p_g_o_bonds          | S&P G.O. Bonds         | text          | text          |
| Yes      | series tag     | s_p_revenue_bonds      | S&P Revenue Bonds      | text          | text          |
| Yes      | numeric metric | debt_to_assessed_value | Debt to Assessed Value | percent       | percent       |
| Yes      | series tag     | audit_opinon           | Audit Opinon           | text          | text          |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:wczt-d4tz d:2010-01-01T00:00:00.000Z t:s_p_revenue_bonds=A+ t:moody_s_revenue_bonds=Aa2 t:audit_opinon=Unqualified t:s_p_g_o_bonds=AA- t:moody_s_g_o_bonds=Aa2 m:debt_to_assessed_value=12.63

series e:wczt-d4tz d:2011-01-01T00:00:00.000Z t:s_p_revenue_bonds=A+ t:moody_s_revenue_bonds=Aa3 t:audit_opinon=Unqualified t:s_p_g_o_bonds=AA- t:moody_s_g_o_bonds=Aa2 m:debt_to_assessed_value=12.55

series e:wczt-d4tz d:2012-01-01T00:00:00.000Z t:s_p_revenue_bonds=A+ t:moody_s_revenue_bonds=Aa3 t:audit_opinon=Unqualified t:s_p_g_o_bonds=AA- t:moody_s_g_o_bonds=Aa2 m:debt_to_assessed_value=12.36
```

## Meta Commands

```ls
metric m:debt_to_assessed_value p:float l:"Debt to Assessed Value" t:dataTypeName=percent

entity e:wczt-d4tz l:"Financial Integrity Benchmarks" t:attribution="City of Jackson" t:url=https://data.jacksonms.gov/api/views/wczt-d4tz

property e:wczt-d4tz t:meta.view v:id=wczt-d4tz v:category="Budget and Finance" v:attributionLink=http://www.jacksonms.gov v:averageRating=0 v:name="Financial Integrity Benchmarks" v:attribution="City of Jackson"

property e:wczt-d4tz t:meta.view.owner v:id=6ngd-c2u2 v:profileImageUrlMedium=/api/users/6ngd-c2u2/profile_images/THUMB v:profileImageUrlLarge=/api/users/6ngd-c2u2/profile_images/LARGE v:screenName="Justin Bruce" v:profileImageUrlSmall=/api/users/6ngd-c2u2/profile_images/TINY v:lastNotificationSeenAt=1492180672 v:displayName="Justin Bruce"

property e:wczt-d4tz t:meta.view.tableauthor v:id=6ngd-c2u2 v:profileImageUrlMedium=/api/users/6ngd-c2u2/profile_images/THUMB v:profileImageUrlLarge=/api/users/6ngd-c2u2/profile_images/LARGE v:screenName="Justin Bruce" v:profileImageUrlSmall=/api/users/6ngd-c2u2/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492180672 v:displayName="Justin Bruce"
```

## Top Records

```ls
| fiscal_year         | moody_s_g_o_bonds | moody_s_revenue_bonds | s_p_g_o_bonds | s_p_revenue_bonds | debt_to_assessed_value | audit_opinon | 
| =================== | ================= | ===================== | ============= | ================= | ====================== | ============ | 
| 2010-01-01T00:00:00 | Aa2               | Aa2                   | AA-           | A+                | 12.63                  | Unqualified  | 
| 2011-01-01T00:00:00 | Aa2               | Aa3                   | AA-           | A+                | 12.55                  | Unqualified  | 
| 2012-01-01T00:00:00 | Aa2               | Aa3                   | AA-           | A+                | 12.36                  | Unqualified  | 
| 2013-01-01T00:00:00 | A1                | Aa3                   | A+            | A+                | 13.24                  | Unmodified   | 
| 2014-01-01T00:00:00 | A1                | A1                    | A+            | A+                | 12.90                  | Unmodified   | 
| 2015-01-01T00:00:00 | Aa2               | A2                    | AA-           | A+                | 12.16                  | Unmodified   | 
| 2016-01-01T00:00:00 |                   |                       |               |                   |                        | Unmodified   | 
```