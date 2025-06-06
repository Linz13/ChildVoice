# BubbleTalk: A Child-Friendly Conversational Speech Large Model

> CSC5051: Natural Language Processing  
> CUHK-Shenzhen | MAIR Group 25

## 🧒 Motivation

While voice-based AI has become increasingly popular, most systems remain adult-oriented and unsuitable for children. They often:

- Use overly complex language
- Lack engaging and expressive voice styles
- Fail to convey warmth or empathy

**BubbleTalk** aims to bridge this gap with a child-centric conversational system that delivers cognitively appropriate language, emotional expression, and consistent high-quality interactions.

## 🛠️ Methodology

BubbleTalk integrates several cutting-edge components:

- **End-to-End Integration**  
  Seamless combination of:
  - Speech Recognition (ASR): [Whisper](https://github.com/openai/whisper)
  - Large Language Model: [Langchain](https://github.com/hwchase17/langchain)
  - Speech Synthesis (TTS): [CozyVoice](https://github.com/FunAudioLLM/CosyVoice)

- **Prompt Engineering for Children**  
  Specially designed prompts tailored to children's comprehension and interaction needs.

- **Adaptive Multi-Emotion Expression**  
  Supports 8 emotions (e.g., happiness, sadness, curiosity) with dynamic tone control.

- **Diverse Character Voices & Personalized Cloning**  
  Multiple cartoon voice options and user-uploaded (e.g., parental) voice cloning.

- **Global Memory & Contextual Flexibility**  
  Handles repetitive questions and non-linear speech patterns.

- **Low-Latency Streaming**  
  Real-time speech synthesis for smooth user experiences.

## 🧪 Results

A user study with 12 children (ages 4–8) and their caregivers showed:

- **83.3%** of children preferred BubbleTalk’s expressive character voices.
- **87.5%** of parents preferred BubbleTalk over traditional assistants for bedtime or educational use.

## 🎯 Features Summary

- Child speech-optimized interaction
- Emotionally rich responses
- Age-aware content filtering
- Real-time emotion analysis
- Voice personalization

## 📫 Contact

- **Lin Zhiyu**: 224040288@link.cuhk.edu.cn  
- **Yang Jingwen**: 224040204@link.cuhk.edu.cn


## 🎬 Demo

### Emotion-adaptive & Multi-Voice
[Click](https://linz13.github.io/BubbleTalk/demo.html)
