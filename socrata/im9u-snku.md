# Tcta 2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/tcta-2015) |
| Metadata | [Link](https://data.austintexas.gov/api/views/im9u-snku) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/im9u-snku/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/im9u-snku/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | im9u-snku |
| Name | Tcta 2015 |
| Category | Government |
| Created | 2015-10-19T19:42:08Z |
| Publication Date | 2015-10-29T19:47:22Z |

## Columns

```ls
| Included | Schema Type | Field Name         | Name               | Data Type | Render Type |
| ======== | =========== | ================== | ================== | ========= | =========== |
| Yes      | series tag  | recreation_centers | Recreation Centers | text      | text        |
| Yes      | series tag  | zip_code           | Zip Code           | text      | text        |
| Yes      | series tag  | phone_number       | Phone Number       | text      | number      |
| Yes      | series tag  | website            | Website            | url       | url         |
| Yes      | series tag  | class_schedule     | Class Schedule     | text      | text        |
| Yes      | series tag  | session            | Session            | text      | text        |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:im9u-snku d:2015-01-01T00:00:00.000Z t:zip_code=78751 t:session="Session 1:  Oct.19-Nov. 12 (Short Film); Session 2: Nov 16-Dec 17 (3D Fibers); Session 3: Jan 4-28 (Photography); Session 4: FEB 1-25 (Painting); Session 5: FEB 29-MAR 31 (Art of Machines)" t:website=http://www.austintexas.gov/department/hancock-recreation-center t:class_schedule="Tuesday and Thursday" t:recreation_centers="Hancock Recreation Center" m:row_number.im9u-snku=1

series e:im9u-snku d:2015-01-01T00:00:00.000Z t:zip_code=78752 t:session="Session 1:  Oct.19-Nov. 12 (Photography); Session 2: Nov 16-Dec 17 (Painting); Session 3: Jan 4-28 (Art of Machines); Session 4: FEB 1-25 (Short Film); Session 5: FEB 29-MAR 31 (3D Fibers)" t:website=http://www.austintexas.gov/department/virginia-l-brown-recreation-center t:class_schedule="Tuesday and Thursday" t:recreation_centers="Virginia L. Brown Recreation Center" m:row_number.im9u-snku=2

series e:im9u-snku d:2015-01-01T00:00:00.000Z t:zip_code=78702 t:session="Session 1:  Oct.19-Nov. 12 (Art of Machines); Session 2: Nov 16-Dec 17 (Short Film); Session 3: Jan 4-28 (3D Fibers); Session 4: FEB 1-25 (Photography); Session 5: FEB 29-MAR 31 (Painting)" t:website=http://www.austintexas.gov/department/oswaldo-ab-cantupan-american-recreation-center t:class_schedule="Tuesday and Thursday" t:recreation_centers="Oswaldo A. B. Cantu/Pan American Recreation Center" m:row_number.im9u-snku=3
```

## Meta Commands

```ls
metric m:row_number.im9u-snku p:long l:"Row Number"

entity e:im9u-snku l:"Tcta 2015" t:url=https://data.austintexas.gov/api/views/im9u-snku

property e:im9u-snku t:meta.view v:id=im9u-snku v:category=Government v:attributionLink=http://www.austintexas.gov/tcta v:averageRating=0 v:name="Tcta 2015"

property e:im9u-snku t:meta.view.license v:name="Public Domain"

property e:im9u-snku t:meta.view.owner v:id=wpqw-45f6 v:screenName=Betty v:displayName=Betty

property e:im9u-snku t:meta.view.tableauthor v:id=wpqw-45f6 v:screenName=Betty v:roleName=editor v:displayName=Betty
```

## Top Records

```ls
| recreation_centers                                 | zip_code | phone_number | website                                                                                      | class_schedule       | session                                                                                                                                                                                     | 
| ================================================== | ======== | ============ | ============================================================================================ | ==================== | =========================================================================================================================================================================================== | 
| Hancock Recreation Center                          | 78751    |              | [http://www.austintexas.gov/department/hancock-recreation-center, null]                      | Tuesday and Thursday | Session 1: Oct.19-Nov. 12 (Short Film); Session 2: Nov 16-Dec 17 (3D Fibers); Session 3: Jan 4-28 (Photography); Session 4: FEB 1-25 (Painting); Session 5: FEB 29-MAR 31 (Art of Machines) | 
| Virginia L. Brown Recreation Center                | 78752    |              | [http://www.austintexas.gov/department/virginia-l-brown-recreation-center, null]             | Tuesday and Thursday | Session 1: Oct.19-Nov. 12 (Photography); Session 2: Nov 16-Dec 17 (Painting); Session 3: Jan 4-28 (Art of Machines); Session 4: FEB 1-25 (Short Film); Session 5: FEB 29-MAR 31 (3D Fibers) | 
| Oswaldo A. B. Cantu/Pan American Recreation Center | 78702    |              | [http://www.austintexas.gov/department/oswaldo-ab-cantupan-american-recreation-center, null] | Tuesday and Thursday | Session 1: Oct.19-Nov. 12 (Art of Machines); Session 2: Nov 16-Dec 17 (Short Film); Session 3: Jan 4-28 (3D Fibers); Session 4: FEB 1-25 (Photography); Session 5: FEB 29-MAR 31 (Painting) | 
| Turner-Roberts Recreation Center                   | 78724    |              | [http://www.austintexas.gov/department/turner-roberts-recreation-center, null]               | Monday and Wednesday | Session 1: Oct.19-Nov. 12 (Painting); Session 2: Nov 16-Dec 17 (Art of Machines); Session 3: Jan 4-28 (Short Film); Session 4: FEB 1-25 (3D Fibers); Session 5: FEB 29-MAR 31 (Photography) | 
| Montopolis Recreation Center                       | 78741    |              | [http://www.austintexas.gov/department/montopolis-recreation-center, null]                   | Monday and Wednesday | Session 1: Oct.19-Nov. 12 (Short Film); Session 2: Nov 16-Dec 17 (3D Fibers); Session 3: Jan 4-28 (Photography); Session 4: FEB 1-25 (Painting); Session 5: FEB 29-MAR 31 (Art of Machines) | 
| Parque Zaragoza Recreation Center                  | 78702    |              | [http://www.austintexas.gov/department/parque-zaragoza-recreation-center, null]              | Tuesday and Thursday | Session 1: Oct.19-Nov. 12 (Art of Machines); Session 2: Nov 16-Dec 17 (Short Film); Session 3: Jan 4-28 (3D Fibers); Session 4: FEB 1-25 (Photography); Session 5: FEB 29-MAR 31 (Painting) | 
| South Austin Recreation Center                     | 78704    |              | [http://www.austintexas.gov/department/south-austin-recreation-center, null]                 | Monday and Wednesday | Session 1: Oct.19-Nov. 12 (Photography); Session 2: Nov 16-Dec 17 (Painting); Session 3: Jan 4-28 (Art of Machines); Session 4: FEB 1-25 (Short Film); Session 5: FEB 29-MAR 31 (3D Fibers) | 
| Delores Duffie Recreation Center                   | 78702    |              | [http://www.austintexas.gov/department/rosewood-recreation-center, null]                     | Monday and Wednesday | Session 1: Oct.19-Nov. 12 (Art of Machines); Session 2: Nov 16-Dec 17 (Short Film); Session 3: Jan 4-28 (3D Fibers); Session 4: FEB 1-25 (Photography); Session 5: FEB 29-MAR 31 (Painting) | 
| Gustavo "Gus" L. Garcia Recration Center           | 78753    |              | [http://www.austintexas.gov/department/gus-garcia-recreation-center, null]                   | Tuesday and Thursday | Session 1: Oct.19-Nov. 12 (Painting); Session 2: Nov 16-Dec 17 (Art of Machines); Session 3: Jan 4-28 (Short Film); Session 4: FEB 1-25 (3D Fibers); Session 5: FEB 29-MAR 31 (Photography) | 
| Dove Springs Recreation Center                     | 78744    |              | [http://www.austintexas.gov/DoveSprings, null]                                               | Tuesday and Thursday | Session 1: Oct.19-Nov. 12 (3D Fibers); Session 2: Nov 16-Dec 17 (Photography); Session 3: Jan 4-28 (Painting); Session 4: FEB 1-25 (Art of Machines); Session 5: FEB 29-MAR 31 (Short Film) | 
```