# ECHO: A Mental Wellness Support System

This project develops an intelligent therapy chatbot powered by Llama 2, tailored for users aged 16–22. It combines intent detection and emotion classification (based on Ekman’s 7 basic emotions) to deliver emotionally aligned, compassionate responses that support mental wellness.

Designed with LoRA-based fine-tuning and model quantization, the chatbot runs efficiently on consumer-grade hardware. Its goal is to simulate human-like therapeutic interactions with a focus on empathy, privacy, and personalization.

# 🔍 Current Limitations
Narrow demographic focus restricts its general use.

Ekman’s model limits nuanced emotion understanding.

Dataset lacks therapy-specific and diverse conversational data.

Basic privacy safeguards exist; advanced methods like differential privacy are planned.

No current integration with EHR or therapeutic monitoring systems.

Lacks ability to handle rare emotional scenarios or long-tail queries.

# 🚀 Future Goals
Expand to support broader age ranges and nuanced emotional states.

Enrich datasets with CBT, DBT, and ACT-based dialogues.

Integrate secure APIs and healthcare compliance features.

Employ few-shot learning and synthetic data generation for rare scenarios.

This project sets the groundwork for a secure, empathetic, and scalable AI therapy assistant for youth mental health.

# RESULTS

![image](https://github.com/user-attachments/assets/82af9393-b052-473a-81ee-c3cad93c4853)

Figure 1 shows Chatbot section displays Chatbot UI which generates proper response and detects the emotions for user input

![image](https://github.com/user-attachments/assets/45e7d51d-a718-4dbd-b08a-6deb8d8e8c4d)

Figure 2 shows Chatbot section which displays Chatbot UI which has the mastermind color game

![image](https://github.com/user-attachments/assets/70f1c60c-9100-402f-9a86-b882e38a79c6)

Figure 3 shows Chatbot section which displays Chatbot UI which has the mastermind number game

![image](https://github.com/user-attachments/assets/8ddaaf5a-bfff-43ae-98ef-7661e26a3f66)

Figure 4 shows Chatbot section which displays Chatbot UI which has the Journal Section

![image](https://github.com/user-attachments/assets/36b77fb5-91f9-4b21-8112-5815bdcb3081)

In Figure 5, we plotted the emotion classification accuracy of RGB vs JHartmann for displaying Adjusted and Raw accuracy for User, Bot and Overall with Adjusted accuracy being highest for User with 68.8% and Raw accuracy being highest for Bot with 86.4%

![image](https://github.com/user-attachments/assets/f3144489-5980-4233-acdb-7339201e9aef)

In Figure 6, a total of 160 samples(20 for each conversations between user and bot were made) which showed (Adjusted accuracy, Raw accuracy) for User, Bot and Overall as (0.6875, 0.8587), (0.6625, 0.8640), (0.6750, 0.8240)
