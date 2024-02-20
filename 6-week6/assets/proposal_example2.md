## Enhancing Road Safety: A Comprehensive Analysis and Prediction of Injury Severity in Traffic Collisions

### Introduction
Our crash reporting dataset provides information for all traffic collisions occurring on county and local roadways within Montgomery County, as collected via the Automated Crash Reporting System (ACRS) of the Maryland State Police, and reported by the Montgomery County Police, Gaithersburg Police, Rockville Police, or the Maryland-National Capital Park Police from 2021-2023. Road safety is a critical concern for communities and governments worldwide. Traffic collisions result in significant loss of life, injuries, and economic costs. To address this issue, an in-depth classification and prediction analysis of this dataset will be conducted, enabling the development of targeted interventions and policies to improve road safety.

The original dataset has 43 categorical and numeric columns and 163,306 observations, but only some of these columns will be selected as features for classification. Features we plan to select are Route Type, Cross-Street Type, Municipality, Collision Type, Weather, Surface Condition,  Light, Traffic Control, Driver Substance Abuse, Non-Motorist Substance Abuse, Driver At Fault, Vehicle Damage Extent, Vehicle Year and Speed Limit. Features will be used to predict Injury Severity which is the target. Further methods such as correlation and domain knowledge analysis might be conducted to determine the final feature selection.  

### Literature Review
Approaches to injury severity prediction in relation to traffic accidents employ a combination of statistical methods and machine learning algorithms, with a notable emphasis on the latter due to their higher predictive accuracy (Zhang et al., 2022). These machine-learning algorithms include support vector machines, decision trees, K-nearest neighbors, and random forests (Zhang et al., 2017). In recent studies, machine learning models such as the Classification and Regression Tree model, rule induction, and Artificial Neural Network-Multilayer Perceptron have been employed to forecast injury severity, indicating location, accident types, collision types, and settlement types to be the most predictive factors (Wahab and Jiang, 2020; Zhang et al., 2017). Lin et al. (2020) used four machine learning classifiers to predict injury severity in juvenile driving incidents, highlighting factors such as speed limits, road class, and the first detrimental occurrence as pivotal determinants.

Nonetheless, limitations persist, including data quality issues and challenges related to generalizing models across diverse traffic scenarios contexts. Ahmadi et al. (2020) recommended improving driver safety education, vehicle design, and roadway infrastructure to mitigate injury severity. While these current practices provide valuable insights, addressing these limitations remains essential in advancing the accuracy of injury severity prediction in traffic accidents.

### Innovation
First, our study utilizes diverse features and can provide a comprehensive explanation for injury severity. The project takes the environment (weather, road conditions, municipality, etc.), driver, and vehicle into consideration. Traffic accidents are a complex issue with many contributing factors. With approximately 14 features in the model, we can better specify the key independent variables that have a significant association with the results.

Second, our study uses panel data covering the period from 2021 to 2023, which can mitigate the influence of extreme events and yield more solid results. Many studies only utilize one year of data, as seen in Megnidio-Tchoukouegno’s work (2023) on predicting traffic accidents in the UK. However, the external environment may vary across different years, particularly during the pandemic. Our three-year dataset can showcase time variation and enhance the robustness of predictions.

Third, we will employ both traditional regression models and computational methods for analysis. Works utilizing machine learning often lack a thorough descriptive analysis and econometric methods. Additionally, studies on road accidents in the social science field rarely leverage computational methods such as machine learning. We will capitalize on the interdisciplinary background of our team members to employ diverse methods and compare results.

### Impacts
Injury severity prediction in traffic accidents is important to a number of stakeholders, and its effective use can have a big impact. 

First of all, government authorities are responsible for public safety, and traffic accidents are a significant public safety concern. They aim to reduce accidents, injuries, and fatalities on the roadways they govern. When injury severity can be accurately predicted, governments may more effectively distribute resources. In order to improve road safety, they may establish targeted road safety rules, send law enforcement and emergency services to accident scenes more effectively, and make data-driven choices. 

