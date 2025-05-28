
# 5. Student Support  
_Promoting academic success and well-being_

This phase focuses on using generative AI to enhance the support structures available to learners, fostering inclusivity, personalization, and early intervention.

## 5.1 Provide Office Hours and Timely Responses to Inquiries

**Task:** 
In addition to your office hours, use generative AI to supplement your availability and provide consistent, supportive responses to common student queries.

### Tool 1: General LLMs (e.g. ChatGPT, Copilot, Gemini, Grok, etc.)
Upload your course material and prompt the LLMs to generate the FAQ.

*Instructional Prompt*
```
Read the attached PDF file(s) and generate a structured FAQ section that summarizes the key aspects of the material. 
Ensure each FAQ includes a clear question and a concise, informative answer, and group the FAQs into thematic categories.
```

### Tool 2: Perplexity
Create a *Space* with your course material and prompt the LLMs to generate the FAQ. Use the same *instructional prompt* presented above.

### Tool 3: NotebookLM
Create a *Notebook* with your course material and use button **FAQ** to generate the FAQ. 

**Sample illustration** Inbox of AI-generated response examples, labeled by type.

## 5.2 Offer Guidance on Assignments and Study Strategies

**Task**
Use AI to offer personalized academic coaching or scaffolded support on deliverables.

*Zero-Shot Prompt*
```
Provide five examples of how generative AI can help faculty learners in a course about AI pedagogy better understand and complete their assignments. Include study strategies and task breakdowns.
```

**Sample illustration** Flowchart: Assignment → AI Feedback → Strategy Suggestion → Revision

## 5.3 Monitor Student Success

**Task:**
Use engagement data or AI-generated insights to detect patterns that indicate a need for support.

*Chain-of-Thought Prompt 1: Tasking the LLM with the Table Design*
```
I want to design a table to collect student information in a course. The goal is to use the data to calculate a "Student Success Score." 

1. Propose a matrix with at least 5 student variables (e.g., attendance, assignment completion, quiz scores, engagement, self-assessments).
2. For each variable, define:
   - Data type (numeric, categorical)
   - Measurement method
   - Weight or influence on success

3. Propose a formula to compute a success score from these variables (e.g., weighted average or custom equation).
4. Explain how this score can be used to monitor or support students throughout the course.
```

