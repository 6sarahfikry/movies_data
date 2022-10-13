# movies_data
<html>
<head>

</head>
<body>

<h3>1-importing needed libraries</h3>
<h3>2-Data Wrangling </h3>
<p>helps us to find some information about data </p>
<h3>3-Data Cleaning</h3>
 <p>* no duplicates in data  </p>
  <p>*some nan values in some columns that we drooped it that makes row 9826 </p>
  <p>*dealing with data types converting 'Vote_Average' from object to float64
    when try it on 'Vote_Count' it makes error as row1115 its data was unordered so convert its value to nan then dropped row and convert it numeric 'int64' </p>
  <p>* dealing with outliers there were more in Popularity and Vote_Count column so we gropped it  </p>
<h3>4-Data Visualization </h3>
 <h5>!visulizing outliers using boxplot </h5>
 <h5>!visulazing most films types </h5> <p> when we tried it it didnot work as one cell has more than one value we need to seperate it using split()
 the index became duplicted then we reset index visualizing it using catplot kind of count it didnot work as data was object type so converting it to category </p> 
 <p> it works well and 'Thriller',' Drama','Action','Comdey' was the most  </p>
 <h5>!visualizing overrated films </h5>
 <p>we use the data which was more than 75% then use catplot kind 'count' we find 'Drama' films with high rated 'Vote_Average'  </p><p>and to make sure allocated 75% to t column and
 describe it found top = 'Drama'</p>
<h5> !visulizing year has the most movies been made </h5>
   <p>we use DatetimeIndex() method to be able to extract year then using hist() on years column its output is 2020 the most year </p>
 <h3> 5- we need to find film which has the highest popularity and its genre</h3>
  <p>using filtering to allocated maxiumn value to filt then show dataframe of it the film is "Spider-Man" then find its genre it is  Action , Adventure , Science Fiction  </p>
    <h3 style="text-align: center">
 finishing data finally  👀🤷‍♀️ 
  </h3>
 
 
 </body>
 
 </html>
