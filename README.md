Official Control of Lead Concentration in Bivalve Mollusks from Portugal
Abstract:
----------------------------------------------------------------------------------------------------------------
This study aims to evaluate the lead concentration on bivalve mollusks from Portugal, understand the main factors that may lead to an increase in lead concentration and a Monte Carlo simulation was conducted for risk assessment of lead through the consumption of Japanese clams. Firstly, the European situation regarding food safety issues associated only with bivalves mollusks was assessed. In this matter  all the RASFF notifications between 2020 and 2023 were analyzed,  allowing us to conclude that biological hazards, like presence of Norovirus and E.coli,  stands out as the main causes of all the food safety recalls analyzed. Analyzing the bivalve mollusks species associated with these food recalls, species like oysters, mussels, and clams were the ones most frequently associated with these notifications. Regarding the decision risk of these notifications, the majority of them with almost 76% of all the RASFF notifications related to mollusks bivalve are considered as serious. This highlights that food safety issues related to bivalve are indeed a concern in Europe. For the purpose of evaluating which factors may lead to an increase in lead concentration, it was calculated the Pearson correlation between the lead, mercury, cadmium concentrations and E.coli content. Then a principal component analysis (PCA) took place, using data from the Portuguese National Monitoring System for Bivalve Mollusks. Results from the Pearson correlation have shown that there is a moderate correlation between mercury and lead concentrations, while cadmium concentration and E.coli content have less influence on lead concentration. PCA results have revealed that the bivalve mollusk species and the production region are crucial factors that may influence the lead concentration. Among all the species, cockles stand out as the species with the highest lead concentration. Regarding the production region, the region of ‘Lisbon and Vale do Tejo’, stand out as the region associated with the highest lead concentration. On the other hand, seasonality does not appear to be a crucial factor, in other words, whether a bivalve mollusk is produced during the ‘Rainy’ season or during the ‘Dry’ season does not seem to influence the lead concentration of bivalve mollusks. Taking into account the Portuguese consumption and the lead concentration in Japanese clams, a Monte Carlo simulation for risk assessment indicated a higher risk of exposure to elevated levels of lead in children and adolescents. However, the probability of exceeding the PTWI (provisional tolerable weekly intake) was low, suggesting that the consumption of Japanese clams does not have a significant risk of high lead exposure to the Portuguese population.
---------------------------------------------------------------------------------------------------------------


Key-Words: Risk Assessment, Bivalve Mollusks, Heavy Metals, Lead, Monte Carlo Simulation




 Introduction

