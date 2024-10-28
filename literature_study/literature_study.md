# Literature Study: Best Practices and Challenges in Agile Requirements Engineering

## 1\. Introduction

Modern companies are increasingly adopting agile methodologies to improve their software development processes and respond to changing market demands. Agile practices emphasize iterative and incremental development, collaboration, and flexibility, enabling teams to deliver high-quality software products efficiently. However, the requirements engineering process in agile projects presents unique challenges due to the dynamic nature of agile development and the need to balance customer needs with technical constraints. While agile methodologies offer numerous benefits, they also require organizations to adapt their requirements engineering practices to suit the agile context. In the following study, we explore the major benefits and challenges of requirements engineering in modern agile projects, with an additional focus on large-scale agile system development.

## 2\. Related Work (Appendix Annotation)

Over this study, several researches have been analyzed to understand the current state of agile requirements engineering practices and challenges. Ramesh et al. (2010) \[2\] conducted an empirical study to identify common agile requirements engineering practices and challenges based on data collection and analysis of 16 US software development organizations. In addition, Inayat et al. (2015) \[3\] conducted a systematic literature review on agile requirements engineering practices and challenges, identifying common themes such as customer collaboration, iterative development, and the need for flexible processes. It also included Ranesh's research and confirmed the findings with other researches. These provided a good general understanding of requirements engineering practices in agile projects, although from looking at the date of the publication and the timeline of the reviewed literature, parts of it might be not up-to-date anymore.

Similarly, Curcio et al. (2018) \[4\] conducted a systematic mapping study on requirements engineering in agile software development, focusing on the use of agile practices, tools, and techniques. The mapping of the literature revealed a wide range of newer studies that addressed agile requirements engineering practices.

Lastly, Rashidah et al. (2021) \[1\] conducted an in-depth study on requirements engineering challenges and practices in large-scale agile system development, focusing on the integration of software and hardware development in complex engineering environments, over a elicitation and validation period of two years, plus an analysis period of one year. They identified 24 challenges in requirements engineering for large-scale agile projects, organized into six themes: building and maintaining shared knowledge, representing requirements, integrating requirements into the process, managing cross-cutting concerns, ensuring stakeholder involvement, and adapting to changing requirements. The study proposed solutions to address these challenges, emphasizing the need for tailored approaches to requirements engineering in large-scale agile environments. The thorough study provides in-depth insights into the specific challenges faced by large-scale modern agile projects in the recent years.

## 3\. Research Results (Main Study)

### Traditional Requirements Engineering Methods vs. Agile Requirements Engineering

Traditional requirements engineering methods are often used in the waterfall model where requirements are defined at the beginning of the project and remain relatively stable throughout the development process. It often involves extensive upfront planning, elicitation, detailed documentation, and formal reviews, which can be time-consuming and inflexible \[4\].

In contrast, agile requirements engineering has allowed for more flexibility and adaptability in the requirements engineering process. It allows for requirements to be incomplete in the initial phase of the development process and evolve over time, enabling teams to respond to changing customer needs and market conditions \[2\]. Agile practices emphasize collaboration, communication, and continuous feedback, enabling teams to deliver high-quality software products efficiently and effectively.

### Agile Requirements Engineering Practices

Ramesh et al. \[2\] identified several common agile requirements engineering practices that are widely adopted in agile projects. Inayat et al. \[3\] confirmed the findings with some additions from other researchers. Here are the key practices that could be mostly found in the reviewed literatures:

#### Face-to-face communication over extensive documentation

Traditional methods rely heavily on detailed documentation of requirements specifications, which can be time-consuming and inflexible. Agile methods, on the other hand, emphasize face-to-face communication, tacit knowledge sharing, and minimal documentation to support knowledge sharing and decision-making.

#### Customer Involvement

Agile methods encourage continuous customer involvement throughout the development process, allowing customers to provide timely feedback and make informed decisions about the product. This helps reduce the cost of rework, increase common ownership, and ensure customer satisfaction.

#### Iterative Requirements

The researches found that agile methods involve iterative requirements, where requirements are not fully defined upfront but evolve throughout the requirements process. This allows teams to adapt to changes, incorporate new insights, and deliver valuable features early in the project.

#### Requirements Prioritization

Five studies reveal \[3\], that agile practices prioritize requirements based on their business value, ensuring that the most critical requirements are addressed first. This allows teams to focus on delivering valuable features early in the project and adapt to changing customer needs.

