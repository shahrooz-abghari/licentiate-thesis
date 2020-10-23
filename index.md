<!--h3 style="text-align:center;color:#606c71;"><b>Licentiate Thesis</b></h3-->
<!--h1 style="text-align:left;color:#606c71;margin-bottom: 0px;">Outlier Detection Analysis:</h1>
<h2 style="text-align:left;color:#606c71;margin-top: 2px;">Approaches for Identifying Deviating Behaviors in Real-world</h2-->
**Abstract**
<p align="justify">Outlier detection is studied and applied in many domains. Outliers arise due to different reasons such as fraudulent activities, structural defects, health problems, and mechanical issues. The detection of outliers is a challenging task that can reveal system faults, fraud, and save people's lives. Outlier detection techniques are often domain-specific. The main challenge in outlier detection relates to modelling the normal behaviour in order to identify abnormalities. The choice of model is important, i.e., an unsuitable data model can lead to poor results. This requires a good understanding and interpretation of the data, the constraints, and requirements of the domain problem. Outlier detection is largely an unsupervised problem due to unavailability of labeled data and the fact that labeled data is expensive.</p>

<p align="justify">In this thesis, we study and apply a combination of both machine learning and data mining techniques to build data-driven and domain-oriented outlier detection models. We focus on three real-world application domains: maritime surveillance, district heating, and online media and sequence datasets. We show the importance of data preprocessing as well as feature selection in building suitable methods for data modelling. We take advantage of both supervised and unsupervised techniques to create hybrid methods.</p>

<p align="justify">More specifically, we propose a rule-based anomaly detection system using open data for the maritime surveillance domain. We exploit sequential pattern mining for identifying contextual and collective outliers in online media data. We propose a minimum spanning tree clustering technique for detection of groups of outliers in online media and sequence data. We develop a few higher order mining approaches for identifying manual changes and deviating behaviours in the heating systems at the building level. The proposed approaches are shown to be capable of explaining the underlying properties of the detected outliers. This can facilitate domain experts in narrowing down the scope of analysis and understanding the reasons of such anomalous behaviours. We also investigate the reproducibility of the proposed models in similar application domains.</p>

**PhD dissertation description and author contribution**
<p align="justify">This thesis consists of seven papers. In Paper I, the author has been one of the main drivers. While in the next six papers, he has been the main driver. The studies in all papers have been developed and designed under the guidance of the supervisors and domain experts. The formatting of the published papers included in this thesis has been changed to achieve a consistent style.</p>

The final version of the dissertation can be downloaded as a <a href="./doc/thesis_final.pdf">[PDF]</a> (version: 2020-10-23).</br>
The complete dissertation can be downloaded as a <a href="./doc/thesis.pdf">[PDF]</a> (version: 2020-10-12).

**Included papers**
<ol>
<li>
<p align="justify">Kazemi, S., <b>Abghari, S.</b>, Lavesson, N., Johnson, H., & Ryman, P. "Open data for anomaly detection in maritime surveillance". <i>Expert Systems with Applications</i>, (40)14 (2013), pp. 5719-5729. DOI:<a href="https://doi.org/10.1016/j.eswa.2013.04.029" target="_blank">10.1016/J.ESWA.2013.04.029</a> - 
<strong><a href="https://www.sciencedirect.com/science/article/pii/S0957417413002765" target="_blank">[ScienceDirect]</a></strong> - <a href="./doc/paper1.pdf">[PDF]</a></p>
  
<button id="b1" class="unstyled-button"  onclick="toggle('a1');update_button('b1')"><u>Abstract</u></button>
<div style="display:none" id="a1">
  <p align="justify">Maritime surveillance has received increased attention from a civilian perspective in recent years. Anomaly detection is one of many techniques available for improving the safety and security in this domain. Maritime authorities use confidential data sources for monitoring the maritime activities; however, a paradigm shift on the Internet has created new open sources of data. We investigate the potential of using open data as a complementary resource for anomaly detection in maritime surveillance. We present and evaluate a decision support system based on open data and expert rules for this purpose. We conduct a case study in which experts from the Swedish coastguard participate to conduct a real-world validation of the system. We conclude that the exploitation of open data as a complementary resource is feasible since our results indicate improvements in the efficiency and effectiveness of the existing surveillance systems by increasing the accuracy and covering unseen aspects of maritime activities.</p>
