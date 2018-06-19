# Percentage of Juvenile Arrests by Race 2002 - 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/percentage-of-juvenile-arrests-by-race-2002-2012) |
| Metadata | [Link](https://data.wa.gov/api/views/dpeg-hp5b) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/dpeg-hp5b/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/dpeg-hp5b/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | dpeg-hp5b |
| Name | Percentage of Juvenile Arrests by Race 2002 - 2012 |
| Attribution | Office of Juvenile Justice |
| Category | Demographics |
| Tags | juvenile justice, annual report, wa-pcjj report, office of juvenile justice, dshs, race, arrests, youth |
| Created | 2015-12-23T05:03:22Z |
| Publication Date | 2016-01-18T23:08:09Z |

## Columns

```ls
| Included | Schema Type    | Field Name       | Name                | Data Type | Render Type |
| ======== | ============== | ================ | =================== | ========= | =========== |
| Yes      | series tag     | race             | Race                | text      | text        |
| Yes      | numeric metric | 2012             | 2012                | number    | text        |
| Yes      | numeric metric | 2011             | 2011                | number    | text        |
| Yes      | numeric metric | 2010             | 2010                | number    | text        |
| Yes      | numeric metric | 2009             | 2009                | number    | text        |
| Yes      | numeric metric | 2008             | 2008                | number    | text        |
| Yes      | numeric metric | 2007             | 2007                | number    | text        |
| Yes      | numeric metric | 2006             | 2006                | number    | text        |
| Yes      | numeric metric | 2005             | 2005                | number    | text        |
| Yes      | numeric metric | 2004             | 2004                | number    | text        |
| Yes      | numeric metric | 2003             | 2003                | number    | text        |
| Yes      | numeric metric | 2002             | 2002                | number    | text        |
| Yes      | series tag     | 2002_2012_change | 2002 -2012 % Change | text      | text        |
```

## Time Field

```ls
Value = 2002
Format & Zone = yyyy
```

## Data Commands

```ls
series e:dpeg-hp5b d:2002-01-01T00:00:00.000Z t:2002_2012_change=-5.3% t:race="White (Hispanic)" m:2008=83.4 m:2009=83.1 m:2006=83 m:2007=82.4 m:2004=83.9 m:2005=82.8 m:2002=84.9 m:2003=84.6 m:2012=80.4 m:2011=82.6 m:2010=83.9

series e:dpeg-hp5b d:2002-01-01T00:00:00.000Z t:2002_2012_change=43.2% t:race="Black (Hispanic)" m:2008=11 m:2009=11.4 m:2006=11.3 m:2007=11.8 m:2004=10 m:2005=10.8 m:2002=9.5 m:2003=9.5 m:2012=13.6 m:2011=11.7 m:2010=10.6

series e:dpeg-hp5b d:2002-01-01T00:00:00.000Z t:2002_2012_change=3.4% t:race="Native American (Hispanic)" m:2008=3 m:2009=3 m:2006=3.2 m:2007=2.9 m:2004=3.4 m:2005=3.6 m:2002=2.9 m:2003=3 m:2012=3 m:2011=2.8 m:2010=2.8
```

## Meta Commands

```ls
metric m:2012 p:float l:2012 t:dataTypeName=number

metric m:2011 p:float l:2011 t:dataTypeName=number

metric m:2010 p:float l:2010 t:dataTypeName=number

metric m:2009 p:float l:2009 t:dataTypeName=number

metric m:2008 p:float l:2008 t:dataTypeName=number

metric m:2007 p:float l:2007 t:dataTypeName=number

metric m:2006 p:float l:2006 t:dataTypeName=number

metric m:2005 p:float l:2005 t:dataTypeName=number

metric m:2004 p:float l:2004 t:dataTypeName=number

metric m:2003 p:float l:2003 t:dataTypeName=number

metric m:2002 p:float l:2002 t:dataTypeName=number

entity e:dpeg-hp5b l:"Percentage of Juvenile Arrests by Race 2002 - 2012" t:attribution="Office of Juvenile Justice" t:url=https://data.wa.gov/api/views/dpeg-hp5b

property e:dpeg-hp5b t:meta.view v:id=dpeg-hp5b v:category=Demographics v:attributionLink=https://dshs.wa.gov/ra/office-juvenile-justice/washington-state-juvenile-justice-annual-report v:averageRating=0 v:name="Percentage of Juvenile Arrests by Race 2002 - 2012" v:attribution="Office of Juvenile Justice"

property e:dpeg-hp5b t:meta.view.license v:name="Public Domain"

property e:dpeg-hp5b t:meta.view.owner v:id=6p7r-jviv v:profileImageUrlMedium=/api/users/6p7r-jviv/profile_images/THUMB v:profileImageUrlLarge=/api/users/6p7r-jviv/profile_images/LARGE v:screenName="Alysa Kipersztok" v:profileImageUrlSmall=/api/users/6p7r-jviv/profile_images/TINY v:displayName="Alysa Kipersztok"

property e:dpeg-hp5b t:meta.view.tableauthor v:id=6p7r-jviv v:profileImageUrlMedium=/api/users/6p7r-jviv/profile_images/THUMB v:profileImageUrlLarge=/api/users/6p7r-jviv/profile_images/LARGE v:screenName="Alysa Kipersztok" v:profileImageUrlSmall=/api/users/6p7r-jviv/profile_images/TINY v:roleName=viewer v:displayName="Alysa Kipersztok"
```

## Top Records

```ls
| race                       | 2012 | 2011 | 2010 | 2009 | 2008 | 2007 | 2006 | 2005 | 2004 | 2003 | 2002 | 2002_2012_change | 
| ========================== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ================ | 
| White (Hispanic)           | 80.4 | 82.6 | 83.9 | 83.1 | 83.4 | 82.4 | 83.0 | 82.8 | 83.9 | 84.6 | 84.9 | -5.3%            | 
| Black (Hispanic)           | 13.6 | 11.7 | 10.6 | 11.4 | 11.0 | 11.8 | 11.3 | 10.8 | 10.0 | 9.5  | 9.5  | 43.2%            | 
| Native American (Hispanic) | 3.0  | 2.8  | 2.8  | 3.0  | 3.0  | 2.9  | 3.2  | 3.6  | 3.4  | 3.0  | 2.9  | 3.4%             | 
| Asian (Hispanic)           | 3.0  | 2.9  | 2.6  | 2.5  | 2.6  | 2.8  | 2.5  | 2.8  | 2.7  | 2.9  | 2.8  | 7.1%             | 
```