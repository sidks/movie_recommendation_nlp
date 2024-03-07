# movie_recommendation_nlp

Introduction
Content recommendation and optimization has long been a field that entertainment giants such as Meta, Tik Tok, and Google have been heavily invested in, constantly tweaking their recommendation algorithms in order to keep viewers watching. In my project, I create our own content recommendation algorithm which uses natural language processing to pick out movies that most closely fit what the user is looking for.

Source of Data
The data used in this project was web scraped from IMDB film pages using the library Beautiful Soup. The program was created to perform the web scraping that scraped more than 10,000 web pages, recording information about the film such as the director, the cast, the general plot, genre, year of release, along with other miscellaneous information.

Possible Sources of Bias
User-Generated Content: IMDb uses ratings, reviews, and cast information submitted by users. Hence, it represents the preferences and opinions of IMDb users, this user-contributed data may contain certain biases.

Self-Selection Bias: IMDb contributors may have a specific interest in movies, which may result in biases in the types of movies that are well-documented and rated on the platform.

Temporal Bias: The current popularity of movies may have an impact on IMDb data. The data may be skewed towards recent releases because new releases may garner more ratings and reviews than older movies.

Selection Bias: The movies that are featured on IMDb are typically those that have become somewhat well-known. The underrepresentation of smaller or independent films may result in a preference for mainstream and English-language films.

These are all the libraries that I'm are using
pandas is used for accessing, manipulating, data structure(data frame) and analyzing the data.
nummpy is used for mathematical calculations
spacy is used as a tool for natural language processing
string is used to do string operations
genim is used for topic modeling or document similarity analysis
operator module provides functions that perform standard operations on built-in Python data types
re module is used for regular expressions, which allow you to match and manipulate text using patterns
time module provides time-related functions
BeautifulSoup is a library for web scraping. It allows you to parse HTML and XML documents
requests library is used for making HTTP requests to web servers
WordCloud library is used to create word cloud visualizations, which show word frequency in a visually appealing way.
Matplotlib is used for plotting
defaultdict is a dictionary subclass that provides default values for missing keys.
os module provides functions for interacting with the operating system, including file and directory manipulation.
