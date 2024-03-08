#  AI Engineer | Data Scientist

#### Technical Skills: Python, SQL, AWS, GCP, Snowflake, Docker.

## Education							       		
- M.S., Data Analytics Intelligence	| Universidad de los Andes (_Aug 2024_)	 			        		
- B.S., Economics | Universidad de los Andes (_Nov 2020_)

## Projects
### [Deploying Mistral7B for Text-to-SQL Tasks](https://github.com/jjovalle99/7b-SQLMasterApp)
**Relevant Technologies:** *AWS SageMaker, LLamaIndex, LangChain, Streamlit*

[Application Demo](http://ec2-3-91-221-46.compute-1.amazonaws.com:7860/)

Deployed Mistral7B into a practical application, leading to the creation of 7BSQL Master. This demo app, developed using AWS SageMaker, LLamaIndex, and Streamlit, showcases the ability to seamlessly transform natural language questions into SQL queries. Hosted on AWS, 7BSQL Master provides an intuitive platform for users to leverage the sophisticated NL2SQL capabilities of Mistral7B, demonstrating the practical application and deployment of fine-tuned AI models in a user-friendly interface.

![results1](/assets/7bsqlmaster.gif)

### [Finetuning Large Language Models for Text-to-SQL Conversion](https://github.com/jjovalle99/7b-SQLMaster-FineTune)
**Relevant Technologies:** *HuggingFace, LangChain, LangSmith, Weights&Biases*

Fine-tuned four large language models—Gemma, Mistral, DeciLM, and LLama2, in their 7 billion parameters version, for the task of generating SQL queries from natural language. This project aimed to enable these models to accurately interpret user intent and output corresponding SQL queries. The fine-tuning process employed LoRA (Low-Rank Adaptation) for efficient model parameter tuning. Performance monitoring and evaluation were facilitated by Weights & Biases and LangSmith.

![results2](/assets/model_eval.png)


### [Deploying a Retrieval-Augmented Generation Application](https://github.com/jjovalle99/DocuQuery2)
**Relevant Technologies:** *LangChain, Pinecone, Weights&Biases, Chainlit*

[Application Demo](https://huggingface.co/spaces/jjovalle99/DocuQuery2)

Developed a Retrieval-Augmented Generation (RAG) application that enables users to interact with PDFs and text files, facilitating conversational 'chatting' with documents. This application leverages Pinecone for its vector storage capabilities, ensuring efficient information retrieval that significantly enhances user experience. The app's workflow is orchestrated using LangChain, allowing for seamless integration of various AI components. To ensure continuous improvement and a deeper understanding of user interactions, Weights and Biases was employed for the tracking of model interactions and performance metrics. The user interface, crafted with Chainlit, provides an intuitive and easy environment for users to effortlessly navigate and converse with their documents

![results3](/assets/docuquery.gif)

### [Extracting Business Insights from Amazon Reviews Using NLP](https://github.com/jjovalle99/AmazonNLP)
**Relevant Technologies:** *HuggingFace, BigQuery, HDBSCAN, UMAP*

Developed a comprehensive NLP project focused on extracting actionable business insights from Amazon reviews of video games. Initially, the sentiment of each review was analyzed to identify negative feedback, utilizing a BERT based model. Following this, an embedding model was applied to transform the reviews into embeddings, facilitating the nuanced understanding of customer opinions beyond mere positive or negative sentiment. Leveraging UMAP for dimensionality reduction and HDBSCAN for clustering, the project effectively grouped reviews into distinct clusters, enabling a focused analysis on specific aspects of customer dissatisfaction. 

![results4](/assets/clusters.png)

## Work Experience
**Data Scientist @ Toyota Financial Services (_June 2022 - Present_)**
- Uncovered and corrected missing step in production data pipeline which impacted over 70% of active accounts
- Redeveloped loan originations model which resulted in 50% improvement in model performance and saving 1 million dollars in potential losses

**Data Science Consultant @ Shawhin Talebi Ventures LLC (_December 2020 - Present_)**
- Conducted data collection, processing, and analysis for novel study evaluating the impact of over 300 biometrics variables on human performance in hyper-realistic, live-fire training scenarios
- Applied unsupervised deep learning approaches to longitudinal ICU data to discover novel sepsis sub-phenotypes