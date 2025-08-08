# RICE Feature Prioritization Tool

A simple React app prototype designed to help product managers and users prioritize product features using the RICE framework.

---

## Overview

As someone exploring product management, I wanted to better understand how real prioritization frameworks are applied in practice. This tool is a simple way to try out the RICE framework—by inputting feature ideas and scoring them based on Reach, Impact, Confidence, and Effort.

The app makes it easy to add and sort features by their calculated RICE scores, helping simulate how product teams might decide what to build first. It’s a lightweight tool built to practice both product thinking and basic front-end development.

---

## Features

- Add features with inputs for:
  - **Reach:** Number of users impacted within a timeframe
  - **Impact:** Value of the feature (1–10 scale)
  - **Confidence:** Certainty of impact (0.0–1.0 scale)
  - **Effort:** Estimated effort in person-months (1–10 scale)
- Calculates RICE score using the formula:
  
RICE Score = (Reach × Impact × Confidence) ÷ Effort

- Automatically sorts features by descending RICE score
- Delete features to keep the list up to date
- Simple, clean UI built in React

---

##  Tech Stack & Development Notes

- React (front-end UI)
- JavaScript (logic and state management)
- UUID (unique IDs for features)
- CSS for basic styling

> **Note:** This project was built starting from a React template I found on Vercel, then customized to implement the RICE prioritization logic and UI.

---

##  Why I Built This

As a college student interested in product management, I wanted to build something hands-on that goes beyond just reading about frameworks. The RICE model is commonly used in product teams to decide what to build next, so I thought: why not turn it into a working app?

Creating this tool helped me:
- Apply a product strategy concept by turning a prioritization framework into something interactive and visual
- Practice thinking like a PM, making decisions about what functionality mattered most for the MVP
- Strengthen my front-end skills, especially with React state management, forms, and basic logic
- Understand trade-offs and iteration, since I had to scope the project to something I could build quickly but still usefully
- Simulate a real PM scenario, where features must be compared, evaluated, and prioritized with incomplete information

This project was a small but meaningful step in combining what I’ve learned about product thinking with actual software execution.

---

##  Demo Screenshots & Video

### Screenshot of the tool in action:

![RICE Tool Screenshot](./Rice%20Score%20Calculator.jpg)

### Demo video showing feature input and prioritization:

[Watch the demo video on Google Drive](https://drive.google.com/file/d/1tCyx6OoN729cHM-tBHm2F_kWnFBxljTX/view?usp=sharing)
---

##  How to Use

1. Input feature ideas with values for Reach, Impact, Confidence, and Effort
2. View the prioritized list sorted by RICE score
3. Use the delete button to remove features as needed

---

## Contact

Feel free to reach out to me for questions or collaboration:

- LinkedIn: www.linkedin.com/in/sravani-reddy-dodda-a177b6245   
- Email: sdodda23@gmail.com

---

*Thank you for checking out my project!*
