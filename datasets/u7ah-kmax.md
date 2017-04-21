# Weatherization Assistance Program Provider Directory

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/weatherization-assistance-program-provider-directory) |
| Metadata | [Link](https://data.ny.gov/api/views/u7ah-kmax) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/u7ah-kmax/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/u7ah-kmax/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | u7ah-kmax |
| Name | Weatherization Assistance Program Provider Directory |
| Attribution | NYS Homes & Community Renewal |
| Category | Economic Development |
| Tags | energy efficiency, energy audit, wap, weatherization, capital program |
| Created | 2016-02-01T15:48:33Z |
| Publication Date | 2016-02-23T18:00:58Z |

## Description

Directory of providers for the Weatherization Assistance Program serving all 62 counties in the State of New York.

## Columns

```ls
| Included | Schema Type | Field Name                            | Name                                  | Data Type | Render Type |
| ======== | =========== | ===================================== | ===================================== | ========= | =========== |
| No       | time        | :updated_at                           | updated_at                            | meta_data | meta_data   |
| Yes      | series tag  | county                                | County                                | text      | text        |
| Yes      | series tag  | provider                              | Provider                              | text      | text        |
| Yes      | series tag  | provider_business_phone               | Provider Business Phone               | text      | text        |
| Yes      | series tag  | provider_business_phone_2             | Provider Business Phone 2             | text      | text        |
| Yes      | series tag  | service_area                          | Service Area                          | text      | text        |
| Yes      | series tag  | wap_services_and_provider_information | WAP Services and Provider Information | url       | url         |
| Yes      | series tag  | street_address                        | Street Address                        | text      | text        |
| Yes      | series tag  | street_address_2                      | Street Address 2                      | text      | text        |
| Yes      | series tag  | city                                  | City                                  | text      | text        |
| Yes      | series tag  | state                                 | State                                 | text      | text        |
| Yes      | series tag  | zip_code                              | Zip Code                              | text      | text        |
| Yes      | series tag  | website                               | Website                               | url       | url         |
| Yes      | series tag  | email                                 | Email                                 | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:u7ah-kmax d:2016-02-23T09:53:09.000Z t:provider_business_phone="(518) 853-8359" t:zip_code=12068 t:email=fulmontcommunity@hotmail.com t:county=Fulton t:website=http://www.fulmont.org/index.shtml t:service_area="Entire county" t:state=NY t:provider="Fulmont Community Action Agency" t:street_address="20 Park Street" t:wap_services_and_provider_information="https://apps.hcr.ny.gov/LocalHousingOrgLists/Profile.aspx?applid=3234" t:city=Fonda m:row_number.u7ah-kmax=1

series e:u7ah-kmax d:2016-02-23T09:53:09.000Z t:provider_business_phone="(315) 297-4205" t:zip_code=13202 t:email=info@peace-caa.org t:county=Oswego t:website=http://www.peace-caa.org/programs-services/individuals-families-services/energy-and-housing/ t:service_area="Entire county" t:state=NY t:provider="People's Equal Action and Community Effort, Inc." t:street_address="217 S Salina Street" t:wap_services_and_provider_information="https://apps.hcr.ny.gov/LocalHousingOrgLists/Profile.aspx?applid=2405" t:city=Syracuse m:row_number.u7ah-kmax=2

series e:u7ah-kmax d:2016-02-23T09:53:09.000Z t:provider_business_phone="(585) 589-5605 x107" t:zip_code=14411 t:email=info@caoginc.org t:county=Orleans t:website=http://www.caoginc.org/programs/weatherization/ t:service_area="Entire county" t:provider_business_phone_2=1-800-726-0565 t:state=NY t:provider="Community Action of Orleans and Genesee, Inc." t:street_address="409 E State Street" t:wap_services_and_provider_information="https://apps.hcr.ny.gov/LocalHousingOrgLists/Profile.aspx?applid=2687" t:city=Albion m:row_number.u7ah-kmax=3
```

## Meta Commands

```ls
metric m:row_number.u7ah-kmax p:long l:"Row Number"

entity e:u7ah-kmax l:"Weatherization Assistance Program Provider Directory" t:attribution="NYS Homes & Community Renewal" t:url=https://data.ny.gov/api/views/u7ah-kmax

property e:u7ah-kmax t:meta.view v:id=u7ah-kmax v:category="Economic Development" v:attributionLink=http://www.nyshcr.org/Programs/WeatherizationAssistance/ v:averageRating=0 v:name="Weatherization Assistance Program Provider Directory" v:attribution="NYS Homes & Community Renewal"

property e:u7ah-kmax t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:u7ah-kmax t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| :updated_at | county   | provider                                         | provider_business_phone | provider_business_phone_2 | service_area                                                          | wap_services_and_provider_information                                         | street_address        | street_address_2 | city          | state | zip_code | website                                                                                              | email                        | 
| =========== | ======== | ================================================ | ======================= | ========================= | ===================================================================== | ============================================================================= | ===================== | ================ | ============= | ===== | ======== | ==================================================================================================== | ============================ | 
| 1456221189  | Fulton   | Fulmont Community Action Agency                  | (518) 853-8359          |                           | Entire county                                                         | [https://apps.hcr.ny.gov/LocalHousingOrgLists/Profile.aspx?applid=3234, null] | 20 Park Street        |                  | Fonda         | NY    | 12068    | [http://www.fulmont.org/index.shtml, null]                                                           | fulmontcommunity@hotmail.com | 
| 1456221189  | Oswego   | People's Equal Action and Community Effort, Inc. | (315) 297-4205          |                           | Entire county                                                         | [https://apps.hcr.ny.gov/LocalHousingOrgLists/Profile.aspx?applid=2405, null] | 217 S Salina Street   |                  | Syracuse      | NY    | 13202    | [http://www.peace-caa.org/programs-services/individuals-families-services/energy-and-housing/, null] | info@peace-caa.org           | 
| 1456221189  | Orleans  | Community Action of Orleans and Genesee, Inc.    | (585) 589-5605 x107     | 1-800-726-0565            | Entire county                                                         | [https://apps.hcr.ny.gov/LocalHousingOrgLists/Profile.aspx?applid=2687, null] | 409 E State Street    |                  | Albion        | NY    | 14411    | [http://www.caoginc.org/programs/weatherization/, null]                                              | info@caoginc.org             | 
| 1456221189  | Cortland | Cortland County Community Action Program         | (607) 753-6781 x120     |                           | Entire county                                                         | [https://apps.hcr.ny.gov/LocalHousingOrgLists/Profile.aspx?applid=2570, null] | 32 N Main Street      |                  | Cortland      | NY    | 13045    | [http://www.capco.org/index.php/energy-services, null]                                               | info@capco.org               | 
| 1456221189  | Essex    | Adirondack Community Action Program              | (518) 873-3207          | 1-877- 873-2979           | Entire county                                                         | [https://apps.hcr.ny.gov/LocalHousingOrgLists/Profile.aspx?applid=1991, null] | 7572 Court Street     |                  | Elizabethtown | NY    | 12932    | [http://www.acapinc.org/programs1/weatherization/, null]                                             | ballen@acapinc.org           | 
| 1456221189  | Cayuga   | Cayuga/Seneca Community Action Agency            | (315) 255-1703          |                           | Entire county                                                         | [https://apps.hcr.ny.gov/LocalHousingOrgLists/Profile.aspx?applid=1739, null] | 89 YORK ST            |                  | Auburn        | NY    | 13021    | [http://www.cscaa.com/energy_services.html, null]                                                    | sbarnard@cscaa.com           | 
| 1456221189  | Erie     | Supportive Services Corp                         | (716) 685-6252          |                           | Erie County (excluding the City of Buffalo & Cattaraugus Reservation) | [https://apps.hcr.ny.gov/LocalHousingOrgLists/Profile.aspx?applid=3233, null] | 210 St. Mary's Street |                  | Lancaster     | NY    | 14086    | [http://www.supportiveservices.org/weather.html, null]                                               | wx@supportiveservices.org    | 
| 1456221189  | Putnam   | Westchester Community Opportunity Program, Inc.  | (845) 279-5533          |                           | Entire county                                                         | [https://apps.hcr.ny.gov/LocalHousingOrgLists/Profile.aspx?applid=513, null]  | 540 Palmer Road       |                  | Yonkers       | NY    | 10701    | [http://www.westcop.org/, null]                                                                      | jarciola@westcop.org         | 
| 1456221189  | Erie     | Neighborhood Housing Services of South Buffalo   | (716) 837-0071          |                           | City of Buffalo excluding part of the East Side                       | [null, null]                                                                  | 135 Manhattan Avenue  |                  | Buffalo       | NY    | 14215    | [http://www.nhssouthbuffalo.org/weatherization.html, null]                                           | info@nhssouthbuffalo.org     | 
| 1456221189  | Monroe   | PathStone Corporation                            | (585) 442-2030 x202     |                           | Monroe County excluding the City of Rochester                         | [https://apps.hcr.ny.gov/LocalHousingOrgLists/Profile.aspx?applid=315, null]  | 400 East Avenue       |                  | Rochester     | NY    | 14607    | [http://www.pathstoneenergyinfo.org/, null]                                                          | saveenergy@pathstone.org     | 
```