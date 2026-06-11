# ⚡️ Avatar Lab – Where AI Meets Emotion

Welcome to **Avatar Lab** – the next generation of intelligent, emotionally expressive avatar animation. More than just lip-syncing, Avatar Lab combines powerful neural speech synthesis and state-of-the-art animation model to generate **realistic**, **emotion-aware avatars** that move, speak, and feel like real humans.

Whether you're building virtual assistants, game characters, or AI-driven content creators, Avatar Lab brings your digital personas to life.

---

## 🎯 Why Avatar Lab?

Most avatar tools stop at syncing lips to sound. **We go further.**

Avatar Lab delivers avatars with:
- 🎙 **Neural Speech Synthesis**  
  Realistic, expressive speech via cutting-edge TTS models.
- 🗣 **True-to-Life Lip Sync**  
  Facial animations that match audio at a near-human level.
- 👀 **Emotional Facial Motion**  
  Micro-expressions, eye blinks, and head tilts for authentic avatars.
- 🔌 **REST API**  
  Easily integrate Avatar Lab into your apps, games, or tools.
- 🧑‍💻 **Developer-Friendly Architecture**  
  Built on a scalable MERN stack with seamless deployment.
  

---

## 🧬 System Architecture

![Architecture](https://github.com/project-info182/Avatar-Lab/blob/bff0709b2070fcd5a1f21bac0176e9f4f9d9bb30/SYSTEM%20ARCHITECTURE.png)

---

## 🧱 Technology Stack

### Frontend
- ⚛️ React.js – Component-based UI
- 🎨 Tailwind CSS – Responsive modern styling
- 🔄 Redux – Efficient state management

### AI & Deep Learning
- 🧠 Zono TTS – Speech synthesis
- 🧍‍♂️ LatentSync – Facial motion & lip-sync generation

### Backend
- 🌐 FLASK– REST API for animation pipeline
- 🗂 MongoDB – Database for user data and animation metadata

---

## 🛠️ Workflow: From Text to Expressive Avatar

![Workflow](https://github.com/project-info182/Avatar-Lab/blob/94b4663f4856a9e8b0cbef705152684d41c7a8ff/WorkFlow%20Final.png)

1. Input text or audio
2. Generate expressive speech via neural TTS
3. Animate realistic facial motion using diffusion models
4. Output an engaging, emotionally aware talking avatar

---

## 🛠️ Software Development Life Cycle

### 📊 Custom SDLC: Modified Waterfall with Parallel Model Integration for AI Pipelines 🤖⚙️

![SDLC](https://github.com/project-info182/Avatar-Lab/blob/main/SDLC.jpg)

---



## 🔬 Models We Explored

### 🗣️ Speech Synthesis Models

We use the most advanced TTS systems to generate high-quality, human-like speech:

- [**Coqui TTS**](https://github.com/coqui-ai/TTS) – Fast, multilingual, expressive speech synthesis  
- [**Zonos TTS**](https://github.com/Zyphra/Zonos) – Lightweight and customizable TTS engine  
- [**Bark TTS**](https://github.com/suno-ai/bark) – Zero-shot voice cloning and audio generation  
- [**Spark TTS**](https://github.com/SparkAudio/Spark-TTS) – Multilingual, high-quality TTS with multiple voices  

### 🎥 Diffusion-Based Facial Animation

These models power expressive facial motion, lip-sync, and emotional realism:

- [**DiffPoseTalker**](https://github.com/DiffPoseTalk/DiffPoseTalk/tree/main) – Diffusion-based facial animation from audio  
- [**Memo Avatar**](https://github.com/memoavatar/memo.git) – Memory-based personalized avatar synthesis  
- [**SadTalker**](https://github.com/OpenTalker/SadTalker) – Realistic facial animation guided by landmarks and audio  
- [**DiffTalk**](https://github.com/sstzal/DiffTalk) – Diffusion-powered speech-to-video avatar animation  
- [**LatentSync**](https://github.com/bytedance/LatentSync) – Audio-latent space sync for expressive talking heads  

---
## 🆕 Selected Models

After evaluating several TTS and diffusion-based facial animation models, we finalized on the following two for **Avatar Lab**:

### 🗣️ Speech Synthesis Model: [Zonos TTS](https://github.com/Zyphra/Zonos)
We chose **Zonos TTS** for its lightweight architecture and natural, expressive voice synthesis.

🎧 **Sample Audio Output:**  

<p><b>🎧 Audio Preview:</b></p>
🎧 click for output: (https://project-info182.github.io/Avatar-Lab/)


---

### 🎥 Diffusion-Based Facial Animation: [LatentSync](https://github.com/bytedance/LatentSync)
We selected **LatentSync** for its highly realistic avatar generation and superior lip-sync accuracy.

📹 **Sample Video Outputs:**  
  <br>
  **Output demo 1**
  <br>
  <a href="https://project-info182.github.io/Avatar-Lab/video.html">
    <img src="https://raw.githubusercontent.com/project-info182/Avatar-Lab/main/thumbnail.png" alt="Watch the demo 1" width="300" />
  </a>
  <br>
  <br>
  **Output demo 2**
  <br>
  <a href="https://project-info182.github.io/Avatar-Lab/video1.html">
    <img src="https://raw.githubusercontent.com/project-info182/Avatar-Lab/main/thumbnail1.png" alt="Watch the demo 2" width="300" height="300"/>
  </a>
</p>

---


## 🚀 Use Cases

Avatar Lab is ideal for:

- 💬 **Virtual Assistants** – HR bots, customer support, smart help desks  
- 🕹 **Gaming** – Immersive, emotional NPCs and AI-driven characters  
- 📚 **Education** – AI tutors, sign-language avatars, multilingual teachers  
- 📹 **Content Creation** – Explainers, influencers, localized video generation  

---

## 🌍 Future Roadmap

Here’s what’s next for Avatar Lab:

✅- 🌐 **Finalize TTS model** – Choose a TTS model which works best for us <br>
✅- 🎥**Finalize Facial Animation model** – Choose a Facial Animation model which works best for us <br>
✅- 😃 **Create Frontend for the project** – A futuristic frontend is to be designed Using Reactjs and TailWind.<br> 
✅- 🕶 **Work on backend** – Make the frontend functional.<br>
✅- 🗣 **Integrating the models with Backend** – Integrating Both models in backend to work seamlessly <br>
✅- 🧑‍🎨 **Make a Fully Fucntional Website** – Users can now access and generate outputs interacting with the webiste.<br>
  - 🚀 **Deploy the website for universal access.**

---

## UPDATES
-✅ **Working on tts integration with the frontend**.
    Currently getting an internal server error when we pass the audio template to the TTS Model.(**resolved**)
  Solution: we have removed the use of local paths to access audio templates in the TTS.py and instead made use of URL to access local file path and download them. 

-**The prototype of the project is all done now, we are polishing and renovating the frontend.**

-**We also tried to run both the models on the same port( currently the tts api is  running on port 8000 and The latentsync api is running on 6900) but we failed to do so because of conflicting model dependencies.**

