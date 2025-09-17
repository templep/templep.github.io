# Presentation

Since September 2022, I am an associate professor at the University of Rennes. I joined the DiverSE team to tackle new challenges in software engineering, software testing, software variability, and machine learning!

From January 2019 to September 2022, I was a post-doc researcher at the Namur Digital Institute (NaDI) from the University of Namur (UNamur).
I was involved in the EoS (Excellence of Science) [VeriLearn project](https://eos.cs.kuleuven.be/content/home) with Gilles Perrouin, Patrick Heymans, Benoit Frenay and Pierre-Yves Schobbens.

Previously, I obtained my PhD working at Université de Rennes and IRISA lab in the [DiverSE](http://diverse.irisa.fr/) working group in Rennes (France).
My supervisors were [Mathieu Acher](http://www.mathieuacher.com/) and [Jean-Marc JEZEQUEL](http://people.irisa.fr/Jean-Marc.Jezequel/).
The thesis is entitled: Investigate the Matrix: Leveraging Variability to Specialize Software and Test Suites (more in the PhD topic section).

Furthermore, I am a tennis player. I began to play tennis at 6 until my 18. I stopped to focus on my studies and started again during my PhD.

## Publications
To see the list of my publications, [click here](./publications.md).

## Teaching
To see the list of classes and courses I am involved in, [click here](./teaching.md).

## Jurys and supervision
I am also involved in jurys and student supervision (PhD and Masters), [click here to know more about that](./jury_and_supervision.md).

## Background

After graduating in Computer Science with a fous on Data Image Processing (a 2-years diploma teachning fundamentals of a panel of facets of computer science, including OS, Programming, Mathematics, Web technologies, network managing, Systems design, etc.)from the Institute of Technology of Lannion (France); I went to ESIR (Ecole Supérieure d'Ingénieurs de Rennes, Rennes, France), an engeeniering school where I chose to continue focusing on Data Image Processing.
During the last year of ESIR, I also graduated from the University of Rennes 1 with a Master in Computer Science with a focus on introducing the world of research to student.
Thus, I have a strong background in Data Image Processing (as well as Machine Learning) on one hand and in Softwarer Engineering thanks to my PhD on the other hand.

## Topics of interest
As my experience in research grows and I explore new ideas, my topics of interest also grow larger and larger... Here is a list, but it is clearly opened to include more topics:
* __Software Variability__
* Software Testing and more precisely __Performance Testing__
* Machine Learning also including __Adversarial Machine Learning__ and more recently Ethics around the use of ML
* Computer Vision
* Data Image Processing (as well as Video Processing)
* Computer Graphics


# Research Activities

## WestOps (ANR TSIA)
The WestOps project is funded by the French National Agency for Research (ANR) and gather the DiverSE team as well as two industrial partners:
 1) [Kereval](https://www.kereval.com/), a small to medium-sized company located in Brittany (just next to Rennes), and specialized in software testing and requirements engineering. Their focus was more on systems designed for medical activities, but they are turning more and more onto AI-based systems.
 2) [Ouest-France](https://www.ouest-france.fr/) is a French newspaper company located in Rennes and targeted the west of France for their audience.
For years now, they know the importance of research for their activities, especially to help them sort and search in their content that grows more and more every day.
They have regular meetings with some members of IRISA (recently, a common lab has been created to facilitate their interactions).

The WestOps project is born from the observation of both Inria and Kereval that AI models are now subject to changes over time. They can adapt to these changes by retraining.
Yet, it may not be sufficient, as abrupt and big changes can occur almost instantly. In addition, triggering retraining is usually done in an automatic way, but when should this be done?
The WestOps project tries to investigate these questions and ensure the quality of AI models evolving over time in an automated way. It targets also a real world application as Ouest-France is willing to apply directly the results of WestOps to their automated pipelines and thus improve their product and processing chain.

## EoS VeriLearn Project
The EoS VeriLearn Project is a blue sky project trying to think about how Machine Learning and other Artificial Intelligence techniques can be tested and/or verified.
Deep Learning is not considered for now in this context.
The project gathers different university of Belgium including universities from Brussels, Leuven and Namur.
Different aspects of testing, verifications as well as ML are tackled in this project.
I am more particularly involved in the testing research direction, including performance aspects; but also, related to my PhD
how to mitigate risks when using ML prediction models in the context of Software Product Lines.
This work is mainly done in Namur with Patrick Heymans and Gilles Perrouin.
I am also involved in the ethics work package in which we try to evaluate risks and consequences of blindly using systems based on ML in critical contexts such as justice or security.
This work is done in collaboration with the University of Leuven (more particularly Pieter Delobelle and Bettina Berendt) and the University of Namur.
Finally, I help also in trying to enforce domain-knowledge constraints directly in ML classifier implementations to make as efficient as possible but explainable and understandable for domain experts.
This work is currently done with Geraldin Nanfack and Benoit Frenay from the University of Namur.

## PhD topic
title: __Investigate the Matrix: Leveraging Variability to Specialize Software and Test Suites__
*[manuscript and slides](https://github.com/templep/Candidature_Prix_these_GPL_2018)*

My PhD tackles both the problem of testing configurable systems and improving the quality of test suites (in particular in the context of configurable systems).
Modern software are configurable since they are designed to appeal to the largest possible number of users via customization and configuration.
This makes software evermore complex, hard to design, code, test and maintain.
In particular, how can we help users, having a specific application in mind or very specific requirements (for instance in terms of performance), in finding a proper configuration that is likely to meet their requirements?
It is very challenging since the number of configuration options is so big (about 13k for the Linux Kernel) that it is usually impossible to generate all the possible variants in order to assess whether they comply with given requirements.
In addition, configuration constraints (telling which combination of options are allowed or not) complexify the configuration space introducing even more computation problems.

The other part of my PhD is about how can we improve the quality of test suites designed to test configurable systems?
Usually, several test cases are needed in order to properly test a piece of software.
It is still the case with configurable software but the problem is that different configurations may behave differently depending on the given inputs, multiplying the number of tests needed to assess the quality of the system (globally).
Because of the different behaviors of configurations, finding *good* (performance) test cases is difficult and I tried to tackle this challenge.

I have applied these different directions to different systems from different domains ranging from code compilers to computer vision based systems including machine learning based systems.


<!--In the context of this PhD, we try to better understand how variability affects configurable systems in their performances.
In particular, we focus on Computer Vision (CV) systems which are based on mathematical fundamentals.
They are also configurable systems with options that can influence their performances.
There are plenty of CV techniques developped to address different yet similar issues (such as tracking objects in videos or tracking pedestrians).
Choosing a CV configuration that will give the best performances w.r.t. an input (i.e., videos or inputs) is a non-trivial process. Inputs can have features that affect drastically the performances (e.g., execution time, memory consumption or even capability of performing the task at hand) of the CV technique.
Additionally, the configuration of the system can have an impact on its performances.-->

<!--Part of my work is to leverage Machine Learning techniques in order to understand how the CV configuration, on one hand, and given inputs, on the other, affect the performance of the program.
Part of my work focused on leveraging Machine Learning techniques to help users configuring their systems such that, by reducing the variability space (i.e., values that can be set to options), it will meet users' performance requirements.
An other part has been to evaluate the relative merits of a set of tests to distinguish different configurations of a system.
In the end, assessing the quality of tests might help in detecting bugs, reducing the number of tests to execute, etc.-->

## Master's internship

My internship took place in the TEXMEX (now [LinkMedia](http://www-linkmedia.irisa.fr/) )working group under the supervision of [Ewa Kijak](http://people.irisa.fr/Ewa.Kijak/) and [Laurent Amsaleg](http://people.rennes.inria.fr/Laurent.Amsaleg/).
The topic of this internship was the _security of Machine Learning processes applied to multimedia content_ which followed the work of Thanh-Toan Do and his PhD.
The goal of this internship was to have a better understanding of how Machine Learning techniques can be influenced in the establishment of their separating functions depending on data that they have seen.
An other concern was how sensitive the establishment of separating functions is w.r.t. the distribution of data points.
This topic is very close to the work conducted by [Battista Biggio](https://pralab.diee.unica.it/en/BattistaBiggio) and the [PRALab](http://pralab.diee.unica.it/en) in Cagliari.



# Program Comittees

I was PC member of the [SPLC'19](http://kishi-lab.sakura.ne.jp/splc2019/call-for-papers/call-for-research-papers/) _Artifacts Track_ organized in Paris from the 9th to the 13th of September 2019.
In 2020, I was PC member of the _Artifact Track_ but also the _Challenge Solution Track_ of [SPLC'20](https://splc2020.net/) organized in Montreal, Canada but held online due to the Covid19 pandemic situation from the 19th to the 23th of October 2020.
In 2022, I was PC member for the _solution track_ of [SPLC'22](https://2022.splc.net/committees/program-committees/) held in Gratz and I served as a PC member for [VaMoS](https://vamos2022.isti.cnr.it/vamosorganisation). 
In 2023, I was again PC member for the _solution track_ but also for the _research track_ at [SPLC'23](https://2023.splc.net/committees/program-committees/) held in Tokyo. I served also as a PC member for [ASE'23](https://conf.researchr.org/track/ase-2023/ase-2023-papers?) held in Luxembourg.

In 2021, I served as a [co-chair](https://splc2021.net/committees/organization) of the complete _Challenge Track_ (evaluation of new cases but also solutions) at [SPLC'21](https://splc2021.net/) organized in Leicester, England, UK from the 6th to the 11th of September 2021. 

I have served since 2023 as a PC member for the **research track** (the main track) at SPLC and VaMoS 2024.
I have also served as a PC member for the FAT* 2020 conference (now named FAccT) and MaLTeSQuE 2021.

# Event Organization

I was part of the organizing committee of the **VaMoS 2025** held in Rennes. The website is accessible [here (clickable link)](https://familiar-project.github.io/VaMoS2025/).
I was in charge of local arrangements that includes: organizing the gala diner, organizing the social events, finding gifts for participants, helping participating find hotels, etc.

In 2025, I also co-organized a **French summer school** with [Jamal El Hachem](https://www.linkedin.com/in/jamal-el-hachem-a5a5386b/?originalSubdomain=fr)
for the national research group for software engineering led by the CNRS. In French, this group is called GDR GPL.
The **summer school (called EJCP)** was held in Vannes between the 30th of June and the 4th of July. The program is available [here](https://gpl-ejcp.github.io/ejcp2025)
and aims at giving an overview of research activities that can be done in software engineering by inviting various researchers to talk about their experience and research interests.
The school is dedicated to young researchers, often PhD students, so that they can create a national network but also learn more about this broad research field that is software engineering.
About 20 PhD students participated to this edition.
The organization's duty consists of finding rooms to run the summer school, finding facilities such as hotel rooms, food and drinks for lunches and breaks, but also contacting researchers to build the scientific programs. Managing the budget is also a big part of the organization's duty.

# Review activities
I made reviews for:
 * TSE (for Dr. Gilles Perrouin)
 * TOSEM
 * JSS
 * JoT
 * SoSyM
 * IST
 * IEEE Trans.-IFS
 * IEEE Trans. on Reliability
 * SEAMS (for Prof. Jean-Marc Jézéquel)
 * ESEM (for Dr. Mathieu Acher)
 
 In 2019 and 2023, I received a Best Reviewer Award from SoSyM that recognizes me as one of the ["Top 1% of SoSyM Reviewers"](https://www.sosym.org/reviewer_awards/).
 I am now on the [distinguished TOSEM reviewers board](https://dl.acm.org/journal/tosem/distinguished-reviewers-board).
 
   
# Contact me
* paul.temple@irisa.fr

<sup><sub> Last update: September 2025 </sub></sup>
