**AutoDownloader**

Background: 
	There are times when the project we are working on requires large amount of data which are not available on hands. And due to this, we ends up wasting atleast 50-60% of time in gathering data, which are more often found in small chunks. Gathering of data this way is a tedious task and makes us unhappy doing so. In attempt to solve this problem, here i represent my efforts through the mini project, 'AutoDownloader'.  
 
 Tools & Techniques : 
  Data Handling and Web Scraping using Python3.
  
  Libraries :
		- BeautifulSoup
  	- requests
  	- pandas
  	- time
  	- webbrowser
 
Working : 
  As an example, the "airfoiltools.com" website is used to abstract datasets of various airfoils which are distributed among various webpages on the site.
  The module of code, AutoDownloader, does an amazing job in getting all the datasets available on website into a folder, which can be used later for analysis and further processes of a project. The modules does the following tasks :
  - abstracting names of all the available airfoils (8100+ in this case)
  - listing all the webpages in sequence to visit in future
  - visiting and abstracting links for various datasets 
  - finally downloading all the necessary datasets into a folder
Hence, making the whole process of data gathering and storing, an automated task. 

Benefits : 
  - no need to go to website again and again
  - prevents frustration
  - saves a lot of time
  - helps focusing on creative stuff

Drawbacks :
  - requires modification in script based on its use-case.
  
  As every websites is unique in itself, the same thing may not work everywhere but the framework used here can be applied for almost any scenario from gathering text, images, audio files, video files, to even complex datasets. Almost everything we can see on internet and anything we want to download can be automated using this framework.


Thanks for reading!!!
