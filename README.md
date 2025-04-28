> **FinInsight:** **AI-Powered** **Financial** **Analysis** **Platform**

**UniversityofMichigan-Dearborn\|** **CIS-5570**
**–IntroductiontoBigData** **Instructor:**Dr.MohamedAbouelenien

**TeamMembers:**OweshChaiwala,Prakruthi
NeelakantanahallyMayanna,NikhilReddy Kandadi,Yogendra SaiPavanNalam,Sai
DeepakChandra

**Project** **Overview**

**FinInsight**isa scalable,modularplatformthatcombines **Big** **Data**
**pipelines**with**AI** **models**to perform real-timefinancial
analysis.

GivenlargedatasetsofSECfilings,newsarticles,andRedditfinancediscussions,theplatform:

> • Cleansandprocessesdiversefinancial textsusing **PySpark**
>
> • Enrichescontentwith**Spark**
> **NLP**(NamedEntityRecognition&SentimentAnalysis)
>
> • Embedsdocumentsusing**Sentence** **Transformers**
>
> • Retrievesrelevantinformationusing**FAISS** **vector** **search**
>
> • Generateshuman-likeanswersusing**FLAN-T5**witha
> Retrieval-AugmentedGeneration (RAG) approach

**Goal:**

Enableuserstoquerymassivefinancial
datasetsandgetcontext-grounded,explainable answers**inseconds**.

**System** **Architecture**

**Tech** **Stack**

> • **ApacheSpark**(PySpark) —Distributeddataprocessing
>
> • **SparkNLP**—Financial entityrecognitionandsentimentextraction
>
> • **Sentence** **Transformers**—Textembedding(MiniLM-L6-v2 model)
>
> • **FAISS**—Densevector similaritysearch
>
> • **LangChain**—Promptconstructionandorchestration
>
> • **FLAN-T5** **Base**—Largelanguagemodel forquestionanswering
>
> • **GoogleColab**—Developmentenvironment
>
> **Project** **Structure**
>
> bash
>
> CopyEdit
>
> FinInsight/
>
> ├──notebooks/
>
> │ └── AI_Powered_Financial_Analysis_FILE\_(2).ipynb
>
> ├──data/
>
> │ ├──CNBC_financial_articles_2.json
>
> │ ├──CNBC_financial_news_1.json
>
> │ └── reddit_posts.json
>
> ├──diagrams/
>
> │ ├──system_architecture.png
>
> │ ├──pyspark_ingestion_flow.png
>
> │ ├──rag_pipeline_diagram.png
>
> ├──screenshots/
>
> │ └── (retrieval examples,queryresponses)
>
> ├──README.md
>
> └── requirements.txt
>
> **How** **toRun**
>
> **1.** **Clonetherepository:**

||
||
||
||
||
||

> **2.** **Installdependencies:**

||
||
||
||
||

> **3.** **Launch** **theJupyter** **Notebook:**

||
||
||
||
||

> **4.** **Follow** **thecodecells:**

||
||
||
||
||
||
||

> **Sample** **Results**

||
||
||
||
||

> **Evaluation:**
>
> • **Top-3** **DocumentRelevance:**~87%
>
> • **Answer** **Clarity:**High
>
> • **Grounding(ContextMatch):**Medium(~0.5)
>
> **Future** **Work**
>
> • Real-timeingestionvia Kafka orSparkStreaming
>
> • Fine-tuningFLAN-T5 onfinancial datasets
>
> • Front-endwebappforpublic financial Q&A
>
> • Expandtoearningscalls,SECexhibits,andinvestorreports

**References**

> • Spark NLP Documentation
>
> • [<u>FAISS byFacebook
> Research</u>](https://github.com/facebookresearch/faiss)
>
> • [<u>SentenceTransformers</u>](https://www.sbert.net/)
>
> • LangChainFramework
>
> • FLAN-T5 onHuggingFace
>
> • [<u>FNSPID Dataset(arXiv)</u>](https://arxiv.org/abs/2402.06698)
