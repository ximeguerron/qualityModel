# Welcome 
You can find relevant information on this site attached to the article the **_A product quality model for cloud services_**. 
The **_product quality model_** and the **_case study_** are detailed in the next sections.

## Index

Product quality model for  cloud services
1. [Metamodel of the quality model ](#metamodel)
2. [Method](#method)
3. [Building quality model](#building)
4. [Quality model for cloud services](#model)

Case study

5. [Design](#design)
6. [Preparation](#prepare)
7. [Data Collection](#collect)
8. [Data analysis](#analysis)
9. [Reporting](#report)

# Product quality model for  cloud services
## 1. Metamodel of the quality model {#metamodel}
The quality model proposes as the baseline the ISO/IEC 25010 standard, extends and decomposes into sub-characteristics adjusted to the domain, determines objectively measurable attributes, and specifies metrics for the attributes. <a href ="./images/modelo.png"> Figure 1 </a> provides a clear and structured representation of the metamodel of the quality model and its metaclasses that describe the relationships among cloud domain and quality model concepts.

 <p> Figure 1.<a href ="./images/modelo.png"> Metamodel of the quality model </a> <br> 

Defining metamodel main concepts:
```markdown
• Characteristics are non-measurable aspects that are used in the quality model to categorize a high-level aspect that can be
evaluated.
• Subcharacteristics specify the aspects to be evaluated but are not objectively measurable and are broken down into quality
attributes. These are contained in the characteristic metaclass with the relationship to itself.
• Attributes are objectively measurable quality aspects (i.e., physical, abstract) that are not further decomposed and can be
measured using metrics.
• Metrics define a possible way to measure an attribute. It provides a measurement scale (i.e., nominal, ordinal, interval,
ratio, or absolute) combined with a measurement approach (i.e., measurement method or measurement function)
• Operationalization is the core of the metamodel, which establishes a mapping between the generic definition of a metric and
 the artifact or cloud platform where the metric is measured. 
```




## 2. Method {#method}

Our proposal is a quality model for cloud services that meet the conditions for a mixed approach and has been defined based on these two resources. 
On the one hand, the quality model proposed by the ISO/IEC 25010 standard, defines the system and software quality characteristics and subcharacteristics at a high level of abstraction. The issue with this standard is that it provides a generic model that needs to be adapted to the specific context or domain of cloud services. 

On the other hand, a taxonomy of metrics for the evaluation of cloud services was obtained through an SLR [3]. The process followed in the SLR contains three main phases: planning to define the review protocol, conducting to perform data collection, and reporting to communicate and report the results. In addition, the taxonomy creation
process detailed the activities with their artifacts, inputs, and outputs for each.
As a result, 240 attributes, 406 metrics, and 470 operationalizations were obtained (see <a href ="./images/modelo.png">Figure 2 </a>)


## 3. Building quality model {#building}
The hierarchical decomposition of the quality model was performed using thematic analysis. This method provides a rigorous and systematic way to process qualitative information by identifying, analyzing, and eliciting patterns (themes) within the data collected [42].
<a href ="./images/modelo.png">Figure 3 </a> shows the process carried out collaboratively by the team of authors, in working meetings, and consisted of the following steps:

```markdown
1. Coding: we read the selected primary studies and identified the text segments that refer to quality characteristics, quality
attributes, and metrics. Then, the text segments containing relevant information were coded using a labeling system developed by
 the authors. Mendeley has been used as a support tool.
2. Transforming codes into themes: the codes obtained were analyzed to compare them and classify them into categories
to combine them into potential themes. This process has been performed iteratively for each attribute and metric.
3. Reviewing and refining themes: the themes obtained have been reviewed and compared to detect coincidences/repetitions.
The quality attributes, the metrics, and the cloud artifacts (where the metrics are applied) were compared with each other
to understand the themes. The result was a set of themes related to quality characteristics, quality attributes, and metrics
 
```

## 4. Quality model for cloud services {#model}
The model is organized hierarchically, starting from characteristics and subcharacteristics to attributes, metrics, and operationalizations. The section covers the cloud service domain, the classification and adaptation of characteristics and subcharacteristics to the domain, the decomposition of quality into attributes, the determination of metrics for attributes, and the establishment of relationships between quality entities.

The proposed cloud services quality model is an adaptation and extension of the ISO/IEC 25010 SQuaRE standard to suit the cloud services domain. The process involved examining the eight characteristics of this standard and the 406 metrics from Guerron et al. [3]. The analysis and decomposition process resulted in 68 subcharacteristics that expand the subcharacteristics of the standard and 240 related attributes, which were used to build the hierarchical decomposition of the quality model. 

<a href ="./images/modelo.png">Figure 4 </a> shows the diagram of the model down to the level of characteristics and subcharacteristics, including existing and adding new ones.

 3.<a href ="./files/TaxonomyQualityMetrics.xlsx"> quality model for cloud services </a> <br> 
</p>

NOTE: In order to visualize the reports, please enable de _Power Pivot_ and _Power View_ complements of Excel.

<a href ="https://support.office.com/en-us/article/Start-the-Power-Pivot-add-in-for-Excel-a891a66d-36e3-43fc-81e8-fc4798f39ea8"> How to enable Excel complements

# Case study
A case study is an empirical method that investigates phenomena in real-world settings. The case study followed the next steps: design, preparation, data
collection, data analysis, and reporting

## 5. Design the case study{#design}
Runeson et al. [52] established some elements for the case study design: the objective of the study, the conceptual
framework of reference, the research questions to address, the sampling strategy, and the methods to use.
First, the objective of the case study was to demonstrate the feasibility of operationalizing the proposed quality
model to assess cloud services (e.g., databases, applications, microservices).

The conceptual framework of reference linked the phenomena studied with the quality assessment of running cloud
services, which means according to the elements defined in the quality model. First, we have defined the requirements
of quality. Then, the customized quality model was established by mapping each element from characteristics to
metrics and their operationalization. We collected raw data from deployed and delivered cloud service in the given
environment, operated the quality assessment, and compared it with expected compliance. Consequently, the quality
assessment of the cloud service was performed following the ISO/IEC 25040 standard [51].

We focus on enabling the operationalization of the quality model of cloud services and using it to assess the services. Hence, the research questions are detailed:
```markdown
• RQ1: Can the quality model be used to configure a custom quality model to assess the quality of a specific cloud service?
• RQ2: Once quality requirements or relevant attributes are identified, can a quality model be built to fit the business needs.?
• RQ3: Do the measurement results, their associated metrics, and operationalization provides actual knowledge of the current state
 of cloud services?
• RQ4: Can the custom model be improved with new or updated metrics?
```

The unit of analysis consisted of a single case SaaS called “Social Alert” (SAlert) running in a test operational environment. It is
a real case of SaaS in the industry, a data science system applied to network analytics content-based. 

## 6. Preparation{#prepare}
The quality model was applied as follows; first, the case team acted as the planner defining the quality requirements. Next, the configurator selected the attributes and metrics that fitted the requirements, mapped metrics and their operationalization to specify how the metrics will be calculated, and obtained a customized quality model for the case study. Third, the model is used in runtime to collect real-time measurements of running cloud service, applies the operationalization, and provides the monitored data.
Finally, we performed the data analysis and reported the current quality state of the case study to enable immediate improvement of cloud service quality; the information provided should support the decision-making and adjustments for evolution or adaptation in cloud service. 

Figure 6 shows the decomposition of quality characteristics into sub characteristics,
quality attributes and metrics for the case study. This selection indicates that the quality characteristics most valued
by the domain experts were Performance Efficiency, Reliability, and Security, while the quality characteristics most
valued by the software developers were Maintainability, Usability, and Compatibility

## 7. Data Collection{#collect}
The data were collected from the set of components of the cloud service (e.g., host, dockers, API). This phase is the execution of the evaluation described in ISO/IEC 25040 [51].
We used a third-party tool called New Relic [38] to perform the measurements by gathering low-level raw data from the components of the SaaS, calculating others’ metrics, and resulting in values on the measurement scales

## 8. Data analysis{#analysis}

We analyzed the values of the measures collected for each metric obtained from the monitored cloud components in order to apply the decision criteria. The processing of this data allows us to determine which metrics meet the established threshold and which do not.

We present the graphical representation of some measurement results performs during a period of time for some specific metrics, we separate them into different dashboard grouping by layers of components monitoring (e.g., host, PostgreSQL, containers, API).

<a href ="./images/taxonomy.png"> Figure 7 </a>, reports the current IaaS state with the usage of CPU, memory, and storage measurements.

<a href ="./images/taxonomy.png"> Figure 8 </a>, reports the PaaS PostgreSQL instance's current state we monitored the connections, commits, and the DB
operations rate as new metrics. Regarding the PaaS containers, we represented the memory usage, and packets received and sent. Resources are shared
among all the containers.

<a href ="./images/taxonomy.png"> Figure 9 </a>, report the monitored SaaS API using the throughput, response time, success, and error rate measurements.

The tool monitor setting and   <p> 1. <a href ="https://onenr.io/02wdKxE1XQE"> IaaS monitor </a> <br>
  
## 9. Reportingy{#report}

The answers for the research questions
RQ1: The quality model supports us to configure a custom quality model by selecting the appropriate quality
attributes, metrics, and operationalization to adjust to a specific cloud service. The cloud service selected for the
case study was Salert, and the custom quality model is represented in figure 5. The results show that the quality
requirements established for the Salert SaaS could be represented by the model generated.
RQ2: Once the quality requirements definition were done, we use a mixed approach to identify the relevant
attributes, connect them to their corresponding characteristic and metrics and select the best operationalization fitted
to the aspect wanted to measure. All these elements together made it possible to obtain a quality model fitted to the
business needs. The business need began with a basic performance definition but evolve to a more complete model
which include other quality characteristics such as reliability, security, etc.
RQ3: In our case study Salert is running over Linode platform. We use a third-party tool to gather raw data to
calculate some specific metrics in the Linode platform. This tool supports the gathering of customized information
to calculate high-level metrics (e.g., success ratio) that cannot be directly measured using the counters provided by
the platform monitoring tool. The results provided in table 21, give the stakeholders complete information about the
current state of Salert Saas in the period of time established and also a comparison with a prior period in order to
detect the ascendant or descendant tendency of the results.
RQ4: In our experience of quality model was operationalized iteratively. We had very few quality requirements
definitions that generated the first quality model with features of the basic performance of components (e.g. size,
used percentage of resources). In the next iteration, we improved the model taking into account other aspects to be
measured and enriched the quality model with new requirements which finally mapped more metrics from the quality
model (e.g., success ratio, response time), becoming a better version. Finally, in the last iteration, we repeat the cycle
but at this time update and incorporate new metrics from other sources such as the third-party monitor tool which gives
value to the stakeholders (e.g., db insert rate) and results in a quality model more suitable to cover and understand
the business needs. During each iteration, the custom model was improved with new and updated metrics to obtain a
quality model more suitable to cover and understand the business needs. Moreover, the process can be repeated at any
time, enabling the continuous improvement of the quality definition for cloud services and their assessment.


## Support or Contact 

Having trouble with Pages or any questions or suggestions? Please, contact us by email 
