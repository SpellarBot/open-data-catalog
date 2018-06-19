# Lead Paint Inspectors

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lead-paint-inspectors) |
| Metadata | [Link](https://data.maryland.gov/api/views/djk4-5e3j) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/djk4-5e3j/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/djk4-5e3j/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | djk4-5e3j |
| Name | Lead Paint Inspectors |
| Attribution | MDE |
| Category | Energy and Environment |
| Tags | lead, lead paint, paint, inspector, mde |
| Created | 2014-05-06T19:25:41Z |
| Publication Date | 2017-04-07T18:19:37Z |

## Description

The Inspection Contractors (IC) listed have been accredited/licensed by the Maryland Department of the Environment to provide lead paint inspection services. The Inspection Contractors qualify to perform different types of inspections based on the accreditation category(ies) of the inspector(s) that work for the contractor. There are three kinds of lead paint inspectors. They qualify in the following ways:
Visual Inspector (VI) - May perform Full or Modified Risk Reduction Inspections. This is done by a Dust Inspection or a Visual Inspection after unit has been prepared for inspection by an accredited lead paint abatement contractor. Visual Inspectors may also perform testing for Clearance.
Inspector Technician (IT) - May perform Lead Free Inspections. This is done by X-ray testing or paint chip analysis of all surfaces. Inspector Technicians may also perform testing for Clearance.
Risk Assessor (RA) - May perform all the functions of a VI and IT. Risk Assessors may also perform Lead Hazard Screenings and Risk Assessments. Risk Assessors may identify lead hazards and make recommendations from analysis of X-ray testing, paint chips, dust, soil, water and questionnaires. Risk Assessors may also perform testing for Clearance.
Disclaimer:
For your convenience MDE publishes this list of accredited lead contractors that meet Maryland?s standards to perform abatement activities involving lead-based paint. The list is an information resource only. MDE does not endorse any of the contractors included on this list nor does MDE provide any warranty about their performance. Consumers are advised to request bids and conduct reference checks before hiring. Contact the individual contractors for information regarding services and fees. Verify with the contractor you are going to hire that the inspector is accredited by MDE. This accreditation and training does not satisfy the EPA Renovation, Repair and Painting (RRP) Rule.
If you have questions regarding official inspection or abatement work procedures call MDE at 410-537-3825.

## Columns

```ls
| Included | Schema Type | Field Name                       | Name                             | Data Type     | Render Type   |
| ======== | =========== | ================================ | ================================ | ============= | ============= |
| Yes      | series tag  | accreditation_certificate_number | Accreditation Certificate Number | text          | number        |
| Yes      | time        | certificate_expiration_date      | Certificate Expiration Date      | calendar_date | calendar_date |
| Yes      | series tag  | contractor_name                  | Contractor Name                  | text          | text          |
| No       |             | contractor_address_line_1        | Contractor Address Line 1        | text          | text          |
| No       |             | contractor_address_line_2        | Contractor Address Line 2        | text          | text          |
| Yes      | series tag  | contractor_city                  | Contractor City                  | text          | text          |
| Yes      | series tag  | contractor_state                 | Contractor State                 | text          | text          |
| Yes      | series tag  | contractor_zip                   | Contractor ZIP                   | text          | number        |
| Yes      | series tag  | contractor_phone                 | Contractor Phone                 | text          | number        |
| Yes      | series tag  | contractor_fax                   | Contractor Fax                   | text          | number        |
| Yes      | series tag  | contact_first_name               | Contact First Name               | text          | text          |
| Yes      | series tag  | contact_last_name                | Contact Last Name                | text          | text          |
| Yes      | series tag  | baltimore_region                 | Baltimore Region                 | checkbox      | checkbox      |
| Yes      | series tag  | eastern_shore                    | Eastern Shore                    | checkbox      | checkbox      |
| Yes      | series tag  | washington_dc_suburbs            | Washington, DC Suburbs           | checkbox      | checkbox      |
| Yes      | series tag  | southern_maryland                | Southern Maryland                | checkbox      | checkbox      |
| Yes      | series tag  | western_maryland                 | Western Maryland                 | checkbox      | checkbox      |
| Yes      | series tag  | statewide                        | Statewide                        | checkbox      | checkbox      |
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
series e:djk4-5e3j d:2017-09-01T00:00:00.000Z t:washington_dc_suburbs=true t:southern_maryland=true t:baltimore_region=true t:contractor_name="# 1 A&A Absolute, LLC" t:contractor_state=MD t:contact_first_name=Patrick t:statewide=true t:contractor_phone=4433541911 t:accreditation_certificate_number=15321 t:contractor_city=Brooklyn t:western_maryland=true t:eastern_shore=true t:contact_last_name=Hibbard t:contractor_zip=21225 m:row_number.djk4-5e3j=1

series e:djk4-5e3j d:2018-06-12T00:00:00.000Z t:washington_dc_suburbs=true t:southern_maryland=true t:baltimore_region=true t:contractor_name="# 1 Absolute Home Inspections" t:contractor_state=MD t:contact_first_name="Joseph Daniel" t:statewide=true t:contractor_phone=4434001101 t:accreditation_certificate_number=14722 t:contractor_city=Baltimore t:western_maryland=true t:eastern_shore=true t:contact_last_name="Elrod, Jr." t:contractor_zip=21220 m:row_number.djk4-5e3j=2

series e:djk4-5e3j d:2019-01-14T00:00:00.000Z t:washington_dc_suburbs=true t:southern_maryland=true t:baltimore_region=true t:contractor_name="# 1 Aisles Lead Services" t:contractor_state=MD t:contact_first_name=Melissa t:statewide=true t:contractor_phone=4104290816 t:accreditation_certificate_number=13855 t:contractor_city=Baltimore t:western_maryland=true t:eastern_shore=true t:contact_last_name=Isles t:contractor_zip=21234 m:row_number.djk4-5e3j=3
```

## Meta Commands

```ls
metric m:row_number.djk4-5e3j p:long l:"Row Number"

entity e:djk4-5e3j l:"Lead Paint Inspectors" t:attribution=MDE t:url=https://data.maryland.gov/api/views/djk4-5e3j

property e:djk4-5e3j t:meta.view v:id=djk4-5e3j v:category="Energy and Environment" v:averageRating=0 v:name="Lead Paint Inspectors" v:attribution=MDE

property e:djk4-5e3j t:meta.view.license v:name="Public Domain"

property e:djk4-5e3j t:meta.view.owner v:id=6wh5-kegk v:profileImageUrlMedium=/api/users/6wh5-kegk/profile_images/THUMB v:profileImageUrlLarge=/api/users/6wh5-kegk/profile_images/LARGE v:screenName="Andrew Gosden" v:profileImageUrlSmall=/api/users/6wh5-kegk/profile_images/TINY v:lastNotificationSeenAt=1491588421 v:displayName="Andrew Gosden"

property e:djk4-5e3j t:meta.view.tableauthor v:id=6wh5-kegk v:profileImageUrlMedium=/api/users/6wh5-kegk/profile_images/THUMB v:profileImageUrlLarge=/api/users/6wh5-kegk/profile_images/LARGE v:screenName="Andrew Gosden" v:profileImageUrlSmall=/api/users/6wh5-kegk/profile_images/TINY v:roleName=editor v:lastNotificationSeenAt=1491588421 v:displayName="Andrew Gosden"
```

## Top Records

```ls
| accreditation_certificate_number | certificate_expiration_date | contractor_name                   | contractor_address_line_1 | contractor_address_line_2 | contractor_city | contractor_state | contractor_zip | contractor_phone | contractor_fax | contact_first_name | contact_last_name | baltimore_region | eastern_shore | washington_dc_suburbs | southern_maryland | western_maryland | statewide | 
| ================================ | =========================== | ================================= | ========================= | ========================= | =============== | ================ | ============== | ================ | ============== | ================== | ================= | ================ | ============= | ===================== | ================= | ================ | ========= | 
| 15321                            | 2017-09-01T00:00:00         | # 1 A&A Absolute, LLC             | P.O. Box 19643            |                           | Brooklyn        | MD               | 21225          | 4433541911       |                | Patrick            | Hibbard           | true             | true          | true                  | true              | true             | true      | 
| 14722                            | 2018-06-12T00:00:00         | # 1 Absolute Home Inspections     | 1522 Chilworth Avenue     |                           | Baltimore       | MD               | 21220          | 4434001101       |                | Joseph Daniel      | Elrod, Jr.        | true             | true          | true                  | true              | true             | true      | 
| 13855                            | 2019-01-14T00:00:00         | # 1 Aisles Lead Services          | PO Box 10913              |                           | Baltimore       | MD               | 21234          | 4104290816       |                | Melissa            | Isles             | true             | true          | true                  | true              | true             | true      | 
| 15390                            | 2017-10-16T00:00:00         | #01 Lead Free Certifications      | 51 Gwynns Mill Court      |                           | Owings Mills    | MD               | 21117          | 4439561113       |                | Jory               | Schunick          | true             | true          | true                  | true              | true             | true      | 
| 15390                            | 2018-12-19T00:00:00         | #01 Lead Free Certifications, LLC | 51 Gwynns Mill Court      |                           | Owings Mills    | MD               | 21117          | 4439561113       |                | Jory               | Schunick          | true             | true          | true                  | true              | true             | true      | 
| 15057                            | 2017-06-11T00:00:00         | #1 A & A Abatement                | 5344 Reisterstown Road    |                           | Baltimore       | MD               | 21215          | 4103361800       |                | Harold             | Morgan            | true             | true          | true                  | true              | true             | true      | 
| 14067                            | 2017-07-23T00:00:00         | #1 A&A Certified                  | 413 Latimer Road          |                           | Joppa           | MD               | 21085          | 4106685672       |                | Alexander McGill   | Watt, Jr.         | true             | false         | false                 | false             | false            | false     | 
| 16329                            | 2018-12-22T00:00:00         | #1 A1 Environmental Services LLC  | 3103 Kentucky Avenue      |                           | Baltimore       | MD               | 21213          | 4433145388       |                | Davonte            | Griffin           | true             | true          | true                  | true              | true             | true      | 
| 13735                            | 2018-09-15T00:00:00         | #1 Above Lead Services LLC        | PO Box 501                |                           | Odenton         | MD               | 21113          | 2405067040       |                | R. Antonio         | Wright            | true             | true          | true                  | true              | true             | true      | 
| 13773                            | 2017-04-24T00:00:00         | #1 Affordable Lead Pros LLC       | 10421 Motor City Drive #3 |                           | Bethesda        | MD               | 20827          | 4104690157       |                | Jonathan           | Rogers            | true             | true          | true                  | true              | true             | true      | 
```