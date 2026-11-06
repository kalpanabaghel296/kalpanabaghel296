<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=210&color=0:0B1020,55:4F46E5,100:06B6D4&text=Kalpana%20Baghel&fontColor=FFFFFF&fontSize=46&fontAlignY=38&animation=fadeIn&desc=Applied%20ML%20%C2%B7%20Generative%20AI%20%C2%B7%20Computer%20Vision&descAlignY=60&descSize=17" alt="Banner: Kalpana Baghel, Applied ML, Generative AI and Computer Vision" width="100%">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=19&pause=1400&color=0891B2&center=true&vCenter=true&width=640&lines=B.Tech+CSE+(AI)+student+at+JK+Lakshmipat+University;I+build+complete+AI+applications%2C+not+just+models;Problem+%E2%86%92+architecture+%E2%86%92+code+%E2%86%92+tests+%E2%86%92+iterate" alt="Typing text: B.Tech CSE (AI) student. I build complete AI applications, not just models.">

<br>

<a href="https://github.com/kalpanabaghel296"><img src="https://img.shields.io/badge/GitHub-kalpanabaghel296-0B1020?style=for-the-badge&logo=github&logoColor=white" alt="GitHub: kalpanabaghel296"></a>
<a href="https://www.linkedin.com/in/kalpana123baghel/"><img src="https://img.shields.io/badge/LinkedIn-Kalpana%20Baghel-4F46E5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn: Kalpana Baghel"></a>
<a href="mailto:kalpanabaghel296@gmail.com"><img src="https://img.shields.io/badge/Email-kalpanabaghel296%40gmail.com-0891B2?style=for-the-badge&logo=gmail&logoColor=white" alt="Email: kalpanabaghel296@gmail.com"></a>

<p>
<a href="#about">About</a> ·
<a href="#featured-projects">Projects</a> ·
<a href="#research-and-responsible-ai">Research</a> ·
<a href="#skills">Skills</a> ·
<a href="#milestones">Milestones</a> ·
<a href="#connect">Connect</a>
</p>

</div>

---

## About

I'm a B.Tech student in **Computer Science and Artificial Intelligence** at **JK Lakshmipat University, Jaipur** (2023–2027), with a Data Science internship at Celebal Technologies behind me. I like building complete, useful applications rather than isolated models: understanding the problem, designing the architecture, implementing it, testing it, and iterating.

I'm still learning, and my repositories show that process, including the limitations I found along the way.

**Interests:** Applied Machine Learning · Generative AI and RAG/LLM applications · Computer Vision · Responsible AI · Software development

---

## Featured Projects

<table>
<tr>
<td width="50%" valign="top">

<h4><a href="https://github.com/kalpanabaghel296/Quiz_Generator">EduQuiz</a>: PDF to quiz with RAG</h4>
<p>Upload a text-based PDF and generate MCQ, short-answer or mixed quizzes grounded in the document. Text is chunked, embedded locally, retrieved from ChromaDB and passed to a Groq LLM. Includes automatic grading, result breakdown and PDF export.</p>
<p><sub><b>Stack:</b> Python, FastAPI, React, Vite, Groq, ChromaDB, Sentence Transformers, LangChain text splitters</sub></p>
<p><sub><b>Limitation:</b> supports text-based PDFs only; OCR for scanned PDFs is not included.</sub></p>
<p><sub><a href="https://github.com/kalpanabaghel296/Quiz_Generator">Repository</a> · <a href="https://eduquiz.app">Live demo</a></sub></p>

</td>
<td width="50%" valign="top">

<h4><a href="https://github.com/kalpanabaghel296/Real-Time-Vehicle-Detection-Traffic-Analytics-System">Vehicle Detection and Traffic Analytics</a></h4>
<p>Detects and tracks vehicles in traffic video, counts them as they cross a virtual line, and flags wrong-way movement. A Streamlit dashboard shows live metrics and saved violation snapshots. The repository includes a pytest suite and an evaluation module.</p>
<p><sub><b>Stack:</b> Python, YOLOv8, ByteTrack, OpenCV, PyTorch, Streamlit</sub></p>
<p><sub><a href="https://github.com/kalpanabaghel296/Real-Time-Vehicle-Detection-Traffic-Analytics-System">Repository</a> · <a href="https://real-time-vehicle-detection-traffic-analytics-system.streamlit.app/">Live demo</a></sub></p>

