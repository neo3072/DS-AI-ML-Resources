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
    + Neural networks and deep learning
        * Specific algorithms
        * Notes
            - Deep learning 'learns to learn' in that the algorithm 'picks' the features automatically
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
        * Weathfront
        * Betterment
    + Spotify 'Daily Mix'
    + Personalized news feeds, including Facebook
- Prediction and Classification
    + Many diseases or issues, including stroke, cancer, ...
        * Cancer detection using cell-free genomes
        * cardiovascular events prediction (e.g., heart attack, stroke)
        * Companies
            - Google DeepMind
            - IBM's Watson (Watson for Oncology)
            - Others (Freenome, CureMetrix, ...)
    + Spam for email
    + Smart email categorization (Gmail)
        * Primary, social, and promotion inboxes, as well as labeling emails as important
    + Stock market predictions and algorithmic trading
        * Kavout
        * Sentient
        * Genotick
        * Numerai
        * qplum
    + Crime
        * Who, Type, and location
        * Based on previous crime and social media activity
        * Examples
            - BRS Labs AISight
    + Suicide risk
        * Based on a lot of different risk factors
        * Examples
            - Facebook
            - Instagram
            - Cogito
    + Uber's ETA
    + Credit decisions
        * Underwrite.ai
    + Agriculture - predicting crop yields
        * Descartes Lab
        * Stanford's Sustainability and Artificial Intelligence Lab
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
                + BRS Labs AISight
            - Navigation, including autonomous vehicles
                + Land, water, and space
            - Medical image processing and diagnosis
            - Military
                + Detection of enemy solidiers and vehicles
                + Missle guidance
            - Drones
                + Inspection (pipelines), surveillance, exploration (buildings), and protection
                    * Digital Signal
                    * Shield.ai
            - Item recognition (Amazon Go)
    + Recognition
        * Shazam
        * Delectable/Vivino
        * Facebook photo recognition (highlights faces and suggests friends to tag)
        * Speech/Voice to text (faster to talk than to type acc'g to Stanford)
            - Google Cloud Speech API
        * Text to speech
            - Amazon Polly
        * Video (NEED EXAMPLE)
            - Clarifai
            - Google Cloud Video Intelligence
        * OCR
            - Mobile app check deposits and uploading receipts
            - Post office address recognition
        * Object recognition
            - Pinterest (then used to recommend other pins)
        * Image
            - Clarifai
            - Captricity
            - Google Cloud Vision API
            - Amazon Rekognition
- Clustering and anomaly detection
    + Clustering
    + Anomaly detection
        * Manufacturing
        * Data security
            - Cylance
            - Darktrace
        * Personal security (security screenings at airports, stadiums, concerts, and other venues)
        * Law enforcement
        * Application performance
        * Credit card fraud detection
- Natural language
    + Smart personal assistants
        * Examples
            - Alexa
            - Google Assistant
            - Siri
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
        * Examples
            - Narrative Science
    + NLP and language translation
        * Voicemail transcripts
        * Textio for writing optimal job descriptions
        * eDiscovery
        * Examples
            - Google Natural Language API
            - Google Cloud Translation API
    + NLU and Chatbots
        * Shopping
        * Errands
        * Day to day tasks
        * Examples
            - x.ai (personal assistant)
            - MindMeld
            - Google Inbox Smart Reply
            - Amazon Lex, includes Automatic speech recognition (ASR)
    + Smart instant messaging
        * Google Allo smart messaging app (https://allo.google.com/)
- Marketing and forecasting
    + Marketing
        * Market basket analysis > location and promotions of items
        * Cohort analysis and segmentation > targeted marketing
        * Customer churn prediction > churn prevention
        * Customer lifetime value forecasting > future business value and predicting growth
        * Targeted and personalized advertising
        * Examples
            - Appier
            - Voyager Labs
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
        * Examples
            - Zoox
            - Nauto
            - nuTonomy
    + Home monitoring, control, and security
        * Flare
    + Voice-controled robotics
    + Photo-realistic pictures generation from text or sketches
        * NYU article
    + Music generation
        * Jukedeck
    + Movie and script generation
    + Automatically generated software code
        * DeepCoder (Microsoft and Cambridge)
    + Authentication without passwords (using mobile phone that knows it's you)
        * TypingDNA
    + Customer support
        * DigitalGenius
    + Optimized directions and routes
    + Plagiarism Checkers
    + Robo-readers and graders
    + Virtual reality
    + Gaming
    + Zillow’s “zestimate” feature, which estimates the price of homes
    + Medical/Health
        * BenevolentAI
    + Sales
        * InsideSales.com

## AI-specific Resources

- Articles
    + Coming soon...

