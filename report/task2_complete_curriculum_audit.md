# Task 2 — Curriculum Audit and Redesign Proposal
## B.Tech CSE (Artificial Intelligence) | Student-led review

**Prepared:** 24 October 2026  
**Basis:** My SIS subject list, my own learning and project experience, three dated job descriptions, and AI-assisted exercises documented in this report.

## Executive summary

I reviewed my B.Tech CSE (AI) curriculum against three entry-level job descriptions: Data Analyst Trainee, AI/ML Engineer, and Full Stack Developer. My curriculum gives me a broad foundation across programming, databases, mathematics, AI/ML, web technologies, data handling, and cloud computing. My experience also shows where I want more applied practice: dashboard development, practical Generative AI work, big-data processing, API integration, testing, version control in team projects, and end-to-end deployment.

I recommend keeping the core programming and algorithm foundations, improving the practical work in existing subjects, and integrating a small number of cross-subject labs rather than adding a separate course for every tool. My independently developed **GenAI Weather Intelligence System**, which uses the OpenWeather and Groq APIs, is the practical project example in this audit. I did not seek faculty or graduate feedback; that limitation is stated explicitly.

## Scope and approach

1. I organized the subject list I provided from my ICFAI SIS for Semesters 1–7 and Semester 8 Internship (IP-2).
2. I compared my learning and practical experience with three job descriptions accessed on 23 October 2026.
3. I identified ten specific KEEP, UPDATE, ADD/INTEGRATE, or conditional REDUCE recommendations.
4. I documented five AI-assisted AI/ML learning exercises, including prompts, output summaries, verification, and sources.
5. I proposed a credit-neutral redesign target affecting **22% of the programme’s official credits**, with equal credits reallocated from duplicated or lower-priority coverage into practical work. I have not treated semester workload/unit totals as credits. Because the exact credit ledger for my cohort is not established by the subject list alone, the report expresses the calculation as a formula rather than inventing a numeric total: if the official programme total is **T credits**, the target reallocation is **0.22 × T credits**, and the programme total remains **T credits**.

## Credit-neutral redesign proposal (22% target)

The redesign target is to affect 22% of the programme’s official credits while keeping the overall programme total unchanged. The intention is to rebalance how learning time is used, not to increase the total credit requirement.

| Proposed destination for reallocated credit | Share of total programme credits | What students would do |
|---|---:|---|
| Practical data analysis: SQL, data cleaning, Excel, visualization, and reporting | 5% of T | Complete one end-to-end analysis using a real or carefully prepared dataset. |
| ML model evaluation and reliability | 5% of T | Compare baseline models, select suitable metrics, check leakage, and perform error analysis. |
| Applied Generative AI / NLP | 4% of T | Build a small API-based LLM application and evaluate its outputs against a prepared test set. |
| API integration, testing, Git, and secure development | 4% of T | Build and test an API, manage secrets correctly, and use version control. |
| Integrated capstone/project work | 4% of T | Connect a user interface, external API or model, data handling, testing, documentation, and a deployment plan. |
| **Total reallocated to practical learning** | **22% of T** | **0.22 × T credits** |

**Balanced offset:** Reallocate the same 22% of T from repeated introductory coverage and assessment time that can be converted to applied work, but only after mapping learning outcomes across Artificial Intelligence, Machine Learning, Soft Computing, Predictive Analytics, Generative AI, and related subjects. A proposed offset should not remove essential theory, mathematical foundations, core algorithms, ethics, or required accreditation content.

**Balance calculation:**  
- Existing official programme total = **T credits**  
- Reallocated away from overlapping/repetitive delivery = **0.22T credits**  
- Reallocated into practical labs and projects = **0.22T credits**  
- Revised total = **T − 0.22T + 0.22T = T credits**  
- Share of programme credits affected = **0.22T / T × 100 = 22%**

The precise number of credits must be populated from the official credit ledger for my cohort before a formal curriculum change is approved. The semester totals previously listed by me are not used as credit values in this calculation.

### Prerequisites and implementation conditions

- **Data analysis lab:** DBMS/SQL and basic Python should come first; advanced dashboard tasks follow basic spreadsheet and visualization work.
- **ML evaluation lab:** Python, basic statistics, and introductory Machine Learning should be prerequisites.
- **GenAI application lab:** Python programming and introductory AI/ML concepts should be prerequisites; API credentials must be handled securely.
- **API/testing lab:** Programming and web-technology fundamentals should come first; Git basics should be taught before collaborative project work.
- **Capstone:** Students should complete the relevant programming, database, and subject-specific prerequisites before undertaking the integrated project.
- **Regulatory and academic conditions:** Preserve mandatory university, statutory, accreditation, ethics, and foundational requirements; obtain approval through the programme’s curriculum committee and applicable academic bodies; map every change to programme outcomes and course outcomes; and maintain required internship/project requirements. These are recommendations, not claims that approval has been obtained.

## Proposed implementation sequence

