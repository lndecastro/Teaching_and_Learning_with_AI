# 6. AI‑Powered Student Support  
*Centering the Personalized Assistant (PA) as the Core Student Support Tool*

Generative AI enables instructors to expand availability, personalize guidance, and deliver timely academic support. In this module, the **Course Personalized Assistant (PA)**, built progressively from Module 1 onward, becomes the central hub of all student support workflows. The PA supplements office hours, answers questions, provides study strategies, generates resources, supports peer collaboration, offers early alerts, and interacts multimodally. Other AI tools remain valuable, but the PA becomes the *student-facing anchor* that integrates them into a coherent support ecosystem.
 
## Learning Objectives
After completing this module, participants will be able to:
- Supplement office hours with AI-generated FAQs and persistent support channels.
- Offer personalized assignment guidance and study strategies using AI.
- Monitor student success using structured analytics and AI‑assisted early alerts.
- Generate AI‑curated study resources, tutoring suggestions, and multimodal aids.
- Facilitate peer collaboration and social learning through AI‑supported workflows.
- Explore AI tutors, including real‑time camera- and screen‑aware AI agents.

## 6.1 The Course Personalized Assistant as the Core Support Hub

### Purpose
Place the **Course PA** at the center of support:  
A consistent, persistent tutor accessible 24/7, deeply grounded in course files, policies, learning outcomes, assignments, and weekly materials.

### What the PA Can Do (Student-Facing)
- Provide multiple level explanations  
- Clarify assignments and expectations (without completing graded work)  
- Offer study plans, study strategies, revision pathways  
- Produce summaries, flashcards, diagrams, examples  
- Suggest peer collaboration strategies  
- Provide responsible-AI reminders  
- Offer nudges, pacing suggestions, and self-assessment tools  

### What the PA Should Not Do
- Provide answers or solutions to graded work  
- Misrepresent institutional or syllabus policies  
- Override instructor judgment  
- Replace office hours or interpersonal communication  

### Updates to the PA
Where necessary, update your existing PA by adding:
- New core responsibilities for student support
- New behaviors and capabilities for study guidance, early alerts, and collaboration
- Tightened safety & boundary rules for academic integrity
- New conversation starters
- Uploading all course materials created since Module 1

> **Note:** Test if your PA refuses to complete graded work by prompting it to do so. If it does not refuse, then you should revise the *core role* or the *safety & boundary* section within the instructions. 

## 6.2 Extend Office Hours and Provide Timely Responses

### Purpose
Extend the instructor’s presence beyond scheduled hours by using AI to generate consistent, accurate responses to common student questions. Although multiple tools can generate FAQs or office-hour support, the PA is still the official student-facing channel.

### Alternative Tool 1: General-Purpose LLMs (e.g., ChatGPT, Copilot, Gemini, Grok, etc.)
Upload your course materials and prompt the LLM to generate an FAQ or any other support resources desired.

### Prompt Template - Instructional
```
Read the attached PDF file(s) and generate a structured FAQ section that summarizes the key aspects of the material. 
Ensure each FAQ includes a clear question and a concise, informative answer, grouped into thematic categories.
```

> **Note:** If you are working within your AI workspace, then the course material will already be uploaded in the model and you only need to prompt it to generate the new support material. Also, in Module 5 you may have created the materials, and these will serve as student support.

### Alternative Tool 2: NotebookLM
Create a *Notebook* with your course material and use button **Flashcards** or other tools to generate the desired support resources. 

## 6.3 Assignment Guidance & Study Strategies

### Purpose  
Help students approach assignments with clarity, confidence, and strategy.  
While generative AI tools can assist with assignment interpretation and study planning, **the Course Personalized Assistant (PA)** remains the *primary student-facing tool* for guiding academic tasks, providing structured breakdowns, study strategies, and self‑assessment prompts without completing graded work.

### Primary Tool: The Course Personalized Assistant

Your PA is responsible for:

- Clarifying assignment descriptions and expectations (without producing solutions)  
- Breaking down complex tasks into manageable steps  
- Suggesting prerequisite knowledge or skills to review  
- Providing study strategies tailored to the task type  
- Offering revision pathways, self-check questions, and pacing guidance  
- Helping students identify misconceptions or knowledge gaps  
- Encouraging responsible AI use while working on assignments  

Because the PA is grounded in the syllabus, assignments, rubrics, and course policies, its guidance is *contextualized*, *consistent*, and *aligned with your teaching intent*.

### Sample PA Prompt for the Students
Students may use this prompt directly with the PA:
```
Help me understand how to approach [Assignment Name]. 
Explain the task in your own words, break it into clear steps, 
suggest study strategies or prerequisite concepts I should review, 
and provide 3–5 self-check questions to confirm my understanding.
Do not give me any part of the solution.
```

