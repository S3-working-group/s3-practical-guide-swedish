# S3 Practical Guide (Swedish Version)

The Swedish translation of the electronic publication [A Practical Guide to Sociocracy 3.0](https://github.com/S3-working-group/s3-practical-guide).

## Build Process

-   add translated files from [S3 Practical Guide Crowdin project](https://crowdin.com/project/sociocracy-30) 
-   check with English repository for changes to:
    -  `config/*`
    -  `templates/*`
    -  `makefile` and `build.sh`
    -  the contents of all the subfolders inside docs (but not the file inside docs)
-   add translated illustrations to `img`
-   update version number in `config/project.yaml`
-   run buildscript (`source build.sh`) to build all formats or only build the website:
	-   `make clean` - clean temporary files and web pages
	-   `make setup` - copy images and ensure all temp folders are created
	-   `make site` - build the website
