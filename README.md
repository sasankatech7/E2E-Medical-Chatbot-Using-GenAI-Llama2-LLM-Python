# E2E-Medical-Chatbot-Using-GenAI-Llama2-LLM-Python

# Steps tu run the project

```bash
1. Create new environment
conda create -n medical-chatbot python=3.11.7 -y
environment location: C:\Installation\anaconda3\envs\medical-chatbot
```

```bash
2. Activate newly created environment -  medical-chatbot
conda activate medical-chatbot
```

```bash
3. Install Libraries
    i.      ctransformers==0.2.27 - https://pypi.org/project/transformers/#history   
    ii.     sentence-transformers=4.1.0
    iii.    pinecone-client
    iv.     langchain==0.3.24
    v.      flask
```

```bash
4. Install all Libraries inside requirements.txt
pip install -r requirements.txt
```

```bash
5. Download Llama2 Model
llama-2-7b-chat.ggmlv3.q4_1.bin
https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML/tree/main
```