<h1 align="center">Scraping Data Analyst Jobs From Wuzzuf</h1> 


### Are you interested in finding a job as a data analyst in Egypt?
Look no further than the Wuzzuf job search website! With the help of this Python script, you can easily extract information about job listings for data analysts and save it to a CSV file for further analysis. The script uses web scraping techniques to find the job titles, company names, locations, required skills, job types, and posted times for each listing.

### The code is organized into three main steps....

* `Scraping the first container`<br>
The first step involves importing the necessary libraries, making GET requests to the [Wuzzuf](https://wuzzuf.net/search/jobs/?q=data+analyst&a=navbl), creating a BeautifulSoup object,
and initializing empty lists to store job information. The script then opens a CSV file and writes a header row for the job information.

* `Scraping the full page`<br>
The second step of the code repeats the process of the first step, but for the full page rather than just the first container,
 looping through each job container and extracting relevant data.
 It appends this information to the relevant list and writes it to the CSV file.
 
* `Scraping multiple pages`<br>
The third step of the code repeats the process of the second step, but for 14 pages instead of just the first page. 
It uses a for loop to iterate over a range of page numbers and modifies the URL to navigate to each page.

**Finally,this Python script provides a convenient, powerful and efficient way to extract job information from the Wuzzuf job search website. 
By automating the data extraction process, it saves time and effort for job seekers looking for data analyst roles in Egypt.
With the help of this tool, you can quickly and easily find relevant job listings and gain insights into the job market. 
This code serves as a valuable resource for those interested in exploring career opportunities as a data analyst in Egypt and can be adapted to scrape other job search websites as well.**
