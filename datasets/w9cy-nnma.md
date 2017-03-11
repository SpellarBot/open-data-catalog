# DYCD after-school programs: Reading And Writing Literacy Programs

## Dataset

* [Dataset URL](https://data.cityofnewyork.us/api/views/w9cy-nnma/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/dycd-after-school-programs-reading-and-writing-literacy-programs-238fc)
* [Metadata URL](https://data.cityofnewyork.us/api/views/w9cy-nnma)
* Id = w9cy-nnma
* Name = DYCD after-school programs: Reading And Writing Literacy Programs
* Attribution = Department of Youth and Community Development (DYCD)
* Category = Education
* Tags = [jobs and economic mobility, education, services, youth, community, development, community development, school, child, children, after-school, after-school programs, programs, young adult, civics, ...
* Created = 2011-09-02T18:40:22Z
* Publication Date = 2011-09-02T18:40:22Z
* Rows Updated = 2011-09-02T18:40:30Z

## Description

Facilities in New York City, by agency and site, that offer after-school programs and resources for adult and adolescent literacy, family literacy, and English as a Second Language (ESOL) programs.
Update Schedule: Annually

## Columns

```ls
| Name                    | Field Name            | Data Type | Render Type | Schema Type | Included | 
| ======================= | ===================== | ========= | =========== | =========== | ======== | 
| updated_at              | :updated_at           | meta_data | meta_data   | time        | No       | 
| PROGRAM TYPE            | program_type          | text      | text        | series tag  | Yes      | 
| PROGRAM                 | program               | text      | text        | series tag  | Yes      | 
| SITE NAME               | site_name             | text      | text        | series tag  | Yes      | 
| BOROUGH / COMMUNITY     | borough_community     | text      | text        | series tag  | Yes      | 
| AGENCY                  | agency                | text      | text        | series tag  | Yes      | 
| Contact Number          | contact_number        | text      | text        | series tag  | Yes      | 
| Grade Level / Age Group | grade_level_age_group | text      | text        | series tag  | Yes      | 
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
```

## Data Commands

```ls





```

## Meta Commands

```ls
entity e:w9cy-nnma l:"DYCD after-school programs: Reading And Writing Literacy Programs" t:attribution="Department of Youth and Community Development (DYCD)" t:url=https://data.cityofnewyork.us/api/views/w9cy-nnma

property e:w9cy-nnma t:meta.view d:2017-03-08T00:23:25.807Z v:id=w9cy-nnma v:category=Education v:averageRating=80 v:name="DYCD after-school programs: Reading And Writing Literacy Programs" v:attribution="Department of Youth and Community Development (DYCD)"

property e:w9cy-nnma t:meta.view.owner d:2017-03-08T00:23:25.807Z v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"

property e:w9cy-nnma t:meta.view.tableauthor d:2017-03-08T00:23:25.807Z v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```