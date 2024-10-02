<h1 align="center">AI Ensure</h1>
<p align="center">
</p>


> The system that is smart enough to take care each of the insurance thing to the coustomer and can also help in the operating part to the insurance company.

## Background
<p align="center">
  <img src="https://i.ibb.co/s6f1WqV/ai.png" />
</p>


In today’s fast-paced world, the insurance industry faces significant challenges in providing seamless, trustworthy, and efficient services to customers. Traditional methods of interacting with insurance agents are often time-consuming, impersonal, and prone to errors, creating barriers to accessing and understanding insurance policies. Furthermore, many consumers struggle with the complexity of policy selection and the intricate process of filing claims, leading to confusion, dissatisfaction, and even rejection of claims.

To address these challenges, there is a growing need to revolutionize how insurance is delivered and experienced. By harnessing the power of artificial intelligence, we can develop an AI-powered humanoid agent that transforms the insurance journey for consumers. This intelligent platform will simplify the process by offering 24/7 personalized guidance through voice, video, or chat, ensuring consumers can make informed decisions with ease. Moreover, it will educate customers, providing clear explanations of policy terms and disclosures to build trust and promote financial literacy.

The most immediate and impactful solution lies in streamlining the application process, particularly through an AI-powered form-filling assistant. This assistant will automate tedious paperwork, reducing human error and increasing claim acceptance rates. By making insurance more accessible and transparent, this innovative approach will foster a user-friendly experience, improve consumer satisfaction, and enhance the overall insurance penetration, ultimately ensuring that insurance works for everyone.

This AI-driven solution has the potential to not only transform customer service but also pave the way for a more efficient and consumer-centric insurance industry.


## WHY AI/ML for Insurance-Companies?


   
Insurance is a well-established and highly regulated sector. This has contributed to the industry's slower adoption of technological innovations compared to others. Many insurance companies still rely heavily on manual, paper-based processes, which are not only time-consuming but also require significant human effort. Customers often face lengthy paperwork and bureaucratic hurdles when filing claims or signing up for new policies. Additionally, many policies are not personalized to meet individual needs, causing customers to pay for coverage that may not be entirely relevant to them. In an era where most daily tasks are handled online and with ease, the insurance experience can still feel outdated and frustrating.

However, the landscape is shifting as insurance companies globally begin to invest in advanced technologies to enhance efficiency, reduce costs, and improve security. Recent years have seen a notable increase in insurers exploring and adopting Artificial Intelligence (AI) solutions.

According to McKinsey, the insurance industry could unlock an annual value of up to $1.1 trillion through the full implementation of AI technologies. The most promising areas for AI impact include:

Sales and Marketing: Machine learning can be leveraged to offer more competitive and personalized pricing for insurance policies. It enables insurers to recommend tailored products based on individual lifestyles and needs, ensuring customers only pay for what is necessary. This personalization not only makes insurance more appealing to a broader audience but also encourages first-time buyers to consider insurance.

Risk Management: AI, particularly neural networks, can identify patterns associated with fraudulent claims, reducing the incidence of fraud. In the U.S., non-health insurance fraud costs an estimated $40 billion annually, adding $400 to $700 in additional premiums for the average household. Machine learning can also enhance insurers' risk models and actuarial assessments, allowing for the development of more profitable and accurate insurance products.

Operations: AI-powered chatbots, utilizing neural networks, can handle the majority of customer inquiries via email, chat, and phone. This automation frees up valuable time and resources, enabling insurers to focus on higher-value tasks and improve overall operational efficiency.


<p align="center">
  <img src="https://i.ibb.co/xSFhWy9/DALL-E-2024-10-02-14-46-29-An-image-representing-AI-and-machine-learning-transforming-the-insurance.png" />
</p>

There is a need for a technology platform to **Revolutionize the operation of Insurance Sector** and that's how our project **AI Ensure** jumps in!
## What is AI Ensure?


**AI Ensure** represents the seamless connection between insurance companies and customers, serving as a transformative gateway to the insurance sector. Our software is a web-based application that leverages modern, cutting-edge technologies to revolutionize the way insurance claims and processes are handled.

AI Ensure offers a comprehensive AI-driven solution for all stakeholders, including customers, agents, and insurance companies. It provides an integrated system for managing insurance claims and policies with ease and efficiency. Additionally, the platform includes a curated database of mechanics, ranked by ratings and reviews, tailored to meet specific customer needs.

