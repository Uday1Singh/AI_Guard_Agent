# AI-Powered Smart Security System

An **AI-based home security assistant** that uses **face recognition**, **voice activation**, and **Gemini** for intelligent, spoken intruder alerts.  
Built using **Python, OpenCV, DeepFace, SpeechRecognition, Google Gemini API, and gTTS (Google Text-to-Speech)**.

---

## Features

✅ **Face Verification** – Detects and recognizes known (trusted) faces using DeepFace and Facenet embeddings.  
✅ **Voice Activation** – Starts guarding mode only after hearing “Guard my room.”  
✅ **Intruder Detection** – Detects unrecognized faces and triggers alarm + AI-generated spoken warnings.  
✅ **Smart Alerts** – Uses Gemini (or GPT) to create polite but firm verbal warnings.  
✅ **Automatic Snapshot** – Saves a photo of each unknown intruder to `/unknown_faces/`.  
✅ **Audible Buzzer Alarm** – Sounds an alarm using `buzzer.mp3` until the intruder leaves.

---

## Working
Voice Activation → Face Detection → Recognition (Facenet512)
→
Trusted / Unknown?
→
No Alarm 🚨 Alert + Speak
→
Save Image + Sound Buzzer
→
Gemini/GPT generates verbal warning

## Notes

Make sure your buzzer.mp3 file exists in the root folder.

Recommended image size for faces: at least 150×150 px.

Works best under consistent lighting.

Requires internet for Gemini/GPT + gTTS APIs.

## Authors
Uday Singh (22B1262) and Ankit Maurya (22B1266)

