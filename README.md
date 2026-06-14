# Research Articles by Furkan Gözükara

A curated collection of research by Furkan Gözükara and collaborators, covering product search, record linkage, focused crawling, sentiment analysis, cyber forensics, human-computer interaction, and power-system optimization.

Repository: [MonsterMMORPG/ResearchArticles](https://huggingface.co/MonsterMMORPG/ResearchArticles/tree/main)

## Research Themes

- E-commerce search, comparison shopping, and product intelligence
- Product identity clustering, record linkage, and noisy data normalization
- Focused web crawling and large-scale data extraction
- Sentiment analysis for Turkish and English text
- Cyber forensics and evidentiary risk analysis
- Air-writing recognition and human-computer interaction
- Power-system optimization, Pareto analysis, and bio-inspired metaheuristics

## Timeline

_Sorted from latest to earliest._

### June 13, 2026 - [Implementation of Modified Effective Butterfly Optimizer in Solving Multi-Objective Pareto Optimal Power Flow Problem with Renewable Uncertainties](https://huggingface.co/MonsterMMORPG/ResearchArticles/resolve/main/Implementation_of_Modified_Effective_Butterfly_Optimizer_in_Solving_Multi-Objective_Pareto_Optimal_Power_Flow_Problem.pdf)

Journal article | Biomimetics, Vol. 11, No. 6, Article 418

Adapts the Modified Effective Butterfly Optimizer (MEBO) for multi-objective optimal power flow with renewable uncertainties, using optimized weighting, multiple Pareto archives, and compromise-solution metrics on IEEE 30- and 57-bus systems.

<details>
<summary><strong>Abstract</strong></summary>

The power flow problem is one of the most challenging tasks in power systems, affecting both generation cost and energy quality. Optimal power flow (OPF) further complicates this task by requiring the optimal adjustment of system variables and parameters. This paper adapts the Modified Effective Butterfly Optimizer (MEBO) to solve multi-objective optimal power flow (MOOPF) problems with the contribution of optimized weighting using multiple Pareto archives. MEBO is an advanced optimization algorithm that utilizes population reduction and parameter learning to guide subsequent searches for unconstrained problems. The proposed technique has been tested on IEEE 30 and 57 bus test systems, and the results have been compared with existing methods reported in the literature. In the paper, four single-objective functions, namely generator cost, active power loss, fuel emission, and voltage deviation, are used to construct four multi-objective (MO) problems: cost-loss, cost-voltage, cost-emission, and emission-loss. For the cost-emission case, the proposed MEBO achieved compromised solutions of 791.1951 USD/h fuel cost with 0.10873 ton/h emission and 801.8172 USD/h fuel cost with 0.10044 ton/h emission under different Pareto-based optimization metrics. In the emission-loss case, the algorithm obtained 0.20539 ton/h emission with 3.1403 MW/h power loss, demonstrating the effectiveness of the proposed approach in balancing conflicting objectives. The Pareto curves of MEBO in achieving MO problems are presented, along with the suggested compromised solutions acquired from the literature. In the literature, this is the first application of MEBO for solving MOOPF problems. The results demonstrate that MEBO performs better than most other alternatives; this shows potential for further improvements with respect to the MOOPF problem.

</details>

### January 29, 2025 - [Letter and Person Recognition in Freeform Air-Writing Using Machine Learning Algorithms](https://huggingface.co/MonsterMMORPG/ResearchArticles/resolve/main/Letter_and_Person_Recognition_in_Freeform_Air-Writing_Using_Machine_Learning_Algorithms.pdf)

Journal article | IEEE Access, Vol. 13

Presents a wearable-glove pipeline for freeform air-writing that jointly models letter recognition and writer recognition, with applications in education, authentication, and motion-based human-computer interaction.

<details>
<summary><strong>Abstract</strong></summary>

Air-writing is an emerging form of human-computer interaction that enables text entry through hand movements in the air. This paper explores air-writing-based person recognition alongside letter recognition to analyze the correlation between subjects and their writing styles. This analysis has potential applications in early childhood education for assessing cognitive and psychomotor skills, as well as in user authentication. A comprehensive framework for freeform air-writing analysis using a wearable glove is introduced, encompassing person and letter recognition, letter segmentation, feature extraction, and dataset generation. Unlike user authentication where person recognition depends on predefined content, such as a passcode or signature, person recognition here depends on the underlying writing style of the writer in free-form. The free-form air-writing indicates the user freedom to select any letter with any size (varying from a quarter to the full size of an A4 page) to write on the air. In the study, a dataset is also developed, containing the air-writing signals from the wearable glove, integrated with IMU sensors (gyroscope and accelerometer). Fourier and wavelet transforms are used to extract features and the performances of various machine learning algorithms, namely Decision Tree, Random-Forest, K-Nearest Neighbors, Support Vector Machine, Artificial Neural Networks, and SubSpace KNN, are comparatively studied. To the best of the authors’ knowledge, there is no study for person recognition from freeform air-writing letters through IMU sensors, and also there is no study using the Fourier and Wavelet features in this context. Furthermore, the study is also original due to its publicly available air-writing dataset on the Turkish alphabet and also applying various machine learning algorithms. The experimental results show that SubSpace KNN is superior to the others under the suggested parameter settings.

</details>

### March 2023 - [An Incremental Hierarchical Clustering Based System For Record Linkage In E-Commerce Domain](https://huggingface.co/MonsterMMORPG/ResearchArticles/resolve/main/An_Incremental_Hierarchical_Clustering_Based_System_For_Record_Linkage_In_E-Commerce_Domain.pdf)

Journal article | The Computer Journal, Vol. 66, No. 3

Introduces a dynamic hierarchical clustering system for e-commerce record linkage that groups identical products across websites without requiring labeled training data.

<details>
<summary><strong>Abstract</strong></summary>

In this study, a novel record linkage system for E-commerce products is presented. Our system aims to cluster the same products that are crawled from different E-commerce websites into the same cluster. The proposed system achieves a very high success rate by combining both semi-supervised and unsupervised approaches. Unlike the previously proposed systems in the literature, neither a training set nor structured corpora are necessary. The core of the system is based on Hierarchical Agglomerative Clustering (HAC); however, the HAC algorithm is modified to be dynamic such that it can efficiently cluster a stream of incoming new data. Since the proposed system does not depend on any prior data, it can cluster new products. The system uses bag-of-words representation of the product titles, employs a single distance metric, exploits multiple domain-based attributes and does not depend on the characteristics of the natural language used in the product records. To our knowledge, there is no commonly used tool or technique to measure the quality of a clustering task. Therefore in this study, we use ELKI (Environment for Developing KDD-Applications Supported by Index-Structures), an open-source data mining software, for performance measurement of the clustering methods; and show how to use ELKI for this purpose. To evaluate our system, we collect our own dataset and make it publicly available to researchers who study E-commerce product clustering. Our proposed system achieves 96.25% F-Measure according to our experimental analysis. The other state-of-the-art clustering systems obtain the best 89.12% F-Measure.

</details>

### November 8, 2021 - [Challenges and Possible Severe Legal Consequences of Application Users Identification from CNG-Logs](https://huggingface.co/MonsterMMORPG/ResearchArticles/resolve/main/Challenges_And_Possible_Severe_Legal_Consequences_Of_Application_Users_Identification_From_Cng-Logs.pdf)

Journal article | Forensic Science International: Digital Investigation, Vol. 39

Examines how carrier-grade NAT log analysis can misidentify users in criminal investigations and explains the resulting forensic and legal risks through real cases.

<details>
<summary><strong>Abstract</strong></summary>

Due to the increase in the use of Internet-connected devices and the limited number of available Internet Protocol Version 4 (IPv4) addresses, a system necessity that would share the same Internet Protocol (IP) address among multiple end-users emerged. These systems that will allow end-users to share the same IP address are commonly called Carrier-Grade Network (CGN) Address Translation (CGNAT). Even though the laws may vary among different countries, many of the current nations impose Internet Service Providers (ISPs) to keep internet users’ activity as logs. Usually, law enforcement is provided with the exact date, public IP address, and the public port number to detect cybercriminals. Unfortunately, though, when reverse-tracking CGN logs methodology is followed, while the precision of actor detection decreases, the false positive rate increases. Therefore, this methodology has significant issues and can cause innocent people to be treated as criminals. As a case study, this study investigated criminal cases in Turkey, where the defendants are accused of being part of a terrorist organization due to the use of a mobile chat application called ByLock. We explored incorrect usage of CGNAT records to detect users of a specific application and how it affected masses from a criminal perspective. In this paper, the dangers of such an approach will be investigated in-depth by providing an actual criminal case example from the ByLock cases. Furthermore, the paper also compares the reverse-tracking of CGNAT logs approach with the approach followed in another mobile chat application (EncroChat) in terms of cybercriminal mass investigations.

</details>

### July 2017 - [Efficient Feature Selection for Product Labeling over Unstructured Data](https://huggingface.co/MonsterMMORPG/ResearchArticles/resolve/main/Efficient_Feature_Selection_For_Product_Labeling_Over_Unstructured_Data.pdf)

Journal article | International Journal of Advanced Computer Science and Applications, Vol. 8, No. 7

Proposes a feature selection method for labeling identical products in noisy, unstructured web data and shows measurable gains in clustering performance.

<details>
<summary><strong>Abstract</strong></summary>

The paper introduces a novel feature selection algorithm for labeling identical products collected from online web resources. Product labeling is important for clustering similar or same products. Products blindly crawled over the web sources, such as online sellers, have unstructured data due to having features expressed in different representations and formats. Such data result in feature vectors whose representation is unknown and non-uniform in length. Thus, product labeling, as a challenging problem, needs efficient selection of features that best describe the products. In this paper, an efficient feature selection algorithm is proposed for product labeling problem. Hierarchical clustering is used with the state of the art similarity metrics to assess the performance of the proposed algorithm. The results show that the proposed algorithm increases the performance of product labeling significantly. Furthermore, the method can be applied to any clustering algorithm that works on unstructured data.

</details>

### January 2017 - [Focused Web Crawler Development Challenges: ECCrawler](https://huggingface.co/MonsterMMORPG/ResearchArticles/resolve/main/Focused_Web_Crawler_Development_Challenges_Eccrawler.pdf)

Journal article | International Journal of Computer Science and Engineering (IJCSE), Vol. 6, No. 1

Documents the design and engineering tradeoffs behind a .NET-based focused crawler for e-commerce sites, covering multithreading, exception handling, bandwidth usage, and performance tuning.

<details>
<summary><strong>Abstract</strong></summary>

Nowadays, the importance of focused web crawlers is more than any time before. As the web has become massive and spammy, it is now essential to have focused web crawlers that can crawl only the targeted websites and obtain the necessary information. Instead of relying on the available public general web crawlers, today, developing a focused web crawler for the targeted web pages is preferred to increase success of information retrieval. In this paper, the challenges encountered and the proposed solutions to attempt these problems are presented, while developing an original hand-crafted, full scale, robust and effective focused web crawler for E-commerce sites, named as EcCrawler, which is developed in C# programming language by using .NET 4.5 framework and MS-SQL Server 2014 database management system. Most of the crawling challenges have been discussed before in the literature, however in this paper, practical implementation and .NET framework based solutions that include thread pool initialization, exception handling, task parallelism, HTTP compression, duplicate web page resolution, number of concurrent connections to the same host, database communication, resource sharing between threads, etc. are presented and the proposed solutions are empirically evaluated. The experimental evaluation shows that applying the proposed solutions improves EcCrawler’s crawling speed over 400% and UI responsiveness over 100%. The proposed solutions may be applicable to any software that is developed by using .NET framework.

</details>

### December 2016 - [An Experimental Investigation of Document Vector Computation Methods for Sentiment Analysis of Turkish and English Reviews](https://huggingface.co/MonsterMMORPG/ResearchArticles/resolve/main/An_Experimental_Investigation_Of_Document_Vector_Computation_Methods_For_Sentiment_Analysis_Of_Turkish_And_English_Reviews.pdf)

Journal article | Çukurova University Journal of the Faculty of Engineering and Architecture, Vol. 31, No. 2

Compares document vectorization, weighting, preprocessing, and SVM choices for Turkish and English sentiment analysis on movie and product reviews.

<details>
<summary><strong>Abstract</strong></summary>

Sentiment analysis is the task of identifying overall attitude of the given text documents by using text analysis and natural language processing techniques. In this study, we present experimental results of sentiment analysis on movie and product reviews datasets that are in Turkish and English languages by using a Support Vector Machine (SVM) classifier. Moreover, we compare different document vector computation techniques and show their effects on the sentiment analysis. We empirically evaluate SVM types, kernel types, weighting schemes such as TF or TF*IDF, TF variances, IDF variances, tokenization methods, feature selection systems, text preprocessing techniques and vector normalizations. We have obtained 91.33% accuracy as the best on our collected Turkish product reviews dataset by using C-SVC SVM type with linear kernel, log normalization TF* probabilistic IDF weighting scheme, L2 vector normalization, Chi-square feature selection, and unigram word tokenization. A very detailed comparison of the document vector computation methods over Turkish and English datasets are also presented.

</details>

### October 2016 - [A Product Search Engine Supporting "Best Product" Queries](https://huggingface.co/MonsterMMORPG/ResearchArticles/resolve/main/A_Product_Search_Engine_Supporting_Best_Product_Queries.pdf)

Journal article | Çukurova University Journal of the Faculty of Engineering and Architecture, Vol. 31, Special Issue 2

Combines focused crawling, record linkage, sentiment analysis, and query processing to answer category-level best-product searches.

<details>
<summary><strong>Abstract</strong></summary>

In this study, a novel product search engine system which supports “find the best products for a given category” type queries is proposed. The product search engine system consists of a focused crawler, a record linkage system, a sentiment analyzer, and a query engine system. The focused crawler is used to crawl product information from various e-commerce sites; the record linkage system determines the identical products that are crawled from different e-commerce sites; the sentiment analyzer classifies users’ reviews about the products as positive or negative so that our product search engine can decide which product is the best for a given category; and the query engine takes the user queries and displays the result. All implementations are done by using C# programming language in .NET 4.5 framework, and MS-SQL Server 2014 database management system is employed for data storage. The core of our system is the record linkage part which is based on a modified incremental Hierarchical Agglomerative Clustering algorithm. To improve the success of record linkage process we also develop a product code matching system such that if the two products from different e-commerce sites have the same product code they are considered as the same. In our experimental analysis we observe 96.25% F-measure in record linkage of E-commerce products and 100% precision in most related products search. Our system can successfully offer best products for a given category. The proposed system provides better user experience than the existing systems.

</details>

### 2016 - [Product Search Engine Using Product Name Recognition and Sentiment Analysis](https://huggingface.co/MonsterMMORPG/ResearchArticles/resolve/main/Product_Search_Engine_Using_Product_Name_Recognition_And_Sentiment_Analysis.pdf)

PhD thesis | Çukurova University, Department of Computer Engineering

Develops a full-scale product search engine architecture that integrates crawling, product-name matching, sentiment analysis, and search, reporting strong gains across all core modules.

<details>
<summary><strong>Abstract</strong></summary>

In this study, a novel product search engine system which consists of a focused crawler, a record linkage system and a sentiment analyzer is proposed. We develop an original focused web crawler for E-commerce sites, and the challenges and our proposed solutions are presented in detail. A sentiment analyzer is developed to classify E-commerce product comments into polarities as negative or positive. A novel record linkage system for E-commerce products is proposed to recognize the same product names collected from different E-commerce sites. The record linkage system is based on a modified dynamic/incremental Hierarchical Agglomerative Clustering algorithm which employs our proposed product code matching system to reduce number of product name comparisons during clustering. In addition to these systems, a search system and a user interface are developed for the product search engine. In this thesis, we present a full scale product search engine that obtains 472% performance boosts in the crawler, 91.08% accuracy in the sentiment analysis, 96.25% F-measure in the record linkage, and 100% precision in most related products search. The proposed system provides better user experience than the existing systems.

</details>

### 2015 - [New Metrics for Clustering of Identical Products over Imperfect Data](https://huggingface.co/MonsterMMORPG/ResearchArticles/resolve/main/New_Metrics_For_Clustering_Of_Identical_Products_Over_Imperfect_Data.pdf)

Journal article | Turkish Journal of Electrical Engineering and Computer Sciences, Vol. 23, No. 4

Introduces new similarity and performance metrics for clustering identical products over imperfect, noisy, web-crawled data.

<details>
<summary><strong>Abstract</strong></summary>

This paper introduces the concept of product identity-clustering based on new similarity metrics and new performance metrics for web-crawled products. Product identity-clustering is defined here as the clustering of identical products, e.g., for price comparison purposes. Products blindly crawled over web sources, e.g., online marketplaces, have different description formats, where the features describing the same products differ in both number and representation formats. This problem causes imperfect feature vectors, where the vectors are considered to be not uniform in length and structure, with the features of various data types (numeric, categorical), and unknown vector structures. Furthermore, the product information usually contains redundant, missing, or faulty data, which are regarded as noise here. Product identity-clustering becomes a challenge when the vectors’ metadata are previously unknown and the imperfect nature of the feature vectors is considered with the occurrence of noise. In this paper, the product identity-clustering concept is introduced as a new mining metric in e-commerce. Then novel similarity metrics are introduced to improve the product identity-clustering performance of legacy metrics. Finally, novel performance metrics are proposed to measure the performance of the identity-clustering algorithms. Using these metrics, a comparison of the legacy-based similarity metrics (Euclidian, cosine, etc.) and the proposed similarity metrics is given. The results show that legacy metrics are not successful in discriminating identical web-crawled products and the proposed metrics enable better achievement in the product identity-clustering problem.

</details>

### June 2012 - [Fiyat Karşılaştırmalı Ürün Arama Motoru Geliştirme](https://huggingface.co/MonsterMMORPG/ResearchArticles/resolve/main/Fiyat_Kar%C5%9F%C4%B1la%C5%9Ft%C4%B1rmal%C4%B1_%C3%9Cr%C3%BCn_Arama_Motoru_Geli%C5%9Ftirme.pdf)

MSc thesis | Mersin University, Department of Computer Engineering

Lays the groundwork for price comparison search by crawling e-commerce sites, normalizing noisy product data, extracting feature vectors, and clustering identical products across sources. The thesis includes the English abstract title "Developing Product Price Comparison Search Engine."

<details>
<summary><strong>Abstract</strong></summary>

Recently, the rapidly growing usage of internet both in the world and in our country has brought many e-commerce and online web markets opportunities together. Probably the biggest job opportunity among these opportunities is online product selling on websites. The number of companies which sell online products is increasing more and more. Due to the competition between companies, the same product prices could be a lot different between companies. For the persons who are going to buy an online product, scanning all of the web markets and other e-commerce sites in order to find the cheapest product they are looking for is very hard and time consuming process. Instead of searching individually, all of the online product selling web sites can be crawled by software and same products can be grouped to display to the users with their prices. But grouping same products which are collected from different web sources is a difficult problem. The product information may have faulty, missing, redundant or inconsistent data by their nature. For example, in order to impress customers there may be extra words when defining product features or missing or incorrectly written words by human errors. This situation that we call as noise is certainly a problem that has to be solved when clustering same products. There are few works about processing product information obtained via web crawling in literature. Unsupervised clustering of the same products, and its priori steps, feature vectors extraction and normalization against noises are topics that are not studied till now. There are works about automatic products clustering in literature but these works are wide scaled categorization and aim to cluster products having one or more similar aspects. In this thesis, e-commerce and online web markets are crawled via our crawling agent and much product information is collected from many different sources. This product information is saved in a designed database and then the noises are eliminated and feature vectors are generated using the proposed normalization and feature vectors extracting methods. The products having extracted features are tested via newly developed clustering algorithm and standard clustering algorithms, and performance analysis is presented. In addition, in this thesis new error metrics are proposed that calculate the error rate in clustering of the same products. Finally, clustered commercial products are opened to public use via the developed web interface that will satisfy users’ demands.

</details>


