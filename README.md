# EXP-2-PROMPT-ENGINEERING-

## Aim: 
Comparative Analysis of different types of Prompting patterns and explain with Various Test Scenarios

Experiment:
Test and compare how different pattern models respond to various prompts (broad or unstructured) versus basic prompts (clearer and more refined) across multiple scenarios. 
Analyze the quality, accuracy, and depth of the generated responses.


## Algorithm:

01
Classify the task type
Before writing a single word, determine whether the task is reasoning-heavy, format-sensitive, creativity-first, or factual. This single classification drives every downstream decision.

02
Assign a role (if domain matters)
A role declaration calibrates vocabulary, depth, and perspective in one sentence. Only skip this if the task is truly domain-agnostic.

03
State the task with full context
Write the core ask. Include: the object (what), the goal (why), the audience (who), and any critical constraints (what not to do). One sentence per element.

04
Inject reasoning scaffold (CoT)
For any non-trivial task, mandate step-by-step thinking. This single line raises accuracy by 25–40 points on reasoning tasks. Only skip for pure format or simple factual tasks.

05
Specify output format & constraints
Tell the model exactly what the answer should look like. Format + length constraints are the highest-ROI elements in a prompt. Never leave format implicit.
Machine-readable output
→
Return JSON: {field1, field2, field3}
Document / report
→
Use headings: [H1, H2, H3]. Max N words.
Recommendation
→
Give exactly 3 bullet points. One sentence each.
Explanation
→
Use one analogy + one concrete example. Max N words.

06
Validate & iterate
Score the output against 4 dimensions: Quality, Accuracy, Depth, Consistency. If any score falls below 75, identify which prompt element failed and refine that element specifically.

## Output

[Prompting_Patterns_Report.docx](https://github.com/user-attachments/files/27296763/Prompting_Patterns_Report.docx)


## Result

Therefore The Comparative Analysis of different types of Prompting patterns and explain with Various Test Scenarios is created successfully.
