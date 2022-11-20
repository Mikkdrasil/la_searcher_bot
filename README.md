# LizaAlert "Searcher Bot"

## What is LA Searcher Bot
[LizaAlert](https://lizaalert.org/) (aka LA) – is a non-profit volunteer 
Search & Resque Organization, which helps to find and 
resque lost people across Russian Federation.

This repo covers [LA Searcher Bot](https://t.me/LizaAlert_Searcher_Bot) – 
non-official LA bot, however it is developed from the scratch 
& maintained by [one of LA Searchers](https://t.me/MikeMikeT).

There is the enthusiasts [Community](https://t.me/+56GrL4LQ-og2NGEy) 
for discussion of ideas and issues in the Bot.

Core audience of the Bot – are LA Searches, that participate in
numerous "field" searches in urban / rural / natural environments.

Bot was created in mid 2021.
As per November 2022 bot has +4000 active users, DAU +2500 users,
daily messages +20000. Annual Growth Rate is 3X.

Bot is built as a parser of phpbb [LA Forum](https://lizaalert.org/forum/), 
which wraps phpbb-styled information into customized 
notification for every user.

## Technological stack

* UI: Telegram (API)
* Language: Python 3.7 
* Git: GitHub
* CI/CD: GitHub Actions
* Infra: Google Cloud Platform
* Executors: Google Cloud Functions
* Message Broker: Google Pub/Sub
* Storage: Google Cloud SQL (Postgres), Cloud Storage, BigQuery
* Monitoring: Google Cloud Logging, Looker Studio

## Repository 

This repository covers only python scripts, which are sent to Google 
Cloud Functions and GitHub Actions Workflow files.

## Contribution

See a dedicated LA Searcher Bot 
[contribution page](https://github.com/Mikkdrasil/la_bot_monorep/blob/main/docs/contribution.md).

TL;DR: 
* contributions to the current python-based repo are welcome via pull requests
* contribution to CI/CD, PSQL, GCP or
* improvement ideas – let's discuss in [community chat](https://t.me/+56GrL4LQ-og2NGEy).




