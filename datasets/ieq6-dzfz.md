# Crime & Safety (2010-2012)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/crime-safety-2010-2012-5a953) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/ieq6-dzfz) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/ieq6-dzfz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/ieq6-dzfz/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | ieq6-dzfz |
| Name | Crime & Safety (2010-2012) |
| Attribution | The Baltimore Neighborhood Indicators Alliance-Jacob France Institute at the University of Baltimore (known as BNIA-JFI) |
| Category | Neighborhoods |
| Tags | crime, neighborhoods, bnia |
| Created | 2014-05-20T15:47:42Z |
| Publication Date | 2014-05-20T15:53:58Z |

## Description

Most indicators throughout Vital Signs are created by acquiring and analyzing data collected from governmental agencies for some public administration purpose, such as 311 calls or housing inspections. However, data from the United States Bureau of the Census remains the best source for demographic and socioeconomic indicators for neighborhoods. The Census Bureau collects a wide variety of information through administration of both the decennial Census and the annual American Community Survey (ACS).

## Columns

```ls
| Included | Schema Type    | Field Name | Name      | Data Type | Render Type |
| ======== | ============== | ========== | ========= | ========= | =========== |
| Yes      | series tag     | csa2010    | CSA2010   | text      | text        |
| Yes      | numeric metric | crime10    | crime10   | number    | number      |
| Yes      | numeric metric | crime11    | crime11   | number    | number      |
| Yes      | numeric metric | crime12    | crime12   | number    | number      |
| Yes      | numeric metric | viol10     | viol10    | number    | number      |
| Yes      | numeric metric | viol11     | viol11    | number    | number      |
| Yes      | numeric metric | viol12     | viol12    | number    | number      |
| Yes      | numeric metric | prop11     | prop11    | number    | number      |
| Yes      | numeric metric | prop12     | prop12    | number    | number      |
| Yes      | numeric metric | juvarr11   | juvarr11  | number    | number      |
| Yes      | numeric metric | juvviol11  | juvviol11 | number    | number      |
| Yes      | numeric metric | juvdrug11  | juvdrug11 | number    | number      |
| Yes      | numeric metric | domvio10   | domvio10  | number    | number      |
| Yes      | numeric metric | domvio11   | domvio11  | number    | number      |
| Yes      | numeric metric | shoot11    | shoot11   | number    | number      |
| Yes      | numeric metric | caslt11    | caslt11   | number    | number      |
| Yes      | numeric metric | narc11     | narc11    | number    | number      |
| Yes      | numeric metric | caracc11   | caracc11  | number    | number      |
| Yes      | numeric metric | gunhom11   | gunhom11  | number    | number      |
| Yes      | numeric metric | gunhom12   | gunhom12  | number    | number      |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ieq6-dzfz d:2010-01-01T00:00:00.000Z t:csa2010="Allendale/Irvington/S. Hilton" m:crime11=46.2 m:narc11=78.8 m:crime12=45.4 m:crime10=40.6 m:juvviol11=12.4 m:juvdrug11=22.2 m:prop12=31.6 m:caslt11=84.4 m:viol10=12.6 m:prop11=33.7 m:gunhom11=0.2 m:gunhom12=0.6 m:viol11=12.5 m:viol12=13.9 m:domvio11=65.4 m:caracc11=44 m:domvio10=59.4 m:shoot11=2.5 m:juvarr11=54.8

series e:ieq6-dzfz d:2010-01-01T00:00:00.000Z t:csa2010="Beechfield/Ten Hills/West Hills" m:crime11=36.1 m:narc11=24.7 m:crime12=36.6 m:crime10=33.6 m:juvviol11=9.1 m:juvdrug11=5.3 m:prop12=29.6 m:caslt11=51.2 m:viol10=8.4 m:prop11=28.9 m:gunhom11=0.2 m:gunhom12=0.2 m:viol11=7.2 m:viol12=7 m:domvio11=44.8 m:caracc11=31.9 m:domvio10=47.9 m:shoot11=2 m:juvarr11=22

series e:ieq6-dzfz d:2010-01-01T00:00:00.000Z t:csa2010=Belair-Edison m:crime11=57.1 m:narc11=50.2 m:crime12=52.7 m:crime10=50.3 m:juvviol11=17.5 m:juvdrug11=16.2 m:prop12=37.7 m:caslt11=77.6 m:viol10=13.3 m:prop11=43 m:gunhom11=0.3 m:gunhom12=0.3 m:viol11=14.1 m:viol12=14.9 m:domvio11=57.8 m:caracc11=45.4 m:domvio10=51.1 m:shoot11=1.5 m:juvarr11=54.8
```

