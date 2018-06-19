# Directory of Aging and Disability Community Resources

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/directory-of-aging-and-disability-community-resources) |
| Metadata | [Link](https://data.ny.gov/api/views/jwv3-3scj) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/jwv3-3scj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/jwv3-3scj/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | jwv3-3scj |
| Name | Directory of Aging and Disability Community Resources |
| Attribution | New York State Office for the Aging |
| Category | Human Services |
| Tags | aging, aging resources, aging offices, hiicap, ltcop, ny connects, aaa |
| Created | 2013-12-23T18:49:28Z |
| Publication Date | 2016-11-08T16:34:02Z |

## Description

This data set from NYS Office for the Aging (OFA) provides a listing of community resources to help the public find services for older and disabled New Yorkers.  Included is information on:  AAAs (Area Agencies on Aging), local offices that plan, develop and support comprehensive in-home and community services; HIICAPs (Health Insurance Information Counseling Program) that provide free, accurate and objective information, counseling, assistance and advocacy on Medicare, private health insurance, and related health coverage plans; LTCOP (Long Term Care Ombudsman Program) office resources and advocates for older adults and persons with disabilities who live in nursing homes, assisted living and other licensed adult care homes; and NYConnects, trusted places for information and assistance about long term services and supports whether you are paying for services yourself, through insurance, or eligible for a government program.

## Columns

```ls
| Included | Schema Type | Field Name         | Name               | Data Type | Render Type |
| ======== | =========== | ================== | ================== | ========= | =========== |
| No       | time        | :updated_at        | updated_at         | meta_data | meta_data   |
| Yes      | series tag  | nysofa_county_code | NYSOFA County Code | text      | text        |
| Yes      | series tag  | county_name        | County Name        | text      | text        |
| Yes      | series tag  | resource_type      | Resource Type      | text      | text        |
| Yes      | series tag  | service_provider   | Service Provider   | text      | text        |
| Yes      | series tag  | street_address     | Street Address     | text      | text        |
| Yes      | series tag  | city               | City               | text      | text        |
| Yes      | series tag  | state              | State              | text      | text        |
| Yes      | series tag  | zip                | Zip                | text      | number      |
| Yes      | series tag  | phone              | Phone              | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:jwv3-3scj d:2016-11-07T23:00:22.000Z t:zip=13902 t:phone="607- 778 - 2411" t:service_provider="Broome County Office for the Aging" t:nysofa_county_code=03 t:resource_type=AAA t:state=NY t:street_address="Broome Co. Office Bldg." t:county_name=Broome t:city=Binghamton m:row_number.jwv3-3scj=1

series e:jwv3-3scj d:2016-11-07T23:00:22.000Z t:zip=14760 t:phone="716- 373 - 8032" t:service_provider="Cattaraugus County Department of the Aging" t:nysofa_county_code=04 t:resource_type=AAA t:state=NY t:street_address="One Leo Moss Drive" t:county_name=Cattaraugus t:city=Olean m:row_number.jwv3-3scj=2

series e:jwv3-3scj d:2016-11-07T23:00:22.000Z t:zip=14902 t:phone="607- 737 - 5520" t:service_provider="Chemung County Dept. of Aging & Long Term Care" t:nysofa_county_code=07 t:resource_type=AAA t:state=NY t:street_address="P.O. Box 588" t:county_name=Chemung t:city=Elmira m:row_number.jwv3-3scj=3
```

## Meta Commands

```ls
metric m:row_number.jwv3-3scj p:long l:"Row Number"

entity e:jwv3-3scj l:"Directory of Aging and Disability Community Resources" t:attribution="New York State Office for the Aging" t:url=https://data.ny.gov/api/views/jwv3-3scj

property e:jwv3-3scj t:meta.view v:id=jwv3-3scj v:category="Human Services" v:attributionLink=http://aging.ny.gov v:averageRating=0 v:name="Directory of Aging and Disability Community Resources" v:attribution="New York State Office for the Aging"

property e:jwv3-3scj t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:jwv3-3scj t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:jwv3-3scj t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | nysofa_county_code | county_name | resource_type | service_provider                               | street_address                 | city       | state | zip   | phone            | 
| =========== | ================== | =========== | ============= | ============================================== | ============================== | ========== | ===== | ===== | ================ | 
| 1478559622  | 03                 | Broome      | AAA           | Broome County Office for the Aging             | Broome Co. Office Bldg.        | Binghamton | NY    | 13902 | 607- 778 - 2411  | 
| 1478559622  | 04                 | Cattaraugus | AAA           | Cattaraugus County Department of the Aging     | One Leo Moss Drive             | Olean      | NY    | 14760 | 716- 373 - 8032  | 
| 1478559622  | 07                 | Chemung     | AAA           | Chemung County Dept. of Aging & Long Term Care | P.O. Box 588                   | Elmira     | NY    | 14902 | 607- 737 - 5520  | 
| 1478559622  | 08                 | Chenango    | AAA           | Chenango County Area Agency on Aging           | County Office Building         | Norwich    | NY    | 13815 | 607- 337 - 1770  | 
| 1478559622  | 11                 | Cortland    | AAA           | Cortland County Area Agency on Aging           | County Office Building         | Cortland   | NY    | 13045 | 607- 753 - 5060  | 
| 1478559622  | 18                 | Genesee     | AAA           | Genesee County Office for the Aging            | Batavia-Genesee Senior Center  | Batavia    | NY    | 14020 | 585- 343 - 1611  | 
| 1478559622  | 28                 | Nassau      | AAA           | Nassau County Department of Human Services     | Office for the Aging           | Uniondale  | NY    | 11553 | (516) 227 - 8900 | 
| 1478559622  | 34                 | Orleans     | AAA           | Orleans County Office for the Aging            | County Administration Building | Albion     | NY    | 14411 | 585- 589 - 3191  | 
| 1478559622  | 35                 | Oswego      | AAA           | Oswego County Office for the Aging             | P.O. Box 3080                  | Oswego     | NY    | 13126 | 315- 349 - 3484  | 
| 1478559622  | 38                 | Rensselaer  | AAA           | Rensselaer County Unified Family Services      | Department for the Aging       | Troy       | NY    | 12180 | 518- 270 - 2730  | 
```