#### Testing before development

Additionally, agile practices emphasize the importance of testing requirements before development to ensure that the requirements are clear, complete, and feasible. This helps identify potential issues early in the development process and reduce the cost of rework.

### Retrospective Meetings

Agile practices often include retrospective meetings with stakeholders at the end of each iteration to reflect on the development process, identify areas for improvement, and make adjustments to the requirements engineering process. This continuous improvement cycle helps teams to refine the requirements if necessary.

## 4\. RE Challenges in Agile Development

Although agile practices offer numerous benefits, they also present unique challenges in requirements engineering. Inayat et al. \[3\] and Curcio et al. \[4\] and Ramesh et al. \[2\] identified several common challenges faced by agile teams in requirements engineering. These could be also confirmed by Rashidah et al. \[1\] in large-scale agile projects. Here are the key challenges that were identified:

### Communication Issues

Communication gaps occur when there is a lapse in providing required information to relevant people. It occurs especially in projects that involve multiple people who are working in multiple teams. Rashidah et al. \[1\] also found that keeping a common understanding of the requirements among all stakeholders is a challenge in large-scale agile projects. It also emphasizes the need for synchronization of development becomes a challenge if there are multiple teams working on different parts of the project. Furthermore, the frequent need to communicate with stakeholders face-to-face can be challenging in distributed teams. Ramesh et al. \[2\] found that in many projects, only the product owner and the development team are co-located, while other stakeholders are mostly not available for face-to-face communication.

### Lack of Documentation

One major issue in agile requirements engineering is the lack of detailed documentation as compared to traditional methods. Agile methods rely on tacit knowledge and face-to-face communication or defining the requirements by defining tests and user stories instead of extensive documentation to prioritize speed. In case of change of team members or stakeholders, this can lead to a loss of knowledge and understanding of the requirements. Rashidah et al. \[1\] also found that companies often struggle to maintain shared knowledge just by constant communication, reading tests or user stories. Ramesh et al. \[2\] also emphasizes the lack of consistency and verifiability of user stories.

### Inappropriate Architecture

Inappropriate architecture can be a consequence of the decisions taken by the team in the early stages of the project. This starts to become problematic when the team is not able to adapt to the changing requirements and the architecture is not flexible enough to accommodate new features. Ramesh et al. \[2\] also found that relying on refactoring could be a risk for the project as it could also lead to a complete rewrite of the system unless you have a team that is constantly occupied with refactoring. Rashidah et al. \[1\] also found that insufficient prior testing of the interaction between software and hardware could cause major changes in the requirements of the infrastructure and lead to a re-architecture of major system components.

### Neglecting of Non-Functional Requirements

Many researchers find that non-functional requirements are often neglected in agile projects due to the focus on delivering functional requirements. Ramesh et al. \[2\] found that non-functional requirements such as performance, security, and usability are often overlooked in agile projects, leading to issues such as poor system performance, security vulnerabilities, and usability problems. Rashidah et al. \[1\] also, that in some companies, the non-functional requirements are defined in the beginning of the project but are not updated anymore during the development process. It becomes difficult to see which non-functional requirements are still valid and which are not.

### Difficulty in Cost and Time Estimation

Agile projects often face challenges in estimating the cost and time required to complete the project due to the iterative and incremental nature of agile development. Ramesh et al. \[2\] found that the lack of detailed requirements and the changing nature of agile projects make it difficult to estimate the cost and time required to complete the project. Rashidah et al. \[1\] also found a concrete example, where some companies were not able to make cost-value tradeoffs based on undefined quality requirements during the development process.

## 5\. Conclusion and Outlook

Agile requirements engineering practices offer numerous benefits, including flexibility, adaptability, and customer satisfaction. However, they also present unique challenges that must be addressed to ensure successful project outcomes. Communication issues, lack of documentation, inappropriate architecture, neglecting non-functional requirements, and difficulty in cost and time estimation are common challenges faced by agile teams in requirements engineering.

### Excluded literature and Future Exploration (Annotation Exploration)

More literature came up during the research that looked highly interesting, but were excluded as it would go over the scope of this study. For example, Wang et al. (2014) \[5\] conducted an empirical study on the role of requirements engineering practices in agile development by surveying companies. Although, due to the nature of surveys not being a primary methodology of research, the study was excluded from the main study. Schön et al. (2017) \[6\] also conducted a study on key challenges in agile requirements engineering, by doing workshops with 26 experts in the field of agile software development. While it has some interesting insights, it didn't include "real life" cases for the study compared to Rashidahh's \[1\] research.

