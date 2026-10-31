# EX.NO.4 – Generate and Evaluate Prompts Using Different Prompt Patterns

### DATE: 31.10.2026

### REGISTER NUMBER: 212224040160

## Aim

To create prompts using seven different prompt patterns—Zero-shot Prompting, Few-shot Prompting, Chain-of-Thought Prompting, Persona Pattern, Reverse Prompting, Graph Prompting, and Active Prompting—and compare their performance across different AI tools using an evaluation rubric.

## Explanation

Selected Unit 5 Use Case: Smart Manufacturing Automation Using IoT and Embedded Systems

The manufacturing industry uses automation to improve production efficiency, reduce manual monitoring, and minimize machinery downtime. IoT sensors and embedded controllers help monitor machines, collect real-time data, and control manufacturing operations.

This experiment applies seven prompt patterns to the smart manufacturing use case. The prompts are designed to generate ideas, explain system operations, compare technologies, and suggest improvements.

Main objectives of the use case:

1. Improve production efficiency by 30%.

2. Minimize machinery downtime through predictive maintenance.

3. Enable real-time monitoring and remote control.

4. Reduce energy consumption through process optimization.

## Procedure

### 1. Define the Scenario and Use Case

Scenario: Smart Manufacturing Automation

A manufacturing company wants to automate its production process using IoT devices and embedded controllers. The system should monitor machine performance, detect possible failures, control equipment remotely, and optimize energy usage.

Target Audience: Manufacturing companies in automotive, electronics, and food-processing industries.

Main requirements:

- Real-time machine monitoring.

- Automated equipment control.

- Predictive maintenance.

- Energy consumption monitoring.

- Improved production efficiency.

### 2. Identify Prompt Patterns for Each Design Aspect

### 2.1 Zero-Shot Prompting

Definition:

Zero-shot prompting instructs an AI model to perform a task without providing any examples. The model generates an answer based on its existing knowledge and the given instruction.

Example Prompts:

1. "Explain how IoT devices improve automation in manufacturing industries."

2. "List five benefits of predictive maintenance in smart manufacturing."

3. "Describe how embedded controllers are used to monitor industrial machines."

Generated Answer:

IoT devices improve manufacturing automation by connecting machines, sensors, and controllers through a communication network. These devices collect real-time information such as temperature, vibration, pressure, and energy consumption.

The collected information helps manufacturers monitor equipment performance and identify unusual operating conditions. Predictive maintenance systems analyze sensor data to identify possible machine failures before they occur.

Embedded controllers process sensor information and perform control operations based on predefined instructions. For example, a temperature sensor can detect excessive heat in a machine and send information to a controller, which can activate a cooling system or trigger an alert.

Benefits of IoT-based manufacturing automation:

- Improves production efficiency.

- Reduces unexpected machine failures.

- Supports remote monitoring.

- Helps optimize energy consumption.

- Reduces the need for continuous manual inspection.

### 2.2 Few-Shot Prompting

Definition:

Few-shot prompting provides a small number of examples to the AI model before asking it to perform a task. These examples help the model understand the expected response format and style.

Example Prompt:

"Identify manufacturing problems and suggest IoT-based solutions using the following format.

Example 1:

Problem: Excessive machine temperature.

Solution: Install temperature sensors to monitor heat levels and send alerts when the temperature exceeds the safe limit.

Example 2:

Problem: High energy consumption.

Solution: Use smart energy meters to monitor electricity usage and identify unnecessary energy consumption.

Now provide five more manufacturing problems and their IoT-based solutions using the same format."

Generated Answer:

| Manufacturing Problem        | IoT-Based Solution                                                  |
| ---------------------------- | ------------------------------------------------------------------- |
| Unexpected machine breakdown | Use vibration sensors to identify abnormal machine conditions.      |
| Production delays            | Use real-time monitoring systems to identify bottlenecks.           |
| Poor product quality         | Install quality-monitoring sensors to detect production variations. |
| Excessive water usage        | Use smart flow sensors to monitor water consumption.                |
| Manual equipment monitoring  | Use IoT-enabled controllers for automated monitoring and alerts.    |

