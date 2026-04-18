🔹 Project Title
AI-Based Productivity Analyzer with Data Visualization

🔹 Description
This project is a desktop application developed using Python, Tkinter, and Matplotlib that helps users manage and analyze their daily tasks efficiently.
It uses a rule-based AI approach to prioritize tasks based on their importance (priority) and time required, 
and presents the results through an interactive graphical user interface (GUI).
The system also provides visual insights using charts to help users understand their productivity patterns.

🔹 Features
✅ Add tasks with priority and time
✅ AI-based task prioritization
✅ Optimized task ordering
✅ Delete selected task
✅ Clear all tasks
✅ Pie chart (priority distribution)
✅ Bar graph (time analysis)
✅ Interactive GUI with hover effects
✅ Status updates for user actions

🔹 Technologies Used

Python – Core programming language
Tkinter – GUI development
Matplotlib – Data visualization

🔹 How It Works

1.User enters:
 Task name
 Priority (High/Medium/Low)
 Time required
2.System assigns a score using AI logic:
 Priority weight (High > Medium > Low)
 Time contribution
3.Tasks are:
 Stored in a list
 Sorted based on calculated score
4.Output:
 Optimized task order
 Charts for analysis
 
🔹 AI Logic Used

The system uses a rule-based scoring function:
Score = Priority Weight + (Time / 2)
Where:
High = 3
Medium = 2
Low = 1
Higher score → Higher priority in execution

🔹 Installation & Running

Step 1: Install Python
Make sure Python is installed on your system.
Step 2: Install Required Library
pip install matplotlib
Step 3: Run the Program
python filename.py

🔹 Output

📋 Task list displayed in GUI
🧠 AI-optimized task order
🥧 Pie chart for priority distribution
📊 Bar graph for time analysis

🔹 Advantages
Improves task management
Provides visual insights
Easy to use interface
Efficient decision-making using AI

🔹 Limitations
Uses basic rule-based AI (not machine learning)
Data is not stored permanently
Limited to small-scale usage

🔹 Future Enhancements
💾 Save/load tasks from file
📅 Add deadlines & urgency
🌐 Web-based version
📊 Dashboard-style embedded charts
🤖 Use machine learning for smarter predictions
🔹 Conclusion

This project demonstrates how Artificial Intelligence can be applied to real-life productivity problems.
By combining AI logic, GUI design, and data visualization, it creates a practical and user-friendly application for task management.
