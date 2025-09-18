📌 README – Task 1: Name Matching System
🔹 Project Overview

This project is a Name Matching System that helps find the closest matches for a given name from a dataset. For example, if someone types Geeta, the system suggests similar names like Geetha, Gita, Gitu, etc.

It uses string similarity matching to return both the best match and a ranked list of alternatives with scores.

🔹 Why It’s Useful

Helps in data cleaning when dealing with messy datasets (different spellings of the same name).

Can be applied in HR systems, customer databases, or search engines to ensure accurate matching.

🔹 Key Features

Stores a list of 30+ similar names.

Accepts user input and finds the closest match.

Returns both:

✅ Best Match (highest similarity)

📌 Ranked list of other possible matches

🔹 Tech Used

Python

FuzzyWuzzy (string similarity library)

🔹 Example Output

Input: Geeta

Best Match: Geetha (Score: 95)

Other Matches:
Geetha - 95
Gita   - 90
Gitu   - 85
Githa  - 82
Gitika - 78
