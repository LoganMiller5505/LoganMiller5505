```
   _       U  ___ u   ____      _      _   _          __  __              _       _     U _____ u   ____     
  |"|       \/"_ \/U /"___|uU  /"\  u | \ |"|       U|' \/ '|u   ___     |"|     |"|    \| ___"|/U |  _"\ u  
U | | u     | | | |\| |  _ / \/ _ \/ <|  \| |>      \| |\/| |/  |_"_|  U | | u U | | u   |  _|"   \| |_) |/  
 \| |/__.-,_| |_| | | |_| |  / ___ \ U| |\  |u       | |  | |    | |    \| |/__ \| |/__  | |___    |  _ <    
  |_____|\_)-\___/   \____| /_/   \_\ |_| \_|        |_|  |_|  U/| |\u   |_____| |_____| |_____|   |_| \_\   
  //  \\      \\     _)(|_   \\    >> ||   \\,-.    <<,-,,-..-,_|___|_,-.//  \\  //  \\  <<   >>   //   \\_  
 (_")("_)    (__)   (__)__) (__)  (__)(_")  (_/      (./  \.)\_)-' '-(_/(_")("_)(_")("_)(__) (__) (__)  (__) 

 ```

[![Website](https://img.shields.io/badge/lmiller.io-000?style=flat-square&logo=firefox-browser&logoColor=white)](https://lmiller.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/loganmiller5505)
[![Email](https://img.shields.io/badge/logan%40lmiller.io-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:logan@lmiller.io)

## About Me

<!--
TODO (Logan): 1-2 sentences in your own voice.
The old README's "Junior at Auburn / originally from Cincinnati" line was the most
human part of the page - this is where that goes. What you're into, what you like
building, what you're looking for. Everything below is assembled fact; this bit isn't.
Delete this comment when you've written it.
-->

- 🦅 Senior at **Auburn University** — B.S. Computer Science, Artificial Intelligence Engineering concentration, Honors Business minor (May 2027)
- 📈 3.82 GPA · Honors College Member · Auburn Engineering Honors Circle (2025)
- 🏙️ Loveland, OH
- 📧 Reach me at [logan@lmiller.io](mailto:logan@lmiller.io)

## Experience

**Data Engineer Intern** — Medpace · *May 2026 – August 2026*

One of four engineers building a company-wide source of truth that consolidates all
active clinical trial data into Snowflake. Drove requirements-gathering with product and
business stakeholders, built the dbt models implementing most of those requirements, and
developed a Prefect orchestration pipeline (Python, Snowpark) that keeps the unified
source current on a CRON schedule driven by a custom configuration table.

**ALEC Team Student Verifier** — Auburn University RFID Lab · *April 2025 – Present*

Review and verify 4,000+ supplier RFID tagging procedures for standards compliance on
confidential client engagements, auditing peer validations to maintain data accuracy.

## Featured Projects

### 🪐 ExoQuery — NASA Exoplanet Data Agent
[Live app](https://exoquery.streamlit.app) · [Repo](https://github.com/LoganMiller5505/exoplanet-agent)

An LLM agent (Groq) with four purpose-built tools that answers natural-language questions
over NASA Exoplanet Archive data — the model never writes raw SQL. Backed by a Neon
Postgres warehouse populated by a GitHub Actions-scheduled daily ingestion pipeline that
pulls 11 NASA tables and builds planet, system, and habitable-zone views. Deployed
publicly on Streamlit.

`Python` `Groq` `PostgreSQL` `GitHub Actions` `Streamlit`

### 🖥️ Self-Hosted Media & Game Server Platform
[Live status page](https://status.lmiller.io)

Design, deploy, and operate a self-hosted platform on a single Debian box with
ZFS-mirrored storage — 15+ containerized services behind a Caddy reverse proxy, serving
up to a dozen concurrent users. Jellyfin with GPU transcoding, a VPN-isolated download
stack, AdGuard Home for network-wide filtering, and Pterodactyl for game servers.

Security and reliability are the interesting part: UFW default-deny with nothing but
80/443 and game ports on the public internet, all admin access gated behind Tailscale,
restic offsite backups, sanoid ZFS snapshotting, and a disaster-recovery procedure
that's been validated for real by three power outages. I keep 9 written technical guides
covering the install, hardening, and recovery procedures.

`Debian` `Docker` `ZFS` `Caddy` `Tailscale` `UFW` `systemd` `restic`

### 🎵 Spotify Genre Classification
[Repo](https://github.com/LoganMiller5505/DataSciProject)

Built a Random Forest classifier predicting genre from Spotify audio features across
113K+ tracks. Training on all 114 raw genre labels overfit badly — 81.7% train vs. 25.4%
test accuracy. Consolidating the labels into five broader supergenre categories and
retraining lifted test accuracy to **59.5%**.

`Python` `scikit-learn` `Pandas` `Matplotlib`

### 🏈 NFL Fantasy Football Predictions Model
[Repo](https://github.com/LoganMiller5505/nfl-data)

Built and trained a solo model to predict NFL players' weekly fantasy point totals,
achieving a Mean Absolute Error of ~7 points.

`Python` `TensorFlow` `Pandas`

## Skills

| | |
|---|---|
| **Programming** | Python · SQL · Java · JavaScript · C · HTML/CSS |
| **Data Engineering** | Snowflake · dbt · Prefect · Snowpark · PostgreSQL · Azure · Pandas · NumPy |
| **Data Science / ML** | TensorFlow · Keras · scikit-learn · Matplotlib · Seaborn |
| **AI Tooling** | Agentic workflows · LLM agents & harnesses |
| **Infrastructure** | Docker · Linux · Git · GitHub Actions · Caddy · Tailscale · ZFS · systemd · Jupyter |
