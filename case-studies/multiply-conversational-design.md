---
title: Building a financial future, for free
---
<link rel="stylesheet" href="/../style.css">

## Project overview
* Client: Multiply is a free app that provides personalised, holistic financial advice for everyday people. To generate their unique financial plan, users provide information about their financial and life circumstances by answering questions in a chatbot-style conversational UI.
* Project: Conversational UI design to guide users through complex financial questions with friendly language
* Role: I designed the conversational logic and wrote the copy. This involved researching national statistics (such as common family types, average property prices) and consulting with in-house financial advisors to determine technical requirements for onboarding questions.
* Skills: Content strategy, UX writing, UX design

## Design problem
To generate a unique financial plan, we needed users to provide information about their financial and life circumstances - in financial advice, this is known as a fact find. In our previous web-based app, the fact find was a single-page form with conditional logic. This form was linear and required users to answer all questions in one go to be able to progress through the onboarding process. This could leave users ‘stuck’ if they didn't have certain information to hand - a particularly common obstacle when answering questions about financial assets.

![Legacy web app: a linear questionnaire with multiple choice questions and free text input. If users could not complete a particular question, they would not be able to proceed any further, causing immediate drop-off.
](https://user-images.githubusercontent.com/12902836/192864365-4045aeed-9758-4bc8-8aa0-afc28b134e23.png)

As part of our design sprint to redesign the app to a native iOS app, we decided to break the fact find into sections, allowing the user to save information to return to later. We also decided to implement chatbot-style conversational UI to guide users through these onboarding questions, and in line with industry trends and user expectations.

## Getting to the solution
Starting with our existing fact find, and a list of customer details we knew we needed to capture, based on advice from our in-house financial experts, we grouped the questions into 4 sections: You, Income & Outgoings, Assets, Debts.

Using low-fidelity tools such as whiteboarding, Post-It notes, and Google Docs, I mapped out what questions and content we would need to include in the conversational scripts. I then further developed the Google Doc ‘script’ of all the questions to indicate the conditional logic. 

![Whiteboard mapping out possible onboarding questions and conditional logic. This method allowed me to quickly experiment with different question pathways and easily visualise the complexity of the logic design.](https://user-images.githubusercontent.com/12902836/192864673-1943f04c-61b8-44df-8830-f879f678e9d9.jpeg)

![Google Doc ‘script’ for “Assets” section of onboarding fact find. Each section had a short introduction to give users context about what was expected, and conditional logic was mapped out using ‘if’ rules.](https://user-images.githubusercontent.com/12902836/192864727-bc0060d7-7bdc-42ad-9750-4b224ea75e74.jpeg) 

I produced artefacts in Figma to illustrate the user flow and interactions through each section of the fact find. These were then shared with the developers who could begin to code the foundations for the ‘chatbot’.

Further developing the Figma wireframes, I created simple clickable prototypes to test the content logic and finesse the copy for clarity and comprehension. Finally, I worked with visual designers to produce high-fidelity assets ready for production, with further copy refinements to adapt to UI constraints as needed.

### Dynamic content
I used conditional logic and dynamic content to streamline the conversation experience and personalise it for the user as much as possible. 

For example, leveraging what the user has already told us about their family and finances to only ask questions relevant to their situation, or to ‘pre-fill’ information.

This reduces cognitive load by avoiding superfluous content, and builds trust and emotional investment in the app by creating a connection to the user’s life.

### Using data to design for outliers
One of the nuances that came up was around cohabiting couples. Being married has certain legal obligations on your finances, so we had to ask people if they were married (or in a civil partnership). However, we knew from user research and market research that many people lived with and shared finances with a partner they weren't married to (according to data from the Office of National Statistics, cohabiting households were the fastest-growing family type in the UK). This presented a challenge for how to handle these customers.

Initially, we were asking users what their relationship status was: single, married, civil partnership. So we considered adding another option for people who were "cohabiting" or in a "serious relationship" or "not married but sharing finances". These options either presented gaps (what if they don't live together, such as long-distance relationships?), introduced ambiguity (what defines a 'serious' relationship?) or just felt clunky. 

Finally, after discussing as a wider group, we decided to reframe the question to "Are you married or in a civil partnership?" since this ultimately what we were trying to determine, rather than the personal nuances of people's relationships.

### Meeting users where they are
I also wrote ‘contextual help’ texts that would be available to view from within a question, providing definitions for legal or financial complexities and guidance to help users answer questions. Since we knew users would have varying financial and legal literacy, we wanted to make sure users could access further explanation without interrupting the flow or creating additional friction for users who didn't need it.

For example, following our decision to ask users if they were “married or in a civil partnership”, I wrote contextual help to provide users with a definition of what a “civil partnership” meant - we knew from user research and secondary research that many people do not realize a civil partnership is defined by a legal contract and isn’t just a ‘long-term’ or cohabiting relationship. 

In some cases this included links to official resources, such as GOV.UK or other national authorities. 

![Onboarding questions and contextual help: “Are you married or in a civil partnership?” offered users information on “What is a civil partnership?” with an explanation that it is a legal relationship. Another question asking the user if they want to include their child’s student living costs in their college savings goal provided contextual help about average university living costs in the UK, and includes link to the government’s student finance calculator.](https://user-images.githubusercontent.com/12902836/192864805-672d8805-706d-492f-ad45-5febdcf860cc.jpeg)

## Outcome
Following the 2-week sprint to redesign the app, which included the new conversational UI ‘chatbot’ onboarding, the designers and I supported the developers in implementing the functionality through design iteration and testing. We successfully relaunched Multiply as a native iOS app approximately 3 months later, in October 2018, meeting our delivery deadline. 

We continued to refine the conversational onboarding in subsequent app updates, for example by rephrasing questions or adding further contextual help based on user research. 
