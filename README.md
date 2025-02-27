# Data and analysis for the eel_mystery website

 I created the website ["The mystery eels of Prospect Park"](https://adiel3.github.io/eel_mystery/) as my first project for Lede 2024. This is the data analysis repository for the project. The website repository can be found [here.](https://github.com/adiel3/eel_mystery)
 
## The data
I wanted to explore what kinds of weird animal incidents were happening around New York City, after reading a few headlines about eels and alligators found in parks in the last few years. 

 Before I chose this dataset, I first looked through animal-related 311 calls to see what city agencies handle what kind of calls. They were handled by the Department of Health and Mental Hygiene, Police, Sanitation (for dead animals outside of parks), and Parks Department. Based on an initial analysis of that data using pandas to see the type and number of calls each agency responded to, I chose to focus just on the Parks Department, which had this second, more detailed dataset about requests for animal assistance, relocation, and/ rescue completed by urban park rangers.

## The analysis
 I started with an initial list of questions about the number of eel-related incidents and similar incidents, but quickly found myself facing new ones, as I was confronted with missing data, including the headline-grabbing initial eel incident that prompted me to start this whole analysis.

 I examined the data many different ways, consulted the data dictionary and even sent a request for comment to the Parks Department in my attempt to account for the missing eels.

 I then turned my attention to exploring other unusual animal incidents in the data. In the end, I made five charts using datawrapper, four of them exported as csvs from my jupyter notebook, the fifth built by hand as it combined a data point from outside the database with two within it (the number of eels per incident chart). 

 The analysis for this project was good practice for my use of pandas, though much of my code did not make it into the final story and data.

## The presentation
 This was my first time using datawrapper for multiple kinds of charts and I realized as I was working with it that several of my csvs needed to be reformatted slightly in order for the data to translate properly into the charts. I made those adjustments in excel, so the csvs created from my notebook are not perfectly formatted for datawrapper. Next time I will think more about how to do that in my code before exporting.

For other art, I pulled images from [a website of creative commons icons](https://thenounproject.com/) recommended by Aaron Reiss, our mapping professor.

I coded my first functioning website for this project in html, and successfully uploaded it to github. I used a template Soma provided, which was easy to use and tweak, and something I will definietly get faster at with practice. 

### A note
The initial commit of this project repository contained only the [original csv](https://data.cityofnewyork.us/Environment/Urban-Park-Ranger-Animal-Condition-Response/fuhs-xmg2/about_data) I downloaded from New York City's open data portal (park_animals.csv), its data dictionary, and the csvs I saved from my jupyter notebook and turned into charts in datawrapper.

 My code notebook required some cleaning before uploading, but was added to the repository two days later.

