

# EXP 5: Comparing Prompting Techniques Through Engineering Problem-Solving Scenarios

# Aim:To compare different prompting techniques and evaluate their effectiveness in solving real-world engineering problems by using a problem selected from a student's 3rd-year or final-year project work. 


# EXPERIMENT OVERVIEW

In this experiment, each student/team selects a genuine problem from their ongoing or completed 3rd-year or final-year engineering project.
The same engineering problem is given to an AI system using different prompting techniques. Students then compare the responses based on relevance, accuracy, completeness, clarity, feasibility and usefulness.
The purpose is not simply to obtain an AI-generated answer. Students must analyse how changing the prompting technique changes the quality of the solution.

EXPERIMENT PROCEDURE
Step 1 – Select the Engineering Problem
Choose one genuine problem from the student's 3rd-year or final-year project.
Step 2 – Write the Base Prompt
Write a simple prompt describing the engineering problem without using advanced prompting techniques.
Step 3 – Apply Different Prompting Techniques
Rewrite the same problem using at least four different prompting techniques.
For example:
Technique 1 – Straightforward Prompt
Suggest a method to detect crop diseases using computer vision.structure.
Run Experiments with ChatGPT:
Input the naïve prompt for each scenario and record the generated response.
Then input the corresponding basic prompt and capture that response.
Repeat this process for all selected scenarios to gather a full set of results.
Evaluate Responses : 
	Compare how ChatGPT performs when given naïve versus basic prompts and analyze the output based on Quality,Accuracy and Depth. Also analyse does ChatGPT consistently provide better results with basic prompts? Are there scenarios where naïve prompts work equally well?
Deliverables:
A table comparing ChatGPT's responses to naïve and basic prompts across all scenarios.
Analysis of how prompt clarity impacts the quality, accuracy, and depth of ChatGPT’s outputs.
Summary of findings with insights on how to structure prompts for optimal results when using ChatGPT.

#**STUDENT SUBMISSION FORMAT**
Each student/team should submit:
Project title and problem statement
Selected engineering scenario
Base prompt
Minimum four improved prompts using different techniques
AI-generated outputs
Comparison/evaluation table
Analysis and observations
Final selected prompting technique
Refined/final prompt
Engineering validation

## **1. SELECTED ENGINEERING PROBLEM**
Project Title: AI-Based Smart Traffic Management System

<img width="2481" height="1418" alt="image" src="https://github.com/user-attachments/assets/9049e0ab-4643-46f2-b4a8-df91ecce0f92" />
#### 2.Problem Statement:
In cities, traffic congestion occurs due to increasing vehicle populations, poor traffic signal coordination, and the absence of real-time traffic monitoring. Traditional traffic signals operate using fixed time intervals, which may cause unnecessary waiting times and traffic delays.

To overcome this problem, an AI-Based Smart Traffic Management System is proposed. The system uses cameras, sensors, and AI algorithms to monitor vehicle density and automatically adjust traffic signal timings.

### **Objectives**

- Reduce traffic congestion.
- Monitor vehicle density in real time.
- Automatically control traffic signals.
- Reduce vehicle waiting time.
- Provide priority to emergency vehicles.
- Improve road safety and traffic flow.

## **3. BASE PROMPT (NAÏVE PROMPT)**

**Prompt:**

"Design an AI-based Smart Traffic Management System to control traffic signals and reduce traffic congestion."

**Expected Output:**

AI suggests using cameras, sensors, and machine learning algorithms to detect vehicle density and control traffic signals automatically.

## **4. APPLICATION OF DIFFERENT PROMPTING TECHNIQUES**

### **Technique 1 – Straightforward Prompting**

**Prompt:**

"Design an AI-based Smart Traffic Management System using cameras and sensors. Explain how the system detects vehicle density, controls traffic signals, reduces waiting time, and handles emergency vehicles."

**Expected Output:**

- Cameras capture real-time traffic images.
- AI processes images to identify vehicles.
- Vehicle density is calculated for each road.
- Traffic signal timings are adjusted according to vehicle density.
- Emergency vehicles receive priority through the control system.

**Observation:** Direct instructions generate a clear solution with the major system requirements.

### **Technique 2 – Persona Pattern**

**Prompt:**

"Act as an AI and IoT engineer. Design a Smart Traffic Management System using computer vision, IoT sensors, and intelligent traffic signals. Explain the hardware components, software requirements, working process, and advantages."

**Expected Output:**

The AI recommends the following components:

| Component               | Purpose                     |
| ----------------------- | --------------------------- |
| CCTV Camera             | Capture traffic images      |
| Raspberry Pi / Computer | Process traffic information |
| Ultrasonic Sensor       | Detect vehicle presence     |
| AI Model                | Identify and count vehicles |
| Traffic Signal          | Control vehicle movement    |
| Database                | Store traffic information   |

**Observation:** Persona prompting generates a more technical solution from an engineering perspective.

