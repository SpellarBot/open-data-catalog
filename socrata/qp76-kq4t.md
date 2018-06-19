# Hatchery Broodstock Tracking Update SoS 2012 Exp --OLD

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hatchery-broodstock-tracking-update-sos-2012-exp-old) |
| Metadata | [Link](https://data.wa.gov/api/views/qp76-kq4t) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/qp76-kq4t/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/qp76-kq4t/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | qp76-kq4t |
| Name | Hatchery Broodstock Tracking Update SoS 2012 Exp --OLD |
| Attribution | WDFW HEAT Unit |
| Category | Natural Resources & Environment |
| Tags | sos, hatchery broodstock heat, wdfw, salmon |
| Created | 2012-08-28T20:11:46Z |
| Publication Date | 2012-08-28T20:13:15Z |

## Description

WDFW HEAT Hatchery Broodstock Tracking Update for SoS

## Columns

```ls
| Included | Schema Type | Field Name              | Name                    | Data Type | Render Type |
| ======== | =========== | ======================= | ======================= | ========= | =========== |
| Yes      | series tag  | region_name             | Region Name             | text      | text        |
| Yes      | series tag  | species                 | Species                 | text      | text        |
| Yes      | time        | year                    | Year                    | number    | text        |
| Yes      | series tag  | total_hatchery_programs | Total Hatchery Programs | text      | text        |
| Yes      | series tag  | hsrg_compliant          | HSRG Compliant          | text      | text        |
| Yes      | series tag  | percent                 | Percent                 | text      | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
```

## Meta Commands

```ls
entity e:qp76-kq4t l:"Hatchery Broodstock Tracking Update SoS 2012 Exp --OLD" t:attribution="WDFW HEAT Unit" t:url=https://data.wa.gov/api/views/qp76-kq4t

property e:qp76-kq4t t:meta.view v:id=qp76-kq4t v:category="Natural Resources & Environment" v:averageRating=0 v:name="Hatchery Broodstock Tracking Update SoS 2012 Exp --OLD" v:attribution="WDFW HEAT Unit"

property e:qp76-kq4t t:meta.view.owner v:id=b2s6-8ii9 v:profileImageUrlMedium=/api/users/b2s6-8ii9/profile_images/THUMB v:profileImageUrlLarge=/api/users/b2s6-8ii9/profile_images/LARGE v:screenName="Brodie Cox" v:profileImageUrlSmall=/api/users/b2s6-8ii9/profile_images/TINY v:displayName="Brodie Cox"

property e:qp76-kq4t t:meta.view.tableauthor v:id=b2s6-8ii9 v:profileImageUrlMedium=/api/users/b2s6-8ii9/profile_images/THUMB v:profileImageUrlLarge=/api/users/b2s6-8ii9/profile_images/LARGE v:screenName="Brodie Cox" v:profileImageUrlSmall=/api/users/b2s6-8ii9/profile_images/TINY v:roleName=publisher v:displayName="Brodie Cox"
```

## Top Records

```ls
| region_name | species          | year | total_hatchery_programs | hsrg_compliant | percent | 
| =========== | ================ | ==== | ======================= | ============== | ======= | 
| Puget Sound | Chinook Salmon   | 1998 | 23                      | 9              | 39      | 
| Puget Sound | Coho Salmon      | 1998 | 11                      | 2              | 18      | 
| Puget Sound | Steelhead        | 1998 | 14                      | 1              | 7       | 
| Puget Sound | Fall Chum Salmon | 1998 | NA                      | NA             | NA      | 
| Puget Sound | Chinook Salmon   | 2008 | 20                      | 9              | 45      | 
| Puget Sound | Coho Salmon      | 2008 | 10                      | 4              | 40      | 
| Puget Sound | Steelhead        | 2008 | 14                      | 3              | 21      | 
| Puget Sound | Fall Chum Salmon | 2008 | NA                      | NA             | NA      | 
| Puget Sound | Chinook Salmon   | 2010 | 18                      | 8              | 44      | 
| Puget Sound | Coho Salmon      | 2010 | 9                       | 7              | 78      | 
```