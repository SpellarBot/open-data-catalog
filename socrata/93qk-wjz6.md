# Security Guard Schools Approved by the Division of Criminal Justice Services

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/security-guard-schools-approved-by-the-division-of-criminal-justice-services) |
| Metadata | [Link](https://data.ny.gov/api/views/93qk-wjz6) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/93qk-wjz6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/93qk-wjz6/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 93qk-wjz6 |
| Name | Security Guard Schools Approved by the Division of Criminal Justice Services |
| Attribution | New York State Division of Criminal Justice Services |
| Category | Public Safety |
| Tags | public safety, security guards, law enforcement |
| Created | 2014-04-09T14:29:59Z |
| Publication Date | 2017-01-30T23:01:18Z |

## Description

This is a current list of approved security guard schools.  The Security Guard Act of 1992 requires registration and training of security guards in New York State. The Division of Criminal Justice Services (DCJS) approves the private security training schools and provides administrative oversight for mandated security training.

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type | Render Type |
| ======== | =========== | ================ | ================ | ========= | =========== |
| No       | time        | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | series tag  | schoolid         | School ID#       | text      | text        |
| Yes      | series tag  | county           | County           | text      | text        |
| Yes      | series tag  | agency           | Agency           | text      | text        |
| Yes      | series tag  | streetaddress1   | Street Address   | text      | text        |
| Yes      | series tag  | streetaddress2   | Street Address 2 | text      | text        |
| Yes      | series tag  | city             | City             | text      | text        |
| Yes      | series tag  | state            | State            | text      | text        |
| Yes      | series tag  | zip              | Zip              | text      | text        |
| Yes      | series tag  | fireams_training | Fireams Training | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:93qk-wjz6 d:2017-01-30T23:01:06.000Z t:zip=12208 t:schoolid=10008 t:county=Albany t:streetaddress1="43 New Scotland Ave." t:streetaddress2="MS 169" t:state=NY t:agency="Albany Medical Center" t:fireams_training=No t:city=Albany m:row_number.93qk-wjz6=1

series e:93qk-wjz6 d:2017-01-30T23:01:06.000Z t:zip=12205 t:schoolid=101780 t:county=Albany t:streetaddress1="1015 Watervliet-Shaker Road" t:state=NY t:agency="Albany, Schoharie, Schenectady, Saratoga BOC" t:fireams_training=no t:city=Albany m:row_number.93qk-wjz6=2

series e:93qk-wjz6 d:2017-01-30T23:01:06.000Z t:zip=12205 t:schoolid=12233 t:county=Albany t:streetaddress1="145 Wolf Road" t:state=NY t:agency="Bryant & Stratton College" t:fireams_training=No t:city=Albany m:row_number.93qk-wjz6=3
```

## Meta Commands

```ls
metric m:row_number.93qk-wjz6 p:long l:"Row Number"

entity e:93qk-wjz6 l:"Security Guard Schools Approved by the Division of Criminal Justice Services" t:attribution="New York State Division of Criminal Justice Services" t:url=https://data.ny.gov/api/views/93qk-wjz6

property e:93qk-wjz6 t:meta.view v:id=93qk-wjz6 v:category="Public Safety" v:attributionLink=http://www.criminaljustice.ny.gov/ops/sgtraining/index.htm v:averageRating=0 v:name="Security Guard Schools Approved by the Division of Criminal Justice Services" v:attribution="New York State Division of Criminal Justice Services"

property e:93qk-wjz6 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:93qk-wjz6 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:93qk-wjz6 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | schoolid | county | agency                                       | streetaddress1              | streetaddress2               | city            | state | zip   | fireams_training | 
| =========== | ======== | ====== | ============================================ | =========================== | ============================ | =============== | ===== | ===== | ================ | 
| 1485817266  | 10008    | Albany | Albany Medical Center                        | 43 New Scotland Ave.        | MS 169                       | Albany          | NY    | 12208 | No               | 
| 1485817266  | 101780   | Albany | Albany, Schoharie, Schenectady, Saratoga BOC | 1015 Watervliet-Shaker Road |                              | Albany          | NY    | 12205 | no               | 
| 1485817266  | 12233    | Albany | Bryant & Stratton College                    | 145 Wolf Road               |                              | Albany          | NY    | 12205 | No               | 
| 1485817266  | 11991    | Albany | Capital District Investigations Sec Trn      | 2 Borthwick Avenue          |                              | Delmar          | NY    | 12054 | Yes              | 
| 1485817266  | 11584    | Albany | Independent Security Svcs                    | 31 Margaret Drive           |                              | Albany          | NY    | 12211 | No               | 
| 1485817266  | 11681    | Albany | Keeplock Security Svc                        | 1019 DiBella Dr             |                              | Schenectady     | NY    | 12303 | Yes              | 
| 1485817266  | 11667    | Albany | New York State Education Dept                | 89 Washington Ave.          | Cultural Educ Center Rm 3071 | Albany          | NY    | 12234 | No               | 
| 1485817266  | 11669    | Albany | New York State Park Police                   | 16 Camp Cass Road           |                              | Rensselaerville | NY    | 12147 | No               | 
| 1485817266  | 10816    | Albany | New York State Police Security Svcs          | Empire State Plaza          | Concourse level-ESP          | Albany          | NY    | 12242 | No               | 
| 1485817266  | 12188    | Albany | Sabourin Security Academy                    | 1510 Central Avenue         |                              | Albany          | NY    | 12205 | No               | 
```