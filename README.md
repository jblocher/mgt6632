# Machine Learning in Business (MGT 6632)

## Mod 3, 2024 (Spring)

This repo content draws on several sources - these should be consulted for more information. 
* Data Science for Business by Foster Provost and Tom Fawcett (2016) available from O'Reilly Publishing
* Machine Learning with PyTorch and Scikit-Learn by Sebastian Raschka, Yuxi Liu, Vahid Mirjalili, Dmytro Dzhulgakov by Pakt Publishing. [Github Repo](https://github.com/rasbt/machine-learning-book/tree/main)
* Machine Learning with Python by Sebastian Raschka and Vahid Mirjalili. [Github Repo](https://github.com/rasbt/python-machine-learning-book-3rd-edition)
* Online tutorials on Deep Learning Fundamentals by lightning.ai and Sebastian Rascka. [Tutorial Here](https://lightning.ai/courses/deep-learning-fundamentals/)
* Honestly, I love everything that Sebastian Raschka does, but he can be pretty technical at times. My approach is to simplify and de-math it a bit to make it more accessible. More of these lectures on deep learning are on [his website](https://sebastianraschka.com/blog/2021/dl-course.html)
* I also will use code/work from Week 3 of AI Summer put on by the Data Science Institute in May 2023. I've kept similar naming conventions so you can see what part of that course we duplicate. 

The original authors of AI Summer were Vanderbilt Data Science Institute data scientists:
* Dr. Jesse Spencer-Smith, Chief Data Scientist
* Dr. Charreau Bell, Senior Data Scientist
* Myranda Shirk, Senior Data Scientist
* Umang Chaudhry, Data Scientist
* Dr. Abigail Petulante, DSI Postdoctoral Fellow

Want to see their version of this material?
* [Github Repo](https://github.com/vanderbilt-data-science/ai_summer)
* [YouTube](https://www.youtube.com/playlist?list=PL6KxUvysa-7yV8T4qcoLaDH3ZzUFwYx8u) recordings of Zoom sessions.

## Setup (same as my MGT 6534 course, so if you took that, you are set)

### Generative AI

***ChatGPT Plus from OpenAI*** This is required for the course. Go to [OpenAI](https://openai.com/) to sign up. 

***Open AI API access*** This is required for the course as well. Go to the [OpenAI Platform](https://platform.openai.com/overview) to sign up. You will need something called an *API Key* to access OpenAI via python as well as to do many in-class assignments. There is no charge to sign up, rather this is a "pay per usage" setup, but the cost is very, very low. You may spend less than $1 for the whole class, but you will need to provide a credit card. 

#### Other Generative AI Options

***Bing Chat*** Microsoft opened access to GPT through Bing Chat, which is based on an early version of GPT4 (in Creative Mode only), currently the most advanced AI chat model available to the public. This is the only free GenAI tool I recommend. You’ll need to install the Edge browser (https://www.microsoft.com › edge › download). With the browser running, click on “Chat” to open the chat window next to the browser window. Bing Chat has access to the internet. 

***Claude 2 from Antrhopic*** This is a lesser known but very good model. The primary benefit is a 100K token context window which allows you to upload long articles, many articles, or even entire books into context. Access it at [Poe](www.poe.com). 

***Bard from Google*** This is not currently recommended. 

***GPT-3.5 from OpenAI*** This is the free version from OpenAI and is not recommended. 

### Google Colab

Sign up for a [Google Collaboratory](https://colab.research.google.com/) account. The free account should be sufficient, but you will get more compute (and longer running times) if you sign up for Colab Pro at ~$5/month.

### HuggingFace

Sign up for a [Huggingface](https://huggingface.co) account. Again, the free account should be sufficient. You need to create a HuggingFace account as we will be using the HuggingFace platform for some of the exercises.

## Class Plan

...





## Other Resources

### How to use Generative AI
There are lots of resources out there, but for our context I really like Ethan Mollick's blog *One Useful Thing*. To get you started, try is post on [how to use AI to do stuff](https://www.oneusefulthing.org/p/how-to-use-ai-to-do-stuff-an-opinionated).

### Prompt Engineering paper 
Written by several professors here at VU, this is a great (easy but also in-depth) intro to what we mean by Prompt Engineering. [Link](https://arxiv.org/abs/2302.11382)

### Coursera Course
This is a full course elaborating on the paper above that you can sign up for via Coursera if you want more information. [Link](https://www.coursera.org/learn/prompt-engineering)

### Semester-long course on transformer models, [DS 5690: Transformers in Theory and Practice](https://docs.google.com/document/d/1eKJn3eQU38jsE1ilZL0s-yrsIKcn8iZ7iSmXYxibx78/edit?usp=sharing). 
Graduate students and advanced undergraduates can register by contacting Jesse Spencer-Smith. 

### Python

The following are ~10 minute video chapters on the foundations of Python. Proficiency in Python is not required, but I recommend you familiarize yourself to be able to read and understand Python code when needed. If you prefer to read the information, the [Python course textbook](https://do1.dr-chuck.com/pythonlearn/EN_us/pythonlearn.pdf) is an additional resource. I have listed the most important lessons below, but you are welcome to complete other lessons as well.

I suggest you complete the following sections from FreeCodeCamp.org [Scientific Computing with Python](https://www.freecodecamp.org/learn/scientific-computing-with-python/) course:

* Introduction: Python as a Language (7:48)
* Introduction: Elements of Python (12:46)
* Variables, Expressions, and Statements (9:41)
* Conditional Execution (13:30)
* Python Functions (10:30)
* Loops and Iterations (9:59)
* Python Lists (10:57)

Also, complete the following sections from FreeCodeCamp.org [Data Analysis with Python](https://www.freecodecamp.org/learn/data-analysis-with-python/) course:

* Data Analysis Example A (9:20)
* How to use Jupyter Notebooks Intro (8:47)
* Numpy Operations (5:03)
* Pandas Introduction (8:07)
* Pandas Indexing and Conditional Selection (9:20)
* Pandas DataFrames (10:20)

### Textbooks

-  *Natural Language Processing with Transformers* by Lewis Tunstall, Leandro von Werra and Thomas Wolf. Transformer models for purposes beyond text. Transformers are the underlying architecture behind Generative AI, and are based in Deep Learning. 
-  *Python for Data Analysis* by Wes McKinney: More on how to use Python.
-  *Think Stats* by Allen Downey: More on thinking “statistically” and how to analyze data.
-  *Python for Finance* by Yves Hilpisch: Specific applications to Finance.
-  *Web Scraping with Python* by Ryan Mitchell: More detail on scraping web pages

As a Vanderbilt University student, you can access these books (and any book by O’Reilly) free by logging into O'Reilly Media using your Vanderbilt VUNetID. Vanderbilt licenses all content from O’Reilly. Link [here](http://www.library.vanderbilt.edu/eres?id=1676). 




