<div align="center">

<img src="banner.svg" alt="Sanskar Agarwal: LLM inference, software engineering, data" width="100%">

<a href="mailto:saga0288@uni.sydney.edu.au"><img src="https://img.shields.io/badge/Email-Get_in_touch-5b5bf0?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
<a href="https://github.com/Sanskar-Agarwal?tab=followers"><img src="https://img.shields.io/github/followers/Sanskar-Agarwal?style=for-the-badge&logo=github&label=Follow&color=24292f" alt="Follow"></a>

</div>

## Measuring what makes LLM inference faster, and what doesn't.

Master of Computer Science student at the **University of Sydney** (Software Engineering, Data Science and AI), graduating November 2026 with a weighted average mark of **86/100 (top ~5% of cohort)**. I benchmark speculative decoding on AMD MI250X GPUs under strict output-equality checks, and I build data and web systems that run in production.

<table>
  <tr>
    <td align="center" width="25%"><h3>29,040</h3><sub>timed decoding calls in the capstone sweep</sub></td>
    <td align="center" width="25%"><h3>6</h3><sub>workloads benchmarked on Setonix MI250X</sub></td>
    <td align="center" width="25%"><h3>400,000+</h3><sub>grid records streamed and visualised</sub></td>
    <td align="center" width="25%"><h3>2,000+</h3><sub>applicants served by a production tool</sub></td>
  </tr>
</table>

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
      <sub><i>University of Sydney · University of Melbourne</i></sub>
      <p>Faculty Communicator at Sydney, and previously President of UMSU International at Melbourne.</p>
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

<table>
  <tr><td><b>Languages</b></td><td><code>Python</code> <code>Java</code> <code>C</code> <code>JavaScript</code> <code>SQL</code> <code>HTML/CSS</code></td></tr>
  <tr><td><b>ML and inference</b></td><td><code>PyTorch</code> <code>Hugging Face</code> <code>vLLM</code> <code>SGLang</code> <code>TensorRT-LLM</code> <code>scikit-learn</code> <code>spaCy</code> <code>SciPy</code></td></tr>
  <tr><td><b>Data and web</b></td><td><code>Pandas</code> <code>NumPy</code> <code>Apache Flink</code> <code>MQTT</code> <code>Django</code> <code>React</code> <code>PuLP</code> <code>MongoDB</code> <code>SQLite</code></td></tr>
  <tr><td><b>Infrastructure</b></td><td><code>Linux</code> <code>Slurm</code> <code>HPC (AMD ROCm / MI250X)</code> <code>Docker</code> <code>Git</code></td></tr>
</table>

</div>
