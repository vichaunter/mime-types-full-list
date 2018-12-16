# File mime types complete list

All file mime types in a csv list with extension and description

The list will be growing, if you miss some mimetype that you know will be perfect if you can send a request to add it (or if you find some wrong one and correct it).

## Load csv with php

You can use str_getcsv to load this csv into an array and work with it.

````
$csv = array_map('str_getcsv', file('mimetype-list.csv'));
````
