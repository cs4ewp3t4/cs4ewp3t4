# Abstract
This page describes the demonstrator that we have set up for CS4E-WP3-T4. The demonstrator is based on a conceptual platform, meant for gathering and managing threat information from different data sources. Basically, the demonstrator has the twofold objective of (i) improving the accuracy of Threat Intelligence Services (such as, e.g., TDSs) in detecting and characterizing incoming attacks, and (ii) enabling the sharing of trusted, reliable and relevant threat information (e.g., discovered by TDSs or gathered by means of honeypots) among organizations and threat detection algorithms.

# Overview
We propose a general framework of interaction and cooperation with threat intelligence services and provided three specific use cases where these services can cooperate. The partners contributed by creating tangible software assets, by integrating them into joint proof-of-concepts, and illustrating the practical feasibility of a modular cybersecurity platform able to provide key information about the status of a system to monitor. This deliverable documented 3 possible integration scenarios, culminating in a variety of videos, online demonstrators and scientific publications. Within these scenarios, we illustrate how such cooperation can (i) improve the performances of the threat prevention and detection systems and minimize the attack surface by strengthening the robustness of machine learning and deep learning models, making them more robust to new threats, false positives and lowering the time to threat detection; and (ii) enable more robust threat intelligence by allowing to better contextualize threat data and devise flexible strategies, methodologies and data formats for collaborative threat intelligence. 


## List of resources

### Scenario 1: Sharing cyberthreat intelligence in a confidential and privacy-preserving manner
*	Online proof-of-concept demonstrators and repositories:
     * https://nuage.cs.kuleuven.be/	[KUL's MISP instance]
     * https://nuage.cs.kuleuven.be/tatis/	[integration with KUL's MISP instance]
     * https://ciel.cs.kuleuven.be/tatis/ 	[integration with CNR's MISP instance]
     * http://155.54.95.184:8082/anonymizer/AnonymizerAPI.html [PP-CTI anonymizer service, integrated with TATIS]
* Videos:
     * https://people.cs.kuleuven.be/~davy.preuveneers/tatis.mp4
* Scientific dissemination: 
     * (Preuveneers and Joosen 2020)
     * (Preuveneers and Joosen 2021)
     * (Preuveneers, Joosen and Bernal Bernabe, et al. 2020).

### Scenario 2: Enriching the information on detected threats via TDS cooperation and gathered by means of honeypot instances:
* Online proof-of-concept demonstrators and repositories
     * https://misp1.icar.cnr.it/		[CNR MISP instance]
* Videos:
     * https://github.com/massimo-guarascio/cs4e_ebids_asset 
* Scientific dissemination: 
     * (Folino, et al. 2021)
     * (Guarascio, et al. 2021)

### Scenario 3: Adaptive deployment
* Online proof-of-concept demonstrators and repositories:
     * [INSERT LINK]
* Videos:
     * [INSERT LINK]
* Scientific dissemination: 
     * (Pinto Bastos Martins 2020)
     * (Dinis da Silva e Barbosa 2020)
