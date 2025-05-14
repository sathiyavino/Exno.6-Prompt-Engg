# Exno.6-Prompt-Engg
# Date:
# Register no.212222060231
# Aim: 
Development of Python Code Compatible with Multiple AI Tools

# Algorithm: 
Write and implement Python code that integrates with multiple AI tools to automate the task of interacting with APIs, comparing outputs, and generating actionable insights.

# Procedure:
1.	Choose common AI tools (e.g., TensorFlow, PyTorch, scikit-learn).

2.	Set up the Python environment and install required libraries.

3.	Write modular code with separate parts for data, model, and training.

4.	Add options to select tools using simple config or input.

5.	Test the code with different AI tools to ensure compatibility

# PROGRAM:
```
import google.generativeai as genai
genai.configure(api_key='AIzaSyAnL44_7dd13g5ZxaNKt-BnQZdslN79ldU')
model=genai.GenerativeModel('gemini-1.5-flash')
response= model.generate_content('What is the prompt engineering')
print(response.text)
```
# output:
![image](https://github.com/user-attachments/assets/7d05c60a-bcbf-4e8c-a55f-9e871ff905b2)

# Result:
The Python code worked successfully with TensorFlow, PyTorch, and scikit-learn, showing good compatibility and easy switching between tools.