1. **Map existing outcomes:** Compare detailed course outcomes and practical assessments to identify genuine overlap and avoid removing content that is required.
2. **Upgrade existing labs first:** Add reproducible SQL/data-cleaning tasks, ML evaluation, and code-quality practices where they fit existing courses.
3. **Run the applied GenAI lab:** Use my GenAI Weather Intelligence System as an example of API-plus-LLM integration, with proposed tests for factual consistency and failure handling.
4. **Assess with evidence:** Use rubrics that check correctness, reproducibility, documentation, testing, security, and explanation of limitations.
5. **Review outcomes:** Compare student project quality and internship/job feedback after the changes; revise the allocation based on evidence.

---



# Appendix A — Curriculum Inventory

I put my subjects in one place so I can review my curriculum semester by
semester for the curriculum audit. I took the subject names below from
the course list I have in my ICFAI SIS. I have kept the names as close
to the list as possible and only cleaned up the formatting.

This is an initial inventory of the subjects I have listed for Semesters
1--7, along with the Semester 8 internship.

## Semester 1

1.  Environmental Sciences
2.  C Programming
3.  English Language Skills
4.  Linear Algebra and Ordinary Differential Equations
5.  Engineering Graphics
6.  Physics

## Semester 2

1.  Chemistry
2.  Basic Electronics
3.  Digital Fabrication
4.  Data Structures in C
5.  Introduction to AI and DS
6.  Professional Communication
7.  Higher Calculus

## Semester 3

1.  Object Oriented Programming Concepts
2.  Database Management Systems
3.  Artificial Intelligence
4.  Introduction to IoT
5.  Discrete Mathematics
6.  Mathematical Essentials for Machine Learning
7.  Dynamics of Social Change

## Semester 4

1.  Computer Organization and Architecture
2.  Design and Analysis of Algorithms
3.  Engineering Economics and Management
4.  Industry Coding Practice (Python/R)
5.  Operating Systems
6.  Soft Computing
7.  Web-Enabled Technologies

## Semester 5

1.  Blockchain Technology
2.  Computer Networks
3.  Constitution of India
4.  Data Wrangling and Visualization
5.  Ethical Hacking
6.  Machine Learning
7.  Predictive Analytics

## Semester 6

1.  Big Data Systems
2.  Deep Learning
3.  Embedded Systems
4.  Natural Language Processing
5.  Pattern Recognition

## Semester 7

1.  Generative AI
2.  Quantum Computing
3.  Computer Vision
4.  Cloud Computing
5.  Professional Ethics

## Semester 8

1.  Internship (IP-2)

## Notes for the curriculum audit

-   This file is a list of the subjects and internship details I
    provided; it is not yet an evaluation of the courses.
-   I still need to compare the course content and learning outcomes
    with job requirements before deciding whether a subject should be
    kept, updated, reduced, or added.
-   I have not assigned individual credits to subjects because I do not
    have those values available.


# Appendix B — Job Description Comparison

I compared three fresher job descriptions with what I have studied across seven semesters of B.Tech CSE (AI). I used my own experience of the classes and labs to compare job requirements with what I have learned and practised.

My coursework has covered programming, databases, data analysis, AI/ML, web development, cloud computing, and other computer science foundations. I learned basic Excel in the Data Wrangling and Visualization (DWV) lab, used Python and Matplotlib in Google Colab for visualization, studied different ML models and completed practical ML exercises, and gained hands-on experience with AWS through college exercises. In Generative AI and Big Data Systems, I learned the concepts but did not have practical lab sessions. I learned API concepts and Git independently.

## 1. Data Analyst Trainee (Fresher) — Moonfire Group

The job listing mentions cleaning and preparing datasets, writing SQL queries, creating dashboards, supporting reporting, and documenting metrics and findings. The listed skills include SQL, Excel, data analysis, Power BI, statistics, and Python.

| Job requirement | Related coursework or experience | My comparison |
|---|---|---|
| SQL queries and databases | Database Management Systems | I studied database concepts and SQL in DBMS. I can build on this foundation by solving more realistic SQL queries and data-analysis tasks. |
| Cleaning and preparing datasets | Data Wrangling and Visualization (DWV) | I studied data wrangling and visualization and completed lab work with data. This connects directly to cleaning and preparing datasets. |
| Statistics and quantitative analysis | Higher Calculus; Linear Algebra and Ordinary Differential Equations; Mathematical Essentials for Machine Learning | These subjects helped me build a mathematical foundation. I want to strengthen applied statistics for analytics by practising with real datasets. |
| Excel and spreadsheets | DWV lab | I learned the basics of Excel in DWV and practised them in the lab. I want to build on this with more advanced spreadsheet analysis. |
| Data visualization | Python, Matplotlib, Google Colab; DWV | I have created visualizations with Python and Matplotlib in Google Colab. I have not used Power BI or another dedicated dashboard tool yet, so dashboard building is a skill I want to learn. |
| Explaining findings and reporting | English Language Skills; Professional Communication; DWV | These subjects support clear communication and data presentation. I want to keep improving at writing concise reports that explain analytical findings and metrics. |

