# Trees Planted by the Port Authority of NY NJ in New York City: Beginning 2008

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/trees-planted-by-the-port-authority-of-ny-nj-in-new-york-city-beginning-2008) |
| Metadata | [Link](https://data.ny.gov/api/views/dxb3-4wp7) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/dxb3-4wp7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/dxb3-4wp7/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | dxb3-4wp7 |
| Name | Trees Planted by the Port Authority of NY NJ in New York City: Beginning 2008 |
| Attribution | Port Authority of New York and New Jersey |
| Category | Energy & Environment |
| Tags | tree, planting, environment, port authority |
| Created | 2013-05-08T15:46:48Z |
| Publication Date | 2013-05-13T16:30:55Z |

## Description

This dataset contains information about trees that have been planted in New York City by the Port Authority of New York and New Jersey from 2008 to 2012.  Trees are planted by the Port Authority or contactors on Port Authority Property.  Tree data includes the tree species, size, location and quantity.

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| Yes      | series tag     | season        | Season        | text      | text        |
| Yes      | numeric metric | quantity      | Quantity      | number    | number      |
| Yes      | series tag     | kind_of_tree  | Kind of Tree  | text      | text        |
| Yes      | series tag     | tree_size     | Tree Size     | text      | text        |
| Yes      | series tag     | borough       | Borough       | text      | text        |
| Yes      | series tag     | property_name | Property Name | text      | text        |
| Yes      | series tag     | property_type | Property Type | text      | text        |
```

## Time Field

```ls
Value = 2008
Format & Zone = yyyy
```

## Data Commands

```ls
series e:dxb3-4wp7 d:2008-01-01T00:00:00.000Z t:property_type="Other (Private)" t:season=Fall08/Spring09 t:property_name="John F. Kennedy International Airport" t:kind_of_tree="Oak (Quercus)" t:borough=Queens t:tree_size="6 ft & up" m:quantity=3

series e:dxb3-4wp7 d:2008-01-01T00:00:00.000Z t:property_type="Other (Private)" t:season=Fall08/Spring09 t:property_name="John F. Kennedy International Airport" t:kind_of_tree="Parrotia (Parrotia)" t:borough=Queens t:tree_size="6 ft & up" m:quantity=4

series e:dxb3-4wp7 d:2008-01-01T00:00:00.000Z t:property_type=Roadway t:season=Fall08/Spring09 t:property_name="Van Wyck Expressway" t:kind_of_tree="Fringetree (Chionanthus)" t:borough=Queens t:tree_size="6 ft & up" m:quantity=12
```

## Meta Commands

```ls
metric m:quantity p:integer l:Quantity t:dataTypeName=number

entity e:dxb3-4wp7 l:"Trees Planted by the Port Authority of NY NJ in New York City:  Beginning 2008" t:attribution="Port Authority of New York and New Jersey" t:url=https://data.ny.gov/api/views/dxb3-4wp7

property e:dxb3-4wp7 t:meta.view v:id=dxb3-4wp7 v:category="Energy & Environment" v:averageRating=0 v:name="Trees Planted by the Port Authority of NY NJ in New York City:  Beginning 2008" v:attribution="Port Authority of New York and New Jersey"

property e:dxb3-4wp7 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:dxb3-4wp7 t:meta.view.tableauthor v:id=kp2w-wfdr v:screenName="Ann Bevins" v:roleName=publisher v:displayName="Ann Bevins"

property e:dxb3-4wp7 t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| season          | quantity | kind_of_tree                 | tree_size | borough | property_name                         | property_type   | 
| =============== | ======== | ============================ | ========= | ======= | ===================================== | =============== | 
| Fall08/Spring09 | 3        | Oak (Quercus)                | 6 ft & up | Queens  | John F. Kennedy International Airport | Other (Private) | 
| Fall08/Spring09 | 4        | Parrotia (Parrotia)          | 6 ft & up | Queens  | John F. Kennedy International Airport | Other (Private) | 
| Fall08/Spring09 | 12       | Fringetree (Chionanthus)     | 6 ft & up | Queens  | Van Wyck Expressway                   | Roadway         | 
| Fall08/Spring09 | 13       | Magnolia (Magnolia)          | 6 ft & up | Queens  | Van Wyck Expressway                   | Roadway         | 
| Fall08/Spring09 | 15       | Pine (Pinus)                 | 6 ft & up | Queens  | Van Wyck Expressway                   | Roadway         | 
| Fall08/Spring09 | 20       | Oak (Quercus)                | 6 ft & up | Queens  | Van Wyck Expressway                   | Roadway         | 
| Fall08/Spring09 | 13       | Cedar (Cedrus)               | 6 ft & up | Queens  | John F. Kennedy International Airport | Other (Private) | 
| Fall08/Spring09 | 3        | Kasturatree (Cercidiphyllum) | 6 ft & up | Queens  | John F. Kennedy International Airport | Other (Private) | 
| Fall08/Spring09 | 16       | Fringetree (Chionanthus)     | 6 ft & up | Queens  | John F. Kennedy International Airport | Other (Private) | 
| Fall08/Spring09 | 6        | Magnolia (Magnolia)          | 6 ft & up | Queens  | John F. Kennedy International Airport | Other (Private) | 
```