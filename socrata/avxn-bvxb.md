# WAOFM - April 1 - Housing by State, County and City, 1990 to Present

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/waofm-april-1-housing-by-state-county-and-city-1990-to-present-78d5e) |
| Metadata | [Link](https://data.wa.gov/api/views/avxn-bvxb) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/avxn-bvxb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/avxn-bvxb/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | avxn-bvxb |
| Name | WAOFM - April 1 - Housing by State, County and City, 1990 to Present |
| Attribution | Washington State Office of Financial Management, Forecasting and Research Division |
| Category | Demographics |
| Tags | wa, washington, ofm, state, county, city, housing, intercensal, postcensal |
| Created | 2014-06-30T18:34:21Z |
| Publication Date | 2016-06-30T18:16:05Z |

## Description

Intercensal and postcensal housing estimates for the state, counties and cities, 1990 to present.

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| Yes      | numeric metric | seq          | SEQ          | number    | number      |
| Yes      | numeric metric | filter       | FILTER       | number    | number      |
| Yes      | series tag     | county       | COUNTY       | text      | text        |
| Yes      | series tag     | jurisdiction | JURISDICTION | text      | text        |
| Yes      | numeric metric | hu_1990      | HU_1990      | number    | number      |
| Yes      | numeric metric | hu_1991      | HU_1991      | number    | number      |
| Yes      | numeric metric | hu_1992      | HU_1992      | number    | number      |
| Yes      | numeric metric | hu_1993      | HU_1993      | number    | number      |
| Yes      | numeric metric | hu_1994      | HU_1994      | number    | number      |
| Yes      | numeric metric | hu_1995      | HU_1995      | number    | number      |
| Yes      | numeric metric | hu_1996      | HU_1996      | number    | number      |
| Yes      | numeric metric | hu_1997      | HU_1997      | number    | number      |
| Yes      | numeric metric | hu_1998      | HU_1998      | number    | number      |
| Yes      | numeric metric | hu_1999      | HU_1999      | number    | number      |
| Yes      | numeric metric | hu_2000      | HU_2000      | number    | number      |
| Yes      | numeric metric | hu_2001      | HU_2001      | number    | number      |
| Yes      | numeric metric | hu_2002      | HU_2002      | number    | number      |
| Yes      | numeric metric | hu_2003      | HU_2003      | number    | number      |
| Yes      | numeric metric | hu_2004      | HU_2004      | number    | number      |
| Yes      | numeric metric | hu_2005      | HU_2005      | number    | number      |
| Yes      | numeric metric | hu_2006      | HU_2006      | number    | number      |
| Yes      | numeric metric | hu_2007      | HU_2007      | number    | number      |
| Yes      | numeric metric | hu_2008      | HU_2008      | number    | number      |
| Yes      | numeric metric | hu_2009      | HU_2009      | number    | number      |
| Yes      | numeric metric | hu_2010      | HU_2010      | number    | number      |
| Yes      | numeric metric | hu_2011      | HU_2011      | number    | number      |
| Yes      | numeric metric | hu_2012      | HU_2012      | number    | number      |
| Yes      | numeric metric | hu_2013      | HU_2013      | number    | number      |
| Yes      | numeric metric | hu_2014      | HU_2014      | number    | number      |
| Yes      | numeric metric | hu_2015      | HU_2015      | number    | number      |
| Yes      | numeric metric | hu_2016      | HU_2016      | number    | number      |
```

## Time Field

```ls
Value = 1990
Format & Zone = yyyy
```

## Data Commands

```ls
series e:avxn-bvxb d:1990-01-01T00:00:00.000Z t:county=Adams t:jurisdiction="Adams County" m:hu_2004=6068 m:hu_2005=6096 m:hu_2006=6083 m:hu_2007=6131 m:hu_2000=5773 m:hu_2001=5827 m:hu_2002=5880 m:hu_2003=5947 m:hu_2008=6178 m:hu_2009=6203 m:hu_1997=6084 m:hu_1998=6107 m:hu_1999=6192 m:hu_1990=5263 m:hu_1991=5324 m:hu_1992=5404 m:hu_1993=5504 m:hu_2010=6242 m:hu_1994=5656 m:hu_1995=5811 m:hu_1996=5921 m:hu_2013=6374 m:hu_2014=6421 m:hu_2011=6275 m:hu_2012=6321 m:hu_2015=6475 m:hu_2016=6567 m:seq=1 m:filter=1

series e:avxn-bvxb d:1990-01-01T00:00:00.000Z t:county=Adams t:jurisdiction="Unincorporated Adams County" m:hu_2004=2684 m:hu_2005=2688 m:hu_2006=2700 m:hu_2007=2716 m:hu_2000=2561 m:hu_2001=2591 m:hu_2002=2629 m:hu_2003=2656 m:hu_2008=2720 m:hu_2009=2722 m:hu_1997=2987 m:hu_1998=2991 m:hu_1999=3065 m:hu_1990=2361 m:hu_1991=2423 m:hu_1992=2501 m:hu_1993=2575 m:hu_2010=2713 m:hu_1994=2683 m:hu_1995=2785 m:hu_1996=2890 m:hu_2013=2775 m:hu_2014=2796 m:hu_2011=2729 m:hu_2012=2749 m:hu_2015=2813 m:hu_2016=2853 m:seq=2 m:filter=2

series e:avxn-bvxb d:1990-01-01T00:00:00.000Z t:county=Adams t:jurisdiction="Incorporated Adams County" m:hu_2004=3384 m:hu_2005=3408 m:hu_2006=3383 m:hu_2007=3415 m:hu_2000=3212 m:hu_2001=3236 m:hu_2002=3251 m:hu_2003=3291 m:hu_2008=3458 m:hu_2009=3481 m:hu_1997=3097 m:hu_1998=3116 m:hu_1999=3127 m:hu_1990=2902 m:hu_1991=2901 m:hu_1992=2903 m:hu_1993=2929 m:hu_2010=3529 m:hu_1994=2973 m:hu_1995=3026 m:hu_1996=3031 m:hu_2013=3599 m:hu_2014=3625 m:hu_2011=3546 m:hu_2012=3572 m:hu_2015=3662 m:hu_2016=3714 m:seq=3 m:filter=3
```

## Meta Commands

```ls
metric m:seq p:integer l:SEQ d:"Sequence number (use this field to return the table to the original sort order)" t:dataTypeName=number

metric m:filter p:integer l:FILTER d:"Filter (use this field to filter the data by geography: 1=county or state, 2=unincorporated county or state, 3=incorporated county or state, 4=city )" t:dataTypeName=number

metric m:hu_1990 p:integer l:HU_1990 d:"Total housing units 1990" t:dataTypeName=number

metric m:hu_1991 p:integer l:HU_1991 d:"Total housing units 1991" t:dataTypeName=number

metric m:hu_1992 p:integer l:HU_1992 d:"Total housing units 1992" t:dataTypeName=number

metric m:hu_1993 p:integer l:HU_1993 d:"Total housing units 1993" t:dataTypeName=number

metric m:hu_1994 p:integer l:HU_1994 d:"Total housing units 1994" t:dataTypeName=number

metric m:hu_1995 p:integer l:HU_1995 d:"Total housing units 1995" t:dataTypeName=number

metric m:hu_1996 p:integer l:HU_1996 d:"Total housing units 1996" t:dataTypeName=number

metric m:hu_1997 p:integer l:HU_1997 d:"Total housing units 1997" t:dataTypeName=number

metric m:hu_1998 p:integer l:HU_1998 d:"Total housing units 1998" t:dataTypeName=number

metric m:hu_1999 p:integer l:HU_1999 d:"Total housing units 1999" t:dataTypeName=number

metric m:hu_2000 p:integer l:HU_2000 d:"Total housing units 2000" t:dataTypeName=number

metric m:hu_2001 p:integer l:HU_2001 d:"Total housing units 2001" t:dataTypeName=number

metric m:hu_2002 p:integer l:HU_2002 d:"Total housing units 2002" t:dataTypeName=number

metric m:hu_2003 p:integer l:HU_2003 d:"Total housing units 2003" t:dataTypeName=number

metric m:hu_2004 p:integer l:HU_2004 d:"Total housing units 2004" t:dataTypeName=number

metric m:hu_2005 p:integer l:HU_2005 d:"Total housing units 2005" t:dataTypeName=number

metric m:hu_2006 p:integer l:HU_2006 d:"Total housing units 2006" t:dataTypeName=number

metric m:hu_2007 p:integer l:HU_2007 d:"Total housing units 2007" t:dataTypeName=number

metric m:hu_2008 p:integer l:HU_2008 d:"Total housing units 2008" t:dataTypeName=number

metric m:hu_2009 p:integer l:HU_2009 d:"Total housing units 2009" t:dataTypeName=number

metric m:hu_2010 p:integer l:HU_2010 d:"Total housing units 2010" t:dataTypeName=number

metric m:hu_2011 p:integer l:HU_2011 d:"Total housing units 2011" t:dataTypeName=number

metric m:hu_2012 p:integer l:HU_2012 d:"Total housing units 2012" t:dataTypeName=number

metric m:hu_2013 p:integer l:HU_2013 d:"Total housing units 2013" t:dataTypeName=number

metric m:hu_2014 p:integer l:HU_2014 d:"Total housing units 2014" t:dataTypeName=number

metric m:hu_2015 p:integer l:HU_2015 d:"Total housing units 2015" t:dataTypeName=number

metric m:hu_2016 p:integer l:HU_2016 d:"Total housing units 2016" t:dataTypeName=number

entity e:avxn-bvxb l:"WAOFM - April 1 - Housing by State, County and City, 1990 to Present" t:attribution="Washington State Office of Financial Management, Forecasting and Research Division" t:url=https://data.wa.gov/api/views/avxn-bvxb

property e:avxn-bvxb t:meta.view v:id=avxn-bvxb v:category=Demographics v:attributionLink=http://www.ofm.wa.gov/pop/april1/default.asp v:averageRating=0 v:name="WAOFM - April 1 - Housing by State, County and City, 1990 to Present" v:attribution="Washington State Office of Financial Management, Forecasting and Research Division"

property e:avxn-bvxb t:meta.view.license v:name="Public Domain"

property e:avxn-bvxb t:meta.view.owner v:id=qav9-tahu v:profileImageUrlMedium=/api/users/qav9-tahu/profile_images/THUMB v:profileImageUrlLarge=/api/users/qav9-tahu/profile_images/LARGE v:screenName="Thomas Kimpel" v:profileImageUrlSmall=/api/users/qav9-tahu/profile_images/TINY v:displayName="Thomas Kimpel"

property e:avxn-bvxb t:meta.view.tableauthor v:id=qav9-tahu v:profileImageUrlMedium=/api/users/qav9-tahu/profile_images/THUMB v:profileImageUrlLarge=/api/users/qav9-tahu/profile_images/LARGE v:screenName="Thomas Kimpel" v:profileImageUrlSmall=/api/users/qav9-tahu/profile_images/TINY v:roleName=administrator v:displayName="Thomas Kimpel"
```

## Top Records

```ls
| seq | filter | county | jurisdiction                 | hu_1990 | hu_1991 | hu_1992 | hu_1993 | hu_1994 | hu_1995 | hu_1996 | hu_1997 | hu_1998 | hu_1999 | hu_2000 | hu_2001 | hu_2002 | hu_2003 | hu_2004 | hu_2005 | hu_2006 | hu_2007 | hu_2008 | hu_2009 | hu_2010 | hu_2011 | hu_2012 | hu_2013 | hu_2014 | hu_2015 | hu_2016 | 
| === | ====== | ====== | ============================ | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | 
| 1   | 1      | Adams  | Adams County                 | 5263    | 5324    | 5404    | 5504    | 5656    | 5811    | 5921    | 6084    | 6107    | 6192    | 5773    | 5827    | 5880    | 5947    | 6068    | 6096    | 6083    | 6131    | 6178    | 6203    | 6242    | 6275    | 6321    | 6374    | 6421    | 6475    | 6567    | 
| 2   | 2      | Adams  | Unincorporated Adams County  | 2361    | 2423    | 2501    | 2575    | 2683    | 2785    | 2890    | 2987    | 2991    | 3065    | 2561    | 2591    | 2629    | 2656    | 2684    | 2688    | 2700    | 2716    | 2720    | 2722    | 2713    | 2729    | 2749    | 2775    | 2796    | 2813    | 2853    | 
| 3   | 3      | Adams  | Incorporated Adams County    | 2902    | 2901    | 2903    | 2929    | 2973    | 3026    | 3031    | 3097    | 3116    | 3127    | 3212    | 3236    | 3251    | 3291    | 3384    | 3408    | 3383    | 3415    | 3458    | 3481    | 3529    | 3546    | 3572    | 3599    | 3625    | 3662    | 3714    | 
| 4   | 4      | Adams  | Hatton                       | 29      | 32      | 32      | 32      | 32      | 33      | 36      | 36      | 36      | 36      | 35      | 39      | 35      | 36      | 36      | 39      | 39      | 39      | 40      | 40      | 40      | 40      | 41      | 41      | 41      | 43      | 44      | 
| 5   | 4      | Adams  | Lind                         | 243     | 239     | 246     | 241     | 242     | 242     | 244     | 246     | 247     | 249     | 307     | 304     | 300     | 297     | 293     | 290     | 287     | 283     | 280     | 276     | 276     | 275     | 274     | 274     | 272     | 272     | 268     | 
| 6   | 4      | Adams  | Othello                      | 1637    | 1637    | 1633    | 1660    | 1697    | 1748    | 1742    | 1792    | 1806    | 1810    | 1864    | 1880    | 1903    | 1943    | 2039    | 2061    | 2032    | 2067    | 2118    | 2146    | 2185    | 2203    | 2230    | 2257    | 2287    | 2323    | 2378    | 
| 7   | 4      | Adams  | Ritzville                    | 883     | 884     | 885     | 890     | 894     | 894     | 898     | 904     | 906     | 909     | 873     | 879     | 882     | 884     | 885     | 886     | 887     | 888     | 894     | 894     | 902     | 903     | 902     | 902     | 900     | 899     | 897     | 
| 8   | 4      | Adams  | Washtucna                    | 110     | 109     | 107     | 106     | 108     | 109     | 111     | 119     | 121     | 123     | 133     | 134     | 131     | 131     | 131     | 132     | 138     | 138     | 126     | 125     | 126     | 125     | 125     | 125     | 125     | 125     | 127     | 
| 9   | 1      | Asotin | Asotin County                | 7519    | 7566    | 7668    | 7794    | 8033    | 8166    | 8465    | 8620    | 8752    | 8877    | 9111    | 9174    | 9213    | 9272    | 9333    | 9439    | 9570    | 9699    | 9774    | 9835    | 9872    | 9895    | 9909    | 9925    | 9954    | 10007   | 10058   | 
| 10  | 2      | Asotin | Unincorporated Asotin County | 4064    | 4132    | 4207    | 4338    | 4517    | 4691    | 4948    | 5072    | 5168    | 5262    | 5257    | 5300    | 5348    | 5403    | 5455    | 5542    | 5655    | 5770    | 5846    | 5891    | 5924    | 5948    | 5960    | 5980    | 6009    | 6053    | 6095    | 
```