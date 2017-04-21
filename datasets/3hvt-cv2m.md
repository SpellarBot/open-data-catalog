# Continuing Education Courses for Private Sewage

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/continuing-education-courses-for-private-sewage) |
| Metadata | [Link](https://data.illinois.gov/api/views/3hvt-cv2m) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/3hvt-cv2m/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/3hvt-cv2m/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 3hvt-cv2m |
| Name | Continuing Education Courses for Private Sewage |
| Attribution | IDPH - Division of Environmental Health |
| Category | Public Health |
| Tags | continuing education, private sewage |
| Created | 2014-06-04T16:53:49Z |
| Publication Date | 2017-01-27T16:17:19Z |

## Description

This dataset provides Continuing Education opportunities for the Private Sewage licensees, which include Portable Sanitation, Installation & Pumping Contractors. Last Update January 2017

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type     | Render Type   |
| ======== | ============== | =================== | =================== | ============= | ============= |
| Yes      | time           | course_date         | Course Date         | calendar_date | calendar_date |
| Yes      | series tag     | time                | Time                | text          | text          |
| Yes      | series tag     | contact_person      | Contact Person      | text          | text          |
| Yes      | series tag     | phone_number        | Phone Number        | text          | text          |
| Yes      | series tag     | sponsor_association | Sponsor/Association | text          | text          |
| Yes      | series tag     | sponsor_e_mail      | Sponsor E-Mail      | email         | email         |
| Yes      | series tag     | street_address      | Street Address      | text          | text          |
| Yes      | series tag     | city                | City                | text          | text          |
| Yes      | series tag     | state               | State               | text          | text          |
| Yes      | series tag     | zip_code            | ZIP Code            | text          | number        |
| Yes      | series tag     | license_type        | License type        | text          | text          |
| Yes      | numeric metric | contact_hours       | Contact hours       | number        | text          |
```

## Time Field

```ls
Value = course_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:3hvt-cv2m d:2016-02-22T00:00:00.000Z t:time="8:00 AM to 5:00 PM" t:license_type="Installers, Pumpers" t:sponsor_association="Water & Wastewater Equipment, Treatment & Trasport Show" t:phone_number=1-877-978-7322 t:state=46225 t:contact_person="Cindy Barrand" t:street_address=Indianapolis t:city=Indiana m:contact_hours=6

series e:3hvt-cv2m d:2017-01-31T00:00:00.000Z t:time="8:00 AM to 4:45 PM" t:license_type=Pumpers t:sponsor_association="Onsite Wastwater Professionals of Illinois" t:phone_number=217-328-7796 t:zip_code=62234 t:state=Illinois t:contact_person="Steve Johnson" t:street_address="1 Gateway Center Drive" t:sponsor_e_mail=contact@owpi.org t:city=Collinsville m:contact_hours=2

series e:3hvt-cv2m d:2017-01-12T00:00:00.000Z t:time="8:30 AM - 5:30 PM" t:license_type="Pumping and Portable Sanitation Contractors" t:sponsor_association="Illinois Association of Local Environmental Health Administrotors" t:phone_number="1-217-431-2662 ext. 243" t:zip_code=61704 t:state=Illinois t:contact_person="Doug Toole" t:street_address="1621 Jumer Drive" t:sponsor_e_mail=dtoole@vchd.org t:city=Bloomington m:contact_hours=3
```

## Meta Commands

```ls
metric m:contact_hours p:float l:"Contact hours" t:dataTypeName=number

entity e:3hvt-cv2m l:"Continuing Education Courses for Private Sewage" t:attribution="IDPH - Division of Environmental Health" t:url=https://data.illinois.gov/api/views/3hvt-cv2m

property e:3hvt-cv2m t:meta.view v:id=3hvt-cv2m v:category="Public Health" v:attributionLink=http://dph.illinois.gov/topics-services/environmental-health-protection/private-sewage-disposal v:averageRating=0 v:name="Continuing Education Courses for Private Sewage" v:attribution="IDPH - Division of Environmental Health"

property e:3hvt-cv2m t:meta.view.license v:name="Public Domain"

property e:3hvt-cv2m t:meta.view.owner v:id=mkk8-dris v:screenName="Greg Matheny" v:displayName="Greg Matheny"

property e:3hvt-cv2m t:meta.view.tableauthor v:id=mkk8-dris v:screenName="Greg Matheny" v:roleName=publisher v:displayName="Greg Matheny"
```

## Top Records

```ls
| course_date         | time               | contact_person   | phone_number            | sponsor_association                                               | sponsor_e_mail        | street_address          | city         | state    | zip_code | license_type                                              | contact_hours | 
| =================== | ================== | ================ | ======================= | ================================================================= | ===================== | ======================= | ============ | ======== | ======== | ========================================================= | ============= | 
| 2016-02-22T00:00:00 | 8:00 AM to 5:00 PM | Cindy Barrand    | 1-877-978-7322          | Water & Wastewater Equipment, Treatment & Trasport Show           |                       | Indianapolis            | Indiana      | 46225    |          | Installers, Pumpers                                       | 6             | 
| 2017-01-31T00:00:00 | 8:00 AM to 4:45 PM | Steve Johnson    | 217-328-7796            | Onsite Wastwater Professionals of Illinois                        | contact@owpi.org      | 1 Gateway Center Drive  | Collinsville | Illinois | 62234    | Pumpers                                                   | 2             | 
| 2017-01-12T00:00:00 | 8:30 AM - 5:30 PM  | Doug Toole       | 1-217-431-2662 ext. 243 | Illinois Association of Local Environmental Health Administrotors | dtoole@vchd.org       | 1621 Jumer Drive        | Bloomington  | Illinois | 61704    | Pumping and Portable Sanitation Contractors               | 3             | 
| 2017-01-12T00:00:00 | 8:30 AM - 5:30 PM  | Doug Toole       | 1-217-431-2662 ext. 243 | Illinois Association of Local Environmental Health Administrotors | dtoole@vchd.org       | 1621 Jumer Drive        | Bloomington  | Illinois | 61704    | Installation Contractors                                  | 6             | 
| 2017-03-14T00:00:00 | 11:30 AM - 3:30 PM | Douglas Ebelherr | 1-815-761-3842          | Chase Environmental Services, Inc.                                | dougebelherr2@aol.com | 515 South Main          | Wauconda     | Illinois | 60084    | Installation, Pumping and Portable Sanitation Contractors | 3             | 
| 2017-03-28T00:00:00 | 11:00 AM - 4:00 PM | Douglas Ebelherr | 1-815-761-3842          | Chase Environmental Services, Inc.                                | dougebelherr2@aol.com | 570 Gary Avenue         | Carol Stream | Illinois | 60188    | Portable Sanitation Training & Exam                       | 3             | 
| 2017-03-15T00:00:00 | 11:30 AM - 3:30 PM | Douglas Ebelherr | 1-815-761-3842          | Chase Environmental Services, Inc.                                | dougebelherr2@aol.com | 940 Galena Square Drive | Galena       | Illinois | 61036    | Installation, Pumping and Portable Sanitation Contractors | 3             | 
| 2017-02-01T00:00:00 | 11:30 AM - 3:30 PM | Douglas Ebelherr | 1-815-761-3842          | Chase Environmental Services, Inc.                                | dougebelherr2@aol.com | 123 West Market Street  | Troy         | Illinois | 62294    | Installation, Pumping and Portable Sanitation Contractors | 3             | 
| 2017-02-28T00:00:00 | 11:30 AM - 3:30 PM | Douglas Ebelherr | 1-815-761-3842          | Chase Environmental Services, Inc.                                | dougebelherr2@aol.com | 700 South 36th Street   | Quincy       | Illinois | 62301    | Installation, Pumping and Portable Sanitation Contractors | 3             | 
| 2017-01-31T00:00:00 | 8:00 AM to 4:45 PM | Steve Johnson    | 217-328-7796            | Onsite Wastwater Professionals of Illinois                        | contact@owpi.org      | 1 Gateway Center Drive  | Collinsville | Illinois | 62234    | Installers                                                | 4             | 
```