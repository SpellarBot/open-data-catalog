# Missouri Certified Incubators Contact Information

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/missouri-certified-incubators-contact-information) |
| Metadata | [Link](https://data.mo.gov/api/views/nc6i-4sv2) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/nc6i-4sv2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/nc6i-4sv2/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | nc6i-4sv2 |
| Name | Missouri Certified Incubators Contact Information |
| Category | Economic Development |
| Created | 2016-09-22T19:03:04Z |
| Publication Date | 2016-12-09T16:11:45Z |

## Columns

```ls
| Included | Schema Type | Field Name                     | Name                           | Data Type | Render Type |
| ======== | =========== | ============================== | ============================== | ========= | =========== |
| No       | time        | :updated_at                    | updated_at                     | meta_data | meta_data   |
| Yes      | series tag  | incubator                      | Incubator                      | text      | text        |
| Yes      | series tag  | sponsor                        | Sponsor                        | text      | text        |
| Yes      | series tag  | certified_year                 | Certified Year                 | text      | text        |
| Yes      | series tag  | contact_person                 | Contact Person                 | text      | text        |
| Yes      | series tag  | street_address                 | Street Address                 | text      | text        |
| Yes      | series tag  | city                           | City                           | text      | text        |
| Yes      | series tag  | zip_code                       | Zip Code                       | text      | text        |
| No       |             | additional_address_information | Additional Address Information | text      | text        |
| Yes      | series tag  | phone_number                   | Phone Number                   | phone     | phone       |
| Yes      | series tag  | fax_number                     | Fax Number                     | phone     | phone       |
| Yes      | series tag  | email                          | Email                          | email     | email       |
| Yes      | series tag  | secondary_email                | Secondary Email                | email     | email       |
| Yes      | series tag  | website                        | Website                        | url       | url         |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = additional_address_information
```

## Data Commands

```ls
series e:nc6i-4sv2 d:2016-09-30T19:48:56.000Z t:phone_number="(314) 802-0995" t:incubator="BEGIN New Venture Center" t:zip_code=63101 t:certified_year="Certified in 2010" t:email=susiewildman@st.patrickcenter.org t:website=http://www.stpatrickcenter.org t:contact_person="Susie Wildman" t:street_address="800 N. Tucker Blvd" t:sponsor="St. Patrick?s Center" t:city="St. Louis" m:row_number.nc6i-4sv2=1

series e:nc6i-4sv2 d:2016-09-30T19:56:39.000Z t:phone_number="(785) 764-9904" t:incubator="Bunker Labs-Kansas City" t:zip_code=64108 t:certified_year="Certified in 2016" t:email=sean.mcintosh@bunkerlabs.org t:contact_person="Sean R. McIntosh" t:street_address="1100 Main St." t:sponsor="The Bunker KC NFP Inc." t:city="Kansas City" m:row_number.nc6i-4sv2=2

series e:nc6i-4sv2 d:2016-09-30T19:49:48.000Z t:phone_number="(816) 463-3532" t:incubator="Independence Regional Ennovation Center" t:zip_code=64050-3436 t:certified_year="Certified in 2010" t:email=lee@inedc.biz t:website=http://www.ennovationcenter.com/ t:contact_person="Lee Langerock" t:street_address="201 N. Forest Ave" t:sponsor="Independence Council for Economic Development" t:city=Independence m:row_number.nc6i-4sv2=3
```

## Meta Commands

```ls
metric m:row_number.nc6i-4sv2 p:long l:"Row Number"

entity e:nc6i-4sv2 l:"Missouri Certified Incubators Contact Information" t:url=https://data.mo.gov/api/views/nc6i-4sv2

property e:nc6i-4sv2 t:meta.view v:id=nc6i-4sv2 v:category="Economic Development" v:averageRating=0 v:name="Missouri Certified Incubators Contact Information"

property e:nc6i-4sv2 t:meta.view.owner v:id=jzbz-iqr6 v:screenName=Breanna v:lastNotificationSeenAt=1492723347 v:displayName=Breanna

property e:nc6i-4sv2 t:meta.view.tableauthor v:id=jzbz-iqr6 v:screenName=Breanna v:roleName=administrator v:lastNotificationSeenAt=1492723347 v:displayName=Breanna
```

## Top Records

```ls
| :updated_at | incubator                                                                                                       | sponsor                                       | certified_year    | contact_person                   | street_address             | city           | zip_code   | additional_address_information | phone_number           | fax_number             | email                              | secondary_email | website                                             | 
| =========== | =============================================================================================================== | ============================================= | ================= | ================================ | ========================== | ============== | ========== | ============================== | ====================== | ====================== | ================================== | =============== | =================================================== | 
| 1475264936  | BEGIN New Venture Center                                                                                        | St. Patrick?s Center                          | Certified in 2010 | Susie Wildman                    | 800 N. Tucker Blvd         | St. Louis      | 63101      |                                | [(314) 802-0995, null] | [null, null]           | susiewildman@st.patrickcenter.org  |                 | [http://www.stpatrickcenter.org, null]              | 
| 1475265399  | Bunker Labs-Kansas City                                                                                         | The Bunker KC NFP Inc.                        | Certified in 2016 | Sean R. McIntosh                 | 1100 Main St.              | Kansas City    | 64108      |                                | [(785) 764-9904, null] | [null, null]           | sean.mcintosh@bunkerlabs.org       |                 | [null, null]                                        | 
| 1475264988  | Independence Regional Ennovation Center                                                                         | Independence Council for Economic Development | Certified in 2010 | Lee Langerock                    | 201 N. Forest Ave          | Independence   | 64050-3436 | #130                           | [(816) 463-3532, null] | [null, null]           | lee@inedc.biz                      |                 | [http://www.ennovationcenter.com/, null]            | 
| 1475265156  | Joseph Newman Business and Technology Innovation Center (JNBTIC)                                                | Joplin Area Chamber of Commerce Foundation    | Certified in 2004 | Steve Russell                    | 320 E. 4th St.             | Joplin         | 64801      |                                | [(417) 624-4150, null] | [(417) 624-4303, null] | steve@joplinincc.com               |                 | [http://www.newmaninnovationcenter.com, null]       | 
| 1475265186  | Institute for Industrial and Applied Life Sciences DBA Innovation Stockyard (FKA Kit Bond Science & Technology) | Missouri Western State University             | Certified in 2010 | Sara Hagan                       | 4221 Mitchell Avenue       | St. Joseph     | 64507-2266 |                                | [(816) 749-4014, null] | [(816) 271-5972, null] | Sara.hagen@innovationstockyard.com |                 | [http://www.missouriwestern.edu/lifesciences, null] | 
| 1475265212  | Life Sciences Business Incubation Center (LSBIC)                                                                | Missouri Innovation Center                    | Certified in 2004 | Quinten Messbarger ; Bill Turpin | 1601 S. Providence         | Columbia       | 65211      |                                | [(573) 884-0492, null] | [(573) 884-3600, null] | messbargerq@missouri.edu           |                 | [http://www.muincubator.com, null]                  | 
| 1475265236  | Ozarks Small Business Incubator                                                                                 | Downtown West Plains, Inc.                    | Certified in 2010 | Heather Fisher                   | 408 Washington Ave.        | West Plains    | 65775      | P.O. Box 1194                  | [(417) 256-9724, null] | [(417) 255-8799, null] | heatherfisher@ozsbi.com            |                 | [http://www.ozsbi.com, null]                        | 
| 1475265252  | Small Business Synergy Center (SBSC)                                                                            | Small Business Synergy Center                 | Certified in 1992 | Craig Frahm                      | 5988 Mid Rivers Mall Drive | St. Charles    | 63304      |                                | [(636) 441-6880, null] | [null, null]           | cfrahm@edcscc.com                  |                 | [http://www.stcc-edc.com, null]                     | 
| 1475265274  | Southeast Missouri Innovation Center (SMIC)                                                                     | Missouri Research Corporation                 | Certified in 2005 | Brian Tapp                       | 920 Broadway               | Cape Girardeau | 63701      |                                | [(573) 651-2570, null] | [(573) 651-5061, null] | btapp@semo.edu                     |                 | [http://www.semo.edu/cie/, null]                    | 
| 1475265299  | St. Louis Enterprise Center-Wellston (StLEC)                                                                    | St. Louis County Economic Council             | Certified in 1990 | Tracy Jackson                    | 6439 Plymouth Ave.         | Wellston       | 63133      |                                | [(314) 615-0118, null] | [(314) 615-7666, null] | TJackson@stlpartnership.com        |                 | [http://www.slcec.com, null]                        | 
```