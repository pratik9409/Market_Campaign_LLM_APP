# Marketing Tool using Streamlit, Langchain, and OpenAI
## Overview:
This code snippet demonstrates how to use Streamlit, Langchain, and OpenAI's GPT-3.5 model to generate marketing content based on user input. The tool allows users to input text, select an action (e.g., write a sales copy, create a tweet, write a product description), choose an age group (e.g., kid, adult, senior citizen), and set a word limit for the generated content.

## Technologies Used:
<b> Streamlit:</b> Used for creating the web interface and handling user inputs.
<b>Langchain:</b> Specifically, the FewShotPromptTemplate class for generating responses based on examples.
<b>OpenAI GPT-3.5 model:</b> Used for generating text based on the provided prompts.
### How It Works:
1. <b>Input:</b> Users provide a text input, select an action, choose an age group, and set a word limit for the generated content.
2. <b>Prompt Template:</b> A prompt template is constructed based on the user's input, including the selected action, age group, and text input.
3. <b>Model Generation:</b> The OpenAI GPT-3.5 model is used to generate marketing content based on the provided prompt.
4. <b>Output:</b>The generated marketing content is displayed to the user using Streamlit.
## Usage:
1. Install the necessary libraries using pip:

``` bash
pip install -r requirements.txt
```
2. Set up your OpenAI API key as an environment variable (e.g., OPENAI_API_KEY).

3. Run the Streamlit app:

```bash
streamlit run app.py
```
4. Enter the text input, select an action, choose an age group, and set a word limit.

5. Click the "Generate" button to generate the marketing content.

Example Output:

![image](https://github.com/pratik9409/Market_Campaign_LLM_APP/assets/67755812/3f1c3026-ba38-4013-aca4-6f0eaf0a84df)




Notes:
- This code snippet provides a basic implementation of a marketing tool using Streamlit, Langchain, and OpenAI. Further customization and optimization can be done based on specific requirements and use cases.
- Ensure that you have the necessary permissions and credentials to access the OpenAI GPT-3.5 model for generating text.
- Consider adding error handling and validation for user inputs to enhance the user experience.
