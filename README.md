## Data Engineer · CDC, Streaming, Lakehouse

10 years in software, 8+ years in data engineering. I build and run data platforms from CDC and streaming to an Iceberg lakehouse and BI. When the root cause is in open source, I fix it upstream: 84 PRs to 48 repositories since 2018, 34 merged.

At scale: CDC for about 200 MySQL tables into Iceberg on a 3-minute commit cycle, millions of app events a day, 1,300+ Airflow DAGs, and a log system handling hundreds of millions of events a day.

[![Blog](https://img.shields.io/badge/-Blog-0A66C2?style=flat-square)](https://seunggabi.github.io/)
[![Portfolio](https://img.shields.io/badge/-Portfolio-2E7D32?style=flat-square)](https://seunggabi.github.io/portfolio/)
[![Resume](https://img.shields.io/badge/-Resume-555555?style=flat-square)](https://seunggabi.github.io/resume-en/)
[![Linkedin Badge](https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/seunggabi)](https://www.linkedin.com/in/seunggabi/)
<a href="mailto:seunggabi@gmail.com"><img src="https://img.shields.io/badge/-seunggabi@gmail.com-333333?style=flat-square&logo=Gmail&logoColor=white"/></a>

### Merged open source

- **Apache Superset**: `epoch_us` dataset time format ([#44500](https://github.com/apache/superset/pull/44500)), MCP API key scope limits ([#45272](https://github.com/apache/superset/pull/45272)), CI fixes ([#44513](https://github.com/apache/superset/pull/44513), [#46582](https://github.com/apache/superset/pull/46582))
- **Apache Spark**: `SparkSession.builder.config(Map)`, shipped in 3.4.0 ([#37478](https://github.com/apache/spark/pull/37478))
- **Apache Airflow**: `TableauOperator` template fields ([#29360](https://github.com/apache/airflow/pull/29360)) · Airflow Helm chart release name fix ([#589](https://github.com/airflow-helm/charts/pull/589))
- **PyAthena**: complex type parsing fix ([#763](https://github.com/pyathena-dev/PyAthena/pull/763))

### In review

- **Apache Flink**: let `flink run` fetch and cache the job JAR from `s3://`, `hdfs://` and other URIs, for [FLINK-6405](https://issues.apache.org/jira/browse/FLINK-6405), open since 2017 ([#30140](https://github.com/apache/flink/pull/30140), draft, in dev@ discussion)
- **Apache Airflow**: fix DAG runs stuck with `max_active_runs=1` ([#77603](https://github.com/apache/airflow/pull/77603), [#77604](https://github.com/apache/airflow/pull/77604)) · exclude DAGs by tag and by `-term` search in the DAG list ([#77622](https://github.com/apache/airflow/pull/77622))
- **Apache Iceberg**: Kafka Connect, case-insensitive `id-columns` lookup ([#19042](https://github.com/apache/iceberg/pull/19042))
- **Apache Superset**: keep viewers when saving a dashboard from edit mode ([#46239](https://github.com/apache/superset/pull/46239)) · SIP-230, download reason logging

### Writing

[seunggabi.github.io](https://seunggabi.github.io/): 100+ posts on CDC, Kafka Connect, Iceberg, Flink and Spark internals, system design, and notes from production. Recent:

- [Fetching the job JAR from S3 in `flink run` (FLINK-6405)](https://seunggabi.github.io/posts/flink-cli-remote-jar/)
- [Why `max_active_runs=1` DAGs stall in Airflow](https://seunggabi.github.io/posts/airflow-max-active-runs-deadlock/)
- [Excluding DAGs by tag and name in the Airflow DAG list](https://seunggabi.github.io/posts/airflow-dag-list-exclude/)

(Posts are in Korean, each with a short English summary.)

### Side projects

- [claude-dashboard](https://github.com/seunggabi/claude-dashboard): k9s-style TUI for Claude Code sessions (Go, Bubble Tea, tmux)
- [cron-manager](https://github.com/seunggabi/cron-manager): crontab GUI desktop app (Electron)
- [intellij-branch-tab-title](https://github.com/seunggabi/intellij-branch-tab-title): git branch + terminal status (⏳/✓) in IntelliJ window tabs · [Marketplace](https://plugins.jetbrains.com/plugin/35988-branch-tab-title)

[![Stars](https://img.shields.io/github/stars/seunggabi/intellij-branch-tab-title?style=social)](https://github.com/seunggabi/intellij-branch-tab-title/stargazers)

#### [ai-heatmap](https://github.com/seunggabi/ai-heatmap)
![ai-heatmap](https://seunggabi-ai-heatmap.vercel.app/api/heatmap?colorScheme=dark)
