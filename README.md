# FortuneReader: Counselor Edition
### *The AI Software for Counselors — Make Your Students AI-Proof*

FortuneReader is a high-speed heuristic engine designed for career counselors to help students navigate 680+ career paths. By using a sophisticated "Matrix Logic," the software narrows down vast datasets into precise career matches based on RIASE categories and specific industry differentiators.

## 🚀 Key Features
- **High-Speed Matrix:** Processes thousands of data points (Jobs, Questions, and Links) in milliseconds using client-side JavaScript.
- **AI-Proofing Strategy:** Beyond just finding a job title, the tool prepares a custom strategy for students to focus on human-centric skills that resist automation.
- **Gemini AI Integration:** Generates a professional prompt based on the student's result, allowing for an immediate deep-dive session with AI career coaching.
- **Privacy First:** Data is processed locally in the browser. No student data is ever uploaded to a server.

## 📁 File Structure
- `index.html`: The core application engine and user interface.
- `data.csv`: The "Knowledge Base" containing:
  - **R (Results):** Career titles and descriptions.
  - **Q (Questions):** RIASE and Differentiator questions.
  - **L (Links):** The matrix coordinates connecting careers to specific traits.

## 🛠 How to Use
1. **Launch:** Open `index.html` in any modern web browser.
2. **Load Data:** Click **"Analyze Dataset"** and select your `data.csv` file.
3. **Stage 1 (Discovery):** Navigate through the RIASE category questions. Clicking **"Agree"** will lock in a primary career orientation.
4. **Stage 2 (Refinement):** The Matrix will automatically identify the most relevant questions to differentiate the remaining careers.
5. **Result:** Once a match is found, click **"Prepare AI Strategy"** to copy a custom prompt.
6. **Consultation:** Paste the prompt into [Gemini](https://gemini.google.com) or your preferred AI to generate a 10-year career roadmap for the student.

## 🧠 The Heuristic Logic
FortuneReader uses a "Matrix Match" algorithm. Instead of a linear path, it looks at the remaining "Pool" of jobs and dynamically selects the question that has the highest mathematical "weight" to split the pool. This ensures the student reaches a result in the fewest number of clicks possible.

---
*Developed to empower counselors and protect the next generation of professionals from the disruptions of AI.*
