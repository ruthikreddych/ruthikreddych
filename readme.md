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
Data Analyst with ~5 years experience turning complex datasets into clear business impact across **financial services** and **healthcare**. I build **Power BI/Tableau** dashboards, automate **ETL** with **dbt/Airflow**, and ship reliable analytics on **AWS/Snowflake/Redshift**. I love clean visuals and smooth UX—so this README moves like a portfolio.

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

### Files to add to your repo
1) `assets/headshot.png` — upload your photo (this README references it).  
2) `assets/torch-bearer.svg` — paste the SVG below.

```svg
<!-- assets/torch-bearer.svg (unchanged core, sized for this profile) -->
<svg viewBox="0 0 1200 260" width="1200" height="260" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Torch bearer animation">
  <defs>
    <linearGradient id="trackGrad" x1="0" x2="1">
      <stop offset="0%" stop-color="#111"/>
      <stop offset="100%" stop-color="#333"/>
    </linearGradient>
    <radialGradient id="flame" cx="50%" cy="30%" r="60%">
      <stop offset="0%" stop-color="#fff8d6"/>
      <stop offset="50%" stop-color="#ffb347"/>
      <stop offset="100%" stop-color="#ff512f"/>
    </radialGradient>
    <filter id="glow" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="4" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <path id="path" d="M 20 200 C 200 180, 400 220, 600 200 S 1000 180, 1180 200" fill="none" />
  </defs>
  <rect x="0" y="190" width="1200" height="35" fill="url(#trackGrad)" rx="18"/>
  <g opacity="0.25">
    <circle cx="100" cy="207" r="2" fill="#fff"/>
    <circle cx="300" cy="207" r="2" fill="#fff"/>
    <circle cx="500" cy="207" r="2" fill="#fff"/>
    <circle cx="700" cy="207" r="2" fill="#fff"/>
    <circle cx="900" cy="207" r="2" fill="#fff"/>
    <circle cx="1100" cy="207" r="2" fill="#fff"/>
  </g>
  <g>
    <g id="runner">
      <ellipse cx="0" cy="18" rx="26" ry="6" fill="#000" opacity="0.25"/>
      <circle cx="0" cy="-40" r="12" fill="#2a2a2a"/>
      <rect x="-8" y="-40" width="16" height="35" rx="6" fill="#3a3a3a"/>
      <g>
        <rect x="-10" y="-8" width="6" height="26" rx="3" fill="#4a4a4a">
          <animate attributeName="y" values="-8;-4;-8" dur="0.6s" repeatCount="indefinite"/>
        </rect>
        <rect x="4" y="-8" width="6" height="26" rx="3" fill="#4a4a4a">
          <animate attributeName="y" values="-4;-8;-4" dur="0.6s" repeatCount="indefinite"/>
        </rect>
      </g>
      <rect x="8" y="-60" width="4" height="30" fill="#8B5A2B"/>
      <ellipse cx="10" cy="-62" rx="9" ry="6" fill="#B8860B"/>
      <g filter="url(#glow)">
        <path d="M10,-76 q-8,10 0,18 q8,-8 0,-18" fill="url(#flame)">
          <animate attributeName="d" dur="0.7s" repeatCount="indefinite"
                   values="M10,-76 q-8,10 0,18 q8,-8 0,-18; M10,-78 q-9,12 0,20 q9,-10 0,-20; M10,-76 q-8,10 0,18 q8,-8 0,-18"/>
        </path>
        <circle cx="10" cy="-66" r="6" fill="#ffcf33" opacity="0.6">
          <animate attributeName="r" values="6;7;6" dur="0.7s" repeatCount="indefinite"/>
        </circle>
      </g>
    </g>
    <animateMotion xlink:href="#runner" dur="7s" repeatCount="indefinite" rotate="auto">
      <mpath xlink:href="#path"/>
    </animateMotion>
  </g>
  <text x="50%" y="40" text-anchor="middle" font-family="Segoe UI, Roboto, sans-serif" font-size="24" fill="#eaeaea">Passing the Flame: Craft • Curiosity • Consistency</text>
</svg>
```

> **Notes**
> - Upload your headshot to `assets/headshot.png` (PNG, ~400px).  
> - GitHub READMEs don’t allow JS; all motion here is pure **SVG/SMIL**, which GitHub renders reliably.

