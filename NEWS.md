## 2019-04-16

 ### What did you do this week?

 - Crystal
    - Run qmodel for 11 threshold for wildtype and 21 thresholds for youtoo. Find optimal threshold for each sample defined by reaching its highest adjusted r^2.
    - Plot all youtoo sample for 3 different thresholds and visually compared.
    - Update function for qmodel and tidy 

 - Emma
    
 - Kalynn
  - API
  - functions for API
  - meetings
  - paper
  


### What is it that you're struggling with right now?

 - Crystal
     - There exists large variation among samples, hard to find the optimal threshold for all. 
     - Hard to evaluate whether PCA transformation is correct by looking at the plot2d in Cranium.
     
 - Emma
    
    
 - Kalynn
  - meeting w confusiing components relative to what we have now?
   


### What are you planning to do next week?

 - Crystal
   - Using optimization to find out the best threshold.
   - 
    
 - Emma
   
    
 - Kalynn
  - help optimization w what Jake wants?
 
   
   
## 2019-04-09

 ### What did you do this week?

 - Crystal
    - Evaluated the "ideal" threshold for the frequency for Wild Type data and You-Too data.
    - Wrote function for model fit assesments. 
       -number of signals
       -r square, RMLSE, quadratic coefficient 

 - Emma
    - Looped through folder to read in data
    - Went through crystal's code and started writing function on freq & fit tradeoff

    
 - Kalynn
  - AWS Bucket access, upload *.h5


### What is it that you're struggling with right now?

 - Crystal
     - How to determine the "ideal" threshold. How could we incorporate variable bias trade off here? 
     - Are there other ways to evaluate the model? How  do we identify when PCA didn't fit the correct first line? I understand that there are the largest variation along this line. 
     
 - Emma
     - Still in the progress of writing functions, will probably have struggles later
  
 - Kalynn
   - access denied aws


### What are you planning to do next week?

 - Crystal
   - Learn API
   - Work on the variance bias trade off.
   - Write functions that could identify difeerent PCA transformation errors.
    
 - Emma
   - Work on the variance bias trade off.
    
 - Kalynn
   - make data public/readonly
   - other potential soltuions
   
   ## 2019-04-02

 ### What did you do this week?

 - Crystal
    - Edit the function of read in h5 file so that it also works for `hdf5r`
    - Learned S3 from Advanced R online book `https://adv-r.hadley.nz/s3.html#s3-methods`

 - Emma
    - Finish editing README
    - Met with Ben and discussed about other options (switching gears)
    - Working with R pacakge `hdf5r` and `rgl`, also `cranium`
    
 - Kalynn
    - meetings
    - catch up on missed meetings
    - review and workd w cranium and 2d & 3d functions

### What is it that you're struggling with right now?

 - Crystal
     - Still need to figure out how to add visualization improvements built on the `plot3d`
     
 - Emma
     - Continue to understand how `hdf5r` works
     - Make 3d plotting work (it works now, but the plot is not the best)

    
 - Kalynn
     - 3d approach and how to improve


### What are you planning to do next week?

 - Crystal
    - Add visualization improvements built on the `plot3d`
    - Learn API
    
 - Emma
    - Look into API
    - Make progress on 3d plotting (and possible adjustments in plotting)
    - Editing functions in `cranium`
    
 - Kalynn
   - contineu to lok for 3d improvments
   - potential API for data, how to store h5 data appropriately


