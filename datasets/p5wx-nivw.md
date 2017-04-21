# Currently Licensed Wildlife Rehabilitators

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/currently-licensed-wildlife-rehabilitators) |
| Metadata | [Link](https://data.ny.gov/api/views/p5wx-nivw) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/p5wx-nivw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/p5wx-nivw/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | p5wx-nivw |
| Name | Currently Licensed Wildlife Rehabilitators |
| Attribution | NYS Department of Environmental Conservation (DEC) |
| Category | Energy & Environment |
| Tags | wildlife, rehabilitator |
| Created | 2015-03-26T17:34:15Z |
| Publication Date | 2016-07-20T16:11:51Z |

## Description

This dataset contains contact information for Wildlife Rehabilitators as well as the type of animals they handle.  These rehabilitators are licensed by the New York State Department of Environmental Conservation (DEC) Bureau of Fish and Wildlife Services.

## Columns

```ls
| Included | Schema Type | Field Name              | Name                    | Data Type     | Render Type   |
| ======== | =========== | ======================= | ======================= | ============= | ============= |
| Yes      | series tag  | county                  | County                  | text          | text          |
| Yes      | series tag  | city                    | City                    | text          | text          |
| Yes      | series tag  | species_accepted        | Species Accepted        | text          | text          |
| Yes      | series tag  | rabies_certified        | Rabies Certified        | text          | text          |
| Yes      | series tag  | licensee_name           | Licensee Name           | text          | text          |
| Yes      | series tag  | business_phone          | Business Phone          | text          | number        |
| Yes      | time        | license_effective_date  | License Effective Date  | calendar_date | calendar_date |
| No       |             | license_expiration_date | License Expiration Date | calendar_date | calendar_date |
| Yes      | series tag  | license_type            | License Type            | text          | text          |
| Yes      | series tag  | license_number          | License Number          | text          | text          |
| Yes      | series tag  | federal_permit_number   | Federal Permit Number   | text          | text          |
```

## Time Field

```ls
Value = license_effective_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = license_expiration_date
```

## Data Commands

```ls
series e:p5wx-nivw d:2012-07-25T00:00:00.000Z t:license_type="Wildlife Rehabilitation License - Class I" t:business_phone=9176478166 t:licensee_name="ADAIR (RACHAEL) MORAN" t:county="NEW YORK" t:license_number=1753 t:species_accepted="Small Mammals" t:rabies_certified=No t:city="NEW YORK" m:row_number.p5wx-nivw=1

series e:p5wx-nivw d:2015-10-15T00:00:00.000Z t:license_type="Wildlife Rehabilitation License - Class I" t:business_phone=5187285431 t:licensee_name="Adam L Bornt" t:county=RENSSELAER t:license_number=2095 t:species_accepted="Amphibians, Reptiles" t:rabies_certified=No t:city=Troy m:row_number.p5wx-nivw=2

series e:p5wx-nivw d:2016-02-11T00:00:00.000Z t:license_type="Wildlife Rehabilitation License - Class I" t:business_phone=6317289453 t:licensee_name="ADRIENNE R GILLESPIE" t:county=SUFFOLK t:license_number=1954 t:species_accepted="Amphibians, Large Mammals, Reptiles, Small Mammals" t:rabies_certified=No t:city=SAYVILLE m:row_number.p5wx-nivw=3
```

## Meta Commands

```ls
metric m:row_number.p5wx-nivw p:long l:"Row Number"

entity e:p5wx-nivw l:"Currently Licensed Wildlife Rehabilitators" t:attribution="NYS Department of Environmental Conservation (DEC)" t:url=https://data.ny.gov/api/views/p5wx-nivw

property e:p5wx-nivw t:meta.view v:id=p5wx-nivw v:category="Energy & Environment" v:attributionLink=http://www.dec.ny.gov/animals/83977.html v:averageRating=0 v:name="Currently Licensed Wildlife Rehabilitators" v:attribution="NYS Department of Environmental Conservation (DEC)"

property e:p5wx-nivw t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:p5wx-nivw t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:p5wx-nivw t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| county      | city          | species_accepted                                               | rabies_certified | licensee_name         | business_phone | license_effective_date | license_expiration_date | license_type                                 | license_number | federal_permit_number | 
| =========== | ============= | ============================================================== | ================ | ===================== | ============== | ====================== | ======================= | ============================================ | ============== | ===================== | 
| NEW YORK    | NEW YORK      | Small Mammals                                                  | No               | ADAIR (RACHAEL) MORAN | 9176478166     | 2012-07-25T00:00:00    | 2016-12-31T00:00:00     | Wildlife Rehabilitation License - Class I    | 1753           |                       | 
| RENSSELAER  | Troy          | Amphibians, Reptiles                                           | No               | Adam L Bornt          | 5187285431     | 2015-10-15T00:00:00    | 2019-12-31T00:00:00     | Wildlife Rehabilitation License - Class I    | 2095           |                       | 
| SUFFOLK     | SAYVILLE      | Amphibians, Large Mammals, Reptiles, Small Mammals             | No               | ADRIENNE R GILLESPIE  | 6317289453     | 2016-02-11T00:00:00    | 2018-12-31T00:00:00     | Wildlife Rehabilitation License - Class I    | 1954           |                       | 
| SUFFOLK     | COMMACK       | Amphibians, Reptiles, Small Mammals                            | No               | ALEXANDRA R GALLINA   | 6315790082     | 2016-02-11T00:00:00    | 2018-12-31T00:00:00     | Wildlife Rehabilitation License - Class I    | 2011           |                       | 
| ORANGE      | NEWBURGH      | Amphibians, Game Birds, Reptiles, Small Mammals                | No               | ALEXANDRIA M BENNETT  | 8455429522     | 2012-01-01T00:00:00    | 2016-12-31T00:00:00     | Wildlife Rehabilitation License - Class I    | 1636           |                       | 
| NIAGARA     | Lewiston      | Small Mammals                                                  | No               | Alfred E Kifer        | 7167544719     | 2016-02-11T00:00:00    | 2019-12-31T00:00:00     | Wildlife Rehabilitation License - Class I    | 2082           |                       | 
| CATTARAUGUS | ELLICOTTVILLE | Large Mammals                                                  | No               | ALICE BARES           | 7166992201     | 2016-01-11T00:00:00    | 2020-12-31T00:00:00     | Wildlife Rehabilitation License - Class I    | 1366           |                       | 
| TOMPKINS    | ITHACA        | Amphibians, Game Birds, Reptiles, Small Mammals                | No               | ALICE H VANDEMARK     | 6072533060     | 2016-02-18T00:00:00    | 2020-12-31T00:00:00     | Wildlife Rehabilitation License - Class - II | 111            |                       | 
| NASSAU      | Oyster Bay    | Amphibians, Game Birds, Large Mammals, Reptiles, Small Mammals | No               | ALICIA L GRUBESSI     | 5166740989     | 2014-07-15T00:00:00    | 2018-12-31T00:00:00     | Wildlife Rehabilitation License - Class I    | 1977           |                       | 
| SCHOHARIE   | SLOANSVILLE   | Large Mammals, Small Mammals                                   | No               | ALICIA R MYERS        | 5182314625     | 2016-02-10T00:00:00    | 2016-12-31T00:00:00     | Wildlife Rehabilitation License - Class I    | 1700           |                       | 
```