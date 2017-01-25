# Data Science Goals, Components, Processes, and Deliverables - Data Science, Data Mining, Machine Learning, AI, Advanced Analytics, and Big Data

## Data Science, Artificial Intelligence, Statistics, Advanced Analytics, Big Data, and IoT Fields
- Data/text mining and data exploration
- Data/text analytics
- Descriptive, predictive, and descriptive analytics
- Machine learning
- Recommendations
- Real-time stream processing and computing (spot opportunities and risks)
- Pattern Matching
- Forecasting
- Visualization
- Semantic analysis
- Statistical analysis
- Network and cluster analysis
- Multivariate statistics
- Graph analysis
- Simulation
- Optimization
- Experimental design
- Complex event processing
- Autonomous systems
- Smart machines and devices
- Neural networks and deep learning
- Real-time scoring
- Entity analytics
- Business intelligence
- Streaming media analytics
- Cognitive IoT
- Cognitive chatbots
- Embedded deep learning
- Embodied robotic cognition
- Computer vision
- Virtual and augmented reality
- Knowledge management
- Fraud detection

## Typical data science goals
* Derive discoveries, insights, and value from data collections
* Turning data into actions, including real-time
* Build data products providing actionable information while abstracting away technical details, data, and analytics
* Question discovery
* Improving products for user benefit and experience
* Driving business decisions and solutions
* Improving the decisions your business makes
    - Decision science uses data to analyze business metrics — such as growth, engagement, profitability drivers, and user feedback — to inform strategy and key business decisions.
    - Decision science uses data analysis and visualization to inform business and product decisions.
* Automated decision making, predictions, recommendations, and deeper insights
* Inform strategic decisions
* Inform product changes and drive company KPIs
* Shift from HiPPO decision making to data-driven decision making
* Competitive advantage, differentiation, future-proofing, and opportunity costs
* Complement business intelligence functions
* Predict and advise
* Grow data economy wealth
* Increase ROI and ROA
* Shifting between deductive (hypothesis-based) and inductive (pattern- based) reasoning (ref. Booz, Allen, Hamilton)
    - Deductive
        + Formulate hypotheses about relationships and underlying models
        + Carry out experiments with the data to test hypotheses and models
    - Inductive
        + Exploratory data analysis to discover or refine hypotheses
        + Discover new relationships, insights and analytic paths from the data

## Tasks by Area (Wikipedia)
- Text analytics/mining
    + Information retrieval
    + Text categorization
    + Text clustering
    + Concept/entity extraction
    + Production of granular taxonomies
    + Sentiment analysis
    + Document summarization
    + Entity relation modeling
    + Named entity recognition
    + Recognition of Pattern Identified Entities
    + Coreference
    + Syntactic parsing
    + Part-of-speech tagging
    + Quantitative text analysis
- Anomaly detection
    + Intrusion detection
    + Fraud detection
    + Fault detection
    + System health monitoring
    + Event detection in sensor networks

## General Considerations
- Dimensions for comparison (Kevin Markham)
    + Problem type (classification/regression)
    + Results interpretable by you?
    + Easy to explain algorithm to others?
    + Average predictive accuracy
    + Training speed
    + Prediction speed
    + Amount of parameter tuning needed (excluding feature selection)
    + Performs well with small number of observations?
    + Handles lots of irrelevant features well (separates signal from noise)?
    + Automatically learns feature interactions?
    + Gives calibrated probabilities of class membership?
    + Parametric?
    + Features might need scaling?

## Data Science Components and Considerations
- Data types
    + Structured data
    + Unstructured data
    + Semi-structured data
    + Streaming data
    + Batch data
- Analytic classes
    + Transforming analytics
        * Aggregation
        * Enrichment
        * Processing
    + Learning analytics
        * Regression
        * Clustering
        * Classification
        * Recommend
    + Predictive analytics
        * Simulation
        * Optimization
    + Descriptive analytics
    + Prescriptive analytics
- Learning models
    + Learning style
        * Supervised
        * Unsupervised
        * Semi-supervised
    + Training style
        * Reinforcement learning
        * Online learning
        * Offline learning
    + Parametric vs non-parametric
        * Parametric - assume model form and estimate coefficients
        * Non-parametric - don't assume model form and find best fit to data
- Execution models
    + Sequencing
        * Serial execution
        * Parallel execution
    + Scheduling
        * Streaming execution
        * Batch execution
