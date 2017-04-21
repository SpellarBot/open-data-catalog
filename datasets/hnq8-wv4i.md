# Jackson Capital Budget Project Details

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/jackson-capital-budget-project-details-df48b) |
| Metadata | [Link](https://data.jacksonms.gov/api/views/hnq8-wv4i) |
| Data: JSON | [100 Rows](https://data.jacksonms.gov/api/views/hnq8-wv4i/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.jacksonms.gov/api/views/hnq8-wv4i/rows.csv?max_rows=100) |
| Host | data.jacksonms.gov |
| Id | hnq8-wv4i |
| Name | Jackson Capital Budget Project Details |
| Category | Public Works |
| Created | 2017-01-23T14:45:21Z |
| Publication Date | 2017-01-23T17:50:14Z |

## Description

Budget data that describes the Projects and Phases of the Infrastructure Master Plan

## Columns

```ls
| Included | Schema Type | Field Name          | Name                | Data Type | Render Type |
| ======== | =========== | =================== | =================== | ========= | =========== |
| No       | time        | :updated_at         | updated_at          | meta_data | meta_data   |
| Yes      | series tag  | project_id          | Project ID          | text      | text        |
| Yes      | series tag  | project_name        | Project Name        | text      | text        |
| Yes      | series tag  | project_description | Project Description | text      | text        |
| Yes      | series tag  | project_details     | Project Details     | text      | text        |
| Yes      | series tag  | project_image       | Project Image       | text      | text        |
| Yes      | series tag  | current_phase       | Current Phase       | text      | text        |
| Yes      | series tag  | ward                | Ward                | text      | number      |
| No       |             | latitude            | Latitude            | number    | number      |
| No       |             | longitude           | Longitude           | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = latitude,longitude
```

## Data Commands

```ls
series e:hnq8-wv4i d:2017-01-23T14:45:24.000Z t:project_name="Hanging Moss Road" t:ward=2 t:project_id=BR-01 t:project_image="https://data.jacksonms.gov/api/file_data/2e660f3e-ca4d-4122-b4ee-ddc28316779f?filename=BR01.jpg" t:project_details="http://capitalprojects.jacksonms.gov/projects/BR-01?category=projects&categoryId=projects&tab=list" t:current_phase=Completed t:project_description="The proposed project will repair the bridge located on Hanging Moss Road, and the tributary of Hanging Moss Creek. Major activity includes replacing the bridge with a structure that meets or exceeds the substandard load carrying capacity. This bridge received a sufficiency rating of 9 out of 100 during a recent MDOT State Aid inspection." m:row_number.hnq8-wv4i=1

series e:hnq8-wv4i d:2017-01-23T14:45:24.000Z t:project_name="Country Club Drive" t:ward=4 t:project_id=BR-02 t:project_image="https://data.jacksonms.gov/api/file_data/3b1b1f5e-c52a-4558-a026-9590eab7e0ef?filename=photo-coming-soon.png" t:project_details="http://capitalprojects.jacksonms.gov/projects/BR-02?category=projects&categoryId=projects&tab=list" t:current_phase=Design t:project_description="The proposed project will repair the bridge located on Country Club Drive above Lynch Creek. Major activity include replacing the bridge with a structure that meets or exceeds substandard load carrying capacity. This bridge received a sufficiency rating less than 40 out of 100 during a recent MDOT State Aid inspection." m:row_number.hnq8-wv4i=2

series e:hnq8-wv4i d:2017-01-23T14:45:24.000Z t:project_name="Robinson Road" t:ward=45 t:project_id=BR-03 t:project_image="https://data.jacksonms.gov/api/file_data/3b1b1f5e-c52a-4558-a026-9590eab7e0ef?filename=photo-coming-soon.png" t:project_details="http://capitalprojects.jacksonms.gov/projects/BR-03?category=projects&categoryId=projects&tab=list" t:current_phase=Design t:project_description="The proposed project will repair the bridge located on Robinson Road above Caney Creek. Major activity includes replacing the bridge with a structure that meets or exceeds substandard load carrying capacity. This bridge received a sufficiency rating less than 50 out of 100 during a recent MDOT State Aid inspection." m:row_number.hnq8-wv4i=3
```

## Meta Commands

```ls
metric m:row_number.hnq8-wv4i p:long l:"Row Number"

entity e:hnq8-wv4i l:"Jackson Capital Budget Project Details" t:url=https://data.jacksonms.gov/api/views/hnq8-wv4i

property e:hnq8-wv4i t:meta.view v:id=hnq8-wv4i v:category="Public Works" v:averageRating=0 v:name="Jackson Capital Budget Project Details"

property e:hnq8-wv4i t:meta.view.owner v:id=6ngd-c2u2 v:profileImageUrlMedium=/api/users/6ngd-c2u2/profile_images/THUMB v:profileImageUrlLarge=/api/users/6ngd-c2u2/profile_images/LARGE v:screenName="Justin Bruce" v:profileImageUrlSmall=/api/users/6ngd-c2u2/profile_images/TINY v:lastNotificationSeenAt=1492180672 v:displayName="Justin Bruce"

property e:hnq8-wv4i t:meta.view.tableauthor v:id=6ngd-c2u2 v:profileImageUrlMedium=/api/users/6ngd-c2u2/profile_images/THUMB v:profileImageUrlLarge=/api/users/6ngd-c2u2/profile_images/LARGE v:screenName="Justin Bruce" v:profileImageUrlSmall=/api/users/6ngd-c2u2/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492180672 v:displayName="Justin Bruce"
```

## Top Records

```ls
| :updated_at | project_id | project_name                     | project_description                                                                                                                                                                                                                                                                                                                                                                      | project_details                                                                                    | project_image                                                                                                | current_phase | ward | latitude    | longitude    | 
| =========== | ========== | ================================ | ======================================================================================================================================================================================================================================================================================================================================================================================== | ================================================================================================== | ============================================================================================================ | ============= | ==== | =========== | ============ | 
| 1485182724  | BR-01      | Hanging Moss Road                | The proposed project will repair the bridge located on Hanging Moss Road, and the tributary of Hanging Moss Creek. Major activity includes replacing the bridge with a structure that meets or exceeds the substandard load carrying capacity. This bridge received a sufficiency rating of 9 out of 100 during a recent MDOT State Aid inspection.                                      | http://capitalprojects.jacksonms.gov/projects/BR-01?category=projects&categoryId=projects&tab=list | https://data.jacksonms.gov/api/file_data/2e660f3e-ca4d-4122-b4ee-ddc28316779f?filename=BR01.jpg              | Completed     | 2    | 32.38114306 | -90.17964694 | 
| 1485182724  | BR-02      | Country Club Drive               | The proposed project will repair the bridge located on Country Club Drive above Lynch Creek. Major activity include replacing the bridge with a structure that meets or exceeds substandard load carrying capacity. This bridge received a sufficiency rating less than 40 out of 100 during a recent MDOT State Aid inspection.                                                         | http://capitalprojects.jacksonms.gov/projects/BR-02?category=projects&categoryId=projects&tab=list | https://data.jacksonms.gov/api/file_data/3b1b1f5e-c52a-4558-a026-9590eab7e0ef?filename=photo-coming-soon.png | Design        | 4    | 32.33159083 | -90.24765139 | 
| 1485182724  | BR-03      | Robinson Road                    | The proposed project will repair the bridge located on Robinson Road above Caney Creek. Major activity includes replacing the bridge with a structure that meets or exceeds substandard load carrying capacity. This bridge received a sufficiency rating less than 50 out of 100 during a recent MDOT State Aid inspection.                                                             | http://capitalprojects.jacksonms.gov/projects/BR-03?category=projects&categoryId=projects&tab=list | https://data.jacksonms.gov/api/file_data/3b1b1f5e-c52a-4558-a026-9590eab7e0ef?filename=photo-coming-soon.png | Design        | 45   | 32.27131694 | -90.26022528 | 
| 1485182724  | BR-04      | Alta Woods Boulevard             | The proposed project will repair the bridge located on Alta Woods Boulevard above Small Stream. Major activity includes the replacement of the bridge with a structure that meets or exceeds substandard load carrying capacity. This bridge received a sufficiency rating of 41 out of 100 during a recent MDOT State Aid inspection.                                                   | http://capitalprojects.jacksonms.gov/projects/BR-04?category=projects&categoryId=projects&tab=list | https://data.jacksonms.gov/api/file_data/3b1b1f5e-c52a-4558-a026-9590eab7e0ef?filename=photo-coming-soon.png | Planning      | 5    | 32.27646417 | -90.22012472 | 
| 1485182724  | DR-01      | Beechcrest Drive                 | To improve 3200 feet of drainage starting at the east of Beechcrest Drive where Purple Creek intersects with a major tributary and extends upstream along Purple Creek to Old Canton Road. Embankment solutions will be used to improve the drainage which is currently causing severe erosion resulting in property loss.                                                               | http://capitalprojects.jacksonms.gov/projects/DR-01?category=projects&categoryId=projects&tab=list | https://data.jacksonms.gov/api/file_data/795aa2d7-fbd4-4e15-9225-9f3517b61b82?filename=DR01.jpg              | Planning      | 1    | 32.37663278 | -90.11785528 | 
| 1485182724  | DR-02      | North Canton Club                | Due to erosion, there is limited access and egress in the North Canton Club area. To combat this, a combination of erosion methods such as rock and vegetation along with a new piping system can be used to help slow down storm water runoff. The proposed project will improve the drainage system along North Canton Club for an estimated linear footage of 3100 feet.              | http://capitalprojects.jacksonms.gov/projects/DR-02?category=projects&categoryId=projects&tab=list | https://data.jacksonms.gov/api/file_data/7c07a404-3dbd-46a3-a5c1-2ce69ea60f94?filename=DR02.jpg              | Planning      | 1    | 32.37922694 | -90.11233778 | 
| 1485182724  | DR-03      | Woodhill Road to Beasley Road    | A combination of erosion and flooding concerns exist along Woodhill Road and can be addressed by implementing both stabilization activities as well as some piping where hydraulics will support it. Clearing and grubbing activities will be necessary as well. The proposed project will improve the drainage system along Woodhill Road for an estimated linear footage of 2000 feet. | http://capitalprojects.jacksonms.gov/projects/DR-03?category=projects&categoryId=projects&tab=list | https://data.jacksonms.gov/api/file_data/04eba00b-44c9-4368-9093-8d7f07a5270e?filename=DR03.jpg              | Planning      | 2    | 32.38960722 | -90.17533611 | 
| 1485182724  | DR-04      | George Washington Drive          | Flooding is a major issue along George Washington Drive. Due to illegal dumping, channels are frequently clogged and cause O&M issues. A new system would help deter dumping and require less maintenance. The proposed project will improve the drainage system along George Washington Drive for an estimated linear footage of 2000 feet.                                             | http://capitalprojects.jacksonms.gov/projects/DR-04?category=projects&categoryId=projects&tab=list | https://data.jacksonms.gov/api/file_data/958af3fd-cc97-41ef-82ce-8ebdb14b539a?filename=DR04.jpg              | Planning      | 2    | 32.36982944 | -90.26121472 | 
| 1485182724  | DR-05      | Forest Avenue to Northside Drive | Though the channel is adequate, erosion is still a major concern along Forest Avenue. Stabilization methods such as rock, retaining walls, and hydro seed are necessary along with a partnership with residents to keep grass cut. The proposed project will improve the drainage system along Forest Avenue for an estimated linear footage of 1600 feet.                               | http://capitalprojects.jacksonms.gov/projects/DR-05?category=projects&categoryId=projects&tab=list | https://data.jacksonms.gov/api/file_data/2ca2cb88-76e4-4709-9d9d-77ede34a0aba?filename=DR05.jpg              | Design        | 3    | 32.36344028 | -90.18567917 | 
| 1485182724  | DR-06      | Woodrow Wilson to Erie Street    | Erosion is a concern along Woodrow Wilson. This proposed project will improve the drainage system along the roadway for an estimated linear footage of 1200 feet. Major activity includes clearing, grubbing, and bank stabilization to improve the drainage.                                                                                                                            | http://capitalprojects.jacksonms.gov/projects/DR-06?category=projects&categoryId=projects&tab=list | https://data.jacksonms.gov/api/file_data/d23dd41d-9b53-4948-a425-8fd4fc807580?filename=DR06.jpg              | Design        | 3    | 32.32318    | -90.19920028 | 
```