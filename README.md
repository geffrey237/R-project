# R-project (CASE STUDY OF US GUNS MURDERS)
Imagine you live in Europe and are offered a job in a US company with many locations across all states. It is a great job, but news with headlines such as US Gun Homicide Rate Higher Than Other Developed Countries10 have you worried. Charts like this may concern you even more:
![image](https://github.com/user-attachments/assets/5031ece9-1729-4dce-b2b4-b575591e8f35)
Or even worse, this version from everytown.org:
![image](https://github.com/user-attachments/assets/5e4155fe-caef-4a7a-b00a-d5b70190dbf7)
But then you remember that the US is a large and diverse country with 50 very different states as well as the District of Columbia (DC).
![image](https://github.com/user-attachments/assets/ac4c28de-e707-45b9-a8af-6b8cde1a82be)
California, for example, has a larger population than Canada, and 20 US states have populations larger than that of Norway. In some respects, the variability across states in the US is akin to the variability across countries in Europe. Furthermore, although not included in the charts above, the murder rates in Lithuania, Ukraine, and Russia are higher than 4 per 100,000. So perhaps the news reports that worried you are too superficial. You have options of where to live and want to determine the safety of each particular state. We will gain some insights by examining data related to gun homicides in the US during 2010 using R.

Before we get started with our example, we need to cover logistics as well as some of the very basic building blocks that are required to gain more advanced R skills. Be aware that the usefulness of some of these building blocks may not be immediately obvious, but later in the book you will appreciate having mastered these skills.

# Analysis Goals :
1. We made a plot of total murders versus population and noted a strong relationship. Not surprisingly, states with larger populations had more murders.

## Keep in mind that many states have populations below 5 million and are bunched up. We may gain further insights from making this plot in the log scale. Transform the variables using the log10 transformation and then plot them.
2. Create a histogram of the state populations.
  note : We can see that there is a wide range of values with most of them between 2 and 3 and one very extreme case with a murder rate of more than 15

4. Generate boxplots of the state populations by region.
