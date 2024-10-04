# YOUTUBE Q&A AND SUMMARIZATION APP 📺


This repository hosts an app developed using **Whisper** and **Langchain** that allows the creation of a Q&A assistant and video summarization. The model's maximum context length is 4097 tokens (gpt-3.5-turbo).

The App can be run locally but requires an `OPENAI_API_KEY` in the `.env` file. Feel free to ⭐ and clone this repo 😉

## 👨‍💻 **Tech Stack**


![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![OpenAI](https://img.shields.io/badge/OpenAI-74aa9c?style=for-the-badge&logo=openai&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=Streamlit&logoColor=white)

## 💬 Set Up

 I recommend installing the modules in the following order. The `ffmpeg` module is required for the proper functioning of the application. You can install it using Conda as follows:

```
poety install
```



## 🫵 App Deployment

The app can be used running `streamlit run youtube_llm_app/app.py` in the terminal. There are 2 options on the sidebar, Q&A or Summarize. I recommend using videos no longer than 5 min of speech due to the model tokens' limitations.

The first option allows a Q&A assistant to ask questions about the video.

<p align="center">
    <img src="images/qa.png" />
</p>

The second option allows us to get a summary of the video.

<p align="center">
    <img src="images/summary.png" />
</p>
