# Sir Mahee DoubtBot AI ✨
**Study • Ask • Solve**

**Sir Mahee DoubtBot AI** कक्षा 5 से 10 (RBSE एवं NCERT) के विद्यार्थियों के लिए तैयार किया गया एक स्मार्ट AI-आधारित लर्निंग वेब ऐप और Android एप्लिकेशन है। यह विद्यार्थियों को कठिन प्रश्नों के सरल, चरण-दर-चरण (Step-by-Step) समाधान हिंदी और अंग्रेजी दोनों माध्यमों में प्रदान करता है।

---

## 🌟 प्रमुख विशेषताएँ (Key Features)

* **🤖 Live Gemini AI Doubt Solver:** Google Gemini (`gemini-2.5-flash` / `gemini-2.5-pro`) की मदद से किसी भी विषय के सवाल का तुरंत Step-by-Step उत्तर।
* **📷 Scan & Solve (Photo से पूछें):** कॉपी या किताब के प्रश्न की फोटो अपलोड करके सीधा हल प्राप्त करें।
* **🎤 Voice Input (बोलकर पूछें):** हिंदी में बोलकर अपना प्रश्न पूछने की सुविधा।
* **🔊 Audio Read-Aloud:** AI द्वारा दिए गए उत्तर को हिंदी या अंग्रेजी आवाज़ में सुनकर समझें।
* **📚 RBSE & NCERT Study Material:** English Grammar, Maths और Science के संक्षिप्त नोट्स व फॉर्मूला शीट।
* **🎯 Exam Special (PYQs & Quiz):** अभ्यास प्रश्नों (MCQs) के साथ तुरंत स्कोर और सटीकता (Accuracy) ट्रैकिंग।
* **💾 Multi-Layer Auto-Save:** विद्यार्थियों की प्रोग्रेस, स्ट्रीक, सेव किए गए प्रश्न और API Key स्वतः सुरक्षित रहते हैं।
* **📱 PWA & Android APK Ready:** इसे सीधे ब्राउज़र में वेब ऐप की तरह इंस्टॉल किया जा सकता है या GitHub Actions के माध्यम से `.apk` बिल्ड किया जा सकता है।

---

## 📂 प्रोजेक्ट स्ट्रक्चर (Repository Structure)

```text
sir-mahee-doubtbot/
├── index.html                      # मुख्य एप्लिकेशन (UI + Gemini AI + Audio Engine)
├── manifest.json                   # PWA ऐप कॉन्फ़िगरेशन व आइकन
├── sw.js                           # Service Worker (ऑफ़लाइन व तेज़ कैशिंग)
├── README.md                       # प्रोजेक्ट विवरण
└── .github/
    └── workflows/
        └── build-apk.yml           # ऑटोमैटिक Android APK बिल्ड वर्कफ़्लो
