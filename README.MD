## Perl Project - Create RSS feed of News Site
Due: Friday, 2/24, 11:59pm
### Description
Work in groups of 2. Write a Perl script, perlproject.pl, to create a RSS feed of the news items at a news site, such as https://www.monmouth.edu/News or http://technews.acm.org. 

Provide the following deliverables by the deadline: 
- The perlproject.pl script
   - Use a Perl module to retrieve the html code at your chosen news site.
   - Write the RSS feed XML file, news.rss.xml, to disk.
      - A good location is in the public_html directory under your home directory, so that it can be published to the Web.
      - news.rss.xml will consist of the news headlines and url links to the articles.
- A valid URL at which your RSS feed can be tested
   - Example: http://rockhopper.monmouth.edu/~jchung/cssenews.rss.xml

### Notes
Your script needs to parse out the individual headlines as well as the corresponding http URL link for each article. 
- You can use another Perl module for HTML parsing or do it yourself with regular expression matching.
Your script must generate a valid RSS feed. Use https://validator.w3.org/feed/ to validate your RSS feed. 
An example RSS file, assembled from http://technews.acm.org, can be found at http://rockhopper.monmouth.edu/~jchung/technews/technews.rss.xml (I recommend saving it to disk to view it). 