In Portugal the fish and seafood sector plays an important role in the country’s economy and from a social perspective as well [1]. Among all these products the bivalve mollusks stands out as one of the products with the highest consumption [2]. This happens not only for all the health benefits- such as low in calories, high in protein and minerals like iron, calcium and zinc, and low in fat- associated with the consumption of these products but also due to the fact that these products are widely used in a large number of traditional Portuguese dishes, like ‘carne de porco à alentejana’ [3]. Despite all the benefits associated with the consumption of bivalve mollusks, these living beings obtain all their nutrients and oxygen through a water filtration process which can lead to an increase in harmful agents, such as chemical contaminants (mercury, lead and cadmium) or biological agents like bacterias and virus. Consequently, this poses potential health issues for human consumers [4]. Taking into account that the consumption of bivalve mollusks can be one exposure pathway to toxic elements, and considering some historical events in Portugal, these living beings have been of great concern, mostly due to the high concentration  levels of heavy metals found in these bivalves, primarily clams from ‘Estuário do Tejo’. In this context, to ensure consumer safety the motorization, evaluation and risk assessment studies are of extreme importance [5].
That being said, and considering the amount of available data, as well as all the historical events in Portugal, particularly related to high contraction levels of lead in bivalves, this study focuses on studying the main factors which may lead to a high concentration of lead in these organisms. Firstly, with the aim of obtaining an European overview regarding the main safety issues related to bivalves, as well as understand the main causes and which species have the highest number of food recalls in Europe, data from RASFF (Rapid Alert System for Food and Feed), between 2020 and 2023, was analyzed. Subsequently, data from the National Bivalve Mollusks Monitoring System (SNMMB), released by the Portuguese Institute of Sea and Atmosphere (IPMA), was analyzed to evaluate potential associations between concentrations of lead, mercury, cadmium and, E.coli content, where for this purpose the pearson correlation was calculated. Because some studies have indicated that bivalve species, production area, and the season in which the bivalve was harvested can be factors influencing the concentration of heavy metals, these variables will be studied. Among all the studies, one study released in 2017 stands out. This study investigated the accumulation rates of heavy metals in four different bivalve species: oysters, mussels, scallops, and clams collected from various regions worldwide. The results revealed distinct accumulation rates among different bivalve species. Oysters, in particular, exhibited hyperaccumulation of copper and zinc, while scallops were identified as hyperaccumulators of cadmium [6]. Regarding production areas, a study conducted in 2008 focused on heavy metal concentrations in two bivalve species, clams and oysters, across different environments in Morocco. The research recorded varying concentrations of heavy metals based on the geographical origin of the mollusk bivalves, with those from the south exhibiting the highest concentrations [7]. Examining the impact of seasonal variations on heavy metal concentrations in mollusk bivalves, a 2022 study investigated the seasonal tissue concentrations of heavy metals in clams over the course of one year in the north of the Persian Gulf. The study's results indicated a significant increase in the tissue accumulation of heavy metals, including Cd, Pb, and Pb, during late autumn and winter. Consequently, the study concluded that seasonal variations could lead to different accumulation rates of heavy metals in clams [8]. That being said, in this study all the mentioned variables will be studied by a principal component analysis (PCA). Lastly, a Monte Carlo simulation was performed for the risk assessment of lead exposure through the consumption of japanese clams. In this Monte Carlo simulation for risk assessment it was combined the lead concentration in japanese clams with the clam consumption data. The lead concentration data were derived from an exploratory data analysis of the National Sample Collection Plan (PNCA), performed by ASAE (Economic and Food Safety Authority), while the consumption data were calculated using information from the National Dietary and Physical Activity Survey (IANF-AF).
 
Materials and Methods

     2.1. Bivalve Mollusks and European Situation

To assess the European situation concerning food safety issues related to bivalve mollusks, an exploratory data analysis was conducted on the information released through the RASFF platform between 2020 and 2023. The Rapid Alert System for Food and Feed or mostly known as RASFF is a consumer-friendly internet tool, created in 1979, which provides latest information on food recall notices enabling information to be shared efficiently between its members [9]. In the RASFF competent authorities in each Member State can submit notifications on the withdrawal or illegal products from the market, this makes a significant contribution to food safety control in the European Union [10]. Therefore this tool allows to prevent future issues related to food safety, ensuring consumers the security of traceability and provides them information about most frequent risks and also allows the importers to take advantage of the information about global imports/exports and thus prevent future detentions [11]. After the data collection of all the RASFF notifications related to mollusks bivalve an exploratory data analysis was conducted using the programming language Python. In this exploratory data analysis the aim was to identify the species with the highest number of notifications as well as the main causes of these notifications. 

     2.2. Multivariate analysis in Bivalve Mollusks