Explore the future of insurance with AI Ensure and discover how we are simplifying the insurance experience for everyone!


<p align="center">
  <img src="https://github.com/Ayanghosh-agno/AI_Insurance/blob/main/images/whole.gif" />
</p>

A further explanation of how each of these works can be found in the Engineering section below.

### Features 

AI-Insurance currently supports all of the following features!

> 1. **Comprehensive Insurance Information:** The assistant provides customers with detailed information about the insurance policies they are interested in.
> 2. **Claims Filing Assistance:** In the event of an accident, customers can easily file a claim through the assistant.
> 3. **Claims Monitoring:** Insurance moderators can review and manage claims or policy requests efficiently.
> 4. **Policy Applications:** Customers can manually apply for new insurance policies through the platform.
> 5. **Claims Submission:** The assistant facilitates the manual submission of claims to the insurance company.
> 6. **Mechanic Recommendations:** Based on the type of car damage, the assistant recommends local mechanics with good ratings and reviews.
> 7. **Claim Status Tracking:** Customers can check the status of their claims effortlessly.
> 8. **Password-less Login:** The project features a hassle-free password-less login page using the **SAWO AUTH API** for enhanced security and convenience.
> 9. **Damage Detection:** The assistant can identify the type of car damage, assisting insurance moderators in taking appropriate actions.
> 10. **User-Friendly Dashboard:** The platform includes distinct dashboard pages for each of the above functionalities, ensuring a seamless user experience.

Delve deep to explore more!


# Engineering

### System Architecture
![sys-arch](https://i.ibb.co/9ZgtJKD/Blank-diagram-5.png)

## Technology Stack:
  1) IBM-Watson Knowledge Studio
  2) Natural Language processing
  3) IBM-Watson Assistance
  4) IBM-Discovery
  5) IBM-Virtual Recognition
  6) React-Js
  7) HTML
  8) Java-Script
  9) SAWO-AUTH API

**So, how everything works?**

<p align="center">
  <img src="https://github.com/Ayanghosh-agno/AI_Insurance/blob/main/images/persona.png" />
</p>

> 1. **Document Upload:** Insurance policy documents are uploaded to Watson Discovery and annotated using Watson's Smart Document Understanding tool for better 
     data management.
> 2. **Mechanic Review:** Mechanic review documents are uploaded to Watson Knowledge Studio and annotated to create custom entities and relationships.
> 3. **User Interaction:** Users can interact with the AI through a web application interface, communicating directly with Watson Assistant.
> 4. **Query Resolution:** Watson Assistant addresses policy-related inquiries by leveraging Watson Discovery's querying capabilities.
> 5. **Mechanic Recommendations:** The chatbot recommends mechanics based on the type of vehicle damage and customer sentiment from reviews.
> 6. **Policy Application:** Users can manually apply for a new insurance policy, supported by an insurance moderator.

## Takeaways 


### What we learned
Throughout this project, we gained valuable insights on both technical and non-technical fronts. Our research skills on platforms like Google and Stack Overflow were significantly enhanced, and we acquired a deeper understanding of IBM Cloud technologies.


### Accomplishments
In just a few days, we explored numerous concepts and technologies. While collaborating across the frontend, backend, and IBM Cloud posed challenges, we successfully completed the project on time, achieving what initially seemed like a daunting task. We believe that our project has the potential to make a meaningful impact in the insurance sector.

### What's next for AI Ensure
**AI Ensure** stands out as one of our most technically advanced projects to date, and we are eager to expand its capabilities beyond this initial development phase. Alongside refining the existing features, we plan to introduce additional operational functionalities to enhance usability and effectiveness.

**Some of them are**:-

> 1. Implementing a machine learning model for improved damage detection capabilities.
> 2. Integrating facial recognition to access the customer database.
> 3. Developing number plate detection to match vehicle databases efficiently.

We also aim to incorporate user-friendly features such as streamlined access controls, easy checkout options, and enhanced IoT-based inter-device support to boost audience engagement. While the project primarily focuses on auto insurance, we are considering adapting some features for other insurance sectors. Additionally, we plan to refactor code, including CSS improvements for a better desktop experience, which was challenging to complete within the initial timeframe. Ultimately, we envision our project becoming widely adopted within the insurance community to redefine existing processes and eliminate inefficiencies.

## Contributors:

* [Anurag Deo](https://github.com/Anurag-deo14)
* [Arya Srivastava](https://github.com/aryaSri17)