Advantages:

- Produces structured and consistent answers.

- Helps the AI follow a specific response pattern.

- Useful for generating repeated solutions.

- Reduces ambiguity in output formatting.

### 2.3 Chain-of-Thought Prompting

Definition:

Chain-of-thought prompting encourages an AI model to approach a complex problem through intermediate steps before providing a final answer. It is useful for tasks involving analysis, planning, and problem-solving.

Example Prompts:

1. "Analyze the causes of unexpected machine breakdowns and explain a step-by-step approach to reducing downtime using IoT-based predictive maintenance. Provide the key steps and final recommendations."

2. "Explain how a smart manufacturing system can monitor energy consumption and identify opportunities for energy savings."

3. "Develop a logical implementation plan for automating a manufacturing unit using sensors, embedded controllers, and IoT connectivity."

Generated Answer:

Step-by-Step Approach to Reduce Machine Downtime:

Step 1: Install IoT Sensors

Install vibration, temperature, and pressure sensors on manufacturing equipment to collect operating information.

Step 2: Collect Machine Data

Connect the sensors to embedded controllers that collect and process machine information continuously.

Step 3: Analyze Performance

Analyze the collected data to identify unusual patterns, such as increasing vibration or excessive temperature.

Step 4: Predict Possible Failures

Use predictive maintenance algorithms to identify conditions that may indicate future equipment failure.

Step 5: Generate Alerts

Send notifications to maintenance personnel when the system identifies abnormal machine conditions.

Step 6: Perform Preventive Maintenance

Schedule inspection or maintenance before the machine experiences a major breakdown.

Expected Benefits:

- Reduced unexpected downtime.

- Improved equipment reliability.

- Better maintenance planning.

- Increased production efficiency.

### 2.4 Persona Pattern

Definition:

Persona prompting assigns a specific professional role or identity to the AI model. This helps generate answers from the perspective of a particular expert and adapts the language and recommendations to the target audience.

Example Prompts:

1. "Act as an industrial automation engineer and explain how IoT sensors can improve manufacturing efficiency."

2. "As a maintenance engineer, recommend methods to reduce unexpected machine breakdowns using predictive maintenance."

3. "Act as an energy management consultant and suggest ways to reduce electricity consumption in a smart manufacturing plant."

Generated Answer:

Role: Industrial Automation Engineer

As an industrial automation engineer, I recommend integrating IoT sensors, embedded controllers, and centralized monitoring software to improve manufacturing operations.

The proposed smart manufacturing system should include the following components:

1. IoT Sensors: Monitor machine temperature, vibration, pressure, and energy consumption.

2. Embedded Controllers: Process sensor readings and control machines based on predefined conditions.

3. Communication Network: Transfer machine information to a centralized monitoring platform.

4. Monitoring Dashboard: Display machine status, production performance, and energy usage.

5. Predictive Maintenance System: Analyze operating data and identify possible equipment failures.

By integrating these components, manufacturing companies can improve machine utilization, reduce manual monitoring, and make better operational decisions.

### 2.5 Reverse Prompting

Definition:

Reverse prompting is a technique in which the AI model is asked to identify, reconstruct, or generate a suitable prompt based on a given desired output, task, or problem statement. The generated prompt can then be used to obtain a more detailed response.

Example Prompts:

1. "I want a detailed report explaining an IoT-based predictive maintenance system for a manufacturing company. Generate an effective prompt that would produce this report."

2. "Given the requirement of reducing machine downtime through real-time monitoring, create a detailed prompt that asks an AI model to suggest a suitable automation system."

3. "Generate a prompt for designing an energy-efficient smart manufacturing system using IoT sensors and embedded controllers."

Generated Answer:

Generated Prompt:

"Act as an industrial IoT system designer. Develop a smart manufacturing automation solution for a company that wants to reduce machine downtime and energy consumption. Include the following sections:

1. Introduction to smart manufacturing.

2. Required IoT sensors and embedded controllers.