### What this comparison suggests

My coursework gives me a foundation for data analysis, especially through DBMS and DWV. I have basic Excel lab experience and have made visualizations with Python and Matplotlib in Google Colab. My next priorities are more SQL practice, advanced Excel, dashboard building with a tool such as Power BI, and communicating findings from real datasets.

## 2. AI / ML Engineer — MaytrixTech

The job description mentions building and deploying machine-learning pipelines and model-serving systems, working with LLMs and retrieval, supervised learning, model evaluation, data engineering, monitoring, and responsible-AI controls.

| Job requirement | Related coursework or experience | My comparison |
|---|---|---|
| Python programming | Industry Coding Practice (Python/R) and my programming coursework | I have learned Python basics, OOP concepts, and exception handling, and have practised these concepts through coursework and labs. |
| AI and machine-learning foundations | Introduction to AI and DS; Artificial Intelligence; Machine Learning; Soft Computing; Predictive Analytics; Deep Learning; Pattern Recognition | I have learned different ML models and completed practical ML lab exercises. This gives me a foundation to build on for model development and evaluation. |
| Training and evaluating models | Machine Learning; Predictive Analytics; Deep Learning; Pattern Recognition | I have completed practical ML exercises. I want to keep strengthening my ability to compare models, interpret their results, and explain why one model performs better than another. |
| Generative AI and LLM applications | Generative AI; Natural Language Processing | In Generative AI, I learned different types of generative models and how they work. I did not have practical GenAI lab sessions. Building an application, using embeddings, and evaluating a retrieval-augmented generation (RAG) system are skills I want to develop through projects. |
| Big-data processing and data engineering | Big Data Systems; Database Management Systems; DWV | In Big Data Systems, I learned the concepts but did not have practical lab sessions. I want hands-on experience processing larger datasets and connecting data preparation to model training. DBMS and DWV provide related foundations in databases and data handling. |
| Cloud deployment and model serving | Cloud Computing; Web-Enabled Technologies; AWS exercises through college | I have hands-on experience with AWS and completed cloud exercises through college. I want to extend this experience to deploying and monitoring an application or trained model. |
| APIs, MLOps, and monitoring | API concepts learned independently; Cloud Computing; Industry Coding Practice | I learned API concepts on my own. I want more practical experience connecting a model to an API and learning experiment tracking, versioning, deployment, and monitoring. |

### What this comparison suggests

My curriculum covers AI, machine learning, deep learning, NLP, Generative AI, data handling, and cloud computing. I have completed practical ML exercises and AWS exercises through college. Generative AI and Big Data Systems were conceptual subjects for me, without practical lab sessions. A useful next step would be a project that starts with data preparation, trains and evaluates a model, exposes it through an API, and deploys it in the cloud.

**Source note:** The page describes the role as a fresher position, but I could not confirm its publication date. I recorded the access date rather than guessing a posting date.

## 3. Full Stack Developer (Fresher) — REAK

The posting describes developing and maintaining full-stack applications, debugging and testing, following software-development life-cycle practices, and delivering features. It mentions programming fundamentals, Git, APIs, front-end and back-end integration, databases, and basic cloud/deployment knowledge.

| Job requirement | Related coursework or experience | My comparison |
|---|---|---|
| Programming and problem-solving | C Programming; Data Structures in C; Object Oriented Programming Concepts; Design and Analysis of Algorithms; Industry Coding Practice | These subjects gave me programming and algorithmic foundations that are relevant to a developer role. |
| Databases | Database Management Systems | I studied database concepts and SQL in DBMS, which are relevant to storing and querying application data. |
| Web development | Web-Enabled Technologies; my practical work with HTML, CSS, and JavaScript | I learned how to write HTML, CSS, and JavaScript and applied them in web development. |
| APIs and front-end/back-end integration | API concepts learned independently; web-development coursework | There is no subject in my curriculum dedicated to APIs. I learned API concepts on my own and want to apply them by connecting a front end, API, and database in one working project. |
| Git and version control | Self-learning | Git is not taught as a dedicated subject in my curriculum. I learned it independently and want to use it consistently for version control and collaboration in project work. |
| Testing, debugging, and software-development workflow | Programming, algorithms, and web-development coursework | These subjects support software development. I want to strengthen my project work with automated tests, systematic debugging, and a clear development workflow. |
| Deployment and cloud basics | Cloud Computing; Computer Networks; Web-Enabled Technologies; AWS exercises through college | I have studied networking and cloud concepts and completed AWS exercises through college. I want more practice deploying a complete application and checking that it works reliably. |

### What this comparison suggests

My curriculum includes programming, algorithms, databases, web technologies, networks, and cloud computing, so it covers many foundations for full-stack development. I have applied HTML, CSS, and JavaScript, and learned API concepts and Git independently. My next step is to build a complete application that connects a front end, API, and database, uses Git, includes tests, and is deployed.

