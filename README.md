# Datahacks2021
For this Data Science Hackathon hosted by UC San Diego's Data Science Student Society, we were given a dataset containing 590 rows and 8267 columns. Each column represent a word that was used in the religious texts, and the rows represent the frequency of each word used in the chapter. For example, a "0" would mean that the word was not used at all in that chapter. 
The prompt was really open-ended, especially for the data visualization part, but there were guided questions that we had to solve, such as a machine learning model to determine the different time periods from which some books in the Bible came from, and determining if two religions have any sort of influence on one another.

## Tasks
1. First things first, we had to ensure that the data is good to proceed with, thus we had to clean it (checking for duplicates, cleaning null values, etc.)
2. Next, we had to investigate the data and come up with visual plots to see trends that occur in the dataset.
3. We then filtered for the most commonly occuring words from each book to get an idea of each religious text and their beliefs.
4. After getting a better idea of the individual texts, we made a machine learning model to categorize an unlabelled dataset where rows belong to either the book of Proverbs, book of Ecclesiastes, or book of Wisdom. In order to solve this, we chose to run a multiple logistic regression model in order to determine which words matter most in determining which books. After playing around with the word selection, we came with a final model.
5. Finally, our last task was to determine if there were similarities and differences between Taoism and Buddhism by simply looking at their word choices. This required mostly analytical and logical thinking, along with filtering for words that both books mostly use.

This was my very first hackathon, so I learned a great deal from it, from learning to manage a great work ethic to handling the pressure with having to figure out Tableau from scratch in less than 2 hours. Overall, it was a really great experience, and I look forward to more opportunities like this that will allow me to grow both my skills and personality.
