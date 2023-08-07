Project Description: Book Similarity Analysis using Jaccard Similarity

In this project, I have designed and implemented a Python program to explore the relationships between a set of books by calculating their similarity using the Jaccard similarity measure. The dataset used for analysis consists of a collection of books from the Premier League, spanning over 20+ seasons. Each book's content, including fixture details, match results, and the number of goals scored, has been provided for analysis.

Key Features:

Jaccard Similarity: The core of this project lies in the application of the Jaccard similarity measure to determine the similarity between each book and all others. By considering the intersection and union of unique words across books, I calculated the Jaccard similarity, revealing books with similar content.
Stopwords Removal: Before applying the Jaccard similarity, the program efficiently removes irrelevant words, known as stopwords, from the book texts. This step ensures that the analysis focuses on significant words and enhances the accuracy of similarity calculations.
Book Signature: To improve efficiency, the program employs a book signature method. It selects the top 25 most frequently occurring words from each book after eliminating stopwords, creating a concise and representative summary of the book's content.
Data Visualization: The results of the similarity analysis are presented in a tabular form using the tkinter library. This graphical representation offers an easily understandable and visually appealing output, showcasing the most similar books for each book in the dataset.
