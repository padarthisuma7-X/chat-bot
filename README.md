# 🤖 RuleEngine.JS - Rule-Based AI Agent Playground

A browser-based Rule-Based Artificial Intelligence Expert System built using **HTML, CSS, JavaScript, Tailwind CSS, and Lucide Icons**.

Unlike modern AI systems powered by Large Language Models (LLMs), this project demonstrates how traditional expert systems work through predefined knowledge rules, keyword matching, regular expression patterns, and deterministic inference logic.

---

## 🌐 Live Demo

**Project Link:**

https://padarthisuma7-x.github.io/chat-bot/

---

# 📖 Overview

RuleEngine.JS is an educational AI playground that allows users to:

* Create custom AI knowledge rules
* Edit and manage a knowledge base
* Import and export rule databases
* Test rule-based reasoning
* Observe inference execution in real time
* Understand how traditional AI systems operate

The application simulates the behavior of early expert systems where decisions are made using predefined logic instead of machine learning.

---

# ✨ Features

## 🧠 Rule-Based Inference Engine

* Sequential rule scanning
* Keyword matching
* Regular expression matching
* Deterministic responses
* First-match execution strategy

---

## 💬 Interactive Chat Interface

* Real-time chatbot interaction
* Human-friendly chat layout
* Preset query suggestions
* Dynamic response generation

---

## 📚 Knowledge Base Management

Users can:

* Add new rules
* Edit existing rules
* Delete rules
* Import knowledge databases
* Export knowledge databases

---

## 🔍 Real-Time Debug Console

The system displays:

* Rule evaluation sequence
* Match attempts
* Successful matches
* Failed matches
* Inference results

This provides complete transparency into how decisions are made.

---

## 📁 JSON Import / Export

The knowledge base can be:

* Saved as JSON
* Shared with others
* Re-imported later
* Extended with custom domains

---

## 🎨 Modern User Interface

Built with:

* Tailwind CSS
* Lucide Icons
* Responsive Design
* Dark Theme Layout
* Modern Dashboard Style

---

# 🏗️ System Architecture

```text
User Query
     │
     ▼
Input Processor
     │
     ▼
Sequential Rule Scanner
     │
     ├── Keyword Matching
     │
     ├── Regex Matching
     │
     ▼
Matched Rule
     │
     ▼
Response Generator
     │
     ▼
Chat Interface
```

---

# ⚙️ How It Works

## Step 1: User Enters Query

Example:

```text
What is AI?
```

---

## Step 2: Query Normalization

Input is converted to lowercase:

```javascript
const query = input.toLowerCase().trim();
```

---

## Step 3: Rule Evaluation

The engine scans every rule:

```javascript
for (const rule of ruleBase)
```

---

## Step 4: Keyword Matching

Example:

```javascript
if (query.includes(keyword))
```

---

## Step 5: Regex Matching

Example:

```javascript
const regex = new RegExp(pattern, 'i');
```

---

## Step 6: Response Selection

The first matching rule returns:

```javascript
return matchedRule.response;
```

---

## Step 7: Debug Logging

The execution trace is displayed in the debugger panel.

---

# 📂 Project Structure

```text
chat-bot/
│
├── index.html
├── README.md
├── knowledge.json
│
├── Components
│   ├── Navigation Bar
│   ├── Rules Viewer
│   ├── Chat Window
│   ├── Debug Console
│   └── Rule Editor
│
├── Logic
│   ├── Inference Engine
│   ├── Rule Evaluator
│   ├── JSON Exporter
│   ├── JSON Importer
│   └── Chat Handler
│
└── Assets
    └── Icons
```

---

# 🧩 Default Knowledge Categories

The system ships with AI-related knowledge including:

## Core Definition

* What is AI
* Artificial Intelligence Definition

## AI History

* AI Origins
* AI Winters
* AI Development Timeline

## Cognitive Capabilities

* Reasoning
* Problem Solving
* Knowledge Representation

## Agent Systems

* Rational Agents
* Utility Functions
* Planning

## Machine Learning

* Supervised Learning
* Unsupervised Learning
* Reinforcement Learning
* Deep Learning

## Natural Language Processing

