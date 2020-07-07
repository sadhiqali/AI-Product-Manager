# AI for Business

Companies should look at AI through the lens of business capabilities rather than technologies

## AI can broadly support three important business needs 
- Automating Business process
- Gaining insights through data analysis
- Engaging with customers and employees

## Top Challenges for AI initiatives
- Implementation Challenges
- Lack of Skills
- Data Issues - Data Privacy, accessing and integrating data etc.,
- Integrating AI into the company's roles and functions
- Challenges in measuring and provins business value

Defining your business goals and success metrics is the first step in avoiding AI product failures and continuously monitoring of success metrics

## Success Metrics
- Customer Experience
- Revenue Gain
- Customer Engagement
- Business Process Automation
- Better & faster decision making


## AI Outcome Vs AI Output
Output - Accuracy, Execution Time, Recall & Precision
Outcome  - Generate Revenue, Improve Customer experience, Increase user satisfaction, Automate & Save costs

"Monitor the accuracy, performance and fairness of your AI models and understand the reasoning behind the results" | Output is just a metric to keep tracking, Outcome is what drives the business

### Customer Service Chatbot Example

Output Metrics 
- Number of Active users 
- Number of bot sessions initiated
- Average chat sessions
- Average chats handled by bot
- Number of new users using bot daily, weekly, monthly

Outcome Metrics
- Increase in Conversion Rate
- Customer Support Savings
- Increase in NPS (Net Promoter Score)
- Cost per acquisition
- Lift/Increase in Engagement
- Customer retention rate

Measure, Learn & Evolve

A/B testing helps to make more data-driven decisions, when it comes to evolving your product and improving it.

Things to consider before deciding on a model
- Cost benefit Analysis
- Consider the potential cost of AI Implementation
- What is the long term investment to implement a better model?
- What if the slightly better model requires much larger infrastructure to support in the long term?
- Consider seasonality effect
- Ensure the experiment avoids "Novelty effect" - E.g - When a new product feature is implemented, users may be curious and clicks on various product recommendations and model may pick this clues as which appear to be as normal user behavior

## Monitor Bias
Monitoring and mitigating bias should be an ongoing initiative as you launch and scale an AI product. AI systems are dependent on the data you put into the model. Bad data may contain racial, gender or ideological biases. 
For E.g Alexa and Google Assistant are 30% less likely to understand non-american accents. Bias is obvious in face recognition systems.

Bias is generated from the training data. Training/Screening Data comes from humans and humans are inherently biased!

## Different types of Bias
- Model Bias
- Data Bias 
- Annotation Bias 

We need diversity where subjective opinions matter! If you are building a product that should universally work for all, you need to collect diverse opinions and train your model accordingly.
- Sentiment Analysis
- Search Relevance
- Data Categorization
- Content Moderation
- Image Moderation
- Audio/Text Collection for Speech AI

## Addressing unwanted Bias 
- Collect data from multiple sources, real world examples, avoid relying heavily on academic data sets, cover enough examples and edge cases, ask diverse questions, annotate with diversity, think about users and test with them
- Build user experiences for failure/edge cases
- Take feedback and improve, ensure that the system is actively learning with new examples, real world data with human in the loop (HILT)

## Active Learning
Model
> Low confident Predictions - sent for human training (HILT) - human annotates and sent back to retrain the model. Smart Selection: Identify the most valuable training data units for human annotation. Increases the model accuracy and reduces cost

> High confident predictions - moves to production system

## Real world example: Spam Filter
1. Filter email with machine learning
2. User corrects mislabeled spams
3. Retrain model with user data
4. Accuracy improves with time

## Optimizing for Accuracy Vs Recall Vs Precision
Recall - The percentage of total relevant results correctly classified by your algorithm
Precision - The proportion of the data points model says was relevant actually were relevant
For example, if we are doing a cancer diagnostics, false negative is completely unacceptable than a false positive. In this case recall is more important than precision. 

## Compliance and Ethics
Today, AI products are entrusted with complex decision systems like granting parole, diagnosing diseases, job interviews, for managing trades, granting credits, autonomous vehicles to autonomous weapons. Which raises a serious concern on areas like fairness, trust, ethics, privacy and security.
41% of voice assistant users have concerns about trust and privacy - Microsoft Report. Building trust is the key for AI Product Managers. 

### Privacy-First Approach
- Data laws and AI coexist with privacy first approach
- Deeper understanding & governance of data
- Understand the sensitivity of the data (PII (Personally identifiable information) and PHI (Protected Health information)) etc.,
- Obtain explicit consent and explain to customers how thier data will be processed