- Key considerations
    + Curse of dimensionality
    + Prediction vs inference
        * Prediction
            - Model an output variable Y (aka response or dependent variable) as a function of a set of input variables X (aka inputs, features, predictors, independent variables)
                + Estimate f such that: Y = f(X) + err
            - Consider reducible vs irreducible errors
        * Inference
            - Understand how Y varies with X and any underlying relationships between Y and X, particularly wrt. individual predictors and each of their impact on the response
            - Understand the degree to which Y varies with each predictor, e.g., linear, non-linear, ...
    + Prediction accuracy vs model interpretability
    + Bias/variance tradeoff

## Analytics Toolbox
- Mathematical
- Computational
- Visual
- Analytic
- Statistical
- Experimental
- Problem definition
- Model building
- Validation

## Data Science Process (non-linear, iterative, and cyclical)
- Domain discovery, goal identification, and question development
    + Understanding the goal of the project and define objectives
    + Drives mapping the problem space to the solution space
- Determine the type of problem and type of solution required
    + Regression, classification, unsupervised, recommender, reinforcement, text analytics, ...
- Data instrumentation, acquisition, collection, extraction, merging/joining, ETL, storage, and pipeline architecture/development
    + Data sources: raw data, real time measurement, events, IoT, and so on
    + Data warehouse or data lake
        * Data lake eliminates need for ETL according to Booz, Allen, and Hamilton
    + Note that more data is almost always better
- Data munging/wrangling
    - Data parsing, cleaning, and tidying
    - Data processing, transformation, and aggregation
        + Includes feature scaling, normalization, and/or standardization
        + Categorical feature transformation and dummy variables
            * One-hot encoding or category indexing
                - Category indexing
                    + Assign a numeric value to each category
                    + Implies ordering of categories, e.g., 0, 1, 2, ...
                    + Best for ordinal variables
                - One-hot encoding
                    + Converts categories into binary vectors with at most one nonzero value, e.g., [0, 0], [0, 1], [1, 0]
                    + Best for nominal (non-ordinal) variables
            * Note: For large number of categorical features, a good technique is to encode only the most important features (e.g., 95% of the importance) and then assign the rest to an 'others' class
        + Deduplication
        + Data conversions
            * Character dates to dates
            * Numerics to strings and vice versa
        + Format conversion
        + Frequency space
            * Fast fourier transform (FFT)
            * Discrete wavelet transform
        + Euclidian space
            * Coordinate transform
        + Transposition if needed
        + Sorting as needed
    - Data filtering
        + Outlier detection and removal
        + Exponential smoothing
        + Gaussian filter
        + Median filter
        + Noise handling and reduction
    - Find and handle missing values
        + Imputation
            * Generate values for other observations in dataset
                - Random sampling
                - Markov chain monte carlo
            * Without other observations
                - Mean
                - Statistical distributions
                - Regression models
        + Data deletion
- Exploratory data analysis (EDA), statistical analysis, descriptive analytics, and visualization
    + General plots | characteristics, trends, outliers, ...
        * Histogram
        * Scatter plot and scatter matrix (aka pair plots)
        * Box plot
        * Line graph
    + Generate frequency table
    + Target variable distribution
    + Distributiont and outlier detection via box and scatter plots for numeric features
    + Correlation analysis and pairwise distribution plots
    + Plots with point color as label for classification tasks
    + Aggregations and analysis
        * Group for counts, sums, and averages
    + Statistical analysis
        * Sensitivity
        * Correlation (and causation where possible)
        * Variance and standard deviation
        * Mean, median, and mode
        * Max and min
        * Quartiles and inter-quartile
        * Skew and kurtosis
        * Quartiles
        * Distribution
        * Count
        * Range
        * Plots
        * Validation via p-values and confidence intervals
    + Summary statistics
- Feature selection and feature engineering
    + Purpose
        * Simpler and faster training
        * Less computationally expensive
        * Find feature interactions to use as new features
        * Improve model performance
        * Optimize bias/variance tradeoff and minimize overfitting
