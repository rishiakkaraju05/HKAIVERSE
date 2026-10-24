# Task 2 — Proposed Practical Project: GenAI Weather Intelligence System

## Project overview

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
