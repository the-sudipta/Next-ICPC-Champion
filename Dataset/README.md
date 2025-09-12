<h1 align="center">🏆 ICPC World Finals Ranking (1999–2024) Dataset</h1>

<p align="center">
  <a href="https://www.kaggle.com/datasets/justinianus/icpc-world-finals-ranking-since-1999">
    <img alt="Kaggle Dataset" src="https://img.shields.io/badge/Source-Kaggle-2E6DF6?logo=kaggle&logoColor=white">
  </a>
  <img alt="Years" src="https://img.shields.io/badge/Years-1999%E2%86%922024-10B981">
  <img alt="Scope" src="https://img.shields.io/badge/Scope-World%20Finals-8B5CF6">
  <img alt="Status" src="https://img.shields.io/badge/Mirror-Read--Only-6366F1">
  <a href="#license-terms">
    <img alt="License" src="https://img.shields.io/badge/License-see%20Kaggle%20page-0EA5E9">
  </a>
</p>

<!-- Decorative gradient divider (inline SVG works on GitHub) -->
<p align="center">
  <svg width="100%" height="6" viewBox="0 0 100 6" preserveAspectRatio="none">
    <defs>
      <linearGradient id="g1" x1="0" x2="1" y1="0" y2="0">
        <stop offset="0%" stop-color="#FB923C"/>
        <stop offset="50%" stop-color="#38BDF8"/>
        <stop offset="100%" stop-color="#A78BFA"/>
      </linearGradient>
    </defs>
    <rect x="0" y="0" width="100" height="6" fill="url(#g1)"/>
  </svg>
</p>

<blockquote>
  Mirror of a public Kaggle dataset for research/analysis within this repository. <br>
  <b>Source:</b> <a href="https://www.kaggle.com/datasets/justinianus/icpc-world-finals-ranking-since-1999">https://www.kaggle.com/datasets/justinianus/icpc-world-finals-ranking-since-1999</a>
</blockquote>

<hr>

<h2 id="dataset-summary">📌 Dataset Summary</h2>

<p>
  The dataset aggregates <b>ICPC World Finals</b> team results from <b>1999 → 2024</b>. It includes <b>≈21 attributes</b> (e.g., team, rank, university, region/country, problems solved, prize).<br>
  Common use-cases: trend/statistical analysis, competition analytics, and ML modeling on competitive-programming performance.
</p>

<blockquote>
  ICPC is a global programming contest organized by the <b>Association for Computing Machinery (ACM)</b>, with teams advancing via regional/online contests to the World Finals.
</blockquote>

<h3>Quick Facts</h3>
<table>
  <tr>
    <td>🗓️ <b>Years</b></td>
    <td>1999–2024</td>
  </tr>
  <tr>
    <td>🧾 <b>Records</b></td>
    <td>Per-team World Finals placements (year by year)</td>
  </tr>
  <tr>
    <td>🧩 <b>Example fields</b></td>
    <td><code>Year</code>, <code>Team</code>, <code>Rank</code>, <code>University</code>, <code>Region</code>, <code>Country</code>, <code>ProblemsSolved</code>, <code>Prize</code>, …</td>
  </tr>
  <tr>
    <td>📜 <b>Canonical schema</b></td>
    <td>See the Kaggle page (authoritative &amp; most up-to-date)</td>
  </tr>
</table>

<hr>

<h2>🔗 Table of Contents</h2>

<ul>
  <li><a href="#files">📂 Files in This Folder</a></li>
  <li><a href="#columns">🧾 Columns (high-level)</a></li>
  <li><a href="#download">⬇️ Reproducible Download (Kaggle CLI)</a></li>
  <li><a href="#quick-start">🔎 Quick Start (Python)</a></li>
  <li><a href="#citation">📑 Citation</a></li>
  <li><a href="#acknowledgements">🙏 Acknowledgements</a></li>
  <li><a href="#license-terms">🛡️ License &amp; Terms</a></li>
</ul>

<hr>

<h2 id="files">📂 Files in This Folder</h2>

<p>You may find one or more of the following (depending on what you downloaded from Kaggle):</p>

<pre><code>Dataset/
├─ icpc-full.csv                # all years combined
├─ years/
│  ├─ icpc-2022.csv
│  ├─ icpc-2023.csv
│  └─ icpc-2024.csv
└─ README.md                    # this file
</code></pre>

<p><b>Tip:</b> If any CSV is large (&gt;50 MB), consider using <kbd>Git LFS</kbd>.</p>

<hr>

<h2 id="columns">🧾 Columns (high-level)</h2>

<p>The full schema is on Kaggle. Common fields include (names may vary slightly):</p>
<ul>
  <li><code>Year</code>, <code>Team</code>, <code>Rank</code>, <code>University</code>, <code>Region</code>, <code>Country</code>, <code>ProblemsSolved</code>, <code>Prize</code>, …</li>
</ul>
<p>For the exact, up-to-date column list and definitions, see the Kaggle page.</p>

<hr>

<h2 id="download">⬇️ Reproducible Download (Kaggle CLI)</h2>

<details>
  <summary><b>Show commands</b></summary>
  <p><b>Install/authorize:</b> <a href="https://github.com/Kaggle/kaggle-api">https://github.com/Kaggle/kaggle-api</a></p>
  <pre><code class="language-bash">kaggle datasets download -d justinianus/icpc-world-finals-ranking-since-1999 -p ./Dataset --unzip</code></pre>
</details>

<hr>

<h2 id="quick-start">🔎 Quick Start (Python)</h2>

<pre><code class="language-python">import pandas as pd

df = pd.read_csv("Dataset/icpc-full.csv")  # or a file under Dataset/years/
print(df.head())
print(df['Year'].min(), df['Year'].max())</code></pre>

<hr>

<h2 id="citation">📑 Citation</h2>

<p>If your work cites datasets, you can reference it like this (adapt to your style):</p>

<pre><code>Justinianus. "ICPC World Finals Ranking since 1999." Kaggle, 2024.
URL: https://www.kaggle.com/datasets/justinianus/icpc-world-finals-ranking-since-1999
</code></pre>

<hr>

<h2 id="acknowledgements">🙏 Acknowledgements</h2>

<p>This project gratefully acknowledges the contributions of:</p>
<ul>
  <li><b>International Collegiate Programming Contest (ICPC) community</b> and the <b>Association for Computing Machinery (ACM)</b> for organizing and preserving the contest ecosystem and historical records.</li>
  <li><b>Kaggle</b> and the dataset author <b>Justinianus</b> for curating and sharing the dataset <i>“ICPC World Finals Ranking since 1999” (2024)</i> —
    <a href="https://www.kaggle.com/datasets/justinianus/icpc-world-finals-ranking-since-1999">dataset link</a>.
  </li>
</ul>

<blockquote>
  Any analyses, interpretations, or errors are solely those of the authors. <br>
  Use of the ICPC name, ACM materials, or the Kaggle dataset does <b>not</b> imply endorsement.
</blockquote>

<hr>

<h2 id="license-terms">🛡️ License &amp; Terms</h2>

<p><b>Always check the license on the Kaggle page before redistribution or commercial use.</b><br>
By using this copy, you agree to the <b>original Kaggle terms/license</b> and relevant <b>ICPC/ACM data usage policies</b>.</p>

<p align="center">
  <img alt="License notice" src="https://img.shields.io/badge/Usage-Respect%20Original%20License-EAB308">
</p>

<hr>

<p align="center">
  <sub>Like this README? ⭐ Star the repo and share with your team.</sub>
</p>
