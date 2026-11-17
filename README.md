<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=Vaishnav%20Veeraraghavan%20Prasad&fontSize=42&fontColor=fff&animation=twinkling&fontAlignY=32&desc=ML%20Engineer%20%7C%20Data%20Analyst%20%7C%20Software%20Developer&descAlignY=55&descSize=18"/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3000&pause=1000&color=6AD4F7&center=true&vCenter=true&multiline=false&width=800&lines=MSc+Computing+Science+Graduate+%40+Glasgow;Building+End-to-End+ML+Systems;LLM+Compression+%7C+Edge+AI+%7C+MLOps;Python+%7C+PyTorch+%7C+FastAPI+%7C+Docker)](https://git.io/typing-svg)

</div>

---

## 🧑‍💻 About Me

```python
class Vaishnav:
    def __init__(self):
        self.name = "Vaishnav Veeraraghavan Prasad"
        self.degree = "MSc Computing Science, University of Glasgow"
        self.undergrad = "BTech Computer Science"
        self.location = "Glasgow, United Kingdom"
        self.languages = ["Tamil", "English", "German (learning)"]

        self.interests = [
            "Machine Learning Engineering",
            "LLM Engineering",
            "Computer Vision",
            "Edge AI",
            "MLOps",
            "AI Deployment"
        ]

        self.current_focus = [
            "Building end-to-end ML pipelines",
            "Efficient LLM deployment",
            "Model evaluation and experimentation"
        ]

    def say_hi(self):
        print("Thanks for stopping by! Let's build something useful.")

me = Vaishnav()
me.say_hi()
```

I'm an MSc Computing Science graduate from the University of Glasgow with industry experience in Python development, machine learning, computer vision and industrial software.

My work includes developing a YOLOv8-based computer vision system achieving **94.91% validation mAP@0.50**, and researching architecture-adaptive LLM compression through structured pruning, quantisation and LoRA-based recovery.

I've also built an end-to-end customer churn prediction pipeline incorporating scikit-learn, PyTorch, MLflow, FastAPI and Docker.

I'm particularly interested in building reliable, efficient machine learning systems and deploying AI models in practical environments.

---

## 🛠️ Tech Stack

<div align="center">

**Programming Languages & Databases**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)

