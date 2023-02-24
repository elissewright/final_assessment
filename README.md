# Final Assessment

## Self-Assessment:

### I played several roles in my group's project. The first role was searching for data related to the topic of our choice (COVID) and finding an API with large enough data sets fr us to build a model with. I read through the documentation and data dictionary and was able to answer some of the questions about variables that some of my group members had, as I have some previous experience analyzing surveys with similar variables. Over the second week, my group asked me to work on the database side of the project, which was the most challenging part. I really had a hard time with the SQL module, and had to spend several hours rereading pages from that module. I used Quick DBD to make ERDs and was able to easily write SQL codes and upload the CSVs into tables in PGAdmin. It helped having cleaned data sets with minimal column variables, and only two tables of data. A tutor was able to help me with the only issue I had with this process, which occurred when one CSV file had several numeric variables saved as integers, but another file had them saved as decimals. This was an easy fix and the database was created.

### While my group members worked on the model, readme files, and Tableau visualizations, I built a website for us to display our visualizations and some additional details about our project and data source. I initially wanted to make a Flask app, but ended up making an HTML website in the end as it had better customization options and looked more professional. This was also challenging, as I had a hard time with the HTML/JavaScript modules. But building a website to display our dashboard helped me improve these skills a lot. The other difficulty was working with Github, especially in a repository with several branches. It helped me get used to using the terminal to push commits, as I often manually uploaded files during previous assignments in the class. I now feel more confident using the terminal to update my codes.

### The roles I didn't play a major part in were creating the unsupervised machine learning model, and writing the readme file. i still contributed to these parts during group discussions, making suggestions and giving feedback to the group members who primarily did these roles. My group members did the same, giving me helpful suggestions for the parts of the project I worked on.

## Project and Team Summary:

### Our project was to create an unsupervised machine learning model which would reveal any kind of correlations and patterns in COVID-19 data, and hopefully tell us something about cases or death trends in the United States. We pulled our data from a COVID-19 API, and focused on evaluating trends or correlations at the state level. Because we didn't already know anything about the raw data that we could use to make training and testing sets, we decided to make an unsupervised model and keep our research question broad. We eventually settled on PCA as a method, which would cluster the data and find associations which could help us tell a story about the pandemic in the US.

### We started by downloading the API data in CSV format and cleaning it. Before cleaning the data, we had a group discussion about the specific variables and, with help from the data dictionary, decided which ones we would keep or discard. One of my team members cleaned the data set using Python, and I also created a version using R. We both ended up doing the same task because of an initial lack of communication and organization within my group, but it ended up being helpful that both of our final dataframes had the exact same features and observations, making us more confident. Afterwards, we all communicated better and defined clearer roles for everybody going forward. I was given the role to create a database and work on a dashboard, while another member worked on building the PCA model, and the other group members created Tableau visualizations, the readme file, and a template for our presentation slides, which we all contributed to.

### As with many unsupervised models, our results were interesting but did raise many more questions that we would have needed to make additional supervised models in order to explore more in depth. We did find three separate clusters to sort states into, but one state ended up in two separate clusters. This is one unanswered question we would have loved to find more information about. We discovered which states had the highest deaths and cases, but did not do an analysis to evaluate potential relationships between these outcomes and the numbers of vaccines administered in these states; this would have been an interesting relationship to explore with a different model. We were able to compare deaths to cases over time, and found that both followed very similar trends on a line graph. We also found associations between COVID cases and weekly hospital bed admissions.

### One advantage we had with our assigned roles was that each of us was able to work more efficiently on our own, and we ended up making a lot of progress very quickly. Because of this, we were able to go beyond the requirements of the rubric. One member of my group created an additional time-series forecasting model to explore some of the questions that were brought up by the clusters we found within our PCA model. I was also able to make an interactive, static HTML website to display our dashboard instead of creating a storyboard in Tableau. With regular communication in class and on our Slack channel, we were able to work independently and get things done in a professional and efficient manner. We also really enjoyed working on this project.


