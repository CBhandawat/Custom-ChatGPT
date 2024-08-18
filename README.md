# Custom-ChatGPT

Built a ChatGPT-style assistant using Python, Streamlit and Langchain. One can ask questions to it just like they do with ChatGPT.

# Getting Started
1. Prerequisites:
  a. 3.11 ≤ Python < 3.12.5 with Conda <br/>
  b. [OpenAI API Key](https://auth.openai.com/authorize?issuer=auth0.openai.com&client_id=DRivsnm2Mu42T3KOpqdtwB3NYviHYzwD&audience=https%3A%2F%2Fapi.openai.com%2Fv1&redirect_uri=https%3A%2F%2Fplatform.openai.com%2Fauth%2Fcallback&device_id=89fec6e2-ceef-4aa9-9a00-c861166971f4&screen_hint=signup&max_age=0&scope=openid+profile+email+offline_access&response_type=code&response_mode=query&state=Q18waFZoY2owbTJ0NUgybnE3MkdUM0NzQW8wTnkyQzYzOGpyYldDZFE3MQ%3D%3D&nonce=VG1sSUNaTU4ydVcxd0c2Vm52c084RmlSbjlVVVRmWEFYMlhFWmN2ajAxQg%3D%3D&code_challenge=7q-RHFsluPgm1sUtF7_sMyoItqfd__7wnDYs6d1n4gY&code_challenge_method=S256&auth0Client=eyJuYW1lIjoiYXV0aDAtc3BhLWpzIiwidmVyc2lvbiI6IjEuMjEuMCJ9&flow=control) <br/>

  2. Clone the repository
    ```
    git clone https://github.com/CBhandawat/Custom-ChatGPT.git

    cd Custom-ChatGPT
    ```

4. Setup
   Create Virtual Environment:
     ```
     python -m venv venv
     ```

   Activate:
     ```
     venv\Scripts\activate
     ```

   Install all requirements:
     ```
     pip install -r requirements.txt
     ```
5. Change .env file
    Enter your own [OPENAI API KEY](https://auth.openai.com/authorize?issuer=auth0.openai.com&client_id=DRivsnm2Mu42T3KOpqdtwB3NYviHYzwD&audience=https%3A%2F%2Fapi.openai.com%2Fv1&redirect_uri=https%3A%2F%2Fplatform.openai.com%2Fauth%2Fcallback&device_id=89fec6e2-ceef-4aa9-9a00-c861166971f4&screen_hint=signup&max_age=0&scope=openid+profile+email+offline_access&response_type=code&response_mode=query&state=Q18waFZoY2owbTJ0NUgybnE3MkdUM0NzQW8wTnkyQzYzOGpyYldDZFE3MQ%3D%3D&nonce=VG1sSUNaTU4ydVcxd0c2Vm52c084RmlSbjlVVVRmWEFYMlhFWmN2ajAxQg%3D%3D&code_challenge=7q-RHFsluPgm1sUtF7_sMyoItqfd__7wnDYs6d1n4gY&code_challenge_method=S256&auth0Client=eyJuYW1lIjoiYXV0aDAtc3BhLWpzIiwidmVyc2lvbiI6IjEuMjEuMCJ9&flow=control)

6. Run
   ```
   streamlit run streamlit_custon_chatgpt.py
   ```
It will open your browser and from there you can enter your OPENAI API KEY and get started.

# Acknowledgement
Special thanks to [LangChain](https://github.com/langchain-ai/langchain), [Streamlit](https://github.com/streamlit/streamlit) for their invaluable contributions to the open source community. 
