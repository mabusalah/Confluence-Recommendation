# Confleunce Recommendation
Confluence Updates Email Recommendation Based on Interests

This email recommendation system is designed to send relevant emails to members based on their Interactions with the system. I developed this peace of work because the current system lacks such feature.

How Confluence Updates Email recommendation system sends relevant updates:

The system maps labels to members in the below:

        1-Articles you posted to Confluence
        2-Comments on posts, or answers to Questions
        3-Interactions with articles (Likes).

The system then compare the labels collected in step one and matches them to the new Confluence updates.
To reduce irrelevant results the system eliminates generic labels that could reduce the relevancy accuracy.
Finally the system Ranks the results and sends the member a list of Articles sorted by relevancy.

Kindly note that this is a Generic basic skeleton, you might enhance this code, some suggestions are below:

	1- If you have a large users base, you might reduce the likes labels relevancy and increase the authorship of articles/comments relevancy.
	2- You might also consider to include the user's views of articles, which I did not consider because in our case this will not add to the Recommendation system

This project uses Python, Pandas, Numpy and smtplib and was developed for Atlassian Confluence wiki.
