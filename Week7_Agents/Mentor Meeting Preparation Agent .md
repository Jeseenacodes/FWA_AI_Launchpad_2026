

# Mentor Meeting Preparation Agent (Single Agent)

## Overview

An AI-powered mentorship preparation assistant that helps users prepare for upcoming mentor meetings by researching mentor context, reviewing previous notes, and generating a structured meeting brief.

<img width="3152" height="1137" alt="Mentor Meeting Preparation Agent (2)" src="https://github.com/user-attachments/assets/d794e4cb-89f7-4f9b-80f2-ef661fd049b9" />

## Problem

Preparing for mentor meetings requires repetitive research, note review, and agenda planning.

## Solution

A single AI agent performs:

- Mentor research
- Context analysis
- Agenda creation
- Question generation
- Discussion prioritization

## Workflow

Inputs
↓
Mentor Prep Agent
↓
Meeting Brief
↓
User

## Inputs

- Mentor LinkedIn Profile
- Previous Meeting Notes
- Career Goals
- Previous Action Items

## Outputs

- Mentor Summary
- Meeting Agenda
- Suggested Questions
- Focus Areas
- Follow-up Actions

## Tools

- OpenAI
- n8n
- Google Calendar
- Notion

## Future Enhancements

- LinkedIn API Integration
- Automated Company Research
- Slack Delivery


---

# System Architecture

This project uses a multi-agent architecture.

## Agents

### Context Research Agent
Collects mentor information, company updates, and previous meeting notes.

### Question Strategy Agent
Generates discussion topics and personalized questions.

### Meeting Coach Agent
Reviews the meeting brief and recommends focus areas and actions.

# Mentor Meeting Preparation Agent (Multi-Agent System)

## Overview

A multi-agent AI system that prepares users for mentorship meetings through specialized agents that collaborate to generate a personalized meeting brief.

<img width="2650" height="856" alt="Multi-Agent Mentor Meeting Prep Agent" src="https://github.com/user-attachments/assets/f6af72ae-debf-47cc-adfa-e48e2e253328" />

## Agent Architecture

User Goal
↓
Mentorship Preparation Assistant
↓
Context Research Agent ↔ Question Strategy Agent
↓
Meeting Brief
↓
Meeting Coach Agent
↓
Email Delivery

## Agents

### Context Research Agent

Responsibilities:

- Review mentor profile
- Analyze company updates
- Review previous meeting history

### Question Strategy Agent

Responsibilities:

- Identify learning goals
- Generate discussion topics
- Create personalized questions

### Meeting Coach Agent

Responsibilities:

- Recommend focus areas
- Explain priorities
- Suggest next actions

## Inputs

- Mentor Profile
- Meeting Notes
- Career Goals
- Company Updates
- Previous Action Items

## Outputs

- Mentor Summary
- Meeting Agenda
- Suggested Questions
- Focus Areas
- Action Recommendations

## Tools

- OpenAI
- n8n
- Google Calendar
- Notion
- Gmail

## Why Multi-Agent?

Specialized agents collaborate and share context, producing higher-quality recommendations than a single-agent workflow.

## Future Enhancements

- Real-time LinkedIn Research
- Company News Monitoring
- Mentor Relationship Memory
- Personalized Learning Recommendations


  
