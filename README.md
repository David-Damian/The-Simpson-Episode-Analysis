#  The-Simpson-Episode-Analysis
Repository to apply Big Data techniques using Simpsons' episodes per seasons database.
Using some statistical hypothesis test, I show that the presence of a celebrity in a The SImpons's episode does not has positively impact
in rating.

## Data
I consider [this](https://en.wikipedia.org/wiki/List_of_The_Simpsons_episodes_(seasons_1%E2%80%9320)#Season_20_(2008%E2%80%9309)) data source.
To avoid the *heavy weight* of copy and paste each data table that contains the episodes for seasons, is better to use a webscrapper.

## Steps
- Build an ETL to upload to the datalake a table with ALL the Simpsons episodes.
- Build an ELT to create a table of episodes in the AWS Glue Catalog database so you can access it from Amazon Athena.
- View and calculate statistics to show if having a star in an episode increases the rating in millions of people or not.

