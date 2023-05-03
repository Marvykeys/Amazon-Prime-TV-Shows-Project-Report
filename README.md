# :movie_camera: Amazon-Prime-TV-Shows-Project-Report :tv:
## Scope :page_with_curl:
This report is focused on studying the trends present in the Amazon Prime TV Shows Dataset, which includes columns containing the Name of the show, Year of release, Number of seasons available, Language, Genre, IMDb rating and Age of viewers. Useful insights were obtained using the provided data on courses from different topics.
 ## Data Design :bar_chart:
The raw data provided was downloaded in CSV file format from kaggle.com and it came with some of its contents being improperly formatted hence, a proper data cleaning had to be done by removing duplicates, renaming cells, creating filters and also deleting empty rows.
 ## Import and Transform Data :scroll:
After downloading the data which was in CSV file format, I imported the data into Microsoft Excel being the tool I’ll be using for analysis.                             <img width="802" alt="Amazon 1" src="https://user-images.githubusercontent.com/130637591/235513178-b8f99b70-fdd6-4de1-83d2-67ffcbbc4021.png">
 ##
A description box popped up with details of the CSV and multiple options to click on. I clicked on “Load” to load the data.  
<img width="802" alt="Amazon 2" src="https://user-images.githubusercontent.com/130637591/235514172-5af3df5b-509f-4a1a-8c8e-8c9fed52fcda.png">
 ##
Now, you see below, 404 rows loaded.                                                                                                                                  <img width="938" alt="Amazon 3" src="https://user-images.githubusercontent.com/130637591/235520835-b1f9575b-5446-431e-ab5d-70e135ebe1ec.png">
 ## Data Cleaning :shower:
My first cleaning process was to convert the "Number Of Seasons Available" column from "General" to "Number" format.      
<img width="802" alt="Amazon 4" src="https://user-images.githubusercontent.com/130637591/235521545-3d5cbd1a-3e85-4758-a003-eeba0703fb26.png">
 ##
Now, the "Genre" column has got multiple genres for each row, but I only need one for each.                                                                           <img width="802" alt="Amazon 5" src="https://user-images.githubusercontent.com/130637591/235523250-fd520e21-114a-47c1-af0e-22e2889c7f71.png">
 ##
I used the "Convert Text to Column Wizard" to separate the row values into different colums, utilizing the "Delimeter" option. <img width="802" alt="Amazon 6" src="https://user-images.githubusercontent.com/130637591/235523927-590acb85-24bb-42c1-9da3-c0441bcfe48a.png">
 ##
Here is the extracted column. <img width="802" alt="Amazon 7" src="https://user-images.githubusercontent.com/130637591/235524720-a21fe300-2b0f-483e-aab0-e6de55b4ec03.png">
 ##
Delete the other columns not needed.
<img width="802" alt="Amazon 8" src="https://user-images.githubusercontent.com/130637591/235525371-5c5489a5-79d2-463c-9509-8fdc3972066a.png">
 ##
Convert the "IMDb Rating" from "General" to "Number" format. 
<img width="802" alt="Amazon 9" src="https://user-images.githubusercontent.com/130637591/235526613-d0bd25d5-a747-437b-9f59-939055ec5432.png">
 ##
My first cleaning process was to filter the data for blank rows and remove them. I used the shortcut Alt + A + T to add a filter, searched for blanks and then clicked OK.                                                                                                                                                                           
<img width="802" alt="Amazon 10" src="https://user-images.githubusercontent.com/130637591/235801219-7fec0db1-2c4e-4c8c-b7b1-744b835197eb.png">
 ##
Now, below are the empty rows. I selected all empty rows and deleted them.
<img width="802" alt="Amazon 11" src="https://user-images.githubusercontent.com/130637591/235801615-aa825cf9-4587-4e4a-a78f-d1151144776c.png">
 ## FUNCTIONS & PIVOT TABLES FOR SUMMARY STATISTICS :bar_chart:
For multi-conditional calculations, Pivot Tables are a powerful tool and they are faster than using formulas because they take less time to set up than other formula methods. But for this project, I used both the COUNTIF Function and PIVOT TABLES as well.                                                                                                                                                                    
I was looking to answer some questions to gain insight from the dataset. The questions were:                                                                                  

a) Which genres are most popular among Amazon Prime users?                                                                                                                   
b) Which age groups are most interested in Amazon Prime TV shows?                                                                                                                         
c) What are the top-rated shows on Amazon Prime?                                                                                                                              
d) Which languages are most popular among Amazon Prime users?                                                                                                                                                                                                                              
            
















