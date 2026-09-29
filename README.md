<div align="center">

<h1>Sanskar Agarwal</h1>

<p><samp>LLM INFERENCE · SOFTWARE ENGINEERING · DATA SYSTEMS</samp></p>

<p>I work on inference systems, reproducible benchmarks and software used in production.</p>

<p><a href="mailto:saga0288@uni.sydney.edu.au"><img src="https://img.shields.io/badge/Email-Get_in_touch-6366F1?style=for-the-badge&logo=gmail&logoColor=white&labelColor=1E293B" alt="Email Sanskar"></a> <a href="https://github.com/Sanskar-Agarwal?tab=followers"><img src="https://img.shields.io/github/followers/Sanskar-Agarwal?style=for-the-badge&logo=github&logoColor=white&label=Follow&color=0D9488&labelColor=1E293B" alt="Follow on GitHub"></a></p>

<p><a href="#selected-projects">Selected projects</a> · <a href="#toolkit">Toolkit</a> · <a href="#recognition">Recognition</a> · <a href="#leadership-and-outreach">Leadership</a></p>

<p><img src="https://img.shields.io/badge/Applicants_served-2%2C000%2B-6366F1?style=flat-square&labelColor=1E293B" alt="2,000+ applicants served in production"> <img src="https://img.shields.io/badge/Setonix_timed_calls-29%2C040-2563EB?style=flat-square&labelColor=1E293B" alt="29,040 timed calls in the Setonix sweep"> <img src="https://img.shields.io/badge/Grid_records_streamed-400%2C000%2B-0D9488?style=flat-square&labelColor=1E293B" alt="400,000+ grid records streamed"></p>

</div>

## Focus areas

**⚡ Inference engineering:** Speculative decoding, prompt-lookup vs. draft-model drafting, KV caching, and serving with vLLM, SGLang and TensorRT-LLM.

**🧪 Rigorous benchmarking:** Token-for-token equality against a reference baseline, FP16 tie-break divergence analysis, and reproducible Slurm sweeps on HPC.

**🛠️ Production systems:** Django and React applications, streaming pipelines with MQTT and Flink, and publicly deployed dashboards.

## Selected projects

### ⚡ [The Cost of a Guess](https://github.com/Sanskar-Agarwal/Workload-Aware-Drafter-For-Speculative-Decoding)

<p><img src="https://img.shields.io/badge/ML_SYSTEMS-6366F1?style=flat-square" alt="ML systems"> <img src="https://img.shields.io/badge/HPC-2563EB?style=flat-square" alt="High-performance computing"></p>

Workload-aware drafter selection for speculative decoding. Compares plain autoregression, a Qwen3-0.6B neural drafter and prompt lookup against a Qwen3-4B target across SQuAD, JFLEG, Spider, CNN/DailyMail, CodeAlpaca and UltraChat.

- **Measurement:** Exact token equality plus an independent per-group check.
- **Investigation:** Traced an FP16 divergence to exact logit ties broken differently by the speculative path.
- **Result:** A task-aware router measured **10.62% lower latency** on held-out prompts, reported as a bounded engineering finding.

<sub><b>PyTorch · Hugging Face · Slurm · ROCm · MI250X</b></sub>

---

### 🔌 [Real-Time Electricity Data Pipeline](https://github.com/Sanskar-Agarwal/real-time-electricity-data-pipeline)

<p><img src="https://img.shields.io/badge/DATA_ENGINEERING-0D9488?style=flat-square" alt="Data engineering"> <img src="https://img.shields.io/badge/STREAMING-0891B2?style=flat-square" alt="Streaming"></p>

*Live data engineering · 2026*

End-to-end pipeline that ingests live generation and CO₂ emissions data for Australia's NEM grid from the OpenElectricity API.

- **Scale:** Processed **400,000+** time-series records.
- **Pipeline:** Streamed facility-level power and emissions over MQTT.
- **Dashboard:** Interactive Plotly dashboard, publicly deployed for a month with **1,000+ visits**.