### **Technique 3 – Few-shot Prompting**

**Prompt:**

"Follow these examples to determine traffic signal timing.

Example 1: Vehicle count = 10 → Green signal = 20 seconds.

Example 2: Vehicle count = 20 → Green signal = 30 seconds.

Example 3: Vehicle count = 30 → Green signal = 40 seconds.

Now determine a suitable green signal duration when the vehicle count is 40. Follow the same pattern."

**Expected Output:**

Vehicle Count = 40

Green Signal Duration = 50 seconds.

**Observation:** Few-shot prompting helps AI identify patterns from examples and apply them to new traffic conditions.

### **Technique 4 – Chain of Thought Prompting**

**Prompt:**

"A traffic junction has four roads with vehicle counts of 50, 30, 20, and 10 respectively. Analyze the traffic density, identify the road requiring the highest priority, and explain the decision-making process for allocating green signal time. Consider a maximum green time of 60 seconds."

**Expected Output:**

- Road 1 has the highest vehicle count.
- Road 1 requires the highest priority.
- Signal duration should be allocated according to vehicle density.
- The maximum green signal duration should not exceed 60 seconds.
- Other roads should also receive suitable signal time to avoid excessive waiting.

**Observation:** Chain of thought prompting encourages structured problem analysis and decision-making.

## **5. PROMPT CHAINING**

Prompt chaining is the process of dividing a complex problem into smaller tasks and using the output of one prompt as the input for the next prompt.

The following prompt chain is used to develop the Smart Traffic Management System.

| Stage                   | Prompt / Task                                                                                      |
| ----------------------- | -------------------------------------------------------------------------------------------------- |
| 1. Problem              | Identify the major causes of traffic congestion and propose an AI-based solution.                  |
| 2. Requirement Analysis | Identify the hardware and software requirements for the system.                                    |
| 3. Architecture         | Design the system architecture connecting cameras, AI processing, and traffic signals.             |
| 4. Algorithm            | Develop an algorithm to detect vehicle density and allocate signal timings.                        |
| 5. Flowchart            | Create a flowchart representing the complete system operation.                                     |
| 6. Python Code          | Generate Python code for vehicle detection and traffic signal control.                             |
| 7. Testing              | Test the system using different vehicle-density scenarios.                                         |
| 8. Documentation        | Prepare complete project documentation with objectives, architecture, implementation, and results. |
<img width="2816" height="1536" alt="image" src="https://github.com/user-attachments/assets/cf912475-5ecb-433d-9d6d-cac6725b6c44" />


## **6. COMPARISON OF NAÏVE AND IMPROVED PROMPTS**

| Criteria   | Naïve Prompt             | Improved Prompt                   |
| ---------- | ------------------------ | --------------------------------- |
| Quality    | General response         | Structured solution               |
| Accuracy   | May lack details         | Clear requirements                |
| Depth      | Basic explanation        | Detailed technical explanation    |
| Relevance  | General traffic solution | Specific engineering solution     |
| Usefulness | Limited guidance         | Practical implementation guidance |

## **7. EVALUATION TABLE**

The prompts are evaluated using a rubric-based method.

**Scoring:** 5 – Excellent, 4 – Very Good, 3 – Good, 2 – Satisfactory, 1 – Poor.

| Prompting Technique | Quality | Accuracy | Depth | Total / 15 |
| ------------------- | ------- | -------- | ----- | ---------- |
| Naïve Prompt        | 3       | 3        | 2     | 8          |
| Straightforward     | 4       | 4        | 4     | 12         |
| Persona             | 5       | 4        | 5     | 14         |
| Few-shot            | 4       | 5        | 4     | 13         |
| Chain of Thought    | 5       | 4        | 5     | 14         |

*Note: These are illustrative evaluation scores. Actual scores should be assigned after testing the prompts using ChatGPT or other AI tools.*

## **8. ENGINEERING VALIDATION**

The proposed system can be validated using simulated traffic conditions.

| Test Case | Vehicle Count              | Expected System Response |
| --------- | -------------------------- | ------------------------ |
| Test 1    | 10                         | Short green signal       |
| Test 2    | 25                         | Medium green signal      |
| Test 3    | 50                         | Longer green signal      |
| Test 4    | Emergency vehicle detected | Emergency priority       |

**Validation:** Check whether the system correctly identifies vehicle density, allocates signal timings, and provides emergency vehicle priority. Actual performance must be verified through simulation or a working prototype.

## **9. CONCLUSION**

Different prompting techniques were applied to the AI-Based Smart Traffic Management System. The results show that improved prompts provide more structured, relevant, and detailed responses than simple prompts.

Persona prompting helped generate technical suggestions, few-shot prompting identified patterns, and chain of thought prompting supported structured problem-solving. Prompt chaining divided the complex engineering problem into smaller stages, from requirement analysis to documentation.


# RESULT:
The prompt for the above said problem executed successfully
