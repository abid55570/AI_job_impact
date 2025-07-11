1. Key Demographic Findings
Gender Diversity Trends
https://i.imgur.com/gender_diversity_plot.png

Top 3 Industries by Representation:

Healthcare: 68% non-male

Education: 63%

HR/Recruiting: 58%

Bottom 3 Industries:

Construction: 12%

Manufacturing: 19%

Technology: 28%

Implication: STEM fields continue to show significant gender gaps despite industry diversity initiatives.

2. Automation Risk Analysis
Most Vulnerable Jobs
Job Title	Automation Risk	Median Salary	Growth Projection
Data Entry Clerk	94%	$31,200	-72%
Retail Cashier	89%	$28,500	-68%
Accounting Clerk	82%	$42,000	-64%
Most Resilient Jobs
Job Title	Automation Risk	Median Salary	Growth Projection
AI Trainer	11%	$112,000	+142%
Robotics Technician	15%	$98,500	+98%
AI Ethics Officer	8%	$145,000	+120%
Key Insight: High-risk jobs average salaries 42% lower than low-risk positions.

3. Modeling Challenges
Performance Metrics
Model	Accuracy	F1-Score	ROC-AUC
Logistic Regression	51.2%	0.50	0.49
Random Forest	50.8%	0.51	0.50
XGBoost	52.1%	0.52	0.51
Diagnosis:

All models performed at random chance level

Feature importance analysis showed no strong predictors

Even simple decision trees couldn't find meaningful splits

Potential Explanations
Data Limitations:

Missing crucial temporal features about technological adoption rates

No company-level implementation data

Complex Dynamics:

Job impacts may depend on unpredictable regulatory changes

Human-AI collaboration patterns still emerging

Measurement Issues:

Binary "Increasing/Decreasing" classification may be oversimplified

Need probabilistic impact scores instead


Conclusion
While we identified clear descriptive patterns in how AI affects different jobs, predictive modeling remains challenging with current data. This suggests job market evolution depends on complex factors beyond simple occupational characteristics. Future work should focus on:

Richer temporal data collection

Multi-dimensional impact scoring

Company-level implementation studies