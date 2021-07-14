# Argus Preloaded Bookmarks

This repository hosts all the .rds files that are used as preloaded data in the [Argus package](https://github.com/JGCRI/argus). The following steps explain how to create an Argus Bookmark, upload it to this repo and then add it into Argus as a preloaded dataset:

1. Create a bookmark in Argus (See the Argus User Guide on [bookmarks](https://jgcri.github.io/argus/articles/vignette_argus.html#bookmarks-1)
2. Upload the bookmark to this repository 
3. Update the [preloaded_data.R file in the Argus repo](https://github.com/JGCRI/argus/blob/main/R/preloaded_data.R) with an appropriate group, name and link to the new bookmark added in this repo and commit the changes. (Access needed to the Argus repo for this).
4. Add the group, name and link to the table below for record keeping.

Next time Argus is loaded up the preloaded_data will include the new dataset ready for quick and easy viewing!

| group       | name |  link   |
| ----------- | ----------- | ---------- |
| examples      | exampleData      | https://github.com/JGCRI/argusbookmarks/raw/main/argus_bookmark_exampleData.rds |
| GCAM   | GCAMvX.X_branch_name        |   link_here       |