## Comparison across the three roles

| Skill area | Data Analyst | AI/ML Engineer | Full Stack Developer | My coursework or experience |
|---|---|---|---|---|
| Programming | Useful for analysis and automation | Core requirement | Core requirement | C, data structures, OOP, Python basics, and Industry Coding Practice |
| Databases and SQL | Core requirement | Useful for data pipelines | Core requirement | DBMS and SQL coursework |
| Data cleaning and visualization | Core requirement | Important before modelling | Useful in data-driven applications | DWV lab; Python and Matplotlib in Google Colab |
| Machine learning | Sometimes useful | Core requirement | Useful for some applications | ML models and practical ML lab exercises |
| Generative AI and LLMs | Usually optional | Relevant to LLM work | Useful for AI-enabled products | Learned generative model types and how they work; no practical GenAI lab sessions |
| Big-data processing | Useful for larger datasets | Relevant to data engineering | Useful for some applications | Learned Big Data Systems concepts; no practical lab sessions |
| Web development and APIs | Useful for data services | Useful for model serving | Core requirement | Applied HTML, CSS, and JavaScript; learned API concepts independently |
| Git and collaborative workflows | Useful | Important | Important | Learned Git independently |
| Cloud and deployment | Useful for dashboards and pipelines | Important for production ML | Important for shipping applications | Hands-on AWS exercises through college; more deployment practice wanted |

## Overall finding

The comparison shows that my curriculum covers many of the foundations these roles ask for, but my practical experience differs by subject. I have practical experience with Excel basics, Python visualizations, ML exercises, AWS exercises, and HTML/CSS/JavaScript. Generative AI and Big Data Systems were mainly conceptual for me, while API concepts and Git are skills I learned independently.

For Data Analyst roles, I want to build on my Excel and Python/Matplotlib experience with more SQL practice, advanced Excel, dashboard building, data-quality checks, and reporting. For AI/ML Engineer roles, I can build on my ML labs and AWS exercises while gaining practical experience in Generative AI applications, big-data processing, APIs, deployment, and monitoring. For Full Stack Developer roles, I can build on my web-development practice and self-taught API and Git knowledge by creating a complete application with a database, tests, and deployment.

I recommend strengthening practical assignments and connecting existing subjects through projects. For data analysis, I want more advanced Excel, SQL practice, and dashboard building. For AI/ML, I want a project covering data preparation, model evaluation, API-based serving, and deployment. For full-stack development, I want a complete application with version control, testing, and deployment.

## Source and evidence notes

The job descriptions were accessed on **23 October 2026**.

- **Data Analyst Trainee (Fresher) — Moonfire Group:** https://ats.moonfiregroup.com/ (the page lists 19 September 2026 as the posting date).
- **AI / ML Engineer — MaytrixTech:** https://www.maytrixtech.com/careers/aiml (publication date not confirmed on the page).
- **Full Stack Developer — REAK:** https://reak.co.in/careers/full-stack-developer/ (the page lists 15 April 2026 as the posting date).

I should preserve permitted screenshots or copies of the job details in the project evidence folder. This comparison is based on my coursework and experience, alongside the requirements listed in these three job descriptions. The postings are a small sample of the market, so the findings should not be treated as requirements for every employer.


# Appendix C — Ten Curriculum Recommendations

I am reviewing the subjects in my B.Tech CSE (AI) curriculum to
understand how they connect to entry-level jobs and what could be
improved. I used the subject list I provided from my ICFAI SIS and
compared it with three fresher job descriptions: Data Analyst, AI/ML
Engineer, and Full Stack Developer.

The comparison suggests that my curriculum already includes many
relevant foundations. The main area I want to examine is how much
practical work connects those subjects to the tasks employers describe.
Since I have not included the detailed syllabus and lab sheets in this
draft, I have not treated a skill as completely absent just because it
is not named in a course title.

## What seems strong in my curriculum

-   **Programming and problem-solving:** C Programming, Data Structures
    in C, Object Oriented Programming Concepts, and Design and Analysis
    of Algorithms give a foundation for software development.
-   **Databases and data work:** Database Management Systems and Data
    Wrangling and Visualization are relevant to SQL, data preparation,
    and analysis.
-   **AI and machine learning:** Artificial Intelligence, Machine
    Learning, Predictive Analytics, Deep Learning, Pattern Recognition,
    Natural Language Processing, and Generative AI cover a broad range
    of AI topics.
-   **Web and systems:** Web-Enabled Technologies, Operating Systems,
    Computer Networks, Big Data Systems, and Cloud Computing provide
    relevant systems and application foundations.
-   **Mathematics:** Linear Algebra and Ordinary Differential Equations,
    Higher Calculus, Discrete Mathematics, and Mathematical Essentials
    for Machine Learning support computing and AI foundations.

## Proposed changes

