#  College Enquiry Chatbot (Dialogflow + Telegram)

A smart **College Enquiry Chatbot** built using **Google Dialogflow** and integrated with **Telegram** to provide instant answers for common student queries like admissions, courses, fees, hostel, placements, and contact details.

This project was developed as **Task 3** of my internship at **Future Interns**.

---

##  Features:

 Greeting message (Welcome intent)  
 FAQ responses (Admissions, Courses, Fees, Hostel, Placements, Contact)  
 Smart fallback response for unknown queries  
 Live chatbot testing using Dialogflow simulator  
 Telegram integration for real-time chat support  

---

##  Tools & Technologies Used:

- **Dialogflow (ES)** – No-code chatbot builder  
- **Telegram Bot** – Deployment platform for chatbot interaction  
- **Intent-based NLP** – Matching user queries with responses  

---

##  Sample Questions Supported:

- "How can I apply for admission?"
- "What courses are available?"
- "What is the fee structure?"
- "Is hostel available?"
- "Do you provide placements?"
- "Where is the college located?"
- "What is the contact number?"

---

##  How It Works:

1. User sends a message in Telegram
2. Telegram forwards the message to Dialogflow using webhook/integration
3. Dialogflow matches the message to an **intent**
4. The chatbot sends the appropriate response back to the user
5. If the query is unknown, the **fallback intent** handles it politely

---

##  Setup / Implementation Steps:

### 1️ Create a Dialogflow Agent
- Go to Dialogflow Console
- Create a new agent (example: `CollegeEnquiryBot`)

### 2️ Create Intents
Add intents such as:
- `Welcome Intent`
- `Admission Enquiry`
- `Course Details`
- `Fee Details`
- `Hostel Facility`
- `Placement Details`
- `Contact / Location`
- `Fallback Intent`

### 3️ Add Training Phrases & Responses
Example:
**Intent:** Admission Enquiry  
**Training Phrases:**  
- "How to apply?"
- "Admission process"
- "How can I join this college?"

**Response:**  
- "You can apply through our official website or visit the admission office."

### 4️ Integrate with Telegram
- Create a Telegram bot using **@BotFather**
- Enable Telegram integration in Dialogflow
- Connect the bot token
- Test chatbot directly in Telegram

---

##  Testing:

The chatbot was tested using:
- Dialogflow simulator
- Telegram live chat interaction

---

##  Future Enhancements:

🚀 Add more intents and better training phrases  
🚀 Add support ticket escalation (email / Google Sheets)  
🚀 Deploy chatbot on a website using Streamlit  
🚀 Improve responses using rich messages/buttons  

---

##  Acknowledgement:

Thanks to **Future Interns** for providing this internship task and learning opportunity.
