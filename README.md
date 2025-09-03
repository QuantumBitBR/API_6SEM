<img width="1584" height="396" alt="_LOCAL TRACKER" src="https://github.com/user-attachments/assets/0da22fc4-df78-411e-bba4-7cef9ce65c0d" />

<div align=center>
     <a href="">Front-end |</a>
     <a href="">Back-end |</a>
     <a href="#sobre">Sobre |</a>
     <a href="#equipe">Contribuidores |</a>
     <a href="#requisitos">Requisitos Funcionais e Não Funcionais |</a>
     <a href="#backlog">Product Backlog |</a>
     <a href="#cronograma">Cronograma de Entregas |</a>
     <a href="#resumo">Resumo das Sprints |</a>
     <a href="#tecnologias">Tecnologias</a>
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
- <a href="">Development standards</a>
- <a href="">Sprint 1</a>

## Functional Requirement and Non-Functional Requirements
<details>

<summary>Click here</summary>

| ID | Requirement |
| ----| --------| 
| FR1 | Allow ticket search by keywords.
| FR2 | Process data according to LGPD before use.
| FR3 | Record user-performed queries.
| FR4 | Return suggested solutions based on history.
| FR5 | Generate suggestive insights from tool usage.
| FR6 | Enable quick view of the most accessed solutions.
| NR1 | Ensure real-time response performance.
| NR2 | Ensure data security and privacy (LGPD compliance).
| NR3 | Provide high system availability.
| NR4 | Offer a simple and intuitive user interface.
</details>


| **Rank** | **Priority** | **User Story** | **Related Requirements** | **Estimate** | **Sprint**
 ------ | ------------------------- |  ------------------------- | ------------------------ | ----- | ----|
1| High | As a user, I want to search tickets by keywords or questions to quickly find old tickets.                                                               | FR1, NR1, NR4            | 7 | 1
2| Medium | As a user, I want the search to consider synonyms and meanings (semantic search) so I don’t miss relevant answers even if they are written differently. | FR1, FR4, NR1            | 8 | 1
3| High | As a support agent, I want the system to suggest solutions based on previous tickets to solve problems faster and reduce rework.                        | FR4, FR6, NR1            | 7 | 1
4| Medium | As a user, I want to record that I used certain information to feed the insights database.                                                              | FR3, FR5, NR1            | 3 | 2
5 | Medium | As a user, I want the system to return solutions ranked by relevance so that I can find the most useful answers quickly.                              | FR4, FR6, NR1          | 5 | 2
6| Low | As a user, I want to provide feedback on returned solutions to evaluate answers and improve the knowledge base.                                         | FR3, FR5                 | 2 | 2
7| High | As a support manager, I want to receive suggestive insights from system usage to make better strategic decisions without relying on complex dashboards. | FR5, NR1                 | 9 | 3
8| Low | As a support user or manager, I want to feed the knowledge base with new problems and solutions that arise over time.                                   | FR3, FR4                 | 5 | 3
9 | Medium | As an administrator, I want the insights to be viewable by support team level to ensure the most efficient distribution of information.               | FR5, NR4, NR1      | 6 | 3
10 | High | As an administrator, I want data to be processed and stored anonymously before use to ensure LGPD compliance.                                           | FR2, NR2                 | 5 | 1

