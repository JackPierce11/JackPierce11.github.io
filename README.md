# Jack Pierce: Portfolio

## Contents
- [About me](#about-me)
- [Projects](#projects)
- [Technical Skills and Programming Ability](#technical-skills-and-programming-ability)
- [Education](#education)
- [Medium Articles](#medium-articles)

[Link to my CV](CV%204.0.pdf)

# **About me**


As a graduate with a Masters in Physics with Philosophy from the University of Manchester, I have always had a passion for exploring the world around me. This led me to spend 11 months in Mexico and Brazil, where I improved my Spanish and learned Portuguese whilst slow-traveling. It was during this time that I also began focusing on acquiring data science skills, a topic that has fascinated me for years.

My journey into the world of computers and technology began during my teenage years when I became fascinated by the idea of learning to code. I pursued this interest by taking computing as an extra GCSE, where I learned some coding basics. However, my interest in AI was sparked by a deeper curiosity about how technology impacts our daily lives and well-being. I came to understand that technologies that harness data can have far-reaching effects that can affect society as well as individual lives.

During my Masters, I delved into the topic of the philosophy of language and wrote my thesis on the subject. My research explored how biological evolution might support a specific theory in the philosophy of language. This experience motivated me to learn Spanish and examine the language learning process, which in turn fuelled my passion for languages and their function. This passion continues to drive my interest in NLP and language models.

In summary, my multidisciplinary background and diverse interests in physics, philosophy, language, and data science have fuelled my passion for exploring the world around me. My desire to better understand the impact of AI and use it to create value in the world drives my commitment to enhancing my technical understanding and ability to use tools that help gain actionable insights from data.

# Projects

## [Customer Segment Analysis](https://github.com/JackPierce11/Customer-Analysis)

**Project Summary**

This customer analysis project aimed to identify customer segments and key characteristics that impact purchasing behavior and provide insights and recommendations for improving sales and revenue. The dataset comes from a business with in-store, online and catalogue retail channels.

**Insights and Recommendations**
- High-income customers exhibit the highest average total spending, mean purchase value per order, and response rate to campaigns. Targeting these customers with exclusive and expensive products could lead to increased sales and revenue.
- The catalog sales channel showed the highest average total spending and mean purchase value per order. Customers who preferred this channel also had the highest response rate to campaigns. Investing more in the catalog sales channel could help reach more customers and generate more sales.
- Customers who participated in more campaigns had higher average total spending and mean purchase value per order. Encouraging customer participation in campaigns can lead to higher spending and purchase values.
- One-person households displayed the highest average total spending, mean purchase value per order, and response rate to campaigns. Offering products and services catering to one-person households, such as smaller and more affordable packages or personalized experiences, can drive higher sales and customer satisfaction.


The diagram below shows customer spending differences among different customer segments:

![image](https://user-images.githubusercontent.com/73466733/229087494-c831a884-b6a5-4747-8ab6-42f1b0badb81.png)

---

## [Women's Clothing Reviews Sentiment Analysis](https://github.com/JackPierce11/Womens-Clothing-Reviews-Sentiment-Analysis)

### Women's Clothing Reviews Sentiment Analysis Conclusion

In this project, the aims were to:
- Perform a detailed exploratory data analysis.
- Build a Word2Vec language model based on the corpus of text in the dataset.
- To predict whether customers left 5-star reviews based solely on the review text they left for the item they purchased.

3 neural network models which contained some form of LSTM layer were made with Keras. It was found that **Model 2 had the highest accuracy score of 0.702**. Here is a table to show the results:

<img width="400" alt="image" src="https://user-images.githubusercontent.com/73466733/223437077-ddde4981-f2d0-441c-a90b-9b0365b3b680.png">

**Evaluation of Results:**  A customer rating of less than 5-stars did not always indicate customer dissatisfaction (82% of reviewers said they would recommend the item). The model had significant false positives. Though the dataset was balanced, it did not match the sentiment split of the dataset. The company should focus on understanding why customers leave a positive text review but do not give a 5-star rating in order to improve customer experience.

---

## [Predicting the Winner For Premier League Matches](https://github.com/JackPierce11/Premier-League-Project)

### Predicting Premier League Winner Conclusion
We found that the **random forest classifier** performed the best on our data, with a **CV score of 0.692** and a **test accuracy score of 0.728**. This means that this model can correctly predict the winner of a football match by seeing the post match stats roughly 73% of the time. 

Below is a table that summarises the results for all the models:

<img width="600" alt="image" src="https://user-images.githubusercontent.com/73466733/219405654-3160b6c3-6d4a-4a4a-9436-fb49c73cc58c.png">

Below is a confusion matrix for the random forest classifier:

<img width="400" alt="image" src="https://user-images.githubusercontent.com/73466733/219404636-6a369dcd-4f77-49ce-a1fa-fda1b7bbf061.png">


---

## [Predicting House Price Sale Value](https://github.com/JackPierce11/Predicting-House-Prices)

### Predicting House Prices Conclusion

We can see that our blended predictions had an **r2 score of 0.969781 on the train set** and a **root mean squared error of 13,810 dollars on the original scale.** Our best performing individual model was the Lasso model with an **r2 score of 0.914418** and a **root mean squared error of 18,919 dollars on the original scale**. We will use the blended model to make predictions on the test set and submit those predictions to the kaggle competition.

Below we can see a summary of the performance of all the models:

<img width="550" alt="image" src="https://user-images.githubusercontent.com/73466733/220097769-c91ded10-6096-4cae-b2e4-26fa08045482.png">

Looking the feature importance for the Lasso and Ridge models we can conclude that the characteristics most important to the house price are related to **the size of the house, the size of the land and the quality of the house**.

In the kaggle competition my submission got a score of **0.13205**. This placed me in position 925 out of 3869 teams **(top 24%)**


# Technical Skills and Programming Ability
- Python (Numpy, Pandas, Matplotlib, Seaborn, Sklearn, Keras)
- SQL (familiar)
- Microsoft Office (Excel, Powerpoint, Word)
- Matlab (Applied in Physics experiments)

 
# Education

### Formal Education
 - 2.1 Masters in Physics with Philosophy from the University of Manchester
 

- **Masters Physics Project** - Research and experimental project on magnetic nanobots.
- **Masters Philosophy Thesis** - "In support of Wittgenstein’s critique of the Tractatus: Moving from The Picture Theory to Forms of Life" - I attempt to use biological evolution to add support for Wittgenstein's later philosophy of language.

**Relevant courses** - Mathematics 1 & 2, Vibrations and Waves, Statistical Mechanics, Mathematics of Waves and Fields, Introduction to Non-Linear Physics, Philosophy of Language
 
### Informal Studying
 - Completed Deep Learning Specialisation on Coursera
 - 88% Completed the dataquest data scientist in Python course 
 - Tracked over 400 hours of self study time, using online courses and applying knowledge in projects
 
[I track all the hours I study and keep a log of what I studied each day in Notion.](https://www.notion.so/Data-21230337f4c04fb8acd0bf1d0143b7bd?pvs=4) See link to see the study tracking and organisational skills that help keep me motivated, focused and constantly progressing!


## Medium Articles

[Check out my Medium profile](https://medium.com/@jacktpierce11)

I like to write about my interests that are related to Data Science, AI and NLP.

### Articles:
- [Input-Based Language Learning: What Deep Learning Can Teach Us](https://medium.com/@jacktpierce11/input-based-language-learning-what-deep-learning-can-teach-us-fc0dc7a24a84)
