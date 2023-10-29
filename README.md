# Retrieval Augmented Generation (RAG) for chatbots
RAG enabled Chatbots using [LangChain](https://www.langchain.com) and [Databutton](https://databutton.com/login?utm_source=github&utm_medium=avra&utm_article=rag)
![](https://github.com/avrabyt/RAG-Chatbot/blob/main/thumbnail.webp)

- For the front-end : `app.py`
- PDF parsing and indexing : `brain.py`
- API keys are maintained over databutton secret management
- Indexed are stored over session state 

Oversimplified explaination : (**Retrieval**) Fetch the top N similar contexts via similarity search from the indexed PDF files -> concatanate those to the prompt (**Prompt Augumentation**) -> Pass it to the LLM -> which further generates response (**Generation**) like any LLM does. **More in the blog!**

Blog Post - [Here](https://medium.com/databutton/why-your-next-ai-product-needs-rag-implemented-in-it-9ee22f9770c8)

To get started quickly, you can use the “Chat with PDF” [template](https://databutton.com/new?templateId=pt-x2Rh7dEYwIuCxXaR) within Databutton 🚀

> Alternatively, you can use [Streamlit](https://streamlit.io) to build and deploy! In that case few changes such as `st.secrets` needs to be implemented!

# Similar projects

#### [Building a Simple Chatbot using ChatGPTAPI & Databutton with memory 🧠](https://github.com/avrabyt/MemoryBot)

>Memory implementation can also be an interesting feature in this current RAG enabled Chatbot.

Repo - [MemoryBot](https://github.com/avrabyt/MemoryBot)

The live demo app is hosted over [here](https://next.databutton.com/v/lgzxq112/Memory_Bot)

Blog - [here](https://medium.com/@avra42/how-to-build-a-chatbot-with-chatgpt-api-and-a-conversational-memory-in-python-8d856cda4542) 

Video - [here](https://youtu.be/cHjlperESbg)

#### [PDF Chatbot with Memory](https://github.com/avrabyt/PersonalMemoryBot)
> Similar to Chat with PDF approach, with enabled memory. 

Demo App - [here](https://next.databutton.com/v/lgzxq112/Personalised_Memory_Bot)

Video - [here](https://youtu.be/daMNGGPJkEE)

Blog - [here](https://medium.com/@avra42/how-to-build-a-personalized-pdf-chat-bot-with-conversational-memory-965280c160f8)

![](https://github.com/avrabyt/RAG-Chatbot/blob/main/compare%20medium.gif)













