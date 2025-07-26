---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true
description: "A fun quiz about {{ replace .Name "-" " " }}."

# Define all questions for the quiz below.
# You can have any number of questions.
# Supported types: "multiple-choice", "true-false", "short-answer"

questions:
  - type: "multiple-choice"
    text: "What is the capital of France?"
    options:
      - "Berlin"
      - "Madrid"
      - "Paris"
      - "Rome"
    answer: "Paris" # The correct answer must match one of the options exactly.
  - type: "true-false"
    text: "The sun rises in the west."
    answer: false # Use 'true' or 'false' for the answer.
  - type: "short-answer"
    text: "What is the chemical symbol for water?"
    answer: "H2O" # Answer is case-sensitive.
---

## About This Quiz

Add any introductory content or instructions for the quiz taker here. This content will appear above the questions.