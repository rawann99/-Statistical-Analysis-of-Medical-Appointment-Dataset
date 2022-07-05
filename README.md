# -Statistical-Analysis-of-Medical-Appointment-Dataset
 This dataset is drawn from 300,000 primary physician visits in Brazil across 2014 and 2015. The information about the appointment was automatically coded when the patient scheduled the appointment and then the patient was marked as having either attended or not. The information about the appointment included demographic data, time data, and conditions concerning the reason for the visit. ################################################################## ##problem 2 Explore the data: Show the type of the data and assign each of feature, phenotype and expression data to different variables 1.a Show the type of each column 1.b Show column names and rows name 1.c Calculate summary of each column 1.d Show frequency of categorical data, taking into the consideration, NA values frequency if any. 1.e Calculate the correlation and covariance between the first 10 columns only of our data set and draw full correlation matrix. 1.f For both genes: GSM95478,GSM95473 show the plot with a line of their relation. => Question 2: Using PCA and SVD, Prove by plotting and values that both can return the same result by suitable normalization. =>Question 3: 256 visual artists were surveyed to find out their zodiac sign. The results were: Aries (29), Taurus (24), Gemini (22), Cancer (19), Leo (21), Virgo (18), Libra (19), Scorpio (20), Sagittarius (23), Capricorn (18), Aquarius (20), Pisces (23). 3.1) Test the hypothesis that zodiac signs are evenly distributed across visual artists. 3.2) Explicitly mention your H1 and Ho assumption. => Question 4: Plot hierarchical clusters on our first 10 columns of edata and apply the kmeans to all the edata columns and show the centroid of the result. Setups to Download Data: 1- Install bioconductor (refer to the labs in this step) 2- Install antiProfilesData By BiocManager::install("antiProfilesData") 3- To Access our data use antiProfilesData::apColonData
