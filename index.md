<!--h3 style="text-align:center;color:#606c71;"><b>Licentiate Thesis</b></h3-->
<h1 style="text-align:left;color:#606c71;"><b>Outlier Detection Analysis:</b></h1> 
<h2 style="text-align:left;color:#606c71;"><b>Approaches for Identifying Deviating Behaviors in Real-world</b></h2>

**Abstract**
<p align="justify">This thesis explores the data modeling for outlier detection techniques in three different application domains: <i>maritime surveillance</i>, <i>district heating</i>, and <i>online media and sequence datasets</i>. The proposed models are evaluated and validated under different experimental scenarios, taking into account specific characteristics and setups of the different domains.</p> 

<p align="justify">Outlier detection has been studied and applied in many domains. Outliers arise due to different reasons such as fraudulent activities, structural defects, health problems, and mechanical issues. The detection of outliers is a challenging task that can reveal system faults, fraud, and save people's lives. Outlier detection techniques are often  domain-specific. The main challenge in outlier detection relates to modeling the normal behavior in order to identify abnormalities. The choice of model is important, i.e., an incorrect choice of data model can lead to poor results. This requires a good understanding and interpretation of the data, the constraints, and the requirements of the problem domain. Outlier detection is largely an unsupervised problem due to unavailability of labeled data and the fact that labeled data is expensive.</p>

<p align="justify">We have studied and applied a combination of both machine learning and data mining techniques to build data-driven and domain-oriented outlier detection models. We have shown the importance of data preprocessing as well as feature selection in building suitable methods for data modeling. We have taken advantage  of both supervised and unsupervised techniques to create hybrid methods. For example, we have proposed a rule-based outlier detection system based on <i>open data</i> for the maritime surveillance domain. Furthermore, we have combined cluster analysis and regression to identify manual changes in the heating systems at the building level. Sequential pattern mining for identifying contextual and collective outliers in online media data have also been exploited. In addition, we have proposed a minimum spanning tree clustering technique for detection of groups of outliers in online media and sequence data. The proposed models have been shown to be capable of explaining the underlying properties of the detected outliers. This can facilitate domain experts in narrowing down the scope of analysis and understanding the reasons of such anomalous behaviors. We have also investigated the reproducibility of the proposed models in similar application domains.</p>

**Thesis description and author contribution**
<p align="justify"></p>

[PDF]()

**Included papers**
<ul>
<li>
<p align="justify">Kazemi, S., <b>Abghari, S.</b>, Lavesson, N., Johnson, H., & Ryman, P. "Open data for anomaly detection in maritime surveillance". <i>Expert Systems with Applications</i>, (40)14 (2013), pp. 5719-5729. DOI:<a href="https://doi.org/10.1016/j.eswa.2013.04.029">10.1016/J.ESWA.2013.04.029</a> - 
<strong><a href="https://www.sciencedirect.com/science/article/pii/S0957417413002765">[sciencedirect]</a></strong></p>
  
<button id="b1" class="unstyled-button"  onclick="toggle('a1');update_button('b1')"><u>Abstract</u></button>
<div style="display:none" id="a1">
  <p align="justify">Maritime surveillance has received increased attention from a civilian perspective in recent years. Anomaly detection is one of many techniques available for improving the safety and security in this domain. Maritime authorities use confidential data sources for monitoring the maritime activities; however, a paradigm shift on the Internet has created new open sources of data. We investigate the potential of using open data as a complementary resource for anomaly detection in maritime surveillance. We present and evaluate a decision support system based on open data and expert rules for this purpose. We conduct a case study in which experts from the Swedish coastguard participate to conduct a real-world validation of the system. We conclude that the exploitation of open data as a complementary resource is feasible since our results indicate improvements in the efficiency and effectiveness of the existing surveillance systems by increasing the accuracy and covering unseen aspects of maritime activities.</p>
</div>
<p>
  <br>
</p>  
</li>

