# Hi, I’m **Ruthik Reddy** 👋

<p align="center">
  <!-- Hero animation: headshot + animated ring + subtle torch‑style flame -->
  <svg viewBox="0 0 900 320" width="900" height="320" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Ruthik hero animation">
    <defs>
      <clipPath id="circleMask"><circle cx="160" cy="160" r="86"/></clipPath>
      <linearGradient id="ring" x1="0" x2="1">
        <stop offset="0%" stop-color="#66d9ff"/>
        <stop offset="100%" stop-color="#a78bfa"/>
      </linearGradient>
      <radialGradient id="flameGrad" cx="50%" cy="30%" r="60%">
        <stop offset="0%" stop-color="#fff9c4"/>
        <stop offset="50%" stop-color="#ffb347"/>
        <stop offset="100%" stop-color="#ff512f"/>
      </radialGradient>
      <filter id="softGlow" x="-50%" y="-50%" width="200%" height="200%">
        <feGaussianBlur stdDeviation="3" result="b"/>
        <feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge>
      </filter>
    </defs>

    <!-- Left: headshot with animated ring -->
    <g transform="translate(0,0)">
      <circle cx="160" cy="160" r="96" fill="none" stroke="url(#ring)" stroke-width="3" opacity="0.6">
        <animateTransform attributeName="transform" type="rotate" from="0 160 160" to="360 160 160" dur="12s" repeatCount="indefinite"/>
      </circle>
      <image href="./assets/headshot.png" x="74" y="74" width="172" height="172" clip-path="url(#circleMask)"/>
      <!-- Tiny torch‑style flame accent -->
      <g transform="translate(245,120)" filter="url(#softGlow)">
        <path d="M0,-16 q-9,12 0,20 q9,-10 0,-20" fill="url(#flameGrad)">
          <animate attributeName="d" dur="1s" repeatCount="indefinite"
            values="M0,-16 q-9,12 0,20 q9,-10 0,-20; M0,-18 q-10,14 0,22 q10,-12 0,-22; M0,-16 q-9,12 0,20 q9,-10 0,-20"/>
        </path>
        <circle cx="0" cy="-6" r="4" fill="#ffd54f" opacity="0.7">
          <animate attributeName="r" values="4;5;4" dur="1s" repeatCount="indefinite"/>
        </circle>
      </g>
    </g>

    <!-- Right: auto‑cycling role captions (Lemni‑style smooth portfolio) -->
    <g transform="translate(320,70)">
      <text x="0" y="0" font-family="Segoe UI, Roboto, sans-serif" font-size="28" fill="#eaeaea">Data Analyst • BI • ML</text>
      <g font-family="Segoe UI, Roboto, sans-serif" font-size="18" fill="#cfcfcf">
        <text id="line1" x="0" y="40">SQL • Python • Power BI • Tableau</text>
        <text id="line2" x="0" y="70">Cloud pipelines: AWS • Snowflake • dbt • Airflow</text>
        <text id="line3" x="0" y="100">Healthcare & Financial Analytics • A/B Testing</text>
      </g>
      <!-- Fade carousel -->
      <g>
        <animate xlink:href="#line1" attributeName="opacity" values="1;0;0" dur="9s" repeatCount="indefinite"/>
        <animate xlink:href="#line2" attributeName="opacity" values="0;1;0" dur="9s" begin="3s" repeatCount="indefinite"/>
        <animate xlink:href="#line3" attributeName="opacity" values="0;0;1" dur="9s" begin="6s" repeatCount="indefinite"/>
      </g>
    </g>

    <!-- Bottom: smooth logo marquee (SVG motion) -->
    <g transform="translate(330,250)" opacity="0.9">
      <g id="marquee">
        <rect x="-20" y="-18" width="520" height="36" fill="#151515" rx="18"/>
        <g>
          <text x="10" y="7" fill="#9aa4b2" font-size="14" font-family="Segoe UI, Roboto, sans-serif">Tools:</text>
          <text x="70" y="7" fill="#e5e7eb" font-size="14" font-family="Segoe UI, Roboto, sans-serif">SQL • Python • Power BI • Tableau • Snowflake • Redshift • dbt • Airflow</text>
        </g>
      </g>
      <animateTransform xlink:href="#marquee" attributeName="transform" type="translate" from="0 0" to="-260 0" dur="12s" repeatCount="indefinite"/>
    </g>
  </svg>
</p>

<p align="center">
  <a href="https://github.com/ruthikreddych?tab=followers"><img src="https://img.shields.io/github/followers/ruthikreddych?style=for-the-badge" alt="Followers"></a>
  <img src="https://komarev.com/ghpvc/?username=ruthikreddych&style=for-the-badge" alt="Profile Views"/>
  <img src="https://img.shields.io/badge/Focus-Data%20Analytics%20%7C%20BI%20%7C%20ML-6e56cf?style=for-the-badge"/>
