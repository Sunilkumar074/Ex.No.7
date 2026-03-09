# Exno.7-Develop a prompt-based application tailored to their personal needs, fostering creativity and practical problem-solving skills while leveraging the capabilities of large language models.

# Date: 9/3/26
# Register no. 212223040213
# Name: SUNIL KUMAR P.B.
# Aim

#AI Tools Required: 
To develop a prompt-based application using ChatGPT that demonstrates how prompts can be designed progressively—from simple to advanced—to organize daily tasks and improve productivity.

# AI Tools Required

ChatGPT (Large Language Model)

Computer / Internet

Optional: Command Line Interface or simple UI

# Explanation

This experiment focuses on designing a personal productivity assistant using prompt engineering.
The assistant interacts with users in natural language, helps manage daily tasks, schedules reminders, suggests wellness tips, and answers general queries.
By refining prompts, the assistant adapts to changing user preferences over time.

Prompt Used

“Design a personal productivity assistant that can help manage daily tasks, schedule reminders, suggest wellness tips, and answer general queries. The assistant should interact using natural language and be adaptable to the user’s changing preferences over time.”

Procedure

Define the core requirements of a personal productivity assistant.

Identify and construct appropriate prompts for each task using an LLM.

Simulate natural user interaction through a command-line or simple interface.

Collect user feedback and adjust responses accordingly.

(Optional) Integrate basic memory to simulate preference adaptation.

Expected Output

(Output file attached via drive link)

Example Response by LLM
Personal Productivity Assistant Features
1. Daily Task Manager

Accepts tasks via natural language
(e.g., “Remind me to call mom at 6 PM”)

Organizes tasks by priority and deadline

Provides daily summaries and pending task lists

2. Smart Scheduler

Schedules events and sets reminders contextually

Detects overlapping appointments

Suggests available free time slots

3. Wellness Tips Generator

Suggests daily wellness advice:

Hydration reminders

Exercise tips

Screen-time breaks

Adapts suggestions based on user feedback and preferences
# Example 1: Reminder Management Assistant
Stage 1: Simple Prompt (Naive Approach)

Prompt:

“Remind me about my activities today.”

Example User Input:

“I need to submit my assignment, attend a yoga class at 6 PM, and call my friend.”

ChatGPT Output:

Here are your activities:

Submit your assignment

Attend yoga class at 6 PM

Call your friend

Analysis

Pros

Quick and simple

Lists tasks clearly

Cons

No time planning

No reminders or notifications

No prioritization

Doesn't add useful suggestions

Stage 2: Structured Prompt (Instruction-Based)

# Explanation: 
Prompt:
"Design a personal productivity assistant that can help manage daily tasks, schedule reminders, suggest wellness tips, and answer general queries. The assistant should interact using natural language and be adaptable to the user’s changing preferences over time."
Procedure:
1. Define the core requirements of a personal productivity assistant.
2. Identify and construct appropriate prompts for each task using an LLM (e.g., ChatGPT).
3. Simulate natural user interaction through a simple interface or command-line system.
4. Collect feedback or inputs from users and adapt responses accordingly.
5. (Optional) Integrate basic memory to simulate preference adaptation.
EXPECTED OUTPUT: - (attached the drive link)
Output (Example Response by LLM):
Personal Productivity Assistant Features:
1. Daily Task Manager:
o Accept tasks via natural language (e.g., "Remind me to call mom at 6 PM").
o Organize tasks by priority and deadline.
o Provide daily summaries and pending items.
2. Smart Scheduler:
o Schedule events and set reminders using contextual understanding.
o Notify user of overlapping appointments or free time slots.
3. Wellness Tips Generator:
o Suggest daily wellness advice (hydration, exercise, screen-time breaks).
o Adapt suggestions based on past user preferences and responses.

“Act as a reminder assistant. List the tasks I provide, assign priority (High/Medium/Low), and suggest reminder times. Format the result in a table.”

Example User Input:

“Submit assignment tomorrow, yoga class at 6 PM, call my friend tonight.”

