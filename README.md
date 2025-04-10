# Impact of AI on Digital Media

## Table of Contents

-[Project Overview](#project-overview)

-[Data Sources](#data-sources)

-[Tools](#tools)

-[Explanatory Data Analysis](#explanatory-data-analysis)

-[Recommendations](#recommendations)



### Project Overview

This project analyzes the impact of Artificial Intelligence (AI) on the digital media industry across various countries. It examines key factors such as AI adoption rates, the volume of AI-generated content, and the extent of job losses due to AI. Additionally, the project explores the revenue increases driven by AI, the rate of human-AI collaboration, and the tools most commonly used in the industry. The analysis also covers the regulatory landscape, consumer trust in AI, and the market share of AI companies. Through this data-driven approach, the project highlights the evolving role of AI in transforming the digital media sector.


### Data Sources


The primary dataset used for this analysis is the 'Global_AI_Content_Impact_Dataset.csv' file containing detailed information about the influence of AI-generated content across various industries, including journalism, social media, entertainment, and marketing.


### Tools
- Excel - Data Cleaning
- SQL server - Data Analysis
- Tableau - Creating dashbords and reports

### Data Cleaning/Preparation

In the initial data cleaning phase, I performed the following tasks:
1. Data Loading and Inspecion.
2. Handling Missing Values.
3. Data Cleaning and Formatting.

### Explanatory Data Analysis
In this stage, I conducted an in-depth exploration of the dataset to uncover patterns, trends, and relationships between variables related to the impact of AI on digital media. The key steps in the EDA process included:

#### 1. Data Overview and Cleaning
   
-Inspected the dataset for missing values, inconsistencies, and data types.

-Handled missing or anomalous data entries to ensure quality and reliability.

-Converted percentage values to a consistent numeric format where needed.

#### 2. Univariate Analysis
   
Analyzed the distribution of individual variables such as:

-AI Adoption Rate (%)

-AI-Generated Content Volume (TBs per year)

-Revenue Increase Due to AI (%)

Job Loss Due to AI (%)

Used histograms, box plots, and summary statistics (mean, median, std) to understand data spread and identify outliers.

#### 3. Bivariate and Multivariate Analysis
   
Explored relationships between key variables using scatter plots and correlation matrices:

For example, checking the correlation between AI Adoption Rate and Revenue Increase Due to AI.

Investigated whether higher AI-generated content volumes were associated with increased consumer trust or market share.

#### 4. Categorical Data Insights
   
Analyzed the distribution of Regulation Status and Top AI Tools Used across different countries and industries.

Examined how these categorical features may influence or be influenced by numerical metrics like adoption rates or collaboration percentages.

#### 5. Country and Industry Comparisons
   
Created grouped visualizations to compare:

AI impact across different countries and industries.

Market trends and trust levels by region.


### Data Analysis
```use ai_impact;
select * from global_ai_content_impact_dataset
where Country = 'France' and `Year` = 2025;
```
### Results/Findings
   
1. Countries with strong regulatory frameworks tend to show higher consumer trust.

2. Industries with a high human-AI collaboration rate often experienced lower job loss percentages.

3. Tools like GPT and DALL·E appeared frequently among top AI tools used in content generation.

### Recommendations

#### 1. Encourage Balanced AI Adoption

While AI adoption boosts efficiency and revenue, it’s important to balance it with human oversight. Organizations should integrate AI in ways that enhance human creativity rather than replace it entirely.

#### 2. Invest in Human-AI Collaboration

Industries with high collaboration rates experienced fewer job losses. Investing in training programs that upskill employees to work alongside AI tools can reduce fear of job displacement and promote innovation.

#### 3. Develop Clear Regulatory Frameworks

Countries with strong AI regulation showed higher consumer trust. Governments should prioritize transparent and ethical AI policies, ensuring consumer protection while supporting technological growth.

#### 4. Monitor and Address Job Displacement

To address potential job losses due to AI, companies and policymakers should work together to provide reskilling opportunities, particularly in industries most affected by automation.

#### 5. Promote Transparency in AI Content

Given the rise in AI-generated media, platforms should implement clear labeling systems to distinguish between human-made and AI-generated content, improving accountability and user awareness.

#### 6. Boost Consumer Trust Through Ethical AI Practices

Organizations should embrace ethical AI principles—like data privacy, fairness, and transparency—to build trust among users and avoid public backlash.

#### 7. Leverage AI for Personalization While Respecting Privacy

AI-driven personalization should be used to enhance user experience, but with clear data consent mechanisms in place to respect user privacy and comply with data protection laws (e.g., GDPR).

#### 8. Track AI Tool Usage and Evolve with Trends

Companies should stay updated with emerging AI tools and trends in media, ensuring they adopt the most effective and responsible technologies that align with their business goals.

### Limitations

#### 1. Limited Data Availability
The dataset may not cover all countries or industries comprehensively, which could limit the generalizability of the findings.

Some countries may have outdated or incomplete data, especially in areas like AI regulation or content volume.

#### 2. Rapidly Changing Technology Landscape
The field of AI is evolving rapidly. New tools and trends may have emerged since the data was collected, making some insights time-sensitive or less relevant over time.

### References
1. kaggle datasets  [Click Here](https://www.kaggle.com/datasets)
2. Her Data Project [Youtube Channel](https://www.youtube.com/@herdataproject)