These are my initial recommendations based on the subject list and job
comparison. Before finalizing them, I should compare the actual course
outlines and lab exercises to avoid recommending something that is
already taught in another course.

  --------------------------------------------------------------------------------------
                No. Action        Course or area  Proposed change   Reason
  ----------------- ------------- --------------- ----------------- --------------------
                  1 KEEP          C Programming   Retain the core   They support
                                  and Data        programming and   problem-solving and
                                  Structures in C data-structure    are useful for
                                                  foundations.      software and
                                                                    AI-related roles.

                  2 KEEP          Design and      Retain the        Full-stack and AI/ML
                                  Analysis of     algorithmic       roles both benefit
                                  Algorithms      foundation.       from being able to
                                                                    reason about
                                                                    algorithms and
                                                                    efficiency.

                  3 UPDATE        Industry Coding Include a         The job descriptions
                                  Practice        structured        expect practical
                                  (Python/R)      project workflow  programming and
                                                  with Git,         modern development
                                                  debugging, code   workflows, not only
                                                  review, and       writing isolated
                                                  automated tests,  code.
                                                  if these are not  
                                                  already included. 

                  4 UPDATE        Database        Use practical     SQL is directly
                                  Management      datasets for SQL  relevant to the Data
                                  Systems         joins, grouping,  Analyst role and is
                                                  filtering,        also useful in
                                                  constraints, and  application
                                                  query validation. development and data
                                                                    pipelines.

                  5 UPDATE        Data Wrangling  Include a         The Data Analyst
                                  and             complete analysis role includes
                                  Visualization   task from raw     cleaning data,
                                                  data through      building dashboards,
                                                  cleaning,         and documenting
                                                  checking data     results.
                                                  quality,          
                                                  visualization,    
                                                  and written       
                                                  findings.         

                  6 UPDATE        Machine         Require baseline  The AI/ML role
                                  Learning and    models,           expects models to be
                                  Predictive      appropriate       trained and
                                  Analytics       evaluation        evaluated; producing
                                                  metrics, checks   a model alone does
                                                  for data leakage, not show that it
                                                  and error         works reliably.
                                                  analysis.         

                  7 UPDATE        Generative AI   Include a small   The AI/ML job
                                  and Natural     retrieval-based   description mentions
                                  Language        application and   LLMs and retrieval,
                                  Processing      evaluate its      so students should
                                                  answers against a practise checking
                                                  prepared test     the quality of AI
                                                  set, if these     outputs.
                                                  topics are not    
                                                  already covered.  

                  8 ADD or        API development Build and test a  This would connect
                    integrate     and software    small API that    AI models and
                    into an       testing         accepts input,    databases to usable
                    existing lab                  validates it,     applications. It is
                                                  returns results,  relevant to both
                                                  and handles       AI/ML and full-stack
                                                  errors.           work.

                  9 ADD or        End-to-end      Build a small web The Full Stack
                    integrate     application     application with  Developer role asks
                    into an       project         a front end, API, for application
                    existing lab                  database, version development,
                                                  control, tests,   front-end/back-end
                                                  and deployment.   integration, Git,
                                                                    testing, and
                                                                    delivery.

                 10 REDUCE only   Introductory    Compare the       This avoids teaching
                    if overlap is content across  course outlines   the same
                    confirmed     Artificial      and reduce        introductory
                                  Intelligence,   repeated          material more than
                                  Machine         introductory      once, but the
                                  Learning, and   material only if  reduction should not
                                  Soft Computing  substantial       be made without
                                                  duplication is    evidence of overlap.
                                                  found. Use any    
                                                  recovered time    
                                                  for deeper        
                                                  practical work.   
  --------------------------------------------------------------------------------------

## Why I am not recommending that every new technology become a new subject

The curriculum already has subjects for AI, ML, data work, web
technologies, and cloud computing. Adding a separate subject for every
tool could make the programme crowded and repeat material that is
already taught.

My first choice is to improve existing labs and connect subjects through
practical projects. A new lab or course should be proposed only when the
current syllabus does not adequately cover the required skill.

## How I would evaluate the changes

I would use practical evidence rather than course titles alone:

-   For the data-analysis work, check whether a student can clean a
    dataset, query it with SQL, create a clear dashboard, and explain
    the findings.
-   For the AI/ML work, check whether a student can train a model,
    choose appropriate metrics, analyze errors, and explain limitations.
-   For the full-stack work, check whether a student can build an
    application that connects a user interface, API, and database, then
    test and deploy it.
-   For all project work, check whether code is documented,
    version-controlled, and tested.

These are proposed evaluation criteria. They are not claims that the
current courses fail to meet them.

## Limitations

-   The subject names in this audit came from my SIS list.
-   I have not yet checked every official course outline, lab manual, or
    assignment.
-   The job comparison uses three postings and cannot represent every
    employer's requirements.
-   The recommendations are proposals for student review, not official
    curriculum changes.
-   Before finalizing any REDUCE or ADD decision, I need to check the
    detailed course content and applicable programme regulations.


