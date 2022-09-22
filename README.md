## What is the project about?

The project uses Python along with a web scraping library (*Selenium*) to go through job postings on *indeed.com* and search for specific words defined by the user.

By default, it checks for Data Analytics tools like *Python, SQL, Tableau* and so on. However, the user can use the *search_list* argument to give it a 
custom set of keywords. 

The user can choose the job name, location and the number of jobs being searched.

Each instance of the *jobs* class has a few attributes such as *.jobs_df* which outputs the dataframe with the collected information as well as the *.most_popular* 
attribute, which shows a list of all the found words and their frequencies, ordered by frequency.

