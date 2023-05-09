
# Professional Research and Publications ## 

* ML in Production: Monitoring Security ML Models in Production. [Blog version of the paper](https://ai.sophos.com/2021/10/15/analyzing-security-ml-models-with-imperfect-data-in-production/)
* Improving Analyst Workflow using Event Clustering: [CAMLIS 2021](https://www.camlis.org/2021-sopan)
* Webinar on AI for Cyber: [Webinar](https://www2.fireeye.com/WBNR-Artificial-Intelligence-Machine-learning-webinar-Part-II.html)
* Interpretation of Threat Prediction Model for SOC Analysts, [CAMLIS 2018](https://www.camlis.org/awalin-nabila-sopan)
* Human in the Loop for Security ML Model. [Blog version of the paper](https://www.mandiant.com/resources/build-machine-learning-models-for-the-soc)
* Panel on Threat Landscape in the Post-pandemic World at WiCyS.

# Featured Works:

## AI Total: Analyzing Security ML Models with Imperfect Data in Production

Once a machine learning model gets deployed into production, we need to move away from static dataset evaluation to automatically evaluating performance on new incoming data. This sounds simpler than it is practice, mainly because in a fully automatic pipeline it is difficult to understand if any observed performance issues are due to model performance, pipeline issues, emerging data distribution biases, or some combination of the above. We need a shared source of truth where all the teams can have a common situational awareness of what is going on with our models. Considering all these use-cases, we built a real-time visualization dashboard that helps our team to fulfill these goals: 

* Monitor the deployed models’ regular performance, observe time trends, and detect anomalies 
* Detect issue with the evaluation data, models, or labeling 
* Investigate the reasons behind the issues 
This web-based visualization system allows the users to quickly gather headline performance numbers while maintaining confidence that the underlying data pipeline is functioning properly. It also enables us to immediately observe the root cause of an issue when something goes wrong. 

![AI Total](/model_metric.webp)


## Reverse Engineering the Analyst: Building Machine Learning Models for the SOC

https://www.mandiant.com/resources/blog/build-machine-learning-models-for-the-soc

Many cyber incidents can be traced back to an original alert that was either missed or ignored by the Security Operations Center (SOC) or Incident Response (IR) team. While most analysts and SOCs are vigilant and responsive, the fact is they are often overwhelmed with alerts. If a SOC is unable to review all the alerts it generates, then sooner or later, something important will slip through the cracks. Think of a SOC as a self-contained machine that inputs unlabeled alerts and outputs the alerts labeled as “malicious” or “benign”. How can we capture the analysis and determine that something is indeed malicious, and then recreate that analysis at scale? In other words, what if we could train a machine to make the same analytical decisions as an analyst, within an acceptable level of confidence? I developed an ML system that classifies cyber events based on SOC analyts' approach of clasiifying them and published a paper and patent based on the analysis of the model's efficacy.

![SOC ML Model](/MLSOC.png) 

![SOC ML Model](/ml-models-soc4.png) 


# Other Projects and Publications #

## Conference Monitor ##
I developed real-time webapp to monitor the backchannel conversation (in Twitter) during academic conferences or any live event.[Paper: SocInfo'12]

<img align="center" src="https://awalin.github.io/Awalin-Sopan/cm.png" alt="conf monitor" width="200">

## Distribution Column Overview ## 
I developed a novel way of exploring distribution data that provides an overview of distribution data, and facilitates the discovery of interesting clusters, patterns, outliers and relationships between distribution-columns. [Paper: Int'l Journal of HCI]

<img align="center" src="https://awalin.github.io/Awalin-Sopan/dc.png" alt="Dist Overview" width="200">


## ManyNets ##
I am a co-developer of this visual analytic tool for network analysis with tabular interface. It visualizes up to several thousand network-overviews, allows network comparison. [VAST Mini Challenge AWARD]


<img align="center" src="https://awalin.github.io/Awalin-Sopan/mn.png" alt="many nets" width="200">


## G-Pare ##
I developed this visual analytic tool to compare uncertain graphs, provides different views to see the overview of two graphs, as well as focused views that show subsets of nodes of interest. [Paper: VAST '11]

<img align="center" src="https://awalin.github.io/Awalin-Sopan/gp.png" alt="G-pare" width="200">


## Wrong Patient Error ##
I developed this project investigating the user interface and human factor issues in EHR systems that cause the problem of selecting a wrong patient. We suggest user interface techniques that can avoid this class of error and improve patient safety.


<img align="center" src="https://awalin.github.io/Awalin-Sopan/room.png" alt="Wrong Patient Error" width="200">



## Nation of Neighbors
I analyzed evolution and dynamics of online community safety groups with network visualization approach.[Paper: IEEE SPM]

<img align="center" src="https://awalin.github.io/Awalin-Sopan/non.png" alt="Nation of N" width="200">


## Community Health Map
I co-developed this  visual analytic tool for exploring US county public health data, in collaboration with US Dept. of Health and Human Services.[Paper: GIQ journal]


<img align="center" src="https://awalin.github.io/Awalin-Sopan/chm.png" alt="Community Health Map" width="200">


## NetVisia
I contributed to this social network visualization system exploring network evolution using heat maps to display node attribute changes over time.[Paper:SocioComp'12]


<img align="center" src="https://awalin.github.io/Awalin-Sopan/nv.png" alt="Net Vizia" width="200">
