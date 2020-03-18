---
# Course title, summary, and position.
linktitle: IJCAI2020 Tutorial on Multimodal Learning in K-12 Education - Promise, Progress and Challenges, Yokohama, Japan
summary: Organized by Zitao Liu (TAL Education Group), Songfan Yang (TAL Education Group), Jiliang Tang (Michigan State University), Neil Heffernan (Worcester Polytechnic Institute), Rose Luckin (University College London).
weight: 1

# Page metadata.
title: IJCAI2020 Tutorial on Multimodal Learning in K-12 Education - Promise, Progress and Challenges
date: "2020-03-18"
lastmod: "2020-03-18"
draft: false  # Is this a draft? true/false
toc: true  # Show table of contents? true/false
type: docs  # Do not modify.

# Add menu entry to sidebar.
# - name: Declare this menu item as a parent with ID `name`.
# - weight: Position of link in menu.
menu:
  ijcai2020:
    name: Overview
    weight: 1
---


## Motivation & Description

Recently we have seen a rapid rise in the amount of education data available through the digitization of education. This huge amount of education data usually exhibits in a mixture form of images, videos, speech, texts, etc. It is crucial to consider data from different modalities to build successful applications in AI in education (AIED). This tutorial targets AI researchers and practitioners who are interested in applying state-of-the-art multimodal machine learning techniques to tackle some of the hard-core AIED tasks. These include tasks such as automatic short answer grading, student assessment, class quality assurance, knowledge tracing, etc. 

In this tutorial, we will comprehensively review recent developments of applying multimodal learning approaches in AIED, with a focus on those classroom multimodal data. Beyond introducing the recent advances of computer vision, speech, natural language processing in education respectively, we will discuss how to combine data from different modalities and build AI driven educational applications on top of these data. More specifically, we will talk about (1) **representation learning**; (2) **algorithmic assessment & evaluation**; and (3) **personalized feedback**. Participants will learn about recent trends and emerging challenges in this topic, representative tools and learning resources to obtain ready-to-use models, and how related models and techniques benefit real-world AIED applications.

## Tentative Outline

This tutorial presents a systematic overview of frontier approaches to multimodal learning in AIED. We will begin with introducing the main research problems, and motivate this topic with several real-world applications. Then, we will introduce methods for learning embedding for each domain and approaches to align embeddings across domains. Specifically, we will discuss how comprehensive information such as linguistic contexts and probabilistic soft logic rules can be leveraged to improve the quality of the embedding, and how to align embeddings in different domains by strategies such as retrofitting, joint learning, and self-supervised learning. Moreover, we will exemplify the use of these embeddings in applications of various areas, and will outline emerging research challenges that may catalyze further investigation on this topic. 


We would like to have a `half-day 210-minute` tutorial with the following detailed contents.

### Part I: The Future of Education for the 21st Century [25 mins]

In this part, we will give an overview of the AIED research and provide sufficient background and potential opportunities of AIED to the general audience. In particular, we would like to cover the followings:

* **The History of AIED**. We will briefly introduce the research area of AIED, which is an interdisciplinary community at the frontiers of the fields of computer science, education, and psychology. 

* **The Reality and the Potential in AIED**. We will shed light on the future potential of applying various advanced AI techniques in education domain.



### Part II: AI in K-12 Education [50 mins]

In this part, we will specifically focus on AI in K-12 education and discuss the following topics:


* **K-12 Education in China v.s United States**. The global education market is set to reach at least \$10T by 2030 as population growth in developing markets fuels a massive expansion and technology drives unprecedented re-skilling and up-skilling in developed economies. China, with the largest education market in the world, has led education VC investment growth over the past five years. China made up 50% of all Global VC investment in education through the decade, the USA 33% followed by Europe, India and the Rest of the World, each investing around 5% of the global funding total. It is worth to take a look at the difference of K-12 education in China and US and we will briefly discuss some interesting findings we observe and this gives us the basis of different classroom multimodal data sources.

* **Existing AI Applications in K-12 Education**. We will show some well developed AI applications in K-12 education market and quickly give audience ideas about how AI can transform our old-fashioned education.

* **Challenges in AI in K-12 Education**. We will introduce the new challenges when studying and developing AI approaches in K-12 education domain and explain the reasons behind the scene. The main challenges are divided into three categories: (1) limited data with crowdsourced labels; (2) human-centered evaluation metrics with long-lasting effects; and (3) low-quality data with heterogeneous sources.

### Part III: Multimodal Learning in Education [120 mins]

In this part, we will discuss some key sub-areas in multimodal learning in education, which is composed of three sub-parts: (1) Representation Learning; (2) Algorithmic Assessment \& Evaluation; and (3) Personalized Feedback. The detailed content structure is listed as follows:


