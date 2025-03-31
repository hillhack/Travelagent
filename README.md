# Travelagent
**AI Travel Planner** project using **Streamlit & Hugging Face API**: 

### **About the Project**  
AI Travel Planner is an interactive **Streamlit** web app that helps users plan their trips based on preferences such as **destination, budget, interests, mobility, and dietary restrictions**. The app integrates with **Hugging Face's Mistral-7B-Instruct model** to generate personalized **trip itineraries, chat-based recommendations, and travel tips**.  

## **Features**  
**Interactive User Input Forms** – Users provide details about their trip (destination, budget, interests, etc.).  
**AI-Powered Itinerary Generation** – Creates a personalized day-by-day travel plan.  
**Conversational Chat Interface** – Users can refine their trip with a chat-based AI assistant.  
**Hugging Face API Integration** – Uses the **Mistral-7B-Instruct model** for intelligent trip planning.  
**Downloadable Travel Itinerary** – Users can save and download their final itinerary. 

## **🛠Tech Stack**  
- **Python** – Backend logic  
- **Streamlit** – Web interface  
- **Hugging Face API** – AI-powered travel recommendations  
- **Requests** – API calls  
- **Dotenv** – Secure API key management  

## ** Setup & Installation**  

### **1️⃣ Clone the Repository**  
```bash
git clone https://github.com/hillhack/Travelagent
```

### **2️⃣ Create a Virtual Environment** (Optional but Recommended)  
```bash
python -m venv venv
source venv/bin/activate  # For macOS/Linux
venv\Scripts\activate  # For Windows
```

### **3️⃣ Install Dependencies**  
```bash
pip install -r rqr.txt
```

### **4️⃣ Set Up Hugging Face API Key**  
Create a **.env** file and add your Hugging Face API key:  
```ini
HUGGING_API_KEY=your_hugging_face_api_key_here
```

### **5️⃣ Run the Application**  
```bash
streamlit run TraveAgent.py
```
Let me know if you'd like any modifications!
