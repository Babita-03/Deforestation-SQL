# Deforestation-SQL
**Project Introduction**
- You’re a data analyst for ForestQuery, a non-profit organization, on a mission to reduce deforestation around the world and which raises awareness about this important environmental topic.

-Your executive director and her leadership team members are looking to understand which countries and regions around the world seem to have forests that have been shrinking in size, and also which countries and regions have the most significant forest area, both in terms of amount and percent of total area. The hope is that these findings can help inform initiatives, communications, and personnel allocation to achieve the largest impact with the precious few resources that the organization has at its disposal.

- Prepare and disseminate a report for the leadership team that uses complete sentences to help them understand the global deforestation overview between 1990 and 2016.

**Steps to Complete**

1.Create a View called “forestation” by joining all three tables - forest_area, land_area and regions in the workspace.

2.The forest_area and land_area tables join on both country_code AND year.

3.The regions table joins these based on only country_code.

**In the ‘forestation’ View, include the following:

- All of the columns of the origin tables
- A new column that provides the percent of the land area that is designated as forest.
- Keep in mind that the column forest_area_sqkm in the forest_area table and the land_area_sqmi in the land_area table are in different units (square kilometers and square miles, respectively), so an adjustment will need to be made in the calculation you write (1 sq mi = 2.59 sq km).