* **Representation Learning**
	* Learning from Limited Crowdsourced Data
	* Learning from Educational Multimodal Data
* **Algorithmic Assessment & Evaluation**
	* Student Assessment
	* Teacher Evaluation
* **Personalized Feedback**
	* Knowledge Tracing
	* Adaptive Learning



In **Representation Learning** section, we will first discuss some state-of-the-art representation learning techniques for learning effective embeddings from limited crowdsourced data. This is pretty common in education scenarios, where the number of data instances is very limited and the corresponding crowdsourced labels are inconsistent. Then, we will review the multimodal representation learning frameworks with an educational focus. We will discuss both the methodologies and the educational applications. 

In **Algorithmic Assessment & Evaluation** section, we will discuss the recent progress of using AI algorithms to assess and evaluate performance of both students and teachers. Algorithmic assessment tools will not only reduce the grading burdens from teachers but give students opportunities to practice and improve their various skills anytime anywhere. Teacher evaluations will analyze instructors' in-class pedagogical instructions and provide objective and timely feedback to them. All these works heavily rely on understanding the multimodal classroom data by using AI algorithms.


In **Personalized Feedback** section, we will discuss some recent works on using AI in educational cognitive diagnosis. Such approaches try to understand the students' learning abilities and their learning outcomes. We will present recent research efforts in both knowledge tracing and adaptive learning. We will cover some recent advances in using deep neural networks in knowledge tracing and the personalized adaptive learning techniques in student modeling.

### Part IV: Conclusion and Future Outlook [15 mins]

In this part, we will conclude this tutorial and outline some interesting directions of both multimodal learning methodologies and the new trends in education.


## Slides 

TBD


## Tutorial Instructors


> ### Zitao Liu
> 
> TAL Education Group
> 
> Bio: Dr. Zitao Liu is the Head of AI Solution at TAL Education Group (NYSE:TAL), one of the largest leading education and technology enterprises in China. He studies and develops AI approaches to tackle some of the hard-core problems in AIED, such as automatic short answer grading, knowledge tracing, dropout prediction, etc. He has published his research in highly ranked conference proceedings, such as AAAI, AIED, Ubicomp, etc. Before joining TAL, Zitao was a senior research scientist at Pinterest and received his Ph.D degree in Computer Science from University of Pittsburgh.


> ### Songfan Yang
> 
> TAL Education Group
> 
> Bio: Dr. Songfan Yang received the Ph.D. degree in electrical engineering from University of California, Riverside in 2014. He is currently the Head of AI Research and Development at TAL Education Group (NYSE:TAL), one of the largest leading education and technology enterprises in China. He was the founder and CEO of FaceThink, an AI startup company, and an Associate Professor at Sichuan University, China. 


> ### Jiliang Tang
> 
> Michigan State University
> 
> Bio: Dr. Jiliang Tang is an assistant professor in the computer science and engineering department at Michigan State University since Fall 2016. Before that, he was a research scientist in Yahoo Research and got his PhD from Arizona State University in 2015. His research interests including social computing, data mining and machine learning and their applications in education. He was the recipients of 2019 NSF Career Award, the 2015 KDD Best Dissertation runner up and 6 best paper awards (or runner-ups) including WSDM2018 and KDD2016. He serves as conference organizers (e.g., KDD, WSDM and SDM) and journal editors (e.g., TKDD). He has published his research in highly ranked journals and top conference proceedings, which received thousands of citations and extensive media coverage.


> ### Neil Heffernan
> 
> Worcester Polytechnic Institute
> 
> Bio: Dr. Neil Heffernan taught middle school math and science in the Teach for America program before going to get a PhD in CS at CMU. After being diagnosed with brain cancer Dr. Heffernan and his spouse Cristina were motivated to make a platform useful to teachers and to give it away for free so they could do all sorts of research. Their ASSISTments platform is used by 50,000 students. Dr. Heffernan has written 60+ papers on learning analytics and over two dozen papers reporting the results of randomized controlled experiment testing different ideas to improve student learning.


> ### Rose Luckin
> 
> University College London
>
> Bio: Dr. Rose Luckin is a Professor of Learner Centered Design at the UCL Knowledge Lab in London. She researches how educational technology is designed and how it is evaluated. Professor Luckin is particularly interested in using AI to show teachers and students how people learn and how learning is cognitively, socially and emotionally shaped. She is also the Director of EDUCATE, a hub for Ed-Tech startups in London. In 2017, Rose was named on the Seldon List as one of the 20 most influential people in Education. She recently sat down with Iridescent CEO Tara Chklovski to discuss her work with education technology, the elements of a good problem, and her advice to staying motivated in the face of setbacks.


