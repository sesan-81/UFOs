UFOS

1	OVERVIEW OF THE PROJECT

Purpose of the Analysis

The request from a client was to display a table organizing UFO data stored as a JavaScript array. The client wanted to have the functionality to filter by multiple criteria creating a dynamic website. Users are able to get a more in-depth analysis of UFO sightings by allowing them to filter for multiple criteria at the same time and view the number of data points. The table was created using JavaScript, while HTML/CSS and Bootstrap were used to modify the aesthetics of the website.

2	RESULTS

The dataset provided is about UFO sightings in the United States with the following columns: Date, City, State, Country, Shape and Comment. Our app is taking those columns and creating a HTML table using D3.js. We've also used Bootstrap to properly lay out the table and add a filter form from where users could search by using the input tags: Date, City, State, Country and Shape and based on the search criteria, the app would filter the table and generate a new one.

Tools

Software: HTML/CSS, JavaScript, Visual Studio Code 1.49.1, BootStrap 4.0.0

Search Criteria Procedure

	Filtering by event date

![image](https://user-images.githubusercontent.com/104377031/179324980-57f28692-9728-45f4-a1ab-900df8bbb44d.png)


The user enters the desired date, the change is detected, and the table is updated accordingly.


	Filtering by city


![image](https://user-images.githubusercontent.com/104377031/179325014-76ef0ce6-4ea6-49c8-ae17-ae52a13d0550.png)


The user enters the desired city, the change is detected, and the table is updated accordingly.


	Filtering by country

![image](https://user-images.githubusercontent.com/104377031/179325050-e56b3a72-1d7d-4acf-bd82-f7c8eab5f0a9.png)


The user enters the desired country, the change is detected, and the table is updated accordingly.

	Filtering by state and shape

![image](https://user-images.githubusercontent.com/104377031/179325078-6de2bf9d-1fe9-4990-8f68-d2ad2b5ca6c6.png)

The user enters the desired state and shape observed, the changes are detected and the table is updated accordingly. 
All filter parameters can be entered simultaneously.

3	SUMMARY

	Drawbacks

One drawback of this design is the difficulty for the user to know what parameter to use for the filtering. For example to pick a city, the user would have to go through the table a find the city desired for the analysis.

Another drawback is the inability for the table to return back to it's original order and after a search criteria is used, making us to always refresh the page before filtering another criterion.

Another drawback is the inability for the page to compute the number of return columns and rows after searches as such users always need to manually count each row to know the numbers of returned values.

	Recommendations 

1. They should be a drop-down menu where all the cities, town and country are listed to give users a first-hand overview of what there are dealing with.

2. Our app should be updated to clear the search and return all contents before another search parameter is used.

3. Our code should also be updated to compute and output the total numbers of rows returned after searches.



