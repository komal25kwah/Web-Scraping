Tools and Libraries:
I used python library Beautiful Soup to help in the crawling process. Its intuitive interface and features allowed me to extract reviews from web pages efficiently. Its abundance of resources, versatility and powerful features helped the process a lot. I utilized the ‘requests’ module to send HTTP requests and retrieve html contents of pages. ‘csv’ module is being utilized to store the data in the csv file. 
Data Statistics:
In this process, I have collected data from 3 websites 
1.	pakwheels.com
2.	gari.pk
3.	motorcycleshop.pk
From these websites I collected product reviews of both Cars and motor bikes and stored it in the csv file of reviews_data.csv. I have scrapped the data and stored it in the column names of Title, Date, Review text and Ratings. I changed the ratings from star pictorial to readable text form and stored it in the lists. So, it can easily be used for interpretations. I cleaned the review text to remove all the extra and unnecessary words and spaces from it. I managed to get 10,000 distinct reviews from my scrall.
