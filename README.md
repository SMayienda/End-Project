# Karamoja Crop Analysis
![Sorghum](https://github.com/user-attachments/assets/84b49113-0eb7-4df0-91cf-c1a17116d14b)   ![maize](https://github.com/user-attachments/assets/037898e2-bfca-4347-b0ab-dba7d889a055)


# Table Content
1. Business Understanding
2. Data understanding
   a. Research Question
   b. Objectives
3. Importing of Libraries
4. Loading of the data sets
5. Data Shapes
6. Understand the structure and summary statistics of the data
7. Missing Values and Duplicates
8. Combining the two data sets
9. Conclusion
10. Recommendation
11. Future Work

# Business Understanding

Karamoja is the most food-insecure region of Uganda. One of the main reasons is the low productivity level of the crops due to intense droughts as well as pest and disease outbreaks. Karamoja (Links to an external site.)Links to an external site.

In Karamoja, several NGOs provide technical support as well as farm inputs to the farmers experiencing extremely low yields. Though, they lack visibility into the overall state of the region and often need to rely on some very local sources of information to prioritize their activities. Dalberg Data Insights (DDI) has been requested to develop a new food security monitoring tool to support the decision making of one of those NGOs active in Karamoja.

To do so, Dalberg Data Insights developed a methodology to remotely measure the yield of the two main staple crops of the region (i.e. sorghum and maize) based on satellite images. The agri-tech team just ran the model for the 2017 crop season.

# Data Understanding
I will be dealing with the following data:

 1. Uganda Karamoja District Crop Yield

 2. Uganda Karamoja Subcounty Crop Yield

Below is the data composition;

Yield and Population per Subcounty

POP: total population for the subcounty

S_Yield_Ha: average yield for sorghum for the subcounty (Kg/Ha)

M_Yield_Ha: average yield for maize for the subcounty (Kg/Ha)

Crop_Area_Ha: total crop area for the subcounty (Ha)

S_Area_Ha: total sorghum crop area for the subcounty (Ha)

M_Area_Ha: total maize crop area for the subcounty (Ha)

S_Prod_Tot: total productivity for the sorghum for the subcounty (Kg)

M_Prod_Tot: total productivity for the maize for the subcounty (Kg)

Yield and Population per District

# Research Question

As a Data Analyst, the agri-tech team is asking you to develop an interactive visualization tool of the results for this first crop season. This visualization tool that you will develop will be used as a first mockup of the Food Security Monitoring tool that DDI will develop for the NGO. Based on your experience, the team expects you to come up with a first draft within the coming 3 working days. They give you carte blanche in terms of structure and functionalities but they know that the client wants:

At least a map in the dashboard

The possibility of visualizing the results by district or sub-county (two administrative levels used by the NGO)

# Objectives

The population distribution across the district and their subcounties.

The crops productivity in each district.

The crops yield in each district.

View crops productivity verses population.


![dashboard](https://github.com/user-attachments/assets/a796f8c8-56b4-47e9-89fa-aa3bea214c71)




# Conclusion
The population for both district and subcounty is evenly distributed except for Kaabong whose population is very high.

Kaabong has the highest population in district and subcounty level with low crop productivity.

Nakapiripirit seems to have a balance between population and crop productivity and crop yield.

Moronto has the lowest productivity which does not relate to its population which is higher.

# Recommendation
More support needs to be given to Kaabong district to improve its productivity which will match its population that is very high.

Support is also needed in Moroto to improve its productivity.

The same applies to Amudata which has very low sorghum production.

The farmers should try crop diversification.

# Future Work
In the future, I would like to work with this data set having included the following information.

Soil type in each region.

Climate seasons.

The seed and fertilizer used are common across all the districts.

https://github.com/SMayienda/End-Project/blob/main/KARAMOJA_PROJECT_.ipynb

https://public.tableau.com/views/KaramojaCropAnalysis_17249659675940/KARAMOJACROPANALYSIS?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link
