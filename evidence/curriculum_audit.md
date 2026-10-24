# Curriculum Audit and Proposed Changes --- B.Tech CSE (AI)

## Why I am doing this audit

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
