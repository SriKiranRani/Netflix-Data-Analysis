# Netflix-Data-Analysis
Explore Netflix's content trends with insights into ratings, genres, and international distribution. Develop a movie recommendation algorithm using TF-IDF and cosine similarity. Identify notable directors and actors based on specific ratings.

# Objective
- Gain insights into Netflix's content distribution, focusing on movies and TV shows. 
- Understand the trends in Netflix's content library, including factors such as ratings, genres, international distribution, and the platform's emphasis on TV shows versus movies.
- Creating a movie recommendation algorithm which uses the TF-IDF matrix and cosine similarity to find titles that are textually similar to a given input title.
- Identify directors or actors known for producing or starring in content with specific ratings.

# Overview
The project extensively employed exploratory data analysis (EDA) using Python, utilizing libraries 
such as pandas, matplotlib, seaborn, and scikit-learn. The Netflix dataset was meticulously explored, revealing its structural nuances.

# Netflix Analysis Dashboard
![image](https://github.com/user-attachments/assets/99144404-81a1-4049-b4fc-f3f0ed5f454e)


# Techniques Used

## TF-IDF (Term Frequency-Inverse Document Frequency): 
- TF-IDF is a numerical statistic that reflects the importance of a word in a document relative 
to a collection of documents (corpus). It considers the frequency of a term in a document 
(Term Frequency) and the rarity of the term across the entire corpus (Inverse Document 
Frequency). 
-  The TF-IDF matrix is created using the TfidfVectorizer from scikit-learn, which converts a 
collection of raw documents to a matrix of TF-IDF features.

## Cosine Similarity:
- Cosine similarity is a metric used to measure how similar two documents are. It calculates 
the cosine of the angle between two vectors, representing the documents, in a 
multidimensional space. 
- In our recommendation system, we compute the cosine similarity between all movies based 
on their TF-IDF vectors. This similarity score is then used to identify movies that are most like a given input.

# Results: 
- The recommendation system successfully provides meaningful and relevant movie 
suggestions based on the textual features of the titles. When a user inputs a specific movie 
title, the system identifies similar movies from the dataset. The results are displayed as a list of recommended titles. 
- These recommendations leverage the textual information (title and description) of the 
movies to suggest content that is semantically similar, providing users with a personalized 
and engaging viewing experience. 
- This recommendation system enhances the overall user experience on the Netflix platform by 
offering tailored suggestions, increasing user satisfaction, and encouraging continued 
engagement with the diverse content library.

# Conclusions
## Key Findings: 
- The top-rated movies analysis highlighted the prevalence of TV-MA ratings, followed by TV
14 and TV-PG. 
- Decadal analysis showcased shifts in the prominence of specific ratings over different 
decades. 
- Content distribution by country identified the United States, India, and the United Kingdom 
as leading contributors to Netflix's diverse content library. 
- The content similarity analysis successfully provided recommendations, improving user 
experience and content discovery. 
- The focus analysis indicated a notable increase in TV show production compared to movies 
in recent years.

##  Strategic Content Adaptation: 
- Netflix has strategically evolved its content library, making significant adjustments over the years to cater to changing viewer preferences and market dynamics.

##  Genre and Rating Focus:
- The platform's content strategy involves a keen focus on specific genres and ratings, 
reflecting a targeted approach to meet diverse viewer demands and preferences.

## Format Preference: 
- The investigation reveals a noteworthy shift in focus towards TV shows in recent years, 
indicating a strategic emphasis on episodic content over traditional movies.

## Enhanced User Engagement: 
- The recommendations generated through content similarity analysis contribute to an 
enriched user experience, fostering higher engagement by aligning content suggestions with 
viewer preferences.

## Actionable Insights: 
- The insights gained from this analysis provide valuable guidance for content creators, 
platform managers, and decision-makers within Netflix, offering actionable strategies to 
further optimize content offerings and viewer satisfaction.




