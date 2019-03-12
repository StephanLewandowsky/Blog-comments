# Blog-comments
Data and supporting material for paper on the effects of blog comments on people's attitudes
(Lewandowsky, Cook, Fay, & Gignac, Science by Social Media: Attitudes Towards Climate Change are Mediated by Perceived Social Consensus).

The PDF files contain the Qualtrics printout of the surveys that were used to instantiate the 4 conditions.

The Excel/csv files are raw data files obtained from Qualtrics. (With potentially identifying information removed). 

The file blog4.dat contains the combined data with condition coded in two factors (post and comment).

The variables in the blog4.dat data set are as follows:

* "Qualtafqscore" -- qualtrics internal variable, ignore
 
* "afq1"			 -- raw response to attention filter 1 (correct differs between conditions)
 
* "afq2"			 -- raw response to attention filter 2 (correct differs between conditions)
 
* "afq3"			 -- raw response to attention filter 3 (correct differs between conditions)
 
* "opinionunaffected", -- "My opinion about a blogpost is completely unaffected by the comments made on the article by others" (SD-SA)
 
* "readerconsensus",   -- "Out of every 100 readers of this post, how many do you think support the basic argument made in this blog
post?" (0-100 scale)

* "isupportpost",	  -- "Overall, I support the basic argument made in this blog post." (SD to SA)
 
* "climnatfluct",      -- "I believe that the climate is always changing and what we are currently observing is just natural fluctuation" (SD to SA, reverse scored)
 
* "climwarmghg",		  -- "I believe that most of the warming over the last 50 years is due to the increase in greenhouse gas
concentrations." (SD to SA)

* "climdamageghg",     -- "I believe that the burning of fossil fuels over the last 50 years has caused serious damage to the planet's
climate" (SD to SA)

* "climCO2cause",      -- "Human CO2 emissions cause climate change" (SD to SA)
 
* "climhuminsig",      -- "Humans are too insignificant to have an appreciable impact on global temperature" (SD to SA, reverse scored)
 
* "sciconsensus",      -- "On a scale from 0% to 100%, in your opinion, how many climate scientists agree that human activity is
causing global warming?" (0-100 scale)

* "age",				  -- age (slider 15-100)
 
* "gender"		      -- M|F
 
* "Tcomment"     -- time spent reading comments
 
* "myafq" 			  -- score of attention filters, only 2 or more correct are included
 
* "post" 			  -- factor for type of post
 
* "comments" 		  -- factor for type of comments
 
* "agw"                -- mean of AGW items
