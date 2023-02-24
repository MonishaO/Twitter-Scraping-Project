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
   
   You should install the latest version of python for executing this project

   Install some python libraries
      
   ```
      pip install streamlit
      pip install pymongo
      pip install pandas
      pip install snscrape
   ```

**RUN LOCALLY**

1. **Clone the project**

   ```
   git clone: [https://github.com/MonishaO/TwitterScraping](website)

   download the above files from this repository and place inside this folder
   ```
  
2. **Change the directory to directory of project file**

   Go to the downloaded/cloned project directory in prompt cmd

   **For example:**
   
   ```
   cd C:\Users\Admin PC\Downloads
   ```

3. **Now Run the below command**

   ```
   streamlit run "filename.py"
   ```

   **For example:**

   ```
   streamlit run "Twitter Scraping.py"
   ```

   Now run the app using streamlit
   
4. **You can now view your Streamlit app in your browser.**

5. **Local URL:** http://localhost:8501

6. **Network URL:** http://192.168.107.230:8501

After clicking on the above url you can see the app in your browser

![twitter scraping image](https://user-images.githubusercontent.com/125800174/221221377-0a5c5847-6a42-4abb-bb39-41279c832b91.png)








      
    
		
