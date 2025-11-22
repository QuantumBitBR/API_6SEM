<img width="1584" height="396" alt="_LOCAL TRACKER" src="https://github.com/user-attachments/assets/0da22fc4-df78-411e-bba4-7cef9ce65c0d" />

<div align=center>
     <a href="#sobre">Problem and Solution |</a>
     <a href="#equipe">Contributers |</a>
     <a href="#requisitos">Functional Requirements|</a>
     <a href="#backlog">Product Backlog |</a>
     <a href="#cronograma">Release Schedule |</a>
     <a href="#tecnologias">Technologies</a>  
</div>

<span id="sobre">
  
## Problem
<p>Currently, users rely on a ticketing system to receive support and resolve recurring issues. This model, however, presents important challenges. A considerable number of tickets are repetitive, referring to problems that have already been identified and solved, which generates unnecessary rework for the support team. Consequently, the team’s efforts are often consumed by low-complexity requests, reducing their ability to focus on critical incidents and new demands. Furthermore, the information related to recurring problems is fragmented, limiting the generation of managerial insights and making it difficult to analyze trends, identify bottlenecks, and explore opportunities for improvement.
</p>

## Solution
<p>
The solution is an intelligent support management platform designed to optimize customer service operations. It combines advanced ticket search, automated strategic insights, AI-driven trend analysis, and robust data anonymization to ensure full compliance with LGPD.
By automatically generating insightful reports, the platform not only reduces repetitive work but also empowers organizations with actionable data to guide strategic decision-making. Over time, the service history is transformed into a valuable source of corporate intelligence, enabling continuous improvement, greater efficiency, and smarter business outcomes.
</p>

## Docs Directory

- <a href="https://github.com/QuantumBitBR/API_6SEM/wiki/User-guide"/>User guide</a>
- <a href="https://github.com/QuantumBitBR/API_6SEM/wiki/Installation-Guide-%E2%80%93-API_6SEM">Instalation guide</a>
- <a href="https://github.com/QuantumBitBR/API_6SEM/wiki/Development-Standards">Development standards</a>
- <a href="https://quantumbitbr.atlassian.net/jira/software/projects/QB/boards/1/backlog?atlOrigin=eyJpIjoiZTdlNzkwMTZkNmNkNDY5Y2I1ZTVkYTI0ZDlmMWUzODEiLCJwIjoiaiJ9" >Jira</a>
- <a href="https://github.com/QuantumBitBR/API_6SEM_BACK" >Back-end Repository</a>
- <a href="https://github.com/QuantumBitBR/API_6SEM_FRONT" >Front-end Repository</a>
- <a href="https://www.figma.com/design/Bj4I4neHqiob9svy5Pw7nj/6SEM_Wireframe?node-id=0-1&t=DrLhuD78MEdMlUF0-1">Figma - WireFrame</a>
- <a href="https://colab.research.google.com/drive/1MeHgPQNOjSO6QcSH3VmlZtNALWgi6mm8?usp=sharing">Artificial Intelligence Training</a>
- <a href="https://github.com/QuantumBitBR/API_6SEM/wiki/Sprint-1">Sprint 1</a>
- <a href="https://github.com/QuantumBitBR/API_6SEM/wiki/Sprint-2">Sprint 2</a>
- <a href="https://github.com/QuantumBitBR/API_6SEM/wiki/Sprint-3">Sprint 3</a>
<span id="requisitos">
     
## Functional Requirement
<details>

<summary>Click here</summary>

| ID   | Functional Requirement (EN) | Detailed Description (EN) | Expected Benefits (EN) |
|------|-----------------------------|---------------------------|------------------------|
| FR1  | Allow ticket search by keywords | The system must allow users to search tickets using one or multiple keywords, returning all results that contain the searched terms. The functionality should offer speed and accuracy, enabling sorting of results to facilitate ticket analysis and tracking. | - Users can quickly find relevant tickets without manually navigating large volumes of data.<br>- Facilitates identification of patterns, recurring issues, and critical areas.<br>- Provides fast access to relevant information for prioritizing actions or responses to customers. |
| FR2  | Process data according to LGPD before use | The system must properly process any personal information contained in tickets, such as names, emails, CPF, or other sensitive data, before storing or using it. Additionally, it must allow users to request deletion of their data at any time, ensuring that such requests are handled in accordance with LGPD. This approach ensures the protection of user privacy and compliance with legal obligations. | - Complies with LGPD requirements, avoiding penalties and legal risks.<br>- Minimizes risk of leakage or misuse of sensitive information.<br>- Shows users that their data is handled responsibly and that they can exercise their rights to deletion.<br>- Ensures data is processed and stored securely, reducing vulnerabilities. |
| FR3  | Revoke permission to use data | The system must ensure that when a user requests the removal of their data, all personal or sensitive information related to them is deleted in accordance with LGPD. This guarantees the protection of personal data and compliance with legal privacy obligations. | - Protection of personal and sensitive data, preventing unauthorized access.<br>- Compliance with LGPD and other applicable data protection regulations. |
| FR4  | Generate insights from historical database | The system must analyze the ticket history and generate insights related to ticket quantities by company, product, status, category, department, and SLAPlan. This analysis should be presented through interactive dashboards, allowing clear visualization of patterns, trends, and potential bottlenecks in ticket handling. | - Identification of bottlenecks and areas requiring process improvements.<br>- Effective monitoring of SLA compliance and prioritization of critical tickets.<br>- Supports data-driven decision making.<br>- Increases operational efficiency and continuous improvement in customer service.<br>- Clear and fast visualization of trends and patterns across multiple dimensions. |
| FR5  | Role-based access control | The system must ensure that only authorized users can access ticket insights and manage related data. This includes roles such as administrators, support managers, and other predefined positions. Access control must be permission-based, ensuring each user sees only information compatible with their authorization level. | - Protection of sensitive and strategic company information.<br>- Ensures that only authorized personnel can make decisions or act on data.<br>- Reduces risks of information leakage or misuse.<br>- Compliance with information security standards and internal data governance policies.<br>- Builds user confidence, knowing critical data is protected. |
| FR6  | Generate trend insights of tickets per product over time | The system must use artificial intelligence to analyze the history of tickets for each product and identify trends over time. This functionality will allow monitoring of complaint volumes, incidents, or support requests, highlighting patterns and significant peaks. | - Proactive visibility on emerging issues for specific products.<br>- Quick identification of patterns and anomalies in tickets.<br>- Supports strategic decision-making and prioritization of corrective actions.<br>- Greater efficiency in managing support and preventing negative impacts. |


