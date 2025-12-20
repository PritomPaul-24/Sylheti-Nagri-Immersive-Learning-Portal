# Software Requirements Specification (SRS)
## Sylheti Nagri Immersive Learning Portal



## 1. Project Overview

The **Sylheti Nagri Immersive Learning Portal** is a web-based, mobile-friendly **Ed-Tech platform** designed to preserve, promote, and modernize the **Sylheti Nagri script** using **Augmented Reality (AR)**, **Artificial Intelligence (AI)**, and **gamified learning techniques**.

The platform is being developed for the **MillionX Bangladesh – AI Innovation Hackathon 2025**, representing a unique fusion of linguistic tradition and cutting-edge technology.

**Hackathon Selection**
- **Domain:** Ed-Tech  
- **Challenge:**  
  - Multimodal Learning Assistant (Text, Voice, Visuals)

<img width="887" height="499" alt="image" src="https://github.com/user-attachments/assets/b441e65b-1a46-449e-937e-bad70ab5fb84" />

## 2. Problem Statement

Despite its rich historical and cultural significance, **Sylheti Nagri** is at risk of extinction due to:

- Absence of modern digital learning tools  
- Limited educational integration  
- Low youth engagement  
- Lack of immersive and interactive learning experiences  
- Poor accessibility in rural and low-bandwidth regions  

Traditional text-based approaches fail to preserve learner interest and cultural depth, making it difficult to sustain the script for future generations.



## 3. Target Users

- Students and self-learners of Sylheti Nagri  
- Children and beginner learners  
- Educators and linguists  
- Cultural preservationists  
- Hackathon evaluators and developers  



## 4. Why the Problem Matters

### 4.1 Local Impact
- Sylheti Nagri is a vital part of Bangladesh’s linguistic heritage  
- Loss of the script threatens historical literature and cultural identity  
- Rural learners lack access to engaging educational resources  

### 4.2 Scalable Impact
- Can be extended to other endangered scripts  
- Adoptable by schools, cultural institutions, and museums  
- Demonstrates how AI and AR can support global cultural sustainability  



## 5. Solution Description

### 5.1 What the System Is

The system is a **standalone web application** enhanced with:
- AR-based immersive learning  
- AI-powered transliteration  
- Gamified educational modules  

> Artificial Intelligence is primarily used for modification, guidance, and transliteration rather than direct control of system operations.



## 6. Core Features

- Sylheti Nagri digital keyboard  
- Bangla ↔ Phonetic ↔ Sylheti Nagri script conversion  
- AR-based 3D letters with pronunciation  
- Gamified learning modules (Basic, Intermediate, Advanced)  
- AI conversational chatbot for guided learning  
- Language history and cultural storytelling section  
- Offline-first learning support  



## 7. System Features
<img width="961" height="472" alt="image" src="https://github.com/user-attachments/assets/cc4299ba-c152-44b8-875a-13db69c4eceb" />

### 7.1 Sylheti Nagri Keyboard
- Input Sylheti Nagri characters  
- Practice writing and typing  
- Each alphabet linked to a word with visual representation  
- Optional 3D Augmented Reality experience  

### 7.2 Immersive Augmented Reality Experience
- Floating 3D letters in real-world surroundings  
- Tap interaction for pronunciation  
- Snapchat/Instagram-style AR filters  

### 7.3 Artificial Intelligence Script Conversion
- Transliteration of Bangla text into Sylheti Nagri  
- AI models ensure accuracy  

### 7.4 Gamified Learning Modules
- AR-based level-up games  
- Progress tracking and rewards  
<img width="973" height="550" alt="image" src="https://github.com/user-attachments/assets/cd5dedf2-b8fb-4436-9b43-cfa64931c255" />

### 7.5 Artificial Intelligence Interactive Guide
- Conversational assistant for alphabets, history, and pronunciation  
- Provides feedback and guidance  
- Implemented as a chatbot  

### 7.6 Language History Section
- Visual and textual content on Sylheti Nagri heritage  



## 8. User Journey / Flow

1. User accesses the portal via web or mobile browser  
2. Selects a learning mode (Alphabet, Keyboard, AR, Game)  
3. Uses Bangla–Nagri transliteration or keyboard input  
4. Activates AR camera to visualize 3D letters  
5. Engages in level-based AR games  
6. Interacts with AI chatbot for guidance  
7. Explores historical and cultural content  



## 9. Workflow Gears Motion

1. **Planning & Design**  
   - Wireframes, AR assets, Nagri font selection in Blender  

2. **Frontend Development**  
   - React app with Phaser 2D games and AR.js 3D letters  

3. **AI & Backend Setup**  
   - Node.js backend  
   - OpenAI chatbot  
   - Bangla–Nagri converter  

4. **AR & Immersive Features**  
   - AR integration and interaction logic  

5. **Integration & Gamification**  
   - Levels, badges, 1952 cultural content  

6. **Testing & Deployment**  
   - Deployment on Vercel  
   - Demo video and pitch deck creation  
<img width="686" height="391" alt="image" src="https://github.com/user-attachments/assets/784c0fc7-51f0-4e16-b606-cc8e6a21f946" />


## 10. Problem–Solution Mapping

**Problem:**  
Traditional language learning methods fail to preserve Sylheti Nagri effectively.

**Solution:**  
An immersive, AI-assisted, AR-powered Ed-Tech platform that modernizes language learning while respecting cultural authenticity.



## 11. Demo Flow