# Appendix D — My GenAI Weather Intelligence System

**Project:** GenAI Weather Intelligence System  
**Project ownership:** Independently developed student project  
**Faculty involvement:** The project was developed independently and was not proposed or supervised by faculty for this curriculum audit.

My GenAI Weather Intelligence System is a weather chatbot/application that combines weather information obtained through the OpenWeather API with responses generated using the Groq API. Its aim is to make weather information easier to understand by using a generative AI model to produce natural-language responses.

This project connects several areas of my learning. My Python knowledge supports the programming logic, while my independent learning about APIs helped me understand how an application can obtain external data and use it as input for an AI-powered response. In my Generative AI coursework, I learned about different types of generative models and how they work, but I did not have practical Generative AI lab sessions. Developing this project independently gave me an opportunity to explore how AI can be integrated into an application.

## Connection to my curriculum audit

The project highlights a gap between learning AI concepts and applying them in a working application. Although I studied Generative AI as part of my curriculum, I did not have practical Generative AI lab sessions. I also learned API concepts independently rather than through a dedicated curriculum subject.

Based on this experience, I recommend adding more hands-on exercises involving external APIs, LLM integration, data handling, error handling, API-key security, and evaluation of AI-generated responses. These activities could help students connect theoretical AI knowledge with practical software development.

## Proposed lab or capstone extension

A future version of this project could be developed into a structured lab or capstone with the following stages:

1. **Retrieve weather data:** Connect to a weather API and handle successful responses, invalid locations, rate limits, and network errors.
2. **Prepare the input:** Extract relevant weather fields and format them into a clear, bounded prompt for the language model.
3. **Generate a response:** Use an LLM API to explain the weather information in natural language without inventing weather measurements.
4. **Add safeguards:** Keep API keys out of source control, validate user input, and clearly distinguish retrieved weather data from generated explanations.
5. **Test reliability:** Create test cases for valid locations, missing data, API failures, contradictory responses, and unsupported questions.
6. **Evaluate output quality:** Check factual consistency against the API response, clarity, relevance, and whether the model adds unsupported claims.
7. **Document and improve:** Record limitations and use test results to decide which changes improve reliability.

These are proposed extensions for a future lab or capstone, not claims that every feature has already been implemented in my current project.

## Curriculum areas connected to the project

| Curriculum or learning area | Connection to the project |
|---|---|
| Python | Supports the application's programming logic and integration code. |
| Generative AI | Provides the conceptual foundation for understanding generative models and LLM-generated responses. |
| Independent API learning | Helped me understand how to retrieve external data and connect services. |
| Web technologies, if used in the project interface | HTML, CSS, and JavaScript can support the user-facing application. |
| Cloud Computing | Offers relevant concepts for a possible future deployment; deployment should only be claimed if completed. |
| Data Wrangling and Visualization | Relevant to extracting, organizing, and presenting weather data clearly. |

## What this project suggests changing in the curriculum

I recommend adding a practical AI application exercise to the existing Generative AI or related lab work. Students could integrate a public API with an LLM, validate external data, manage failures, protect credentials, and test generated responses against a known source. This would complement theory with applied work without necessarily requiring a new standalone subject.

The project also illustrates the value of cross-subject work: a useful AI application may require programming, data handling, API integration, interface development, and testing—not only knowledge of AI models.

## Faculty and graduate feedback

I did not obtain feedback from faculty members or graduates for this audit. The recommendations are based on my experience of the programme, my independent project work, and the comparison of the selected job descriptions with the skills I developed. The recommendations have therefore not been validated through faculty or graduate interviews, which is a limitation of this audit.

## Evidence and limitations

- The project is my own work and was developed independently.
- The description identifies OpenWeather and Groq API integration as the core project approach.
- I have not claimed that the proposed extensions, evaluation tests, or deployment have already been completed.
- Before submission, I should attach genuine evidence of the implementation where available, such as screenshots, a repository link, selected code, or a short demonstration.
- The project is one practical example and does not by itself establish that every student has the same experience or that the entire programme has the same gaps.


# Appendix E — AI-Assisted AI/ML Exercises and Verification Log

**Date prepared and source-checked:** 24 October 2026  
**AI model used:** ChatGPT (GPT-6)

These five exercises focus on AI/ML concepts related to my B.Tech CSE (AI) coursework. The prompts and summaries document AI-assisted learning. The verification notes distinguish calculations checked directly from conceptual explanations supported by references and practical experiments not yet run.

## Exercise 1 — Data preprocessing and data leakage

**Prompt**

> Explain data leakage in machine learning using a simple example. Give a safe order for splitting data, fitting preprocessing steps, and evaluating a model. Explain why a scaler must not be fitted on the full dataset before the train/test split.

**AI output (summary)**