Aiming to analyze correlations between concentrations of lead, mercury, cadmium and E.coli content  which is an indicator of fecal contamination allowing to assess the water quality in which the bivalves were produced. Other factors such as species, region in which the bivalve was produced and the season of the year in which the bivalve was harvested, the pearson correlation, between concentrations of lead, mercury, cadmium concentration and E.coli content was calculated. Subsequently, all the mentioned variables were used to perform a principal component analysis (PCA) allowing us to understand if the species, production region and season in which the bivalve was harvested have some influence on the lead concentration. In this context, data from the National Bivalve Mollusks Monitoring System (SNMMB), released by the Portuguese Institute of Sea and Atmosphere (IPMA), were employed to conduct all the mentioned analyses. The SNMMB, developed by IPMA, is the Portuguese national system for monitoring the quality of bivalve mollusks produced across various regions of Portugal. In this system, IPMA is the responsible institution for assessing a wide range of quality parameters related to the quality of bivalve mollusks, ensuring in this way the public health [12]. Microbiological parameters, such as E.coli count is one of the analyses performed by IPMA and allows access to fecal contamination as E.coli is a great indicator of fecal contamination among the commonly used fecal-indicator organisms [13,14]. In terms of chemical parameters, the monitoring of lead, cadmium and mercury stands out as the heavy metals for which IPMA conducts analyses within the SNMMB [15]. Biotoxinas motorization is another domain for which IPMA is responsible for, within the SNMMB. In this matter it is assessed the levels of lipophilic biotoxins, amnesic biotoxins and paralyzing biotoxins as well [16]. 
As in the previous topic, following the data collection, all this information was treated in Python, where the mentioned PCA analysis was conducted. For this PCA analysis it was taking into account the lead concentration by species, by production region and by season. Regarding the species it was analyzed the specie of cockle (Scrobicularia plana), mussel (Mytilus edulis), japanese clam (Ruditapes philippinarum), good clam (Ruditapes decussatus),  japanese oyster (Crassostrea gigas) and portuguese oyster (Crassostrea angulata). Concerning the study of lead concentration by production region all the production areas from Portugal were grouped by 5 different regions (Alentejo, Lisbon and Vale do Tejo, Algarve, Centro e Norte) allowing an easier interpretation of the results. Finally, for the study of the lead concentration by season the data was grouped by two different seasons, “Dry” and “Rainy”. Taking into account variations in precipitation, humidity levels, and temperature, the months between September and May belong to the “Dry” season, on the other hand the months between May and September belong to the “Rainy” season. Numerical variables such as the concentration of lead, mercury, cadmium and E.coli content were standardized through standardization (z-score normalization). This step ensures that all the data has the same scale. This is an important step because PCA will give more importance to features with larger variances[17]. After the standardization,  PCA was applied to reduce the dimensionality of variables. Then, both PCA variables were plotted by species, production region and season.

                2.3. Risk Assessment 
	
	The lead risk to the portuguese population through the consumption of japanese clams was assessed by comparing the weekly intake level, the provisional tolerable weekly intake (PTWI) value established by an EFSA panel on contaminants in the food chain, which was determined to be 25 μg/kg b.w [18]. A Monte Carlo simulation was carried out to estimate the Portuguese lead intake by each age group through the consumption of Japanese clams. For this purpose, data about the weekly consumption of clams and data on the lead concentration on japanese clams were combined. Then, the probability of exceeding the PTWI was calculated and compared to the results of the Monte Carlo simulation. Once again, for the Monte Carlo simulation,  both consumption data and lead concentration data were processed using Python programming language, where it was taken into account the consumption of clams by each age group, children (< 10 years old), teensagers (10 ≤ x ≤ 18 years old ), adults (18 ≤ x ≤ 84 years old) and elderlies (> 84 years old). Additionally, the number of samples for the simulation was determined based on  an approximation of the Portuguese population within  each age group, according to data released by PORDATA in 2023. This approach ensures a  sample size that is representative of the actual Portuguese population. Considering the data provided by PORDATA in 2023 there are 867032 children (< 10 years old), 1029582 teenagers (10-17 years old), 8153571 adults (18-84 years old) e 257527 elderlies (> 84 years old) individuals in Portugal [19]. With that being said the sample size, for each age group corresponds to the Portuguese population mentioned previously.
The consumption of bivalve mollusks was obtained through a descriptive analysis of data provided by the National Dietary and Physical Activity Survey (IANF-AF). Carried out by the Medical University of Porto between 2014 and 2016, this survey aimed to gather information about Portuguese  food consumption and physical activity. Moreover, it allowed the acquisition of further information about the food consumption and physical activity across various Portuguese regions, socioeconomic conditions, and in accordance with other health determinants. The survey sample, consisting of 6553 Portuguese citizens, was randomly selected and it included individuals aged between 3 months and 84 years old [20]. 
Regarding the Japanese clam lead concentration needed to perform the Monte Carlo simulation, this information was acquired through an exploratory data analysis of the data from the PNCA between 2013 and 2022, carried out by the Risk Assessment Department form ASAE. The National Sample Collection Plan, or PNCA for short, is an official control plan for sampling, with the aim of verifying that all the food products placed on the market pose a risk to human safety and health, and also to ensure all correct and appropriate labeling information to prevent consumer misguidance [21] .
After calculating the weekly consumption of  clams for each age group and, subsequently the collection of all the lead concentration data in japanese clams, considering a metric called mean squared error, which is a metric to measure the difference between observed values and the predicted values [22], a distribution was fitted to both data sets. Then, the weekly intake exposure of lead through the consumption of japanese clams for each age group was calculated by the following formula: 

               Intake Exposure (µg/kg bw /week) =[PB] (µg/g)  Weekly Consumption(g)Body Weight (kg)

	Lastly, the probability of exceeding the respective PTWI for each age group was determined by the following formula: 

	                                         P (Xi > PTWI) =(Xi > PTWI)n,
				where,
				P (Xi > PTWI) : probability of exceeding PTWI;
				(Xi > PTWI): number of weekly intake values exceeding PTWI;
				n: sample size;
				Xi: lead intake value

