+++
title = 'About Me'
description = "A page that describes who I am and what I do."
date = 2024-10-24T22:04:47+02:00
tags = ["Me", "Myself", "I"]
draft = false
+++

I just finished my studies in computer science at the [ENS Paris-Saclay](https://ens-paris-saclay.fr/ "ENS Paris Saclay website"), and the [IASD](https://www.masteriasd.eu/ "IASD website") Master's degree at [Dauphine PSL](https://dauphine.psl.eu/ "Dauphine PSL website").

I am currently looking for a job around machine learning, in R&D, ML Ops, or Data science.

You can download my resume [here](/Resume_MariusRoger.pdf), or its French version [here](/CV_MariusRoger.pdf).

<!-- TODO: set the experiences and educations in separate files + replace by a hugo range  -->
- Experience
    - {{< mydetail title="ML Engineer Intern" location="GitGuardian" date="Summer 2024" name="exp" >}}
In this 6-month R&D internship at [GitGuardian](https://www.gitguardian.com/), I experimented with open and closed-source Large Language Models to help users prioritize security incidents.

After familiarizing myself with the [secret](https://www.gitguardian.com/glossary/secret-sprawl-definition) detection engine, I helped build datasets to train and evaluate LMs on the task of adding context on incidents based on surrounding information, before comparing the performances of several models.
    {{< / mydetail >}}
    - {{< mydetail title="Research assistant" location="LMU Munich" date="2022-2023" name="exp" >}}
During this year abroad, within the [Statistics department](https://www.slds.stat.uni-muenchen.de/) of the [LMU Munich](https://www.lmu.de/en/), I investigated French and German LMs.

I assessed their performance on language-specific tasks, contributed to other research in the department (we wrote a [paper](https://huggingface.co/papers/2307.07331)), reviewed candidate conference papers, and helped with the [Deep Learning for NLP](https://slds-lmu.github.io/dl4nlp/) course. 
    {{< / mydetail >}}
    - {{< mydetail title="ML Engineer Intern" location="HrFlow.ai" date="Summer 2022" name="exp" >}}
In this 4-month R&D internship at [HrFlow.ai](https://hrflow.ai/), I used NLP techniques to predict the similarity between candidate profiles and job offers.

I used textual and historical data on both sides to infer optimal matches, despite the sparsity and bias of the data.
    {{< / mydetail >}}
    - {{< mydetail title="NLP Research Intern" location="LAMSADE" date="Summer 2021" name="exp" >}}
This 5-month research internship at the [LAMSADE](https://www.lamsade.dauphine.fr/) lab of Dauphine PSL University enabled me to build a NLP model based on [Neural ODE](https://arxiv.org/abs/1806.07366), by thinking of text tokens as observations of a phenomenon and trying to solve the underlying differential equation.

Working towards this result, I learned about recurrent neural networks in detail, as well as their uses for Natural Language Processing and signal processing.
    {{< / mydetail >}}
    - {{< mydetail title="Speech Research Intern" location="INRIA Lille" date="Summer 2020" name="exp" >}}
During the 3 months of this fully remote research internship at [INRIA Lille](https://team.inria.fr/magnet/) and [LORIA](https://team.inria.fr/multispeech/), I tested the robustness of a neural speech anonymization pipeline, within the [VoicePrivacy](https://www.voiceprivacychallenge.org/) challenge.

My task was to add perturbations to the pipeline, such as noise or dropout on intermediary features or changing their dimensions, and observe how the metrics changed (as well as listen to the way speech samples were regenerated).
    {{< / mydetail >}}
    {.experience}

- Education
    - {{< mydetail title="Master 2 IASD" location="Dauphine PSL University" date="2023-2024" name="edu" >}}
I did my last year as a _normalien_ student within [Dauphine](https://dauphine.psl.eu/) and the [PSL University](https://psl.eu/), at the [_**I**ntelligence **A**rtificielle, **S**ystèmes, **D**onnées_](https://www.masteriasd.eu/) M2, a young but promising research Master's degree aiming to teach the theory behind Data Science.

The classes include foundational ones, such as theoretical ML, optimization, reinforcement learning, text and image processing, and data handling, as well as electives, among which I chose graph analytics, social choice, differential privacy, knowledge graphs, ML for Big Data and NoSQL.

The year began with a series of 3 consecutive month-long competitive sprint projects on recommendation, GANs, and adversarial ML. We then carried on with a data extraction project to store links between researchers in Neo4j data, another to store/query time series efficiently using the iSAX technique, and several research paper analyses.

An opportunity within PSL was also the PSL Weeks, where I could apply NLP to social sciences, or go to [ESPCI](https://www.espci.psl.eu) and learn about low-level optimization for greener machine learning. I finished the year in a very technical internship setting at GitGuardian.

    {{< / mydetail >}}
    - {{< mydetail title="Master 2 MVA" location="ENS Paris-Saclay" date="2021-2022" name="edu" >}}
My third year at [ENS Paris-Saclay](https://ens-paris-saclay.fr/) revolved around the [_**M**athématique, **V**ision, et **A**pprentissage_](https://www.master-mva.com/) M2, a renowned research Master's degree in AI held across many high-level institutions near Paris.

Among its many classes, I focused on statistics, optimization, topological data analysis, graph neural networks, NLP, audio, and time series analysis. With great cross-domain teachers, I was able to understand the fundamental links between NLP and signal processing, as well as learn about different representations of data.

There was research paper analysis project for most classes, and I was then able to apply this knowledge to a real-world problem for the first time at HrFlow.ai during my internship.
    {{< / mydetail >}}
    - {{< mydetail title="Master 1 MPRI" location="ENS Paris-Saclay" date="2020-2021" name="edu" >}}
In my second year, within the [_**M**aster **P**arisien de **R**echerche en **I**nformatique_](https://wikimpri.dptinfo.ens-cachan.fr), held at [ENS Paris-Saclay](https://ens-paris-saclay.fr/), I was able to continue learning about theoretical CS, while opening towards ML.

The topics were Markov chains, probabilistic algorithms, convex and combinatorial optimization, computer vision, deep learning, and a software engineering project, in which I built with 4 classmates a C++ program for modular audio processing and generation.

Weekly sessions were also dedicated to learning about research processes, like how to understand and explore a new field, or how to write a research article. During the second semester, I focused on learning and experimenting with NLP for my internship at LAMSADE.
    {{< / mydetail >}}
    - {{< mydetail title="BS in Computer Science" location="ENS Paris-Saclay" date="2019-2020" name="edu" >}}
During my first year at [ENS Paris-Saclay](https://ens-paris-saclay.fr/), I learned about computer science theory. Classes focused on (graph) algorithms, complexity and computability, discrete maths, grammars and automata, logic, architecture and systems, compilation, programming languages theory, lamba-calculus and functional programming.

In this time, I was able to do a few class projects, such as a (minimal) C compiler in OCaml, a CPU from NAND gates using a HDL, and a few smaller C, OCaml or Scala programs. I also prepared the [Cambridge Advanced](https://www.cambridgeenglish.org/exams-and-tests/advanced/) exam, which I got with grade A (C2 level).

At the end of this year, I discovered (deep) machine learning and research through my INRIA Lille internship.
    {{< / mydetail >}}
    - {{< mydetail title="Preparatory Classes" location="Lycée Camille Guérin" date="2017-2019" name="edu" >}}
These two years in _**C**lasses **P**réparatoires aux **G**randes **É**coles_ were an intensive training in mathematics, physics, chemistry, computer science, literature/philosophy and english specific to nationwide competitive exams for the entrance to the _Grandes Écoles_.

I followed the MPSI and MP\* cursus at [_Lycée Camille Guérin_](https://lyc-camilleguerin.fr/cpge-et-pppe/) in Poitiers, and was admitted to [ENS Paris-Saclay](https://ens-paris-saclay.fr/).
Biweekly oral examinations (_colles_) as well as monthly written exams in the various classes ensured we kept the pace to be successful after the second year.

I also prepared a practical physics research project, which studied how we can use light polarization to study mechanical stresses in birefingent materials (that transform light differently depending on the axis).
    {{< / mydetail >}}
    {.education}
{.resume}
