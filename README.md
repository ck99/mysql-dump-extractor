mysql-dump-extractor
====================

Handy little utility to reduce the size of a mysql dump file by using a regexp blacklist to exclude particular insert statements. I built this to solve a problem where I had a large (4GB) dump file, which included lots of data that I didnt want. The DB in question was a Magento dump, but this utility will work with any mysql dump. 