</p>

---

## 🧭 About Me
Data Analyst with ~5 years experience turning complex datasets into clear business impact across **financial services** and **healthcare**. I build **Power BI/Tableau** dashboards, automate **ETL** with **dbt/Airflow**, and ship reliable analytics on **AWS/Snowflake/Redshift**.

- 📍 Chicago, IL · ✉️ **chruthik84@gmail.com** · 🔗 [LinkedIn](https://www.linkedin.com/in/ruthikreddy-cheruku/) · 🌐 [Portfolio](https://ruthikreddych.github.io/Ruthik-protfolio/)

---

## 🛠️ Tech Stack
**Languages:** Python, SQL, R  
**BI & Viz:** Power BI, Tableau, Plotly, matplotlib, seaborn  
**Data:** Snowflake, Redshift, BigQuery, Postgres, MySQL, SQL Server  
**Pipelines:** dbt, Airflow, Talend, Fivetran, Hightouch  
**Cloud:** AWS (S3, Athena), Azure  
**Analytics:** A/B testing, regression, forecasting, clustering, classification  

---

## 🔥 Impact Highlights (auto‑cycling ticker)
<p>
  <svg viewBox="0 0 900 60" width="900" height="60" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Impact ticker">
    <defs><linearGradient id="grad" x1="0" x2="1"><stop offset="0%" stop-color="#22d3ee"/><stop offset="100%" stop-color="#a78bfa"/></linearGradient></defs>
    <rect x="0" y="10" width="900" height="40" rx="20" fill="#0f172a"/>
    <g font-family="Segoe UI, Roboto, sans-serif" font-size="16" fill="#e5e7eb">
      <text id="t1" x="30" y="36">✅ 12+ Power BI dashboards boosted client satisfaction by 18%</text>
      <text id="t2" x="30" y="36" opacity="0">✅ SQL+Python on 15M+ txns/mo cut churn by 6.2%</text>
      <text id="t3" x="30" y="36" opacity="0">✅ dbt/Airflow ETL → 2 TB/week with higher reporting accuracy</text>
      <text id="t4" x="30" y="36" opacity="0">✅ Data quality checks reduced erroneous trade entries by 91%</text>
    </g>
    <g>
      <animate xlink:href="#t1" attributeName="opacity" values="1;0;0;0" dur="12s" repeatCount="indefinite"/>
      <animate xlink:href="#t2" attributeName="opacity" values="0;1;0;0" dur="12s" begin="3s" repeatCount="indefinite"/>
      <animate xlink:href="#t3" attributeName="opacity" values="0;0;1;0" dur="12s" begin="6s" repeatCount="indefinite"/>
      <animate xlink:href="#t4" attributeName="opacity" values="0;0;0;1" dur="12s" begin="9s" repeatCount="indefinite"/>
    </g>
    <rect x="10" y="12" width="4" height="36" rx="2" fill="url(#grad)"/>
  </svg>
</p>

---

## 📊 Featured Projects
<table>
<tr>
<td>
<b>Financial Advisory KPIs (Power BI)</b><br/>
Interactive dashboards for portfolio underperformance and churn signals.
</td>
<td>
<b>Healthcare Claims Insights</b><br/>
Streamlit + SQL + predictive readmission modelling (82% accuracy).
</td>
</tr>
<tr>
<td>
<b>ETL on Snowflake</b><br/>
dbt + Airflow pipelines processing 2 TB/week, with automated DQ checks.
</td>
<td>
<b>Pneumonia Detection (VGG16/19)</b><br/>
94% accuracy on pediatric X‑rays; robust preprocessing and regularization.
</td>
</tr>
</table>

---

## 🔄 Torch‑Bearer Runner (signature animation)
<p align="center">
  <img src="./assets/torch-bearer.svg" width="720" alt="Torch bearer animation" />
</p>

---

## 📈 GitHub Analytics
<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=ruthikreddych&show_icons=true&hide_title=true" alt="Stats"/>
  <img height="165" src="https://github-readme-streak-stats.herokuapp.com?user=ruthikreddych" alt="Streak"/>
</p>

---

## 🤝 Contact
- ✉️ **chruthik84@gmail.com**  
- 🔗 [LinkedIn](https://www.linkedin.com/in/ruthikreddy-cheruku/)  
- 🌐 [Portfolio](https://ruthikreddych.github.io/Ruthik-protfolio/)

---

### How to use
- Create a repository named exactly `ruthikreddych` and place this README at the root.
- Keep the assets in an `assets/` folder as provided.
