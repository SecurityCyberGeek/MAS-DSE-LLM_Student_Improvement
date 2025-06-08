# MAS DSE Cohort 10 - Using LLMs to Improve Student Outcomes

#### This project is to determine how many students use the AI tutor and if those students do better than the students who used Traditional Instruction. The following explains how to use this repository for any course. This repository is designed to help cleanup the data from any course (UC San Diego's MATH 3B is used here), then do a comparison on the data to understand both groups (AI and Non-AI), and finish with the tools to make the visualizations. These visualizations are the main point of the project to show the comparisons of the data.

MAS-DSE-LLM_Student_Improvement - Tim Harmon & Clinton Anderson  
  1. Final Report - Using LLMs to Improve Student Outcomes.pdf  
  2. google colab/  
     Math_3B_Cleaning.ipynb  
     Math_3B_Comparisons.ipynb    
  3. excel data/  
     Anonymized Math 3B Tutor Conversations Week 1-4.xlsx  
     Math 3B Anonymized Gradebook.xlsx  
  4. csv data/  
     capstone_ai.csv 
     capstone_none.csv  
     Grades-3B-May12-SP25.csv  
     Math 3B Anonimized Gradebook - Sheet2.csv  
     capstone_ai_chatTotal.csv  
     capstone_conversations_length.csv  
     capstone_conversations_studentsideon.csv  
     capstone_key_categories.csv  
     capstone_key_counts.csv  
     capstone_no_ai_chatTotal.csv  
     capstone_raw_conversations.csv  
     capstone_rawdata_questionanswer.csv  
  6. tableau/  
     Math 3B Real Data Visualizations.twbx	

To run, ensure that the all CSVs are accessibly by the notebooks. Google Colab was used, but a developer can modify the path to run in Jupyter Lab. Run Math 3B Cleaning to (re)create the CSVs "ai_chatTotal" and "no_ai_chatTotal". Run Math 3B Comparisons to view data exploration and basic graphs within the notebook (uses Plotyly and Seaborn)

The Tableau visualization are included with 'extracted' files (i.e., .twbx can be run stand-alone). Add ai_chatTotal and no_ai_chatTotal, along with remaning "capstone" CSVs in a licensed Tableau Desktop to modify these graphs or make additional ones. 

### **DISCLAIMER**
UC San Diego and Vocareum will not be held liable if this information is used for unethical and/or illegal purposes. Student Personal Identifiable Information (PII) should always be anonymized to ensure it is in compliance with Family Educational Rights and Privacy Act (FERPA) and actual student data should never be used to gain personal profit or to deny any student their rights. Safeguards are in place to ensure the student PII is anonymized in the data before it gets processed for data cleaning and comparison. The person, or people, who use this information for unethical and illegal purposes will be prosecuted to the fullest extent of the law.
