## Statistical Analysis of the impact of pre-harvest growth factors in Hydroponic farming

The Princeton Student Climate Initiative estimates that 
> ‘by 2050, we will need to increase food production by about 70% in order to meet the caloric needs of a global population of 9.8 billion people—68% of whom are projected to live in urban areas.’
> [ref](https://psci.princeton.edu/tips/2020/11/9/the-future-of-farming-hydroponics)
Hydroponics offer an resource and space efficient future for farming ; with hydroponic farms using 90% less water and yielding 3-10 times more crops in the same amount of space.

This project explores the impact of pre-harvest growth factors (such as ionic strength of nutrient solution, light intensity and type of nutrient solution)  on metabolic marker levels. This is done using the Kruskal-Wallis and Kendall’s Tau statistical tests.

Findings are visualized using seaborn and matplolib: a sample visualization is provided below:
<img width="600" alt="image" src="https://github.com/user-attachments/assets/77d7d639-2120-4dde-b03c-8dc694eb417c" />
<img width="600" alt="image" src="https://github.com/user-attachments/assets/96e5d926-131d-4739-ba5c-d286bebd3c4b" />



Analysis of Kruskal-Wallis results found that changes in ionic strength, light strength and the macrocation ratio resulted in statistically different metabolic compound levels.

Compiling and comparing the Kendall’s Tau results for each pre-harvest factor identified the following pre-harvest growth factors are the most impactful (in order of importance): 
1. Ionic Strength (Electrical Conductivity) of nutrient solution as a dominant factor: 51 % of metabolic markers recorded
2. Light Intensity as a dominant factor: 28%
3. Ratio of macrocations (K, Ca, and Mg)as a dominant factor : 21%
