# Victim Assistance Program (VAP) Business Offices

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/victim-assistance-program-vap-business-offices) |
| Metadata | [Link](https://data.ny.gov/api/views/wykp-id5i) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/wykp-id5i/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/wykp-id5i/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | wykp-id5i |
| Name | Victim Assistance Program (VAP) Business Offices |
| Attribution | Office of Victim Services |
| Category | Human Services |
| Created | 2014-08-27T15:35:06Z |
| Publication Date | 2016-08-05T20:45:43Z |

## Description

Since 1981, OVS has had a legislative appropriation for the purpose of making grants for the provision of local victim/witness assistance and services. Initially, twenty-three programs received grant funds for this purpose. Currently, 186 victim/witness assistance programs have grant awards from the OVS, ranging from $32,000 to over $1.8 million. OVS supports statewide, comprehensive victim/witness assistance services in all sectors of the community. Criminal justice agencies, non-profit victim programs and specific municipal programs all receive support. Examples include DA offices, Probation Departments, YWCAs, local police departments, hospitals, and nonprofit organizations. This data set contains all service locations associated with OVS VOCA awards. It should be noted that some programs do not have a physical address listed, instead, they show a PO Box. In these cases the physical addresses are safeguarded as they are generally Domestic Violence shelters providing services to victims who may be in danger were their location to be disclosed.

## Columns

```ls
| Included | Schema Type    | Field Name   | Name                                    | Data Type | Render Type |
| ======== | ============== | ============ | ======================================= | ========= | =========== |
| No       | time           | :updated_at  | updated_at                              | meta_data | meta_data   |
| Yes      | series tag     | vap_name     | Victim Assistance Program (VAP) Name    | text      | text        |
| Yes      | series tag     | vap_number   | VAP Number                              | text      | number      |
| No       |                | address_1    | Address 1                               | text      | text        |
| No       |                | address_2    | Address 2                               | text      | text        |
| Yes      | series tag     | city         | City                                    | text      | text        |
| Yes      | series tag     | state        | State                                   | text      | text        |
| Yes      | series tag     | zip_code     | ZIP Code                                | text      | text        |
| Yes      | series tag     | county       | County                                  | text      | text        |
| No       |                | w1           | Primary Telephone Number (W1)           | number    | number      |
| Yes      | numeric metric | w1_extension | Primary Telephone Number (W1) Extension | number    | number      |
| Yes      | numeric metric | hotline      | Hotline                                 | number    | number      |
| Yes      | numeric metric | hotline_ext  | Hotline Extension                       | number    | number      |
| Yes      | series tag     | web_site     | Web Site                                | url       | url         |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address_1,address_2,w1
```

## Data Commands

```ls
series e:wykp-id5i d:2016-08-05T11:39:18.000Z t:vap_number=50 t:zip_code=14851 t:county=Tompkins t:state=NY t:vap_name="Advocacy Center of Tompkins County" t:web_site=http://www.manta.com/c/mt1fr11/the-advocacy-center-of-tompkins-county t:city=Ithaca m:hotline=6072775000

series e:wykp-id5i d:2016-08-05T11:39:18.000Z t:vap_number=617 t:zip_code=12742 t:county=Sullivan t:state=NY t:vap_name="Catskill Regional Medical Center" t:web_site=http://www.crmcny.org t:city=Harris m:hotline=8457919595

series e:wykp-id5i d:2016-08-05T11:39:18.000Z t:vap_number=188 t:zip_code=14454 t:county=Livingston t:state=NY t:vap_name="Chances and Changes" t:web_site=http://www.chancesandchanges.org t:city=Geneseo m:hotline=8882529360
```

## Meta Commands

```ls
metric m:w1_extension p:integer l:"Primary Telephone Number (W1) Extension" d:"Primary Telephone number extension that will take caller to program." t:dataTypeName=number

metric m:hotline p:long l:Hotline d:"Crisis phone number for callers in critical need of assistance. This may be operational 24/7, but not necessarily." t:dataTypeName=number

metric m:hotline_ext p:long l:"Hotline Extension" d:"Crisis phone number extension that will take caller to program." t:dataTypeName=number

entity e:wykp-id5i l:"Victim Assistance Program (VAP) Business Offices" t:attribution="Office of Victim Services" t:url=https://data.ny.gov/api/views/wykp-id5i

property e:wykp-id5i t:meta.view v:id=wykp-id5i v:category="Human Services" v:averageRating=0 v:name="Victim Assistance Program (VAP) Business Offices" v:attribution="Office of Victim Services"

property e:wykp-id5i t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:wykp-id5i t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:wykp-id5i t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | vap_name                                        | vap_number | address_1                     | address_2               | city      | state | zip_code | county     | w1         | w1_extension | hotline    | hotline_ext | web_site                                                                      | 
| =========== | =============================================== | ========== | ============================= | ======================= | ========= | ===== | ======== | ========== | ========== | ============ | ========== | =========== | ============================================================================= | 
| 1470397158  | Advocacy Center of Tompkins County              | 50         | P.O. Box 164                  |                         | Ithaca    | NY    | 14851    | Tompkins   | 6072773203 |              | 6072775000 |             | [http://www.manta.com/c/mt1fr11/the-advocacy-center-of-tompkins-county, null] | 
| 1470397158  | Bivona Child Advocacy Center                    | 610        | The Skalny Building           | 1 Mount Hope Avenue     | Rochester | NY    | 14620    | Monroe     | 5859357800 |              |            |             | [http://www.BivonaCAC.org, null]                                              | 
| 1470397158  | Brighter Tomorrows, Inc.                        | 632        | PO Box 706                    |                         | Shirley   | NY    | 11967    | Suffolk    | 6313951801 |              |            |             | [null, null]                                                                  | 
| 1470397158  | Catskill Regional Medical Center                | 617        | 68 Harris Bushville Road      |                         | Harris    | NY    | 12742    | Sullivan   | 8457943300 |              | 8457919595 |             | [http://www.crmcny.org, null]                                                 | 
| 1470397158  | Chances and Changes                             | 188        | P.O. Box 326                  |                         | Geneseo   | NY    | 14454    | Livingston | 5856583940 |              | 8882529360 |             | [http://www.chancesandchanges.org, null]                                      | 
| 1470397158  | Day One                                         | 620        | PO Box 1507 Canal St. Station |                         | New York  | NY    | 10013    | New York   | 2125668120 |              |            |             | [http://dayoneny.org, null]                                                   | 
| 1470397158  | Edwin Gould Services for Children and Famililes | 631        | POBox 287326                  |                         | New York  | NY    | 10128    | New York   | 6463157600 |              |            |             | [null, null]                                                                  | 
| 1470397158  | Erie County Probation                           | 192        | One Niagara Plaza             |                         | Buffalo   | NY    | 14202    | Erie       | 7168586402 |              |            |             | [http://www.erie.gov/depts/probation/, null]                                  | 
| 1470397158  | HANAC, Inc.                                     | 62         | George T. Douris Tower        | 27-40 Hoyt Avenue South | Astoria   | NY    | 11102    | Queens     | 7187283811 |              |            |             | [http://www.hanac.org/, null]                                                 | 
| 1470397158  | Harlem Hospital Center                          | 140        | Social Work Office, Rm. 6111  | 506 Lenox Avenue        | New York  | NY    | 10037    | New York   | 2129394613 |              |            |             | [http://www.ci.nyc.ny.us/html/hhc/html/facilities/harlem.shtml, null]         | 
```