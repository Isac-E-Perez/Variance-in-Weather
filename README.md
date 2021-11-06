# Variance in Weather Project
### About: 

For this project, I implemented data analysis using R. I used the libraries readr, and dplyr which helped me to build the project. I analyze the dataset from 2015 that contains over 39,000 data points about weather conditions in London to gain a better understanding and insight about weather condition during that time.  
 
### Note:

I could not find the dataset that I used for this code, therefore to prove I understand how to analyze similar datasets with another project called Variance in Weather in London, England Project that I will expand on more.
 
# Variance in Weather in London, England Project
### About: 

For this project, I implemented data analysis using R. I used the libraries readr, dplyr and tidyverse which helped me to build the project. I analyze the 2015 data of Smeteostat.net to gain a better understanding and insight of the weather conditions in London, England. 
 
### Note:

This data comes from meteostat.net 
 
### Results:
Here are the results I gained through data analysis of the England_data.csv data.

-- Here is the process:

I first read the *England_data* csv and set it equal to England_df.
 
<img width="246" alt="Screen Shot 2021-11-06 at 4 31 27 PM" src="https://user-images.githubusercontent.com/89553126/140624382-68d38706-e6fc-4cd7-aa23-8e76bd5e89ea.png">

I then inspected the data and gleamed that there was **365** rows and **11** columns of data.

The *average precipitation* was then calculated for all of 2015 equalling **1.512707 mm**.

<img width="411" alt="Screen Shot 2021-11-06 at 4 32 09 PM" src="https://user-images.githubusercontent.com/89553126/140624406-2cf96e2b-0cc5-4a1d-84fe-09f3974157dc.png">


The *precipitation variance* for the year was **15.90826 mm** and the *precipitation standard deviation* was **3.988516 mm**. 
 
<img width="481" alt="Screen Shot 2021-11-06 at 4 32 45 PM" src="https://user-images.githubusercontent.com/89553126/140624433-25a9348e-1515-4e13-afa2-11a3d88466ba.png">

I inspect and defined *june* and *july*.

<img width="598" alt="Screen Shot 2021-11-06 at 4 33 16 PM" src="https://user-images.githubusercontent.com/89553126/140624448-22a7d1a1-def6-4f12-ad0c-189a90bfcf19.png">
 
Afterwards I found the *monthly mean of the precipitation* in june and july, which were **0.4233333 mm** and **2.325806 mm** respectfully.

The *monthly standard deviation of the precipitation* in june and july, which were **1.14521 mm** and **6.959692 mm**.
  
### June's Average Temperature

![june_temp](https://user-images.githubusercontent.com/89553126/134444162-21757da5-5716-408a-9f5f-90db3e99cc7c.png)

### July's Average Temperature

![july_temp](https://user-images.githubusercontent.com/89553126/134444174-ebf0bcbd-da03-42d9-8cfc-b2cccea47ed5.png)

### Average Temperature
 
![England_df_temp](https://user-images.githubusercontent.com/89553126/134444183-32a3a8ed-fcfb-4a6f-9893-8aeda41bd297.png)

### June's Precipitation

![june_prcp](https://user-images.githubusercontent.com/89553126/134444204-7987f954-060c-4810-b215-4775ef6d2595.png)

### July's Precipitation

![july_prcp](https://user-images.githubusercontent.com/89553126/134444217-ea71324e-fda7-4651-8a1b-7c1deb8de318.png)

### Precipitation

![England_df_prcp](https://user-images.githubusercontent.com/89553126/134444225-c45b7e87-422c-4d7e-8ef2-413e8e33dd96.png)
