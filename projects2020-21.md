Sensor Analysis, Shambhavi Deshpande Tahiti Dey and Janhavi Sathe

    If we were to manage air pollution, the first step would be to carefully and thoroughly measure the air quality. Air quality is location-specific and varies over time due to changes in traffic density or environmental conditions, so having more stations would give us more insight into the air pollution patterns. However, setting up these stations is a costly endeavor, in terms of finances and physical space required. The motive behind developing the Air Quality Monitoring System was to develop a smaller and cheaper station, thereby making it more accessible to the general public.

    As we set out to build it, we researched and tried out several common low-cost sensors. We chose the sensors from the well-reputed MQ series: the MQ-7 for Carbon Monoxide and the MQ-131 for Ozone. For the MQ-7, we procured a basic module called the Flying Fish FC-22 module. Despite its reputation and widespread use, we found it severely lacking in documentation. Through further investigation, we conclusively determined that the Flying Fish module has the wrong circuitry for the sensor. Problems such as these are commonplace in low-cost sensors. The performance of many popular air pollutant sensors is not tested, and there is very little, or misleading, documentation about their usage. Our work over the past year highlights major issues in the field that can be taken up further as full-time research projects, or to develop new products entirely.



[Dyslexia Detection](https://github.com/algoasylum/Dyslexia_detection), Samik Pal and Soham Joshi 

    Dyslexia is a neurological disorder which effects about 5-10% of the total population which amounts to about 700 million worldwide. It is a language-based learning disability. It's symptoms are different for different people. It generally effects the way in which people read and write. Among the total population of people having difficulties with reading, writing, speaking and spellings, about 70-80% suffer from some level of dyslexia. Dyslexia is generally defined in a spectrum of difficulties. The current methods of detecting dyslexia is based on a series of reading, writing and speaking tests. The drawback of this system of testing is that they are quite expensive and not available everywhere. We developed a technique of detecting dyslexia based on eye tracking using unsupervised Machine Learning classification techiniques. There has already been some research has been done in the domain of detecting this condition by analysing eye-tracking data. We took some inspiration from such a study titled: "Screening for Dyslexia Using Eye Tracking during Reading", conducted by Nilsson Benfatto and his group. Their work relyed on extracting features from the eye-tracking data. They developed a classification algorithm based on a supervised learning method. The data that they worked on was available online and we used the same data for building our classifier. The data consisted of eye-tracking reading of 98 dyslexic candidates and 88 non-dyslexic/control condidates. We wanted to approach the problem from a non-supervised learning perspective. We were curious to see if we could differentiate Dyslexic from non-dyslexic based on the data itself and not relying on the existing labels to train our classifier. We developed an unique approach to analyze eye-tracking data based on the nature of the frequency spectrum.

    Highlights:

    - We used the Eye tracking data set for two groups: control and Dyslexic. Since the reading speed of each person is different, the samples in the data set have varying lengths.
    - We used a binning approach to tackle the unequal lengths of data in two approaches:
        - Binning on Spectral Data: To get equal length vectors which encompass all temporal information.
        - Short time Fourier Transform: Binning on temporal data and then considering the frequency components to evaluate the temporal significance of certain spectral values.
    - PCA: Principal Component Analysis on binned data to reduce the number of dimensions.


Decision Trees, Purva Bhalekar and Ruchi Pendse

    What does entropy (and other information-theoretic concepts) mean in the context of decision trees? We worked on two perspectives of performance: (i) how accurate a tree is, converging towards the notion of an optimal decision tree, and (ii) the time for training and testing, parallelizing key components for speedups. We also developed a methodology for comparing different implementations of the core platform and libraries.

[Epidemic Spread](https://github.com/algoasylum/TDA-UMAP), Soham Joshi and Abhishek Deshpande 

    Various methods have been developed to model the COVID-19 spread, the most typical of which is the use of an SEIR agent-based model on a network. This network graph dictates the interactions between agents (individuals) through the edges of the graph. Existing models use scale-free graphs with random edge generation algorithms to represent social connections. The edge generation in these models follows degree distribution constraints without considering any locality. It can be observed that spatial attributes can affect the interaction of individuals as they are most likely to interact with agents in their vicinity. Thus, a network that accurately represents a population should consider the location of the nodes. In our work, we show that an epidemic simulation is significantly different from existing scale-free models if we consider a location-aware network.

    Preliminary results (using UMAP) presented at pycon India & Intel AI Developers summit. 

    This was in collaboration with the inimitable Varad Deshmukh. Still collaborating after all these years :)

[Rainfall Pattern Quantification](https://github.com/algoasylum/SatelliteImageAnalysis), Siddharth Srivastava, Yash Damania, Raghav Gaggar and Yash Chaudhari

    Variations and fluctuations in precipitation often have adverse impacts on the environment and affect communities in substantial ways. Accurate assessment and analysis of precipitation is thus of prime importance in flood control, developmental planning, and water management. Our goal is to develop a quantitative model that accurately measures the variation in rainfall. We use satellite data to get fine-grained rainfall measurements at a high frequency and across a large geographic area. We aim to characterize and quantify the patterns of rainfall by analysing the time-series data of rainfall and studying the different representations of this data to give accurate measurements. To devise an accurate strategy for pattern quantification, we evaluate existing metrics and also present novel metrics to shed light on the problem of quantifying patterns not just in rainfall, but also the broader time-series domain. We present conclusions on different data representations, metrics, and ultimately analyse the difference in rainfall patterns over a large spatio-temporal scale.

    Preliminary work presented at PyCon 2020
