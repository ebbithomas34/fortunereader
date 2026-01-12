# FortuneReader

**AI-Resistant Career Assessment Tool**

Find your ideal career path from 680 professionally curated occupations designed to thrive in an AI-driven future.

🔗 **Live Demo:** [https://ebbithomas34.github.io/fortunereader/](https://ebbithomas34.github.io/fortunereader/)

---

## 📖 About

We live in turbulent times. AI is taking away millions of jobs. But AI can't replicate human judgment, creativity, and connection. 

FortuneReader is the first tool in the world to match your strengths and weaknesses to occupational spaces where humans thrive. Through a systematic assessment process, it guides you from 680 AI-resistant professional directions—tethered to the O*NET database—down to a single career recommendation tailored to your preferences.

---

## ✨ Features

- **680 AI-Resistant Occupations** - Professionally researched career paths where humans excel
- **Three-Stage Assessment** - RIASE personality types → Preference filtering → Job-specific evaluation
- **Real-Time Progress Tracking** - Visual feedback showing remaining opportunities after each choice
- **Session History** - Track and review your assessment history across sessions
- **Claude.ai Integration** - Instant prompt generation for deeper career exploration
- **Smart Filtering** - Dynamic question selection based on your evolving profile
- **Mobile Responsive** - Works seamlessly on desktop, tablet, and mobile devices

---

## 🚀 How It Works

### Stage 1: RIASE Assessment (5 Questions)
Identify your core work preference type:
- **R**ealistic - Hands-on, practical work
- **I**nvestigative - Analytical, problem-solving
- **A**rtistic - Creative, expressive work
- **S**ocial - Helping, teaching, caring for people
- **E**nterprising - Leading, managing, persuading

### Stage 2: Preference Differentiators
Evaluate real trade-offs across multiple dimensions:
- Environment (outdoor, urban, private workspace)
- Physical demands (active, standing, lifting)
- Social preferences (solo, public-facing, collaborative)
- Time structure (night shifts, deadlines, self-paced)
- Cognitive style (routine, abstract, quantitative)
- Decision-making (high-stakes, autonomous, rapid)
- Emotional intensity (stress, trauma, intense work)

### Stage 3: Job-Specific Selection
Choose from up to 10 curated job recommendations that match your profile.

---

## 💻 Technology Stack

- **Frontend:** Pure HTML5, CSS3, JavaScript (ES6+)
- **Data Processing:** PapaParse for CSV parsing
- **Storage:** LocalStorage for session history
- **Deployment:** GitHub Pages
- **Data Source:** O*NET occupational database

---

## 📊 Data Structure

The assessment uses a sophisticated data model:

- **680 Professional Directions** - Curated career paths with detailed descriptions
- **42 Assessment Questions** - With guidance text explaining each trade-off
- **680 Job-Specific Questions** - Tailored prompts for final selection
- **Link Table** - Connects jobs to RIASE types and preferences
- **Entity Table** - Defines all preference categories

---

## 🎯 Usage

### Online (Recommended)
Visit [https://ebbithomas34.github.io/fortunereader/](https://ebbithomas34.github.io/fortunereader/)

Data loads automatically from GitHub. Just click "Begin Assessment" to start.

### Local Development
1. Clone the repository:
   ```bash
   git clone https://github.com/ebbithomas34/fortunereader.git
   cd fortunereader
   ```

2. Open `index.html` in your browser
   - On GitHub Pages: Auto-loads data.csv
   - Locally: Click "Begin Assessment" to upload data.csv manually

3. Complete the assessment and receive your career recommendation

---

## 📁 File Structure

```
fortunereader/
├── index.html          # Main application file
├── data.csv           # Assessment data (680 jobs, questions, links)
├── README.md          # This file
└── (optional files)
    ├── FortuneReader.html  # Local version (manual file upload)
    └── assets/             # Any additional resources
```

---

## 🔧 Configuration

### For GitHub Pages Deployment

The application automatically detects GitHub Pages and loads `data.csv` from:
1. jsdelivr CDN (fastest)
2. GitHub raw content
3. Local file (fallback)

### For Local Use

Use `FortuneReader.html` which prompts for manual `data.csv` upload.

---

## 🎨 Design Philosophy

**Minimalist Interface**
- Clean, uncluttered design with #FFFBEB background
- Compact control panel with 2px border
- Progress bars showing real-time impact of choices

**User Control**
- Read intro text at your own pace
- Clear visual feedback on each decision
- Ability to restart at any time
- Session history for comparison

**Transparency**
- Each question includes detailed guidance
- Shows exactly how many jobs remain
- Explains trade-offs before you commit

---

## 📝 License

**All rights reserved. © Abraham Thomas 2026**

This software is proprietary. No part of this software may be reproduced, distributed, or transmitted in any form without prior written permission from the copyright holder.

---

## 🤝 Integration with Claude.ai

FortuneReader generates a custom prompt for discussing your chosen career with Claude:

> "FortuneReader helped me select [Career Title] as a career I could live with for years. I have accepted some sacrifices to make this decision. Tell me the problems I should expect and how I can cope."

Click the "CLAUDE.AI" button on the results page to:
1. Copy the prompt to clipboard
2. Open Claude.ai in a new tab
3. Paste and continue your career exploration

---

## 🎓 Methodology

FortuneReader uses a three-stage filtering approach:

1. **Broad categorization** by RIASE personality type
2. **Iterative refinement** through preference trade-offs
3. **Final selection** from curated matches

This methodology ensures:
- Efficient narrowing from 680 to 1 career
- Meaningful choices at each step
- Self-awareness through trade-off evaluation
- High-quality final recommendations

---

## 📞 Support

For questions, issues, or feedback:
- Open an issue on GitHub
- Contact: Abraham Thomas

---

## 🌟 Acknowledgments

- **O*NET Database** - Occupational data source
- **Claude.ai** - AI career counseling integration
- **PapaParse** - CSV parsing library

---

## 📈 Version History

- **v1.0** (January 2026) - Initial release
  - 680 AI-resistant professional directions
  - Three-stage assessment process
  - Session history tracking
  - Claude.ai integration
  - GitHub Pages deployment

---

**Make AI work for you!**

Visit [[FortuneReader](https://ebbithomas34.github.io/fortunereader/) to find your ideal career path.](https://abrahamthomas34.substack.com/) to explore the foundational approach of FortuneReader
