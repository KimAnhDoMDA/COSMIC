---
title: "Welcome to CASINO"
layout: splash
permalink: /
classes: wide

header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/splash.JPG
excerpt: "Computational Statistics, Biology, and Oncology"
feature_row:
  - image_path: /assets/images/blood-test.JPG
    alt: "Article 1"
    title: "First-of-its-kind study demonstrates the utility of a blood-based biomarker test together with a risk model based on subject characteristics for identifying asymptomatic individuals at high-risk of developing a lethal lung cancer."
    excerpt: "There are approximately 27 million smokers with smoking history of greater than 10 pack-year in the US. It is expected to have 1,341,900 deaths from lung cancer during the next 20 years (67,095 death per year). Our recent study shows a 9% improvement in the sensitivity of detecting lethal lung cancer by comparing the performance of our LungSpot test with current USPSTF criteria.  This is  equivalents to saving additional 24,154 lives from lung cancer death in the US during the next 20 years (1,208 per year) compared to current screening guideline."
    url: "https://ascopubs.org/doi/abs/10.1200/JCO.22.02424?role=tab&journalCode=jco"
  - image_path: /assets/images/oral-microbiome.JPG
    alt: "Article 2"
    title: "Study finds link between oral microbiome and common side effect in patients with head and neck cancer"
    excerpt: "Oral mucositis – the development of sores in the mouth – is a common side effect for patients with head and neck cancers, affecting as many as 90%. It can lead to difficulty eating, weight loss, and readmission or prolonged hospital stays to manage pain or infections. In a new study researchers investigated the influence of oral microbial features on the severity of oral mucositis during and after treatment for patients with squamous cell carcinoma of the head and neck. The research, part of an ongoing project to better understand the mechanisms behind oral mucositis, revealed associations of several specific microbiome features that both positively and negatively correlated with oral mucositis severity. These findings suggest the potential to personalize treatment plans with tailored microbiome interventions that could help minimize severity."
    url: "https://acsjournals.onlinelibrary.wiley.com/doi/10.1002/cncr.35001"
  - image_path: /assets/images/cells.JPG
    alt: "Article 3"
    title: "A machine learning-based method for automatically identifying novel cells in annotating single-cell RNA-seq data"
    excerpt: "Single-cell RNA sequencing (scRNA-seq) has been widely used to decompose complex tissues into functionally distinct cell types. The first and usually the most important step of scRNA-seq data analysis is to accurately annotate the cell labels. In recent years, many supervised annotation methods have been developed and shown to be more convenient and accurate than unsupervised cell clustering. We developed a straightforward yet effective method combining autoencoder with iterative feature selection to automatically identify novel cells from scRNA-seq data. Our method trains an autoencoder with the labeled training data and applies the autoencoder to the testing data to obtain reconstruction errors. By iteratively selecting features that demonstrate a bi-modal pattern and reclustering the cells using the selected feature, our method can accurately identify novel cells that are not present in the training data."
    url: "https://academic.oup.com/bioinformatics/article/38/21/4885/6694844"
feature_row2:
  - image_path: /assets/images/article4.JPG
    alt: "Article 4"
    title: "A unified mediation analysis framework for integrative cancer proteogenomics with clinical outcomes"
    excerpt: 'We develop a general mediation analysis framework for proteogenomic data that include multiple exposures, multivariate mediators on various scales of effects as appropriate for continuous, binary and survival outcomes. Multilevel molecular profiling of tumors and the integrative analysis with clinical outcomes have enabled a deeper characterization of cancer treatment. Mediation analysis has emerged as a promising statistical tool to identify and quantify the intermediate mechanisms by which a gene affects an outcome. However, existing methods lack a unified approach to handle various types of outcome variables, making them unsuitable for high-throughput molecular profiling data with highly interconnected variables. Our estimation method avoids imposing constraints on model parameters such as the rare disease assumption, while accommodating multiple exposures and high-dimensional mediators. We compare our approach to other methods in extensive simulation studies at a range of sample sizes, disease prevalence and number of false mediators. Using kidney renal clear cell carcinoma proteogenomic data, we identify genes that are mediated by proteins and the underlying mechanisms on various survival outcomes that capture short- and long-term disease-specific clinical characteristics.'
    url: "https://academic.oup.com/bioinformatics/article/39/1/btad023/6989623"
  - image_path: /assets/images/microbiome.JPG
    alt: "Article 5"
    title: "Sparse tree-based clustering of microbiome data to characterize microbiome heterogeneity in pancreatic cancer"
    excerpt: 'A novel unsupervised clustering approach in the Bayesian framework to characterize variation in the microbiome across cancer patients. Our proposed method innovates over existing model-based clustering approaches, such as the Dirichlet multinomial mixture model, in three key respects: we incorporate feature selection, learn the appropriate number of clusters from the data, and integrate information on the tree structure relating the observed features. We compare the performance of our proposed method to existing methods on simulated data designed to mimic real microbiome data. We then illustrate results obtained for our motivating data set, a clinical study aimed at characterizing the tumor microbiome of pancreatic cancer patients.'
    url: "https://pubmed.ncbi.nlm.nih.gov/37034187/"
  - image_path: /assets/images/genomics.JPG
    alt: "Article 6"
    title: "DINGO: differential network analysis in genomics"
    excerpt: 'Cancer progression and development are initiated by aberrations in various molecularnetworks through coordinated changes across multiple genes and pathways. It is important tounderstand how these networks change under different stress conditions and/or patient-speciﬁcgroups to infer differential patterns of activation and inhibition. Existing methods are limited to cor-relation networks that are independently estimated from separate group-speciﬁc data and withoutdue consideration of relationships that are conserved across multiple groups.'
    url: "https://www.researchgate.net/publication/279863741_DINGO_Differential_Network_Analysis_in_Genomics"
