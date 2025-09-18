Task 1: Name Matching System

🔹 Project Overview
This project is a Name Matching System that finds the closest matches for a given input name from a dataset. For example, if a user types Geeta, the system suggests similar names like Geetha, Gita, Gitu, etc.

It leverages string similarity algorithms to return both the best match and a ranked list of alternatives with scores.

🔹 Objective
To design a tool that helps in data cleaning and search optimization by matching names with different spellings or variations. Useful for HR systems, CRMs, and large databases where accurate record matching is essential.

🔹 Key Highlights

🔍 Similarity Matching: Finds the closest match for a given name.

📑 Ranked Results: Returns the best match along with a list of alternatives and their similarity scores.

✅ Practical Application: Helps resolve spelling variations, duplicate entries, and fuzzy search queries.

🔹 Tech Stack

Python

FuzzyWuzzy (string similarity)

🔹 Example Output
Input: Geeta

Best Match: Geetha (Score: 96)  
Other Possible Matches:  
- Gita (Score: 92)  
- Gitu (Score: 85)  
- Geeti (Score: 80)  
