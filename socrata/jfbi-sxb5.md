# Maryland State Agency Contact Information

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-state-agency-contact-information) |
| Metadata | [Link](https://data.maryland.gov/api/views/jfbi-sxb5) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/jfbi-sxb5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/jfbi-sxb5/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | jfbi-sxb5 |
| Name | Maryland State Agency Contact Information |
| Attribution | Maryland State Archives (MSA) |
| Category | Administrative |
| Tags | state agency, agency, department, executive, phone, email, address |
| Created | 2015-09-18T19:34:45Z |
| Publication Date | 2015-11-16T18:37:08Z |

## Description

This dataset shows the 20 principal departments within Maryland's Executive Branch.  Other agencies are included beyond the 20 principal departments.  Additional information can be found at Maryland State Archives: http://msa.maryland.gov/msa/mdmanual/09dept/html/00list.html

## Columns

```ls
| Included | Schema Type | Field Name                       | Name                             | Data Type | Render Type |
| ======== | =========== | ================================ | ================================ | ========= | =========== |
| No       | time        | :updated_at                      | updated_at                       | meta_data | meta_data   |
| Yes      | series tag  | maryland_department              | Maryland Department Name         | text      | text        |
| No       |             | address                          | Street                           | text      | text        |
| Yes      | series tag  | website                          | Website                          | url       | url         |
| Yes      | series tag  | phone_number                     | Phone Number                     | phone     | phone       |
| Yes      | series tag  | city                             | City                             | text      | text        |
| Yes      | series tag  | zip_code                         | Zip Code                         | text      | text        |
| Yes      | series tag  | toll_free_number                 | Toll Free Number                 | phone     | phone       |
| Yes      | series tag  | maryland_relay_tty               | Maryland Relay (tty)             | phone     | phone       |
| Yes      | series tag  | email                            | Email                            | email     | email       |
| Yes      | series tag  | fax                              | Fax                              | phone     | phone       |
| Yes      | series tag  | toll_free_number_espanol         | Toll Free Number (Espanol)       | phone     | phone       |
| Yes      | series tag  | twitter                          | Twitter                          | url       | url         |
| Yes      | series tag  | facebook                         | Facebook                         | url       | url         |
| Yes      | series tag  | instagram                        | Other                            | url       | url         |
| Yes      | series tag  | pia_representative_name          | PIA Representative Name          | text      | text        |
| No       |             | pia_representative_address       | PIA Representative Address       | text      | text        |
| Yes      | series tag  | pia_representative_phone_number  | PIA Representative Phone Number  | phone     | phone       |
| Yes      | series tag  | pia_representative_email_address | PIA Representative Email Address | email     | email       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address,pia_representative_address
```

## Data Commands

```ls
series e:jfbi-sxb5 d:2015-09-21T05:46:29.000Z t:twitter=https://twitter.com/MDOTNews t:phone_number=Blank t:zip_code=21076 t:website=http://www.mdot.maryland.gov/ t:phone_type=Fax t:maryland_department="DEPARTMENT OF TRANSPORTATION" t:city=Hanover m:row_number.jfbi-sxb5=1

series e:jfbi-sxb5 d:2015-09-21T05:51:52.000Z t:twitter=https://twitter.com/MDDisabilities t:instagram=https://twitter.com/MDIATC t:phone_number=Blank t:zip_code=21201 t:email=info.mdod@maryland.gov t:website=http://www.mdod.maryland.gov t:phone_type=Fax t:facebook=https://www.facebook.com/Maryland-Department-of-Disabilities-105423909499726/timeline/ t:maryland_department="DEPARTMENT OF DISABILITIES" t:city=Baltimore m:row_number.jfbi-sxb5=2

series e:jfbi-sxb5 d:2015-09-21T06:24:50.000Z t:twitter=https://twitter.com/@MDVeterans t:instagram=https://www.facebook.com/MarylandVeterans t:phone_number=Blank t:zip_code=21401 t:email=mdveteransinfo@maryland.gov t:website=http://veterans.maryland.gov/ t:phone_type=Fax t:facebook=https://www.facebook.com/MDVeterans t:maryland_department="DEPARTMENT OF VETERANS AFFAIRS" t:city=Annapolis m:row_number.jfbi-sxb5=3
```

## Meta Commands

```ls
metric m:row_number.jfbi-sxb5 p:long l:"Row Number"

entity e:jfbi-sxb5 l:"Maryland State Agency Contact Information" t:attribution="Maryland State Archives (MSA)" t:url=https://data.maryland.gov/api/views/jfbi-sxb5

property e:jfbi-sxb5 t:meta.view v:id=jfbi-sxb5 v:category=Administrative v:attributionLink=http://msa.maryland.gov/msa/mdmanual/09dept/html/00list.html v:averageRating=0 v:name="Maryland State Agency Contact Information" v:attribution="Maryland State Archives (MSA)"

property e:jfbi-sxb5 t:meta.view.license v:name="Public Domain"

property e:jfbi-sxb5 t:meta.view.owner v:id=9c6n-6ayg v:screenName=aivey v:displayName=aivey

property e:jfbi-sxb5 t:meta.view.tableauthor v:id=9c6n-6ayg v:screenName=aivey v:roleName=publisher v:displayName=aivey
```

## Top Records

```ls
| :updated_at | maryland_department                                           | address                          | website                                                                                    | phone_number           | city      | zip_code | toll_free_number         | maryland_relay_tty      | email                             | fax                   | toll_free_number_espanol | twitter                                                                    | facebook                                                                                                                                                                         | instagram                                                                                | pia_representative_name                               | pia_representative_address                                                                      | pia_representative_phone_number | pia_representative_email_address | 
| =========== | ============================================================= | ================================ | ========================================================================================== | ====================== | ========= | ======== | ======================== | ======================= | ================================= | ===================== | ======================== | ========================================================================== | ================================================================================================================================================================================ | ======================================================================================== | ===================================================== | =============================================================================================== | =============================== | ================================ | 
| 1442814389  | DEPARTMENT OF TRANSPORTATION                                  | 7201 Corporate Center Drive      | [http://www.mdot.maryland.gov/, www.mdot.maryland.gov/]                                    | [(410) 865-1000, Work] | Hanover   | 21076    | [1-888-713-1414, Other]  | [(410) 684-6919, Other] |                                   | [(410) 865-1338, Fax] | [Blank, null]            | [https://twitter.com/MDOTNews, https://twitter.com/MDOTNews]               | [null, null]                                                                                                                                                                     | [null, null]                                                                             |                                                       |                                                                                                 | [null, null]                    |                                  | 
| 1442814712  | DEPARTMENT OF DISABILITIES                                    | 217 East Redwood St., Suite 1300 | [http://www.mdod.maryland.gov, www.mdod.maryland.gov]                                      | [(410) 767-3660, Work] | Baltimore | 21201    | [1-800-637-4113, Other]  | [(410) 767-3660, Other] | info.mdod@maryland.gov            | [(410) 333-6674, Fax] | [Blank, null]            | [https://twitter.com/MDDisabilities, https://twitter.com/MDDisabilities]   | [https://www.facebook.com/Maryland-Department-of-Disabilities-105423909499726/timeline/, https://www.facebook.com/Maryland-Department-of-Disabilities-105423909499726/timeline/] | [https://twitter.com/MDIATC, Twitter: Transitioning Youth]                               |                                                       |                                                                                                 | [null, null]                    |                                  | 
| 1442816690  | DEPARTMENT OF VETERANS AFFAIRS                                | 16 Francis St.                   | [http://veterans.maryland.gov/, http://veterans.maryland.gov/]                             | [(410) 260-3838, Work] | Annapolis | 21401    | [1-866-793-1577, Other]  | [Blank, null]           | mdveteransinfo@maryland.gov       | [(410) 216-7928, Fax] | [Blank, null]            | [https://twitter.com/@MDVeterans, https://twitter.com/@MDVeterans]         | [https://www.facebook.com/MDVeterans, https://www.facebook.com/MDVeterans]                                                                                                       | [https://www.facebook.com/MarylandVeterans, Facebook: Maryland's Commitment to Veterans] |                                                       |                                                                                                 | [null, null]                    |                                  | 
| 1442900932  | DEPARTMENT OF TRANSPORTATION: MARYLAND TRANSIT ADMINISTRATION | 6 St. Paul St.                   | [http://mta.maryland.gov/, http://mta.maryland.gov/]                                       | [(410) 539-5000, Work] | Baltimore | 21202    | [1-866-743-3682, Other]  | [(410) 539-3497, Other] |                                   | [Blank, null]         | [Blank, null]            | [https://twitter.com/mtamaryland, https://twitter.com/mtamaryland]         | [https://www.facebook.com/mtamaryland, null]                                                                                                                                     | [https://www.youtube.com/user/TheMTAMaryland, YouTube]                                   |                                                       |                                                                                                 | [null, null]                    |                                  | 
| 1444292725  | DEPARTMENT OF THE ENVIRONMENT                                 | 1800 Washington Blvd.            | [http://www.mde.maryland.gov, www.mde.maryland.gov]                                        | [(410) 537-3000, Work] | Baltimore | 21230    | [1-800-633-6101, Other]  | [(410) 631-3009, Other] | mde.webmaster@maryland.gov        | [Blank, null]         | [Blank, null]            | [https://twitter.com/MDEnvironment, https://twitter.com/MDEnvironment]     | [https://www.facebook.com/MDEnvironment, https://www.facebook.com/MDEnvironment]                                                                                                 | [https://www.flickr.com/photos/mdenvironment, Flickr]                                    | Amanda R. Degen Interdepartmental Information Liaison | 1800 Washington Blvd Baltimore, MD 21230                                                        | [(410) 537-4120, null]          | amanda.degen@maryland.gov        | 
| 1444288590  | DEPARTMENT OF COMMERCE                                        | 401 East Pratt St.               | [http://business.maryland.gov/, http://business.maryland.gov/]                             | [(410) 767-6300, Work] | Baltimore | 21201    | [800-552-7724, Other]    | [410-767-6960, Other]   | Communications@ChooseMaryland.org | [(410) 333-8628, Fax] | [Blank, null]            | [https://twitter.com/MDBiz, https://twitter.com/MDBiz]                     | [https://www.facebook.com/MarylandBiz, https://www.facebook.com/MarylandBiz]                                                                                                     | [https://www.youtube.com/user/MarylandBiz, YouTube]                                      | Colleen A. Lamont                                     | World Trade Center 401 E. Pratt Street, 9th floor Baltimore, MD 21202                           | [(410) 767-6447, null]          | colleen.lamont@maryland.gov      | 
| 1444292993  | DEPARTMENT OF TRANSPORTATION: STATE HIGHWAY ADMINISTRATION    | 707 North Calvert Street         | [http://www.roads.maryland.gov/, http://www.roads.maryland.gov/]                           | [Blank, null]          | Baltimore | 21202    | [1-800-323-6742, Other]  | [711, Other]            |                                   | [Blank, null]         | [Blank, null]            | [https://twitter.com/MDSHA, https://twitter.com/MDSHA]                     | [https://www.facebook.com/MarylandStateHighwayAdministration, https://www.facebook.com/MarylandStateHighwayAdministration]                                                       | [https://www.youtube.com/user/MDStateHighwayAdmin, YouTube]                              | Gregory Slater (Director)                             | Office of Planning & Preliminary Engineering 707 North Calvert Street, C411 Baltimore, MD 21202 | [(410) 545-0412, null]          | gslater@sha.state.md.us          | 
| 1444288646  | DEPARTMENT OF NATURAL RESOURCES                               | 580 Taylor Ave.                  | [http://dnr2.maryland.gov/Pages/default.aspx, http://dnr2.maryland.gov/Pages/default.aspx] | [(410) 260-8100, Work] | Annapolis | 21401    | [1-877-620-8DNR, Other]  | [(410) 260-8835, Other] | customerservice.dnr@maryland.gov  | [(410) 260-8111, Fax] | [Blank, null]            | [https://twitter.com/accessdnr, https://twitter.com/accessdnr]             | [https://www.facebook.com/AccessDNR/, https://www.facebook.com/AccessDNR/]                                                                                                       | [https://www.youtube.com/user/AccessDNR, YouTube]                                        | Eugene Deems (PIA Coordinator)                        | Office of Communications 580 Taylor Avenue, D4 Annapolis, MD 21401                              | [(410) 260-8014, null]          | Gene.deems@maryland.gov          | 
| 1444288705  | MARYLAND ENERGY ADMINISTRATION                                | 60 West Street, Suite 300        | [http://energy.maryland.gov/, http://energy.maryland.gov/]                                 | [(410) 260-7655, Work] | Annapolis | 21401    | [(800) 72-ENERGY, Other] | [null, null]            | DLinfo_MEA@maryland.gov           | [(410) 974-2250, Fax] | [null, null]             | [http://twitter.com/#!/MDEnergy, http://twitter.com/#!/MDEnergy]           | [https://www.facebook.com/MDEnergyAdministration, https://www.facebook.com/MDEnergyAdministration]                                                                               | [https://instagram.com/meacommunications/, Instagram]                                    | Ralph Scherini (Director of Finance & Admin.)         | 60 West Street, Ste. 300 Annapolis, MD 21401                                                    | [(410) 260-7184, null]          | ralph.scherini@maryland.gov      | 
| 1444290007  | STATE DEPARTMENT OF EDUCATION                                 | 200 West Baltimore St.           | [http://marylandpublicschools.org, marylandpublicschools.org]                              | [410-767-0100, Work]   | Baltimore | 21201    | [1-888-246-0016, Other]  | [Blank, null]           | info.msde@maryland.gov            | [Blank, null]         | [Blank, null]            | [https://twitter.com/MdPublicSchools, https://twitter.com/MdPublicSchools] | [https://www.facebook.com/MdPublicSchools, https://www.facebook.com/MdPublicSchools]                                                                                             | [http://marylandpublicschools.org/MSDE/newsroom/publications/pubsbulletins/, Newsletter] | William Reinhard (Media Relations)                    | 200 W. Baltimore St. Baltimore , MD 21201                                                       | [(410) 767-0486, null]          | william.reinhard@maryland.gov    | 
```