Results

3.1. Bivalve Mollusks and European Situation

	By a descriptive data analysis of all the RASFF notifications between 2020 and 2023 it was possible to get an overview on which are the main reasons and which are the species with the highest number of food recalls within the bivalve mollusks domain Through this it was identified 301 notifications related to bivalve mollusks. 
A look at the reasons for these notifications have shown that the main cause was mostly due to microbiological hazards, where the presence of Norovirus stands out with 128 (43%) notifications followed by presence of E.coli with 66 (22%) notifications (Fig.1.). Concerning only chemical hazards, the presence of high concentrations of cadmium was the only recall related to this domain. Despite all the historical issues in Portugal caused by high concentrations of lead found in bivalve mollusks, in a European point of view this has not been a reason for food recalls.


Figure 1  - Bivalve Mollusks and RASFF Notifications Reasons

An examination of the figure 2 reveals that oysters are the  bivalve species with the highest number of RASFF notifications, totaling 111 (37%) notifications. Then, mussels and clams stand out with 80 (27%)and 73 (24%) notifications respectively. As we can see the RASFF notifications related to clams represents almost 24% of the total number of RASFF notifications within the mollusks bivalve domain, which can be seen as a noteworthy presence or prevalence in the context of these notifications.


Figure 2- Number of RASFF Notifications by Bivalve Mollusks Species 
In the figure 3, the results of the decision risk are displayed, and by analyzing them allows us to assess whether the RASFF notifications related to mollusks were indeed a concern in Europe. By the examination of the mentioned figure, out of the 301 RASFF notifications related to mollusks bivalve, 229 were considered serious. This represents practically 76% of all mollusks bivalve RASFF notifications. This high number of notifications considered as serious highlights that, in Europe, food safety issues related to mollusks bivalve are indeed a concern,

Figure 3- Number of RASFF Notifications by Risk Decision 	

3.2. Lead Concentration Factors in Bivalve Mollusks

	Figure 4 presents Pearson correlation results for the heavy metal concentrations and also for the E.coli content. Moderate positive correlation (r = 0.62) was found between Pb and Hg, while weak negative correlations were found between E.coli content, Cd concentration and Pb concentration with values of r = 0.12 and r = -0.24, respectively. These results have shown that Cd and E.coli content does not appear to have a significant influence in Pb concentration. However, despite the highest pearson correlation having been detected between Pb and Hg, this is still a low value to consider that Hg can lead to an increase in Pb.


Figure 4- Pearson Correlation Results

	In this study, PCA was performed based on concentrations of heavy metals and E.coli content to reduce the dimensionality of variables and in this way analyze these variables by mollusk bivalve species, production area and also by season . By the PCA, two principal components were obtained, which are PC1 and PC2. According to the pearson correlation performed between the original variables and the two principal components, PC1 has a high positive correlation with [Pb] and [Hg], showing a value of r = 0.81 and r = 0.85, respectively, while PC2 has a moderate positive correlation with E.coli content, showing a value of r = 0.62. In this way PC1 can be considered as representative of [Pb] and [Hg] and PC2 slightly representative of E.coli content. In the PCA results (Fig.5.), mollusks bivalve species appear to be a factor which may influence the lead concentration. By the analysis of the top left chart, cockle seems to be the specie most associated with highest values of PC1, in this way it can be said the cockle is the species with the highest values of [Pb]. Analyzing the PCA results by production area, top right chart, the ‘Lisbon and Vale do Tejo’ looks the production area more correlated with PC1. That being said, among all the production areas analyzed, ‘Lisbon and Vale do Tejo’ is the production area with highest values of [Pb]. On the other hand, if we analyze the PCA results by season, the last chart, the season during which the mollusk bivalve was harvested, seems to not be a factor which may influence the [Pb]. 


Figure 5 - PCA Results

