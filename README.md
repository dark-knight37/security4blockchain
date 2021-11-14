# Security4blockchain
Security4Blockchain

This repository contains some results of our research in automated security modelling and analysis of blockchain protocols by means of model-driven techniques. 

## Motivation
The software here contained is related to a scientific research providing a modelling and analysis framework for the automated security assessment of block chain protocols. In particular, the approach is based on model-driven principles and on the reuse of existing transformational and analysis toolchains.

## Content of the repository
To demonstrate the feasibility of the approach, an application to the case study of the Tweetchain protocol is reported. Up to date, this repository serves as a replication package supporting submitted papers. The repository contains the is structured in the following folders:
* *BCgenericDomainModel*: this folder contains the domain model developed in Papyrus.
* *BCProfile*: this folder contains the UML Profile developed in Papyrus, according to the domain model.
* *tweetChain Protocol UML model*: this folder contains the UML model, developed in Papyrus, annotated with the BCProfile.
* *message_notation_tweetchain.grm*: SableCC grammar specifying the notation for the message/transaction payloads.
* *tweetchain.anb*: AnB notation of the Tweetchain registration scenario, generated with the specified model transformation from UML to AnB.
* *tweetchain_generated.spthy*: Tamarin file as it is generated from tweetchain.anb by means of the approach of Keller.
* *tweetchain_generated_modified.spthy*: tweetchain_generated.spthy where labels are added to ease the analysis.
* *tweetchain_handmade.spthy*: model of the FORSE 2021 paper to allow comparison with generatd model.


## People
* Simona Bernardi - Universidad de Zaragoza
* Stefano Marrone - Università della Campania "Luigi Vanvitelli" (Italy)
* Josè Merseguer - Universidad de Zaragoza
* Mariapia Raimondo - Università della Campania "Luigi Vanvitelli" (Italy)

## Credits
To make and analyse the models, the following software is needed:
* Tamarin Prover v1.6.0 - https://tamarin-prover.github.io/
* Eclipse Papyrus - https://www.eclipse.org/papyrus/
* AnB to Tamarin - https://infsec.ethz.ch/research/software/anb.html

## Acknowledgement
The work of Mariapia Raimondo was formerly funded by the grant "Orio Carlini" for young researchers 2019 - GARR Consortium (Italy). Currently, she is granted by INPS --- Istituto Nazionale di Previdenza Sociale (Italy) - with the XXXVI cycle PhD program.

S. Bernardi and J. Merseguer were supported by the Spanish Ministry of Science and Innovation [ref. PID2020-113969RB-I00].

## Bibliography
Please refer to the following papers:
1. Raimondo, M., Bernardi, S., Marrone, S.; On formalising and analysing the tweetchain protocol; (2021) ICISSP 2021 - Proceedings of the 7th International Conference on Information Systems Security and Privacy, pp. 781-791.
1. Buccafurri, F., Lax, G., Nicolazzo, S., Nocera, A.; Overcoming limits of blockchain for IoT applications; (2017) ACM International Conference Proceeding Series, Part F130521, art. no. a26. DOI: 10.1145/3098954.3098983