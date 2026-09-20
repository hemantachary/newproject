# 🧬 GroupDNA — WhatsApp Chat Personality Analyzer

GroupDNA is a Python-based WhatsApp chat analysis project that analyzes group-chat communication patterns and assigns each participant a personality archetype based on measurable chat behavior.

## 🚀 What GroupDNA Does

GroupDNA analyzes a WhatsApp chat export and extracts behavioral patterns such as:

* Message activity
* Participant contribution
* Activity by hour
* Response times
* Silent periods
* Frequently used words
* Behavioral keyword patterns
* Personality/archetype scores

The project then uses these patterns to assign each participant an archetype.

## 🧠 Personality Archetypes

GroupDNA currently identifies:

* **THE SPAMMER**
* **THE GROUP MOM**
* **THE STORYTELLER**
* **THE DRAMA QUEEN**
* **THE NIGHT OWL**
* **THE GHOST**

## 📊 Example Analysis

The analyzed dataset contained:

* **Participants:** 6
* **Messages:** 3,174
* **Period:** April 1, 2024 → May 30, 2024
* **Busiest day:** May 4, 2024
* **Busiest hour:** 18:00

### Final Archetypes

| Participant | Archetype       |
| ----------- | --------------- |
| Rahul       | THE SPAMMER     |
| Priya       | THE GROUP MOM   |
| Karan       | THE STORYTELLER |
| Neha        | THE DRAMA QUEEN |
| Aman        | THE NIGHT OWL   |
| Vikas       | THE GHOST       |

## 🔍 Archetype Evidence

The archetypes were generated from measurable chat patterns.

| Participant | Evidence                        |
| ----------- | ------------------------------- |
| Rahul       | 4.52 average messages per burst |
| Priya       | 576 caring keyword hits         |
| Karan       | 57.05 average words/message     |
| Neha        | 62.20% dramatic messages        |
| Aman        | 79.80% night messages           |
| Vikas       | 73.33% silent days              |

## 📈 Visualizations

The project generates visualizations for:

1. Messages by Participant
2. Group Activity by Hour
3. Archetype Distribution
4. Average Response Time

## 🛠️ Technologies Used

* Python
* Pandas
* Matplotlib
* Regular Expressions
* JSON
* Jupyter Notebook / Google Colab

## 📁 Project Structure

```text
GroupDNA/
│
├── GroupDNA.ipynb
├── groupdna_report.json
├── README.md
│
└── visualizations/
    ├── messages_by_participant.png
    ├── group_activity_by_hour.png
    ├── archetype_distribution.png
    └── average_response_time.png
```

## ⚙️ How It Works

```text
WhatsApp Chat Export
        ↓
Message Parsing
        ↓
Participant Extraction
        ↓
Statistical Analysis
        ↓
Behavioral Pattern Detection
        ↓
Archetype Scoring
        ↓
Final Personality Classification
        ↓
JSON Report + Visualizations
```

## 🎯 Project Goal

The goal of GroupDNA is to demonstrate how conversational data can be transformed into meaningful behavioral insights using Python-based data analysis.

## 📌 Output

After processing a chat dataset, GroupDNA produces:

* Participant statistics
* Activity patterns
* Response-time analysis
* Word-frequency analysis
* Archetype scores
* Final personality classifications
* Visualizations
* A JSON analysis report

## ⚠️ Note

The personality archetypes are project-defined classifications based on observable chat patterns. They are intended for entertainment and data-analysis demonstration rather than psychological diagnosis.

## 👨‍💻 Author

**Hemant Achary**

B.Tech — Computer Science & Engineering (Data Science)
