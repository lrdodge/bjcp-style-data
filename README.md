BJCP Style Data
===============
While the [BJCP website](http://www.bjcp.org/stylecenter.php) contains a wealth
of beer style information, none of the provided files are conducive to
data processing. The goal of this project is to provide the official BJCP style
guidelines in multiple data formats which can be easily used in software
applications.

Usage
-----
Files should be used as an application's data source of BJCP style data. Be
sure to read the file descriptions in order to choose the file which best meets
the needs of the application.

Files
-----
All files use the UTF-8 character set unless otherwise stated.

### beer-vital-statistics.csv
BJCP code, category/sub-category name, and max/min vital statistics for each
beer style. Data contains some categorical values.

* Field Delimiter: `,`
* Text Delimiter: `"`

### beer-vital-statistics-numerical.csv
BJCP code designation, category/sub-category name, and max/min vital statistics
for each beer style. Categorical values have been removed.

* Field Delimiter: `,`
* Text Delimiter: `"`

### framework-tree.json
Style, category, subcategory, and BJCP code designations in a parent-child
relationship suited for tree structures.framework-tree.min.json

### tree.json
All style data in a parent-child relationship suited for tree structures.
Compacted version with all white space removed (reduced file size): 
tree.min.json

Definitions
-----------
### Vital Statistics
Refers to the following attributes:

* Original Gravity (OG)
* Final Gravity (FG)
* Alcohol by Volume (ABV)
* International Bittering Units (IBU)
* Standard Reference Method (SRM)

License
-------
The MIT License (MIT)