# 4. Preparation of Assignments and Exams
*This phase involves designing AI-assisted assessment strategies that align with learning goals while promoting authenticity, clarity, and integrity*

This phase involves designing AI-assisted assessment strategies that align with learning goals while promoting authenticity, clarity, and integrity. Key tasks include designing formative and summative assessments, creating authentic tasks like case studies or AI-assisted projects, developing clear rubrics to define performance expectations, and ensuring accessibility and academic integrity. AI can assist in differentiating assessment types, designing real-world tasks, and drafting rubrics. 

## Learning Objectives
After completing this module, participants will be able to:

- Design formative and summative assessments aligned with course learning outcomes.
- Create authentic, real‑world AI‑enhanced tasks such as quizzes, exams, case studies, and projects.
- Develop clear, consistent, AI‑assisted rubrics.
- Ensure accessibility and academic integrity in all AI‑supported assessments.

## 4.1 Design Formative and Summative Assessments Aligned with Learning Outcomes

### Purpose  
Use GenAI to understand and design assessments that track learning progress (formative) and evaluate mastery (summative), ensuring alignment with the course learning outcomes.

### Prompt — Instructional
```
Explain the difference between formative and summative assessments in the context of learning.
Provide technical or scientific references from the literature about these two types of assessments.
Then generate an example of each for a course on [Course Title/Topic].
```

### Course-Tailored Prompt — Instructional
```
Based on the learning outcomes presented below, suggest one formative and one summative assessment aligned with them.
[Learning Outcomes]
```

> **Note 1:** You can use the same or a similar prompt for each learning outcome.
> **Note 2:** If you know the type of assignment you want to create, you can prompt the model to create exactly that type of assignment.

## 4.2 Create Authentic Tasks (Quizzes, Exams, Case Studies, Projects)

### Purpose  
Generate real‑world, meaningful tasks that reflect authentic professional or academic scenarios enhanced with GenAI.

### Prompt Template — Role‑Based + Instructional
```
You are an instructional designer creating a real-world, authentic task for a course on [Course Title/Topic].
Create an assignment where the students must use generative AI whilst still acquiring the required knowledge,
skills and critical thinking associated with the topic.
Include a rationale for how AI enhances learning.
```

### Additional Prompt Variant — Zero‑Shot
```
Give three examples of authentic, real-world assignments for a course on [Course Title/Topic].
Include one quiz with 5 questions, one AI-supported case study, and one project-based task.
Provide correct answers.
```

> **Note:** Some foundational models and general-purpose LLMs contain features and tools that allow you to create specific types of assignments, such as *Artifacts -> Quiz* in Claude.ai. There are also AI tools designed exclusively to support teaching and learning activities, such as Eduaide (eduaide.ai) and Khanmigo (khanmigo.ai), that can support the development of assignments.

## 4.3 Create Rubrics with GenAI

### Purpose  
Develop clear, consistent rubrics using structured prompting, ensuring transparency and alignment with learning outcomes.

### Prompt Template — Instructional
```
Create a rubric for the following assignment:
[Paste the assignment here or upload it in the prompt]

Use the following criteria:
[Criterion 1, Criterion 2, ..., Criterion N]

Create a 1–5 Likert scale and ensure the total points equal 10.
```

### Additional Prompt Variant — Role-Based + Chain-of-Thought
```
You are an assessment specialist on [Course Name/Topic]. Create a detailed analytic rubric for the assignment below.
Include 4 criteria, each with 4 performance levels, and point values that total 100 points.
[Paste assignment description here]

Explain your reasoning step-by-step as you generate a rubric for this assignment.
Identify the core skills being assessed, justify each criterion, and then produce the final rubric table.
```

### Rubric Audit Prompt 
```
Audit the rubric below for clarity, comprehensiveness, redundancy, and misalignment with the assignment.
Suggest revisions and then provide an improved version.
[Paste rubric]
```

### Rubric Difficulty Leveling
```
Generate three rubric versions for the same assignment:
- Introductory level  
- Intermediate level  
- Advanced level  

Each version should reflect increasing expectations in cognitive demand.
```

### Rubric for Multimodal Deliverables
```
Create a rubric for an assignment where students submit two deliverables:
1) A written report  
2) An AI-generated multimodal asset (e.g., image, podcast script, or diagram)

The rubric should evaluate both independently and their integration.
```

### Rubric for Partial AI Use Transparency
```
Create a rubric that includes a specific criterion assessing transparency in how students used AI during the assignment (e.g., listing prompts, describing AI contributions).
```

## 4.4 Ensure Accessibility and Academic Integrity

**Task:**
Use GenAI to review or generate assessments with accessibility in mind and minimize integrity issues.

*Role-Based Prompt for accessibility*
```
You are an educator designing an inclusive assignment using generative AI. What principles should guide your design to ensure accessibility (e.g., for neurodiverse or multilingual learners)? Include examples of modifications.
```

*Instructional Prompt for integrity*
```
Suggest five ways to promote academic integrity in AI-assisted assignments. For each, include a strategy to monitor or mitigate misuse of generative tools.
```

**Sample illustration:** Checklist diagram with “Accessibility” and “Integrity” columns side-by-side.
