# Desired flow

1. user uploads CSV
2. user sets intent
3. use ingest apis to get processor & task spec
4. use batch api on first 5 rows
5. choice
   1. go back to step 2
   2. perform batch api on all rows
