# 🌍 AI AGENT Travel Planner 

## 📌 Project Overview
This project is an intelligent **AI travel planner chatbot** built using **IBM Watsonx Agent** and deployed via **Watsonx.ai Runtime** on IBM Cloud. The chatbot helps users plan trips based on budget, location, and preferences, using integrated tools such as Google Search, DuckDuckGo, Wikipedia, Webcrawler, and Weather APIs.

---

## 🚀 Problem Statement
The Challenge  - A Travel Planner Agent is an AI-powered assistant that helps users plan trips efficiently 
and intelligently. 
It uses real-time data to suggest destinations, build itineraries, and recommend transport and 
accommodation options. 
By understanding user preferences, budgets, and constraints, it tailors personalized travel plans. 
Integrated with maps, weather updates, and local guides, it ensures a smooth travel experience. 
The agent can also manage bookings, alert users to changes, and optimize schedules on the go. 
This smart assistant transforms complex travel planning into a seamless, enjoyable process.

---

##  Proposed Solution
Using **Watsonx.ai's Prompt Lab and Gen AI Solution**, we built a custom **Watsonx Agent** that utilizes a LangGraph + ReAct framework to:
- Understand user queries like:  
  *"Plan a ₹15,000 trip to Kochi from Hyderabad"*
- Search the internet in real time using integrated tools
- Return contextual suggestions including places, food, hotels, and transportation

---

## ⚙ Technology Stack

- **IBM Cloud (Lite Tier)**
- **Watsonx.ai → Prompt Lab → Gen AI Solution**
- **Watsonx Agent (LangGraph + ReAct)**
- **Watsonx.ai Runtime (for deployment)**
- **Integrated Tools**:
  - Google Search
  - DuckDuckGo Search
  - Wikipedia Search
  - Webcrawler
  - Weather Lookup
- **Custom Prompt Engineering**
- **No-code Agent Interface**
- **Interactive Web Preview for Testing**

---

##  Features

- Understands natural language travel requests  
- Provides real-time suggestions for:
  - Travel destinations
  - Local foods
  - Hotel/accommodation options
  - Weather conditions
- Deployable via REST API (Watsonx Runtime)
- Easy to update/edit agent instructions

---

## 🖥 How It Works

1. Login to [IBM Cloud](https://cloud.ibm.com/)
2. Open **Watsonx.ai → Prompt Lab → Gen AI Solution**
3. Create a new **Agent** using **LangGraph + ReAct**
4. Add tools:  
   `Google Search, DuckDuckGo, Wikipedia, Webcrawler, Weather`
5. Write your **agent instruction prompt** for travel planning
6. Save the agent and deploy it using **Watsonx.ai Runtime**
7. Test using the preview interface or API

---

##  Sample Query

> **User:** *"Plan a trip to Munnar from Chennai within ₹12,000. Suggest places, food, and travel options."*

> **Agent Output:**  
 - Suggested route: Bus/train from Chennai to Munnar  
 - Local attractions: Echo Point, Tea Museum  
 - Food: Kerala Sadya, Appam with Stew  
 - Budget: ₹11,800 including stay and meals

---

##  Future Enhancements

- Integrate live booking APIs for flights, hotels, and buses  
- Enable voice interaction using Watson Speech Services  
- Generate multi-day itineraries  
- Add user history and trip-saving features  
- Build mobile app or responsive web UI


Feel free to fork, reuse, and improve with credit.

