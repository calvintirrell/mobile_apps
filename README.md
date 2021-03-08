# Mobile Apps
Analyzing mobile phone apps data provided by this Kaggle [link](https://www.kaggle.com/ramamet4/app-store-apple-data-set-10k-apps)

# Summary of findings (from code file):
929 apps or almost 13% of all the apps in the data set have 0 ratings. Apps with 1 rating were the next most common at 120 or about 1.6%.

2,603 apps had 1,000 (or more) ratings and 1,016 apps had 10,000 (or more) ratings.
218 apps had 100,000 (or more) ratings and  only 6 apps had 1,000,000 (or more) ratings.

The 'Games' category of apps made up more than 53% (3,862) of all the apps in the data set.
'Catalogs' genre had the least of all categories with 10 apps total. No other genre had over 1,000 apps.

The 2 most expensive apps were both in the 'Education' category: LAMP Words For Life ($299.99) and Proloquo2Go - Symbol-based AAC ($249.99).
Both had user ratings of 4.0 but Proloquo2Go had 773 total ratings compared to LAMP's 41 total ratings.

Using total ratings as a means to help estimate total revenue and such would result in the following for these 2 apps:

| name     	                     | price	 | genre     	| user rating	| total rating count | estimated revenue	| apple app fee | revenue after fee |
|--------------------------------|---------|------------|-------------|--------------------|--------------------|---------------|-------------------|
| Proloquo2Go - Symbol-based AAC | 249.99	 | Education	| 4.0	        | 773	               | 193,242.27	        | 28,986.3405	  | 164,255.9295      |
| LAMP Words For Life	           | 299.99	 | Education	| 4.0	        | 41	               | 12,299.59	        | 1,844.9385	  | 10,454.6515       |

There are a total of 4,056 free apps with an average user rating of 3.53 and median user rating of 4 out of 5.
There are a total of 3,141 paid apps with an average user rating of 3.9 and median user rating of 4.5 out of 5.

Based on this data set the most popular and profitable game is: Final Fantaxy IX.

| name     	       | price	| genre  | user rating | total rating count | estimated revenue	| apple app fee | revenue after fee |
|------------------|--------|--------|-------------|--------------------|-------------------|---------------|-------------------|
| FINAL FANTASY Ⅸ | 20.99	 | Games	| 4.5	        | 1,502	             | 31,526.98	       | 4,729.0470	   | 26,797.9330       |

name     	        price	  genre     	user rating 	total rating count	estimated revenue	 apple app fee  revenue after fee
	 20.99	 Games       4.5	         1502	               31,526.98	        4,729.0470	   26,797.9330
