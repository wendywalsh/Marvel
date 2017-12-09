# Marvelous_Analysis README

Team Members: Jiji Jacob, Alex Murray, Wendy Walsh, Ian Womack

Team goal: Compare the success of Marvel vs DC with target span of 20 years, covering both comics and movies, to discover who came out on top, and why. 

Movie Analysis:
We retrieved list of movies from https://www.statcrunch.com and plotted data using sums and means of box office sales to illustrate trends.  We also used the list of movies to query the OMDB API and obtain rating data from different sites in order to plot average ratings per movie.

Comic Book Analysis:
We downloaded 20 years of monthly comic book sales for Marvel, DC, and other comic brands from http://www.comichron.com/monthlycomicssales.htmla and used Python to call each file and perform analysis on the average comic books sold each year.  We illustrated this for both the top 30 comics sold in each month and also on the total commic books sold per year.  Using bar graphs, a pie chart, and regression analysis, we concluded that Marvel has consistently outperformed DC and this will continue.

Twitter Analysis:
Using Tweepy API, we retrieved the number of followers for both Marvel and DC to determine which is more popular on Twitter.  We also used the Vader Sentiment Analyzer to calculate and plot the polarity on  tweets for the recently released blockbusters Thor (Marvel) and Justice League (DC).

Observations:
Marvel has been dominating DC in sales in recent years in both moves and comics.
Even with a massive head start in the film world, DC has fallen behind.
Marvel averages 194 Million sales per movie, while DC averages 134 Million.
Marvel is releasing movies at a much faster pace than DC.
Marvel took the lead in 2000 (X-Men), DC regained lead in 2005 and 2008 ((Christopher Nolan Batman) 
Both Marvel and DC see regular fluctuations in ratings, but Marvel tends to be more consistent
Both companies have been in the comics business much longer than film (Marvel 1939, DC 1934).
Statistical analysis shows Marvel has slight edge over DC in comic book sales.
Marvel has more than double the Twitter followers than DC.
Justice League has more positive recent sentiment than Thor.


The Verdict:
Based on the data we found surrounding Marvel vs DC in both movies and comics, we found that Marvel is the more popular brand.

Reasoning:
Marvel consistently outperforms DC in both comic and movie sales and has a stronger Twitter following.

Additional Analysis opportunities:
Determine correlation between comic sales and movies sales.  