ChatGPT Output

Task	Priority	Suggested Reminder
Submit assignment	High	Today 7 PM
Yoga class at 6 PM	Medium	Today 5:30 PM
Call friend	Low	Today 8 PM
Analysis

Pros

Organized output

Suggests reminders

Adds some logic

Cons

Not personalized

No schedule integration

Stage 3: Context-Aware Prompt (Advanced Instruction)

Prompt

“You are a smart reminder assistant. The current time is 10 AM. My working hours are 9 AM – 6 PM. Create a schedule for my tasks and suggest reminder notifications before each activity.”

Example Tasks

Submit assignment tomorrow

Yoga class at 6 PM

Call my friend

Prepare notes for tomorrow’s class

ChatGPT Output

Daily Plan

10:00 AM – 12:00 PM
Prepare notes for tomorrow’s class

12:00 PM – 1:00 PM
Work on assignment submission

5:30 PM Reminder
Prepare for yoga class

6:00 PM – 7:00 PM
Yoga class

8:00 PM Reminder
Call friend

Analysis

Pros

Time-aware scheduling

More actionable

Context included

Cons

Still a single interaction

Doesn't remember past preferences

Stage 4: Persona-Driven Interactive Prompt

System Prompt

“You are LifeSync, an intelligent personal reminder assistant. Your goal is to help users manage activities efficiently.

Rules:

Ask clarification questions when needed

Provide time-based reminders

Maintain a friendly and supportive tone

Suggest productivity improvements when possible”

User Interaction

User:
“Remind me to study and go for jogging.”

LifeSync:
“Sure! How long would you like to study, and what time do you prefer to go jogging?”

User:
“Study for 2 hours and jog at 7 PM.”

LifeSync Output:

Today's Plan

4 PM – 6 PM
Focused Study Session

6:45 PM Reminder
Prepare for jogging

7 PM – 7:45 PM
Jogging

Motivation:
“Great balance between productivity and health!”

Analysis

Pros

Interactive conversation

Personalized scheduling

Encouraging feedback

Adaptive planning

Cons

Requires system-level prompt setup

More complex to design

# Example 2: Wellness Tips Assistant
Stage 1: Simple Prompt

Prompt
“Give me wellness tips.”

Output

Drink water

Exercise regularly

Sleep well

Problem: Too generic.

Stage 2: Structured Prompt

Prompt
“Provide 5 daily wellness tips for someone working on a computer for long hours.”

Output

Take a 5-minute break every hour

Stretch your neck and shoulders

Stay hydrated

Use proper sitting posture

Reduce screen brightness at night

Better but still static.

Stage 3: Context-Aware Prompt

Prompt
“You are a wellness coach. I work on a laptop from 9 AM to 5 PM. Suggest a wellness schedule during my workday.”

Output

9:00 AM – Start work
10:30 AM – Stretch break
12:30 PM – Lunch and walk
3:00 PM – Hydration break
5:00 PM – Light exercise

Now it becomes actionable advice.

Stage 4: Interactive Wellness Coach

System Prompt

“You are WellGuide, a friendly wellness assistant. Track user habits, provide personalized health tips, and adapt suggestions based on feedback.”

Interaction

User:
“I feel tired during work.”

WellGuide:
“That might be due to long screen time. Try a 10-minute walk or eye relaxation exercise. Would you like a daily wellness routine?”

User:
“Yes.”

WellGuide Output

Morning Routine

Drink water after waking up

5-minute stretching

Work Routine

Break every 60 minutes

Eye relaxation every 2 hours

Evening Routine

20-minute walk

Limit screen exposure before sleep
# Result: 
The lab exercise resulted in the creation of a prototype concept for a personal assistant powered by large language models. Students were able to:
 Understand how to tailor LLM prompts to real-life applications.
 Foster creativity by designing features suited to their personal or academic lives.
 Learn prompt engineering techniques for optimal interaction with AI tools.
 Experience the versatility and utility of generative AI in solving everyday problems.
