# Day 2 - Six Pattern Drills

## Pattern 1 - PERSONA

### Prompt
You are a senior placement coach at Aditya University. You have prepared 200 B.Tech CSE students for TCS, Infosys, and Cognizant placement interviews. A 3rd-year CSE student with 7.5 CGPA asks you about Big-O notation. Explain it the way you would in a 1-on-1 prep session — concrete, conversational, exam-relevant.

### Best Output
Big-O notation describes how an algorithm's running time grows as input size increases. For example, linear search takes O(n) because it may check every element. Interviewers ask Big-O to evaluate your understanding of algorithm efficiency and scalability.

### Self Score
5/5

### Peer Score
9/10

---

## Pattern 2 - FEW SHOT

### Prompt
Q: What is recursion?
A: A function calling itself with a smaller problem. Like Russian dolls.

Q: What is a stack?
A: LIFO data structure. Like a stack of plates.

Q: What is Big-O notation?
A:

### Best Output
Big-O notation measures how an algorithm's execution time grows with input size. Think of it as a speed rating for algorithms. Example: linear search is O(n), binary search is O(log n).

### Self Score
4/5

### Peer Score
8/10

---

## Pattern 3 - CHAIN OF THOUGHT

### Prompt
Explain Big-O notation to a placement interview candidate.

Step 1: Define Big-O in one sentence.
Step 2: Give one concrete example with code.
Step 3: Explain why interviewers ask about it.
Step 4: Summarise in three sentences.

### Best Output
Definition: Big-O notation measures algorithm growth as input increases.

Example:
for i in arr:
    print(i)

This loop is O(n).

Interviewers ask Big-O to test algorithmic thinking and optimization skills.

Summary: Big-O helps compare algorithm efficiency. It predicts performance at scale. Understanding it improves coding interview success.

### Self Score
5/5

### Peer Score
10/10

---

## Pattern 4 - STRUCTURED OUTPUT

### Prompt
Explain Big-O notation for a placement interview.

Return ONLY valid JSON:

{
  "definition":"",
  "intuition":"",
  "code_example":"",
  "common_pitfall":"",
  "interview_test_question":""
}

### Best Output

{
  "definition":"Measures algorithm growth rate.",
  "intuition":"Speed rating for algorithms.",
  "code_example":"for i in arr: print(i)",
  "common_pitfall":"Confusing worst-case and average-case.",
  "interview_test_question":"What is the complexity of binary search?"
}

### Self Score
5/5

### Peer Score
9/10

---

## Pattern 5 - SYSTEM PROMPT

### System Prompt
You are a senior placement coach for B.Tech CSE students at an Indian engineering college. Explain technical concepts in 50-80 words with one example.

### User Prompt
Explain Big-O notation.

### Best Output
Big-O notation describes how execution time grows as input size increases. For example, traversing an array of n elements takes O(n). Placement interviewers use Big-O questions to assess your understanding of algorithm efficiency.

### Self Score
4/5

### Peer Score
8/10

---

## Pattern 6 - PROMPT CHAINING

### Extract Prompt
List the 5 most important sub-concepts of Big-O notation.

### Expand Prompt
Explain each concept for a 3rd-year CSE placement candidate.

### Polish Prompt
Combine the explanations into one concise answer with a practice question.

### Best Output
Big-O notation measures algorithm efficiency as input size grows. Common complexities include O(1), O(log n), O(n), and O(n²). It helps compare algorithms and choose scalable solutions. Interviewers ask Big-O to test problem-solving and optimization skills.

Practice Question:
What is the time complexity of binary search?

### Self Score
5/5

### Peer Score
10/10

---

# Reflection

For my placement-prep students, the patterns I will use most are Persona and Prompt Chaining because they produce more targeted explanations and better learning outcomes. Persona adapts the response to the student's level, while Prompt Chaining breaks complex topics into manageable steps and improves answer quality.