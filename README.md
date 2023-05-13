# Groundwater_quality Regression

Examining the relationship between economic growth, income inequality, with environmental quality in India and exploring the Environmental Kuznets Curve hypothesis, which suggests that as per capita income increases, environmental quality first deteriorates and then improves. A district-level data on environmental quality, economic output, and income inequality to estimate regression models and analyze the relationship between these variables has been used.

AIM
In this project, we are trying to test the Environmental Kuznets Curve (EKC) Hypothesis for Ground Water Quality in India
The Environmental Kuznets Curve (EKC) is an economic theory that suggests that as a country's income increases, its environmental impact will initially increase, but then eventually decrease
DATASET, POWER INEQUALITY & CONTROL VARIABLES
The chosen dataset has been taken from a span of 18 consecutive years i.e. 2000 to 2018
Power variables are used to analyze and measure the distribution of power in a society and can affect EKC in many ways
In the context of EKC, control variables are used to account for the effects of other factors that may affect the relationship between income and environmental quality

We have also used several Tests and Estimations like Chow test,T test,P value test,Monte Carlo estimations,Levene Test etc.

CONCLUSION

After reaching a certain threshold, the impact of SDP and EQI becomes non-linear, and a positive correlation is observed between them. The relationship between the two is not only linear but also follows a complex U- shaped pattern, as indicated by the positive value of SDP2.
To eliminate the bias in the data, we introduced some control variables such as the use of fertilizers and annual rainfall, and analyzed the impact of various power inequality variables on the chosen Environmental Quality Indicator. By conducting hypothesis testing, we found that some of these variables significantly affect EQI.
The inclusion of control variables allowed us to obtain a more accurate estimate of the effect of SDP on EQI, indicating that the control variables help remove bias from the data.
Our analysis showed that SDP has a negative impact on EQI, specifically on the amount of electric conductivity. This means that as income increases, electric conductivity decreases, leading to improved groundwater quality.
In our enhanced model, we included the state-wise Gini index, which was found to have a higher positive correlation value (4183) than the district-wise Gini index, which had a negative correlation with EQI when other variables were held constant. This difference may be attributed to lower granularity in state-wise data, which leads to such variations.
The standard errors for all the variables were very small, indicating that the coefficient estimates are more precise and reliable.
Based on observations, it can be concluded that there is a significant relationship between TeleDensity and Electric Conductivity. An increase in TeleDensity leads to improved communication and connectivity, which can have a positive impact on the future Environmental Quality. On the other hand, a negative relationship was found between Voter Turnout Average and Electric Conductivity. This may be due to the fact that people are currently more concerned about demanding better infrastructure and education from the government, and may not be giving as much attention to improving the Environmental conditions.
We performed Bartlett test for four state groups- south, east, west north to test the equality of variances of the variable amount of electrical conductivity of the four state groups. The p-value associated with the test was extremely small (e-16) indicating the small evidence to suggest the variance of amount of electrical conductivity differ across the state groups