<li>
<p align="justify"><b>Abghari, S.</b>, Garcia-Martin, E., Johansson, C., Lavesson, N., & Grahn, H. "Trend analysis to automatically identify heat program changes". <i>Energy Procedia</i>, 116 (2017), pp. 407-415. DOI:<a href="https://doi.org/10.1016/j.egypro.2017.05.088">10.1016/J.EGYPRO.2017.05.088</a> - 
<strong><a href="https://www.sciencedirect.com/science/article/pii/S1876610217322956">[sciencedirect]</a></strong></p>
<p>Also published in: <i>The 15th Int'l Symp. on District Heating and Cooling</i>, 2016, Seoul, Korea.</p>

<button id="b2" class="unstyled-button"  onclick="toggle('a2');update_button('b2')"><u>Abstract</u></button>
<div style="display:none" id="a2">
  <p align="justify">The aim of this study is to improve the monitoring and controlling of heating systems located at customer buildings through the use of a decision support system. To achieve this, the proposed system applies a two-step classifier to detect manual changes of the temperature of the heating system. We apply data from the Swedish company NODA, active in energy optimization and services for energy efficiency, to train and test the suggested system. The decision support system is evaluated through an experiment and the results are validated by experts at NODA. The results show that the decision support system can detect changes within three days after their occurrence and only by considering daily average measurements.</p>
</div>
<p>
  <br>
</p>  
</li>

<li>
<p align="justify"><b>Abghari, S.</b>, Boeva, V., Lavesson, N., Grahn, H., Gustafsson, J., & Shaikh, J. "Outlier detection for video session data using sequential pattern mining". In <i>Association for Computing Machinery’s Special Interest Group on Knowledge Discovery and Data Mining: Workshop On Outlier Detection De-constructed</i>, 2018, London, UK.
<a href="https://www.andrew.cmu.edu/user/lakoglu/odd/index.html">[ODD v5.0 Workshop]</a> - 
<strong><a href="./doc/paper3.pdf">[PDF]</a></strong></p>

<button id="b3" class="unstyled-button"  onclick="toggle('a3');update_button('b3')"><u>Abstract</u></button>
<div style="display:none" id="a3">
<p align="justify">The growth of Internet video and over-the-top transmission techniques has enabled online video service providers to deliver high quality video content to viewers. To maintain and improve the quality of experience, video providers need to detect unexpected issues that can highly affect the viewers’ experience. This requires analyzing massive amounts of video session data in order to find unexpected sequences of events. In this paper we combine sequential pattern mining and clustering to discover such event sequences. The proposed approach applies sequential pattern mining to find frequent patterns by considering contextual and collective outliers. In order to distinguish between the normal and abnormal behavior of the system, we initially identify the most frequent patterns. Then a clustering algorithm is applied on the most frequent patterns. The generated clustering model together with Silhouette Index are used for further analysis of less frequent patterns and detection of potential outliers. Our results show that the proposed approach can detect outliers at the system level.</p>
</div>
<p>
  <br>
</p>  
</li>

<li>
<p align="justify"><b>Abghari, S.</b>, Boeva, V., Lavesson, N., Grahn, H., Ickin, S., and Gustafsson, J. "A Minimum Spanning Tree Clustering Approach for Outlier Detection in Event Sequences" In <i> 2018 17th IEEE International Conference on Machine Learning and Applications (ICMLA)</i>, (pp. 1123-1130). DOI: <a href="https://doi.org/10.1109/ICMLA.2018.00182">10.1109/ICMLA.2018.00182</a> - 
<strong><a href="https://ieeexplore.ieee.org/abstract/document/8614207">[IEEE]</a></strong></p>

<button id="b4" class="unstyled-button"  onclick="toggle('a4');update_button('b4')"><u>Abstract</u></button>
<div style="display:none" id="a4">
<p align="justify">Outlier detection has been studied in many domains. Outliers arise due to different reasons such as mechanical issues, fraudulent behavior, and human error. In this paper, we propose an unsupervised approach for outlier detection in a sequence dataset. The proposed approach combines sequential pattern mining, cluster analysis and a minimum spanning tree algorithm in order to identify clusters of outliers. Initially, the sequential pattern mining is used to extract frequent sequential patterns. Next the extracted patterns are clustered into groups of similar patterns. Finally the minimum spanning tree algorithm is used to find groups of outliers. The proposed approach has been evaluated on two different real datasets, i.e., smart meter data and video session data. The obtained results have shown that our approach can be applied to narrow down the space of events to a set of potential outliers and facilitate domain experts in further analysis and identification of system level issues.</p>
</div>
<p>
  <br>
