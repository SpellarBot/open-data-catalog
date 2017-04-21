# IDPH Modular Dwellings

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idph-modular-dwellings-48de4) |
| Metadata | [Link](https://data.illinois.gov/api/views/5xra-wi7t) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/5xra-wi7t/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/5xra-wi7t/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 5xra-wi7t |
| Name | IDPH Modular Dwellings |
| Attribution | Division of Environmental Health |
| Category | Public Health |
| Created | 2012-03-28T18:12:17Z |
| Publication Date | 2017-03-02T14:47:45Z |

## Description

Modular Dwellings. Updated March 2017.

## Columns

```ls
| Included | Schema Type | Field Name           | Name                 | Data Type | Render Type |
| ======== | =========== | ==================== | ==================== | ========= | =========== |
| No       | time        | :updated_at          | updated_at           | meta_data | meta_data   |
| Yes      | series tag  | name_of_manufacturer | Name of Manufacturer | text      | text        |
| Yes      | series tag  | status               | Status               | text      | text        |
| No       |             | address              | Address              | text      | text        |
| Yes      | series tag  | city                 | City                 | text      | text        |
| Yes      | series tag  | state                | State                | text      | text        |
| Yes      | series tag  | zip                  | Zip                  | text      | text        |
| Yes      | series tag  | phone_number         | Phone Number         | phone     | phone       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:5xra-wi7t d:2013-04-02T13:51:40.000Z t:zip=46540 t:phone_number=574/825-9999 t:status="Inactive or Out of Business" t:state=IN t:name_of_manufacturer="Admiration Builders" t:city=Middlebury m:row_number.5xra-wi7t=1

series e:5xra-wi7t d:2013-04-02T13:51:40.000Z t:zip=61920 t:phone_number=217/345?3921 t:status="Inactive or Out of Business" t:state=IL t:name_of_manufacturer="Advance Building Systems" t:city=Charleston m:row_number.5xra-wi7t=2

series e:5xra-wi7t d:2013-04-02T13:51:40.000Z t:zip=47441 t:phone_number=812/847-8924 t:status="Inactive or Out of Business" t:state=IN t:name_of_manufacturer="Advanced Building Concepts" t:city=Linton m:row_number.5xra-wi7t=3
```

## Meta Commands

```ls
metric m:row_number.5xra-wi7t p:long l:"Row Number"

entity e:5xra-wi7t l:"IDPH Modular Dwellings" t:attribution="Division of Environmental Health" t:url=https://data.illinois.gov/api/views/5xra-wi7t

property e:5xra-wi7t t:meta.view v:id=5xra-wi7t v:category="Public Health" v:attributionLink=http://www.idph.state.il.us/envhealth/ehhome.htm v:averageRating=0 v:name="IDPH Modular Dwellings" v:attribution="Division of Environmental Health"

property e:5xra-wi7t t:meta.view.owner v:id=vice-rsdw v:profileImageUrlMedium=/api/users/vice-rsdw/profile_images/THUMB v:profileImageUrlLarge=/api/users/vice-rsdw/profile_images/LARGE v:screenName="IDPH Staff" v:profileImageUrlSmall=/api/users/vice-rsdw/profile_images/TINY v:displayName="IDPH Staff"

property e:5xra-wi7t t:meta.view.tableauthor v:id=vice-rsdw v:profileImageUrlMedium=/api/users/vice-rsdw/profile_images/THUMB v:profileImageUrlLarge=/api/users/vice-rsdw/profile_images/LARGE v:screenName="IDPH Staff" v:profileImageUrlSmall=/api/users/vice-rsdw/profile_images/TINY v:roleName=publisher v:displayName="IDPH Staff"
```

## Top Records

```ls
| :updated_at | name_of_manufacturer                  | status                      | address                                   | city        | state | zip   | phone_number         | 
| =========== | ===================================== | =========================== | ========================================= | =========== | ===== | ===== | ==================== | 
| 1364910700  | Admiration Builders                   | Inactive or Out of Business | 11133 C.R. 2                              | Middlebury  | IN    | 46540 | [574/825-9999, null] | 
| 1364910700  | Advance Building Systems              | Inactive or Out of Business | 750 West State                            | Charleston  | IL    | 61920 | [217/345?3921, null] | 
| 1364910700  | Advanced Building Concepts            | Inactive or Out of Business | 325 S.E. 12th Street                      | Linton      | IN    | 47441 | [812/847-8924, null] | 
| 1364910700  | Advanced Laminated Housing Structures | Inactive or Out of Business | P.O. Box 70, 52400 S.R. 15 North          | Bristol     | IN    | 46507 | [574/848-9504, null] | 
| 1364910700  | Adventure Homes                       |                             | 1119 Fuller Drive                         | Garrett     | IN    | 46738 | [260/357-1948, null] | 
| 1364910700  | All American Homes                    |                             | P.O. Box 219, 1551 15th Avenue S.E.       | Dyersville  | IA    | 52040 | [563/875?2421, null] | 
| 1364910700  | All American Homes                    |                             | 1418 South 13th Street                    | Decatur     | IN    | 46733 | [260/724?9171, null] | 
| 1364910700  | All American Homes                    | Inactive or Out of Business | 102 Evergreen Drive, P.O. Box 890         | Springfield | TN    | 37172 | [615/382-7111, null] | 
| 1364910700  | All American Kan Build Homes          | Inactive or Out of Business | Nichols Road & Hwy. 31 East, P.O. Box 259 | Osage City  | KS    | 66523 | [800/343?2783, null] | 
| 1364910700  | American Family Homes (Taylor Homes)  | Inactive or Out of Business | P.O. Box 438                              | Anderson    | MO    | 64831 | [417/845?3311, null] | 
```