<sub><b>Python · MQTT · Pandas · Plotly · OpenElectricity API</b></sub>

---

### 🎓 Predictive ATAR Calculator

<p><img src="https://img.shields.io/badge/FULL_STACK-2563EB?style=flat-square" alt="Full stack"> <img src="https://img.shields.io/badge/PRODUCTION-0D9488?style=flat-square" alt="Production"></p>

*Full-stack web app · 2026*

Implements **8 ATAR methodologies** (NSW, VIC, WA, QLD, SA, TAS, ACT, IB) with linear-programming subject selection.

- **Integration:** Real-time result logging through the Google Sheets API.
- **Production use:** Used by **10 concurrent assessors** across a scholarship round of **2,000+ applicants**.

<sub><b>Python · Django · React · SQLite · PuLP · Docker</b></sub>

## Currently

- Working on workload-aware speculative decoding on **Setonix at Pawsey**, using **AMD MI250X** GPUs.
- Studying inference systems: arithmetic intensity, quantisation, caching, parallelism and disaggregated serving.

## Toolkit

**Languages**

<p><img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"> <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java"> <img src="https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white" alt="C"> <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript"> <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white" alt="SQL"> <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5"> <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" alt="CSS3"></p>

**ML and inference**

<p><img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch"> <img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="Hugging Face"> <img src="https://img.shields.io/badge/vLLM-30A2FF?style=flat-square" alt="vLLM"> <img src="https://img.shields.io/badge/SGLang-7C3AED?style=flat-square" alt="SGLang"> <img src="https://img.shields.io/badge/TensorRT--LLM-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="TensorRT-LLM"> <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="scikit-learn"> <img src="https://img.shields.io/badge/spaCy-09A3D5?style=flat-square&logo=spacy&logoColor=white" alt="spaCy"> <img src="https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white" alt="SciPy"></p>

**Data and web**

<p><img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="Pandas"> <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" alt="NumPy"> <img src="https://img.shields.io/badge/Apache_Flink-E6526F?style=flat-square&logo=apacheflink&logoColor=white" alt="Apache Flink"> <img src="https://img.shields.io/badge/MQTT-660066?style=flat-square&logo=mqtt&logoColor=white" alt="MQTT"> <img src="https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white" alt="Django"> <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React"> <img src="https://img.shields.io/badge/PuLP-2E8B57?style=flat-square" alt="PuLP"> <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" alt="MongoDB"> <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" alt="SQLite"></p>

**Infrastructure**

<p><img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux"> <img src="https://img.shields.io/badge/Slurm-0E7490?style=flat-square" alt="Slurm"> <img src="https://img.shields.io/badge/AMD_ROCm-ED1C24?style=flat-square&logo=amd&logoColor=white" alt="AMD ROCm"> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker"> <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git"></p>

## Recognition

| Recognition | Details |
| :--- | :--- |
| 🎓 **Top ~5% of cohort** | Master of Computer Science · **WAM 88/100**, High Distinction |
| 📚 **High Distinctions** | IT Innovations **99** ·Machine Learning and Data Mining **93** · Computational Statistical Methods **92** · Statistics **91** · Data Engineering **88** |
| 🏅 **Awards** | International Student Award **AUD 25,000** · PG High Honour Roll **2025** |
| 🌏 **Melbourne** | Deputy Vice-Chancellor (International) Award · People Leadership Award **2023** · Leaders in Community Award **2022** |

## Leadership and outreach

Faculty and Outreach Communicator, and previously President of the International Student Union.

- Postgraduate mentorship program with **60+ mentees**.
- STEM workshops for **Year 6 to 12** students.
- Represented **27,000+ international students** and managed a **AUD 400,000 budget**.

---

<div align="center">
  <sub>Interested in inference systems, data engineering or a project here? <a href="mailto:saga0288@uni.sydney.edu.au">Get in touch.</a></sub>
</div>
