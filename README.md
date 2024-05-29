# Project Title

Developed a highly accurate personality identification system that integrates Enneagram principles with machine learning, achieving over 90% accuracy from data collected via Google Forms. 

The system leverages Neurolinguistic Programming (NLP) to enhance user interaction and includes a stress-reducing chatbot based on Transactional Analysis principles, integrated with the Google Gemini API. 

I meticulously created a dataset with a shape of (47,578, 90) more than 1057 combinations by manually inputting data into an Excel sheet. And collected responses from 59 individuals using a Google Forms survey with 90 yes/no questions. 

The Support Vector Machine (SVM) algorithm was used to predict personalities, and the system was tested on data from these 59 individuals to ensure accuracy and reliability.


## Tech Stack

**LANGUAGE :** Python

**LIBRARIES:** Pandas,Sklearn,Matplotlib,Joblib

**DATA COLLECTION :** Excel,Google_Forms

**AI :** Google_gemini

**DATA VISUALIZATION :** Matplotlib

**DATA MANIPULATION :** Pandas

**DATA PREPROCESSING  :** Sklearn

**ML ALGORITHM  :** SVM
 







## Enneagram

***What is the Enneagram?***

The Enneagram is a personality typology system that categorizes human personalities into nine distinct types. Each type represents a unique set of core motivations, fears, desires, and habitual patterns of thinking, feeling, and behaving. The nine types are interconnected, reflecting a dynamic model of personality that includes aspects of growth and stress points, as well as relationships between the types.

**Why is it Used?**

**Self-Awareness and Personal Growth:** By understanding their own type, individuals can gain deep insights into their behavior and motivations, fostering personal development and self-improvement.

**Interpersonal Relationships:** It helps people understand others better, improving empathy and communication, which leads to more harmonious and effective relationships.

**Professional Development:** Organizations use the Enneagram for team building, leadership development, and enhancing workplace dynamics by leveraging the diverse strengths of each personality type.

**Impact and Changes**

**Psychology and Counseling:** Therapists and counselors use the Enneagram to better understand clients' issues and to tailor interventions more effectively.

**Education:** Educators apply the Enneagram to understand students' learning styles and motivations, improving educational outcomes.

**Corporate World:** Companies use the Enneagram for team dynamics, leadership training, conflict resolution, and improving workplace culture.

**Personal Growth Communities:** The Enneagram has a large following in self-help and spiritual growth communities, providing a framework for personal transformation.
## Transactional Analysis (TA)

**What is Transactional Analysis (TA)?**

Transactional Analysis is a psychological theory developed by **Dr. Eric Berne** in the 1950s. It explores the dynamics of interpersonal communication and behavior. TA is based on the concept that our personality is composed of three ego states: **Parent, Adult, and Child.** These ego states influence how we think, feel, and behave in various situations.

**Parent:** This ego state encompasses attitudes and behaviors learned from our parents or caregivers. It can be nurturing or controlling.

**Adult:** This state is rational and objective, processing information based on the present moment.

**Child:** This state reflects our childhood feelings, needs, and experiences. It can be free and spontaneous or adapted and compliant.


**Why is it Used?**

Transactional Analysis is used for several purposes, including:

**Understanding Communication:** TA helps analyze and improve communication patterns by identifying which ego states are involved in transactions between people.

**Personal Growth:** It aids individuals in understanding their behavior and emotions, promoting self-awareness and personal development.

**Conflict Resolution:** By recognizing dysfunctional communication patterns, TA provides strategies to resolve conflicts effectively.

**Therapy and Counseling:** Therapists use TA to help clients understand their interactions and relationships, fostering emotional healing and growth.

**TA has significantly influenced various fields:**

**Psychotherapy and Counseling:** TA is widely used by therapists to help clients understand and change their communication patterns and relationships.

**Education:** Educators use TA to improve teacher-student interactions and create supportive learning environments.

**Business and Organizations:** Companies apply TA to enhance leadership, teamwork, and organizational culture.
## Neuro Linguistic Programming (NLP)

Neurolinguistic Programming (NLP) is a psychological approach that explores the relationship between neurological processes, language, and behavioral patterns learned through experience. Developed in the 1970s by **Richard Bandler and John Grinder**, NLP aims to understand and modify human behavior to achieve desired outcomes.

NLP recognizes that individuals have different learning preferences, often categorized into three main types:

**Visual Learning**

Characteristics: Visual learners prefer images, diagrams, and written instructions. They think in pictures and remember visual details.
Techniques: Diagrams, charts, mind maps, color-coding notes.

**Auditory Learning**

Characteristics: Auditory learners learn best through listening. They benefit from verbal instructions, discussions, and audio recordings.
Techniques: Lectures, discussions, audio recordings, repeating information out loud.

**Kinesthetic Learning**

Characteristics: Kinesthetic learners prefer hands-on experiences and learn through movement and touch. They excel in activities involving physical activity.
Techniques: Hands-on activities, role-playing, interactive tools, building models.
## Roadmap

- Selected Enneagram,Neuro-linguistic programming,Transactional Analysis as personality identification tools

- Created a dataset using Excel with only Ones and Zeros for Enneagram and Transactional Analysis, A function for finding Neuro linguistic programming (Visual,Auditory,Kinestetic)


- Created a Google-Forms Questionnaire of 90 Yes or No type Questions, and collected response  from 59 individuals 56 of them used for trainning the model

- Using a simple python code the responses are converted to Ones and Zeros (1,0) curresponding to Yes and No


- After hyperparameter tuning SVM showing the best accuracy

- Responses are tested using the Trained SVM model and taken feedback from all of them 

- 90 % above of them got their personality type 

- Using these responses as reference, Studied the clear patterns in personalities by matching the core concepts of Enneagram & TA,created a program for attending questions and instant response ensured

- Created a chatbot for reducing the stress levels of user by Prompt engineering of core concepts in TA,Enneagram & NLP integrated with googlegemini API





## Screenshots

![Responses collected through Google-Forms](https://github.com/AZADS98/Personality-identification-Raw/blob/main/Screenshots/56.png)

![Sample summary of responses -1](https://github.com/AZADS98/Personality-identification-Raw/blob/main/Screenshots/Responses%20be%20like.png)

![Sample summary of responses -2](https://github.com/AZADS98/Personality-identification-Raw/blob/main/Screenshots/Responses%20be%20like%202.png)

![Response Google Sheet 1](https://github.com/AZADS98/Personality-identification-Raw/blob/main/Screenshots/googlesheet1.png)

![Response Google Sheet 2](https://github.com/AZADS98/Personality-identification-Raw/blob/main/Screenshots/googlesheet%202.png)

![Response Google Sheet 3](https://github.com/AZADS98/Personality-identification-Raw/blob/main/Screenshots/google%20sheet3.png)




## Acknowledgements

I would like to express my heartfelt gratitude to my friends for their unwavering support and invaluable assistance throughout the development of this project. Their dedication and patience in completing my 90-question questionnaire multiple times were instrumental in refining the model. Without their enthusiastic participation and encouragement, I would not have been able to achieve the level of accuracy and reliability needed to present this to the wider group of 59 participants. Thank you for being an essential part of this journey and for your steadfast support.

## References

**Enneagram :** - Annie Maria

**Enneagram :** - Dr: Sreenath Karayatt

**The wisdom of the Enneagram :** Don Richard Riso and Russ Hudson

**Transactional Analysis in Psychotherapy, Games People Play:** Eric Berne

*Thalayilezhuth thirutham TA psychologyyiloode* (Malayalam title) - K A Sebastian