</div>
<p>
  <br>
</p>  
</li>

<li>
<p align="justify"><b>Abghari, S.</b>, Boeva, V., Lavesson, N., Grahn, H., Gustafsson, J., & Shaikh, J. "Outlier detection for video session data using sequential pattern mining". In <i>Association for Computing Machinery’s Special Interest Group on Knowledge Discovery and Data Mining: Workshop On Outlier Detection De-constructed</i>, 2018, London, UK.
<strong><a href="https://www.andrew.cmu.edu/user/lakoglu/odd/index.html" target="_blank">[ODD v5.0 Workshop]</a></strong> - <a href="./doc/paper2.pdf">[PDF]</a></p>

<button id="b2" class="unstyled-button"  onclick="toggle('a2');update_button('b2')"><u>Abstract</u></button>
<div style="display:none" id="a2">
<p align="justify">The growth of Internet video and over-the-top transmission techniques has enabled online video service providers to deliver high quality video content to viewers. To maintain and improve the quality of experience, video providers need to detect unexpected issues that can highly affect the viewers’ experience. This requires analyzing massive amounts of video session data in order to find unexpected sequences of events. In this paper we combine sequential pattern mining and clustering to discover such event sequences. The proposed approach applies sequential pattern mining to find frequent patterns by considering contextual and collective outliers. In order to distinguish between the normal and abnormal behavior of the system, we initially identify the most frequent patterns. Then a clustering algorithm is applied on the most frequent patterns. The generated clustering model together with Silhouette Index are used for further analysis of less frequent patterns and detection of potential outliers. Our results show that the proposed approach can detect outliers at the system level.</p>
</div>
<p>
  <br>
</p>  
</li>

<li>
<p align="justify"><b>Abghari, S.</b>, Boeva, V., Lavesson, N., Grahn, H., Ickin, S., and Gustafsson, J. "A minimum spanning tree clustering approach for outlier detection in event sequences". In <i>2018 17th IEEE International Conference on Machine Learning and Applications (ICMLA)</i> (pp. 1123-1130). DOI: <a href="https://doi.org/10.1109/ICMLA.2018.00182" target="_blank">10.1109/ICMLA.2018.00182</a> - 
<strong><a href="https://ieeexplore.ieee.org/abstract/document/8614207" target="_blank">[IEEE]</a></strong> - <a href="./doc/paper3.pdf">[PDF]</a></p>

<button id="b3" class="unstyled-button"  onclick="toggle('a3');update_button('b3')"><u>Abstract</u></button>
<div style="display:none" id="a3">
<p align="justify">Outlier detection has been studied in many domains. Outliers arise due to different reasons such as mechanical issues, fraudulent behavior, and human error. In this paper, we propose an unsupervised approach for outlier detection in a sequence dataset. The proposed approach combines sequential pattern mining, cluster analysis and a minimum spanning tree algorithm in order to identify clusters of outliers. Initially, the sequential pattern mining is used to extract frequent sequential patterns. Next the extracted patterns are clustered into groups of similar patterns. Finally the minimum spanning tree algorithm is used to find groups of outliers. The proposed approach has been evaluated on two different real datasets, i.e., smart meter data and video session data. The obtained results have shown that our approach can be applied to narrow down the space of events to a set of potential outliers and facilitate domain experts in further analysis and identification of system level issues.</p>
</div>
<p>
  <br>
</p>  
</li>

<li>
<p align="justify"><b>Abghari, S.</b>, Garcia-Martin, E., Johansson, C., Lavesson, N., & Grahn, H. "Trend analysis to automatically identify heat program changes". <i>Energy Procedia</i>, 116 (2017), pp. 407-415. DOI:<a href="https://doi.org/10.1016/j.egypro.2017.05.088" target="_blank">10.1016/J.EGYPRO.2017.05.088</a> - 
<strong><a href="https://www.sciencedirect.com/science/article/pii/S1876610217322956" target="_blank">[ScienceDirect]</a></strong> - <a href="./doc/paper4.pdf">[PDF]</a></p>
<p>The paper was presented at the <i> 2016 15th International Symposium on District Heating and Cooling</i>, Seoul, Korea.</p>

