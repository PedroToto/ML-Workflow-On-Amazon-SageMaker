# ML Workflow On Amazon SageMaker

In this project we created an event-drivent ML workflow that can be incorporated into the Scones Unlimited production architecture. We used the SageMaker Estimator API to deploy the SageMaker Model and Endpoint, and we used AWS Lambda and Step Functions to orchestrate your ML workflow. Using SageMaker Model Monitor, we instrumented and observed the Endpoint, and at the end of the project we built a visualization to help stakeholders understand the performance of the Endpoint over time. 
