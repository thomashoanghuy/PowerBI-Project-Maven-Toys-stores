# PowerBI-Project-Maven-Toys-stores
Data Visualization Project for PowerBI beginner 
Explore dataset of MavenToys Stores to create data visualization to view revenue / profits / orders from Jan 2022 - Jul 2023


Good beginner project that will introduce you to PowerBI basics:

These subtopic which is:
1) Linking relationship between foreign keys to between different table in star-schema.
  Note: We need to pay attention to "one-to-many" relationship and cross-filter relationship should be one direction in most cases. So that when you slice products by categories and date of target table, it does not also filter the source table which can affect the actual figures.

2) DAX query can add new column on the table OR you can also add custom column ( which will literally add new columns on table when you rightclick Edit Query
  a) DAX query only require rightclick > functions sum() or related() to link with other table.

  b) if adding new custom column and you want to link with other tables, have to use "merge queries" to perform JOIN with another tables, using foreign key ( similar to SQL join ).

3) For time series data ( week / month / year ) , it is good practice to have a separate csv file with just calendar date, where you can add hierarchy , such as start of month , start of week etc... so that later on you can use hierarchy on x-axis for easy compilation by month.