<button id="b4" class="unstyled-button"  onclick="toggle('a4');update_button('b4')"><u>Abstract</u></button>
<div style="display:none" id="a4">
  <p align="justify">The aim of this study is to improve the monitoring and controlling of heating systems located at customer buildings through the use of a decision support system. To achieve this, the proposed system applies a two-step classifier to detect manual changes of the temperature of the heating system. We apply data from the Swedish company NODA, active in energy optimization and services for energy efficiency, to train and test the suggested system. The decision support system is evaluated through an experiment and the results are validated by experts at NODA. The results show that the decision support system can detect changes within three days after their occurrence and only by considering daily average measurements.</p>
</div>
<p>
  <br>
</p>  
</li>

<li>
<p align="justify"><b>Abghari, S.</b>, Boeva, V., Brage, J., & Johansson, C. "District heating substation behaviour modelling for annotating the performance. In <i>Cellier P., Driessens K. (eds) Machine Learning and Knowledge Discovery in Databases. ECML PKDD 2019. Communications in Computer and Information Science</i>, vol 1168. Springer, Cham. DOI: <a href="https://doi.org/10.1007/978-3-030-43887-6_1" target="_blank">10.1007/978-3-030-43887-6_1</a> - <strong><a href="https://link.springer.com/chapter/10.1007/978-3-030-43887-6_1" target="_blank">[Springer]</a></strong> - <a href="./doc/paper5.pdf">[PDF]</a></p>
  
<button id="b5" class="unstyled-button" onclick="toggle('a5');update_button('b5')"><u>Abstract</u></button>
<div style="display:none" id="a5">
  <p align="justify">In this ongoing study, we propose a higher order data mining approach for modelling district heating (DH) substations’ behaviour and linking operational behaviour representative profiles with different performance indicators. We initially create substation’s operational behaviour models by extracting weekly patterns and clustering them into groups of similar patterns. The built models are further analyzed and integrated into an overall substation model by applying consensus clustering. The different operational behaviour profiles represented by the exemplars of the consensus clustering model are then linked to performance indicators. The labelled behaviour profiles are deployed over the whole heating season to derive diverse insights about the substation’s performance. The results show that the proposed method can be used for modelling, analyzing and understanding the deviating and sub-optimal DH substation’s behaviours.</p>
</div>
<p>
  <br>
</p>  
</li>

<li>
<p align="justify"><b>Abghari, S.</b>, Boeva, V., Brage, J., & Grahn, H. "Multi-view clustering analyses for district heating substations". In <i>2020 9th International Conference on Data Science, Technology and Applications (DATA).</i> vol 1. SciTePress, ISBN: <a href="https://www.scitepress.org/ProceedingsDetails.aspx?ID=3AJl2lT2kdc=&t=1" target="_blank"> 978-989-758-440-4</a>, pp 158-168. DOI: <a href="https://www.scitepress.org/PublicationsDetail.aspx?ID=AKru4e1EjUI=&t=1" target="_blank"> 10.5220/0009780001580168</a> - <strong><a href="https://www.scitepress.org/PublicationsDetail.aspx?ID=AKru4e1EjUI=&t=1" target="_blank">[SciTePress]</a></strong> - <a href="./doc/paper6.pdf">[PDF]</a></p>
  
<button id="b6" class="unstyled-button"  onclick="toggle('a6');update_button('b6')"><u>Abstract</u></button>
<div style="display:none" id="a6">
    <p align="justify">In this study, we propose a multi-view clustering approach for mining and analysing multi-view network datasets. The proposed approach is applied and evaluated on a real-world scenario for monitoring and analysing district heating (DH) network conditions and identifying substations with sub-optimal behaviour. Initially, geographical locations of the substations are used to build an approximate graph representation of the DH network. Two different analyses can further be applied in this context: step-wise and parallel-wise multi-view clustering. The step-wise analysis is meant to sequentially consider and analyse substations with respect to a few different views. At each step, a new clustering solution is built on top of the one generated by the previously considered view, which organizes the substations in a hierarchical structure that can be used for multi-view comparisons. The parallel-wise analysis on the other hand, provides the opportunity to analyse substations with regards to two different views in parallel. Such analysis is aimed to represent and identify the relationships between substations by organizing them in a bipartite graph and analysing the substations’ distribution with respect to each view. The proposed data analysis and visualization approach arms domain experts with means for analysing DH network performance. In addition, it will facilitate the identification of substations with deviating operational behaviour based on comparative analysis with their closely located neighbours.</p>
