<div align="center">

<img src="assets/terminal-banner.svg" alt="terminal banner" width="100%"/>

<br/>

<img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=600&size=22&duration=2800&pause=900&color=3FCF8E&center=true&vCenter=true&multiline=true&repeat=true&width=820&lines=staff+data+%2B+ml+platform+engineer;lakehouse+%7C+streaming+%7C+mlops+%7C+feature+stores;inference+%7C+RAG+%7C+AI+platform+at+scale" alt="typing intro"/>

<br/>

[![profile views](https://komarev.com/ghpvc/?username=hrishisarma&label=profile+views&color=0d1117&style=for-the-badge)](https://github.com/hrishisarma)
[![hireable](https://img.shields.io/badge/hireable-yes-3FCF8E?style=for-the-badge&logo=github&logoColor=0d1117)](https://github.com/hrishisarma)
[![company](https://img.shields.io/badge/GOAT_Group-staff_engineer-1f6feb?style=for-the-badge)](https://github.com/goatapp)
[![resume site](https://img.shields.io/badge/résumé-hrishisarma.github.io-0d1117?style=for-the-badge&logo=googlechrome&logoColor=3FCF8E)](https://hrishisarma.github.io)

</div>

---

### ```zsh``` session — `ssh github.com`

```bash
hrishisarma@github ~ % whoami
Hrishikesh Sarma — Staff Data Platform / Software Engineer
Round Rock, TX · Remote-friendly

hrishisarma@github ~ % cat about.txt
Staff engineer for lakehouse, streaming, and ML platform at marketplace scale.
Data planes (Iceberg, Kafka, Flink, Airflow) plus MLOps, feature stores, online inference,
and RAG-style retrieval for discovery, ranking, and internal AI tooling.

hrishisarma@github ~ % ./skills --list
```

<div align="center">

[![stack](https://skillicons.dev/icons?i=python,pytorch,tensorflow,java,go,aws,kafka,spark,airflow,docker,kubernetes,fastapi,postgres,redis&perline=14&theme=dark)](https://skillicons.dev)

</div>

```bash
hrishisarma@github ~ % cat ~/skills.txt
```

| area | stack |
| :--- | :--- |
| **Data platform** | Iceberg, Spark, Flink, Kafka, Airflow, Databricks, Delta Lake, Pinot |
| **Streaming** | Kafka Streams, Spark Streaming, Materialize |
| **Lakehouse / SQL** | S3, Snowflake, Redshift, Postgres, Parquet, Advanced SQL, Data Modeling |
| **Backends** | FastAPI, REST, Elasticsearch |
| **Cloud** | AWS, Kubernetes, Docker |
| **ML / AI / RAG** | Feature stores, online inference, PyTorch, embeddings, vector search, RAG, MLOps |
| **Languages** | Python, SQL, Java, Go, Shell |

```bash
hrishisarma@github ~ % man experience
```

<table>
<tr>
<td width="50%" valign="top">

**GOAT Group** · Staff Software Engineer  
`Feb 2023 → Present` · Remote

```diff
+ S3 / Iceberg lakehouse — ~30% warehouse cost ↓, p95 &lt; 10s dashboards
+ 15+ ingestion connectors, ~2 TB/mo, contracts + replay
+ Kafka + Flink — 10K+ events/min, p99 &lt; 2s real-time KPIs
+ Airflow tier-1 — 99.9%+ through BFCM, snapshot recovery
+ Quality + observability — incident detect &lt; 30 min
+ MLOps + feature store — offline/online features, drift + freshness gates
+ Inference paths for ranking/personalization — no stale features in prod
```

</td>
<td width="50%" valign="top">

**Expedia Group** · Senior Software Engineer  
`Jan 2020 → Feb 2023` · Austin

```diff
+ Data / ML discovery platform — 40% faster asset discovery
+ Kafka Streams — sub-15-min freshness (hours → minutes)
+ Metadata, lineage, search — foundation for ML + RAG-style discovery
```

**Comcast** · Software Engineer  
`Earlier roles` · Distributed systems foundation

</td>
</tr>
</table>

```bash
hrishisarma@github ~ % npm run highlights
```

| metric | what shipped |
| :--- | :--- |
| `lakehouse` | Spark → Iceberg, Snowflake marts, compaction + time travel |
| `streaming` | Event-time windows, checkpoints, ops dashboards live during peak |
| `platform` | Shared ingestion standards · 4 partner teams · 20+ stakeholders |
| `mlops` | Training pipelines, model registry patterns, deploy gates on drift |
| `feature_store` | Product / seller / buyer signals — offline training, online serving |
| `inference` | Low-latency serving APIs · feature freshness SLAs · FastAPI surfaces |
| `ai_rag` | Vector retrieval + catalog/lineage — search &amp; grounding for ML/LLM tools |

```bash
hrishisarma@github ~ % cat architecture/ml-platform.mmd
```

```mermaid
flowchart LR
  subgraph ingest["Data plane"]
    K[Kafka / Flink]
    I[Iceberg lakehouse]
  end
  subgraph ml["ML platform"]
    F[Feature store\noffline + online]
    T[Training / batch features]
    M[Model inference]
  end
  subgraph ai["AI / RAG"]
    V[Embeddings / vector index]
    R[RAG retrieval]
    A[Apps · Slack · APIs]
  end
  K --> I --> F
  F --> T --> M
  I --> V --> R --> A
  M --> A
```

```bash
hrishisarma@github ~ % git log --oneline --stat
```

<div align="center">

<img height="165em" src="https://github-readme-stats.vercel.app/api?username=hrishisarma&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d111700&title_color=3FCF8E&icon_color=79c0ff&text_color=c9d1d9&custom_title=git+stats" alt="github stats"/>
<img height="165em" src="https://github-readme-streak-stats.herokuapp.com/?user=hrishisarma&theme=tokyonight&hide_border=true&background=0d111700&ring=3FCF8E&fire=3FCF8E&currStreakLabel=3FCF8E&sideLabels=3FCF8E&dates=8b949e" alt="streak"/>

<br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=hrishisarma&bg_color=0d1117&color=3FCF8E&line=1f6feb&point=3FCF8E&area=true&hide_border=true&custom_title=contribution+heatmap" alt="activity graph" width="100%"/>

</div>

```bash
hrishisarma@github ~ % ls ~/projects
```

<!--START_SECTION:repos-->
_Public repos will show here once you pin or push more work — try `gh repo list` locally._
<!--END_SECTION:repos-->

```bash
hrishisarma@github ~ % open https://hrishisarma.github.io    # terminal résumé (Resume-dp.pdf)

hrishisarma@github ~ % ./connect.sh
```

<div align="center">

[![email](https://img.shields.io/badge/email-dugisharma007@gmail.com-0d1117?style=for-the-badge&logo=gmail&logoColor=ea4335)](mailto:dugisharma007@gmail.com)
[![linkedin](https://img.shields.io/badge/linkedin-/in/hrishisarma-0d1117?style=for-the-badge&logo=linkedin&logoColor=0A66C2)](https://linkedin.com/in/hrishisarma)
[![goat](https://img.shields.io/badge/day_job-@goatapp-0d1117?style=for-the-badge&logo=github&logoColor=white)](https://github.com/goatapp)

</div>

```bash
hrishisarma@github ~ % fortune
> "Backfills are just time travel with better audit trails."
hrishisarma@github ~ % █
```

<!-- snake eats contributions -->
![Snake animation](https://github.com/hrishisarma/hrishisarma/blob/output/github-contribution-grid-snake.svg)