</details>

<span id="backlog">
     
## Product Backlog

| Rank | Priority | User Story (EN) | Related Requirements | Estimate | Sprint |
|------|---------|-----------------|--------------------|---------|--------|
| 1 | High | As a user, I want to receive quantitative insights from the historical database on ticket quantities by company, product, status, and category, so that I can make better strategic decisions without relying on complex dashboards. | FR4 | 8 | 1 |
| 2 | High | As an administrator, I want personal data to be processed and stored only as long as necessary, and completely deleted when no longer required or upon request, so that the system complies with LGPD and user privacy is guaranteed. | FR2 | 7 | 1 |
| 3 | High | As an administrator, I want to delete user data upon a deletion request, ensuring protection of personal information and compliance with LGPD. | FR3 | 6 | 1 |
| 4 | High | As a user, I want to search tickets by keywords so that I can quickly locate old tickets, identify patterns, track ticket history, and resolve issues more efficiently. | FR1 | 8 | 1 |
| 5 | Medium | As a user, I want to receive quantitative insights from the historical database on ticket quantities by department, SLAPlan and priorities so that I can make better strategic decisions without relying on dashboards. | FR4 | 6 | 2 |
| 6 | Medium | As a user, I want the system to use artificial intelligence to analyze the history of tickets for each product, so that patterns, trends, and peaks in complaint or incident volumes are automatically identified. | FR6 | 9 | 2 |
| 7 | Medium | As a user, I want to filter the dashboards by periods and flags such as company, product, period and categories, so that I can quickly analyze specific scenarios, identify patterns, and make better data-driven decisions. | FR4 | 5 | 2 |
| 8 | Medium | As a user, I want to apply predefined filters in the ticket search, such company, product, status, priority, category, and subcategory, so that I can reduce search time, focus only on the most relevant cases, and avoid manually configuring filters every time I perform an analysis. | FR4 | 8 | 2 |
| 09 | Low | As a user, I want the system to generate written reports based on AI-provided insights, so that I can easily understand patterns, trends, and peaks in tickets and share this information clearly with my team or managers. | FR6 | 8 | 3 |
| 10 | Low | As a system administrator, I want only authorized users to access ticket insights and manage related data, so that sensitive information is protected and each user sees only data compatible with their authorization level. | FR5 | 4 | 3 |
| 11 | Low | As a user, I want to visualize the tickets linked to dashboards so that I can understand which tickets are impacting the process. |FR1, FR4 | 5 | 3 |


<span id="cronograma">

## Release Schedule

Sprint| Start| End  
--- | --- | ---
Kick off | 25/08/2025| -------------
Sprint 1| 08/09/2025 | 28/09/2025 
Sprint 2| 06/10/2025| 26/10/2025
Sprint 3| 03/11/2025| 23/11/2025 
Solution Fair | 04/12/2025 | -------------

<span id="equipe">
     
## Contributers

| Name | Role | Networking | Identification |
| -----| ---------| ----------------| ---------|
André Filipe | Scrum Master | <a href="https://github.com/AndreMeneses0103"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a><a href="https://www.linkedin.com/in/andre-meneses-dev/"><img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a> | <a href="" ><img src="https://github.com/TechHorizonBR/API_3SEM/assets/89109574/ca09a732-b248-41dc-ab7c-145822ffd74b" width="60"></a> |
Cainan Thomas | Developer | <a href="https://github.com/Kainanthyz"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a><a href="https://www.linkedin.com/in/cainan-santos-70938094/"><img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>| <a href="" ><img src="https://avatars.githubusercontent.com/u/91689791?v=4" width="60"></a>
Gilvane Amaro | Developer | <a href="https://github.com/gilvaneamaro"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white5" alt="GitHub"></a> <a href="https://www.linkedin.com/in/gilvane-amaro/"><img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a> |<img src="https://avatars.githubusercontent.com/u/121205315?v=4" width="60">|
Gabriel Mota | Developer | <a href="https://github.com/gabmota88"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white5" alt="GitHub"></a> <a href="https://www.linkedin.com/in/gabriel-mota-4a0816a0/"><img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a> |<img src="https://avatars.githubusercontent.com/u/44507787?v=4" width="60">|
Jhony Santos | Product Owner | <a href="https://github.com/santosjhony12"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a><a href="https://www.linkedin.com/in/jhony-santos-de-souza-920229238"><img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a> |<img src="https://avatars.githubusercontent.com/u/123211025?v=4" width="60">|


<span id="tecnologias">

## Used Technologies

![WhatsApp Image 2025-10-26 at 19 11 18](https://github.com/user-attachments/assets/3d327c62-65dc-4822-ad10-b8db9fe3a088)