## Meta Commands

```ls
metric m:crime10 p:float l:crime10 d:"Part 1 Crime Rate per 1,000 Residents (2010)" t:dataTypeName=number

metric m:crime11 p:float l:crime11 d:"Part 1 Crime Rate per 1,000 Residents (2011)" t:dataTypeName=number

metric m:crime12 p:float l:crime12 d:"Part 1 Crime Rate per 1,000 Residents (2012)" t:dataTypeName=number

metric m:viol10 p:float l:viol10 d:"Violent Crime Rate per 1,000 Residents (2010)" t:dataTypeName=number

metric m:viol11 p:float l:viol11 d:"Violent Crime Rate per 1,000 Residents (2011)" t:dataTypeName=number

metric m:viol12 p:float l:viol12 d:"Violent Crime Rate per 1,000 Residents (2012)" t:dataTypeName=number

metric m:prop11 p:float l:prop11 d:"Property Crime Rate per 1,000 Residents (2011)" t:dataTypeName=number

metric m:prop12 p:float l:prop12 d:"Property Crime Rate per 1,000 Residents (2012)" t:dataTypeName=number

metric m:juvarr11 p:float l:juvarr11 d:"Juvenile Arrest Rate per 1,000 Juveniles (2011)" t:dataTypeName=number

metric m:juvviol11 p:float l:juvviol11 d:"Juvenile Arrest Rate for Violent Offenses per 1,000 Juveniles (2011)" t:dataTypeName=number

metric m:juvdrug11 p:float l:juvdrug11 d:"Juvenile Arrest Rate for Drug-Related Offenses per 1,000 Juveniles (2011)" t:dataTypeName=number

metric m:domvio10 p:float l:domvio10 d:"Domestic Violence Calls For Service per 1,000 Residents (2010)" t:dataTypeName=number

metric m:domvio11 p:float l:domvio11 d:"Domestic Violence Calls For Service per 1,000 Residents (2011)" t:dataTypeName=number

metric m:shoot11 p:float l:shoot11 d:"Number of Shootings per 1,000 Residents (2011)" t:dataTypeName=number

metric m:caslt11 p:float l:caslt11 d:"Number of Common Assault Calls for Service per 1,000 Residents (2011)" t:dataTypeName=number

metric m:narc11 p:float l:narc11 d:"Number of Narcotics Calls for Service per 1,000 Residents (2011)" t:dataTypeName=number

metric m:caracc11 p:float l:caracc11 d:"Number of Automobile Accident Calls for Service per 1,000 Residents (2011)" t:dataTypeName=number

metric m:gunhom11 p:float l:gunhom11 d:"Rate of Gun Homicides per 1,000 Residents (2011)" t:dataTypeName=number

metric m:gunhom12 p:float l:gunhom12 d:"Rate of Gun Homicides per 1,000 Residents (2012)" t:dataTypeName=number

entity e:ieq6-dzfz l:"Crime & Safety (2010-2012)" t:attribution="The Baltimore Neighborhood Indicators Alliance-Jacob France Institute at the University of Baltimore (known as BNIA-JFI)" t:url=https://data.baltimorecity.gov/api/views/ieq6-dzfz

property e:ieq6-dzfz t:meta.view v:id=ieq6-dzfz v:category=Neighborhoods v:attributionLink=http://bniajfi.org v:averageRating=0 v:name="Crime & Safety (2010-2012)" v:attribution="The Baltimore Neighborhood Indicators Alliance-Jacob France Institute at the University of Baltimore (known as BNIA-JFI)"

property e:ieq6-dzfz t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:ieq6-dzfz t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:ieq6-dzfz t:meta.view.tableauthor v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```

