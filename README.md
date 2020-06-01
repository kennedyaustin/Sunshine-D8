# Sunshine-D8


Project Link: https://kennedyaustin.github.io/Sunshine-D8/

# Project Description 
The concept of our project is the facilitation of deciding what to do for a date night. Our goal is to make date-planning easier, complete with customized suggestions based on user input. The categories will be:

● Food & Drinks <br>
● Activities

# Webpage Components
Libraries​: <br>
● HTML5 <br>
● CSS <br>
● Bootstrap <br>
● Jquery <br>
● API calls using AJAX

# APIs:

● Yelp -- https://www.yelp.com/dataset○https://www.yelp.com/dataset/documentation/main & https://www.yelp.com/developers/documentation/v3/business_search
Yelp Fusion
We used this API to pull details from Yelp’s database for two searches: Restaurants & Activities. 
We created selector fields for type and zip code for each to return appropriate results.
(AJAX Used to pull data) 

● Mapbox -- https://docs.mapbox.com/api/maps/
Map Box
We used this API to show where the results pulled from Yelp are located. The user can quickly see where the various results are based on the interactive map. An AJAX request was used to pull data. <br>
![](SunshineD8_SS/MapPreview.png)

# New Technology - Javascript Plugins
Both of the plugins below were used on our sign-in homepage form. <br>
● X-Ray.js <br>
Allow the user to show/hide password strings in their password field when needed. <br>
  ● Hide Password <br>
  ![](SunshineD8_SS/HidingPass.png)
  ● Show Password <br>
  ![](SunshineD8_SS/ShowingPass.png)
● Validator.js <br>
Forces the user to have some sort of email to the degree of being at least 'text@text.com' <br>
  ● Valid Email <br>
  ![](SunshineD8_SS/ValidEmail.png)
  ● Invalid Email <br>
  ![](SunshineD8_SS/InvalidEmail.png)


# Repeating Elements
● Using for loops, we generated repeating elements for activities and restaurants from the Yelp API: <br>
Image <br>
Business Name <br>
Phone Number <br>
Rating <br>
Link to Reviews on Yelp <br>
![](SunshineD8_SS/Repeating.png)

# Design Layout
● CSS <br>
● Bootstrap: <br>
    Cards <br>
    Modals <br>
    Columns/Rows <br>
    Buttons <br>
![](SunshineD8_SS/SigninModal.png)

# Validation Specs
● Both search fields (type and zip)= required <br>
● Zip Code- Limited to 5 characters <br>
![](SunshineD8_SS/Validation.png)

# Team Members 
* Austin Kennedy 
* Zalina Magiday
* Dana Nobile 
* Joshua Maldonado
* Majid Modak
* Jackie Geiger 
