# Simple_health_checker

# Overview of the project
The Simple Health Checker is a console-based Python tool that provides users with a basic, non-critical health assessment based on a list of symptoms they input. It operates on a rule-based matching engine that compares the user's symptoms against a small, curated dictionary of common illnesses (e.g., cold, flu, allergies). The primary goal is to offer fast, simple information for mild ailments and strongly advise users to consult a professional doctor.

# Features
Simple Text Input: Accepts a single line of comma-separated symptoms (e.g., fever, sore throat, headache).Rule-Based Matching: Uses set intersection to compare user symptoms against a fixed KNOWLEDGE_BASE.Relevance Scoring: Ranks potential conditions based on the number of matched symptoms.Prioritized Output: Displays the top 3 most likely common conditions that have a strong symptom match (typically $\ge 2$ matches).Safety First: Includes a mandatory, prominent medical disclaimer with every result set.User Feedback: Lists the exact symptoms that contributed to each potential match for clarity.

# Technologies/tools used
Python 3: The core programming language used for all logic and execution.
Standard Library: "Utilizes dictionaries for the knowledge base, sets for efficient matching (intersection), and basic string manipulation."
Console/Terminal: The primary User Interface (UI) for both input and output.

INSTALLATION AND SETUP:
Since this project consists of a single function, installation involves cloning the repository and importing the function into your Python environment. Clone the Repository: Open your terminal or command prompt and run: git clone https://github.com/krishna25boe1013/Simple_health_checker.git cd Simple_health_checker

# Instructions for testing
To test the application, you can use specific combinations of symptoms to verify that the scoring and output logic correctly identify the intended conditions.
Cold Test: runny nose, headache, sore throat: Common Cold
Flu Testfever: body aches, fatigue, headache: Influenza (Flu)
Allergy Test: sneezing, itchy eyes, runny nose: Allergies
Weak Match Test: mild headache, vomiting: Migraine or Gastroenteritis 
No Match Test: broken bone, dizziness: "Symptoms do not strongly match."
# Screenshots 
