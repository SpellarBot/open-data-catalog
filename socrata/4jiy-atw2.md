# Lead Paint Contractors

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lead-paint-contractors) |
| Metadata | [Link](https://data.maryland.gov/api/views/4jiy-atw2) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/4jiy-atw2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/4jiy-atw2/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | 4jiy-atw2 |
| Name | Lead Paint Contractors |
| Attribution | Maryland Department of the Environment |
| Category | Energy and Environment |
| Tags | lead paint, paint, contractors, lead paint services, mde |
| Created | 2013-11-01T18:14:59Z |
| Publication Date | 2017-04-07T18:08:32Z |

## Description

The Residential, Commercial and Public Building Contractors (RC) listed have been accredited by the Maryland Department of the Environment to provide lead paint abatement services.
There are two kinds of lead paint supervisors who may perform lead paint abatement work on residential, commercial and public buildings. They qualify in the following ways:
?	Maintenance & Repainting Supervisor (S4) - May provide oversight of Lead Paint Abatement Workers and perform work for activities such as minor repairs, painting and window replacement.
?	Removal & Demolition Supervisor (S2) ? Also known as an Abatement Supervisor. May provide oversight of Lead Paint Abatement Workers and perform work from minor repairs and painting to major renovations, demolitions and lead paint abatement projects.
Lead Paint Abatement Workers are to have their current training ID card in their possession while performing lead paint abatement. There is no accreditation for them but are to work under the supervision of an accredited Lead Paint Abatement Supervisor.

Disclaimer:
For your convenience MDE publishes this list of accredited lead contractors that meet Maryland?s standards to perform abatement activities involving lead-based paint. The list is an information resource only. MDE does not endorse any of the contractors included on this list nor does MDE provide any warranty about their performance. Consumers are advised to request bids and conduct reference checks before hiring. Contact the individual contractors for information regarding services and fees. Verify with the contractor you are going to hire that the supervisor is accredited by MDE and all lead paint abatement workers have current training. This accreditation and training does not satisfy the EPA Renovation, Repair and Painting (RRP) Rule.

## Columns

```ls
| Included | Schema Type | Field Name                  | Name                        | Data Type     | Render Type   |
| ======== | =========== | =========================== | =========================== | ============= | ============= |
| Yes      | series tag  | certificate_number          | Certificate Number          | text          | number        |
| Yes      | time        | certificate_expiration_date | Certificate Expiration Date | calendar_date | calendar_date |
| Yes      | series tag  | contractor_name             | Contractor Name             | text          | text          |
| No       |             | contractor_address_line_1   | Contractor Address Line 1   | text          | text          |
| No       |             | contractor_address_line_2   | Contractor Address Line 2   | text          | text          |
| Yes      | series tag  | contractor_city             | Contractor City             | text          | text          |
| Yes      | series tag  | contractor_state            | Contractor State            | text          | text          |
| Yes      | series tag  | contractor_zip_code         | Contractor ZIP Code         | text          | number        |
| Yes      | series tag  | phone_number                | Phone Number                | text          | number        |
| Yes      | series tag  | fax_number                  | Fax Number                  | text          | number        |
| Yes      | series tag  | contact_first_name          | Contact First Name          | text          | text          |
| Yes      | series tag  | contact_last_name           | Contact Last Name           | text          | text          |
| Yes      | series tag  | baltimore_area              | Baltimore Area              | checkbox      | checkbox      |
| Yes      | series tag  | eastern_shore               | Eastern Shore               | checkbox      | checkbox      |
| Yes      | series tag  | washington_dc_suburbs       | Washington, DC Suburbs      | checkbox      | checkbox      |
| Yes      | series tag  | southern_maryland           | Southern Maryland           | checkbox      | checkbox      |
| Yes      | series tag  | western_maryland            | Western Maryland            | checkbox      | checkbox      |
| Yes      | series tag  | statewide                   | Statewide                   | checkbox      | checkbox      |
| Yes      | series tag  | mhic_registration_number    | MHIC Registration Number    | text          | number        |
| Yes      | series tag  | carpentry_services          | General Carpentry Services  | checkbox      | checkbox      |
| Yes      | series tag  | drywall_services            | Drywall Services            | checkbox      | checkbox      |
| Yes      | series tag  | home_improvement            | Home Improvement            | checkbox      | checkbox      |
| Yes      | series tag  | cleaning                    | Cleaning                    | checkbox      | checkbox      |
| Yes      | series tag  | painting                    | Painting                    | checkbox      | checkbox      |
| Yes      | series tag  | removal                     | Paint Removal               | checkbox      | checkbox      |
| Yes      | series tag  | weatherization              | Weatherization              | checkbox      | checkbox      |
```

## Time Field

```ls
Value = certificate_expiration_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = contractor_address_line_1,contractor_address_line_2
```

## Data Commands

```ls
series e:4jiy-atw2 d:2017-06-11T00:00:00.000Z t:southern_maryland=true t:cleaning=true t:phone_number=4103361800 t:contact_first_name=Harold t:home_improvement=true t:certificate_number=15056 t:contractor_city=Baltimore t:weatherization=true t:carpentry_services=true t:washington_dc_suburbs=true t:mhic_registration_number=99168 t:removal=true t:baltimore_area=true t:contractor_name="#1 A & A Abatement" t:contractor_state=MD t:statewide=true t:contractor_zip_code=21215 t:western_maryland=true t:eastern_shore=true t:drywall_services=true t:contact_last_name=Morgan t:painting=true m:row_number.4jiy-atw2=1

series e:4jiy-atw2 d:2019-01-14T00:00:00.000Z t:southern_maryland=true t:cleaning=true t:phone_number=4438393565 t:contact_first_name=Terrell t:home_improvement=false t:certificate_number=14852 t:contractor_city=Lochern t:weatherization=true t:carpentry_services=true t:washington_dc_suburbs=true t:removal=true t:baltimore_area=true t:contractor_name="00 Lead Inspections & Abatements" t:contractor_state=MD t:statewide=true t:contractor_zip_code=21207 t:western_maryland=true t:eastern_shore=true t:drywall_services=true t:contact_last_name=Atkinson t:painting=true m:row_number.4jiy-atw2=2

series e:4jiy-atw2 d:2017-04-30T00:00:00.000Z t:southern_maryland=true t:cleaning=false t:phone_number=4438066201 t:contact_first_name=Mark t:home_improvement=true t:certificate_number=13979 t:contractor_city=Baltimore t:weatherization=false t:carpentry_services=true t:washington_dc_suburbs=true t:removal=false t:baltimore_area=true t:contractor_name="01 Abatement LLC" t:contractor_state=MD t:statewide=true t:contractor_zip_code=21206 t:western_maryland=true t:eastern_shore=true t:drywall_services=true t:contact_last_name=McCoy t:painting=true m:row_number.4jiy-atw2=3
```

## Meta Commands

```ls
metric m:row_number.4jiy-atw2 p:long l:"Row Number"

entity e:4jiy-atw2 l:"Lead Paint Contractors" t:attribution="Maryland Department of the Environment" t:url=https://data.maryland.gov/api/views/4jiy-atw2

property e:4jiy-atw2 t:meta.view v:id=4jiy-atw2 v:category="Energy and Environment" v:averageRating=0 v:name="Lead Paint Contractors" v:attribution="Maryland Department of the Environment"

property e:4jiy-atw2 t:meta.view.license v:name="Public Domain"

property e:4jiy-atw2 t:meta.view.owner v:id=6wh5-kegk v:profileImageUrlMedium=/api/users/6wh5-kegk/profile_images/THUMB v:profileImageUrlLarge=/api/users/6wh5-kegk/profile_images/LARGE v:screenName="Andrew Gosden" v:profileImageUrlSmall=/api/users/6wh5-kegk/profile_images/TINY v:lastNotificationSeenAt=1491588421 v:displayName="Andrew Gosden"

property e:4jiy-atw2 t:meta.view.tableauthor v:id=6wh5-kegk v:profileImageUrlMedium=/api/users/6wh5-kegk/profile_images/THUMB v:profileImageUrlLarge=/api/users/6wh5-kegk/profile_images/LARGE v:screenName="Andrew Gosden" v:profileImageUrlSmall=/api/users/6wh5-kegk/profile_images/TINY v:roleName=editor v:lastNotificationSeenAt=1491588421 v:displayName="Andrew Gosden"
```

## Top Records

```ls
| certificate_number | certificate_expiration_date | contractor_name                        | contractor_address_line_1 | contractor_address_line_2 | contractor_city | contractor_state | contractor_zip_code | phone_number | fax_number | contact_first_name | contact_last_name | baltimore_area | eastern_shore | washington_dc_suburbs | southern_maryland | western_maryland | statewide | mhic_registration_number | carpentry_services | drywall_services | home_improvement | cleaning | painting | removal | weatherization | 
| ================== | =========================== | ====================================== | ========================= | ========================= | =============== | ================ | =================== | ============ | ========== | ================== | ================= | ============== | ============= | ===================== | ================= | ================ | ========= | ======================== | ================== | ================ | ================ | ======== | ======== | ======= | ============== | 
| 15056              | 2017-06-11T00:00:00         | #1 A & A Abatement                     | 5344 Reisterstown Road    |                           | Baltimore       | MD               | 21215               | 4103361800   |            | Harold             | Morgan            | true           | true          | true                  | true              | true             | true      | 99168                    | true               | true             | true             | true     | true     | true    | true           | 
| 14852              | 2019-01-14T00:00:00         | 00 Lead Inspections & Abatements       | 3800 Cedar Drive          |                           | Lochern         | MD               | 21207               | 4438393565   |            | Terrell            | Atkinson          | true           | true          | true                  | true              | true             | true      |                          | true               | true             | false            | true     | true     | true    | true           | 
| 13979              | 2017-04-30T00:00:00         | 01 Abatement LLC                       | 5501 Cedella Avenue       |                           | Baltimore       | MD               | 21206               | 4438066201   |            | Mark               | McCoy             | true           | true          | true                  | true              | true             | true      |                          | true               | true             | true             | false    | true     | false   | false          | 
| 13058              | 2018-02-06T00:00:00         | 121 Abatement and Inspections          | 2006 Gwynn Oak Avenue     |                           | Gwynn Oak       | MD               | 21207               | 4109088619   |            | Caswel             | Young             | true           | true          | true                  | true              | true             | true      |                          | true               | true             | true             | true     | true     | true    | true           | 
| 13335              | 2018-02-16T00:00:00         | 4M Associates, LLC                     | 12911 Princeleigh Street  |                           | Upper Marlboro  | MD               | 20774               | 3012491964   |            | Michael L.         | Chambers          | true           | false         | true                  | true              | false            | false     |                          | true               | true             | false            | true     | true     | true    | false          | 
| 8113               | 2018-08-05T00:00:00         | A & A Aaron Painting & Abatement Group | 342 E 27th Street         |                           | Baltimore       | MD               | 21218               | 4109496343   |            | Myron J.           | Seay, Sr.         | true           | false         | true                  | true              | false            | false     |                          | false              | false            | false            | false    | false    | false   | false          | 
| 5884               | 2019-04-04T00:00:00         | A & I, Inc.                            | 8301 B Pulaski Highway    |                           | Baltimore       | MD               | 21237               | 4102383020   | 4102383024 | Alison             | O'Neill           | true           | true          | true                  | true              | true             | true      |                          | false              | false            | false            | true     | false    | true    | false          | 
| 5606               | 2017-05-01T00:00:00         | A & L Home Improvements, LLP           | P.O. Box 373              |                           | Smithsburg      | MD               | 21783               | 3019922411   | 3018246179 | Donald E.          | Hays              | false          | false         | false                 | true              | true             | false     |                          | true               | true             | true             | false    | true     | false   | false          | 
| 15264              | 2017-08-20T00:00:00         | A K Remodeling, LLC                    | 4480 Plum Point Road      |                           | Huntington      | MD               | 20639               | 4436361068   |            | Alan               | Kozlowski         | true           | true          | true                  | true              | true             | true      |                          | true               | true             | true             | false    | true     | true    | true           | 
| 4412               | 2018-03-29T00:00:00         | A-L Abatement, Inc.                    | 4299 Fitch Avenue         |                           | Baltimore       | MD               | 21236               | 4108823166   | 4108823170 | Jimmy              | Jerscheid         | true           | false         | false                 | false             | false            | false     |                          | true               | true             | true             | true     | true     | true    | true           | 
```