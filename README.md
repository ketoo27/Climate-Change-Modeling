Climate Change Sentiment Analysis Project
Table of Contents
Project Overview
Dataset Description
Data Science Applications
Methodology
Data Cleaning and Preprocessing
Sentiment Analysis
Trend Analysis
Engagement Analysis
Topic Modeling
Results
Sentiment Analysis Results
Engagement Analysis Results
Topic Modeling Results
Ethical Considerations
Future Work
Acknowledgements
Project Overview
This project analyzes over 500 user comments collected from high-performing posts on NASA's Facebook page dedicated to climate change. The analysis aims to gauge public opinion on climate change, identify trends in sentiment and engagement, and uncover prevalent themes in the discourse surrounding this critical global issue.

Dataset Description
The dataset includes the following columns:

date: The date and time when the comment was posted.
likesCount: The number of likes each comment received.
profileName: The anonymized name of the user who posted the comment.
commentsCount: The number of responses each comment received.
text: The actual text content of the comment.
Sentiment: The sentiment score assigned to each comment.
The data was collected from various posts between 2020 and 2023.

Data Science Applications
Despite being a small dataset, it provides valuable opportunities for analysis and Natural Language Processing (NLP). Potential applications include:

Sentiment Analysis: Gauge public opinion on climate change and NASA's communication strategies.
Trend Analysis: Identify shifts in public sentiment over the specified period.
Engagement Analysis: Understand the correlation between the content of a post and user engagement.
Topic Modeling: Discover prevalent themes in public discourse about climate change.
Methodology
Data Cleaning and Preprocessing
The dataset was cleaned to handle any missing values and format inconsistencies.
Text data was preprocessed for sentiment analysis, including tokenization, removing stop words, and normalization.
Sentiment Analysis
A sentiment analysis was performed using a pre-trained sentiment analysis model (e.g., VADER) to assign sentiment scores to the comments.
Trend Analysis
The average sentiment scores were resampled by month to analyze trends in public sentiment over time.
Engagement metrics (likes and comments) were aggregated to observe how they changed over time.
Engagement Analysis
Correlation analysis was conducted to understand the relationship between sentiment and engagement metrics (likes and comments).
Visualizations were created to illustrate the correlation.
Topic Modeling
Latent Dirichlet Allocation (LDA) was used to identify prevalent topics in the comments.
The topics were derived from the comments, and key terms associated with each topic were listed.
Results
Sentiment Analysis Results
The average sentiment score across all comments was calculated.
Monthly sentiment trends were visualized, highlighting shifts in public opinion.
Engagement Analysis Results
Correlation analysis revealed insights into how sentiment relates to user engagement.
Trends in likes and comments over time were plotted to showcase engagement patterns.
Topic Modeling Results
Five predominant topics were identified through LDA, along with key terms associated with each topic.
The distribution of dominant topics among comments was visualized.
Ethical Considerations
All profile names in this dataset have been hashed using SHA-256 to ensure privacy while maintaining data usability. This approach aligns with ethical data mining practices, ensuring that individual privacy is respected without compromising the dataset's analytical value.

Future Work
Expand the dataset to include more comments for deeper insights.
Explore additional NLP techniques for more nuanced sentiment analysis.
Investigate user demographics (if available) to analyze how different groups engage with climate change content.
Acknowledgements
We extend our gratitude to NASA and their Facebook platform for facilitating open discussions on climate change. Their commitment to fostering public engagement and awareness on this critical global issue is deeply appreciated.
