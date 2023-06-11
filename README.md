# job-scraper-similarity

In my job search I found LinkedIn's job recommendations to be useful but incomplete.  I wanted to have more control over what jobs I viewed each day I went to apply.

I built a method which does the following:
* Download list of jobs that meet a set of criteria (city, level,keywords)
* Filter out jobs I am definitely not interested in
* Scrape job descriptions for each one of these jobs using Selenium
* Create bag of words of all job descriptions, as well as my resume
* Determine similarity of words using cosine similarity between job description and my resume's bag of words
* Sort these results largest to smallest

This has helped me to apply to jobs that I did not see in my LinkedIn searches.

Thanks and I hope you find this useful!
Jack Mengel