Data leakage occurs when information that would not be available at prediction time influences model training or evaluation. If a scaler is fitted on the full dataset before splitting, information from the test set influences preprocessing. A safer workflow is to split the data first, fit preprocessing only on the training set, apply the fitted transformation to the test set, train the model, and evaluate on the untouched test set. A pipeline helps keep these steps in the correct order.

**Verification**

I compared this explanation with the scikit-learn documentation on data leakage. It recommends splitting data before preprocessing, never fitting transformations on test data, and using the fitted training transformation on test data. The explanation is consistent with that guidance.

**Status:** Conceptual explanation source-checked. I have not run a scikit-learn code example for this exercise.

## Exercise 2 — Regression evaluation metrics

**Prompt**

> Explain MAE, MSE, RMSE, and R-squared. Use actual values `[3, 5, 7]` and predicted values `[2, 5, 9]` to calculate MAE, MSE, and RMSE step by step. Give one limitation of R-squared.

**AI output**

Errors are `[1, 0, -2]`; absolute errors are `[1, 0, 2]`.

- MAE = `(1+0+2)/3 = 1`
- MSE = `(1²+0²+(-2)²)/3 = 5/3 ≈ 1.67`
- RMSE = `sqrt(5/3) ≈ 1.29`

MAE is the average absolute error in the target's units. MSE averages squared errors, penalizing larger errors more. RMSE is the square root of MSE and returns to the target's units. R-squared compares predictions with a baseline based on the target mean, but a high R-squared alone does not prove good generalization.

**Verification**

I recalculated the absolute errors (1, 0, 2) and squared errors (1, 0, 4). Their averages are 1 and `5/3`, respectively, so RMSE is approximately 1.29. The scikit-learn metrics reference lists MAE, MSE, RMSE, and R-squared as regression evaluation metrics.

**Status:** Arithmetic independently recalculated; metric definitions source-checked.

## Exercise 3 — Classification metrics and class imbalance

**Prompt**

> A classifier is evaluated on 100 samples: 40 are actually positive and 60 are actually negative. It correctly identifies 32 positive cases and 54 negative cases. Calculate TP, FN, TN, FP, accuracy, precision, and recall. Explain why accuracy alone may be insufficient.

**AI output**

- TP = 32
- FN = `40 − 32 = 8`
- TN = 54
- FP = `60 − 54 = 6`
- Accuracy = `(TP+TN)/100 = 86%`
- Precision = `TP/(TP+FP) = 32/38 ≈ 84.21%`
- Recall = `TP/(TP+FN) = 32/40 = 80%`

Accuracy alone can hide poor performance on a minority class. Precision and recall describe different kinds of errors, and the appropriate metric depends on the application.

**Verification**

I checked that `32+8=40` actual positives, `54+6=60` actual negatives, and all four confusion-matrix values sum to 100. The metrics recalculate to 86% accuracy, approximately 84.21% precision, and 80% recall. The scikit-learn metrics reference documents accuracy, precision, recall, and confusion-matrix measures.

**Status:** Counts and calculations independently recalculated; metric definitions source-checked.

## Exercise 4 — Overfitting and cross-validation

**Prompt**

> Explain overfitting in machine learning. Give an example where training accuracy is 99% but validation accuracy is 72%. Explain what this difference may indicate, how cross-validation helps, and why the test set should not be repeatedly used to choose a model.

**AI output (summary)**

Overfitting occurs when a model fits the training data too closely, including noise, and performs less well on unseen data. Training accuracy of 99% and validation accuracy of 72% suggests a generalization gap and possible overfitting, although the data split and evaluation setup should also be examined. Cross-validation estimates performance across multiple training/validation splits. The test set should be reserved for final evaluation; repeatedly selecting models based on test results leaks information into model selection.

**Verification**

I checked the explanation against scikit-learn's guidance that test data must not be used to make model choices and that leakage can create overly optimistic performance estimates. The 99% and 72% values are an illustrative example, not results from a model I trained.

**Status:** Conceptual explanation source-checked; no model was trained for this example.

## Exercise 5 — Generative AI model families

**Prompt**

> Explain the basic idea behind variational autoencoders (VAEs), generative adversarial networks (GANs), and transformer-based generative models. For each, give one typical use and one limitation. Do not claim one family is always best.

**AI output (summary)**

- **VAE:** Learns a probabilistic latent representation and uses a decoder to generate samples. It can support representation learning and data generation. Some VAE image-generation approaches can produce blurrier samples than GAN approaches.
- **GAN:** Trains a generator and discriminator in competition. It can produce realistic-looking samples, but training can be unstable.
- **Transformer-based generative models:** Use attention to model relationships among tokens or sequence elements and generate outputs based on context. They are widely used for text and other sequence generation, but can produce incorrect content and can require substantial data and compute.

**Verification**

I compared the summary with OpenAI's educational article on generative models, which describes VAEs and autoregressive models and discusses trade-offs, and Google's Machine Learning documentation, which explains the generator/discriminator structure of GANs. I also included the original Transformer paper as a reference for the architecture underlying transformer-based models. These references support the high-level comparison, but I have not implemented or benchmarked these model families in this exercise.

