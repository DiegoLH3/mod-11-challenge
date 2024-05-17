# mod-11-challenge

Part 1:
    I scraped the website to extract all the text elements in order to get the information I needed to get for the titles of the articles and the previews.
    After getting that then I made a dictionary in order to just get the text for the titles of the articles and their previews.

Part 2:
    Started with going into the Mars temperature data site and got the rows from the table. Then made a dictionary for a table and for the rows in the table in order to have it be cleaned and read better.
    Used that dictionary and made it into a data frame to get the following: id, terrestrial_date, sol, ls, month, min_temp, pressure as headers and the data from each listed below. After doing that I wanted to get get their dtypes and change their astypes to their appropriate paths. Looked at how many months there were on Mars by grouping the data frame and counting them by the months.
    follwoed by the amount of martian days with just counting the months in the data frame. Lastly before getting into the plots/graphs I looked at the avg low temperatur by month by doing a groupby of the data frame and grouping the month with the min_temp then getting the avg by using ".mean()"

    From looking at the graphs the average temperature by month on Mars the beginning of the year is the coldest, got this by making a bar graph:
    (coldest month: 3)
    (warmest month: 8)
    Getting the atmospheric pressure by month tells me, got this by making a bar graph:
    (Highest atmospheric pressure month: 9)
    (Lowest atmospheric pressure month: 6)


# https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.dtypes.html
    
# The link above was used to make dtypes to examine the data types of each column

# https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.astype.html

# The link above was used when needing to make astypes when I had to change the data types for data analysis

# Classmate Chris Canala helped in making a csv