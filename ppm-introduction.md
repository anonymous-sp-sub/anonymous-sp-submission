# Categorization of PPMs
We provide a detailed introduction of each PPM category.

## Content-based PPMs.
### (1) Dynamic Notification (16/117 papers mentioned)
A method that enable users to actively monitor and receive alerts about privacy-related activities. These methods visually present potential instances of personal information collection, often through dashboards[1-2] or communication notifications[3]. This approach ensures that users are informed about their privacy in real time.

### (2) Tangible Privacy (11/117 papers mentioned)
This method provide users with physical mechanisms to control their privacy directly. These systems are typically hardware-based, allowing users to intentionally enable or disable sensors on smart devices. For instance, the work by Do et al.[4] introduces a microphone that only powers on when manually activated by the user, offering a hands-on approach to managing information collection.

### (3) Privacy Label (11/117 papers mentioned)
The privacy label is a form of visual indicators affixed to devices, designed to inform users about data collection practices. These labels explain the types of data being collected based on the device's functions and sensors. Privacy labels take various forms, from privacy notices[5-6] to privacy labels[7].

### (4) Access Control (29/117 papers mentioned)
This method provides users with tools to manage the flow of their personal data. This typically involves the use of management systems that allow for the customization and modification of data collection settings, often with a rule-based frameworks[8-9], such as IFTTT[10].

## System-based PPMs.
### (5) System Design (68/117 papers mentioned)
This approach involves the creation of novel privacy management architectures that differ from traditional authorization, differential privacy or blockchain-based protections. These designs are tailored to the unique challenges of IoT devices, often incorporating fog computing modules or optimizing the computing capabilities of devices to enhance privacy protections[11-12].

### (6) Authorization (26/117 papers mentioned)
This method focus on developing new systems for authentication and access control to isolate and manage sensor data. These methods ensure that only authorized users have access to sensitive information, thereby minimizing unauthorized data collection. Authorization is one of the most pervasive yet complex forms of privacy protection[13-14].

## Algorithm-based PPMs.
### (7) Blockchain (22/117 papers mentioned)
This includes those utilizing decentralized blockchain infrastructures to protect users' privacy. By adopting a blockchain system between users and IoT devices, users could share anonymous data without revealing identifiable information, accessing services securely[15-16]. 

### (8) Differential Privacy (10/117 papers mentioned)
This includes the techniques that adopted k-anonymity or similar differential privacy algorithms in protecting the privacy. By applying differential privacy protections through data obfuscation, users can securely access IoT services without disclosing personal information[17].

### (9) Trading (4/117 papers mentioned)
This method addresses privacy breaches by pricing and exchanging private information which involved users and data buyers. This approach facilitates the effective and protected sharing of privacy information through fair pricing and bidding mechanisms[18]. A key characteristic of this method is the assumption that users willingly share certain information when the transaction is clear and fair.

[1] Windl, Maximiliane, et al. "SaferHome: interactive physical and digital smart home dashboards for communicating privacy assessments to owners and bystanders." Proceedings of the ACM on Human-Computer Interaction 6.ISS (2022): 680-699.
[2] Thakkar, Parth Kirankumar, et al. "“It would probably turn into a social faux-pas”: Users’ and Bystanders’ Preferences of Privacy Awareness Mechanisms in Smart Homes." Proceedings of the 2022 CHI Conference on Human Factors in Computing Systems. 2022.
[3] Mhaidli, Abraham, et al. "Listen only when spoken to: Interpersonal communication cues as smart speaker privacy controls." Proceedings on Privacy Enhancing Technologies (2020).
[4] Do, Youngwook, et al. "Powering for privacy: improving user trust in smart speaker microphones with intentional powering and perceptible assurance." 32nd USENIX Security Symposium (USENIX Security 23). 2023.
[5] Schaub, Florian, et al. "A design space for effective privacy notices." Eleventh symposium on usable privacy and security (SOUPS 2015). 2015.
[6] Colnago, Jessica, et al. "Informing the design of a personalized privacy assistant for the internet of things." Proceedings of the 2020 CHI Conference on Human Factors in Computing Systems. 2020.
[7] Emami-Naeini, Pardis, et al. "Ask the experts: What should be on an IoT privacy and security label?." 2020 IEEE Symposium on Security and Privacy (SP). IEEE, 2020.
[8] Bastys, Iulia, Musard Balliu, and Andrei Sabelfeld. "If this then what? Controlling flows in IoT apps." Proceedings of the 2018 ACM SIGSAC conference on computer and communications security. 2018.
[9] He, Weijia, et al. "Rethinking access control and authentication for the home internet of things ({{{{{IoT}}}}})." 27th USENIX Security Symposium (USENIX Security 18). 2018.
[10] Xu, Rixin, et al. "Privacy leakage in smart homes and its mitigation: IFTTT as a case study." IEEE Access 7 (2019): 63457-63471.
[11] Arruda, Mayke Ferreira, and Renato Freitas Bulcão-Neto. "Toward a lightweight ontology for privacy protection in IoT." Proceedings of the 34th ACM/SIGAPP symposium on applied computing. 2019.
[12] Gupta, Sanonda Datta, et al. "PHIN: a privacy protected heterogeneous IoT network." International Conference on Research Challenges in Information Science. Cham: Springer International Publishing, 2021.
[13] Wilson, Stephen, Nour Moustafa, and Elena Sitnikova. "A digital identity stack to improve privacy in the IoT." 2018 IEEE 4th World Forum on Internet of Things (WF-IoT). IEEE, 2018.
[14] Ali, Inayat, Sonia Sabir, and Zahid Ullah. "Internet of things security, device authentication and access control: a review." arXiv preprint arXiv:1901.07309 (2019).
[15] Awan, Sana, et al. "Poster: A reliable and accountable privacy-preserving federated learning framework using the blockchain." Proceedings of the 2019 ACM SIGSAC conference on computer and communications security. 2019.
[16] Qiu, Ying, et al. "A novel location privacy-preserving approach based on blockchain." Sensors 20.12 (2020): 3519.
[17] Yin, Chunyong, et al. "Location privacy protection based on differential privacy strategy for big data in industrial internet of things." IEEE Transactions on Industrial Informatics 14.8 (2017): 3628-3636.
[18] Barhamgi, Mahmoud, et al. "Enabling end-users to protect their privacy." Proceedings of the 2017 ACM on Asia conference on computer and communications security. 2017.



