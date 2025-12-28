🕵️ Chrome Browser History Analyzer (Forensics)
A Python-based digital forensics tool that extracts and analyzes Google Chrome browsing and search history from a forensic perspective.
This tool is designed for Cybersecurity students, SOC analysts, and Digital Forensics investigators to understand user browsing behavior while maintaining evidence integrity.
________________________________________

📌 Features
•	🔍 Extracts last 20 search queries from:
o	Google
o	YouTube
o	Amazon
o	ChatGPT (derived from page titles)
•	🌐 Displays last 20 visited websites
•	🕒 Converts Chrome timestamp to human-readable date & time
•	📄 Generates an automatic forensic report (.txt)
•	🖥️ Prints output to terminal + report file simultaneously
•	🛡️ Maintains forensic integrity by analyzing a copied history file

________________________________________

🧪 Forensic Relevance
This tool is useful for:
•	Browser forensics
•	Incident response investigations
•	User activity reconstruction
•	Academic & lab demonstrations
•	SOC analyst training
•	Cybercrime investigations (educational use)
⚠️ Note: This tool is intended for educational and authorized forensic analysis only.

________________________________________

🛠️ Requirements
•	Python 3.x
•	Linux (Tested on Kali Linux)
•	Google Chrome browser
•	Required Python modules (built-in):
o	sqlite3
o	shutil
o	datetime
o	urllib.parse
No external libraries required ✅

________________________________________

🚀 Installation & Usage
1️⃣ Clone the Repository
git clone https://github.com/yourusername/Browser_history_analyzer.git
cd Browser_history_analyzer
2️⃣ Run the Script
python3 Browser_history_analyzer.py
3️⃣ Output
•	A report file will be generated automatically:
Chrome_Forensic_Report_1.txt
Chrome_Forensic_Report_2.txt
•	Output is displayed in terminal and saved to the report file simultaneously.

________________________________________

📂 Sample Output
[01] 🕒 2025-12-27 17:19:01
     🔍 Engine : Google
     🔑 Query  : amazon laptop
------------------------------------------------------------

[01] 🕒 2025-12-27 16:46:51
     🌍 Site   : www.youtube.com
     📄 Title  : YouTube
     🔢 Visits : 125
------------------------------------------------------------

________________________________________

🔐 Forensic Methodology Used
•	Chrome History SQLite database
•	Evidence duplication (History_copy)
•	Read-only analysis
•	Timeline-based reconstruction
•	Search query extraction using URL parameters

________________________________________

📚 Learning Outcomes
•	Understand browser artifact structure
•	Learn Chrome SQLite database analysis
•	Practice real-world digital forensics
•	Improve Python scripting for security

________________________________________

👨‍💻 Author
Dhruvik Variya
🎓 MSc IT (Cybersecurity & Digital Forensics)
🛡️ Cybersecurity Student
🐧 Kali Linux User

________________________________________

⚖️ Disclaimer
This tool is developed strictly for educational and ethical forensic purposes.
Unauthorized access or misuse of personal data is illegal and unethical.

________________________________________

⭐ Support
If you find this project useful:
•	⭐ Star the repository
•	🍴 Fork it
•	🛠️ Improve it

________________________________________