</div>
<p>
<br>
</p>  
</li>

<li>
<p align="justify"><b>Abghari, S.</b>, Boeva, V., Brage, J., & Grahn, H. "Higher order mining approach for analysis of real-world datasets". <i>Submitted for journal publication,</i> - (The paper is an extention of <a href="#p-10">Paper 10</a>.). 
</p>

<button id="b7" class="unstyled-button"  onclick="toggle('a7');update_button('b7')"><u>Abstract</u></button>
<div style="display:none" id="a7">
<p align="justify">In this study, we propose a higher order mining approach that can be used for analysis of real-world datasets. The approach can be used for monitoring and identifying deviating operational behaviour of the studied phenomenon in the absence of prior knowledge about data. The proposed approach consists of several different data analysis techniques such as sequential pattern mining, clustering analysis, consensus clustering and minimum spanning tree (MST). Initially, clustering analysis is performed on the extracted patterns to model the behaviour modes of the studied phenomenon for a given time interval. The built clustering models corresponding to every two consecutive time intervals can further be assessed for mining changes in the monitored behaviour. In case some significant difference is observed, further analysis is performed by integrating the built models into a consensus clustering and applying an MST for identifying deviating behaviours. The validity and potential of the proposed approach has been demonstrated on a real-world dataset originating from a network of district heating (DH) substations. The obtained results show that our approach is capable of detecting deviating and sub-optimal behaviours of the DH substations.</p>
</div>
<p>
  <br>
</p>  
</li>
</ol>

**Related papers**

<ol start="8">

<li>
<p align="justify"><b>Abghari, S.</b>, Boeva, V., Lavesson, Gustafsson, J., Shaikh, J., & Grahn, H. "Anomaly Detection in Video Session Data". In <i>2017 5th Swedish Workshop on Data Science (SweDS)</i>. <strong><a href="https://cse.gu.se/english/sweds2017" target="_blank">[SweDS 2017 Workshop]</a></strong></p>

<button id="b8" class="unstyled-button" onclick="toggle('a8');update_button('b8')"><u>Abstract</u></button>
<div style="display:none" id="a8">
<p align="justify">Online video service providers (OVSPs) continuously improve their services to satisfy the subscribers’ expectation. This requires analysing massive amount of log files and different video event types. We use sequential pattern mining to analyse video data sequences to detect unexpected issues that can highly affect the subscribers’ experience. The video session data has temporal order and contains detailed information regarding which video is requested, what type of device is used for watching the video, and the list of occurrences of all event types.</p>
<p align="justify">The initial assumption with using sequential pattern mining is that most frequent sequential patterns (MFSPs) can be considered as normal system behaviour, while the others, non-most frequent sequential patterns (NMFSPs), can be potential anomalies. By performing clustering analysis, the MFSPs can be grouped based on their similarities. Finally, NMFSPs can be evaluated by the created model. The goodness-of-fit of the NMFSPs can be identified by applying an internal cluster validation measure such as Silhouette Index (SI).</p>
<p align="justify">The proposed method has six steps as follows:</p>
<ol><li><p align="justify">The video sessions are divided into equal-sized segments, e.g., daily.</p></li>
<li><p align="justify">The PrefixSpan algorithm is used to extract frequent sequential patterns. Such sequential patterns can lead us to detect collective anomalies, i.e., a collection of related data points (event types) assumed to be anomalous based on their occurrences together.</p></li>
<li><p align="justify">The extracted frequent sequential patterns are mapped with the video sessions and extra information related to date and time such as workday or weekend for finding contextual anomalies will be added to them.</p></li>
<li><p align="justify">The frequent sequential patterns are divided into two groups based on how frequent they are. Those patterns that occurred in more than one segment are named MFSPs with initial assumption that they are normal. The NMFSPs, on the other hand can be assumed as potentially anomalies.</p></li>
<li><p align="justify">MFSPs are clustered into partitions based on their similarities.</p></li>
<li><p align="justify">The clustering model built in the previous step is used to analyse the NMFSPs by matching each pattern into a cluster. To evaluate the goodness-of-fit of each NMFSP, SI is used. The SI has a range of [-1, 1]. A score 1 shows the NMFSP is assigned to a correct cluster. When score is about zero, this indicates that the NMFSP is on the decision boundary between two neighbouring clusters. Finally, a score close to -1 indicates the pattern is misclassified and assigned to an erroneous cluster, i.e., such NMFSP can be identified as anomaly.</p></li></ol>
<p align="justify">The proposed approach is applied on two months (October-November 2016) of data for a large OVSP company. The results show an increase in the number of quality adaptation events for many video sessions in both months. Such surge in the number of video streaming performance events during video sessions can be related to the fact that many viewers simultaneously try to watch the same video (e.g., a special live show) or an issue at the system level. In both cases, additional analysis by the company experts is needed for better understanding and interpretation of the results.</p>
</div>
<p>
  <br>
