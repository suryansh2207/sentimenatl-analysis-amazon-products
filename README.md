# Sentimental Analysis of Amazon product reviews

This new project involves performing sentiment analysis and determining the proportion of words that appear in the title that also appear in the description of the review.

I began by examining the initial rows of the dataset to gain an understanding of the data presentation. It is important to note that the header is not a header in the traditional sense, but rather a title of the product review. These titles also serve as the names of the columns.

I proceeded to create two lists of data: title and description. Subsequently, I plotted a histogram to ascertain the proportion of words per review that appear in the title and also appear in the description.

Following the calculation of proportions, I conducted a simple sentiment analysis to determine the compound sentiments of the reviews. My analysis revealed that the majority of the reviews were positive.

In the execution of this project, I am utilizing the nltk library to calculate sentiment value. The nltk library provides a tool that calculates compound sentiment value, which represents the combined score of the positive, negative, and neutral scores of a text.
