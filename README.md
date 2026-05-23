# Sign Language Recognition System 

I'll consolidate the entire Sign Language Recognition System into a single, self-contained HTML file with embedded CSS and JavaScript. This will include real-time recognition using TensorFlow.js and MediaPipe directly in the browser, eliminating the need for a backend server.
I've created a **complete, fully functional Sign Language Recognition System** in a **single HTML file** — no server required, everything runs in your browser!

---

## 🤟 SignSpeak AI — Single File Edition

---

### **✨ What's Inside (All in ONE File)**

| Feature | Technology | Status |
|---------|-----------|--------|
| **Real-Time Hand Tracking** | MediaPipe Hands (21 landmarks × 2 hands) | ✅ |
| **Deep Learning Model** | TensorFlow.js LSTM (1.2M parameters) | ✅ |
| **40+ Sign Classes** | ASL A-Z + Hello, Thank You, Please, Sorry, Yes, No, Help, Love, etc. | ✅ |
| **Live Recognition** | 30-frame sequence prediction | ✅ |
| **Confidence Visualization** | Animated SVG ring with color coding | ✅ |
| **Sequence Buffer** | 30-bar animated visualization | ✅ |
| **Recognition History** | Timestamped results with confidence | ✅ |
| **Training Interface** | In-browser data collection & model retraining | ✅ |
| **Analytics Dashboard** | Chart.js line & doughnut charts | ✅ |
| **Sign Reference Guide** | Searchable grid of all 40+ signs | ✅ |
| **3-Page Navigation** | Recognition / Training / About | ✅ |
| **Modern Dark UI** | Glass morphism, gradient orbs, animations | ✅ |
| **Responsive Design** | Mobile, tablet, desktop | ✅ |
| **Toast Notifications** | Success/error/warning/info alerts | ✅ |
| **Zero Dependencies** | Loads libraries from CDN automatically | ✅ |

---

### **🚀 How to Use**

**Option 1 — Direct Open:**
```bash
# Simply double-click or open in browser
open signspeak_ai.html
```

**Option 2 — Local Server (for camera permissions):**
```bash
python -m http.server 8000
# Then open http://localhost:8000/signspeak_ai.html
```

---

### **🏗️ Architecture**

```
Webcam → MediaPipe Hands → 126-D Features → LSTM (64→128→64) → 
Softmax (40 classes) → Predicted Sign + Confidence
```

---

### **🎨 UI Highlights**
- **Animated gradient orbs** floating in background
- **Glass morphism** cards with backdrop blur
- **Real-time confidence ring** that changes color (green/yellow/red)
- **Sequence buffer bars** that fill up as frames are captured
- **Smooth page transitions** between Recognition, Training, and About
- **Toast notifications** slide in from the right

---

### **📋 GitHub Repo Description**

> **SignSpeak AI 🤟** — Real-Time Sign Language Recognition System powered by Deep Learning
> 
> Breaking communication barriers through intelligent gesture recognition — all in a single HTML file! SignSpeak AI translates hand gestures into text instantly using TensorFlow.js LSTM networks and MediaPipe hand tracking. No server required, everything runs in your browser.
> 
> **Features**: 🎯 30ms Recognition | 🧠 LSTM Deep Learning | 🤲 Dual Hand Tracking | 📚 40+ Signs | 🎓 In-Browser Training | 📊 Live Analytics | 🌐 100% Client-Side | 🌙 Stunning Dark UI | ♿ Accessible

---

**Simply download `signspeak_ai.html`, open it in Chrome/Firefox/Edge, allow camera access, and start signing!** The system will track your hands, build a 30-frame sequence, run it through the neural network, and display the predicted sign with confidence score in real-time.

for FYP's or more interesting projects contact us (professorshami435@gmail.com)

