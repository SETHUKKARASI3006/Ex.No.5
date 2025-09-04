

# EXP 5: COMPARATIVE ANALYSIS OF DIFFERENT TYPES OF PROMPTING PATTERNS AND EXPLAIN WITH VARIOUS TEST SCENARIOS

# Aim: 
To test and compare how different pattern models respond to various prompts (broad or unstructured) versus basic prompts (clearer and more refined) across multiple scenarios.  Analyze the quality, accuracy, and depth of the generated responses 

### AI Tools Required: 
ChatGPT

# Explanation: 
Define the Two Prompt Types:

Write a basic Prompt: Clear, detailed, and structured prompts that give specific instructions or context to guide the model.
Based on that pattern type refined the prompt and submit that with AI tool.
Get the ouput and write the report.

Prepare Multiple Test Scenarios:
Select various scenarios such as:
Generating a creative story.
Answering a factual question.
Summarizing an article or concept.
Providing advice or recommendations.
Or Any other test scenario
For each scenario, create both a naïve and a basic prompt. Ensure each pair of prompts targets the same task but with different levels of structure.
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

# PROMPT:
Study of prompt templating techniques for automated maintenance report generation.

#### Prompt type: Instructional Pattern

# OUTPUT:

<img width="2892" height="2844" alt="img" src="https://github.com/user-attachments/assets/cbc18a86-440b-489f-b97a-84647156c202" />

### Study of Prompt Templating Techniques for Automated Maintenance Report Generation
### 1. Introduction

Automated maintenance report generation involves using AI models (especially Large Language Models, LLMs) to convert structured or semi-structured machine, sensor, or inspection data into clear, human-readable reports. Prompt templating provides a standardized way to instruct the AI, ensuring consistency, accuracy, and reduced errors.

### 2. What is Prompt Templating?

Prompt templating refers to designing reusable, parameterized text instructions (templates) that guide LLMs to produce specific outputs. Instead of crafting prompts from scratch, templates define:

- Structure (report sections, headings, formatting)

- Context (equipment type, inspection details, environment)

- Variables (fault codes, sensor readings, technician notes)

### 3. Key Techniques in Prompt Templating
#### 3.1 Slot-Filling Templates

- Predefined structure with placeholders (e.g., {machine_name}, {issue_detected}, {repair_action}).

- Ensures consistency across reports.

- Example:
“Generate a maintenance summary for {machine_name}. Fault detected: {issue_detected}. Action taken: {repair_action}. Next scheduled check: {next_date}.”

#### 3.2 Chain-of-Thought Decomposition

- Breaking down complex reporting into smaller steps (diagnosis → action → recommendation).

- Template instructs the model to sequentially process inputs before finalizing.

#### 3.3 Instruction + Context Hybrid

- Combines explicit instructions (e.g., "Summarize sensor data in plain language") with contextual examples.

- Increases clarity when reports involve technical jargon.

#### 3.4 Style-Control Templates

- Embeds style constraints: concise, formal, or user-friendly.

- Example: “Write a maintenance report in a professional and concise format suitable for engineers.”

#### 3.5 Dynamic Prompting with Metadata

- Uses structured data (JSON, database records) as input and injects them into natural language templates.

- Ensures factual grounding and reduces hallucination.

<img width="2772" height="1836" alt="Study of Prompt Templating Techniques for Automated Maintenance Report Generation - visual selection" src="https://github.com/user-attachments/assets/48470078-4155-4e89-9501-6e7275bd3b8e" />

### 4. Benefits of Prompt Templating
- Consistency → Uniform structure across reports.

- Scalability → Easy replication for multiple machines/facilities.

- Clarity → Reduces ambiguity in language.

- Automation → Enables integration with CMMS (Computerized Maintenance Management Systems).

### 5. Challenges

- Data Quality Dependence → Poor sensor/inspection data reduces report accuracy.

- Domain Adaptation → Templates must be tailored to industry (aviation, manufacturing, utilities).

- Over-constraint vs Flexibility → Overly rigid templates may ignore nuances; too loose may reduce consistency.

### 6. Applications

- Predictive maintenance systems (sensor-driven).

- Field technician reporting apps.

- Automated compliance documentation.

- Integration with IoT and digital twins.

### 7. Future Directions

- Few-shot example-based templating → Embedding real maintenance reports as style guides.

- Adaptive templates → Dynamic adjustment based on severity level of faults.

- Multi-modal inputs → Integrating images, vibration charts, or audio notes.

- Human-in-the-loop refinement → Allowing technicians to approve AI-generated drafts.

### 8. Conclusion

Prompt templating offers a reliable way to standardize and automate maintenance report generation. By combining structured placeholders, contextual instructions, and adaptive styles, organizations can streamline reporting, improve operational efficiency, and maintain compliance—while reducing manual effort.


# RESULT: 
The prompt for the above said problem executed successfully