Secondly, since accidents may affect corporate reputation and legal liabilities, automakers have a stake in road safety. Based on accident data, they could also wish to enhance the safety elements of the cars. Car manufacturers can lower the risk of serious injuries in accidents by designing and manufacturing vehicles with better safety features with the guidance of accurate injury severity prediction. This can lead to increased consumer trust and potentially better sales. 

Thirdly, drivers are directly affected by road safety. Accurate injury severity predictions can provide valuable information about the potential consequences of accidents. This information can influence their driving behavior and encourage safer driving practices. More over, reliable estimates of injury severity can give the news media vital information they need to notify the public about how bad an accident is. They can use it to report on accident trends and patterns as well. In addition, rapid and more precise analyses of the severity of injuries can help emergency services plan ahead and react to incidents in a proper manner. They may be able to manage resources more wisely with its assistance. 

### Risks
We also face risks associated with inaccurate predictions or misinterpretation of data. These may caused by several reasons. 

Firstly,  Regional bias may occur if the injury severity prediction model is trained exclusively using data from Montgomery County, Maryland. In other areas with distinct traffic patterns, road conditions, and demographics, the model might not generalize as well. When used outside of Montgomery County, this restriction may reduce the precision of forecasts. The dataset might not fully reflect the variety of incidents that occur in the county; for example, it might leave out some accident categories or underrepresent some types of collisions or road conditions. Predictions that are skewed may result from this lack of representativeness. 

Secondly, different car brands and models come equipped with various safety features and technologies. The model might not correctly represent how safety factors affect the severity of injuries if the dataset does not take these variances into account. 

Lastly, age bias is also a worth noting problem. There is a chance of age bias if the dataset has an overrepresentation of incidents involving drivers with a certain number of driving years. The model may perform well for one age group but poorly for others.

### References
A. Mohammed, K. Ambak, A. Mosa, and D. Syamsunur, “A review of the traffic accidents and related practices worldwide. open transport. j.13, 65–83,” 2019.

Zhang, S., Khattak, A., Matara, C. M., Hussain, A., & Farooq, A. Hybrid feature selection-based machine learning Classification system for the prediction of injury severity in single and multiple-vehicle accidents. PLoS one, 2022. 17(2), e0262941.

Zhang J.; Li Z.; Pu Z., and Xu C., Comparing prediction performance for crash injury severity amongvarious machine learning and statistical methods. IEEE Access, 2018. 6: p. 60079–60087.

Fiorentini N. and Losa M., Handling imbalanced data in road crash severity prediction by machine learning algorithms. Infrastructures, 2020. 5(7): p. 61.

Wahab L. and Jiang H., Severity prediction of motorcycle crashes with machine learning methods. International journal of crashworthiness, 2020. 25(5): p. 485–492.

Lin C.; Wu D.; Liu H.; Xia X., and Bhattarai N., Factor identification and prediction for teen driver crash severity using machine learning: a case study. Applied Sciences, 2020. 10(5): p. 1675.

Ahmadi A.; Jahangiri A.; Berardi V., and Machiani S.G., Crash severity analysis of rear-end crashes in California using statistical and machine learning classification methods. Journal of Transportation Safety & Security, 2020. 12(4): p. 522–546. https://doi.org/10.4271/2016-01-1439 PMID: 27648455

Megnidio-Tchoukouegno M, Adedeji JA. Machine learning for road traffic accident improvement and environmental resource management in the transportation sector. Sustainability. 2023;15(3):2014. doi: https://doi.org/10.3390/su15032014.



## Timeline:

By Oct 16: Proposal

By Oct 30: Data Description & Data Analysis

By Nov 13: Classification 

By Nov 22: Result Interpretation

By Dec 4: Report & Slides

By Dec 18: Polish 