## 2019-03-26

 ### What did you do this week?

 - Crystal
    - Aligned You Too sample data and generated an aggregated sample output as well as an html for all the plots.
    - Open issue for broken code 
    - Organize issues opened by Morgan and Margret.

 - Emma
    - Writing the README
    - Run several sample alignments so that I can put them in README
    
 - Kalynn
    - help start up readme/img
    - Continued to look at the interactivity for the user
    - sick :(

### What is it that you're struggling with right now?

 - Crystal
     - Confused by the structure of the code.
     
 - Emma
     - Needs to re-adjust the size of pictures in README.
    
 - Kalynn
     - pulling out the model that I want user to interact w


### What are you planning to do next week?

 - Crystal
    - Having a clear goal of what changes we could make
    - Start programming
    - List things for the program to be improved
    
 - Emma
    - Going to move onto other parts of the project.
    - Pick one issue, look through the code, try to find a solution.
    - If can't do it alone, ask for help.
    
 - Kalynn
   - look for interactivity for single plots
   - look for interactivity for subplots

## 2019-03-19
- Crystal
  - Worked on the `__init__.py` code, understaning the dimension parameters x,y,z.
  - Worked on DataCamp Intermediate Python for Data Science-Dictionaries & Pandas
- Emma
  - Worked on updating README
- Kalynn
  - review some code
  - looked into interactivity via python


## 2019-03-5

 ### What did you do this week?

 - Crystal
    - Aligned You Too sample data and generated an aggregated sample output as well as an html for all the plots.
    - Open issue for broken code 
    - Organize issues opened by Morgan and Margret.

 - Emma
    - Aligned 14 Wild Type sample data and generated an aggregated sample output as well as an html for all the plots.
    - Aligned 22 You-Too sample data and generated an aggregated sample output as well as an html for all the plots.
    - Met with Crystal to discuss back-end code
    
 - Kalynn
    - Attempted to download and align wild type and you too
    - Family emergency

### What is it that you're struggling with right now?

 - Crystal
     - Confused by the structure of the code.
     
 - Emma
     - Coding
     
 - Kalynn
     - alignment install


### What are you planning to do next week?

 - Crystal
    - Having a clear goal of what changes we could make
    - Start programming
    - List things for the program to be improved
    
 - Emma
    - Meeting with our client today
    - Give our client our new alignments
    - Run over issues with client and see if he's ok with what we want to do
    
 - Kalynn
   -  Meeting w client
   - compare alignments
   - catch up

## 2019-02-25

 ### What did you do this week?

 - Crystal
    - Met with Prof. Barresi and Jake and updated our progress.
    - Distributed sample data, uploaded data on github.
    - Distributed work among three of us.
    - Aligned 14 sample data and generated an aggregated sample output as well as an html for all the plots.
    
 - Emma
    - Met with Crystal and Kalynn and ran through the alignment process
    - Got our new data and split our data to do new alignments
    - Running and correcting actual wild type alignment data
    
 - Kalynn
    - Met w client and Jake with updated progress
    - Meeting to distribute the sample data per person
    - ran over the process
    - ran only 1-2 alignments 


### What is it that you're struggling with right now?

 - Crystal
     - Don't understand the backend process such as how the program ran
     
 - Emma
     - Want to move on to the coding stage
     - Still not exactly clear about what to do next
     
 - Kalynn
     - waiting for coding steps?


### What are you planning to do next week?

 - Crystal
    - Having a clear goal of what changes we could make
    - Start programming
    - List things for the program to be improved
    
 - Emma
    - Meeting with our client again
    - Give our client our new alignments
    - Specify things to do
    
 - Kalynn
   - finish up my part of the alignments
   - meeting with client again
   - compare our alignments to jake's aligments
  

## 2019-02-18

 ### What did you do this week?

 - Crystal
    - Finished Morgan's tutorial, which stopped at landmarks
    - Manually modified sample 02 using Correction Methods
    - Ran landmarks, tried different bin values
    
 - Emma
    - Finished Morgan's tutorial, which stopped at landmarks
    - Synced master branch with our forked repository
    - Ran alignments and landmarks and manually changing codes
    
 - Kalynn
    - Finished Morgan's tutorial, which stopped at landmarks
    - Synced master branch with our forked repository
    - Ran alignments and attempted landmarks


### What is it that you're struggling with right now?

 - Crystal
     - Don't understand the backend process such as how the program ran
     
 - Emma
     - Don't understand the backend process such as how the program ran
     - Some errors when trying to run landmarks
     - We still have two other files we need to run, but no guidance/tutorial
     
 - Kalynn
     - some parts of code, need to run through the libraries used
     - still questions unanswered in terms of continuing on


### What are you planning to do next week?

 - Crystal
    - Having a clear goal of what changes we could make
    - Start programming
    - List things for the program to be improved
    
 - Emma
    - Having a clear goal of what changes we could make
    - Fix errors in landmarks
    - Start programming
    - List things for the program to be improved
    
 - Kalynn
   - meeting with client
   - start programming
   - get better understanding of the code
   - find things needed for potential improvment


## 2019-02-11

 ### What did you do this week?

 - Crystal
    - met w client
    - went through morgan's tutorial
    - attempted to follow along tutorial
    - got the data on hard drive
    - drew hand written letters 
    
 - Emma
    - met w client
    - went throguh morgan's tutorial
    - attempted to follow along tutorial
    - got the data on harddrive, copied from Crystal
    - went to Oregon for presenation
    
 - Kalynn
    - met w client
    - went throguh morgan's tutorial
    - attempted to follow along tutorial
    - sent oak to get spayed


### What is it that you're struggling with right now?

 - Crystal
     - unable to change kernel in jypter (no deltascope :( )
     
 - Emma
     - unable to change kernel in jypter (no deltascope :( )
     
 - Kalynn
     - unable to change kernel in jypter (no deltascope :( )


### What are you planning to do next week?

 - Crystal
    - meet w jake to discuss the installations
    - get updated code
    - get the big data
    
 - Emma
    - meet w jake to discuss the installations
    - get updated code
    - get the big data
    
 - Kalynn
    - meet w jake to discuss the installations
    - get updated code
    - get the big data

## 2019-01-29

### What did you do this week?

- Crystal
    - Set up Python environment-Anaconda
    - Tried to download DeltaScope, ran into issue
    - Created a copy of the original deltascope Repository.
- Emma
    - Set up Python environment-Anaconda
    - Tried to download DeltaScope
- Kalynn
    - Create repos/git related, help others set up
    - Install DeltaScope as is
    - Very BRIEFLY looked at existing code

### What is it that you're struggling with right now?

- Crystal
    - Do not have access to data
    - Can't understand Github code
    - Need to get more information from the in-person meeting with our client on 2/5.
- Emma
    - We will know after we meet up with our client
    - We need to get access to data
- Kalynn
    - We will know after we meet up with our client
    - Getting existing Delta Scope to work, need to download needed dependencies, will look further after meeting w client

### What are you planning to do next week?

- Crystal
    - Understand the code
    - Start to run DeltaScope software with the data
- Emma
    - Meeting with our client and set up a plan for the week/coming week
    - Get the data, watch the tutorial and test deltascope
- Kalynn
    - We will know after we meet up with our client
    - Get existing Delta Scope to work?
    - Look further into the code