</p>
</li>

<li>
<p align="justify"><b>Abghari, S.</b>, Boeva, V., Lavesson, N., Grahn, H., Ickin, S., & Gustafsson, J. "A Minimum Spanning Tree Clustering Approach for Mining Sequence Datasets". In <i>2018 6th Swedish Workshop on Data Science (SweDS)</i>. <strong><a href="http://sweds2018.cs.umu.se/" target="_blank">[SweDS 2018 Workshop]</a></strong></p>

<button id="b9" class="unstyled-button" onclick="toggle('a9');update_button('b9')"><u>Abstract</u></button>
<div style="display:none" id="a9">
<p align="justify">We propose an unsupervised approach for outlier detection in a sequence dataset. Outlier detection has been studied in many domains. Outliers arise due to different reasons such as mechanical issues, fraudulent behavior, and human error. Our approach consists of a preprocessing step and three main steps: 1) Sequential patterns mining, 2) Frequent sequential pattern clustering, and 3) Minimum spanning tree (MST) building and outlier detection analysis.</p>
<p align="justify">In the preprocessing step, Data segmentation, data is partitioned into equal-sized segments in order to identify sequential patterns. The first step, Sequential patterns mining, concerns the extraction of frequent sequential patterns and mapping them with records of a sequence dataset. The PrefixSpan algorithm is used to find frequent sequential patterns from each segment. The extracted patterns can lead us to find collective outliers. Furthermore, the extracted patterns are mapped with the source they come from. This can help us to find additional information about the patterns such as pattern frequency and its occurrence time. The latter is useful for finding a contextual outliers. In the second step, Frequent sequential pattern clustering, the selected patterns are clustered by applying affinity propagation (AP) algorithm. AP can estimate the number of clusters from data. In the third step, Minimum spanning tree building and outlier detection analysis, the exemplars of the clusters are used for building a complete weighted graph, where vertices of the graph are the exemplars and edges are the distance between them. The aim is to determine a subset of edges that connect all the vertices together without any cycles that has the minimum total edge weight. In order to identify outliers, the longest edge of the tree is removed. The constructed MST will be replaced by the created sub-trees. The sub-trees are ranked from smallest to largest based on the number of items they match within the sequence dataset. Here the smallest subtrees can be regarded as outliers.</p>
<p align="justify">The proposed approach can be used to facilitate the domain experts in identification of outliers. Building the minimum spanning tree on top the clustering solution can lead to identifying clusters of outliers. This can reduce the time complexity of the proposed approach. The proposed approach has been evaluated in two different experimental scenarios. Namely, it has been applied on two different sequence datasets: smart meter data and video session data. Both datasets contain sequences of event types that either shows the operational status of a smart meter or the current action that takes place in a viewer’s video session. The results of the experiments on the smart meter data are more comprehensible compared to the video session data. The main reason is the fact that the event types in smart meters are explicitly detailed, explaining the status of the devices. However, in video session data the event types are general which requires more investigation and experts’ knowledge in order to detect video sessions with quality issues. The validation of the results on video session data by the domain experts showed that 67% of the labeled sessions by the proposed approach were correct.</p>
</div>
<p>
  <br>
</p>
</li>