3.3. Risk Assessment 
	In order to perform a Monte Carlo simulation for risk assessment of lead intake through the consumption of Japanese clam, the first step involved calculating the consumption of Japanese clams. For this purpose data from the IANF-AF survey was analyzed, revealing that clam is the bivalve species with the highest weekly consumption in Portugal, followed by mussel and cockles (table 1).

Table 1 - Bivalves weekly consumption in Portugal by specie
Specie
Weekly Consumption (g/week)
Clams
93
Mussles
20
Cockles
13
Scallops
1,4
Oysters
0,2


As clams have the highest consumption among all the species, a deep analysis was conducted to determine the weekly consumption by age group. Through this analysis adults were revealed to be the age group with the highest consumption with a weekly consumption of 102 g/week. On the other hand, children are the age group with the lowest consumption with a consumption of 58 g/week (table 2).
Table 2 -  Clams weekly consumption in Portugal
Age Group
Weekly Consumption (g/week)
Adults 
(18-84 years old)
102
Teenagers 
(10–17 years old)
94
Elderlies 
(>84 anos)
79
Children 
(<10 anos)
58


	Before conducting the Monte Carlo simulation, an exploratory data analysis was performed on the PNCA data. The aim was to assess the lead concentration in Japanese clams samples collected between 2013 and 2022. Taking into account that, according to the Regulation (EU) 2023/915 of the Commission of April 25, 2023, which establishes the maximum levels of certain contaminants in food [23],  the maximum level for lead in bivalves is 1.5 mg/kg. No non-compliance was detected  between 2013 and 2022, with the maximum value being recorded at 1.2 mg/kg (figure 6).

Figure 6 - Lead concentration from PNCA Japanese clams samples 
	As mentioned on the 2.3. topic, after calculating the consumption of clams and the lead concentration in japanese clams, the best distribution was fitted for each datasets. For this purpose it was calculated the metric mean squared error to access which is the best distribution for both cases. Based on the mentioned metric the best distribution for the consumption datasets was found to be the “gamma” distribution whereas for the lead concentration dataset was the “extreme-value” distribution (Fig. 6).



Figure 6 - Clam Consumption and Lead Concentration in Japanese Clams Distributions

	After both distributions were fitted and considering the bodyweight and the number of simulations for each age group it was combined both distributions. In the table 2 it’s possible to observe the body weight considered, the sample size and the respective PTWI value for each age group.

Table 1 - Assumptions, Sample Size and  PTWI for each Age Group
Age Group
Assumptions
Sample Size
PTWI                                            (µg/ week)
Body Weight (kg)
          Children
 (<10 years old)
15,00
867032,00
375,00
Teenagers
 (10–17 years old)
45,00
1029582,00
1125,00
Adults
(18-84 years old)
65,00
8153571,00
1625,00
Elderlies
(>84 years old)
65,00
257527,00
1625,00












	Subsequently, the probability of exceeding the respective PTWI and some descriptive metrics were determined for each age group. The results are presented in table 2 . 
Table 2 - Ingestão de Chumbo e Probabilidade de Exceder o PTWI por Grupo Etário
Age Group
Lead Intake (µg/kg. bw/ week)
Probability of exceeding PTWI (%)
25th Percentile
Average ±
Standard Deviation 
Median
75th Percentile
90th Percentile
Maximum
Children
0,25
1,20
±
1,62
0,63
1,49
2,93
70,16
0,0048
Teenagers
0,12
0,70
±
1,02
0,33
0,85
1,76
25,80
 9,73e-05
Adults
0,21
0,63
±     
0,65
0,42
0,81
1,38
14,78
0
Elderlies
0,08
0,30
±
0,50
0,15
0,28
0,68
17,27
0


A detailed examination of this table allows us to conclude that there were some cases in the age groups of children and teenagers, where the intake level exceeded the respective PTWI value. Additionally, it is evident that the average lead intake through the consumption of Japanese clam is higher in the children's age group Analyzing the probability of exceeding the respective PTWI,children have the highest probability with a value of 0,0048%, followed by the teenagers’ group with 9.73e-05% and lastly, the adults and the elderly groups with 0%.  Despite the highest probability of exceeding the PTWI being observed in the group of children and teenagers, this is still a low value. This allows us to conclude that the consumption of japanese clam does not appear to be a crucial factor for high lead exposure.