3. Real-time monitoring architecture.

4. Predictive maintenance process.

5. Remote equipment control.

6. Energy optimization methods.

7. Expected benefits and implementation challenges.

Present the solution in a structured report using simple technical language."

Explanation:

The generated prompt can be reused in an AI tool to obtain a complete smart manufacturing report. Reverse prompting helps users create better instructions when they know the desired output but are unsure how to formulate the prompt.

### 2.6 Graph Prompting

Definition:

Graph prompting instructs an AI model to represent information using a graph or flowchart. It helps explain relationships between components, processes, and operations in a system.

Example Prompts:

1. "Create a flowchart showing how IoT sensors, embedded controllers, and monitoring systems work together in smart manufacturing."

2. "Represent the predictive maintenance process in a graph, starting from sensor data collection and ending with maintenance action."

3. "Create a system architecture diagram showing the relationship between machines, sensors, controllers, cloud monitoring, and maintenance personnel."

Generated Answer:

Smart Manufacturing System Architecture:

<img width="972" height="535" alt="image" src="https://github.com/user-attachments/assets/ba663454-2584-4f42-b215-f134021000c3" />


The smart manufacturing system follows this sequence:

1. Manufacturing Machines: Machines perform production activities.

2. IoT Sensors: Sensors collect temperature, vibration, pressure, and energy data.

3. Embedded Controllers: Controllers process sensor information and manage machine operations.

4. Communication Gateway: Transfers information to the monitoring platform.

5. Monitoring Dashboard: Displays machine status and production information.

6. Predictive Maintenance: Analyzes data to identify possible equipment failures.

7. Maintenance Team: Receives alerts and performs necessary maintenance.

Flow of the System:

<img width="388" height="798" alt="image" src="https://github.com/user-attachments/assets/9f58bbba-6eea-4307-bfb0-fc21f8bcd408" />

<img width="417" height="691" alt="image" src="https://github.com/user-attachments/assets/ec7b6ca7-8c2b-4242-8373-62f51740bb7d" />



### 2.7 Active Prompting

Definition:

Active prompting is a technique in which the AI model asks questions to collect missing information or clarify requirements before generating its final response. It helps produce more relevant and context-specific answers.

Example Prompts:

1. "Help me design an IoT-based smart manufacturing system. First, ask me questions about the factory size, number of machines, available sensors, budget, and monitoring requirements. Then suggest a suitable solution."

2. "Before recommending a predictive maintenance system, ask me about the types of machines, their operating conditions, and the available maintenance data."

3. "Help me reduce energy consumption in a manufacturing plant. Ask questions about current energy usage, production schedules, and major energy-consuming equipment before suggesting improvements."

Generated Answer:

AI Model – Initial Questions:

Before designing the smart manufacturing system, the AI model asks:

1. What type of manufacturing industry is involved: automotive, electronics, or food processing?

2. How many machines need to be monitored?

3. What parameters should be monitored, such as temperature, vibration, or pressure?

4. Is remote monitoring required?

5. Is there an existing IoT network or communication infrastructure?

6. What is the available budget for implementing the system?

Example Responses:

- Industry: Automotive manufacturing.

- Number of machines: 20.

- Monitoring requirements: Temperature, vibration, and energy consumption.

- Remote monitoring: Required.

- Existing infrastructure: Basic industrial network.

- Budget: Limited.

Suggested Solution:

Based on these responses, the AI model can recommend installing temperature and vibration sensors on the machines, connecting them to embedded controllers, and using a centralized dashboard for real-time monitoring. A predictive maintenance module can analyze the collected data and notify maintenance personnel when abnormal conditions are detected.

Advantages:

- Collects missing information before generating an answer.

- Produces customized recommendations.

- Reduces unclear assumptions.

- Improves the relevance of the generated output.

## 3. Comparison of Prompt Patterns

