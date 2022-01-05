# BookingTourismAnalysis

searching, extracting and displaying statistics for tourist destinations from the world wide web, based on specific search terms.

The basic function of the application is: given a search term related to a tourist destination, e.g. a city, and a date, to become a kind of web search on specific target websites (data sources) and from the analysis of their content and aggregate statistics emerge. In this way our application is able to "read" (via parsing) and use accommodation information, accompanied by reviews and ratings received, drawing data from various "known" websites such as Booking.com.
The main goal of the work is to be able to display statistics to the user such as:

Number of accommodations (total number, available number)

Average review score per accommodation

Average price per accommodation

Overall average rating of accommodations per destination

Overall average price of accommodation per destination

In more detail, the application uses jsoup library and Builder Design Pattern and meets the following specifications:

The console application has a basic console menu, numbered with the following options

Enter the destination and date

View statistics

Export statistics to csv file

Exit

The application will have a local SQLite database in which search results will be stored.

When selecting search terms, the application will ask the user for the destination they are interested in, as well as a date (select one day)

Builder design pattern is used during the implementation of classes and / or interfaces, in the architecture of the application.

The searches of the users are stored in the database with a timestamp, so that the application can display the statistics of the search terms and based on the time of those searches that have been stored in the DB.

The user can press Y (yes) to continue and N (no) to stop and end the program.

 All statistics are exported to csv file.

