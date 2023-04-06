# Vishal Mega Mart
 ![image](https://user-images.githubusercontent.com/93968656/230279628-a28c1795-610d-4a66-93eb-02fbf7cce07b.png)

Vishal Mega Mart is India’s leading Fashion led hypermarket with 400+ stores spread across India. Vishal Mega Mart’s mission is to make aspirations affordable for all its customers by providing shoppers with a wide range of Latest Fashion, General Merchandise and Grocery needs. Vishal’s customers love its unique combination of great quality and amazing prices.
Vishal also delivers excellent quality products in fashion, food & grocery and general merchandise at great value through its exclusive brands available only at Vishal.
Assignment Prompt: Retail Store Location Scraper
For this assignment, your task is to scrape the locations of your favourite retail brand in India and extract the following information:
•	Store Name
•	Address
•	Timings
•	Coordinates (Latitude/Longitude) (bonus)
•	Phone Number

## Vishal Mega Mart Website. 
https://stores.vishalmegamart.com/ or https://stores.vishalmegamart.com/?page=1 
There are a of total 21 pages on Vishal Mega Mart website containing details of 559 stores. 
We will scrap them one by one.
## The full process is divided into five Parts.
1.	We will use Postman to create a Request code for us to web scrap data. Postman is an API Platform for developers to design, build, test and iterate their APIs.
2.	We will Copy this Request code and use it in Jupyter Notebook or any other IDE for web scraping the webpage.
3.	We will inspect the website to get the html tag details of the element containing the desired information.
4.	After getting the html tag detail, we will extract the information from webpage.
5.	In the end, we will convert the information we have found from the webpage to a .csv file. 

We will use Postman to create a request code for us to web scrap data.
 
![image](https://user-images.githubusercontent.com/93968656/230279728-8bedda06-71b8-4b9d-952d-5c17fa386ab3.png)
![image](https://user-images.githubusercontent.com/93968656/230279760-da886b4b-6537-4441-a42f-db3c073cf6f6.png)
![image](https://user-images.githubusercontent.com/93968656/230279773-92879cc0-aad7-4ec9-962e-9954ac404881.png)
![image](https://user-images.githubusercontent.com/93968656/230279794-48c63ef6-a40d-4b08-82e6-bd659f2d0ad1.png)
![image](https://user-images.githubusercontent.com/93968656/230279813-5dc1140f-c7f1-4ccd-8acf-8cf009c3b479.png)

This is our Request code. We will Copy this code and use it in Jupyter Notebook or any other ide for web scraping.

## Jupyter Notebook
 ![image](https://user-images.githubusercontent.com/93968656/230279852-8b6131ff-c5b8-47f1-bf00-63b5bd2129a8.png)


### Here we have used a loop. As there are total 21 pages on the website. 
To scrap them all we will do by iterating and then combining the scraped data in a list called “response”.
 ![image](https://user-images.githubusercontent.com/93968656/230279880-85b90439-cb7f-4847-b400-9129b076a2b5.png)


### We are also using Beautifulsoup for scraping and Pandas for data manipulation purpose.
 ![image](https://user-images.githubusercontent.com/93968656/230279902-bb27602b-de64-4331-b3e5-f759dda793c5.png)

Object of Beautifulsoup on a subset data.
## •	Store Name

#### First, we will inspect the website to get the html tag details of the element containing the Store Name.<br>
 ![image](https://user-images.githubusercontent.com/93968656/230279966-8c95708c-14cd-4ff2-af55-8329b673c58f.png)
<br>
#### Second Step is to find the class name of the html tag that contains store name.<br>
 ![image](https://user-images.githubusercontent.com/93968656/230279981-994aa820-50eb-4b72-ae52-d0e073ab5f3d.png)
<br>
#### Now use the class name we find to extract the store name from the website.<br>
 ![image](https://user-images.githubusercontent.com/93968656/230279990-a3989ec9-831e-4d5d-b70a-5bef9e473125.png)

### Similar steps will be followed to extract the Timing, Full Address, Phone no. etc…
## •	Timing
![image](https://user-images.githubusercontent.com/93968656/230280011-b598d714-88f5-404a-8439-c4c8f54a5e61.png)<br><br>
![image](https://user-images.githubusercontent.com/93968656/230280020-a912c9e3-ad66-46ce-86f0-72a46e398952.png)<br><br>
![image](https://user-images.githubusercontent.com/93968656/230280041-093dae87-e088-47ad-b1c4-80ad28991af7.png)


## •	Phone
 ![image](https://user-images.githubusercontent.com/93968656/230280103-fa7cb289-1c19-416e-9082-122bcaeb0cc4.png)<br><br>
![image](https://user-images.githubusercontent.com/93968656/230280115-3424fded-da15-4708-88d1-e6700c752e2b.png)<br><br>
![image](https://user-images.githubusercontent.com/93968656/230280134-925117ee-1367-4faa-9460-1dfa4ea836f0.png)


## •	Full Address
 ![image](https://user-images.githubusercontent.com/93968656/230280154-4c0cf98e-53bf-4c7b-9a4c-5b927fb15a5a.png)<br><br>
![image](https://user-images.githubusercontent.com/93968656/230280175-43d6da1b-dc33-43da-b870-35ad7546435a.png)<br><br>
![image](https://user-images.githubusercontent.com/93968656/230280198-720e9690-3c82-4638-b4e0-fb0e882c19d9.png)

 
## •	City Name
 ![image](https://user-images.githubusercontent.com/93968656/230280218-03d980c2-dac9-4e42-b4c1-3001518d4828.png)<br><br>
![image](https://user-images.githubusercontent.com/93968656/230280238-e60cb81e-7b71-4c9a-8bfb-09314af96c51.png)<br><br>
![image](https://user-images.githubusercontent.com/93968656/230280249-66888bd8-b584-4037-9645-69479101fbf6.png)


## •	Coordinates
 ![image](https://user-images.githubusercontent.com/93968656/230280266-1952df84-6868-46fb-8b64-d2d0cc38aa6c.png)<br><br>
![image](https://user-images.githubusercontent.com/93968656/230280278-80883eca-7516-4dfe-a425-7f46de0c63aa.png)<br><br>
![image](https://user-images.githubusercontent.com/93968656/230280291-d21f467a-1695-410e-a052-69f58adeb14c.png)

 
### Now will scrap out the data from all 559 stores.
 ![image](https://user-images.githubusercontent.com/93968656/230280311-959a217b-65a1-4a01-a302-8a915735b794.png)
<br>
 ![image](https://user-images.githubusercontent.com/93968656/230280336-84d30c75-8bd0-45d7-b1f7-f95b30832204.png)

### As the total number of stores are 559.<br>
### Converting all lists into a DataFrame
 ![image](https://user-images.githubusercontent.com/93968656/230280354-42e82a84-7aad-460f-b1f0-9b14d9a07dda.png)

### Web Scraped Data
 ![image](https://user-images.githubusercontent.com/93968656/230280366-72e9d366-d9c6-4d09-848d-466517344c34.png)

### Saving the pandas DataFrame to a .csv file
 
![image](https://user-images.githubusercontent.com/93968656/230280381-769ea542-3490-41e9-9eaf-e46de5f88dd2.png)



