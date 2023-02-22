# Twitter Scraping
Twitter Scraping by using snsscrape, MongoDB and Streamlit

**INTRODUCTION:**

  Twitter Scraping with Snscrape and Streamlit is a Python-based web application that allows users to scrape and analyze Twitter data. The application uses the Snscrape    package to extract tweets from Twitter and the Streamlit package to provide a user-friendly interface for analyzing the data. The application can be run on a local       machine and is optimized for performance, making it ideal for scraping large amounts of data.
  
 
**REQUIRED SKILLS:**

 1) Python scripting
 2) MongoDB
 3) Streamlit
 4) Snscrape
 
**Interative GUI using streamlit for twitter scraping contains following features**
 
 1) Can enter any keyword or Hashtag to be searched,
 2) select the starting date 
 3) select the ending date
 4) can enter the number of tweets needs to be scrapped(max: 10000 tweets)
 

 After entering the Above details : 
 1. Can Scrape the tweets based on above input
 2. Can Display the tweets in tabular form in the GUI by clicking show button 
 3. Can upload the scraped tweets into mongoDB database for future accessing
 4. Can download the Scraped tweets in either CSV or JSON format .
 5. Can view the uploaded data or tweets 

**EXECUTION OF THE PROJECT:**

**Pre requisite Installation**

Pre requisite Installation
You should install the latest version of python for executing this project

Install some python libraries

 ```
 pip install streamlit
 pip install pymongo
 pip install pandas 
 pip install snscrape
 ```

**RUN LOCALLY**

Clone the project

  
  git clone: [https://github.com/MonishaO/TwitterScraping](website)
  

Change the directory to directory of project file

Go to the downloaded/cloned project directory in prompt cmd
```
for example:
  cd C:\Users\Admin PC\Downloads
```

Now Run the below command

```
streamlit run "filename.py"
```

```
for example:
streamlit run Twitter Scraping.py
```

**Accessing the localhost server**

      
  You can now view your Streamlit app in your browser.
  
  Local URL: http://localhost:8501
  
  Network URL: http://192.168.43.83:8501
  
  click the above link to display the created Twitter scraping web app
		
