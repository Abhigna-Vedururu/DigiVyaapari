# DigiVyaapari

<img width="596" height="580" alt="image" src="https://github.com/user-attachments/assets/ae9a0c5f-886e-4693-8846-0ec3f8852837" />

## ❓ Problem Statement
Local Hawkers, Street Vendors and Micro Entrepreneurs often remain  digitally invisible while struggling with new technologies like UPI. They are also unaware of government’s MSME schemes and guidance to apply for these advantages. Many struggle with understanding the guidelines due to language barriers.

## 🎯 Proposed Solution
 A street vendor digitalization Agent that uses Natural Language Processing (NLP), Retrieval-Augmented Generation (RAG), to assist users in generating user profiles, guiding UPI and QR setup, recommending market strategies, explaining MSME and Udyam registration steps with document checklists in local languages.

## ⚙️ Technologies Used:
 1. IBM cloud lite services
 2. Natural Language Processing (NLP)
 3. RAG pipeline with internal vector index for direct queries (MSME guides, UPI PDFs)
 4. IBM Granite model with local language support

## 🐝 IBM Cloud Services Used:
1. IBM Cloud Watsonx AI Studio
2. IBM Cloud Watsonx AI runtime
3. IBM Cloud Agent Lab
4. IBM Granite-3.3-8B-Instruct
5. IBM Cloud Object Storage

## 🌟 Advantages:
1. Hyperlocal Intelligence: Utilizes geolocation to offer government programs, location-specific advice, and pricing benchmarks specific to the vendor's region.
2. Multilingual Support: Allows non-English speakers to access digital onboarding by supporting regional languages like Telugu, Hindi, and Marathi.
3. RAG-Powered Personalization: For precise, current answers, Retrieval-Augmented Generation is used with grounded documents such as MSME registration checklists and UPI guidelines.
4. NDC & Fintech Ready: Provides vendors with guidance on how to list their goods on Meesho, WhatsApp Business, and ONDC, allowing them to fully participate in digital commerce platforms.
5. Language understanding: Responds to queries based on user’s input and can switch between languages in the same chat window based on requirements.

## 👤 End Users:
1. Street Vendors
2. Local Hawkers
3. Small business owners
4. Micro-entrepreneurs

## 📣 Important Features:
1. Instant Q&A: Offers prompt responses based on financial and official government PDFs.
2. Simple Interface: To have their questions answered, vendors can text the agent.
3. Document-based Recommendations: Provides precise, useful answers by utilizing official MSME, UPI, and local SEO advice.
4. Language Customization: Improves accessibility by providing answers in the vendor's preferred language.
5. Guided Assistance: Walks vendors through procedures like MSME registration and UPI setup step-by-step.

## 🔀 Working:
1. The user enters a question, such as "How do I set up UPI?"
2. The request is processed by IBM Granite LLM, which comprehends its purpose.
3. Relevant documents, such as the MSME checklist and the UPI guide, are retrieved by the Vector Index.
4. In response, the agent offers suggestions, clear instructions, and a customized response.
5. Vendors can request the creation of QR codes or promotional materials.

## ⌞ ⌝ Screenshots:
1. Building the Agent:
<img width="1919" height="970" alt="image" src="https://github.com/user-attachments/assets/7caaea9b-edb9-43de-8993-e47b63fb232d" />
2. Adding the vector files:
<img width="1918" height="967" alt="image" src="https://github.com/user-attachments/assets/2636e2f1-b890-4fbc-939c-b791e3a352bc" />
3. Adding the necessary tools:
<img width="921" height="752" alt="image" src="https://github.com/user-attachments/assets/beb2a5c9-7700-4f86-9ebe-de50eb38d13a" />
4. Add the instructtions:
<img width="1754" height="751" alt="image" src="https://github.com/user-attachments/assets/a0fca47f-3b33-4fad-9165-cf1ac71b5273" />
5. Preview the model:
<img width="1382" height="749" alt="image" src="https://github.com/user-attachments/assets/1b42fd25-fdb5-4c7e-b54f-31685481f8d1" />
<img width="1258" height="766" alt="image" src="https://github.com/user-attachments/assets/1f613697-b0bd-41b3-9469-ddcb68b0ab04" />
<img width="1394" height="829" alt="image" src="https://github.com/user-attachments/assets/52db56bc-3bc8-4a10-a5f8-9b187c118248" />
6. Deploy the agent in IBM Cloud:
<img width="1247" height="618" alt="image" src="https://github.com/user-attachments/assets/e6bfba18-0dcc-425d-ac50-9a5908b31012" />

## ✅ Conclusion:
To make digital entrepreneurship accessible and economical for informal businesses, the hybrid approach of simplicity and personalized agent support will provide value to assist entrepreneurs and informal vendors: how to grow their hyperlocal business, how and where to make repayments in relation to digital transactions, how to access government schemes and policies, and how to market. The agent uses sophisticated artificial intelligence via Retrieval-Augmented Generation (RAG) and Natural Language Processing (NLP) to create context and meaningful insights. 
 
## 📑 References:
1. [IBM Cloud Lite](https://cloud.ibm.com)
2. [IBM Watsonx.ai](https://www.ibm.com/products/watsonx)
3. [UPI Information](https://en.wikipedia.org/wiki/Unified_Payments_Interface)
4. [MSME Registration process](https://razorpay.com/learn/msme-india-registration/)
5. [MSME Schemes](https://msme.gov.in/sites/default/files/Scheme-booklet-Eng.pdf)


