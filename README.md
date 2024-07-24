# Sustainable Model Assignment Optimization - MGSC 662 Project

## Introduction
In the fast-paced world of fashion, aligning the right models with the right jobs is a complex challenge. This project, completed as part of the Decision Analytics course (MGSC 662) at McGill University, elevates this process by not only streamlining job assignments but also embedding a deep commitment to sustainability. The focus was to account for a variety of constraints and objectives pertinent to a modeling agency's operations.

## Project Contributors
- Avi Malhotra
- Meriem Mehri
- Moiz Zahid Shaikh
- Rohan Kumar
- Yvan Kammelu

## Files Included
- **MGSC662_DecisionAnalytics_Presentation.pdf**: A detailed presentation of the project, covering the problem context, methodology, results, and recommendations.
- **MGSC662-FinalReport_Group1.pdf**: The final report documenting the project, including the executive summary, problem description, mathematical formulation, numerical implementation, strategic recommendations, and future scope.
- **ModelAgency_FINAL.ipynb**: Jupyter Notebook containing the implementation of the linear optimization model using Python and Gurobi.
- **final_results.xlsx**: The results generated from the optimization model.
- **Job and Model data.xlsx**: The dataset used for the optimization model, including information on models, jobs, and locations.

## The Challenge
Fashion model agencies often face the dual challenge of efficiently assigning models to various jobs while considering the environmental impact of their travel. The traditional approach has largely overlooked the sustainability aspect, leading to increased carbon footprints. This project aims to create a solution that addresses both efficiency and environmental responsibility.

## The Solution: A Dual-Focused Optimization Model
The core of this project is an optimization model that achieves two key goals:

- **Efficient Model Assignment**: Ensuring models are assigned to jobs that match the client’s requirements, maximizing job success and satisfaction.
- **Sustainability Consideration**: Integrating a sensitivity analysis of CO2 emissions associated with model travel, promoting environmentally conscious decisions.

## How It Works
- **Optimization Algorithm**: The model uses Gurobi to evaluate various factors such as model availability, job requirements, and travel distances.
- **CO2 Emissions Analysis**: A unique aspect is the inclusion of a CO2 emission calculator. This tool estimates the environmental impact based on travel distance and mode of transportation.
- **Sensitivity Analysis for Sustainability**: Agencies are provided with a sensitivity analysis regarding CO2 emissions. This allows them to decide how much weight to give to sustainability in their assignment decisions, aligning with their environmental goals.

## Sensitivity Analysis
The project includes a sensitivity analysis to observe how job assignments change with varying weights on CO2 emissions, allowing agencies to balance profitability with environmental impact. This is crucial for making informed, sustainable decisions in the modeling industry.

## Results and Discussion
- **Model Performance**: The model adeptly assigns models to jobs, maintaining a balance between agency profit and model compensation while adhering to CO2 emission restrictions.
- **CO2 Emissions Sensitivity Analysis**: The analysis indicated a significant change in model-job assignments with varying CO2 emission weights, showing a preference for local assignments to reduce emissions at higher weights.

## Strategic Recommendations
1. **Talent Pool Enhancement**: Address gaps in the agency's model roster by expanding recruitment efforts, providing additional training, and revising job acceptance criteria.
2. **Cost Efficiency**: Optimize resource allocation by strategically selecting model assignments that minimize financial outlay.
3. **Sustainability**: Promote environmentally responsible choices by selecting local models and collaborating with eco-conscious clients.

## Future Scope
1. **Fair Opportunity Allocation**: Implement tier-based job distribution to ensure equitable career advancement for all models.
2. **Emergency Backup Options**: Develop a pool of standby models to handle last-minute changes and ensure continuity in operations.

## Acknowledgments
This project was part of a course at McGill University. Thanks to the course instructors and fellow students for their support and guidance.

## Conclusion
The Sustainable Model Assignment Optimization project showcases how operational efficiency can be harmoniously blended with environmental stewardship. It’s a step towards more responsible and sustainable practices in the fashion industry, demonstrating the pivotal role of data analytics in achieving this balance.
