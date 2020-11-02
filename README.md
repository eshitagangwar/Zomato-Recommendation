# Zomato-Recommendation
Recommendation Engine

1.	From this URL (https://www.zomato.com/bangalore/great-food-no-bull), scrape the following information and store them in a data frame
    a.	Restaurant Name
    b.	URL to the restaurant
2.	Loop through each restaurant and do the following
    a.	Check if you are able to scrape sample reviews. Because certain URLs will take you to restaurant’s branches page. You can skip these kind of restaurants 
    b.	If you are able to scrape sample reviews, make sure you click the load more button continuously in a loop until all reviews are loaded
    c.	From each review extract the following
        i.	Reviewer name
        ii.	Reviewer ID
        iii.	Ratings
3.	Repeat the above process for atleast 50 restaurants. Store all the results in the data frame with the following structure
Restaurant Name	Restaurant ID	User Name	User ID	Rating

4.	Perform exploratory data analysis using the above data
5.	User the above data, build a recommendation engine using User Based Collaborative Filtering. Create a function which takes User ID as input and return 3 restaurants that you would recommend to the user. Make sure you show a sample input and output. 
