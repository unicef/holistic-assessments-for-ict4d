# DHIS2 "The Open Platform"

<figure><img src="../../.gitbook/assets/tech-2 open.png" alt="" width="100%"><figcaption></figcaption></figure>

_This solution is an "open platform" in that it provides a foundation for almost any kind of health and data application to be built upon. The work to be done is NOT ONLY configuration and deployment, but also customization and software development. However, there is also an ecosystem of third-party solutions and vendors that can be utilized to build a complete solution._


[<i class="bi bi-cloud-download"></i> Download DHIS2 Report (PDF)](../../assets/reports/DHIS2-Holistic-Assessment-Report-v1-FINAL-PUBLIC.pdf){.btn-action-primary .btn .btn-warning .btn-lg role="button"}

<br />
<mark class="purple">🕵️**The Assessment Outcome**</mark>

We found this solution to be stable and ready for implementation. It is a free, open-source software platform designed for reporting, collecting, analyzing, and disseminating individual-level and aggregated data. Although not specifically designed for the specific area of function we were assessing (Civil Registration and Vital Statistics or [CRVS](../../glossary.md)), it can integrate with many systems or be extended to include custom features and applications. Implementing interoperability can be costly in terms of both initial integration and long-term operation and maintenance. We also assessed the additional costs associated with combining this software with an external system.

The software, provided as a global public good to support sustainable development goals, includes a suite of visualization and analysis tools, making it effective for linking data for reporting and tracking purposes. It can be hosted locally on various devices or in the cloud and is most commonly used for health data. It integrates with various other software and tools through its Application Programming Interface (API) and is deployed in 75 low- and middle-income countries, with over 100 NGOs having implemented it.&#x20;

> ### <mark class="yellow-bg">**The solution fits many contexts and use cases, such as logistics, education, COVID-19 vaccine tracking, agriculture projects, e-governance, food and nutrition, and more**</mark><mark class="yellow-bg">.</mark>&#x20;

Our assessment involved reviewing publicly available documentation, attending virtual meetings, leveraging resources on YouTube and their community resources page, and testing a local cluster using the command line tool. We deployed an instance to test vulnerabilities and dependencies, created a Software Bill of Materials (SBOM) for the codebase, audited the architecture deployed in AWS, and conducted various vulnerability scans and penetration tests. Despite some scheduling difficulties, the team has been responsive and engaged, providing feedback and clarity.

<mark class="orange">**🔍 Discovered during the Assessment:**</mark>

The solution is highly adaptable, and capable of being customized to suit a variety of use cases. Its extensive configurability and the developers' efforts in adding multiple extension points for new functionalities suggest it could be effectively transformed into a robust CRVS system. However, this specific functionality is not currently available and would need to be developed before the system could be adopted for CRVS purposes. Our assessment uncovered a number of security enhancements which would be strongly recommended if adopted.

<mark class="yellow-bg">**🖍 Recommendations & Actions:**</mark>&#x20;

With such an adaptable solution, any implementing partner must think critically about the user workflows and roles before adoption, ensuring the solution fits their contextual needs. Ongoing cost considerations, as well as implementing an interoperable solution, will require significant technical and financial resources coupled with updated documentation. Finally, security remains a critical component of any adopted CRVS system. Therefore, a set of recommendations for strengthening infrastructure and source code were provided. Some fixes have been implemented and recommendations were received warmly.&#x20;
