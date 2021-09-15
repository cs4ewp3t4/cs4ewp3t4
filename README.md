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
     * Preuveneers, D., et al. &quot;TATIS: trustworthy APIs for threat intelligence sharing with UMA and CP-ABE.&quot; Foundations and Practice of Security. 12th International Symposium, FPS 2019, Toulouse, France, November 5–7, 2019, Revised Selected Papers. Vol. 12056. Springer International Publishing; Switzerland, 2020.
     * Preuveneers, D., et al. &quot;Distributed Security Framework for Reliable Threat Intelligence Sharing.&quot; Security and Communication Networks 2020 (2020).
     * Preuveneers, D., and Wouter J. &quot;Sharing Machine Learning Models as Indicators of Compromise for Cyber Threat Intelligence.&quot; Journal of Cybersecurity and Privacy 1.1 (2021): 140-163.

### Scenario 2: Enriching the information on detected threats via TDS cooperation and gathered by means of honeypot instances:
* Online proof-of-concept demonstrators and repositories
     * https://misp1.icar.cnr.it/		[CNR MISP instance]
* Videos:
     * https://github.com/massimo-guarascio/cs4e_ebids_asset 
* Scientific dissemination: 
     * F. Folino, G. Folino, M. Guarascio, F.S. Pisani, L. Pontieri. On learning effective ensembles of deep neural networks for intrusion detection. Information Fusion, 2021, 72, pp.48-69. doi: https://doi.org/10.1016/j.inffus.2021.02.007.
     * M. Guarascio, N. Cassavia, F.S. Pisani, G. Manco. Boosting Cyber Threat Intelligence via collaborative intrusion detection. Submitted to FGCS.

### Scenario 3: Adaptive deployment
* Online proof-of-concept demonstrators and repositories:
     * [INSERT LINK]
* Videos:
     * [INSERT LINK]
* Scientific dissemination: 
     * Pinto Bastos Martins, Maria Inês. 2020. Anomaly Detection in Cybersecurity. Mater Thesis, https://sigarra.up.pt/fcup/pt/pub_geral.show_file?pi_doc_id=275358. 
     * Dinis da Silva e Barbosa, Mário. 2020. JBriareos: A Secure and Scalable Distributed Intrusion Detection System. Master Thesis, https://sigarra.up.pt/fcup/pt/pub_geral.show_file?pi_doc_id=274710. 
