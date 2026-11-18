
from pathlib import Path

readme = r"""<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:101828,50:0077B6,100:00D9FF&height=190&section=header&text=JAAYDEEP%20PRAJAPATI&fontSize=52&fontColor=ffffff&animation=fadeIn&fontWeight=700&fontAlignY=38&desc=AI%20%7C%20Machine%20Learning%20%7C%20Deep%20Learning%20%7C%20Engineering&descSize=16&descAlignY=62&descColor=E0F2FE" width="100%" />

<br/>

<a href="https://jaaydeep.dev">Portfolio</a> •
<a href="https://linkedin.com/in/jaaydeep-prajapati">LinkedIn</a> •
<a href="https://twitter.com/jaaydeep_codes">Twitter</a> •
<a href="mailto:jaaydeep.prajapati@gmail.com">Email</a>

</div>

---

## About

AI and software engineering enthusiast focused on building intelligent systems,
exploring machine learning architectures, and engineering practical software
solutions.

My interests span deep learning, computer vision, AI infrastructure,
system optimization, and scalable backend engineering.

- **Focus:** AI, Machine Learning & Deep Learning
- **Interests:** Computer Vision, Model Optimization & AI Systems
- **Engineering:** Python, Backend Systems & Linux
- **Currently:** Building, experimenting and exploring intelligent systems

---

## Technical Focus

<table>
<tr>
<td width="50%" valign="top">

### AI & Machine Learning

- Deep Learning
- Neural Networks
- Computer Vision
- Model Optimization
- PyTorch
- TensorFlow
- OpenCV

</td>
<td width="50%" valign="top">

### Software Engineering

- Python
- JavaScript / TypeScript
- FastAPI
- Node.js
- React
- REST APIs
- Linux

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Data & Infrastructure

- PostgreSQL
- MongoDB
- Redis
- Docker
- AWS
- Cloud Infrastructure

</td>
<td width="50%" valign="top">

### Development Tools

- Git & GitHub
- VS Code
- Jupyter
- Linux
- ONNX

</td>
</tr>
</table>

---

## Featured Project

### TRINETRA — Neural Security Intelligence

An intelligent vision-based security system concept focused on video
analytics, object detection, tracking and automated security monitoring.

**Technical direction**

- Video processing and preprocessing pipelines
- Object detection using YOLO
- Neural network-based vision analysis
- Kalman-filter-based object tracking
- API-based system integration
- Edge-oriented optimization

**Technology:** Python · PyTorch · YOLO · OpenCV · FastAPI · Docker

[Project Repository](https://github.com/jaaydeep/TRINETRA) ·
[Technical Write-up](https://blog.jaaydeep.dev/trinetra)

---

## Other Engineering Interests

| Area | Focus |
|---|---|
| Neural Networks | Training, architecture and optimization |
| Computer Vision | Detection, tracking and image processing |
| AI Infrastructure | Efficient inference and deployment |
| Backend Engineering | APIs, services and distributed systems |
| Edge AI | Efficient computation on resource-constrained devices |
| Research | Experimentation, evaluation and implementation |

---

## GitHub Activity

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=jaaydeep&show_icons=true&hide_border=true&theme=transparent&title_color=0077B6&icon_color=0077B6&text_color=64748b" height="170" />

<img src="https://github-readme-streak-stats.demolab.com?user=jaaydeep&hide_border=true&theme=transparent&ring=0077B6&fire=00D9FF&currStreakLabel=0077B6" height="170" />

<br/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=jaaydeep&layout=compact&hide_border=true&theme=transparent&title_color=0077B6&text_color=64748b" height="150" />

</div>

---

## Engineering Principles

- **Understand the problem:** Architecture begins with requirements, not code.
- **Fundamentals first:** Strong foundations matter more than chasing trends.
- **Measure performance:** Benchmark before making optimization claims.
- **Build for reality:** Consider resource limits, reliability and deployment.
- **Continuous learning:** Research, experiment, implement and iterate.

---

## Connect

<div align="center">

<a href="https://jaaydeep.dev">
<img src="https://img.shields.io/badge/Portfolio-Visit-0077B6?style=flat" />
</a>
<a href="https://linkedin.com/in/jaaydeep-prajapati">
<img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin" />
</a>
<a href="mailto:jaaydeep.prajapati@gmail.com">
<img src="https://img.shields.io/badge/Email-Contact-EA4335?style=flat&logo=gmail" />
</a>

</div>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00D9FF,100:101828&height=100&section=footer" width="100%" />

<sub>Building, learning and engineering intelligent systems.</sub>

</div>
"""

output = Path("/mnt/agents/output/README.md")
output.parent.mkdir(parents=True, exist_ok=True)
output.write_text(readme, encoding="utf-8")

print("README.md saved successfully!")
print(f"Location: {output}")
print(f"Lines: {len(readme.splitlines())}")
print(f"Characters: {len(readme)}")
