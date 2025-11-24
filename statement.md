# Problem statement
Users need a quick, preliminary assessment of mild symptoms to decide on the next steps 
(e.g., rest vs. doctor's visit), avoiding confusion from general search results.

# Scope of the project
The project aims to create a minimal, rule-based software tool to provide preliminary, 
non-critical health information.

# Target users
The primary target users are individuals 
seeking basic, preliminary information on common, non-critical ailments.

# High-level features
1. Input/Interface:	Simple, single Text Input prompt for users to list comma-separated symptoms (e.g., fever, cough).
2. Core Logic: Symptom Matching Engine calculates a relevance score by matching user input against the knowledge base.
3. Output:	Prioritized Results: Displays the top 3 most likely common conditions based on the highest relevance score.
4. Information Display:	Matched Symptom List: Explicitly lists the user's input symptoms that contributed to each specific condition match.
5. Safety/Compliance:	Mandatory Medical Disclaimer: A prominent, non-dismissible warning stating the tool is not a substitute for professional medical advice.
