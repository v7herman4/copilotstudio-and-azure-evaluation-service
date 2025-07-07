## Table of Contents
- [Overview](../README.md#overview)
- [Requirements for Installation](requirements-for-installation.md)
- [Requirements for End Users](requirements-for-end-users.md)
- [Installation Guide](installation.md)
- [How to Use The Solution](howtousereporting.md)
- [FAQs](faq.md)
<br><br>

- [Color Coding](##colorcoding)
- 
## How To Use The Solution
The evaluation service provides analysis of conversations from an aggregate perspective down to the individual prompts and responses. 

### View Evaluations in Aggregate (Many Conversations)
The page "Overview" shows all evaluators averaged over a date range and for all agents.<br><br>

![Figure 0‑1](images/1-Report-Dashboard.png)

### Quality Trends
The page "Trends - Quality" displays the evaluators for AI quality over a date range and for all agents. Filter as needed or sort the table to view data by column.<br><br>

![Figure 0‑2](images/2-Report-QualityEvals.png)


#### Quality Trends Conversation Analysis
Select **one** conversation on the timeline or in the table to analyze the specific conversation. Note the Conversation Analysis visual in the bottom right.<br><br>

![Figure 0‑3](images/3-Report-QualityEval-1.png)

The Conversation Analysis visual shows the average of the evaluators for that entire conversation. The bottom sections shows the individual messages between a user and the agent. Each prompt/response is considered a run and gets its own evaluation. The users's prompt is in green and the agent's prompt is in grey. The *Run Index* is for internal use only.<br><br>

![Figure 0‑4](images/4-Report-QualityEval-Analysis.png)

You can view the individual evaluations for each specific run by clicking on the "AI Quality" or "Safety Harm" buttons for that run. Additionally, you can view the reason each evaluation was scored as shown by hovering over each evaluator. For example, below the mouse is hovering over the *Relevance* evaluator. <br><br>

![Figure 0‑5](images/5-Report-QualityEval-Analysis-Reason.png)

### Safety and Risk Trends
Similar to the "Trends - Quality" page, the page "Trends - Safety and Risk" displays the evaluators for Safety and Risk over a date range and for all agents. Filter as needed or sort the table to view data by column.<br><br>

![Figure 0‑6](images/6-Report-SafetyRiskEval-Analysis.png)

#### Safety and Risk Conversation Analysis
The conversation analysis is similar to the quality trends conversation analysis except for safety and risk evaluators.

### Color Coding
AI Quality conditional coloring

•	Green: 4.01 – 5.00
•	Yellow: 2.00 – 4.00
•	Red: 0.00 – 1.99

Safety Risk conditional coloring
•	Green: 0.00 – 1.99
•	Yellow: 2.00 – 5.00
•	Red: 6.01 – 7.00
