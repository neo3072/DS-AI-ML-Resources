# Artificial Intelligence

## Types

- AI (encompasses machine learning and other fields)
    + Strong/weak
    + Deep/narrow
    + Hard/soft
    + General
- Machine learning (ML, and subset of AI)
    + Primary
        * Supervised
            - Regression
            - Classification
        * Unsupervised
            - Clustering
            - Anomaly detection
        * Semi-supervised
        * Reinforcement learning
    + Other
        * Transfer learning
        * Recommender systems
            - Content-based and collaborative-based filtering
        * Ensemble methods
            - Bagging (random forests) and boosting

## Common Algorithms

- AI
    + [Neural networks and deep learning](http://www.asimovinstitute.org/neural-network-zoo/)
        * Feed forward neural networks (FF or FFNN) and perceptrons (P)
        * Radial basis function (RBF)
        * Hopfield network (HN)
        * Markov chains (MC or discrete time Markov Chain, DTMC)
        * Boltzmann machines (BM)
        * Restricted Boltzmann machines (RBM)
        * Autoencoders (AE)
        * Sparse autoencoders (SAE)
        * Variational autoencoders (VAE)
        * Denoising autoencoders (DAE) 
        * Deep belief networks (DBN)
        * Convolutional neural networks (CNN or deep convolutional neural networks, DCNN)
        * Deconvolutional networks (DN)
        * Deep convolutional inverse graphics networks (DCIGN)
        * Generative adversarial networks (GAN)Recurrent neural networks (RNN)Long / short term memory (LSTM)
        * Gated recurrent units (GRU)
        * Neural Turing machines (NTM)
        * Bidirectional recurrent neural networks, bidirectional long / short term memory networks and bidirectional gated recurrent units (BiRNN, BiLSTM and BiGRU respectively)
        * Deep residual networks (DRN)
        * Echo state networks (ESN)
        * Extreme learning machines (ELM)
        * Liquid state machines (LSM)
        * Support vector machines (SVM)
        * Kohonen networks (KN, also self organising (feature) map, SOM, SOFM)
    + Notes
        * Deep learning 'learns to learn' in that the algorithm 'picks' the features automatically
- ML
    + Refer to this repo's algorithms [page](https://github.com/InnoArchiTech/datascience-ai-machinelearning-resources/blob/master/Algorithms%20and%20Tasks.md)

## AI and ML Process (High-level)

- Ask the right question
- Obtain the data
- Parse and process the data
- EDA - statistical analysis and data visualization
- Choose models/algorithms and performance metric
- Iterate and improve performance
- Deliver/communicate/present results

## AI and ML Considerations and Tradeoffs (High-level)

- Overfitting (bias vs variance, noise)
- Model performance vs interpretability
- Model complexity vs simplicity (i.e., parsimony)
- Curse of dimensionality
- Unsupervised learning limitations for AI

## Real-world Applications and Vendors by Category

- Recommender systems
    + Netflix
        * Increase engagement, retention, and revenues
        * Examples
            - "Because you watched ..."
            - "Top picks for ..."
            - Recommendations by category
                + Trending Now
                + Neflix originals
                + TV Documentaries
    + Amazon
        * Increase average order size and therefore sales (studies show between 5.9 to 30%)
        * Examples
            - "Customers who bought this item also bought"
            - "Customers who viewed this item also viewed"
            - "What other items do customers buy after viewing this item?"
            - "Recommendations for you in ..." (e.g., "Recommended for You in Kindle Books")
            - "New for you"
            - "Inspired by your shopping trends"
            - "Inspired by your Wish List"
    + Robo-advisors and portfolio rebalancing
        * [Weathfront](https://www.wealthfront.com/)
        * [Betterment](https://www.betterment.com/)
    + Spotify
        * [Daily Mix](https://support.spotify.com/us/using_spotify/search_play/daily-mix/)
    + Personalized news feeds, including Facebook
- Prediction and Classification
    + Many diseases or issues, including stroke, cancer, ...
        * Cancer detection using cell-free genomes
        * Cardiovascular events prediction (e.g., heart attack, stroke)
        * Companies
            - [Google DeepMind](https://deepmind.com/)
            - IBM's [Watson](https://www.ibm.com/watson/) (Watson for Oncology)
            - Others
                - [Freenome](https://www.freenome.com/)
                - [CureMetrix](http://curemetrix.com/)
    + Spam for email
    + Smart email categorization (Gmail)
        * Primary, social, and promotion inboxes, as well as labeling emails as important
    + Stock market predictions and algorithmic trading
        * Companies
            - [Kavout](https://www.kavout.com/)
            - [Sentient](http://www.sentient.ai/)
            - [Genotick](http://genotick.com/)
            - [Numerai](https://numer.ai/)
            - [QPLUM](https://www.qplum.co/)
    + Crime
        * Who, Type, and location
        * Based on previous crime and social media activity
        * Companies
            - [BRS Labs AISight](https://www.genetec.com/solutions/resources/brs-labs-aisight-technology-and-omnicast-integration)
    + Suicide risk
        * Based on a lot of different risk factors
        * Companies
            - [Facebook](https://research.fb.com/category/facebook-ai-research-fair/)
            - [Instagram](https://www.instagram.com/)
            - [Cogito](https://www.cogitocorp.com/)
    + Uber's ETA
    + Credit decisions
        * Companies
            - [Underwrite.ai](http://www.underwrite.ai/)
    + Agriculture - predicting crop yields
        * Companies
            - [Descartes Lab](http://www.descarteslabs.com/)
            - [Stanford's Sustainability and Artificial Intelligence Lab](http://sustain.stanford.edu/)
- Computer vision and recognition
    + Computer vision
        * Components
            - Recognition (e.g., objects)
            - Motion analysis
            - Scene reconstruction
            - Image restoration
        * Examples
            - Manufacturing 
                + Inspections
                + Quality control
                + Assembly line
            - Visual surveillance
                + Companies
                    * [BRS Labs AISight](https://www.genetec.com/solutions/resources/brs-labs-aisight-technology-and-omnicast-integration)
            - Navigation, including autonomous vehicles
                + Land, water, and space
            - Medical image processing and diagnosis
            - Military
                + Detection of enemy solidiers and vehicles
                + Missle guidance
            - Drones
                + Inspection (pipelines), surveillance, exploration (buildings), and protection
                + Companies
                    * [Digital Signal](http://www.digitalsignalcorp.com/)
                    * [Shield.ai](http://shield.ai/)
            - Item recognition
                + Companies
                    * [Amazon Go](https://www.amazon.com/b?node=16008589011)
    + Recognition
        * [Shazam](https://www.shazam.com/)
        * Wine
            - Companies
                + [Delectable](https://delectable.com/)
                + [Vivino](https://www.vivino.com/)
        * Facebook photo recognition (highlights faces and suggests friends to tag)
        * Speech/Voice to text (faster to talk than to type acc'g to Stanford)
            - Companies
                + [Google Cloud Speech API](https://cloud.google.com/speech/)
        * Text to speech
            - Companies
                + [Amazon Polly](https://aws.amazon.com/polly/)
        * Video
            - Companies
                + [Clarifai](https://www.clarifai.com/)
                + [Google Cloud Video Intelligence](https://cloud.google.com/video-intelligence/)
        * OCR
            - Mobile app check deposits and uploading receipts
            - Post office address recognition
        * Object recognition
            - Companies
                + [Pinterest](https://medium.com/@Pinterest_Engineering) (then used to recommend other pins)
        * Image
            - Companies
                + [Clarifai](https://www.clarifai.com/)
                + [Captricity](http://captricity.com/)
                + [Google Cloud Vision API](https://cloud.google.com/vision/)
                + [Amazon Rekognition](https://aws.amazon.com/rekognition/)
- Clustering and anomaly detection
    + Clustering
    + Anomaly detection
        * Manufacturing
        * Data security
            - Companies
                + [Cylance](https://www.cylance.com/en_us/home.html)
                + [Darktrace](https://www.darktrace.com/)
        * Personal security (security screenings at airports, stadiums, concerts, and other venues)
        * Law enforcement
        * Application performance
        * Credit card fraud detection
- Natural language
    + Smart personal assistants
        * Companies
            - [Alexa](https://developer.amazon.com/alexa)
            - [Google Assistant](https://assistant.google.com/)
            - [Siri](https://www.apple.com/ios/siri/)
        * Uses
            - Internet searches and answer questions
            - Set reminders
            - Integrate with your calendar
                + Make appointments
            - Receive sports, news, and finance updates
            - Create to-do lists
            - Order items online
            - Use services (e.g., order an Uber)
            - Play music
            - Play games
            - Smart home integration
    + NLG - computer generated reports and news
        * Summarizing documents
        * Story telling
        * Sports recaps
        * Companies
            - [Narrative Science](https://www.narrativescience.com/)
    + NLP and language translation
        * Voicemail transcripts
        * eDiscovery
        * Companies
            - [Google Natural Language API](https://cloud.google.com/natural-language/)
            - [Google Cloud Translation API](https://cloud.google.com/translate/)
            - [Textio](https://textio.com/) for writing optimal job descriptions
    + NLU and Chatbots
        * Shopping
        * Errands
        * Day to day tasks
        * Companies
            - [x.ai](https://x.ai/) (personal assistant)
            - [MindMeld](https://www.mindmeld.com/)
            - [Google Inbox Smart Reply](https://blog.google/products/gmail/save-time-with-smart-reply-in-gmail/)
            - [Amazon Lex](https://aws.amazon.com/lex/), includes Automatic speech recognition (ASR)
    + Smart instant messaging
        * Companies
            - [Google Allo](https://allo.google.com/) smart messaging app (https://allo.google.com/)
- Marketing and forecasting
    + Marketing
        * Market basket analysis > location and promotions of items
        * Cohort analysis and segmentation > targeted marketing
        * Customer churn prediction > churn prevention
        * Customer lifetime value forecasting > future business value and predicting growth
        * Targeted and personalized advertising
        * Companies
            - [Appier](https://www.appier.com/)
            - [Voyager Labs](http://voyagerlabs.co/)
    + Forecasting
        * Revenue and growth
- Other
    + Google search
    + Autonymous vehicles (Business insider)
        * Reduce accidents and related injuries and death
        * Improved traffic (via ridesharing and smart traffic lights) and fuel efficiency
        * Reduced carbon emissions
        * Faster commutes and travel time
        * Get your time back in the vehicle to do what you want
        * Efficient ride-sharing
        * Companies
            - [Zoox](http://zoox.com/)
            - [Nauto](http://www.nauto.com/)
            - [nuTonomy](http://nutonomy.com/)
    + Home monitoring, control, and security
        * Companies
            - [Flare](https://buddyguard.io/)
    + Voice-controled robotics
    + Photo-realistic pictures generation from text or sketches
        * [NYU article](http://cds.nyu.edu/astronomers-explore-uses-ai-generated-images-using-ai-generating-imagess/)
    + Music generation
        * Companies
            - [Jukedeck](https://www.jukedeck.com/)
    + Movie and script generation
    + Automatically generated software code
        * Companies
            - [DeepCoder](https://openreview.net/pdf?id=ByldLrqlx) (Microsoft and Cambridge)
    + Authentication without passwords (using mobile phone that knows it's you)
        * Companies
            - [TypingDNA](https://typingdna.com/)
    + Customer support
        * Companies
            - [DigitalGenius](https://www.digitalgenius.com/)
    + Optimized directions and routes
    + Plagiarism Checkers
    + Robo-readers and graders
    + Virtual reality
    + Gaming
    + [Zillow’s](https://www.zillow.com/zestimate/) “zestimate” feature, which estimates the price of homes
    + Medical/Health
        * Companies
            - [BenevolentAI](http://benevolent.ai/)
    + Sales
        * Companies
            - [InsideSales.com](https://www.insidesales.com/)

## AI-specific Resources

- Articles
    + [AI 100: The Artificial Intelligence Startups Redefining Industries](https://www.cbinsights.com/blog/artificial-intelligence-top-startups/)
    + [Sensors, Plus Brains: 17 IoT Companies Using Artificial Intelligence Tech](https://www.cbinsights.com/blog/artificial-intelligence-iot-company-list/)
    + [Meet the 2017 CNBC Disruptor 50 companies](http://www.cnbc.com/2017/05/16/the-2017-cnbc-disruptor-50-list-of-companies.html)
    + [MIT - The Missing Link of Artificial Intelligence](https://www.technologyreview.com/s/600819/the-missing-link-of-artificial-intelligence/)
    + [Everyday Examples of Artificial Intelligence and Machine Learning](https://www.techemergence.com/everyday-examples-of-artificial-intelligence-and-machine-learning/)
    + [What is Artificial Intelligence? An Informed Definition](https://www.techemergence.com/what-is-artificial-intelligence-an-informed-definition/)
    + Company-specific
        * [Q&A: Uber’s machine learning chief says pattern-finding computing fuels ride-hailing giant](https://www.geekwire.com/2016/uber-collapse-without-pattern-finding-computers-says-chief-machine-learning/)
        * [Netflix - Recommending for the World](https://medium.com/netflix-techblog/recommending-for-the-world-8da8cbcf051b)
        * [Netflix Recommendations: Beyond the 5 stars (Part 1)](https://medium.com/netflix-techblog/netflix-recommendations-beyond-the-5-stars-part-1-55838468f429)
        * [Amazon Help - About Recommendations](https://www.amazon.com/gp/help/customer/display.html?ie=UTF8&nodeId=16465251)
- Videos
    + [The Promise of AI](https://vimeo.com/215926017)

