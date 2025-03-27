## 💡 Detox Dial

**A multi-modal AI-powered tool designed to curb digital addiction through real-time, personality-driven interventions.**

### 🧠 Inspiration  
Most app blockers passively restrict access without considering behavioral patterns. Detox Dial takes a proactive approach—leveraging phone calls, chat, and push notifications to actively engage users during moments of distraction.

### 🚀 What It Does  
- Uses an **MBTI-based quiz** to assign a custom AI persona  
- Allows users to set **focus sessions** to avoid distracting apps  
- Triggers multi-level interventions:
  - Push notifications  
  - In-app AI chatbot  
  - Personalized voice calls via Twilio  
- Tailors tone (friendly, sarcastic, tough love) to match user personality

### 🛠️ How It Works  
- **Personality profiling** via quiz, stored in a MongoDB database  
- **Flask backend** monitors trigger conditions (e.g., app use, screen time)  
- **Twilio Voice API** powers real-time AI phone call interventions  
- **Chatbot system** mimics social media interfaces to disrupt scrolling  
- **Adaptive AI responses** based on personality for realistic interaction

### 🧩 Key Challenges  
- Managing API secrets securely  
- Designing interventions that are helpful but not overwhelming  
- Ensuring real-time responsiveness for triggering actions  
- Applying behavioral psychology for effective habit disruption

### 📚 Insights Gained  
- Tailoring interaction style to personality boosts engagement  
- Combining voice, text, and behavior cues leads to stronger results  
- Emotional tone (sarcasm, empathy, assertiveness) greatly influences user response

### 🌟 Impact & Vision  
Detox Dial transforms digital wellness into a proactive experience. By combining AI, psychology, and personalization, it fosters healthier habits, encourages mindful tech use, and redefines how digital interventions are delivered.

[![Watch the demo](https://img.shields.io/badge/Watch-Demo-red?logo=youtube)](https://youtu.be/j50Vgk322rQ)
