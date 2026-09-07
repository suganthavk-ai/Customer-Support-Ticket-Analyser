# Customer-Support-Ticket-Analyser
The project demonstrates fundamental Python concepts such as dictionaries, lists, functions, loops, conditional statements, sets, string methods, and user input.
## 📌 Project Overview
The Customer Support Ticket Analyser is a beginner-friendly Python project designed to store, clean, analyse, and extract useful insights from customer support tickets.
It helps analyse customer issues based on keywords, ticket priority, issue description length, and unique words.
## 🎯 Objectives
The main objectives of this project are:
-	Store customer support ticket information using Python data structures.
-	Allow users to add new support tickets.
-	Validate ticket priority.
-	Clean and standardize issue descriptions.
-	Perform keyword-based analysis.
-	Analyse ticket priorities.
-	Identify the ticket with the longest issue description.
-	Extract and sort unique words from ticket descriptions.
-	Generate meaningful summary insights from the ticket data.
## 📊 Dataset
The project starts with 10 preloaded customer support tickets.
Each ticket contains:
| Field | Description |
| ---------| ---------- |
| Ticket_No | Unique ticket number |
| Customer_Name | Name of the customer |
| Issue_Description | Description of the customer issue |
| Priority | Ticket priority: High, Medium, or Low |

```
Example:
ticket_data = {
    'Ticket_No': [1, 2, 3, 4, 5],
    'Customer_Name': ['Ravi', 'Meera', 'Sam', 'Anu', 'Rakesh'],
    'Issue_Description': [
        'Internet not working',
        'slow response, very poor service',
        'GREAT support! issue resolved.',
        'okay... need help',
        'not BAD but slow'
    ],
    'Priority': ['High', 'Low', 'High', 'Medium', 'Low']
}
```
## 🔄 Project Workflow
The project is divided into the following steps:
## Step 1: Preloaded Tickets
The program begins with a dictionary containing customer support ticket information.
A function is used to display the ticket data in a readable format.
## Step 2: Add New Tickets
The user can enter additional tickets during program execution.
The program accepts:
-	Customer Name
-	Issue Description
-	Priority
Priority is validated using a while loop.
Only the following values are accepted:
-	High
-	Medium
-	Low
Ticket numbers are automatically generated using the existing number of tickets.
## Step 3: Text Cleaning
The issue descriptions are cleaned using a custom clean_text() function.
The cleaning process includes:
-	Converting text to lowercase
-	Removing punctuation
-	Replacing shorthand such as ok with okay
-	Removing extra spaces
-	Removing leading and trailing spaces
```
Example:
" GREAT support! issue resolved. "
becomes:
"great support issue resolved"
```
## Step 4: Keyword-Based Issue Insights
The program searches issue descriptions for specific keywords.
The following keywords are analysed:
-	Poor
-	Good
-	Slow
-	excellent
The program counts the number of tickets containing each keyword.
1.	For example:
good support and good behaviour contains the word good, so the ticket is counted once, even though good appears twice.
## Step 5: Final Analysis
The final analysis includes:
### 1. Final Cleaned Ticket Data
Displays the complete cleaned ticket dataset.
### 2. Priority Analysis
Calculates the number of:
-	High-priority tickets
-	Medium-priority tickets
-	Low-priority tickets
### 3. Longest Issue Description
Identifies the ticket with the longest issue description based on word count.
The output displays:
-	Ticket Number
-	Customer Name
-	Issue Description
-	Word Count
### 4. Unique Word Analysis
Extracts all unique words from the issue descriptions using a Python set.
The unique words are then sorted alphabetically.
## 🧠 Python Concepts Demonstrated
| Task | Python Concept |  
| ------------- | ---------------|
| Store ticket information | Dictionary + Lists |
| Display tickets | Function + Loop | 
| Add tickets | input() + append() |
| Generate ticket numbers | len() |
| Validate priority | while + if |
| Clean text | lower(), replace(), split(), join(), strip() | 
| Keyword analysis | Function + Loop |
| Priority analysis | count() |
| Find longest description	| split() + Comparison | 
| Find unique words | set() |
| Sort words | sorted() |
## ▶️ How to Run the Project
### Step 1: Install Python
Make sure Python 3 is installed on your computer.
Check the Python version:
python --version
### Step 2: Clone the Repository
git clone <your-github-repository-url>
### Step 3: Open the Project Folder
cd Customer-Support-Ticket-Analyser
### Step 4: Run the Python Program
python customer_support_ticket_analyser.py
## 💻 Sample User Input
```
ADD NEW TICKETS
How many new tickets do you want to add? 2
Enter details for Ticket 11
Customer Name: Priya
Issue Description: Internet connection is very slow
Priority (High / Medium / Low): High

Enter details for Ticket 12
Customer Name: Kumar
Issue Description: Good support from the team
Priority (High / Medium / Low): Medium
```
📈 Sample Analysis Output
======================================================================
KEYWORD-BASED ISSUE INSIGHTS
======================================================================
```
Tickets containing 'poor'      : 2
Tickets containing 'good'      : 2
Tickets containing 'slow'      : 3
Tickets containing 'excellent' : 1
```
Priority analysis:
======================================================================
PRIORITY ANALYSIS
======================================================================
```
High Priority Tickets   : 4
Medium Priority Tickets : 3
Low Priority Tickets    : 3
```
## 🛠️ Technologies Used
-	Python 3
-	Dictionaries
-	Lists
-	Functions
-	Loops
-	Conditional Statements
-	Sets
-	String Methods
-	User Input

## 🗂️ Project Structure
Customer-Support-Ticket-Analyser/
│
├── customer_support_ticket_analyser.py
└── README.md

## 🔍 Key Insights
This project demonstrates how basic Python programming can be used for simple data analysis.
The analysis can help a customer support team:
-	Identify frequently occurring issue-related keywords.
-	Understand ticket priority distribution.
-	Find tickets with lengthy issue descriptions.
-	Identify commonly used words in customer complaints.
-	Organize and clean raw text data.
-	Prepare data for further analysis.
## 🚀 Future Improvements
The project can be further enhanced by adding:
-	📊 Data visualization using Matplotlib
-	🐼 Data analysis using Pandas
-	😊 Customer sentiment analysis
-	📅 Ticket date and time analysis
-	👤 Support agent performance analysis
-	📈 Monthly ticket trend analysis
-	💾 CSV file import and export
-	🗄️ Database integration using SQL
-	📊 Power BI dashboard integration
## 🎓 Learning Outcome
Through this assignment, I learned how to:
-	Work with Python dictionaries and lists.
-	Create and use functions.
-	Use loops and conditional statements.
-	Accept and validate user input.
-	Clean and manipulate text data.
-	Use sets to identify unique values.
-	Perform basic keyword-based data analysis.
-	Generate meaningful insights from structured data.
## ⭐ Conclusion
The Customer Support Ticket Analyser is a practical beginner-level Python project that combines programming fundamentals with basic data analysis techniques.
It provides a foundation for progressing toward more advanced tools and technologies such as Pandas, NumPy, Matplotlib, SQL, and Power BI.

👩‍💻 Author
Sugantha B
-	Aspiring Data Analyst
-	Python | SQL | Excel | Power BI | Data Cleaning | Data Analysis


