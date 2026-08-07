---
hide:
  - toc
  - nav
---

The [National Humanities and Social Sciences Team](https://docs.alliancecan.ca/wiki/Humanities_and_Social_Sciences) at the Digital Research Alliance of Canada supports and advocates for the Canadian humanities and social sciences research community. As part of this mission, we are launching a new training series beginning in September 2026. 

The workshops in this series are designed to take researchers and students in the humanities and social sciences through the different stages of the research process, introducing them to digital tools and research approaches relevant to each stage. The training series includes workshops on digital longevity, cloud computing, programming in R and python, data cleaning and analysis software, and data repositories. Most workshops are open to participants of all skill levels; where there are prerequisites, these will be listed in the workshop description. 

All workshops are offered online and registration is free. The workshops are aimed at folks in the humanities and social sciences, but are open to anyone interested in attending. 

## Upcoming workshops
Other workshops may be added to the series over time - check back regularly to see! 
[](){ #page-top }

| Workshop | Date |
|----------|------------|
|[Introduction to the Alliance & ARC for HSS](#intro-en)|September 22, 2026|
|[Introduction à l'Alliance & CIP pour les SHS](#intro-fr)| September 24, 2026|
|[Planning your Endings-Compliant Digital Project](#endings-en)|October 6, 2026|
|[Introduction to the cloud for HSS](#cloud-en)|November 3, 2026|
|[Ollama for OCR, transcription and data extraction](#ocr-en)|November 17, 2026|
|[Introduction to OpenRefine](#openrefine-en)|November 24, 2026|
|[Testing AI for Social Science and Humanities Research Using Chainforge](#ai-en)|December 3, 2026|
|[Introduction to R and RStudio](#r-en)|January 12, 2027|
|[Getting started in Python](#python-en)|January 27, 2027|
|[Using Python for natural language processing (NLP)](#nlp-en)|March 3, 2027|
|[How to deposit: Picking a data repository and preparing your data](#rdm-en)|March 17, 2027|

## Workshop descriptions

[](){ #intro-en }
### Introduction to the Alliance & ARC for HSS

- Date: **September 22nd, 2026** at 9am PT | 10am MT | 12pm ET | 2pm AT
- Duration: 1 hour
- Language of instruction: English

This workshop will introduce participants to the [Digital Research Alliance of Canada](https://www.alliancecan.ca/en) (the Alliance). The Alliance supports Canadian researchers in the areas of advanced research computing, research data management and research software. The Alliance also provides access to cloud computing and high-performance computing. Participants will be guided through the process of accessing these resources, and of getting support when using them. Throughout the workshop, participants will learn why and how ARC is useful in the humanities and social sciences. 

Instructor: [Maria Sigridur Finnsdottir](https://mariasfinnsdottir.ca/) is the Humanities and Social Sciences Specialist with the Digital Research Services team at the University of Alberta. She holds a PhD in Sociology awarded from the University of Toronto in 2024. She is also the chair of the national HSS team at the Digital Research Alliance of Canada.   

[Back to the schedule](#page-top)

[](){ #intro-fr }
### Introduction à l'Alliance & CIP pour les SHS

- Date: **September 24, 2026** at 9am PT | 10am MT | 12pm ET | 2pm AT
- Duration: 1 hour
- Language of instruction: French

This workshop will introduce participants to the [Digital Research Alliance of Canada](https://www.alliancecan.ca/en) (the Alliance). The Alliance supports Canadian researchers in the areas of advanced research computing, research data management and research software. The Alliance also provides access to cloud computing and high-performance computing. Participants will be guided through the process of accessing these resources, and of getting support when using them. Throughout the workshop, participants will learn why and how ARC is useful in the humanities and social sciences. 

Instructors: TBD

[Back to the schedule](#page-top)

[](){ #endings-en }
### The End is Where We Start From: Planning your Endings-Compliant Digital Project

- Date: **October 6, 2026** at 9am PT | 10am MT | 12pm ET | 2pm AT
- Duration: 1 hour and 30 minutes
- Language of instruction: English

To give our projects the best shot at surviving long-term, we need to think about long-term sustainability and preservation from the very beginning of our digital projects. This workshop covers the principles established by the Endings Projects for beginning, releasing, and archiving your digital project in Endings-compliant ways.

Instructor: **Janelle Jenstad**, PhD FRSC, is Professor of English and Academic Director of the Humanities Computing and Media Centre at the University of Victoria. She is a founding member of the [Endings Project](endings.uvic.ca), and directs The Map of Early Modern London (MoEML) and Linked Early Modern Drama Online (LEMDO). With Jennifer Roberts-Smith and MB Kaethler, she co-edited Shakespeare’s Language in Digital Media (Routledge). Her essays and book chapters have appeared in Shakespeare Bulletin, Elizabethan Theatre, EMLS, JMEMS, DHQ, Digital Studies, Scholarly Editing, and other venues.

[Back to the schedule](#page-top)

[](){ #cloud-en }
### Introduction to cloud computing for HSS

- Date: **November 3, 2026** at 9am PT | 10am MT | 12pm ET | 2pm AT
- Duration: 1 hour and 30 minutes
- Language of instruction: English

This introductory workshop explores how cloud computing can support research projects. Participants will be introduced to the fundamentals of cloud computing and be given the tools for determining  when cloud computing is the right choice over high-performance computing (HPC). The workshop will provide an overview of the cloud services offered by the Digital Research Alliance of Canada, including the available cloud sites, the process of getting a cloud project, and the storage options and types of cloud projects available. The workshop will also discuss common research use cases, practical considerations for getting started and conclude with a live demonstration of launching a cloud virtual machine and hosting a basic website.

Instructor: **Srivathsan Shanmuganathan** is a Cloud Analyst with the Digital Research Services team at the University of Alberta. Srivathsan works with researchers to identify and design cloud computing solutions that support their research needs, including helping researchers choose appropriate cloud technologies and developing cloud architectures using platforms such as OpenStack, Google Cloud Platform (GCP) and Amazon Web Services (AWS).

[Back to the schedule](#page-top)

[](){#ocr-en}
### Ollama for OCR, transcription and data extraction

- Date: **November 17, 2026** at 10am PT | 11am MT | 1pm ET | 3pm AT
- Duration: 1 hour
- Language of instruction: English

This workshop will introduce the use of the Ollama application to extract text and structured data from images and sound recordings. It will cover installation and operation of Ollama, and will provide worked examples which can be explored in real time. Ollama provides a chat interface for familiar chat interactions, and also a network API which allows programmatic access to its service, using scripts in various programming languages (the examples will use Python). Ollama is free and open source, and can be installed on Windows, Mac and Linux machines. 

It uses free downloadable LLMs which are useful for a variety of tasks such as OCR, speech transcription, or even deriving structured data such as CSV or JSON. With a good GPU and the use of Python scripts it is possible to automate these tasks to handle large sets of page images. The quality depends on the size of the model, which in turn depends on the hardware. The best results come when running on a machine with an NVIDIA GPU or a Mac with integrated memory; but even on a simpler system it can be used for private investigation of the capabilities of LLMs for various tasks.

The workshop will demonstrate three tasks: OCR of a handwritten text, transcription of a voice recording, and extraction of CSV data from a structured printed document. The examples will use the desktop application and Python scripts. It will familiarize you with the basic methods of applying LLMs to these research problems. The processes can be transferred to paid online AI services, but for most research purposes, output from a local LLM running on a reasonably capable workstation will be of equal quality.

Instructor: [Peter Binkley](https://profile.hcommons.org/members/pbinkley/) is a librarian with the U of A Library, where he offers workshops and consultations to support researchers with problems and methods of digital scholarship. He has worked in digitization, digital librarianship and digital preservation since the early years of this century. His academic background is in textual studies in the Latin Middle Ages, and he has a Ph.D. in Medieval Studies. His research is now mostly devoted to the 20th century history of pre-digital research technologies such as microfilm.

[Back to the schedule](#page-top)

[](){ #openrefine-en }
### Introduction to OpenRefine

- Date: **November 24, 2026** at 9am PT | 10am MT | 12pm ET | 2pm AT
- Duration: 2 hours
- Language of instruction: English

This session will introduce participants to OpenRefine, a powerful, free and open source tool to work with large datasets. We will quickly work through how to use OpenRefine to effectively clean and format tabular data while automatically tracking any changes. This session is suitable for beginners with no prior knowledge of OpenRefine. There are no prerequisite coding skills. While the examples and data used will be aimed at the Humanities and Social Sciences community, the session is open to anyone and everyone interested in learning about OpenRefine. View the workshop materials [here](https://mariasfinnsdottir.ca/openrefine_fall2025/). 

Instructor: [Maria Sigridur Finnsdottir](https://mariasfinnsdottir.ca/) is the Humanities and Social Sciences Specialist with the Digital Research Services team at the University of Alberta. She holds a PhD in Sociology awarded from the University of Toronto in 2024.  She is also the chair of the National Humanities and Social Sciences Team at the Digital Research Alliance of Canada. 

[Back to the schedule](#page-top)

[](){ #ai-en }
### Testing AI for Social Science and Humanities Research Using Chainforge

- Date: **December 3, 2026*** at 9am PT | 10am MT | 12pm ET | 2pm AT
- Duration: 2 hours
- Language of instruction: English

If you want to use Large Language Models for research you will want to test different combinations of evidence, prompts, and models. Chainforge is a free in-browser visual programming environment that lets you lay out flows that try variations of evidence, prompts, and models. In this workshop we will show you how to use Chainforge to create flows that fit your research needs. We will also survey some common models for flows in the Social Science and Humanities.

Instructor: **Dr. Geoffrey Martin Rockwell** is a Professor of Philosophy and Digital Humanities at the University of Alberta. He holds a Canada CIFAR AI Chair and is a Fellow at the Alberta Machine Intelligence Institute. He has a Ph.D. in Philosophy from the University of Toronto and has published on subjects such as artificial intelligence and ethics, philosophical dialogue, textual visualization and analysis, digital humanities, instructional technology, computer games and multimedia. His books include Defining Dialogue: From Socrates to the Internet (Humanity Books, 2003) and Hermeneutica, co-authored with Stéfan Sinclair (MIT Press, 2016). Hermeneutica is part of a hybrid text and tool project with Voyant Tools (voyant-tools.org), an award-winning suite of analytical tools. He recently co-edited Right Research: Modelling Sustainable Research Practices in the Anthropocene (Open Book Publishers, 2021) and On Making in the Digital Humanities (UCL Press, 2023).

[Back to the schedule](#page-top)

[](){ #r-en }
### Introduction to R and RStudio

- Date: **January 12, 2027** at 9am PT | 10am MT | 12pm ET | 2pm AT
- Duration: 3 hours
- Language of instruction: English

Welcome to this workshop on R and R studio! In this session, participants will learn the basics of coding in R, and will become familiar with using RStudio. We will cover creating objects, importing and working with data, using the basic libraries, and performing simple operations. This session is suitable for beginners with no prior knowledge of R. There are no prerequisite coding skills. 

While the examples and data used will be aimed at the Humanities and Social Sciences community, the session is open to anyone and everyone interested in learning about R. You can view the materials [here](https://mariasfinnsdottir.ca/intro_r_fall2025/).

Instructor: [Maria Sigridur Finnsdottir](https://mariasfinnsdottir.ca/) is the Humanities and Social Sciences Specialist with the Digital Research Services team at the University of Alberta. She holds a PhD in Sociology awarded from the University of Toronto in 2024.  She is also the chair of the National Humanities and Social Sciences Team at the Digital Research Alliance of Canada. 

[Back to the schedule](#page-top)

[](){ #python-en }
### Getting started in Python: An introductory course to programming in Python using MoMA datasets as an example

- Date: **January 27, 2027** at 9am PT | 10am MT | 12pm ET | 2pm AT
- Duration: 3 hours
- Language of instruction: English

Python has been one of the most popular programming languages for the past 20 years. Today it is a key language for data analysis in a huge number of fields, including many in the social sciences and humanities. 

This introductory workshop will walk you through the basics of programming in Python. You will be introduced to the main language features of Python, including: variables and data types, conditionals, lists, for/while loops, list comprehensions, and dictionaries. You will also learn how to write your own functions, and how to work with and plot tabular data. The workshop will give you lots of opportunities for hands-on practice; instead of covering these topics in a dry and abstract fashion, we will play with datasets from the Museum of Modern Art and discuss concepts as we go.

Instructor: **Marie-Hélène Burle** is an evolutionary and behavioural biologist by training, a Software/Data Carpentry instructor, and an open source advocate. She develops and delivers high-performance computing and machine learning training for researchers at Canadian universities on behalf of [Simon Fraser University](https://www.rcg.sfu.ca/) and the [Digital Research Alliance of Canada](https://alliancecan.ca/).

[Back to the schedule](#page-top)

[](){ #nlp-en }
### Using Python for natural language processing (NLP)

- Date: **March 3, 2027** at 9am PT | 10am MT | 12pm ET | 2pm AT
- Duration: 3 hours
- Language of instruction: English

Instructor: **Marie-Hélène Burle** is an evolutionary and behavioural biologist by training, a Software/Data Carpentry instructor, and an open source advocate. She develops and delivers high-performance computing and machine learning training for researchers at Canadian universities on behalf of [Simon Fraser University](https://www.rcg.sfu.ca/) and the [Digital Research Alliance of Canada](https://alliancecan.ca/).

[Back to the schedule](#page-top)

[](){ #rdm-en }
### How to deposit: Picking a data repository and preparing your data

- Date: **March 16, 2027** at 9am PT | 10am MT | 12pm ET | 2pm AT
- Duration: 1 hour
- Language of instruction: English

Data deposit is an important part of the FAIR Principles and a crucial aspect of the research lifecycle, especially as it is becoming a requirement for more and more funders and publishers. This workshop will provide guidance on how to find an appropriate repository and how to prepare your data for deposit. It will also highlight Canada's national generalist repository, the Federated Research Data Repository.

Instructor: **Laura Gerlitz** is a graduate of the University of Alberta with a Masters in Library and Information Science and a Masters of Arts in Digital Humanities, and is currently a Metadata Analyst at the Digital Research Alliance of Canada. Previously, she worked with the Federated Research Data Repository as a Curation Officer, and at the Bank of Canada as a Metadata Librarian. She is involved in the Canadian RDM landscape as a member of the National HSS Team, the Discovery and Metadata Expert Group and the Curation Expert Group.

[Back to the schedule](#page-top)
