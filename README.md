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
<p>The proposal is to implement an intelligent knowledge search system that reduces repetitive ticket openings by providing quick and relevant consultations in a historical database of problems and solutions. The system works by processing the existing ticket database and enabling intelligent keyword searches, allowing end users to find answers autonomously. All consultations are recorded in real time, which not only improves operational efficiency but also generates valuable insights for both operational and managerial decision-making.
</p>

## Docs Directory

- <a href=""/>User guide</a>
- <a href="">Instalation guide</a>
- <a href="https://github.com/QuantumBitBR/API_6SEM/wiki/Development-Standards">Development standards</a>
- <a href="https://github.com/QuantumBitBR/API_6SEM/wiki/Sprint-1">Sprint 1</a>



<span id="requisitos">
     
## Functional Requirement
<details>

<summary>Click here</summary>

| **ID**  | **Functional Requirement**                       | **Detailed Description**                                                                                                                                                                                                 |
| ------- | ------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **FR1** | Allow ticket search by keywords                  | The system must allow users to search for tickets using one or multiple keywords, returning results.                        |
| **FR2** | Process data according to LGPD before use        | Before storing or using ticket data, the system must process and anonymize any personal information (names, emails, IDs). It must also allow data removal upon user request, ensuring compliance with LGPD.              |
| **FR3** | Record user-performed queries                    | Every query executed by a user must be recorded with metadata (timestamp, keywords used, and user type). This log will be used to generate statistics, identify recurring issues, and provide feedback for improvements. |
| **FR4** | Revoke data usage permission | The system must revoke viewing permissions and anonymize the data for which access has been revoked.       
| **FR5** | Generate insights based on history database     | The system must generate insights based on history database for process improvement with dashboards.
| **FR6** | Generate suggestive insights from tool usage     | The system must analyze user interactions (most common queries, unused suggestions, repeated searches) and generate suggestive insights for process improvement, without requiring dashboards.                           |
| **FR7** | Enable quick view of the most accessed solutions | The system must highlight and display the most accessed solutions in real time, allowing quick access to frequently used knowledge. This helps reduce response time and training needs.                                  |
| **FR8** | Feedback on solutions | The system must allow users to provide feedback (useful/not useful) on the suggested solutions to improve relevance over time.
| **FR9** | Role-based access control | The system must ensure that only authorized users (e.g., admins, support managers) can view insights and manage data.

</details>

<span id="backlog">
     
## Product Backlog

| **Rank** | **Priority** | **User Story** | **Related Requirements** | **Estimate** | **Sprint**
 ------ | ------------------------- |  ------------------------- | ------------------------ | ----- | ----|
1 | High | As a support manager, I want to receive quantitative insights from the historical knowledge base regarding ticket counts by company, product, status, and category, so that I can make better strategic decisions without relying on complex dashboards. | FR5 | 8 | 1
2 | High | As an administrator, I want data to be processed and stored anonymously before use to ensure LGPD compliance.                                           | FR2                 | 7 | 1
3 | High | As an administrator, I want to anonymize user data upon deletion requests so that personal information is protected while ensuring compliance with LGPD. | FR4 | 6 | 1
3 | High | As a user, I want to search tickets by keywords to quickly find old tickets.                                                               | FR1            | 4 | 1
4| Medium | As a support agent, I want the system to suggest solutions based on previous tickets to solve problems faster and reduce rework.                        | FR6         | 6 | 2
5| Medium | As a user, I want to record that I used certain information to feed the insights database.                                                              | FR3, FR5       | 3 | 2
6 | Medium | As a user, I want the system to return solutions ranked by relevance so that I can find the most useful answers quickly.                              | FR6          | 5 | 2
7| Medium | As a support manager, I want to receive suggestive insights generated dynamically from ongoing system usage so that I can adapt my strategies based on current user behavior without relying on complex dashboards. | FR6                | 9 | 2
8 | Low | As an administrator, I want the insights to be viewable by support team level to ensure the most efficient distribution of information.               | FR7, FR9      | 6 | 3
9 | Low | As a user, I want to provide feedback on returned solutions to evaluate answers and improve the knowledge base.                                         | FR8                 | 2 | 3
10| Low | As a support user or manager, I want to feed the knowledge base with new problems and solutions that arise over time.                                   | FR3, FR8                | 5 | 3

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
Cainan Thomas | Developer | <a href="https://github.com/Kainanthyz"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a><a href="https://www.linkedin.com/in/cainan-santos-70938094/"><img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>| <a href="" ><img src="https://media.licdn.com/dms/image/v2/D4D03AQE1W01zaQS6EQ/profile-displayphoto-scale_200_200/B4DZjUS3Y8GkAY-/0/1755908372844?e=1759363200&v=beta&t=vj2Kb0yljMgSpZDqg_ibKKuDa79diCLTsg5T6_4lCkc" width="60"></a>
Gilvane Amaro | Developer | <a href="https://github.com/gilvaneamaro"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white5" alt="GitHub"></a> <a href="https://www.linkedin.com/in/gilvane-amaro/"><img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a> |<img src="https://avatars.githubusercontent.com/u/121205315?v=4" width="60">|
Gabriel Mota | Developer | <a href="https://github.com/gabmota88"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white5" alt="GitHub"></a> <a href="https://www.linkedin.com/in/gabriel-mota-4a0816a0/"><img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a> |<img src="https://avatars.githubusercontent.com/u/44507787?v=4" width="60">|
Jhony Santos | Product Owner | <a href="https://github.com/santosjhony12"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a><a href="https://www.linkedin.com/in/jhony-santos-de-souza-920229238"><img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a> |<img src="https://avatars.githubusercontent.com/u/123211025?v=4" width="60">|


<span id="tecnologias">

## Used Technologies

<img width="1584" height="396" alt="Readme TechHorizon 2S" src="https://github.com/user-attachments/assets/900a98d4-70d7-4f41-b4b8-8ed50e94a7cb" />