### What the PA will generate:
- A simplified explanation of the assignment  
- A structured approach (step-by-step)  
- A recommended study plan (daily/weekly)  
- Suggested tools or resources (if allowed)  
- A list of self-check or reflection questions  
- A reminder about responsible AI use  
- Warnings to avoid using AI to generate prohibited content  

### When Should Students Use the PA for Assignments?
Encourage students to contact the PA when they:
- are unsure how to start an assignment  
- need examples of *approach*, not *answers*  
- want a study plan  
- need help interpreting rubrics  
- want help identifying what they already know vs. what they must review  
- need guidance on preparing for group work or collaborative responsibilities  

### Alternative Tool 1: General-Purpose LLMs
Instructors may use additional AI tools to produce resources to students.
Use general LLMs to create:
- reading summaries  
- sample study plans  
- diagrams or concept maps  
- lists of common misconceptions  

### Sample Instructor Prompt (Workspace or private LLM):
```
Based on the attached assignment and rubric, create a list of common misconceptions students may have and suggest study strategies for each.
```

### Alternative Tool 2: NotebookLM  
NotebookLM can generate grounded resources that can be later distributed:
- document-grounded summaries  
- flashcards on assignment-relevant concepts  
- video and/or audio explainers  
- step‑by‑step walkthroughs of prerequisite topics
- mindmaps

> **Note:** Use NotebookLM to produce structured learning aids *based solely on your uploaded readings*, then make them available for student support.

### Optional Add-On: PA‑Assisted Study Planning  
Your PA can generate personalized study plans based on the course schedule.

### Sample Prompt for the Students
```
Create a 7-day study plan to help me prepare for [Assignment Name], 
considering the course pacing and major concepts we’ve covered. 
Suggest checkpoints and ways to evaluate my progress.
```

## 6.4 Monitor Student Success

### Purpose
Use engagement data or AI-generated insights to detect patterns that indicate a need for support.

### Prompt Template - Design a Student Success Table*
```
I want to design a table to collect student information in a course. The goal is to use the data to calculate a "Student Success Score". 

1. Propose a matrix with at least 5 student variables (e.g., attendance, assignment completion, grades, engagement, self-assessments).
2. For each variable, define:
   - Data type (numeric, categorical)
   - Measurement method
   - Weight or influence on success

3. Propose a formula to compute a success score from these variables (e.g., weighted average or custom equation).
4. Explain how this score can be used to monitor or support students throughout the course.
5. Save this matrix as a table in XLSX, CSV, or Google Spreadsheet format.
```

### Additional Prompt Variant - Using a Pre-Specified Score Matrix
Provide the following details to create a matrix or table for collecting student information and calculating a success score.
```
Create a table for calculating the students' success score.
The table should include relevant student data points, and a success score will be calculated using a weighted equation.
Use a clear, structured table format, and ensure the success score equation is included with explanations of each component.

Student Information to Collect:
[List or upload the data points you want to collect for each student. Examples include:
- Student Name: 
- Attendance Rate: 
- Assignment Completion Rate: 
- Quiz Average Score: 
- Discussion Participation: 
- Time Spent on LMS: 
Add or modify data points as needed.]

Table Structure:
[Design a table to collect the data. Example structure:
| Student Name | Attendance Rate (%) | Assignment Completion Rate (%) | Quiz Average Score (%) | Discussion Participation (Posts) | Time Spent on LMS (Hours/Week) | Success Score |
|--------------|---------------------|-------------------------------|-----------------------|---------------------------------|-------------------------------|---------------|
| [Name 1]     | [Percentage]        | [Percentage]                  | [Percentage]          | [Number]                        | [Hours]                       | [TBD]         |
| [Name 2]     | [Percentage]        | [Percentage]                  | [Percentage]          | [Number]                        | [Hours]                       | [TBD]         |
Ensure the table includes a column for the Success Score, which will be calculated.]

## Success Score Equation
[Define the equation to calculate the Success Score. Here is an example equation with weights assigned to each data point:
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

Additional Notes:
- Ensure all percentages are on a 0-100 scale for consistency.
- The Success Score should range from 0 to 100, with higher scores indicating greater likelihood of success.
- Include a brief explanation of how to interpret the score (e.g., “Scores above 80 indicate strong performance, 60-80 suggest moderate success with room for improvement, below 60 indicate a need for intervention”).

Output: 
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

**Output file and graphs**
- Save the generated table in an XLSX or CSV spreadsheet file.
- Generate a bar graph for each student with the values in each criteria normalized in the 0-100 interval. The success score bar should have different colors for each of the three interpretations.
```



