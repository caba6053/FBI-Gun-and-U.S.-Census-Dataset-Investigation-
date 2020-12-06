# ProjectInvestigateADataset
My datasets where taken from this link: https://s3.amazonaws.com/video.udacity-data.com/topher/2018/July/5b57919a_data-set-options/data-set-options.pdf under "FBI Gun Data". 
After exploring the data I had to do quite a bit of data cleaning. The adjustments I made to the two csv files are:
  1. df_gun needs to have column attributes to be all lowercase with no spaces
  2. df_gun needs to seperate the data in column "month" to "month" and "year"
  3. change "multiple" and "totals" in df_gun both to floats for consistency and year to an int
  4. delete "fact note" column in df_census since it not useful
  5. delete extra rows on the bottom of df_census that contain notes
  6. flip columns and rows in df_census
  7. df_census needs to fix column attribute names to all lowercase with no spaces
  8. adjust column names in df_census to be more readable and useful
  9. change columns in df_census to floats
Afterwards I explored the two questions: 
  What census population data coorelates to states with the most gun permits in the 21st century?
  Does state size increase or decrease with private gun sales?
 I used matplotlib visualizations to come up with my conclusion. 
