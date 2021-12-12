[Back to Home Page](https://grace-yoon1.github.io/DATA150/)

Grace Yoon

COLL 150 Human Development and Data Science

Professor Brewer

14 December 2021

Word count: 2,131

---

### Final Research Proposal: Combining Satellite Imagery and Machine Learning to Assess and Analyze Poverty in India

---

#### Introduction

Poverty is a significant harm to countries all over the world. It causes millions of humans to face challenges like poor health and untenable living conditions. People are unable to fulfill their basic needs and capabilities to survive due to the lack of resources, goods, and services (Fashridjal). To reduce the amount of poverty in the world, researchers have tried numerous approaches, however, the issue is not knowing exactly where in these countries that individuals suffer from poverty the most. Without knowing these areas of poverty, development in these countries is slowed down, not allowing them to attain the freedoms to allow them to thrive. To find specific areas of poverty, data science methods using geospatial and satellite data can be used to spatially target and estimate poverty in these underdeveloped countries (Bill and Melinda Gates Foundation, World).

Methods to alleviate poverty around the world are described in all of the articles I have researched. From using traditional methods such as data collection from surveys to utilizing technology, such as convolutional neural networks, to explore data, there is one common objective: to eliminate poverty. I have learned that this can be achieved through observing poverty maps from satellite imagery data. Satellite data can be used to obtain information and create spatial datasets for poverty status in developing countries. It is important to use this effective approach frequently to track poverty accurately over time and provide the necessary resources in areas that need it, in order to live a life with basic capabilities, freedoms, and opportunities.

In Amartya Sen’s “Development as Freedom,” Sen discusses how analyzing and assessing poverty can enhance the lives we lead and the freedoms we enjoy (Sen). Gathering data to find areas that are not as developed can allow us to use freedoms to further develop and remove the unfreedom of low income (Bill and Melinda Gates Foundation, World). Sen discusses how development is the process of expanding human freedoms and by obtaining information about these poorer areas, actions and policies can be made to allow these countries to reach this developmental freedom (Sen). 

In investigating if poverty can be mapped and estimated accurately from satellite imagery at a closer neighborhood-level resolution to obtain more refined and precise predictions, it appears that it has been neglected and left unanswered. All of the existing bodies of literature studied zoomed out satellite images of vast areas of land to predict and assess poverty in a country. However, I would like to investigate more on this research gap to see if the same approach could be applied with taking satellite imagery at neighborhood levels to estimate poverty. In this research proposal, I will assess geospatial data science methods utilized to assess poverty, model relationships between variables, and analyze interactions to produce findings in alleviating poverty in a developing country: India. With this investigation, I hope to answer if poverty can be mapped and estimated accurately from satellite imagery at a closer neighborhood-level resolution to obtain more refined and precise predictions.

---

#### Data Science Methods

There are several data science methods that I have found to be significant and interesting in assessing and analyzing poverty in areas like India. I would like to use some of these data science methods in my research plan to grasp a better understanding of where resources are needed the most in India. To predict and understand poverty on a geographic level, neural networks can be used in conjunction with geospatial datasets to produce accurate assessments for even the most rural areas. Identifying these impoverished areas is difficult which causes these populations to lack “money, food, medicine, and access to education” (Kumar). There are many resources being produced for billions of people, yet due to the difficulty of understanding and identifying these countries, many still suffer in poverty. To alleviate poverty, data science strategies like creating computer vision models allow us to provide resources and predict poverty in countries. 

The article, “How to Understand Global Poverty from Outer Space,” discusses five key steps to approaching global poverty (Kumar). The author discusses a method to predict poverty using a convolutional neural network and uses daytime and nighttime satellite images to analyze certain areas in order to improve policy initiatives and alleviate poverty. The first step is to download Demographic and Health Surveys (DHS), nightlight satellite imagery, and daytime satellite imagery. The article discusses downloading data and constructing clusters to gain a better understanding and measurement for “health, population, and nutrition” (Kumar). They used the Google Maps Platform to obtain daytime images that have features of landscape and activity. Then, the next step is to test whether nightlights can predict wealth accurately. From the data collected, the DHS and nightlights data is merged to see if nightlights data can be used for predicting poverty. The author explains how creating this visualization that highlights certain areas of the satellite imagery shows that nightlight luminosity is a strong predictor of wealth. After, extracted features of the daytime imagery are tested to see if they can also predict wealth accurately. Daytime imagery can be a valuable tool as well and when merged with the DHS data, “a model of wealth as a function of these basic daytime features [can be] fitted” (Kumar). Next, a convolutional neural network is constructed to leverage a combined dataset of daytime and nighttime images. A transfer learning approach using a convolutional neural network estimates nightlight intensities, repurposes the model, and obtains final feature vectors. Lastly, maps are constructed to show the predicted distributions of wealth. In conclusion, an approach to predict poverty in areas is to use convolutional neural networks with daytime and nighttime satellite imagery with survey data. Analyzing the data from this is scalable and inexpensive, hence why the author plans to expand this for more countries (Kumar). This article relates to Amartya Sen’s definition of human development the author discusses how using data science can lead a population towards freedom. From using convolutional neural networks and satellite imagery, more information can be obtained to understand those suffering from the unfreedom of poverty. With a greater understanding of these areas from using neighborhood-level satellite images, it becomes far more feasible in my research plan to help these individuals deprived of basic capabilities out of poverty and expand their ability to live freely (Sen).

---

#### Proposal

To advance answering my central research question, I will discuss a research plan that will take place in a 1-3 year time frame. In my approach, I will create a team of researchers to collect and clean data on neighborhood-level daytime and nighttime satellite images. To get a neighborhood-level resolution, the data could be collected from existing or newly constructed satellites. Then, it is necessary to train a convolutional neural network on the data collected, to be able to predict poverty levels. Alongside the satellite data, a team could be sent to obtain survey data, or data from DHS could be used in conjunction with the satellite datasets and convolutional neural networks to produce accurate assessments and understandings. The next step would be to construct maps to show the predicted distributions of wealth in order to grasp a better understanding. Lastly, from the data and analysis done, the right resources could be provided and sent to these neighborhood-targeted areas based on the results to help alleviate the human development issue of poverty.

---

#### Objective

The objective of my research plan is to gain a deeper understanding of poverty in India. I chose India because it is a large country by both population and size, it is made up mostly of rural areas, and it suffers from high levels of poverty. India is the second-most populous country in the world with 21.9% of 1.34 billion people suffering from poverty (Das). In undeveloped countries like India, the people suffer complex challenges such as no access to basic health care, clean living situations, safe drinking water, and adequate food due to “centralized development” and “inequitable distribution of income” (Satapathy). Even though India is the fastest growing economy and its GDP grew from $93.7 billion in 1950 to $2.65 trillion in 2017, it still faces poverty and it has remained an issue throughout the years. A major reason India still faces widespread poverty is due to a discrepancy in the amount of infrastructure that has been developed in different areas of the country (Satapathy). Millions of people in India live on less than $1.90 per day with an unreliable income source, which is not enough to experience human freedoms from development and growth. It is challenging to map poverty in countries with large populations over a large area of land, making India an interesting case study as a country with these attributes. Surveys and other non-data science poverty predicting methods would not be as effective and accurate for large developing countries because of widespread poverty and issues like communication, which is why I chose to explore geospatial data science methods to assess and analyze poverty in India. The use of these methods can help the objective of my inquiry because it is a much faster and accurate approach than traditional methods (Das). 

An obstacle I anticipate in my research could be collecting accurate neighborhood-level survey data to use in conjunction with satellite data. This could be due to factors such as low participation, language barriers, lack of data from rural areas, and time. The difficulty of collecting satellite images or the quantity of satellite images from India, since the land is so large, could be another obstacle faced in the process. From the outcomes of the study, further research could be done with even closer images or more zoomed-out images to learn more about poverty analysis. The results of the study could also be useful to apply to studies in other developing countries. By knowing which areas are poor from the results, we could better allocate resources to those who need them. 

---

#### Funding and Possible Issues

I believe that funders should fund my research plan because my method could potentially be more accurate, which could save money for India’s government and lessen poverty over the years. While there have been attempts to diminish poverty on a global scale, most have been unsuccessful in these underdeveloped areas (Fashridjal). To further grow and sustain the globe, an exact poverty map is needed from effective and reliable data collection from neighborhood-level satellite imagery and convolutional neural networks. My method could be powerful because using the three methods of mapping poverty using high-resolution satellite imagery, convolutional neural networks, and the traditional method of survey data could lead to better understandings from the different perspectives (Das). While my method may be more accurate, there are potentially more costs in creating the model due to the amount of satellite imagery that is needed. 

---

#### Budget

This research plan would have a budget of $100,000 to cover costs associated with paying myself and other researchers involved in the study, data collection from satellites and survey data, travel/accommodations/food while researching in India, etc. Of the $100,000, the majority of the funds, around $60,000, would be devoted to data collection from satellites and surveys and modeling from the data. About $12,000 of the funds could be used to pay for living/food expenses and travel expenses of the researchers in India. Around $25,000 would be spent for hardware support, necessary equipment, and collections of datasets and databases. The rest of the funding would be used for any additional costs of project proceeds.

---

#### Conclusion

Methods to alleviate poverty around the world are described in all of the articles I’ve researched. From using traditional methods such as data collection from surveys to utilizing technology, such as CNNs and satellites, to explore data, there is one common objective: to eliminate poverty. I’ve learned that this can be achieved through observing poverty maps from satellite imagery data. Satellite data can be used to obtain information and create spatial datasets for poverty status in developing countries. It is important to use this effective approach frequently in my research plan to track poverty accurately over time and provide the necessary resources in areas that need it, in order to live a life with basic capabilities, freedoms, and opportunities. 

From the gap in the literature that I explored, all of the articles studied zoomed out satellite images of vast areas of land to predict and assess poverty in a country. From my research plan, I hope to discover if the same approach could be applied with taking satellite imagery at neighborhood levels to estimate poverty. I am interested in exploring more from the analysis and research I’ve done in poverty in developing countries like India, and hope that the findings of my research plan could be further researched for other developing countries in the world. The goal of this research proposal is to answer my central research question: Can poverty be mapped and estimated accurately from satellite imagery at a closer neighborhood-level resolution to obtain more refined and precise predictions?

---

#### Citations

Bill and Melinda Gates Foundation. “High Resolution Poverty Mapping from Cell Phone and Satellite Data.” WorldPop, https://www.worldpop.org/portfolio/project?id=23. Accessed 2 Oct. 2021.

Bill and Melinda Gates Foundation, World Bank, Grameen Foundation. “High Resolution Progress out of Poverty Mapping.” WorldPop, https://www.worldpop.org/portfolio/project?id=22. Accessed 30 Sept. 2021.

Das, Partha Sarathi, et al. “Socio Economic Analysis of India with High Resolution Satellite Imagery to Predict Poverty.” 2020 10th International Conference on Cloud Computing, Data Science & Engineering (Confluence), 9 Apr. 2020, pp. 310–314., https://doi.org/10.1109/Confluence47617.2020.9057972. Accessed 23 Oct. 2021.

Elvidge, C. D., et al. “The Night Light Development Index (NLDI): a Spatially Explicit Measure of Human Development from Satellite Data.” Social Geography, 23 July 2012, Accessed 23 Oct. 2021.

Fashridjal, Freddy. “How Data Science Can Give Further Understanding on Urban Poverty.” Towards Data Science, 13AD, https://towardsdatascience.com/how-data-science-can-give-further-understanding-on-urban-poverty-ab52e448913.

Jean, Neal, et al. “Combining Satellite Imagery and Machine Learning to Predict Poverty.” American Association for the Advancement of Science, vol. 353, no. 6301, Aug. 2016, pp. 790–794., https://doi.org/https://doi.org/10.1126/science.aaf7894. Accessed 23 Oct. 2021.

Kumar, Asmi. “How to Understand Global Poverty from Outer Space.” Towards Data Science, 5 July 2020, https://towardsdatascience.com/how-to-understand-global-poverty-from-outer-space-442e2a5c3666.

Satapathy, Swastik S, and Krishna K Jaiswal. “A Study on Poverty Estimation and Current State of Poverty in India.” International Journal of Advanced Scientific Research and Management, vol. 3, no. 6, June 2018, Accessed 23 Oct. 2021.

Sen, A. K. (2010). Development as freedom. Oxford University Press.
