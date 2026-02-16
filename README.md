# Antardarpana – Daily Productivity Insights Workflow

> *Antardarpana* (अन्तर्दर्पण) — "inner mirror." A daily reflection system that holds up a mirror to your productivity through the lens of the Bhagavad Gita.

## What It Does

Antardarpana is an automated n8n workflow that compares what you *planned* to do with what you *actually* did — and delivers honest, personalized feedback rooted in Gita wisdom.

At the end of each day, the workflow:
1. **Pulls your planned tasks** from Google Calendar
2. **Collects what you actually did** via a Google Form you fill out daily
3. **Sends both to an LLM** which analyzes task completion, identifies gaps, and generates a productivity score
4. **Scrapes VEDABASE.io** for a contextually relevant Bhagavad Gita shloka
5. **Delivers a motivational insight** in Krishna's voice — honest, direct, and occasionally sarcastic — stored in Airtable

## Why

Built on the principle of *karmanyevadhikaraste* — your right is to the action, not the fruit. This workflow makes accountability personal, spiritual, and actually motivating instead of guilt-inducing.

## Tech Stack

- **n8n** – workflow automation
- **Google Calendar API** – planned task input
- **Google Forms** – actual task input
- **LLM API** – productivity analysis and insight generation
- **VEDABASE.io** – Bhagavad Gita verse scraping
- **Airtable** – data storage and logging
- **HTML/CSS/JavaScript** – dashboard (in progress)

## Status

Core workflow complete. Basic HTML dashboard created. V2.0 involving a better, more robust UI/UX as well as workflow dynamics in progress.