*Chain-of-Thought Prompt 1: Guiding the LLM with Your Desired Table*
```
# Prompt to Design a Student Success Score Matrix

Please provide the following details to create a matrix or table for collecting student information and calculating a success score. The matrix should include relevant student data points, and a success score will be calculated using a weighted equation. Use a clear, structured table format, and ensure the success score equation is included with explanations of each component.

## Student Information to Collect
[List the data points you want to collect for each student. Examples include:
- Student Name: [Text input, e.g., John Doe]
- Attendance Rate: [Percentage, e.g., 95%]
- Assignment Completion Rate: [Percentage, e.g., 90%]
- Quiz Average Score: [Percentage, e.g., 85%]
- Discussion Participation: [Number of posts, e.g., 5]
- Time Spent on LMS: [Hours per week, e.g., 10 hours]
Add or modify data points as needed.]

## Table Structure
[Design a table to collect the data. Example structure:
| Student Name | Attendance Rate (%) | Assignment Completion Rate (%) | Quiz Average Score (%) | Discussion Participation (Posts) | Time Spent on LMS (Hours/Week) | Success Score |
|--------------|---------------------|-------------------------------|-----------------------|---------------------------------|-------------------------------|---------------|
| [Name 1]     | [Percentage]        | [Percentage]                  | [Percentage]          | [Number]                        | [Hours]                       | [TBD]         |
| [Name 2]     | [Percentage]        | [Percentage]                  | [Percentage]          | [Number]                        | [Hours]                       | [TBD]         |
Ensure the table includes a column for the Success Score, which will be calculated.]

## Success Score Equation
[Define the equation to calculate the Success Score. Here’s an example equation with weights assigned to each data point:
Success Score = (0.2 * Attendance Rate) + (0.3 * Assignment Completion Rate) + (0.3 * Quiz Average Score) + (0.1 * Normalized Discussion Participation) + (0.1 * Normalized Time Spent on LMS)

- **Weights Explanation**:
  - Attendance Rate (20%): Reflects engagement and consistency.
  - Assignment Completion Rate (30%): Measures task completion, a key indicator of effort.
  - Quiz Average Score (30%): Assesses academic performance.
  - Discussion Participation (10%): Gauges interaction (normalized to a 0-100 scale, e.g., max posts = 10, so 5 posts = 50%).
  - Time Spent on LMS (10%): Indicates resource usage (normalized to a 0-100 scale, e.g., max expected hours = 20, so 10 hours = 50%).

- **Normalization**:
  - Normalize Discussion Participation: (Student Posts / Max Expected Posts) * 100
  - Normalize Time Spent on LMS: (Student Hours / Max Expected Hours) * 100

Modify weights or add/remove components as needed.]

## Additional Notes
- Ensure all percentages are on a 0-100 scale for consistency.
- The Success Score should range from 0 to 100, with higher scores indicating greater likelihood of success.
- Include a brief explanation of how to interpret the score (e.g., “Scores above 80 indicate strong performance, 60-80 suggest moderate success with room for improvement, below 60 indicate a need for intervention”).

## Output Format
[Generate the final table and equation in a clear format, e.g.:
**Student Success Score Matrix**

| Student Name | Attendance Rate (%) | Assignment Completion Rate (%) | Quiz Average Score (%) | Discussion Participation (Posts) | Time Spent on LMS (Hours/Week) | Success Score |
|--------------|---------------------|-------------------------------|-----------------------|---------------------------------|-------------------------------|---------------|
| John Doe     | 95                  | 90                            | 85                    | 5                               | 10                            | [Calculated]  |
| Jane Smith   | 80                  | 70                            | 65                    | 3                               | 8                             | [Calculated]  |

**Success Score Equation**  
Success Score = (0.2 * Attendance Rate) + (0.3 * Assignment Completion Rate) + (0.3 * Quiz Average Score) + (0.1 * Normalized Discussion Participation) + (0.1 * Normalized Time Spent on LMS)

**Interpretation**  
- Above 80: Strong performance  
- 60-80: Moderate success, room for improvement  
- Below 60: Needs intervention  
]
```

**Sample illustration** Early alert system diagram with AI dashboard and action paths.

---

## 🛡 4. Create a Climate of Psychological Safety and Inclusiveness

### 📌 Task:
Use AI to generate language and design interactions that foster trust, inclusivity, and a safe learning environment.

### 🧠 Prompt (🔹Role-Based Prompt):
```
You are an inclusive educator designing onboarding materials for a course on AI in teaching. Use generative AI to write a welcoming message and set expectations that promote a climate of respect and curiosity.
```

### 🖼 Illustration:
AI-generated inclusive welcome messages annotated with best practices.

---

## 📚 5. Provide AI-Curated Resources (e.g., Study Guides, Tutoring Suggestions)

### 📌 Task:
Curate and generate personalized learning resources using GenAI.

### 🧠 Prompt (🔹Instructional Prompt):
```
Create a custom study guide using generative AI for learners struggling with the ethical use of AI in education. Include summaries, definitions, discussion questions, and one quiz.
```

### 🖼 Illustration:
Sample study guide layout with AI-generated components.

---

## 🤗 6. Encourage Peer Collaboration and Support Networks

### 📌 Task:
Design AI-assisted prompts and activities that build peer learning environments.

### 🧠 Prompt (🔹Few-Shot Prompt):
```
Examples of peer-support strategies:
1. Weekly study groups
2. Peer feedback rounds

Now generate an AI-supported version of these strategies that helps form and manage peer groups using generative tools.
```

### 🖼 Illustration:
Collaboration map showing peers, prompts, and AI facilitation layers.

---