feature_row3:
  - image_path: /assets/images/genomics.JPG
    alt: "Article 7"
    title: "iDINGO—integrative differential network analysis in genomics with Shiny application"
    excerpt: "Differential network analysis is a vital approach for unraveling the intricate network rewiring implicated in disease progression and development. By constructing differential networks from diverse 'omics data sources, we gain a comprehensive understanding of how interactive systems differ within distinct patient-specific groups. While DINGO has been invaluable in inferring group-specific dependencies and constructing differential networks, it and similar tools are constrained in their ability to analyze data stemming from a single platform. Furthermore, these tools often disregard the hierarchical structure intrinsic to multi-'omics data. To address these limitations, we introduce the iDINGO R package. This innovative tool estimates group-specific dependencies, providing insights into integrative differential networks while accounting for the biological hierarchy among 'omics platforms. Additionally, we've created a user-friendly Shiny application that streamlines the analysis and visualization of results, aiding in the identification of hub genes across platforms."
    url: "https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6030922/"
  - image_path: /assets/images/article8.JPG
    alt: "Article 8"
    title: "Personalized Integrated Network Modeling of the Cancer Proteome Atlas"
    excerpt: 'Personalized (patient-specific) approaches have recently emerged with a precision medicine paradigm that acknowledges the fact that molecular pathway structures and activity might be considerably different within and across tumors. The functional cancer genome and proteome provide rich sources of information to identify patient-specific variations in signaling pathways and activities within and across tumors; however, current analytic methods lack the ability to exploit the diverse and multi-layered architecture of these complex biological networks. We assessed pan-cancer pathway activities for >7700 patients across 32 tumor types from The Cancer Proteome Atlas by developing a personalized cancer-specific integrated network estimation (PRECISE) model. PRECISE is a general Bayesian framework for integrating existing interaction databases, data-driven de novo causal structures, and upstream molecular profiling data to estimate cancer-specific integrated networks, infer patient-specific networks and elicit interpretable pathway-level signatures. PRECISE-based pathway signatures, can delineate pan-cancer commonalities and differences in proteomic network biology within and across tumors, demonstrates robust tumor stratification that is both biologically and clinically informative and superior prognostic power compared to existing approaches. Towards establishing the translational relevance of the functional proteome in research and clinical settings, we provide an online, publicly available, comprehensive database and visualization repository of our findings: https://mjha.shinyapps.io/PRECISE/.'
    url: "https://www.nature.com/articles/s41598-018-32682-x"
  - image_path: /assets/images/article9.JPG
    alt: "Article 9"
    title: "A Bayesian integrative approach for multi-platform genomic data: A kidney cancer case study"
    excerpt: 'Integration of genomic data from multiple platforms has the capability to increase precision, accuracy, and statistical power in the identification of prognostic biomarkers. A fundamental problem faced in many multi-platform studies is unbalanced sample sizes due to the inability to obtain measurements from all the platforms for all the patients in the study. We have developed a novel Bayesian approach that integrates multi-regression models to identify a small set of biomarkers that can accurately predict time-to-event outcomes. This method fully exploits the amount of available information across platforms and does not exclude any of the subjects from the analysis. Through simulations, we demonstrate the utility of our method and compare its performance to that of methods that do not borrow information across regression models. Motivated by The Cancer Genome Atlas kidney renal cell carcinoma dataset, our methodology provides novel insights missed by non-integrative models.'
    url: "https://onlinelibrary.wiley.com/doi/abs/10.1111/biom.12587"
    
---
<p>
Dr. Kim-Anh Do and her dedicated research team are at the forefront of cutting-edge inquiry in Computational StAtisticS, BIology, and ONcOlogy (CASINO). <br />
This dynamic group provides a wealth of expertise in developing statistical and machine-learning methodologies for the integration of biological omic data (genomic, transcriptomic, proteomic, metabolomic, microbiome, single cell RNA-sequencing, and spatial transcriptomic), developing computational tools to efficiently apply our statistical methods to large biological data sets, small clinical data sets or large pan-cancer data sets. <br />
Together, they are passionately committed to advancing statistical research and its transformative impact on healthcare. <br />
Their collective efforts underscore the significance of rigorous statistical methods in unraveling the complexities of biological data, marking them as vital contributors to the ongoing progress of these fields, particularly in personalized medicine and precision oncology. <br />
Our group provides critical collaborative expertise (nonparametric multivariable and dimension reduction methodologies, Bayesian methodology, graphical network modeling, feature selection of biomarkers, and causal models to maximize causal prediction performance) to data scientists, biologists, clinicians, bioinformaticians, geneticists, and statisticians.  We also participate in the education and training of the next generation of computational statisticians and data scientists.</p>

<figure class="center">
<img src="{{ site.url }}{{ site.baseurl }}/assets/images/group.jpg" alt="">
<figcaption>Dr Kim-Anh Do with the CASINO team 2023</figcaption>
</figure>


<div class="centerIframe">
<h1></h1>
<iframe src="https://onedrive.live.com/embed?resid=DD1D7A6CCCA3FEEC%2160909&amp;authkey=!ALLKjlXnQyb-dDA&amp;em=2&amp;wdAr=1.7777777777777777" width="1000px" height="600px" frameborder="0">This is an embedded <a target="_blank" href="https://office.com">Microsoft Office</a> presentation, powered by <a target="_blank" href="https://office.com/webapps">Office</a>.</iframe>
</div>



{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row2" %}

{% include feature_row id="feature_row3" %}
