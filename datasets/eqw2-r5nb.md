# NYS Attorney Registrations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nys-attorney-registrations) |
| Metadata | [Link](https://data.ny.gov/api/views/eqw2-r5nb) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/eqw2-r5nb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/eqw2-r5nb/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | eqw2-r5nb |
| Name | NYS Attorney Registrations |
| Attribution | NYS Unified Court System |
| Category | Transparency |
| Tags | attorney, registrations, integrity |
| Created | 2013-04-12T18:29:05Z |
| Publication Date | 2017-03-11T11:24:57Z |
| Rows Updated | 2017-03-11T11:24:34Z |

## Description

The data included here is the information in the NYS Attorney Registration Database that is deemed public information pursuant to 22 NYCRR 118.

## Columns

```ls
| Included | Schema Type    | Field Name                       | Name                             | Data Type | Render Type |
| ======== | ============== | ================================ | ================================ | ========= | =========== |
| Yes      | numeric metric | registration_number              | Registration Number              | number    | number      |
| Yes      | series tag     | first_name                       | First Name                       | text      | text        |
| Yes      | series tag     | middle_name                      | Middle Name                      | text      | text        |
| Yes      | series tag     | last_name                        | Last Name                        | text      | text        |
| Yes      | series tag     | suffix                           | Suffix                           | text      | text        |
| Yes      | series tag     | company_name                     | Company Name                     | text      | text        |
| Yes      | series tag     | street_1                         | Street 1                         | text      | text        |
| Yes      | series tag     | street_2                         | Street 2                         | text      | text        |
| Yes      | series tag     | city                             | City                             | text      | text        |
| Yes      | series tag     | state                            | State                            | text      | text        |
| Yes      | series tag     | zip                              | Zip                              | text      | text        |
| Yes      | series tag     | zip_plus_four                    | Zip Plus Four                    | text      | text        |
| Yes      | series tag     | country                          | Country                          | text      | text        |
| Yes      | series tag     | county                           | County                           | text      | text        |
| Yes      | series tag     | phone_number                     | Phone Number                     | text      | text        |
| No       |                | email_address                    | Email Address                    | text      | text        |
| Yes      | time           | year_admitted                    | Year Admitted                    | number    | number      |
| Yes      | numeric metric | judicial_department_of_admission | Judicial Department of Admission | number    | number      |
| Yes      | series tag     | law_school                       | Law School                       | text      | text        |
| Yes      | series tag     | status                           | Status                           | text      | text        |
| Yes      | series tag     | next_registration                | Next Registration                | text      | text        |
```

## Time Field

```ls
Value = year_admitted
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = email_address
```

## Data Commands

```ls
series e:eqw2-r5nb d:2013-01-01T00:00:00.000Z t:zip=77056 t:phone_number="(713) 840-0499" t:status="Currently registered" t:law_school="UNIVERSITY OF IOWA COLLEGE OF LAW" t:state=TX t:city=Houston t:country="United States" t:zip_plus_four=6537 t:first_name=JIANNAN t:street_1="3050 Post Oak Blvd Ste 1200" t:next_registration="May 2017" t:county="Out of State" t:company_name="SINOPEI USA, INC." t:last_name=WEI m:registration_number=5134408 m:judicial_department_of_admission=3

series e:eqw2-r5nb d:2013-01-01T00:00:00.000Z t:first_name=HYE-SHIL t:next_registration="May 2017" t:status="Currently registered" t:law_school="NORTHWESTERN UNIVERSITY" t:last_name=KIM m:registration_number=5134416 m:judicial_department_of_admission=3

series e:eqw2-r5nb d:2013-01-01T00:00:00.000Z t:first_name=SZE t:next_registration="Nov 2017" t:street_1="1 SUPREME COURT LANE" t:phone_number="+81 80 4319 4788" t:county="Out of USA" t:company_name="SUPREME COURT OF SINGAPORE" t:status=Delinquent t:middle_name=YAO t:law_school="UNIVERSITY OF CAMBRIDGE" t:last_name=TAN t:country=SINGAPORE t:city="SINGAPORE 178 879" m:registration_number=5134424 m:judicial_department_of_admission=3
```

## Meta Commands

```ls
metric m:registration_number p:integer l:"Registration Number" t:dataTypeName=number

metric m:judicial_department_of_admission p:integer l:"Judicial Department of Admission" t:dataTypeName=number

entity e:eqw2-r5nb l:"NYS Attorney Registrations" t:attribution="NYS Unified Court System" t:url=https://data.ny.gov/api/views/eqw2-r5nb

property e:eqw2-r5nb t:meta.view v:id=eqw2-r5nb v:category=Transparency v:averageRating=0 v:name="NYS Attorney Registrations" v:attribution="NYS Unified Court System"

property e:eqw2-r5nb t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:eqw2-r5nb t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:eqw2-r5nb t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```