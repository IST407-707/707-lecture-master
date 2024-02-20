# Creating an ML Project Proposal

Not all projects that use data and computers work well as ML projects.  The aim of this document is to help you figure out what a good ML project looks like, and how to build an effective proposal.

__Outline__
1. [Designing ML Projects](#designing-ml-projects) - an overview of the critical elements that go into designing an ML project
2. [Designing an ML Proposal](#designing-an-ml-proposal) - how to write up your proposal in a compelling way
3. [Using Generative AI](#using-generative-ai) - how to use generative AI effectively.

## Designing ML Projects

There are four critical elements to consider when building an ML project:
1. [Stakeholder analysis](#stakeholder-analysis) - who cares?
2. [Objective specification](#objective-specification) - what are you trying to do for your stakeholders?
3. [Data identification](#data-identification) - where are you going to get your data, and is it any good?
4. [Modeling methods](#modeling-methods) - what kind of approach will you use to achieve your objectives?

Each of these items are elaborated below.

### Stakeholders

 One of the most important aspects of a project is to identify a set of stakeholders.  A _stakeholder_ is any person or group that could be potentially impacted by your project effort. Stakeholders vary in their degree of interest and importance to a project, and it is critical to have a comprehensive view when you set about your project. Many fields, including business, policy, design, and marketing offer a variety of taxonomies for thinking about stakeholders.  I do not recommend one in particular, but I do recommend being familiar with these taxonomies because they can be used as tools for thinking about the design of your project.

__The Power / Interest Grid__

![alt text](image.png)

The power / interest matrix (also referred to as Mendelow's matrix[^1]) groups stakeholders along the dimensions of interest and influence.  This is a useful starting point for thinking about stakeholders. The different groups are:

* **High Interest / High Power** These stakeholders are key players that could consist of upper management, directors, or major investors. You should monitor this group closely and ensure they’re fully engaged. They’re very involved with decision making and have the power to stop or pause a project they’re not happy with. 

* **High Interest / Low Power** This group has low influence so they don’t really have a say on business decisions, but they do have a keen interest in them. They could include staff members. Keep them well-informed of changes and be sure to hear out their opinions and suggestions for improvements.

* **Keep satisfied** This could include local governments as they may have the power to change laws and legislation but will likely have minimal interest in your organization. You should still aim to keep them satisfied as you never know when they could move to the high interest and high power category.

* **Low Interest / Low Power** These people don’t have the influence to impact your business, and are not interested in doing so. This means there’s no need to engage or inform this group, but you should monitor them in case their status changes.  

One of the drawbacks of the power / interest matrix is that attention to power might lead the developer or designer to priority individuals or groups who may not be impacted as much as others who do not currently have power, ignoring social inequities and the evolving power dynamics.

__The Salience Model__

![alt text](image-1.png)

The Theory of Stakeholder Identification and Salience[^2] addresses the above issues with the concept of _salience_. Salience is a function of three attributes: power, legitimacy, and urgency. This framework is particularly useful for understanding not just who the stakeholders are but also why their claims might be considered important.  The following offers more detail on each aspect of this framework.

* **Power** Power refers to the ability of a stakeholder to impose their will or influence the project's outcomes. In the context of ML, power can manifest in various ways, such as through control over crucial resources (e.g., data, funding, computational resources), regulatory authority, or influence over public opinion. 

* **Legitimacy** Legitimacy involves the perceived validity or appropriateness of a stakeholder's involvement or claims concerning the project. This attribute is particularly important in ML projects due to the ethical and societal implications of AI technologies. Stakeholders with legitimacy may include affected communities, end-users, industry standards bodies, and ethical watchdogs. 

* **Urgency** Urgency refers to the degree to which stakeholder claims require immediate attention or response. In ML projects, urgency may arise from various factors, such as time-sensitive ethical concerns (e.g., privacy breaches), competitive pressures, or critical societal needs (e.g., health crises). 

* **Stakeholder Salience** Mitchell, Agle, and Wood propose that the presence of one, two, or all three of these attributes increases the salience of a stakeholder to the project managers, meaning the degree to which managers give priority to competing stakeholder claims. 

In its original formulation, the authors of this framework defined seven types of stakeholders based on the combination of these attributes:

* **Dormant Stakeholders** Have power but lack legitimacy and urgency. They have the potential to influence but currently do not have a pressing claim or recognized legitimacy.

* **Discretionary Stakeholders** Possess legitimacy but lack power and urgency. Their claims are considered valid but not pressing or powerful enough to demand immediate action.

* **Demanding Stakeholders** Characterized by urgency but lack power and legitimacy. Although they seek immediate attention, their lack of power and legitimacy often means their claims can be overlooked.

* **Dominant Stakeholders** Have both power and legitimacy, making their claims important to address, though they may not be urgent.

* **Dangerous Stakeholders** Possess power and urgency but lack legitimacy. They can press for immediate action but their lack of a legitimate relationship with the project can pose challenges.

* **Dependent Stakeholders** Have legitimacy and urgency but lack power, relying on others to carry their claims forward.

* **Definitive Stakeholders** Have power, legitimacy, and urgency, making their claims the most salient. They are key players in the project and their needs and concerns must be prioritized.

__Personas__

![alt text](image-2.png)

Ultimately, stakeholders provide you with a set of needs that you will use to guide the development of your project. One powerful tool (used widely in UX and Interaction Design) is through the development of _personas_.  Personas are fictional characters created based on research to represent the different user types that might use a service, product, site, or brand in a similar way. Developing personas usually involves gathering data from user research and then synthesizing it into character profiles that represent key segments of your audience. 

The real power of personas is that they help designers take a stakeholder's point of view, revealing dimensions of need that can be hard to see from the "outside." Personas can also serve as a common reference point for team members and stakeholders, facilitating communication and consensus about whom the project is serving. They help align the team's efforts and ensure that everyone understands the target users' needs and goals.

The process of persona development can be broken into the following steps:

1. **Research** The first step in creating personas is gathering data about the users. This can involve a variety of methods, including interviews, surveys, observation, and analysis of existing data. The goal is to understand the users' behaviors, attitudes, preferences, and needs.

2. **Segmentation** Based on the research findings, the next step is to identify meaningful groups of users who share similar goals, behaviors, or challenges. These segments form the basis of the individual personas.

3. **Creation** For each identified segment, a persona is created. Each persona typically includes demographic information, behaviors, goals, needs, challenges, and any relevant background information that helps bring the persona to life. Personas should also include quotes or narratives that encapsulate their perspective.

4. **Application** The final step is to use the personas throughout the design and development process to guide decisions, prioritize features, and evaluate the user experience.

For instance, in an ML project aimed at predicting recidivism, personas might include:

- A parole board member focused on reducing recidivism rates while ensuring public safety.
- An individual with a criminal record seeking reintegration into society, facing barriers to employment and social services.
- A community representative concerned about the impacts of recidivism on community safety and cohesion.

### Objective Specification

Stakeholders help you decide *what* you are going to do, but what you can do might also dictate how you prioritize your stakeholders.  In all cases, your objectives should be concretely connected to your stakeholder needs.  Note that a stakeholder's needs may or may not be known--in fact, innovation often involves envisioning a desireable future world that others have not yet seen!

When establishing your objectives, it is important to consider the following:

- **Clarity and Scope** Clearly define the problem the ML project aims to solve. This involves understanding the scope of the problem, its relevance to stakeholders, and how an ML solution fits into the broader context. **Every proposed solution must be connected to a specific need.** How will your solution help your identified stakeholders? A well-defined problem statement ensures that the project has a focused direction and that the ML solution developed is actually needed and applicable.

- **Feasibility and Impact** Assess the feasibility of solving the problem with ML techniques and consider the potential impact of the solution. This includes evaluating whether ML is the best approach compared to other solutions and understanding the project's potential social, economic, and environmental impacts.

    When thinking about whether ML is the right tool for the job, it is important to consider several different dimensions:

    - Are you trying to _describe_, _explain_ or _predict_? If the latter, than ML is a good option. However, visualization and statistical analyses often do a better job at highlighting patterns and revealing potential causal influences than ML. Traditional statistical models often offer greater interpretability, making them suitable for situations where explanations are required for compliance, ethical, or operational reasons. ML models, especially complex ones like deep learning, may lack this transparency even though they offer superior performance. 

    - Does your data include complex non-linear interactions, or can it be modeled using linear statistical techniques? ML models are particularly useful for dealing with complex, non-linear relationships and interactions between a large number of features. If the problem at hand involves predicting outcomes based on complex input data with intricate relationships, ML might offer significant advantages over traditional statistics.

    - Is your data high dimensional?  Is there a lot of it? ML techniques often require large amounts of data to perform well and generalize beyond the training set. If you have access to large datasets with many examples, ML can leverage this data to build more accurate and robust models. ML models can also be more effective than other statistical techniques in identifying patterns and significant features, especially with techniques designed to handle overfitting and dimensionality reduction.

- **Ethical Considerations** Ensure that the problem definition incorporates ethical considerations, such as fairness, transparency, and accountability. It's important to consider the ethical implications of the ML project from the outset, including potential biases in the data and algorithms, privacy concerns, and the risk of harm to individuals or groups.

### Data Identification

An ML project cannot proceed without access to a sufficient amount of appropriate data.  There are several important considerations when identifying a dataset. 

#### Data Provenance and Credibility

- **Data Provenance**: Provenance includes the source of the data, the methodology used to collect it, and any transformations it has undergone. Accurate provenance ensures that data can be traced back to its origins, allowing for verification of its authenticity and integrity.

- **Credibility**: Assessing the credibility of the data involves evaluating the reputation and reliability of the data source, the transparency of the collection methods, and the presence of any biases or errors. Credible data sources typically have a track record of accuracy and are transparent about their data collection and processing methodologies.  If your dataset does not come with this additional information, be cautious about using it!

- **Collection Methods**: The methods used to collect the data can significantly impact its quality, relevance, and ethical standing. It's important to evaluate whether the data collection methods were unbiased, scientifically valid, and ethically conducted. This includes considering the sampling strategy, the instruments or measures used, and the context in which data was collected.

- **Transparency and Documentation**: The availability of detailed documentation describing the data collection methods, data processing steps, and any assumptions or limitations is essential for assessing the data's suitability for your project.

#### Accuracy and Coverage

- **Accuracy**: Data accuracy pertains to the correctness and precision of the data points. It's essential to evaluate the data for errors, inconsistencies, and outliers that could skew the results of the ML analysis. Techniques such as data cleaning, validation checks, and anomaly detection can help ensure data accuracy.  This is standard operating procedure in ML, but data which is too noisy might not be a suitable basis for an ML project.

- **Coverage**: The data should comprehensively cover the domain of interest, including all relevant features and a representative sample of observations. Lack of coverage or missing data can lead to biased models and unreliable predictions. It's also important to assess whether the data is up-to-date and reflective of current conditions, especially in rapidly changing domains.

#### Ethical Considerations

- **Personal Identifiable Information (PII)**: The presence of PII in the dataset raises significant privacy concerns. It's essential to identify PII and either anonymize or securely handle it to protect individual privacy. Generally speaking, if you find data that has PII, you should not use it, and you should contact the hosting service to let them know about the breach.

- **Potential Harms**: Evaluate whether the data or the resulting ML analysis could inadvertently lead to harm. This includes considering whether the data reflects or amplifies biases, whether the analysis could be used to target or discriminate against vulnerable populations, and whether the release of the data or findings could have negative societal impacts.

- **Consent and Fairness**: Assess whether the data was collected and is being used in a manner that respects the consent and rights of the individuals it represents. This includes considering the fairness of the data representation and whether certain groups are over- or under-represented.

#### Data Access and Cost

- **Access**: Accessibility of data is a practical concern, especially for sensitive or proprietary datasets. Restrictions on data access can limit the scope of the ML project or necessitate partnerships or licensing agreements.

- **Cost**: The cost of obtaining, storing, and processing data can be significant, especially for large datasets or those requiring special handling for privacy reasons. Budget constraints should be considered when planning ML projects, and cost-effective data management strategies should be developed.

#### Evaluating Collection Methods

- **Collection Methods**: The methods used to collect the data can significantly impact its quality, relevance, and ethical standing. It's important to evaluate whether the data collection methods were unbiased, scientifically valid, and ethically conducted. This includes considering the sampling strategy, the instruments or measures used, and the context in which data was collected.

- **Transparency and Documentation**: The availability of detailed documentation describing the data collection methods, data processing steps, and any assumptions or limitations is essential for assessing the data's suitability for your project.

### Modeling Methods

While libraries like SciKit Learn provide many different models and tools for assembling them, evaluating their performance, and tuning parameter, the modeling approach taken for any given project involves a variety of high level decisions that inform the use of these tools. Rarely is it a simple question of SVM vs. Random Forest vs. Deep Learner. The modeling method is your overall approach, including many different sub-problems that you should strive to anticipate.

The process of developing a modeling method is similar to the ML process you are familiar with already, but each of the steps taken are typically more involved than what you encounter with toy problems.

* **Data Quality and Preparation** In many cases data preparation will include a bit of sleuthing to figure out what the data is about, and enrichment by combining multiple datasets.  After this, you might need to perform multiple transformations - pivoting categorical columns to create new features, discretizing continuous ranges, turning unstructured data into structured data, dimensionality reduction, clustering, and feature creation.

* **Model Selection** It's common to experiment with a variety of models to find the best fit for the data and the problem. This might include simple linear models, decision trees, ensemble methods (like random forests or gradient boosting machines), and neural networks. You might consider several phases of modeling, possibly chaining models together to add successively more informative features. These decisions must be traded off against the scalability and efficiency of these operations. 

* **Evaluation and Iteration** Choosing appropriate evaluation metrics is crucial and should align with the project's objectives and stakeholder needs. For projects with significant social implications, fairness and bias metrics are also critical. Incorporating feedback from stakeholders into the evaluation process can help refine the model and pipeline design, ensuring that the final product meets the intended needs and addresses ethical considerations.

## Designing an ML Proposal

The [Heilmeier Catechism](https://www.darpa.mil/work-with-us/heilmeier-catechism), developed by George H. Heilmeier, is a set of questions designed to help evaluate proposed research projects. It encourages clear thinking and communication about what the project intends to achieve, how it differs from existing approaches, and its potential impacts and risks. Connecting this framework to the previous discussion on stakeholder analysis, objective specification, data identification, and modeling methods provides a structured way to translate your thoughts into a compelling proposal. Here, I focus on the the first five elements of the Heilmeier Catechism, as the remainder are not especially relevant for a class project.

### 1. **What are you trying to do? Articulate your objectives using absolutely no jargon.**

This question aligns with the **objective specification** described above. It's about defining the problem you intend to solve with your ML project in simple, clear terms. For students, this means distilling the complex technical goals of their ML project into a straightforward statement of purpose that anyone can understand, directly reflecting the project's objectives and desired outcomes.

### 2. **How is it done today, and what are the limits of current practice?**

This question requires an understanding of the **current state of affairs and its limitations**, which is part of the initial stakeholder analysis and objective specification. In most cases, this is how we highlight the *need* for your proposed solution. It involves researching how the problem is currently addressed, whether through traditional methods, heuristic approaches, or existing ML solutions, and identifying the gaps or inefficiencies in these approaches. 

### 3. **What is new in your approach and why do you think it will be successful?**

Here, you connect to the **modeling methods** and **data identification** components discussed earlier. This question asks for an explanation of the novelty in your approach, which could be a unique combination of data sources, an innovative application of ML algorithms, or a novel feature engineering technique. It's about articulating how the chosen data and ML methodologies differ from or improve upon existing practices and the theoretical or empirical basis for believing that your approach will address the identified limitations successfully.

### 4. **Who cares? If you are successful, what difference will it make?**

Directly tied to **stakeholder analysis**, this question emphasizes the importance of clearly identifying who will benefit from the project and how. It's about linking the project's outcomes to the needs and interests of specific stakeholders, demonstrating the project's relevance, and the potential impact of its success. By showing who cares about the results, you underline the value of the project beyond its technical merits, highlighting the social, economic, or environmental differences it will make.

### 5. **What are the risks?**

While we've discussed **stakeholder risks** earlier, here the focus is on **project risks**, separate from the broader stakeholder implications. This includes risks related to the feasibility of the approach, such as challenges in data acquisition, potential technical hurdles in model development, scalability issues, or uncertainties around model performance in real-world conditions. Identifying these risks not only demonstrates a realistic understanding of the project's scope and potential obstacles but also shows foresight in planning for how these risks might be mitigated.

The Heilmeier Catechism will help you build comprehensive and critical examination of your envisioned proposed ML project. It ensures that the project is grounded in clear objectives, informed by an understanding of existing solutions and their limitations, designed with innovative and technically sound methods, relevant to identified stakeholders, and cognizant of potential project-specific risks. This structured approach not only aids in the development of robust and impactful ML projects but also in effectively communicating the project's value and feasibility to a broader audience, including non-specialists and funding bodies.

## Using Generative AI

While GenAI tools can be incredibly useful for brainstorming, summarizing research, and generating initial drafts, reliance on them without careful scrutiny can lead to issues in your proposals, such as the use of hyperbolic language and a lack of nuanced understanding.

### Hyperbolic Language and Absolutes

GenAI models often respond to vague or broadly defined prompts with language that might seem overly emphatic or absolute. This can be indicative of a lack of specificity and depth in the input prompt, leading the model to fill in gaps with generalized, strong assertions. For example, consider the following:

- **Prompt**: "Tell me why data is important in ML."
- **AI Response**: "Data is **the backbone of all ML projects**. Without data, developing an ML model is impossible. It's **absolutely crucial** for any successful application."

Here, I've highlighted some of the signals that indicate that your prompt has not provided the AI with enough information to generate a useful response.  Consider the alternative:

- **Prompt**: "Discuss the role of data quality and quantity in training machine learning models for healthcare applications, considering privacy concerns."
- **AI Response**: "In healthcare applications, both the quality and quantity of data play significant roles in training effective ML models. High-quality data ensures models are trained on accurate and relevant information, while sufficient quantity allows for capturing the diversity of patient conditions. However, data collection and use must navigate privacy concerns, adhering to regulations like HIPAA to protect patient information. The balance between data utility and privacy is a key consideration in healthcare ML projects."

In the preceding, the prompt contains enough information for the AI to generate a useful piece of of text. 

As general guidance:

1. **Be Specific in Your Prompts**: Tailor your prompts to be as detailed and specific as possible. Specificity encourages the generation of more precise and measured responses, reducing the likelihood of receiving overly generalized or hyperbolic content.

2. **Question and Validate**: Always question the information provided by AI tools and seek validation through external sources. This is crucial for ensuring the accuracy and reliability of the content, especially for academic and professional work.

3. **Recognize the Limits**: Understand that while AI can generate informative and coherent responses, it may not always capture the nuances of complex topics or the latest developments in a field. Use AI as a starting point, not the final word.

4. **Avoid Over-reliance on Absolutes**: Be wary of responses that use absolutes (e.g., "always", "never") or strong emphatic language (e.g., "crucial", "invaluable") without clear justification. Such language can signal a lack of depth or uncritical acceptance of broad claims.


[^1]: Mendelow A. (1991). Proceedings of the Second International Conference on Information Systems. Cambridge, MA.

[^2]: Mitchell, R. K., Agle, B. R., & Wood, D. J. (1997). Toward a theory of stakeholder identification and salience: Defining the principle of who and what really counts. The Academy of Management Review, 22(4), 853–886
