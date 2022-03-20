# ufo

### Overview of Project
We will be helping Dana to build a table which will display all of the UFO sightings. We'll iterate through the array of objects in our data file and then append them to a table row. However, she’d like to provide a more in-depth analysis of UFO sightings by allowing her users to filter for multiple criteria at the same time. Users on her site will be able to filter for the city, state, country, and shape.

### Results
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

### Summary
#### Drawback

#### Recommendation 1: 

#### Recommendation 2:
