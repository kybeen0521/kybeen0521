<!-- kybeen0521/kybeen0521 리포의 README.md 로 넣으면 프로필 상단에 렌더링됩니다 -->

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3500&pause=1000&color=2E9EF7&center=true&vCenter=true&width=680&lines=PHM+%26+Machinery+Signal+Intelligence;Time-Series+Foundation+Models;AI+Agents+on+the+Edge+(Jetson)" alt="Typing SVG" />

</div>

---

## 👋 About me

**Yongbeen Kim** — Researcher at the intersection of **Prognostics & Health Management (PHM)**,
**machinery / signal intelligence**, and **AI agents**.

I turn machine vibration into decisions — remaining useful life, fault diagnosis, operating-point
optimization — and I automate the research loop around it with LLM-based multi-agent systems running
on edge devices.

- 🔧 **Domain:** rotating machinery — motors, bearings, pumps/fans; vibration & acceleration signals
- 🧠 **Method:** Time-Series Foundation Models (MOMENT, TimesFM), Gaussian-process surrogates, operator learning (FNO/PINN)
- 🤖 **Systems:** planner / executor / validator multi-agent orchestration on NVIDIA Jetson
- 📍 Korea · 📫 kybeen0521@gmail.com

---

## 🔬 Research interests

- **PHM / RUL** — bearing & motor remaining-useful-life under label noise and sparse-measurement regimes
- **Time-Series Foundation Models** — adapting TSFMs to industrial vibration far outside their pretraining granularity
- **AI Agents** — edge multi-agent harnesses, deterministic validation, code-as-harness design
- **Scientific ML** — GP surrogates, Fourier/operator methods (FNO), physics-informed models for machinery

---

## 🚀 Selected Work

| Area | Project | Summary |
|------|---------|---------|
| **PHM 실증** | **IE4 Motor Field Trial** | 부산 자갈치 IE4 고효율 모터 현장에 MotorSense 진동센서 설치 → WiFi AP → 클라우드 Console → API 파형 수집 파이프라인 구축 (현장 출장·통신 셋업·데이터셋 생성) |
| **유체기기 최적화** | **KETI_FLOW** | 펌프/팬 운전점 최적화 시스템 — 표준 CSV → **GPR 대리모델**(Head·Power) → LUT·PQ맵 사전계산 → MQTT 학습수신 + TCP 예측루프 런타임 |
| **Agentic AI (CAE)** | **mcp-design** | 사람 vs 에이전트 "설계 계측기" — 동일 `issue→gate→author→build→measure→verify` 하니스를 **Blender 형상 저작 · OpenFOAM CFD(Cd/Cl) · 크레인 훅 구조해석(Blender→MPSD 라이브 2-툴)** 세 도메인에 적용, 결정론은 코드·판단만 LLM |
| **PHM / RUL** | **Bearing RUL (KSPHM)** | KSPHM-KIMM Data Challenge 2026 — ~900 물리기반 진동 특징 + total-life quantile(HistGBM) + floor 후처리, CV-LB 불일치 규명 → **최종 11위 (0.4923)** |
| **Edge Agents** | **pi-orchestration · watcher-agent** | Jetson 로컬 멀티에이전트(planner/executor/validator), GitHub commit → diff 요약 → Slack 자동 리포팅 봇 |
| **Knowledge Base** | **knowledge-vault** | 논문 리뷰 110+ 노트(Agentic-AI / SciML-PINN / DL foundations) + 자작 Claude 스킬 6종(paper-summary, obsidian-notes 등) |

> 소속: KETI (Korea Electronics Technology Institute)

<details>
<summary>🔗 <b>Project repositories</b></summary>

<br/>

- **[mcp-design](https://github.com/kybeen0521/mcp-design)** — 사람 vs 에이전트 CAE 설계 하니스 (Blender · OpenFOAM · 크레인 훅)
- **[knowledge-vault](https://github.com/kybeen0521/knowledge-vault)** — 논문 리뷰 · SciML/Agentic-AI 노트 · 자작 Claude 스킬
- **[phm](https://github.com/kybeen0521/phm)** — 교번운전 회전기기 정지시점 가속도 기반 고장 식별
- **KETI_FLOW** · **KETI_KSPHM_data_challenge_2026** — KETI 협업 repo (팀 계정)

</details>

---

## 🛠️ Tech Stack

**Language & Scientific Computing**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat&logo=scipy&logoColor=white)

**ML / SciML**  
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![Transformers](https://img.shields.io/badge/Transformers-FFD21E?style=flat&logo=huggingface&logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)

**Edge / Infra**  
![NVIDIA Jetson](https://img.shields.io/badge/Jetson-76B900?style=flat&logo=nvidia&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![MQTT](https://img.shields.io/badge/MQTT-660066?style=flat&logo=mqtt&logoColor=white)

**Tooling**  
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

---

## 📊 GitHub Stats

<div align="center">

![Followers](https://img.shields.io/github/followers/kybeen0521?style=flat&logo=github&logoColor=white&label=Followers&labelColor=2E9EF7&color=0d1117)
![Stars](https://img.shields.io/github/stars/kybeen0521?style=flat&logo=github&logoColor=white&label=Stars&labelColor=2E9EF7&color=0d1117&affiliations=OWNER)
![Last commit](https://img.shields.io/github/last-commit/kybeen0521/kybeen0521?style=flat&logo=github&logoColor=white&label=Last%20commit&labelColor=2E9EF7&color=0d1117)

<br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/kybeen0521/kybeen0521/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/kybeen0521/kybeen0521/output/github-snake.svg" />
  <img alt="Contribution snake animation" src="https://raw.githubusercontent.com/kybeen0521/kybeen0521/output/github-snake.svg" />
</picture>

<br/>

<!-- generated by .github/workflows/metrics.yml into main -->
<img alt="Language & activity metrics" src="https://raw.githubusercontent.com/kybeen0521/kybeen0521/main/metrics.svg" width="560" />

</div>

---

<div align="center">
<img src="https://komarev.com/ghpvc/?username=kybeen0521&label=Profile%20views&color=2E9EF7&style=flat" alt="views" />
</div>