**Status:** Conceptual summary source-checked; no model was trained.

## Reflection

These exercises cover data leakage, regression metrics, classification metrics, overfitting, cross-validation, and generative model families. I independently recalculated the regression and classification metrics. I checked the conceptual explanations against technical references. I have not claimed to run code or train models where I did not do so.

## References

All links accessed on **24 October 2026**.

1. scikit-learn developers. “Common pitfalls and recommended practices,” including data leakage and preprocessing. https://scikit-learn.org/stable/common_pitfalls.html
2. scikit-learn developers. “sklearn.metrics” reference, including regression and classification metrics. https://scikit-learn.org/stable/api/sklearn.metrics.html
3. OpenAI. “Generative models.” https://openai.com/index/generative-models/
4. Google for Developers. “Introduction to Generative Adversarial Networks.” https://developers.google.com/machine-learning/gan
5. Vaswani, A. et al. “Attention Is All You Need.” NeurIPS, 2017. https://arxiv.org/abs/1706.03762

## Evidence to save

- My working for the regression and classification calculations.
- If possible, a scikit-learn example showing preprocessing fitted only on training data.
- If possible, a model comparison showing training versus validation performance.
- Screenshots or outputs from any code I genuinely run, including corrections.


## AI-use disclosure and personal contribution

I used ChatGPT (GPT-6) to help organize and edit the curriculum comparison, draft explanations for the AI/ML learning exercises, check arithmetic in the regression and classification examples, and structure the report. The exercise log records the prompts, output summaries, verification steps, and sources used. I have distinguished conceptual examples from code or models I have not run.

My personal contribution is the subject inventory I supplied from my SIS, my descriptions of what I learned and practised, the comparison of that experience with the selected job requirements, and my independently developed GenAI Weather Intelligence System. The project was not proposed or supervised by faculty for this audit. I did not obtain faculty or graduate feedback.

## Faculty and graduate feedback

I did not contact or obtain feedback from faculty members or graduates for this audit. The recommendations are based on my own programme experience, my project work, and the selected job descriptions. This means the proposals have not been validated through faculty or graduate interviews.

## Limitations

- The job comparison uses three postings, so it is a useful sample rather than a complete representation of the labour market.
- The job listing for MaytrixTech did not have a publication date I could confidently confirm; the access date is recorded instead of guessing one.
- My curriculum descriptions reflect my experience of the subjects and labs. The report does not claim that every possible topic is absent from all teaching materials.
- I have not obtained faculty or graduate feedback.
- The credit reallocation is a balanced 22% design model expressed against the official total **T**, because the SIS subject list available for this report does not provide a confirmed, cohort-specific official credit ledger. No semester unit totals have been relabelled as credits.
- Proposed future tests, deployment, and capstone extensions are not described as completed features of my existing weather project.

## Sources and access dates

**Job descriptions — accessed 23 October 2026**
1. Moonfire Group, Data Analyst Trainee (Fresher): https://ats.moonfiregroup.com/ — the page lists 19 September 2026 as the posting date.
2. MaytrixTech, AI/ML Engineer: https://www.maytrixtech.com/careers/aiml — publication date not confirmed.
3. REAK, Full Stack Developer: https://reak.co.in/careers/full-stack-developer/ — the page lists 15 April 2026 as the posting date.

**Curriculum source — accessed 24 October 2026**
4. ICFAI Tech Hyderabad, B.Tech programme structure: https://www.ifheindia.org/icfai-tech-school-hyderabad/icfaitech-btech-program-structure
5. ICFAI Tech Hyderabad, B.Tech CSE (Artificial Intelligence) programme page: https://www.ifheindia.org/icfaitech-school-hyderabad/icfaitech/ugprograms/btech-cse-artificial-intelligence

The public programme-structure page provides context for the programme, but the subject inventory in this report follows the list supplied from my SIS. I have not copied public-page credit figures into my cohort’s credit calculation because the published structure does not establish that it is the exact credit ledger applicable to my specific SIS list.

**AI/ML technical references — accessed 24 October 2026**
6. scikit-learn developers, “Common pitfalls and recommended practices”: https://scikit-learn.org/stable/common_pitfalls.html
7. scikit-learn developers, metrics reference: https://scikit-learn.org/stable/api/sklearn.metrics.html
8. OpenAI, “Generative models”: https://openai.com/index/generative-models/
9. Google for Developers, “Introduction to Generative Adversarial Networks”: https://developers.google.com/machine-learning/gan
10. Vaswani, A. et al. “Attention Is All You Need.” NeurIPS, 2017: https://arxiv.org/abs/1706.03762

## Companion interactive file

The interactive curriculum comparison is supplied as a separate HTML file: `curriculum_comparison.html`. It supports filtering by role, semester, experience type, and search term, plus a credit-change calculator. The calculator requires the official programme-credit total to be entered; it does not assume that semester workload/unit totals are credits.
