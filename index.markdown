
### Transforming information into insights. Putting users first. Leading with compassion.

I am Awalin Sopan, a data scientist focusing on data visualization and human-centered AI. I build data platforms enabling users to gain meaningful insights. I earned my Master’s in Computer Science with a focus on data science and interactive visual analytics from the University of Maryland (Human-Computer Interaction Lab), College Park. I have been published in IEEE VIS, SocialComp, KDD and SIGCHI. As a principal data science engineer I developed platforms to monitor machine learning models and incorporated such models into cyber analysts’ workflow. I have built data science applications to tackle cyber-attacks collaborating with 3 different teams; worked with healthcare workers and online community leaders analyzing public health and social network data. I like to bring people from different teams together and work closely with the product users. I am currently a [White House Presidnetial Innovation Fellow](https://presidentialinnovationfellows.gov/fellows/awalin-sopan/), serving the US Small Busienss Administration as a strategic advisor on data and analytics.

# Featured Works (more [projects](/projects.markdown) and [publications](/publications.md))

## AI Total: Analyzing Security ML Models with Imperfect Data in Production

Once a machine learning model gets deployed into production, we need to move away from static dataset evaluation to automatically evaluating performance on new incoming data. This sounds simpler than it is practice, mainly because in a fully automatic pipeline it is difficult to understand if any observed performance issues are due to model performance, pipeline issues, emerging data distribution biases, or some combination of the above. We need a shared source of truth where all the teams can have a common situational awareness of what is going on with our models. Considering all these use-cases, we built a real-time visualization dashboard that helps our team to fulfill these goals: 

* Monitor the deployed models’ regular performance, observe time trends, and detect anomalies 
* Detect issue with the evaluation data, models, or labeling 
* Investigate the reasons behind the issues 
This web-based visualization system allows the users to quickly gather headline performance numbers while maintaining confidence that the underlying data pipeline is functioning properly. It also enables us to immediately observe the root cause of an issue when something goes wrong. 

[Paper: AI Total: Analyzing Security ML Models with Imperfect Data in Production](https://ieeexplore.ieee.org/document/9629396). 2021 IEEE Symposium on Visualization for Cyber Security (VizSec).

![AI Total](/model_metric.webp)

## Reverse Engineering the Analyst: Building Machine Learning Models for the SOC

Many cyber incidents can be traced back to an original alert that was either missed or ignored by the Security Operations Center (SOC) or Incident Response (IR) team. While most analysts and SOCs are vigilant and responsive, the fact is they are often overwhelmed with alerts. If a SOC is unable to review all the alerts it generates, then sooner or later, something important will slip through the cracks. Think of a SOC as a self-contained machine that inputs unlabeled alerts and outputs the alerts labeled as “malicious” or “benign”. How can we capture the analysis and determine that something is indeed malicious, and then recreate that analysis at scale? In other words, what if we could train a machine to make the same analytical decisions as an analyst, within an acceptable level of confidence? I developed an ML system that classifies cyber events based on SOC analyts' approach of clasiifying them and published a paper and patent based on the analysis of the model's efficacy. 

[Blog](https://www.mandiant.com/resources/blog/build-machine-learning-models-for-the-soc) and [Paper: Building a machine learning model for the soc, by the input from the soc, and analyzing it for the soc](https://ieeexplore.ieee.org/document/8709231). 2018 IEEE Symposium on Visualization for Cyber Security (VizSec).

![SOC ML Model](/MLSOC.png) 

![SOC ML Model](/ml-models-soc4.png) 


