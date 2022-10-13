![image](https://user-images.githubusercontent.com/64021988/195591355-f1ff7dd9-7762-42ce-a8e4-9f0b7bb9f7c1.png)


# Whisper in combination with GPT-3 and Streamlit 

upload a audio file to generate a transcript and then use GPT-3 to classify the transcripts sentiment.
## Installation:
* Simply run the command ***pip install -r requirements.txt*** to install the necessary dependencies.

## Usage:
1. Head over to [this link](https://github.com/openai/whisper) and follow the steps to get a comprehensive overview of the architecture of OpenAI's whisper models. 
2. Simply run the command: 
```
streamlit run app.py
```
3. Navigate to http://localhost:8501 in your web-browser.
4. By default, streamlit allows us to upload files of **max. 200MB**. If you want to have more size for uploading audio files, execute the command :
```
streamlit run app.py --server.maxUploadSize=1028
```

## How to start from here?:

Create a .env file in the root of the project and add your OpenAI GPT3 Key like this: OPENAI_API_KEY="sk-4xxxxxxxxxxxxxxxxxxxxxxxxxxxxxx5"

Go to [this](https://github.com/lablab-ai/whisper-gpt3-streamlit/blob/main/app.py#L104) line in app.py. Here you can modify the prompt to your needs. You can use the OpenAI Playground to test these first [here](https://beta.openai.com/playground?lang=python)


---

[![Artificial Intelligence Hackathons, tutorials and Boilerplates](https://storage.googleapis.com/lablab-static-eu/images/github/lablab-banner.jpg)](https://lablab.ai)


## Join the LabLab Discord


![Discord Banner 1](https://discordapp.com/api/guilds/877056448956346408/widget.png?style=banner1)  
On lablab discord, we discuss this repo and many other topics related to artificial intelligence! Checkout upcoming [Artificial Intelligence Hackathons](https://lablab.ai) Event


[![Acclerating innovation through acceleration](https://storage.googleapis.com/lablab-static-eu/images/github/nn-group-loggos.jpg)](https://newnative.ai)
