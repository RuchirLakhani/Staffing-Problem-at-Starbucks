# Staffing-Problem-at-Starbucks
This repository contains the source code and documentation for the Staffing Optimization project, which aims to solve the staffing problem for Starbucks on our campus using linear programming techniques.

**Description**
The Staffing Optimization project is developed to help Starbucks efficiently allocate staff members to different shifts throughout the day. By utilizing linear programming, the project aims to optimize the staffing schedule to meet customer demand while minimizing labor costs and ensuring employee availability.

**Problem Statement**
The problem is defined as follows:
Starbucks operates on our campus and needs to determine the optimal number of employees to assign to each shift, considering factors such as historical customer demand, employee availability, and labor costs. The goal is to create a staffing schedule that minimizes costs while ensuring an adequate number of employees are present during peak hours to provide quality service.

**Approach**
To solve the staffing problem, we adopt a linear programming approach using the following steps:

Gather historical data: Collect data on customer footfall, sales, and employee availability for different time periods (e.g., hourly or half-hourly) from Starbucks' records.

Formulate the objective function: Define the objective function, considering factors such as labor costs and customer satisfaction. The objective is to minimize the total cost while meeting service level requirements.

Define decision variables: Determine the decision variables, such as the number of employees assigned to each shift.

Establish constraints: Set constraints based on employee availability, minimum and maximum staffing requirements, and customer demand during different time periods.

Implement linear programming model: Use a linear programming solver library (e.g., PuLP, Gurobi, or CPLEX) to implement the mathematical model based on the objective function and constraints.

Optimize staffing schedule: Solve the linear programming model to obtain the optimal staffing schedule that satisfies all constraints and minimizes costs.

Evaluate and refine: Assess the performance of the optimized staffing schedule by monitoring customer satisfaction, labor costs, and employee availability. Refine the model as needed based on feedback and data analysis.

**Documentation**
The documentation for the Staffing Optimization project includes the following artifacts:

Problem Statement: A detailed description of the staffing problem faced by Starbucks on our campus, including the key factors and requirements to consider.

Linear Programming Formulation: A mathematical formulation of the linear programming model, including the objective function and constraints used to optimize the staffing schedule.

Data Analysis and Results: An analysis of the input data, optimization results, and performance evaluation of the staffing schedule.

**Credits**
The Staffing Optimization project is developed by **Ruchir Lakhani, Carson Goodman, Rounak Amre and Jacob Warchola**.

