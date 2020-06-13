# Welcome 
In this site, you can find relevant information attached to the article the **_A Taxonomy of quality metrics for cloud services_**. The research methodology and results are detailed in the next sections.

## Index

PLANNING
1. [Search Protocol](#Protocolo)
2. [Search Strings](#busqueda)

CONDUCTING
3. [Primary Studies](#estudios)
4. [Quality Assessment](#qa)

REPORTING
5. [Taxonomy of QoS metrics for cloud services](#clasificacion)

# Planning 
## 1. Search Protocol {#Protocolo}
Defining the objective:
```markdown
This research aims to systematically identify and taxonomically classify 
available evidence on quality metrics for cloud services and provide a 
holistic comparison to analyze potential limitations of existing research
```

The main research question addressed is:
```markdown
What metrics have been used to evaluate the internal and external 
quality of cloud services and how are they measured and used?
```

The resulting subquestions are: 

```markdown
•	RQ1: What quality characteristics and attributes were evaluated?
•	RQ2: What type of metrics were they?
  ─	RQ2.1: If the metric is base, what unit was used to calculate it?
  ─	RQ2.2: If the metric is derived, what measurement function and unit were used to calculate it?
•	RQ3: Are there tools to support the measurement process, and, if so, which ones?
•	RQ4: What type of measurement results from the metrics provided?
•	RQ5: During which phases of the cloud service lifecycle were these metrics used?
•	 RQ6: For which type of stakeholders (cloud roles) are these metrics relevant?
•	RQ7: To what type of cloud service (i.e., SaaS, PaaS, IaaS) were these metrics applied?
•	RQ8: What cloud artifacts or resources were measured?
•	RQ9: Which validation method was used to provide evidence about the metrics’ usefulness?
```

## 2. Search Strings {#busqueda}

The search string selected is shown below:

Concept	| Alternative Terms or Synonyms
------------ | -------------
Measure	| ((metric* OR measur*) AND
Quality 	| (QoS OR "quality of service" OR "quality model" OR "evaluation model" OR "assessment model" OR "quality in cloud" OR "quality of cloud") AND
Cloud	| (cloud*))

The search string applied to the same metadata (_title, abstract and keyword_) of the articles. 
The period or search dated from _2006_ to _November 2018_. 

The search string was adapted to each digital library (IEEE Xplore, ACM Digital Library, ScienceDirect y Springer Link) and listed below: 

Digital Libray| Search String | Search Metadata |Constraints
------------ | ------------- |------------ | ------------- 
IEEE Xplore |((("Publication Title":attribute OR "Publication Title":characteristic OR "Abstract":attribute OR "Abstract":characteristic OR "IEEE Terms":attribute OR "IEEE Terms":characteristic OR "Author Keywords":attribute OR "Author Keywords":characteristic) OR ("Publication Title":metric OR "Publication Title":measur OR "Abstract":metric* OR "Abstract":measur* OR "IEEE Terms":metric* OR "IEEE Terms":measur* OR "Author Keywords":metric* OR "Author Keywords":measur*)) AND ("Publication Title":QoS OR "Publication Title":"quality of service" OR "Publication Title":"quality model" OR "Publication Title":"evaluation model" OR "Publication Title":"assessment model" OR "Publication Title":"quality in cloud" OR "Publication Title":"quality of cloud" OR "Abstract":QoS OR "Abstract":"quality of service" OR "Abstract":"quality model" OR "Abstract":"evaluation model" OR "Abstract":"assessment model" OR "Abstract":"quality in cloud" OR "Abstract":"quality of cloud" OR "IEEE Terms":QoS OR "IEEE Terms":"quality of service" OR "IEEE Terms":"quality model" OR "IEEE Terms":"evaluation model" OR "IEEE Terms":"assessment model" OR "IEEE Terms":"quality in cloud" OR "IEEE Terms":"quality of cloud" OR "Author Keywords":QoS OR "Author Keywords":"quality of service" OR "Author Keywords":"quality model" OR "Author Keywords":"evaluation model" OR "Author Keywords":"assessment model" OR "Author Keywords":"quality in cloud" OR "Author Keywords":"quality of cloud") AND ("Publication Title":cloud OR "Abstract":cloud OR "IEEE Terms":cloud OR "Author Keywords":cloud))|Title, abstract and keywords|Content Type: Conference Publications and Journals & Magazines. Year: 2006-2018
ACM Digital Library|(Title:((attribute OR characteristic) OR (metric* OR measur*)) OR Abstract:((attribute OR characteristic) OR (metric* OR measur*))  OR Keyword:((attribute OR characteristic) OR (metric* OR measur*))) AND (Title:(QoS "quality of service" "quality model" "evaluation model" "assessment model" "quality in cloud" "quality of cloud") OR Abstract:(QoS "quality of service" "quality model" "evaluation model" "assessment model" "quality in cloud" "quality of cloud") OR Keyword:(QoS "quality of service" "quality model" "evaluation model" "assessment model" "quality in cloud" "quality of cloud")) AND (Title:(cloud) OR Abstract:(cloud) OR Keyword:(cloud))|Title, abstract and keywords |Published since: 2006
ScienceDirect|TITLE-ABSTR-KEY(cloud ((attribute OR characteristic) OR (metric OR measur)) AND (QoS OR "quality of service" OR "quality model" OR "evaluation model" OR "assessment model" OR "quality in cloud" OR "quality of cloud")) |Title, abstract and keywords|Pub-date > 2005. Content type: Journal.
SpringerLink| cloud* AND (attribute* OR characteristic* OR measur* OR metric*) AND (QoS OR "quality of service" OR "quality model" OR "evaluation model" OR "assessment model" OR "quality in cloud" OR "quality of cloud")|Full text 	|Content Type: Article. Discipline: Computer Science Language: English.

# Conducting
## 3. Primary Studies {#estudios}
In this subsection, we present the list of papers selected. 

Code | Primary Studies 
------------ | ------------- 
S01 | Abd, S. K., Al-Haddad, S. A. R., Hashim, F., Abdullah, A. B. H. J., & Yussof, S. (2017). An effective approach for managing power consumption in cloud computing infrastructure. Journal of Computational Science, 21, 349–360. https://doi.org/https://doi.org/10.1016/j.jocs.2016.11.007
S02 | Abdeladim, A., Baina, S., & Baina, K. (2014). Elasticity and scalability centric quality model for the cloud. In 2014 Third IEEE International Colloquium in Information Science and Technology (CIST) (pp. 135–140). http://doi.org/10.1109/CIST.2014.7016607
S03 | Abrahão, S., & Insfran, E. (2017). Models@runtime for Monitoring Cloud Services in Google App Engine. In 2017 IEEE World Congress on Services (SERVICES) (pp. 30–35). https://doi.org/10.1109/SERVICES.2017.14
S04 | Alam, A. F. B., Soltanian, A., Yangui, S., Salahuddin, M. A., Glitho, R., & Elbiaze, H. (2016). A Cloud Platform-as-a-Service for multimedia conferencing service provisioning. In 2016 IEEE Symposium on Computers and Communication (ISCC) (pp. 289–294). https://doi.org/10.1109/ISCC.2016.7543756
S05 | Al-Jawad, A., Trestian, R., Shah, P., & Gemikonakli, O. (2015). BaProbSDN: A probabilistic-based QoS routing mechanism for Software Defined Networks. In Network Softwarization (NetSoft), 2015 1st IEEE Conference on (pp. 1–5). http://doi.org/10.1109/NETSOFT.2015.7116128
S06 | de Oliveira Jr., F. A., & Ledoux, T. (2011). Self-management of Applications QoS for Energy Optimization in Datacenters. In Green Computing Middleware on Proceedings of the 2Nd International Workshop (pp. 3:1–3:6). New York, NY, USA: ACM. doi:10.1145/2088996.2088999
S07 | Arumugam, K., & Sumathi, P. (2017). Secure and QoS guaranteed selection resource for storing health care information of cloud users. In 2017 International Conference on Computing Methodologies and Communication (ICCMC) (pp. 1165–1170). https://doi.org/10.1109/ICCMC.2017.8282657
S08 | Bao, D., Xiao, Z., Sun, Y., & Zhao, J. (2010). A method and framework for quality of cloud services measurement. In 2010 3rd International Conference on Advanced Computer Theory and Engineering(ICACTE) (Vol. 5, pp. V5–358–V5–362). http://doi.org/10.1109/ICACTE.2010.5579535
S09 | Baranwal, G., & Vidyarthi, D. P. (2014). A framework for selection of best cloud service provider using ranked voting method. In Advance Computing Conference (IACC), 2014 IEEE International (pp. 831–837). http://doi.org/10.1109/IAdCC.2014.6779430
S10 | Baranwal, G., & Vidyarthi, D. P. (2016). A cloud service selection model using improved ranked voting method. Concurrency and Computation: Practice and Experience, 28(13), 3540–3567. https://doi.org/10.1002/cpe.3740
S11 | Barba-Jimenez, C., Ramirez-Velarde, R., Tchernykh, A., Rodríguez-Dagnino, R., Nolazco-Flores, J., & Perez-Cazares, R. (2016). Cloud based Video-on-Demand service model ensuring quality of service and scalability. Journal of Network and Computer Applications, 70, 102–113. https://doi.org/10.1016/j.jnca.2016.05.007
S12 | Bardhan, S., & Milojicic, D. (2012). A Mechanism to Measure Quality-of-service in a Federated Cloud Environment. In Proceedings of the 2012 Workshop on Cloud Services, Federation, and the 8th Open Cirrus Summit (pp. 19–24). New York, NY, USA: ACM. doi:10.1145/2378975.2378981
S13 | Bousselmi, K., Brahmi, Z., & Gammoudi, M. M. (2016). QoS-Aware Scheduling of Workflows in Cloud Computing Environments. In 2016 IEEE 30th International Conference on Advanced Information Networking and Applications (AINA) (pp. 737–745). http://doi.org/10.1109/AINA.2016.72
S14 | Bruneo, D. (2014). A Stochastic Model to Investigate Data Center Performance and QoS in IaaS Cloud Computing Systems. IEEE Transactions on Parallel and Distributed Systems, 25(3), 560–569. http://doi.org/10.1109/TPDS.2013.67
S15 | Cedillo, P., Jimenez-Gomez, J., Abrahao, S., & Insfran, E. (2015). Towards a Monitoring Middleware for Cloud Services. In Services Computing (SCC), 2015 IEEE International Conference on (pp. 451–458). http://doi.org/10.1109/SCC.2015.68
S16 | Cervino, J., Rodriguez, P., Trajkovska, I., Mozo, A., & Salvachua, J. (2011). Testing a Cloud Provider Network for Hybrid P2P and Cloud Streaming Architectures. In Cloud Computing (CLOUD), 2011 IEEE International Conference on (pp. 356–363). http://doi.org/10.1109/CLOUD.2011.52
S17 | Costa, C. M., Leite, C. R. M., & Sousa, A. L. (2015). Service Response Time Measurement Model of Service Level Agreements in Cloud Environment. In 2015 IEEE International Conference on Smart City/SocialCom/SustainCom (SmartCity) (pp. 969–974). http://doi.org/10.1109/SmartCity.2015.196
S18 | de Assunção, M. D., Cardonha, C. H., Netto, M. A. S., & Cunha, R. L. F. (2016). Impact of user patience on auto-scaling resource capacity for cloud services. Future Generation Computer Systems, 55, 41–50. http://doi.org/http://dx.doi.org/10.1016/j.future.2015.09.001
S19 | Dou, W., Xu, X., Meng, S., & Yu, S. (2015). An Energy-Aware QoS Enhanced Method for Service Computing across Clouds and Data Centers. In 2015 Third International Conference on Advanced Cloud and Big Data (pp. 80–87). http://doi.org/10.1109/CBD.2015.23
S20 | Duggan, J., Cetintemel, U., Papaemmanouil, O., & Upfal, E. (2011). Performance Prediction for Concurrent Database Workloads. In Proceedings of the 2011 ACM SIGMOD International Conference on Management of Data (pp. 337–348). New York, NY, USA: ACM. doi:10.1145/1989323.1989359
S21 | Ezenwoke, A., Daramola, O., & Adigun, M. (2018). QoS-based ranking and selection of SaaS applications using heterogeneous similarity metrics. Journal of Cloud Computing, 7(1), 15. https://doi.org/10.1186/s13677-018-0117-4
S22 | Faragardi, H. R., Shojaee, R., Tabani, H., & Rajabi, A. (2013). An analytical model to evaluate reliability of cloud computing systems in the presence of QoS requirements. In Computer and Information Science (ICIS), 2013 IEEE/ACIS 12th International Conference on (pp. 315–321). http://doi.org/10.1109/ICIS.2013.6607860
S23 | Garcia-Pineda, M., Segura-Garcia, J., & Felici-Castell, S. (2018). Estimation techniques to measure subjective quality on live video streaming in Cloud Mobile Media services. Computer Communications, 118, 27–39. https://doi.org/10.1016/j.comcom.2017.08.009
S24 | Garg, S. K., Versteeg, S., & Buyya, R. (2013). A framework for ranking of cloud computing services. Future Generation Computer Systems, 29(4), 1012–1023. http://doi.org/http://dx.doi.org/10.1016/j.future.2012.06.006
S25 | Ghafari, S. M., Fazeli, M., Patooghy, A., & Rikhtechi, L. (2013). Bee-MMT: A load balancing method for power consumption management in cloud computing. In Contemporary Computing (IC3), 2013 Sixth International Conference on (pp. 76–80). http://doi.org/10.1109/IC3.2013.6612165
S26 | Ghahramani, M. H., Zhou, M., & Hon, C. T. (2017). Toward cloud computing QoS architecture: analysis of cloud systems and cloud services. IEEE/CAA Journal of Automatica Sinica, 4(1), 6–18. https://doi.org/10.1109/JAS.2017.7510313
S27 | Gholami, A., & Arani, M. G. (2015). A trust model for resource selection in cloud computing environment. In 2015 2nd International Conference on Knowledge-Based Engineering and Innovation (KBEI) (pp. 144–151). http://doi.org/10.1109/KBEI.2015.7436036
S28 | Ghosh, R., Longo, F., Naik, V. K., & Trivedi, K. S. (2010). Quantifying Resiliency of IaaS Cloud. In Reliable Distributed Systems, 2010 29th IEEE Symposium on (pp. 343–347). http://doi.org/10.1109/SRDS.2010.49
S29 | Gonzales, D., Kaplan, J. M., Saltzman, E., Winkelman, Z., & Woods, D. (2017). Cloud-Trust—a Security Assessment Model for Infrastructure as a Service (IaaS) Clouds. IEEE Transactions on Cloud Computing, 5(3), 523–536. https://doi.org/10.1109/TCC.2015.2415794
S30 | Guérout, T., Medjiah, S., Costa, G. Da, & Monteil, T. (2014). Quality of service modeling for green scheduling in Clouds. Sustainable Computing: Informatics and Systems, 4(4), 225–240. http://doi.org/http://dx.doi.org/10.1016/j.suscom.2014.08.006
S31 | Hasan, M. S., Alvares, F., Ledoux, T., & Pazat, J. (2017). Investigating Energy Consumption and Performance Trade-Off for Interactive Cloud Application. IEEE Transactions on Sustainable Computing, 2(2), 113–126. https://doi.org/10.1109/TSUSC.2017.2714959
S32 | Hassam, M., Kara, N., Belqasmi, F., & Glitho, R. (2014). Virtualized Infrastructure for Video Game Applications in Cloud Environments. In Proceedings of the 12th ACM International Symposium on Mobility Management and Wireless Access (pp. 109–114). New York, NY, USA: ACM. doi:10.1145/2642668.2642679
S33 | Hecht, G., Jose-Scheidt, B., Figueiredo, C. D., Moha, N., & Khomh, F. (2014). An Empirical Study of the Impact of Cloud Patterns on Quality of Service (QoS). In Cloud Computing Technology and Science (CloudCom), 2014 IEEE 6th International Conference on (pp. 278–283). http://doi.org/10.1109/CloudCom.2014.141
S34 | Heidari, P., Boucheneb, H., & Shami, A. (2015). A Formal Approach for QoS Assurance in the Cloud. In 2015 IEEE 7th International Conference on Cloud Computing Technology and Science (CloudCom) (pp. 629–634). http://doi.org/10.1109/CloudCom.2015.36
S35 | Hu, Y., Deng, B., Yang, Y., & Wang, D. (2017). Elasticity evaluation of IaaS cloud based on mixed workloads. In Proceedings - 15th International Symposium on Parallel and Distributed Computing, ISPDC 2016 (pp. 157–164). Beijing Institute of System Engineering, Beijing, China. https://doi.org/10.1109/ISPDC.2016.28
S36 | Hwang, K., Bai, X., Shi, Y., Li, M., Chen, W.-G., & Wu, Y. (2016). Cloud Performance Modeling with Benchmark Evaluation of Elastic Scaling Strategies. IEEE Transactions on Parallel and Distributed Systems, 27(1), 130–143. https://doi.org/10.1109/TPDS.2015.2398438
S37 | Ibrahim, A. A. Z. A., Wasim, M. U., Varrette, S., & Bouvry, P. (2018). PRESEnCE: Performance Metrics Models for Cloud SaaS Web Services. In 2018 IEEE 11th International Conference on Cloud Computing (CLOUD) (pp. 936–940). https://doi.org/10.1109/CLOUD.2018.00140
S38 | Joy, N., Chandrasekaran, K., & Binu, A. (2015). A study on energy efficient cloud computing. In 2015 IEEE International Conference on Computational Intelligence and Computing Research (ICCIC) (pp. 1–6). http://doi.org/10.1109/ICCIC.2015.7435661
S39 | Kaaniche, N., Mohamed, M., Laurent, M., & Ludwig, H. (2017). Security SLA Based Monitoring in Clouds. In 2017 IEEE International Conference on Edge Computing (EDGE) (pp. 90–97). https://doi.org/10.1109/IEEE.EDGE.2017.20
S40 | Karim, R., Ding, C., & Miri, A. (2015). End-to-End Performance Prediction for Selecting Cloud Services Solutions. In Service-Oriented System Engineering (SOSE), 2015 IEEE Symposium on (pp. 69–77). http://doi.org/10.1109/SOSE.2015.11
S41 | Katsaros, G., Subirats, J., Fitó, J. O., Guitart, J., Gilet, P., & Espling, D. (2013). A service framework for energy-aware monitoring and VM management in Clouds. Future Generation Computer Systems, 29(8), 2077–2091. http://doi.org/http://dx.doi.org/10.1016/j.future.2012.12.006
S42 | Kaur, P. D., & Chana, I. (2014). A resource elasticity framework for QoS-aware execution of cloud applications. Future Generation Computer Systems, 37, 14–25. http://doi.org/http://dx.doi.org/10.1016/j.future.2014.02.018
S43 | Kirsal, Y., Ever, Y. K., Mostarda, L., & Gemikonakli, O. (2015). Analytical Modelling and Performability Analysis for Cloud Computing Using Queuing System. In 2015 IEEE/ACM 8th International Conference on Utility and Cloud Computing (UCC) (pp. 643–647). http://doi.org/10.1109/UCC.2015.115
S44 | Lee, J. Y., Lee, J. W., Cheun, D. W., & Kim, S. D. (2009). A Quality Model for Evaluating Software-as-a-Service in Cloud Computing. In Software Engineering Research, Management and Applications, 2009. SERA ’09. 7th ACIS International Conference on (pp. 261–266). http://doi.org/10.1109/SERA.2009.43
S45 | Lim, E., & Thiran, P. (2014). Communication of Technical QoS among Cloud Brokers. In Cloud Engineering (IC2E), 2014 IEEE International Conference on (pp. 403–409). http://doi.org/10.1109/IC2E.2014.92
S46 | Lin, Y.-K., & Chang, P.-C. (2011). Maintenance reliability estimation for a cloud computing network with nodes failure. Expert Systems with Applications, 38(11), 14185–14189. http://doi.org/http://dx.doi.org/10.1016/j.eswa.2011.04.230
S47 | Liu, M., Dou, W., Yu, S., & Zhang, Z. (2014). A clusterized firewall framework for cloud computing. In 2014 IEEE International Conference on Communications (ICC) (pp. 3788–3793). http://doi.org/10.1109/ICC.2014.6883911
S48 | Liu, X., Xia, C., Wang, T., & Zhong, L. (2017). CloudSec: A Novel Approach to Verifying Security Conformance at the Bottom of the Cloud. In 2017 IEEE International Congress on Big Data (BigData Congress) (pp. 569–576). https://doi.org/10.1109/BigDataCongress.2017.87
S49 | Lu, L., & Yuan, Y. (2018). A novel TOPSIS evaluation scheme for cloud service trustworthiness combining objective and subjective aspects. Journal of Systems and Software, 143, 71–86. https://doi.org/10.1016/j.jss.2018.05.004
S50 | Manuel, P. (2015). A trust model of cloud computing based on Quality of Service. Annals of Operations Research, 233(1), 281–292. http://doi.org/10.1007/s10479-013-1380-x
S51 | Mastelic, T., Brandic, I., & Jaarevic, J. (2014). CPU Performance Coefficient (CPU-PC): A Novel Performance Metric Based on Real-Time CPU Resource Provisioning in Time-Shared Cloud Environments. In Cloud Computing Technology and Science (CloudCom), 2014 IEEE 6th International Conference on (pp. 408–415). http://doi.org/10.1109/CloudCom.2014.13
S52 | Mesbahi, M. R., Rahmani, A. M., & Hosseinzadeh, M. (2018). Reliability and high availability in cloud computing environments: a reference roadmap. Human-Centric Computing and Information Sciences, 8(1), 20. https://doi.org/10.1186/s13673-018-0143-8
S53 | Nadanam, P., & Rajmohan, R. (2012). QoS evaluation for web services in cloud computing. In Computing Communication Networking Technologies (ICCCNT), 2012 Third International Conference on (pp. 1–8). http://doi.org/10.1109/ICCCNT.2012.6395991
S54 | Pedersen, J. M., Riaz, M. T., Junior, J. C., Dubalski, B., Ledzinski, D., & Patel, A. (2011). Assessing Measurements of QoS for Global Cloud Computing Services. In Dependable, Autonomic and Secure Computing (DASC), 2011 IEEE Ninth International Conference on (pp. 682–689). http://doi.org/10.1109/DASC.2011.120
S55 | Preuveneers, D., Heyman, T., Berbers, Y., & Joosen, W. (2016). Systematic scalability assessment for feature oriented multi-tenant services. Journal of Systems and Software, 116, 162–176. https://doi.org/10.1016/j.jss.2015.12.024
S56 | Qian, S., Cao, J., Le Mouël, F., Li, M., & Wang, J. (2015). Towards Prioritized Event Matching in a Content-based Publish/Subscribe System. In Proceedings of the 9th ACM International Conference on Distributed Event-Based Systems (pp. 116–127). New York, NY, USA: ACM. doi:10.1145/2675743.2771823
S57 | Ran, Y., Shi, Y., Yang, E., Chen, S., & Yang, J. (2014). Dynamic resource allocation for video transcoding with QoS guaranteeing in cloud-based DASH system. In 2014 IEEE Globecom Workshops (GC Wkshps) (pp. 144–149). http://doi.org/10.1109/GLOCOMW.2014.7063421
S58 | Ravindhren, V. G., & Ravimaran, S. (2017). CCMA—cloud critical metric assessment framework for scientific computing. Cluster Computing. https://doi.org/10.1007/s10586-017-1384-4
S59 | Ravindran, K. (2013). Self-Assessment and Reconfiguration Methods for Autonomous Cloud-based Network Systems. In Distributed Simulation and Real Time Applications (DS-RT), 2013 IEEE/ACM 17th International Symposium on (pp. 87–94). http://doi.org/10.1109/DS-RT.2013.37
S60 | Rizvi, S., Ryoo, J., Kissell, J., & Aiken, B. (2015). A Stakeholder-oriented Assessment Index for Cloud Security Auditing. In Proceedings of the 9th International Conference on Ubiquitous Information Management and Communication (pp. 55:1–55:7). New York, NY, USA: ACM. doi:10.1145/2701126.2701226
S61 | Rizvi, S., Roddy, H., Gualdoni, J., & Myzyri, I. (2017). Three-Step Approach to QoS Maintenance in Cloud Computing Using a Third-Party Auditor. Procedia Computer Science, 114, 83–92. https://doi.org/10.1016/j.procs.2017.09.014
S62 | Roohitavaf, M., Entezari-Maleki, R., & Movaghar, A. (2013). Availability Modeling and Evaluation of Cloud Virtual Data Centers. In Parallel and Distributed Systems (ICPADS), 2013 International Conference on (pp. 675–680). http://doi.org/10.1109/ICPADS.2013.120
S63 | Saiz, E., Ibarrola, E., Cristobo, L., & Taboada, I. (2014). A cloud platform for QoE evaluation: QoXcloud. In ITU Kaleidoscope Academic Conference: Living in a converged world - Impossible without standards?, Proceedings of the 2014 (pp. 241–247). http://doi.org/10.1109/Kaleidoscope.2014.6858471
S64 | Samet, N., Letaïfa, A. Ben, Hamdi, M., & Tabbane, S. (2016). Real-Time User Experience Evaluation for Cloud-Based Mobile Video. In 2016 30th International Conference on Advanced Information Networking and Applications Workshops (WAINA) (pp. 204–208). http://doi.org/10.1109/WAINA.2016.120
S65 | Singh, S., & Chana, I. (2015). Q-aware: Quality of service based cloud resource provisioning. Computers & Electrical Engineering, 47, 138–160. http://doi.org/http://dx.doi.org/10.1016/j.compeleceng.2015.02.003
S66 | Slivar, I., Skorin-Kapov, L., & Suznjevic, M. (2016). Cloud Gaming QoE Models for Deriving Video Encoding Adaptation Strategies. In Proceedings of the 7th International Conference on Multimedia Systems (pp. 18:1–18:12). New York, NY, USA: ACM. doi:10.1145/2910017.2910602
S67 | Son, S., & Sim, K. M. (2015). Adaptive and similarity-based tradeoff algorithms in a price-timeslot-QoS negotiation system to establish cloud SLAs. Information Systems Frontiers, 17(3), 565–589. http://doi.org/10.1007/s10796-013-9432-y
S68 | Sousa, F. R. C., & Machado, J. C. (2012). Towards Elastic Multi-Tenant Database Replication with Quality of Service. In Utility and Cloud Computing (UCC), 2012 IEEE Fifth International Conference on (pp. 168–175). http://doi.org/10.1109/UCC.2012.36
S69 | Souza, R. H. de, Flores, P. A., Dantas, M. A. R., & Siqueira, F. (2016). Architectural recovering model for Distributed Databases: A reliability, availability and serviceability approach. In 2016 IEEE Symposium on Computers and Communication (ISCC) (pp. 575–580). https://doi.org/10.1109/ISCC.2016.7543799
S70 | Taherizadeh, S., & Stankovski, V. (2017). Incremental Learning from Multi-level Monitoring Data and Its Application to Component Based Software Engineering. In 2017 IEEE 41st Annual Computer Software and Applications Conference (COMPSAC) (Vol. 2, pp. 378–383). https://doi.org/10.1109/COMPSAC.2017.148
S71 | Vedam, V., & Vemulapati, J. (2012). Demystifying Cloud Benchmarking Paradigm - An in Depth View. In 2012 IEEE 36th Annual Computer Software and Applications Conference (pp. 416–421). http://doi.org/10.1109/COMPSAC.2012.61
S72 | Wagle, S. S., Guzek, M., Bouvry, P., & Bisdorff, R. (2015). An Evaluation Model for Selecting Cloud Services from Commercially Available Cloud Providers. In 2015 IEEE 7th International Conference on Cloud Computing Technology and Science (CloudCom) (pp. 107–114). http://doi.org/10.1109/CloudCom.2015.94
S73 | Wang, S., & Dey, S. (2012). Cloud Mobile Gaming: Modeling and Measuring User Experience in Mobile Wireless Networks. SIGMOBILE Mob. Comput. Commun. Rev., 16(1), 10–21. doi:10.1145/2331675.2331679
S74 | Wen, Z. Y., & Hsiao, H. F. (2014). QoE-driven performance analysis of cloud gaming services. In Multimedia Signal Processing (MMSP), 2014 IEEE 16th International Workshop on (pp. 1–6). http://doi.org/10.1109/MMSP.2014.6958835
S75 | Wu, X., Liu, G., & Xu, J. (2015). A QoS-constrained scheduling for access requests in cloud storage. In Industrial Electronics and Applications (ICIEA), 2015 IEEE 10th Conference on (pp. 155–160). http://doi.org/10.1109/ICIEA.2015.7334102
S76 | Xia, Y., Zhou, M., Luo, X., Zhu, Q., Li, J., & Huang, Y. (2015). Stochastic Modeling and Quality Evaluation of Infrastructure-as-a-Service Clouds. IEEE Transactions on Automation Science and Engineering, 12(1), 162–170. http://doi.org/10.1109/TASE.2013.2276477
S77 | Xiao, Y., Lin, C., Jiang, Y., Chu, X., & Shen, X. (2010). Reputation-Based QoS Provisioning in Cloud Computing via Dirichlet Multinomial Model. In Communications (ICC), 2010 IEEE International Conference on (pp. 1–5). http://doi.org/10.1109/ICC.2010.5502407
S78 | Xiong, K., & Chen, X. (2015). Ensuring Cloud Service Guarantees via Service Level Agreement (SLA)-Based Resource Allocation. In 2015 IEEE 35th International Conference on Distributed Computing Systems Workshops (pp. 35–41). http://doi.org/10.1109/ICDCSW.2015.18
S79 | Xu, H., Qiu, X., Sheng, Y., Luo, L., & Xiang, Y. (2018). A Qos-Driven Approach to the Cloud Service Addressing Attributes of Security. IEEE Access, 6, 34477–34487. https://doi.org/10.1109/ACCESS.2018.2849594
S80 | Yu, N., Gu, F., Guo, X., & He, Z. (2015). A Fine-grained Flow Control Model for Cloud-assisted Data Broadcasting. In Proceedings of the 18th Symposium on Communications {&} Networking (pp. 24–31). San Diego, CA, USA: Society for Computer Simulation International. Retrieved from http://dl.acm.org/citation.cfm?id=2872550.2872554
S81 | Zant, B. El, & Gagnaire, M. (2015). Towards a unified customer aware figure of merit for CSP selection. Journal of Cloud Computing, 4(1), 1–23. http://doi.org/10.1186/s13677-015-0049-1
S82 | Zheng, X., Martin, P., & Brohman, K. (2013). Cloud Service Negotiation: A Research Roadmap. In Services Computing (SCC), 2013 IEEE International Conference on (pp. 627–634). http://doi.org/10.1109/SCC.2013.93
S83 | Zheng, X., Martin, P., Brohman, K., & Xu, L. D. (2014). CLOUDQUAL: A Quality Model for Cloud Services. IEEE Transactions on Industrial Informatics, 10(2), 1527–1536. http://doi.org/10.1109/TII.2014.2306329
S84 | Zhou, P., Wang, Z., Li, W., & Jiang, N. (2015). Quality Model of Cloud Service. In High Performance Computing and Communications (HPCC), 2015 IEEE 7th International Symposium on Cyberspace Safety and Security (CSS), 2015 IEEE 12th International Conferen on Embedded Software and Systems (ICESS), 2015 IEEE 17th International Conference on (pp. 1418–1423). http://doi.org/10.1109/HPCC-CSS-ICESS.2015.134
S85 | Feng, J., & Kong, L. (2015). A Fuzzy Multi-objective Genetic Algorithm for QoS-based Cloud Service Composition. In 2015 11th International Conference on Semantics, Knowledge and Grids (SKG) (pp. 202–206). http://doi.org/10.1109/SKG.2015.23
S86 | Khan, H. M., Chan, G. Y., & Chua, F. F. (2016). An adaptive monitoring framework for ensuring accountability and quality of services in cloud computing. In 2016 International Conference on Information Networking (ICOIN) (pp. 249–253). http://doi.org/10.1109/ICOIN.2016.7427071
S87 | Khurana, R., & Bawa, R. K. (2016). QoS based Cloud Service Selection paradigms. In 2016 6th International Conference - Cloud System and Big Data Engineering (Confluence) (pp. 174–179). https://doi.org/10.1109/CONFLUENCE.2016.7508109
S88 | Klymash, M., Beshley, M., Strykhalyuk, B., & Maksymyuk, T. (2014). Research and development the methods of quality of service provision in Mobile Cloud systems. In Communications and Networking (BlackSeaCom), 2014 IEEE International Black Sea Conference on (pp. 160–164). http://doi.org/10.1109/BlackSeaCom.2014.6849030

## 4. Quality Assessment {#qa}
In order assess the quality of studies, we designed the following quality questions.

**QUALITY QUESTIONS** |
------------ |
Q1. (Motivation) Is the research problem clearly specified? |
Q2. (Aim)Are the research aim(s)/objective(s) clearly established? |
Q3. (Context) Is the context of the study clearly specified? |
Q4. (Data) Are the metrics for assessing the quality of cloud services clearly defined? |
Q5. (Data) Are the measurement functions for calculating the metrics clearly defined? |
Q6. (Design) Are the metric(s) empirically validated? | 
Q7. (Usefulness) Is there enough evidence that shows how the metrics can be used in practice? |
Q8. (Contributions/results) Are the contributions/results of the paper discussed? |
Q9. (Insights) Are the insights/lessons learned of the study reported? |
Q10. (Limitations) Are the limitations of the study discussed? |


**QUALITY ASSESSMENT**

The primary studies' quality was scored based on how well they satisfied the ten quality questions.  Be clear that we do not evaluate the quality of the paper itself with these criteria, but only its contributions’ alignment with our research questions. Then the scores less than five were removed (S85,S86, S87,S88).

Code | Q1 | Q2 | Q3 | Q4 | Q5 | Q6 | Q7 | Q8 | Q9 | Q10 | Total

--- | ----- | ---------| ------- | --------- | -------- | ---------- | ------- | -------- | --------- | -------
S01 | Y | P | Y | Y | Y | P | Y | Y | N | N | 7
S02 | Y | P | Y | Y | Y | P | Y | Y | P | P | 8
S03 | Y | P | Y | Y | Y | Y | Y | Y | N | P | 8
S04 | Y | Y | Y | Y | Y | P | Y | P | N | N | 7
S05 | P | P | P | Y | Y | P | N | Y | N | N | 5
S06 | Y | Y | N | P | P | P | Y | Y | N | Y | 6,5
S07 | Y | P | P | Y | Y | P | N | P | N | N | 5
S08 | P | P | Y | Y | Y | P | N | P | N | N | 5
S09 | P | Y | Y | Y | Y | N | P | N | N | N | 5
S10 | P | Y | Y | Y | Y | N | Y | Y | N | N | 6,5
S11 | P | Y | Y | Y | Y | P | Y | Y | N | N | 7
S12 | Y | Y | Y | Y | Y | P | Y | Y | P | N | 8
S13 | Y | Y | P | Y | Y | P | Y | Y | N | N | 7
S14 | Y | Y | P | Y | Y | P | N | Y | P | N | 6,5
S15 | Y | Y | Y | Y | Y | N | Y | P | P | N | 7
S16 | Y | Y | Y | Y | Y | N | Y | Y | P | N | 7,5
S17 | P | P | P | Y | Y | P | Y | P | N | N | 5,5
S18 | Y | Y | P | Y | Y | P | P | Y | P | N | 7
S19 | P | Y | Y | Y | Y | P | P | Y | P | N | 7
S20 | Y | Y | Y | Y | Y | P | Y | Y | N | Y | 8,5
S21 | Y | N | Y | Y | Y | P | N | Y | P | N | 6
S22 | Y | Y | Y | P | P | N | P | P | P | Y | 6,5
S23 | P | P | Y | Y | Y | Y | N | Y | N | N | 6
S24 | Y | Y | Y | Y | Y | N | Y | Y | P | P | 8
S25 | P | P | Y | Y | Y | P | N | Y | N | N | 5,5
S26 | Y | P | Y | Y | Y | N | N | Y | Y | N | 6,5
S27 | Y | P | Y | Y | Y | P | N | Y | P | N | 6,5
S28 | Y | P | Y | Y | Y | P | N | P | N | N | 5,5
S29 | Y | Y | Y | P | P | P | P | Y | Y | Y | 8
S30 | Y | P | Y | Y | Y | P | P | Y | Y | N | 7,5
S31 | P | P | Y | Y | Y | P | N | Y | N | Y | 6,5
S32 | P | P | Y | Y | Y | N | N | Y | N | N | 5
S33 | P | P | Y | P | P | Y | N | Y | P | N | 5,5
S34 | P | Y | Y | Y | Y | N | N | P | P | N | 5,5
S35 | P | P | Y | Y | Y | P | N | Y | N | N | 5,5
S36 | Y | P | Y | Y | Y | Y | Y | Y | Y | N | 8,5
S37 | P | P | Y | Y | Y | P | N | Y | P | N | 6
S38 | Y | N | Y | Y | Y | N | N | Y | N | N | 5
S39 | Y | N | Y | P | P | P | P | Y | N | N | 5
S40 | Y | P | Y | Y | Y | N | N | Y | N | N | 5,5
S41 | Y | P | Y | Y | Y | P | N | Y | N | N | 6
S42 | Y | P | Y | Y | Y | N | P | Y | N | N | 6
S43 | P | P | Y | P | P | P | P | Y | N | N | 5
S44 | Y | P | Y | Y | Y | N | P | Y | N | N | 6
S45 | P | P | Y | Y | Y | N | N | Y | N | N | 5
S46 | Y | N | Y | Y | Y | P | P | P | N | N | 5,5
S47 | Y | N | Y | Y | Y | P | P | Y | N | N | 6
S48 | Y | Y | Y | Y | Y | P | N | P | N | N | 6
S49 | Y | Y | Y | Y | Y | Y | N | P | N | N | 6,5
S50 | P | Y | Y | Y | Y | N | P | N | N | N | 5
S51 | Y | N | Y | Y | Y | P | P | Y | N | N | 6
S52 | Y | P | Y | Y | Y | N | N | Y | Y | P | 7
S53 | Y | N | Y | Y | Y | N | N | Y | N | N | 5
S54 | P | P | Y | Y | Y | N | N | Y | P | N | 5,5
S55 | Y | P | Y | P | P | P | Y | Y | Y | N | 7
S56 | Y | N | Y | Y | Y | P | N | Y | Y | P | 7
S57 | Y | N | Y | Y | Y | N | N | Y | N | N | 5
S58 | P | N | Y | Y | Y | P | N | Y | P | N | 5,5
S59 | Y | Y | Y | P | P | N | P | Y | N | N | 5,5
S60 | Y | N | Y | Y | Y | P | N | Y | N | N | 5,5
S61 | Y | P | Y | Y | Y | N | N | P | N | N | 5
S62 | Y | N | Y | Y | Y | N | N | Y | N | P | 5,5
S63 | Y | Y | Y | P | P | N | N | Y | N | N | 5
S64 | Y | P | Y | Y | Y | N | N | P | N | N | 5
S65 | P | N | Y | Y | Y | P | Y | Y | Y | N | 7
S66 | P | N | Y | Y | Y | P | N | Y | P | P | 6
S67 | P | Y | Y | P | P | N | N | Y | Y | N | 5,5
S68 | Y | N | Y | Y | Y | N | N | Y | P | N | 5,5
S69 | P | Y | P | Y | Y | N | P | P | N | N | 5
S70 | P | Y | P | Y | Y | P | N | P | N | N | 5
S71 | N | N | Y | Y | Y | N | P | P | Y | N | 5
S72 | P | Y | Y | Y | Y | N | N | Y | Y | N | 6,5
S73 | P | N | Y | Y | Y | P | Y | Y | Y | N | 7
S74 | P | N | Y | Y | Y | P | N | Y | P | N | 5,5
S75 | Y | N | Y | Y | Y | N | N | Y | P | N | 5,5
S76 | Y | N | Y | Y | Y | N | N | Y | Y | Y | 7
S77 | P | P | P | Y | Y | N | P | Y | N | N | 5
S78 | Y | P | Y | Y | Y | P | N | P | N | N | 5,5
S79 | Y | Y | Y | Y | Y | P | N | Y | Y | N | 7,5
S80 | Y | Y | Y | Y | Y | P | N | P | N | N | 6
S81 | Y | Y | Y | Y | Y | P | N | Y | N | N | 6,5
S82 | Y | Y | Y | Y | Y | N | N | Y | P | N | 6,5
S83 | P | Y | Y | Y | Y | Y | Y | Y | N | Y | 8,5
S84 | N | Y | Y | Y | Y | P | N | Y | N | N | 5,5
S85 | P | P | P | Y | Y | N | N | P | N | N | 4
S86 | P | N | Y | P | P | N | P | P | N | N | 3,5
S87 | P | N | P | Y | P | N | N | P | N | N | 3
S88 | P | P | Y | Y | Y | N | N | P | N | N | 4,5

Y: Fully compliance, P: Partially comply, N: Do not comply

**RELEVANCE OF PRIMARY STUDIES**

In order to know the impact and influence of the papers. We used two criteria: 

•	The relevance of the journal or conference where the paper was published (CORE-ERA ranking for conference papers and the impact factor in Journal Citations Reports(JCR) for journal papers).  
•	The number of citations of the paper, collected from Google Scholar . 

Code | Type conference /journal | Relevant publication | Citations | Year | Rate Citation Value | Library
------------ | -------------  | ------------- | ------------- | ------------- | ------------- | -------------
S01 | J | 10 | 12 | 2017 | 10 | ScienceDirect
S02 | C | 5 | 5 | 2014 | 0 | IEEE Xplore
S03 | C | 0 | 3 | 2017 | 10 | IEEE Xplore
S04 | C | 5 | 5 | 2016 | 0 | IEEE Xplore
S05 | C | 0 | 16 | 2015 | 5 | IEEE Xplore
S06 | C | 0 | 5 | 2011 | 0 | ACM
S07 | C | 0 | 0 | 2017 | 5 | IEEE Xplore
S08 | C | 0 | 11 | 2010 | 5 | IEEE Xplore
S09 | C | 0 | 40 | 2014 | 5 | IEEE Xplore
S10 | J | 10 | 21 | 2016 | 5 | ACM
S11 | J | 10 | 17 | 2016 | 5 | ScienceDirect
S12 | C | 0 | 12 | 2012 | 5 | ACM
S13 | C | 5 | 11 | 2016 | 5 | IEEE Xplore
S14 | J | 10 | 160 | 2014 | 10 | IEEE Xplore
S15 | C | 10 | 12 | 2015 | 5 | IEEE Xplore
S16 | C | 5 | 30 | 2011 | 5 | IEEE Xplore
S17 | C | 0 | 2 | 2015 | 0 | IEEE Xplore
S18 | J | 10 | 24 | 2013 | 5 | ScienceDirect
S19 | C | 0 | 1 | 2015 | 0 | IEEE Xplore
S20 | C | 10 | 134 | 2011 | 10 | ACM
S21 | J | 0 | 4 | 2018 | 10 | ACM
S22 | C | 5 | 20 | 2013 | 5 | IEEE Xplore
S23 | J | 10 | 1 | 2018 | 10 | ACM
S24 | J | 10 | 702 | 2013 | 10 | ScienceDirect
S25 | C | 0 | 39 | 2013 | 5 | IEEE Xplore
S26 | J | 0 | 63 | 2017 | 10 | IEEE Xplore
S27 | C | 0 | 3 | 2015 | 0 | IEEE Xplore
S28 | C | 10 | 53 | 2010 | 10 | IEEE Xplore
S29 | J | 10 | 70 | 2017 | 10 | IEEE Xplore
S30 | J | 10 | 24 | 2014 | 5 | ScienceDirect
S31 | J | 0 | 7 | 2017 | 10 | IEEE Xplore
S32 | C | 5 | 3 | 2014 | 0 | ACM
S33 | C | 5 | 8 | 2014 | 0 | IEEE Xplore
S34 | C | 5 | 0 | 2015 | 0 | IEEE Xplore
S35 | C | 0 | 2 | 2017 | 10 | IEEE Xplore
S36 | C | 0 | 83 | 2016 | 10 | IEEE Xplore
S37 | C | 5 | 0 | 2018 | 5 | IEEE Xplore
S38 | C | 0 | 1 | 2015 | 0 | IEEE Xplore
S39 | C | 0 | 7 | 2017 | 10 | IEEE Xplore
S40 | C | 0 | 7 | 2015 | 0 | IEEE Xplore
S41 | J | 10 | 50 | 2013 | 10 | ScienceDirect
S42 | J | 10 | 56 | 2014 | 10 | ScienceDirect
S43 | C | 0 | 3 | 2015 | 0 | IEEE Xplore
S44 | C | 5 | 138 | 2009 | 10 | IEEE Xplore
S45 | C | 0 | 4 | 2014 | 0 | IEEE Xplore
S46 | J | 0 | 47 | 2011 | 5 | ScienceDirect
S47 | C | 5 | 10 | 2014 | 5 | IEEE Xplore
S48 | C | 0 | 0 | 2017 | 5 | IEEE Xplore
S49 | J | 10 | 3 | 2018 | 10 | ScienceDirect
S50 | J | 0 | 122 | 2015 | 10 | SpringerLink
S51 | C | 5 | 3 | 2014 | 0 | IEEE Xplore
S52 | J | 10 | 10 | 2018 | 10 | SpringerLink
S53 | C | 0 | 21 | 2012 | 5 | IEEE Xplore
S54 | C | 5 | 26 | 2011 | 5 | IEEE Xplore
S55 | J | 10 | 6 | 2016 | 0 | ACM
S56 | C | 0 | 1 | 2015 | 0 | ACM
S57 | C | 0 | 5 | 2014 | 0 | IEEE Xplore
S58 | J | 10 | 2 | 2017 | 10 | SpringerLink
S59 | C | 5 | 2 | 2013 | 0 | IEEE Xplore
S60 | C | 0 | 6 | 2015 | 0 | ACM
S61 | J | 0 | 3 | 2017 | 10 | ACM
S62 | C | 5 | 5 | 2013 | 0 | IEEE Xplore
S63 | C | 0 | 3 | 2014 | 0 | IEEE Xplore
S64 | C | 0 | 3 | 2016 | 0 | IEEE Xplore
S65 | J | 10 | 67 | 2015 | 10 | ScienceDirect
S66 | C | 0 | 21 | 2016 | 5 | ACM
S67 | J | 10 | 18 | 2015 | 5 | SpringerLink
S68 | C | 0 | 33 | 2012 | 5 | IEEE Xplore
S69 | C | 5 | 2 | 2016 | 0 | IEEE Xplore
S70 | C | 5 | 3 | 2017 | 10 | IEEE Xplore
S71 | C | 5 | 10 | 2012 | 5 | IEEE Xplore
S72 | C | 5 | 24 | 2015 | 5 | IEEE Xplore
S73 | J | 0 | 57 | 2012 | 10 | ACM
S74 | C | 5 | 12 | 2014 | 5 | IEEE Xplore
S75 | C | 0 | 6 | 2015 | 0 | IEEE Xplore
S76 | J | 10 | 62 | 2015 | 10 | IEEE Xplore
S77 | C | 5 | 52 | 2010 | 10 | IEEE Xplore
S78 | C | 0 | 12 | 2015 | 5 | IEEE Xplore
S79 | J | 10 | 1 | 2018 | 10 | IEEE Xplore
S80 | C | 0 | 0 | 2015 | 0 | ACM
S81 | J | 0 | 4 | 2015 | 0 | JoCCASA
S82 | C | 10 | 14 | 2013 | 5 | IEEE Xplore
S83 | J | 10 | 80 | 2014 | 10 | IEEE Xplore
S84 | C | 5 | 4 | 2015 | 0 | IEEE Xplore
S85 | C | 5 | 6 | 2015 | 0 | IEEE Xplore
S86 | C | 5 | 8 | 2016 | 0 | IEEE Xplore
S87 | C | 0 | 2 | 2016 | 0 | IEEE Xplore
S88 | C | 0 | 24 | 2014 | 5 | IEEE Xplore

J: Journal, C: Conference

CORE-ERA http://portal.core.edu.au

JCR https://www.recursoscientificos.fecyt.es/factor/

# Reporting
## 5. Taxonomy of QoS metrics for cloud services {#clasificacion}
In this subsection, is shown the taxonomy of metrics for cloud services. The classification was done using the data extraction criteria. 

 1.<a href ="./images/modelo.png"> Taxonomy of quality metrics metamodel </a>
 2.<a href ="./images/taxonomy.png"> Taxonomy of quality metrics for cloud services summary</a> 
 3.<a href ="./files/TaxonomyQualityMetrics.xlsx"> Taxonomy of quality metrics for cloud services </a>

NOTE: In order to visualize the reports, please enable de _Power Pivot_ and _Power View_ complements of Excel.

<a href ="https://support.office.com/en-us/article/Start-the-Power-Pivot-add-in-for-Excel-a891a66d-36e3-43fc-81e8-fc4798f39ea8"> How to enable Excel complements


## Support or Contact 

Having trouble with Pages or any questions or suggestions? Please, contact us by email 
