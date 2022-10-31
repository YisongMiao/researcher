---
layout: default
---

## Yisong Miao's Academic Homepage

<img class="profile-picture" src="photo.jpg">




<!-- Welcome to my personal website! -->

# About

Aloha 👋 You have reached my 1-page style academic homepage. 

I am a second year PhD student at [WING](https://wing.comp.nus.edu.sg/)-[SoC](https://comp.nus.edu.sg/)-[NUS](https://nus.edu.sg/). I study natural language processing with [Prof Min-Yen Kan](https://www.comp.nus.edu.sg/~kanmy). 

Here is an [overview of my research](#research).



**Physical Yisong:** AS6 Building, meet me in the lab :P <br>**Digital Yisong:** [[Google Scholar](http://scholar.google.com/citations?user=a-oIKBoAAAAJ&hl=en)]  [[LinkedIn](https://www.linkedin.com/in/yisongmiao/)]  [[GitHub](https://github.com/YisongMiao/)] [[Twitter](https://twitter.com/yisongmiao)]  [[Skype](live:miaoyisong)] [[Out-dated 1-page CV](https://yisong.me/Yisong-CV-2021-Feb.pdf)]<br>**Email Yisong:** [yisong domain-of comp.nus.edu.sg]; [miaoyisong domain-of gmail.com].<br>

I keep a progress log for my research:

- [2022](log/2022)

My [Google Calendar](#calendar) is also available at the end of the page. Carpe Diem!<br>

**Table of content:**

- [Research overview](#research)

- [Paper archive](papers)

- [Teaching and mentoring](TaM)

- [Service](#service)

- [Education](edu)


---

# Research overview {#research}

**One-sentence SOP:** I want to build computational models that understand human's language in an explainable and intelligent way. 

To achieve it, I am studying (have studied) the following topics:

## Discourse (2021-)

Discourse concerns the organization of text in a coherent and logical manner. It is a perfect discipline to study language understanding because diverse linguistic devices exist and complex reasoning is required. 

The problem is decomposed as:

- **Can we find a computational proxy for understanding discourse?** Despite the strong performance, pretrained language models (PLMs) are said to NOT understand the language [from text alone](https://aclanthology.org/2020.acl-main.463/). But can we say [certain understanding is achieved](https://aclanthology.org/2021.acl-long.143/) when the models [behave like human](https://aclanthology.org/2022.coling-1.8/)?
- **Intermediate guidance for better understanding?** PLMs are also pruned to adversarial input and spurious features. Can we guide the model with human's intelligence about decision-making [as intermediate input](https://arxiv.org/abs/2203.14465)?
- **Neurons for discourse functions?** Can we [causally estimate](https://arxiv.org/abs/2202.05262) [different components](http://netdissect.csail.mit.edu/) in PLMs that are responsible for different discourse functions? 
- **Better pretraining strategy?** Popular PLMs (e.g. BERT) are trained in a [mask] way ([mask]=(simple, stupid, ...)). Are there better pretraining strategies to make it understand the language better?

Under submission. Please contact me if you're interested in reading it!



## Bridging emoji and lexical semantics (2021-) {#emoji}

Emojis inspire people to text creatively. People compose several emojis together to express a new meaning. For example:

🐻‍❄️=🐻+🧊, where 🐻‍❄️ is a composition of a bear 🐻 and ice 🧊 (means it is cold).

We have created a new dataset for concepts and their corresponding emoji compositions. We also have a model to learn such composition.

This is a FYP project by Zi Yun Yang that I co-advised with Prof Min. We tried to submit a paper to COLING '22, but it didn't make in. We are now revising the paper. Please contact us if you want to read our manuscript.



## Conversational recommendation (2018-2020) {#CRS}

Users have a hard time "telling" recommendation systems what they like. Recent advances in dialogue systems unlock new possibilities for user interactions. My [co-authored papers in 2020](#paper-2020) studied this topic. 

Even though I am not studying this topic currently, I wish the following aspects can be considered by our community:

- **Taxonomy creation**: Existing feature taxonomies are handcrafted. Is there a smart/soft way to build a taxonomy for better system design and evaluation?
- **Discourse structure:** Existing works (ours included) consider multi-round dialogue in a superficial manner. What features/products in previous rounds ***contrast\*** with those later? What information users heard in previous rounds ***caused\*** their later decision?
- **Real-world applications:** Many works (ours included) are developed and evaluated in the sandbox -- user simulation. How can we develop systems with (and for) real-world users (with diverse backgrounds, multiplex intent, and language variations)?

**Recommendation:** [Tutorials](http://staff.ustc.edu.cn/~hexn/slides/sigir20-tutorial-CRS-slides.pdf) by Wenqiang et al. A pretty cool integrated [CRSLab](https://github.com/RUCAIBox/CRSLab) environment by RUC. Talk to my group mate [Victor Li](https://lichuangnus.github.io/) who is currently studying this topic.



---

# Paper archive {#papers}

Here is an archive for my (co-)authored conference papers, workshop papers and technical reports. 

Some of them belongs to fast research and some to slow research ([😛 wiki here](http://coling2018.org/wp-content/uploads/2018/08/180824-researchFastAndSlow-1.pdf) from Min's talk on this concept).



## 2022 {#paper-2022}

[1] Yihao Ang, <u>Yisong Miao</u>* . (\*=Ordered Alphabetically) (2021) <u>Towards Molecular-level Similarity Search based on Text Data.</u> An In-Class Project in CS6219, Advanced Topics in Computer Systems. [[Slides](publications/CS6219-Slides.pdf)@here] [[Code](https://github.com/YisongMiao/text-dna)@GitHub]

<u>One sentence summary:</u> We embed text 🔤 into DNA 🧬 and support similarity search.

[2] Yong Liang Goh* , Yongbin Li* , <u>Yisong Miao</u>\*. (\*=Ordered Alphabetically) (2021) <u>Connecting the Dots: Explaining Human Reasoning on the Graph. A Case Study on Deep Question Generation.</u> An In-Class Paper in CS6208, Advanced Topics in AI. [[PDF](publications/tech-report-eDQG.pdf)] [Code upon request]

<u>One sentence summary:</u> We explore the importance of nodes and edges for the reasoning in question generation. 

[3] Saurabh Jain, Yisong Miao, Min-Yen Kan, <u>Comparative Snippet Generation.</u> [ [2022.ecnlp-1.7](https://www.aclweb.org/anthology/2022.ecnlp-1.7/) (@ ACL Anthology) ] [ [Poster (.pdf)](https://www.comp.nus.edu.sg/~kanmy/talks/poster_v2.pdf) ] [ [Dataset (@ GitHub)](https://github.com/wing-nus/comparative-snippet-generation-dataset) ] 

<u>One sentence summary:</u> We create a corpus for product review and experiment with computational models to generate comparative sentences based on the corpus. 



## 2021 {#paper-2021}

[1] Wenqiang Lei, <u>Yisong Miao</u>, Runpeng Xie, Bonnie Webber, Meichun Liu, Tat-Seng Chua and Nancy Chen (2021) <u>Have We Solved The Hard Problem? It’s Not Easy! Contextual Lexical Contrast as a Means to Probe Neural Coherence</u> (AAAI '21) [[PDF]](https://cont2lex.github.io/files/8523.LeiW.pdf) [[Slides](https://cont2lex.github.io/files/cont2lex-slides-20min.pdf)] [[Poster]](https://cont2lex.github.io/files/aaai-poster-final.pdf) [[Code and Data](https://cont2lex.github.io)] [[bib](publications/AAAI-21-bib.md)]

<u>One sentence summary:</u> We find not all antonyms exhibit a contrasting meaning in context and provides the first corpus to characterize such a phenomenon. 

[2] Yisong Miao. (2021). <u>Mining and Analyzing Questions from Paper Titles.</u> An Engineering Trial Task. [[Slides@Google](https://docs.google.com/presentation/d/1d0xlTMaDiJ_x_VW1rEop4HEhbAZ5piqsC0lPZmGy7bg/edit?usp=sharing)] [[Codebase@GitHub](https://github.com/YisongMiao/Q-Title)]

<u>One sentence summary:</u> We provide a tool to automatically find all questions from paper titles in dblp libarary. 



## 2020 {#paper-2020}

[1] Wenqiang Lei, Xiangnan He, <u>Yisong Miao</u>, Qingyun Wu, Richang Hong, Min-Yen Kan, Tat Seng Chua (2020). <u>Estimation-Action-Reflection: Towards Deep Interaction Between Conversational and Recommender Systems.</u> In Proceedings of the Thirteenth ACM International Conference on Web Search and Data Mining (WSDM '20). [[PDF](https://yisong.me/publications/wsdm20-EARS.pdf)]  [[Slides](https://ear-conv-rec.github.io/EAR-slides-wsdm.pdf)] [[Poster](https://ear-conv-rec.github.io/EAR-poster-wsdm.pdf)]  [[Codes and Project Websites @ Github.io](https://ear-conv-rec.github.io/)] 

<u>One sentence summary:</u> We are the first to consider multi-round conversational recommendation and propose a three-step solution for that. 

[2] Wenqiang Lei, Gangyi Zhang, Xiangnan He, <u>Yisong Miao</u>, Xiang Wang, Liang Chen and Tat-Seng Chua (2020). <u>Interactive Path Reasoning on Graph for Conversational Recommendation</u>. (KDD '20). [[PDF]](https://arxiv.org/abs/2007.00194) [[Codes and Project Websites @ Github.io]](https://cpr-conv-rec.github.io/)

<u>One sentence summary:</u> Based on the WSDM work, we consider graph constraints to make the exploration more efficient. 



---



# Teaching and Mentoring {#TaM}

I list my TAs and mentorships in a reverse chronological order:

## TA:

- 2022-2023 Spring. CS4248 Natural Language Processing. (TBD. I wish I can TA it again 😉) 
- 2022-2023 Fall. CS5228 Knowledge Discovery and Data Mining. (Primarily for grading)
- 2021-2022 Spring. CS4248 Natural Language Processing. (Tutorial leader and project consultation).
- 2021-2022 Fall. CS3244 Machine Learning. (Student experience)

## Mentoring:

- Zi Yun Yang. Graduated 2022 Spring. Topics about emoji composition and lexical semantics. [Outstanding Undergraduate Researcher Prize](https://www.comp.nus.edu.sg/news/2022-ourp-ocp-2122/) (OURP, 5 out of 1k+). 
- Saurabh Jain. Graduated 2021 Winter. *<u>Comparative Snippet Generation.</u>* [ECNLP@ACL'22](https://aclanthology.org/2022.ecnlp-1.7/).



---

# Service {#service}

## Program Committee / Reviewer

[... Forgot to record for a long time!] 

## 2022

ACL Rolling Review. EMNLP 2022. AAAI 2023. 



## Before 2022

- [Dec 2021] Invited by [ARR](https://aclrollingreview.org/). Evaluated 1 papers. I only got 1 paper so I finish by myself! 💪
- [Nov 2021] Invited by [ARR](https://aclrollingreview.org/). Evaluated 5 papers. Received many many help from  [Yuxi Xie](https://yuxixie.github.io/), [Victor Li,](https://lichuangnus.github.io/) and [Hengchang Hu](https://github.com/HoldenHu). 👍
- [Oct 2021] Invited by AAAI 2022. Evaluated two papers in discourse track and one paper in language grounding (got a lot of help from [Yuxi Xie](https://yuxixie.github.io/)). 👍
- [Mar 30th 2021] Invited by EMNLP 2021, but I was not assigned any paper. 🤷‍♂️
- [Dec 5th 2020] Invited by ACL-IJCNLP 2021, reviewed 1 paper in discourse and pragmatics track as main reviewer. 
- [Oct 22nd 2020] Invited by NAACL 2021, reviewed 2 papers in interactive system track as main reviewer.
- [Sometime 2019] NLPCC 2019, evaluated 2 research papers in NLP (dialogue track).

## Secondary Reviewer

- AAAI 2021, evaluated 2 research papers in NLP (dialogue track + discourse track). 

- AAAI 2020, evaluated 1 research paper in NLP (dialogue track).

---



# Education {#edu}

2014-2018, Bachelor of Engineering in Computer Science. <br>
**Founding Class** of undergrad program of [University of Chinese Academy of Sciences](https://english.ucas.ac.cn/). 

2018-2020, Master of Computing, National University of Singapore. <br>Thesis advisor: [Min-Yen Kan](https://www.comp.nus.edu.sg/~kanmy/). I learned a ton of knowledge from [Wenqiang Lei](https://sites.google.com/view/wenqianghome/home) about dialogue/discourse and conversational recommendation. I also consulted my research to [Xiangnan He](http://staff.ustc.edu.cn/~hexn/), [Tat-Seng Chua](https://www.chuatatseng.com/), and [Nancy F. Chen](https://sites.google.com/site/nancyfchen/home). 

2021- , PhD in Computer Science, National University of Singapore. <br>Thesis advisor: [Min-Yen Kan](https://www.comp.nus.edu.sg/~kanmy/).



# Calendar {#calendar}

<dev>

<center>
<iframe src="https://calendar.google.com/calendar/embed?height=600&amp;wkst=1&amp;bgcolor=%23ffffff&amp;ctz=Asia%2FManila&amp;src=ZTNvcTIwbXBqYzMyMDc4OG1zajNpZm84M3NAZ3JvdXAuY2FsZW5kYXIuZ29vZ2xlLmNvbQ&amp;color=%23039BE5" style="border:solid 1px #777" width="800" height="600" frameborder="0" scrolling="no"></iframe>
</center>
</dev>



<script type="text/javascript" id="clustrmaps" src="//cdn.clustrmaps.com/map_v2.js?cl=ffffff&w=200&t=tt&d=edk2D6NRWsf3yF00Cbk3Ts8MR2oVgXMDSn-oFxUPJ_8&co=1cb2f2&cmo=3acc3a&cmn=ff5353&ct=ffffff"></script>



<center><i>------ Stay Hungry, Stay Foolish ------</i><br><br><br></center>

