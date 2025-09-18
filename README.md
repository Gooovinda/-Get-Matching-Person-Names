Name Matching System

A Python-powered application that finds the closest matches for a given input name from a dataset. Designed for handling spelling variations and fuzzy searches, this project showcases text similarity implementation in a practical use case.

📌 Objective
Build a system that takes a user’s input name and returns the best matching name along with a ranked list of alternatives with similarity scores. This can be used for data cleaning, search optimization, or duplicate detection.

🚀 Key Highlights

🔍 Similarity Matching: Identifies the closest match for any given input.

📑 Ranked Results: Returns both the best match and a list of similar names with scores.

✅ Practical Utility: Useful for CRMs, HR systems, and large datasets where duplicate or misspelled entries exist.

📊 Tech Stack

Python

FuzzyWuzzy (string similarity)

📂 Dataset

A list of 30+ sample names (with variations such as Geetha, Gita, Gitu, Geeti, etc.).

Stored directly in the project for quick experimentation.

🧪 Example Output
Input: Geeta

Best Match: Geetha (Score: 96)  
Other Possible Matches:  
- Gita (Score: 92)  
- Gitu (Score: 85)  
- Geeti (Score: 80)  


📂 Project Structure

├── name_match.py          # Main script  
├── names_list.txt         # Sample dataset of names  
└── README.md              # Project documentation  


⚡ How to Run the Project

Clone the repository or download the ZIP file.

Install dependencies: pip install fuzzywuzzy

Run the script: python name_match.py

Enter a name when prompted to get best matches with similarity scores.
