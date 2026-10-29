<p align="center">
  <img src="https://raw.githubusercontent.com/ma-pmo/ma-pmo-ext/main/docs/assets/logo.png" alt="MA-PMO logo: seven smiling agents holding hands around a checkmark" width="180">
</p>

<h1 align="center">Hi, we're MA-PMO 👋</h1>

<p align="center">
  <b>Seven little AI agents that run your PMO — and always ask a human before the big decisions.</b><br>
  PMO를 대신 굴려주는 7명의 작은 AI 에이전트 — 중요한 결정은 꼭 사람에게 물어봐요.
</p>

<p align="center">
  <a href="https://github.com/ma-pmo/ma-pmo-ext"><img alt="Repository" src="https://img.shields.io/badge/repo-ma--pmo--ext-5A9BF0?logo=github"></a>
  <a href="https://pypi.org/project/ma-pmo/"><img alt="PyPI" src="https://img.shields.io/pypi/v/ma-pmo?color=7ED6A7"></a>
  <a href="https://github.com/ma-pmo/ma-pmo-ext/blob/main/LICENSE"><img alt="License: AGPL v3 + commercial" src="https://img.shields.io/badge/license-AGPL--3.0%20%2B%20commercial-FFC857"></a>
  <img alt="English and Korean" src="https://img.shields.io/badge/lang-EN%20%7C%20KO-F48FB1">
</p>

---

<p align="center">
  <img src="https://raw.githubusercontent.com/ma-pmo/ma-pmo-ext/main/docs/assets/demo.gif" alt="MA-PMO demo: dashboard, a four-phase agent scenario, language switch and the approval queue" width="860">
</p>

## 🤖 Meet the team · 에이전트 소개

| | Agent | What it does | 하는 일 |
|:-:|---|---|---|
| 🧭 | **A1 Orchestrator** | reads your goal and hands out the work | 목표를 읽고 일을 나눠줘요 |
| 📅 | **A2 Planning** | finds the critical path (CPM) and the real finish date | 임계경로(CPM)와 진짜 완료일을 찾아요 |
| 🧑‍🤝‍🧑 | **A3 Resources** | matches people by skill and spots overload | 스킬에 맞게 사람을 배치하고 과부하를 찾아요 |
| 🚨 | **A4 Risk** | catches risks early, before they hurt | 리스크를 아프기 전에 미리 잡아요 |
| 📝 | **A5 Reporting** | writes the executive report for you | 경영 보고서를 대신 써요 |
| 🚦 | **A6 Governance** | checks stage gates G1–G4 | 스테이지 게이트 G1~G4를 심사해요 |
| 📚 | **A7 Knowledge** | answers from past lessons — always with sources | 과거 교훈에서 답해요 — 출처는 항상 함께 |

…and **you** 🙋 approve anything risky in the human-in-the-loop queue. · 위험한 결정은 **사람**이 승인 큐에서 최종 결정해요.

## ✨ Why it's nice · 이런 점이 좋아요

- 🔌 **Works offline** — no API key needed to try it. Plug in Claude or a free local Ollama model when you're ready. · API 키 없이 바로 체험, 준비되면 Claude나 무료 Ollama 연결.
- 🧾 **Auditable** — agents talk in versioned, schema-checked messages saved to an append-only log. · 모든 대화는 스키마 검증 + 추가 전용 로그로 남아요.
- 📊 **Measurable** — five KPI axes (time, resource, delivery, risk, cost) and 20 lifecycle scenarios. · 5축 KPI와 20개 생애주기 시나리오.
- 🌏 **English & 한국어** — dashboard, API and reports in both languages. · 대시보드·API·보고서 모두 두 언어 지원.

## 📸 A quick look · 미리보기

<table>
  <tr>
    <td align="center"><img src="https://raw.githubusercontent.com/ma-pmo/ma-pmo-ext/main/docs/assets/dashboard-en.png" alt="Dashboard with five-axis KPIs" width="420"><br><sub>Dashboard · 대시보드</sub></td>
    <td align="center"><img src="https://raw.githubusercontent.com/ma-pmo/ma-pmo-ext/main/docs/assets/scenario-trace-ko.png" alt="Four-phase scenario trace in Korean" width="420"><br><sub>Agents at work (한국어 UI) · 에이전트 협업</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="https://raw.githubusercontent.com/ma-pmo/ma-pmo-ext/main/docs/assets/scenarios-en.png" alt="Scenario catalog" width="420"><br><sub>20 scenarios · 20개 시나리오</sub></td>
    <td align="center"><img src="https://raw.githubusercontent.com/ma-pmo/ma-pmo-ext/main/docs/assets/approvals-en.png" alt="Human-in-the-loop approval queue" width="420"><br><sub>You approve · 사람이 승인</sub></td>
  </tr>
</table>

## 🚀 Try it in a minute · 1분 만에 써보기

```bash
pip install ma-pmo
ma-pmo init-db && ma-pmo serve     # → http://127.0.0.1:8000/docs
```

Full guide with the dashboard: **[ma-pmo-ext](https://github.com/ma-pmo/ma-pmo-ext)** · 한국어 안내: **[README.ko.md](https://github.com/ma-pmo/ma-pmo-ext/blob/main/README.ko.md)**

## 💌 Say hi · 연락하기

- 🐛 Bugs & ideas → [Issues](https://github.com/ma-pmo/ma-pmo-ext/issues) · 버그·아이디어는 이슈로
- 🤝 Want to contribute? → [CONTRIBUTING](https://github.com/ma-pmo/ma-pmo-ext/blob/main/CONTRIBUTING.md) · 기여 환영해요
- 💼 Commercial license, support & questions → **[mjinttt@gmail.com](mailto:mjinttt@gmail.com)** · 상업적 이용·지원·문의는 메일로

<p align="center"><sub>Open source under AGPL-3.0 · commercial licenses available · "MA-PMO" is a trademark of myeongjin.ji</sub></p>
