---
layout: default
---

<img src="./imgs/HEADSHOT.jpg" alt="Headshot" style="width:300px">

Hello! My name is Rebecca, and I am a second-year Computer Science Master's student at UCLA as a DeepMind Fellow. I'm currently doing research in NLP, specifically on under-resourced languages and code-switching datasets with Prof. Peng's [Plus Lab](https://vnpeng.net/), as well as [Prof. Cacoullos](https://nmcode-switching.la.psu.edu/work-with-us/) at Penn State. I received my B.S. with Honors at Stanford University, where I wrote my thesis under the advisement of Prof. Christopher Manning.

More broadly, I am interested in producing language technologies that aid in maintaing language practices. When I am not working, you can find me writing, dancing flamenco, and collecting earrings!

# Research

## Publications

**Pattichis, R.**, Trawick, S., LaCasse, D., & Torres Cacoullos, R. (2023, July). [SRW] Aligning Code-Switching Metrics with Bilingual Behavior. In _The 61st Annual Meeting Of The Association For Computational Linguistics._ _([poster)](https://virtual2023.aclweb.org/paper_S25.html#poster))_
<details>
  <summary>Abstract</summary>
  Models and metrics of linguistic code-switching (CS) have almost exclusively worked with word-level units. However, any two words are not equally likely CS points in bilingual speech. In addition, other-language single-word items and alternating-language multi-word items have distinct properties. Adapting these familiar metrics to the Intonation Unit (IU), we capture a shared tendency for CS to occur across rather than within prosodic boundaries. This constraint is distorted when single- and multi-word other-language items are merged. Individual differences according to language distribution and CS rates are independent, visualized in the number and breadth of language bands in transcripts of bilingual speech. These results are important to consider in future development of code-switched datasets for NLP tasks, as the IU token and exclusion/inclusion of single-word items highly impacts the CS represented in the input text.
</details>

Alvero, A., **Pattichis, R.**, (2022). “Linguistic and Cultural Strategies: Identification and Analysis of Spanish Language Usage in College Admissions Essays”.
(Under review) _([preprint](https://osf.io/preprints/socarxiv/wmsre/))_
<details>
  <summary>Abstract</summary>
  In US K-12 education, the Spanish language is subject to practices and policies that limit its expression, especially among Latinx students. However, Spanish is seen as a positive form of diversity in higher education. In light of these contradictions, we examine the degree to which Spanish is strategically deployed in selective college admissions by high school students in their admissions essays. We use two years of undergraduate application essays (n = 276,768) and metadata submitted to the University of California by every self-identified Latinx applicant and a racially representative random sample of non-Latinx applicants. To identify Spanish language usage in the text, we develop a computational mixed methods approach by combining machine translation and human reading. Spanish was used by 33\% of Latinx and 15\% of non-Latinx students with stylistic variation by class and ethnicity. We also find that lower income Mexican and Central American applicants were the most likely to use substantive forms of Spanish in their admissions essays as well as provide translations into English. We posit this as an example of students identifying cultural mismatch between themselves and university admissions offices due to the perceived need of translating the Spanish words and phrases.
</details>

**Pattichis, R.** (2022). Centering the Voices of First-Generation Immigrant Youth: Multilingual NLP Methods in the Translanguaging Context. Stanford Digital Repository. Available at <https://purl.stanford.edu/nd602zq5759>
<details>
  <summary>Abstract</summary>
  Translanguaging, or the act of using multiple languages within a speech utterance (e.g., sentence and/or word), is a global phenomenon for multilingual communities. In the context of the United States, translanguaging is a frequent occurrence among Latin American immigrant communities. While there are several large multilingual models such as XLM-RoBERTa and multilingual BERT, these models have been trained on and evaluated with parallel monolingual data. Upholding parallel monolingualism as the standard definition of multilingualism erases the language practices of many communities of color, including Latin American immigrants in the United States. The consequences are even worse for racialized children in the schooling system who may be labeled as English Language Learners (ELL) for the very notion that their fluency in multiple languages must be separate and apart. This ELL label has immediate consequences regarding future classes they have access to, as well as their own sentiment around and through their language practices. Moreover, there is currently no labeled NLP dataset that includes translanguaging between Spanish and English for the task of sentiment analysis. In collaboration with the Stanford Graduate School of Education, this research aims to center the voices of first-generation Indigenous Latin American immigrant students in NLP research through the task of sentiment analysis. Specifically, this thesis constructs the Interview Transcripts Dataset, an innovate trilingual dataset composed of transcribed interview data that contain instances of translanguaging, as well as a framework for developing these datasets. The findings of this project provide a promising starting point, and emphasize the need to leverage current pre-trained models on similar domains as well as develop a more robust large-scale dataset that centers translanguaging. Ultimately, translanguaging remains an open problem in NLP research tasks.
</details>

## Final Class Projects

### UCLA
CS269 - Fairness, Accountability, and Robustness in Natural Language Processing: "Towards the Equivalence Constraint: Evaluating Code-Switching Benchmarks on a Different Perspective" _([repo](https://github.com/rpattichis/cs-269))_
<details>
  <summary>Abstract</summary>
  Code-switching (CS) is increasingly relevant in the field of NLP with the development of multilingual language models. We evaluate current CS datasets on their multilinguality and switching complexity using previously established metrics, and curate a dataset that aligns with the Equivalence Constraint Theory of CS. Currently, this theory is left out of NLP datasets, although data is crucial in studying it further. We perform manual editing and human validation by native English-Spanish speakers. Ultimately, we find that data are either entirely monolingual, or present a skewed perspective of CS patterns (i.e., single-word switches). These findings hold implications for the future collection of CS datasets for NLP.
</details>

CS 260 - Machine Learning Algorithms: "Lyric Generation Based on Model Complexity and Repetition Evaluation" _([repo](https://github.com/rpattichis/lyric-generation))_

### Stanford
CS 224N - NLP with Deep Learning: ["RobustQA Using Data Augmentation"](https://www.semanticscholar.org/paper/RobustQA-Using-Data-Augmentation-Rebecca-Pattichis/8e4d7d60307047b45197c7c434576a0af09516bf)
    <details>
      <summary>Abstract</summary>
      This project aims to explore possible improvements and extensions to the RobustQA Default baseline provided by the CS224N Winter quarter staff. Our goal is to create a domain-agnostic question answering system given DistilBERT as a pre-trained transformer model. The main method attempted in this paper is that of Task Adaptive Fine Tuning (TAPT) [1], which entails a pre-training step utilizing the Masked Language Modeling task. This method was combined with experimentation on hyperparameters (batch size, number of epochs, and learning rate) to produce the highestachieving model. Specifically, a pre-trained MLM model with a batch size of 32 yielded an EM of 42.75 and F1 of 61.14, which are each around 2 points higher than the baseline metrics. 
    </details>

CS 221 - Artificial Intelligence: Principles and Techniques: "Modeling Platelet Transfusion for The Stanford Blood Center: Inference Using Sentiment Analysis and Recurrent Neural Networks" _([poster](https://stanford-cs221.github.io/autumn2019-extra/posters/129.pdf))_
<details>
  <summary>Abstract</summary>
  Platelets are a blood product that expire within 3 days of arriving to the hospital. The Stanford Hospital system wastes
about 10% of platelets annually. Researchers previously used aggregated data in order to predict usage, create a three-day ordering strategy, and thus reduce wastage. However, this ordering strategy was not implemented due to lack of human trust in models. New research attempts to address this issue by using patientlevel prediction. This project aims to aid this research by predicting which surgeries will need a platelet transfusion. The two methods used for prediction are stochastic gradient descent on bag-of-words features and Recurrent Neural Networks.
</details>

CS 129 - Applied Machine Learning: "Music Genre Classification Using MFCCs and Neural Networks" _([code](https://github.com/rpattichis/CS129_project))_
<details>
  <summary>Abstract</summary>
  We approach the music genre classification problem using the GTZAN data-set, which contains 100 30-second song clips for 10 different genres. Our first component of the project revolved around computing the Mel Frequency Cepstral Coefficients (MFCCs) and feeding the result into a variety of classification algorithms: KNN, SVM, and a neural network with fully connected layers (FCNN). We also considered a FCNN classifier based on initial code provided online [5]. We then adopted the FCNN as a baseline model and considered several variations that included: i) reducing the difference between the training and validation errors without sacrificing accuracy, ii) reducing the number of layers to reduce the total number of parameters, and iii) considering a different activation and dropout. Compared to the 47% accuracy achieved by the SVM, we derived reduced FCNN parameter models that gave validation and test accuracy of 61-62%.
</details>

# Awards and Fellowships

* DeepMind Fellow at UCLA (2022-2024)
* Class of 2022 Stanford Award of Excellence
* Cecilia & Tony Burciaga Community Development Award, Stanford's El Centro Chicano y Latino (2022)
* Stanford's Department of Theater and Performance Studies Award for Contribution to Dance (2022)
* [Cadence's Latinx Students in Technology Scholarship](https://newsdirect.com/news/meet-the-2021-winners-of-cadences-latinx-students-in-technology-scholarship-154120563) (2021)
* Google CS Research Mentorship Program (2021b)
* [Stanford VPUE STEM Fellow](https://undergradresearch.stanford.edu/student-spotlight/stem-fellows) (2020)
* Advancing Women in Technology (2019)

# Hobbies

While at Stanford, I danced with [Aleta Hayes'](https://www.aletahayes.com/about) Chocolate Heads company! Check out our performances below:

* ["Fashion Fable"](https://vimeo.com/742072113), 2022, Stanford's Cantor Museum
* ["Riot of Spring"](https://vimeo.com/579947905), 2021, Zoom
* ["Traveling in Place"](https://vimeo.com/580049177), 2020, Zoom

Before that, I danced flamenco at the National Institute of Flamenco for thirteen years. During my senior year of high school, I performed with the University of New Mexico's dance company in ["Elementos"](https://www.youtube.com/watch?v=YAg5wkbgqok) choreographed by Adrian Santana.