</p>  
</li>

<li>
<p align="justify"><b>Abghari, S.</b>, Boeva, V., Brage, J., Johansson, C., Grahn, H., & Lavesson, N. "Higher order mining for monitoring district seating substations". In <i> 2019 6th IEEE International Conference on Data Science and Advanced Analytics (DSAA)</i> (pp. 382-391). DOI: <a href="https://doi.org/10.1109/DSAA.2019.00053">10.1109/DSAA.2019.00053</a> - 
<strong><a href="https://ieeexplore.ieee.org/document/8964173">[IEEE]</a></strong>
</p>
  
<button id="b5" class="unstyled-button"  onclick="toggle('a5');update_button('b5')"><u>Abstract</u></button>
<div style="display:none" id="a5">
  <p align="justify">We propose a higher order mining (HOM) approach for modelling, monitoring and analyzing district heating (DH) substations' operational behaviour and performance. HOM is concerned with mining over patterns rather than primary or raw data. The proposed approach uses a combination of different data analysis techniques such as sequential pattern mining, clustering analysis, consensus clustering and minimum spanning tree (MST). Initially, a substation's operational behaviour is modeled by extracting weekly patterns and performing clustering analysis. The substation's performance is monitored by assessing its modeled behaviour for every two consecutive weeks. In case some significant difference is observed, further analysis is performed by integrating the built models into a consensus clustering and applying an MST for identifying deviating behaviours. The results of the study show that our method is robust for detecting deviating and sub-optimal behaviours of DH substations. In addition, the proposed method can facilitate domain experts in the interpretation and understanding of the substations' behaviour and performance by providing different data analysis and visualization techniques.</p>
</div>
<p>
  <br>
</p>  
</li>

<li>
<p align="justify"><b>Abghari, S</b>. Boeva, V., Brage, J., & Grahn, H. "Multi-view clustering analyses for district heating substations". In <i> 2020 9th International Conference on Data Science, Technology and Applications (DATA 2020).</i> 
</p>
  
<button id="b6" class="unstyled-button"  onclick="toggle('a6');update_button('b6')"><u>Abstract</u></button>
<div style="display:none" id="a6">
    <p align="justify">In this study, we propose a multi-view clustering approach for mining and analysing multi-view network datasets. The proposed approach is applied and evaluated on a real-world scenario for monitoring and analysing district heating (DH) network conditions and identifying substations with sub-optimal behaviour. Initially, geographical locations of the substations are used to build an approximate graph representation of the DH network. Two different analyses can further be applied in this context: step-wise and parallel-wise multi-view clustering. The step-wise analysis is meant to sequentially consider and analyse substations with respect to a few different views. At each step, a new clustering solution is built on top of the one generated by the previously considered view, which organizes the substations in a hierarchical structure that can be used for multi-view comparisons. The parallel-wise analysis on the other hand, provides the opportunity to analyse substations with regards to two different views in parallel. Such analysis is aimed to represent and identify the relationships between substations by organizing them in a bipartite graph and analysing the substations’ distribution with respect to each view. The proposed data analysis and visualization approach arms domain experts with means for analysing DH network performance. In addition, it will facilitate the identification of substations with deviating operational behaviour based on comparative analysis with their closely located neighbours.</p>
</div>
<p>
<br>
</p>  
</li>

<li>
<p align="justify"><b>Abghari, S.</b>, 
</p>
  
<button id="b7" class="unstyled-button"  onclick="toggle('a7');update_button('b7')"><u>Abstract</u></button>
<div style="display:none" id="a7">
  <p align="justify"></p>
</div>
<p>
  <br>
</p>  
</li>

</ul>
