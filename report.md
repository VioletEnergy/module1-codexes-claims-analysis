### Provide a summary of the most common codes found in the dataset. Analyze and report on any patterns or insights you observe in the codex data (e.g., are certain codes more prevalent in specific regions, times, or patient groups?).

# When I first input the website into the notebook I received an error message stating to add low memory = FALSE to the code. At first I wasnt sure what that meant so I googled it and it said to add low memory = False to the end of the link. low memory = FALSE means that the whole columns will be read in first, and then the proper types determined. 
# After doing this I decided to add the sep='|' to the code so it would organize the data better as we learned during lecture.
# As I did this I checked to see how the data would be organized by inputting data and running the code.
# I then proceeded to run the code print(data.head()) so I could see what the first 5 headers of the data would be. I did play around with this code by adding more header options like print(data.head(20)), print(data.head(50)), and so forth. 
# At this point I wanted to determine what ICD codes I would find but it was a little tricky figuring out what I was looking at while going through the header options. I then proceeded to look back at the data link itself in safari and scan through the data for some examples.
# Once I had chosen what I believed were ICD codes, I chose 8 and defined them one by one for easier input of the variables into the rest of the code.
# By using the variable names 
