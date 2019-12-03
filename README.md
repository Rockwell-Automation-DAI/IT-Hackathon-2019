# Pick and Place Nozzle Performance and Prediction
### Use Case #2
### Data Analytics and Insights Group
### Key Contacts: Francisco Maturana/ Marzell Brown

## Overview

Create a prediction algorithm for monitoring anomalies in an electronic assembly manufacturing process.

This problem involves an end-to-end IoT solution (non real time) with four development stages: ​

- Use case understanding, data acquisition and data preparation​
- Performance prediction algorithm to anomaly detection​
- Machine Learning based forecasting of anomaly​
- Trigger notifications & Performance visualization

Recommended Options (Hardware/Software) for Use Case 2 – Any below​
- Laptop (Edge) and/or Microsoft Azure (Cloud) 
- Development suite: FT Edge; Thingworx Analytics; Custom​
- Cloud: Blob storage; Azure Functions; Azure ML Studio; Databricks; SendGrid (notification); PowerBI​
- Programming: JavaScript, C# or Python & Visual Studio Code


## [Problem Statement Background](Background.md)


<!-- ## Hackathon Prompt

Evaluate and Produce a Maintainable and supportable solution for detecting anomalies in the Pick and Place nozzles.

Solutions can contain, but are not limited to:
- Storm tracker diagrams (Live PowerBI dashboard)
- Evaluate vector path of nozzle and tabulate a nozzle score over time
- Trigger users when nozzle exceeds threshold of performance
- Parameters to change to adjust sensitivity -->


## [Challenge 1 - Data acquisition and preparation](/Challenges/Challenge1.md)

## [Challenge 2 - Performance predicition algorithm to anomaly detection](/Challenges/Challenge2.md)

## [Challenge 3 - Machine Learning based forecasting of anomaly](/Challenges/Challenge3.md)

## [Challenge 4 - Notifications and Performance Visualization](/Challenges/Challenge4.md)


## [Sample Architecture](Sample_Architecture.md)



## Success Criteria
We are looking for a solution that will innovate the anomaly-detection system
- Find alternative ways to organize the data
- Simpler, an easy-to-understand anomaly reporting and notification

We would like to see a scalable and repeatable solution
- Move away from custom build solutions

We need a solution that will help users to quickly implement the next solution without requiring high-level expertise, something that can be automated
- E.g. FT Edge pipelines

## Scoring
If you select your own tool set, that will be an acceptable solution approach; however for scoring, you are asked to port the solution to one or a combination of the suggested tools

Full mark if you automate the solution using one or a combination of the suggested tools, like FTEdge and AzureML 

If you implement a custom solution only because the lack of tool expertise, you will get xyz%

But if you show how the prototype can be ported in the future to the FTInnovationSuite, your score is zyx%




## Recommended Technology Help Docs
Architecture/ Platforms can be provided if participants choose these technologies.

Please request access to VMs on a group basis and connection creditials will be provided.

#### Advanced Predictive Analytics Modeling
VM has Visual Studio Code with Python and JS Libraries
- [FactoryTalk Analytics Edge](FTEdge.md)

#### Machine Learning Modeling

- [AzureML](/Tech/AzureML/AzureML.md)
- [Thingworx Analytics](/Tech/Thingworx/Thingworx.md)

#### Solution Reporting

- [PowerBI](/Tech/PowerBI/PowerBI.md)
- [Thingworx Mashups](/Tech/Thingworx/Thingworx.md)

#### Notifications

- [Twilio Sendgrid]("https://www.twilio.com/sendgrid")
- [Thingworx Notifications]("")

#### Data Source (Required)
- Azure Blob container
- Json Strings

#### Development Tools
- Visual Studio Code (IDE for FT Edge)
- Python Libraries