## Top Records

```ls
| csa2010                           | crime10 | crime11 | crime12 | viol10 | viol11 | viol12 | prop11 | prop12 | juvarr11 | juvviol11 | juvdrug11 | domvio10 | domvio11 | shoot11 | caslt11 | narc11 | caracc11 | gunhom11 | gunhom12 | 
| ================================= | ======= | ======= | ======= | ====== | ====== | ====== | ====== | ====== | ======== | ========= | ========= | ======== | ======== | ======= | ======= | ====== | ======== | ======== | ======== | 
| Allendale/Irvington/S. Hilton     | 40.6    | 46.2    | 45.4    | 12.6   | 12.5   | 13.9   | 33.7   | 31.6   | 54.8     | 12.4      | 22.2      | 59.4     | 65.4     | 2.5     | 84.4    | 78.8   | 44.0     | 0.2      | 0.6      | 
| Beechfield/Ten Hills/West Hills   | 33.6    | 36.1    | 36.6    | 8.4    | 7.2    | 7.0    | 28.9   | 29.6   | 22.0     | 9.1       | 5.3       | 47.9     | 44.8     | 2.0     | 51.2    | 24.7   | 31.9     | 0.2      | 0.2      | 
| Belair-Edison                     | 50.3    | 57.1    | 52.7    | 13.3   | 14.1   | 14.9   | 43.0   | 37.7   | 54.8     | 17.5      | 16.2      | 51.1     | 57.8     | 1.5     | 77.6    | 50.2   | 45.4     | 0.3      | 0.3      | 
| Brooklyn/Curtis Bay/Hawkins Point | 81.7    | 79.1    | 62.1    | 25.3   | 21.3   | 15.2   | 57.8   | 46.9   | 83.3     | 16.8      | 30.8      | 68.0     | 74.1     | 2.9     | 158.5   | 101.1  | 39.9     | 0.3      | 0.2      | 
| Canton                            | 61.0    | 64.8    | 57.9    | 8.3    | 7.7    | 6.7    | 57.2   | 51.2   | 81.5     | 14.8      | 7.4       | 34.3     | 39.6     | 0.0     | 46.2    | 4.0    | 32.8     | 0.0      | 0.0      | 
| Cedonia/Frankford                 | 43.7    | 48.4    | 46.7    | 12.0   | 11.3   | 12.1   | 37.1   | 34.6   | 46.5     | 9.5       | 10.7      | 60.2     | 70.2     | 0.8     | 10.7    | 22.8   | 26.5     | 0.3      | 0.3      | 
| Cherry Hill                       | 60.0    | 64.7    | 59.1    | 22.6   | 22.2   | 19.6   | 42.6   | 39.5   | 61.6     | 13.8      | 29.4      | 62.9     | 71.1     | 6.0     | 110.2   | 97.4   | 25.2     | 0.5      | 0.4      | 
| Chinquapin Park/Belvedere         | 43.6    | 33.4    | 44.5    | 12.6   | 7.1    | 9.0    | 26.3   | 35.5   | 37.9     | 10.2      | 7.3       | 39.7     | 44.2     | 0.3     | 60.1    | 17.9   | 38.9     | 0.0      | 0.4      | 
| Claremont/Armistead               | 52.6    | 63.2    | 49.0    | 13.2   | 12.6   | 8.9    | 50.5   | 40.1   | 18.7     | 7.7       | 3.3       | 60.4     | 68.8     | 0.9     | 10.9    | 19.9   | 60.1     | 0.1      | 0.1      | 
| Clifton-Berea                     | 57.9    | 61.0    | 56.4    | 23.3   | 23.5   | 20.0   | 37.5   | 36.5   | 144.9    | 33.2      | 63.7      | 49.7     | 63.5     | 7.3     | 121.0   | 201.9  | 47.0     | 0.6      | 0.8      | 
```