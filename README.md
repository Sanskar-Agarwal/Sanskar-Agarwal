<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="banner-dark.svg">
  <img src="banner.svg" alt="Sanskar Agarwal: LLM inference, software engineering, data" width="100%">
</picture>

<a href="mailto:saga0288@uni.sydney.edu.au"><img src="https://img.shields.io/badge/Email-Get_in_touch-5b5bf0?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
<a href="https://github.com/Sanskar-Agarwal?tab=followers"><img src="https://img.shields.io/github/followers/Sanskar-Agarwal?style=for-the-badge&logo=github&label=Follow&color=6e40c9" alt="Follow"></a>

</div>



<div align="center">

<img src="https://img.shields.io/badge/2%2C000%2B-APPLICANTS_SERVED_IN_PRODUCTION-5b5bf0?style=for-the-badge" alt="2,000+ applicants served in production">
<img src="https://img.shields.io/badge/29%2C040-TIMED_CALLS_IN_THE_SETONIX_SWEEP-e5484d?style=for-the-badge" alt="29,040 timed calls in the Setonix sweep">
<img src="https://img.shields.io/badge/400%2C000%2B-GRID_RECORDS_STREAMED-0ea5a4?style=for-the-badge" alt="400,000+ grid records streamed">

</div>

## Focus areas

<table>
  <tr>
    <th width="33%">⚡ Inference engineering</th>
    <th width="33%">🧪 Rigorous benchmarking</th>
    <th width="33%">🛠️ Production systems</th>
  </tr>
  <tr>
    <td valign="top">Speculative decoding, prompt-lookup vs. draft-model drafting, KV caching, and serving with vLLM, SGLang and TensorRT-LLM.</td>
    <td valign="top">Token-for-token equality against a reference baseline, FP16 tie-break divergence analysis, and reproducible Slurm sweeps on HPC.</td>
    <td valign="top">Django and React applications, streaming pipelines with MQTT and Flink, and dashboards deployed publicly.</td>
  </tr>
</table>

## Featured work

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>⚡ <a href="https://github.com/Sanskar-Agarwal/Workload-Aware-Drafter-For-Speculative-Decoding">The Cost of a Guess</a></h3>
      <sub><i>COMP5709 capstone · supervised by A/Prof Nguyen H. Tran</i></sub>
      <p>Workload-aware drafter selection for speculative decoding. Compares plain autoregression, a Qwen3-0.6B neural drafter and prompt lookup against a Qwen3-4B target across SQuAD, JFLEG, Spider, CNN/DailyMail, CodeAlpaca and UltraChat.</p>
      <ul>
        <li>Strict measurement protocol: exact token equality plus an independent per-group check.</li>
        <li>Traced an FP16 divergence to exact logit ties broken differently by the speculative path.</li>
        <li>A task-aware router measured <b>10.62% lower latency</b> on held-out prompts, reported as a bounded engineering finding.</li>
      </ul>
      <sub><b>PyTorch · Hugging Face · Slurm · ROCm · MI250X</b></sub>
    </td>
    <td width="50%" valign="top">
      <h3>🔌 <a href="https://github.com/Sanskar-Agarwal/real-time-electricity-data-pipeline">Real-Time Electricity Data Pipeline</a></h3>
      <sub><i>Live data engineering · 2026</i></sub>
      <p>End-to-end pipeline that ingests live generation and CO₂ emissions data for Australia's NEM grid from the OpenElectricity API.</p>
      <ul>
        <li>Processed <b>400,000+</b> time-series records.</li>
        <li>Streamed facility-level power and emissions over MQTT.</li>
        <li>Interactive Plotly dashboard, publicly deployed for a month with <b>1,000+ visits</b>.</li>
      </ul>
      <sub><b>Python · MQTT · Pandas · Plotly · OpenElectricity API</b></sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🎓 Predictive ATAR Calculator</h3>
      <sub><i>Full-stack web app · 2026</i></sub>
      <p>Implements <b>8 ATAR methodologies</b> (NSW, VIC, WA, QLD, SA, TAS, ACT, IB) with linear-programming subject selection.</p>
      <ul>
        <li>Real-time result logging through the Google Sheets API.</li>
        <li>In production, used by 10 concurrent assessors across a scholarship round of <b>2,000+ applicants</b>.</li>
      </ul>
      <sub><b>Python · Django · React · SQLite · PuLP · Docker</b></sub>
    </td>
    <td width="50%" valign="top">
      <h3>🏛️ Leadership and outreach</h3>
      <p>Faculty and Outreach Communicator, and previously President of the International Student Union.</p>
      <ul>
        <li>Postgraduate mentorship program with <b>60+ mentees</b>.</li>
        <li>STEM workshops for Year 6 to 12 students.</li>
        <li>Represented <b>27,000+</b> international students and managed a <b>AUD 400,000</b> budget.</li>
      </ul>
      <sub><b>Leadership · Teaching · Community</b></sub>
    </td>
  </tr>
</table>

## Currently

- Finishing the speculative-decoding capstone on **Setonix (Pawsey, AMD MI250X)**.
- Studying inference systems: arithmetic intensity, quantisation, caching, parallelism and disaggregated serving.
- Looking for **graduate roles in ML systems, inference engineering and data/software engineering**.

## Recognition

| | |
|---|---|
| 🎓 **Top ~5% of cohort**, Master of Computer Science | WAM 86/100 · High Distinction |
| 📚 **High Distinctions** | Machine Learning and Data Mining (93) · Computational Statistical Methods (92) · Statistics (91) · Data Engineering (88) |
| 🏅 **Awards** | International Student Award (AUD 25,000) · PG High Honour Roll 2025 |
| 🌏 **Melbourne** | Deputy Vice-Chancellor (International) Award · People Leadership Award 2023 · Leaders in Community Award 2022 |

## Toolkit

<div align="center">

**Languages**<br>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
<img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java">
<img src="https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white" alt="C">
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript">
<img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white" alt="SQL">
<img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5">
<img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" alt="CSS3">
<br><br>

**ML and inference**<br>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch">
<img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="Hugging Face">
<img src="https://img.shields.io/badge/vLLM-30A2FF?style=flat-square" alt="vLLM">
<img src="https://img.shields.io/badge/SGLang-7C3AED?style=flat-square" alt="SGLang">
<img src="https://img.shields.io/badge/TensorRT--LLM-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="TensorRT-LLM">
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="scikit-learn">
<img src="https://img.shields.io/badge/spaCy-09A3D5?style=flat-square&logo=spacy&logoColor=white" alt="spaCy">
<img src="https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white" alt="SciPy">
<br><br>

**Data and web**<br>
<img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="Pandas">
<img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" alt="NumPy">
<img src="https://img.shields.io/badge/Apache_Flink-E6526F?style=flat-square&logo=apacheflink&logoColor=white" alt="Apache Flink">
<img src="https://img.shields.io/badge/MQTT-660066?style=flat-square&logo=mqtt&logoColor=white" alt="MQTT">
<img src="https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white" alt="Django">
<img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React">
<img src="https://img.shields.io/badge/PuLP-2E8B57?style=flat-square" alt="PuLP">
<img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" alt="MongoDB">
<img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" alt="SQLite">
<br><br>

**Infrastructure**<br>
<img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux">
<img src="https://img.shields.io/badge/Slurm-0E7490?style=flat-square" alt="Slurm">
<img src="https://img.shields.io/badge/AMD_ROCm-ED1C24?style=flat-square&logo=amd&logoColor=white" alt="AMD ROCm">
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git">
<br><br>

</div>
