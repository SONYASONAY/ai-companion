# AI Wellness Companion

Building AI course project

## Summary

AI-Companion or AI Wellness Companion is is a mobile first AI assistant that helps people track and improve their mental well being through daily mood logging, habit suggestions, and early detection of signs of stress, anxiety, or burnout.  
**Building AI course project**

## Background

Mental health issues like anxiety, depression, and burnout are widespread yet millions lack access to affordable care or are reluctant to seek help. Especially after the pandemic, isolation and digital overload have worsened this. My motivation stems from personal experience and friends who wished they had someone to talk to regularly without judgment

* Limited access to affordable mental health services
* Social stigma preventing people from reaching out
* Need for consistent, non-intrusive emotional check-ins
* Lack of tools for tracking mental wellbeing over time

## How is it used?

The app prompts users with a short daily check in

* “How are you feeling today?”
* They can write freely, and the AI analyzes sentiment and keywords to detect emotional states. Based on input, it may

Based on responses, the AI

* Recommend breathing exercises or journal prompts
* Remind users of positive habits
* Suggest reaching out to a friend or professional help if distress is detected
* Visualize mood over time using graphs

## Users

* College students
* Remote workers
* Elderly users living alone
* Anyone seeking consistent emotional support

## Data sources and AI methods

* Pre trained NLP models like BERT, RoBERTa, or OpenAI’s GPT for conversation
* Emotion detection datasets like GoEmotions
* Sentiment analysis using transformers + fine tuning
* Simple time series analysis for visualizing mood trends

If built as a prototype, it can be done using Python, HuggingFace’s Transformers, Streamlit for UI, and SQLite for mood logs

## Challenges

* It does not replace a human therapist ethical disclaimers must be clear
* Misinterpretation of ambiguous input
* Requires data privacy and encryption people share sensitive data
* Potential dependence on the chatbot for emotional validation

## What next?

To grow, this project could Connect users to verified therapists or hotlines when risk is detected, expand to multiple languages and cultural contexts, partner with mental health NGOs for distribution and add voice interface for accessibility

## Needed skills

Needed skills might be UX/UI designer for empathetic interface, NLP engineer for better emotion detection and Legal advisor on data protection laws

## Acknowledgments

* Inspired by mood journaling apps like Daylio, Woebot, Wysaand and Reflectly
* Uses datasets such as GoEmotions by Google or Creative Commons
* Thanks to OpenAI and HuggingFace for foundational NLP models
* Sleep and activity tracking ideas from open-source wearables like [Fitbit Web API](https://dev.fitbit.com/build/reference/web-api/)

