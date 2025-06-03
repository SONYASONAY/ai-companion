# AI Wellness Companion

Building AI course project

## Summary

AI-Companion or AI Wellness Companion is is a mobile first AI assistant that helps people track and improve their mental well being through daily mood logging, habit suggestions, and early detection of signs of stress, anxiety, or burnout.  
**Building AI course project**

## Background

Mental health issues like anxiety, depression, and burnout are widespread yet millions lack access to affordable care or are reluctant to seek help. Especially after the pandemic, isolation and digital overload have worsened this. My motivation stems from personal experience and friends who wished they had someone to talk to regularly without judgment

1) Limited access to affordable mental health services

2) Social stigma preventing people from reaching out

3) Need for consistent, non-intrusive emotional check-ins

4) Lack of tools for tracking mental wellbeing over time

## How is it used?

The app prompts users with a short daily check in

1) “How are you feeling today?”
2) They can write freely, and the AI analyzes sentiment and keywords to detect emotional states. Based on input, it may

Based on responses, the AI

1) Recommend breathing exercises or journal prompts

2) Remind users of positive habits

3) Suggest reaching out to a friend or professional help if distress is detected

4) Visualize mood over time using graphs

## Users

1) College students

2) Remote workers

3) Elderly users living alone

4) Anyone seeking consistent emotional support

## Data sources and AI methods

1) Pre trained NLP models like BERT, RoBERTa, or OpenAI’s GPT for conversation

2) Emotion detection datasets like GoEmotions

3) Sentiment analysis using transformers + fine tuning

4) Simple time series analysis for visualizing mood trends

If built as a prototype, it can be done using Python, HuggingFace’s Transformers, Streamlit for UI, and SQLite for mood logs

## Challenges

1) It does not replace a human therapist ethical disclaimers must be clear

2) Misinterpretation of ambiguous input

4) Requires data privacy and encryption people share sensitive data

5) Potential dependence on the chatbot for emotional validation

## What next?

To grow, this project could Connect users to verified therapists or hotlines when risk is detected, expand to multiple languages and cultural contexts, partner with mental health NGOs for distribution and add voice interface for accessibility

## Needed skills

Needed skills might be UX/UI designer for empathetic interface, NLP engineer for better emotion detection and Legal advisor on data protection laws

## Acknowledgments

1) Inspired by Woebot, Wysa, and AI based journaling tools

2) Uses datasets such as GoEmotions by Google or Creative Commons

3) Thanks to OpenAI and HuggingFace for foundational NLP models

4) Building AI course by Reaktor and University of Helsinki
