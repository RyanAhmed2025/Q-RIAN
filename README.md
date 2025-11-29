# Q-RIAN
Advanced Quiz Renderer for Offline Distribution
## ✨ Fully Offline. Fully Private.
### **The Most Advanced Local-First Quiz Builder Ever Created**
Create, design, publish, and analyze quizzes — **entirely offline**, with **zero coding knowledge needed**, yet packed with the power of a full examination suite.

Q-RIAN runs *entirely on your computer*.
No account.
No servers.
No cloud.
No tracking.

  yet one quiz html for everyone to solve individually;
  Quiz can be taken without internet connectivity;
  Live updates, hints for progressive approach: less anxious build;
  * Unlimited Renders with elegant visuals;
  * Test it first to feel the convenience;

Perfect for:
* Schools
* Institutes
* Coaching centers
* Offline examinations
* Secure assessments

---

## 🚀 Build Quizzes Like a Pro

* Beautiful drag-free visual builder
* Real-time preview of every question
* Create MCQ, descriptive, and sectioned exams
* Add images, diagrams, video, and audio to any question
* Built-in hint system

---

## 🎧 Multimedia-Enhanced Questions

Attach:

* Images
* Diagrams
* Audio clips
* Videos

Everything is embedded directly into the final quiz file — **no internet required**.

---

## 🔐 Anti-Cheat & Secure Evaluation

* Tracks tab-switch attempts
* Prevents time manipulation
* Includes hidden session metadata
* Generates a secure encoded answer key
* Detects tampering attempts

Teacher-safe. Student-proof.

---

## 📄 One-Click Publishing

Instantly export:

* A **standalone interactive quiz** (HTML)
* A **AI-ready Markdown version**
* JSON structure for developers

Works on:

* Browser
* Windows EXE (via PyWebView + Python backend)

---

## 🧠 Smart Result Analysis

Drop in an answer key → instantly view:

* Score
* Time taken
* Student metadata
* Anti-cheat logs
* Event history

Everything rendered in a clean, card-based layout.

---

## 🌓 Light & Dark Mode for Comfort

Toggle themes instantly.
Perfect for night-time work, dim labs, or classroom projection.

---

## 🏷 Dynamic Header Fields

Collect:

* Student name
* Roll number
* Class
* Email
  Note: Images are avoided to keep personalized key useful and portable

# ----------------------------------------------------------------------------------------------------------------------
FOR IN-DEPTH UNDERSTANDING #CODERS

## **1. Architecture**

* **Local-first application** with:

  * Python backend (Flask)
  * Frontend built entirely in HTML/CSS/JS
  * PyWebView wrapper for native desktop experience
* **Web + Desktop Dual Execution**

  * Works in a browser OR as a standalone `.exe` application.
* All quizzes are generated as **self-contained HTML files** (no external dependencies).

---

## **2. Quiz Builder Features**

### **2.1 Quiz Item Types**

Supports 4 structured item types:

* **MCQ questions**
* **Descriptive questions** (with sub-questions)
* **Sections**
* **Header fields** (metadata collection)

### **2.2 Media-Attachable Questions**

Each question supports:

* **Images** (base64 embedded)
* **Audio**
* **Video**

### **2.3 Editor UI**

* Auto-resizing text areas
* Real-time edit ↔ preview toggling
* Drag-free, click-to-edit tiles
* Dynamic textarea placeholders
* Dark/Light theme toggle
* Automatic scroll to newest item

---

## **3. Hint & Support Systems**

* Inline **hint tray** per question
* Supports:

  * Text hints
  * URL hints
  * Additional notes

---

## **4. Import/Export Engine**

### Export:

* Converts entire quiz → AI-friendly Markdown
* Includes:

  * Title
  * Date
  * Timer
  * Randomization flag
  * Headers
  * Sections
  * MCQ options and answers
  * Hints
  * Descriptive sub-questions

### Import:

* Accepts:
  * JSON
    NOte: Format is Pre-built to be Copied for ease of use;
          Use AI tools to boost efficiency 
    
Automatically:
* Converts Imported structure → structured quiz item list
* Generates new unique IDs
* Normalizes MCQ options (minimum 4)

---

## **5. Anti-Cheat System**

### Built into student-generated quiz HTML:

* **Tab-switch logging**
* **Focus loss detection**
* **Event timestamping**

Logs are bundled into the exported answer key.

---

## **6. Encryption-Style Data Signature**

Your custom mechanism includes:

* Payload encoded as Base64
* Reversed-string signature embedded
* `QKEY-<payload>.<signature>` format
* Signature mismatch = “Data Tampered” alert

This prevents:

* Manual score editing
* Self-cheating
* Fake submissions

---

## **7. Student-Side Quiz Engine**

Features include:

* Timer countdown
* Auto-submit on timeout
* Randomized question order (optional)
* Descriptive questions rendering
* Image/audio/video viewing with modals
* Keyboard/UX-friendly form controls
* Clean scoring + performance summary

---

## **8. Result Review & Analysis Tools**

Inside the builder:

* Dedicated **Analysis View**
* Extracts:

  * Score
  * Time taken
  * Anti-cheat logs
  * Student metadata headers
* Displays in a structured tile
* Supports uploaded key files

---

## **9. Export System**

### When running through Flask:

* Returns `.html` file as downloadable blob

### When running through PyWebView:

* Uses native save dialog
* Auto opens output in default browser

Ensures:

* Clean file path
* HTML-safe filename
* Timestamp uniqueness

---

## **10. Robust Utility Layer**

* Autoresize textareas
* Base64 file readers
* Image header uniqueness enforcement
* Scroll stabilization
* ID generation with timestamp + random seed
* Safe HTML template rendering inside Python using Jinja2

---

## **11. Application Security & Integrity**

* No remote server — all local
* No dependency on external CDNs
* No cloud storage
* All media embedded inline
* Data never leaves user's device

This makes the tool:

* Offline-safe
* Privacy-friendly
* Classroom-ready
* Examination-safe
--- 
# -------------------------------------------------
©RYAN AHMED - 2025
RYANAHMED2025@GMAIL.COM
