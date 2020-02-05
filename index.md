# Presentation

I am currently a post-doc at the PReCISE research center at the University of Namur (UNamur).
I am working on the EoS (Excellence of Science) VeriLearn project with Gilles Perrouin, Patrick Heymans, Benoit Frenay and Pierre-Yves Schobbens.

Previously, I obtained my PhD working at Université de Rennes and IRISA lab in the [DiverSE](http://diverse.irisa.fr/) working group in Rennes (France).
My supervisors were [Mathieu Acher](http://www.mathieuacher.com/) and [Jean-Marc JEZEQUEL](http://people.irisa.fr/Jean-Marc.Jezequel/).
The thesis is entitled: Investigate the Matrix: Leveraging Variability to Specialize Software and Test Suites (more in the PhD topic section).

Furthermore, I am a tennis player. I began to play tennis at 6 until my 18. I stopped to focus on my studies and started again during my PhD.

## Background

After graduating in Computer Science with a fous on Data Image Processing (a 2-years diploma teachning fundamentals of a panel of facets of computer science, including OS, Programming, Mathematics, Web technologies, network managing, Systems design, etc.)from the Institute of Technology of Lannion (France); I went to ESIR (Ecole Supérieure d'Ingénieurs de Rennes, Rennes, France), an engeeniering school where I chose to continue focusing on Data Image Processing.
During the last year of ESIR, I also graduated from the University of Rennes 1 with a Master in Computer Science with a focus on introducing the world of research to student.
Thus, I have a strong background in Data Image Processing (as well as Machine Learning) on one hand and in Softwarer Engineering thanks to my PhD on the other hand.

## Topics of interest
* Software Product Line
* Software Variability
* Software Testing
* Machine Learning
* Computer Vision
* Data Image Processing (as well as Video Processing)
* Computer Graphics


# Research Activities

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

My internship took place in the TEXMEX (now [LinkMedia](http://www-linkmedia.irisa.fr/) )working group under the supervision of [Ewa Kijak](http://www.irisa.fr/texmex/Ewa.Kijak/index_en.php) and [Laurent Amsaleg](http://people.rennes.inria.fr/Laurent.Amsaleg/).
The topic of this internship was the _security of Machine Learning processes applied to multimedia content_ which followed the work of [Thanh-Toan Do](https://sites.google.com/site/thanhtoando2212/) and his PhD.
The goal of this internship was to have a better understanding of how Machine Learning techniques can be influenced in the establishment of their separating functions depending on data that they have seen.
An other concern was how sensitive the establishment of separating functions is w.r.t. the distribution of data points.
This topic is very close to the work conducted by [Battista Biggio](https://pralab.diee.unica.it/en/BattistaBiggio) and the [PRALab](http://pralab.diee.unica.it/en) in Cagliari.


# Publications

* Paul Temple, Mathieu Acher, Jean-Marc Jézéquel. [Empirical Assessment of Multimorphic Testing](https://ieeexplore.ieee.org/document/8755468). IEEE Transactions on Software Engineering (TSE)

* Paul Temple, Gilles Perrouin, Mathieu Acher, Battista Biggio, Jean-Marc Jézéquel, Fabio Roli. Empirical Assessment of Generating Adversarial Configurations for Software Product Lines. EMSE Special Issue (under review)

* Géraldin Nanfack, Paul Temple, and Benoit Frénay. Constraint Enforcement on Decision Trees: a Survey. ACM Computing Surveys (under review)

* Paul Temple, Mathieu Acher, Gilles Perrouin, Battista Biggio, Jean-Marc Jézéquel, Fabio Roli. [Towards Quality Assurance of Software Product Lines with Adversarial Configurations](). Software Product Line Conference (SPLC), Sep 2019, Paris, France

* Paul Temple, Gilles Perrouin, Benoît Frénay, Pierre-Yves Schobbens. [Customizing Adversarial Machine Learning to Test Deep Learning Techniques](https://pure.unamur.be/ws/portalfiles/portal/39547657/Customizing_Adversarial_Machine_Learning_to_test_Deep_Learning_techniques.pdf). 1st Workshop on Deep Learning<=> Testing (co-located with ICSE'19), May 2019, Montréal, Canada

* Paul Temple, Hugo MARTIN, Mathieu ACHER, Jean-Marc Jézéquel. [Applying Multimorphic Testing to Deep Learning Systems](). 1st Workshop on Deep Learning<=> Testing (co-located with ICSE'19), May 2019, Montréal, Canada

* Benoit Amand, Maxime Cordy, Patrick Heymans, Mathieu Acher, Paul Temple, Jean-Marc Jézéquel. [Towards Learning-Aided Configuration in 3D Printing: Feasibility Study and Application to Defect Prediction](https://hal.inria.fr/hal-01990767/document). 13th International Workshop on Variability Modelling of Software-Intensive Systems (VaMoS), Feb 2019, Leuven, Belgium

* Paul Temple, Mathieu Acher, Jean-Marc Jézéquel. [Multimorphic Testing](https://hal.inria.fr/hal-01730163/). 40th International Conference on Software Engineering (ICSE), May 2018, Gothenburg, Sweden  (*Poster Session*)

* Jabier Martinez, Jean-Sébasten Sottet, Alfonso Garcia Frey, Tegawendé Bissyandé, Tewfik Ziadi, Jacques Klein, Paul Temple, Mathieu Acher, Yves Le Traon. [Towards Estimating and Predicting User Perception on Software Product Variants](http://hal.upmc.fr/hal-01720519). International Conference on Software Reuse (ICSR), May 2018, Madrid, Spain

* Mathieu Acher, Paul Temple, Jean-Marc Jézéquel, José Angel Galindo Duarte, Jabier Martinez, Tewfik Ziadi. [VaryLaTeX: Learning Paper Variants That Meet Constraints](https://hal.inria.fr/hal-01659161). 12th International Workshop on Variability Modelling of Software-Intensive Systems (VaMoS), Feb 2018, Madrid, Spain

* Paul Temple, Mathieu Acher, Jean-Marc Jézéquel, Olivier Barias. [Learning Contextual-Variability Models](http://resolver.ebscohost.com/openurl?sid=google&auinit=P&aulast=Temple&atitle=Learning+Contextual-Variability+Models&id=doi%3a10.1109%2fMS.2017.4121211&site=ftf-live). IEEE Software Special Issue on Context Aware and Smart Healthcare, Novembre-Décembre 2017

* Paul Temple, José Angel Galindo Duarte, Mathieu Acher, Jean-Marc Jézéquel. [Using Machine Learning to Infer Constraints for Product Lines](https://hal.inria.fr/hal-01323446). Software Product Line Conference (SPLC), Sep 2016, Beijing, China

* Paul Temple, Mathieu Acher, Battista Biggio, Jean-Marc Jézéquel, Fabio Roli. [Towards Adversarial Configurations for Software Product Lines](https://arxiv.org/abs/1805.12021)

* Paul Temple, Mathieu Acher, Jean-Marc Jézéquel, Léo Noel-Baron, José Galindo. [Learning-Based Performance Specialization of Configurable Systems](https://hal.inria.fr/hal-01467299)

# Program Comitees

I was PC member of the [SPLC'19](https://splc2019.net/) Artifacts Track organized in Paris from the 9th to the 13th of September 2019.

I was PC member of the [1st Workshop on Computational Intelligence for Software Product Lines (CI4SPL)](https://ci4spl.github.io/) which will be held in conjunction with SPLC2018 in September 2018 in Gothenburg, Sweden.

# Review activities
I made reviews for:
 * TSE (for Dr. Gilles Perrouin)
 * JSS
 * SoSyM
 * IEEE T-IFS
 * SEAMS (for Prof. Jean-Marc Jézéquel)
 * ESEM (for Dr. Mathieu Acher)
 
 In 2019, I received a Best Reviewer Award from SoSyM that recognizes me as one of the ["Top 1% of SoSyM Reviewers"](http://www.sosym.org/awards/).
 
# Supervision & Jury Member

I am currently helping in the supervision of two PhD students: Géraldin Nanfack (PhD student under the supervision of Prof. Benoît Frénay) and Sophie Fortz (PhD student under the supervision of Dr. Gilles Perrouin).
During my PhD, I have worked with Clémentine Delambily, Hugo Martin and Léo Noël-Baron; all of them were brillant student helping during summers 2017 and 2018.

In June 2019, I was member of the jury (president jury) at the defense of _Samraa Alzubi_. She defended her Master thesis in cybersecurity entitled _Black-Box Adversarial Reprogramming Attack Against Convolutional Neural Networks Using Genetic Algorithm_.

The same year, I was also involved in the jury evaluating the work of _Simon Genin_ to obtain his Master's degree.
This Master's thesis was supervised by Prof. Benoît Frénay and Prof. Benoît Vanderose.

# Teaching activities

during the universitary year *2019-2020*:
   * Mathematics for Computer Science (Tutoring 15h): basics concepts of Mathematics for Cryptography mainly (modular arithmetic, discrete log, symmetric encryption and asymmetric encryption, elliptic curves); for 2nd year of Bachelor students from the Economics department of the University of Namur, Belgium

during the universitary year *2017-2018*:
   * Programming (Session labs -> 32h): basics of programming (and Object Oriented Programming) in Java to ESIR1 students (equivalent L3 // Bachelor's degree)
   * Modélisation & Développement Industriel or MDI (Session Labs 12h + Tutoring 10h) : UML, Design Pattern, Basics of software testing and Good Practices in the modeling of a system to ESIR2 students (equivalent M1 // first year of master's degree)
   * Software Architecture (Session labs -> 12h) : introduction to containers, component based architecture to ESIR2 students (equivalent M1 // first year of master's degree)

during the universitary year *2016-2017*:
   * Programming (Session labs -> 32h): basics of programming (and Object Oriented Programming) in Java to ESIR1 students (equivalent L3 // Bachelor's degree)
   * Modélisation & Développement Industriel or MDI (Session Labs 12h + Tutoring 10h): Introduction to Design Pattern, UML modeling and Good Practices in the modeling of a system to ESIR2 students (equivalent M1 // first year of master's degree)
   * Validation & Verification (Session labs -> 10h): Software Verification and Validation; software testing and technology to help testing. Adressed to ESIR3 students (equivalent M2 // second year of master's degree)

during the universitary year *2015-2016*:
   * Programming (Session labs -> 32h): basics of programming (and Object Oriented Programming) in Java to ESIR1 students (equivalent L3 // Bachelor's degree)
   * Software Architecture (Session labs -> 2*12h): introduction to containers, component based architecture to ESIR2 students (equivalent M1 // first year of master's degree)
   * Validation & Verification (Session labs -> 10h): Software Verification and Validation; software testing and technology to help testing. Adressed to ESIR3 students (equivalent M2 // second year of master's degree)
   * Introduction to Machine Learning (Session labs -> 12h): Introduction to supervised techniques (SVM, Decision Trees, Bayesian Classifier) and to abductive learning or inferential learning via ALEPH (in Prolog) to INSA students (equivalent M1 // first year of master's degree)

during the universitary year *2015-2014* (at ENSICaen):
   * Programming (Session labs -> 32h): basics of programming (and Object Oriented Programming) in Java to ENSICaen1 students (equivalent L3 // Bachelor's degree)
   * Databases (Session labs -> 32h): SQL databases and requests; PL/SQL to ENSICaen2 students (equivalent M1 // first year of master's degree)
   
# Contact me
* paul.temple@unamur.be