Discussion

	Taking into account the RASFF notifications related to mollusks bivalve, food safety issues can be considered as a concern in Europe, particularly concerning microbiological hazards, especially the presence of Norovirus and E.coli, and oysters as the main species with the highest number of issues. The fact that the majority of all of these notifications were considered as having a risk decision as serious shows that indeed this is a real problem in Europe. Several studies have been showing the same results and among all the studies one conducted in 2018 stands out. This study aimed to highlight the most relevant noncompliance affecting seafood and explore their possible relationships between variables characterizing notified products through the analysis of the RASFF notifications between 2011 and 2015. In this study it was identified a total of 16304 notifications related to seafood, where the majority of them were caused by non-compliant content of heavy metals and pathogenic microorganisms in mollusks bivalve. Also, in this study the RASFF notifications at border-level, and the results have shown that seafood was rejected in 37% of cases, especially (41.1%) because of poor temperature control, unsuitable transport conditions or fraudulent/absence of health certificate [24]. As this study analyzed data between 2011 and 2015, this supports the finding that food safety issues related to mollusks bivalve it's not an issue which came from the last years but at least since 2011 issues related to heavy metals and microbiological hazards in bivalves are  an issue in Europe. That being said, in order to reduce the number of occurrences and guarantee the health safety of consumers, it is essential to continue monitoring heavy metals and pathogenic microorganisms in bivalves. If possible, consider expanding this monitoring effort.
	Multivariate analysis has shown, through pearson correlation, that there is no significant correlation between the heavy metals analyzed and E.coli content, In this way, the [Hg], [Cd] and E.coli content does not seem to be factors which may lead to an increase on [Pb]. However, by the PCA analysis, it was possible to see that factors such as species and production area are important factors which may influence [Pb]. On the other hand the seasonality does not seem to be a crucial factor for [Pb]. Among all the species, the cockle stands out as the one with the highest lead concentration. This can be mainly attributed to the fact that, like other bivalve species, it feeds through a filtration process. However, this particular species has a unique characteristic, which is the fact that it is typically found buried in sediments [25]. This can lead to a higher accumulation of lead, as contamination of heavy metals in soil is a common problem. This contamination occurs mainly because sediments can act as a sink for heavy metals [26]. Several studies on this domain have concluded that [Pb] can vary according to the mollusk bivalve species. One study conducted in August 2023 aimed to determine the contamination of Pb in clams, mussels and cockles. The samples from this study came from five wholesale seafood markets located on the upper Gulf of Thailand during the period 2017-2019. Determinations on Pb content in the bivalves  revealed that the highest [Pb] were found in cockles > mussels > clams with 151, 64 and 112  µg/kg wet wt [27]. These findings have demonstrated that the cockle species is indeed the mollusk bivalve species which is highest correlated to highest values of [Pb]. As mentioned before the production area in which the mollusk bivalve was produced is a crucial factor as well. One of the main production zones from ‘Lisbon and Vale do Tejo’ is the zone Tagus estuary, which among all the production zones, is the one which has been demonstrated to be most related with highest heavy metals concentrations along the previous years. Due to the history of this zone many illegally harvested cockles are involved in collection and commerce, these results were in some way expected [28].