| Prompt Pattern    | Main Purpose                           | Best Application       |
| ----------------- | -------------------------------------- | ---------------------- |
| Zero-shot         | Generates answers without examples     | Basic explanations     |
| Few-shot          | Uses examples to guide output          | Structured reports     |
| Chain of Thought  | Encourages stepwise problem-solving    | Complex analysis       |
| Persona           | Assigns a professional role            | Expert recommendations |
| Reverse Prompting | Generates prompts from desired outputs | Prompt creation        |
| Graph Prompting   | Represents relationships visually      | System architecture    |
| Active Prompting  | Collects information through questions | Customized solutions   |

## 4. Evaluation Using Rubrics

The generated responses can be evaluated using a rubric with five criteria. Each criterion is scored from 1 to 5.

Evaluation criteria:

| Criterion    | Description                                      |
| ------------ | ------------------------------------------------ |
| Relevance    | How closely the response matches the given task. |
| Accuracy     | Whether the information is technically correct.  |
| Clarity      | Whether the response is easy to understand.      |
| Completeness | Whether all important requirements are covered.  |
| Structure    | Whether the response is properly organized.      |

Rubric Scale:

| Score | Performance       |
| ----- | ----------------- |
| 5     | Excellent         |
| 4     | Very Good         |
| 3     | Good              |
| 2     | Needs Improvement |
| 1     | Poor              |

Sample Evaluation Table:

The following is an illustrative evaluation to demonstrate how the rubric can be used. It is not a record of actual testing results.

| Prompt Pattern    | Relevance | Accuracy | Clarity | Completeness | Structure |
| ----------------- | --------- | -------- | ------- | ------------ | --------- |
| Zero-shot         | 4         | 4        | 5       | 3            | 4         |
| Few-shot          | 5         | 4        | 4       | 4            | 5         |
| Chain of Thought  | 5         | 4        | 4       | 5            | 4         |
| Persona           | 5         | 4        | 5       | 4            | 4         |
| Reverse Prompting | 4         | 4        | 4       | 4            | 4         |
| Graph Prompting   | 4         | 4        | 5       | 4            | 5         |
| Active Prompting  | 5         | 4        | 5       | 5            | 4         |

## 5. Cross-Platform Comparison

The prompts can be tested using the following AI tools:

<img width="937" height="455" alt="image" src="https://github.com/user-attachments/assets/9ededb1c-5995-4b81-97ef-f61dcdd95db7" />

For a fair comparison, submit the same prompt and scenario to each tool, use equivalent instructions, and evaluate their responses using the same rubric. Actual scores should be recorded after testing each platform.

## Prompt Used to Get the Answer

`` 

Act as an expert in Prompt Engineering and prepare a detailed 

Selected Unit 5 use case: Smart Manufacturing Automation Using IoT and Embedded Systems.

Scenario: A manufacturing company wants to improve production efficiency by 30%, minimize machine downtime using predictive maintenance, enable real-time monitoring and remote control, and reduce energy consumption.

Follow the given procedure:

1. Define the scenario and use case.
2. Identify and explain all seven prompt patterns.
3. Provide at least three example prompts for each pattern.
4. Generate detailed answers for each pattern using the selected smart manufacturing scenario.
5. Include a system architecture explanation and a flowchart for Graph Prompting.
6. Compare all seven prompting patterns in a table.
7. Evaluate the prompts using a rubric based on relevance, accuracy, clarity, completeness, and structure.
8. Explain how to compare ChatGPT, Gemini, Claude, and Microsoft Copilot fairly.

Maintain the experiment format with Aim, Explanation, Procedure, Conclusion, Result, and Prompt Used to Get the Answer. Use simple, detailed, student-friendly language suitable for a college practical record. Clearly label illustrative evaluation scores and do not claim that actual cross-platform testing has occurred unless results are provided.

```

## Conclusion

The seven prompt patterns demonstrate different ways of guiding AI models to generate explanations, structured information, technical solutions, and visual representations. Evaluating their outputs with a common rubric helps identify which prompting technique is most suitable for a particular task.

## Result

The seven prompt patterns were successfully demonstrated using the smart manufacturing automation use case, and their outputs were compared using an illustrative evaluation rubric.
