# Building a Together AI Application with Streamlit


## Objective:
In this assignment, you will create a Python-based application using Together AI and Streamlit. The application will generate Python code based on a user-provided description. By following the provided step-by-step instructions, you will gain hands-on experience with Streamlit Cloud, Together AI, and deploying applications to the web.

https://drlee.io/building-a-python-code-generator-with-codellama-in-streamlit-cloud-4a78886918eb

## Instructions

1. Create a GitHub Repository
- Log in to your GitHub account and create a new repository with the name together-ai-streamlit-app.
- Set the repository visibility to Public or Private (your choice).


2. Create and Add Files   
- app.py
  - Add a new file named app.py to your repository.
  - Copy and paste the Python code from the provided guide into the file.
- requirements.txt
  - Add another file named requirements.txt.
  - Include the following dependencies:
      - Copy code: streamlit together

   
3. Deploy on Streamlit Cloud
- Log in to Streamlit CloudLinks to an external site. using your GitHub account.
- Deploy your app:
    - Click New App.
    - Select your together-ai-streamlit-app repository.
    - Set the branch to main and the main file path to app.py.
- Under the Secrets Management tab, add your Together AI API key:
    - Key: TOGETHER_API_KEY
    - Value: Your actual API key.


4. Test Your Application
- Visit the public URL of your deployed app.
- Enter a description of the Python code or application you want to generate.
- Verify the output Python code generated by Together AI.


5. Example Input/Output
- Input: "Write a Python script to reverse a string."
- Output: Python code that implements a string-reversing function.


6. Submit Your Assignment
- Copy the public URL of your deployed app.
- Submit the URL on Canvas under the assignment submission section.
