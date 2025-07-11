# **ALIDA**

Advanced Learning and Intelligent Data Analytics

*An Engineering Solution*

![image_013_image1.png](media/image_013_image1.png)

The ALIDA Team

<https://home.alidalab.it/>

info@alidalab.it

December 3, 2024

## **Abstract**

ALIDA is a microservice-based platform for composition, deployment,
optimization, execution and monitoring of big data analytics workflow.

It is an ENG asset thought and developed in the light of the massive use
of AI algorithms on diverse datasets. It simplifies all the four (4)
phases of big data analytics, from the selection of the data set(s) to
the selection of the algorithm to be applied on it. It allows the
definition of processing workflows on multiple yet dispersed data
sources.

## **Dedication**
(missing)

## **Declaration**
(missing)

## **Acknowledgements**

To those who remain in the heart of the ALIDA Team: Domenico Messina,
\...

To those who still swim in this sea: Susanna Bonura, Delia Milazzo,
Flavio Scaccia, Davide Profeta, Nicola Masi, Matteo Stanislao Giarrusso,
Piero Di Liberto, Sergio Comella, Salvatore Cipolla, Rosario Catelli,
\...

## **Contents**

[Contents [7](#contents)]

### [Part I [23](#part-i)]

[Introduction [23](#introduction)]

[1. ALIDA [24](#alida)]

[1.1 What is it? [24](#what-is-it)]

[1.2 What is it for? [24](#what-is-it-for)]

[1.3 Why do you need it? [25](#why-do-you-need-it)]

[1.4 How does it work? [25](#how-does-it-work)]

[1.5 When can it be used?
[25](#when-can-it-be-used)]

[1.6 In a nutshell? [26](#in-a-nutshell)]

[2. Use Cases [28](#use-cases)]

[2.1 MobiSpaces [28](#mobispaces)]

[2.1.1 Partners [28](#partners)]

[2.1.2 Overview [29](#overview)]

[2.1.3 Zooming into project
[30](#zooming-into-project)]

[2.1.4 Alida in the project
[31](#alida-in-the-project)]

[2.2 CyberSEAS [33](#cyberseas)]

[2.2.1 Partners [33](#partners-1)]

[2.2.2 Overview [35](#overview-1)]

[2.2.3 Zooming into Project
[35](#zooming-into-project-1)]

[2.2.4 Alida in the Project
[36](#alida-in-the-project-1)]

[2.3 CiTrace [39](#citrace)]

[2.3.1 Partners [39](#partners-2)]

[2.3.2 Overview [40](#overview-2)]

[2.3.3 Zooming into Project
[40](#zooming-into-project-2)]

[2.4 BD4NRG [41](#bd4nrg)]

[2.4.1 Partners [41](#partners-3)]

[2.4.2 Case Overview [43](#case-overview)]

[2.4.3 Zooming into Project
[43](#zooming-into-project-3)]

[2.4.4 Alida in the Project
[45](#alida-in-the-project-2)]

[2.5 SCREAM [46](#scream)]

[2.5.1 Partners [46](#partners-4)]

[2.5.2 Case Overview [46](#case-overview-1)]

[2.5.3 Zooming into Project
[47](#zooming-into-project-4)]

[2.5.4 Alida in the Project
[48](#alida-in-the-project-3)](

[2.6 Infinitech [49](#infinitech)]

[2.6.1 Partners [49](#partners-5)]

[2.6.2 Case Overview [52](#case-overview-2)]

[2.6.3 Zooming into Project
[52](#zooming-into-project-5)]

[2.6.4 Alida in the Project
[55](#alida-in-the-project-4)]

[2.7 OK-INSAID [58](#ok-insaid)]

[2.7.1 Partners [58](#partners-6)]

[2.7.2 Case Overview [59](#case-overview-3)]

[2.7.3 Zooming into Project
[59](#zooming-into-project-6)]

[2.7.4 Alida in the Project
[60](#alida-in-the-project-5)]

[2.8 ICARUS [65](#icarus)]

[2.8.1 Partners [65](#partners-7)]

[2.8.2 Case Overview [66](#case-overview-4)]

[2.8.3 Zooming into Project
[66](#zooming-into-project-7)]

[2.9 Agritech [68](#agritech)]

[2.9.1 Partners [68](#partners-8)]

[2.9.2 Case Overview [70](#case-overview-5)]

[2.9.3 Zooming into Project
[70](#zooming-into-project-8)]

[2.9.4 Alida in the Project
[72](#alida-in-the-project-6)]

### [Part II [73](#part-ii)]

[User Guide [73](#user-guide)]

[1. Data Access\* [73](#data-access)]

[1.1 Enterprise Application Integration
[73](#enterprise-application-integration)]

[1.1.1 Definition [73](#definition)]

[1.1.2 In ALIDA [73](#in-alida)]

[1.2 Data Replication and Synchronization
[73](#data-replication-and-synchronization)]

[1.2.1 Data Replication [73](#data-replication)]

[1.2.2 Data Synchronization
[74](#data-synchronization)]

[1.2.3 In ALIDA [75](#in-alida-1)]

[1.3 Basic and Advanced ETL Functionality
[76](#basic-and-advanced-etl-functionality)]

[1.3.1 Basic ETL Functionality
[76](#basic-etl-functionality)]

[1.3.1.1 Extract [76](#extract)]

[1.3.1.2 Transform [76](#transform)]

[1.3.1.3 Load [76](#load)]

[Common Use Cases: [77](#common-use-cases)]

[1.3.2 Advanced ETL Functionality
[77](#advanced-etl-functionality)]

[1.3.2.1 Advanced Extract [77](#advanced-extract)]

[1.3.2.2 Advanced Transform
[77](#advanced-transform)]

[1.3.2.3 Advanced Load [78](#advanced-load)]

[1.3.2.4 Automation & Orchestration
[78](#automation-orchestration)]

[1.3.2.4.1 Advanced Scalability & Performance
[78](#advanced-scalability-performance)]

[1.3.2.4.2 Security & Governance
[78](#security-governance)]

[1.3.2.4.3 Integration with Modern Architectures
[78](#integration-with-modern-architectures)]

[1.3.2.4.4 In ALIDA [79](#in-alida-2)]

[1.4 Hybrid and Multi Cloud Data Sources
[79](#hybrid-and-multi-cloud-data-sources)]

[1.4.1 Hybrid Cloud [79](#hybrid-cloud)]

[1.4.2 Multi-Cloud [80](#multi-cloud)]

[1.5 Access to Nontraditional Data Types
[80](#access-to-nontraditional-data-types)]

[1.5.1 Geospatial Data [81](#geospatial-data)]

[1.5.2 Mobile Phone Data [81](#mobile-phone-data)]

[1.5.3 Social Media Data [81](#social-media-data)]

[1.5.4 Sensor Data [81](#sensor-data)]

[1.5.5 Citizen-Generated Data
[81](#citizen-generated-data)]

[1.5.6 Transaction Data [81](#transaction-data)]

[1.6 Connectivity to Data Lake Infrastructure
[82](#connectivity-to-data-lake-infrastructure)]

[1.6.1 Choose the Right Data Lake Platform
[82](#choose-the-right-data-lake-platform)]

[1.6.2 Set Up Authentication and Access Control
[82](#set-up-authentication-and-access-control)]

[1.6.3 Data Ingestion and Integration
[82](#data-ingestion-and-integration)]

[1.6.4 Data Management and Governance
[82](#data-management-and-governance)]

[1.6.5 Analytics and Processing
[83](#analytics-and-processing)]

[1.7 Data Lineage [83](#data-lineage)]

[1.7.1 Importance of Data Lineage
[83](#importance-of-data-lineage)]

[1.7.2 Components of Data Lineage
[83](#components-of-data-lineage)]

[1.7.3 Tools for Data Lineage
[84](#tools-for-data-lineage)]

[1.7.4 Benefits of Data Lineage
[84](#benefits-of-data-lineage)]

[1.8 Data Governance and Metadata Management
[84](#data-governance-and-metadata-management)]

[1.8.1 Data Governance [84](#data-governance)]

[1.8.2 Metadata Management
[85](#metadata-management)]

[1.8.3 Synergy Between Data Governance and Metadata Management
[85](#synergy-between-data-governance-and-metadata-management)]

[1.9 API-Based Access to Web Data
[86](#api-based-access-to-web-data)]

[1.9.1 How API-Based Access Works
[86](#how-api-based-access-works)]

[1.9.2 Popular Tools and Libraries
[86](#popular-tools-and-libraries)]

[1.9.3 Use Cases [86](#use-cases-1)]

[1.9.4 Learning Resources
[86](#learning-resources)]

[2. Data Preparation [88](#data-preparation)]

[2.1 Data Blending/Wrangling
[88](#data-blendingwrangling)]

[2.2 Data Augmentation [89](#data-augmentation)]

[2.3 Data Quality Support
[91](#data-quality-support)]

[2.4 Dataset Partitioning
[91](#dataset-partitioning)]

[2.5 Binning and Smoothing
[91](#binning-and-smoothing)]

[2.6 Filter and Search [91](#filter-and-search)]

[2.7 Feature Generation [91](#feature-generation)]

[2.8 Official Watermarking of Datasets
[91](#official-watermarking-of-datasets)]

[2.9 Basic Data Catalogue
[91](#basic-data-catalogue)]

[2.10 Data Labelling/Annotation
[91](#data-labellingannotation)]

[2.11 Transformations, Aggregation and Set Operations
[91](#transformations-aggregation-and-set-operations)]

[2.12 Data Enrichment [91](#data-enrichment)]

[2.13 Augmented Data Preprocessing
[91](#augmented-data-preprocessing)]

[2.14 Augmented Data Preparation
[91](#augmented-data-preparation)]

[2.15 Cloud, Hybrid and Multicloud Support
[91](#cloud-hybrid-and-multicloud-support)]

[3. Data Exploration and Visualisation \<omissis\>
[92](#data-exploration-and-visualisation-omissis)]

[3.1 Univariate and Bivariate Statistics
[92](#univariate-and-bivariate-statistics)]

[3.2 Statistical Significance Testing
[92](#statistical-significance-testing)]

[3.3 Signal Preprocessing
[92](#signal-preprocessing)]

[3.4 Data Visualizations
[92](#data-visualizations)]

[3.5 Exporting Results [92](#exporting-results)]

[3.6 Custom Visualization
[92](#custom-visualization))

[3.7 Clustering and Self-Organizing Maps
[92](#clustering-and-self-organizing-maps)]

[3.8 Geolocation Mapping
[92](#geolocation-mapping)]

[3.9 Affinity and Graph Analysis
[92](#affinity-and-graph-analysis)]

[3.10 Conjoint and Survey Analysis
[92](#conjoint-and-survey-analysis)]

[3.11 Density Estimation [92](#density-estimation)]

[3.12 Similarity Metrics [92](#similarity-metrics)]

[3.13 Augmented Data Discovery
[92](#augmented-data-discovery)]

[3.14 On-Premises [92](#on-premises)]

[3.15 Cloud, Multicloud and Hybrid
[92](#cloud-multicloud-and-hybrid)]

[4. User Interface [93](#user-interface)]

[4.1 Ease of Use and Learning Curve
[93](#ease-of-use-and-learning-curve)]

[4.2 Developer-Focused Data Science
[93](#developer-focused-data-science)]

[4.3 NLP Q&A [93](#nlp-qa)]

[4.4 Documentation [93](#documentation)]

[4.5 User Community [93](#user-community)]

[4.6 Third-Party Applications
[93](#third-party-applications)]

[4.7 Visual Pipelining or Visual Composition Framework
[93](#visual-pipelining-or-visual-composition-framework)]

[4.8 Wizards and Contextual Aids \<start again\>
[93](#wizards-and-contextual-aids-start-again)]

[4.8.1 ALIDA Home -- Dashboard
[93](#alida-home-dashboard)]

[4.8.2 Notifications [94](#notifications)]

[4.8.3 DataSource [99](#datasource)]

[4.8.4 Datasets [102](#datasets)]

[4.8.5 BDA Services [104](#bda-services)]

[4.8.6 BDA Application [108](#bda-application)]

### [Part III [143](#part-iii)]

[1. Machine Learning [143](#machine-learning)]

[1.1 Regression [143](#regression)]

[1.2 Time Series Analysis
[143](#time-series-analysis)]

[1.3 Deep Learning (Deep Neural Nets)
[143](#deep-learning-deep-neural-nets)]

[1.4 Reinforcement Learning
[143](#reinforcement-learning)]

[1.5 Classification and Regression Trees
[143](#classification-and-regression-trees)]

[1.6 Further Rule Induction Techniques
[143](#further-rule-induction-techniques)]

[1.7 Support Vector Machines
[143](#support-vector-machines)]

[1.8 Instance-Based Approaches
[143](#instance-based-approaches)]

[1.9 Bayesian Modeling [143](#bayesian-modeling)](

[1.10 Transfer Learning [143](#transfer-learning)]

[1.11 Ensembles and Hierarchical Models
[143](#ensembles-and-hierarchical-models)]

[1.12 Recommendation Techniques
[143](#recommendation-techniques)]

[1.13 Measures of Fit [143](#measures-of-fit)]

[1.14 Testing of Predictive Models
[143](#testing-of-predictive-models)]

[1.15 CNN, RNN, GNN [143](#cnn-rnn-gnn)]

[1.16 Generative Adversarial Networks (GAN)
[143](#generative-adversarial-networks-gan)]

[1.17 Federated Learning
[143](#federated-learning)]

[2. Other Advanced Analytics
[144](#other-advanced-analytics)]

[2.1 Solver approaches [144](#solver-approaches)]

[2.2 Heuristic approaches
[144](#heuristic-approaches)]

[2.3 Design of experiments
[144](#design-of-experiments)]

[2.4 Discrete Events [144](#discrete-events)]

[2.5 Monte Carlo Simulation
[144](#monte-carlo-simulation)]

[2.6 Agent-Based Modelling
[144](#agent-based-modelling)]

[2.7 Text Analytics [144](#text-analytics)]

[2.8 Customizable Pretrained Algorithms
[144](#customizable-pretrained-algorithms)]

[2.9 Audio Mining [144](#audio-mining)]

[2.10 Image Analytics [144](#image-analytics)]

[2.11 Geospatial Analysis
[144](#geospatial-analysis)]

[2.12 Financial Modelling and Econometrics
[144](#financial-modelling-and-econometrics)]

[2.13 Decision Modelling
[144](#decision-modelling)]

[2.14 Decision Management
[144](#decision-management)]

[2.15 Composite AI [144](#composite-ai)]

[2.16 Stream Processing/Data in Motion
[144](#stream-processingdata-in-motion)]

[3. Flexibility, Extensibility and Openness
[145](#flexibility-extensibility-and-openness)]

[3.1 R [145](#r)]

[3.2 Python [145](#python)]

[3.3 Scala [145](#scala)]

[3.4 Java [145](#java)]

[3.5 Third-Party Libraries
[145](#third-party-libraries)]

[3.6 Popular Libraries and Frameworks
[145](#popular-libraries-and-frameworks)]

[3.7 Data Science Notebooks
[145](#data-science-notebooks)]

[3.7.1 Read datasets inside Notebooks
[145](#read-datasets-inside-notebooks)]

[3.8 Open-Source Data Management Platforms (e.g., Spark and Hadoop)
[146](#open-source-data-management-platforms-e.g.-spark-and-hadoop)]

[3.9 Docker [146](#docker)]

[3.10 Scripting and Embedding Capabilities
[146](#scripting-and-embedding-capabilities)]

[3.11 Open-Source Automated Machine Learning Tools
[146](#open-source-automated-machine-learning-tools)]

[3.12 Code Visibility and Transparency
[146](#code-visibility-and-transparency)]

[4. Performance and Scalability
[147](#performance-and-scalability)]

[4.1 In-Database Analytics
[147](#in-database-analytics)]

[4.2 Big Data Volume Scalability
[147](#big-data-volume-scalability)]

[4.3 Real-Time Data and Streams
[147](#real-time-data-and-streams)]

[4.4 In-Memory, Hadoop and Spark
[147](#in-memory-hadoop-and-spark)]

[4.5 Support of GPUs [147](#support-of-gpus)]

[4.6 Support of Other Specialized Hardware
[147](#support-of-other-specialized-hardware)]

[4.7 Algorithmic Efficiency in a Single-Node or MultipleNode Environment
[147](#algorithmic-efficiency-in-a-single-node-or-multiplenode-environment)]

[4.8 Cost guidance [147](#cost-guidance)]

[4.9 Performance options for training
[147](#performance-options-for-training)]

[4.10 On-Premises [147](#on-premises-1)]

[4.11 Cloud, Hybrid and Multicloud
[147](#cloud-hybrid-and-multicloud)]

[5. Delivery [148](#delivery)]

[5.1 Write-back [148](#write-back)]

[5.2 Recoding [148](#recoding)]

[5.3 REST APIs [148](#rest-apis)]

[5.4 PMML and ONNX [148](#pmml-and-onnx)]

[5.5 Augmented Model Deployment and Monitoring
[148](#augmented-model-deployment-and-monitoring)]

[5.6 Containerization [148](#containerization)]

[5.7 Web deployment [148](#web-deployment)]

[5.8 Other [148](#other)]

[5.9 Deployment Mode [148](#deployment-mode)]

[5.9.1 Model Serving [148](#model-serving)]

[5.10 Parallel Model Deployments
[150](#parallel-model-deployments)]

[6. Platform and Project Management
[151](#platform-and-project-management)]

[6.1 Compliance and Auditing
[151](#compliance-and-auditing)]

[6.2 Object Reuse [151](#object-reuse)]

[6.3 Multiuser Capabilities
[151](#multiuser-capabilities)]

[6.4 Debugging and Unit Testing
[151](#debugging-and-unit-testing)]

[6.5 Runtime Optimization
[151](#runtime-optimization)]

[6.6 Audit and Logs [151](#audit-and-logs)]

[6.7 Data Encryption [151](#data-encryption)]

[6.8 Securing ML Pipeline
[151](#securing-ml-pipeline)]

[6.9 Client Deployment [151](#client-deployment)]

[7. Model Management [152](#model-management)]

[7.1 Metadata management
[152](#metadata-management-1)]

[7.2 Traceability [152](#traceability)]

[7.3 Champion/Challenger
[152](#championchallenger)]

[7.4 Model Telemetry [152](#model-telemetry)]

[7.5 Confusion Matrices [152](#confusion-matrices)]

[7.6 Model Catalog and Reproducibility
[152](#model-catalog-and-reproducibility)]

[7.7 Technical Performance Tracking
[152](#technical-performance-tracking)]

[7.8 Business Performance Tracking
[152](#business-performance-tracking)]

[7.9 Adaptive ML [152](#adaptive-ml)]

[7.10 Model Alignment to Business Ojectives
[152](#model-alignment-to-business-ojectives)]

[7.11 Governance [152](#governance)]

[7.12 Model Licensing Issues
[152](#model-licensing-issues)]

[7.13 Scripting and Automation
[152](#scripting-and-automation)]

[7.14 Process Monitoring
[152](#process-monitoring)]

[7.15 Model Management Across Deployment Modes
[152](#model-management-across-deployment-modes)]

[8. MLOps [153](#mlops)]

[8.1 Intro [153](#intro)]

[8.2 Model life cycle [153](#model-life-cycle)]

[8.3 Data collection and preprocessing
[155](#data-collection-and-preprocessing)]

[8.4 Model Development, testing and validation
[155](#model-development-testing-and-validation)]

[8.5 Model Deployment [155](#model-deployment)]

[8.6 Monitoring and Maintenance
[156](#monitoring-and-maintenance)]

[9. Explainable AI [157](#explainable-ai)]

[9.1 Explainable AI [157](#explainable-ai-1)]

[9.2 Support for Open Source
[157](#support-for-open-source)]

[9.3 Augmented Explainability
[157](#augmented-explainability)]

[9.4 Explainabiliity Techniques (Including Permutation Importance,
Feature Importance, Sensitivity Analysis, Partial Dependence Plots, ICE
Plots, Integrated Gradients, Similarity Based Methods and Others)
[157](#explainabiliity-techniques-including-permutation-importance-feature-importance-sensitivity-analysis-partial-dependence-plots-ice-plots-integrated-gradients-similarity-based-methods-and-others)]

[9.5 Responsible AI [157](#responsible-ai)]

[9.6 Regulations [157](#regulations)]

[10. Precanned Solutions
[158](#precanned-solutions)]

[10.1 Marketing, Sales and Customer Service
[158](#marketing-sales-and-customer-service)]

[10.2 Finance, Risk Management and Quality Management
[158](#finance-risk-management-and-quality-management)]

[10.3 Internet of Things
[158](#internet-of-things)]

[10.4 Supply Chain/Logistics
[158](#supply-chainlogistics)]

[10.5 Back-Office Analytics
[158](#back-office-analytics)]

[10.6 IT Operations [158](#it-operations)]

[10.7 Cybersecurity [158](#cybersecurity)]

[10.8 Anomaly Detection [158](#anomaly-detection)]

[10.9 What-If Scenarios [158](#what-if-scenarios)]

[11. Collaboration [159](#collaboration)]

[11.1 Collaboration Across All Modeling Steps for Distributed Teams
[159](#collaboration-across-all-modeling-steps-for-distributed-teams)]

[11.2 Discussion Threads
[159](#discussion-threads)]

[11.3 Ratings and Recommendations
[159](#ratings-and-recommendations)]

[11.4 Marketplace/Hub [159](#marketplacehub)]

[11.5 Multipersona Collaboration
[159](#multipersona-collaboration)]

### [Part IV [160](#part-iv)]

[R&I Guide [160](#ri-guide)]

[1. Data Access [160](#data-access-1)]

[1.1 Enterprise Application Integration
[160](#enterprise-application-integration-1)]

[1.2 Data Replication and Synchronization
[160](#data-replication-and-synchronization-1)]

[1.3 Basic and Advanced ETL Functionality
[160](#basic-and-advanced-etl-functionality-1)]

[1.4 Hybrid and Multicloud Data Sources
[160](#hybrid-and-multicloud-data-sources)]

[1.5 Access to Non-traditional Data Types
[160](#access-to-non-traditional-data-types)]

[1.6 Connectivity to Data Lake Infrastructure
[160](#connectivity-to-data-lake-infrastructure-1)]

[1.7 Data Lineage [160](#data-lineage-1)]

[1.8 Data Governance and Metadata Management
[160](#data-governance-and-metadata-management-1)]

[1.9 API-Based Access to Web Data
[160](#api-based-access-to-web-data-1)]

[2. Data Preparation [161](#data-preparation-1)]

[2.1 Data Blending/Wrangling
[161](#data-blendingwrangling-1)]

[2.2 Data Augmentation
[161](#data-augmentation-1)]

[2.3 Data Quality Support
[161](#data-quality-support-1)]

[2.4 Dataset Partitioning
[161](#dataset-partitioning-1)]

[2.5 Binning and Smoothing
[161](#binning-and-smoothing-1)]

[2.6 Filter and Search
[161](#filter-and-search-1)]

[2.7 Feature Generation
[161](#feature-generation-1)]

[2.8 Official Watermarking of Datasets
[161](#official-watermarking-of-datasets-1)]

[2.9 Basic Data Catalog [161](#basic-data-catalog)]

[2.10 Data Labeling/Annotation
[161](#data-labelingannotation)]

[2.11 Transformations, Aggregation and Set Operations
[161](#transformations-aggregation-and-set-operations-1)]

[2.12 Data Enrichment [161](#data-enrichment-1)]
[2.13 Augmented Data Preprocessing
[161](#augmented-data-preprocessing-1)]

[2.14 Augmented Data Preparation
[161](#augmented-data-preparation-1)]

[2.15 Cloud, Hybrid and Multicloud Support
[161](#cloud-hybrid-and-multicloud-support-1)]

[3. Data Exploration and Visualisation
[162](#data-exploration-and-visualisation)]

[3.1 Univariate and Bivariate Statistics
[162](#univariate-and-bivariate-statistics-1)]

[3.2 Statistical Significance Testing
[162](#statistical-significance-testing-1)]

[3.3 Signal Preprocessing
[162](#signal-preprocessing-1)]

[3.4 Data Visualizations
[162](#data-visualizations-1)]

[3.5 Exporting Results
[162](#exporting-results-1)]

[3.6 Custom Visualization
[162](#custom-visualization-1)]

[3.7 Clustering and Self-Organizing Maps
[162](#clustering-and-self-organizing-maps-1)]

[3.8 Geolocation Mapping
[162](#geolocation-mapping-1)]

[3.9 Affinity and Graph Analysis
[162](#affinity-and-graph-analysis-1)]

[3.10 Conjoint and Survey Analysis
[162](#conjoint-and-survey-analysis-1)]

[3.11 Density Estimation
[162](#density-estimation-1)]

[3.12 Similarity Metrics
[162](#similarity-metrics-1)]

[3.13 Augmented Data Discovery
[162](#augmented-data-discovery-1)]

[3.14 On-Premises [162](#on-premises-2)]

[3.15 Cloud, Multicloud and Hybrid
[162](#cloud-multicloud-and-hybrid-1)]

[4. User Interface [163](#user-interface-1)]

[4.1 Ease of Use and Learning Curve
[163](#ease-of-use-and-learning-curve-1)]

[4.2 Developer-Focused Data Science
[163](#developer-focused-data-science-1)]
[4.3 NLP Q&A [163](#nlp-qa-1)]

[4.4 Documentation [163](#documentation-1)]

[4.5 User Community [163](#user-community-1)]

[4.6 Third-Party Applications
[163](#third-party-applications-1)]

[4.7 Visual Pipelining or Visual Composition Framework
[163](#visual-pipelining-or-visual-composition-framework-1)]

[4.8 Wizards and Contextual Aids
[163](#wizards-and-contextual-aids)]

[5. Machine Learning [164](#machine-learning-1)]

[5.1 Regression [164](#regression-1)]

[5.2 Time Series Analysis
[164](#time-series-analysis-1)]

[5.3 5.3 Deep Learning (Deep Neural Nets) 5.4 Reinforcement Learning
[164](#deep-learning-deep-neural-nets-5.4-reinforcement-learning)]

[5.4 Classification and Regression Trees
[164](#classification-and-regression-trees-1)]

[5.5 Further Rule Induction Techniques
[164](#further-rule-induction-techniques-1)]

[5.6 Support Vector Machines
[164](#support-vector-machines-1)]

[5.7 Instance-Based Approaches
[164](#instance-based-approaches-1)]

[5.8 Bayesian Modeling
[164](#bayesian-modeling-1)]

[5.9 Transfer Learning
[164](#transfer-learning-1)]

[5.10 Ensembles and Hierarchical Models
[164](#ensembles-and-hierarchical-models-1)]

[5.11 Recommendation Techniques
[164](#recommendation-techniques-1)]

[5.12 Measures of Fit [164](#measures-of-fit-1)]

[5.13 Testing of Predictive Models
[164](#testing-of-predictive-models-1)]

[5.14 CNN, RNN, GNN [164](#cnn-rnn-gnn-1)]

[5.15 Generative Adversarial Networks (GAN)
[164](#generative-adversarial-networks-gan-1)]

[5.16 Federated Learning
[164](#federated-learning-1)]

[6. Other Advanced Analytics
[165](#other-advanced-analytics-1)]

[6.1 Solver approaches
[165](#solver-approaches-1)]

[6.2 Heuristic approaches
[165](#heuristic-approaches-1)]

[6.3 Design of experiments
[165](#design-of-experiments-1)]

[6.4 Discrete Events [165](#discrete-events-1)]

[6.5 Monte Carlo Simulation
[165](#monte-carlo-simulation-1)]

[6.6 Agent-Based Modeling
[165](#agent-based-modeling)]

[6.7 Text Analytics [165](#text-analytics-1)]

[6.8 Customizable Pretrained Algorithms
[165](#customizable-pretrained-algorithms-1)]

[6.9 Audio Mining [165](#audio-mining-1)]

[6.10 Image Analytics [165](#image-analytics-1)]

[6.11 Geospatial Analysis
[165](#geospatial-analysis-1)]

[6.12 Financial Modeling and Econometrics
[165](#financial-modeling-and-econometrics)]

[6.13 Decision Modelling
[165](#decision-modelling-1)]
[6.14 Decision Management
[165](#decision-management-1)]

[6.15 Composite AI [165](#composite-ai-1)]

[6.16 Stream Processing/Data in Motion
[165](#stream-processingdata-in-motion-1)]

[7. Flexibility, Estensibility and Openness
[166](#flexibility-estensibility-and-openness)]

[7.1 R [166](#r-1)]

[7.2 Python [166](#python-1)]

[7.3 Scala [166](#scala-1)]

[7.4 Java [166](#java-1)]

[7.5 Third-Party Libraries
[166](#third-party-libraries-1)]

[7.6 Popular Libraries and Frameworks
[166](#popular-libraries-and-frameworks-1)]

[7.7 Data Science Notebooks
[166](#data-science-notebooks-1)]

[7.7.1 Intro [166](#intro-1)]

[7.7.2 Technologies involved
[167](#technologies-involved)]

[7.7.2.1 Jupyter Notebooks
[168](#jupyter-notebooks)]
[7.7.2.2 Jupyter Hub [169](#jupyter-hub)]

[7.7.2.3 Data access [170](#data-access-2)]

[7.8 Open-Source Data Management Platforms (e.g., Spark and Hadoop)
[172](#open-source-data-management-platforms-e.g.-spark-and-hadoop-1)]

[7.9 Docker [172](#docker-1)]

[7.10 Scripting and Embedding Capabilities
[172](#scripting-and-embedding-capabilities-1)]

[7.11 Open-Source Automated Machine Learning Tools
[172](#open-source-automated-machine-learning-tools-1)]

[7.12 Code Visibility and Transparency
[172](#code-visibility-and-transparency-1)]

[8. Performance and Scalability
[160](#performance-and-scalability-1)]

[8.1 In-Database Analytics
[160](#in-database-analytics-1)]

[8.2 Big Data Volume Scalability
[160](#big-data-volume-scalability-1)]

[8.3 Real-Time Data and Streams
[160](#real-time-data-and-streams-1)]

[8.4 In-Memory, Hadoop and Spark
[160](#in-memory-hadoop-and-spark-1)]

[8.5 Support of GPUs [160](#support-of-gpus-1)]

[8.6 Support of Other Specialized Hardware
[160](#support-of-other-specialized-hardware-1)]1)

[8.7 Algorithmic Efficiency in a Single-Node or MultipleNode Environment
[160](#algorithmic-efficiency-in-a-single-node-or-multiplenode-environment-1)]

[8.8 Cost guidance [160](#cost-guidance-1)]

[8.9 Performance options for training
[160](#performance-options-for-training-1)]

[8.10 On-Premises [160](#on-premises-3)]

[8.11 Cloud, Hybrid and Multicloud
[160](#cloud-hybrid-and-multicloud-1)]

[9. Delivery [161](#delivery-1)]

[9.1 Write-back [161](#write-back-1)]

[9.2 Recoding [161](#recoding-1)]

[9.3 REST APIs [161](#rest-apis-1)]

[9.4 PMML and ONNX [161](#pmml-and-onnx-1)]

[9.5 Augmented Model Deployment and Monitoring
[161](#augmented-model-deployment-and-monitoring-1)]

[9.6 Containerization [161](#containerization-1)]

[9.7 Web deployment [161](#web-deployment-1)]

[9.8 Other [161](#other-1)]

[9.9 Deployment Mode [161](#deployment-mode-1)]

[9.10 Parallel Model Deployments
[161](#parallel-model-deployments-1)]

[10. Platform and Project Management
[162](#platform-and-project-management-1)]

[10.1 Compliance and Auditing
[162](#compliance-and-auditing-1)]

[10.2 Object Reuse [162](#object-reuse-1)]

[10.3 Multiuser Capabilities
[162](#multiuser-capabilities-1)]

[10.4 Debugging and Unit Testing
[162](#debugging-and-unit-testing-1)]

[10.5 Runtime Optimization
[162](#runtime-optimization-1)]

[10.6 Audit and Logs [162](#audit-and-logs-1)]

[10.7 Data Encryption [162](#data-encryption-1)]

[10.8 Securing ML Pipeline
[162](#securing-ml-pipeline-1)]

[10.9 Client Deployment
[162](#client-deployment-1)]

[11. Model Management [163](#model-management-1)]

[11.1 Metadata management
[163](#metadata-management-2)]

[11.2 Traceability [163](#traceability-1)]

[11.3 Champion/Challenger
[163](#championchallenger-1)]

[11.4 Model Telemetry [163](#model-telemetry-1)]

[11.5 Confusion Matrices
[163](#confusion-matrices-1)]

[11.6 Model Catalog and Reproducibility
[163](#model-catalog-and-reproducibility-1)]

[11.7 Technical Performance Tracking
[163](#technical-performance-tracking-1)]

[11.8 Business Performance Tracking
[163](#business-performance-tracking-1)]

[11.9 Adaptive ML [163](#adaptive-ml-1)]

[11.10 Model Alignment to Business Ojectives
[163](#model-alignment-to-business-ojectives-1)]

[11.11 Governance [163](#governance-1)]

[11.12 Model Licensing Issues
[163](#model-licensing-issues-1)]

[11.13 Scripting and Automation
[163](#scripting-and-automation-1)]

[11.14 Process Monitoring
[163](#process-monitoring-1)]

[11.15 Model Management Across Deployment Modes
[163](#model-management-across-deployment-modes-1)]

[12. Explainable AI [164](#explainable-ai-2)]

[12.1 Explainable AI [164](#explainable-ai-3)]

[12.2 Support for Open Source
[164](#support-for-open-source-1)]

[12.3 Augmented Explainability
[164](#augmented-explainability-1)]

[12.4 Explainabiliity Techniques (Including Permutation Importance,
Feature Importance, Sensitivity Analysis, Partial Dependence Plots, ICE
Plots, Integrated Gradients, Similarity Based Methods and Others)
[164](#explainabiliity-techniques-including-permutation-importance-feature-importance-sensitivity-analysis-partial-dependence-plots-ice-plots-integrated-gradients-similarity-based-methods-and-others-1)]

[12.5 Responsible AI [164](#responsible-ai-1)]

[12.6 Regulations [164](#regulations-1)]

[13. Precanned Solutions
[165](#precanned-solutions-1)]

[13.1 Marketing, Sales and Customer Service
[165](#marketing-sales-and-customer-service-1)]

[13.2 Finance, Risk Management and Quality Management
[165](#finance-risk-management-and-quality-management-1)]

[13.3 Internet of Things
[165](#internet-of-things-1)]

[13.4 Supply Chain/Logistics
[165](#supply-chainlogistics-1)]

[13.5 Back-Office Analytics
[165](#back-office-analytics-1)]

[13.6 IT Operations [165](#it-operations-1)]

[13.7 Cybersecurity [165](#cybersecurity-1)]

[13.8 Anomaly Detection
[165](#anomaly-detection-1)]

[13.9 What-If Scenarios
[165](#what-if-scenarios-1)]

[14. Collaboration [166](#collaboration-1)]

[14.1 Collaboration Across All Modeling Steps for Distributed Teams
[166](#collaboration-across-all-modeling-steps-for-distributed-teams-1)]

[14.2 Discussion Threads
[166](#discussion-threads-1)]

[14.3 Ratings and Recommendations
[166](#ratings-and-recommendations-1)]

[14.4 Marketplace/Hub [166](#marketplacehub-1)]

[14.5 Multipersona Collaboration
[166](#multipersona-collaboration-1)]

### [Part V [167](#part-v)]

[Conclusions [167](#conclusions)]

[Acronyms [168](#acronyms)]

[Dictionary [169](#dictionary)]

[Publications [170](#publications)]

[Book Chapters [170](#book-chapters)]

[Conference Papers [171](#conference-papers)]

[Journal Papers [172](#journal-papers)]

#

# **Part I**    

## Introduction

#

## ALIDA

This chapter introduces the ALIDA platform. In particular, there are two
main sections: the first presents the software product in its overall
view, explaining its raison d'être, while the second provides an
overview of the use cases in which ALIDA finds application, although
these cases are not exhaustive but rather constantly evolving and
enriching.

## What is it?

ALIDA is a cutting-edge microservices-based platform meticulously
designed and developed by Engineering Ingegneria Informatica.

It is a resource that is both fundamental and versatile: on the one hand
it optimises, automates and industrialises Data Science and Machine
Learning (DSML) processes, on the other hand it composes, distributes,
optimises, executes and monitors Data Analytics workflows.

ALIDA is built to simplify the process of applying analytics and
artificial intelligence algorithms to disparate data sets, enabling
organisations to increase operational efficiency and agility,
accelerating the transition from proof of concept to production.

##  What is it for?

ALIDA has a pivotal role in facilitating the entire spectrum of big data
analytics and serves as a versatile tool for designing, deploying, and
operationalising their applications.

It allows users to seamlessly handle all phases of big data processing,
from the initial selection of data sets to the choice of the most
appropriate algorithms for analysis, enabling the creation of customised
workflows even with real time data, selecting services and data from an
extensive catalogue. In addition, it makes possible to manage schedules,
outputs and errors related to different executions, enabling evaluations
and validations capabilities.

Essentially, ALIDA serves as a comprehensive tool for data scientists
and analysts to manage and optimise their big data analytics workflows:
it is indispensable for rapidly prototyping AI and Big Data Analytics
applications while supporting the operationalisation of Machine Learning
(ML) models.

## Why do you need it?

In the current data science and machine learning landscape, the volume
and complexity of data make traditional approaches inadequate. In turn,
DSML platforms are rapidly evolving and organisations must adapt to stay
competitive: ALIDA is your solution to meet the challenges of modern
analytics.

With ALIDA, you can promptly address these evolving needs in data
science, ML, and data analytics operationalisation because it simplifies
and enhances your big data analytics endeavours. In addition, it
addresses the need for agility, resilience, and operational efficiency
in ML pipelines and production models: it empowers you to efficiently
harness the potential of AI algorithms on diverse data sets, ensuring
that your data-driven decisions are well-informed and accurate.

## How does it work?

ALIDA's operation is based on a microservices architecture, providing
modularity and scalability.

It allows users to define and process customised workflows on multiple
but separate data sources by selecting big data analytics services from
its catalogue: this means that you can orchestrate complex data analysis
tasks by breaking them down into manageable components, optimising
resource utilisation, and monitoring each step of the process. ALIDA's
integration with AI algorithms and data sets is seamless, making it easy
to create, deploy, and optimise data analytics workflows.

Finally, ALIDA simplifies deployment within the target cluster using a
package manager. It leverages the most cutting-edge technologies and
frameworks, and its cloud-native design ensures scalability of computing
and storage resources through a pipeline orchestration engine built on
Kubernetes capabilities for cloud resource management.

## When can it be used?

ALIDA can be used whenever you engage in big data analytics projects.
Its versatility and capabilities are an invaluable support for a wide
range of scenarios, including but not limited to:

- **Agile ML Pipelines**: for rapidly prototyping AI and Big Data
  Analytics applications.

- **Business Intelligence**: to gain insights from large volumes of data
  for strategic decision-making.

- **Cloud-Native Environments**: for scaling computing and storage
  resources as needed.

- **Data Analytics**: in processing and analysing large volumes of data
  for actionable insights.

- **Data Mining**: for extracting valuable patterns and knowledge from
  complex data sources.

- **Data Transformation and Integration**: in data preprocessing and
  cleansing phases.

- **Federated Learning**: ML technique for training algorithms via
  multiple independent sessions, addressing critical issues such as data
  privacy and security.

- **Industrialised DSML**: to streamline and automate the transition
  from proof of concept to production.

- **Model Evaluation and Comparison**: assessing the correctness of
  inferences, predictions and functionality of the resulting models.

- **Model Serving**: to make the ML model accessible to multiple
  applications via API.

- **Operationalisation of ML Models**: to support the deployment of ML
  models within target infrastructures.

- **Predictive Analytics**: in forecasting trends, behaviour, or
  outcomes based on historical data.

- **Research, Development and Innovation**: when exploring new data sets
  and AI algorithms to develop cutting-edge solutions to bring to
  market.

## In a nutshell?

In summary, ALIDA is your go-to corporate asset for modern data science
and machine learning: it is a powerful resource that empowers
organisations to embrace the industrialisation of DSML.

In addition, it provides automation capabilities, supports rapid
prototyping and makes ML models operational, making them essential for
the evolving landscape of data science, ML and data analysis operations.

Overall, it simplifies, streamlines, and empowers your big data
analytics endeavours, ensuring you make data-driven decisions with
confidence.


##

# **Use Cases**

<br>

> ## MobiSpaces



<figure>
<img src="media/image_012_image2.jpg" style="max-width: 50%; height: auto;"/>
</figure>


> *Figure 2.1.1: MobiSpaces Project Logo*

| **Type** | **Start Date** | **End Date** | **ENG Grant Amount** | **PM** |
| --- | --- | --- | --- | --- |
| ML-Ops | 1 Sept 2022 | 31 Aug 2025 | 412500,00 € | x |

> *Table 2.1.1: MobiSpaces Project Info*

### Partners

<figure>
<img src="media/image_014_image3.jpg" style="max-width: 75%; height: auto;"/>
</figure>

> *Figure 2.1.2: MobiSpaces Partners Logos 01*

### Overview

MobiSpaces is an end-to-end mobility-aware and mobility-optimized data
governance platform based on mobility analytics for efficient, reliable,
secure, fair and trustworthy data processing.


| **Partner Name** | **Acronym** | **Country** |
| --- | --- | --- | 
| Engineering Ingegneria Informatica  S.p.A. | ENG | Italy |
| Atos Spain SA | ATOS | Spain |
| Robert Bosch GMBH | BOSCH | Germany |
| Siemens SRL | SIEM | Romania |
| Frequentis AG | FREQ | Austria |
| Azienda Mobilità e trasporti SpA | AMT | Italy |
| Marintrafik Opereisons Monoprospi Anonymi | MOMA | Greece |
| Etairia Pliroforikis |  |  |
| Emisia SA-Anonymi Etairia Perivallontikon kai Energiakon Meleton kai Anaptixis | Logismikou                                 |             |             |
| Emisia SA-Anonimi Erairia                  | EMISIA      | Greece      |
| OKYS LTD                                   | OKYS        | Bulgaria    |
| Ubitech Limited                            | UBIT        | Cyprus      |
| Leanxcale SL                               | LEANX       | Spain       |
| Unparallel Innovation LDA                  | UIL         | Portugal    |
| Trust-IT Services SRL                      | TRUST       | Italy       |
| COMMPLA SRL                                | COMMPLA     | Italy       |
| Geodatastyrelsen                           | GEODATA     | Denmark     |
| Digital Systems 4.0                        | DS4         | Bulgaria    |
| NET-U Consutlant LTD                       | NET-U       | Cyprus      |
| Universal of Piraeus Research Center       | UPRC        | Greece      |
| Universite Libre de Bruxelles              | ULB         | Belgium     |
| Australian Institute of Technology GMBH    | AIT         | Australia   |
| Aalborg Univeristet                        | AAUN        | Denmark     |
| White Label Consultancy APS                | WLC         | Denmark     |
| Fujitsu Service GMBH                       | FSG         | Germany     |
| Fujitsu Technology Solutions GMBH          | FTSG        | Germany     |

> *Table 2.1.2: MobiSpaces Partners*

The purpose of the application is to address the problem of bus
scheduling. Given a timetable (provided by the municipality of Genoa),
it aims to assign a series of bus trips to a specific bus, optimizing
battery usage, depot charging times, and overall fleet deployment.

Subsequently, it seeks to transform the maintenance process, currently
performed traditionally, into a modern process with an approach based on
automatic data learning.

Finally, it aims to measure the degradation of bus battery performance
over time, predict their useful life, and anticipate details regarding
their maintenance.

<figure>
<img src="media/image_015_image4.jpg" style="max-width: 75%; height: auto;"/>
</figure>

> *Figure 2.1.3: MobiSpaces Partners Logos 02*


### Zooming into project

MobiSpaces aims to address the complex challenges of managing mobility
data by providing a trustworthy and privacy-preserving platform that
optimizes data processing for various applications such as intelligent
transportation and vessel tracking. Through decentralized processing and
validation across multiple use cases, MobiSpaces aims to establish a
standard for reliable and sustainable data analytics, fostering growth
in the EU digital economy.

### Alida in the project

From the management point of view, this work was divided in five
different tasks, one for each use case: Task 6.2 (iRoute -- Intelligent
Public Transport Routing), Task 6.3 (SmartSense -- Intelligent
Infrastructure Traffic Sensing), Task 6.4 (MT

Tracker -- Edge-powered Vessel Tracking), Task 6.5 VesselEdge (Edge
Computing Onboard of Moving Vessel) and Task 6.6 (CrowdSeaMapping--
Federated Learning for Enhancing Nautical Charts).

In particular, for iRoute, use case deals with data governance,
management and analysis for public transport applications, especially in
electric buses field AMT, public transport company in the city of
Genova, Italy and leader of iRoute use case, has identified two real
scenarios to exploit the research of MobiSpaces, applying it to
challenging situations of public transport management, that can be
optimized thanks to a right usage of the big amount of data collected
everyday by AMT.

The scenarios allow to take advantage of the MobiSpaces outcomes and
exploit the mobility-aware data governance framework to drive strategic
decisions based on the outcomes of the analytics.

The use case is set in the electric-vehicle environment that is growing
in AMT: the e-bus fleet includes more than 100 buses, with the related
operational and managerial issues given by the complexity of the
electric system, from bus recharging to battery decay.

The first scenario is about predictive maintenance of electric buses and
aims to anticipate possible faults, thanks to the machine learning
techniques studied in the project. The second scenario deals with
battery level management and aims to give an instrument to re-build bus
schedules, both real-time and long-term, given predictions on battery
duration based on the data analysed and on the expected battery decay.

<figure>
<img src="media/image_043_image5.jpg" style="max-width: 75%; height: auto;"/>
</figure>

> *Figure 2.1.4:  MobiSpaces Contribution 01*

Together with the already quoted machine learning techniques, many
MobiSpaces components are working for use case 1, as explained in detail
in the paragraphs below. The starting datasets are mostly internal to
AMT, and are:

- AVM (Automatic Vehicle Monitoring) data, that show real-time the
  positioning of each bus of the fleet and afterwards the trajectory
  travelled by the bus.

- GTFS data, that contain the planned transit service in an open
  de-facto standard used by Public Transport Operators.

- CanBus data, that collect information about the status of many bus
  systems including battery level, using FMS standard.

These internal data will be interlinked with external data, relevant for
battery level, such as weather data or the elevation and the gradient of
the path.

The internal data are usually located and stored on internal servers. A
mission of the use case, detailed later in the deliverable, is to create
a good, efficient and sustainable data path for the datasets described.

> ## CyberSEAS

<figure>
<img src="media/image_044_image6.jpg" style="max-width: 50%; height: auto;"/>
</figure>

> *Figure 2.2.1: CyberSEAS Project Logo*


| **Type** | **Start Date** | **End Date** |  **ENG Grant Amount** |  **PM** |
| --- | --- | --- | --- | --- |
| FML | 1 Octo 2021 | 30 Sept 2024 | €722264,38 | x |

> *Table 2.1.4: CyberSEAS Project Info*


### Partners

<figure>
<img src="media/image_045_image7.jpg" style="max-width: 75%; height: auto;"/>
</figure>

> *Figure 2.2.2: CyberSEAS Partners Logo*


| **Partner Name** | **Acronym** | **Country** |
| --- | --- | --- | 
| Engineering Ingegneria Informatica S.p.A.   | ENG         | Italy       |
| Consorzio Interuniversitario Nazionale per l'Informatica  | CINI        | Italy       |
| Airbus Potect GMBH                            | AIRP        | Germany     |
| Fraunhofer Gesellschaft zur Fonderung der Angewandten Forschung EV     | FGFR        | Germany     |
| Guardtime                                     | GT          | Estonia     |
| Ikerlan S. COOP                               | IKS         | Spain       |
| Informatika Informacijske Storitve in Inzeniring DD        | IIS         | Slovenia    |
| Rheinisch-Westfaelische Technische Hochschule Aachen | RWTG        | Germany     |
| Software Imagination &Vision SRL              | SIV         | Romania     |
| Software Quality System SA                    | SQS         | Spain       |
| STAM SRL                                      | STAM        | Italy       |
| Synelixis Lyseis Pliroforikis                 | SLPA        | Greece      |
| Automatismou & Tilepikoinonion Anonimi Etairia       | ATAE        | Greece      |
| Wing ict Solutions Technologies Pliroforikis kai Epikoinonion Anonimi Etaireia  | WSTP        | Greece      |
| Ziv Aplicaciones y Tecnologia SL              | ZAT         | Spain       |
| Comune di Berchidda                           | CDBE        | Italy       |
| Comune di Benetutti                           | CDBT        | Italy       |
| Eles doo Operater Kombiniranega Prenosneg in Distribucijskega Elektroenergetskega Omrezja | EOKP        | Slovenia    |
| Petrol Slovenska Energetska Druzba dd  Ljubljana         | PSED        | Slovenia    |
| Akademska in Raziskovalns Mreza Slovenije     | ARMS        | Slovenia    |
| Hrvatski Operator Prijenosnog Sustava D.D.  | HOPS        | Croatia     |
| Enerim OY                                     | ENER        | Finland     |
| Elektrilevi OU                                | ELL         | Estonia     |
| Compania Nationala de Trasport al Energiei Electrice Transelectrica SA   | CNTE        | Romania     |
| Centrul Roman al Energiei                     | CRE         | Romania     |
| Timelex                                       | TML         | Belgium     |
| Operato DOO                                   | OPER        | Slovenia    |
|                                               |             |             |

> *Table 2.2.1: CyberSEAS Partners*

### Overview

The benefits of using *Federated Machine Learning (FML)* include the
ability to train models on distributed data without having to centralize
them, ensuring data privacy and reducing the risk of transmitting
sensitive information.

Within the CyberSEAS project we worked on a use case in the field of
*Social Engineering Detection*, in particular in training intelligent
models to detect fraudulent emails from the analysis of its text.

The FML therefore allowed us to create a *text classification* model for
emails in a collaborative and secure way, without compromising the
confidentiality of the personal data contained in the emails themselves.

### Zooming into Project

The move towards more agile, connected, intelligent and data-driven
energy systems, and their interconnection with our day-to-day lives,
means that there is a major increase in cyber exposure of energy systems
leading to major safety and privacy incidents.

The EU-funded CyberSEAS project improves the resilience of energy supply
chains by protecting them from disruptions generated by complex attack
scenarios.

CyberSEAS delivers an open and extendable ecosystem of 30 customisable
security solutions providing effective support for key activities, such
as risk assessment; interaction with end devices; secure development and
deployment; real-time security monitoring; skills improvement and
awareness; and certification, governance and cooperation. CyberSEAS
solutions will be validated through experimental campaigns consisting of
numerous attack scenarios.

### Alida in the Project

The adopted solution in CyberSEAS is the synergistic use of ALIDA tool,
in pair with SED (Social Engineering Detection).

ALIDA (Advanced Learning and Integration for Data Analysis) is a
platform designed for federated machine learning and big data analytics.
It facilitates secure, scalable, and privacy-preserving machine learning
across distributed datasets. The platform supports various machine
learning frameworks and provides tools for developing, registering, and
managing BDA services.

SED (Social Engineering Detection): The SED tool focuses on detecting
social engineering and phishing attempts through comprehensive analysis
of email headers, body content, and attachments.

Most existing FML-enabled platforms support only a few open-source
frameworks/libraries available to support the development/integration of
FML-based algorithms. On the other hand, the solution integrated within
the ALIDA asset wants to be able to support as many existing libraries
and frameworks as possible, and in such a way as to be able to perform
its own federation tasks quickly, thanks also to the support of a
cloud-side graphical interface, and by exploiting/re-utilizing the
algorithms made and already available within the ALIDA catalogue.

ALIDA leverages FLOWER (Federated Learning Over Wireless Networks) \[4\]
federated learning framework because of its flexibility,
customizability, interoperability, and easiness of use. Its design
integrates workflows independent of the ML/DL framework (PyTorch,
TensorFlow, etc.) with minimum performance overhead. It supports a wide
range of machine learning algorithms, including deep learning,
reinforcement learning and classical machine learning. It also includes
model aggregation and fault tolerance, which are critical components of
any federated learning system. Flower allows building scalable federated
learning systems that can be deployed on a range of devices, including
mobile phones, edge devices, and cloud servers.

The CyberSEAS federated and self-sovereign data analytics infrastructure
has been built starting from the ALIDA platform, one of the tools made
available in the CyberSEAS toolset. ALIDA (https://home.alidalab.it/) is
a Data Science (DS) and ML platform based on advanced frameworks and
open-source technologies for design, deployment, execution and
monitoring of both stream and batch Big Data Analytics (BDA) workflows.

ALIDA is cloud-native, so it is able to scale computing and storage
resources thanks to a pipeline orchestration engine that leverages the
capabilities of Kubernetes for cloud resource management. ALIDA provides
an extensible catalogue of BDA services (the building blocks of the BDA
Application) which covers all phases, from ingestion to preparation, to
ML analysis and for data publishing.

The reference framework used to enable FML between multiple client nodes
and an aggregator node is Flower, a unified approach to federated
learning, analytics, and evaluation. As shown in the next *Figure 2.2.3:
FML Architecture Flow in ALIDA platform*, ALIDA allows federated model
training, so that users can train models without the need to expose
data.

<figure>
<img src="media/image_046_image8.jpg" style="max-width: 75%; height: auto;"/>
</figure>

> *Figure 2.2.3: FML Architecture Flow in ALIDA platform*

Among the few open-source technologies that enable FML, Flower has been
chosen for the following features:

1.  Scalability: it was built to enable real-world systems with many
    clients

2.  ML Framework Agnostic: it's compatible with most existing and future
    machine learning frameworks such as PyTorch, Keras, SK-Learn

3.  Cloud, Mobile, Edge & Beyond: it enables research on all kinds of
    servers and devices, including mobile

4.  Research to Production: it enables ideas to start as research
    projects and then gradually move towards production deployment with
    low engineering effort and proven infrastructure

5.  Platform Independent: it's interoperable with different operating
    systems and hardware platforms to work well in heterogeneous edge
    device environments

6.  Usability: it's easy to get started with code examples for different
    frameworks.

Starting from the Flower framework, templates have been created for a
new pair of BDA services areas for ALIDA platform: FML Aggregator and
FML Participant areas, thus based on specific modules for the
micro-service to be ALIDA compliant, being able to integrate and use at
the same time all the features provided by Flower.

> ## CiTrace


<figure>
<img src="media/image_047_image9.jpg" style="max-width: 35%; height: auto;"/>
</figure>

> *Figure 2.3.1: CiTrace Project Logo*


| **Type** | **Start Date** | **End Date** | **ENG Grant Amount** | **PM** |
| --- | --- | --- | --- | --- |
| FML | 1 June 2021 | 1 May 2024 | n.a. | n.a. |

 > *Table 2.3.1: CiTrace Project Info*

### Partners

![image_048_image10.jpg](media/image_048_image10.jpg)

> *Figure 2.3.2: CiTrace Partners Logo*

| **Partner Name**  | **Acronym** | **Country** |
| --- | --- | --- |
| Engineering Ingegneria Informatica S.p.A.     |       ENG   |       Italy |
| EHT    |                                              EHT |         Italy|
| Oranfresh   |                                         ORF |         Italy|

> *Table 2.3.2: CiTrace Partners*

### Overview

The CiTrace project proposes a reinterpretation of the concept of
traceability in the Agrifood sector, offering a data-centric solution
that views the product as an Information Vector along the entire
production chain, from the field to the final consumer.

This Information Vector progressively enriches its informational content
by leveraging all available information sources continuously. Applied to
the citrus supply chain, the CiTrace solution acts as a concentrator of
harmonized information, on which a set of Value-Added Services and
specific tools can be built for the different phases of the supply
chain, benefiting all involved stakeholders.

### Zooming into Project

In the context of an agri-food project, Alida will be used to provide:

The Flexible and Optimal Pricing Strategy service is calculated
considering three main indicators: production cost, selling price, and
brand reputation. Once all necessary information and values are
obtained, the result of executing the pipeline is a dataset that
indicates the optimal and flexible pricing strategy.

Evaluating the shelf life of products along the supply chain through
mathematical models and Machine Learning algorithms, aiming to obtain a
trained model representing the added value of Dynamic Shelf-Life
Assessment.

In defining the optimal distribution strategy, a fundamental role is
played by analyzing data collected along the entire supply chain. This
service is obtained by calculating and combining three indices: market
penetration rate, inventory turnover, and order fulfilment. The Optimal
Distribution Strategy model will be the result of training a Machine
Learning algorithm based on these data.

> ## BD4NRG

<figure>
<img src="media/image_058_image11.jpg" style="max-width: 35%; height: auto;"/>
</figure>
> *Figure 2.4.1: BD4NRG Project Logo*

| **Type** | **Start Date** | **End Date** | **ENG Grant Amount** | **PM** |
| --- | --- | --- | --- | --- |
| ML-OPS | 1 Janu 2021 | 1 Dece 2023 | € 833 000,00 | n.a.|

> *Table 2.4.3: BD4NRG Project Info*

### Partners

<figure>
<img src="media/image_059_image12.jpg" style="max-width: 75%; height: auto;"/>
</figure>

> *Figure 2.4.2: BD4NRG Partners Logos*

| **Partner Name**                           | **Acronym** | **Country**   |
| --- | --- | --- | 
| Engineering Ingegneria Informatica  S.p.A.       | ENG         | Italy         |
| Ethnicon Metsovion Polytechnion            |      EMP       |      Greece        |
| Rheinisch-Westfaelische Technische Hochschule Aachen        | RWTHA       | Greece        |
| European Dynamics Luxembourg SA            | EDL         | Luxemburg     |
| International Data Spaces EV               | IDS         | Germany       |
| European Network of Transmission System  Operators for Electricity Aisbl | ENTSO       | Belgium       |
| Panepistimio Dytikis Attikis               | PDA         | Greece        |
| Atos Ppain SA                              | ATOS        | Spain         |
| Fundacion Cartif                           | FC          | Spain         |
| Univerza v Ljubljani                       | UNIL        | Slovenia      |
| Enel x srl                                 | ENEL        | Italy         |
| Rede Electrica Nacional SA                 | REN         | Portugal      |
| Centro de Investigacao em Energia Ren - State Grid SA   | CIER        | Portugal      |
| Uninova-Instituto de Desenvolvimento de Novas Tecnologias-Associacao    | UNINOVA     | Portugal      |
| Enercoutim - Associacao Empresarialde Energia Solar de Alcoutim      | ENERC       | Portugal      |
| Fiware Foundation EV                       | FIWARE      | Germany       |
| Centrica Business Solution Belgium         | CBSB        | Belgium       |
| Nederlandse Organisatie voor Toegepast Natuurwetenschappelijk Onderzoek TNO     | NORNO       | Netherlands   |
| Asm Terni SPA                              | ASM         | Italy         |
| Vides Investiciju Fonds SIA                | VIF         | Latvia      |
| Comsensus, Komunikacije in Senzorika DOO   | COMS        | Slovenia      |
| Holistic Ike                               | HI          | Greece      |
| Interuniversitair Micro-Electrinica Centrum     | IMEC        | Belgium     |
| Terrasigna SRL                             | TER         | Romania       |
| UBIMET GMBH                                | UBIMET      | Austria     |
| Elektro Ljubljana Podjetje Zadistribucijo Elektricne Enerije D.D.              | ELPZ        | Slovenia    |
| Borzen, Operater Trga z Elektriko, D.O.O.       | BORZ        | Slovenia      |
| Ajuantamiento de Sant Cugat del Valles     | ASCV        | Spain         |
| Eles doo Operater Kombiniranega Prenosnega in Distribucijskega Elektroenergetskega Omrezja | EOKP        | Slovenia    |
| E-LEX - Studio Legale                      | ELEX        | Italy         |
| Osmangazi Elektrik Dagitim Anonim Sirketi        | OED         | Türkiye       |
| Veolia Servicios Lecam Sociedad Anonima Unipersonal   | VSLSAU      | Spain       |
| Stichting Egi                              | SEGI        | Netherlands |
| Cintech Solution LTD                       | CSL         | Cyprus      |
| Emotion SRL                                | EMO         | Italy       |

> *Table 2.4.4: BD4NRG Partners*

### Case Overview

BD4NRG envisions to confront big data management challenges for the
energy sector, giving a competitive edge to the European stakeholders to
improve decision making and at the same time to open new market
opportunities.

### Zooming into Project

BD4NRG aims to enable an incremental decentralized energy data-driven
ecosystem and a collaborative data sovereignty driven ecosystem. The
goal is to unlock and exploit the economic potential of big data and
give to Energy Sector stakeholders, the opportunity to improve their
business operational performance.

To achieve this and to address the emerging challenges in big data
management, BD4NRG partners will develop, adapt, deliver and deploy a
distributed big data energy analytics framework - BD4NRG Framework,
consisting of:

- Several distributed intelligent collaborative federated nodes, the
  BD4NRGData Hubs

- A graphically enriched Open Modular Big Data Analytics Energy Toolbox

- A scalable big-data energy analytics environment

BD4NRG will combine DLTs/blockchain technologies with edge processing,
Federated Machine Learning and Artificial Intelligence, to operate the
data-driven energy ecosystem. Also, the project will make extensive
adoption of open sources technology components and tools and Open APIs.

The BD4NRG Framework will include 4 horizontal and 1 vertical (cyber
security) layer:

**Data Governance Layer**

A necessary middleware to act as a mediator between data users and data
providers who may want to decide case by case whether to disclose their
data or not. State of the art solutions to guarantee traceability,
provenance tracking and accountability but guaranteeing confidentiality
as well.

**Scalable Big Data Management & Processing Layer**

Smart management and processing of data by an intelligent information
broker. The content of multiple data sources, being generated, managed
and stored in the data management systems and the data hubs of the
different operators and actors by innovative components and technology
enablers.

**Applications Layer**

Analytics-centred applications tailoring power network improved
cross-functional decision-making to improve power network reliability,
optimize management of flexibility assets, address building-scale energy
efficient comfort management and dynamic situated renewable investment
risk assessment.

1.  Open Modular Smart Grid Big Data Analytics Toolbox: User-friendly
    with modern vision of the data analytics Toolbox, providing a
    working space for self-service capabilities that give autonomy to
    the end-user combining data that come from different sources.

2.  Data / Models / Resources Marketplace: A virtual workbench with a
    variety of assets, including data, third party services, machine
    learning models, computing resources and storage resources as
    tradable assets providing off the shelf tools, library of reusable
    AI-based machine learning models, external off-domain data sets and
    reusable data-driven analytics applications.

**Cyber Security - Data Privacy Layer**

A vertical layer to establish user authentication and authorisation to
secure the non-open data of the transaction as well as to comply with
the EC regulation on Data Protection

### Alida in the Project

BD4NRG aims to develop data analytics services capable to analyse data
in a seamless and holistic fashion, across multiple data sources. Among
the existing efforts analysed, ALIDA BDA platform has been selected as a
starting point for the BD4NRG Analytics Toolbox and it will be extended
and validated in the energy domain, according to the needs that emerged
in the requirements elicitation phase of the project. ALIDA embraces the
paradigm of BDA-as-a-service (BDAaaS). Besides relevant cost savings,
the provision of Big Data analytical capabilities using the cloud
delivery model could ease the adoption of the toolbox and could simplify
useful insights with different kinds of competitive advantage. BDAaaS
consists of as a set of automatic tools and methodologies that allows
users lacking Big Data expertise to manage BDA and deploy big data
pipeline applications ready-to-be-executed addressing their goals at
edge/fog/cloud nodes.

<figure>
<img src="media/image_060_image13.jpg" style="max-width: 50%; height: auto;"/>
</figure>

> *Figure 2.4.3: ALIDA general architecture for BD4NRG* 

The ALIDA platform supports full orchestration of BDA application
workflows and allows for composition, deployment and execution of
workflows (either batch or stream) of BDA applications. *Figure 2.4.3*
describes the ALIDA general architecture.

> ## SCREAM

<figure>
<img src="media/image_061_image14.jpg" style="max-width: 35%; height: auto;"/>
<figcaption><p>Figure 2.4.3</p></figcaption>
</figure>

> *Figure 2.5.1: SCREAM Project Logo*

| **Type** | **Start Date** | **End Date** | **ENG Grant Amount**  | **PM**|
| --- | --- | --- | --- | --- |
| CLOUD-EDGE | 1 July 2020 | 30 June 2023 | n.a. | n.a.|

> *Table 2.5.5: SCREAM Project Info*

### Partners

<figure>
<img src="media/image_062_image15.jpg" style="max-width: 75%; height: auto;"/>
</figure>

> *Figure 2.5.2: SCREAM Partners Logo*


| **Partner Name**                           | **Acronym** | **Country**   |
| --- | --- | --- | 
| Engineering Ingegneria Informatica S.p.A.    | ENG         | Italy       |
| Eka Srl                                    | EKA         | Italy       |
| IPREL Progetti Srl                           | IPREL       | Italy       |

> *Table 2.5.6: SCREAM Partners*

### Case Overview

The SCREAM project proposes to study, define, design and implement an
integrated, modular, flexible and adaptable platform for building
dedicated solutions for the remote and optimised monitoring, maintenance
and management of machines (Monitoring and Control - M&C) and production
equipment (e.g. to predict equipment failures and determine solutions
before they occur).

The platform will allow machine problems to be diagnosed (or predicted)
and resolved via secure remote access, without the need for an on-site
visit.

An open-source GUI for data visualization and exploration was made
available on the cloud to consult both the stored historical data and
the predictions obtained from the ML models trained on the consumption
of the cutting blade and number of cuts; other ML/DL models for
predictive maintenance and decision support were exported and used
within applications run on the Sofidel company's own machines, applied
to real-time data.

<figure>
<img src="media/image_063_image16.jpg" style="max-width: 75%; height: auto;"/>
</figure>

> *Figure 2.5.3: SCREAM Contribution 01*

### Zooming into Project

The solutions proposed in the project will be based on Big Data and
Artificial Intelligence and will consider the specific characteristics,
peculiarities, needs and requirements of the production environment and
the organisations using the production equipment and machines.
Furthermore, special attention will be given to the specific business
relationship that exists between the manufacturer/supplier and the
various users (goods producing industries).

Engineering is the Project Coordinator and is responsible for all
activities linked to the definition of the SCREAM Framework. Engineering
is also working on Big Data Infrastructure for remote and secure "M&C"
systems, aiming to define the infrastructure for Industrial Big Data
Analytics based on a hybrid edge-cloud model and a complete toolkit of
algorithms and analysis techniques to support machine analyses. Moreover
Engineering takes care of the design of application services for the
remote "M&C" systems of production machinery, with the aim of offering
advanced services to support decision making.

### Alida in the Project

In the example, the company Sofidel (producer of paper for hygienic and
domestic use) sends IoT data in streaming to ALIDA through an
asynchronous MQTT messaging protocol. This data includes information
from machinery (embosser, rewinder, cutter blade, unwinder) for paper
production.

In ALIDA, both **BDA App** streaming for the *data acquisition* and
*data preparation,* and *batch* for pre-process and generate ML/DL
models based on data stored within distributed data storage.

> ## Infinitech


<figure>
<img src="media/image_064_image17.png" style="max-width: 40%; height: auto;"/>
</figure>

> *Figure 2.6.1: Infinitech Project Logo*

| **Type** | **Start Date** | **End Date** | **ENG Grant Amount**  | **PM**|
| --- | --- | --- | --- | --- |
| ML-OPS |      1 Octo 2019 |  31 Marc 2023  |        n.a.|            n.a.|

> *Table 2.6.7: Infinitech Project Info*

### Partners

<figure>
<img src="media/image_065_image18.jpg" style="max-width: 75%; height: auto;"/>
</figure>

> *Figure 2.6.2: Infinitech Partners Logo 01*


| **Partner Name**                           | **Acronym** | **Country**   |
| --- | --- | --- | 
| Engineering Ingegneria Informatica S.p.A.    | ENG         | Italy       |
| Atos Spain Sa                          | ATOS        | Spain         |
| Ibm Israel - Science And Technology Ltd   | IBM         | Israel        |
| Fujitsu Technology Solution            | FUJITSU     | France        |
| Hewlett Packard Italiana Srl           | HP          | Italy         |
| Singularlogic Anonymi Etaireia Pliroforiakon Systimaton Kai Efarmogonpliroforikis         | SAEP        | Greece        |
| Innovation Sprint                      | IS          | Belgium       |
| Santander Uk Plc                       | SAN         | United Kindom |
| Sia Spa                                | SIA         | Italy         |
| Unicaja Banco Sa                       | UB          | Spain         |
| National Bank Of Greece Sa             | NBG         | Greece        |
| Aktif Yatirim Bankasi As               | AYB         | Türkiye       |
| Banka Slovenije                        | BS          | Slovenia      |
| Banking & Payments Federation Ireland Company Limited By Guarantee  | BPFI        | Ireland       |
| Dynamis Ae Genikon Asfaleion           | DAGA        | Greece        |
| Genillard & Co Gmbh                    | GEN         | Germany       |
| Jrc Capital Management Consultancy & Research Gmbh   | JRC         | Germany       |
| Prive Services Europe Gmbh             | PSE         | Austria       |
| Crowdpolicy Psifiakes Symmetoxikesypiresies                   | CPSI        | Greece        |
| Poste Italiane - Spa                     | PI          | Italy         |
| Wenalyze                                 | WEN         | Spain         |
| Paris Europlace                          | PE          | France        |
| Copenhagen Fintech                       | CF          | Denmark       |
| Reportbrain Limited                      | RL          | United Kingdom       |
| Leanxcale Sl                             | LEAN        | Spain         |
| Gioumpitek Meleti Schediasmos Ylopoiisi Kai Polisi Ergon Pliroforikis Etaireia Periorismenis Efthynis | GMSY        | Greece        |
| Innov-Acts Limited                       | IAL         | Cyprus        |
| Unparallel Innovation Lda                | UI          | Portugal      |
| Roessingh Research And Development Bv    | RRAD        | Netherlands   |
| Etam Anonymh Etaireia Symboyleytikon Kai Melethtikon Ypireseion | EAES        | Greece        |
| Fondazione Bruno Kessler                 | FBK         | Italy         |
| University Of Galway                     | UG          | Ireland       |
| Uninova-Instituto De Desenvolvimento De Novas Tecnologias-Associacao | UID         | Portugal      |
| Bogazici Universitesi                    | BU          | Türkiye       |
| Institut Jozef Stefan                    | IJS         | Slovenia      |
| Edex - Educational Excellence Corporation ltd            | EDEX        | Cyprus        |
| University Of Glasgow                    | UG          | United Kingdom       |
| Association O.R.T                        | ORT         | France        |
| Fundacion Para La Promocion De La Innovacion Investigacion Y Desarrollo Tecnologico En La Industria De Spain  Automocion De Galicia     | FPLAPDLI    |     Spain     |
| Fundacion Centro Tecnoloxico De Telecomunicacions De Galicia          | FCT         | Spain         |
| Dwf Germany Rechtsanwaltsgesellschaft  Mbh  | DWF         | Germany       |
| Abi Lab-Centro Di Ricerca E Innovazione Per La Banca    | ABILAB      | Italy         |
| Bank Of Cyprus Public Company Ltd        | BCP         | Cyprus        |
| Caixabank Sa                             | CAIXA       | Spain         |
| Agricultural Applications Ike            | AAI         | Greece        |
| University Of Piraeus Research Center    | UPRC        | Greece        |
| Assentian Europe Limited                 | AEL         | Ireland       |
| Clear Communication Associates Ltd       | CCAL        | United Kingdom       |
| Inneurope Initiative S.L.                | IISL        | Spain         |
| The Governor And Company Of The Bank Of Ireland | BOI         | Ireland       |
| Traffikanalysis Hub Limited              | THL         | United  Kingdom      |
| Nexi Payments Spa                        | NEXI        | Italy         |

> *Table 2.6.8: Infinitech Partners 01*

### Case Overview

Poste Italiane sends data related to banking transactions to ALIDA,
which, through the BDA App, trains a model for outlier classification.

This model is then deployed and used on a graphical user interface (UI)
to provide a probability (to a domain expert) that new transactions were
fraudulent.

The same interface is also utilized to gather feedback from the domain
expert, which is useful for enriching the labelling of data, thus making
the model increasingly performing with each training iteration. See
*Figure 2.6.3: Infinitech Contributions 01*


<figure>
<img src="media/image_067_image19.jpg" style="max-width: 75%; height: auto;"/>
</figure>

> *Figure 2.6.3: Infinitech Contributions 01*

### Zooming into Project

Emerging technologies such as big data, artificial intelligence (AI) and
the internet of things (IoT) all have the potential to revolutionise how
we live, work and play. But tapping into that potential first requires
knowing how to use them -- something that for the financial and
insurance industry can be easier said than done.

"Many financial and insurance institutions still face difficulties using
big data technology due to complicated regulations and a lack of
appropriate test bed resources," says Maurizio Ferraris, innovation
manager at GFT Italia.

With the support of the EU-funded INFINITECH project, GFT, together with
a consortium of over 40 fintech partners, are working to lower the
barriers to datadriven innovation, boost regulatory compliance and
stimulate investment.

In a nutshell, ALIDA is a Micro-service based platform for composition,
deployment, optimisation, execution and monitoring of pipelines of Big
Data Analytics (BDA) services. ALIDA is a result of previous research
activities developed by ENG. Currently, it is a work in progress. ALIDA
offers a catalogue of BDA services (ingestion, preparation, analysis,
visualization): user designs his own (stream/batch) pipeline by choosing
the BDA services from it, indicates which Big Data set he wants to
process, launches and monitors the execution of the pipeline and
personalizes the results visualization by choosing from a set of
available graphs, all this without worrying about having software
developer skills or particular knowledge on big data technologies. This
service is registered in ALIDA catalogue as Spring Boot Application
containing the python code and its dependencies. After implementing the
algorithm using Pyspark, creating the Dockerfile and pushing the new
image inside a repository, this microservice is registered into the
ALIDA catalogue through the GUI. Source: https://home.alidalab.it/

ALIDA asset is a microservice based platform for data management and
composition, deployment, optimisation, execution and monitoring of big
data analytics data workflow (covering ingestion, preparation, analysis
and visualization), which has been developed by ENG in previous and
ongoing research activities. The main functionalities of ALIDA are:

- Streaming and Batch data workflow processing

- Catalogue of Big Data Analytics (BDA) services (covering ingestion,
  prepara-tion analysis, visualization) for various data analytics
  scenarios

- Graphical editor for building data workflow

- Data pipeline deployment by means of modern resource orchestrators
  such as Kubernetes

- Workflow execution monitoring

- Data visualization customization through a set of graphs and query
  editor

- Graphical User Interface to easily create and redistribute new custom
  BDAservices.

ALIDA presents a microservice architecture, where microservices are
deployed in containers, whose management is largely simplified by
Kubernetes, a container orchestrator which automates the deployment,
management, scaling, and networking of containers.

Basically, *Figure 2.6.4: Infinitech Contribution 02* shows three flows:
service registration (blue flow), workflow design and execution (red
flow) and visualization (orange flow).

The key flow is the workflow design and execution: by means of the GUI
user designs a workflow and executes it. In this case, the core
components of ALIDA submit the request of execution and deployment of
the workflow to the candidate orchestrator. Currently just Spring Cloud
Data Flow 8 is adopted as pipeline orchestrator in ALIDA.

Spring Cloud Data Flow (SCDF) is a Microservice based Streaming and
Batch data processor that can make use of a variety of container
orchestrators. In the ALIDA platform, the SCDF engine instance uses an
implementation of the Spring Cloud Deployer for Kubernetes. Then,
Kubernetes uses the computation resources available into the platform
and the persistence layer to manage data storage and workloads.

The platform currently supports several frameworks such as Spark, H2O,
Flink, mainly used for BDA service development and registration. Other
frameworks may be deployed, and relevant machine learning libraries
available for Python can be used. It is worth to notice that BDA
services may or may not be implemented working on these frameworks. The
only requirement that the BDA services must match is that they have to
be implemented as a spring boot application shipped within a docker
image that can optionally contain a python application.

In ALIDA, most of the BDA services developed are based on Spark, so they
are able to process a large volume of data, in a distributed
environment. Spark is used for both batch and streaming applications
thanks to Spark Streaming.

Regarding the persistence layer, Hive and Redis play several roles. Hive
is used both to access the data resulting from the execution of the
workflows through the visualization component, and to ensure that SPARK
can write and read the datasets stored into HDFS.

![image_068_image20.png](media/image_068_image20.png)

> *Figure 2.6.4: Infinitech Contribution 02*

Redis is used by ALIDA to store some properties related to the platform
and to serve the visualization component with the aim to create graphs
and visualizations with real time updating capabilities. Last but not
least, Kafka is adopted on various fronts: the platform, the core
component of ALIDA, uses it to transmit and update the properties during
the workflow execution phases. SCDF itself exploits it in the management
of streams pipelines. ALIDA is cloud native software, this means that it
can be seamlessly deployed both in an on-premises environment and on the
cloud environments provisioned by the widely known providers such as
Microsoft Azure, Amazon AWS and Google Cloud Platform. In the context of
the INFINITECH project, ALIDA will be used in Pilot 10 to facilitate the
development of real-time BDA service in the context of Cyber-Security
for financial transactions.

### Alida in the Project

This pilot aims at significantly improving the detection rate of
malicious events (i.e., fraud attempts) and enabling the identification
of security-related anomalies while they are occurring by the analysis
in real-time of the financial transactions of a home and mobile banking
system.

This approach thus allows proactive and prompt interventions on
potential security threats. More specifically, Pilot 10 is developing a
tool based on ML techniques applied to real-time, financial transaction
data-streams focused on adaptive detection for malicious transactions
leveraging on established big-data analytics' practices.

The analysis of vast amounts of data will help to define relevant
cyber-risk rating metrics and allow us to implement adaptive security
measures and controls, based on real cyber-security postures.

*Current implementation status on Pilot 10 is shown in Figure 2.6.5:
Infinitech Contribution 03*.

![image_069_image21.jpg](media/image_069_image21.jpg)

> *Figure 2.6.5: Infinitech Contribution 03*

Poste Italiane create Synthetic and Realistic data set on "Bank Transfer
SEPA" transactions that are consistent with the real data present in the
data operations environment *Figure 2.6.6: Infinitech Contribution 04*.
These data sets are going to be used by Pilot 10 and, more in concrete,
for the first PoC. To develop the services and workflows and ALIDA
instance was deployed on ENG premise. As a Preliminary step: a job to
transfer synthetic data set on "Bank Transfer SEPA" transactions from an
SFTP server to ALIDA HDFS, was designed and it is up and running.

With the data ready to be processed, and using ALIDA, a first Batch
processing/workflow has been created. This workflow converts qualitative
fields into quantitative one, train a KMeans model and makes the
clustering process. The Figure 31:shows developed ALIDA workflow based
on three steps (string-indexer, trains the data with a KMeans models and
the clustering creation).

> After that, the data is grouped and visualized by clusters (*Figure
> 2.6.7: Infinitech Contribution 05*).

Here a domain expert has to label which clusters would be suspicious of
fraud. After that the Stream processing would start labelling and
detecting new incoming data in real time. But this part is not
implemented yet.

![image_070_image22.png](media/image_070_image22.png)

> *Figure 2.6.6: Infinitech Contribution 04*

![image_071_image23.png](media/image_071_image23.png)

> *Figure 2.6.7: Infinitech Contribution 05*

#

> ## OK-INSAID

<figure>
<img src="media/image_072_image24.jpg" style="max-width:40%; height: auto;"/>
</figure>

> *Figure 2.7.1: OK-INSAID Project Logo*

| **Type** | **Start Date** | **End Date** | **ENG Grant Amount**  | **PM**|
| --- | --- | --- | --- | --- |
| CLOUD-EDGE |    1 Nove 2018 |  31 Marc 2022  |        n.a.   |        n.a. |

> *Table 2.7.9:* OK-INSAID Project Info

### Partners

<figure>
<img src="media/image_066_image25.jpg" style="max-width: 75%; height: auto;"/>
</figure>

> *Figure 2.7.2: OK-INSAID Partners Logos*

| **Partner Name**                           | **Acronym** | **Country**   |
| --- | --- | --- | 
| Engineering Ingegneria Informatica S.p.A.    | ENG         | Italy       |
| EKA S.r.l. |     EKA  |         Italy |
| Università degli Studi di Palermo |    UNIPA |         Italy |
| Università del Salento  |   UNISAL |        Italy |
| Consiglio Nazionale delle Ricerche  |    CNR   |        Italy |
| Cefriel |    CEFRIEL |         Italy |
| Tera S.r.l. |      TERA  |        Italy |
| Consorzio Calef  |   CALEF |         Italy |
| GE Avio S.r.l.   |   GEA   |        Italy |
| SACMI |    SACMI |         Italy |

> *Table 2.7.10: OK-INSAID Partners*

### Case Overview

In this case, the SACMI company that create ceramic slabs sends data to
ALIDA in streaming. These data include information about the composition
used for the creation of slabs and the results obtained about the
quality of the stubs produced. ALIDA, through a **streaming BDA App
(1)**, processes, cleans, and stores such data in a distributed store,
fundamental for **Big Data** management.

In a later time, another **BDA App batch (2)** deals with training of a
model based on collected data. An application puts on the edge
(**Prediction**), near the data production site, **downloads from ALIDA
the model** of the produced ML.

This model guides company operators to the composition of the procedure,
based on input parameters.


<figure>
<img src="media/image_001_image26.jpg" style="max-width:75%; height: auto;"/>
</figure>

> *Figure 2.7.3: OK-INSAID Contribution 01*

### Zooming into Project

One of the most widely adopted quality management strategies today is
Zero Defect Manufacturing (ZDM), a new paradigm aimed at surpassing
traditional Six Sigma approaches through knowledge management, supported
by new methodologies, technologies, and integrated tools for
maintenance, quality control, and production logistics.

The general functional requirements of zero-defect manufacturing can be
summarized as a system with the following capabilities:

1.  Data collection via smart sensors,

2.  Automatic signal processing, filtering, and feature extraction,

3.  Data mining and knowledge discovery for diagnosis and prognosis,

4.  Providing clear and concise information and advice on defects to the user,

5. Self-adaptation and optimization control.

ZDM Monitoring systems highlight that, in order to achieve zero defect
manufacturing, new cost-effective tools for monitoring and optimizing
quality with multiple and autocorrelated data should be developed.

Therefore, it is necessary to manage processes in real-time based on
inputs derived from simulation models to provide a clear and detailed
understanding of the entire process and detect all possible causes of
defects.

To achieve such digital representations, it is necessary to build a
detailed and high-precision model capable of providing various options
for identifying optimal product or process parameters.

The suggestion is to adopt Digital Twin technology during the production
phase to optimize production planning and process control.

In SACMI's production, the main components identified to better define
an investigation in this regard concern porosity and the percentage of
average penetration in the welding process.

The algorithms developed to predict the percentage values of penetration
and porosity in laser welding have been uploaded to the online platform
provided by the project, using the Docker system.

### Alida in the Project

The entire predictive analysis pipeline, as designed, implemented, and
extensively documented in previous project reports, consists of five
fundamental steps (pipeline steps, abbreviated as PS):

1.  Pre-processing of datasets, consisting of temporal reordering,
    cleaning, normalization, splitting into train/validation/test, and
    final saving of the divided files. **\[PS1\]**

2.  Model training, exploring different training configurations (e.g.,
    referring to model hyperparameters such as learning rate or the
    number of training epochs, among others, or the type of training);
    finally, saving the weights of the trained model. **\[PS2\]**

3.  Validation of model performance, with the objective of selecting the
    best configuration based on calculated values for specific accuracy
    metrics, such as the well-known precision and recall; finally,
    saving the best parameters. **\[PS3\]**

4.  Testing model performance, to evaluate the quality of predictions
    when they are made on new and unseen data, but whose true value is
    known (i.e., the true welding quality). **\[PS4\]**

5.  Final prediction on completely new data that, according to what
    emerged during the project, are provided by the predictive models
    trained and tested by other partners. **\[PS5\]**

**Services and Application**

The Alida Cloud microservices platform operates on two fundamental
components, namely "**services**" and "**applications**."

Specifically, one or many services constitute an application. The end
user is responsible for launching an application, while the services
represent something abstract and internal to the application itself.

In this context, the 5 PS were transferred and implemented as Python
scripts within services. To achieve this, the PS were first grouped
into:

1.  **Dataset Preparation + Model Training + Validation \[PS1\] +
    \[PS2\] + \[PS3\]** we could call it as **S1;**

2.  **Model Testing \[PS4\] we could call it as S2;**

3.  **Prediction on New Data \[PS5\]** we could call it as **S3.**

The three services implemented on the Alida microservices platform were
transformed into Docker images to make them portable and host them on
the popular Docker image hosting platform known as DockerHub. Indeed, to
create a new service on the Alida Cloud platform, a JSON file containing
all the characteristics and metadata of the service, including the
reference to the Docker image uploaded on DockerHub, must be created.

Thus, a Python script was implemented and released for the partners
involved in predictive analysis through the Alida Cloud platform,
designed to generate the JSON configuration file.

Having uploaded the services as Docker images on DockerHub and generated
the JSON files containing the metadata for each service, it was possible
to create and upload the services on the Alida Cloud platform. They can
be found on the platform as:

**\[S1\] poliba-fit-3-0** - *Figure 2.7.4: OK-INSAID Contribution 02*
shows a screenshot of the parameters required by the service.

**\[S2\] poliba-test-3-0** - *Figure 2.7.5: OK-INSAID Contribution 03*
shows a screenshot of the parameters required by the service.

**\[S3\] poliba-predict-3-6** - *Figure 2.7.6: OK-INSAID Contribution
04* shows a screenshot of the parameters required by the service.

Finally, as indicated previously, the three services were grouped to
form two applications (named A1 and A2):

**\[A1\]** comprising S1+S2, for pre-processing, training, and testing -
*Figure 2.7.7: OK-INSAID Contribution 05* shows a screenshot of the
execution of application A1.

**\[A2\]** comprising S3, consisting of prediction on new data - *Figure
2.7.8: OK-INSAID Contribution 06* shows a screenshot of the execution of
application A2.


<figure>
<img src="media/image_002_image27.jpg" style="max-width: 100%; height: auto;"/>
</figure>

> *Figure 2.7.4: OK-INSAID Contribution 02*

![image_003_image28.jpg](media/image_003_image28.jpg)

> *Figure 2.7.5: OK-INSAID Contribution 03*

![image_004_image29.jpg](media/image_004_image29.jpg)

> *Figure 2.7.6: OK-INSAID Contribution 04*

![image_005_image30.jpg](media/image_005_image30.jpg)

> *Figure 2.7.7: OK-INSAID Contribution 05*

![image_006_image31.jpg](media/image_006_image31.jpg)

> *Figure 2.7.8: OK-INSAID Contribution 06*

#

> ## ICARUS

<figure>
<img src="media/image_007_image32.jpg" style="max-width:40%; height: auto;"/>
</figure>


> *Figure 2.8.1: ICARUS Project Logo*

| **Type** | **Start Date** | **End Date** | **ENG Grant Amount**  | **PM**|
| --- | --- | --- | --- | --- |
| ML-OPS |      1 Janu 2018 |  30 June 2021  |        n.a.   |         n.a. |

> *Table 2.8.11: ICARUS Project Info*

### Partners

![image_008_image33.jpg](media/image_008_image33.jpg)

> *Figure 2.8.2: ICARUS Partners Logo*


| **Partner Name**                           | **Acronym** | **Country**   |
| --- | --- | --- | 
| Engineering Ingegneria Informatica S.p.A.    | ENG         | Italy       |
| PACE AEROSPACE ENGINEERING AND INFORMATION TECHNOLOGY GMBH |   PACE |        Germany |
| SUITE5 DATA INTELLIGENCE SOLUTIONS LIMITED  |  SUITE5 |        Ireland |
| UNIVERSITY OF CYPRUS |    UNICYP |        Cyprus |
| CINECA CONSORZIO INTERUNIVERSITARIO |     CCI  |         Italy |
| OAG AVIATION WORLDWIDE LIMITED |     OAG |          UK |
| SINGULARLOGIC ANONYMI ETAIREIA PLIROFORIAKON SYSTIMATON KAI EFARMOGONPLIROFORIKIS |   SINGUL |        Greece |
| ISTITUTO PER L'INTERSCAMBIO SCIENTIFICO |     IIS  |        Italy |
| CELLOCK LTD |   CELLOCK |      Cyprus |
| ATHENS INTERNATIONAL AIRPORT S.A. |     AIA   |      Greece |
| SUITE5 DATA INTELLIGENCE SOLUTIONS Ltd |    SDIS |        Cyprus |

> *Table 2.8.12: ICARUS Partners*

### Case Overview

The European aviation industry faces a surge of multi-source and
multi-lingual data. The EU-funded ICARUS project will build a novel data
value chain in aviation-related sectors aimed at data-driven innovation
and collaboration across industry players. Using methods such as big
data analytics, deep learning, semantic data enrichment and
blockchain-powered data sharing, ICARUS aims to develop a multi-sided
platform allowing integration and deep analysis of data for EU-based
companies, organisations and scientists. ICARUS will bring together the
aerospace, tourism, health, security, transport, retail, weather and
public sectors and accelerate their data-driven collaboration.

### Zooming into Project

Industries of all types are using the power of big data and analytics to
fundamentally transform how they do business. The notable exception is
the aviation industry. In fact, there is currently little data diffusion
and sharing between the different stakeholders of the aviation-related
sectors.

"The European aviation industry needs to leverage the surge of
multisource data in order to gain augmented intelligence and open the
door to a range of unprecedented services," says Dimitrios Alexandrou,
business innovation director at UBITECH, a Greek technology company.

With a focus on building a data value chain, the EU-funded ICARUS
(Aviation driven Data Value Chain for Diversified Global and Local
Operations) project is helping the aviation industry embrace data-driven
innovation. "Using big data analytics, deep learning, data enrichment,
and blockchain-powered data sharing, the ICARUS project aims to deliver
a unique data and intelligence platform for the aviation industry," adds
Alexandrou, who serves as the project coordinator.

A one-stop shop for aviation data and intelligence The objective of the
project

is to conceptualise, design and develop the ICARUS platform. When
finalised, the platform will enable data exploration,
blockchain-empowered sharing, and the brokerage of a large variety of
heterogeneous data sources. It will also serve as a one stop shop for
aviation data and intelligence -- covering the entire big data
lifecycle, from data collection to curation, exploration, integration
and analysis.

"The platform will provide users with a deeper understanding of, for
example, flight optimisation, pollution awareness, tourism operations,
the passenger experience -- even how aviation can cause an epidemic to
spread," explains Alexandrou. "As such, it will be an invaluable tool
for the aviation industry, aviation-related service providers, and other
cross-sectoral stakeholders."

The platform will also serve as a trusted and secure sandbox-style
workspace where users can conduct analytical experiments in a safe and
confidential closedlab environment. "The ICARUS platform aims to address
the security and privacy concerns that have made the aviation industry
and related industries reluctant to leverage big data technologies,"
notes Alexandrou.

According to him, the platform has already received expressions of
interest from a number of external stakeholders.

Enabling data-driven innovation and collaboration Despite some delays
caused by COVID-19, the ICARUS project succeeded in creating a platform
that enables data-driven innovation and collaboration across the
aviation sector.

"The ICARUS platform effectively addresses the industry's reluctance to
explore, curate, share, trade, integrate and deeply analyse big data in
a trusted and fair manner," concludes Alexandrou. "In other words, it
provides the big data that will drive the design and implementation of
the innovative new services that will disrupt the aviation industry."

The platform will soon be available in beta format. Project researchers
are currently exploring the best business plan for bringing the platform
to market.

#

> ## Agritech

<figure>
<img src="media/image_009_image34.png" style="max-width:30%; height: auto;"/>
</figure>


> *Figure 2.9.1: Agritech Project Logo*

| **Type** | **Start Date** | **End Date** | **ENG Grant Amount**  | **PM**|
| --- | --- | --- | --- | --- |
| ML-OPS |       Dec 2021 |   May 2024 |           n.a. |           n.a. |

> *Table 2.9.13: Agritech Project Info*

### Partners

![image_010_image35.png](media/image_010_image35.png)


> *Figure 2.9.2: Agritech Partners Logo*


| **Partner Name**                           | **Acronym** | **Country**   |
| --- | --- | --- | 
| Engineering Ingegneria Informatica S.p.A.    | ENG         | Italy       |
| Consiglio Nazionale delle Ricerche          | CNR         | Italy       |
| Università degli Studi di Bari              | UNIBA       | Italy       |
| Alma Mater Studiorum -- Università di Bologna      | UNIBO       | Italy       |
| Università degli Studi di Milano            | UNIMI       | Italy       |
| Università di Napoli Federico II            | UNINA       | Italy       |
| Università di Padova                        | UNIPD       | Italy       |
| Università di Siena                         | UNISI       | Italy       |
| Università degli Studi di Torino            | UNITO       | Italy       |
| Centro Euro-Med sui Cambiamenti Climatici   | CMCC        | Italy       |
| Consiglio per la ricerca in agricoltura e l'analisi dell'economia agraria    | CREA        | Italy       |
| New Technologies, Energy and Sustainable Economic Development                | ENEA        | Italy       |
| Fondazione Edmund Mach                      | FEM         | Italy       |
| Politecnico di Milano                       | POLIMI      | Italy       |
| Politecnico di Torino                       | POLITO      | Italy       |
| Scuola Superiore Sant'Anna                  | SSSA        | Italy       |
| Università degli Studi della Basilicata     | UNIBAS      | Italy       |
| Università di Bolzano                       | UNIBZ       | Italy       |
| Università Campus Bio-Medico di Roma        | UCBM        | Italy       |
| Università Cattolica del Sacro Cuore        | UCSC        | Italy       |
| Università di Catania                       | UNICT       | Italy       |
| Università di Foggia                        | UNIFG       | Italy       |
| Università di Firenze                       | UNIFI       | Italy       |
| Università degli Studi di Genova            | UNIGE       | Italy       |
| Università di Perugia                       | UNIPG       | Italy       |
| Università di Pisa                          | UNIPI       | Italy       |
| Università di Parma                         | UNIPR       | Italy       |
| Università di Reggio Calabria               | UNIRC       | Italy       |
| Sapienza Università di Roma                 | UNIROMA     | Italy       |
| Università di Salerno                       | UNISA       | Italy       |
| Università di Sassari                       | UNISS       | Italy       |
| Università di Udine                         | UNIUD       | Italy       |
| Università delle Marche                     | UNIVPM      | Italy       |

> *Table 2.9.14: Agritech Partners*

### Case Overview

As part of a project within the National Recovery and Resilience Plan
(PNRR), there is a need for a use case to train a model that, based on
the movements of a cow (monitored through an IoT collar), validates
whether the growth occurs outdoors or indoors in a stable.

In addition to creating the ML model and managing its entire lifecycle,
ALIDA will also validate satellite data on a blockchain and provide
analytical results to a traceability system that will expose the outcome
during the scanning phase of the QR code displayed on the finished
product.

<figure>
<img src="media/image_011_image36.jpg" style="max-width: 75%; height: auto;"/>
</figure>

> *Figure 2.9.3: Agritech Contribution 01*

### Zooming into Project

In the context of an \*\*Agritech\*\* project, ALIDA can offer tools and
methods to efficiently manage and analyze large amounts of agricultural
data. Here's how you could use ALIDA in an Agritech project (*Figure
2.9.3: Agritech Contribution 01*):

1.  Data Collection and Preprocessing

ALIDA can assist in collecting data from various sources such as IoT
sensors, satellite images, and existing databases. Additionally, it
provides tools for data preprocessing:

- Data Cleaning: Removing missing or anomalous data.

- Data Normalization: Adjusting data to ensure uniformity.

- Data Integration: Combining data from different sources.

2.  Data Analysis

ALIDA offers numerous algorithms for analyzing agricultural data:

- Statistical Analysis: To understand trends in crop yield data, climate
  data, etc.

- Predictive Analysis: Using machine learning models to predict crop
  yields, plant diseases, and other relevant metrics.

- Spatial Analysis: For analyzing geographic data, such as land maps and
  crop distribution.

3.  Data Visualization

Effectively visualizing data is crucial for making informed decisions.
ALIDA provides tools to create:

- Interactive Charts: To dynamically explore data.

- Thematic Maps: To visualize crop distribution, soil moisture, and
  other geospatial variables.

- Customized Dashboards: To monitor key metrics in real-time.

4.  Process Automation

In the context of Agritech, automation can increase efficiency:

- Automated Data Collection: Using sensors and drones to collect data
  automatically.

- Automated Analysis: Configuring analysis pipelines that automatically
  perform predictive analyses on new data.

- Automated Decision-Making: Implementing decision support systems that
  use analysis results to suggest actions.

5.  Specific Applications

    - Crop Monitoring: Using sensor data and satellite images to monitor
      crop health and identify issues early.

    - Irrigation Management: Analyzing soil moisture data and weather
      forecasts to optimize water use.

    - Crop Planning: Using predictive models to plan crop rotation and
      maximize yields.

    - Pest Management: Analyzing data to predict and prevent pest
      infestations.

### Alida in the Project

Example of Using ALIDA in an Agritech Project

Imagine an Agritech project aiming to optimize corn production. Here's
how you could use ALIDA:

1.  Data Collection:

Collect data from soil moisture sensors, weather stations, and
satellite images.

2.  Preprocessing:

Clean and normalize the data to ensure quality.

3.  Predictive Analysis:

Use machine learning algorithms to predict corn yields based on future
weather conditions.

4.  Visualization:

Create maps and charts showing yield predictions and water stress
areas.

5.  Automation:

Implement a system that sends notifications to farmers when it's time
to irrigate or fertilize based on predictions and real-time data.

In conclusion, ALIDA can be a powerful tool in an Agritech project,
offering advanced functionalities for data collection, analysis,
visualization, and automation to improve agricultural efficiency and
productivity.

<br>

#

# **Part II**

## User Guide

#

## **Data Access**

<!-- (\*ChatGPT and CoPilot)* *\ -->



## Enterprise Application Integration

### Definition

Enterprise Application Integration (EAI) is a strategic approach to
connect systems, applications, and data within an organization to
improve communication, efficiency, and productivity. EAI enables
enterprises to integrate heterogeneous software and data silos, creating
an interoperable infrastructure.

It refers to the process of connecting the many business applications
(such as ERP, CRM, SCM, and others) to enable smooth data exchange and
functionality. The aim is to eliminate barriers between systems, reduce
data duplication, and improve workflow.

### In ALIDA

\[...\]

## Data Replication and Synchronization

Data replication and synchronization are critical concepts in
distributed systems, database management, and cloud computing. They
enable consistency, fault tolerance, high availability, and scalability
across systems. Here\'s a breakdown:

### Data Replication

**Definition**: The process of copying data from one location to
another, typically across different servers, databases, or regions.

**Purpose:**

- **Fault Tolerance**: Ensures data availability even if a node or
  server fails.

- **High Availability**: Provides access to data from multiple
  locations.

- **Performance**: Improves read performance by enabling users to access
  data from a replica closer to them.

- **Backup and Recovery**: Creates redundancy for disaster recovery.

**Types of Replication:**

1.  **Synchronous Replication**:

    - Changes are immediately propagated to all replicas.

    - **Pros**: Ensures data consistency.

    - **Cons**: Higher latency due to waiting for acknowledgments from
      replicas.

    - Example: Financial systems.

2.  **Asynchronous Replication**:

    - Changes are propagated to replicas after the primary operation is
      complete.

    - **Pros**: Lower latency for the primary operation.

    - **Cons**: Risk of eventual inconsistency.

    - Example: Content delivery networks (CDNs).

**Challenges:**

- **Consistency**: Maintaining uniform data across replicas (solved by
  algorithms like Paxos or Raft).

- **Latency**: Balancing performance and real-time updates.

- **Conflict Resolution**: Handling updates that conflict between
  replicas.

### Data Synchronization

**Definition**: The process of ensuring data consistency between
multiple systems or replicas over time.

**Purpose:**

- Keeps all copies of data consistent after updates, modifications, or
  deletions.

- Ensures that users see the same data across different systems or
  devices.

**Approaches to Synchronization:**

1.  **One-Way Synchronization**:

    - Data flows in a single direction (e.g., master-to-slave).

    - Useful for backups or simple replication.

2.  **Two-Way Synchronization**:

    - Data flows bidirectionally between systems.

    - Example: Collaborative tools like Google Docs.

3.  **Near Real-Time Synchronization**:

    - Updates are synchronized almost instantaneously after changes.

    - Useful for systems requiring high consistency.

4.  **Scheduled Synchronization**:

    - Data is synchronized at predetermined intervals (e.g., nightly
      batch updates).

    - Suitable for low-priority or high-latency applications.

**Techniques:**

- **Change Data Capture (CDC)**: Tracks changes in a source system to
  propagate updates.

- **Conflict Resolution**: Algorithms to address data inconsistencies
  during synchronization.

- **Version Control**: Ensures the correct sequence of updates (e.g.,
  timestamps or vector clocks).

|  **Aspect** |           **Replication** |       **Synchronization** |
| --- | --- | --- |
| **Scope** |             Copies data to multiple locations | Ensures consistency acrosslocations |
| **Directionality** |    Often one-way (primary to replica) | Can be one-way or two-way |
| **Real-Time Need** |   Often synchronous or asynhcronous |    Typically focuses on eventual consistency |
| **Goal** |             Redundancy and availability |           Consistency and coordination |

> *Table 1.2.2 - Key Differences Between Replication and Synchronization*


**Use Cases**

- **Replication**: Content delivery networks (CDNs), disaster recovery,
  cloud database mirroring.

- **Synchronization**: Multi-device applications, distributed databases,
  real-time collaboration platforms.

### In ALIDA

\[...\]

## Basic and Advanced ETL Functionality

Extract, Transform, Load (ETL) functionality plays a pivotal role in
data integration, ensuring data from diverse sources is consolidated,
cleaned, and made ready for analysis. Below is a breakdown of **basic**
and **advanced ETL functionalities**.

### Basic ETL Functionality

Basic ETL processes address fundamental data integration needs, focusing
on simplicity and standard operations.

### Extract

- **Purpose**: Retrieve raw data from source systems (structured or
  unstructured).

- **Features**:

  - Support for standard data sources: Relational databases, flat files
    (e.g., CSV, JSON, XML), APIs, etc.

  - Minimal source system impact: Lightweight data extraction
    techniques.

  - Full or incremental extraction.

### Transform

- **Purpose**: Convert raw data into a usable format.

- **Features**:

  - Data cleaning: Removing duplicates, fixing errors, and handling
    missing values.

  - Basic transformations: Data type conversions, aggregations (e.g.,
    sums, averages), and filtering.

  - Lookups: Mapping reference data or joining datasets.

### Load

- **Purpose**: Load transformed data into a target system.

- **Features**:

  - Support for common data destinations: Data warehouses, databases, or
    flat files.

  - Basic scheduling: Loading data at periodic intervals (batch
    processing).

  - Overwrite or append operations.

### Common Use Cases:

- Migrating data from operational databases to a centralized data
  warehouse.

- Basic reporting and dashboards.

- Small-scale projects with limited data complexity.

### Advanced ETL Functionality

Advanced ETL processes address complex data integration needs,
emphasizing scalability, real-time capabilities, and intelligent
automation.

### Advanced Extract

- **Purpose**: Handle diverse and complex data sources.

- **Features**:

  - Support for modern data formats: NoSQL databases, streaming data
    (e.g., Kafka), cloud services, and IoT devices.

  - Change Data Capture (CDC): Extract only data changes to optimize
    performance.

  - Data profiling: Analyse source data to understand quality and
    structure.

### Advanced Transform

- **Purpose**: Enable sophisticated and intelligent data
  transformations.

- **Features**:

  - Data enrichment: Augment data with external sources (e.g., adding
    geolocation data).

  - Advanced data cleaning: AI/ML-based anomaly detection and
    correction.

  - Complex transformations:

    - Advanced joins (e.g., fuzzy matching).

    - Hierarchical data processing.

    - Pivoting and unpivoting.

  - Metadata management: Track data lineage and transformation history.

  - Event-driven transformations: Trigger specific workflows based on
    data events.

### Advanced Load

- **Purpose**: Optimize data delivery and usability in the target
  system.

- **Features**:

  - Support for real-time and streaming loads (ETL evolves into ELT or
    Streaming ETL).

  - Partitioning and indexing: Improve query performance in the target
    system.

  - Scalability: Handle large-scale data loads in distributed systems
    (e.g., Hadoop, Spark).

  - Data validation: Post-load validation to ensure data integrity.

  - Upset operations: Update existing records or insert new ones.

### Automation & Orchestration

- Workflow automation tools (e.g., Apache Airflow, AWS Step Functions).

- Event-based ETL pipelines.

- Error handling and recovery mechanisms.

#### *Advanced Scalability & Performance*

- Parallel processing for large datasets.

- Cloud-native capabilities (e.g., Snowflake, AWS Glue).

- Distributed ETL frameworks for big data (e.g., Apache Spark).

#### *Security & Governance*

- Data encryption during transfer and storage.

- Role-based access control (RBAC).

- Compliance features for regulations like GDPR, HIPAA, or CCPA.

#### *Integration with Modern Architectures*

- ELT workflows for big data (using tools like BigQuery, Databricks).

- Data mesh support: Decentralized data processing across domains.

- Integration with CI/CD pipelines for DevOps workflows.

**Common Use Cases:**

- Real-time analytics for IoT or streaming platforms.

- Enterprise-level data warehouses.

- AI/ML model training pipelines.

**Comparison: Basic vs. Advanced ETL**


| **ASPECT** | **BASIC ETL** | **ADVANCED ETL** |
| --- | --- | --- | 
| **Data Sources** |       Relational databases, files |   NoSQL, APIs, streaming, IoT, cloud |
|  **Data Volume** |        Small to moderate    |   Large-scale and distributed |
| **Processing** |         Batch processing   |     Batch, real-time, streaming |
| **Transformation** |     Simple cleaning, aggregations  |     Complex, AI-driven transformations |
| **Scalability** |        Limited     |            Highly scalable (cloud/distributed) |
| **Governance** |         Minimal             |    Advanced security and compliance |

### In ALIDA

\[...\]

## Hybrid and Multi Cloud Data Sources

Hybrid and multi-cloud strategies are increasingly popular for
managing data sources in modern IT environments. Here's a brief
overview of each:

### Hybrid Cloud

A hybrid cloud combines on-premises infrastructure (private cloud)
with public cloud services. This setup allows data and applications to
move between the two environments, providing greater flexibility and
more deployment options. [Hybrid clouds are often used to meet
regulatory requirements, maximize existing infrastructure investments,
and reduce latency by processing data closer to where it is
generated](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/scenarios/hybrid/).

### Multi-Cloud

Multi-cloud refers to the use of multiple cloud services from
different providers. This approach allows organizations to choose the
best services for specific tasks, enhancing flexibility and reducing
dependency on a single vendor. [Multi-cloud environments can include
both public and private clouds, offering a heterogeneous setup that
can be tailored to various business
needs2](https://www.cloudflare.com/learning/cloud/multicloud-vs-hybrid-cloud/).

**Key Benefits**

- Flexibility: Both strategies offer the ability to scale resources up
  or down based on demand.

- Risk Mitigation: Using multiple providers can reduce the risk of
  downtime and data loss.

- Cost Efficiency: Organizations can optimize costs by selecting the
  most cost-effective services for different workloads.

- [Compliance and Security: Hybrid clouds can help meet regulatory
  requirements by keeping sensitive data on-premises while leveraging
  the public cloud for less sensitive
  workloads1](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/scenarios/hybrid/).

**Popular Platforms**

- [Google Cloud: Offers tools for building hybrid and multi-cloud
  architectures, enabling seamless integration and management of data
  across different
  environments](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/scenarios/hybrid/)[3](https://cloud.google.com/architecture/hybrid-multicloud-patterns-and-practices).

- [Microsoft Azure: Provides comprehensive support for hybrid and
  multi-cloud setups, with features designed to enhance security,
  compliance, and operational
  efficiency1](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/scenarios/hybrid/).

- Amazon Web Services (AWS): Supports hybrid cloud solutions with
  services like AWS Outposts, which bring AWS infrastructure and
  services to on-premises environments.

##  Access to Nontraditional Data Types

Accessing nontraditional data types can provide unique insights and
enhance data-driven decision-making. Here are some examples of
nontraditional data sources and their applications:

### Geospatial Data

Satellite Imagery: Used for monitoring environmental changes, urban
development, and agricultural patterns.

Geographic Information Systems (GIS): Helps in mapping and analyzing
spatial data for various applications, including disaster management and
urban planning.

### Mobile Phone Data

Location Data: Tracks population movements and mobility patterns, useful
for urban planning and transportation studies.

Call Detail Records (CDRs): Analyzes communication patterns and can be
used in epidemiology to track disease spread.

### Social Media Data

Sentiment Analysis: Analyzes public opinion on various topics, such as
product reviews or political sentiments.

Trend Analysis: Identifies emerging trends and patterns in real-time,
useful for market research and public health monitoring.

### Sensor Data

Internet of Things (IoT): Collects data from connected devices, such as
smart meters, weather stations, and health monitors.

Environmental Sensors: Monitors air quality, water quality, and other
environmental parameters.

### Citizen-Generated Data

Crowdsourcing Platforms: Gathers data from the public on various issues,
such as traffic conditions, disaster response, and public health.

Participatory Mapping: Involves communities in mapping their own areas,
providing valuable local insights.

### Transaction Data

E-commerce Data: Analyzes purchasing behavior and trends from online
transactions.

Financial Data: Tracks economic activities and can be used for market
analysis and financial forecasting.

These nontraditional data sources can complement traditional data
collection methods, offering richer and more diverse datasets for
analysis.

## Connectivity to Data Lake Infrastructure

Connecting to data lake infrastructure is crucial for managing and
analyzing large volumes of data. Here are some key steps and
considerations for establishing connectivity:

### Choose the Right Data Lake Platform

*Azure Data Lake Storage (ADLS):* Offers scalable storage and supports
big data analytics. You can connect to ADLS using various tools like
Azure Databricks, which provides seamless integration and powerful data
processing capabilities.

*Amazon S3*: Widely used for data lakes, S3 integrates with AWS
analytics services like Amazon Redshift and AWS Glue. It supports a wide
range of data formats and provides robust security features.

*Google Cloud Storage*: Suitable for building data lakes on Google
Cloud, it integrates with BigQuery for analytics and supports various
data ingestion methods.

### Set Up Authentication and Access Control

*Service Principals and IAM Roles*: Use service principals (Azure) or
IAM roles (AWS and Google Cloud) to manage access to your data lake.
This ensures secure and controlled access to data.

*OAuth 2.0*: Implement OAuth 2.0 for secure authentication, especially
when connecting from external applications or services.

### Data Ingestion and Integration

*ETL Tools*: Use Extract, Transform, Load (ETL) tools like Apache NiFi,
Talend, or AWS Glue to ingest data into your data lake. These tools help
automate data pipelines and ensure data is properly formatted and
cleaned.

*Streaming Data*: For real-time data ingestion, use tools like Apache
Kafka or AWS Kinesis. These tools allow you to process and analyze data
as it arrives.

### Data Management and Governance

*Metadata Management*: Implement a metadata management system to catalog
and organize your data. Tools like Apache Atlas or AWS Glue Data Catalog
can help with this.

*Data Governance*: Establish data governance policies to ensure data
quality, security, and compliance. This includes setting up data access
controls, auditing, and monitoring.

### Analytics and Processing

*Big Data Processing*: Use platforms like Apache Spark, Databricks, or
Google BigQuery for processing and analyzing large datasets. These
platforms offer powerful analytics capabilities and can handle complex
queries.

*Machine Learning*: Integrate machine learning frameworks like
TensorFlow, PyTorch, or AWS SageMaker to build and deploy machine
learning models on your data lake.

By following these steps, you can effectively connect to and utilize
data lake infrastructure for your big data and analytics needs.

## Data Lineage

Data lineage refers to the process of tracking and visualizing the flow
of data from its origin through various transformations and stages until
it reaches its final destination. This practice is crucial for ensuring
data quality, compliance, and effective data governance. Here are some
key aspects of data lineage:

### Importance of Data Lineage

*Traceability*: Helps in understanding the data's journey, making it
easier to identify and rectify errors.

*Compliance*: Ensures that data handling complies with regulatory
requirements by providing a clear audit trail.

*Data Quality*: Enhances data quality by allowing organizations to track
and manage data transformations and dependencies.

### Components of Data Lineage

*Data Origin*: The source of the data, such as databases, files, or
external systems2.

Transformations: The processes that modify the data, including cleaning,
aggregating, and enriching.

*Data Flow*: The movement of data through various systems and
processes2.

End Points: The final destinations where the data is stored or used,
such as data warehouses, analytics platforms, or reports.

### Tools for Data Lineage

*Apache Atlas*: An open-source tool for managing metadata and data
lineage in Hadoop ecosystems.

*Informatica*: Provides comprehensive data lineage capabilities,
supporting various data sources and transformations.

*Talend*: Offers data lineage features as part of its data integration
and management suite.

*Collibra*: A data governance platform that includes robust data lineage
tracking1.

### Benefits of Data Lineage

*Improved Decision-Making*: Provides a clear understanding of data
origins and transformations, leading to more informed decisions.

*Enhanced Data Governance*: Facilitates better data management practices
and compliance with regulations.

*Operational Efficiency*: Streamlines data operations by providing
visibility into data flows and dependencies.

Implementing data lineage can significantly improve how organizations
manage and utilize their data.

##  Data Governance and Metadata Management

Data governance and metadata management are essential components for
ensuring data quality, compliance, and effective data utilization within
an organization. Here's an overview of each and how they work together:

### Data Governance

Data governance involves the overall management of data availability,
integrity, and security. It includes establishing policies, procedures,
and guidelines to ensure proper data handling and utilization. Key
components of data governance include:

*Data Stewardship*: Assigning roles and responsibilities for managing
data quality and integrity.

*Data Quality Management*: Ensuring data is accurate, consistent, and
up-to-date.

*Data Security*: Implementing measures to protect sensitive information
from unauthorized access or breaches.

*Compliance*: Meeting regulatory requirements, such as data privacy laws
and industry-specific regulations.

### Metadata Management

Metadata management involves organizing and categorizing metadata, which
is data about data. Metadata provides context and information about data
assets, such as their origin, structure, and usage. Key aspects of
metadata management include:

*Business Metadata*: Information that provides business context, such as
data definitions, classifications, and confidentiality levels.

Technical Metadata: Details about data structure, storage, and
transformations, such as table names, column structures, and data
lineage.

*Metadata Cataloging*: Creating a searchable index of metadata to
facilitate data discovery and access.

### Synergy Between Data Governance and Metadata Management

The integration of data governance and metadata management enhances
data-driven decision-making and operational efficiency. Here's how they
complement each other:

*Improved Data Quality*: Metadata management helps in tracking data
transformations and lineage, ensuring data quality and consistency.

*Enhanced Compliance*: Data governance policies, combined with metadata
management, ensure that data handling complies with regulatory
requirements.

*Better Data Utilization*: Metadata provides the context needed to
understand and use data effectively, while data governance ensures that
data is managed and utilized properly.

By implementing robust data governance and metadata management
practices, organizations can unlock the full potential of their data
assets.

##  API-Based Access to Web Data

API-based access to web data is a powerful method for retrieving and
interacting with data from various online sources. Here's an overview of
how it works and some tools you can use:

### How API-Based Access Works

*API Requests*: APIs (Application Programming Interfaces) allow you to
send requests to a web server to retrieve or manipulate data. These
requests are typically made using HTTP methods like GET, POST, PUT, and
DELETE.

*Data Formats*: The data returned by APIs is often in formats like JSON
or XML, which are easy to parse and use in your applications.

*Authentication*: Many APIs require authentication, usually through API
keys, OAuth tokens, or other methods to ensure secure access.

### Popular Tools and Libraries

*Python Requests Library*: A simple and popular library for making HTTP
requests in Python. It's great for interacting with web APIs and
handling responses.

*Postman*: A powerful tool for testing and interacting with APIs. It
allows you to create and save complex API requests and view responses in
a user-friendly interface.

*Swagger*: An open-source framework for designing, building, and
documenting APIs. It helps in creating interactive API documentation and
testing endpoints.

### Use Cases

*Data Integration*: APIs can be used to integrate data from various
sources into a centralized database or data warehouse.

*Real-Time Data Access*: APIs enable real-time access to data, which is
crucial for applications that require up-to-date information.

*Automation*: Automate repetitive tasks by using APIs to interact with
web services and perform actions programmatically.

### Learning Resources

*Dataquest*: Offers courses on APIs and web scraping in Python,
providing practical skills for extracting and analyzing web data.

*freeCodeCamp*: Provides tutorials on how to use web APIs in coding
projects, helping you understand the basics and advanced concepts.

API-based access to web data can significantly enhance your data
analysis and integration capabilities.

<br>
<br>

## **Data Preparation**

### Data Blending/Wrangling

In **Machine Learning** and **Data Science**, the concepts of **Data
Blending** and **Data Wrangling** refer to two distinct but
complementary processes for data preparation.

##### Data Wrangling (or Data Munging)

**Data Wrangling** is the process of **cleaning, transforming, and
restructuring** raw data into a format best suited for analyzing and
training machine learning models.

1.  **Data cleansing**: Managing missing values, eliminating duplicates,
    correcting errors in data.

2.  **Standardization**: conversion of units of measurement,
    normalization of values.

3.  **Feature Engineering**: Creating new features from existing
    features.

4.  **Formatting**: Converting data types, restructuring columns and
    rows.

**Goal**: Make data usable for analysis or predictive models.

##### Data Blending

**Data Blending** is the process of **combining data from different
sources** (e.g., databases, CSV files, APIs, etc.), and merging them to
create a unified dataset. It differs from simple **Data Integration**
because it allows you to combine heterogeneous data without necessarily
structuring them in the same database.

The most common techniques include:

1.  **Join (INNER, LEFT, RIGHT, FULL)**: A union of datasets based on
    common keys.

2.  **Union**: A concatenation of datasets with a similar structure.

3.  **Lookup & Matching**: data enrichment based on identifiers.

**Goal**: Merge data from multiple sources to gain richer insights.

#### Key Difference

| **Aspect** |     **Data Wrangling** |             **Data Blending** |
| --- | --- | --- |
|  **Objective**  | Data Cleansing and Transformation  |            Merging data from multiple sources |
| **Focus** |      Data quality and structure   |   Merging heterogeneous datasets |
| **Techniques used** |    Normalization, feature engineering, missing value management    |    Join, union, lookup |

#### Practical example

Imagine you have:

1.  A file with monthly sales (**CSV**)

2.  A database with customer information (**SQL)**

3.  Marketing data collected via **API**

<!-- -->

1.  With **Data Blending**, you combine these sources to get a single
    dataset.

2.  With **Data Wrangling**, clean up the dataset (removing errors,
    transforming variables, handling missing data).

### Data Augmentation

**Data Augmentation** is a technique used to **artificially increase the
amount of data** available for training a model, creating new instances
of the original data through transformations, modifications, or
synthetic generation.

**Goal**: Improve model generalization, reduce overfitting, and achieve
better performance, especially when the dataset is limited.

**Data Augmentation in the different areas**

#### ***Computer Vision (Images)***

In computer vision, **Data Augmentation** is widely used to generate
multiple images from existing ones. Common techniques include:

1.  **Flip and rotation** (horizontal/vertical mirror, rotation of
    random angles)

2.  **Zoom and crop** (zoom in or crop portions of the image)

3.  **Translation and distortion** (displacement, elastic deformation)

4.  **Adding noise** (to simulate real-world variations)

5.  **Changing brightness and contrast**

6.  **Generation of synthetic data** (e.g. GAN - Generative Adversarial
    Networks)

-  **Example**: In a dataset of cat images, you can create new images by
rotating them or applying filters to simulate different lighting
conditions.

#### ***Natural Language Processing (NLP)***

In text, **Data Augmentation** can be more complex because editing a
sentence without altering its meaning is difficult. Some techniques
include:

1.  **Synonym Replacement** (replacing words with synonyms)

2.  **Back Translation** (translation into another language and return
    to the original)

3.  **Sentence Shuffling** (change in word order)

4.  **Word Dropout** (random word removal)

5.  **Generation with language models** (e.g. GPT to create new similar
    texts)

**Example**: The phrase *\"The dog runs in the park\"* can be
increased to *\"The dog sprints in the garden\"* by synonyms.

*** Tabular Data (Structured Data)***

In tabular datasets, Data Augmentation is more complex, but can be
accomplished with:

1.  **Jittering** (adding small random noises to numerical data)

2.  **Synthetic Minority Over-sampling Technique (SMOTE)**

3.  **Statistical perturbations** (random changes to the data while
    maintaining the original distribution)

**Example**: If you have little data from high-income customers,
SMOTE can generate new synthetic examples to improve class balance.

#### ***Benefits of Data Augmentation:***

**- Improves model** **generalization**

**- Reduces overfitting**, especially with small **datasets**

**- Increases model robustness** to variations in real **data**

**- Allows you to better leverage deep learning models**, which require
large amounts of data.

**Limitations and Challenges:**

⚠ **Not always effective for all data**\
⚠ T**ypes Risk of introducing bias or noise** if augmentation is poorly
designed\
⚠ **Increased training time**, especially with images and text.

## **Data Quality Support**

Data Quality Support refers to the set of activities, tools, methodologies, and interventions aimed at ensuring that the data used in applied research projects are accurate, complete, consistent, reliable, and timely, throughout their entire lifecycle—from collection to dissemination.
In applied research contexts (e.g., agri-food, environmental, healthcare), supporting data quality plays a key role because it:
Directly impacts the scientific validity of results
Ensures reproducibility and traceability of findings
Affects the scalability and transferability of results to real-world applications (e.g., industry, supply chains, regulatory bodies)

### **Core Components of Data Quality Support**

**1. Standardization**

Standardization is the foundational pillar of data quality support, enabling the harmonization of data structure, content, and meaning. In applied research, the adoption of formal ontologies, controlled vocabularies, and standardized data formats allows for the efficient integration of heterogeneous data sources, reduces semantic ambiguity, and enhances data reusability in accordance with FAIR principles. The use of international standards (e.g., ISO 8000 – Data Quality, ISO/IEC 25012 – Data Quality Model) reinforces compliance and interoperability at both European and global levels.

**2. Validation and Verification**

Validation and verification are essential processes to ensure the reliability and internal consistency of the datasets used. These activities include both automated and manual checks to detect syntactic errors, semantic inconsistencies, duplicates, missing values, and outliers. In multidisciplinary research contexts, such verification mechanisms must be modular and adaptable, supporting data quality throughout the entire lifecycle—including during the integration of distributed and heterogeneous sources.
Monitoring of semantic consistency and relational integrity.

**3. Governance and Metadata**

Effective data governance requires the definition of key roles (e.g., data stewards, data owners) and the use of tools for documentation, traceability, and version control. Metadata play a central role in describing the origin, structure, intended use, and constraints of data. In applied research, this approach facilitates quality assessment, data provenance (lineage), and scientific trustworthiness. Integration with Data Management Plans (DMPs) is essential for projects funded at national and EU levels.

**4. Technologies and Tools**

Technological support for data quality relies on specialized tools for data profiling, cleansing, continuous monitoring, and remediation. Open-source tools such as Talend, OpenRefine, or Apache Griffin, along with emerging technologies (e.g., AI/ML for anomaly detection), enable automation in identifying and correcting data anomalies. Furthermore, interoperable platforms such as ALIDA (for analytical workflow orchestration) or Distributed Ledger Technologies (DLTs) (to ensure integrity and traceability) strengthen quality control throughout the entire data lifecycle.

### **Practical Applications**

#### *Sensor and experimental data quality*

In experimental contexts (e.g., agronomy, environmental studies, Industry 4.0), Data Quality Support ensures the accuracy and consistency of data collected from sensors, lab instruments, IoT systems, or manual surveys. The adoption of standardized protocols, automatic validation checks, and data cleaning tools improves the reliability of datasets used for modeling and predictive analysis.

#### *Integration and harmonization of heterogeneous data*

Applied research frequently involves the combined use of datasets that vary in format, granularity, origin, or frequency (e.g., open data, historical records, enterprise systems, institutional sources). Data Quality Support enables harmonization through data fusion, semantic mapping, and assisted integration, supporting complex use cases such as the development of digital twins or decision support systems.

#### *Integrity and consistency checks in distributed systems (DLT, edge computing)*

In distributed architectures—such as DLTs or edge computing infrastructures—data quality must be ensured at both local and global levels. Data Quality Support includes input data validation, temporal alignment, and integrity monitoring throughout the processing pipeline.

#### *Support for data collection from external stakeholders (e.g., companies, field operators)*

In applied research, data are often sourced from external actors with varying levels of digitalization and technical expertise. Data Quality Support involves the creation of guided templates, standardized collection forms, operational manuals, and technical training to ensure data accuracy and compatibility.

#### *Enabling distributed and federated analytics*

In scenarios where data cannot be centralized (due to privacy, ownership, or cost reasons), Data Quality Support enables federated analysis (e.g., federated learning) by ensuring that locally trained models are based on valid, comparable, and compliant data.

#### *Continuous monitoring and alerting on data stream quality*

In projects involving continuous data flows (e.g., streaming, sensors, logs), Data Quality Support includes real-time monitoring and automatic alerts in case of quality degradation (e.g., dropped flows, anomalies, missing values). This is critical in high-automation or mission-critical environments.

#### *Support for interoperability in multi-actor research projects*

In collaborative research projects involving institutions, enterprises, and public authorities, data quality is a prerequisite for sharing and interoperability. Support activities may include semantic alignment of datasets, negotiation of shared ontologies, and the definition of standardized data exchange formats.


## Benefits of Data Quality Support

The adoption of structured data quality practices enhances the validity of experimental results and ensures higher reproducibility of studies. This is particularly crucial when data feed predictive models, simulations, or automated decision-making processes.

#### *Greater transparency, traceability, and auditability*

High-quality data can be traced back to its origin and transformations, facilitating internal and external review processes. It supports regulatory compliance (e.g., GDPR, EU regulations) and enables certification or audit workflows, especially in tech-intensive or public-funded projects.

#### *Reduced risk of errors and bias in analytical models*

Incomplete, incorrect, or inconsistent data can introduce bias or misleading outcomes in analyses. Data Quality Support allows for timely detection of anomalies or errors, reducing the risk of flawed decisions or compromised statistical robustness.

#### *Optimized reuse of existing datasets*

By ensuring quality and interoperability, Data Quality Support enables the effective reuse of existing data, reducing the need for redundant data collection and improving the operational efficiency of research initiatives.

#### *Increased value of data for technology transfer*

Reliable and well-documented data are more easily exploitable for technology transfer, commercialization, or intellectual property valorization. Data quality becomes a strategic asset, particularly in applied, industrial, or patent-driven projects.

#### *Enabler of interoperability and distributed analytics*

Quality support allows the alignment of semantics and structure across heterogeneous sources, facilitating integration of data from various actors (e.g., companies, institutions, IoT systems). This is essential for building interoperable systems and performing distributed analytics (e.g., federated learning, DLT).

#### *Support for sustainability and efficiency in research projects*

Investing in data quality helps reduce future costs, avoid rework, and increase the long-term durability of results. Data Quality Support makes research projects more sustainable, scalable, and ready for replication.




## Dataset Partitioning

Dataset partitioning is a foundational step in ensuring fair, robust, and reproducible evaluation of analytical and predictive models in applied research. The choice of strategy—whether stratified, temporal, or cross-validation—depends on the nature of the data and the research objectives, and it must be implemented carefully to ensure the credibility of the results.

#### Definition and Purpose

Dataset partitioning refers to the systematic division of a dataset into multiple subsets, each serving a distinct purpose in a data analysis or machine learning pipeline. It is a critical step in ensuring:

 - Objective validation of model performance

 - Generalization of results to unseen data

 - Control over bias and overfitting

 - Balanced representation of data classes or features



## Binning and Smoothing

In the context of applied Artificial Intelligence (AI) and data-driven research, the quality and structure of input data play a pivotal role in determining the reliability, robustness, and interpretability of analytical models. Two key preprocessing techniques often employed to enhance data usability are binning and smoothing. These methods are particularly useful when working with noisy, high-dimensional, or continuous-valued datasets, which are common in fields such as agrifood technology, environmental monitoring, digital health, and decentralized systems using DLT (Distributed Ledger Technologies).

#### *Binning: Discretizing Continuous Data*

Binning is a data discretization technique that transforms continuous numerical variables into categorical intervals, or "bins". Instead of using raw values, each observation is replaced by a representative value associated with its corresponding bin. This approach can simplify the structure of the data, reduce the influence of minor fluctuations or measurement errors, and prepare the dataset for algorithms that operate more effectively on categorical features (e.g., decision trees, Naive Bayes classifiers).

More advanced techniques, such as supervised binning or optimal binning, take into account the relationship between input variables and the target variable to determine the best way to discretize the data. In some cases, fuzzy binning or clustering-based binning is applied to allow for soft boundaries and probabilistic memberships, especially in complex or uncertain domains.

In applied research, binning is particularly useful when datasets contain sensor readings, geospatial coordinates, or quantitative lab results. Discretizing such data can improve the stability of the model and reduce its sensitivity to noise or outliers.

#### *Smoothing: Reducing Noise and Highlighting Trends*

Smoothing refers to a set of techniques used to reduce noise in datasets, particularly in time series or high-frequency data, while preserving underlying patterns and trends. The goal is to produce a cleaner signal that can be more effectively analyzed, modeled, or interpreted.

Common smoothing methods include:

Moving average smoothing, where each data point is replaced by the average of its neighboring values within a defined window.

Exponential smoothing, which applies exponentially decreasing weights to older observations, giving more importance to recent values.

Savitzky–Golay filtering, which fits a low-degree polynomial to a sliding window of the data, preserving the original shape and features of the signal better than simple averaging.

Additive smoothing (e.g., Laplace smoothing), used in categorical data to avoid zero probabilities in probabilistic models.

Other advanced techniques such as kernel-based smoothing or spline interpolation may also be applied, particularly when handling complex temporal or spatial datasets.

In applied AI systems, smoothing is commonly used to preprocess real-world data collected from IoT devices, agricultural sensors, satellite imagery, or health monitors. These sources are often subject to environmental noise, missing values, or irregular sampling intervals. By smoothing the data, researchers can extract meaningful patterns, improve model training, and reduce the risk of overfitting caused by random fluctuations.

#### Combined Use of Binning and Smoothing

In many practical applications, binning and smoothing are used in combination. For instance, data can first be grouped into bins, and then each bin can be smoothed by replacing its values with the mean or median of the bin. This dual approach allows researchers to discretize the data structure while also attenuating local noise, providing a more stable input for AI models.
Such preprocessing is particularly valuable in fields where raw data is heterogeneous, sparse, or highly variable—such as in blockchain-enabled traceability systems (DLT), where multiple nodes may contribute inconsistent data over time. Applying binning and smoothing in this context helps to align formats, remove outliers, and improve the consistency of the analytical pipeline.

Binning and smoothing are fundamental preprocessing techniques in applied AI that facilitate the simplification, standardization, and noise reduction of raw data. Their proper implementation enhances the interpretability, stability, and performance of machine learning models, especially in complex or data-rich domains. When used thoughtfully, these techniques contribute significantly to the reproducibility and scientific reliability of research outcomes.

## Filter and Search

Filter and search operations are essential pillars of applied AI pipelines. Far beyond simple data subsetting or keyword retrieval, these operations support intelligent interaction with large, complex, and distributed datasets. Whether through preprocessing, semantic search, high-dimensional indexing, or user-driven exploration, effective filtering and search mechanisms ensure that AI systems remain relevant, efficient, and explainable — key requirements for responsible innovation in data-intensive research environments.

The ability to filter and search through large volumes of structured or unstructured data is fundamental to enabling efficient analysis, model training, and decision support. These operations are not limited to traditional information retrieval, but are embedded in every layer of data processing — from feature selection and data querying to intelligent knowledge extraction in distributed environments.

The “Filter and Search” paradigm in AI-driven systems extends beyond basic keyword queries or dataset subsetting. It involves a combination of algorithmic filtering, semantic search, ranking, and contextual matching, often integrated into intelligent pipelines that support automation, scalability, and explainability.

#### 1. Filtering as a Preprocessing Step
Filtering is widely used during data preprocessing to remove irrelevant, redundant, or low-quality data before training a machine learning model. This includes:

Filtering rows based on thresholds (e.g., only records with temperature > 30°C)

Removing missing, inconsistent, or noisy entries

Selecting relevant features (feature filtering) based on statistical significance or domain knowledge

Applying conditional logic to retain only data that meets experiment-specific criteria

In applied research, particularly in fields like agriculture, environmental monitoring, or digital health, filtering helps ensure that the training data is representative, clean, and meaningful, reducing noise and bias in downstream analysis.

#### 2. Semantic and Context-Aware Search
Modern search systems in AI extend beyond syntactic matching. They include semantic search methods that use embeddings, ontologies, and contextual similarity to retrieve information that is relevant, even if it doesn't contain the exact search terms.

For example:

In a knowledge graph, a semantic search might return all entities related to “organic farming” even if the exact phrase does not appear

In NLP-based applications, transformer models (e.g., BERT) can retrieve semantically similar documents or concepts using vector similarity instead of keywords

In decentralized data environments (e.g., DLTs), search can involve cross-node querying with ontology alignment and metadata indexing

Semantic filtering and search are essential when datasets are heterogeneous, multilingual, or multi-source, as is often the case in applied EU-funded research or AI-driven policy analysis.

#### 3. Search in High-Dimensional or Unstructured Data
In AI and applied science, researchers often work with unstructured data (text, images, signals) or high-dimensional datasets (e.g., genomics, multispectral imaging). Efficient search mechanisms allow for:

Similarity search (e.g., finding the most similar sensor readings or images)

Subspace filtering (selecting only features or dimensions relevant to a hypothesis)

Use of indexing structures like KD-trees, inverted indexes, or approximate nearest neighbors (ANN) to handle large-scale search efficiently

This is especially relevant in domains such as precision agriculture, where satellite or drone imagery is queried to locate specific patterns (e.g., disease hotspots), or in smart manufacturing, where sensor logs are filtered to detect early warnings.

#### 4. User-Driven Filtering in Interactive Systems
In applied systems that include human-in-the-loop components, filtering is often user-driven. Researchers, domain experts, or decision-makers interact with dashboards or visual analytics tools that support:

Custom filters (by time, location, category)

Multidimensional queries (e.g., “show me anomalies in refrigerated transport for dairy products in July”)

Real-time updates as filters are modified

This supports explainability and interpretability, which are increasingly critical in AI systems deployed in real-world environments, especially when transparency is required (e.g., healthcare, food safety, environmental impact assessments).

#### 5. Filtering and Search in Distributed and Federated Contexts
In modern research architectures involving distributed data sources or federated learning, filtering and search must operate across decentralized nodes. This introduces specific challenges:

Ensuring interoperability of queries across datasets with different schemas or standards

Filtering data locally at the edge, before it is shared or aggregated

Maintaining privacy and security while still enabling efficient data access

In such systems, filtering and search mechanisms must be lightweight, secure, and often ontology-driven to ensure meaningful results across different domains and languages.


## Feature Generation

Feature generation is a critical step in any data analytics or machine learning workflow. By transforming raw data into meaningful, domain-relevant variables, it enables models to better capture real-world complexity, improve predictive accuracy, and align with scientific or operational goals. In applied research contexts—where data is often noisy, incomplete, or heterogeneous—feature generation becomes not just a technical task, but a strategic activity that bridges data science and domain expertise.

In modern data analytics workflows, particularly those involving machine learning or AI-based modeling, the quality of the input features is often more critical than the choice of algorithm. Feature generation—also known as feature construction—refers to the process of creating new, informative variables from raw data, in order to better represent the underlying structure of the problem and enhance model performance.

Rather than relying solely on the original data fields collected from sensors, databases, or user input, analysts generate new features that capture domain knowledge, reveal latent relationships, or simplify complex patterns.

#### 1. Definition and Purpose
Feature generation is the process of transforming raw data into structured variables (features) that are more meaningful and predictive for a specific analytical task. It is distinct from feature selection (which picks the best existing features), in that it creates new variables, either by combining existing ones or deriving them through domain logic or mathematical transformations.

The goal is to improve:

 - Model accuracy and generalization

 - Interpretability and explainability

 - Robustness to noise or missing data

 - Alignment with domain-specific knowledge

In applied settings such as agriculture, smart manufacturing, or energy systems, feature generation often incorporates expert knowledge about time, geography, system behavior, or regulatory constraints.

#### 2. Types of Feature Generation
There are several common strategies for generating features:

a. Mathematical Transformations
Raw numerical features can be transformed using operations like logarithms, square roots, ratios, or polynomial expansions. For example, generating a “temperature variation” feature from daily min/max values.

b. Aggregations and Window Functions
In time-series or sequential data, features can be created by computing statistics (mean, median, standard deviation, min/max) over time windows or spatial segments. This is widely used in predictive maintenance or crop monitoring.

c. Interaction Terms
New features can be generated by multiplying or combining two or more variables to capture interactions that are not visible when variables are treated independently. For instance, “soil moisture × temperature” could be more informative than each variable alone.

d. Domain-Derived Features
Features derived from subject matter expertise—such as growing degree days (GDD) in agriculture, or normalized load curves in energy systems—allow models to integrate real-world processes into their structure.

e. Text and Categorical Encoding
When working with textual or categorical data, feature generation includes techniques such as TF-IDF vectors, n-grams, word embeddings (e.g., BERT), or one-hot encoding, to convert raw text or labels into numerical inputs.

f. Spatial and Temporal Features
In geospatial or time-aware applications, generating features such as “distance from origin”, “days since last event”, or “seasonality index” enables the model to leverage temporal and spatial patterns that are often key in applied research.

#### 3. Automated vs Manual Feature Generation
Feature generation can be manual, relying on expert insight and exploratory data analysis, or automated, using algorithmic approaches such as:

Featuretools for deep feature synthesis

AutoML platforms that generate candidate features and rank them

Embedding techniques (e.g., in graph neural networks or NLP) that automatically learn latent features from complex structures

In applied research environments, a hybrid approach is often used—combining human expertise with automated pipelines—to ensure that generated features are both meaningful and technically robust.

#### 4. Role in the Data Analytics Pipeline
Feature generation plays a foundational role in transforming data from its raw state to a model-ready form. It is typically positioned between data cleaning and model training:

Raw data ingestion

Preprocessing (cleaning, normalization)

Feature generation

Feature selection and dimensionality reduction

Model development and evaluation

Without relevant features, even the most sophisticated algorithms can perform poorly. Conversely, well-designed features can dramatically improve model performance—even when using relatively simple models.

#### 5. Benefits in Applied Research and AI
In applied domains, feature generation enables:

Adaptation to domain-specific constraints (e.g., regulatory thresholds, biological cycles)

Improved explainability, allowing stakeholders to understand how inputs influence predictions

Data enrichment, especially when integrating multiple sources (e.g., IoT + satellite data)

Reduced dimensionality, by condensing raw variables into more meaningful aggregates

Greater resilience to data sparsity, noise, or drift over time

For example, in agrifood traceability systems, generating features that represent “chain consistency”, “average time per transformation step”, or “anomaly scores from past batches” can support fraud detection or quality assurance processes.


## Official Watermarking of Datasets

Official watermarking of datasets represents a powerful and emerging strategy to strengthen data governance, provenance assurance, and scientific integrity in the age of open data and AI. By embedding persistent, verifiable marks into datasets, organizations and research institutions can ensure authenticity, accountability, and trust in the data they produce and share. As the data landscape becomes more decentralized, collaborative, and regulated, watermarking will increasingly become a foundational practice in responsible data analytics and digital trust frameworks.

In modern data-driven environments, the integrity, authenticity, and traceability of datasets are critical to ensuring responsible and verifiable use of data. One emerging technique that supports these goals is official watermarking—a process by which digital identifiers or cryptographic marks are embedded directly into datasets, establishing their origin, ownership, or certification status in a verifiable way.

Unlike traditional metadata or file naming conventions, official watermarking is embedded at the data level, making it harder to tamper with and easier to audit. This technique is particularly relevant in sectors such as research, healthcare, public administration, agri-food traceability, and AI model development, where the reliability and provenance of data can impact regulatory compliance, scientific validity, and public trust.

#### 1. Definition and Core Concept
Official watermarking of datasets refers to the systematic embedding of unique, traceable digital signatures—called watermarks—into a dataset or its derived content. These watermarks can be either visible (semantic labels, tags, hashes) or invisible (statistically encoded or cryptographic markers). The objective is to create an unambiguous link between a dataset and its publisher, custodian, or issuing authority.

Unlike traditional document watermarks, which are often visual and superficial, dataset watermarks are resilient to format transformations, hidden within the data, and detectable via validation tools. They can also include timestamps, version numbers, origin identifiers, or digital certificates.

#### 2. Why Watermarking is Needed in Data Analytics
In applied data analytics and AI-driven research, watermarking supports several critical needs:

 - Data provenance and attribution: Tracking who created, certified, or modified the dataset.

 - Integrity verification: Ensuring that the dataset has not been tampered with, altered, or corrupted.

 - Legal and ethical accountability: Enabling traceability for data sharing under formal agreements, public policies, or licensing constraints.

 - Reproducibility in research: Certifying that a given dataset used in experimentation is the officially released version.

 - Counterfeit detection: Identifying unlicensed copies or manipulated versions of open/public datasets.

These needs are becoming increasingly relevant in collaborative R&D projects, data marketplaces, federated data spaces, and regulatory AI frameworks.

#### 3. Types of Dataset Watermarking
There are several technical approaches to watermarking, each suited to different data types and use cases:

 - Cryptographic watermarking: Embedding hashes, digital signatures, or cryptographic checksums directly in the dataset or its metadata to verify integrity.

 - Statistical watermarking: Introducing subtle perturbations in numerical data (e.g., ±0.001%) that are statistically invisible but verifiable through a secret key.

 - Semantic watermarking: Embedding unique codes or identifiers into specific categorical fields (e.g., ID codes, batch numbers, geotags) in a structured way.

 - Embedded metadata schemes: Creating hidden fields or labels within structured data (e.g., hidden columns in a CSV or JSON schema) to encode origin information.

Depending on the application, these methods can be passive (detectable without affecting the data use) or active (designed to raise alerts if tampered with).

#### 4. Applications in Applied Research and Data Governance
In the context of data analytics for applied research and public-interest projects, official watermarking is particularly useful for:

 - Certifying Open Datasets: Ensuring that published research datasets (e.g., under Open Science mandates) carry a verifiable mark of authenticity from the issuing institution or funding body.

 - DLT and Blockchain Integration: Embedding dataset watermarks as transaction hashes or on-chain references to guarantee origin and immutability.

 - Cross-institutional Data Exchange: Enabling secure and traceable data flows between consortia partners while maintaining accountability.

 - Model Training Auditability: Embedding watermark identifiers into datasets used for AI model training to allow trace-back in case of bias or misuse.

Sensitive Data Monitoring: Protecting regulated data (e.g., personal health or agricultural subsidy records) by embedding audit trails directly within the dataset.


## Basic Data Catalogue
A basic data catalogue acts as a centralized, searchable inventory that documents all data assets within an organization—including structured tables, unstructured files, dashboards, and ML models. It relies on metadata (technical, operational, and business) to support discovery, trust, and governance. By enabling users to locate relevant data quickly, examine lineage, and understand usage context, a data catalogue dismantles data silos and supports self-service analytics and compliance. https://www.ibm.com/think/topics/data-catalog?utm_source=chatgpt.com

## Data Labelling / Annotation
Data labelling (or annotation) involves applying structured tags or labels to raw data—whether text, images, audio, or video—to enable AI algorithms to understand and learn from it. Common formats include classification labels, bounding boxes, and semantic segmentation. High-quality annotations fuel accurate model training and are essential for domains like autonomous vehicles, medical imaging, and sentiment analysis. https://en.wikipedia.org/wiki/Data_annotation?utm_source=chatgpt.com

## Transformations
Transformations comprise the suite of operations—such as normalization, encoding, pivoting, or scaling—used to convert raw inputs into formats suited for analysis. Tools like dbt (Data Build Tool) exemplify modern transformation orchestration in analytics pipelines. Transformations ensure data consistency and prepare inputs for model training or integration .

## Aggregation and Set Operations
Aggregation involves summarizing granular data (for example, computing the mean, sum, or count across groups), while set operations support combining or comparing datasets (using union, intersection, difference). These techniques are key in feature engineering, enabling analysts to derive meaningful trends and group-level insights—such as average sensor values by location or commonalities between datasets.

## Data Enrichment
Data enrichment enhances existing datasets by integrating external or auxiliary information. This can involve adding weather statistics to agricultural sensors, demographic data to health records, or geospatial context to logistics logs. Enrichment boosts model performance by embedding deeper, contextual knowledge into analytics pipelines.

## Augmented Data Preprocessing
Augmented data preprocessing applies machine learning or AI techniques to automate and enhance traditional preparation steps—such as cleaning, validation, or profiling. Modern platforms leverage natural language queries and ML-powered quality scoring to guide users through preprocessing tasks, democratizing access to advanced analytics. https://www.qlik.com/us/data-management/data-catalog?utm_source=chatgpt.com


## Augmented Data Preparation
Building on preprocessing, augmented data preparation offers a self-service interface that guides users through data ingestion, transformation, and cleaning via AI-enhanced suggestions. These platforms allow analysts to visually explore samples, adjust pipelines, and operationalize them without requiring heavy coding, thereby accelerating time-to-insight and reducing dependency on IT .

## Cloud, Hybrid and Multicloud Support
Modern analytics infrastructure often spans cloud, on‑premises, and multiple cloud providers. Supporting hybrid and multicloud architectures ensures that data catalogues, transformation tools, and ML workflows can seamlessly operate across diverse environments. This flexibility empowers organizations to optimize for data locality, regulatory compliance, and cost-efficiency while maintaining a unified governance layer and enabling distributed processing .

<br>
<br>

# **Data Exploration and Visualisation** 

In advanced data analytics, effective exploration and visualization are foundational to ensuring insightful, reliable, and actionable results. Together, these methods form an advanced toolkit for data exploration in applied AI settings. From univariate/bivariate statistics to interactive and graph-based visual analysis, augmented discovery, and flexible deployment architecture, they empower analysts to extract reliable insights and present them effectively to decision-makers.

Below is a narrative overview of key methods:

## Univariate and Bivariate Statistics
Univariate analysis focuses on the distribution of a single variable—its central tendency (mean, median, mode), variability (variance, standard deviation), and overall shape (skewness, kurtosis), often visualized via histograms or box plots. https://smogdr.github.io/edar_coursebook/eda1.html?utm_source=chatgpt.com https://en.wikipedia.org/wiki/Descriptive_statistics?utm_source=chatgpt.com . Bivariate analysis examines the relationship between two variables, using scatter plots, correlation coefficients, or contingency tables to reveal associations. https://behaveannual.org/statistical-analysis/univariate-and-bivariate-analysis/?utm_source=chatgpt.com

## Statistical Significance Testing
After identifying potential relationships, hypothesis tests (e.g. t-tests, chi-square, ANOVA) assess whether observed differences or correlations are statistically robust, guiding whether findings generalize beyond the sample.

## Signal Preprocessing
Before visualizing time-based or sensor data, preprocessing steps—such as denoising (e.g., filtering), detrending, normalization, and handling missing values—are applied to reveal genuine patterns and avoid spurious anomalies.

## Data Visualizations
Effective visualizations translate numerical insights into clear visual formats—line charts for time series, heatmaps for correlation matrices, geolocation maps for spatial data, and network diagrams for relational patterns—critical for accurate interpretation and stakeholder communication.

## Exporting Results
Exploration outcomes must be shareable; exporting summarized statistics, visual objects, or dashboards (e.g., as CSVs, PowerPoints, or interactive web exports) ensures findings are integrated into reports or used in downstream systems.

## Custom Visualization
Complex projects often require tailored visual formats—such as composite charts, interactive filters, or domain-specific plots—built through libraries like D3.js or Plotly, to emphasize insights tailored for specific audiences (e.g., agronomists, policymakers).

## Clustering and Self-Organizing Maps
Clustering groups similar observations, revealing structure in high-dimensional data. Self‑organizing maps project such clusters onto two-dimensional grids, preserving topological consistency—making latent patterns visually interpretable. https://en.wikipedia.org/wiki/Self-organizing_map?utm_source=chatgpt.com

## Geolocation Mapping
Visualizing data on maps (e.g., heatmaps, choropleths, marker clusters) is instrumental in identifying spatial patterns—such as disease spread, product traceability in supply chains, or sensor coverage in environmental monitoring.

## Affinity and Graph Analysis
Networks are constructed based on entity connections (e.g., co-occurrence, similarity), and graph algorithms highlight affinity structures, detect communities, and visualize relationships—useful in social network analysis or traceability graphing in DLT environments.

## Conjoint and Survey Analysis
In behavioral research, surveys often use conjoint analysis to identify preferences and trade-offs. Responses are statistically analyzed to quantify attribute importance, which is then visualized through bar charts, part-worth utilities, or preference maps.

## Density Estimation
Kernel density estimation and contour plots reveal the distribution of observations, helping identify clusters or anomalies. Useful in continuous data exploration such as geospatial sensor readings or income distributions.

## Similarity Metrics
Quantitative measures—such as Euclidean distance, cosine similarity, Jaccard index, or Mahalanobis distance—are calculated to assess similarity between data points, guiding clustering or nearest-neighbor viewing.

## Augmented Data Discovery
Modern analytics tools integrate AI to automatically suggest visualizations, detect anomalies, and propose filters. This augmented exploration accelerates insights for non-technical users via semantic queries or auto-generated dashboards.

## On-Premises, Cloud, Multicloud and Hybrid
Visualization architectures must adapt to varied environments—on-premises servers, public clouds, or hybrid setups. Multicloud integration ensures that visualization tools (catalogues, dashboards, notebooks) operate seamlessly across distributed platforms while respecting data locality, compliance rules, and interactive performance.


<br>
<br>

#  **User Interface**

## Ease of Use and Learning Curve

## Developer-Focused Data Science

## NLP Q&A

## Documentation

## User Community

## Third-Party Applications

## Visual Pipelining or Visual Composition Framework

## Wizards and Contextual Aids \<start again\>

### ALIDA Home - Dashboard

The ALIDA homepage displays some general information. In the upper-left
corner, there is a link to the ALIDA Official Website, where you can
find information on core functionalities, the technologies used, and
projects where ALIDA has been applied. In the upper-right corner, you'll
find the link to the Official Documentation. *Figure 4.8.1: Home Page -
DASHBOARD*.

On the left side of the screen, there is a panel showing the number of
Available Services (representing the number of BDA Services in the
catalogue), Available Datasets (the number of Datasets registered in
ALIDA), and Available Models (the number of models registered in ALIDA).

In the lower-left corner, the My Stats panel shows your BDA Applications
and BDA Services, categorized by their visibility level as Private,
Team, or Public.

<figure>
<img src="media/image_016_image37.png" style="max-width: 75%; height: auto;"/>
</figure>

> *Figure 4.8.1: Home Page - DASHBOARD*

In the center of the screen, a panel displays a graph of Created
Applications, indicating how many Applications have been created over
time.

Finally, the panel on the right presents the Application Status in a pie
chart, showing possible statuses: completed, failed, and running.

### Notifications

User notifications have become a *must have* in the modern web platforms
in order to be up to date with the current situation and the progress of
tasks and processes.

ALIDA notifications are accessible from every page through the bell icon
on the far right of the navbar on top of the user interface (*Figure
4.8.2: Button to navigate to user notifications section*).



<figure>
<img src="media/image_017_image38.png" style="max-width: 30%; height: auto;"/>
</figure>

> *Figure 4.8.2: Button to navigate to user notifications section*

The main page of notifications section is represented by the list of all
notifications for the current user, as shown in *Figure 4.8.3: User
Notifications List*. From here, the user can perform some basic browsing
on the notifications returned, filter them by date or time, change page
and choose a different page size.

When it comes to notifications, it is crucial to understand which ones
are new and which the user was already aware about: this can be achieved
by the *read* option. By default, all new notifications are *unread* and
the system highlights them in blue, while the ones that the user has
marked as read are plain white. This can be achieved by the "read
notification" button each entry of the list is provided with the
following screen

<figure>
<img src="media/image_018_image39.png" style="max-width: 75%; height: auto;"/>
</figure>

> *Figure 4.8.3: User Notifications List*

to mark one notification at a time, or by the handy shortcut "Mark all
as read" button, placed on the far right among the toolbar items.

#### Notification Preferences

Users are also provided with an extensive section where they can deeply
customise notification settings. It is accessible through a button on
the top right of the notifications list page.

User preferences are divided into *three main categories*:

1.  **Web Preferences** - related to the alerts the users can receive on
    their browser while using the web application.

2.  **Feed Preferences** - related to the alerts the user set on
    different means of communication, like emails, instant messaging
    apps and others.

3.  **Triggers** - related to custom additional logic that can be
    executed upon receiving notifications under specific circumstances.

*Figure 4.8.4: User Notifications Preferences* shows the page that
allows the user to fully personalise the notification settings. First,
the user can choose to enable just specific types of notifications.
Below this select, settings are divided into three tabs, one for each
category.

**Web Preferences** from the Web Preferences tab (*Figure 4.8.5:
Notifications Web Preferences*) the user can first of all choose to
disable all web notifications. When enabled, a list of advanced settings
is listed below, divided in groups.

- **Applications** - the user can enable or disable notifications
  related to the BDA Applications execution or they can change the
  default monitoring behaviour, from getting notifications about the
  applications the user has executed, to getting all notifications
  related to the owned applications or a custom setting, where they can
  choose the specific applications, they want to keep monitoring.

<figure>
<img src="media/image_019_image40.png" style="max-width: 75%; height: auto;"/>
</figure>

> *Figure 4.8.4: User Notifications Preferences*

<figure>
<img src="media/image_020_image41.png" style="max-width: 75%; height: auto;"/>
</figure>

> *Figure 4.8.5: Notifications Web Preferences*

**Feed Preferences** Feed Notifications include all the remaining means
of communication with the user from outside of the platform, external
channels like emails or third-party messaging apps.

<figure>
<img src="media/image_021_image42.png" style="max-width: 75%; height: auto;"/>
</figure>

> *Figure 4.8.6*: Notifications Feed Preferences

As shown in *Figure 4.8.6*: Notifications Feed Preferences, settings are
grouped based on the technology or communication channel. For each of
them, the user can choose to enable or disable the alerts independently
or manage the settings peculiar to the underlying technology:

- **Email** - provided with the email address to send the notification
  to;

**Triggers** The term "Trigger" refers to the custom HTTP requests that
can be registered to be executed upon receiving of certain notifications
based on conditions specified by the user (*Figure 4.8.8: New Trigger
Modal*).

<figure>
<img src="media/image_022_image43.png" style="max-width: 75%; height: auto;"/>
</figure>

> *Figure 4.8.7: Notifications Trigger*

When adding a new trigger or editing an existing one, a modal opens
containing a form asking for all the information about a trigger that's
required for its correct execution.

<figure>
<img src="media/image_023_image44.png" style="max-width: 75%; height: auto;"/>
</figure>

> *Figure 4.8.8: New Trigger Modal*

As *Figure 4.8.8: New Trigger Modal* shows, besides the name, the user
is asked to provide all the basic information related to the HTTP call
to perform, like the **method** (*GET, POST, PUT, PATCH, DELETE*), the
**URL** to send the request to, the optional **query parameters**,
additional **headers** and **body**.

<figure>
<img src="media/image_024_image45.png" style="max-width: 75%; height: auto;"/>
</figure>

> *Figure 4.8.9: Trigger Advanced Settings*

The last tab of the requested set of information related to a
notification trigger contains general settings: the trigger can work
based on the *notification type*, meaning that it will be executed every
time a specific type of notification is received, or it can have an
*advanced* logic, so the user can specify certain conditions for the
execution of the HTTP Request, like the **BDA Application**, the **BDA
Service** and the **asset key** (*Figure 4.8.9: Trigger Advanced
Settings*).

### DataSource

#### Register DataSource

To create a BDA, the first step is to connect to a data source. This
means we need to identify where the data originates from. On ALIDA, you
can connect to various data sources via the "Data Source" menu option.
(*Figure 4.8.10: DataSource Menu*)

<figure>
<img src="media/image_025_image46.png" style="max-width: 75%; height: auto;"/>
</figure>

> *Figure 4.8.10: DataSource Menu*

Once inside Data Source menu, you can view the list of available Data
Sources shown in the "Data Sources List" which includes sources created
by the system or the user over time. New sources can be registered
through "***+ Register Data Source***" where you specify the Name,
Access Level (whether the item is visible as Private, Team, or Public),
and enter a Description field with details on the content of the Data
Source. (*Figure 4.8.11: Register Datasource*)

<figure>
<img src="media/image_026_image47.png" style="max-width: 75%; height: auto;"/>
</figure>

> *Figure 4.8.11: Register Datasource*

It's essential to specify the Data Source type in the Type field, which
could be: Message Broker, useful for streaming flows, or Object Storage,
the default ALIDA system, allowing persistence of structured,
unstructured, and semi-structured generic data, such as Min.IO.
Additional types include Tabular Storage, such as MySQL, and Filesystem
Storage, which acts as a typical filesystem. (*Figure 4.8.12: New
DataSource Registration Form*)

<figure>
<img src="media/image_027_image48.png" style="max-width: 75%; height: auto;"/>
</figure>

> *Figure 4.8.12: New DataSource Registration Form*

Depending on the Data Source type, different fields need to be
specified. For example, Tabular Storage requires fields like Host, Port,
Database, User, and Password. Object Storage types might require fields
such as Driver, Host, and Bucket Access Key.

There is a predefined list of Data Sources. When a new user is created,
ALIDA automatically creates Min.IO spaces: one private, one team-based,
and a public space for all users. A message broker, KAFKA, is available
on all ALIDA instances for potential use in streaming flows.

The page contains all connectors to data storage, which may be internal
(as in the example screen) or created by the user to connect to external
storage.

As you can see, we're not yet dealing with Datasets but rather defining
a source where data can be stored. Only after defining the data source
can a Dataset be created.

### Datasets

#### Create Dataset

The dataset is a representation in the form of metadata for a specific
datasource. To proceed with creating a dataset, select the "***+
Register Dataset***" option. You can find it upper right into Dataset
menu. (*Figure 4.8.13: Register Dataset*)

<figure>
<img src="media/image_028_image49.png" style="max-width: 75%; height: auto;"/>
</figure>

> *Figure 4.8.13: Register Dataset*

In the screen that appears, you can choose the Data Source referring to.
Once the Data Source is selected, choose the desired directory and enter
a description and tags. If the Data Source is of a tabular type, you can
view the table schema with the related fields, which can be edited.
(*Figure 4.8.14: New Dataset Filling Details*)

<figure>
<img src="media/image_029_image50.png" style="max-width: 75%; height: auto;"/>
</figure>

> *Figure 4.8.14: New Dataset Filling Details*

You can then save and access the creation report screen for the new
dataset, with a toast message displaying "*Dataset registered
successfully*," (*Figure 4.8.15: Dataset Registered Successfully*) from
which you can view a Dataset Preview for potential modifications.

<figure>
<img src="media/image_030_image51.jpg" style="max-width: 75%; height: auto;"/>
</figure>

> *Figure 4.8.15: Dataset Registered Successfully*

#### Dataset Handling

In the Datasets List, (*Figure 4.8.16: Dataset List*) you can also
recognize if the dataset was created by a user, indicated by a blue
ribbon displaying the text "*This has been created by user*" If the
dataset is generated by a BDA flow, it is marked by a black ribbon with
the text "*This is an output from an execution*"

> After this, the new dataset will appear in the updated Datasets List.

Another element can be associated with the result of the previous
process, marked with a yellow ribbon and the label "*This has not been
created yet*" This occurs when the application has not yet been executed
with the RUN of the BDA application.

As you access the details of a single Dataset, the following actions are
available: copy to clipboard, preview, edit, and delete.

- **Copy to clipboard** - copies the structure of the Dataset in JSON
  format.

- **Preview** - displays the data contained within the Dataset.

- **Edit** - allows modification of the Dataset structure.

- **Delete** - allows for deletion of the Dataset.

<figure>
<img src="media/image_031_image52.jpg" style="max-width: 75%; height: auto;"/>
</figure>

> *Figure 4.8.16: Dataset List*

### BDA Services

BDA Services are microservices capable of processing Big Data and
handling both BATCH and STREAM data flows. (*Figure 4.8.17: Service
List*)

<figure>
<img src="media/image_032_image53.jpg" style="max-width: 75%; height: auto;"/>
</figure>

> *Figure 4.8.17: Service List*

The creation of these BDA services requires varying timeframes.

Our ALIDA catalogue includes a range of BDA services categorized by
area: ingestion, preparation, processing, analysis, visualization,
evaluation, FML (Federated

Machine Learning) aggregator, and FML participant. (*Figure 4.8.18:
Create New Service*)

<figure>
<img src="media/image_033_image54.jpg" style="max-width: 75%; height: auto;"/>
</figure>

> *Figure 4.8.18: Create New Service*

Within a BDA service, there is a set of properties that are useful
during the design phase.

A BDA service, as exemplified in this case (kmeans-fit-elbow-method),
was created using SPARK, a software employed on ALIDA to scale
computation. In this instance, the scaling is achieved horizontally
across multiple nodes.

Thanks to this microservice utilizing SPARK, it is theoretically
possible to work with Big Data. The parameters shown in the example are
all properties defined by the creator of the BDA service. (*Figure
4.8.19: Kmeans Service Sample*)

<figure>
<img src="media/image_034_image55.jpg" style="max-width: 75%; height: auto;"/>
</figure>

> *Figure 4.8.19: Kmeans Service Sample*

All BDA services are microservices built as Docker images.
(e.g., *gitlab.alidalab.it:5000/alida/analytics/spark-analytics/kmeans-elbow:1.2.0*)

Meanwhile, the Keys list all the properties used during the runtime of
the BDA service.

#### BDA Services Creation

To proceed with the creation of a BDA Service, log in to the ALIDA
platform and select **BDA Service** from the menu in the top-left
corner.

<figure>
<img src="media/image_034_image56.jpg" style="max-width: 75%; height: auto;"/>
</figure>

> *Figure 4.8.20: BDA Service Creation*

A list of Services will appear, and in the top-right corner, you'll find
the **+Register Service** button. (*Figure 4.8.20: BDA Service
Creation*)

By clicking this button opens the **New Service - Register new service
below** screen, which displays input fields, some of which are
mandatory.

Alternatively, you can create a service by selecting **Import
Definition**, where instead of entering each field manually, you can
import a JSON file in textual format containing the required fields for
the service's creation.

<figure>
<img src="media/image_036_image57.jpg" style="max-width: 75%; height: auto;"/>
</figure>

> *Figure 4.8.21: BDA Service - Import Definition*

This interface validates the syntax of the pasted JSON. If the
validation check returns the message **Definition looks good.**, the
JSON is validated, and you can proceed by clicking **Save** to register
the service as defined. (*Figure 4.8.21: BDA Service - Import
Definition*)

Finally, the service properties screen will appear, and you can verify
the newly created service in ALIDA's list of services.

### BDA Application

The BDA App is the component that allows us to define our logic for
analytics.

#### BDA Application Creation

To create a BDA Application, navigate to the **BDA Application** menu
and select **+Create Application**.

You can configure the access level and consequentially, the default data
source available.

For example, if we want to create an application with a defined access
level (e.g., *team*), which will then display the loaded data sources
associated with the corresponding access level, such as *Engineering* in
this example.

Alternatively, if the access level *Public* were selected, all data
sources associated with that access level would be available for
selection.

<figure>
<img src="media/image_037_image58.jpg" style="max-width: 75%; height: auto;"/>
</figure>

> *Figure 4.8.22: BDA Application Creation*

By selecting the *Confirm* button, a dashboard appears displaying all
the available elements, including services, datasets, and models, for
creating the BDA application.

If we want to add a dataset, we can select one from the list available
in the left-hand panel. For instance, we look for a test dataset, such
as the one named *IRIS*.

Next step, we select which service to associate with this dataset by
choosing from the service categories such as *preparation*, *analysis*,
or *fml_aggregator*. (*Figure 4.8.23: BDA App Creation 01*)

<figure>
<img src="media/image_038_image59.jpg" style="max-width: 75%; height: auto;"/>
</figure>

> *Figure 4.8.23: BDA App Creation 01*

Once the dataset is selected, it provides information about the name and
type of its fields.

Additionally, it is possible to preview the dataset, which is displayed
in a table format.

So, we link the *IRIS* dataset as the input to the *KMEANS* BDA service.
This operation is facilitated by the system, which indicates the
connection with *green dots*.

Next, we proceed to select from the models panel, which is represented
by the *blue dot*.

It is straightforward to understand that the output generated by the BDA
service will serve as the input to the chosen ML model.

In this example, we use a *kmeans* service to train a model based on a
specific dataset (*IRIS*). Once the dataset is selected, it provides
information about the name and type of its fields. Additionally, it is
possible to preview the dataset, which is displayed in a table format.

Within the chosen BDA service, it is also possible to define various
parameters, such as *maxIteration* or the *Maximum number of clusters*
and *Minimum number of clusters* to display in the distribution.
(*Figure 4.8.24: BDA App Creation 02*)

<figure>
<img src="media/image_039_image60.jpg" style="max-width: 75%; height: auto;"/>
</figure>

> *Figure 4.8.24: BDA App Creation 02*

The combination of elements can also be multi-layered, meaning that the
output of one model can serve as the input for another BDA service, such
as a prediction service.

Once you consider the configuration as completed, you need to fill in
the *Name* and *Description* fields and click *Create Application* to
create your BDA App.

#### BDA Application Modify

Once the BDA App is created, you can check its presence in the
Application List.

The card provides several details, including the Name, the creator, the
workflow schema, the BDA state (first state is READY), the list of
Application Media it represents, any transitional data with output
elements viewable even before the batch process is complete, and the BDA
version, which changes if it is edited and modified.

Once the BDA App is created, you can check its presence in the
Application List. The card provides several details, including the Name,
the creator, the workflow schema, the BDA state (first state is READY),
the list of Application Media it represents, any transitional data with
output elements viewable even before the batch process is complete, and
the BDA version, which changes if it is edited and modified.

For this BDA, there is still the option to delete it, export it using
EXPORT, or, in the case of standalone operation, run it as a DOCKER
COMPOSE outside the ALIDA cluster. This is achieved by generating a .zip
file containing a .yml Docker file with the characteristics of the
created BDA App. (*Figure 4.8.25: BDA Application Feature*)

In this case, it is crucial to consider both the specifications of the
machine running DOCKER and the accessibility of the data being used.

<figure>
<img src="media/image_040_image61.jpg" style="max-width: 75%; height: auto;"/>
</figure>

> *Figure 4.8.25: BDA Application Feature*

#### BDA Application Run

Once the BDA App has been configured and created, it can either be RUN
or scheduled for execution.

Due to resource distribution, it is not possible to estimate the
execution time of a BDA App, as it needs to gather both data and
services from various Docker images.

Notifications can be received during the RUN of a BDA App; however, this
feature is not available for all BDA Apps.

> As an example, we examine the BDA App called *Adaboost Nocc*.

From this, we can observe not only the multiple versions created during
testing but also, once the app reaches the **COMPLETED** state, the
ability to view *Application Media*. (*Figure 4.8.26: Application Media
Sample*)

<figure>
<img src="media/image_041_image62.jpg" style="max-width: 75%; height: auto;"/>
</figure>

> *Figure 4.8.26: Application Media Sample*

These include additional elements such as *f1_metric*, *roc_metric*, and
*accuracy_metric*, as well as visualizations like *ROC Curve of test
set.png* or *Confusion Matrix of test set.png*.'

<figure>
<img src="media/image_042_image63.jpg" style="max-width: 75%; height: auto;"/>
</figure>

> *Figure 4.8.27: MLflow Tool*

If the trained model within the BDA App is of the FML type, it is
possible to perform a comparison using the *Experiments* button, which
provides access to the *mlflow* tool. (*Figure 4.8.27: MLflow ToolFigure
4.8.27: MLflow Tool*)

#

# **Part III** 

# Machine Learning

#

In the field of applied machine learning, a wide array of algorithms and modeling approaches are used to extract patterns, make predictions, and support decision-making across domains. Below is a detailed and discursive overview of foundational and advanced ML techniques.

## Regression

Regression models aim to predict a continuous output variable based on one or more input features. Common methods include linear regression, ridge/lasso regression, and nonlinear models. These are foundational in applications like demand forecasting, risk scoring, and sensor calibration.

## Time Series Analysis

Time series models capture trends, seasonality, and temporal dependencies in sequential data. Techniques include ARIMA, exponential smoothing, and ML-based forecasting (e.g., LSTM networks). These are widely used in finance, energy, climate modeling, and supply chain analytics.

## Deep Learning (Deep Neural Nets) 

Deep learning uses multi-layer neural networks to model highly complex patterns in data. Architectures such as feedforward networks, CNNs, and autoencoders are trained on large datasets. They are crucial in fields like image recognition, NLP, and biomedical signal processing.

## Reinforcement Learning

Reinforcement learning models learn optimal decision-making policies by interacting with an environment and receiving feedback in the form of rewards. Applications include robotics, game playing, autonomous driving, and real-time resource allocation.

## Classification and Regression Trees

CART models build decision trees by recursively splitting the data based on feature values to minimize prediction error. These interpretable models are used in areas like credit scoring, fraud detection, and clinical diagnostics.

## Further Rule Induction Techniques

Beyond decision trees, rule induction methods like RIPPER or CN2 generate if-then rules from training data. These are valued for their interpretability in domains requiring explainable AI, such as healthcare and legal analytics.

## Support Vector Machines

SVMs are powerful classifiers that find the optimal separating hyperplane between classes by maximizing margin. Kernel functions extend them to nonlinear problems. They are effective in high-dimensional spaces like text classification and bioinformatics.

## Instance-Based Approaches

These methods, such as k-nearest neighbors (KNN), rely on comparing new data to stored instances using distance metrics. They are non-parametric and suitable for pattern recognition in low-dimensional, well-behaved datasets.

## Bayesian Modeling

Bayesian models incorporate prior knowledge and quantify uncertainty in predictions. Techniques include Bayesian linear regression, Naive Bayes classifiers, and probabilistic graphical models. They are useful in uncertain or low-data environments.

## Transfer Learning

Transfer learning leverages knowledge from a pretrained model on a related task to improve performance on a new problem. It is commonly used in image and language models where annotated data is scarce.

## Ensembles and Hierarchical Models

Ensemble methods like bagging (Random Forests), boosting (XGBoost), and stacking combine multiple models to improve accuracy and robustness. Hierarchical models structure relationships between sub-models or levels of abstraction.

## Recommendation Techniques

Recommender systems suggest items to users based on collaborative filtering, content-based filtering, or hybrid approaches. Matrix factorization and deep learning methods drive applications in e-commerce, streaming platforms, and personalized education.

## Measures of Fit

Model evaluation metrics vary by task: R^2, RMSE, MAE for regression; accuracy, precision, recall, F1-score, and ROC-AUC for classification. Proper selection of metrics ensures fair model comparison and tuning.

## Testing of Predictive Models

Model testing involves techniques like train-test split, cross-validation, and bootstrapping. These methods assess model generalization and help prevent overfitting by simulating performance on unseen data.

## CNN, RNN, GNN

CNNs are specialized for image and spatial data, using convolutional layers to capture local patterns. Applications include object detection, medical imaging, and scene understanding.

RNNs process sequential data using recurrent connections to retain memory of past inputs. Variants like LSTM and GRU overcome limitations like vanishing gradients. They are pivotal in time series, NLP, and audio processing.

GNNs operate on graph-structured data, learning representations for nodes, edges, and entire graphs. Use cases include social network analysis, recommendation, and molecular property prediction.

## Generative Adversarial Networks (GAN)

GANs consist of a generator and discriminator in a zero-sum game. The generator learns to produce realistic data while the discriminator distinguishes real from fake. GANs are used for data augmentation, image synthesis, and style transfer.

## Federated Learning

Federated learning enables model training across decentralized devices without centralizing data. It supports privacy-preserving AI in sectors like healthcare, mobile applications, and edge computing by aggregating model updates rather than raw data.

<br>
<br>

# Other Advanced Analytics

#

## Solver approaches

Solver-based approaches use mathematical optimization techniques—such as linear programming, integer programming, and constraint satisfaction—to find the best solution from a feasible set. Widely used in logistics, operations research, and scheduling.

## Heuristic approaches

Heuristics use problem-specific strategies or rules of thumb to find good (but not necessarily optimal) solutions efficiently. Common techniques include greedy algorithms, simulated annealing, and tabu search—applicable in planning, routing, and design problems.

## Design of experiments

DoE is a systematic method for planning, conducting, and analyzing controlled tests to evaluate factors affecting outcomes. It supports robust model development and process optimization in manufacturing, healthcare, and scientific research.

## Discrete Events

Discrete event simulation models systems where state changes occur at distinct points in time, such as in queuing systems or production lines. Useful for evaluating throughput, bottlenecks, and resource utilization.

## Monte Carlo Simulation

Monte Carlo methods use repeated random sampling to estimate the probability distribution of uncertain outcomes. Common in financial risk analysis, reliability engineering, and stochastic modeling.

## Agent-Based Modelling

Agent-based models simulate interactions of autonomous entities (agents) with local rules, revealing emergent system-level behavior. Used in complex systems modeling, from urban mobility to market dynamics.

## Text Analytics

Text analytics extracts structured information from unstructured text using techniques like natural language processing, sentiment analysis, and topic modeling. Applied in document classification, customer feedback analysis, and compliance monitoring.

## Customizable Pretrained Algorithms

Pretrained algorithms—such as transformers or CNNs—can be fine-tuned on domain-specific data to accelerate deployment. This enables rapid adaptation of state-of-the-art models with minimal labeled data.

## Audio Mining

Audio mining analyzes audio content for patterns, keywords, or speaker characteristics. Techniques include speech-to-text, audio segmentation, and acoustic event detection, relevant in customer service, security, and healthcare.

## Image Analytics

Image analytics applies computer vision techniques to extract insights from visual data. Use cases range from quality inspection in manufacturing to satellite image classification and medical diagnostics.

## Geospatial Analysis

Geospatial analysis examines data with spatial components using mapping, spatial statistics, and geocoding. It supports applications in environmental monitoring, urban planning, and location-based services.

## Financial Modelling and Econometrics

These models analyze and forecast financial trends using statistical and mathematical tools. Techniques include time series econometrics, portfolio optimization, and pricing models, supporting investment and policy decisions.

## Decision Modelling

Decision modeling structures complex choices using decision trees, influence diagrams, or cost-benefit frameworks. It enhances clarity and accountability in strategic, operational, or policy decisions.

## Decision Management

Decision management integrates business rules, analytics, and workflows to automate operational decisions. It ensures consistency, compliance, and responsiveness in real-time systems.

## Composite AI

Composite AI combines different AI techniques—such as symbolic reasoning with machine learning—to improve interpretability, adaptability, and performance. This hybrid approach supports AI applications in regulated or knowledge-rich domains.

## Stream Processing/Data in Motion

Stream processing handles real-time data flows—capturing, analyzing, and acting on data as it arrives. Technologies like Apache Kafka and Spark Streaming enable event-driven architectures for fraud detection, IoT, and real-time dashboards.

<br>

<br>

# Flexibility, Extensibility and Openness

#

## R

## Python

## Scala

## Java

## Third-Party Libraries

## Popular Libraries and Frameworks

## Data Science Notebooks

### Read datasets inside Notebooks

To read a dataset registered in ALIDA inside a Notebook you can copy the
dataset metadata from ALIDA UI through the button highlighted below:

Then use the following code inside the notebook. Remember to paste the
copied json (make it one liner) where it says:
\<here-paste-json-metadata-of-dataset\>.

> \# Install requirements
>
> !pip install alida-notebook-utils

import json

from alidanotebookutils.pandasAssets import load_as_pandas_dataframe
os.environ\[\'GET_PROPERTIES_FROM_ENV\'\] = \"true\"

> \# Read dataset
>
> df = load_as_pandas_dataframe(raw_data=json.loads
> (\<here-paste-json-metadata-of-dataset\>)) print(df.sample)

*Figure 3.7.1*:

*Read Dataset*

## Open-Source Data Management Platforms (e.g., Spark and Hadoop)

## Docker

## Scripting and Embedding Capabilities

## Open-Source Automated Machine Learning Tools

## Code Visibility and Transparency

<br>

<br>

# Performance and Scalability

#

## In-Database Analytics

## Big Data Volume Scalability

## Real-Time Data and Streams

## In-Memory, Hadoop and Spark

## Support of GPUs

## Support of Other Specialized Hardware

## Algorithmic Efficiency in a Single-Node or MultipleNode Environment

## Cost guidance

## Performance options for training

## On-Premises

## Cloud, Hybrid and Multicloud

<br>

<br>

# Delivery

#

## Write-back

## Recoding

## REST APIs

## PMML and ONNX

## Augmented Model Deployment and Monitoring

## Containerization

## Web deployment

## Other

## Deployment Mode

In this section, we will explain the process of deploying a model,
turning your work into a service accessible via a REST API. This way
will allow to easily integrate the prediction of your model within
different applications and systems.

### Model Serving

To deploy a model through ALIDA UI, you need to create an AI/ML model
using ALIDA's dedicated section. Once the model reaches the "completed"
status without any errors, navigate to the model details page and click
the play button located in the top right corner of the header.

![](media/image66.jpg){width="5.9055260279965in"
height="1.8980971128608923in"}

Upon clicking, ALIDA will display a panel for configuring deployment
settings as follow:

> ![](media/image67.jpg){width="3.543351924759405in"
> height="2.7087904636920386in"}

- Replicas: Specify the number of copies to be deployed in the cluster.

- CPU Limit: Set a limit on CPU consumption to prevent resource
  saturation.

- Memory Limit: Define a limit on memory consumption to prevent
  resourcesaturation.

Upon clicking the Start button in this window, a pop-up message will
appear, indicating the successful deployment of the model. Subsequently,
the Model Deployment section will provide detailed information about the
deploying model. Once the status transitions from , the service is fully
operational and ready to be utilised for making predictions with the URL
provided within the Model Deployment Section.

to

![](media/image72.jpg){width="5.9055260279965in"
height="2.25879593175853in"}

The deployed model is now prepared to receive prediction requests
through the provided URL. If it becomes unnecessary, you have the option
to halt the deployment by using the Pause button located in the top
right corner.

## Parallel Model Deployments

<br>

# Platform and Project Management

## Compliance and Auditing

## Object Reuse

## Multiuser Capabilities

## Debugging and Unit Testing

## Runtime Optimization

## Audit and Logs

## Data Encryption

## Securing ML Pipeline

## Client Deployment

<br>

# Model Management

## Metadata management

## Traceability

## Champion/Challenger

## Model Telemetry

## Confusion Matrices

## Model Catalog and Reproducibility

## Technical Performance Tracking

## Business Performance Tracking

## Adaptive ML

## Model Alignment to Business Ojectives

## Governance

## Model Licensing Issues

## Scripting and Automation

## Process Monitoring

## Model Management Across Deployment Modes

<br>

# MLOps

## Intro

**N.B. Bisogna capire se fare una sezione specifica per MLOps, oppure
rispondere in maniera puntuale nelle sezioni "Performance and
Scalability", "Delivery" e "Model Management" le cui innovazioni sono
per Gartner il concetto di MLOps.**

In this section we will introduce how ALIDA supports a machine learning
model life cycle.

## Model life cycle

**Questa sottosezione va spostata perché non spiega all'utente come
sfruttare Alida per fare qualcosa, bensì tratta teoria generica.** ML
model life cycle involves a series of interconnected stages aimed at
developing, deploying, and maintaining machine learning models in a
systematic and efficient manner. This life cycle typically consists of
the following key phases:

1.  Problem Definition and Planning:

    - In this initial phase, the business problem or opportunity is
      defined, andthe goals for the machine learning project are
      established.

    - Project stakeholders collaborate to set expectations, identify
      success cri-teria, and allocate resources.

2.  Data Collection and Preprocessing:

    - Relevant data is collected and prepared for model training. This
      involvestasks such as data cleaning, feature engineering, and
      handling missing values.

    - Data quality and integrity are crucial, as they directly impact
      the per-formance and reliability of the machine learning model.

3.  Model Development:

    - Data scientists and machine learning engineers create and train
      modelsusing various algorithms and techniques.

    - This phase involves experimenting with different models,
      fine-tuning pa-rameters, and evaluating performance metrics to
      select the most effective model for the given task.

4.  Model Testing and Validation:

    - Models are tested on independent datasets to assess their
      generalisationcapabilities and ensure they perform well on unseen
      data.

    - Validation is a critical step to detect issues such as overfitting
      and tofine-tune the model for optimal performance.

5.  Model Deployment:

    - The selected model is deployed to production or staging
      environments,making it accessible for integration into
      applications or business processes.

    - MLOps tools, like MLFLOW or SELDON, play a crucial role in
      automat-ing and managing the deployment process, ensuring
      reproducibility and consistency.

6.  Monitoring and Maintenance:

    - Once deployed, models need continuous monitoring to ensure they
      per-form as expected in real-world conditions.

    - MLOps tools facilitate monitoring of model health, tracking
      performancemetrics, and triggering alerts for potential issues.

7.  Model Updates and Iterations:

    - As new data becomes available or business requirements change,
      modelsmay need to be updated or retrained.

    - MLOps practices support automated pipelines for model updates,
      ensur-ing a seamless integration of new versions without
      disrupting ongoing operations.

8.  Retirement or Replacement:

    - Models that no longer meet performance criteria or are no longer
      relevantto business objectives may be retired or replaced with
      more advanced versions.

    - MLOps provides frameworks for graceful model retirement and
      replace-ment processes.

In the next sections, each of this steps will be described, except for
the first one, since it is outside the scope of ALIDA.

## Data collection and preprocessing

**Questo va nella famiglia "Data Access"**

Data collection in ALIDA happens in two ways:

- Using the ALIDA IO Client, a small application that allows to download
  andupload datasets of undefined dimension (up to the tests done so
  far, it is possible to upload any size of dataset).

- Using a streaming BDA app with sink services saving inside ALIDA
  storages.Preprocessing happens within workflows using preprocessing
  service blocks, or can be done inside a Jupyter notebook (an instance
  of Jupyter hub is deployed with ALIDA).

## Model Development, testing and validation

**Se qui l'intenzione era descrivere la presenza del workflow builder
grafico, quella descrizione andrebbe sotto la sezione "Visual Pipelining
or Visual Composition Framework". Altre questioni, inerenti MLFLOW vanno
piazzate altrove, cercando di capire di cosa si vuole parlare, quale
feature si vuole descrivere.**

**Model development** is the main job of analytics workflows. This can
be done using the services available inside ALIDA or developing new ones
starting from available templates (advised), or from scratches to
address specific needs. Regarding fine **tuning** of hyper-parameters we
added support for ML-Flow framework. Each instance of ALIDA comes with
ML-Flow. Inside the page of a BDA app you can click to the experiment
icon and you will be redirected to ML-Flow (check official Ml-Flow doc
for more information). This is only supported with services developed
specifically for ML-Flow. Testing and validation can be done also by
using BDA apps and more specifically using evaluation services.

## Model Deployment

**Anche queste sottosezioni andrebbero spostate, presumibilmente sotto
quella di "Delivery".**

> Currently there are two ways of serving a model:

- Using the play button on the model page (works only for MLFLow
  wrappedmodels and Tensorflow Serving compatible model). Those models
  will be served with Seldon Core on the backend. It is also possible to
  specify resources dedicated to the model serving, such as amount of
  replicas and reserved CPU percentage.

- Using MLFlow generic predict service, that reads model from MLflow
  andserve them inside a BDA app. BDAs can be then exported and work on
  the edge.

## Monitoring and Maintenance

Models can be monitored using frameworks such as Evidently wrapped in
BDA services.

<br>

# Explainable AI

## Explainable AI

## Support for Open Source

## Augmented Explainability

## Explainabiliity Techniques (Including Permutation Importance, Feature Importance, Sensitivity Analysis, Partial Dependence Plots, ICE Plots, Integrated Gradients, Similarity Based Methods and Others)

## Responsible AI

## Regulations

<br>

# Precanned Solutions

## Marketing, Sales and Customer Service

## Finance, Risk Management and Quality Management

## Internet of Things

## Supply Chain/Logistics

## Back-Office Analytics

## IT Operations

## Cybersecurity

## Anomaly Detection

## What-If Scenarios

<br>

# Collaboration

## Collaboration Across All Modeling Steps for Distributed Teams

## Discussion Threads

## Ratings and Recommendations

## Marketplace/Hub

## Multipersona Collaboration

<br>

<br>

# **Part IV**

# R&I Guide

#

# Data Access

## Enterprise Application Integration

## Data Replication and Synchronization

## Basic and Advanced ETL Functionality

## Hybrid and Multicloud Data Sources

## Access to Non-traditional Data Types

## Connectivity to Data Lake Infrastructure

## Data Lineage

## Data Governance and Metadata Management

## API-Based Access to Web Data

# Data Preparation

## Data Blending/Wrangling

## Data Augmentation

## Data Quality Support

## Dataset Partitioning

## Binning and Smoothing

## Filter and Search

## Feature Generation

## Official Watermarking of Datasets

## Basic Data Catalog

## Data Labeling/Annotation

## Transformations, Aggregation and Set Operations

## Data Enrichment

## Augmented Data Preprocessing

## Augmented Data Preparation

## Cloud, Hybrid and Multicloud Support

# Data Exploration and Visualisation

## Univariate and Bivariate Statistics

## Statistical Significance Testing

## Signal Preprocessing

## Data Visualizations

## Exporting Results

## Custom Visualization

## Clustering and Self-Organizing Maps

## Geolocation Mapping

## Affinity and Graph Analysis

## Conjoint and Survey Analysis

## Density Estimation

## Similarity Metrics

## Augmented Data Discovery

## On-Premises

## Cloud, Multicloud and Hybrid

**\**

# User Interface

## Ease of Use and Learning Curve

## Developer-Focused Data Science

## NLP Q&A

## Documentation

## User Community

## Third-Party Applications

## Visual Pipelining or Visual Composition Framework

## Wizards and Contextual Aids

# Machine Learning

## Regression

## Time Series Analysis

## 5.3 Deep Learning (Deep Neural Nets) 5.4 Reinforcement Learning

## Classification and Regression Trees

**5.18**

**Self-Supervised Learning**

## Further Rule Induction Techniques

## Support Vector Machines

## Instance-Based Approaches

## Bayesian Modeling

## Transfer Learning

## Ensembles and Hierarchical Models

## Recommendation Techniques

## Measures of Fit

## Testing of Predictive Models

## CNN, RNN, GNN

## Generative Adversarial Networks (GAN)

## Federated Learning

# Other Advanced Analytics

## Solver approaches

## Heuristic approaches

## Design of experiments

## Discrete Events

## Monte Carlo Simulation

## Agent-Based Modeling

## Text Analytics

## Customizable Pretrained Algorithms

## Audio Mining

## Image Analytics

## Geospatial Analysis

## Financial Modeling and Econometrics

## Decision Modelling

## Decision Management

## Composite AI

## Stream Processing/Data in Motion

# Flexibility, Estensibility and Openness

## R

## Python

## Scala

## Java

## Third-Party Libraries

## Popular Libraries and Frameworks

## Data Science Notebooks

### Intro

**[Questa sottosezione va spostata perché non spiega all'utente come
sfruttare Alida per fare qualcosa, bensì tratta teoria
generica.]{.mark}**

Integrating a big data machine learning platform with python notebooks
(e.g., Jupyter Notebook) can offer several advantages for data
scientists, engineers, and researchers working with large datasets and
complex machine learning tasks. Here are some reasons why such
integration might be beneficial:

- Interactive Data Exploration: python notebooks provide an interactive
  and user-friendly environment for data exploration. Data scientists
  can load, visualise, and manipulate large datasets easily, which is
  crucial for understanding the data before building machine learning
  models.

- Collaboration: notebooks are often coupled with multi-user servers
  allowing multiple users to collaborate on the same platform. This is
  especially useful in a team or educational setting, where data
  scientists and analysts can work together on big data projects, share
  insights, and collaborate on code.

- Reproducibility: notebooks help in documenting the entire data
  analysis and machine learning process. Users can keep track of code,
  comments, and visualisations, making it easier to reproduce results,
  troubleshoot issues, and share findings with others.

- Flexibility: Big data machine learning platforms are often complex,
  requiring advanced configuration and code development. Notebooks offer
  flexibility by allowing users to write code in a more user-friendly
  and modular way, which can be especially helpful for prototyping and
  experimentation.

- Access to Big Data Tools: Big data platforms often come with a variety
  of tools for distributed data processing, such as Apache Spark and
  Hadoop. Integrating these tools with notebooks allows data scientists
  to work with large datasets and leverage distributed computing without
  leaving the familiar notebook environment.

- Visualisations: Notebooks support a wide range of data visualisation
  libraries.This makes it easy to create interactive visualisations of
  big data, helping data scientists explore patterns and trends in the
  data without the complexity of developing BDA services before having a
  clear picture in mind.

- Documentation: Data scientists can use notebooks to document their
  workin a narrative format, combining code, visualisations, and
  explanations. This aids in knowledge sharing, on-boarding new team
  members, and ensuring that the work is well-documented.

- Parallel Computing: Notebook servers can be configured to run
  notebooks onclusters, which is especially beneficial for handling big
  data tasks. Users can leverage parallel computing and distributed
  resources to speed up calculations.

- Ease of Deployment: Notebooks can be set up to run on cloud-based
  infras-tructure, making it easier for organisations to scale their big
  data machine learning projects and access computing resources
  on-demand.

### Technologies involved

Nowadays multiple technologies allow the use of code notebooks. Jupyter
notebooks is probably the most popular choice, however other notebook
technologies, such as R Markdown, Zeppelin, and Databricks notebooks,
have their own strengths. The choice between notebook technologies
should be based on factors like the programming language needed and
specific use cases. A more extensive list of notebook enabling
technologies can be found at [this
link](https://landscape.lfai.foundation/card-mode?category=notebook-environment&grouping=category).

Being the most popular and allowing so far all the desired features for
ALIDA, Jupyter notebook has been chosen. Moreover, as it happens on BDA
services, it can be used in conjuction with pyspark, allowing big data
analytics.

### Jupyter Notebooks

Jupyter notebooks, often referred to simply as "notebooks," are
interactive computing documents that allow you to create and share code,
visualizations, and narrative text. They are widely used in data
science, scientific research, and education for

tasks like data analysis, data visualization, machine learning, and
more. Jupyter notebooks have become particularly popular in the Python
programming community, although they support multiple programming
languages.

Here are some key characteristics and components of Jupyter notebooks:

1.  Cells: Notebooks are composed of cells, which are individual units
    that cancontain code, text, or other content. There are two primary
    types of cells:

    - Code Cells: These cells contain executable code. You can write
      code inlanguages like Python, R, Julia, and others. When you run a
      code cell, it executes the code and displays the output right
      below the cell.

    - Markdown Cells: These cells contain narrative text written in
      Markdownformat. You can use them to provide explanations,
      documentation, and annotations for your code and results.

2.  Interactive Execution: One of the main advantages of Jupyter
    notebooks istheir interactive nature. You can run code cells one by
    one, allowing you to see the immediate results of your code. This
    interactivity is beneficial for data exploration, experimentation,
    and step-by-step code development.

3.  Rich Output: Jupyter notebooks support a wide range of rich media
    outputs,including tables, charts, images, and interactive
    visualizations. This makes them an excellent tool for data
    visualization and storytelling.

4.  Mixing Code and Text: Jupyter notebooks enable you to combine code
    andtext, providing a means for documenting and explaining your work.
    This is especially useful for creating reproducible research reports
    or educational materials.

5.  Kernel: Each notebook is associated with a computational kernel,
    which isresponsible for executing the code in the notebook. You can
    use different kernels for different programming languages.

6.  Exporting and Sharing: Jupyter notebooks can be exported to various
    formats,such as PDF, HTML, Markdown, and more. This makes it easy to
    share your work with others. Notebooks can also be shared online
    through platforms like GitHub, JupyterHub, or cloud-based services
    like Google Colab.

7.  Extensions and Plugins: Jupyter notebooks can be extended with
    variousplugins and extensions that add functionality and improve the
    user experience. For example, JupyterLab is a more advanced
    interface built on top of Jupyter notebooks with additional features
    and plugins.

8.  Version Control: Notebooks can be managed with version control
    systems likeGit, allowing you to track changes over time and
    collaborate with others on the same notebook.

Jupyter notebooks have gained popularity in the data science and
research communities due to their versatility and ability to document,
share, and reproduce computational workflows. They provide an
interactive and user-friendly environment for data analysis and
experimentation.

### Jupyter Hub

JupyterHub is a multi-user web application that allows users to create
and manage Jupyter notebooks on a shared server. Jupyter notebooks are
interactive computing environments that enable users to write and
execute code, display visualizations, and document their work in a
combination of code, text, and multimedia content. Here are some key
features and aspects of JupyterHub:

1.  Multi-User Support: JupyterHub is designed for multi-user
    environments suchas classrooms, research groups, or organizations.
    It enables multiple users to access Jupyter notebooks on a shared
    server, each with their own isolated environments.

2.  Web-Based Interface: Users access JupyterHub through a web browser,
    making it accessible from various devices and platforms. They can
    create, edit, and run Jupyter notebooks from this interface.

3.  User Authentication: JupyterHub supports various authentication
    mechanisms, allowing administrators to control who can access the
    system. Common methods include integrating with LDAP, OAuth, or
    other identity providers.

4.  Isolation and Scalability: JupyterHub provides isolated environments
    for eachuser, which means that users can install their own libraries
    and packages without affecting others. It can also be configured to
    scale horizontally to accommodate a large number of users.

5.  Customization: JupyterHub can be customized to meet the specific
    needs ofan organization or educational institution. You can
    configure it to launch notebooks with different programming
    languages, specify resource limits, and create custom landing pages.

6.  Integration with Spawners: JupyterHub uses spawners to launch user
    notebooks. A spawner is responsible for starting and managing the
    notebook servers. JupyterHub supports various spawners, including
    local spawner (for running on the same server), Docker spawner,
    Kubernetes spawner and more.

7.  Resource Management: JupyterHub can manage resources like CPU and
    memory to ensure that users get a fair share of the available
    resources.

8.  Community and Ecosystem: JupyterHub is part of the Jupyter Project,
    whichincludes a rich ecosystem of tools and libraries for
    interactive computing, data analysis, and scientific computing. It
    is widely used in educational settings and data science workflows.

### Data access

Besides notebook enabling technologies, other instruments are needed. A
user should in fact be able to load ALIDA produced or registered models
and datasets. To this aim many possibilities are available, ranging from
a python library allowing to load them, to more complex solutions.

**Python library** A Python library that enables users to download
datasets from a big data and machine learning platform into notebooks
could provide a convenient and programmatic way to access and retrieve
data from the platform's repositories.

This library's aim would be to simplify the process of acquiring,
importing, and working with data by providing easy-to-use functions.

Moreover, code could be generated inside the platform, allowing even
easier use of it inside notebooks.

**POSIX-compliant file systems** Distributed and scalable
POSIX-compliant file systems could be used to access files directly as a
developer would do on his local machine, without knowing much aboud
ALIDA inner workings and data management.

Basically this would involve reading datasets from the simulated file
system. Let's break down what are the carateristics of these systems:

1.  Distributed File System: A distributed file system is a file system
    that spansmultiple storage servers or nodes. It allows users to
    store and retrieve files on a network of interconnected machines.
    This distribution can improve data availability, fault tolerance,
    and data access speed.

2.  Scalability: Scalability in this context refers to the ability of
    the file systemto handle a growing amount of data, users, or
    workloads. It should be able to scale horizontally (by adding more
    servers) to accommodate increased storage and data processing needs.

3.  POSIX Compliance: POSIX is a set of standards that define the
    behavior ofoperating systems and file systems. A POSIX-compliant
    file system adheres to these standards, ensuring that it provides a
    familiar and consistent interface for working with files and
    directories. POSIX compliance allows applications to interact with
    the file system using standard system calls, such as *open*, *read*,
    *write*, *close*, and others.

4.  Characteristics: A distributed and scalable POSIX-compliant file
    system typically exhibits the following characteristics:

    - Data Consistency: It maintains data consistency and integrity even
      indistributed and fault-prone environments. Users can expect
      reliable data access and storage.

    - Parallelism: It allows multiple users or applications to read and
      writedata concurrently, facilitating high-throughput operations.

    - Data Availability: Data is stored redundantly across multiple
      nodes toensure high availability and fault tolerance.

    - File Locking: Support for file locking and concurrency control
      mecha-nisms to manage access to files when multiple users are
      involved.

    - Metadata Management: Effective management of file and directory
      meta-data (e.g., file permissions, ownership) while maintaining
      performance.

5.  Use Cases: Distributed and scalable POSIX-compliant file systems are
    commonly used in large-scale data processing, big data analytics,
    scientific computing, cloud environments, content delivery networks,
    and any scenario where

a consistent and shared file system interface is needed across multiple
nodes or servers.

**Juice FS** JuiceFS is a distributed and scalable POSIX-compliant file
system designed for cloud-native and big data workloads. JuiceFS is
built to address the challenges of managing large amounts of data in
cloud environments, making it easier to work with big data, machine
learning, and data-intensive applications.

With JuiceFS, massive cloud storage can be directly connected to big
data, machine learning, artificial intelligence, and various application
platforms in production environments. Without modifying code, the
massive cloud storage can be used as efficiently as local storage.

At the time of writing this document it supports the following data
storage:

- Amazon S3 *(and other S3 compatible Object Storage services)*

- Google Cloud Storage

- Azure Blob Storage

- Alibaba Cloud Object Storage Service (OSS)

- Tencent Cloud Object Storage (COS)

- Qiniu Cloud Object Storage (Kodo)

- QingStor Object Storage

- Ceph RGW

- MinIO

- Local disk

- Redis

## Open-Source Data Management Platforms (e.g., Spark and Hadoop)

## Docker

## Scripting and Embedding Capabilities

## Open-Source Automated Machine Learning Tools

## Code Visibility and Transparency

## 

# Performance and Scalability

## In-Database Analytics

## Big Data Volume Scalability

## Real-Time Data and Streams

## In-Memory, Hadoop and Spark

## Support of GPUs

## Support of Other Specialized Hardware

## Algorithmic Efficiency in a Single-Node or MultipleNode Environment

## Cost guidance

## Performance options for training

## On-Premises

## Cloud, Hybrid and Multicloud

# Delivery

## Write-back

## Recoding

## REST APIs

## PMML and ONNX

## Augmented Model Deployment and Monitoring

## Containerization

## Web deployment

## Other

## Deployment Mode

## Parallel Model Deployments

# Platform and Project Management

## 10.1 Compliance and Auditing

## 10.2 Object Reuse

## 10.3 Multiuser Capabilities

## 10.4 Debugging and Unit Testing

## 10.5 Runtime Optimization

## 10.6 Audit and Logs

## 10.7 Data Encryption

## 10.8 Securing ML Pipeline

## 10.9 Client Deployment

# Model Management

## Metadata management

## Traceability

## Champion/Challenger

## Model Telemetry

## Confusion Matrices

## Model Catalog and Reproducibility

## Technical Performance Tracking

## Business Performance Tracking

## Adaptive ML

## Model Alignment to Business Ojectives

## Governance

## Model Licensing Issues

## Scripting and Automation

## Process Monitoring

## Model Management Across Deployment Modes

# Explainable AI

## Explainable AI

## Support for Open Source

## Augmented Explainability

## Explainabiliity Techniques (Including Permutation Importance, Feature Importance, Sensitivity Analysis, Partial Dependence Plots, ICE Plots, Integrated Gradients, Similarity Based Methods and Others)

## Responsible AI

## Regulations

# Precanned Solutions

## Marketing, Sales and Customer Service

## Finance, Risk Management and Quality Management

## Internet of Things

## Supply Chain/Logistics

## Back-Office Analytics

## IT Operations

## Cybersecurity

## Anomaly Detection

## What-If Scenarios

# Collaboration

## Collaboration Across All Modeling Steps for Distributed Teams

## Discussion Threads

## Ratings and Recommendations

## Marketplace/Hub

## Multipersona Collaboration

**\**

<br>

<br>

# **Part V**

# Conclusions

The Viz typesetting markup language is especially suitable for documents
that include BDA application. Assets are rendered properly an easily
once one gets used to the commands.

Given a set of numbers, there are elementary methods to compute its Big
Data Analytics or Big Data Analytics (BDA), which is abbreviated BDA.

# Acronyms

**ALIDA** Advanced Learning and Intelligent Data Analytics. 2

**BDA** Big Data Analytics. 160

**ML** Machine Learning. 110

# Dictionary

**asset** Metadata useful to define a physical entity such as Dataset,
ML Model, Workflow. 160

**bda application** logical set of all the assets that make up a
workflow. 160

**viz** Visualisation tool aimed at charting certain types of datasets.
160

**Appendix A**

Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Ut purus elit,
vestibulum ut, placerat ac, adipiscing vitae, felis. Curabitur dictum
gravida mauris. Nam arcu libero, nonummy eget, consectetuer id,
vulputate a, magna. Donec vehicula augue eu neque. Pellentesque habitant
morbi tristique senectus et netus et malesuada fames ac turpis egestas.
Mauris ut leo. Cras viverra metus rhoncus sem. Nulla et lectus
vestibulum urna fringilla ultrices. Phasellus eu tellus sit amet tortor
gravida placerat. Integer sapien est, iaculis in, pretium quis, viverra
ac, nunc. Praesent eget sem vel leo ultrices bibendum. Aenean faucibus.
Morbi dolor nulla, malesuada eu, pulvinar at, mollis ac, nulla.
Curabitur auctor semper nulla. Donec varius orci eget risus. Duis nibh
mi, congue eu, accumsan eleifend, sagittis quis, diam. Duis eget orci
sit amet orci dignissim rutrum.

Suspendisse vel felis. Ut lorem lorem, interdum eu, tincidunt sit amet,
laoreet vitae, arcu. Aenean faucibus pede eu ante. Praesent enim elit,
rutrum at, molestie non, nonummy vel, nisl. Ut lectus eros, malesuada
sit amet, fermentum eu, sodales cursus, magna. Donec

**Appendix B**

# Publications

In different ways, each of these works contributed to outline ALIDA,
answering a few questions and asking new ones. But, above all, these
works suggested the direction to take from time to time, in some cases
similar to the previous one and in others completely different,
encouraging a continuous tension while looking for solutions to
problems.

The papers published in support of ALIDA are listed below, divided into
journal or conference articles, listed in order of acceptance from the
most recent (top) to the least recent (bottom).

## Book Chapters

> • Massimiliano Aschi, Susanna Bonura, Nicola Masi, Domenico Messina,
> and Davide Profeta (2022). "Cybersecurity and Fraud Detection in
> Financial Transactions". In: *Big Data and Artificial Intelligence in
> Digital Finance: Increasing Personalization and Trust in Digital
> Finance using Big Data and AI*. ed. by John Soldatos and Dimosthenis
> Kyriazis. Cham: Springer International Publishing, pp. 269--278. isbn:
> 978-3-030-94590-9. doi:
> [10.1007/9783-030-94590-9_15](https://doi.org/10.1007/978-3-030-94590-9_15).
> url:
> [https://doi.org/10.1007/978-3-030-945909_15](https://doi.org/10.1007/978-3-030-94590-9_15)

## Conference Papers

- Christos Doulkeridis, Georgios M. Santipantakis, Nikolaos
  Koutroumanis, George

> Makridis, Vasilis Koukos, George S. Theodoropoulos, Yannis
> Theodoridis, Dimosthenis Kyriazis, Pavlos Kranas, Diego Burgos,
> Ricardo Jiménez-Peris, Mariana M. G. Duarte, Mahmoud Attia Sakr,
> Esteban Zimányi, Anita Graser,

Clemens Heistracher, Kristian Torp, Ioannis Chrysakis, Theofanis
Orphanoudakis,

> Evgenia Kapassa, Marios Touloupou, Jürgen Neises, Petros Petrou,
> Sophia Karagiorgou, Rosario Catelli, Domenico Messina, Marcelo
> Corrales Compagnucci, and Matteo Falsetta (2023). "MobiSpaces: An
> Architecture for EnergyEfficient Data Spaces for Mobility Data". In:
> *IEEE International Conference on Big Data, BigData 2023, Sorrento,
> Italy, December 15-18, 2023*. Ed. by Jingrui He, Themis Palpanas,
> Xiaohua Hu, Alfredo Cuzzocrea, Dejing Dou, Dominik Slezak, Wei Wang,
> Aleksandra Gruca, Jerry Chun-Wei Lin, and Rakesh Agrawal. IEEE, pp.
> 1487--1494. doi:
> [10.1109/BIGDATA59044.2023.](https://doi.org/10.1109/BIGDATA59044.2023.10386539)
>
> [10386539](https://doi.org/10.1109/BIGDATA59044.2023.10386539). url:
> <https://doi.org/10.1109/BigData59044.2023.10386539>

- Dimitrios Miltiadou, Stamatis Pitsios, Dimitrios Spyropoulos,
  Dimitrios Alexan-drou, Fenareti Lampathaki, Domenico Messina, and
  Konstantinos Perakis (2021). "A Secure Experimentation Sandbox for the
  Design and Execution of Trusted and Secure Analytics in the Aviation
  Domain". In: *Lecture Notes of the Institute for Computer Sciences,
  Social Informatics and Telecommunications Engineering*. Springer
  International Publishing, pp. 120--134. doi:

> [10.1007/978-3-030-66922-5_8.](https://doi.org/10.1007/978-3-030-66922-5_8)
> url:
> [https://doi.org/10.1007%2F9783-030-66922-5_8](https://doi.org/10.1007%2F978-3-030-66922-5_8)

- Dimitrios Miltiadou, Stamatios Pitsios, Dimitrios Spyropoulos,
  Dimitrios Alexan-drou, Fenareti Lampathaki, Domenico Messina, and
  Konstantinos Perakis (2020). "A Big Data Intelligence Marketplace and
  Secure Analytics Experimentation Platform for the Aviation Industry".
  In: *Big Data Technologies and Applications - 10th EAI International
  Conference, BDTA 2020, and 13th EAI*

> *International Conference on Wireless Internet, WiCON 2020, Virtual
> Event,*
>
> *December 11, 2020, Proceedings*. Ed. by Deze Zeng, Huan Huang, Rui
> Hou, Seungmin Rho, and Naveen K. Chilamkurti. Vol. 371. Lecture Notes
> of the Institute for Computer Sciences, Social Informatics and
> Telecommunications Engineering. Springer, pp. 48--62. doi:
> [10.1007/978-3-030-72802-1\\\_4.](https://doi.org/10.1007/978-3-030-72802-1/_4)
> url: <https://doi.org/10.1007/978-3-030-72802-1%5C_4>

- Davide Profeta, Nicola Masi, Domenico Messina, Davide Dalle
  Carbonare,Susanna Bonura, and Vito Morreale (2019). "A Novel
  Micro-Service Based Platform for Composition, Deployment and Execution
  of BDA Applications". In: *45th Euromicro Conference on Software
  Engineering and Advanced Applications, SEAA 2019,
  Kallithea-Chalkidiki, Greece, August 28-30, 2019*. Ed. by Miroslaw
  Staron, Rafael Capilla, and Amund Skavhaug. IEEE, pp. 182--185. doi:
  [10.1109/SEAA.2019.00037](https://doi.org/10.1109/SEAA.2019.00037).
  url: [https://doi.org/10.1109/SEAA.
  2019.00037](https://doi.org/10.1109/SEAA.2019.00037)

## Journal Papers

> • void