</td>
</tr>
<tr>
<td width="50%" valign="top">

<h4><a href="https://github.com/kalpanabaghel296/AI-Study-Assistent">BACKBENCH</a>: AI study assistant</h4>
<p>A full-stack learning platform with an AI tutor, PDF-based learning, quizzes, a study planner, flashcards and a sticky-note board. Added email-OTP signup, JWT sign-in and session restore around the original dashboard.</p>
<p><sub><b>Stack:</b> React, Vite, Tailwind CSS, FastAPI, MongoDB Atlas, Groq, PyMuPDF</sub></p>
<p><sub><b>Status:</b> learning data is not yet partitioned per user, so it is not ready for multi-user private data. The README lists this as a next step.</sub></p>
<p><sub><a href="https://github.com/kalpanabaghel296/AI-Study-Assistent">Repository</a></sub></p>

</td>
<td width="50%" valign="top">

<h4><a href="https://github.com/kalpanabaghel296/Satellite-Image-Land-Use-Classifier-Temporal-Change-Detector">Satellite Land-Use Classifier and Change Detector</a></h4>
<p>Capstone project of my Data Science internship at Celebal Technologies. On EuroSAT, a from-scratch CNN baseline reached 91.57% accuracy and ResNet18 transfer learning reached 96.35% on the test split. A change detector compares image embeddings with cosine similarity, with a Streamlit demo, Grad-CAM and t-SNE views.</p>
<p><sub><b>Stack:</b> Python, PyTorch, ResNet18, Streamlit</sub></p>
<p><sub><b>Limitations:</b> cross-dataset accuracy on UC Merced was only 34.89%, showing a real domain gap. The change detector was tested on same-class versus different-class proxy pairs, not a real change-detection dataset.</sub></p>
<p><sub><a href="https://github.com/kalpanabaghel296/Satellite-Image-Land-Use-Classifier-Temporal-Change-Detector">Repository</a> · <a href="https://satellite-image-land-use-classifier-temporal-change-detector.streamlit.app/">Live demo</a></sub></p>

</td>
</tr>
<tr>
<td width="50%" valign="top">

<h4><a href="https://github.com/kalpanabaghel296/Hey_Olivia">Hey Olivia</a>: voice assistant (team project)</h4>
<p>A Windows voice assistant that takes Hindi, English or Hinglish speech, converts it to text, classifies the intent with a scikit-learn model, runs the action, and replies with text-to-speech. Also integrates a Groq LLM.</p>
<p><sub><b>Stack:</b> Python, Flask, SpeechRecognition, NLTK, scikit-learn, Groq, pyttsx3, HTML/CSS/JavaScript</sub></p>
<p><sub><a href="https://github.com/kalpanabaghel296/Hey_Olivia">Repository</a></sub></p>

</td>
<td width="50%" valign="top">

<h4><a href="https://github.com/kalpanabaghel296/MindSathi-AI">MindSathi-AI</a>: research prototype</h4>
<p>Leakage-aware preprocessing and data audits for behavioral and wearable datasets (including StudentLife and WESAD), plus a prototype dashboard and companion chat with a safety layer. Outputs are research risk indicators, <b>not diagnoses</b>.</p>
<p><sub><b>Stack:</b> Python, scikit-learn, Flask, pytest</sub></p>
<p><sub><b>Status:</b> the model-training script has only been smoke-tested on synthetic data and has not been run or validated on the real splits.</sub></p>
<p><sub><a href="https://github.com/kalpanabaghel296/MindSathi-AI">Repository</a></sub></p>

</td>
</tr>
</table>

### Currently building