## 6.4 Provide AI-Curated Resources (e.g., Study Guides, Tutoring Suggestions)

**Task:**
Curate and generate personalized learning resources using GenAI.

*Instructional Prompt*
```
Create a custom study guide using generative AI for learners struggling with [the ethical use of AI in education]. Include summaries, definitions, discussion questions, and one quiz.
```

**Sample illustration** Sample study guide layout with AI-generated components.

## 6.5 Encourage Peer Collaboration and Support Networks

**Task:**
Design AI-assisted prompts and activities that build peer learning environments.

**Use Case 1: Initiating Collaboration & Group Formation**
Help students find common ground, form groups, and define initial collaborative tasks.

*Role-Based Prompt*
```
Act as a matchmaker. Given the following student responses about their biggest challenges in [Course Topic] and their areas of interest, suggest 3-5 potential peer learning groups. For each group, briefly explain the common thread that connects them and suggest an initial discussion topic.
Student 1: [Input: 'Struggles with [Course Topic], interested in [Topic].']
Student 2: [Input: 'Finds [Course Topic] confusing, good at explaining [Topic].']
Student 3: [Input: 'Wants to apply [Course Topic] to real-world cases, enjoys problem-solving.']
```

**Use Case 2: Collaborative Icebreaker & Goal Setting**
Help students to feel comfortable with one another, the instructor, and the learning environment.

*Instructional Prompt*
```
Generate an icebreaker activity for a new peer learning group in [Course Name]. The activity should encourage members to share a personal learning goal for the upcoming module and one strength they bring to the group. After the icebreaker, provide 3 guiding questions for them to collaboratively define their group's learning objectives for the week.
```
**Use Case 3: Scenario-Based Team Formation**
Help students to build teams under a specific context (scenario).

*Instructional Prompt*
```
You are designing a collaborative project for [Course Name] focusing on [Specific Topic]. Create 3-4 diverse roles within a team (e.g., 'Researcher,' 'Synthesizer,' 'Presenter,' 'Critique Editor'). For each role, describe the primary responsibilities and the type of skills that would be best suited for it. Then, generate a short 'team charter' template that groups can fill out to define their internal roles and communication norms.
```

**Use Case 4: Fostering Support Networks & Reflection**
Encourage students to offer and seek help, reflect on the benefits of collaboration, and build a sense of community.

*Role-Based Prompt*
```
Imagine you are a student struggling with [Specific Skill/Concept]. Write 3 different ways to ask for help from a peer or a peer learning group, varying the level of detail or formality. Ensure the prompts are empathetic and clear about the challenge.
```

**Sample illustration** Collaboration map showing peers, prompts, and AI facilitation layers.

## 6.6 Introduce AI Tutors

**Task:**
Explore the use of AI assistants in dynamic, real-world contexts using **Google AI Studio** with the **Stream function** enabled. The focus is on teaching AI to interact with **your environment** through a **background camera** or **screen capture**. This powerful setup brings AI into your personal or digital workspace, enhancing observation, navigation, and learning experience.

### Tools & Setup

- **Platform**: Google AI Studio
- **Key Feature**: Stream
- **Capabilities Used**:
  - Background Camera
  - Screen Capture
  - Real-Time AI Interaction

> Ensure the **Stream** function is enabled and permissions for camera and screen sharing are granted.

**Use Case 1:** Interacting with the Physical Environment

*Scenario*: The participant activates their **background camera** and points it toward their environment (e.g., desk, classroom, lab, objects).

*Instructional + Role-Based Interaction (**Voice Prompt**)*
```
Observe my environment and describe what you see. Focus on identifying objects and their likely purpose or function. Then suggest one or two ideas for organizing or improving this workspace for productivity.
```

*Alternative **Voice Prompt** (Educational Context):*
```
Act as a tutor. I am pointing my camera at an object. Explain what you are seeing.
[SELECT THE OBJECT OR CONTEXT]
```

**What students learn**:
- How to direct the AI’s visual attention
- How to formulate prompts to extract meaningful insights from real-time observations

**Use Case 2:** Navigating the Digital Workspace

*Scenario*: The participant shares their **screen** (e.g., browser, application, workspace, spreadsheet), and the AI assistant provides support.

*Chain-of-Thought + Instructional **Voice Prompt***
```
Watch my screen as I navigate my email inbox. Help me:
1. Identify unread messages and group them by priority
2. Draft responses to the top three messages
3. Create a task list based on action items in the emails
```

*Instructional **Voice Prompt***
```
I am going to open a website I am unfamiliar with. As I explore, please explain what each section seems to do, and guide me to locate the help center and pricing information.
```



