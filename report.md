# Summary

## Initial Problem
1. When I first input the website into the notebook I received a warning message stating to add low memory = FALSE to the code.

## Solution
At first I wasnt sure what that meant so I googled it and it said to add low memory = False to the end of the link. 

low memory = FALSE means that the whole columns will be read in first, and then the proper types determined. 
## Data Organization
1. I decided to add the sep='|' at the end of the csv line after low memory = FALSE so it would organize the data better as we learned during lecture.
2. As I did this I checked to see how the data would be organized by inputting data and running the code.
## Headers
1. I ran the code print(data.head()) so I could see what the first 5 headers of the data would be.
2. I did play around with this code by adding more header options like:
   - print(data.head(20))
   -  print(data.head(50))
   -  and so forth.
## ICD Codes
- At this point I wanted to determine what ICD codes I would find but it was a little tricky figuring out what I was looking at while going through the header options.

I proceeded to look back at the data link itself in safari and scan through the data for some examples.
Once I had chosen what I believed were ICD codes, I chose 8 and defined them one by one for easier input of the variables into the rest of the code.

 I used the variable names: 
- drg_codes
- icd_codes1 
- icd_codes2 
- icd_codes3 
- icd_codes4 
- icd_codes5 
- icd_codes6 
- hcpcs_codes 

## Frequency
1. I input the code to check for the frequency of how often these codes showed up in the data.
2. Once given the output I checked to make sure there were not any code sets that were missing and if there was then I would replace them or disregard them from my analysis.
## Analysis
1. I noticed that there was repetition within some ICD code sets.
For example:
- ICD_DGNS_CD10 and ICD_DGNS_CD6 shared the codes: E1121 , R931 , Z653.
- ICD_PRCDR_CD4 and ICD_PRCDR_CD7 shared the code: Z1331.
- ICD_PRCDR_CD4, ICD_PRCDR_CD15, and ICD_PRCDR_CD25 shared the code: Z9981.
- ICD_PRCDR_CD15 and ICD_PRCDR_CD25 shared the code: F08H5ZZ.
## Code Dictionary
1. E1121-Type 2 diabetes mellitus with diabetic nephropathy.
2. R931-Abnormal findings on diagnostic imaging of heart and coronary circulation.
3. Z653-Problems related to other legal circumstances.
4. Z1331-Encounter for screening for depression.
5. Z9981-Dependence on supplemental oxygen.
6. F08H5ZZ-Wound Management Treatment of Integumentary System (Whole Body).


