# Lesson QA Automation

## Overview

Lesson QA Automation is an AI-powered workflow built with Relay.app, Google Forms, and Google Sheets.

The automation reviews new lesson drafts for my educational apps, Little Noories, Tamilingo, and Little Readers and checks whether the lesson is age-appropriate, clear, aligned with vocabulary goals, connected to quiz questions, and formatted consistently.

This workflow helps streamline curriculum review and quality assurance across multiple learning experiences designed for children.

<img width="1149" height="1369" alt="ChatGPT Image May 12, 2026, 08_42_55 PM" src="https://github.com/user-attachments/assets/babf9f8d-6aae-4205-a4e7-41ff21f23fab" />


<img width="1536" height="1024" alt="Lesson QA Automation" src="https://github.com/user-attachments/assets/d4d4768a-e43f-438e-972d-0fc364775704" />

---

## About the Apps

### Little Noories
An interactive Islamic learning app focused on Quran-inspired stories, Arabic learning, duas, habits, activities, and value-based learning for children.

### Tamilingo
A Tamil language learning app designed for young learners, especially children growing up in Western countries, using interactive vocabulary, pronunciation, and literacy activities.

### Little Readers
An early literacy app that helps children improve reading skills through beginner-friendly stories, vocabulary activities, quizzes, and interactive learning experiences.

---

## Problem Statement

Creating educational content for children requires more than writing lessons. Each lesson needs to be reviewed for clarity, age-level fit, vocabulary difficulty, quiz alignment, and formatting consistency.

Manually reviewing every lesson can take time, especially while building multiple educational apps simultaneously. This automation helps speed up the review process by using AI to provide structured lesson QA feedback.

---

## Tools Used

- Google Forms
- Google Sheets
- Relay.app
- AI Writing Step in Relay.app

---

## Workflow

```text
Lesson Draft Submitted
        ↓
Relay.app Trigger
        ↓
AI Reviews Lesson Quality
        ↓
QA Results Saved to Google Sheets
        ↓
Lessons Can Be Tracked and Improved
```

---

## Automation Steps

### 1. Create a Lesson Draft Form

A Google Form was created to collect lesson draft details.

The form collects:

* App Name
* Lesson Title
* Age Group
* Lesson Content
* Vocabulary Words
* Quiz Questions
* Activity Type

<img width="314" height="623" alt="image" src="https://github.com/user-attachments/assets/9dad9865-a9a2-4add-9500-626306ba1722" />

---

### 2. Connect Form Responses to Google Sheets

Each form submission is saved into Google Sheets.

The sheet includes:

* Timestamp
* App Name
* Lesson Title
* Age Group
* Lesson Content
* Vocabulary Words
* Quiz Questions
* Activity Type
* QA Score
* Age-Level Check
* Clarity Check
* Vocabulary Check
* Quiz Alignment Check
* Formatting Check
* Improvement Suggestions
* Status

<img width="1202" height="632" alt="image" src="https://github.com/user-attachments/assets/51806d07-7671-4e9a-a42c-e5b5e1fbfb69" />

---

### 3. Create Relay.app Workflow

Relay.app was used to automate the review process.

Trigger:

* New Google Form response is submitted

Actions:

* AI reviews the lesson draft
* Google Sheets creates or updates a QA row

<img width="776" height="621" alt="image" src="https://github.com/user-attachments/assets/7145e2bd-cc09-4636-9de2-3350a6cdc22e" />

---

### 4. Add AI Lesson Review Step

The AI step reviews the lesson draft using curriculum quality criteria.

Prompt used:

```text
You are a senior early-childhood curriculum reviewer.

Review this lesson draft for a kids educational app.

Evaluate the lesson using these categories:

1. Age-Level Fit
2. Clarity
3. Vocabulary Appropriateness
4. Quiz Alignment
5. Formatting Consistency
6. Overall QA Score out of 10
7. Improvement Suggestions

Keep the feedback concise, teacher-friendly, and actionable.
```

<img width="1091" height="774" alt="Screenshot 2026-05-12 200958" src="https://github.com/user-attachments/assets/3a69a9c7-3b3b-4533-8dd8-101633b5c417" />

---

### 5. Save QA Results to Google Sheets

Relay.app saves the AI review back into Google Sheets.

The automation stores:

* QA Score
* Age-Level Check
* Clarity Check
* Vocabulary Check
* Quiz Alignment Check
* Formatting Check
* Improvement Suggestions
* Status

<img width="1676" height="729" alt="image" src="https://github.com/user-attachments/assets/2c133af9-006a-4864-a2c2-7c5ac7f51559" />

---

## Example Use Cases

### Tamilingo

Lesson drafts can be checked for:

* age-appropriate Tamil vocabulary
* pronunciation support
* simple quiz alignment
* clarity for children living in the West

### Little Readers

Story lessons can be checked for:

* reading level
* vocabulary difficulty
* comprehension question alignment
* sentence clarity

### Little Noories

Islamic and Arabic learning lessons can be reviewed for:

* child-friendly language
* vocabulary reinforcement
* activity alignment
* lesson consistency

---

## What Worked

* Google Forms made it easy to collect lesson draft information.
* Relay.app provided a simple visual automation builder.
* The AI writing step produced structured QA feedback.
* Google Sheets worked well as a lightweight QA tracking database.

---

## What I Would Improve Next

Future improvements could include:

* Separating the AI response into individual structured fields automatically
* Adding a reviewer approval column
* Sending alerts when QA Score is below a threshold
* Creating a dashboard to track lesson quality over time
* Adding app-specific QA rules for Tamilingo, Little Readers, and Little Noories

---

## Key Learning

This project showed how AI and automation can support content quality control for educational apps. Instead of manually reviewing each lesson from scratch, the workflow creates a repeatable QA system that helps identify clarity issues, vocabulary gaps, quiz misalignment, and improvement opportunities.

---

## Final Outcome

A working Lesson QA Automation system that:

* Collects new lesson drafts
* Reviews lessons using AI
* Scores lesson quality
* Saves QA feedback to Google Sheets
* Supports continuous improvement for Little Noories, Tamilingo, and Little Readers

```
```



