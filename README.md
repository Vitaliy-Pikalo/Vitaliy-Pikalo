<!-- Profile README for github.com/Vitaliy-Pikalo — lives in the Vitaliy-Pikalo/Vitaliy-Pikalo repo -->

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,45:1f3b73,100:7aa2f7&height=210&section=header&text=Vitaliy%20Pikalo&fontSize=58&fontColor=ffffff&fontAlignY=36&desc=Computer%20Engineering%20%40%20Penn%20State%20%C2%B7%20quant%20research%20%2B%20software%20engineering&descSize=17&descAlignY=58&animation=fadeIn" alt="Vitaliy Pikalo" width="100%" />
</p>

<p align="center">
  <a href="https://github.com/Vitaliy-Pikalo">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1200&color=7AA2F7&center=true&vCenter=true&width=760&lines=I+test+ideas+until+they+break%2C+then+report+what+survived.;Market+microstructure+research+on+prediction+markets.;AlphaZero-style+Chess960+engine%2C+trained+from+self-play.;Founder+of+Pikalo+%E2%80%94+U.S.+finance+explained+for+immigrants." alt="Typing animation" />
  </a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/vitaliypikalo/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://vitaliypikalo.com"><img src="https://img.shields.io/badge/Portfolio-vitaliypikalo.com-1f3b73?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio" /></a>
  <a href="https://pikalo.org"><img src="https://img.shields.io/badge/Pikalo-pikalo.org-7aa2f7?style=for-the-badge&logo=vercel&logoColor=white" alt="Pikalo" /></a>
</p>

---

### About

- Computer Engineering at **Penn State University Park**, class of May 2028
- Looking for **Summer 2027 internships** in software engineering and quant development
- I build research tools and products end to end, and I report null results the same way I report wins
- Away from the keyboard: went 17-0 in singles playing NCAA D-III tennis, plus chess, poker, and pickleball

### Now

- **[Adverse Selection Lab](https://github.com/Vitaliy-Pikalo/adverse-selection-lab)** — measuring maker adverse selection on Kalshi BTC/ETH binaries: does a toxicity-aware quoting policy beat static and inventory-aware quoting under conservative fill assumptions? Research and paper simulation only.
- **[Pikalo](https://github.com/Vitaliy-Pikalo/pikalo.ai)** — shipping the AI tutor and growing past 1.3k waitlist signups.

---

### Featured work

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>📉 <a href="https://github.com/Vitaliy-Pikalo/adverse-selection-lab">Adverse Selection Lab</a></h4>
      Market-making research on Kalshi crypto binaries. WebSocket recorders for Kalshi order books and Coinbase spot, RSA-PSS signed read-only client, Parquet storage, 24/7 collector under systemd.
      <br /><br />
      <code>Python</code> <code>WebSockets</code> <code>Parquet</code> <code>pytest</code> <code>GitHub Actions</code>
    </td>
    <td width="50%" valign="top">
      <h4>🧪 <a href="https://github.com/Vitaliy-Pikalo/quant-research-pipeline">Quant Research Pipeline</a></h4>
      From-scratch pipeline for testing market-inefficiency hypotheses on free public data. Purged and combinatorial CV, deflated Sharpe, PBO, FDR control. Three hypotheses tested, all rejected, all written up.
      <br /><br />
      <code>Python</code> <code>HMM</code> <code>FRED</code> <code>SEC EDGAR</code> <code>49 tests</code>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4>♟️ <a href="https://github.com/Vitaliy-Pikalo/chess960-nn">Chess960-NN</a></h4>
      AlphaZero-style Chess960 engine. 10-block ResNet (6.7M parameters), MCTS with PUCT, trained by reinforcement-learning self-play to roughly 1600 Elo. <a href="https://chess960-nn.netlify.app">Play it in the browser.</a>
      <br /><br />
      <code>PyTorch</code> <code>MCTS</code> <code>RL self-play</code> <code>Hugging Face Spaces</code>
    </td>
    <td width="50%" valign="top">
      <h4>💸 <a href="https://github.com/Vitaliy-Pikalo/pikalo.ai">Pikalo</a></h4>
      Financial education for immigrants, international students, and first-time filers. "Ask Pikalo" answers from 1,491 IRS passages; every number is cited or computed by calculator tools over MCP, never by the model. Evals gate CI.
      <br /><br />
      <code>Next.js</code> <code>TypeScript</code> <code>Supabase</code> <code>AWS Bedrock</code> <code>CDK</code>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4>🎯 <a href="https://github.com/Vitaliy-Pikalo/kalshi-trading-bot">Kalshi Trading Bot</a></h4>
      Live-API paper-trading daemon. Log-normal volatility pricing, fractional Kelly sizing (k = 0.25), 270K+ market snapshots and 13K+ predictions logged, ECE calibration analysis. Finding: the apparent ROI was sampling variance.
      <br /><br />
      <code>Python</code> <code>SQLite</code> <code>Kelly sizing</code> <code>Calibration</code>
    </td>
    <td width="50%" valign="top">
      <h4>🛰️ <a href="https://github.com/Vitaliy-Pikalo/peaklo">Peaklo</a></h4>
      Answers "what should I apply to today?" Ingests internship postings straight from Greenhouse, Lever, and Ashby into one schema within minutes of going live. 267 tests, 91% coverage, <code>mypy --strict</code> clean.
      <br /><br />
      <code>FastAPI</code> <code>PostgreSQL</code> <code>SQLAlchemy</code> <code>Docker</code>
    </td>
  </tr>
</table>

### Open source and hackathons

- **[marimo #9943](https://github.com/marimo-team/marimo/pull/9943)** — merged fix so `mo.audio` accepts array-protocol objects such as `torch.Tensor` and JAX arrays; shipped in v0.23.12
- **[Levee](https://github.com/AHasenbein/Levee)** — 3rd place on the AWS track; I built the AWS integration ([levee.rentals](https://levee.rentals))

---

### Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=py,ts,java,go,pytorch,tensorflow,opencv,fastapi,nextjs,tailwind&perline=10" alt="Languages and frameworks" />
  <br />
  <img src="https://skillicons.dev/icons?i=postgres,supabase,sqlite,redis,docker,aws,githubactions,flutter,firebase,linux&perline=10" alt="Data and infrastructure" />
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:7aa2f7,55:1f3b73,100:0d1117&height=110&section=footer" alt="" width="100%" />
</p>
