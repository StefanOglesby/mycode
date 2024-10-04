# Probing_OpenEndeds
A demo app demonstrating how genAI can probe respondents' answers to open ended questions

The input is the question from the online survey questionnaire plus the respondent's answer. The app generates a varied probe for specific. 
It works in English and German
Next steps is setting-up a streamlit prototype:
The streamlit prototype has the following input fields:
Question: String
Answer: String
Language: Dropdown "Enlish", "German"
Temperature: Dropdown 0 to 2, with 0.1 steps
The streamlit prototype hs the following output window:
probe: String response from LLM API, nicely formatted.