Another research of Schön et al. (2017) \[7\] conducted a systematic literature review on agile requirements engineering that also explored newer papers that were not included in Inayat et al. \[3\] and Curcio et al. \[4\]'s studies. It also explores researches that conducted studies on the elicitation of non-functional requirements in agile projects, which would have been interesting to include in the study but was excluded due to the focus on large-scale agile projects in Rashidahh's study and limited time.

For future work, research on solutions for these challenges could be conducted. Rashidah et al. \[1\] proposed solutions to address each of these challenges but they also seemed to be very specific to the explored large-scale agile projects and being proposed by the specific companies that were involved in the research. A more general approach could be taken to find solutions that could be applied to a wider range of large-scale agile projects.

# Sources

\[1\] Rashidahh Kasauli, Eric Knauss, Jennifer Horkoff, Grischa Liebel, Francisco Gomes de Oliveira Neto, Requirements engineering challenges and practices in large-scale agile system development, Journal of Systems and Software, Volume 172, 2021, 110851, ISSN 0164-1212, [https://doi.org/10.1016/j.jss.2020.110851](https://doi.org/10.1016/j.jss.2020.110851). ([https://www.sciencedirect.com/science/article/pii/S0164121220302417](https://www.sciencedirect.com/science/article/pii/S0164121220302417))

\[2\] Ramesh, B., Cao, L. and Baskerville, R. (2010), Agile requirements engineering practices and challenges: an empirical study. Information Systems Journal, 20: 449-480. [https://doi.org/10.1111/j.1365-2575.2007.00259.x](https://doi.org/10.1111/j.1365-2575.2007.00259.x)

\[3\] Irum Inayat, Siti Salwah Salim, Sabrina Marczak, Maya Daneva, Shahaboddin Shamshirband, A systematic literature review on agile requirements engineering practices and challenges, Computers in Human Behavior, Volume 51, Part B, 2015, Pages 915-929, ISSN 0747-5632, [https://doi.org/10.1016/j.chb.2014.10.046](https://doi.org/10.1016/j.chb.2014.10.046). ([https://www.sciencedirect.com/science/article/pii/S074756321400569X](https://www.sciencedirect.com/science/article/pii/S074756321400569X))

\[4\] Karina Curcio, Tiago Navarro, Andreia Malucelli, Sheila Reinehr, Requirements engineering: A systematic mapping study in agile software development, Journal of Systems and Software, Volume 139, 2018, Pages 32-50, ISSN 0164-1212, [https://doi.org/10.1016/j.jss.2018.01.036](https://doi.org/10.1016/j.jss.2018.01.036). ([https://www.sciencedirect.com/science/article/pii/S0164121218300141](https://www.sciencedirect.com/science/article/pii/S0164121218300141))

\[5\] Wang, X., Zhao, L., Wang, Y., Sun, J. (2014). The Role of Requirements Engineering Practices in Agile Development: An Empirical Study. In: Zowghi, D., Jin, Z. (eds) Requirements Engineering. Communications in Computer and Information Science, vol 432\. Springer, Berlin, Heidelberg. [https://doi.org/10.1007/978-3-662-43610-3\_15](https://doi.org/10.1007/978-3-662-43610-3_15)

\[6\] Schön, EM., Winter, D., Escalona, M.J., Thomaschewski, J. (2017). Key Challenges in Agile Requirements Engineering. In: Baumeister, H., Lichter, H., Riebisch, M. (eds) Agile Processes in Software Engineering and Extreme Programming. XP 2017\. Lecture Notes in Business Information Processing, vol 283\. Springer, Cham. [https://doi.org/10.1007/978-3-319-57633-6\_3](https://doi.org/10.1007/978-3-319-57633-6_3)

\[7\] Eva-Maria Schön, Jörg Thomaschewski, María José Escalona, Agile Requirements Engineering: A systematic literature review, Computer Standards & Interfaces, Volume 49, 2017, Pages 79-91, ISSN 0920-5489, [https://doi.org/10.1016/j.csi.2016.08.011](https://doi.org/10.1016/j.csi.2016.08.011). ([https://www.sciencedirect.com/science/article/pii/S0920548916300708](https://www.sciencedirect.com/science/article/pii/S0920548916300708))  