In this domain a study, from 2018, where it was evaluated the heavy metals content in the sediments of the Tagus estuary revealed the sediments from this zone have a high level of heavy metals contamination, especially those nearby industrial areas, emphasizing the need for the development of a management plan for the species exploitation in the Tagus estuary [29].
	According to these results, it is recommended to take a special attention to [Pb] in cockles and also from the mollusks bivalve which came from the ‘Lisbon and Vale do Tejo’ zone, especially the Tagus estuary area. Reduction of contamination sources and adaptation of the production conditions is also recommended. Regarding production conditions its highly recommended to adapt the depuration, which has been a mandatory process to eliminate microorganisms in bivalve mollusks, where bivalves are maintaining for a period up to 48 h in sterile seawater (through ozone, UV-light, chlorination or iodophors) with sufficient oxygen and without any feed [30]. Despite the importance of the depuration to reduce the microorganism content in bivalves, his efficiency on eliminating toxic chemicals are still being evaluated through several studies. The results from this studies have been highlighting a positive potential for the reduction of heavy metals content by applying a depuration process. In 2015, a research aimed to assess the effects of depuration on the levels of heavy metals in three bivalve species, Japanese clam, mussel, and cockle. Results from this study indicate that depuration has a significant effect on the reduction of heavy metal content. However, a prolonged depuration process has been shown to increase the mortality rate in cockles [31]. That being said, it is important to apply depuration, while adapting the process conditions to each bivalve species.
	For the purpose of risk assessment, the consumption and lead concentration were the two main factors determining the probabilities of exceeding the Pb PTWI. In Portugal, clams are the species with the highest consumption, with adults standing out as the highest consumers. In order to explain this findings data from the IANF-AF survey was analyzed in more detail. In this analysis the goal was to understand how clams were consumed in Portugal.  Results have shown that bivalves are mostly consumed as ingredients incorporated in dishes, where among all the dishes ‘Carnde de Porco a Alentejana’ is the dish with the highest consumption. This dish is well-known in Portugal and as its primary ingredient is clams. In this way it’s possible to conclude that the main reason for this high consumption of clams is mainly due to the high consumption of this dish which has clams as one of the main ingredients.
	Despite the relatively high consumption of clams in Portugal, the results of the risk assessment indicate a low probability of exceeding the respective PTWI among all age groups. One contributing factor to this outcome is the fact that the lead concentration ([Pb]) in Japanese clams remains below the established maximum level of 1.5 mg/kg. The findings from this study affirm the robustness of this maximum level. However, it is essential to conduct additional studies and generate more accurate data to deepen our understanding and ensure more reliable results.











































References

Murthy, A., Galli, A., Madeira, C., Pires, A. (2023). Consumer Attitudes towards Fish and Seafood in Portugal: Opportunities for Footprint Reduction. Special Issue The Environmental Footprint Family: Methodological Advancements, Synergies, and Case Studies. 
Anacleto, P., Barrento, S., Nunes, M., Rosa, R. (2014). Portuguese consumer’s attitudes and perceptions of bivalve molluscs. Food Control pg. 168 - 177.
Pereira, L., Teixeira, B., & Oliveira, M. B. (2021). Avaliação da Segurança Alimentar e Nutricional de Moluscos Bivalves Consumidos em Portugal. Revista de Saúde Pública, pg. 55- 75.
Anacleto, P., Barrento, S., Nunes, M., Rosa, R. (2014). Portuguese consumer’s attitudes and perceptions of bivalve molluscs. Food Control pg. 168 - 177.
Mendonça, C (2016). Apanha Ilegal de Toneladas de Amêijoa no Tejo Ameaça Saúde Pública. Obtido a 17 de outubro de 2023, em: https://www.publico.pt/2016/05/15/sociedade/noticia/apanha-ilegal-de-toneladas-de-ameijoa-no-tejo-ameaca-saude-publica-1731779
Wang, W., Lu., G (2017). Chapter 21 - Heavy Metals in Bivalve Mollusks. Chemical Contaminants and Residues in Food (Second Edition). Woodhead Publishing Series in Food Science, Technology and Nutrition. pg. 553-594
Maanan, M. (2008). Heavy metal concentrations in marine molluscs from the Moroccan coastal region. Environmental Pollution. ppg. 176-783
Khoei, Arash. (2021). Seasonal heavy metals accumulations in the bivalve Barbatia decussate and their relationships with water quality and the metal-induced biochemical biomarkers. Environ Sci Pollut Res Int.ppd.16103-16112.
European Commission (2019). Protecting EU consumers from unsafe food: EU’s Rapid Alert System for Food and Feed. European Commission -Questions and answers.
Kowalska, A., Manning, L. (2020). Using the rapid alert system for food and feed: potential benefits and problems on data interpretation. Crit Rev Food Sci Nutr, pg. 906-919.
Food and Agriculture Organization of the United Nations (2021). Food Control -Border Alerts & Rejections: European Union. accessed  23 December 2023, <https://www.fao.org/in-action/globefish/import-notifications/import-notifications-eu/rasff/en/>
MAR 2020 (2021). Sistema Nacional de Monitorização de Moluscos Bivalves. accessed 23 December 2023, <https://www.mar2020.pt/noticias/sistema-nacional-de-monitorizacao-de-moluscos-bivalves/>
IPMA (2023). Análises de Microbiologia. accessed 23 December 2023. <https://www.ipma.pt/pt/bivalves/micro/>
 Gupta, R., Khan, F (2020). Escherichia coli (E. coli) as an Indicator of Fecal Contamination in Groundwater: A Review. Environmental Science and Engineering. 
