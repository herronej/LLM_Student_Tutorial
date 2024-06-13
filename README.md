<img src="https://github.com/your-username/your-repository/blob/main/path-to-image.png](https://raw.githubusercontent.com/herronej/LLM_Student_Tutorial/main/ollama/example_files/ce2f9b8c-0f77-4832-bc28-72c849165fc2.webp" alt="Generative Natural Language Processing" width="300">

# Generative Natural Language Processing Primer: Riding the Journey to Large Language Models
## An AI for Science Tutorial for Summer Students Organized by ORNL’s AI Initiative
## Presented by Tirthankar Ghosal, Vanessa Lama, and Emily Herron

### Abstract:
Generative AI, particularly Large Language Models (LLMs), has transformed various domains, including industry, government, scientific research, and academia. However, the impressive capabilities of modern-day LLMs are deeply rooted in Natural Language Processing (NLP) fundamentals. In this comprehensive tutorial, we will explore the evolution of LLMs and uncover the sophisticated mechanisms that power this cutting-edge technology. We will discuss the importance of safety and trustworthiness in LLMs and how to utilize these models responsibly for research and application development. Additionally, attendees will participate in hands-on exercises, including text pre-processing for fine-tuning or training LLMs, running LLMs locally on laptops, a live demonstration of a Retrieval Augmented Generation application, and experience how we can use LLMs as research and programming assistants. We would also explore useful resources for anyone interested in NLP and LLMs. Please join us for a dense and insightful journey into the world of LLMs and gain practical skills to harness their potential effectively. 


### Ollama Tutorial
- Ollama is an open-source platform that offers a user interface for installing and running popular open source LLMs locally​
- To download and install Ollama, follow instructions on Ollama's [website](https://ollama.com/)
#### Installing Models
- View all models [here](https://ollama.com/library) 
- Select model and install using command `ollama run <model_name>​` in your terminal window
#### Creating a Custom model 
- List available models: `ollama list`
- Open and edit model file to customize: ​`vim ollama/modelfile_astrophysicist​` 
- Create model from model file: ​`ollama create astrophysicist -f ollama/modelfile_astrophysicist​`
- Run model file:​ `ollama run astrophysicist​`
#### Test Models With Example Prompts
- "What is gravity?"​
- "Describe this image: ollama/example_files/attention.png"​
- "Summarize this paper: ollama/example_files/KAN.pdf"​
- "Write a Python function to find the n-th Fibonacci number."​
​

