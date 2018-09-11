# Udacity Project - Dataset Investigation

## An Investigation of Firearm Background Checks Using the FBI's NICS and U.S. Census Data

### Introduction:

This project is a part of Udacity's Data Analyst Nano-Degree Program Term-1(April Cohort, 2018).

The data used in this project has been sourced from the FBI's National Instant Criminal Background Check System and the U.S. Census of 2016. These datasets have been curated by Udacity and can be viewed here.

According to the FBI's official website the NICS is:

"Mandated by the Brady Handgun Violence Prevention Act (Brady Act) of 1993, Public Law 103-159, the National Instant Criminal Background Check System (NICS) was established for Federal Firearms Licensees (FFLs) to contact by telephone, or other electronic means, for information to be supplied immediately on whether the transfer of a firearm would be in violation of Section 922 (g) or (n) of Title 18, United States Code, or state law. The Brady Act is a public record and is available from many sources, including the Internet at www.atf.gov."

"The NICS is a national system that checks available records on persons who may be disqualified from receiving firearms. The FBI developed the system through a cooperative effort with the Bureau of Alcohol, Tobacco, Firearms and Explosives (ATF) and local and state law enforcement agencies. The NICS is a computerized background check system designed to respond instantly on most background check inquiries so the FFLs receive an almost immediate response. In calendar year 2015, the NICS Contracted Call Centers (NCCC) handled calls an average of 141 seconds. After transferring the calls to the NICS Section, the wait and processing time averaged 446.3 seconds. When firearm background checks were conducted via the NICS E-Check, the wait and processing time averaged 107.5 seconds. Depending on the willingness of state governments to act as a liaison for the NICS, the FFLs contact either the FBI or a designated state point of contact (POC) to initiate background checks on individuals possessing or receiving firearms."

Concomitantly, the U.S. Census Bureau's website states:

"The U.S. Census Bureau has been headquartered in Suitland, Md. since 1942, and currently employs about 4,285 staff members. The Census Bureau is part of the U.S. Department of Commerce. The U.S. Census Bureau is overseen by the Economics and Statistics Administration (ESA) within the Department of Commerce. The Economics and Statistics Administration provides high-quality economic analysis and fosters the missions of the U.S. Census Bureau and the Bureau of Economic Analysis."

"Prior to conducting our investigation, it must be highlighted that the information accompanying the datasets provided by the FBI clearly state that the statistics represented in the number of firearm background checks in the NICS do not represent the number of firearms sold based on varying state laws and purchase scenarios. Therefore, a one-to-one correlation cannot be made between a firearm background check and a firearm sale. These checks can, however, provide a safe estimation of gun sales in the U.S."

### Questions Explored:

**Q1. Which states have the highest guns per capita, both in 2010 and 2016. Also, contrast the top 5 states of 2016 with their data from 2010.**

**Q2. Is there a correlation between the number of veterans and guns per capita (as of 2016)?**

**Q3. What is the overall yearly trend of gun purchases / FBI background checks in the US?**

**Q4. Which states have the highest gun registration rates from 2010 and 2016?**

**Q5. How many checks have there been in each state since November, 1998 in every state?**

### Resources Used:

1. String replace  

https://pandas.pydata.org/pandas-docs/version/0.22/generated/pandas.Series.str.replace.html

2. Replacing specific string characters from dataframe 

https://stackoverflow.com/questions/13682044/pandas-dataframe-remove-unwanted-parts-from-strings-in-a-column

3. Changing string percentages to float
https://stackoverflow.com/questions/50686004/change-column-with-string-of-percent-to-float-pandas-dataframe

4. Dropping characters from DataFrame Index

https://stackoverflow.com/questions/43718432/removing-characters-index-dataframe

4. Merging multiple dataframes together in one go using reduce():
https://stackoverflow.com/questions/23668427/pandas-joining-multiple-dataframes-on-columns

5. Plotting a horizontal bar chart
https://matplotlib.org/api/_as_gen/matplotlib.pyplot.barh.html#matplotlib.pyplot.barh

6. Matplotlib stacked bar chart demo:
https://matplotlib.org/gallery/statistics/barchart_demo.html#sphx-glr-gallery-statistics-barchart-demo-py

7. Seaborn Tutorials:
https://seaborn.pydata.org/tutorial.html

8. Changing x or y label value exponentiation:
https://stackoverflow.com/questions/14711655/how-to-prevent-numbers-being-changed-to-exponential-form-in-python-matplotlib-fi

9. Pandas text book:

    McKinney, W. (2017). Python for data analysis: Data wrangling with pandas, NumPy, and IPython. Sebastopol, CA: OReilly.

10. Python text book:

    Lutz, M. (2017). Learning Python. Sebastopol: OReilly.
