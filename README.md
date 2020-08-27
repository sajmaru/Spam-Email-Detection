# Spam-Email-Detection📨
A text classifier in Python using classification algorithms of machine learning (Support vector machines, Naïve Bayes classifier) to detect if a given mail or message is spam or ham (not spam). Spam dataset was derived from Kaggle, UCI repository etc.

E-mail is an effective and very cheap means of communication, this fact is being exploited by numerous organizations for carrying out their advertisements. This process is being carried out so extensively that, email inboxes of millions of people are filled with spam e-mails. This results in lot of wastage of valuable time for each user, to go through the spam emails. Additionally, spam emails traffic between servers results in delay in delivery of important e-mails at the right time to the users. Considering the scale and intensity of this problem, I developed a system that uses the concepts of Multinomial Naïve Bayes theorem and Supports Vector Machines to identify spam e-mails. Our spam detection system identifies emails that are spam emails and in turn saves time for millions of users.

**Flow🛠️**

----


1. Exploring Data
2. Snitize Data
3. Removing Stop Words
4. Tokenization 
5. Convert the text into a matrix of token counts
6. Create and train diffiernt models which are suitable for classification with discrete features
7. Evaluate model based confusion matrix & accuracy score

**Best model I have found is support vector machine with 98.3% accuracy🔥.**

**It classifies every non-spam emails correctly (Model precision)📨**

**It classifies 87.7% of spam emails correctly (Model recall)🎉**