**Machine Learning & Data Science**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Scikit Learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Hugging Face](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![YOLO](https://img.shields.io/badge/YOLOv8-FF6F00?style=for-the-badge)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)

**MLOps & Deployment**

![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)

**LLM Engineering & Model Optimisation**

![LoRA](https://img.shields.io/badge/LoRA-Fine--Tuning-8A2BE2?style=for-the-badge)
![Quantization](https://img.shields.io/badge/Quantization-Model%20Compression-7057FF?style=for-the-badge)
![llama.cpp](https://img.shields.io/badge/llama.cpp-000000?style=for-the-badge)

**Development Tools & Frameworks**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![PyQt6](https://img.shields.io/badge/PyQt6-41CD52?style=for-the-badge&logo=qt&logoColor=white)
![Django REST](https://img.shields.io/badge/Django%20REST-092E20?style=for-the-badge&logo=django&logoColor=white)

</div>

---

## 🚀 Featured Projects

### 1. Customer Churn Prediction Pipeline | End-to-End MLOps

**[View GitHub Repository](YOUR-CHURN-REPOSITORY-LINK)**

An end-to-end, containerised customer churn prediction system comparing traditional machine learning with a neural network.

- Developed a scikit-learn logistic regression pipeline and a PyTorch neural network challenger.
- Achieved **0.852 holdout ROC AUC** with the scikit-learn model, compared with 0.849 for PyTorch.
- Implemented leakage-safe preprocessing using ColumnTransformer and stratified 5-fold cross-validation.
- Integrated MLflow for experiment tracking and skops for model persistence.
- Built a Pydantic-validated FastAPI prediction service and packaged it using Docker.
- Implemented batch customer risk scoring and handling of unseen categorical values.

**Technologies:** Python, scikit-learn, PyTorch, MLflow, FastAPI, Docker, Pydantic, skops.

<sub>Built using a synthetic dataset of 2,500 customers as an engineering and MLOps project.</sub>

### 2. Model-Agnostic Structured Pruning and Recovery for Edge Deployment of Sub-7B Language Models | MSc Thesis

**[View Portfolio / Research](YOUR-THESIS-PORTFOLIO-LINK)**

Developed an architecture-adaptive LLM compression pipeline combining structured pruning, low-bit quantisation and LoRA-based recovery.

- Reduced TinyLlama-1.1B model size from **2,098.2 MB to 517.07 MB**, achieving 4.06× compression while retaining classification accuracy (88.93% to 88.95%).
- Extended the pipeline to Qwen2.5-1.5B without architecture-specific changes.
- Developed a Streamlit interface for model compression and evaluation.
- Tested CPU-only inference on the STM32MP257F-DK edge platform using llama.cpp.
- Achieved inference speeds of 1.91 tokens/sec on TinyLlama and 1.25 tokens/sec on Qwen2.5.

**Technologies:** Python, PyTorch, Hugging Face, LoRA, Structured Pruning, Quantisation, Streamlit, llama.cpp.

### 3. ML Component Detection & Inventory Management

**[View GitHub Repository](https://github.com/pvvraghavan/ml-component-detection-inventory)**

Industry-sponsored computer vision and industrial software project.

- Developed a YOLOv8s model to detect and classify electrical components in dense design schematics.
- Achieved **94.91% validation mAP@0.50**.
- Built a PyQt6 desktop application with PostgreSQL integration.
- Implemented automated Bill of Materials (BOM) generation and component tracking.
- Led a four-person development team and presented progress to senior management.

**Technologies:** Python, YOLOv8, PyTorch, PyQt6, PostgreSQL.

### 4. Pune Tourism Website

**[View Live Website](https://pvvraghavan.github.io/PuneTourismWebsite/)**

Responsive tourism website featuring city attractions, interactive maps and geolocation functionality.

**Technologies:** HTML, CSS, JavaScript, Geolocation API.

---

## 📄 Publications

| Year | Publication | Venue |
|:---:|---|---|
| 2026 | *A Computer Vision Approach for Electrical Design Component Detection and Management using Deep Learning* | AICCoNS 2026, University of Wollongong in Dubai |
| 2024 | [AI and Privacy: Ethical Concerns in Data Collection and Surveillance](https://www.ijfmr.com) | International Journal for Multidisciplinary Research, Vol. 6, Issue 6 |

---

## 💼 Professional Experience

**Machine Learning Project Intern | Kristl Seibt India Pvt. Ltd.**  
*September 2024 – May 2025*

- Led a four-person team developing an industrial component-tracking solution.
- Developed a PyQt application integrating PostgreSQL inventory management, automated BOM generation and computer vision.
- Fine-tuned YOLOv8s for electrical schematic component detection, achieving 94.91% validation mAP@0.50.
- Presented technical progress to the Managing Director during regular reviews.

**Software Developer Intern | Kristl Seibt India Pvt. Ltd.**  
*May 2024 – August 2024*

- Developed a PyQt6 and PostgreSQL application for roller chassis dynamometer testing.
- Automated Siemens S7 PLC data acquisition using Python and dynamic hardware-address mapping.

**Web Developer Intern | Lisys Technocraft**  
*February 2024 – March 2024*

- Developed a responsive web application using HTML, CSS and JavaScript.

**Software Developer | Kristl Seibt India Pvt. Ltd.**  
*June 2023 – August 2023*

- Built Python-based visualisation tools for industrial automation test results and performance anomalies.
- Automated test-report generation to reduce manual reporting effort.

---

## 🎓 Education

**MSc Computing Science — Merit**  
University of Glasgow | September 2025 – September 2026

Dissertation: *Model-Agnostic Structured Pruning and Recovery for Edge Deployment of Sub-7B Language Models.*

**BTech Computer Science**  
DY Patil International University, Pune | October 2021 – June 2025

---

## 🏆 Certifications

- 🥇 **NPTEL Cloud Computing** — 86%, Top 5% Nationwide in India (July – October 2024).
- 🥈 **NPTEL Internet of Things (IoT)** — 84% (July – October 2024).

---

## 📬 Let's Connect

<div align="center">

[![Email](https://img.shields.io/badge/Email-raghavanprasad2003%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:raghavanprasad2003@gmail.com)

[![GitHub](https://img.shields.io/badge/GitHub-pvvraghavan-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/pvvraghavan)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/YOUR-LINKEDIN-HERE)

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer"/>

![Visitor Count](https://komarev.com/ghpvc/?username=pvvraghavan&color=6AD4F7&style=flat&label=Profile+Views)

</div>