IPMA (2023). Análises de Metais Contaminantes. accessed 23 December 2023. <https://www.ipma.pt/pt/bivalves/metais/>
 Safjan, K. (2023). Checks and Data Preprocessing Steps Before Applying PCA. accessed 26 December 2023. <https://safjan.com/before-pca/#preparations-to-pca>
IPMA (2023). Análises de Metais Contaminantes. accessed 23 December 2023. <https://www.ipma.pt/pt/bivalves/biotox/>
 Bendord, D. (2010). The EFSA scientific opinion on lead in food. accessed 23  December 2023  <https://www.leadammunitiongroup.org.uk/wp-content/uploads/2015/07/The_EFSA_scientific_opinion_on_lead_in_food.pdf>
 PORDATA (2023). População residente: total e grupo etário. accesed 26 December 2023, <https://www.pordata.pt/portugal/populacao+residente+total+e+por+grupo+etario-10>
Lopes, C., Torres, D., Oliveira, A., Severo, M., Alarcão, V., Guiomar, S., Mota, J., Teixeira, P., Rodrigues, S., Lobato, L., Magalhâes, V., Correia, D., Carvalho, C., Pizarro, A., Marques, A., Vilela, S., Oliveira, L., Nicola, P., Soares., S., Ramos, R. (2017). Inquérito Alimentar Nacional e de Atividade Física, IANF-AF 2015-2016: Relatório de resultados 2017. Universidade do Porto.
 ASAE (2018). Plano Nacional de Colheita de Amostras. accessed 23 December, <https://www.asae.gov.pt/cientifico-laboratorial/area-tecnico-cientifica/pnca-plano-nacional-de-colheita-de-amostras.aspx>
 Cadima, J. (2020). Estatística e Delineamento: O Modelo Linear. Instituto Superior de Agronomia: Universidade de Lisboa
Commission Regulation (EU) 2023/915  of 25 April 2023 on maximum levels for certain contaminants in food and repealing Regulation (EC) No 1881/2006  
D’Amico, P., Nucera, D., Guardone, L., Mariotti, M., Nuvoloni, R., Armani, A. (2018). Seafood products notifications in the EU Rapid Alert System for Food and Feed (RASFF) database: Data analysis during the period 2011-2015. Food Control. ppg. 241-250.
Cunha, V. (2012). Redução do Teor de Contaminantes Químicos em Bivalves Provenientes do Estuário do Tejo. Tese de Mestrado, Instituto Superior de Agronomia. Lisboa.
 Chiesa, S., Chainho, P., Almeida,  .,Figueira, E., Soares, Amadeu., Freitas, R., (2018). Metals and As content in sediments and Manila clam Ruditapes philippinarum in the Tagus estuary (Portugal): Impacts and risk for human consumption. Marine Pollution Bulletin. ppg 281-292 —----------------- Find another reference to replace this one!!!!!!!!!!!!!!
 Tanaviyutpakdee, P, Karnpanit, W. (2023). Exposure Assessment of Heavy Metals and Micro-plastic-like Particles from Consumption of Bivalves. Foods. ppg 12 -16
Coelho, P., Carvalho, F., Goulding, T., Chainho, P., Guerreiro, J., (2021). Management Models of the Manila Clam (Ruditapes philippinarum) Fisheries in Invaded European Coastal Systems. frontiers in Marine Science. 
Chiesa, S., Chainho, P., Almeida,  .,Figueira, E., Soares, Amadeu., Freitas, R., (2018). Metals and As content in sediments and Manila clam Ruditapes philippinarum in the Tagus estuary (Portugal): Impacts and risk for human consumption. Marine Pollution Bulletin. ppg 281-292
 Lee,R., Lovatelli,A., Ababouch, L. (2008). Bivalve depuration: fundamental and practical aspects. FAO FISHERIES TECHNICAL PAPER. FAO.
Ancleto, P., Maulvault, A., Nunes, M., Carvalho, M., Rosa, R., Marques, A. (2015). Effects of depuration on metal levels and health status of bivalve molluscs. Food Control. ppg. 493 - 501
