#Mission To Mars Website

This project is all about web-scraping and visualizing the information we have gathered from specific 
websites about the Moon. News, images, Mars facts and comparison between earth and the moon are presented.

#Process

To perform this project, we used BeautifulSoup and Splinter to automatically scraping four specific websites 
about the moon:

##Hemispheres Moon Images

Mars facts
Recent Moon News
Featured Moon Image
All the gathered information is stored in a Mongo Database. The information is also visualized in a webpage 
created with the help of Flask and Bootstrap as the main template for our html file.

1. Scrapping
During the study of this week module, we extracted information from three out of the four websites are listed 
above. Now, we need to do the same process for the Hemispheres Moon Images. The process was implemented in 
Python using Jupyter notebook: Mission_to_Mars_Challenge.ipynb.

2. MongoDB and HTML template
As it was mentioned before, we use mongodb for storing the extracted information and then using Flask we 
created a webpage for visualizing all the information. This process was implemented using a Python script: 
scraping.py and a HTML template: index.html.

3. Customizing our website
The html file is customized by adding some styling to our app. Specifically, the colors of the jumbotron 
header and the button were changed from the original version. In addition, the hemispheres images were 
reorganized so the four images fit the width of the webpage. This customizing was made by using a css file 
that helps us to overrule the original bootstrap template. The changes are in the file custom.css and Figure 
1 has images of the website before and after the styling.
