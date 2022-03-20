<h1 align="center"> UFO's Sightings </h1>

<h3> Overview of Project </h3>
We will be helping Dana to build a table which will display all of the UFO sightings. We'll iterate through the array of objects in our data file and then append them to a table row. However, she’d like to provide a more in-depth analysis of UFO sightings by allowing her users to filter for multiple criteria at the same time. Users on her site will be able to filter for the city, state, country, and shape.

## Results
#### Here are some steps and variation you can do when performing or applying filters.

##### Step 1: Go to website. Here is what you should see on the home page when you first open the website. 
<img src="/images/main.png" alt="main-screen" width="950"><br><br>

##### Step 2: On the bottom left of the website, you will see filters section. Looks like this:
<img src="/images/filters.png" alt="main-screen" width="350"><br><br>

As of right now, there are no filters applied and the result is being displayed on the right hand side of the filters form. Since there is no filters applied, its displaying all of the data. Lets apply some filters and see how it affects our output. 

#
#### Applying the Date Filter
We will start of be applying the `date filter`. Here is how it looks and the output as well.<br><br>
<img src="/images/dateFilter.png" alt="main-screen" width="950"><br><br>
This filter is showing us data from the date of January 1, 2010.<br>

#
#### Applying the City Filter
Next lets add the `city filter`. Here is how it looks and the output as well.<br><br>
<img src="/images/cityFilter.png" alt="main-screen" width="950"><br><br>
This filter is showing us data from the date of January 1, 2010 and only from the city name "El Cajon".<br>

#
#### Applying the State, country and Shape Filter
Next we will add the `state`, `country`, and `shape` filters at once. Here is how it looks and the output as well.<br><br>
<img src="/images/shapeFilter.png" alt="main-screen" width="950"><br><br>
This filter is showing us data where the:
  - date = "January 1, 2010",
  - city = "El Cajon",
  - state = "ca"
  - country = "us"
  - shape = "triangle".
  
 As we can see this only produces two results. <br>

## Summary
### Drawback
Trough my analysis I came across a few draw backs. One being the search fields are "case-sensitive". For example if in the state search parameter I type in "Ca" or "CA", it wont return any results. Although we have put hints in the palceholders, we still cannont expect our users to understand those hints. Another thing I noticed could be a problem is that there is no "filter" button, and there aren't any instructions that notify the user to hit enter or to move to next filter to apply them. One more thing I noticed was that, this data was stored locally. Which means its not as easily updateable. It will be more convenient if the data was stored on a server where it is constantly being updated. This also provides the user with the most up to date information.

There are a few recommendations I can suggest which will help improve the user experience of the app. Here are two that I think will make the most impact.
#### Recommendation 1: 
Adding the data to a server. This will provide the user with the most accurate and current information. 

#### Recommendation 2:
I would make the UI a little bit more user friendly. It's safe to assume that most of our users will not know how to use the website from the start. Creating a user friendly UI can make the user experience a lot better. 
