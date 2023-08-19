<!DOCTYPE html>
<html>
<head>

</head>
<body>
  <h1>Netflix Movie Duration Analysis 🍿🍿 </h1>

  <h2>Introduction</h2>
  <p>This project involves performing an exploratory analysis of Netflix movie durations over the years. We'll use Python and its data manipulation and visualization libraries to gain insights into the trends and characteristics of movie durations on the Netflix platform.</p>

  <h2>Data</h2>
  <p>We started by analyzing average movie durations from 2011 to 2020, provided by a friend. These durations are: 103, 101, 99, 100, 100, 95, 95, 96, 93, and 90, respectively. To delve deeper, we obtained more comprehensive data from a CSV file ("datasets/netflix_data.csv").</p>

  <h2>Project Steps</h2>
  <ol>
    <li><strong>Loading Data:</strong> We began by loading our friend's data into a dictionary and created a DataFrame. This data provided initial evidence that movie durations might be decreasing.</li>
    <li><strong>Creating a DataFrame:</strong> We created a DataFrame using pandas from the dictionary, allowing us to manipulate and analyze the data more effectively.</li>
    <li><strong>Visual Inspection:</strong> We visually inspected the data by creating a line plot to observe the trend in movie durations.</li>
    <li><strong>Loading More Data:</strong> We loaded additional data from a CSV file containing Netflix data. This data included details about movies and TV shows.</li>
    <li><strong>Filtering for Movies:</strong> We filtered the data to focus only on movies by selecting rows with the "Movie" type and relevant columns.</li>
    <li><strong>Creating a Scatter Plot:</strong> We created a scatter plot to visualize movie durations over a longer time range.</li>
    <li><strong>Digging Deeper:</strong> We analyzed the distribution of short movies (under 60 minutes) and explored their genres.</li>
    <li><strong>Marking Non-Feature Films:</strong> We marked non-feature films with different colors on the scatter plot to identify trends associated with genres like "Children," "Stand-Up," and "Documentaries."</li>
    <li><strong>Final Plot:</strong> We created a final scatter plot with colored points to visualize movie durations and understand trends better.</li>
  </ol>

  <h2>Conclusion</h2>
  <p>Through data analysis and visualization, we observed trends in movie durations on Netflix. We found that non-feature films, such as children's movies and documentaries, tend to have shorter durations. This project showcases how Python and its libraries can be used to explore and gain insights from data.</p>

  <h2>Future Work</h2>
  <ul>
    <li>Perform statistical analysis to quantify trends and differences in movie durations.</li>
    <li>Explore correlations between movie genres and durations to identify patterns.</li>
    <li>Create more advanced visualizations and interactive plots to present findings effectively.</li>
    <li>Apply machine learning techniques to predict movie durations based on various features.</li>
  </ul>

  <p>Feel free to explore the code and adapt it to your own analyses. Happy coding!</p>
</body>
</html>