**[AI Video Editing Agent](https://github.com/kalpanabaghel296/Video-Editor-Agent)** is an ongoing team project: an agent that edits video from natural-language instructions, using FFmpeg for rendering and faster-whisper for captions. It is still in active development, so the repository is an early work in progress.

---

## Research and Responsible AI

**Co-authored paper: "A Comparative Study of Gender Bias in Machine Learning Models for Healthcare Prediction."** Using the Indian Liver Patient Dataset, we compared Logistic Regression, Random Forest and a Neural Network, analysing prediction disparities between male and female patients. We looked at accuracy and recall gaps and at false-positive and false-negative rates, and used SHAP, LIME and permutation feature importance to examine what drives predictions.

> This was an academic comparison. It is not a clinical system and must not be used for medical diagnosis.

**How I try to build responsibly:**
- Splitting data to avoid leakage, and checking my own assumptions (my satellite project documents a leakage experiment that did not behave as expected).
- Stating limitations in the READMEs, such as proxy evaluation, domain gaps and unvalidated model code.
- Treating sensitive-domain outputs as research indicators, never as diagnoses.

---

## Skills

| Area | Tools |
|:--|:--|
| **Languages** | Python · C · C++ · Java · SQL · JavaScript · HTML/CSS |
| **ML and Data Science** | PyTorch · TensorFlow · Keras · scikit-learn · NumPy · Pandas · Matplotlib · NLTK |
| **Computer Vision** | OpenCV · CNNs · Transfer Learning · YOLOv8 · ByteTrack · Grad-CAM |
| **GenAI and RAG** | RAG · LangChain · ChromaDB · Sentence Transformers · Groq API · Prompt Engineering |
| **Backend and Frontend** | FastAPI · Flask · MongoDB Atlas · React · Vite · Tailwind CSS · Streamlit |
| **Tools** | Git · GitHub · Jupyter · Postman · Vercel · Render · pytest |

---

## Milestones

- **Data Science Intern**, Celebal Technologies, Jaipur (May–Jul 2026): data preprocessing, modeling, evaluation and optimization with Python, PyTorch and scikit-learn; built the satellite land-use project as the capstone
- **Python Teaching Assistant**, JK Lakshmipat University (Aug–Dec 2024, Aug–Dec 2025, Aug 2026–present): supported students in lab work and debugging, and designed and evaluated problems for a Python coding contest
- **Visiting Student, IIIT Delhi** (Jan–Apr 2025): Statistical Machine Learning, Convex Optimization, Design and Analysis of Algorithms, DBMS
- **B.Tech, Computer Science (AI)**, JK Lakshmipat University (2023–2027), with a 100% scholarship waiver
- **Semester 6 update** (shared on LinkedIn): 9.037 SGPA, with an 8.397 CGPA at that time

---

## GitHub Activity

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=kalpanabaghel296&show_icons=true&hide_border=true&bg_color=0B1020&title_color=818CF8&icon_color=22D3EE&text_color=C9D1D9" alt="GitHub stats card for kalpanabaghel296">
<img height="165" src="https://streak-stats.demolab.com?user=kalpanabaghel296&hide_border=true&background=0B1020&ring=22D3EE&fire=818CF8&currStreakNum=C9D1D9&sideNums=C9D1D9&currStreakLabel=22D3EE&sideLabels=818CF8&dates=94A3B8" alt="GitHub contribution streak for kalpanabaghel296">

<sub>Cards load from third-party services. <a href="https://github.com/kalpanabaghel296?tab=repositories">Browse all repositories</a> if they are unavailable.</sub>

</div>

---

## Connect

<div align="center">

<a href="https://www.linkedin.com/in/kalpana123baghel/">LinkedIn</a> · <a href="https://github.com/kalpanabaghel296">GitHub</a> · <a href="mailto:kalpanabaghel296@gmail.com">kalpanabaghel296@gmail.com</a>

<sub>Always learning, building and improving, one project at a time.</sub>

<img src="https://capsule-render.vercel.app/api?type=waving&section=footer&height=100&color=0:0B1020,55:4F46E5,100:06B6D4" alt="" width="100%">

</div>
