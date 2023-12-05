# LAMP-Stack-Training-System-
Building a system for the DoD military personnel to take courses

**Project Description:** For the purpose of this project, we suppose we own a company **TarbariTech Inc._**, and we have won a contract to support the **Department of Defense (DoD)**. The contract requires **_TarbariTech Inc._** to develop a cloud-based system to support the military personal training. The system will process, store, and transmit Controlled Unclassified Information (**CUI**), Electronic Protected Health Information (**ePHI**), and **payment card information**. We have chosen to leverage a **L.A.M.P(Linux, Apache, MySQL, PHP) Stack** for the development of the system.

For the planning, documentation, development, and monitoring of the system, we are going to follow the [NIST Risk Management Framework (**RMF**)](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-37r2.pdf).

The NIST RMF will help us manage the system we ar edeveloping from inception to disposal, in short the System Developement Lifecycle (**SDLC**). The definition provided by **NIST** is "_RMF provides a comprehensive, flexible, repeatable, and measurable 7-step process that any organization can use to manage information security and privacy risk for organizations and systems and links to a suite of NIST standards and guidelines to support implementation of risk management programs to meet the requirements of the Federal Information Security Modernization Act (**FISMA**)._"
The 7 steps from the RMF we are going to follow for the implementation of the project are: 
1. Prepare: we'll define essential activities to prepare the DoD to manage security and privacy risks.
2. Categorize: we'll categorize the system and information processed, stored, and transmitted based on a Business Impact Analysis (**BIA**).
3. Select: We'll select the essential NIST SP 800-53 controls to protect the system based on risk assessments.
4. Implement: We'll be implementing the selected controls and document how controls are deployed
5. Assess: We'll assess to determine if the the controls are in place, operating as intended, and producing the desired results.
6. Authorize: Senior official (us in this case) makes a risk-based decision to authorize the system to operate.
7. Monitor: We'll continuously monitor control implementation and risks to the system.

** **NOTE:** For the SDLC methodology, I am currently thinking about the Prototyping model, that is 'we are assuming that we are only developing an understanding of the system requirements without actually developing a final operational system. However, if I feel the time allows us, we will switch to the **Waterfall model;** meaning we will actually develop the system. 

** Frameworks we will need to comply with:
-NIST SP  800-39
- HIPAAH
- PCI DSS
- FedRAMP
- ISO 27001