- Performance metric selection, including:
    + Mean squared error (MSE)
    + Root mean squared error (RMSE)
    + Mean absolute error (MAE)
    + R squared (aka explained variance)
    + [Confusion matrix](https://en.wikipedia.org/wiki/Confusion_matrix)
        * Outcomes
            - True positive
            - True negative
            - False positive (Type 1 error, false alarm)
            - False negative - (Type II error, miss)
        * Metrics
            - Recall, sensitivity, hit rate, or true positive rate (TPR)
                + TP/P = TP/(TP+FN)
                + Fraction of relevant instances that are retrieved
                + How complete the results are
            - Specificity or true negative rate (TNR)
                + TN/N = TN/(FP+TN)
            - Precision or positive predictive value (PPV)
                + TP/(TP+FP)
                + Fraction of retrieved instances that are relevant
                + How useful the results are
            - Negative predictive value (NPV)
                + TN/(TN+FN)
            - Fall-out or false positive rate (FPR)
                + FP/N = FP/(FP+TN) = 1 - TNR
            - False discovery rate (FDR)
                + FP/(FP+TP) = 1 - PPV
            - Miss rate or false negative rate (FNR)
                + FN/P = FN/(FN+TP) = 1 - TPR
            - Accuracy
                + (TP+TN)/(P+N)
            - F1 score, or F-score
                + (2TP)/(2TP+FP+FN)
            - Matthews correlation coefficient (MCC)
            - Informedness or Bookmaker Informedness (BM)
            - Markedness (MK)
    + Receiver operator characteristic (ROC)
        * Area under the ROC curve (AUC)
            - Represents the likelihood of giving the positive example a score higher than a negative example
    + Loss functions
    + Per Kaggle
        * LB: Score you get is calculated on a subset of testing set
        * CV: Score you get by local cross validation is commonly referred to as a CV score.
- Data splitting
    + Training, validation, test
    + Cross-validation as alternative to traditional splitting
- Model selection, training, evaluation, validation, resampling methods, tuning, and complexity reduction
    + Iterative process and involves revisiting previous stages, including model selection
    + Ensemble methods exploration and implementation as needed to achieve performance goals
        * Benefits
            - Bias and variance reduction, thus reduced overfitting risk
            - Increased performance
    + Error analysis and tradeoffs
        * Type 1
        * Type 2
        * ...
    + Kaggle notes
        * Tree-based (top for Kaggle)
            - Gradient Boosted Trees
            - Random Forest
            - Extra Randomized Trees
        * Lower performance
            - SVM
            - Linear Regression
            - Logistic Regression
            - Neural Networks
    + Model validation, resampling methods, and selection
        * E.g., cross-validation
    + Model complexity reduction via subset selection, shrinkage methods, regularization (e.g., ridge regression and lasso), and dimensionality reduction
        * Dimensionality reduction
    + Bias variance tradeoff
    + Hyperparameter optimization, grid search, ...
    + Model tuning goals
        * Performance
        * Accuracy
        * Robustness
        * Speed
- Deliverables, deployment, and results communication (see below)

## Data Science Deliverables
- Automated decision making, predictions, recommendations, and insights
- Deep and actionable insights
    + Story telling
    + Writing
    + Speaking
    + Reports
    + Dashboards
    + Visualizations
    + Presentation
- Statistical analysis
- Asynchronous messaging, notifications, insights, and alerts
- Deployed batch and/or real-time solution (e.g., analytics models and algorithms), potentially including monitoring, performance measurement, analytics, dashboards, and reporting
- Analytics
    + Descriptive analytics - What happened and why?
        * Visualization
        * Exploratory data analysis
    + Predictive analytics - What is the probability of something happening?
        * Machine learning
        * Artificial intelligence
        * Forecasting
    + Prescriptive analytics - What specific recommendations will drive business decisions and help achieve business goals (i.e., what to do if 'X' happens)
- Machine learning and Artificial intelligence specific
    + Supervised learning and prediction
        * Classification
            - Binary (two class) and multi-class
        * Regression
            - Univariate and multivariate
        * Anomoly detection
    + Unsupervised learning
        * Clustering, grouping, and characterizations
        * Anomaly detection
    + Recommendation systems (aka recommendation engine)
    + Recognition
        * Image
        * Speech
        * Video
        * Text and optical character
        * Pattern
        * Audio
        * Facial    
        * Handwriting
    + Text analytics
    + Reinforcement learning
    + Probability estimates and likelihoods
    + Graph analytics (e.g., social network analysis)
    + Health diagnosis
    + Process improvements
- Tradeoff analysis and reporting
    + Precision vs recall
    + Cost of false positives vs false negatives
- Optimization
- Segmentation
- Targeted advertising
- Forecasts
- Risk analysis
- Optimization and response surface models (RSM) for design of experiments (DOE) projects

## Types of Analytics
- [The four types of analytics - Neil Raden](http://www.actian.com/wp-content/uploads/2014/07/Neil-Raden-White-Paper4.pdf)
    + Quantitative R&D - Type I
        * PHD or equivalent
        * The creation of theory and development of algorithms for all forms of quantitative analysis
        * Quantitative Research analytics are performed by mathematicians, statisticians and other pure quantitative scientists
    + Data scientist or quantitative analyst - Type II
        * Advanced math/stats, not nec. PHD
        * More practical than theoretical
        * Incorporation of advanced analytical approaches derived from quantitative R&D activities
        * Two sub-types - both perform roughly the same function – providing guidance and expertise in the application of quantitative analysis – they are differentiated by the sophistication of the techniques applied
            - Heavy
                + Understand the mathematics behind the analytics and may apply very complex tools
            - Light
                + Work with more common and well-understood techniques
                + Approach the problems they deal with using more conventional best practices and/or packaged analytical solutions from third parties
    + Operational analytics - Type III
        * Business domain knowledge, optional background in statistics
            - The part of analytics we’re most familiar with
            - The application of Type II applications into real work is the realm of operational analysts
            - Analytics using the _whats_ without always knowing the _whys_
    + Business intelligence/discovery - Type IV
        * Data and numbers oriented, but no special advanced statistical skills
        * The analytical work we are most familiar with via reports, OLAP, dashboards and visualizations
        * Pulling the right information, and understanding what information means

## Tips
- Random forest usually reach optimum when max_features is set to the square root of the total number of features.
- [How to Rank 10% in Your First Kaggle Competition](https://dnc1994.com/2016/05/rank-10-percent-in-first-kaggle-competition-en/)
    + Ensemble methods
        * Base models should be as unrelated as possibly. This is why we tend to include non-tree-based models in the ensemble even though they don’t perform as well. The math says that the greater the diversity, and less bias in the final ensemble.
        * Performance of base models shouldn’t differ to much.
    + Cross-validation
        * Usually 5-fold CV is good enough
        * We shouldn’t use too many folds if our training data is limited. Otherwise we would have too few samples in each fold to guarantee statistical significance.
        * More folds, the CV score would become more reliable, but the training takes longer to finish as well.
    + Automated pipeline
        * Modularized feature transformations. We only need to write a few lines of codes (or better, rules / DSLs) and the new feature is added to the training set.
        * Automated grid search. We only need to set up models and parameter grid, the search will be run and the best parameters will be recorded.
        * Automated ensemble selection. Use K best models for training the ensemble as soon as we put another base model into the pool.
- [Rules of Machine Learning: Best Practices for ML Engineering](http://martin.zinkevich.org/rules_of_ml/rules_of_ml.pdf)
    + Start with directly observed and reported features as opposed to learned features.
        * A learned feature is a feature generated either by an external system (such as an unsupervised clustering system) or by the learner itself (e.g. via a factored model or deep learning).
        * The primary issue with factored models and deep models is that they are non­convex. Thus, there is no guarantee that an optimal solution can be approximated or found, and the local minima found on each iteration can be different. This variation makes it hard to judge whether the impact of a change to your system is meaningful or random.
    + Use very specific features when you can.
        * You can use regularization to eliminate the features that apply to too few examples.
    + Combine and modify existing features to create new features in human­understandable ways.
        * Transformations, with the two most standard approaches are “discretizations” and “crosses”.
            - Discretization consists of taking a continuous feature and creating many discrete features from it. Don’t overthink the boundaries of these histograms: basic quantiles will give you most of the impact.
            - Crosses combine two or more feature columns.
                + Note that it takes massive amounts of data to learn models with crosses of three, four, or more base feature columns.
            - Crosses that produce very large feature columns may overfit.
    + The number of feature weights you can learn in a linear model is roughly proportional to the amount of data you have.
        * There are fascinating statistical learning theory results concerning the appropriate level of complexity for a model, but this rule is basically all you need to know.
    + Clean up features you are no longer using. Unused features create technical debt.
    + When choosing models, utilitarian performance trumps predictive power.
    + Look for patterns in the measured errors, and create new features.
    + Keep ensembles simple
        * To keep things simple, each model should either be an ensemble only taking the input of other models, or a base model taking many features, but not both
- [Practical advice for analysis of large, complex data sets](http://www.unofficialgoogledatascience.com/2016/10/practical-advice-for-analysis-of-large.html)
    + Technical
        * Look at your distributions
        * Consider the outliers
        * Report noise/confidence
        * Look at examples
        * Slice your data
        * Consider practical significance
        * Check for consistency over time
    + Process
        * Separate Validation, Description, and Evaluation
        * Confirm expt/data collection setup
        * Check vital signs
        * Standard first, custom second
        * Measure twice, or more
        * Check for reproducibility
        * Check for consistency with past measurements
        * Make hypotheses and look for evidence
        * Exploratory analysis benefits from end to end iteration
    + Social
        * Data analysis starts with questions, not data or a technique
        * Acknowledge and count your filtering
        * Ratios should have clear numerator and denominators
        * Educate your consumers
        * Be both skeptic and champion
        * Share with peers first, external consumers second
        * Expect and accept ignorance and mistakes

## Process Models
- [Ask, Get, Explore, Model, Communicate and visualize results](http://www.datascientists.net/what-is-data-science)
- [Sample, Explore, Modify, Model, and Assess - SEMMA](https://en.wikipedia.org/wiki/SEMMA)
- [Acquire, Prepare, Analyze, Act (Booz, Allen, Hamilton)](https://www.boozallen.com/content/dam/boozallen/documents/2015/12/2015-FIeld-Guide-To-Data-Science.pdf)
    + Analyze stage (iterate evaluation)
        * Setup
        * Try
        * Do
- [The Data Science Maturity Model: Collect, Describe, Discover, Predict, Advise (Booz, Allen, Hamilton)](https://www.boozallen.com/content/dam/boozallen/documents/2015/12/2015-FIeld-Guide-To-Data-Science.pdf)
- [Balancing the Five Analytic Dimensions (Booz, Allen, Hamilton)](https://www.boozallen.com/content/dam/boozallen/documents/2015/12/2015-FIeld-Guide-To-Data-Science.pdf)
    + Speed
    + Analytic complexity
    + Accuracy and precision
    + Data size
    + Data complexity
- [Implementation Constraints (Booz, Allen, Hamilton)](https://www.boozallen.com/content/dam/boozallen/documents/2015/12/2015-FIeld-Guide-To-Data-Science.pdf)
    + Computational frequency
    + Solution timeliness
    + Implementation speed
    + Computational resource limitations
    + Data storage limitations
- [Fractal Analytic Model (Booz, Allen, Hamilton)](https://www.boozallen.com/content/dam/boozallen/documents/2015/12/2015-FIeld-Guide-To-Data-Science.pdf)
    + Goal
        * Describe
        * Discover
        * Predict
        * Advise
    + Data
    + Computation
        * Aggregation
        * Enrichment
        * Clustering
        * Classification
    + Action
        * Productization
        * Data monetization
        * Insights and relationships
- [Cross Industry Standard Process for Data Mining - CRISP-DM](https://en.wikipedia.org/wiki/Cross_Industry_Standard_Process_for_Data_Mining)
    + [CRISP Visual Guide](https://exde.files.wordpress.com/2009/03/crisp_visualguide.pdf)
- [Knowledge Discovery in Databases - KDD](https://en.wikipedia.org/wiki/Data_mining#Process)
    + [Overview of the KDD Process](http://www2.cs.uregina.ca/~dbd/cs831/notes/kdd/1_kdd.html)
    + [From Data Mining to Knowledge Discovery in Databases](http://www.kdnuggets.com/gpspubs/aimag-kdd-overview-1996-Fayyad.pdf)
- [Team Data Science Process (TDSP)](https://docs.microsoft.com/en-us/azure/machine-learning/data-science-process-overview) and [Interactive graphic](https://azure.microsoft.com/en-us/documentation/learning-paths/data-science-process/)
- [Acquire, Prepare, Analyze, Report, Act](https://www.coursera.org/learn/big-data-introduction/lecture/Fonq2/steps-in-the-data-science-process)
- [The REASON Method: Relating, Explaining, Selecting, Outlining, and Navigating](http://www.datasciencecentral.com/m/blogpost?id=6448529%3ABlogPost%3A369943)

## Data Mining
Coming soon...

<!-- ## References
- [The Field Guide to Data Science (Booz, Allen, Hamilton)](https://www.boozallen.com/content/dam/boozallen/documents/2015/12/2015-FIeld-Guide-To-Data-Science.pdf) -->
