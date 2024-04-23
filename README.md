"PrivacyAI", a technologically advanced browser extension designed to ensure responsible use of Generative AI, specifically OpenAI's ChatGPT, within organizational boundaries, policies, laws, and regulations. PrivacyAI is poised to play a pivotal role in revolutionizing the digital landscape.
Upon document upload, PrivacyAI utilizes Python's OCR library to preprocess scanned documents, facilitating seamless conversion to editable text. Following this, (SpaCy an NLP library) analyzes the text, extracting key elements to derive rules and regulations, which are then assigned using Python backend algorithms.In "PrivacyAI" we integrated Reinforcement Learning (RL), leveraging its suitability for dynamic environment tasks. Crucially, Reinforcement learning (RL) excels in Real-Time decision-making, allowing "PrivacyAI” to promptly adapt to evolving policies.

Our Chrome extension seamlessly integrates with a TensorFlow.js ML model, facilitating direct connectivity to SpaCy within the extension. User queries in ChatGPT trigger JavaScript's DOM analysis of search results, delivering valuable insights to the user. This involves thorough examination and extraction of relevant information.

Based on predefined criteria, weights, and extracted entities, the system assigns scores (1-10) to identified rules' harmfulness/relevance in the user's search query using backend Python code. The algorithm meticulously analyzes rules, assigning scores based on criteria matching degree.
Users are promptly alerted to potential risks or deceptive practices from search results via popup notifications, featuring corresponding risk scores. JavaScript, Chrome Extension APIs, and DOM manipulation facilitate these notifications. Risk scores are determined based on match severity, ensuring timely and informative alerts.
Upon continued disregard of alerts, JavaScript manipulates the DOM to highlight search box and results, emphasizing relevant text snippets. The system then dispatches SMS notifications via Twilio API to the user's mobile number and a government agency. This alert system proactively mitigates risks and escalates notifications in response to ignored popups or harmful data.
UNIQUENESS:
1 SpaCy NLP Integration
Leveraging SpaCy's NLP prowess for rapid, real-time text analysis within Chrome extensions, ensuring efficient processing and accurate insights.
2. SMS Alerting Feature:
Our extension provides dual alert functionality: notifying users via SMS to their mobile numbers and simultaneously sending the same message to a designated government agency for reporting purposes.
3. Search Highlighting Feature:
Our extension alerts users to incorrect searches by highlighting both the search box and search results, ensuring immediate identification of erroneous queries.
4. Search Risk Scoring:
Our extension calculates a risk score (ranging from 1 to 10) for user searches in ChatGPT, providing insight into potentially inappropriate information and enhancing user awareness.

ADVANTAGES over Others:
1. OCR-Enhanced Document Processing:
Utilizing Python's OCR library, PrivacyAI accelerates document conversion, enhancing workflow efficiency and rule extraction precision

2. Real-Time Adaptation via Reinforcement Learning (RL):
PrivacyAI integrates RL for rapid decision-making, enabling prompt adjustments to changing policies. This boosts responsiveness and adaptability, enhancing overall system performance

3. Streamlined TensorFlow.js Integration:
PrivacyAI's extension seamlessly incorporates TensorFlow.js, connecting directly to SpaCy for advanced text analysis, thereby improving computational speed and query accuracy.

4. Accurate Risk Assessment via Rule Scoring Algorithm
Using a sophisticated Python algorithm, PrivacyAI assigns scores to rules based on predefined criteria, weights, and extracted entities, ensuring precise identification of relevant risks

5. Timely Threat Detection and Response:
PrivacyAI's alert system swiftly identifies and notifies users of potential risks, employing JavaScript manipulation and Twilio API for rapid escalation, ensuring proactive risk management.

![image](https://github.com/Saini-Anmol/PRIVACY--AI/assets/114739487/d15f3ee6-0cb1-41d0-9aa8-c982ca3c6664)
