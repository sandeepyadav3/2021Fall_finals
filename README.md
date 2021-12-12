# World Poverty Measure
Group Prooject
Project contributers: Sandeep Pala Sreeramulu, Thashma Nellira Ragunanda, Akshat Gupta
Project Topic: World Poverty Measure

Introducton:

Poverty is not just the lack of the money but there are other apects of it such as  poor health, hunger, lack of clean water or deprivation of Electricity o rthe lack os education.

To provide a more complete picture multidimensional poverty measurements can be employed. With this we can see who is spoor and most importantly how. We can further tell the amount of poverty in different locations of the nation and between different sub groups of the people.

Multidimensional Poverty Index (MPI):
It is a poverty indicator that tells us about the numerous disadvantages that poor/ disadvantaged people endure in  terms of living conditions. health and education.
MPI measures 
1. Incidence of multidimenional poverty: The percentage of people in the total population who are multidimensionally poor.
3. Intensity: Th average number of disadvantages a poor person endures.

Datasets used in the project:

https://ophi.org.uk/global-mpi-report-2021/ : A global multidimensinal poverty index dataset provided by OPHI, an institution of UNDP.
and,
https://data.worldbank.org/topic/poverty: Poverty index dataset provided by world bank.

Hypothesis testes in this proect:
1. The MPI urban and MPI rural are accurate indicators of the poverty levels (can verify by comparing it with the % population listed below poverty level).

2. The higher the difference between the income of the highest 10% and the bottom 10%, the higher the chances are for a country to fall under most poor countries.

3. The higher the annualized growth of the bottom 40% of people in terms of income the higher the chances are for that country to push of the poverty zone.

![image](https://user-images.githubusercontent.com/89531599/145722362-0514df23-de91-495f-88d7-525880b562ff.png)


The above list of countries ploted against the poverty estimates (Y-axis) are ranked ( Highest to Lowest for first 20 countries) according to the world bank using only the income factors in these countries. 

![image](https://user-images.githubusercontent.com/89531599/145723253-72932603-01b0-49ec-9ca8-6bddf11084f7.png)

The idea is to change the weights of the other factores that are are included in the MPI data and look for the percentage match with the orignal one. This way we can tell if the MPI rural and MPI Urban are the accurate indicators for poverty. The changes will be done in steps with variable weights given to the different factors. 

When given the highest weights to the NUtrietion, Child Mortality rate and Years of schooling' and lower similar weights to rest of the other factors (According to OPHI); the new list list thus obtained has a 32% match in the sequence if ranks of the first 25 countries. As seen in the new list:
![image](https://user-images.githubusercontent.com/89531599/145723293-46ceff80-86fc-4469-806c-aff17def4600.png)

Similarly, changing the weights further showed different insights as follows: 

When Nutrition, Year of Schooling and School attendence were given the highest weights the graphs the list obtained was (Having a match of 32% between MPI index and World bank ratings):
![image](https://user-images.githubusercontent.com/89531599/145723653-f91d0901-24ec-471b-abf9-e9d245f30775.png)


When factors like drinking water, electricity, housing and assets were given the higher weights; resulted in a 33.33% accuracy. The resulting list of ranking is:

![image](https://user-images.githubusercontent.com/89531599/145723672-f4afb098-c48d-4494-a797-c978241814c8.png)

When gven the highest weight to only Nutrition and Child Mortality the accuracy was 32% and the resulting list of ranking was:
![image](https://user-images.githubusercontent.com/89531599/145723710-c94f57d3-43a0-4444-adae-4e4b8061ae87.png). 

Since the highest match was obtaind for the higher weights of Electricity, Housing , drinking water and Assest. The resulting list will be taken for the final hypotheis testings.






