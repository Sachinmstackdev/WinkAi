# 🌍 AI Global Chat Assistant

> 🤖 Auto-generate smart replies, translate across languages, and engage in meaningful conversations — anywhere in the world.

Built with Flutter, Mistral AI, Java, Supabase, and a stack of intelligent APIs — this AI assistant helps users chat seamlessly across languages with context-aware, real-time replies.

---

## 🚀 Application Features

- 🧠 **AI-Powered Auto Replies**  
  Suggest intelligent phrases and responses in real time using Mistral AI and NLP models.

- 🌐 **Multilingual Support**  
  Detect, translate, and respond in 100+ languages automatically — breaking global language barriers.

- 💬 **Chat Interface (Flutter)**  
  Fast,  responsive mobile UI for interactive messaging.

- 🔗 **Backend with Supabase + Java APIs**  
  Handles real-time data, auth, and session logic securely.

- 📚 **Context-Aware Q&A**  
  Ask anything — get accurate, relevant answers from integrated AI models.

- ⚡ **Fast + Scalable Architecture**  
  Designed for low-latency performance and future AI plug-ins.

---

## 🛠 Tech Stack

| Layer         | Tech Used                 |
|---------------|---------------------------|
| Frontend      | Flutter                   |
| Backend       | Java (Spring Boot / APIs) |
| Realtime DB   | Supabase                  |
| AI Engine     | Mistral AI (LLM)          |
| Translations  | Multilingual APIs (TBD)   |
| Auth          | Supabase Auth             |

---

## 🧪 How It Works

1. User sends a message  
2. Message is:  
   - Parsed for intent and language  
   - Translated if needed  
   - Processed with Mistral for best reply  
3. AI generates response → rendered in Flutter UI

---

## 🔧 Setup (Local )

```bash
git clone https://github.com/yourusername/ai-global-chat-assistant.git
cd ai-global-chat-assistant

# Flutter setup
flutter pub get
flutter run

# Backend (Java)
cd backend/
./gradlew bootRun
