# Projects
## Dashboards
### Tableau
#### Fantasy Football Draftboard
This is more than a draftboard, it is a fantasy football draft optimizer where player rankings are based on value above replacement player. We first obtain NFL statistic projections from multiple sources. Then calculate fantasy points and average it to obtain Player Projected Points. We then compare those projections to a replacement player's projected points. A replacement player is defined as the "worst" starter given the league's number of teams and positional requirements settings. For example, a 10 team league with 1 QB starter would mean that for QBs a replacement player would be the 10th highest Player Projected Points as mentioned above(1x10=10). Finally, we summarize these rankings by creating an interactive Tableau dashboard that can be used live on draft day to guide you in making data driven draft decisions. Try it directly from this site my clicking Try Dashboard below!

NOTE: Projected Points are calculated based on Yahoo's standard scoring. Future variations may include the ability to enter custom scoring settings.

<a href="FantasyFootballDraftboard">Try Dashboard</a><br>
<a href="https://public.tableau.com/app/profile/davor.kondic/vizzes">See my Tableau Public Profile</a><br>

## Web Apps
### AI Agents and Chatbots
#### Resume Chatbot

For your convenience and fun, I built a Resume AI so that you can chat with my resume directly. A Gradio web app deployed to HuggingFace Spaces powered by Meta-Llama-3.3-70B-Instruct large language model (LLM) and with careful system prompt engineering is able to answer to user's questions based only on my resume's content. It is a conversational AI so it will remember your conversation as you chat with it. 

<a href="ResumeChatbot">Try App</a><br>
<a href="https://github.com/Dacho688/ResumeChatbot">Source Code on GitHub</a>

![](https://img.shields.io/badge/Meta_Llama-white?logo=meta&logoColor=black) ![](https://img.shields.io/badge/Python-white?logo=Python) ![](https://img.shields.io/badge/PyTorch-white?logo=pytorch) ![](https://img.shields.io/badge/HuggingFace_Hub-white?logo=huggingface) ![](https://img.shields.io/badge/Gradio-white?logo=gradio)

#### Data Analyst AI Agent

A personal Data Analyst Agent built with Meta-Llama-3.1-70B-Instruct LLM and deployed as a Gradio web app to HuggingFace Spaces. Using the ReACT (Reasoning and Action) framework this AI agent thinks, acts, and observes sequentially until the final answer is reached. Using the transformers Python package and their ReactCodeAgent framework, this agent acts and observes with only a Python code interpreter tool. 

1. Upload data as .csv text file.
2. Ask a question or give it a task.
3. Hit RUN!
4. Watch it think and act using Python code and print outputs!
   
<a href="DataAnalyst">Try App</a><br>
<a href="https://github.com/Dacho688/Data_Analyst">Source Code on GitHub</a>

![](https://img.shields.io/badge/Meta_Llama-white?logo=meta&logoColor=black) ![](https://img.shields.io/badge/Python-white?logo=Python) ![](https://img.shields.io/badge/PyTorch-white?logo=pytorch) ![](https://img.shields.io/badge/HuggingFace_Transformers-white?logo=huggingface) ![](https://img.shields.io/badge/Gradio-white?logo=gradio)

#### Image Chatbot
A conversational AI using the open source and SOTA Llava-Next large multimodal model (LMM). With advanced visual reasoning and conversational skills, this AI is capable of summarizing, question answering, and even holding a conversation on any image. Llava-Next is downloaded from Huggingface Hub, loaded to Cuda GPU, and deployed as a Gradio web app on Huggingface's ZeroGPU technology. 

<a href="ImageChatbot">Try App</a><br>
<a href="https://github.com/Dacho688/ImageChatbot">Source Code on GitHub</a>

![](https://img.shields.io/badge/Python-white?logo=Python) ![](https://img.shields.io/badge/PyTorch-white?logo=pytorch) ![](https://img.shields.io/badge/HuggingFace_Transformers-white?logo=huggingface) ![](https://img.shields.io/badge/Gradio-white?logo=gradio)