* NLP
* GPT
* Transformers
* Language Understanding

## Perception

* Computer Vision
* Sensors
* Object Recognition

## Social Intelligence

* Affective Computing
* Emotion Recognition

## Future AI

* AGI
* Human-Level Intelligence

---

# 💡 Example Queries

```text
What is AI?

Define Artificial Intelligence

When was AI founded?

What is an AI Winter?

Explain Machine Learning

What is Supervised Learning?

What is Reinforcement Learning?

Explain Natural Language Processing

What is AGI?

What are the goals of AI?
```

---

# 📸 Screenshots

You can add screenshots here later:

```markdown
![Home Screen](screenshots/home.png)

![Chat Interface](screenshots/chat.png)

![Debugger](screenshots/debugger.png)

![Rule Editor](screenshots/editor.png)
```

---

# 🚀 Installation

## Clone Repository

```bash
git clone https://github.com/PadarthiSuma7-X/chat-bot.git
```

---

## Open Project

Simply open:

```text
index.html
```

in any modern web browser.

No backend required.

No server required.

No database required.

---

# 🔧 Custom Rule Example

Example Rule:

```json
{
  "id": "robotics",
  "category": "Engineering",
  "description": "Answers robotics questions",
  "keywords": [
    "robot",
    "robotics",
    "robotic"
  ],
  "patterns": [
    "robot.*"
  ],
  "response": "Robotics combines mechanical engineering, electronics, and computer science to build intelligent machines.",
  "source_snippet": "Custom knowledge source"
}
```

---

# 📤 Export Format

Example exported file:

```json
{
  "agent_metadata": {
    "name": "RuleEngineJS",
    "version": "1.0"
  },
  "rules": []
}
```

---

# 🎯 Educational Objectives

This project helps students learn:

* Artificial Intelligence Fundamentals
* Expert Systems
* Knowledge Engineering
* Rule-Based Reasoning
* Pattern Matching
* Explainable AI
* Human-Computer Interaction
* Front-End Development

---

# 🔮 Future Enhancements

Planned improvements:

### AI Features

* Fuzzy Matching
* Semantic Search
* Confidence Scores
* Multi-Rule Inference
* Knowledge Graphs
* Local LLM Integration

### User Experience

* Voice Input
* Voice Output
* Theme Customization
* Mobile Optimization
* Searchable Rule Database

### Storage

* IndexedDB Support
* Cloud Synchronization
* User Profiles

### Analytics

* Rule Usage Statistics
* Match Frequency Reports
* Knowledge Coverage Analysis

---

# 🛠 Technologies Used

| Technology   | Purpose           |
| ------------ | ----------------- |
| HTML5        | Structure         |
| CSS3         | Styling           |
| JavaScript   | Logic             |
| Tailwind CSS | UI Framework      |
| Lucide Icons | Icons             |
| JSON         | Knowledge Storage |

---

# 📊 AI Concepts Demonstrated

This project demonstrates:

* Expert Systems
* Rule-Based Agents
* Symbolic AI
* Pattern Matching
* Knowledge Bases
* Inference Engines
* Explainable Decision Making

---

# 👨‍💻 Developer

**XKing**

Electronics & Communication Engineering Student

Interested in:

* Artificial Intelligence
* Embedded Systems
* Robotics
* IoT
* ROS2
* Computer Vision
* Intelligent Agent Design

---

# 🤝 Contributing

Contributions are welcome.

Steps:

1. Fork the repository
2. Create a new branch
3. Implement improvements
4. Submit a pull request

---

# ⭐ Support

If you find this project useful:

* Star the repository
* Share the project
* Suggest improvements
* Contribute new knowledge bases

---

# 📜 License

MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files, to deal in the Software without restriction.

---

## Final Note

RuleEngine.JS is designed to demonstrate the foundations of classical artificial intelligence through transparent, explainable, and educational rule-based reasoning. While modern AI systems rely heavily on machine learning and neural networks, understanding rule-based expert systems remains essential for learning the historical and theoretical foundations of AI.

Built with curiosity, logic, and a healthy amount of human determination to teach machines how to answer questions using nothing but rules and pattern matching.