1. Landing page introduction  
2. Alphabet learning with Bangla–Nagri comparison  
3. AR camera activation showing floating 3D letters  
4. Tap-to-hear pronunciation  
5. Script conversion demonstration  
6. Gamified level-up learning  
7. AI chatbot interaction  
8. Cultural history visualization  



## 12. System Architecture

### 12.1 Frontend
- React.js  
- Tailwind CSS  
- Phaser.js (2D gamification)  
- AR.js / Unity AR Foundation  

### 12.2 Backend
- Node.js  
- Express.js  
- MongoDB  
- RESTful APIs  

### 12.3 AI Layer
- Python-based LLM models  
- Bangla–Sylheti Nagri transliteration  
- Conversational AI chatbot
- Hugging Face  

### 12.4 Authentication & Deployment
- Firebase Authentication  
- JWT  
- Deployment on Vercel / Cloud infrastructure

<img width="869" height="489" alt="image" src="https://github.com/user-attachments/assets/09519efc-ecd8-4aee-ba84-f0d6b6515d45" />

## 13. Dataset Description (Nagri Sound Dataset)
The nagri-sound-dataset, hosted on Hugging Face, contains letter-level reference pronunciation audio samples for the Sylheti Nagri script. It supports AI-driven pronunciation feedback, AR-based letter triggering, and multimodal learning (text, voice, visuals) within the Sylheti Nagri Immersive Learning Portal. The dataset is stored in Parquet format with a train split and includes fields such as sample_id, letter_id, audio_file, spoken_language, target_language, duration_ms, noise_level, confidence_score, unity_action_id, and gesture_expected. It enables real-time feedback, adaptive learning analytics, and immersive XR interactions, making it ideal for cultural heritage and Ed-Tech XR projects in Sylhet. 

## 14. Functional Requirements

- Real-time AR rendering and audio playback  
- Script conversion accuracy  
- AI chatbot responsiveness  
- Progress tracking and gamification  



## 15. Non-Functional Requirements

- **Performance:** Smooth AR interaction  
- **Scalability:** Thousands of concurrent users  
- **Accessibility:** Offline mode, bilingual support  
- **Security:** Secure authentication and data privacy  
- **Usability:** Simple UI with gamified UX  
- **Cultural Sensitivity:** Respectful heritage representation  



## 16. Impact and Scalability

### 16.1 Expected Impact
- Revival of Sylheti Nagri script  
- Increased youth engagement  
- Inclusive access to language education  
- Promotion of cultural identity through technology  

### 16.2 Scalability
- Expandable to other endangered languages  
- Integration with schools and Ed-Tech platforms  
- AI analytics for adaptive learning paths  



## 17. Sustainable Development Goals (SDGs)

- **SDG 4:** Quality Education  
- **SDG 9:** Industry, Innovation, and Infrastructure  
- **SDG 11:** Sustainable Cities and Communities  
<img width="765" height="430" alt="image" src="https://github.com/user-attachments/assets/35e3a1ff-e3fb-41f1-a078-c6288c0d3c6e" />



## 18. Team Overview

- **Pritom Paul** – Lead Researcher, XR Developer & System Architect (Team Lead); Metropolitan University, Bangladesh  
- **Shivani Gokul Badgujar** – XR Conceptualizer, 3D Designer & AI Developer; MIT Institute Of Design, India
- **Sahil Uddin Ishmam** - Software Developer (Django, React) & Competitive Programmer; Metropolitan University, Bangladesh  
- **Ratul Saha Roy** – Full-Stack Software Developer & Video Editor; Metropolitan University, Bangladesh 
- **Banidipa Chakraborty** – Graphic Designer, Content Writer & Vocal Artist; Metropolitan University, Bangladesh



The **Sylheti Nagri Immersive Learning Portal** represents a powerful convergence of **heritage preservation** and **digital innovation**. By leveraging **Augmented Reality**, **Artificial Intelligence**, and **gamified learning**, the system provides a **sustainable, scalable, and engaging solution** for preserving an endangered script. This project highlights **Bangladesh’s capacity to lead** in culturally enriched, **future-ready Ed-Tech solutions**.

## Project Summary

The **Sylheti Nagri Immersive Learning Portal** is an innovative Ed-Tech solution for the **MillionX Bangladesh – AI Innovation Hackathon 2025**, targeting **Adaptive Tutors, Learning Analytics Dashboard, and Multimodal Learning Assistant** challenges. This platform fuses **Augmented Reality**, **AI-powered transliteration**, **gamified learning modules**, and **cultural heritage** to preserve and modernize the Sylheti Nagri script. Key features include a digital keyboard, interactive 3D AR letters with pronunciation, Bangla-to-Nagri conversion, leveled AR games, an AI conversational chatbot, and historical content inspired by the **1952 Language Movement**. Built with **Unity AR Foundation, React.js, Node.js, and OpenAI models**, the system ensures **offline accessibility, scalability, and cultural sensitivity**, particularly for learners and educators in low-bandwidth regions. 

[SRS Document] https://drive.google.com/file/d/1jfR23VUCctE17zXcLKbw8dWjPt54y8yQ/view?usp=sharing

[Datasets] https://huggingface.co/datasets/shivdi1999/nagri-sound-dataset

[Youtube Demo Video] https://youtu.be/qCMpn9jdgdo

[Google Drive Folder] https://drive.google.com/drive/folders/1HzkNmcKxrnBP4ixCGW4JOq4-U5XhbZe9?usp=sharing