<li>
<p align="justify" id="p-10"><b>Abghari, S.</b>, Boeva, V., Brage, J., & Grahn, H. "Higher order mining for monitoring district seating substations". In <i>2019 6th IEEE International Conference on Data Science and Advanced Analytics (DSAA)</i> (pp. 382-391). DOI: <a href="https://doi.org/10.1109/DSAA.2019.00053" target="_blank">10.1109/DSAA.2019.00053</a> - 
<strong><a href="https://ieeexplore.ieee.org/document/8964173" target="_blank">[IEEE]</a></strong> - <a href="./doc/paper10.pdf">[PDF]</a>
</p> 
  
<button id="b10" class="unstyled-button"  onclick="toggle('a10');update_button('b10')"><u>Abstract</u></button>
<div style="display:none" id="a10">
<p align="justify">We propose a higher order mining (HOM) approach for modelling, monitoring and analyzing district heating (DH) substations' operational behaviour and performance. HOM is concerned with mining over patterns rather than primary or raw data. The proposed approach uses a combination of different data analysis techniques such as sequential pattern mining, clustering analysis, consensus clustering and minimum spanning tree (MST). Initially, a substation's operational behaviour is modeled by extracting weekly patterns and performing clustering analysis. The substation's performance is monitored by assessing its modeled behaviour for every two consecutive weeks. In case some significant difference is observed, further analysis is performed by integrating the built models into a consensus clustering and applying an MST for identifying deviating behaviours. The results of the study show that our method is robust for detecting deviating and sub-optimal behaviours of DH substations. In addition, the proposed method can facilitate domain experts in the interpretation and understanding of the substations' behaviour and performance by providing different data analysis and visualization techniques.</p>
</div>
<p>
  <br>
</p>  
</li>

<li>
<p align="justify"><b>Abghari, S.</b>, Boeva, V., Brage, J., Johansson, C., Grahn, H., & Lavesson, N. "Monitoring district heating substations via clustering analysis". In <i>2019 31st Swedish AI
Society Workshop (SAIS)</i>. <strong><a href="https://sais2019.cs.umu.se/program/" target="_blank">[SAIS 2019 Workshop]</a>
</strong> - <a href="./doc/paper11.pdf">[PDF]</a></p> 
  
<button id="b11" class="unstyled-button"  onclick="toggle('a11');update_button('b11')"><u>Abstract</u></button>
<div style="display:none" id="a11">
<p align="justify">In this paper, we describe an ongoing study for detecting deviating behaviour of district heating (DH) substations. We propose an approach for modelling, monitoring and analyzing the DH substations operational behaviour on a weekly basis. The proposed approach combines sequential pattern mining together with clustering analysis and minimum spanning tree to identify outliers. Our goal is to detect changes in operational behaviour of substations that can decrease their efficiency.</p>
</div>
<p>
  <br>
</p>  
</li>

<li>
<p align="justify">Eghbalian, A., <b>Abghari, S.</b>, Boeva, V., & Basiri, F. "Multi-view data mining approach for behaviour analysis ofsmart control valve". In <i>2020 19th IEEE InternationalConference on Machine Learning and Applications</i>, December 14-17, 2020, Miami, Florida (Accepted) - <a href="./doc/paper12.pdf">[PDF]</a></p>

<button id="b12" class="unstyled-button"  onclick="toggle('a12');update_button('b12')"><u>Abstract</u></button>
<div style="display:none" id="a12">
<p align="justify">In this study, we propose a multi-view data analysis approach that can be used for modelling and monitoring smart control valve system behaviour. The proposed approach consists of four distinctive steps: (i) multi-view interpretation of the available data attributes by separating them into several representations (views), e.g., operational parameters, contextual factors, and performance indicators; (ii) modelling different control valve system operating modes by clustering analyses of the operational data view; (iii) annotating each operating mode (cluster) by using the remaining views (i.e., contextual and system performance data); (iv) context-aware monitoring of the control valve system operating behaviour by applying the built model. In addition, the data points (daily profiles) observed during the monitoring can be annotated by comparing them with the known typical behavioural modes. This information can be further analysed and used for continuous updating and improvement of the model.</p>

<p align="justify">The potential of the proposed approach has been evaluated and demonstrated on real-world sensor data originating from a company in the smart building domain. The obtained results show the robustness of the proposed approach in modelling, analysing, and monitoring the control valve system behaviour.</p>
</div>
<p>
  <br>
</p>  
</li>

</ol>
