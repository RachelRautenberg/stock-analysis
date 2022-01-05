#STOCK ANALYSIS
## Overview
#### Work was completed to prepare an anyalysis for Steve in order to have a more clear conversation and decision path with his parents regarding stocks to consider investin in. Analysis considered volume of trades and pricing. Having completed that work, the code was refactored for ease of use and speed of analysis.

### Results

##### The original run time for analysis was approximately .8 seconds. Based on this analysis the recommendation would be that investment in RUN stocks would be the best decision since that particular stock showed higher returns in 2018, than 2018; all other stocks had lower returns in 2018 than 2017 even when still showing positive returns. 

##### ![2017 Stock_Original](https://user-images.githubusercontent.com/96299861/148297516-43898da0-b37b-45a1-939f-b555bb8a3ba1.PNG)
##### ![2018 Stock_Original](https://user-images.githubusercontent.com/96299861/148297646-ab079df0-48c5-453a-b112-3b1a3ed48378.PNG)

##### While that analysis is acceptable, upon refactoring the code, the run time was reduced and the addition of the coloring made the analysis much easier to visually read. 

##### ![2017 Stock Refactored](https://user-images.githubusercontent.com/96299861/148298202-66a4981a-42c4-4385-9d74-c9be28a126ac.PNG)
##### ![2018 Stock Refactored](https://user-images.githubusercontent.com/96299861/148298231-3406f3a8-e836-414a-9f35-5985eec12c24.PNG)

##### Runtime for each year was reduced to almost a tenth of a second, total reduction time of over half a second!  The recommendation remains the same, with the lean toward RUN stocks.

### Summary
#### One clear advantage to refactoring code is the reduced run time. This would be even more impactful as data size grows.  Refactoring should result in overall reduced code block that is both easier to read and edit.  Future editing should then result in lower errors on output or need to debug.

#### Disadvantage to refactoring code, time spent to first review and gather traction in the code to understand what was previously written. 
