# Olympic Prestige

The Olympic Games are global sports events where athletes from around the world compete in various sport competitions. Despite their popularity, hosting the Games incurs significant financial risks, with average costs exceeding $8.9 billion per event. A study by the University of Oxford's Said Business School found consistent cost overruns for hosting countries over the past 60 years, questioning the financial rationale behind hosting the Olympics.

This project, 'Olympic Prestige,' aims to investigate the perceived benefits of hosting the Olympics. One hypothesis is that hosting countries may gain a homebase advantage, leading to increased medal counts for their athletes. Additionally, the extensive data available on Olympic athletes, dating back to 1896, allows for an examination of physical factors such as age, height, and weight to identify trends and changes in Olympic sports.

## Data sources: 
Costs&Outturn databases - https://data.world/sports/olympics

Olympic Athletes database - https://data.world/johndimm/olympic-medals-1896-to-2014-in-detail

Oxford's Said Business School Study - https://dx.doi.org/10.2139/ssrn.2804554

## Presentation link:
https://docs.google.com/presentation/d/1CPESXT-HilZzopMpjXpdZAfdavBT59S3AntgzG7g45s/edit?usp=sharing

## Getting Started
In 'Data cleaning, filtering, csv export' Jupyter NB you can find the Cost and Outturn CSV's have been uploaded, cleaned and manipulated as df1 and df2, accordingly. 
df3 is detailing the medals and their respective winners, while df4 are detailing all athletes participating in Olympic events regardless of medal wins. Once NaN rows cleaned and categories labeled, the NB ends with exporting to MySQL.

'Home Advantage;Data cleaning,SQL queries,Functioning,Hypothesis' Jupyter NB queries relevant SQL databases into combined data frames which allow for further analysis. Once combined and further encoded (summer games = year_1 , winter games = year_0), a function called 'calculate medals' designed to output two new columns for each hosting country(each row) calculating the wins from the games before&after the hosting year. These new columns are used to test the hypothesis that "homebase advantage" increases the amount of medals won by the hosting country in the following games. See three relevant hypotheses. The NB ends with an export to CSV, fur further plotting in Tableau. 

## Conclusion
The hypotheses were rejected, and "homebase advantage" not significantly proven. Presumably all hosting countries athletes' benefited from investment in sport facilities , however this did not decisively profit the medal count of the hosting country. 
When looking into the Olympians physical factors data, the biggest changing sport found over the decade data span was of Bobsleigh. The change in over 20kg average athlete weight, tells the story of the changing sport and it's machinery. 
