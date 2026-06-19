<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=FF5C00&height=120&section=header&text=Mathew%20Carballo&fontSize=36&fontColor=ffffff&fontAlignY=65&desc=Software%20Engineer%20%E2%80%A2%20Python%20%C2%B7%20Cloud%20%C2%B7%20XR&descSize=14&descAlignY=85&descColor=ffffff" />

[![Open to Work](https://img.shields.io/badge/▶_open_to_work-FF5C00?style=for-the-badge&labelColor=1A1A18)](mailto:macarb2831@gmail.com)
[![Portfolio](https://img.shields.io/badge/△_portfolio-contrainfinito.github.io-FF5C00?style=for-the-badge&labelColor=1A1A18)](https://contrainfinito.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-mathewjc-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/mathewjc)
[![Email](https://img.shields.io/badge/email-macarb2831@gmail.com-333?style=for-the-badge&logo=gmail&logoColor=white)](mailto:macarb2831@gmail.com)

</div>

---

## About

Python engineer with hands-on machine learning and data pipeline experience — all projects deployed and open source on GitHub.

Recent work includes an end-to-end MLOps pipeline (RandomForest, 5-fold cross-validation, Dockerized FastAPI) where I caught and resolved a data leakage bug that was producing a suspiciously perfect R² of 0.9997 — investigated, found the cause, corrected it to an honest 0.80. Also built and deployed a Python CLI security auditor that ran against a live AWS account and identified 4 real IAM misconfigurations.

Currently working as a Simulation Software Engineer for PimaSens R&D (MacEwan University, Canada) on an international XR training project — full solution architecture, direct client engagement in English — and as an AI Systems Coding Specialist at Meridial evaluating production AI voice agents: professionally trained to know when a model is wrong and explain it clearly.

Practitioner of AI-assisted development through structured agent orchestration, custom skill systems, and multi-model workflows. Published open-source tooling to PyPI (Praxis — IBM Bob Hackathon 2026).

B.Sc. Computer Engineering, TEC Costa Rica (Jun 2026).
---

## △ Projects

### △ 4807m &nbsp; Sentinel Band &nbsp; <sub>Band of Agents Hackathon 2026 · Track 3</sub>
![Python](https://img.shields.io/badge/Python-FF5C00?style=flat-square&logo=python&logoColor=white)
![Multi-Agent](https://img.shields.io/badge/multi--agent-FF5C00?style=flat-square)
![AWS](https://img.shields.io/badge/AWS-FF5C00?style=flat-square&logo=amazonaws&logoColor=white)
![Band](https://img.shields.io/badge/Band-SDK-333?style=flat-square)
![tests](https://img.shields.io/badge/tests-35_passing-1F7A44?style=flat-square)

Zero-trust, multi-agent system that automatically remediates AWS CIS-benchmark violations — **safely**. Four agents coordinate in one Band room over a deterministic pure-Python safety layer: Auditor and Verifier are read-only, the Scribe has no cloud access, and only Remediation can write — and only for low-risk, reversible fixes. **Four independent gates** must agree before any AWS write, every lookup fails closed, and a planted **prompt-injection produces zero actions**. Remove every LLM from the diagram and the safety still holds — it's backed by 35 tests, not prompts.

[![source](https://img.shields.io/badge/source-sentinel--band-333?style=flat-square&logo=github)](https://github.com/ContraInfinito/sentinel-band)
[![demo](https://img.shields.io/badge/narrated_demo-video-FF5C00?style=flat-square&labelColor=1A1A18)](https://github.com/ContraInfinito/sentinel-band/blob/main/docs/Sentinel_Band_narrated.mp4)

<table>
<tr>
<td width="33%" valign="top">

### △ 3842m &nbsp; Praxis
![Python](https://img.shields.io/badge/Python-FF5C00?style=flat-square&logo=python&logoColor=white)
![PyPI](https://img.shields.io/badge/PyPI-published-FF5C00?style=flat-square)
![CLI](https://img.shields.io/badge/CLI-tool-333?style=flat-square)

Python CLI that reads a codebase and generates idiomatic AI agent config for **Bob IDE**, **Claude Code**, and **Cursor** simultaneously. Seven-principle methodology contract encoded in each target. Built solo in 48h for IBM Bob Hackathon 2026.

[![pip install praxis-bob](https://img.shields.io/badge/pip%20install-praxis--bob-FF5C00?style=flat-square&labelColor=1A1A18)](https://pypi.org/project/praxis-bob/)
[![source](https://img.shields.io/badge/source-bob--praxis-333?style=flat-square&logo=github)](https://github.com/ContraInfinito/bob-praxis)

</td>
<td width="33%" valign="top">

### △ 2647m &nbsp; aws-policy-auditor
![Python](https://img.shields.io/badge/Python-FF5C00?style=flat-square&logo=python&logoColor=white)
![boto3](https://img.shields.io/badge/boto3-FF5C00?style=flat-square&logo=amazonaws&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

Python CLI + FastAPI service auditing AWS IAM and S3 against **CIS benchmark rules** via boto3. 17 checks across two services. Ran against a real account — found and fixed 4 misconfigurations.

[![CI](https://github.com/ContraInfinito/aws-policy-auditor/actions/workflows/ci.yml/badge.svg)](https://github.com/ContraInfinito/aws-policy-auditor/actions)
[![live demo](https://img.shields.io/badge/demo-live-brightgreen?style=flat-square&labelColor=1A1A18)](https://aws-policy-auditor.onrender.com/docs)
[![source](https://img.shields.io/badge/source-333?style=flat-square&logo=github)](https://github.com/ContraInfinito/aws-policy-auditor)

</td>
<td width="33%" valign="top">

### △ 1203m &nbsp; ML Market Value
![Python](https://img.shields.io/badge/Python-FF5C00?style=flat-square&logo=python&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

End-to-end MLOps pipeline: 5-fold CV, Dockerized FastAPI, P50/P95 latency benchmarking. Caught and corrected a **data leakage bug** — R²=0.9997 → honest R²=0.80.

[![live demo](https://img.shields.io/badge/demo-live-brightgreen?style=flat-square&labelColor=1A1A18)](https://ml-infrastart.onrender.com)
[![source](https://img.shields.io/badge/source-333?style=flat-square&logo=github)](https://github.com/ContraInfinito/ml-infrastart)

</td>
</tr>
</table>

---

## Skills

<div align="center">

**Languages**&nbsp;&nbsp;
[![skills](https://skillicons.dev/icons?i=python,go,ts,js,java,cs,cpp&theme=light)](https://github.com/ContraInfinito)

**Cloud & Infra**&nbsp;&nbsp;
[![skills](https://skillicons.dev/icons?i=aws,azure,docker,kubernetes,linux,githubactions&theme=light)](https://github.com/ContraInfinito)

**Backend & Data**&nbsp;&nbsp;
[![skills](https://skillicons.dev/icons?i=fastapi,postgres,prometheus,grafana&theme=light)](https://github.com/ContraInfinito)

**XR**&nbsp;&nbsp;
[![skills](https://skillicons.dev/icons?i=unity&theme=light)](https://github.com/ContraInfinito)

</div>

---

## Stats

<div align="center">

<a href="https://github.com/ContraInfinito">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=ContraInfinito&show_icons=true&bg_color=1A1A18&title_color=FF5C00&icon_color=FF5C00&text_color=e2e8ed&border_color=FF5C00&count_private=true&include_all_commits=true&hide_border=false" />
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ContraInfinito&layout=compact&bg_color=1A1A18&title_color=FF5C00&text_color=e2e8ed&border_color=FF5C00&langs_count=8&hide_border=false" />
</a>

</div>

---

## // status

```
role       ->  Software Engineer
grad       ->  Jun 2026 . TEC Costa Rica
english    ->  C1 (advanced / professional working)
pypi       ->  published  (pip install praxis-bob)
aws        ->  live scan confirmed . zero findings
band       ->  4 agents live . zero-trust AWS remediation
xr         ->  active . Meta Quest . PimaSens R&D
location   ->  10.3157 N, 84.5157 W . San Carlos, CR
```

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=FF5C00&height=80&section=footer" />

all projects open source &nbsp;·&nbsp; [contrainfinito.github.io](https://contrainfinito.github.io)

</div>
